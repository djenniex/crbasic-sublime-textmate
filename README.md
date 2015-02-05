# crbasic-sublime-textmate

A [TextMate][textmate] _(and [Sublime Text][sublime])_ bundle for [CRBasic][crbasic].

## Overview

Provides basic syntax highlighting for CRBasic programs using TextMate. It currently has support for a limited set of datalogger instructions, but there is support for control syntax, sub routine and variable declarations, and other basic syntax.

Currently Campbell Scientific's CRBasic Editor is only available for Windows. I created this plugin so that Mac users could view and make basic edits to preexisting datalogger programs. It is not intended as a replacement for the CRBasic Editor.

## Installation
TextMate, and most editors that support TextMate bundles, allow the installation of bundles simply by extracting an archive or cloning the repository into the application's bundle directory. This bundle is no different. Below is a list of common bundle directories.


### Sublime Text
CRBasic can be installed in a variety of ways in Sublime Text:
* Through Package Control [http://wbond.net/sublime_packages/package_control](http://wbond.net/sublime_packages/package_control)

 * Open Package Control
 * Select 'Install Package'
 * Find and select 'CRBasic'

* By cloning this repository in Packages
		cd into your Packages folder
		git clone git@github.com:djenniex/crbasic-sublime-textmate.git .

* By downloading the files and placing them in a directory under Packages, such as CRBasic or User

 If you don't put the files in Packages/User (you *can*, but probably shouldn't), make sure they live in Packages/CRBasic.

### TextMate
    /Library/Application Support/TextMate/Bundles

### TextMate 2
You can install this bundle in TextMate 2 by opening the preferences and going to the bundles tab. After installation it will be automatically updated for you.

Credits
-------
CRBasic Syntax was originally created by [beerlington][beerlington]

Contributing
------------
* Fork the project.
* Use topic branch.
* Make pull request.

[sublime]: http://www.sublimetext.com/
[textmate]: http://macromates.com/
[crbasic]: http://www.campbellsci.com/
[beerlington]: https://github.com/beerlington/crbasic-textmate
