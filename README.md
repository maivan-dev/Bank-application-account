User Authentication & Dashboard Web App

A modern web application built with HTML, CSS, SASS, BEM, and Vue.js. Users can authenticate, verify their identity, submit personal information, and access a personalized dashboard.

Features

User Authentication (Login / Register)

Identity Verification

Personal Information Form

Vue.js-Based Dynamic Dashboard

SASS + BEM for clean and scalable styling

Fully responsive UI


Technologies Used

HTML5

CSS3

SASS / SCSS

BEM Methodology

Vue.js

JavaScript (ES6)


Project Structure

project-folder/
│── index.html
│── login.html
│── verify.html
│── dashboard.html
│── /src
│     ├── /scss
│     │     ├── base/
│     │     ├── components/
│     │     ├── layout/
│     │     └── main.scss
│     ├── /js
│     │     ├── app.js
│     │     └── components/
│     └── /vue
│           ├── Dashboard.vue
│           ├── Form.vue
│           └── Login.vue
│── /dist
│── README.md

Installation & Setup

git clone https://gitlab.com/your-username/your-project.git

npm install

npm run sass

Open index.html in your browser, or run:

npx live-server

Future Improvements

Backend API integration

Database support

Vue Router

Global state management (Pinia / Vuex)

Advanced validation
