# **Listyn**

## **Project Description**

**Listyn** is an online repository of music lists from various publications. **Listyn** utilizes the **Spotify Web API** to organize information, and deliver an easy to navigate drop-down menu for every list.

Music publications provide their respective audiences with an endless barrage of "all-time greatest" and "best of this or that year" lists. Often times, the information is difficult to parse through, and requires the user to click or scroll incessantly. Links to purchase or preview the content in question are rarely offered for older lists and rankings. 

**Listyn** offers users a one-stop shop for browsing these lists, and discovering the music they love. 

>"Every great work of art has two faces, one toward its own time and one toward the future, toward eternity." 

>-Lester Bangs

## **Project Planning**

Below is an overview of my course of action for this project. For a more detailed accounting of the project timeline, please visit the Trello Board section below.  

To begin this project, I created wireframes/rough mockups of my desired end product. These mockups will act as a reminder to prioritize the user experience throughout the development process. I have also done extensive research to confirm that the Spotify API can meet my project's goals.

#### Home Page

![Homepage](https://i.imgur.com/oaXpXr7.png)

#### Interior List Page

![List Sample](https://i.imgur.com/MXuPxzk.png)

#### About Us Page

![About Us](https://i.imgur.com/Cq5t3wr.png)

### **Development Process**

#### First Steps

>• Building the basic HTML structure of an interior list page.

>• Setting up a preliminary CSS Style document.

>• Setting up a preliminary Javascript file. 

#### Core Challenges

>• Completing the OAuth Access Token process. 

>• Accessing the Spotify Web API with Javascript.

>• Retrieving song, artist, album, and album cover data.

#### Next Steps

>• Complete Home and About Us pages.

>• Building out site navigation. 

>• Building out multiple lists from different publications.

>• Making these lists accessible from the home page.

#### Stretch Goals

>• Using CSS, I would like to make the record spin when a song preview is playing. 

>• Include a link to purchase the song or album on Amazon. 

## **User Experience**

#### User Experience Overview

Upon entering the site, the user will be greeted with a welcome message and a drop-down menu used to select a desired list. Once a list has been selected, a user will be taken to an interior page that displays the title of the list, a drop down menu for navigating the list, as well as the data corresponding to the first item on the list. This page will also include a preview button for listening to a song, and navigation buttons for clicking through a list, one item at a time. 

#### User Story One

>As a young music fan, I want to familiarize myself with the supposed luminaries of my favorite musical genre. With **Listyn** I can view all the artists from a particular music publication's rankings list, in one easy to use drop-down menu. 

#### User Story Two

>As a long time fan of a genre, I want to know how my favorite songs are viewed by critics today. With **Listyn** I can easily locate a particular song in a given list, and then listen to a preview of the song. 

## **Technology Used**

![Tech Used](https://i.imgur.com/6OQkMaA.png)

## **Spotify Web API**

This project utilizes the Spotify Web API. This API offers excellent documentation and tutorials for proper implementation.

To learn more visit 
https://developer.spotify.com/documentation/web-api/

#### Code Snippets

Code snippets relevant to this project are included below. **Listyn** will retrieve a playlist, and then retrieve the relevant track/artist/album information from that playlist. 

##### • Get a Playlist's Items

A playlist's Items can be fetched with this. The response returns an array of track items with an index corresponding to their order in the playlist. The response is limited to 100 items, so pagination will be required for lists over this number. The response includes a track id, that can be used with Get a Track. 

>https://developer.spotify.com/console/get-playlist-tracks/

![Playlist](https://i.imgur.com/IuvQnJQ.png)

##### • Get a Track

A track object can be fetched with this. Using the track id returned from the playlist items, we have access to the Artist, Album, Release Date, and Album Art. 

>https://developer.spotify.com/console/get-track/

![Track](https://i.imgur.com/6H60nbx.png)

## **Trello Board**

To follow the progress of this project please visit the Trello Board linked below.

https://trello.com/b/RteikJuy/listyn

## **Credits**

Created by William Hunter Long

https://github.com/whlong1

Special thanks to **Miguel Á. Padriñán** for the background image used throughout the site mockups. 

Special thanks to **Schuyler Luckey** for the suggesting the use of customized graphics in the **Technology Used** section of this README.md





