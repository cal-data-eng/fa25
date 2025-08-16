# DATA 101 Fall 2025 Website

[![Deploy Data 101 FA25 Website](https://github.com/cal-data-eng/fa25/actions/workflows/jekyll.yml/badge.svg)](https://github.com/cal-data-eng/fa25/actions/workflows/jekyll.yml)
[![Run all page tests](https://github.com/cal-data-eng/fa25/actions/workflows/rspec.yml/badge.svg)](https://github.com/cal-data-eng/fa25/actions/workflows/rspec.yml)

## Installation

Prerequisites:

- You have everything that [Jekyll requires](https://jekyllrb.com/docs/installation/)
- You have installed [Bundler](https://bundler.io/): Run `gem install jekyll bundler`

1. [Fork](https://github.com/berkeley-eecs/berkeley-class-site/fork) the repository.
2. Clone your fork (replace `YOUR_GITHUB_USERNAME` and `YOUR_REPO` accordingly).
```
git clone git@github.com:YOUR_GITHUB_USERNAME/YOUR_REPO.git
```
3. Install dependencies:
```
cd YOUR_REPO
bundle install
```

## Usage

To run the site locally, run:

```
bundle exec jekyll serve
```

## Deployment

The easiest way to deploy your site is with [GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll).

## License

[BSD 3-Clause](LICENSE)
