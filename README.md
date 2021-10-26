Original App Design Project - README
===

# Travel-Hub

## Table of Contents
1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Data Models](#Data Models)

## Overview
### Description
Travel-Hub is a travel app to allow people to explore the world right at your fingertips! Serving as a crowdsourced travel log of journal entries from across the globe, Travel-Hub is all about you and all the other amazing people in the world. Explore and visualize posts on an interactive map and log every one of your adventures. You can also explore places through streetview, or discover adventures and win points for completing more adventures.

### App Evaluation

- **Category:** Social Networking
- **Mobile:** This app would be primarily developed for mobile but would perhaps be just as viable on a computer, such as Instagram or other similar apps. Functionality wouldn't be limited to mobile devices, however mobile version could potentially have more features.
- **Story:** A travel app to allow people to explore the world right at your fingertips! Serving as a crowdsourced travel log of journal entries from across the globe.
- **Market:** Any individual could choose to use this app. Our target population includes social media users and travellers of all ages around the world.
- **Habit:** This app could be used as often or unoften as the user wanted depending on how deep their social life is, and what exactly they're looking for.
- **Scope:** First, this app will have features for users to document their travel by picking any location on the map and creating a post based on that location. They will also be able to discover landmarks and things to do around them based on their location. This app has the potential to compete with similar social media apps in the market.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can explore map and view posts from around the world, seeing markers of all the places people have posted
* User can create post from any location in the world from the map.
* User can search for posts using hashtags or based on the location of their choice.
* User can discover restaurants, museums, clubs, and hotels near a certain location
* Profile pages for each user
* Settings (Accesibility, Notification, General, etc.)
*

**Optional Nice-to-have Stories**
* Google talk-back for visually impaired people
* Landscape mode
* Custom markers on Google maps
* Offline mode

### 2. Screen Archetypes

* Map/Home Screen
    * Users can see posts in location
    * Users can add new posts
    * User can view post details
    * User can discover more about an area
    * User can view streetview
* Profile page
    * Users can see travel stats (how many cities/countries)
    * Users can navigate to settings
    * Users can change profile picture and description
    * Users can edit posts
* Settings page
    * Users can change basic information here
* Discover Page
    * Users can get "an adventure of the day" or it will just be a large list of activities in their current location. Users can type in a new location as well and screen reloads.

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Map (Home)
* Discover
* Profile Page
* Settings
* Login/Signup

**Flow Navigation** (Screen to Screen)

* Map Screen
    * Create post
    * Search post
* Discover
    * View places/restuarants/hotels from Yelp API
    * Detail view of each item
* Settings
    * Toggle settings screen
* Login/Signup
    * Login/Signup screen

## Wireframes

<img src="https://i.imgur.com/xHbioPD.png" width=800>


### 4. Data Models
|Property| Type | Description |
|objectId | String | Unique id for th user's post|
