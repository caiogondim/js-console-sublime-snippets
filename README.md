# JavaScript Console snippets [![Build Status](https://secure.travis-ci.org/caiogondim/js-console-sublime-snippets.png?branch=master)](https://travis-ci.org/caiogondim/js-console-sublime-snippets)

<img src="https://raw.github.com/caiogondim/js-console-sublime-snippets/master/js-console-snippets-logo.png" alt="JS Console snippets" align="right" width="250" />

Snippets and Code completion for Sublime Text 2.
Works with JavaScript and CoffeeScript syntax.

To install through [Package Control](http://wbond.net/sublime_packages/package_control),
search for **JavaScript Console**. If you still don't have Package Control in Sublime Text, [go get it](http://wbond.net/sublime_packages/package_control/installation).
It's pure awesomeness. If you insist to not install it, you can download the package and
put it manually inside your `Pacakages` directory. It should work but will not update automatically.

You can get the documentation about each method in the [Firebug API documentation](http://getfirebug.com/wiki/index.php/Console_API)
or the [Chrome DevTools documentation](https://developers.google.com/chrome-developer-tools/docs/console).

## Snippets

Snippets are the fastest way to code.
To trigger a method of the [Console API](http://getfirebug.com/wiki/index.php/Console_API)
just put a `>` followed by it's name, like so:

![snippets](https://raw.github.com/caiogondim/js-console-sublime-snippets/master/snippets.gif)

`>log` expands to `console.log()`

`>info` expands to `console.info()`

You got the point.

## Code completion

If you're more into code completion, we got you covered too.
Just start typing the name of the method and the methods should start appearing.

![console](https://raw.github.com/caiogondim/js-console-sublime-snippets/master/console.png)

## Methods covered

- console.assert()
- console.clear()
- console.count()
- console.debug()
- console.dir()
- console.dirxml()
- console.error()
- console.exception()
- console.group()
- console.groupCollapsed()
- console.groupEnd()
- console.info()
- console.log()
- console.profile()
- console.profileEnd()
- console.tab()
- console.time()
- console.timeEnd()
- console.timeStamp()
- console.warn()

## Changelog

- 0.2: added support for CoffeeScript
- 0.1: first release
