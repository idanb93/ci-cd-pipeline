# Synopsis

I created a Jenkins container which i have used to create a job that poll SCM periodically every one minute for a certain Git repository, and automatically retrieve files from that Git repository every time someone commit changes to it. Then i created a Tomcat container with folder mapping to the Jenkins folder so the retrived files from the Git repository will be automatically mapped to the Tomcat container and will be displayed when reaching the server.

When i created the containers i put them in one network so they could communicate with each other, Then i used a plugin for Jenkins called 'Monitor Site' and added it to the job. Everytime you build the job it checks if the tomcat server is up or down.

## Goals

Create an automated process that can link and update changes from a git repository on a server.

## Motivation

Allow developers to commit changes to the git repository anytime without worrying about dealing with deploying the changes on the server.

## Demonstration 

[![https://user-images.githubusercontent.com/35878173/103166910-60d27480-482f-11eb-8b1e-73edccece4e5.gif](https://user-images.githubusercontent.com/35878173/103166910-60d27480-482f-11eb-8b1e-73edccece4e5.gif)](https://www.youtube.com/watch?v=LkW4Uj31RZ0 "Jenkins")
