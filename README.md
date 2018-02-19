# hello-world-react

[![Build Status](https://travis-ci.org/aevitas/hello-world-react.svg?branch=master)](https://travis-ci.org/aevitas/hello-world-react)

This repository contains a React **Hello World** application that runs on Docker. It is served via Nginx, and CI is provided by TravisCI.

The React application is simply a slightly modified application by [`create-react-app`](https://reactjs.org/docs/add-react-to-a-new-app.html).

## Run it in Docker

Running the application on Docker is straight forward:

* `docker build -t hello-world-react .` to build the Docker image
* `docker run -p 8080:80 hello-world-react` to fire up the container

Visit `http://localhost:8080`, or any port you set it to to view the application.

## Run the development server

You can also run the application on the default React development server by simply running `npm start` in the project's root. It'll fire up the application on `http://localhost:3000`.