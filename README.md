[![License]][url: License] [![Semver]][url: Semver] [![Gittip]][url: Gittip]

# [**L**BNF] <br/> for [Sublime Text]

> Provides syntax (highlighting) in [Sublime Text] for the [**L**BNF] \(**Labeled** [Backus Naur Form]) formalism. LBNF is primarily used by [bnfc].

## Requirements

[Sublime Text] 3. Version 2 is not supported.

## Getting Started

### 1. Installation

#### Package Control

If you already have [Package Control] installed in Sublime Text:

* Select "Install Package" from the Command Palette:
    + <kbd>Ctrl+Shift+P</kbd> on Windows and Linux
    + <kbd>⇧⌘P</kbd> on OS X
* Search for "**LBNF**" and hit <kbd>ENTER</kbd>.

#### Manual Installation

Go to `Preferences -> Browse Packages`, and then either download and unzip this plugin into that directory, or:

```shell
git clone https://github.com/centril/sublime-lbnf-syntax.git "sublime-lbnf-syntax"
```

### 2. Set syntax as default

Optionally, make sure that `.cf` files are shown with this syntax.
If not, set `LBNF` as default for `.cf` files.

## Sneak peak

![screenshot: test.cf]
> Sneak peak of highlighting [`test.cf`] with the [Monocyanide ColorScheme] theme, or [Cyanide Theme].

## Changelog

See the **[messages folder][CHANGES]**.

## Bugs / Issues / Feature requests / Contribution

Want to contribute? Great stuff! Please use the issue system that github provides to report bugs/issues or request an enhancement. Pull requests are also more than welcome.

## Author

**Mazdak Farrokhzad / Centril [&lt;twingoow@gmail.com&gt;]**

[![twitter][twitter_image]][twitter] [![github][github_image]][github] [![facebook][facebook_image]][facebook]

## Copyright & License

Licensed under the **[MIT License]**.
Copyright (c) 2016 Mazdak Farrokhzad.

<!-- references -->

[Gittip]: http://img.shields.io/gittip/Centril.svg?style=flat
[url: Gittip]: https://www.gittip.com/Centril/
[License]: http://img.shields.io/badge/license-MIT-blue.svg?style=flat
[url: License]: LICENSE.md
[Semver]: http://img.shields.io/badge/semver-2.0.0-blue.svg?style=flat
[url: Semver]: http://semver.org/spec/v2.0.0.html

[**L**BNF]: https://github.com/BNFC/bnfc/blob/master/docs/lbnf.rst
[bnfc]: https://github.com/BNFC/bnfc
[Backus Naur Form]: https://en.wikipedia.org/wiki/Backus%E2%80%93Naur_form

[screenshot: test.cf]: https://cdn.pbrd.co/images/mM41gWVDR.png "Sneak peak of highlighting of text.cf"
[`test.cf`]: https://github.com/Centril/sublime-lbnf-syntax/blob/master/test.cf

[Sublime Text]: http://www.sublimetext.com/
[Package Control]: http://wbond.net/sublime_packages/package_control/

[Monocyanide ColorScheme]: https://github.com/centril/sublime-monocyanide-colorscheme
[Cyanide Theme]: https://github.com/lefoy/cyanide-theme

[twitter]: http://twitter.com/CenoRIX
[twitter_image]: http://cdn.flaticon.com/png/128/8800.png
[github]: https://github.com/centril
[github_image]: http://cdn.flaticon.com/png/128/25231.png
[facebook]: https://www.facebook.com/Centril
[facebook_image]: http://cdn.flaticon.com/png/128/33702.png
[&lt;twingoow@gmail.com&gt;]: mailto:twingoow@gmail.com

[CHANGES]: messages/
[MIT License]: LICENSE.md

<!-- references -->