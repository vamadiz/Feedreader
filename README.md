# Project Overview

Using Jasmine to test our RSS feed reader application.

To Run:

Making sure you have Jasmine installed on your machine, open the index.html file in the project folder.

Jasmine can be found here:
https://jasmine.github.io/index.html

This project tests for the following:

1. Loops through each feed in the allFeeds object and ensures each URL is defined and that the URL is not empty.
2. Loops through each feed in the allFeeds object and ensures each name is defined and that the name is not empty.
3. Ensures the menu element is hidden by default.
4. Ensures the menu changes visibility when the menu icon is clicked. Does the menu display when it is clicked and does it hide when clicked again?
5. Ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
6. Ensures when a new feed is loaded by the loadFeed function that the content changes.
