# demo-microservice-app

A simple demo Microservice Architecture application.

## Overview

This application is composed of the following services:

- Client (The Front-End Web Application)
- Comments-Service (Service Logic for Comments)
- Posts-Service (Service Logic for Posts)
- Query-Service (Service Logic for handling X-Data easier)
- Moderation-Service (Service Logic for handling Comments moderation; Try submitting `goldfinger` as a comment...)
- Event Bus/Broker (A manual implementation of an Event Bus to showcase _Event Brokering_ between services)

## Quick Start

There are two ways of running this locally, with each option requiring the same steps to _Start_ each of the Application Services:

A.) NPM

```
# `cd` into each service and run the following commands:
npm install
npm run start
```

B.) Docker

```
# `cd` into each service and run the following commands:
docker build -t <tagName> .
docker run <tagName>
```

Once each of the Services has been launched, visit `localhost:3000` in your web browser.

## Technologies & Frameworks

- [Create React App](https://facebook.github.io/create-react-app/)
- [React](https://reactjs.org/)
- [Bootstrap](http://getbootstrap.com/)
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [Docker](https://www.docker.com/)
