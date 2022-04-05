## Table of contents

* [Overview](#overview)
* [Team Contract](#team-contract)

## Overview

Over Da Rainbow is a web application for University of Hawaii students to get together and explore beautiful sceneries and destinations offered here.

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

It also provides code that implements a variety of useful design concepts, including:

* Three primary collections (Profiles, Projects, Interests) as well as three "join" Collections (ProfilesInterests, ProfilesProjects, and ProjectsInterests) that implement many-to-many relationships between them.
* Top-level index pages (Profiles, Interests, and Projects) that show how to manipulate these six collections in various ways.
* Initialization code to define default Profiles, Interests, and Projects and relations between them.
* A simple Filter page to illustrate how to perform simple queries on the database and display the results.
* Use of Meteor Methods to illustrate how to simplify implementation of multiple collection updates.
* Use of indexes to enforce uniqueness of certain fields in the collections, enabling them to serve as primary keys.
* Authentication using the built-in Meteor accounts package along with Sign Up and Sign In pages.
* Authorization examples: certain pages are public (Profiles, Projects, Interests), while other pages require login (AddProject, Filter).
* Use of Meteor Assets to initialize the database (helpful when initialization exceeds settings file size limits).

## Team Contract

[Team Contract](https://docs.google.com/document/d/1HXy_bQAs_UlvUBsboftt7dbf-zyPfi7BWICM8ahgs0M/edit)

##Goals

* Create a user friendly outdoor guide web application that allows UH students/staff to safely discover Oahu’s best kept secret spots.
* Visually appealing and outdoor theme
* Make the activities/spots suggested customized to user 
* Provide suggestions for students to volunteer to help the community

## What Should the System Provide

* Home page where all users are funneled to
* Users can login and keep track of all the places they’ve already explored
* Suggested page where users can surf through different suggested destinations for their next experience.
* Anonymous ratings under each destination to help future explorers.
* Choice to leave comments under the destination.
* “Volunteering” tab for people who need volunteer hours or want to help community
* Tags for each location about what kind of activity  (ex. Beach, hike, etc.)
