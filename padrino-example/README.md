Living Style Guide
==================

Example project for the [Living Style Guide Gem](https://github.com/hagenburger/livingstyleguide). You can find an
  online version under <http://padrino-livingstyleguide.de.a9sapp.eu/assets/styleguide.html>


Setup
-----

Ruby 1.9.x (or higher) must be [installed](http://www.ruby-lang.org/de/downloads/).

    git clone git@github.com:hagenburger/livingstyleguide-example.git
    cd livingstyleguide-example/padrino-example
    gem install bundler
    bundle


Development
-----------

    cd livingstyleguide-example/padrino-example
    bundle exec padrino s

Now you can open the style guide at <http://localhost:3001/assets/styleguide.html>


Quick Documentation
-------------------

* [styleguide.html.lsg](https://github.com/hagenburger/livingstyleguide-example/blob/master/padrino-example/app/assets/stylesheets/styleguide.html.lsg) defines which styles to use

* For every [`@import` in your SCSS/Sass source](https://github.com/hagenburger/livingstyleguide-example/blob/master/padrino-example/app/assets/stylesheets/application.css.scss#L13), the LivingStyleGuide
  checks for a [Markdown file with the same name at the same location](https://github.com/hagenburger/livingstyleguide-example/blob/master/padrino-example/app/assets/stylesheets/modules/_button.md).

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

Tweet @[wikimatze](https://twitter.com/wikimatze) or open an
issue [here](https://github.com/hagenburger/livingstyleguide-example/issues). Thanks to
@[hagenburger](https://twitter.com/hagenburger) for making such an awesome gem.

