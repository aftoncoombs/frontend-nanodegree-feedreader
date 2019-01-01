# Project Overview

This is a Udacity course project on test suites using [Jasmine](http://jasmine.github.io/). It was completed for the Udacity Front End Web Development Nanodegree.

## Contents
- /css contains the style sheets for the page
- /fonts contains the fonts
- /jasmine/spec contains the tests
- /js contains the javascript for loading the feed
- index.html contains the main website

## Testing
/jasmine/spec/feedreader.js contains the Jasmine test suite. In order to use this, just run the index.html file in your browser. The test should appear at the bottom of the page.

Tests currently implemented:
- RSS feeds are defined
- RSS feeds have defined URL
- RSS feeds have defined names
- The menu is hidden by default
- The menu changes visibility when clicked
- Initial entries have at least one entry
- The news feed selection changes content when a new feed is loaded