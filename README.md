# KeiKei React Native Challenge

At our software development house nestled in the vibrant city of İstanbul, we embody innovation and a passion for crafting top-notch solutions. We wholeheartedly embrace agile methodologies and adhere to industry best practices throughout the software life cycle.

Our commitment to excellence extends beyond just technology, as we strongly value our company culture and invest in our team. We strive to assemble a group of highly skilled developers, each driven by their love for software development.

**We continue to constantly seek talented individuals to join our team. Please direct all questions regarding employment opportunities to us via :**

- E-mail: [developer@keikei.co](mailto:developer@keikei.co)
- Linkedin: [KeiKei](https://www.linkedin.com/company/keikeico/)

# About the challenge

This assessment requires the creation of a React Native application utilizing the provided screens as a reference. The task involves retrieving content, sorting, searching and generating user data, and displaying it in the view.

Please note that while this is a basic exercise, it is expected that the submitted code will exhibit simplicity, proper design, and thorough testing. A keen attention to detail and quality is essential.

# Task

Using the provided screens as a reference, you will need to build a set of React components to render the app. You will also need to request a data feed, filter that data, and use the relevant fields.

We have provided mock user data (https://dummyjson.com/docs/users). While requesting data, we also ask you to use React Query for storing incoming data. So this stored data will be used when you build the app and the components.

Use the returned data to display a page of results that matches the given design.

Please include a README with setup instructions, and any tests or other documentation you created as part of your solution.

You can use frameworks or packages as long as you can explain to us why you chose them.

# Design

You can find the design sample in the [_screens_](/screens) folder. You can work independently as a UI on design. We expect you to be committed to designing when it comes to UX.

# Details

You will need to build the following 5 pages:

1. Login
2. Home
3. Create a new user
4. User detail
5. Profile

   ## Login Page

   This will be your first screen. You can request https://dummyjson.com/docs/auth for authentication to keep the logged-in user and separate the auth stack from the app stack.

   ## Home Page

   This will be the page where the users are listed.

   - Listed users must be over the age of 18 and in order from youngest to oldest.
   - At least 3 characters must be entered for the search function.
   - New users should be loaded as the list scrolls down.
   - The case of no search results should be handled.
     ### Create New User Page
     - Create a new user with validations.
     - User should go back to home page after successful creation.
     ### User Detail Page
     - User age must be calculated manually.

   ## Profile Page

   - Information of the logged in user is displayed
   - User age must be calculated manually.
   - Logout button should be working and user should be redirected to login page.

# Nice to have

1. Utilization of TypeScript
2. Documentation of the development process through Git commit history.
3. Adherence to production-grade coding standards, including clean, maintainable, and reusable code.
4. Implementation of unit tests using Jest and React Testing Library.
5. Use of styled-components for styling.
6. Incorporation of React Query.

# Submission Guidelines

- Please submit your code by sending a GitHub repository link.
