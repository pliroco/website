# The Pliro company website

A GitHub Pages (Jekyll) site.

## Requirements

1. [Ruby](https://www.ruby-lang.org/en/) (see [`.ruby-version`](https://github.com/pliroco/website/blob/main/.ruby-version) for exact version)
2. [Bundler](https://bundler.io/)

We recommend using [rbenv](https://github.com/rbenv/rbenv) to manage Ruby versions on your system.

## Setup

After cloning the repo, make sure you have the correct Ruby version installed. From within the repo, run:

```sh
rbenv versions
```

If the correct version isn't installed, you can use rbenv to install it:

```sh
rbenv install
```

Check if Bundler is installed:

```sh
gem list -i bundler
```

If not, install it:

```sh
gem install bundler
rbenv rehash
```

Install dependencies:

```sh
bundle install
```

## Starting the server

```sh
bundle exec jekyll serve
```

Now you should be able access the site on http://localhost:4000.
