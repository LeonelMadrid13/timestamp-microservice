
# Timestamp Microservice

This is a solution to the [Timestamp Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/timestamp-microservice) backend certification project from [freeCodeCamp](https://www.freecodecamp.org).

## Table of Contents

- [Timestamp Microservice](#timestamp-microservice)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
    - [The Challenge](#the-challenge)
    - [Links](#links)
  - [My Process](#my-process)
    - [Built With](#built-with)
    - [What I Learned](#what-i-learned)
    - [Continued Development](#continued-development)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

User Stories

- A request to /api/:date? with a valid date should return a JSON object with a unix key that is a Unix timestamp of the input date in milliseconds.
- A request to /api/:date? with a valid date should return a JSON object with a utc key that is a string of the input date in the format: Thu, 01 Jan 1970 00:00:00 GMT.
- A request to /api/1451001600000 should return { unix: 1451001600000, utc: "Fri, 25 Dec 2015 00:00:00 GMT" }.
- Your project can handle dates that can be successfully parsed by new Date(date_string).
- If the input date string is invalid, the api returns an object having the structure { error : "Invalid Date" }.
- An empty date parameter should return the current time in a JSON object with a unix key.
- An empty date parameter should return the current time in a JSON object with a utc key.

### Links

- Live Site URL: [fcc--timestamp-microservice](https://fcc--timestamp-microservice.herokuapp.com/)

## My Process

### Built With

- [NodeJS](https://nodejs.org)
- [ExpressJS](https://expressjs.com)

### What I Learned

- How the requests are handled in a server, which the ExpressJS makes easy.
- How the responses are generated and handled for a request.
- How to create routes for specific requests.
- How the date and time formats are handled.

### Continued Development

I will be focussing more on the basic level JavaScript and its various functions, because this project really taught how the basic and fundamental functions can help.

## Author

- freeCodeCamp: [randombit](https://www.freecodecamp.org/randombit)

## Acknowledgments

- [freeCodeCamp](https://www.freeCodeCamp.org) - For providing such a great and free platform for budding developers.
