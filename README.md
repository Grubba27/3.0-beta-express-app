# Meteor Beta with Express.js

This is a Meteor project that uses Express.js to create a simple API for managing links.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Node.js and Meteor installed on your machine.

### Installing

1. Clone the repository
2. Navigate to the project directory
3. Run `meteor npm install` to install the dependencies
4. Run `meteor` to start the server

## Usage

The project exposes an API endpoint `/all-links` that returns all the links in the database.

## Code Overview

The project uses Meteor's `WebAppInternals` to integrate Express.js into the Meteor server. It defines a single Express route handler for the `/all-links` endpoint.

The `insertLink` function is used to insert a new link into the `LinksCollection`. This function is used in the `Meteor.startup` function to populate the `LinksCollection` with some initial data if it's empty.

## Built With

* [Meteor](https://www.meteor.com/)
* [Express.js](https://expressjs.com/)
* [MongoDB](https://www.mongodb.com/)
