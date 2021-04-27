## VarrockGE Project - API Server


VarrockGE is a full stack web application built with React, Express, and PostgresSQL that allows users to buy, sell, and collect video game collectibles. This repository serves as the backend API server for the [VarrockGE repository](https://github.com/gwan93/varrockge).

This project was completed by [Jesse Mcdermott](https://github.com/mcdermottjesse), [Ray Yiu](https://github.com/rayyiu), & [Gio Wan](https://github.com/gwan93) for the final project at Lighthouse Labs.

[Hosted on Heroku](https://varrockge-api-gw.herokuapp.com/) - Please wait 30-60 seconds for the Heroku server to start up after clicking the link.


## Project Setup

1. Fork this repository, then clone your fork of this repository.
2. Create the `.env` in the root of the directory by using `.env.example` as a reference.
3. Install all dependencies:
   ```shell
   npm install
   ```
4. Install the proper POSTGRESQL database:
   ```shell
   npm run db:reset
   ```
5. Start the web server using:
     ```shell
     npm start
     ```
6. Open your web browser and enter the default URL:
     ```browser
     http://localhost:<your port number>/
     ```
7. When finished, the server can be safely shut down with `control + c`.


## Dependencies

- Node 10.16.1 or above
- NPM 6.9.0 or above
- Cors 2.8.5 or above
- dotenv 8.2.0 or above
- Express 4.17.1 or above
- pg 8.5.1 or above
- pg-native 3.0.0 or above
