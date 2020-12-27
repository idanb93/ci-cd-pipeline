# Synopsis

I created jenkins docker container and tomcat docker container on the same network and then created a job on jenkins that poll the SCM periodically from a git repository once per minute, if there is changes it retrive the changes and then automatically map them to the webapps folder on tomcat.

## Goals

Create an automated process for deploying changes in other containers / services when developers making changes in a git repository.

## Motivation

Spare time and effort for deploying changes manually on the different services that we use.

## DEMO

[![https://user-images.githubusercontent.com/35878173/103166910-60d27480-482f-11eb-8b1e-73edccece4e5.gif](https://user-images.githubusercontent.com/35878173/103166910-60d27480-482f-11eb-8b1e-73edccece4e5.gif)](http://www.youtube.com/watch?v=QmFHNb4QLdQ "Jenkins")
