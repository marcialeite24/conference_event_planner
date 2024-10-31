# Conference Event Planner

Course: [Developing Front-End Apps with React](https://www.coursera.org/learn/developing-frontend-apps-with-react?specialization=ibm-full-stack-cloud-developer) - [IBM Full Stack Software Developer](https://www.coursera.org/professional-certificates/ibm-full-stack-cloud-developer)

## Table of contents

- [Overview](#overview)
- [Project Features](#project-features)
- [Learning Objectives](#learning-objectives)
- [Getting Started](#getting-started)


## Overview
This project is a Conference Expense Planner created for BudgetEase as part of the IBM Full Stack Software Developer course on Coursera. It helps clients manage and estimate the costs of their conference events. The application allows users to select rooms, add-ons like microphones and projectors, and meal options, providing a dynamic breakdown of costs based on real-time selections. This project reinforces component structuring in React and state management using Redux Toolkit.

## Project Features
- **Dynamic User Interface:** Real-time UI updates based on user selections, making the application responsive to changes.
- **Venue and Add-on Selection:** Components for selecting conference rooms, add-ons, and meals, with options displayed dynamically.
- **Cost Calculator:** Calculates and displays costs for selected items, including subtotal and total costs.
- **Redux Integration:** Uses Redux Toolkit for efficient state management and to handle multiple UI sections.
- **Pop-Up Summary Table:** Shows a pop-up window with a summary table of selected items, including item names, unit costs, quantities, and total costs.

## Learning Objectives
Through this project, the following skills and concepts were learned:

- **React Component Design:** Creating nested and composed React functional components.
- **State Management:** Using the `useState` and `useEffect` hooks for managing state within components.
- **Redux Integration:** Managing complex application states with Redux Toolkit, including actions, reducers, and the Redux store.
- **Dynamic Data Rendering:** Mapping over arrays to display options and selected items within the UI.
- **Event Handling and Conditional Rendering:** Handling user events and conditionally rendering elements based on actions.

## Getting Started
- Clone the repository (it was necessary to clone the repository of this course to start this project):

``` bash 
git clone git clone https://github.com/ibm-developer-skills-network/conference_event_planner.git
cd event-planner-landing-page
```

- Install dependencies:

``` bash
npm install
```

- Start the development server:

``` bash
npm run preview
```
- Open http://localhost:4173 to view the landing page in your browser.

## Acknowledgements
This project was developed as part of the IBM Full Stack Software Developer Specialization on Coursera. It provided valuable insights into creating component-based front-end applications using React.

## License
This project is open-source and available under the Apache 2.0 License.