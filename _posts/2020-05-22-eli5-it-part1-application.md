---
title: Explain IT like I'm five - Part 1 - What is an application?
last_modified_at: 2020-05-20T18:00:00-05:00
categories:
  - Blog
tags:
  - 100DaysToOffload
  - IT
  - ELI5
---

As far as I can tell, a lot of my peers, family or friends, has had a hard time figuring out what the hell I am doing of my workdays. With this blog, I finally have the opportunity to explain this.

Computer engineering is a really complex topic. I am 27 years old, so I am very far from understanding all of its aspects. Nevertheless, I think I know enough to explain with simple words what the IT (Information technology) field looks like so anybody, even boomers (sorry), can understand this really popular yet quite unknown industry.

Because this topic is quite complex, I will need a LOT of articles to cover it. But I will make sure to narrow down each one to a specific notion for more clarity.

This first article will talk about the basic concept of Application.

## What is an application?

Nowadays, everything is an application. You certainly know a lot of them: Facebook, Spotify, Google Maps, WhatsApp... The very word application is a catch-all term that has lost of lot of meaning. For the public at large, the meaning of Application is very close to the meaning of the "old", pre-smartphone era, *software* word.

**An application is a set of programs that helps the user to achieve one or several tasks.**

Let's take an example: Google Maps is an application. Its main objective is to help you locate things in the world. Note that I am considering which device you are using to use this application.

This is an important notion to understand: applications are not only executed on mobiles. If you want to be specific, you can indeed talk about "mobile application", but all applications are not mobile-specific.

Let's go back to the Google Maps example: before existing on smartphones, you experiences Google Maps on your computer. This wasn't even a software you installed on your Windows computer with an .exe file. This was (and is still) a service you access with your web browser at google.com/maps. This still makes it an application. In this case we would say a *web application*.

## Okay so I can access the same service on mobile and with my computer... What should I understand?

Here comes the interesting part. You probably understand that engineers at Google haven't developed the same service twice, for mobile **and** the web.

We are slowly approaching the concepts of Software Architecture and I will try to make this part as understandable as possible.

Let me introduce you to the concepts of **frontend** and **backend**.

In an application, the frontend is basically the user interface, while the backend actually does the real work and calculation resulting from the frontend's requests which then are presented to the user.

You, as a final user, are only presented to frontends and will probably never be faced to backend services, except if you start learning development.

In the Google Maps example, we have two frontends and the backend services are hosted on some obscure Google servers you will never know about.

![google_maps_frontend_backend_schenma](/assets/images/googlemaps-frontend-backend.png)

I think that is enough for today, next article I will probably explain a bit longer what does compose the backend of an application.

Feel free to comment this article and share it with anyone!

---

*This is my 2nd article written for the [#100DaysToOffload](https://100daystooffload.com/) challenge !* 