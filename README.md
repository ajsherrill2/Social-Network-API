# Social-Network-API

## Description

In this challenge I created an Api for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. Which utilizes Express.js for routing, a MongoDB database, and the Mongoose ODM.

Walkthrought Video:
(https://drive.google.com/file/d/1-Lg7XFDal7DfA5gNhHn6zaqhZPKhny7u/view)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Badges](#Badges)
- [Features](#Features)
- [Questions](#Questions)

## Installation

To Install:

Install node.js lts

Clone the repository from GitHub (https://github.com/ajsherrill2/Social-Network-API).

Run these command lines in your terminal to install necessary dependencies:

```
npm init -y
npm install
```

Additional installations (express, mongoose)

```
npm i express
npm i mongoose
```

Add script "start" which runs "node index"

## Usage

Direct your terminal to the repository root directory and run this command line to initiate application:

```
npm run start
```

Direct your browser via Insomnia  to "http://localhost:3001/"

Watch this short video demonstration [here](https://drive.google.com/file/d/1-Lg7XFDal7DfA5gNhHn6zaqhZPKhny7u/view)

## License

This application is covered under the MIT license.

## Badges

![license](https://img.shields.io/badge/license-MIT-yellow.svg)

![badmath](https://img.shields.io/github/languages/top/lernantino/badmath)

![badmath](https://img.shields.io/github/repo-size/ajsherrill2/Social-Network-API)

## Features

Features you will find in this app include:

- CRUD operations on mongoose powered documents in a mongoDB database
- CRUD operations {
  * find all users/thoughts
  * find user/thoughts by id
  * create/update/delete user
  * create/update/delete thoughts
  * create/delete reaction
  * add friend
  * remove friend
- Note that when a user is delete all thoughts by said user are also pulled from the database

## Questions

If you have any questions about the repo open an issue or contact me directly at adamsherrill2@gmail.com. You can find more of my work at [ajsherrill2](https://github.com/ajsherrill2/).
