# 全目录

[更多系统、论文，供君选择 ~~>](https://www.yuque.com/wisebit/blog)
# Bootbox - Twitter Bootstrap powered alert, confirm and flexible dialog boxes

Please see http://bootboxjs.com for full usage instructions, or head over to http://paynedigital.com/bootbox for
the original writeup about the project.

# Contact

The easiest thing is to [find me on twitter @makeusabrew](http://twitter.com/makeusabrew).

# Contributing

Please see the [CONTRIBUTING](https://github.com/makeusabrew/bootbox/blob/master/CONTRIBUTING.md) file for guidelines.

## Running Tests [![Build Status](https://api.travis-ci.org/makeusabrew/bootbox.png)](http://travis-ci.org/makeusabrew/bootbox)

Tests are run using [Karma](http://karma-runner.github.io/0.8/index.html) using the Mocha test adapter.
To run the tests yourself, simply run ```npm install``` within the project followed by ```npm test```.
Please note that this will require [PhantomJS](http://phantomjs.org/) being installed and in your path - if
it is not, you may run the tests and capture browsers manually by running ```karma start``` from the root
of the project.

The project is also hosted on [Travis CI](https://travis-ci.org/makeusabrew/bootbox) - when submitting
pull requests **please** ensure your tests pass as failing requests will be rejected. See the
[CONTRIBUTING](https://github.com/makeusabrew/bootbox/blob/master/CONTRIBUTING.md) file for more information.

## Building a minified release

The repository no longer contains a minified bootbox.min.js file - this is now only generated
[for releases](https://github.com/makeusabrew/bootbox/releases). To build your own minified copy
for use in development simply run ```npm install``` if you haven't already, followed by ```grunt uglify```.
This will generate a bootbox.min.js file in your working directory.

## A note on Bootstrap dependencies

Bootbox **4.0.0** is the first release to support Bootstrap 3.0.0.

Bootbox **3.3.0** is the *last* release to support Bootstrap 2.2.x.

Much more dependency information can be found [on the Bootbox website](http://bootboxjs.com/#dependencies).

### Roadmap

The latest major release of Bootbox - 4.0.0 - involved a total rewrite of the
internal code and introduced an entirely new public API. It has not re-implemented
some functionality from the 3.x series as of yet; this will be addressed in the
coming weeks in the form of new minor releases;
[a task list for 4.2.0 is available](https://github.com/makeusabrew/bootbox/issues/162) -
please feel free to add feedback and requests.

There is no new major (e.g. 5.x) release on the roadmap at present.

## Latest Release: 4.1.0

* Add support for placeholder attribute in prompts
* Add select, email and checkbox types for prompts (thanks [@tarlepp](https://github.com/tarlepp))
* Add Norwegian locale
* Allow setDefaults to take two key/val arguments
* Add unique classes for main dialog methods
* Create bower package

For a full list of releases and changes please see [the changelog](https://github.com/makeusabrew/bootbox/blob/master/CHANGELOG.md).

