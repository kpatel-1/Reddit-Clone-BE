# Spring Boot & AngularJS Reddit Clone
### Back End (Sprint Boot)



[![Build Status](https://raw.githubusercontent.com/travis-ci/travis-api/master/public/images/result/unknown.png)](https://github.com/kpatel-1/Reddit-Clone-BE/)

Tutorial by freeCodeCamp: https://www.youtube.com/watch?v=DKlTBBuc32

## Features

- Authentication, refresh tokens, password encryption, etc.
- Homepage, view posts, create posts, create threads, etc.
- Create subreddit, view subreddit, voting, etc.
- User profile management

## Tech

Dillinger uses a number of open source projects to work properly:

- [AngularJS](https://angularjs.org/)
- [Spring Boot](https://spring.io/projects/spring-boot)
- [VSCode](https://code.visualstudio.com/)
- [IntelliJ IDEA](https://www.jetbrains.com/idea/)
- [node.js](https://nodejs.org/en/)
- [MySQL Workbench](https://www.mysql.com/products/workbench/)
- [Git](https://git-scm.com/)

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Installation

- Modify **application.properties** 
```sh
###### Database Properties  ###########################################
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.url=
spring.datasource.username=
spring.datasource.password=
spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL8Dialect
spring.jpa.hibernate.ddl-auto=update
spring.datasource.initialize=always
spring.jpa.show-sql=true
############# Mail Properties ###########################################
spring.mail.host=smtp.mailtrap.io
spring.mail.port=
spring.mail.username=
spring.mail.password=
spring.mail.protocol=smtp
############ JWT Properties #####################
jwt.expiration.time=900000
```

- Compile & Run
