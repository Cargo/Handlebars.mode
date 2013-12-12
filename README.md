# Handlebars Coda Syntax Mode

[Coda 2](http://panic.com/coda) syntax mode for [Handlebars](http://handlebarsjs.com) and [Mustache](http://mustache.github.io) templates. Current features include:

* Handlebars and Mustache syntax highlighting within HTML documents, with support for inline styles and scripts
* Navigator symbols for sections and partials tags
* Custom bookmarks for the Code Navigator, e.g. `{{! !Bookmark }}`
* Autocomplete for Handlebars helpers and Mustache tags used throughout the current document

## Installation

#### Automatic, via Finder

Either *Clone in Desktop* or *Download ZIP*. Note that when downloading a ZIP you will need to first unzip, then, if necessary, rename the unzipped directory from `Handlebars.mode-branchname` to `Handlebars.mode`. Next, double-click `Handlebars.mode` or open it with Coda 2. When asked by Coda 2 if you want to install the mode, click *Install*.

#### Manual, via Terminal

Installing via Terminal with git has the added bonus of easily staying up-to-date. Open Terminal, run the commands below, and launch/restart Coda 2:

```bash
mkdir -p ~/Library/Application\ Support/Coda\ 2/Modes
cd ~/Library/Application\ Support/Coda\ 2/Modes
git clone https://github.com/Cargo/Handlebars.mode
```

Updating to the latest version `Handlebars.mode` can then be as simple as the following (don't forget to restart Coda 2 afterwards):

```bash
cd ~/Library/Application\ Support/Coda\ 2/Modes/Handlebars.mode
git pull
```

## License
```
Copyright 2013 Cargo Collective, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
