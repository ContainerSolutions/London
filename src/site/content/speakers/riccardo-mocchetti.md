---
title: "Designing serverless applications like microservices is a bad idea"
description: "Today's most popular way to design a new application or to refactor an existing one is to think about it as a set of microservices. We follow well-established guidelines that lead us to a design where services have very well defined boundaries and communicate with other services for data that they need, but they don't own.
This design pattern works well with non-serverless technologies, but what happens when we apply it to a serverless application? What does data ownership mean when we deal with functions instead of services? And what is the price we pay when design service to service communication to preserve data ownership?

Riccardo spent the last year working on a serverless platform to collect data from wearables. In this talk, he will address these questions showing how and why following microservices guidelines for data partitioning led to the poor performance of the platform, and how his team changed the design to deliver a stable and performant solution."
speaker: Riccardo Mocchetti
bio: "Riccardo builds stuff in the cloud at Container Solutions. In the last three years playing with serverless technologies, he developed several serverless platforms, primarily to gather data, from many different sources, from websites to wearables.

When he is not working, he likes to draw caricatures of real and fictional characters. Sometimes he plays the piano, but he is not good at it."
image: /images/speakers/Riccardo_Mocchetti.jpg
twitter: rmokk
---