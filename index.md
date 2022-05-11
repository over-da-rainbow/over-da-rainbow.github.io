# Over Da Rainbow

## Table of contents

* [Overview](#overview)
* [Deployment](#Deployment)
* [Goals](#goals)
* [Deployment](#Deployment)
* [Milestones](#Milestones)
* [Developer Guide](#Developer-guide)
* [User Guide](#User-guide)
* [Community Feedback](#Community-Feedback)

## Overview

Over Da Rainbow is a web application for University of Hawaii students to step outside their dorms and classrooms and explore beautiful sceneries and destinations offered here.

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

## What the System will Provide

* Home page where all users are funneled to
* Users can login and keep track of all the places they’ve already explored
* Suggested page where users can surf through different suggested destinations for their next experience.
* Anonymous ratings under each destination to help future explorers.
* Choice to leave comments under the destination.
* “Volunteering” tab for people who need volunteer hours or want to help community
* Tags for each location about what kind of activity  (ex. Beach, hike, etc.)


## Deployment

This web application is deployed through digital ocean and available [here](https://overdarainbow.xyz/) or at https://overdarainbow.xyz/


![ci-badge](https://github.com/over-da-rainbow/over-da-rainbow/workflows/over-da-rainbow/badge.svg)


## Goals

* Create a user friendly outdoor guide web application that allows UH students/staff to safely discover Oahu’s best kept secret spots.
* Give students ideas for outdoor activities to ease their minds from their classes.
* Provide volunteer opportunities for students to help the community and enhance their resumes.
* Coordinate plans with friends by using our bulletin page.


## Developer Guide

#### This section provides information pertaining to Meteor developers wishing to use this code base as a basis for their own development tasks.

### Installation

First, install Meteor.

Second, visit the Bowfolios application github page, and click the “Use this template” button to create your own repository initialized with a copy of this application. Alternatively, you can download the sources as a zip file or make a fork of the repo. However you do it, download a copy of the repo to your local computer.

Third, cd into the bowfolios/app directory and install libraries with:

`$ meteor npm install`

Fourth, run the system with:

`$ meteor npm run start`

After completing the following steps, the application should appear at http://localhost:3000 on your local machine.

### Adding a new Location

First, login to your deployment of Over Da Rainbow using an admin account.

![admin-login](https://user-images.githubusercontent.com/97726557/165465087-9c3c5f6c-7b38-40d0-932d-750aa0e63f40.png)

Second, click on the account name on the right of the navbar to open a dropdown menu and click on "Add Location"

![addLocation-navbar](https://user-images.githubusercontent.com/97726557/165465443-2f702b25-d4e2-43a5-8d16-2e0dd66f9a2b.png)

Third, input the location name, type of location, description of the location, the actual physical location, and a link to an image of the location to create a new location.

![addLocation-example](https://user-images.githubusercontent.com/97726557/165465990-e2411a7f-64ec-4a6e-8b55-05f33f53b55c.JPG)

### Edit or Delete a Location

First, login to your deployment of Over Da Rainbow using an admin account.

![admin-login](https://user-images.githubusercontent.com/97726557/165465087-9c3c5f6c-7b38-40d0-932d-750aa0e63f40.png)

Second, navigate to the location page of the location that you want to edit or delete

![edit-delete](https://user-images.githubusercontent.com/97726557/167368247-7ebbf700-ab65-4f6c-b739-f854c7b0d504.png)

To edit a location, click the "Edit Location" button and you will be taken to a page with a pre-filled form for that location that can be changed to update fields on for the location. After changing at least one field you can click the "Submit" button to update the information for that location.

![edit-location](https://user-images.githubusercontent.com/97726557/167368637-bb276243-bf6d-47b0-abf2-1cb5614e67a4.png)

To Delete a location, click the "Delete Location" button and you will be taken to the list page for that type of location (Beach, Hike, Spot, etc.) with the deleted page now gone.



## User Guide

This section provides a crash course on using our application to the full extent of its capabilities...



### New-User Landing page

Upon arriving at our site, users will be presented with this screen: 

![landing-mockup](https://user-images.githubusercontent.com/96926588/165230731-e69cf994-30e0-494c-931f-d34a7180aa48.png)

![landing-mockup](https://user-images.githubusercontent.com/96926588/165230607-085e9b61-eed1-4c24-b6b2-5c14652fbdad.png)




From here, Students, Staff, and anyone in the University of Hawaii system will be able to create an account.

First click the "Login" button in the upper right hand corner, then choose the "Sign-up" option if you are a new user, or the login button if you are a returning user.

You will be redirected to this sign-up form where you will be prompted to enter your school email and create a password for your over-da-rainbow account.




![sign-up-page](https://user-images.githubusercontent.com/96926588/165232694-8f59fc11-7030-4a3d-97b0-04a0e8cd7516.png)



Upon entering the appropriate information and creating the account, you should be taken to our beautiful landing page. 

From here you can navigate through our selection of outdoor activities including beaches, hikes, scenic points, campus spots, and even volunteer opportunities. 


### User logged in Landing page

![landing](https://user-images.githubusercontent.com/96926588/165230345-7e9bad4a-9702-431f-8ff2-7be8890d1354.png)



### Beach Page

A variety of beaches around the island for you to choose from.

![beachPage-mockup](https://user-images.githubusercontent.com/96926588/167752258-608a96ec-e6ea-449a-8263-5644275048e5.png)



### Hike Page

Sunny skies, thick foilage, or flowing waterfalls. We have something for everyone on our hikes page

![hikePage-mockup](https://user-images.githubusercontent.com/96926588/167752308-91568f6a-1a1c-4dff-9dc0-eaa40aeb2455.png)


### Scenic Views Page

Breathtaking views from any corner of the island

![scenicPage-mockup](https://user-images.githubusercontent.com/96926588/167754530-9a85e853-d966-4475-93cb-a3716e5d7f94.png)



### Campus Page

Cool places to hangout with your friends, study, or grab a quick snack.

![campusPage-mockup](https://user-images.githubusercontent.com/96926588/167754557-2ea5da95-8a92-4d32-afe7-3bed658b3a18.png)




### Volunteer Page 

It has never been easier to find volunteer opportunities to beef up your resume or be a productive member of society. Get your volunteer hours buddy

![volunteerPage-mockup](https://user-images.githubusercontent.com/96926588/167752345-048310ae-c590-44cb-9ace-5feac730bc4c.png)




### Just Click!

When Navigating through any of the pages listed above, simply click on the location you want to learn more about and we will redirect you to another page with more information!


<img width="1440" alt="Screen Shot 2022-04-26 at 2 25 43 PM" src="https://user-images.githubusercontent.com/96926588/165414303-e4735749-ad28-445f-b2f2-987ac2c19a07.png">


### Bulletin Messages and Events

To see the message board click the Bulletin dropdown in the navbar and then "Messages" where you can see what other users have posted or post your own message for others to see.

![messages](https://user-images.githubusercontent.com/97726557/167372926-bd2764af-ab1b-497d-ba38-c941fefe2c88.png)

To see the events page click the Bulletin dropdown in the navbar and then "Events" where you can see events planned by other people or plan an event for others to go to.

![events](https://user-images.githubusercontent.com/97726557/167373903-a2daa6d3-89aa-4edb-b6f3-5e1f1fd767fb.png)



## Community Feedback

Students from the UH community have used our application and found it very useful. If you want to provide feedback to help us further develop our system, we would love to hear your feedback. Please take a couple of minutes to fill out our [Over Da Rainbow Feedback Form.](https://forms.gle/j1imHUd9JbaM7HbN6)

Real User testimonials:

"I used this application to find nice beaches on the east side." -Reed

"Left a couple reviews to share my experience with future visitors." -Campbell

"So cherrreh the chill campus spawts, CHEEEHOOO!" -Davin



## Team Contract

[Team Contract](https://docs.google.com/document/d/1HXy_bQAs_UlvUBsboftt7dbf-zyPfi7BWICM8ahgs0M/edit)


## Milestones

Management and development goals for this project are separated into three major milestones.
Each milestone has a corresponding project board to ensure all tasks are completed.
Milestone boards listed below:

[Milestone 1 project board](https://github.com/over-da-rainbow/over-da-rainbow/projects/1)

[Milestone 2 project board](https://github.com/over-da-rainbow/over-da-rainbow/projects/2)

[Milestone 3 project board](https://github.com/over-da-rainbow/over-da-rainbow/projects/3)


### More about the organization

[Over-da-Rainbow Organization](https://github.com/over-da-rainbow)


