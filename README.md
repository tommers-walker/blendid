This is forked from blendid: https://github.com/vigetlabs/blendid<br>with a customised sass starter directory structure from:<br>
https://github.com/tommers-walker/sass-starter-flex<br>
which, in turn is forked from:<br>
  https://github.com/marcellegane/sass-starter-flex

# ![Blendid](https://raw.githubusercontent.com/vigetlabs/blendid/master/extras/blendid-logo.png)

[![Build Status](https://travis-ci.org/vigetlabs/blendid.svg?branch=static-server)](https://travis-ci.org/vigetlabs/blendid)
[![Stories in Ready](https://badge.waffle.io/vigetlabs/blendid.png?label=ready&title=Ready)](https://waffle.io/vigetlabs/blendid)

**Blendid** *(formerly known as Gulp Starter)* is a delicious stand-alone blend of tasks and build tools poured into [Gulp](http://gulpjs.com/) to form a full-featured modern asset pipeline. It can be used as-is as a static site builder, or can be configured and integrated into your own development environment and site or app structure.

## Quick start on a fresh project (empty directory)
```
yarn init
```
~~yarn add blendid~~
```
yarn add https://github.com/tommers-walker/blendid
yarn run blendid init
yarn run blendid
```

This will create default src and config files in your directory and start compiling and live-updating files! Try editing them and watch your browser auto-update!

## Documentation

[Full documentation is available on the Wiki](https://github.com/vigetlabs/blendid/wiki)

***

<a href="http://code.viget.com">
  <img src="http://code.viget.com/github-banner.png" alt="Code At Viget">
</a>

Visit [code.viget.com](http://code.viget.com) to see more projects from [Viget.](https://viget.com)

***

**Tip:** Typing four commands each time you start a project gets a bit tedious, so add some aliases to your bsh or zsh profile:

```
alias newblend="yarn init; yarn add https://github.com/tommers-walker/blendid; yarn run blendid -- init; yarn run blendid"
alias blend="yarn run blendid"
alias buildblend="yarn run blendid build"
```
