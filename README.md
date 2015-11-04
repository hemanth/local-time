# local-time

Custom [Polymer](http://polymer-project.org/) element for converting UTC to local time.

> Maintained by [Hemanth.HM](http://github.com/hemanth)

## Demo

[Demo](http://h3manth.com/demo/custom-elements/local-time/)

## Installation

  `$ bower install --save local-time`

## Usage

0. Import Web Components polyfill (if needed):

  `<script src="../webcomponentsjs/webcomponents-lite.js"></script>`

1. Import Custom Element:

  `<link rel="import" href="../bower_components/local-time/local-time.html">`

2. Start using it!

  `<local-time><local-time>`

  `<local-time time='04/05/2013 4:42:42 PM UTC'></local-time>` would display the given UTC time in local time.

## Development

1. Install dependencies

  `npm install`

2. Run the dev server (to preview changes in the browser)

  `npm start`

3. Preview your progress

  `http://localhost:8080/components/local-time/index.html`

4. Run tests

  `npm test`
