<!--rose canlas
    README.md
-->

# **Feed Reader Testing**

This project is a web-based application that reads RSS feed. This application uses Jasmine, a Behavior Driven Development testing framework for JavaScript. A process that initially test the code to make sure it passes before writing the application code. These will test the underlying business logic of the application as well as the event handling and DOM manipulation.

## Before you start
   
   - Download the zip file then run the index.html

## In completing the project I..
    
   **Review the [Feed Reader Testing Project Rubric](https://www.udacity.com/course/javascript-testing--ud549)**

  1. Took the [JavaScript Testing course]. (https://www.udacity.com/course/javascript-testing--ud549)

  2. [Downloaded] the required project assets. (https://github.com/udacity/frontend-nanodegree-feedreader)

  3. **Reviewed** the functionality of the application within your browser.

  4. Explored the application's _HTML_ (**./index.html**), _CSS_ (**./css/style.css**)and _JavaScript_ (**./js/app.js**) to gain an understanding of how it works.

  5. Explored the _Jasmine_ spec file in **./jasmine/spec/feedreader.js** and reviewed the [Jasmine documentation]. (https://jasmine.github.io/)

  6. Edited the `allFeeds` variable in **./jasmine/spec/feedreader.js** to make the provided test fail and see how _Jasmine_ visualizes this failure in your application.

  7. Returned the `allFeeds` variable to a passing state.

  8. Wrote a test that uses `for loops` through each feed in the `allFeeds` object and ensures it has a *URL* defined and that the URL is not empty.

  9. Wrote a test that uses `for loops` through each feed in the `allFeeds` object and ensures it has a *name* defined and that the name is not empty.

 10. Wrote a new test suite named `"The menu"`.

 11. Wrote a test that ensures the menu element is *hidden* by default. Analyzed the _HTML_ and the _CSS_ to determine how we're performing the hiding/showing of the menu element.

 12. Wrote a test that ensures the menu changes *visibility* when the menu icon is clicked. This test have two expectations: does the menu display when clicked and does it hide when clicked again.

 13. Wrote a test suite named `"Initial Entries"`.

 14. Wrote a test that ensures when the *loadFeed* function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.

 15. Wrote a test suite named `"New Feed Selection"`.

 16. Wrote a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.

 17. _No test_ are be dependent on the results of another.

 18. _Callbacks_ are be used to ensure that feeds are loaded before they are tested.

 19. Implemented error handling for undefined variables and out-of-bound array access.

 20. When completed - **_all of tests passed_**.

 21. Wrote a `README` file detailing all steps required to successfully run the application. 

## License
