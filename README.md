# Legato
Legato is a *language spec* that provides a simple and extensible syntax.


## Goals
- Simple, readable, writable
- Extensible modular elements
- Flexible: Good for writers, programmers, and other domains


## Implementations
Think of XML as a general syntax and HTML as a specific implementation for web.
XML consists of `<tag></tag>` but it has no concept of `<a>` or `<img>`.
(While this is [not correct](https://stackoverflow.com/questions/5558502/is-html5-valid-xml), you get the idea)

- [ ] legato-richtext: a language module that provides common components for legato-liberal and legato-linear.
  includes title, image, text styling, link.
- [ ] legato-liberal: an implementation for writing a general text *article* with basic media data (image/video).
- [ ] legato-linear: an implementation for making *presentation*. It is a new way of presenting. has no concept of slides.


## Motivation
While Markdown is popular with its simple and easy syntax, it has many [limitations and problems](http://ericholscher.com/blog/2016/mar/15/dont-use-markdown-for-technical-docs/).

For me, I use tables a lot and these make Markdown unusable.

1. lacks the nesting (e.g. markup inside table, code inside table)
2. enforce the first row to be the header row
3. easy-to-read but really hard-to-write table syntax
