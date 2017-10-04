# Project Overview

This project is **a web-based application that reads RSS feeds**.
The code also includes [Jasmine](http://jasmine.github.io/) testing methods.
The program is testing the following functionalities:

## RSS Feeds

### are defined
This test checks it tests to make sure that the `allFeeds` variable has been defined and that it is not empty.

### URLs are defined
This test loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.

### have a name
This test loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.

## The menu

### is hidden
This test ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.

### changes on click
This test ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.

## Initial Entries

### feed contains minimum 1 entry element
This test ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.

## New Feed Selection

### content actually changes
This test ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
Implemented error handling for undefined variables.
