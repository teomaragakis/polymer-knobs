# polymer-knobs

[![GitHub version](https://badge.fury.io/gh/teomaragakis%2Fpolymer-knobs.svg)](https://badge.fury.io/gh/teomaragakis%2Fpolymer-knobs)
[![Dependency Status](https://gemnasium.com/teomaragakis/polymer-knobs.svg)](https://gemnasium.com/teomaragakis/polymer-knobs)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/teomaragakis/polymer-knobs?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

⚠️ Until version 1.0.0, the components are under development and should not be considered production-ready in any way. ⚠️

Knob, switch and other web components, built with Polymer, and the seed-element. Leaving the rest of the README untouched for now.

Hey you! Are you any good with Polymer? I need some help! Take a look at the tasks I have marked with [help-wanted](https://github.com/teomaragakis/polymer-knobs/labels/help%20wanted) and roll up your sleeves! ✊ For questions, comments or ideas join me on [Gitter](https://gitter.im/teomaragakis/polymer-knobs?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge).

## Installation in your project
You can use [Bower](http://bower.io/) to install polymer-knobs into your project:

    bower install teomaragakis/polymer-knobs

## Demonstration & Playing around

Element dependencies are managed via Bower.  After downloading or checking out the package, install polymer-knobs with:

    bower install

If you wish to work on polymer-knobs in isolation, just use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep the bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at `http://localhost:8080/components/polymer-knobs/`.

## Testing

Navigate to the `/test` directory of your element to run its tests. If
you are using Polyserve: `http://localhost:8080/components/polymer-knobs/test/`

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.
