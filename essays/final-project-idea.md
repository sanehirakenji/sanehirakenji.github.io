---
layout: essay
type: essay
title: "Final Project Idea"
date: 2022-03-27
labels:
  - Software Engineering
  - Meteor
---
<i>In collaboration with Michael Ito and Johanan Leoncio.</i>

# Overview
<i>The problem: </i> Many students at UH commute to school via car to "save money" yet with rising gas prices and the hybrid UH classes, driving to school alone can be inefficient and costly to both the student and the economy.

<i>The solution: </i> CarpoolUH is an application for University of Hawaii students, allowing drivers to offer rides and riders to search for rides in their area that work for their schedules.

# Approach 

When a user first creates an account with CarpoolUH, they are met with an account creation field with profile fields including their name, major, a brief bio, a picture of themselves, and most importantly, their hometown and whether they are a driver or a rider. There will also be a field with the best way to contact the driver in question to allow individuals to communicate with eachother about their ride situation.

These profile fields will be public on the website as the user's individual profile page, which will be displayed on either the Riders page or the Drivers page based on what the user has picked.

The two main usages of CarpoolUH will be:
<ol>
  <li>Allowing UH students to view drivers and riders who could lend or receive rides based on both time and location convenience to communicate with eachother.</li>
  <li>Allow people in emergency situations to find other users who may be able to give them a ride through the "Fast Ride" feature.</li>
</ol>

Regarding the first usage of CarpoolUH, the drivers and riders pages will be nearly identical with the only difference being the content of the page itself. Both pages will contain all profiles listed under their respective roles. The top of the pages will also allow the user to filter out the list of profiles to fit their requested times or place. Clicking on any of the listed profiles will take the user to that user's specific profile page. The drivers page will have an exclusive section that asks the user if they are in need of a fast ride, and will link them to the "Fast Ride" page.

The second usage of CarpoolUH is utilizes a form that allows a user to ask for a ride from anyone who is willing to give them one. The form asks for the users requested leave/pickup time as well as where they are getting picked up from or going to. The user is then added to another list of individuals on the "Fast Ride" page, and will wait to see if a driver is able to take them to where they need to go.

Although the application can be very situational, when used correctly it can provide UH students in need of rides or who are short on money an alternative method of getting around besides public trasportation and mobile-taxi applications like Uber or lyft.


# Mockup Page Ideas
Some possible mockup pages include:
<ul>
  <li>Landing Page</li>
  <li>User Home Page</li>
  <li>Admin Home Page</li>
  <li>User Profile Page</li>
  <li>Riders Page</li>
  <li>Drivers Page</li>
  <li>"Fast Ride" Page</li>
  <li>"Fast Ride" Request Form Page</li>
</ul>

# Use Case Ideas
<ul>
  <li>New user goes to the landing page, logs in, gets home page, creates profile as a driver.</li>
  <li>New user goes to the landing page, logs in, gets home page, creates profile as a rider.</li>
  <li>Admin goes to landing page, logs in, gets home page, allowed access to edit all pages and monitor driver and rider profiles.</li>
  <li>Rider goes to landing page, logs in, goes to Drivers page and finds right driver, goes to driver profile page to find info.</li>
  <li>Rider goes to landing page, logs in, goes to Fast Ride Request Form Page, fills out form.</li>
  <li>Driver goes to landing page, logs in, finds a suitable rider on the Fast Ride Page, goes to rider profile and contacts rider.</li>
</ul>

# Beyond the Basics
<ul>
  <li>Some sort of incentive system to encourage drivers to look for suitable riders in the Fast Ride Page.</li>
  <li>A rating system for drivers as an added decision making factor above location and time.</li>
  <li>Application-based messaging.</li>
  <li>Real-time "drivers leaving soon" page that shows drivers scheduled to leave in the next 20 minutes.</li>
</ul>
