# Scuba TV
## We take a deep dive into the shows you want!

![GitHub](https://img.shields.io/github/license/alex-whan/team-bulbasaur-301-final-project)
![GitHub package.json version](https://img.shields.io/github/package-json/v/alex-whan/team-bulbasaur-301-final-project)
[![Build Status](https://travis-ci.com/alex-whan/team-bulbasaur-301-final-project.svg?branch=development)](https://travis-ci.com/alex-whan/team-bulbasaur-301-final-project)


## Authors:
### Code Fellows - Code 301 Final Project - Team Bulbasaur
* Lulu Sevignon
* Josh Williams
* Kamit Satkeev
* Alex Whan

**Version:** 1.3.0

* View the deployed site for **Scuba TV** here: https://scuba-tv.herokuapp.com/

## Overview

There are an overwhelming number of series available on multiple streaming platforms, making choosing what to watch difficult. This application makes it easier to decide on what series/show a user is going to watch, as it gives them valuable information up front that makes the decision as to what to watch simpler. This way users can identify ahead of time which series is right for them based off of the time required to finish the series (overall time, number of seasons, etc).

## Architecture

The back end of this application is built on an Express server, and uses Superagent for making API calls to the Trakt.tv, RapidAPI/uTelly, and The Movie Database (TMDb) APIs. Postgres stores data in a database, and uses SQL to query stored information from the database to populate the user Collection and Comments to avoid excess API calls. The front end of the application is created using tje EJS (Embedded JavaScript) templating library for views and partials. Travis.CI is used implement Continuous Integration and testing before deployment.

### Technologies
- Javascript
- Node.js
- SQL
- PostgreSQL
- EJS
- APIs: Utelly, TMDb, Trakt.TV

### Domain Modelling

![Web Request Response Cycle](./public/assets/images/project-wrrc.png)

### CRUD:
* Create (Post) - Add series to favorites/database
* Read (Get) - Getting routes
* Update (Put) - Comment updates
* Delete (Delete) - Delete from favorites/database

### Database Entity Relationship Diagram

![Database Entity Relationship Diagram](./public/assets/images/project-erd.jpg)

### Application Wireframe

![Wireframe 1](./public/assets/images/wireframe-1.jpg)
![Wireframe 2](./public/assets/images/wireframe-2.jpg)
![Wireframe 3](./public/assets/images/wireframe-3.jpg)
![Wireframe 4](./public/assets/images/wireframe-4.jpg)
![Wireframe 5](./public/assets/images/wireframe-5.jpg)
![Wireframe 6](./public/assets/images/wireframe-6.jpg)
![Wireframe 7](./public/assets/images/wireframe-7.jpg)

<img alt="wireframe" src="./public/assets/images/wireframe-1.jpg" width="350" />


## Links and Important Resources

* [Trello Project Management Board](https://trello.com/b/b31pfDlT/bulbasaur)

* Project Preparation Documents
  - [Software Requirements](./md/requirements.md)
  - [Conflict & Communication Plan](./md/conflict-communication.md)
  - [Work Plan & Git Flow](./md/work-git.md)
