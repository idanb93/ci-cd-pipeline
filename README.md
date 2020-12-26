# devops-project

# Synopsis

Continuous integration project - I created jenkins docker container and tomcat docker container on the same network and then created a job on jenkins that samples changes in a git repository once per minute, pulls the changes and then automatically map the changed files to the webapps folder on tomcat.

## Goals

Create an automated process for deploying changes in other containers / services when developers making changes in a git repository.

## Motivation

Spare time and effort for deploying changes manually on the different services that we use.

## DEMO

[![Demo CountPages alpha](<iframe src='//gifs.com/embed/k8AMxX' frameborder='0' scrolling='no' width='640px' height='360px' style='-webkit-backface-visibility: hidden;-webkit-transform: scale(1);' ></iframe>)](https://www.youtube.com/watch?v=QmFHNb4QLdQ)

