React State Management Project

This directory contains a series of tasks aimed at enhancing your understanding of state management in React applications.
Task 0: Adding Local State for Notifications

In this task, we'll build upon our modularized React application and start adding logic and state. The primary objective is to create a local state to manage the display of notifications.
Steps:

    Open the file task_0/dashboard/src/App/App.js.

    Modify the App component to include a local state variable displayDrawer.

    Define default state values for the state variable in the constructor of the App class.

    Implement the functions handleDisplayDrawer and handleHideDrawer to update the value of displayDrawer based on user interactions.

    Update the Notifications component import in task_0/dashboard/src/App/App.js to pass the displayDrawer prop using the local state.

    Pass the functions handleDisplayDrawer and handleHideDrawer as props to the Notifications component.

    Update the test suite for the App component in task_0/dashboard/src/App/App.test.js to ensure that the default state and the functions work as expected.

    Modify the Notifications component in task_0/dashboard/src/Notifications/Notifications.js to utilize the new props and interactions.

    Update the test suite for the Notifications component in task_0/dashboard/src/Notifications/Notifications.test.js to validate the functionality of the added interactions.

Tips:

    Remember to follow best practices when using React state, props, and components.
    Utilize setState to manage component state updates.
    Employ testing techniques using Enzyme to ensure your components work as intended.

Task 1: Controlled Components and State Callback

In this task, you will implement controlled components and a state callback mechanism within the Login component.
Steps:

    Open the file task_1/dashboard/src/Login/Login.js.

    Create a local state variable isLoggedIn within the Login component.

    Replace the submit button with an input element of type submit.

    Implement the function handleLoginSubmit to update the isLoggedIn state when the form is submitted.

    Modify the local state to include email and password fields.

    Implement the functions handleChangeEmail and handleChangePassword to update the respective state fields as the user types.

    Create a state variable enableSubmit and update it based on the contents of the email and password fields.

    Update the Submit button to be enabled only when the enableSubmit state is true.

    Update the tests for the Login component to validate the newly added features.

Tips:

    Utilize controlled components to manage form elements' state.
    Use state callbacks to efficiently update the state based on user interactions.
    Employ Enzyme's simulate method to test input changes and form submissions.

Task 2: Context

In this task, you will work with React Context to manage user authentication and interactions.
Steps:

    Open the file task_2/dashboard/src/App/AppContext.js.

    Create a React context that includes a default user object and a logOut function.

    Update the local state of the App component to include user data and the logOut function.

    Implement the logIn and logOut functions within the App component to manage user authentication.

    Refactor the Header component to utilize the ContextType API for accessing context data.

    Update the Header component to display a "Welcome" message and a logout link when the user is logged in.

    Implement tests to validate the changes made to the Header and App components.

Tips:

    Follow React's official documentation for working with Context.
    Use React.createContext to create a new Context instance.
    Employ the Context.Provider component to wrap components and share context data.
    Update your components to consume context data using the ContextType API.

Task 3: Context Consumer & Advanced State

In this task, you will further enhance your understanding of React Context and work with advanced state management techniques.
Steps:

    Update the Footer component to subscribe to context changes and display additional content when the user is logged in.

    Modify the App component to manage a list of notifications in its local state.

    Implement the markNotificationAsRead function within the App component to update the list of notifications.

    Pass the list of notifications and the markNotificationAsRead function to the Notifications component.

    Update the Notifications component to use the new function for marking notifications as read.

    Implement tests to ensure the correctness of the modifications made in this task.

Tips:

    Utilize React Hooks to manage state in functional components.
    Make use of the Context API to efficiently share data across components.
    Use state callbacks and controlled components to manage complex interactions.

Task 4: Introduction to React Hook

In this task, you will explore React Hooks by implementing a checkbox functionality within the CourseListRow component.
Steps:

    Open the file task_4/dashboard/src/CourseList/CourseListRow.js.

    Implement a new style named rowChecked with a background color of #e6e4e4.

    Add a checkbox element within the first cell of the row.

    Implement logic to apply the rowChecked style when the checkbox is checked.

Tips:

    Utilize React Hooks to manage state in functional components.
    Implement the useState hook to manage checkbox state.
    Employ conditional rendering to apply styles based on the checkbox state.