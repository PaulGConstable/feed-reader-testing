# Project Overview

Here is my JavaScript feedreader app tested using [Jasmine](http://jasmine.github.io/) for Project 6 of the [Udacity Front-End Web Developer Nanodegree] (https://www.udacity.com/course/nd001).

In this project we were given a web-based application that reads RSS feeds. The developer had already included Jasmine in their files, but no tests had been added.

Tests are important tool for any developer company and with that in mind I wrote a number of tests against a pre-existing application.

**The Aim** was to test the underlying business logic of the application as well as event handling and DOM manipulation. Also, to create tests that are comprehensive enough to test the app functionality.

## Udacity Course Studied:

* [JavaScript Testing](https://www.udacity.com/course/ud549)

### Running the Tests:

To run the tests, clone it from my github account:

-  Git clone https://github.com/PaulGConstable/feed-reader-testing.git

- Then open index.html in your browser.

The Jasmine spec results will show at the bottom of the window.

### Results:

- All required tests pass and are comprehensive enough to test the app.

### Tests Undertaken

1. Write a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
2. Write a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
3. Write a new test suite named "The menu".
4. Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
5. Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
6. Write a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container. Remember, loadFeed() is asynchronous so this test wil require the use of Jasmine's beforeEach and asynchronous done() function.
7. Write a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes. Remember, loadFeed() is asynchronous.
8. When complete - all of the tests should pass.

### Bibliography

- [JavaScript Testing](https://www.udacity.com/course/ud549)
- [Jasmine](http://jasmine.github.io/)
- [Udacity Style
  Guide](http://udacity.github.io/frontend-nanodegree-styleguide/javascript.html)
- [Udacity Discussion Forum thread for load feeds] (https://discussions.udacity.com/t/step-16-write-a-test-that-ensures-when-a-new-feed-is-loaded-by-the-loadfeed-function-that-the-content-actually-changes/20810)

