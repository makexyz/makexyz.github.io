---
layout: post
current: post
cover: https://i.ibb.co/n6t2Nhv/px-vs-dp.jpg
navigation: True
title: About Bundler
date: 2018-05-12 10:18:00
tags: jekyll
class: post-template
subclass: 'post'
logo: https://s-hacker.info/img/bundler.png
author: deadblox
---

`gem install bundler` installs the bundler gem through RubyGems. You only need to install it once - not every time you create a new Jekyll project. Here are some additional details:

`bundler` is a gem that manages other Ruby gems. It makes sure your gems and gem versions are compatible, and that you have all necessary dependencies each gem requires.

The `Gemfile` and `Gemfile.lock` files inform `Bundler` about the gem requirements in your site. If your site doesn’t have these Gemfiles, you can omit `bundle exec` and just `run jekyll serve`.

When you run `bundle exec jekyll serve`, `Bundler` uses the gems and versions as specified in `Gemfile.lock` to ensure your Jekyll site builds with no compatibility or dependency conflicts.

For more information about how to use `Bundler` in your Jekyll project, this tutorial should provide answers to the most common questions and explain how to get up and running quickly.