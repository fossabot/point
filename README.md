# `point`
## A simple tool for creating HTML presentations

[![Maintainability](https://api.codeclimate.com/v1/badges/1cede0dc4f659ebb2c3c/maintainability)](https://codeclimate.com/github/skuzzymiglet/point/maintainability)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/b238e72b91fb42c2986eee097bc06947)](https://www.codacy.com/manual/skuzzymiglet/point?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=skuzzymiglet/point&amp;utm_campaign=Badge_Grade)

## Installation

`go get github.com/skuzzymiglet/point`

##  Usage

Two blank lines in your `md` file indicate a new slide

`point -i IN [-s STYLE] [-o OUT]`

(IN being a markdown file)

Prints a HTML file to stdout by default.

It can then be opened in a browser. Use <kbd>Right</kbd> and <kbd>Left</kbd> to move through the slides

## TODO

- [X] Embed CSS
- [X] Embed JS
- [ ] Embed images as `base64`
- [ ] Minify
