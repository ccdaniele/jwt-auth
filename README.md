

<h1 align="center">Authentication API</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/{{YOUR_GITHUB_USERNAME}}/jwt-auth?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/{{YOUR_GITHUB_USERNAME}}/jwt-auth?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/{{YOUR_GITHUB_USERNAME}}/jwt-auth?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/{{YOUR_GITHUB_USERNAME}}/jwt-auth?color=56BEB8">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/{{YOUR_GITHUB_USERNAME}}/jwt-auth?color=56BEB8" /> -->

  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/{{YOUR_GITHUB_USERNAME}}/jwt-auth?color=56BEB8" /> -->

  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/{{YOUR_GITHUB_USERNAME}}/jwt-auth?color=56BEB8" /> -->
</p>

<hr> -->

<br>

## :dart: About ##

Describe your project


Original repo: https://github.com/giridhar7632/Authentication.git | Thanks giridhar7632 

Recommended post: https://www.honeybadger.io/blog/javascript-authentication-guide/ 

Creating jwt-authentication-api for authorize app on git-api

## :sparkles: Features ##

:heavy_check_mark: JWT authentication API based in user email-password;\
:heavy_check_mark: Cloud DB hosted on Mongodb;\
:heavy_check_mark: Email password recovery ;

## :white_check_mark: Requirements ##

Before starting :checkered_flag:, you need to have [Git](https://git-scm.com) and [Node](https://nodejs.org/en/) installed.

Also you should have a DB available. 

In this project was used Mongo_db: https://www.freecodecamp.org/news/get-started-with-mongodb-atlas/ 

Also I tested postgres DB locally with https://www.npmjs.com/package/sequelize 

## :checkered_flag: Starting ##

```bash
# Clone this project
$ git clone https://github.com/{{YOUR_GITHUB_USERNAME}}/jwt-auth

# Access
$ cd jwt-auth

# Install dependencies
$ npm install 

# Run the project
$ npm dev run 

# The server will initialize in the <http://localhost:3000>
```

Test endpoints using curl: 

```
$curl -X POST http://localhost:8080/auth/signup \
--header 'Content-Type: text/plain' \
--data-raw '{
    "email":"<TEST_EMAIL>",
    "password":"<TEST_PASSWORD>"
}'

```



&#xa0;

<a href="#top">Back to top</a>
