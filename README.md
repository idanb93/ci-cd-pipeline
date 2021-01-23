# Synopsis

I created a Jenkins container which i have used to create a job that automatically retrieve files from a git repository every time someone commit changes, Then i created a Tomcat container with folder mapping to the Jenkins folder so the retrived files will be automatically mapped to the Tomcat container and be displayed when reaching the server.

When I created the containers I put them in one network so they could communicate, then I used a plugin for Jenkins called 'Monitor Site' that checks if the site is up / down.

## Goals

Create an automated process that can link and update changes from a git repository on a server.

## Motivation

Allow developers the commit changes to the git repository without worrying about dealing with deploying the changes on the server.

## Demonstration 

[![https://user-images.githubusercontent.com/35878173/103166910-60d27480-482f-11eb-8b1e-73edccece4e5.gif](https://user-images.githubusercontent.com/35878173/103166910-60d27480-482f-11eb-8b1e-73edccece4e5.gif)](https://www.youtube.com/watch?v=LkW4Uj31RZ0 "Jenkins")
