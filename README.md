# Milestone Project 1: The Monkees Website

The deployed website can be accessed from here: [The Monkees](https://jepainter.github.io/MilestoneProject1/)

## Goal of the website

The website created is a responsive and interactive website to show case The Monkees. 
The band is a 60's era rock band, having produced numerous albums and peforming tours.
The band is still active and can be booked for events.

The main purpose of the website is to showcase the band, and provide fans with information that 
would be useful to them.

## UX
 
The Client (The Monkees) required a website that would enable them to:
- Target their fans and potential fans who wish to use the site to see and hear clips from their albums.
- Showcase their music with the aim to solicit performances at events.

This website provides the relevant functionality to satisfy both these requirements, but also includes (guided by user stories/requirements):
- Provide the opportunity to sign-up to a newsletter to stay up to date with developments regarding the band.
- Information on the band and band members for existing and new fans to read.
- Give and indication of upcomming tours as well as a means to book tickets via a third-party website.
- Provide additional visual resources such as images and video.
- Provide fans and potential fans the opportunity to use social media to follow the band.

### User Stories:
- As a fan of the band, I want to be able to provide my contact details, in order for the band to confirm whether they can be booked for and event.
- As a new fan of the band, I want to be able to access information on the band members, in order to get and insight into the individuals.
- As a fan of the band, I want to be able to view their upcomming tour dates, with the view to potentially book tickets to these events.
- As a fan of the band, I want to be able to view their song lists for their albums and potentially listen to sample tracks from the albums.
- As a fan of the band, I want to be able to provide my contact details, in order to stay up to date on the most recent news regarding the band.
- As a fan of the band, I want to be able to view visual material regarding the band, potentially access video of a performance.
- As a user of the website, I want to be able to easily navigate the website, in order to quickly find the relevant information I require.
- As a user of the website, I want the site to function well on any device size, while still maintaining correct functionality.

### Wireframes:
Wireframes for the initial development of the site can be found here:
- [Mobile](https://github.com/jepainter/MilestoneProject1/blob/master/development/MilestoneProject1Mobile.pdf)
- [Desktop](https://github.com/jepainter/MilestoneProject1/blob/master/development/MilestoneProject1.pdf)

### Design considerations:
It was decided to style the website with a 60's era feel (color palette, rounded containers, background image, etc).

The design would utilise Bootstrap grid system, containers and components responsive to different screen sizes and devices. 

Also to reduce information overload on the About page, it was decided to add in Modals to expand on information regarding the band members and band, by clicking on a Read More Button.

This site is limited to front-end design only (HMTL, CSS and Bootstrap). 

## Features

### Existing Features
- Feature 1 - Newsletter Sign-up: allows user subscribe to a newsletter by having them fill out a forms with contact information, once the Sign Up button in pushed on the Home page (modal in index.html).
- Feature 2 - Band Information: allows the user to read information on the band and band members by visiting the About page (about.html). More information can be found once the Read More buttons are pushed (modals in about.html for additional information).
- Feature 3 - Tour Information: allows the users to view upcomming tour dates (located in tours.html), and allows them to book tickets for an "available" event by pushing the Book buttons, which links to a third party ticketting website.
- Feature 4 - Image Gallery:  allows the user to view images of the band in a carousel (located in media.html), using a carousel.  The user can skip to the next image by using the previous and next button on the carousel.
- Feature 5 - Albums:  The user can view the song list of specific albums, and can also listen to a sample track by using the audio players (located on media.html).
- Feature 6 - Video:  The user van view a music video of the band, by using the embedded music video section (located on media.html). 
- Feature 7 - Booking:  The user can provide contact information as well as event details, by filling out a form (located on contact.html), which can be submitted with the aim to book the band for the event.
- Feature 8 - Following Band:  The user can gain access to the band and follow them on social media, by using the social media links located in the footers of every page, alternatively on the Bookings / Contact Us page (contact.html).
- Feature 9 - Navigate: The user can easily navigate the website by following the links at the top/header of each page, alternatively clicking on the navigation questions on the Home page (index.html).

### Features Left to Implement
- Feature A - A separate merchandising page can be included to allow the user to select and purchase merchandise (albums, t-shirts, etc.) regarding the band.
- Feature B - An alert to pop up indicating that a form has successfully been submitted after validation - JavaScript required
- Feature C - Actual submission of form for further processing on a server required - JavaScript required at least
- Feature D - A container/blog that tracks social media posts from the band can be included as an aside on pages.


## Technologies Used

The following languages, frameworks, libraries, IDE, repositories and tools were used for the creation of this website:

- [HTML](https://en.wikipedia.org/wiki/HTML)
    - This project utilises the **HTML** language and sematic elements for basic layout and function.   

- [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    - This project is styled using **CSS** where required for classes and specific elements. 

- [Bootstrap](https://getbootstrap.com/)
    - This project was predominantly created using the **Bootstrap** grid system and components (incorporated through the Bootstrap CDN), to create the layout and responsive design of the page.

- [Hover.css](https://ianlunn.github.io/Hover/)
    - This project utilises the **Hover.css CDN** for effects on hover, specifically for the navquestions on the index page.  

- [FontAwesome](https://fontawesome.com/)
    - This project utilises **FontAwesome CDN** for icons utilised on the website, specifically for social media icons. 

- [jQuery](https://jquery.com/)
    - This project utilises **jQuery** for the responsive navbar.

- [Popper.js](https://popper.js.org/)
    - The project uses **Popper.js**  for the responsive navbar.

- [AWS Cloud9](https://www.awseducate.com)
    - This project was created using **AWS Cloud9** IDE for development, as well as committing of progress to GitHub. 

- [GitHub](https://github.com)
    - This project uses **GitHub** for hosting of project repository, as well a publishing of website. 

- [Favicon](https://www.favicon.cc/)
    - Used **Favicon.cc** to generate at favicon for my site.

- [W3C Markup Validation Service](https://validator.w3.org/)
    - This project was tested using the **W3C Markup Validation Service** for checking conformity and validity of html content. 

- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
    - This project was tested using the **W3C CSS Validation Service** for checking conformity and validity of css content. 

- [Autoprefixer CSS Online](https://autoprefixer.github.io/)
    - Used **Autoprefixer CSS Online** tool to update/confirm prefixes for style.css code.

## Testing

Testing for this site was performed as follows:

### Code Validation:
The various html files was firstly tested using the W3C HTML Validation site, with no errors reported.
The style.css file was tested using the W3C CSS Validation site, with no errors reported.
The style.css file was run through the Autoprefixer CSS Online tool.

The site was tested on Google Chrome (desktop and mobile through dev tools), Opera (desktop only) and Safari (mobile only) for functionality.  Verified working well.

This site was also tested manually in line with the user stories and general functionality.  The following testing scenarios were applied across all screen sizes (as a test of responsive design):

### Testing Scenarios:
1. Newsletter Sign-Up form:
    1. Go to the "Home" page, click on Sign Up button.
    2. Modal to appear with input to be filled in form, verified working correctly.
    3. Try to submit the empty form and verified that an error message about the required fields appears.
    4. Try to submit the form with an invalid email address and verified that a relevant error message appears.
    5. Try to submit the form with all inputs valid with no errors (form to clear after submission), verified working correctly.

2. Booking form:
    1. Go to the "Booking / Contact Us" page.
    2. Checked that content is viewable in containers and structure looks good, stacked on top of one another on smaller screens and adjacent to one another on larger displays, verified working correctly.
    3. Try to submit the empty form and verified that an error message about the required fields appears.
    4. Try to submit the form with an invalid email address and verified that a relevant error message appears.
    5. Try to submit the form with all inputs valid with no errors (form to clear after submission), verified working correctly.

3. Information on band:
    1. Go to the "About" page.
    2. Checked that content is viewable in containers and structure looks good, stacked on top of one another on smaller screens and adjacent to one another on larger displays, verified working correctly.
    3. Push "Read More" buttons to view more information specific to the subject (modal must pop up), verified working correctly.
    4. Be able to close modal and return to "About" page by using the close button at the top or bottom of the modal, verified working correctly.

4. Tours information:
    1. Go to the "Tours" page.
    2. Checked that content is viewable in containers and structure looks good, stacked on top of one another on smaller screens and adjacent to one another on larger displays, verified working correctly.
    3. Try to push "Sold Out" buttons, it is not affected by hover or is not clickable (disabled), verified working correctly.
    4. Push "Book" buttons, it should all link to a third-party website to book tickets (opens in a new separate window/tab), verified working correctly.

5. Pictures:
    1. Go to "Media" page.
    2. Carousel should adjust size appropriately according to screen size and centered (Bug1: issue with display size on iPad Pro in portrait view).  Functioning well on all other devices and orientations.
    3. Bug1 Fix: Removed assigment of height (vh) to containers to prevent skewing/scalling issue of carousel container.
    4. Images to fill Carousel appropriately, without skewing/scaling issues or overflows outside of containers (Bug2: some scaling issues, especially iPad Pro, minor issues with other displays).
    5. Bug2 Fix: Assigned width of 100 to carousel-items to prevent skewing/scaling issues in the container. 
    6. "Previous" and "Next" buttons on Carousel functional and responsive, verified working correctly. 
    7. Using Carousel progress indicator at bottom to cycle images/jump to images tested, verified working correctly.

6. Albums and audio players:
    1. Go to "Media" page.
    2. Checked that content is viewable in containers and structure looks good, stacked on top of one another on smaller screens and adjacent to one another on larger displays, verified working correctly.
    3. Checked that album images floats is central on top of song list for smaller screens, floats right of song list on larger displays, verified working correctly.   
    4. Checked audio players are centered within specific album container across different screen sizes, verified working correctly.
    5. Checked audio players function (stop, play, mute, skip) regardless of device type, verified working correctly (Bug3: multiple audio files can be played at once). 
    6. Bug3 Fix: Requires JavaScript (not implemented) to prevent simultaneous playback for audio files.

7. Video player:
    1. Go to "Media" page.
    2. Checked that content is centered and viewable in container and structure looks good, stacked on top of one another on smaller screens and centered below albums on larger displays, verified working correctly.
    3. Video scales across all view screen sizes, verified working correctly.
    4. Video plays across all view screen sizes (Bug4: Video do not play on Apple Products - iPhone, iPad, iPad Pro), verfiied working on desktop and Andriod devices (Galaxy, Pixel). 
    5. Bug4 Fix: Utilised the video tag instead of iFrame embed (issue with iOS devices), added prevent autostart and preload.  Functioning correctly in iOS devices.

8. Navigation Questions:
    1. Go to "Home" page and scroll down to Navigation Questions below callout section.
    2. Checked that content is viewable in containers and structure looks good, stacked 2 x 2 on smaller screens and adjacent to one another on larger displays, verified working correctly.
    3. On hover, questions should bounce out on desktops, verified working correctly.
    4. All questions link to appropriate pages, verified working correctly.

7. Footers:
    1. Go to Footers on each page.
    2. Checked that footer content is stacked on top of one another for smaller screen sizes and adjacent to one another on larger displays, verified working correctly.
    3. Checked that icons link to correct social media site (in a new page), verified working correctly.
    4. Checked that transitions on desktop view is applied on hover over social media icons, working correctly.

8. Navigation Bars:
    1. Go to Navigation bar on each page.
    2. Check that band logo resizes on larger screens, verified working correctly.
    3. Check that navigation links collapse to navigation toggle on smaller screens, verified working correctly.
    4. Checked that navigation links indicate active (bold) based on page that is current, verified working correctly.
    5. Checked that navigation links transition based on hover on desktop display, verified working correctly. 
    6. Checked that links navigate to correct page, verified working correctly.

## Deployment

This project is deployed on GitHub and is accessible as follows:
- Website: [GitHub Pages](https://jepainter.github.io/MilestoneProject1/)
- Repository: [GitHub](https://github.com/jepainter/MilestoneProject1)

For this project I used the AWS Cloud9 IDE platform [AWS Cloud9](https://www.awseducate.com) via the AWS Educate portal.
The platform allowed me to commit my pages (and changes) to Git, following which it was pushed through to the [GitHub repository](https://github.com/jepainter/MilestoneProject1).

Deployment of the website from its repository to GitHub Pages were accomplished through the following method: 
1. Logged into the GitHub website. 
2. Selected the **jepainter/MilestoneProject1** repository.
3. Selected **Settings** from the menu items.
4. Found the **GitHub Pages** section by scrolling down in the browser window.
5. Selected the **Master Branch** options from the drop-down list under the **Source** section
6. The web site is deployed once the page refreshes, from where the link to the site can be obtained by scrolling down to the **GitHub Pages** section.

This website can also be **locally deployed** by following the method outlined below:
1. Use the following link to access the project repository: [GitHub](https://github.com/jepainter/MilestoneProject1).
2. Click on the **Clone or Download** button, under the repository name.
3. Copy the clone URL for the repository, found in the **Clone with HTTPS** section. 
4. Open **Git Bash** in your local IDE environment.
5. Select the location to where the cloned directory must be made.
6. Input ```git clone``` together with the copied clone URL into Git Bash and press Enter.


## Credits

### Content
- The text for the About Page and Modal (The Monkees) was copied from the [Wikipedia article - The Monkees](https://en.wikipedia.org/wiki/The_Monkees)
- The text for the About Page and Modal (Micky Dolenz) was copied from the [Wikipedia article - Micky Dolenz](https://en.wikipedia.org/wiki/Micky_Dolenz)
- The text for the About Page and Modal (Michael Nesmith ) was copied from the [Wikipedia article - Michael Nesmith](https://en.wikipedia.org/wiki/Michael_Nesmith)
- The text for the About Page and Modal (Peter Tork) was copied from the [Wikipedia article - Peter Tork](https://en.wikipedia.org/wiki/Peter_Tork)
- The text for the About Page and Modal (David Jones) was copied from the [Wikipedia article - Davy Jones](https://en.wikipedia.org/wiki/Davy_Jones_(musician))
- The content for the Tour Page is purely fictional and do not represent any actual tour dates or venues, unless by pure coincidence.

### Code
- Audio-players: Code was adapted from [HTML.com](https://html.com/attributes/audio-src/) in order to play audio files.
- Video-players: Code was adapted from [StackOverflow](https://stackoverflow.com/questions/19664622/disable-html5-video-autoplay) in order to play video, without autostart.
- Modals: Code for fixing and making content scrollable was adapted from [StackOverflow](https://stackoverflow.com/questions/10476632/how-to-scroll-the-page-when-a-modal-dialog-is-longer-than-the-screen) 
- Favicon:  Code for favicon adapted from [StackOverflow](https://stackoverflow.com/questions/11893478/add-favicon-to-website)
- Background Fixed: Code for background fixed problem (iOS devices) adapted from [StackOverflow](https://stackoverflow.com/a/43058483)

### Media
- The photos, video and audio files used in this site were provided from CodeInstitute as part of the assets made available for the project.  It is used purely for educational purposes.
- Additional images were sourced from the following websites, used for educational purposes only:
    - [Wallpaperplay](https://wallpaperplay.com/board/60s-background-wallpapers): Background image for secondary pages (i.e. not index.html).
    - [FanPop](http://www.fanpop.com/clubs/the-monkees/images): Images for carousel on Media Page.

### Acknowledgements
- I would like to thank my mentor, Dick Vlaanderen, for input provided during the development of the site.
- I would also like to acknowledge and give credit to the Slack Community (too many to mention specifically) for advice and solutions provided on the forums that provided additional resources for consideration during the development of this project.
