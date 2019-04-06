---
layout: post
title:  "Edge Cases"
date:   2015-02-17 11:04:01
categories: post
---
Some edge cases and cautionary examples on using Markdown for writing content using this theme. In particular, list syntax can really knot things up.
<!--more-->

* Table of contents
{:toc}

### Mathjax improperly parsing greater and less than and ampersands inside blocks

The mathjax plugin has been modified to contain all the block style mathjax inside a ```<div class="mathblock">..</div>``` tag wrapper pair
which fixes many of the issues with conflicts with the Kramdown parser. Some examples sent to me by Quxiaofeng are now parsing correctly, I believe.

This code:


