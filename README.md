Original App Design Project - README Template
===

# iCharts

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Discover new songs through different song charts and a discover page, by clicking a song it will take you to a new page with the song's music video at the top and lyrics underneath. Each genre can be sorted by a tab at the bottom.

### App Evaluation
- **Category:** Music / Discovery
- **Mobile:** Mobile uses audio hardware to playback user's playlists and songs 
- **Story:** Allows users to browse and listen to new music on the go with a set of lyrics
- **Market:** Anyone that likes to listen music, users are able to find their specific interests by browsing through their preferred genre tab
- **Habit:** Users can listen nonstop if they choose, features like repeat and shuffle enable the user to spice up their listening 
- **Scope:** Main goal is to achieve a pleasant listening experience and navigation for discovering new music, can expand into chatting service between fans of similar artists 

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Login / register page
* Recycler view list of songs
* New activity screen with music video at the top and lyrics underneath
* Uses parse as a backend 
* Ability to playback songs for the user
* Location based recommended top songs (New activity screen)
* Shazam-like audio listener

**Optional Nice-to-have Stories**

* Different screens for the charts/genres
* Implementing a shuffle and repeat features for song
* Add a credits tab along with the music video and lyrics


### 2. Screen Archetypes

* Login
* Register
   * Upon redownloading or open, user is prompted to login or create a new account.
* Landing page
   * The main screen where the user will spend most of their time with a list view of songs that a user can click on to lead them to a video and lyrics.
   * ...
* Song page
   * When a user clicks on a song, this is the page where the song's music video plays with lyrics underneath
* Location based recommonded song page
    * Recycler view of top 5 songs that is chosen based off GPS location

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Landing page
* Location based recommonded song page
* Favorite Songs/playlist/profile

**Flow Navigation** (Screen to Screen)

* Login/register
   * [list screen navigation here]
   * ...
* [list second screen here]
   * [list screen navigation here]
   * ...

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]







