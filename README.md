# Theory Of A Deadman Fan Site

The purpose of the project is to allow fans of Theory Of A Deadman to stay up to date with their favourite band while also allowing the band to have a
single location where they can release new music and make important announcements such as new tour dates.
It also gives potential fans a great insight into the band by allowing them to hear their music, watch their previous performances and also see where 
they will be touring in the near future. 

As the band are trying to grow their social media presence the website has all the links to their official channels across all platforms such as Instagram, 
Facebook, Spotify, etc. This allows the fans to find them on other platforms where they might not have done when browsing through the platform itself.
Alongside the social media links there is a fan club mailing list, which emails hardcore fans when any announcements are made.

## UX 

The project is essentially a hub for theory of a deadman fans to enjoy the music and performances of the band. As this will be managed by the bands 
promotional team all of the content will be official and there will not be any issues of fake edits or false rumours released onto the website.

The website itself has been designed on a mobile first approach but is responsive and can be used easily on all devices. Bootstrap has been used to help 
achieve this.

The website is clean and simple to navigate, there is a few examples of this below;
- A current fan lands on the main page and wants to see recent performances, they go to the nav bar at the top of the page and clicks on Live Performances,
  this takes them to the page in which the bands recent performances have been uploaded via YouTube.
- A new fan lands on the main page as they heard a song on the radio and searched google to listen to more of their music. They click on New Album on the 
  bar which allows them to listen to the bands new album via Spotify.
- A partner of a fan lands on the main page as they are looking to see where the bands next gig is as they are looking at getting tickets for their partners
  birthday, they click on Tour Dates in the nav bar and are then directed to the page listing all of the upcoming performance dates and locations.

## Existing Features
- Mailing list allows fans to enter their email address to receive new offers and music from the band, this feature is only frontend at the moment
- Spotify embedded code allows fans to listen to the bands most recent single or album depending on what page of the website they are on
- YouTube embedded code allows fans to watch the bands previous live performances
- Social media links allow fans to follow the band on popular social media platforms

## Future Features 
- Create backend code for the mailing list so email addresses are actually collected
- A store page where official merchandise can be purchased

## Technologies Used
The languages used in the project were HTML and CSS only. 
The bootstrap framework was used (http://getbootstrap.com/), this was used to allow the website to be responsive while laying out sections of the
website into blocks. Bootstrap fonts were also used for the social media icons.
iFrame technology was used to embed youtube videos and Spotify songs

## Testing
1. Navigating the site:
  1. Go to the nav bar which is identical on all pages on the site
  2. Click on the headings within the nav bar which takes you through all of the pages 
2. Navigating index page:
  1. Scroll down the index page making testing all features on the page
  2. Playing the YouTube video to make sure the link is working correctly
  3. Playing the Spotify track to make sure the link is working
  4. Entering email address into the sign up bar making sure that it allows user input
  5. Testing all of the social media links to make sure they are working and take the user to the correct page
3. Navigating the Live Performances Page:
  1. Playing all videos on the page on safari making sure that they working
  2. Doing the same on google chrome
  3. Doing the same on mobile and checking the responsiveness of the page
4. Navigating the new album page:
  1. Play the album on safari making sure that it works
  2. Doing the same on google chrome
  3. Doing the same on mobile and checking the responsiveness of the page
5. Navigating the tour dates page:
  1. scrolling down the page making sure all the dates and venues are visible on safari on desktop
  2. Doing the same on google chrome
  3. Doing the same on mobile and checking the responsiveness of the page

The task that caused the biggest headache was the sizing of the YouTube videos, on both the index page and the live performances page. Initially on 
desktop the videos were too large but this was sorted with the initial CSS code. When the first CSS code I created was running it made the videos unresponsive 
and not mobile friendly. I searched on stack and overflow for solutions but the solutions suggested either sacrificed the desktop design or the mobile 
response. Through a lot of trial and error and merging different ideas on CSS the videos are responsive and aesthetically pleasing.

## Deployment

This project has been hosted on GitHub Pages. This site was deployed after using GitHub as a code repository.

## Credits

The image used in this project for the header is taken from the official Theory Of A Deadman site (http://www.theoryofadeadman.com).
The videos have been taken from YouTube (https://www.youtube.com/) and uploaded by fans.
The audio has been taken from Spotify (https://www.spotify.com/uk/).

### Acknowledgements

The inspiration for this project was taken from the band Theory of a Deadman. The colour design is inline with the bands current style. 
The inspiration for the structure and layout of the website was taken from previous work that I have done with Code Institute.



