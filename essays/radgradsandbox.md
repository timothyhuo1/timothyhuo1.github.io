---
layout: essay
type: essay
title: Building my personal RadGrad2 sandbox 
# All dates must be YYYY-MM-DD format!
date: 2021-05-21
labels:
  - Software Engineering
---

This summer's Research Interns at RadGrad2 was tasked to complete practice exercises to get familiarized with the RadGrad system. This is my experience with this task and the problems I faced.

# Task 1: 

For Task 1, we started off with a simple exercise that many coders are familiar with, which is “Hello, World”. In this task, we had to display Hello World using RadGradSegment and RadGradHeader components. For segments in the RadGrad system, the style is an icon on the left side of the title and black line separating the title and body.  

<img class="ui image" src="../images/sandbox/Task1-task.png">

This was my first time using fomantic-ui to find the icon needed for this task. The advice and hints I got from the session helped me complete this task smoothly. Here is the code:

```<RadGradSegment header={<RadGradHeader title='TASK 1: HELLO WORLD' icon='globe americas'/>}> Hello World </RadGradSegment>```

#Task 2:

For Task 2, we are creating another RadGradSegment detailing the user who is currently logged in and the user that appears in the URL. The one challenge that I had was getting the username in the URL. With the help from other interns, I was directed to a hook called UseParams that grabbed the username in the URL. 

``` const { username } = useParams(); ```

Same user logged in:

<img class="ui image" src="../images/sandbox/Task2-user.png">

Different user logged in:

<img class="ui image" src="../images/sandbox/Task2-admin.png">



