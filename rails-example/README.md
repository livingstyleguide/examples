LivingStyleGuide Example for Ruby on Rails
==========================================

Example project for the [Living Style Guide Gem](https://github.com/hagenburger/livingstyleguide).


Setup
-----

Ruby 1.9.x must be [installed](http://www.ruby-lang.org/de/downloads/).

    git clone git@github.com:hagenburger/livingstyleguide-example.git
    cd livingstyleguide-example/rails-example
    gem install bundler
    bundle


Development
-----------

    cd livingstyleguide-example/rails-example
    rails s

Now you can open the style guide at <http://localhost:3000/assets/styleguide.html>.


Quick Documentation
-------------------

* **styleguide.html.lsg** defines which styles to use

* For every `@import` in your SCSS/Sass source, the LivingStyleGuide
  checks for a Markdown file with the same name at the same location.

* There are some Markdown extensions that will help you to document your
  CSS. Mostly you want to create an HTML example like this:

      ~~~ example
      <div class="***hello-world***">
        Hello World
      </div>
      ~~~

  This will:

    * Output the plain HTML (to see how it looks like)
    * Output the HTML source syntax highlighted
    * Highlight the class name (and everything else wrapped in three asterisks)


Feedback
--------

Just tweet @[hagenburger](https://twitter.com/hagenburger) or open an
issue [here](https://github.com/hagenburger/livingstyleguide-example/issues).


Credits
-------

Designed and developed by:
[Nico Hagenburger](https://github.com/hagenburger)
[hagenburger.net](http://hagenburger.net)
@[hagenburger](https://twitter.com/hagenburger)


