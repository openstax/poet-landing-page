# POET landing page

This repository contains the code for the [Jekyll](https://jekyllrb.com/) based site at [https://poet.openstax.org](https://poet.openstax.org). When files in the `main` branch of this repo are modified, the site will be automatically updated in at most 20 minutes (if there is an error building the site, you [should receive an email](https://docs.github.com/en/github/working-with-github-pages/about-jekyll-build-errors-for-github-pages-sites)). The content for the main landing page is broken down across:

* [index.md](index.md) - The main list of books and corresponding [gitpod.io](https://gitpod.io) links.
* [tools.md](tools.md) - Documentation on getting started, useful links, etc.

## Developing and testing the site locally

You can clone this repository and test changes using the following steps:

```bash
$ bundle install
$ bundle exec jekyll serve
```

After running the above, you should be able to browse to [http://localhost:4000/](http://localhost:4000/). Conversely, if you just want to generate and inspect the static content you can run:

```bash
$ bundle exec jekyll build
```

The generated content can then be found in `./_site`.
