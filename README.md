# Project Overview
 Simply open index.html and check the Jasmine test results. All should be succeed.

# Expected Results
9 specs, 0 failures
 * Jasmine__TopLevel__Suite
   * RSS Feeds
     - are defined
     - feed has a URL defined and that the URL is not empty
     - feed has a name defined and that the name is not empty
   * The menu
     - the menu element is hidden by default
     - the menu changes visibility when the menu icon is clicked
   * Initial Entries
     - loadFeed is called
     - loadFeed loads at least a single entry element
   * New Feed Selection
     - loadFeed function is called for a new feed load
     - new feed is loaded by the loadFeed function
