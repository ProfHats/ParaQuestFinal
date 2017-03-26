# Assignment 1 - ReactJS app.
ParaQuest App

Name: ... your name ...
Eoin Moloney, Student 20053732

## Overview.
...... A statement of the app concept and objectives (about a half-page) ........

The App is a browser-based game. It consists of a number of interconnected 'Pages', which the user can navigate between via interacting
with the various Components on screen. Each Page includes a text description of a particular environment, and a list of possible options
that the user can take. Sometimes options are simple text links, sometimes they are buttons. Each page also contains an element that allows
them to go back to the previous state. The user has statistics (Strength, Brains, and Charm), which are used to pass the different tests.
If the user passes a test, their stats may increase, while some circumstances can result in their stats being reduced. The player also has
a second set of statistics, "Menaces", which track harm done to their character (Injury, Stress, and Scandal). Certain circumstances (such
as attempting a test and failing it) can increase Menaces. If a Menace exceeds a certain amount, a penalty will be applied to the player
(such as dying and needing to restart the game).

 . . . . . List of user features (excluding user registration and authentication) . . . . 
 
 + Dynamic Routing through parameterised URLs, which are tracked by way of a complex array of interconnected objects
 + Randomisation, carried out by API and used together with stats to determine the outcome of tests. 


## Installation requirements.
+ ReactJS v15.4.2
+ Bootstrap 3
+ create-react-app tool

After cloning the app from the repository, one only needs to run it via 'npm start'. No extra steps need to be taken.


## Data Model Design.

Diagram of app's data model (see example below) AND/OR a sample of the test data used (JSON or equivalent).

![][image1]
(model)

Use meaningful sample data. Briefly explain any non-trivial issues.

## App Component Design.

A diagram showing the app's hierarchical component design (see example below). 

![][image2]
(design)

## UI Design.

. . . . . Screenshots of app's views (see example below) with appropriate captions (user regeneration and login views, if implemented, can be omitted) . . . . . . . 

![][image3]
(screen)

## Routing.
. . . . List each route supported and state the associated view . . . . . 

+ /:advID - routes the player to an AdventureView, with data based on the advID

## Extra features

. . . . . Briefly explain any non-standard features, functional or non-functional (e.g. user registration, authentication) developed for the app . . . . . .  
The app also features a random number generator, created in the API via the math.random method. This is used to determine whether or not a user
passed a test, when they take one.


## Independent learning.

. . . . . State the non-standard aspects of Angular (or other related technologies) that you researched and applied in this assignment . . . . .  
-The proper use of browserhistory.push() to programmatically go to a certain route
-

[image1]: ./model.png
[image2]: ./design.jpg
[image3]: ./screen.png