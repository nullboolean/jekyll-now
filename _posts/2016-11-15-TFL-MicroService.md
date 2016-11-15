---
layout: post
title: TFL Microservice Started
---

Decided to kick things off with this new GitHub account by creating a new project for me to work on while I commute to and from work. Well, when there is normally some dead time. So this project had to use as little resources as possible.

So the project is to create a micro service with Spring Boot that calls the TFL (Transport for London) unified web API. This would allow other projects to include this within their micro service cluster. Now this would allow for levels of caching and possible local storage of items that make sense.

The microservice will pull in a common TFL client, which will be built within the project however as a separate maven module. This will allow others to pull just this jar down without the micro service.

Currently, the repository is private at the time of writing this post. Only while I get things started and will make it public once there is something to show. Check the projects page on this site, or my GitHub  for more information on the project.
