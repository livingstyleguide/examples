Living Style Guide
==================

Example project for the [Living Style Guide Gem](https://github.com/hagenburger/livingstyleguide).


Setup
-----

Ruby 1.9.x must be [installed](http://www.ruby-lang.org/de/downloads/).

    git clone XYZ
    cd XYZ
    gem install bundler


Development
-----------

    cd XYZ
    bundle # Unter Mac OS: bundle --without linux
    middleman

Now you can open the style guide at <http://localhost:4567/>.


Production
----------

    cd XYZ
    bundle # for Mac OS: bundle --without linux
    middleman build

Now all stylesheets are available at XYZ/build:

  * rendered as CSS
  * compressed
  * with hashed file names (also for images/fonts/…)

You’ll find all CSS file names with hashes at `XYZ/build/css-files.json`.


Credits
-------

Designed and developed by:
[Nico Hagenburger](https://github.com/hagenburger)
[hagenburger.net](http://hagenburger.net)
@[hagenburger](https://twitter.com/hagenburger)

