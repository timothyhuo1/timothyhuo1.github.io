---
layout: project
type: project
image: img/ecocamino/camino_logo.png
title: "EcoCamino"
date: 2021-10-22
published: true
labels:
  - Hackathon
  - Software Engineering
summary: "A community application to help organize events (e.g., cleanups and workshops) and communicate through forums. Developed during the 2021 Meteor Hackathon."
---

### Meteor Hackathon 
This year's Meteor Hackathon 2021 event was five days long, where teams of up to 5 participants had to develop an impactful application using Meteor Framework. The teams were given freedom on what they wanted to develop. The application was judged on if it was impactful, helpful in some way, and usable. I joined a team of 5, and our tech stack was Meteor, React.js, Bootstrap, MongoDB, and Galaxy. Going into the hackathon, we knew that we wanted to do something dealing with the environment. In many communities, there was a lack of information and environmental awareness. We knew many people wanted to contribute but did not know about the existing efforts of non-profit organizations and ways to be involved. Our goal was to create a web application designed to be a one-way stop for those interested in being involved with the community and helping the environment. 

### EcoCamino and Personal Contribution 
<img class="img-fluid" src="/img/ecocamino/landing.png">

Our application was called EcoCamino, a platform to help users organize events such as cleanups and workshops, report trash or needed assistance, communicate through forums, and promote other non-profit organizations around the area. For this project, I mainly focused on the events and reporting system. There were three collections/tables, EventsCollection, UserEventCollection, and ReportCollection. For EventsCollection and ReportCollection, I implemented the basic functionality such as adding, editing, and deleting events and reports. In addition, users could upload pictures of trash along with their reports, which pushed our vision of the application. For UserEventCollection, I implemented functionalities, such as allowing users to join and leave events. One key feature that I wanted to integrate was React Google Maps, Places, and GeoPlaces API. These APIs allow users to mark the location of the events. When you visit the Events page, there will be a google map that shows all the markers color-coded by cleanups, workshops, and reports. 

<div class="text-center p-4">
  <img width="400px" src="/img/ecocamino/addevent.png" class="img-thumbnail" >
  <img width="400px" src="/img/ecocamino/all-events.png" class="img-thumbnail" >
</div>

<br/>

See our github.io page to learn more about our project here: <a href="https://hacc-camino.github.io/projects/eco-camino.html" target="_blank">Eco-Camino</a>

See our project repository here:  <a href="https://github.com/HACC-Camino/eco-camino" target="_blank">GitHub</a>

Articles about our project: <a href="https://blog.meteor.com/meet-team-haccamino-the-2021-meteor-hackathon-winner-acb74136e986" target="_blank">Meteor Blog</a> and <a href="https://www.hawaii.edu/news/2021/10/28/hackathon-students-victorious/" target="_blank">University of Hawaii News</a>

### Experience and What I learned 
From day one, we organized an issue management board with Github, a pull request system, and milestones for each day. I was very fortunate to have teammates that supported each other and knew what our strengths and weaknesses were.

During these 5 days of the hackathon, communication played a huge role in our success in creating a working application. There were times when we had merge conflicts and files disappearing after GitHub commits, but we resolved them quickly. Everyone had issues they were working on, but we made time and effort to help each other out and made the hackathon a better experience. I learned that sometimes the initial plan might not work out, and you must adapt to the current situation. I am happy with the progress we made in such a short amount of time.