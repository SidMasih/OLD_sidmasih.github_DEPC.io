---
layout: page
title: Projects
---
<style>
.media {
  // Proper spacing between instances of .media
  margin-top: 15px;
  position: absolute;
   right: 30px;
   top: 4em;


  &:first-child {
    margin-top: 0;
  }
}

@media (max-width: 1110px) {
  .media {
    display: none;
  }
  .media-left,
.media > .pull-left {
  display: none;
}
}

}

.media-right,
.media > .pull-right {
  padding-left: 10px;
}

.media-left,
.media > .pull-left {
  padding-right: 10px;
  height: auto;
   width: auto;
   max-width: 150px;
   max-height: 200px;
}

.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}

.media-middle {
  vertical-align: middle;
}

.media-bottom {
  vertical-align: bottom;
}


.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}

.media-list {
  padding-left: 0;
  list-style: none;
}
</style>

<div class="media">
  <img src="https://raw.githubusercontent.com/SidMasih/sidmasih.github.io/master/sidphoto.jpg" alt="Sid Masih" class="pull-left">
  <div class="media-body">
    <h4 class="media-heading">Sid Masih</h4>
    <ul class="media-list">
      Quick Links! 
      <li><a href="mailto:sid.masih@berkeley.edu">Email</a></li>
      <li><a href="https://github.com/SidMasih/">GitHub</a></li>
      <li><a href="https://drive.google.com/file/d/0B-jZSHo3nEE7cmZJLVhTX0l2MHM/view?usp=sharing">Resume</a></li>
      <li><a href="https://www.linkedin.com/in/sid-masih-65b54382">LinkedIn</a></li>

    </ul>
  </div>
</div>
<p class="message">
  Here are some of the projects I have recently worked on! Please take a look. To students potentially cheating on school projects ... don't... you will get caught. If you have found this website you must be feeling pressured. I understand how you feel (I was once there). Go to office hours and ask your peers, but do not copy code! 
</p>

## Berkeley CS 169 Team Manager

* Building web app for students to find and select teams and assign discussion sections and course entry priorities
* Allow students to create and build teams and choose discussion sections for CS 169, a project based class
* Use Stable Marriage algorithm to help match discussion sections with student prefferences 
* Distributes course passwords for enrollment and allows EECS staff to easily manage students 
* Built in Rails, Bootstrap, and SQL
* Tested with Cucumber, RSpec, Travis CI, and Capybara
* Built with 5 person team, focused on proper application developement with Agile Development 
* Currently used by about 200 students during class scheduling
* Check out the code: [Repo](https://github.com/adnanhemani/enrollme)

## Berkeley EECS Corporate Recruiting Portal

* Building web app, with a couple of friends, for student groups and EECS staff to manage scheduling of company events in one unfied portal
* Allow groups to add info sessions, companies to request info sessions, and staff to aprove, deny, and view the status of info sessions
* Implementation should reduce company info session event conflicts, such as when Goldman Sachs, Facebook, and State Farm all were scheduled accidently on the same day
* Distributes course passwords for enrollment and allows EECS staff to easily manage students 
* Built in Rails, Bootstrap, and SQL
* Currently a side project, hope it will get aproved for use in EECS 
* In advanced planning stages, code not ready or clean enough for viewing! 

## Bearmaps
* Web mapping application, inspired by GoogleMaps and OpenStreetMap project 
* Included a map of Berkeley with presized tiles from OpenStreetMap, image rastering, image zoom, route search, and rendering highlighted routes on map
* Implement A* and quadtree image zoom 
* Built in Java and Maven
* Check out the code: [Download]({{ site.url }}/download/BearMaps.zip)
* Do not share this code (it is not on github for a reason!)

## TextEditor
* Built a text editor from scratch 
* Implemented features such as cursor movement, word wrapping, backspace, calculating new lines, open files, save files, arrow movement, mouse input, window re-sizing, undo, redo, and various font size options.
* Check out the code: [Download]({{ site.url }}/download/TextEditor.zip)
* Do not share this code (it is not on github for a reason!)

## MIPS Assembler and Linker
* Impelement a large subset of MIPS Assembly Language and translate it into executable machine code
* Include support for pseudo instructions and error detection
* Includes linker to translate .out files into fully executable files
* Assembler built in C, Linker built in MIPS
* Code witheld by request, email me directly to see this project! 

## Journey Christian Fellowship Website
* Built new front end information website for my church
* Bootstrap for front end, Jekyll for CMS
* Deployed on Heroku
* Check out the code: [Repo](https://github.com/SidMasih/churchwebsite)

## Berkeley Computer Science Undergraduate Association Office Message Board
* Built HTML message board for my club hosted on Github Pages 
* Displays upcomming events as well as company sponsors
* Jekyll for CMS
* Check out the code: [Repo](https://github.com/csuabb/csuabb.github.io)

## Linear Algebra Library in Java
* Built new matrix data type for education purposes, replacing old library in C++ for high school teacher
* Completed the project with operations such as add, subtract, multiply matrices, invert matrices, transpose matrices, row reduce matrices, find eigenvalues using QR, find vector projections, and perform regression with different sorts of functions given a set of points
* Students are expected to complete as much as possible, with the best students being able to implement regressions  
* Check out the code! [Repo](https://github.com/SidMasih/LinearAlgebraOperations)

## Drakify - Built at CalHacks 2.0 
* In 36 hours, created a web application that returns the video output of a song based on the speech input (lyrics or title) given by user
* Created an algorithm to search for lyrics ‘phrase-by-phrase’ reducing search time and improving accuracy.
* Worked on intergrating Rap Genius api with hack
* Awarded "joke" award for best use of [Drake](http://www.drakeofficial.com/) in a Hack. While not a very serious award, we did win something!
* My first hackathon! :) 
* Built using Node.JS, RapGenius, and Google Web Speech 
* Check out what code looks like with 36 hours of no sleep and a case of Red Bull (it's not that great but hey it works!) [Repo](https://github.com/rrtigga/drakify) 

## The City Club of San Diego App
* App built for high school teacher's friend who wanted a way to easily push information from an existing blog to a mobile app
* Used RSS parsing to pull the article and put it into a mobile view of the blog
* Focused on ease of use for my teacher's friend, since he was not technology adept at other CMS
* Built for iOS as an internal tool
* Check out the code! [Repo](https://github.com/SidMasih/City-Club-App)





Thanks for reading! Email me if you have any questions. 
