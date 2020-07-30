# Macrobars JavaScript Templating Library

### Why this exists

A couple of years ago, I made <a href="https://github.com/Udo/minibars">Minibars</a>,
a (sort-of) drop-in replacement for the Handlebars JavaScript templating library and
its relatives, mostly because they have a huge code size and I don't need all their
features.

Since then my thinking on templating has come full circle, mostly because I got tired
of all the glue code that tends to accumulate *outside* of templates, especially if
they don't fit neatly within the "this template renders a struct as-is" paradigm.
Macrobars is a return to full code execution in templates. Obviously, that makes it
unsuitable for some applications, but to be honest it's questionable whether Handlebars-like
templating was ever suitable in these contexts either.

