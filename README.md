# technotes

Builds every time you push a change to the main branch.

Uses the Github Action [Deploy MkDocs](https://github.com/marketplace/actions/deploy-mkdocs) to build the page and put the build artifacts to [gh-pages](https://github.com/MaxStroh/technotes/tree/gh-pages) branch. Afterwards [github pages](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages) is used to host the page under: [**https://maxstroh.github.io/technotes**](https://maxstroh.github.io/technotes).

## Install

``sudo pip3 install mkdocs``

``sudo pip3 install mkdocs-material``

sudo might be necessary to add mkdocs on the path. If you want to change color or the navigation refer to [mkdocs martial setup guide](https://squidfunk.github.io/mkdocs-material/setup/changing-the-colors/).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.
* `mkdocs gh-deploy --clean` - Builds the site and push the generated artefacts to gh-pages branch of the repo

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
