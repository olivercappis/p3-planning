# project-2-planning

```js
Application
├── client
│ ├── public
│ │ ├── vite.svg
│ ├── src
│ │ ├── asssets
│ │ │ ├── react.svg
│ │ ├── components
│ │ │ ├── navbar.jsx
│ │ │ ├── ? widget.jsx
│ │ ├── pages
│ │ │ ├── notLoggedHome.jsx
│ │ │ ├── loggedInHome.jsx
│ │ │ ├── settings.jsx
│ │ │ ├── login.jsx
│ │ ├── utils
│ │ │ ├── auth.js
│ │ │ ├── *fill in after wireframe
│ │ ├── App.jsx
│ │ ├── main.jsx
│ ├── eslintrc.cjs
│ ├── .gitignore
│ ├── index.html
│ ├── package.json
│ ├── vite.config.js
├── server
│ ├── config
│ │ ├── connection.js
│ ├── models
│ │ ├── index.js
│ │ ├── User.js
│ │ ├── Preferene.js
│ ├── schemas
│ │ ├── index.js
│ │ ├── resolvers.js
│ │ ├── typeDefs.js
│ ├── utils
│ ├── package.json
│ ├── server.js
├── .gitignore
├── .npmrc
├── package.json
├── README.md

```

YouNews (we can change the name) User Stories:
User Story 1: Global Landing Page (Before Login)
As a visitor, I want to land on the global YouNews page and see a general selection of top news (e.g., World News, Tech, Stocks, Sports) without needing to log in.
As a visitor, I want to be able to browse the top news categories before deciding to log in or sign up.
As a user, after logging in, I want to be redirected from the global landing page to my personalized landing page, which displays the news widgets I have selected or removed based on my preferences.

User Story 2: Sign-Up and Login
As a user, I want to sign up and log in so I can save my personalized news dashboard preferences.

User Story 3: Customizable Widgets
As a user, I want to choose from a variety of widgets (e.g., sports, tech, world news, weather) and arrange them on my dashboard.
As a user, I want to easily add or remove widgets as my interests change.
User Story 4: News Preferences

As a user, I want to choose specific news categories (e.g., technology, entertainment, finance) so my dashboard shows news based on my preferences.

User Story 5: Real-Time News Updates
As a user, I want the widgets to update with the latest news in real-time so I can always stay informed.