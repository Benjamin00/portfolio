+++
date = "2018-11"
weight = 110
description = "Lead Campaign App Developer: Built with Swift and Firebase"
title = "Beto for Texas"
draft = false
bref= "A native IOS app designed to increase volunteerism"
toc = true
author = "Benjamin Hill"
+++
## Background
This app was developed over the course of the summer of 2018. I had the idea to build an app for the team when I realized there was none, I was frustrated by the state of politics in Texas, and wanted to volunteer to build something for a cause I cared about. When I wasn't taking classes I was communicating and coordinating solutions for the app with high ranking campaign staff, and learning how to code with Swift and Xcode. Firebase was used for a backend solution, and real-time updates were possible. What follow are examples of the different pages of the app, and a description of why they were needed and how they were made.

## Nearby Events
This page would populate with the location and upcoming event information for volunteering oppoutunities around the users current location. Mapping the volunteer events would help the users get an idea for just how many upcoming events there were, and the users could RSVP to events directly through the app. The data was pulled through an API developed for the Beto for Texas team, and has since been removed from this legacy code for privacy reasons. 
<figure>
<video controls autoplay loop class="center-image">
 <source src="/img/beto1.mp4" type ="video/mp4">
</video>
</figure>

## Volunteer On-Boarding
This menu provided an on-boarding guide and was developed with help from the volunteer coordinators on the campaign. Condensing the information and optimizing the path to becoming a volunteer would ideally attract more people who were interested, but not really to invest a lot of time into looking up how the process works. Having all the resources at hand for the volunteers provided a simple solution to people more casually interested in entering the policial world.
<figure>
<video controls autoplay loop class="center-image">
 <source src="/img/beto2.mp4" type ="video/mp4">
</video>
</figure>

## Issues
A firebase backend tied into the app allowed for quick changes that would propagate to all users. Each list could have elements added or removed and would be reflected instantly on all phones. This feature was developed to mirror the Beto for Texas website which included talking points. Ideally this feature on the phone would be used to help spark conversations, and have evidence for the candidates stance on certain issues. 
<figure>
    <video controls autoplay loop class="center-image">
 <source src="/img/beto3.mp4" type ="video/mp4">
</video>
</figure>

<figure>
    <img width="625" alt="Screen Shot 2019-05-17 at 10 27 17 PM" src="https://user-images.githubusercontent.com/8885471/57965012-f3403180-78f2-11e9-9167-dc40c4c3becb.png">
</figure>

## What I Learned
This was my first foray into developing for a professional organization, and I certainly learned a lot. 
Firstly I needed learn how to maximize my time management, because I was taking classes over the summer, which amounted to 20 hours a week just sitting in class, not to mention the homework that was assigned. 
Additionally I learned how to communicate, and how best to prioritize tasks that a customer gives you. I learned that customers aren't always available to answer questions, and that it's best to use more of an Agile methodology. This meant making some small assumptions about what the customer wanted in order to deliver a working prototype which could be refined. 

The biggest challenge for me was working with the JSON calls to the CloudFlare server that was hosting the original "Beto for Texas" website. I needed to ensure that the calls could be made asyncronously so any new data would be populated immediately if it were in the frame of the users screen. There were thousands of events to map, so optimizing how the data was managed was important.

Finally, I learned the thrill of sucessfully finishing a months-long project by myself. When I had finally finsihed the app I was ecstatic! It was a great experience, and I got to work with some great people along the way.
