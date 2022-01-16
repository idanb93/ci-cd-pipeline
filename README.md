# Synopsis

In this project I built a ci-cd-pipeline using Jenkins container which I used to create a job that poll SCM every minute to check if a new commit has been made in a particular Git repository. if it detects a new commit it automatically retrieve the files.

Afterwards I created a Tomcat container with folder mapping from the Jenkins folder so the retrived files from the Git repository will be automatically mapped to the Tomcat folder and will be displayed when reaching the server.

When i created the containers i put them in one network so they could communicate with each other, Then on the jenkings container i added a plugin for the job called 'Monitor Site', so that everytime that the jenkins job is being built it checks if the tomcat server is up or down.

## Goals

Create an automated process that can link and update changes from a git repository on a server.

## Motivation

Allow developers to commit changes to the git repository anytime without worrying about dealing with deploying the changes on the server.

## Demonstration 

[![https://user-images.githubusercontent.com/35878173/103166910-60d27480-482f-11eb-8b1e-73edccece4e5.gif](https://user-images.githubusercontent.com/35878173/103166910-60d27480-482f-11eb-8b1e-73edccece4e5.gif)](https://www.youtube.com/watch?v=LkW4Uj31RZ0 "Jenkins")
