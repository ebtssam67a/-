
#### Install
[GitHub]  https://github.com/udacity/ud549)
[GitHub]  https://github.com/ebtssam67a/feedreader.git)

# Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.




## What will I learn?

i learnd how to use Jasmine to write a number of tests against a pre-existing application. These  test the underlying business logic of the application as well as the event handling and DOM manipulation.

When you're all finished, write a `README` file detailing all steps required to successfully run the application. If you have added additional tests, provide documentation for what these future features are and what the tests are checking for.



# detailing all steps 

in first test named "RSS Feeds" - it tests to make sure that the 

 * allFeeds variable has been defined and that it is not empty .. 

 * loops through each feed and make sure that has a URL defined and that the URL is not empty..   

 * loops through each feed and make sure that has a NAME defined and that the NAME is not empty..

 in second test named "The menu"  - it tests to make sure that 

 * ensures the menu element is hidden by default

 * test that ensures the menu change visibility when the menu icon is clicked
   have two expectations: does the menu display when clicked and does it hide when clicked again.
in third test named "Initial Entries" - it tests to make sure that the

 * ensures when the loadFeed function is called and completes its work 
in fourth test named "New Feed Selection" - it tests to make sure that the

* when a new feed is loaded by the loadFeed function that the content actually changes. 
Remember, loadFeed() is asynchronous.
 

