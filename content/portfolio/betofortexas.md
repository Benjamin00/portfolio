+++
date = "2018-11"
weight = 110
description = "A native IOS app to increase volunteerism"
title = "Beto for Texas"
draft = false
bref= "Built an App for the Beto for Texas Senate Campaign"
toc = true
+++

## Background
This app was developed over the course of the summer of 2018. I had the idea to build an app for the team when I realized there was none, I was frustrated by the state of politics in Texas, and wanted to volunteer to build something for a cause I cared about. When I wasn't taking classes I was communicating and coordinating solutions for the app with campaign staff, and learning how to code with swift and Xcode from scratch. Firebase was used for a backend solution, and real-time updates were possible. What follow are examples of the different pages of the app, and a description of why they were needed and how they were made.

### Nearby Events
![StartEvents](https://user-images.githubusercontent.com/8885471/57964753-71023e00-78ef-11e9-9bf2-6d7711f4ffbf.gif)

This page would populate with the location and upcoming event information for volunteering oppoutunities around the users current location. Mapping the volunteer events would help the users get an idea for just how many upcoming events there were, and the users could RSVP to events directly through the app. The data was pulled through an API developed for the Beto for Texas team, and has since been removed from this legacy code for privacy reasons. 

### Volunteer On-Boarding
![VolunteerMenu](https://user-images.githubusercontent.com/8885471/57964754-71023e00-78ef-11e9-8cc2-66a7fb214977.gif)

This menu provided an on-boarding guide and was developed with help from the volunteer coordinators on the campaign. Condensing the information and optimizing the path to becoming a volunteer would ideally attract more people who were interested, but not really to invest a lot of time into looking up how the process works. Having all the resources at hand for the volunteers provided a simple solution to people more casually interested in entering the policial world.

### Issues
![Issues](https://user-images.githubusercontent.com/8885471/57964752-71023e00-78ef-11e9-9c4e-9e15b2b3f40f.gif)
<img width="625" alt="Screen Shot 2019-05-17 at 10 27 17 PM" src="https://user-images.githubusercontent.com/8885471/57965012-f3403180-78f2-11e9-9167-dc40c4c3becb.png">

A firebase backend tied into the app allowed for quick changes that would propagate to all users. Each list could have elements added or removed and would be reflected instantly on all phones. This feature was developed to mirror the Beto for Texas website which included talking points. Ideally this feature on the phone would be used to help spark conversations, and have evidence for the candidates stance on certain issues. 

### Donate
![Donate](https://user-images.githubusercontent.com/8885471/57964751-71023e00-78ef-11e9-9cca-cbc23253de14.gif)

This was just a simple webpage redirect, as no native solution could be developed through a third party API
