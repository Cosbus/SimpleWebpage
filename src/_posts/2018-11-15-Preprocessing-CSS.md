---
layout: post
title:  "CSS preprocessing"
date:   2018-11-15 20:00 -0600
categories: dunno
comments: true
---
A CSS preprocessor generates CSS from a syntax defined by the preprocessor. The preprocessor allows for more powerful and efficient functions and syntax compared to "regular" CSS. For this site the preprocessor called [Sass](https://sass-lang.com/) has been used through the [static site generator]({{ site.baseurl }}{% post_url 2018-11-14-SSG %}) [Jekyll](https://jekyllrb.com/).

There is of course a learning curve to using a CSS preprocessor and it requires a bit more initial work, but after the groundwork has been made changes in the style are easy and efficient to implement throughout the site. I prefer it to working with regular CSS.

Some techniques used in this site are variables, nested rules (CSS rules nested within each other) and referencing parent selectors (through the usage of "&"). 

More information regarding CSS preprocessors can e.g. be found [here](https://developer.mozilla.org/en-US/docs/Glossary/CSS_preprocessor "MDN web docs")

