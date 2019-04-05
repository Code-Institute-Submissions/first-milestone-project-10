<h1>Stream One Project: User-Centric Fronted Development</h1>

<h2>My Approach</h2>

<p>According to the brief, the primary target audiences are “fans who wish to use the site and to see and hear clips from their back catalogue
and any new material as it becomes available.” In addition, the client requested the site showcase their music and allow fans to book the band
to perform at weddings and parties.</p>

<p>The site was developed to be mobile-first. I used the basic CSS grid along with Bootstrap's grid to provide a site whose elements adapted
to the screen size to provide the best user experience possible. My goal with the site was to deliver this functionality tied to an aesthetic
that conveyed the band’s personality – colourful, playful and energetic. The cover section is the first part of the site the user sees; it a colourful grid featuring pictures of each individual member of
a band that is responsive, snapping to a smaller size on mobile and tablet devices. I intended to engage the user immediately with a dynamic
colour scheme and style that represented the Monkees. </p>

<p>The Monkees are not a band who take themselves too seriously and that is to be celebrated, including with the design. It’s loud and colourful
and an attempt to capture the attitude and aesthetic of the video clip contained in the github repo assets. The idea for the grid came midway
through the project in what was an organic creative process. As I tried and tested ideas I gained a better idea of what worked and how I wanted
it to look. Initially the cover was a simple black and white image but this was rather flat and didn’t convey the right message. Nor was it a
good representation of the band or the best use of the assets provided. </p>

<p>Another section initially used to introduce the band members individually was repurposed to showcase individual tracks for the user to listen to,
combined with a text box containing song lyrics. Initially I had the tracks grouped together and titled; however I felt this broke the flow of the page
and did not strike the right balance between style and structure and so it had to be changed. </p>

<p>Finally, the background of the site consisted of a colour gradient with one colour for each section transitioning to the next to provide a seamless experience
for the user as she scrolled through the site. Ideas evolved and in some cases combined throughout the project. The site is the culmination of that process.</p>

<h2>UX</h2>

<p>The goal of the UX is to provide a seamless experience for the user that is a potential fan or even an old one. I made an effort to capture the look and feel of
The Monkees in the design of the website in a way that was timeless yet took advantage of modern technology to provide an accessible user experience. 
A booking form is found at the end of the site, a CTA, and links to social media (inactive) are found in the navigation bar and footer of the website in order to reach the
client’s objective of building a social media following. 
</p>

<h2>Technologies</h2>

<ul>
<li>HTML</li>
<li>CSS</li>
<li>Bootstrap Version 4.3.1</li>
<li>FontAwesome Version 4.7</li>
<li>Google Fonts</li>
</ul>

<h2>Testing</h2>

<p>The site was tested on various browsers and devices as well as using Google Chrome's web developer tools.</p>
<p>The grid at the top of the page is responsive, changing to a 12x12 grid on desktop and a 3x9 grid on smaller screens.
Media queries hide or reveal grid squares dynamically based on screen-size. Issues arose with the letters spelling out "Monkees!"
contained in certain squares, requiring me to add properties such as line-height and font-size to make sure the letters fit cells 
neatly without distorting them, along with media queries for further necessary adjustments relative to screen size. </p>
<p>Each audio-player is accompanied by an image and text book containing the relevant song lyrics. This section is responsive
in that the elements containing lyrics appear before or after the audio track using the display property with media queries
in order to provide a visual experience approperiate to the screen-size used.</p>
<p>The store front provides a button that is intended to link to a payment page that is currently inactive. The button acts as a "call-to-action",
drawing the user's attention and urging them to act.</p>
<p>The form section requires a name, email and details of the venue before a request may be submitted. However, 
the facility to process these requests is not available.</p>

<h2>Deployment</h2>

<p>The site is hosted on Github pages at this <a href="https://stiofaneimeid.github.io/first-milestone-project/" target="_blank">address</a>. Originally designed using Cloud9's workspace feature, a git remote was set up and updates
pushed to the Github repository. </p>

<h2>Credits</h2>

<h3>Media</h3>

<p>All media originates from the Code Institute project repository.</p>

<h3>Content</h3>

<p>All copy for the site was written by me. The wireframes were also drawn by me. Lyrics are by The Monkees.</p>

<h3>Acknowledgements</h3>

<p>HTML and CSS used to design the form and social media links used in the Code Institute CV/resumé tutorial was used with some stylistic changes.</p>

<p>The HTML used in the navbar and form elements was found in the Bootstap documentation found
<a href="https://getbootstrap.com/docs/4.0/components/navbar/" target="_blank">here</a> and <a href="https://getbootstrap.com/docs/4.0/components/carousel/" target="_blank">here</a>,
respectively.</p>

<p>The media query for ipads was found in a Stackoverflow thread found <a href="https://stackoverflow.com/questions/41978487/correct-media-query-for-ipad-pro" target="_blank">here</a>.</p>

