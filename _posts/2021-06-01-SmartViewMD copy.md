---
layout: post
title: SmartView MD
---

> Creating a design system, marketing site and conducting research for a consolidated web based portal for medical providers to review patient vitals shared from disparate selected 3rd party medical devices.

An issue that many primary care clinics were challenged with worldwide, during the COVID-19 pandemic, was having their patients be responsible for manually recording vitals from several medical devices and properly documenting those records for clinic visits. 

-----

## The Proposal

A mobile application which is a consolidated web based portal for medical providers to review (monitor and receive automated alerts of) patient vitals shared (via patient smartphones) from disparate selected 3rd party medical devices (e.g. blood pressure monitor, glucose monitoring, fingertip pulse oximeter, self monitoring blood glucose meter, and peak flow meter to monitor respiratory conditions such as asthma.)

![placeholder](http://placehold.it/800x400 "Large example image")


This solution helps clinics/physicians and transforms their patients’ vital recording process from one that is reactive to proactive.

The app, entitled *SmartView MD*, was to set precedence for the development of projects in the future of our parent company [Belle IT](https://belleit.net/) therefore, this quote was a mantra throughout the development process: 

*Because of the size and potential scope of this project, it was important that we were deliberate and intentional when phasing the different parts of the process. We set out to follow a process cycle that would allow for the right amount of definition, exploration, and reflection:*  

Define → Explore → Refine → Build → Learn

<cite>&mdash; [Emily](http://emilybrick.me/) <small>Designer @ Github</small></cite> 

<br/>
## Deliverables

1. Create a UML for SmartView MD application.
2. Develop a design system that is consistent with Belle IT, INC.
3. Launch a marketing site that provides information about SmartView MD and allows for clinics/physicians to request demos and inquire about the SmartView MD application.

<br/>

-----

## UML

To start, I mapped out the different components of the application which was inspired by a [course](https://www.linkedin.com/learning/react-cloud-powered-apps-with-firebase) called 
*React: Cloud-Powered Apps with Firebase*, taught by Victor Mejia offered on [LinkedIn Learning](https://www.linkedin.com/learning/).

We used the authentication capabilities of Firebase for user authentication and the cloud storage capabilities of Firestore for storing patient vitals and physician/patient information.
The application is deployed using Firebase hosting. Below is an initial sketch and the UML for *SmartView MD <small>v1</small>*:

![placeholder](http://placehold.it/800x400 "Large example image")

## Design System

With our objectives in mind, I began ideating solutions through visual experimentation and mockups. Through generative design exercises, conversations with patients/physicians, and exploration of current medical device applications (that communicate with medical devices via bluetooth), I created a number of concepts to consider that would help define the visuals and layouts of our application.

*Iconography*

I implemented the use of a collection of icons for React called Material Design Icons which helps ensure readability and clarity at large sizes for SmartView MD’s older audience of patients.

![placeholder](http://placehold.it/800x400 "Large example image")

We also worked on a naming convention for all of our assets and a color palette to be used across all of our products and sites:



*Color system*
 
We ended up defining a simple three color palette that, in combination with the clean minimal layouts defined in the design system, emphasize the order Belle IT  brings to clinics.

![placeholder](http://placehold.it/400x200 "Large example image")

-----

Online Presence

After many iterations, here’s [SmartView MD](https://smartviewmd.com/)! You’ll notice that the design decisions of the marketing site were informed by the design system of the application. 

<script async class="speakerdeck-embed" data-id="e89b88f117de46a48455b2f369517431" data-ratio="1.29456384323641" src="//speakerdeck.com/assets/embed.js"></script>
