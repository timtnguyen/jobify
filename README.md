# Jobify

#### Track Your Job Search

Project in Action - [Jobify](https://www.jobify.live/)

#### Support

Find the App Useful? [You can always buy me a coffee](https://www.buymeacoffee.com/johnsmilga)

#### Run The App Locally

-.npm run install-dependencies
-.rename .ivn.temp to .env
-.setup values for - MONGO_URL, JWT_SECRET, JWT_LIFETIME
-.npm start
-.visit url http://localhost:3000/

#### Setup React App

- create 'client' folder
- open terminal
- cd client
- npx create-react-app .
- npm start
- set editor/browser side by side
- copy/paste assets from complete project

#### Spring Cleaning

- in src remove
- App.css
- App.test.js
- logo.svg
- reportWebVitals.js
- setupTests.js
- fix App.js and index.js

#### Title and Favicon

- change title in public/index.html
- replace favicon.ico in public
- resource (favicons) [https://favicon.io/]

#### Normalize.css and Global Styles

- CSS in JS
- saves times on the setup
- less lines of css
- speeds up the development
- normalize.css
- small CSS file that provides cross-browser consistency in the default styling of HTML elements.
- (normalize)[https://necolas.github.io/normalize.css/]
- npm install normalize.css
- import 'normalize.css' in index.js
- SET BEFORE 'index.css'
- if any questions about normalize or specific styles
- Coding Addict (Default Starter)[https://youtu.be/UDdyGNlQK5w]
- Repo (Default Starter) [https://github.com/john-smilga/default-starter]

#### Landing Page

- zoom leval 175%
- markdown preview extension
- get something on the screen
- react router and styled components right after
- create pages directory in the source
- for now Landing.js
- create component (snippets extension)
- setup basic return

```
js
<h4>Landing Page<h4>
```

- import logo.svg and main.svg
- import Landing in App.js render
