React intro (Dashboard App)

This directory contains a series of tasks for creating and modifying a React-based dashboard application. The application provides a simple dashboard interface for a school, displaying important information and notifications.
Task 0: Basic Application

In this task, you will create a basic React app named "dashboard" using create-react-app in the task_0 directory. The app should include the Holberton logo and a favicon. Unused files, such as service-worker, index.css, and App.test.js, should be removed. The main components of the app are as follows:
App.js

The App.js file in task_0/dashboard/src should contain the following components:

    A header div with the class App-header, containing the Holberton logo and an h1 element with the text "School dashboard."
    A body div with the class App-body, containing at least one paragraph with the text "Login to access the full dashboard."
    A footer div with the class App-footer, containing at least one paragraph with the text "Copyright 2020 - Holberton School."

Task 1: Embedding Expressions, Functions

In this task, you will build upon the code from the previous task and create some utility functions and components. The changes are as follows:
utils.js

    Create a function named getFullYear that will return the current year.
    Create a function named getFooterCopy(isIndex) that accepts a boolean argument isIndex. When isIndex is true, the function should return "Holberton School," and when isIndex is false, it should return "Holberton School main dashboard."

Notifications.js

    Create a new component Notifications in the file task_1/dashboard/src/Notifications.js.
    The Notifications component should return a div with the class Notifications and contain a paragraph with the text "Here is the list of notifications."

Notifications.css

    Style the Notifications class by adding a border and padding around the div.

Task 2: Modify the App and Notifications

In this task, you will further modify the App and Notifications components. The changes are as follows:
App.js

    Under the paragraph "Login to access the full dashboard," add a label and input for email and password.
    Clicking on a label should select the corresponding input.
    Add a button element with the text "OK."

utils.js

    Create a function named getLatestNotification that returns the following string: <strong>Urgent requirement</strong> - complete by EOD.

Notifications.js

    Add a button element with inline styling (without using the CSS file) on the right side of the notifications box. The button should have an aria-label of "Close."
    When the user clicks on the button, it should log to the console: "Close button has been clicked."
    Add an img element as a child of the button, importing the close-icon.png image.
    After the paragraph, add an unordered list with three items:
        The first item should have a default priority and say "New course available."
        The second item should have an urgent priority and say "New resume available."
        The third item should display the content of getLatestNotification using dangerouslySetInnerHTML.

Notifications.css

    Style the notification priorities using their data attribute: set the color of default items to blue and the color of urgent items to red.

Task 3: Create Basic Tests

In this task, you will write basic tests for the functions and components of the application. The tests are as follows:
utils.test.js

    Write a test to check that the function getFullYear returns the correct year.
    Write a test to check that getFooterCopy returns the correct string when the argument is true or false.
    Write a test to check the returned string for getLatestNotification.

App.test.js

    Create four tests:
        Test that App renders without crashing.
        Verify that App renders a div with the class App-header.
        Verify that App renders a div with the class App-body.
        Verify that App renders a div with the class App-footer.

Notifications.test.js

    Create three tests:
        Test that Notifications renders without crashing.
        Verify that Notifications renders three list items.
        Verify that Notifications renders the text "Here is the list of notifications."

Task 4: Install Enzyme

In this task, you will install Enzyme and set up the necessary configurations. The steps are as follows:

    Install Enzyme with npm.
    Create a file named setupTests.js and configure the adapter for Enzyme.

Task 5: Create React Tests

In this task, you will create React tests for the components of the application. The tests are as follows:
App.test.js

    Create four tests:
        Test that App renders without crashing.
        Verify that App renders a div with the class App-header.
        Verify that App renders a div with the class App-body.
        Verify that App renders a div with the class App-footer.

Notifications.test.js

    Create three tests:
        Test that Notifications renders without crashing.
        Verify that Notifications renders three list items.
        Verify that Notifications renders the text "Here is the list of notifications."

Task 6: Deploy to GitHub Pages

In this task, you will deploy your application to GitHub Pages using the gh-pages branch and create-react-app. Ensure that your application works correctly when accessed via the GitHub URL.
Task 7: Create a Project Using Webpack

In this task, you will start a new npm project and set up a basic Webpack configuration. The steps are as follows:

    Set up a system to output a bundle.js file in a dist folder.
    Set up a dev server with hot reloading.
    Create a src folder containing your JavaScript code.
    Set up a simple HTML file in the dist folder that imports the bundle.js file.

Task 8: Install Babel

In this task, you will install Babel and configure it to support preset-env and preset-react. Additionally, you'll add a babel-loader to the Webpack configuration to support js and jsx files. All JavaScript and React code should be within the src folder.
Task 9: Reorganize the Files

In this task, you will reorganize the files in the project as follows:

    Move all files related to the App component to an App folder.
    Move all files related to the Notifications component to a Notifications folder.
    Move all utility functions to a utils folder.
    Place all assets in an assets folder.
    Set up the favicon.ico in the dist folder.
    Move the Webpack config file to a config folder if it isn't already.

Task 10: Install Babel

In this task, you will install Babel and configure it to support preset-env and preset-react. Additionally, you'll add a babel-loader to the Webpack configuration to support js and jsx files. All JavaScript and React code should be within the src folder.
Task 11: Reorganize the Files

In this task, you will reorganize the files in the project as follows:

    Move all files related to the App component to an App folder.
    Move all files related to the Notifications component to a Notifications folder.
    Move all utility functions to a utils folder.
    Place all assets in an assets folder.
    Set up the favicon.ico in the dist folder.
    Move the Webpack config file to a config folder if it isn't already.

Task 12: Create Basic Tests with Four Tests

In this task, you will create basic tests for the application using Jest. The tests are as follows:
utils.test.js

    Write a test to check that the function getFullYear returns the correct year.
    Write a test to check that getFooterCopy returns the correct string when the argument is true or false.
    Write a test to check the returned string for getLatestNotification.

App.test.js

    Create four tests:
        Test that App renders without crashing.
        Verify that App renders a div with the class App-header.
        Verify that App renders a div with the class App-body.
        Verify that App renders a div with the class App-footer.

Notifications.test.js

    Create three tests:
        Test that Notifications renders without crashing.
        Verify that Notifications renders three list items.
        Verify that Notifications renders the text "Here is the list of notifications."

utils.test.js

    Write a test to check that the function getFullYear returns the correct year.
    Write a test to check that getFooterCopy returns the correct string when the argument is true or false.
    Write a test to check the returned string for getLatestNotification.
