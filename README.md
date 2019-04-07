# Stream One Project: User-Centric Fronted Development

## Introduction

The Monkees are a band that doesn't take itself too seriously. I sought to celebrate that with the design of the website. It’s bright and colourful in an attempt to capture the attitude and aesthetic of the video clip contained in the Github repo assets.

The site allows the user to engage with the band, through listening to their music, purchasing merchandise and booking the band for live performances. The website is intended to be the one-stop shop and digital home of the band. 

## UX

According to the brief, the primary target audiences are “fans who wish to use the site and to see and hear clips from their back catalogue
and any new material as it becomes available.” In addition, the client requested the site showcase their music and allow fans to book the band
to perform at weddings and parties.

My ultimate goal with the site was to deliver this functionality tied to an aesthetic that conveyed the band’s personality – colourful, playful and energetic. The site was developed to be mobile-first. I used the basic CSS grid along with Bootstrap's grid to provide a site whose elements adapted
to the screen size to provide the best user experience possible. The cover section is the first part of the site the user sees; it a colourful grid featuring pictures of each individual member of a band that is responsive, snapping to a smaller size on mobile and tablet devices.

A booking form is found at the end of the site, a "call-to-action (CTA)"", and links to social media (inactive) are found in the navigation bar and footer of the website in order to fulfil the client’s goal of building a social media following. 

[Wireframe 1](https://github.com/stiofanEimeid/first-milestone-project/blob/master/wireframes/wireframe1.jpg "wireframe1") provides intial conceptual designs while [wireframe 2](https://github.com/stiofanEimeid/first-milestone-project/blob/master/wireframes/wireframe2.jpg "wireframe2") illustrates the grid concept. 

### User stories

As a user, if I want to book The Monkees, I need to provide a name, a valid email address and a short description of the venue at which I wish the band to perform.

If the user tries to resize the screen on a larger screen, she will see the grid snap from the larger to the smaller version.

As a user, if I want to jump to a different section of the page, I can do so at any time with the fixed navbar. 

## Creative Process

The idea for the grid came midway through the project in what was an organic creative process. As I tried and tested ideas I gained a better idea of what worked and how I wanted it to look. Initially the cover was a simple black and white image but this was rather flat and didn’t convey the right message. It wasn't a good representation of the band nor the best use of the assets provided. 

Another section initially used to introduce the band members individually was repurposed to showcase individual tracks for the user to listen to, combined with a text box containing song lyrics. Initially I had the tracks grouped together as seen in section two of [wireframe 2](https://github.com/stiofanEimeid/first-milestone-project/blob/master/wireframes/wireframe2.jpg "wireframe2"); however, I felt this broke the flow of the page. Also, it did not strike the right balance between style and structure and so it had to be changed. 

Finally, the background of the site consisted of a colour gradient with one colour for each section transitioning to the next to provide a seamless experience for the user as she scrolled through the site. Ideas evolved and in some cases combined throughout the project. The site is the culmination of that process.

## Features

### Existing Features

#### Navbar

The navbar, the collapsed version on smaller screens and the drop-down menu were pulled from the Bootstrap documentation.  Social media icons were included on the right-hand side to allow users to access the band on social media quickly and easily. The navbar is fixed to the screen, accessible at all times as the user scrolls to allow for fluid and easy navigation throughout the site. 

#### Cover

The cover is a CSS grid that is 8x3 on smaller devices and 6x6 on larger devices.
Certain squares or “cells” also spell out “Monkees!” The cells needed to make the grid change from 3x8 to 6x6 are set to “display: none” in order to display the grid properly on mobile.  A media query sets the property of the cell to “display: inline” on larger screens. In addition, in order for the letter order to make sense, some squares containing letters are mobile only to be replaced with squares containing letters that are medium-only.

#### Discography

The discography section contains four songs in an audio-player contained in a figure element along with an image. These elements are accompanied by a h3 element that provides the song name along with lyrics from the song with a white font-colour in order to stand out against the background. On smaller screens, the order is as follows: title, figure and lyrics. On larger screens, figures alternate between the right and left of the screen with their respective title and lyrics to their side. This was accomplished by making two versions of each group of title, and lyrics; with one or the other appearing or disappearing based on the screen size to maintain the proper arrangement.

The carousel code was also taken from the Bootstrap documentation, occupying half the width of the screen on larger screens and the full-width of the screen on smaller devices using Bootstrap’s grid functionality.

#### Storefront

The storefront provides a button that is intended to link to a payment page that is currently inactive. The button acts as a "call-to-action", drawing the user's attention and urging them to act. 

#### Form

The form provides three fields that must be completed because of the required keyword included in the HTML otherwise the form will not submit. 

### Features Left to Implement

Features left to implement include a navbar animation whereby the menu button changes to an “x” when active and backend facilities for processing forms. I would also like to add more content to the storefront and watch video sections and perhaps include a gallery filled with pictures of performances where The Monkees have been hired by users to play. 

## Technologies Used

1. HTML
2. CSS
3. Bootstrap Version 4.3.1
4. FontAwesome Version 4.7
5. Google Fonts
6. JQuery (Used specifically for navbar functionality.)

## Testing

The site was tested on various browsers and devices as well as using Google Chrome's web developer tools. 

The grid at the top of the page is responsive, changing to a 6x6 grid on desktop and a 8x3 grid on smaller screens. Media queries hide or reveal grid squares dynamically based on screen-size. Issues arose with the letters spelling out "Monkees!" contained in certain squares, requiring me to add properties such as line-height and font-size to make sure the letters fit cells neatly without distorting them, along with media queries for further necessary adjustments relative to screen size. 

In addition, as the user tries to resize the screen on a larger screen, she will see the grid snap from the larger to the smaller version. However, I noticed the grid became somewhat distorted as cells containing letters and images squeezed empty cells in order for the grid to occupy the entire screen. I applied media queries to make the grid change to its smaller version at a higher width to avoid this. While this worked for larger screens, I found the grid changed too quickly on laptop screens. I therefore had to allow some grid distortion on larger screens to preserve the user’s visual experience on laptop along with certain tablets to avoid depriving them of seeing the larger grid altogether.

The form section requires a name, email and details of the venue before a request may be submitted. While the user may fail to provide adequate details regarding the venue, this is a quality control issue that cannot be addressed by HTML. In any event, any lack of clarity can be provided through further correspondence between the band and the user over email. 

Each link contained in the navbar(excluding the social media icons) work as intended, although if the user refreshes the page, she will be taken to the last section she jumped to rather than the top of the page. The section linked to will be included in the URL that is refreshed. As such, the user will have to manually set the URL in the address bar to return to the top of the page. 

In general, the site content stretched on larger screens to an unsightly degree. In order to remedy this, a included a media query that added padding to the sides of each section to keep the content nice and compact and deliver a better visual experience to the user. 

## Deployment

The site is hosted on Github pages at this [address](https://stiofaneimeid.github.io/first-milestone-project/ "git repo"). Originally designed using Cloud9's workspace feature, a git remote was set up in the Cloud9 workspace and updates pushed to the Github repository. 

In order to run the code locally please clone this repository directly in to an editor by pasting `git clone https://github.com/stiofanEimeid/first-milestone-project.git` into the terminal. To remove the repository, type “git remote rm origin” in to the terminal.

## Credits

### Media

All media originates from the Code Institute project repository.

### Content

All copy for the site was written by me; information sourced from Wikipedia Article on Monkees found [here](https://en.wikipedia.org/wiki/The_Monkees "Monkees wikipage"). The wireframes were also drawn by me. Lyrics are by The Monkees. 

### Acknowledgements

HTML and CSS used to design the form and social media links used in the Code Institute CV/resumé tutorial was used with some stylistic changes.

The HTML used in the navbar and form elements was found in the Bootstap documentation found
[here](https://getbootstrap.com/docs/4.0/components/navbar/ "navbar") and [here](https://getbootstrap.com/docs/4.0/components/carousel/ "carousel"), respectively.

The media query for ipads was found in a Stack Overflow thread found [here](https://stackoverflow.com/questions/41978487/correct-media-query-for-ipad-pro "stack").
