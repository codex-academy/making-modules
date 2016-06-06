# Making Modules

Brief guide of how to make new codeX modules in a consistent way.

# 1. Make a skeleton for your content.

We use [generator-codex-skellington](https://github.com/codex-academy/generator-codex-skellington) to scaffold out new modules. It's a [Yeoman](http://yeoman.io/) generator that asks you a few questions, then copies a bunch of files for you.

1. Install Yeoman globally using npm: `npm install -g yo`.
2. Install the generator globally using npm: `npm install -g generator-codex-skellington`.
3. In your new folder, run the generator using Yeoman: `yo codex-skellington` and answer the questions it asks.

# 2. Fill in your content.

All the codeX docs sites use [Jekyll](http://jekyllrb.com/) and are published using [GitHub Pages](https://pages.github.com/).

1. [Install Jekyll](https://jekyllrb.com/docs/installation/).
    * You'll need to install Ruby and RubyGems if you don't have them already. You can check if Ruby is installed by running `ruby --version`. You can check if RubyGems is installed by running `gem --version`.
2. Run Jekyll in your new folder: `jekyll serve`.

# 3. Check your content.

We want our docs to be consistent and correct, so we use an automated tool to check for some common things.

1. Install [retext-codex-standard](https://github.com/codex-academy/retext-codex-standard) globally using npm: `npm install -g retext-codex-standard`.
2. Check your content by running: `retext-codex-standard`. The output will give you a list of things that don't match the standard (with their file names and positions).
