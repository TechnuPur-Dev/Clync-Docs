# Clync Readme




A  project created in Web using ReactJs. clone the project using the URL mentioned below:
```
https://github.com/TechnuPur-Dev/Clync.git
```
## Getting Started

This README file provides a detailed overview of the project's structure, explaining how it adheres to specific architectural patterns and outlining steps required to build and configure the project for React developers. It lists all dependencies and includes information about the recommended Node.js and npm versions to ensure a smooth development experience.

Within this README, developers will find explanations of design choices that guide the architecture, including state management strategies and dependency management patterns, aimed at establishing a scalable and maintainable codebase. The setup and installation instructions cover essential steps, making it straightforward to clone, configure, and run the project locally. The dependencies section lists all libraries and packages used in the project, along with versions and roles, so developers understand the third-party tools and frameworks involved.

Following this README allows developers to comprehensively understand the project’s structure, architectural decisions, and dependencies, empowering them to contribute effectively or extend the project as needed.

## System Requirements 

* React: Version 18.3.1
* Node.js: Version 18.0.0 or greater
* npm: Version 9.0.0 or greater


## How to Use 

**Step 1:**

Download or clone this repo by using the link below:

```
https://github.com/TechnuPur-Dev/Clync.git
```

**Step 2:**

Navigate to the project root and install the required dependencies by running the following command:

```
npm install
```

**Step 3:**

To start the development server and run the project locally:

```
 npm start 
```

To create an optimized production build, use the following command:

```
 npm run build
```

To run tests (if any are included), use: 

```
 npm test
```

## Managing Unwanted Files

At the root of your project, create or edit the .gitignore file to exclude commonly generated files and folders from version control. Add the following entries to ensure that dependencies, build artefacts and environment files are ignored:

```
**/node_modules
**/build
**/.env
```
This configuration ensures that any files matching these patterns won’t be tracked in version control (e.g., Git).

In Visual Studio Code, navigate to `Preferences` -> `Settings` and search for `Files:Exclude`. Add the following patterns:
```
**/node_modules
**/build
**/.env
```

## Features:

* User Authentication (Login, Registration, Logout)
* Dashboard Home
* Routing with react-router-dom
* Customizable Theme (Light/Dark Mode)
* API Integration with Axios
* Data Visualization with react-apex-charts
* Form Validation using react-hook-form
* User Notifications with react-toastify
* Responsive Design with react-bootstrap
* Role-based Access Control
* Date and Time Management with moment and react-datepicker

### Libraries & Tools Used
Following tools and libraries are used in this project 

* @emotion/react

Version: ^11.11.4

Description: Provides a flexible styling solution for React components using Emotion.

Link: https://pub.dev/packages/get 
* connectivity_plus 

Version: ^6.0.5 

Description: Provides tools to check network connectivity status. 

Link: https://www.npmjs.com/package/@emotion/react 
* @emotion/styled

Version: ^11.11.5

Description: Styled component library for React using Emotion.

Link: https://www.npmjs.com/package/@emotion/styled
* @mui/material 

Version: ^5.15.17 

Description: Material UI library for React, providing a set of accessible and customizable UI components.

Link: https://www.npmjs.com/package/@mui/material
* @reduxjs/toolkit

Version: ^2.2.3 

Description: A Redux library that simplifies state management and enhances development efficiency.

Link: https://www.npmjs.com/package/@reduxjs/toolkit
* Axios 

Version: ^1.6.8

Description: Promise-based HTTP client for making network requests.

Link: https://www.npmjs.com/package/axios
* react-router-dom 

Version: ^6.21.3

Description: Declarative routing library for React applications to manage navigation and URL handling. 

Link: https://www.npmjs.com/package/react-router-dom
* react-redux 

Version: ^9.1.1

Description: Official React bindings for Redux, enabling state management in React apps. 

Link: https://www.npmjs.com/package/react-redux
* React-toastify

Version: ^10.0.5

Description: Provides toasts and notifications in React applications. 

Link: https://www.npmjs.com/package/react-toastify
* redux-persist 

Version: ^6.0.0

Description: A library to persist and rehydrate Redux state between sessions. 

Link: https://www.npmjs.com/package/redux-persist
* React-datepicker

Version: ^6.9.0

Description: A React component for date-picking functionality with customizable options.

Link: https://www.npmjs.com/package/react-datepicker 
* react-select 

Version: ^5.8.0 

Description: A flexible and customizable dropdown component for React.

Link: https://www.npmjs.com/package/react-select
* react-bootstrap

Version: ^2.10.2

Description: A popular React component library that integrates Bootstrap with React.

Link: https://www.npmjs.com/package/react-bootstrap
* react-calendar 

Version: ^5.0.0

Description: A customizable calendar component for React apps. 

Link: https://www.npmjs.com/package/react-calendar 
* react-qr-code

Version: ^2.0.12 

Description: A React component for rendering QR codes.

Link: https://www.npmjs.com/package/react-qr-code
* react-apexcharts 

Version: ^1.4.1 

Description: React component for ApexCharts, a powerful charting library.

Link: https://www.npmjs.com/package/react-apexcharts 
* moment

Version: ^2.30.1

Description: A popular library for date and time manipulation in JavaScript.

Link: https://www.npmjs.com/package/moment
* redux 

Version: ^5.0.1

Description: A predictable state container for JavaScript apps.

Link: https://www.npmjs.com/package/redux
* sonner

   Version: ^1.4.41 

Description: A lightweight, flexible toast notification system for React.

Link: https://www.npmjs.com/package/sonner
* react-js-loader

Version: ^0.1.3

Description: A React component for displaying loading spinners and progress indicators.

Link: https://www.npmjs.com/package/react-js-loader
* web-vitals

Version: ^2.1.4

Description: A library to measure essential web performance metrics.

Link: https://www.npmjs.com/package/web-vitals


### Folder Structure
Here is the core folder structure which flutter provides.

```
CLYNC-ADMIN/
|- github
|- build
|- public
|- src
```

Here is the folder structure we have been using in this project

```
├── public                              - Public files accessible to the browser
├── src                                 - Main source folder for all React code
    ├── actions                           - Redux actions (if using Redux)
    ├── components                        - Reusable UI components (Buttons, Modals, etc.)
    ├── fonts                             - Font files used in the application
    ├── functions                         - Helper functions or utilities
    ├── img                               - All image assets (including GIFs, Icons)
    ├── interceptors                      - HTTP interceptors (for requests/responses, e.g., Axios interceptors)
    ├── redux                             - Redux-related files (reducers, store, actions)
    ├── routes                            - Contains routes or pages for navigation
    ├── utils                            - Utility functions or classes (e.g., formatting, validation)
    ├── views                            - Screen or page components (Home, Profile, etc.)
    ├── app.tsx                           - Main app component
    ├── app.css                          - Global styles for the app
    ├── index.tsx                           - Main app component (entry point)
    └── config.js                        - Centralized configuration file (API endpoints, etc.)
├── .env                                 - Environment variables (e.g., API URLs, authentication keys)
├── package.json                        - Node.js dependencies and scripts
├── .gitignore                          - Files to ignore in version control
├── node_modules                        - Project dependencies
└── README.md                           - Project documentation
```

Now, lets dive into the lib folder which has the main code for the application.

```
1- actions - Contains the Redux actions that are responsible for dispatching events to update the application’s state.
2- components - Holds reusable UI components, such as `Buttons`, `Modals`, `Card` components, etc., which are shared across multiple screens or views in the app.
3- fonts - This directory contains all the font files used in the application, typically `.woff`, `.woff2`, `.ttf`, or `.otf` files.
4- functions - Contains helper functions or utilities that are used across the application for various tasks like formatting, parsing, or calculations.
5- img - Contains all the image assets used in the app, including static images, GIFs, icons, or other visual resources.
6- interceptors - Contains HTTP interceptors, such as those used with `Axios`, for handling requests and responses globally (e.g., adding authorization headers, handling errors).
7- redux - This folder contains all the Redux-related files, including reducers, actions, and store configuration.
8- routes - Contains route definitions for navigation within the app, mapping paths to specific page components.
9- utils - Includes utility functions or classes that provide common functionality, such as validation, logging, or other reusable logic.
10- views - Contains the main screen or page components like `Home`, `Profile`, `Dashboard`, etc. These components represent the different views or sections of the app.
11- app.tsx - This is the root application component that ties everything together. It includes global configurations and renders the main layout of the app.
12- app.css - This file contains global styles or shared CSS that apply to the entire application.
13- index.tsx - The entry point for the React app, responsible for rendering the root component (`app.tsx`) into the DOM.
14- config.js - Centralized configuration file where API endpoints, authentication keys, or other global settings are defined.
```

### Actions

Actions are responsible for managing the data flow in your application. They handle side-effects, such as making API calls, and dispatch necessary updates to the Redux store or component state. Each action typically involves communication with an API and manages the state transitions based on the response:

```
src\actions
        └── action.js - Contains actions related to user login, including `LoginUser` for logging in users.
        └── actionStatistics.js - Contains actions for fetching statistics and graphs, such as:
            └── `getFinancialHubStatistics` - Fetches financial hub statistics.
            └── `getTransfersGraph` - Retrieves transfer-related graph data.
            └── `getSocialHubStatistics` - Fetches social hub statistics.
            └── `getSocialHubMembers` - Gets the list of members in the social hub.
            └── `getSocialHubTransactionData` - Retrieves social hub transaction data.
            └── `handleSearch` - Manages search functionality for different data types.
            └── `getUserHourlyOfToday` - Retrieves hourly data of users for the current day.
        └── homeAction.js - Contains actions related to the home screen, such as:
            └── `getHomeStatistics` - Fetches statistics for the home screen.
            └── `getTopTransfers` - Retrieves top transfers data for display.
            └── `handleSearch` - Manages search functionality for the home screen.
            └── `getGoogleAnalytics` - Fetches Google Analytics data for the home dashboard.
        └── legalTerms.js - Contains actions related to community and legal terms, such as:
            └── `aboutUs` - Fetches information about the community or company.
            └── `termsAndConditions` - Retrieves the terms and conditions for the application.
            └── `privacyPolicy` - Fetches privacy policy details for the app.
        └── transaction.js - Manages transaction-related actions, including:
            └── `getReasons` - Fetches the reasons for transactions.
            └── `createReason` - Creates a new transaction reason.
            └── `updateReason` - Updates an existing transaction reason.
            └── `deleteReason` - Deletes a transaction reason.
```
### Components

Components in this application represent reusable UI elements and specific sections of the user interface. Each component is designed to serve a specific function, whether it's displaying data, managing user interactions, or supporting layout structure. The components are organized based on functionality to make the structure intuitive and maintainable:

```
src\components
        └── aboutUs.js - Displays information about the company or platform.
        └── adminActivity.js - Shows recent activity performed by admins.
        └── allAdmins.js - Lists all admin users and their roles.
        └── avatar.js - Represents a user avatar component, allowing users to display and edit profile images.
        └── billingHistory.js - Displays the user's billing history and past transactions.
        └── billingInfo.js - Shows billing information, including payment details.
        └── blockedList.js - Lists all users who are currently blocked.
        └── cardStatus.js - Displays the current status of cards, such as active or inactive.
        └── circleDetail.js - Shows detailed information for a specific user circle.
        └── circles.js - Lists all user-created circles and provides options to manage them.
        └── colors.js - Allows customization of color themes or elements within the app.
        └── communityRules.js - Displays the platform's community guidelines and rules.
        └── createdPolls.js - Lists all polls created by the user and their statuses.
        └── customizeCalendar.js - Provides options for users to personalize calendar views.
        └── userGraph.js - Displays a graph or chart of user data, such as activity or statistics.
        └── deleteCirclePopup.js - Popup component for confirming the deletion of a circle.
        └── deleteNotePopup.js - Popup component for confirming the deletion of a note.
        └── deleteUserPopup.js - Popup component for confirming the deletion of a user account.
        └── friendListGraphs.js - Displays data visualization of the friend list, such as mutual friends or connections.
        └── navbar.js - Top navigation bar that includes links to main sections and quick actions.
        └── notesDetail.js - Shows detailed information for a selected note.
        └── overviewCard.js - A summary card that provides an overview of key statistics or information.
        └── reportCircle.js - Allows users to report a specific circle for inappropriate content or behavior.
        └── stats.js - Displays various statistics and data insights.
        └── transactions.js - Lists all user transactions with options to view, filter, or manage them.
```


### Redux

Redux is used to manage the application's state in a centralized way. Each component of Redux (provider, reducers, store, etc.) has a distinct role in managing, updating, and accessing state throughout the app. This folder structure keeps your Redux logic modular and organized:

```
src\redux
        └── provider - Wraps the application to give access to the Redux store in all components.
        └── reducers - Manages application state.
        └── store.js - Creates and configures the Redux store, applying middleware like Redux Thunk.
```

### Utils

Utility functions such as formatChatData and getCurrentMonthOption are general-purpose functions that perform specific tasks, like formatting data or fetching options. These functions can be imported wherever they are needed, providing cleaner and more readable code:

```
src\utils
    └── formatChatData.js - Formats raw chat data into a more user-friendly structure for display in the chat UI.
    └── getCurrentMonthOption.js - Returns the current month in a specific format or as an option for dropdowns or date selectors.
```

### Main

The App component serves as the root of the application. It initializes global styles and configurations, including Bootstrap and custom CSS.
import React , {useEffect , useState}from "react";
import "./App.css";
import OurRoutes from "./Routes/OurRoutes.tsx";
import "./../node_modules/bootstrap/dist/css/bootstrap.min.css";
import { ToastContainer } from "react-toastify";
import "react-toastify/dist/ReactToastify.css";
import { Toaster } from "sonner";
import { Spinner } from "react-bootstrap";

function App() {
  const [isLoading, setIsLoading] = useState(true);

  // Let create async method to fetch fake data
  useEffect(() => {
    const fakeDataFetch = () => {
      setTimeout(() => {
        setIsLoading(false);
      }, 2000);
    };

    fakeDataFetch();
  }, []);
  return isLoading ? (
  
    <div className="loader">
      <Spinner  className="spinner-border text-primary" />

  </div>  
  ) : (
    <>
    <div className="App">
      <OurRoutes />
    </div>
    <ToastContainer />
    <Toaster position="bottom-center" toastOptions={{ duration: 2500 }} />
  </>
  );
}

export default App;



## Conclusion

In conclusion, this README provides a detailed guide to understanding and working with the Clync Dashboard. It covers the system requirements, setup instructions, and usage steps to get started with the project. The document also outlines the project's folder structure, explaining the purpose of each directory and file at general level, which helps in maintaining a clean and organized codebase. Additionally, it lists the libraries and tools used, along with their versions and descriptions, ensuring that developers are aware of the project's dependencies. By following this guide, developers can efficiently set up, run, and contribute to the Clync project, leveraging its robust architecture and comprehensive feature set.

We will be happy to answer any questions.


