---
layout: project
type: project
image: img/ecocamino/camino_logo.png
title: "EcoCamino"
date: 2021-10-22
published: true
labels:
  - Meteor Hackathon 2021
  - Software Engineering
  - 1st Place
summary: "A community application to help organize events (e.g., cleanups and workshops) and communicate through forums."
---

### Meteor Hackathon 
This year's Meteor Hackathon 2021, event was 5 days long where teams of up to 5 participants had to develop an impactful application using Meteor Framework. The teams were given freedom on what they wanted to develop and were judged on if the application was impactful, helpful in some way, and usable. I joined a team of 5 and our tech stack was Meteor, React.js, Bootstrap, MongoDB, and Galaxy. Going into the hackathon, we knew that we wanted to do something dealing with the environment. In many communities, there was a lack of information and environmental awareness. There were people who wanted to contribute but do not know about the existing efforts of non-profit organizations and ways to be involved. Our goal was to create a web application designed to be a one-way stop for those who are interested in being involved with the community and helping the environment. 

### EcoCamino and Personal Contribution 
<img class="img-fluid" src="/img/ecocamino/landing.png">

Our application was called EcoCamino, which was a platform to help users organize events such as cleanups and workshops, report trash or needed assistance, communicate through forums, as well as promote other non-profit organizations around the area. For this project, I mainly focused on the events and reporting system. There was a total of three collections, EventsCollection, UserEventCollection, and ReportCollection. For EventsCollection and ReportCollection, I implemented the basic functionality such as adding, editing and deleting events and reports. In addition with the help of some of my teammates, users were able to upload pictures of trash along with the report which really pushed our vision of the application. For UserEventCollection, I implemented functionalities such as allowing users to join and leave events. One key feature that I wanted to integrate was React Google Maps, Places, and GeoPlaces API. This allows users to specifically mark where their events will take place. When you visit the Events page, there will be a google map that shows all the markers color-coded by cleanups, workshops, and reports. 

<div class="text-center p-4">
  <img width="400px" src="/img/ecocamino/addevent.png" class="img-thumbnail" >
  <img width="400px" src="/img/ecocamino/all-events.png" class="img-thumbnail" >
</div>

<br/>

See our github.io page here: <a href="https://hacc-camino.github.io/projects/eco-camino.html" target="_blank">Eco-Camino</a>
See our project here:  <a href="https://github.com/HACC-Camino/eco-camino" target="_blank">Project Repository</a>

### Experience and What I learned 
From day one, we organized an issue management board with Github, a pull request system, and milestones for each day. All of us worked together before on previous projects so we knew what our strengths and weaknesses were. With the amazing planning and organization from my team, I was able to completely focus on Events and dedicate my time working on the functionality. I was very fortunate to have teammates that supported each other and helped set me up such as laying out the UI and obtaining the Google Maps API key. 

During these 5 days, communication played a huge role in our success in creating a working application. There were times where we had merge conflicts and files disappearing after GitHub commits but we were able to resolve them quickly. I had a great time working with my team. Whenever we were free, we would join a discord call and just work and struggle together. Everyone had the problems that they were dealing with, but we helped each other out and made the hackathon a better experience. I learned that you shouldn’t be afraid to ask others for help, as long as you understand their availability and give them enough context. Also, I realize that sometimes the initial plan might not work out and you have to adapt to the current situation at hand. There were many times where an idea didn’t pane out correctly and we had to quickly adapt to new solutions. I am very happy with the progress we made and excited for our next hackathon.