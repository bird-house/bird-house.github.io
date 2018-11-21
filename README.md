# Birdhouse Website

[![Build Status](https://travis-ci.org/bird-house/bird-house.github.io.svg?branch=master)](https://travis-ci.org/bird-house/bird-house.github.io)
[![GitHub license](https://img.shields.io/github/license/bird-house/bird-house.github.io.svg)](https://github.com/bird-house/bird-house.github.io/blob/master/LICENSE)

This is the source of the [Birdhouse Website](https://bird-house.github.io/).

The Birdhouse Website is the main site for the Birdhouse project
where you can find links to documentation and demos.

## Contributing

Contributions are welcome. Feel free to open a pull request with changes.

### Running it Locally

It can be helpful to preview changes on your computer before opening a pull request. The *Birdhouse Website* uses the [Jekyll static site generator](http://jekyllrb.com/).

Clone this repository locally, and cd into it:

```
$ git clone https://github.com/bird-house/bird-house.github.io
$ cd bird-house.github.io
```

Make sure you have ruby installed on your computer.
See https://www.ruby-lang.org/en/downloads/.

Install `bundler`, and use it to install the dependencies to build the website:

```
gem install bundler
bundle install
```

Now you can ask Jekyll to build the website:

```
bundle exec jekyll build
bundle exec jekyll serve
```

Point your browser at http://localhost:4000.

Edit the various parts, Jekyll should automatically rebuild and
refresh the pages when changes occur.

To stop serving the website, press **`Ctrl`**-`C` in your terminal.

## Deployment

Pull requests merged to the master branch are automatically deployed to the production website.

## Where to Edit?

You can edit the main page of the website by changing `index.md`.
It is written in [Markdown](https://guides.github.com/features/mastering-markdown/).

The site has other pages written in Markdown like `about.md`.

To customise the layout read the documentation of the [minima theme](https://github.com/jekyll/minima).

## Links

* [Jekyll minima theme](https://github.com/jekyll/minima) ([view](https://jekyll.github.io/minima/))
* [Jupyter Website](https://github.com/jupyter/jupyter.github.io) based on minima theme ([view](https://jupyter.org/))
* [Markdown](https://guides.github.com/features/mastering-markdown/)
