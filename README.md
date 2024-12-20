# Birdhouse Website

[![GitHub license](https://img.shields.io/github/license/bird-house/bird-house.github.io.svg)](https://github.com/bird-house/bird-house.github.io/blob/main/LICENSE)
[![Join the chat at Gitter](https://badges.gitter.im/bird-house/birdhouse.svg)](https://gitter.im/bird-house/birdhouse?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This is the source of the [Birdhouse Website](https://bird-house.github.io/).

The Birdhouse Website is the main site for the Birdhouse project
where you can find links to documentation and demos.

## Contributing

Contributions are welcome. Feel free to open a pull request with changes.

### Running it Locally

It can be helpful to preview changes on your computer before opening a pull request. The *Birdhouse Website* uses [MkDocs](https://www.mkdocs.org/) to build GitHub-Pages from Markdown.

Clone this repository locally, and cd into it:

```console
git clone https://github.com/bird-house/bird-house.github.io
cd bird-house.github.io
```


Install `mkdocs`, for example with `conda`:

```console
conda env create
conda activate birdhouse2
```

Now you can ask `mkdocs` to build the website:

```console
mkdocs build
mkdocs serve
```

Point your browser at http://127.0.0.1:8000/.

Edit the various parts, `mkdocs` should automatically rebuild and
refresh the pages when changes occur.

To stop serving the website, press **`Ctrl`**-`C` in your terminal.

## Deployment

Pull requests merged to the main branch are automatically deployed to the production website.

## Where to Edit?

You can edit the main page of the website by changing `index.md`.
It is written in [Markdown](https://guides.github.com/features/mastering-markdown/).

The site has other pages written in Markdown like `about.md`.

To customise the layout read the documentation of [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

