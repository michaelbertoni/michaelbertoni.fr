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

*English version below*

---

Pour autant que je sache, les gens qui m'entourent, qu'ils soient de ma famille ou de mes amis, ont eu du mal à comprendre ce que je fais de mes journées de travail. Avec ce blog, j'ai enfin l'occasion de l'expliquer.

Le génie informatique est un sujet vraiment complexe. J'ai 27 ans, donc je suis très loin d'en comprendre tous les aspects. Néanmoins, je pense en savoir assez pour expliquer avec des mots simples à quoi ressemble le domaine de l'informatique afin que tout le monde, même les boomers (désolé), puisse comprendre cette industrie très populaire mais assez méconnue.

Comme ce sujet est complexe, j'aurai besoin de BEAUCOUP d'articles pour le couvrir. Mais je m'assurerai de réduire chacun d'entre eux à une notion spécifique pour plus de clarté.

Ce premier article traitera du concept de base de l'application.

## Qu'est-ce qu'une application ?

De nos jours, tout est une application. Vous en connaissez certainement beaucoup : Facebook, Spotify, Google Maps, WhatsApp... Le mot même d'application est un terme fourre-tout qui a perdu beaucoup de son sens. Pour le grand public, le sens du mot application est très proche de celui du mot *logiciel*, "ancien", de l'ère pré-smartphone on peut dire.

**Une application est un ensemble de programmes qui aident l'utilisateur à réaliser une ou plusieurs tâches.**

Prenons un exemple : Google Maps est une application. Son principal objectif est de vous aider à localiser des choses dans le monde. Notez que je ne parle pas de quel appareil vous utilisez pour utiliser cette application.

C'est une notion importante à comprendre : les applications ne sont pas seulement exécutées sur les mobiles. Si vous voulez être précis, vous pouvez en effet parler d'"application mobile", mais toutes les applications ne sont pas spécifiques aux mobiles.

Revenons à l'exemple de Google Maps : avant d'exister sur les smartphones, vous faites l'expérience de Google Maps sur votre ordinateur. Ce n'était même pas un logiciel que vous aviez installé sur votre ordinateur Windows avec un fichier .exe. C'était (et c'est toujours) un service auquel vous accédez avec votre navigateur web à l'adresse google.com/maps. Cela en fait toujours une application. Dans ce cas, nous parlerons d'une *application web*.

## Ok donc je peux accéder au même service sur mon mobile et avec mon ordinateur... Que dois-je comprendre ?

Voici la partie intéressante. Vous comprenez probablement que les ingénieurs de Google n'ont pas développé deux fois le même service, pour le mobile **et** le web.

Nous approchons lentement de notions d'architecture logicielle et je vais essayer de rendre cette partie aussi compréhensible que possible.

Laissez-moi vous présenter les concepts de **frontend** et **backend**.

Dans une application, le frontend est essentiellement l'interface utilisateur, c'est ce que vous voyez lorsque vous tapez facebook.com ou lorsque vous ouvrez l'application Facebook sur votre smartphone.

Ce type d'application ne peut pas fonctionner seule sur votre appareil, elle doit toujours récupérer certaines données sur des serveurs distants. Facebook, par exemple, a besoin de récupérer le contenu de votre fil d'actualité, la liste de vos messages, vos dernières notifications.

Les serveurs requêtés par le frontend hébergent en fait le "backend" qui fait le vrai travail et les calculs. Ceux-ci n'ont pas besoin d'interface graphique utilisateur.

En tant qu'utilisateur final, on ne vous présente que les frontends et ne serez probablement jamais confronté aux services backends, sauf si vous commencez à apprendre le développement.

Dans l'exemple de Google Maps, nous avons deux applications frontends : votre application web google.com/maps et l'application mobile Google Maps. Les services backends sont hébergés sur d'obscurs serveurs Google dont vous n'aurez sûrement jamais connaissance.

![google_maps_frontend_backend_schenma](/assets/images/googlemaps-frontend-backend.png)

Si vous voulez un exemple plus illustré, imaginez des voitures qui partagent le même moteur V8. Vous pouvez comparer le moteur V8 au service backend qui répond aux instructions du conducteur provenant des tableaux de bord de différentes voitures, qui représentent le frontend. Ce n'est pas le meilleur exemple que je puisse vous donner car un moteur ne répond pas à différents tableaux de bord en même temps, mais je pense que vous l'avez compris.

Je pense que cela suffit pour aujourd'hui, dans le prochain article, je vais probablement expliquer un peu plus longuement ce que sont exactement les services backends, ce qui se passe sous le capot de nos applications les plus connues.

N'hésitez pas à commenter cet article et à le partager !

---

*C'est mon 2ème article écrit pour le défi [#100DaysToOffload](https://100daystooffload.com/) !* 

---

As far as I can tell, a lot of my peers, family or friends, has had a hard time figuring out what the hell I am doing of my workdays. With this blog, I finally have the opportunity to explain this.

Computer engineering is a really complex topic. I am 27 years old, so I am very far from understanding all of its aspects. Nevertheless, I think I know enough to explain with simple words what the IT (Information technology) field looks like so anybody, even boomers (sorry), can understand this really popular yet quite unknown industry.

Because this topic is quite complex, I will need a LOT of articles to cover it. But I will make sure to narrow down each one to a specific notion for more clarity.

This first article will talk about the basic concept of Application.

## What is an application?

Nowadays, everything is an application. You certainly know a lot of them: Facebook, Spotify, Google Maps, WhatsApp... The very word application is a catch-all term that has lost of lot of meaning. For the public at large, the meaning of Application is very close to the meaning of the "old", pre-smartphone era, *software* word.

**An application is a set of programs that helps the user to achieve one or several tasks.**

Let's take an example: Google Maps is an application. Its main objective is to help you locate things in the world. Note that I am not considering which device you are using to use this application.

This is an important notion to understand: applications are not only executed on mobiles. If you want to be specific, you can indeed talk about "mobile application", but all applications are not mobile-specific.

Let's go back to the Google Maps example: before existing on smartphones, you experiences Google Maps on your computer. This wasn't even a software you installed on your Windows computer with an .exe file. This was (and is still) a service you access with your web browser at google.com/maps. This still makes it an application. In this case we would say a *web application*.

## Okay so I can access the same service on mobile and with my computer... What should I understand?

Here comes the interesting part. You probably understand that engineers at Google haven't developed the same service twice, for mobile **and** the web.

We are slowly approaching the concepts of Software Architecture and I will try to make this part as understandable as possible.

Let me introduce you to the concepts of **frontend** and **backend**.

In an application, the frontend is basically the user interface, this is what you see when you type facebook.com or you open the Facebook application on your smartphone. 

This type of application cannot work on its own on your device, it always needs to retrieve some data from remote servers. Facebook, for example, needs to retrive the content of your news feed, the list of your messages, your latest notifications.

Those servers that are requested by the frontend actually host the "backend" which does the real work and calculations. Those backend services don't need graphical user interface.

You, as a final user, are only presented to frontends and will probably never be faced to backend services, except if you start learning development.

In the Google Maps example, we have two frontends : your google.com/maps web application and the Google Maps mobile application. The backend services are hosted on some obscure Google servers you will never know about.

![google_maps_frontend_backend_schenma](/assets/images/googlemaps-frontend-backend.png)

If you want a more illustrated example, imagine some cars that share the same V8 motor. You can compare the V8 motor to the backend service that responds to the conductor instructions coming from different car dashboards, which represents the frontend. This is not the best example I could come with because one motor doesn't responds to different car dashboards at the same time, but I think you got it.

I think that is enough for today, next article I will probably explain a bit longer what exactly are backend services, what is hapenning under the hood of our most well known applications.

Feel free to comment this article and share it !

---

*This is my 2nd article written for the [#100DaysToOffload](https://100daystooffload.com/) challenge !* 