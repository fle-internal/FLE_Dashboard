FLE Dashboard
=============

This is a Node.js project for a dashboard system that will visualize cool data from our calendars, HipChat, GitHub etc. in our offices using [blessed](https://github.com/chjj/blessed) and [blessed-contrib](https://github.com/yaronn/blessed-contrib/). Dashboard 'system' because it may end up being more than just a command-line based dashboard that blessed and blessed-contrib are designed for.

We should aim to make this extensible later on. We should try and compartmentalize various API interactions so that we can connect them to not only our blessed-contrib (for now) but also other dashboard tools (in the future).

Contribute
----------

To work on this project, clone this repo into any folder and run `npm install` to set everything up. `dashboard.js` should run the blessed-contrib powered dashboard in your command line. Make sure you have Node.js installed.

To understand how the various widgets work, check out the documentation for [blessed](https://github.com/chjj/blessed/blob/master/README.md) and [blessed-contrib](https://github.com/yaronn/blessed-contrib/blob/master/README.md).
