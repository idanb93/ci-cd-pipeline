# devops-project

# Synopsis

Continuous integration project - I created jenkins docker container and tomcat docker container on the same network and then created a job on jenkins that samples changes in a git repository once per minute, pulls the changes and then automatically map the changed files to the webapps folder on tomcat.

## Goals

Create an automated process for deploying changes in other containers / services when developers making changes in a git repository.

## Motivation

Spare time and effort for deploying changes manually on the different services that we use.

## DEMO

[![https://user-images.githubusercontent.com/35878173/103166707-6464fc00-482d-11eb-91bb-2c6db446e010.gif](https://user-images.githubusercontent.com/35878173/103166707-6464fc00-482d-11eb-91bb-2c6db446e010.gif)](http://www.youtube.com/watch?v=QmFHNb4QLdQ "Jenkins")


