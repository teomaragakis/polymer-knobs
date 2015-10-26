# polymer-knobs

[![GitHub version](https://badge.fury.io/gh/teomaragakis%2Fpolymer-knobs.svg)](https://badge.fury.io/gh/teomaragakis%2Fpolymer-knobs)
[![Dependency Status](https://gemnasium.com/teomaragakis/polymer-knobs.svg)](https://gemnasium.com/teomaragakis/polymer-knobs)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/teomaragakis/polymer-knobs?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Knob, switch and other web components, built with Polymer, and the seed-element. @PolymerElements/seed-element. Leaving the rest of the README untouched for now. #todo

Until version 1.0.0, the components are under development and not considered ready in any way.

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at
`http://localhost:8080/components/seed-element/`, where `seed-element` is the name of the directory containing it.


## Testing Your Element

Simply navigate to the `/test` directory of your element to run its tests. If
you are using Polyserve: `http://localhost:8080/components/seed-element/test/`

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
