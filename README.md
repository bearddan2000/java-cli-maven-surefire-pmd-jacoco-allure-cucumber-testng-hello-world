# java-cli-maven-surefire-pmd-jacoco-allure-cucumber-testng-hello-world

## Description
A POC for maven app using testNg
and cucumber framework with jacoco,
pmd, allure, and surefire plugins.

Serves allure report from link given
after the build.

## Tech stack
- java
- maven
  - testNg
  - surefire
  - jacoco
  - cucumber
  - pmd
	- allure

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco
- pmd report found at bin/target/site

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
- [Jacoco config](https://www.baeldung.com/jacoco)
