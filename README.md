# Project Lyrics

React.js Music Application. 



## Description 

   A Music Player ( A spotify kind of thing basically ) that is able to play the songs from RapidAPI Shazam Core API [Link](https://rapidapi.com/tipsters/api/shazam-core?utm_source=youtube.com%2FJavaScriptMastery&utm_medium=referral&utm_campaign=DevRel)

   It contains a Discover section which also acts as a landing page for the site, we can also search for the song. Has a SideBar for navigation to other pages such as TopCharts Around you etc.
    
   Top Charts - Provide the top played songs. They can be viewed as a seperate page as well as a column in other pages
   Top Artist - Provides the top artists. Similart to top charts can also be viewed as a page as well as in a sliding row below the column of top chart
   Around You - Provides the top songs in your country, where the country is found using a IP geolocation api[Link](https://geo.ipify.org/)
   Other features include providing the Lyrics and details of the song upon clicking the song, as well as providing artist detais upon clicking the artist name. 

   The entire page is also mobile responsive, where the sidebar can also be opened or closed with a dedicated button. 

## Screenshot

   [](Desktop.png)
   [](Mobile.png)


## System Requirements

To get started with development, you need to install few tools

1. git 
   
   `git` version 2.13.1 or higher. Download [git](https://git-scm.com/downloads) if you don't have it already.

   To check your version of git, run:

   ```shell
    git --version
   ```

2. node 
   
   `node` version 16.15.1 or higher. Download [node](https://nodejs.org/en/download/) if you don't have it already.

   To check your version of node, run:

   ```shell
    node --version
   ```

3. npm
  
   `npm` version 5.6.1 or higher. You will have it after you install node.

   To check your version of npm, run:

   ```shell
    npm --version
   ```

## Setup

To set up a development environment, please follow these steps:

1. Clone the repo

   ```shell
    git clone https://github.com/JavaScript-Mastery-PRO/project1_team4_repository.git
   ```

2. Change directory to the project directory

    ```shell
    cd project1_team4_repository
    ```

3. Install the dependencies
   
    ```shell
     npm install
    ```

    If you get an error, please check the console for more information.

    If you don't get an error, you are ready to start development.

4. Run the app
   
    ```shell
    npm run dev
    ```

    Project will be running in the browser.

    Open [http://localhost:3000](http://localhost:3000) to view it in your browser.


## Note

   The API's might not work after a certain number of tries as they are limited.