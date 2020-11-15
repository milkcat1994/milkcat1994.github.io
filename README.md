# [Lone Wolf Theme Jekyll][1]

[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://github.com/manid2/lone-wolf-theme/blob/master/LICENSE)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%203.8-blue.svg)][jekyll]
[![Ruby gem](https://badge.fury.io/rb/lone-wolf-theme.svg)](https://rubygems.org/gems/lone-wolf-theme/)
[![Build Status](https://travis-ci.com/manid2/lone-wolf-theme.svg?branch=master)](https://travis-ci.com/manid2/lone-wolf-theme)

A simple [bootstrap][bs4] based jekyll theme.

It uses

- [github-pages compatible gems][gh-gems]
- [bootswatch wrappers][bootswatch]
- [animate.css][ani-css].

## Who uses it

- [Lone wolf theme docs][1]
- [Me, manid2][2]

## Installation

### Using remote theme

Easiest way to use the theme if you dont want to make changes to the theme's
code.

- Add `remote_theme    : "manid2/lone-wolf-theme"` to your `_config.yml` file.

### By forking the theme repository

If you want to make changes to the code and to truly own the site.
Follow the blog on [smashing magazine][sm-gh-pages] to learn about this method.

### As a ruby gem

When you want to host the site on any server other than the github pages
and also to make use of plenty of jekyll plugins.

- Add `gem "lone-wolf-theme"` to your `Gemfile`.
- Update bundled gems by using `bundle` command.
- Add `theme    : "lone-wolf-theme"` to your `_config.yml`.

## Run in Local

### First

Ruby+Devkit Install

### Start Command Prompt with Ruby

```
gem install jekyll
gem install minima
gem install bundler
gem install jekyll-feed
gem install tzinfo-data
gem kramdown-parser-gfm

chcp 65001
bundle exec jekyll serve
```

## ERROR

#### Dependency Error: Yikes! It looks like you don't have kramdown-parser-gfm or one of its dependencies installed.
```
1. go to gem file add  gem "kramdown-parser-gfm"

2. open terminal and give command 'bundle isntall'
```

## Contribution

Use the link to learn how to [contribute][3] to LWT.

<!-- Links in the post -->
[jekyll]: https://jekyllrb.com/
[bs4]: https://getbootstrap.com/
[bootswatch]: https://bootswatch.com/
[gh-gems]: https://pages.github.com/versions/
[ani-css]: https://daneden.github.io/animate.css/
[sm-gh-pages]: https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/

[1]: https://manid2.github.io/lone-wolf-theme/
[2]: https://manid2.github.io/
[3]: https://manid2.github.io/lone-wolf-theme/contribute/
