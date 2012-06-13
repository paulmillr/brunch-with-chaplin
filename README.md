# Brunch with Chaplin
Brunch with Chaplin is a skeleton (boilerplate) for [Brunch](http://brunch.io) 
based on [Chaplin](https://github.com/chaplinjs/chaplin) framework.

Requires Brunch 1.1+.

## Getting started
* Create new project via executing `brunch new <project name> --skeleton git://github.com/paulmillr/brunch-with-chaplin.git`
* Build the project with `brunch b` or `brunch w`.
* Open the `public/` dir to see the result.
* Write your code.

Example application built with the lib:
[Ost.io](https://github.com/paulmillr/ostio).

See [Chaplin github page](https://github.com/chaplinjs/chaplin) for
documentation.

## Difference from Chaplin Boilerplate
[Chaplin Boilerplate](https://github.com/chaplinjs/chaplin-boilerplate)
is a official boilerplate all for chaplin. This skeleton is almost the same,
except a few changes:

* Added Header.
* Added authentication abstractions (`SessionController`, `LoginView` etc).
* CommonJS is used instead of AMD, because it's easier to use & debug.

## Features
* HTML5Boilerplate 3.0 html & css are included.
* CoffeeScript + Stylus + Handlebars as app languages
(you can change this to anything you want)
* Backbone as main framework
* Cross-module communication using the Mediator and Publish/Subscribe patterns
* Controllers for managing individual UI views
* Rails-style routes which map URLs to controller actions
* An application view as dispatcher and view manager
* Extended model, view and collection classes to avoid repetition and
enforce conventions
* Strict memory management and object disposal
* A collection with additional manipulation methods for smarter change events
* A collection view for easy and intelligent list rendering
* Client-side authentication using service providers like Facebook, Google
and Twitter

## Other
Versions of software the skeleton uses:

* HTML5Boilerplate 3.0.3
* jQuery 1.7.2
* Backbone 0.9.2
* Underscore 1.3.3
* Chaplin [c8c4f04ffe4262c1c014a86221c99b86b841aa9a](https://github.com/moviepilot/chaplin/commit/c8c4f04ffe4262c1c014a86221c99b86b841aa9a)

## License
The MIT license.

Copyright (c) 2012 Paul Miller (http://paulmillr.com/)

Copyright (c) 2012 Moviepilot GmbH, 9elements GmbH et al.

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
