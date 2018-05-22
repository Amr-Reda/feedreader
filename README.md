# Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


# The Contained Tests

- test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
- test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
- test suite named `"The menu"`.
- test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
- test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
- test suite named `"Initial Entries"`.
- test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
- test suite named `"New Feed Selection"`.
- test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
- No test is dependent on the results of another.
