# Welcome to Brackets! [![Build Status](https://travis-ci.org/brackets-cont/brackets.svg?branch=master)](https://travis-ci.org/brackets-cont/brackets)

Brackets is a modern open-source code editor for HTML, CSS, and JavaScript that's *built* in HTML, CSS, and JavaScript.

This is a fork of a [project](https://github.com/brackets-cont/brackets) that has been maintained by the community. We might change names in the future.

A lot of work needs to be done to make this fork become independent. Feel free to open a PR! Want to help coordinate the project itself? Check the projects tab ([here](https://github.com/brackets-cont/brackets/projects)).

## What makes Brackets different from other web code editors?

* **Tools shouldn't get in your way.** Instead of cluttering up your coding environment with lots of panels and icons, the Quick Edit UI in Brackets puts context-specific code and tools inline.
* **Brackets is in sync with your browser.** With Live Preview, Brackets works directly with your browser to push code edits instantly and jump back and forth between your real source code and the browser view.
* **Do it yourself.** Because Brackets is open source, and built with HTML, CSS, and JavaScript, you can [help build](https://github.com/brackets-cont/brackets/blob/master/CONTRIBUTING.md) the best code editor for the web.

Brackets may have reached version 1, but we're not stopping there. We have many feature ideas on our [trello board](http://bit.ly/BracketsTrelloBoard) that we're anxious to add and other innovative web development workflows that we're planning to build into Brackets. So take Brackets out for a spin and let us know how we can make it your favorite editor.

You can see some [screenshots of Brackets](https://github.com/brackets-cont/brackets/wiki/Brackets-Screenshots) on the wiki, [intro videos](http://www.youtube.com/user/CodeBrackets) on YouTube, and news on the [Brackets blog](http://blog.brackets.io/).

## How to install and run Brackets

### Download

Installers for the latest stable build for Mac and Windows can be [downloaded here](https://brackets-cont.github.io/).

### Usage

By default, Brackets opens a folder containing some simple "Getting Started" content. You can choose a different folder to edit using *File > Open Folder*.

Most of Brackets should be pretty self-explanatory, but for information on how to use its unique features, like Quick Edit and Live Preview, please read [How to Use Brackets](http://github.com/brackets-cont/brackets/wiki/How-to-Use-Brackets). Also, see the [release notes](http://github.com/brackets-cont/brackets/wiki/Release-Notes) for a list of new features and known issues in each build.

In addition to the core features built into Brackets, there is a large and growing community of developers building extensions that add all sorts of useful functionality. See the [Brackets Extension Registry](https://registry.brackets.io/) for a list of available extensions. For installation instructions, see the [extensions wiki page](https://github.com/brackets-cont/brackets/wiki/Brackets-Extensions).

### Need help?

Having problems starting Brackets the first time, or not sure how to use Brackets? Please review [Troubleshooting](https://github.com/brackets-cont/brackets/wiki/Troubleshooting), which helps you to fix common problems and find extra help if needed.

## Helping Brackets

### I found a bug!

If you found a repeatable bug, and [troubleshooting](https://github.com/brackets-cont/brackets/wiki/Troubleshooting) tips didn't help, then be sure to [search existing issues](https://github.com/brackets-cont/brackets/issues) first. Include steps to consistently reproduce the problem, actual vs. expected results, screenshots, and your OS and Brackets version number. Disable all extensions to verify the issue is a core Brackets bug. [Read more guidelines for filing good bugs.](https://github.com/brackets-cont/brackets/wiki/How-to-Report-an-Issue)

### I have a new suggestion, but don't know how to program!

For feature requests, please first check our [Trello board](http://bit.ly/BracketsBacklog) to see if it's already there; you can upvote it if so. If not, feel free to file it as an issue as above; we'll move it to the feature backlog for you.

### I want to help with the code!

Awesome! _There are lots of ways you can help._ First read [CONTRIBUTING.md](https://github.com/brackets-cont/brackets/blob/master/CONTRIBUTING.md), then learn how to [pull the repo and hack on Brackets](https://github.com/brackets-cont/brackets/wiki/How-to-Hack-on-Brackets).

The text editor inside Brackets is based on [CodeMirror](http://github.com/codemirror/CodeMirror)—thanks to Marijn for taking our pull requests, implementing feature requests, and fixing bugs! See [Notes on CodeMirror](https://github.com/brackets-cont/brackets/wiki/Notes-on-CodeMirror) for info on how we're using CodeMirror.

Although Brackets is built in HTML/CSS/JS, it currently runs as a desktop application in a thin native shell, so that it can access your local files. (If you just try to open the index.html file in a browser, it won't work yet.) The native shell for Brackets lives in a separate repo, [brackets-cont/brackets-shell](https://github.com/brackets-cont/brackets-shell/).

## I want to keep track of how Brackets is doing!

Not sure you needed the exclamation point there, but we like your enthusiasm.

### What's Brackets working on next?

* In our [feature backlog](http://bit.ly/BracketsBacklog), the columns to the right (starting from "Development") list the features that we're currently working on. "Ready" shows what we'll be working on next.
* Watch our [GitHub activity stream](https://github.com/brackets-cont/brackets/pulse).
* The entire development process is outlined in the [Developer Guide](https://github.com/brackets-cont/brackets/wiki/Brackets-Developers-Guide).

### Contact info

* **Matrix:** [@brackets-cont:matrix.org](https://matrix.to/#/#brackets-cont:matrix.org)
* **Discord:** [Brackets Discord Server](https://discord.gg/rBpTBPttca)
* **Reddit:** [r/Brackets](https://www.reddit.com/r/brackets/)

---

Please note that this project is released with a [Contributor Code of Conduct](https://github.com/brackets-cont/brackets/blob/master/CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.
