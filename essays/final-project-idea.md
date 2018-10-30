---
layout: essay
type: essay
title: "Final Project Idea"
date: 2018-10-30
labels:
  - Software Engineering
  - Meteor
  - Co-authors: Leah-Mei Villanueva and Michael Boyle
---
# Project: UH and Chill

## Overview
The Problem: The University of Hawaii at Manoa is a large campus that consists of thousands of students who we may or not meet.  
The Solution: The UH and Chill app, which is limited to UH Manoa students only, will provide a central networking service where students can meet based on common interests and what not.

## Approach
For this app, you will create a way to organize and present available menu items for all campus locations in a unified manner. There are three roles: Users, who can login to establish preferences for their food choices; Vendors, who can login to specify their choices of the day or otherwise modify their profile data; and Admins, who also can login to define users as having the vendor role and otherwise administer the system.

Your app should provide a consolidated, easy to use source directory of menu items taken from the UHM Food Vendors and Manoa Dining Services. In addition to organizing menus by vendor, you should also organize the data by menu item type (ethnicity, vegan, etc.).

Users should be able to indicate preferences and/or food types to exclude in their profile, which will help the app to present more useful choices.

For places with weekly or daily changing menus, vendors should be able to login to provide this data.

Note: if you choose this idea for your final project, you cannot name it “Manoa Munchies”. Come up with a different name for your final project.

Some possible mockup pages include:

* Landing page
* User profile page
* Admin home page
* Registration page
* Sign in page
* Sign out page
* Events page

## Use case ideas
Whether or not the following bullet points list all pages or not, the completed use case should show an end-to-end scenario of using the system.

* New user goes to landing page, logs in, gets home page, sets up profile. (How do they learn how system works?)
* Admin goes to landing page, logs in, gets home page, edits site for inappropriate things, delete users.
* User goes to landing page, logs in, looks for interests.
* User is notified of events related to interests

## Beyond the basics
After implementing the basic functionality, here are ideas for more advanced features:

* Notify students via email, twitter, SMS when particular event choices are available.
* Automated updating of relatable people. For example, they agree to post their daily specials via twitter, and your application retrieves their twitter feed and uses that data to update their page.
* Allow students to rate events/person.
