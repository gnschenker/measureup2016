# Introduction
Sample used during my presentation at MeasureUp 2016 with the tile

**How Docker simplifies CI/CD**

# How to use
Clone this repository and then run the following command in a terminal from the root of the project

`docker-compose up --build`

Open a REST client, e.g. Postman, and execute

```
GET localhost/api             // returns welcome message
GET localhost/api/bears       // returns all bears

POST localhost/api/bears
  Headers:
    Content-Type: application/json
  Body:
    { "name": "[name of bear]"}
```
