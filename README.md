[![Build Status](https://travis-ci.org/nikos/springboot-security-mongodb.svg?branch=master)](https://travis-ci.org/nikos/springboot-security-mongodb)
[![Codacy Badge](https://api.codacy.com/project/badge/grade/843f4e03e4664cfc8abcf441fd0b3f63)](https://www.codacy.com/app/niko_2/spring-boot-security)

# Demo for Spring Boot with Spring Security

A sample app on how you could integrate Spring Boot with an
simple UI to administer users based on Spring Security concepts.

Based on an articles by [Ivan Hristov](http://ingini.org/2015/03/26/authentication-authorization-schema-design-with-mongodb/)
and [Bartosz Kielczewski](http://kielczewski.eu/2014/12/spring-boot-security-application/).

Run with:

    ./gradlew -Dspring.profiles.active=dev bootRun


### DB Migration


https://github.com/mongeez/mongeez/wiki/How-to-use-mongeez

### IDEA Integration

Set output directory to

    build / classes / main

Enable Lombok (requires Lombok plugin installed first) annotation processor:

    Preferences -> Build... -> Compiler -> Annotation Processors
