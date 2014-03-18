# [sublime-railscasts-extended](https://github.com/jzelenkov/sublime-railscasts-extended)

> Extends original Railscasts theme with additional syntax highlighting for Markdown, LESS, HTML, Handlebars and more.

This theme attempts to add all the good things found in [sublime-monokai-extended](https://github.com/jonschlinkert/sublime-monokai-extended) theme by Jon Schlinkert to the original [TextMate Railscasts theme](https://github.com/ryanb/textmate-themes) by Ryan Bates.

This theme supports all of the color keys found in Monokai and Monokai Extended themes. This improves the functionality of the syntax highlighting plugins.

All of the values set in this theme were analyzed first. No global search and replace was performed.


#### [Jump to Examples ↓](#examples)

## Getting Started

### 1. Installation

#### Package Control

If you already have [Package Control](http://wbond.net/sublime_packages/package_control/) installed in Sublime Text:

* Select "Install Package" from the Command Palette: <kbd>Ctrl+Shift+P</kbd> on Windows and Linux or <kbd>⇧⌘P</kbd> on OS X
* Search for "**Railscasts Extended**" and click <kbd>enter</kbd>.

#### Manual Installation

Go to `Preferences -> Browse Packages`, and then either download and unzip this plugin into that directory, or:

``` bash
git clone https://github.com/jzelenkov/sublime-railscasts-extended.git "sublime-railscasts-extended"
```

### 2. Switch Themes

Then inside Sublime Text, go to `Preferences -> Color Scheme -> User -> Railscasts Extended`.


## Railscasts Enhancements

Adds scopes, support and/or improves styling for:

* [GitGutter](https://github.com/jisaacks/GitGutter)
* `Makefile`
* `HTML: Doctype/XML Processing`
* `HTML: Comment Block`
* `HTML: Script`
* `HTML: Style`
* `HTML: Text`
* `HTML: Attribute punctuation`
* `HTML: Attributes`
* `HTML: Quotation Marks`
* `HTML: Tag`
* `HTML: style`
* `HTML: Styles`
* `HTML: {}`
* `HTML: Tags punctuation`
* `Handlebars: Variable` (To highlight Handlebars, install the [Handlebars](https://github.com/daaain/Handlebars) language package for Sublime Text)
* `Handlebars: Constant`
* `CSS: Selector`
* `CSS: Tag Name`
* `CSS: @import`
* `CSS: @at-rule`
* `CSS: #Id`
* `CSS: .class`
* `CSS: Property Name`
* `CSS: Property Value`
* `CSS: Standard Value`
* `CSS: Additional Constants`
* `CSS: Numeric Value`
* `CSS: Constructor Argument`
* `CSS: !Important`
* `CSS: {}`
* `CSS: Tag Punctuation`
* `CSS: : ,`
* `CSS :pseudo`
* `LESS: variables`
* `LESS: mixins`
* `LESS: extend`
* `js: function name`
* `js: storage type`
* `js: source`
* `js: function`
* `js: numeric constant`
* `js: []`
* `js: ()`
* `js: {}`
* `JSON string`
* `diff.range`
* `markdown: plain` (Also install [sublime-markdown-extended](https://github.com/jonschlinkert/sublime-markdown-extended) for additional features.)
* `markdown: raw inline`
* `markdown: linebreak`
* `markdown: heading`
* `markdown: italic`
* `markdown: bold`
* `markdown: underline`
* `markdown: blockquote`
* `markdown: quote`
* `markdown: link`
* `markdown: raw block`
* `markdown: fenced code block`
* `markdown: fenced language`
* `markdown: raw block fenced`
* `markdown: list items punctuation`
* `markdown: separator`
* `markdown: table`


## Examples

### Markdown

![railscasts-001-md-before](https://f.cloud.github.com/assets/205659/2443257/953bc540-ae31-11e3-9bc5-3f963c17f5a5.png)

![railscasts-002-md-after](https://f.cloud.github.com/assets/205659/2443262/a034d8a6-ae31-11e3-84d0-5a1cae8ae2b6.png)


### CSS

> The following improvements apply to both CSS and LESS.

![railscasts-003-css-before](https://f.cloud.github.com/assets/205659/2443263/a84dec58-ae31-11e3-8532-d59a8e1fd527.png)

![railscasts-004-css-after](https://f.cloud.github.com/assets/205659/2443264/a868faa2-ae31-11e3-9e37-2d7b81a24fb9.png)


### GitGutter

Intuitive `colors`

	new => green
	modified => yellow
	removed => red


## Author of the extended version

__Jev Zelenkov__

* [http://twitter.com/jzelenkov](http://twitter.com/jzelenkov)
* [http://github.com/jzelenkov](http://github.com/jzelenkov)


## Special thanks

> To [Jon Schlinkert](https://github.com/jonschlinkert) author of the original sublime-monokai-extended theme for inspiring me to do the same for the Railscasts theme.

<br/>

> To [Troy Murray](https://github.com/tdm00) for adding the original Railscasts theme to Sublime Package Control.


## Copyright and license

Copyright (c) 2014 Jev Zelenkov <br/>
Copyright (c) 2008 Ryan Bates


[License](LICENSE)
