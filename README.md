# Objective

We will develop a web application with the idea of getting to know your knowledge of different topics.

The excerice will have two parts.

- Take-home exercise
- Live-pairing exercise

**Do not develop more than expected on the take-home exercise and do not build anything from the live-pairing exercise before the day of the interview, except for the basic Frontend structure (see instructions below).**

# Web application requirements

- At a minimum, we expect a search feature that lists activities based on user input.
- You should build at least one API endpoint which your frontend application can use to get data or search results.
- Based on the provided data, you can add additional features which you think may be useful for travelers.
- User experience matters. We value the delivered product as much as we value technologies used.

If you'd like to build this step by step, you can follow this guidance:

- Start by creating the API endpoint (take-home)
- Create a simple app which uses the endpoint to get data, search and display a list of activities (live-pairing)
- Improve the visual display of the app and search results (live-pairing)
- If time allows, add any additional features you think could be useful (live-pairing)

# Technical requirements

Use the tools, libraries or frameworks you think are appropriate with the following guidelines:

- Using CLI creator tools that setup a build toolchain is fine (vue-cli, create-react-app, etc).
- Please don't use creator apps or starter kits that setup a whole code structure for you. We want to see what you come up with.
- We'd prefer to see actual CSS code (or a CSS in JS solution) rather than usage of a UI library.

# Take-home exercise

We will give you time to complete the take-home exercise. You should share the repository with us ahead of the interview time, so the interviewers can prepare questions that we will discuss at the beginning of the live-pairing interview.

## Take-home exercise instructions

- Fork this repository to your local machine.
- There is a server/index.js file with a minimal Express setup.
  - You can run this server with `npm run server` after performing an `npm ci`
  - **If you prefer to use another Node.js server** (Koa, Hapi), please install it and prepare a **minimal setup** ahead of time
  - **If you prefer to use another backend language** (Java, PHP, Ruby, etc), please prepare a **basic setup** with one endpoint ahead of time
- Setup a simple development environment with your tools of choice. Use the IDE of your preference.

## Take-home exercise requirements

- You should build at least one API endpoint that your front-end application can use to search and display activities.
- Use the provided static JSON file containing sample activity data as your data source.

# Live-pairing exercise

During the live-pairing exercise, you will use the endpoint that you developed on the take-home exercise to create a web application to search and display activities.

## Live-pairing exercise instructions

- Please include, ahead of the interview (at home), the basic Frontend structure:
  - Using vue-cli, run the following to start an app:
    - `npx @vue/cli create search-app`
  - Using React CLI, run the following to start an app:
    - `npx create-react-app search-app`
- You can choose to use a different framework or no framework at all, but we expect you to be ready to start developing and not spend time on setting up an environment.
- Only the basic Frontend structure should be done at home. It could be the React, Vue, or framework of your choice "Hello World!" page. We expect you to start writing the Frontend components at the Live-pairing exercise moment.
- The interviewers will guide you throughout the Live-pairing exercise and will address any questions.

## Live-pairing exercise requirements

- The web application allows displaying and searching for activities based on user input.
  - You decide the type of user input (text input, checkboxes, etc.)
- Think about the needs of a traveler that is looking for things to do in a destination.
  - For example, a person visiting Berlin that is interested in things to do during their visit.

# What you should prepare ahead of time, before our live-pairing interview

To reiterate, these are the things you should prepare at home before our live-pairing interview:

- The take-home exercise should be ready.
- The repository containing the take-home exercise should have already been shared with us.
- Please include, ahead of the interview, the basic Frontend structure:
  - Using vue-cli, run the following to start an app:
    - `npx @vue/cli create search-app`
  - Using React CLI, run the following to start an app:
    - `npx create-react-app search-app`
- You can choose to use a different framework or no framework at all, but we expect you to be ready to start developing and not spend time on setting up an environment.
- Only the basic Frontend structure should be done at home. It could be the React, Vue, or framework of your choice "Hello World!" page. We expect you to start writing the Frontend components at the Live-pairing exercise moment.

# Important!

We'll expect you to share your screen while creating this application and talk us through what you're doing.

- Our video conferencing app supports screen sharing.
- Turning on the "Do Not Disturb" mode can be helpful during the live-pairing exercise.
