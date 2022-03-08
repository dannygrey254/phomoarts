import url("https://fonts.googleapis.com/css?family=Source+Sans+Pro:300,900");
@import url("fontawesome-all.min.css");

/*
	Big Picture by HTML5 UP
	html5up.net | @ajlkn
	Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)
*/

html, body, div, span, applet, object,
iframe, h1, h2, h3, h4, h5, h6, p, blockquote,
pre, a, abbr, acronym, address, big, cite,
code, del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var, b,
u, i, center, dl, dt, dd, ol, ul, li, fieldset,
form, label, legend, table, caption, tbody,
tfoot, thead, tr, th, td, article, aside,
canvas, details, embed, figure, figcaption,
footer, header, hgroup, menu, nav, output, ruby,
section, summary, time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;}

article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
	display: block;}

body {
	line-height: 1;
}

ol, ul {
	list-style: none;
}

blockquote, q {
	quotes: none;
}

	blockquote:before, blockquote:after, q:before, q:after {
		content: '';
		content: none;
	}

table {
	border-collapse: collapse;
	border-spacing: 0;
}

body {
	-webkit-text-size-adjust: none;
}

mark {
	background-color: transparent;
	color: inherit;
}

input::-moz-focus-inner {
	border: 0;
	padding: 0;
}

input, select, textarea {
	-moz-appearance: none;
	-webkit-appearance: none;
	-ms-appearance: none;
	appearance: none;
}

/* Basic */

	@-ms-viewport {
		width: device-width;
	}

	html {
		height: 100%;
	}

	html {
		box-sizing: border-box;
	}

	*, *:before, *:after {
		box-sizing: inherit;
	}

	body {
		background: #ffffff;
		height: 100%;
		min-width: 320px;
	}

		body.is-preload *, body.is-preload *:before, body.is-preload *:after {
			-moz-animation: none !important;
			-webkit-animation: none !important;
			-ms-animation: none !important;
			animation: none !important;
			-moz-transition: none !important;
			-webkit-transition: none !important;
			-ms-transition: none !important;
			transition: none !important;
		}

/* Spinner */

	@-moz-keyframes spinner-rotate {
		0% {
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
		}

		100% {
			-moz-transform: scale(1) rotate(360deg);
			-webkit-transform: scale(1) rotate(360deg);
			-ms-transform: scale(1) rotate(360deg);
			transform: scale(1) rotate(360deg);
		}
	}

	@-webkit-keyframes spinner-rotate {
		0% {
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
		}

		100% {
			-moz-transform: scale(1) rotate(360deg);
			-webkit-transform: scale(1) rotate(360deg);
			-ms-transform: scale(1) rotate(360deg);
			transform: scale(1) rotate(360deg);
		}
	}

	@-ms-keyframes spinner-rotate {
		0% {
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
		}

		100% {
			-moz-transform: scale(1) rotate(360deg);
			-webkit-transform: scale(1) rotate(360deg);
			-ms-transform: scale(1) rotate(360deg);
			transform: scale(1) rotate(360deg);
		}
	}

	@keyframes spinner-rotate {
		0% {
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
		}

		100% {
			-moz-transform: scale(1) rotate(360deg);
			-webkit-transform: scale(1) rotate(360deg);
			-ms-transform: scale(1) rotate(360deg);
			transform: scale(1) rotate(360deg);
		}
	}

/* Loader */

	@-moz-keyframes spinner-show {
		0% {
			opacity: 0;
		}

		100% {
			opacity: 1;
		}
	}

	@-webkit-keyframes spinner-show {
		0% {
			opacity: 0;
		}

		100% {
			opacity: 1;
		}
	}

	@-ms-keyframes spinner-show {
		0% {
			opacity: 0;
		}

		100% {
			opacity: 1;
		}
	}

	@keyframes spinner-show {
		0% {
			opacity: 0;
		}

		100% {
			opacity: 1;
		}
	}

	@-moz-keyframes spinner-hide {
		0% {
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
			color: #e5e6e7;
			z-index: 100001;
		}

		99% {
			-moz-transform: scale(0.5) rotate(360deg);
			-webkit-transform: scale(0.5) rotate(360deg);
			-ms-transform: scale(0.5) rotate(360deg);
			transform: scale(0.5) rotate(360deg);
			color: #e5e6e7;
			z-index: 100001;
		}

		100% {
			-moz-transform: scale(0.5) rotate(360deg);
			-webkit-transform: scale(0.5) rotate(360deg);
			-ms-transform: scale(0.5) rotate(360deg);
			transform: scale(0.5) rotate(360deg);
			color: #e5e6e7;
			z-index: -1;
		}
	}

	@-webkit-keyframes spinner-hide {
		0% {
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
			color: #e5e6e7;
			z-index: 100001;
		}

		99% {
			-moz-transform: scale(0.5) rotate(360deg);
			-webkit-transform: scale(0.5) rotate(360deg);
			-ms-transform: scale(0.5) rotate(360deg);
			transform: scale(0.5) rotate(360deg);
			color: #e5e6e7;
			z-index: 100001;
		}

		100% {
			-moz-transform: scale(0.5) rotate(360deg);
			-webkit-transform: scale(0.5) rotate(360deg);
			-ms-transform: scale(0.5) rotate(360deg);
			transform: scale(0.5) rotate(360deg);
			color: #e5e6e7;
			z-index: -1;
		}
	}

	@-ms-keyframes spinner-hide {
		0% {
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
			color: #e5e6e7;
			z-index: 100001;
		}

		99% {
			-moz-transform: scale(0.5) rotate(360deg);
			-webkit-transform: scale(0.5) rotate(360deg);
			-ms-transform: scale(0.5) rotate(360deg);
			transform: scale(0.5) rotate(360deg);
			color: #e5e6e7;
			z-index: 100001;
		}

		100% {
			-moz-transform: scale(0.5) rotate(360deg);
			-webkit-transform: scale(0.5) rotate(360deg);
			-ms-transform: scale(0.5) rotate(360deg);
			transform: scale(0.5) rotate(360deg);
			color: #e5e6e7;
			z-index: -1;
		}
	}

	@keyframes spinner-hide {
		0% {
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
			color: #e5e6e7;
			z-index: 100001;
		}

		99% {
			-moz-transform: scale(0.5) rotate(360deg);
			-webkit-transform: scale(0.5) rotate(360deg);
			-ms-transform: scale(0.5) rotate(360deg);
			transform: scale(0.5) rotate(360deg);
			color: #e5e6e7;
			z-index: 100001;
		}

		100% {
			-moz-transform: scale(0.5) rotate(360deg);
			-webkit-transform: scale(0.5) rotate(360deg);
			-ms-transform: scale(0.5) rotate(360deg);
			transform: scale(0.5) rotate(360deg);
			color: #e5e6e7;
			z-index: -1;
		}
	}

	@-moz-keyframes overlay-hide {
		0% {
			opacity: 1;
			z-index: 100000;
		}

		15% {
			opacity: 1;
			z-index: 100000;
		}

		99% {
			opacity: 0;
			z-index: 100000;
		}

		100% {
			opacity: 0;
			z-index: -1;
		}
	}

	@-webkit-keyframes overlay-hide {
		0% {
			opacity: 1;
			z-index: 100000;
		}

		15% {
			opacity: 1;
			z-index: 100000;
		}

		99% {
			opacity: 0;
			z-index: 100000;
		}

		100% {
			opacity: 0;
			z-index: -1;
		}
	}

	@-ms-keyframes overlay-hide {
		0% {
			opacity: 1;
			z-index: 100000;
		}

		15% {
			opacity: 1;
			z-index: 100000;
		}

		99% {
			opacity: 0;
			z-index: 100000;
		}

		100% {
			opacity: 0;
			z-index: -1;
		}
	}

	@keyframes overlay-hide {
		0% {
			opacity: 1;
			z-index: 100000;
		}

		15% {
			opacity: 1;
			z-index: 100000;
		}

		99% {
			opacity: 0;
			z-index: 100000;
		}

		100% {
			opacity: 0;
			z-index: -1;
		}
	}

	body {
		text-decoration: none;
	}

		body:before {
			-moz-animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-hide 0.25s ease-in-out forwards !important;
			-webkit-animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-hide 0.25s ease-in-out forwards !important;
			-ms-animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-hide 0.25s ease-in-out forwards !important;
			animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-hide 0.25s ease-in-out forwards !important;
			-moz-transform-origin: 50% 50%;
			-webkit-transform-origin: 50% 50%;
			-ms-transform-origin: 50% 50%;
			transform-origin: 50% 50%;
			-moz-osx-font-smoothing: grayscale;
			-webkit-font-smoothing: antialiased;
			font-family: FontAwesome;
			font-style: normal;
			font-weight: normal;
			text-transform: none !important;
			color: #e5e6e7;
			content: '\f1ce';
			cursor: default;
			display: block;
			font-size: 2em;
			height: 2em;
			left: 50%;
			line-height: 2em;
			margin: -1em 0 0 -1em;
			opacity: 0;
			position: fixed;
			text-align: center;
			top: 50%;
			width: 2em;
			z-index: -1;
		}

		body:after {
			-moz-animation: overlay-hide 1.5s ease-in forwards !important;
			-webkit-animation: overlay-hide 1.5s ease-in forwards !important;
			-ms-animation: overlay-hide 1.5s ease-in forwards !important;
			animation: overlay-hide 1.5s ease-in forwards !important;
			background: #ffffff;
			content: '';
			display: block;
			height: 100%;
			left: 0;
			opacity: 0;
			position: fixed;
			top: 0;
			width: 100%;
			z-index: -1;
		}

		body.is-preload:before {
			-moz-animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-rotate 0.75s infinite linear !important;
			-webkit-animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-rotate 0.75s infinite linear !important;
			-ms-animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-rotate 0.75s infinite linear !important;
			animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-rotate 0.75s infinite linear !important;
			z-index: 100001;
		}

		body.is-preload:after {
			-moz-animation: none !important;
			-webkit-animation: none !important;
			-ms-animation: none !important;
			animation: none !important;
			opacity: 1;
			z-index: 100000;
		}

	@media (-webkit-min-device-pixel-ratio: 2) {

		body:before {
			line-height: 2.025em;
		}

	}

/* Type */

	body, input, textarea, select {
		font-family: "Source Sans Pro", "sans-serif";
		font-weight: 300;
		font-size: 18pt;
		line-height: 1.75em;
		color: #39454b;
		letter-spacing: 0.025em;
	}

		@media screen and (max-width: 1920px) {

			body, input, textarea, select {
				font-size: 17pt;
			}

		}

		@media screen and (max-width: 1680px) {

			body, input, textarea, select {
				font-size: 15pt;
			}

		}

		@media screen and (max-width: 1280px) {

			body, input, textarea, select {
				font-size: 13pt;
			}

		}

		@media screen and (max-width: 1000px) {

			body, input, textarea, select {
				font-size: 13pt;
			}

		}

		@media screen and (max-width: 736px) {

			body, input, textarea, select {
				font-size: 12pt;
				line-height: 1.5em;
			}

		}

	h1, h2, h3, h4, h5, h6 {
		font-weight: 900;
		color: inherit;
		letter-spacing: -0.0325em;
	}

		h1 a, h2 a, h3 a, h4 a, h5 a, h6 a {
			color: inherit;
			text-decoration: none;
		}

	h2 {
		font-size: 2.25em;
		line-height: 1.25em;
		letter-spacing: -0.05em;
	}

	@media screen and (max-width: 736px) {

		h2 {
			font-size: 1.5em;
		}

	}

	strong, b {
		font-weight: 900;
		color: inherit;
	}

	em, i {
		font-style: italic;
	}

	a {
		-moz-transition: color 0.2s ease-in-out;
		-webkit-transition: color 0.2s ease-in-out;
		-ms-transition: color 0.2s ease-in-out;
		transition: color 0.2s ease-in-out;
		color: #98c593;
	}

	sub {
		position: relative;
		top: 0.5em;
		font-size: 0.8em;
	}

	sup {
		position: relative;
		top: -0.5em;
		font-size: 0.8em;
	}

	hr {
		border: 0;
		border-top: solid 1px #e5e6e7;
	}

	blockquote {
		border-left: solid 0.5em #e5e6e7;
		padding: 1em 0 1em 2em;
		font-style: italic;
	}

	p, ul, ol, dl, table {
		margin-bottom: 1em;
	}

/* Box */

	.box {
		background: #ffffff;
		color: #39454b;
		padding: 2em;
	}

		.box > :last-child {
			margin-bottom: 0;
		}

		.box.style2 {
			padding: 3.5em 2.5em 3.5em 2.5em;
		}

		@media screen and (max-width: 736px) {

			.box {
				padding: 1em;
			}

				.box.style2 {
					padding: 1.5em 1.25em 1.5em 1.25em;
					background-color: rgba(255, 255, 255, 0.9);
				}

		}

/* Button */

	input[type="button"],
	input[type="submit"],
	input[type="reset"],
	.button,
	button {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		-moz-transition: background-color 0.2s ease-in-out;
		-webkit-transition: background-color 0.2s ease-in-out;
		-ms-transition: background-color 0.2s ease-in-out;
		transition: background-color 0.2s ease-in-out;
		background-color: #98c593;
		border: 0;
		border-radius: 3.5em;
		color: #ffffff;
		cursor: pointer;
		display: inline-block;
		height: 3.5em;
		line-height: 3.5em;
		outline: 0;
		padding: 0 2em 0 2em;
		position: relative;
		text-align: center;
		text-decoration: none;
	}

		input[type="button"].down,
		input[type="submit"].down,
		input[type="reset"].down,
		.button.down,
		button.down {
			width: 5em;
			height: 5em;
			line-height: 4.5em;
			padding: 0;
			background-image: url("images/dark-arrow.svg");
			background-position: center center;
			background-repeat: no-repeat;
			text-indent: -10em;
			overflow: hidden;
		}

			input[type="button"].down.anchored,
			input[type="submit"].down.anchored,
			input[type="reset"].down.anchored,
			.button.down.anchored,
			button.down.anchored {
				bottom: 0;
				border-bottom: 0;
				border-radius: 3em 3em 0 0;
				height: 4.5em;
				margin-left: -2.5em;
			}

		input[type="button"].anchored,
		input[type="submit"].anchored,
		input[type="reset"].anchored,
		.button.anchored,
		button.anchored {
			position: absolute;
			left: 50%;
		}

		input[type="button"]:hover,
		input[type="submit"]:hover,
		input[type="reset"]:hover,
		.button:hover,
		button:hover {
			background-color: #a8cea4;
		}

		input[type="button"]:active,
		input[type="submit"]:active,
		input[type="reset"]:active,
		.button:active,
		button:active {
			background-color: #88bc82;
		}

		input[type="button"].style2,
		input[type="submit"].style2,
		input[type="reset"].style2,
		.button.style2,
		button.style2 {
			background-color: transparent;
			border: solid 2px #e5e6e7;
			color: inherit;
		}

			input[type="button"].style2:hover,
			input[type="submit"].style2:hover,
			input[type="reset"].style2:hover,
			.button.style2:hover,
			button.style2:hover {
				background-color: rgba(229, 230, 231, 0.25);
			}

			input[type="button"].style2:active,
			input[type="submit"].style2:active,
			input[type="reset"].style2:active,
			.button.style2:active,
			button.style2:active {
				background-color: rgba(229, 230, 231, 0.375);
			}

			input[type="button"].style2.down,
			input[type="submit"].style2.down,
			input[type="reset"].style2.down,
			.button.style2.down,
			button.style2.down {
				background-image: url("images/arrow.svg");
			}

/* Form */

	form {
		margin: 0 0 2em 0;
	}

		form > :last-child {
			margin-bottom: 0;
		}

		form > .fields {
			display: -moz-flex;
			display: -webkit-flex;
			display: -ms-flex;
			display: flex;
			-moz-flex-wrap: wrap;
			-webkit-flex-wrap: wrap;
			-ms-flex-wrap: wrap;
			flex-wrap: wrap;
			width: calc(100% + 3em);
			margin: -1.5em 0 2em -1.5em;
		}

			form > .fields > .field {
				-moz-flex-grow: 0;
				-webkit-flex-grow: 0;
				-ms-flex-grow: 0;
				flex-grow: 0;
				-moz-flex-shrink: 0;
				-webkit-flex-shrink: 0;
				-ms-flex-shrink: 0;
				flex-shrink: 0;
				padding: 1.5em 0 0 1.5em;
				width: calc(100% - 1.5em);
			}

				form > .fields > .field.half {
					width: calc(50% - 0.75em);
				}

				form > .fields > .field.third {
					width: calc(100%/3 - 0.5em);
				}

				form > .fields > .field.quarter {
					width: calc(25% - 0.375em);
				}

		@media screen and (max-width: 480px) {

			form > .fields {
				width: calc(100% + 2em);
				margin: -1em 0 2em -1em;
			}

				form > .fields > .field {
					padding: 1em 0 0 1em;
					width: calc(100% - 1em);
				}

					form > .fields > .field.half {
						width: calc(100% - 1em);
					}

					form > .fields > .field.third {
						width: calc(100% - 1em);
					}

					form > .fields > .field.quarter {
						width: calc(100% - 1em);
					}

		}

	label {
		display: block;
	}

	input[type="text"],
	input[type="password"],
	input[type="email"],
	input[type="tel"],
	input[type="search"],
	input[type="url"],
	select,
	textarea {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		-moz-transition: border-color 0.2s ease-in-out, color 0.2s ease-in-out;
		-webkit-transition: border-color 0.2s ease-in-out, color 0.2s ease-in-out;
		-ms-transition: border-color 0.2s ease-in-out, color 0.2s ease-in-out;
		transition: border-color 0.2s ease-in-out, color 0.2s ease-in-out;
		color: #39454b;
		display: block;
		width: 100%;
		padding: 0.65em 0.75em;
		background: none;
		border: solid 2px #e5e6e7;
		color: inherit;
		border-radius: 0.5em;
		outline: none;
	}

		input[type="text"]:focus,
		input[type="password"]:focus,
		input[type="email"]:focus,
		input[type="tel"]:focus,
		input[type="search"]:focus,
		input[type="url"]:focus,
		select:focus,
		textarea:focus {
			border-color: #9ac8e9;
		}

	input[type="text"],
	input[type="password"],
	input[type="email"],
	input[type="tel"],
	input[type="search"],
	input[type="url"],
	select {
		line-height: 1.35em;
	}

	textarea {
		min-height: 8em;
	}

	::-moz-focus-inner {
		border: 0;
	}

	::-webkit-input-placeholder {
		opacity: 0.375;
	}

	:-moz-placeholder {
		opacity: 0.375;
	}

	::-moz-placeholder {
		opacity: 0.375;
	}

	:-ms-input-placeholder {
		opacity: 0.375;
	}

/* Icon */

	.icon {
		text-decoration: none;
		position: relative;
		text-decoration: none;
	}

		.icon:before {
			-moz-osx-font-smoothing: grayscale;
			-webkit-font-smoothing: antialiased;
			display: inline-block;
			font-style: normal;
			font-variant: normal;
			text-rendering: auto;
			line-height: 1;
			text-transform: none !important;
			font-family: 'Font Awesome 5 Free';
			font-weight: 400;
		}

		.icon:before {
			line-height: inherit;
		}

		.icon > .label {
			display: none;
		}

		.icon.solid:before {
			font-weight: 900;
		}

		.icon.brands:before {
			font-family: 'Font Awesome 5 Brands';
		}

/* Image */

	.image {
		position: relative;
		display: inline-block;
	}

		.image:before {
			content: '';
			position: absolute;
			left: 0;
			top: 0;
			width: 100%;
			height: 100%;
			background: url("images/overlay.png");
		}

		.image img {
			display: block;
			width: 100%;
		}

		.image.featured {
			display: block;
			width: 100%;
			margin: 0 0 2em 0;
		}

		.image.fit {
			display: block;
			width: 100%;
		}

		.image.left {
			float: left;
			margin: 0 2em 2em 0;
		}

		.image.centered {
			display: block;
			margin: 0 0 2em 0;
		}

			.image.centered img {
				margin: 0 auto;
				width: auto;
			}

/* List */

	ul.default {
		list-style: disc;
		padding-left: 1em;
	}

		ul.default li {
			padding-left: 0.5em;
		}

	ul.menu {
		cursor: default;
	}

		ul.menu li {
			display: inline-block;
			line-height: 1em;
			border-left: solid 1px #e5e6e7;
			padding: 0 0 0 0.5em;
			margin: 0 0 0 0.5em;
		}

			ul.menu li:first-child {
				border-left: 0;
				padding-left: 0;
				margin-left: 0;
			}

	ol.default {
		list-style: decimal;
		padding-left: 1.25em;
	}

		ol.default li {
			padding-left: 0.25em;
		}

/* Actions */

	ul.actions {
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		cursor: default;
		list-style: none;
		margin-left: -1em;
		padding-left: 0;
	}

		ul.actions li {
			padding: 0 0 0 1em;
			vertical-align: middle;
		}

		ul.actions.special {
			-moz-justify-content: center;
			-webkit-justify-content: center;
			-ms-justify-content: center;
			justify-content: center;
			width: 100%;
			margin-left: 0;
		}

			ul.actions.special li:first-child {
				padding-left: 0;
			}

		ul.actions.stacked {
			-moz-flex-direction: column;
			-webkit-flex-direction: column;
			-ms-flex-direction: column;
			flex-direction: column;
			margin-left: 0;
		}

			ul.actions.stacked li {
				padding: 1.3em 0 0 0;
			}

				ul.actions.stacked li:first-child {
					padding-top: 0;
				}

		ul.actions.fit {
			width: calc(100% + 1em);
		}

			ul.actions.fit li {
				-moz-flex-grow: 1;
				-webkit-flex-grow: 1;
				-ms-flex-grow: 1;
				flex-grow: 1;
				-moz-flex-shrink: 1;
				-webkit-flex-shrink: 1;
				-ms-flex-shrink: 1;
				flex-shrink: 1;
				width: 100%;
			}

				ul.actions.fit li > * {
					width: 100%;
				}

			ul.actions.fit.stacked {
				width: 100%;
			}

		@media screen and (max-width: 480px) {

			ul.actions:not(.fixed) {
				-moz-flex-direction: column;
				-webkit-flex-direction: column;
				-ms-flex-direction: column;
				flex-direction: column;
				margin-left: 0;
				width: 100% !important;
			}

				ul.actions:not(.fixed) li {
					-moz-flex-grow: 1;
					-webkit-flex-grow: 1;
					-ms-flex-grow: 1;
					flex-grow: 1;
					-moz-flex-shrink: 1;
					-webkit-flex-shrink: 1;
					-ms-flex-shrink: 1;
					flex-shrink: 1;
					padding: 1em 0 0 0;
					text-align: center;
					width: 100%;
				}

					ul.actions:not(.fixed) li > * {
						width: 100%;
					}

					ul.actions:not(.fixed) li:first-child {
						padding-top: 0;
					}

					ul.actions:not(.fixed) li input[type="submit"],
					ul.actions:not(.fixed) li input[type="reset"],
					ul.actions:not(.fixed) li input[type="button"],
					ul.actions:not(.fixed) li button,
					ul.actions:not(.fixed) li .button {
						width: 100%;
					}

						ul.actions:not(.fixed) li input[type="submit"].icon:before,
						ul.actions:not(.fixed) li input[type="reset"].icon:before,
						ul.actions:not(.fixed) li input[type="button"].icon:before,
						ul.actions:not(.fixed) li button.icon:before,
						ul.actions:not(.fixed) li .button.icon:before {
							margin-left: -0.5rem;
						}

		}

/* Icons */

	ul.icons {
		cursor: default;
	}

		ul.icons li {
			display: inline-block;
		}

		ul.icons a {
			display: inline-block;
			width: 2em;
			height: 2em;
			line-height: 2em;
			text-align: center;
			border: 0;
		}

/* Sections/Article */

	header {
		margin-bottom: 1em;
	}

		header p {
			display: block;
			margin: 1em 0 0 0;
			padding: 0 0 0.5em 0;
		}

	footer {
		margin-top: 2em;
	}

/* Table */

	table {
		width: 100%;
	}

		table.default {
			width: 100%;
		}

			table.default tbody tr:nth-child(2n+2) {
				background: rgba(229, 230, 231, 0.5);
			}

			table.default td {
				padding: 0.5em 1em 0.5em 1em;
			}

			table.default th {
				text-align: left;
				font-weight: 900;
				padding: 0.5em 1em 0.5em 1em;
			}

			table.default thead {
				background: #39454b;
				color: #ffffff;
			}

			table.default tfoot {
				background: #e5e6e7;
			}

/* Poptrox */

	.poptrox-popup {
		-moz-box-sizing: content-box;
		-webkit-box-sizing: content-box;
		-ms-box-sizing: content-box;
		box-sizing: content-box;
		background: #fff;
		padding-bottom: 3em;
		box-shadow: 0 0.1em 0.15em 0 rgba(0, 0, 0, 0.15);
	}

		.poptrox-popup .loader {
			position: absolute;
			top: 50%;
			left: 50%;
			margin: -1em 0 0 -1em;
			width: 2em;
			height: 2em;
			display: block;
			font-size: 2em;
		}

			.poptrox-popup .loader:before {
				-moz-animation: spinner-rotate 0.75s infinite linear !important;
				-webkit-animation: spinner-rotate 0.75s infinite linear !important;
				-ms-animation: spinner-rotate 0.75s infinite linear !important;
				animation: spinner-rotate 0.75s infinite linear !important;
				-moz-osx-font-smoothing: grayscale;
				-webkit-font-smoothing: antialiased;
				font-family: FontAwesome;
				font-style: normal;
				font-weight: normal;
				text-transform: none !important;
				color: #e5e6e7;
				content: '\f1ce';
				cursor: default;
				display: block;
				height: 2em;
				left: 0;
				line-height: 2em;
				position: absolute;
				text-align: center;
				top: 0;
				width: 2em;
			}

		.poptrox-popup .caption {
			position: absolute;
			bottom: 0;
			left: 0;
			background: #ffffff;
			width: 100%;
			height: 3em;
			line-height: 2.8em;
			text-align: center;
			cursor: default;
			z-index: 1;
			font-size: 0.9em;
		}

		.poptrox-popup .nav-next,
		.poptrox-popup .nav-previous {
			-moz-transition: opacity 0.2s ease-in-out;
			-webkit-transition: opacity 0.2s ease-in-out;
			-ms-transition: opacity 0.2s ease-in-out;
			transition: opacity 0.2s ease-in-out;
			position: absolute;
			top: 0;
			width: 50%;
			height: 100%;
			opacity: 0;
			cursor: pointer;
			background: rgba(0, 0, 0, 0.01);
			-webkit-tap-highlight-color: rgba(255, 255, 255, 0);
		}

		.poptrox-popup .nav-next:before,
		.poptrox-popup .nav-previous:before {
			content: '';
			position: absolute;
			width: 96px;
			height: 64px;
			background: url("images/poptrox-nav.svg");
			top: calc(50% - 1.5em);
			margin: -32px 0 0 0;
		}

		.poptrox-popup:hover .nav-next,
		.poptrox-popup:hover .nav-previous {
			opacity: 0.5;
		}

		.poptrox-popup:hover .nav-next:hover,
		.poptrox-popup:hover .nav-previous:hover {
			opacity: 1.0;
		}

		.poptrox-popup .nav-previous:before {
			-moz-transform: scaleX(-1);
			-webkit-transform: scaleX(-1);
			-ms-transform: scaleX(-1);
			transform: scaleX(-1);
			-ms-filter: "FlipH";
			filter: FlipH;
		}

		.poptrox-popup .nav-next {
			right: 0;
		}

			.poptrox-popup .nav-next:before {
				right: 0;
			}

		.poptrox-popup .nav-previous {
			left: 0;
		}

			.poptrox-popup .nav-previous:before {
				left: 0;
			}

		.poptrox-popup .closer {
			-moz-transition: opacity 0.2s ease-in-out;
			-webkit-transition: opacity 0.2s ease-in-out;
			-ms-transition: opacity 0.2s ease-in-out;
			transition: opacity 0.2s ease-in-out;
			position: absolute;
			top: 0;
			right: 0;
			width: 64px;
			height: 64px;
			text-indent: -9999px;
			z-index: 2;
			opacity: 0;
			-webkit-tap-highlight-color: rgba(255, 255, 255, 0);
		}

			.poptrox-popup .closer:before {
				content: '';
				display: block;
				position: absolute;
				right: 16px;
				top: 16px;
				width: 40px;
				height: 40px;
				border-radius: 100%;
				box-shadow: inset 0 0 0 2px #fff;
				background: url("images/poptrox-closer.svg") center center;
				color: #ffffff !important;
			}

		.poptrox-popup:hover .closer {
			opacity: 0.5;
		}

			.poptrox-popup:hover .closer:hover {
				opacity: 1.0;
			}

		body.is-touch .poptrox-popup .nav-next,
		body.is-touch .poptrox-popup .nav-previous,
		body.is-touch .poptrox-popup .closer {
			opacity: 1.0 !important;
		}

		@media screen and (max-width: 736px) {

			.poptrox-popup .nav-next:before,
			.poptrox-popup .nav-previous:before {
				width: 48px;
				height: 32px;
				background-size: contain;
				margin: -16px 0 0 0;
			}

			.poptrox-popup .closer:before {
				right: 12px;
				top: 12px;
				width: 20px;
				height: 20px;
				box-shadow: inset 0 0 0 1px #fff;
				background-size: contain;
				opacity: 0.65;
			}

		}

/* Gallery */

	.gallery {
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-wrap: wrap;
		-webkit-flex-wrap: wrap;
		-ms-flex-wrap: wrap;
		flex-wrap: wrap;
		width: 45em;
		max-width: 100%;
		margin: 0 auto 2em auto;
	}

		.gallery article {
			-moz-transition: -moz-transform 1s ease, opacity 1s ease;
			-webkit-transition: -webkit-transform 1s ease, opacity 1s ease;
			-ms-transition: -ms-transform 1s ease, opacity 1s ease;
			transition: transform 1s ease, opacity 1s ease;
			-moz-transform: translateX(0);
			-webkit-transform: translateX(0);
			-ms-transform: translateX(0);
			transform: translateX(0);
			width: 50%;
			position: relative;
			opacity: 1.0;
		}

			.gallery article .image {
				margin: 0;
				display: block;
			}

			.gallery article:nth-last-child(1n) {
				-moz-transition-delay: 0.05s;
				-webkit-transition-delay: 0.05s;
				-ms-transition-delay: 0.05s;
				transition-delay: 0.05s;
			}

			.gallery article:nth-last-child(2n) {
				-moz-transition-delay: 0.05s;
				-webkit-transition-delay: 0.05s;
				-ms-transition-delay: 0.05s;
				transition-delay: 0.05s;
			}

			.gallery article:nth-last-child(2n) {
				-moz-transition-delay: 0.1s;
				-webkit-transition-delay: 0.1s;
				-ms-transition-delay: 0.1s;
				transition-delay: 0.1s;
			}

			.gallery article:nth-last-child(3n) {
				-moz-transition-delay: 0.1s;
				-webkit-transition-delay: 0.1s;
				-ms-transition-delay: 0.1s;
				transition-delay: 0.1s;
			}

			.gallery article:nth-last-child(3n) {
				-moz-transition-delay: 0.15s;
				-webkit-transition-delay: 0.15s;
				-ms-transition-delay: 0.15s;
				transition-delay: 0.15s;
			}

			.gallery article:nth-last-child(4n) {
				-moz-transition-delay: 0.15s;
				-webkit-transition-delay: 0.15s;
				-ms-transition-delay: 0.15s;
				transition-delay: 0.15s;
			}

			.gallery article:nth-last-child(4n) {
				-moz-transition-delay: 0.2s;
				-webkit-transition-delay: 0.2s;
				-ms-transition-delay: 0.2s;
				transition-delay: 0.2s;
			}

			.gallery article:nth-last-child(5n) {
				-moz-transition-delay: 0.2s;
				-webkit-transition-delay: 0.2s;
				-ms-transition-delay: 0.2s;
				transition-delay: 0.2s;
			}

			.gallery article:nth-last-child(5n) {
				-moz-transition-delay: 0.25s;
				-webkit-transition-delay: 0.25s;
				-ms-transition-delay: 0.25s;
				transition-delay: 0.25s;
			}

			.gallery article:nth-last-child(6n) {
				-moz-transition-delay: 0.25s;
				-webkit-transition-delay: 0.25s;
				-ms-transition-delay: 0.25s;
				transition-delay: 0.25s;
			}

			.gallery article:nth-last-child(6n) {
				-moz-transition-delay: 0.3s;
				-webkit-transition-delay: 0.3s;
				-ms-transition-delay: 0.3s;
				transition-delay: 0.3s;
			}

			.gallery article:nth-last-child(7n) {
				-moz-transition-delay: 0.3s;
				-webkit-transition-delay: 0.3s;
				-ms-transition-delay: 0.3s;
				transition-delay: 0.3s;
			}

			.gallery article:nth-last-child(7n) {
				-moz-transition-delay: 0.35s;
				-webkit-transition-delay: 0.35s;
				-ms-transition-delay: 0.35s;
				transition-delay: 0.35s;
			}

			.gallery article:nth-last-child(8n) {
				-moz-transition-delay: 0.35s;
				-webkit-transition-delay: 0.35s;
				-ms-transition-delay: 0.35s;
				transition-delay: 0.35s;
			}

			.gallery article:nth-last-child(8n) {
				-moz-transition-delay: 0.4s;
				-webkit-transition-delay: 0.4s;
				-ms-transition-delay: 0.4s;
				transition-delay: 0.4s;
			}

			.gallery article:nth-last-child(9n) {
				-moz-transition-delay: 0.4s;
				-webkit-transition-delay: 0.4s;
				-ms-transition-delay: 0.4s;
				transition-delay: 0.4s;
			}

			.gallery article:nth-last-child(9n) {
				-moz-transition-delay: 0.45s;
				-webkit-transition-delay: 0.45s;
				-ms-transition-delay: 0.45s;
				transition-delay: 0.45s;
			}

			.gallery article:nth-last-child(10n) {
				-moz-transition-delay: 0.45s;
				-webkit-transition-delay: 0.45s;
				-ms-transition-delay: 0.45s;
				transition-delay: 0.45s;
			}

			.gallery article:nth-last-child(10n) {
				-moz-transition-delay: 0.5s;
				-webkit-transition-delay: 0.5s;
				-ms-transition-delay: 0.5s;
				transition-delay: 0.5s;
			}

			.gallery article:nth-last-child(11n) {
				-moz-transition-delay: 0.5s;
				-webkit-transition-delay: 0.5s;
				-ms-transition-delay: 0.5s;
				transition-delay: 0.5s;
			}

			.gallery article:nth-last-child(11n) {
				-moz-transition-delay: 0.55s;
				-webkit-transition-delay: 0.55s;
				-ms-transition-delay: 0.55s;
				transition-delay: 0.55s;
			}

			.gallery article:nth-last-child(12n) {
				-moz-transition-delay: 0.55s;
				-webkit-transition-delay: 0.55s;
				-ms-transition-delay: 0.55s;
				transition-delay: 0.55s;
			}

			.gallery article:nth-last-child(12n) {
				-moz-transition-delay: 0.6s;
				-webkit-transition-delay: 0.6s;
				-ms-transition-delay: 0.6s;
				transition-delay: 0.6s;
			}

			.gallery article:nth-last-child(13n) {
				-moz-transition-delay: 0.6s;
				-webkit-transition-delay: 0.6s;
				-ms-transition-delay: 0.6s;
				transition-delay: 0.6s;
			}

			.gallery article:nth-last-child(13n) {
				-moz-transition-delay: 0.65s;
				-webkit-transition-delay: 0.65s;
				-ms-transition-delay: 0.65s;
				transition-delay: 0.65s;
			}

			.gallery article:nth-last-child(14n) {
				-moz-transition-delay: 0.65s;
				-webkit-transition-delay: 0.65s;
				-ms-transition-delay: 0.65s;
				transition-delay: 0.65s;
			}

			.gallery article:nth-last-child(14n) {
				-moz-transition-delay: 0.7s;
				-webkit-transition-delay: 0.7s;
				-ms-transition-delay: 0.7s;
				transition-delay: 0.7s;
			}

			.gallery article:nth-last-child(15n) {
				-moz-transition-delay: 0.7s;
				-webkit-transition-delay: 0.7s;
				-ms-transition-delay: 0.7s;
				transition-delay: 0.7s;
			}

			.gallery article:nth-last-child(15n) {
				-moz-transition-delay: 0.75s;
				-webkit-transition-delay: 0.75s;
				-ms-transition-delay: 0.75s;
				transition-delay: 0.75s;
			}

			.gallery article:nth-last-child(16n) {
				-moz-transition-delay: 0.75s;
				-webkit-transition-delay: 0.75s;
				-ms-transition-delay: 0.75s;
				transition-delay: 0.75s;
			}

			.gallery article:nth-last-child(16n) {
				-moz-transition-delay: 0.8s;
				-webkit-transition-delay: 0.8s;
				-ms-transition-delay: 0.8s;
				transition-delay: 0.8s;
			}

			.gallery article:nth-last-child(17n) {
				-moz-transition-delay: 0.8s;
				-webkit-transition-delay: 0.8s;
				-ms-transition-delay: 0.8s;
				transition-delay: 0.8s;
			}

			.gallery article:nth-last-child(17n) {
				-moz-transition-delay: 0.85s;
				-webkit-transition-delay: 0.85s;
				-ms-transition-delay: 0.85s;
				transition-delay: 0.85s;
			}

			.gallery article:nth-last-child(18n) {
				-moz-transition-delay: 0.85s;
				-webkit-transition-delay: 0.85s;
				-ms-transition-delay: 0.85s;
				transition-delay: 0.85s;
			}

			.gallery article:nth-last-child(18n) {
				-moz-transition-delay: 0.9s;
				-webkit-transition-delay: 0.9s;
				-ms-transition-delay: 0.9s;
				transition-delay: 0.9s;
			}

			.gallery article:nth-last-child(19n) {
				-moz-transition-delay: 0.9s;
				-webkit-transition-delay: 0.9s;
				-ms-transition-delay: 0.9s;
				transition-delay: 0.9s;
			}

			.gallery article:nth-last-child(19n) {
				-moz-transition-delay: 0.95s;
				-webkit-transition-delay: 0.95s;
				-ms-transition-delay: 0.95s;
				transition-delay: 0.95s;
			}

			.gallery article:nth-last-child(20n) {
				-moz-transition-delay: 0.95s;
				-webkit-transition-delay: 0.95s;
				-ms-transition-delay: 0.95s;
				transition-delay: 0.95s;
			}

			.gallery article:nth-last-child(20n) {
				-moz-transition-delay: 1s;
				-webkit-transition-delay: 1s;
				-ms-transition-delay: 1s;
				transition-delay: 1s;
			}

			.gallery article:nth-last-child(21n) {
				-moz-transition-delay: 1s;
				-webkit-transition-delay: 1s;
				-ms-transition-delay: 1s;
				transition-delay: 1s;
			}

			.gallery article:nth-last-child(21n) {
				-moz-transition-delay: 1.05s;
				-webkit-transition-delay: 1.05s;
				-ms-transition-delay: 1.05s;
				transition-delay: 1.05s;
			}

			.gallery article:nth-last-child(22n) {
				-moz-transition-delay: 1.05s;
				-webkit-transition-delay: 1.05s;
				-ms-transition-delay: 1.05s;
				transition-delay: 1.05s;
			}

			.gallery article:nth-last-child(22n) {
				-moz-transition-delay: 1.1s;
				-webkit-transition-delay: 1.1s;
				-ms-transition-delay: 1.1s;
				transition-delay: 1.1s;
			}

			.gallery article:nth-last-child(23n) {
				-moz-transition-delay: 1.1s;
				-webkit-transition-delay: 1.1s;
				-ms-transition-delay: 1.1s;
				transition-delay: 1.1s;
			}

			.gallery article:nth-last-child(23n) {
				-moz-transition-delay: 1.15s;
				-webkit-transition-delay: 1.15s;
				-ms-transition-delay: 1.15s;
				transition-delay: 1.15s;
			}

			.gallery article:nth-last-child(24n) {
				-moz-transition-delay: 1.15s;
				-webkit-transition-delay: 1.15s;
				-ms-transition-delay: 1.15s;
				transition-delay: 1.15s;
			}

		.gallery.inactive article {
			opacity: 0;
		}

			.gallery.inactive article.from-left {
				-moz-transform: translateX(-14em);
				-webkit-transform: translateX(-14em);
				-ms-transform: translateX(-14em);
				transform: translateX(-14em);
			}

			.gallery.inactive article.from-right {
				-moz-transform: translateX(14em);
				-webkit-transform: translateX(14em);
				-ms-transform: translateX(14em);
				transform: translateX(14em);
			}

			.gallery.inactive article.from-top {
				-moz-transform: translateY(-7em);
				-webkit-transform: translateY(-7em);
				-ms-transform: translateY(-7em);
				transform: translateY(-7em);
			}

			.gallery.inactive article.from-bottom {
				-moz-transform: translateY(7em);
				-webkit-transform: translateY(7em);
				-ms-transform: translateY(7em);
				transform: translateY(7em);
			}

		@media screen and (max-width: 480px) {

			.gallery {
				-moz-flex-wrap: nowrap;
				-webkit-flex-wrap: nowrap;
				-ms-flex-wrap: nowrap;
				flex-wrap: nowrap;
				-moz-flex-direction: column;
				-webkit-flex-direction: column;
				-ms-flex-direction: column;
				flex-direction: column;
			}

				.gallery article {
					width: 100%;
				}

		}

/* Header */

	#header {
		position: fixed;
		z-index: 10000;
		left: 0;
		top: 0;
		width: 100%;
		background: rgba(255, 255, 255, 0.95);
		height: 3em;
		line-height: 3em;
		box-shadow: 0 0 0.15em 0 rgba(0, 0, 0, 0.1);
	}

		#header h1 {
			position: absolute;
			left: 1em;
			top: 0;
			height: 3em;
			line-height: 3em;
			cursor: default;
		}

			#header h1 a {
				font-size: 1.25em;
			}

		#header nav {
			position: absolute;
			right: 0.5em;
			top: 0;
			height: 3em;
			line-height: 3em;
		}

			#header nav ul {
				margin: 0;
			}

				#header nav ul li {
					display: inline-block;
					margin-left: 0.5em;
					font-size: 0.9em;
				}

					#header nav ul li a {
						display: block;
						color: inherit;
						text-decoration: none;
						height: 3em;
						line-height: 3em;
						padding: 0 0.5em 0 0.5em;
						outline: 0;
					}

		@media screen and (max-width: 736px) {

			#header {
				height: 2.5em;
				line-height: 2.5em;
			}

				#header h1 {
					text-align: center;
					position: relative;
					left: 0;
					top: 0;
					height: 2.5em;
					line-height: 2.5em;
				}

					#header h1 a {
						font-size: 1em;
					}

				#header nav {
					display: none;
				}

		}

	body {
		padding-top: 3em;
	}

		@media screen and (max-width: 736px) {

			body {
				padding-top: 2.5em;
			}

		}

/* Main */

	.main {
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		position: relative;
		margin: 0;
		overflow-x: hidden;
	}

		.main > .content {
			width: 45em;
			max-width: calc(100% - 4em);
			margin: 0 auto;
		}

			.main > .content > :last-child {
				margin-bottom: 0;
			}

		.main.fullscreen {
			min-height: 100%;
		}

		.main.style1 {
			-moz-align-items: center;
			-webkit-align-items: center;
			-ms-align-items: center;
			align-items: center;
			-moz-justify-content: center;
			-webkit-justify-content: center;
			-ms-justify-content: center;
			justify-content: center;
			text-align: center;
			padding: 3em 0 3em 0;
		}

			.main.style1 h2 {
				font-size: 4.25em;
				line-height: 1em;
			}

			.main.style1 > .content {
				-moz-transition: opacity 1s ease;
				-webkit-transition: opacity 1s ease;
				-ms-transition: opacity 1s ease;
				transition: opacity 1s ease;
				-moz-transform: translateZ(0);
				-webkit-transform: translateZ(0);
				-ms-transform: translateZ(0);
				transform: translateZ(0);
				opacity: 1.0;
				margin: 0;
			}

			.main.style1.inactive > .content {
				opacity: 0;
			}

		.main.style2 {
			-moz-align-items: center;
			-webkit-align-items: center;
			-ms-align-items: center;
			align-items: center;
			-moz-justify-content: center;
			-webkit-justify-content: center;
			-ms-justify-content: center;
			justify-content: center;
			padding: 3em 0 3em 0;
			overflow: hidden;
		}

			.main.style2 > .content {
				-moz-transition: -moz-transform 1s ease;
				-webkit-transition: -webkit-transform 1s ease;
				-ms-transition: -ms-transform 1s ease;
				transition: transform 1s ease;
				-moz-transform: translateZ(0);
				-webkit-transform: translateZ(0);
				-ms-transform: translateZ(0);
				transform: translateZ(0);
				position: relative;
				width: 35%;
				margin: 0;
			}

			.main.style2.left {
				-moz-justify-content: -moz-flex-start;
				-webkit-justify-content: -webkit-flex-start;
				-ms-justify-content: -ms-flex-start;
				justify-content: flex-start;
			}

			.main.style2.right {
				-moz-justify-content: -moz-flex-end;
				-webkit-justify-content: -webkit-flex-end;
				-ms-justify-content: -ms-flex-end;
				justify-content: flex-end;
			}

			.main.style2.inactive.left > .content {
				-moz-transform: translateX(-100%);
				-webkit-transform: translateX(-100%);
				-ms-transform: translateX(-100%);
				transform: translateX(-100%);
			}

			.main.style2.inactive.right > .content {
				-moz-transform: translateX(100%);
				-webkit-transform: translateX(100%);
				-ms-transform: translateX(100%);
				transform: translateX(100%);
			}

		.main.style3 {
			text-align: center;
			padding: 6em 0 6em 0;
		}

			.main.style3 .content > header {
				margin-bottom: 2em;
			}

			.main.style3.primary {
				background: #ffffff;
			}

			.main.style3.secondary {
				background: #f5f6f7;
			}

		.main.dark {
			color: #ffffff;
		}

			.main.dark a {
				color: inherit;
			}

			.main.dark .button.style2 {
				border-color: #ffffff;
			}

				.main.dark .button.style2:hover {
					background-color: rgba(255, 255, 255, 0.125);
				}

				.main.dark .button.style2:active {
					background-color: rgba(255, 255, 255, 0.25);
				}

				.main.dark .button.style2.down {
					background-image: url("images/dark-arrow.svg");
				}

		body.is-touch .main {
			background-attachment: scroll !important;
		}

		@media screen and (max-width: 1920px) {

			.main.style2 .content {
				width: 40%;
			}

		}

		@media screen and (max-width: 1280px) {

			.main.style2 .content {
				width: 50%;
			}

		}

		@media screen and (max-width: 1000px) {

			.main.style2 .content {
				width: 60%;
			}

		}

		@media screen and (max-width: 736px) {

			.main > .content br {
				display: none;
			}

			.main.fullscreen {
				height: auto !important;
			}

			.main.style1 {
				padding: 4em 15px 4em 15px;
			}

				.main.style1 h2 {
					font-size: 3em;
				}

			.main.style2 {
				padding: 6em 15px 6em 15px;
			}

				.main.style2:before, .main.style2:after {
					display: none !important;
				}

				.main.style2 .button.anchored {
					display: none;
				}

				.main.style2 .content {
					width: 100%;
					max-width: 100%;
					text-align: center;
					-moz-transform: none;
					-webkit-transform: none;
					-ms-transform: none;
					transform: none;
				}

			.main.style3 {
				text-align: center;
				padding: 3em 10px 3em 10px;
			}

		}

		@media screen and (max-width: 480px) {

			.main > .content {
				max-width: calc(100% - 1.5em);
			}

		}

/* Footer */

	#footer {
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-align-items: center;
		-webkit-align-items: center;
		-ms-align-items: center;
		align-items: center;
		-moz-justify-content: space-between;
		-webkit-justify-content: space-between;
		-ms-justify-content: space-between;
		justify-content: space-between;
		position: relative;
		margin: 0;
		line-height: 1em;
		padding: 1.5em;
		background: #39454b;
		color: rgba(185, 186, 187, 0.5);
		overflow: hidden;
	}

		#footer > * {
			margin-bottom: 0;
		}

		#footer a {
			color: inherit;
		}

			#footer a:hover {
				color: #b9babb;
			}

		#footer ul.menu {
			margin: 0;
		}

			#footer ul.menu li {
				border-left-color: rgba(185, 186, 187, 0.2);
				font-size: 0.9em;
			}

		@media screen and (max-width: 1000px) {

			#footer {
				-moz-flex-direction: column;
				-webkit-flex-direction: column;
				-ms-flex-direction: column;
				flex-direction: column;
				-moz-justify-content: center;
				-webkit-justify-content: center;
				-ms-justify-content: center;
				justify-content: center;
				line-height: 1.5em;
				text-align: center;
				padding: 2em 1em 2em 1em;
			}

				#footer > * {
					margin: 0 0 1em 0;
				}

		}

		@media screen and (max-width: 736px) {

			#footer ul.menu li {
				border-left: none;
				display: block;
				line-height: inherit;
				margin: 0.25em 0 0 0;
				padding: 0.25em 0 0 0;
			}

				#footer ul.menu li:first-child {
					margin-top: 0;
					padding-top: 0;
				}

		}

/* Intro */

	#intro {
		background: url("images/overlay.png"), url("../../images/intro.jpg");
		background-size: 256px 256px, cover;
		background-attachment: fixed, fixed;
		background-position: top left, bottom center;
		background-repeat: repeat, no-repeat;
	}

/* One */

	#one {
		background: url("images/overlay.png"), url("../../images/one.jpg");
		background-size: 256px 256px, cover;
		background-attachment: fixed, fixed;
		background-position: top left, center center;
	}

/* Two */

	#two {
		background: url("images/overlay.png"), url("../../images/two.jpg");
		background-size: 256px 256px, cover;
		background-attachment: fixed, fixed;
		background-position: top left, center center;
	}

/* Contact */

	#contact {
		overflow: hidden;
		padding-bottom: 0;
	}

		#contact .box {
			-moz-transition: -moz-transform 1s ease;
			-webkit-transition: -webkit-transform 1s ease;
			-ms-transition: -ms-transform 1s ease;
			transition: transform 1s ease;
			-moz-transform: translateY(0);
			-webkit-transform: translateY(0);
			-ms-transform: translateY(0);
			transform: translateY(0);
			position: relative;
		}

		#contact.inactive .box {
			-moz-transform: translateY(100%);
			-webkit-transform: translateY(100%);
			-ms-transform: translateY(100%);
			transform: translateY(100%);
		}

		@media screen and (max-width: 736px) {

			#contact .box {
				padding: 1.5em 1.5em 2em 1.5em;
			}

		}

		@media screen and (max-width: 480px) {

			#contact .box {
				padding: 1em 1em 2em 1em;
			}

		} 
