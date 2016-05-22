# Infrangible

![](https://cdn.rawgit.com/FearGoidte/infrangible/master/logo.svg)

A <dfn>non-breaking space</dfn> is the same width as a normal space, but prevents the text from flowing to a new line or page. It is an invisible glue between the words on either side.

This is a [Ruby](https://www.ruby-lang.org/) extension for the [Middleman](https://middlemanapp.com) static website generator to automate the insertion of [non-breaking spaces](https://en.wikipedia.org/wiki/Non-breaking_space) between certain words.

## Features

* Respects existing non-breaking spaces and ignores [Text-level Semantics](http://www.w3.org/TR/html5/text-level-semantics.html#text-level-semantics) mark-up.
* Limits the length of generated ‘unbreakable’ lines to forty characters, by default, or to a variable that can be passed to the extension.

## Copyright

<cite property="dc:title">Infrangible</cite> by <span property="cc:attributionName"><a href="https://github.com/FearGoidte" property="cc:attributionURL">James Ó Nuanáin</a></span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

<p property="dc:source" typeof="DCMIType:software">Based upon <span property="dc:creator">Anton Bryl</span>’s <a href="http://blog.epubbooks.com/898/formatting-poetry-for-small-screens" property="dc:identifier"><cite property="dc:title">poemnobr.pl</cite></a>.</p>