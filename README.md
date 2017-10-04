# Feed Reader
-------------
This project is **a web-based application that reads RSS feeds**.
The code also includes [Jasmine](http://jasmine.github.io/) testing methods.
The program is testing the following functionalities:

## Install
----------
Download or clone project folder.
Open index.html in the main project directory by using a web browser that supports html5 and css3.
To successfully ran the application you will need an active internet connection

## The test
------------

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

## The application uses
-----------------------
Jasmine JavaScript 2.1.2 framework for testing
jQuery 2.1.1 JavaScript library
Handlebars 2.0.0 for creating templates


## License
----------
Copyright [2017] [Gabor Furesz]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
