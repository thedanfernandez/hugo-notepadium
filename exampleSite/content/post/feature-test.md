+++
author = "Dan"
title = "Feature Test for Notepadium"
date = "2020-04-02"
description = "A test page for features"
tags = [
    "hugo",
    "test",
]
cover = "../../images/blog-cover.jpg"
imgs = ["../../images/01.png", "../../images/04.png"]
toc = true
readingTime = true  # show reading time after article date
+++

This is a test page for features and front-matter

<!--more-->

## Key features enabled on feature test page

* Cover image
* Reading Time
* Inline HTML

## Font Awesome

{{<raw>}}
    <div class="flex-center">
        <a href="https://twitter.com/danielfe/"><i class="fab fa-twitter fa-2x"></i></a>
        <a href="https://linkedin.com/in/danfernandez/"><i class="fab fa-linkedin fa-2x"></i></a>
        <a href="https://github.com/thedanfernandez/"><i class="fab fa-github fa-2x"></i></a>
        <a href="https://github.com/thedanfernandez/"><i class="fas fa-rss-square fa-2x"></i></a>
    </div>
{{</ raw>}}

## Inline HTML using Raw

{{<raw>}}
    <h2>Test to see what happens with HTML</h2>
    <img src="images/01.png" border=2 />
{{</ raw>}}

## Blockquotes - Lorem Ipsum

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

### Blockquote without attribution

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Note** that you can use *Markdown syntax* within a blockquote.

#### Blockquote with attribution

> Don't communicate by sharing memory, share memory by communicating.</p>
> — <cite>Rob Pike[^1]</cite>
