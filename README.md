#<x-ip>

Custom [Polymer](http://polymer-project.org/) element for converting UTC to local time.

> Maintained by [Hemanth.HM](http://github.com/hemanth)

## Demo

[Demo](http://h3manth.com/demo/custom-elements/local-time/)

## Installation

`$ bower install --save local-time`

## Usage

0. Import Web Components' polyfill:

`<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>`

1. Import Custom Element:

`<link rel="import" href="src/local-time.html">`

2. Start using it!

`<local-time><local-time>`

`<local-time time='04/05/2013 4:42:42 PM UTC'></local-time>` would display the given UTC time in local time.

