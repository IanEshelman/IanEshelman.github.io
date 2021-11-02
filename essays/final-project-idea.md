---
layout: essay
type: essay
title: "Final Project Idea"
date: 2021-11-02
labels:
  - Software Engineering
  - Meteor
---

Ian Eshelman, Jay Ramos, Jon Valencia, Ju-Bin Choi

# Overview

## Problem
Parking on UH Manoa campus can get confusing with certain lots being open during different times of the day and other lots being closed due to maintenance. Unless you check your email religiously, it can be difficult to keep track of where on campus you will be able to park for the day.


## Solution
To solve this problem, we can develop an app that keeps track of the variables that may change the lot status - what time it is, the status of maintenance, if there is an event, what zone pass the user has - and use those variables to display the lots that you can park in.


# Mockup Page Ideas
* Landing page
* User home page
* Admin home page
* Available parking lot page
* Search parking lot page


# Use Cases
* New users will go to the landing page, log in, get to the home page, set up a profile with their parking pass if they have one.
* Users, when parked, will update their status to where/what time they parked in the landing page.
* The available lot page will show what lots are currently available to the user, as well as notes for why certain lots are closed (due to maintenance, events, etc)
* If the user does not have a pass linked to their account, they will have the option to select an open lot that they wish to park in, and instructions for purchasing a day pass will be displayed.


# Beyond the Basics
* Keep track of if you have a ticket to a certain event that would allow you to park in a closed-off lot
* Dynamically updates the zones that you can park in based on time of day, or if it’s a weekday, weekend, or holiday
