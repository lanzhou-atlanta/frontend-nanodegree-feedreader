# Testing Application-Feedreader using Jasmine
Wrote 7 specs against pre-existing application with Jasmine. 
## Jasmine document
https://jasmine.github.io/

## Steps to run the test
1. clone repository at https://github.com/lanzhou-atlanta/frontend-nanodegree-feedreader.git; open index.html in a browser;
2. run at github pages: https://lanzhou-atlanta.github.io/frontend-nanodegree-feedreader/#

## Tests implementation
1. a test suite "RSS feed"
- a spec to test allFeed array is defined and not empty;
- a spec that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
- a spec that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
2. a test suite named "The menu".
- a spec that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
- a spec that ensures the menu changes visibility when the menu icon is clicked. This test has two expectations: does the menu display when clicked and does it hide when clicked again.
3. a test suite named "Initial Entries".
- a spec that ensures when the loadFeed function is called and completes its work, there is at least a single .entryelement within the .feed container.
4. a test suite named "New Feed Selection".
- a spec that ensures when a new feed is loaded by the loadFeed function that the content actually changes.


