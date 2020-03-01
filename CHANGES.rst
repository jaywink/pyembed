.. :changelog:

Changes
=======

unreleased
----------

Enhancements:

- Allow passing additional options in the Embed call ([commit](https://github.com/jaywink/pyembed/commit/16f351f3c3230511ce04d86623a2bca904a8979e))
- Allow passing a timeout to embed calls. Defaults to 10s. ([commit](https://github.com/jaywink/pyembed/commit/e2b8a994cc90b61e3a4a53eb60cad676307d8244))
- Decrease oembed consuming logging level errors to debug ([commit](https://github.com/jaywink/pyembed/commit/6f8c1cc98d61ee3083e9803255e4b2cc90b5a0dd))

Bug fixes:

- Ensure when using oembed.com providers all links are not matched with Spotify ([commit](https://github.com/jaywink/pyembed/commit/f42021ed5f5da8268382a3522c1478d25b92e3b0))

  Fixes https://github.com/pyembed/pyembed/issues/64

v1.3.3, 2016-04-16
------------------

Bug fixes:

- #62: Add explicit scheme for YouTube.

v1.3.1, 2015-11-19
------------------

Bug fixes:

- #61: Handle downtime of provider list.

v1.3.0, 2015-09-05
------------------

Enhancements:

- #59: Reorder discovery.

v1.2.3, 2015-08-27
------------------

Bug fixes:

- #53: Don't hit provider list until necessary.

v1.2.2, 2015-08-15
------------------

Bug fixes:

- #51: Fix other Beautiful Soup warning

v1.2.1, 2015-08-15
------------------

Bug fixes:

- #50: Specify Beautiful Soup parser

v1.2.0, 2015-08-12
------------------

Enhancements:

- #48: Use official list of providers

v1.1.2, 2015-01-03
------------------

Enhancements:

- #44: Allow overriding of default templates by subclassing.

v1.1.1, 2014-09-02
------------------

Bug fixes:

- #42: Error embedding from SoundCloud.

v1.1.0, 2014-08-02
------------------

Enhancements:

- #40: Add support for providers that do not have discovery enabled.

v1.0.0, 2014-02-05
------------------

Initial stable release

v0.7.0, 2014-01-20
------------------

Breaking changes:

- The `pyembed.core.consumer.embed` method has been removed.  Instead, call
  `embed` on the `pyembed.core.PyEmbed` class.

v0.6.1, 2014-01-11
------------------

Bug fixes:

- #36: Failure to handle relative OEmbed URLs

v0.6.0, 2014-01-01
------------------

Breaking changes:

- The option to provide Mustache templates for rendering has been removed. It
  will be restored in a new pyembed-mustache module.

Enhancements:

- #33: Make rendering engines pluggable

v0.5.0, 2014-01-01
------------------

Breaking changes:

- The ``rembed`` package has been renamed to ``pyembed``.

Enhancements:

- #30: Rename to PyEmbed

v0.4.3, 2013-12-29
------------------

Rebuilt due to error in deployment process.  No functional changes.

v0.4.2, 2013-12-29
------------------

Rebuilt due to error in deployment process.  No functional changes.

v0.4.1, 2013-12-29
------------------

Rebuilt due to error in deployment process.  No functional changes.

v0.4.0, 2013-12-29
------------------

Enhancements:

- #5: More control over embedding format

v0.3.0, 2013-08-03
------------------

Breaking changes:

- The ``rembed`` package has been renamed to ``rembed.core``.

Enhancements:

- #19: Make rembed into a namespace package

v0.2.2, 2013-08-03
------------------

Enhancements:

- #20: Add code coverage to build
- #21: Add static analysis to build

v0.2.1, 2013-08-02
------------------

Bug fixes:

- #17: Classifiers not shown in PyPI

v0.2.0, 2013-07-30
------------------

Enhancements:

- #3: Support Python 3
- #4: Add maxheight and maxwidth parameters
- #10: Improve PyPI package entry

Bug fixes:

- #9: Tidy up requirements duplication

v0.1.1, 2013-07-29
------------------

Bug fixes:

- #6: Package fails to install

v0.1.0, 2013-07-29
------------------

Initial release
