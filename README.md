# Ninja Gym website
## Stream One Project: User-Centric Frontend Development - Code Institute
### Introduction
This is a website for Ninja Gym, an imaginary boxing gym, to attract boxing enthusiasts who are new potential members and retain existing members by providing useful info. The information is structured into:

**1. The gym**
  * List of facilities
  *Photos of the gym and members
  *Details of classes 
  
**2. Instructors background**
  * Photos of instructors
  * Their names and boxing experience
  
**3. Membership rates**
  * Individual plans
  * Corporate plans
  
**4. Class schedule**
  * Day by day schedule with classes color coded, and who is teaching the class
  
**5. Contact details**
  * Google maps location details
  * Social media links
  * Contact form to register interest

### User stories:
As a boxing enthusiast potentially becoming a member, I want to:
  * Learn more about the gym to consider signing up
  * Check if classes available are suited to my timings
  * Check if instructors are experienced
  * Take a look at the gym facilities
  * Know about the membership rates
  * Testimonials from existing members
  * Have the option to contact the gym directly or have someone contact me
  
As an existing gym member, I want to:
  * Check the class schedule and book classes online
  * Have articles/blog posts about boxing
  * Have the option to contact the gym directly or have someone contact me
  ***
### UX
* **Landing page experience** – when users first come to the page, they see a large, eye catching boxing-related image with a call to action to book a trial (modal popup for desktop version, links to contact form/ class schedule in mobile version). There are no slow-to-load items, eg, videos, and for the desktop version, there are three columns following the image for easy navigation to the information they would most likely want to access: Info about the gym facilities, Class schedule, and Quality of instructors. There is a sticky navbar at the top for every page
* **Content** – Text is kept to the minimum to ensure readers only have to read what they are interested in. To keep the layout clean, text-heavy descriptions are hidden in accordions, flip back cards and drop down tables
* **Text hierarchy** – Headers for each section are positioned in a dark-background, fixed attachment jumbotron to make them stand out. This is consistent across all sections. For sub headers and paragaphs, they are in uniform colors (purple and black respectively) across all sections. 
* **Call to action** – One primary purpose of the website is to get members to sign up. There are several touchpoints where users can do this: At the landing page, on the price rates page, and at the contact form. The buttons are uniformly styled to ensure a consistent user experience.

### UI and Features
The website has been designed to be responsive for all media forms (Mobile, tablet and laptop)

**Overall**
* Light grey background with dark text so that it is easy to read.
* Color scheme is maroon/black/purple/grey/white. The dark colours are relatively strong and bold, fitting to match the image of a boxing gym. 
* Use of font awesome icons in navbar and social media section to personalize the site
* Site is not overcrowded – sufficient negative space to ensure design looks balanced and not cluttered
* Use of bootstrap grid layout throughout so that divs are all evenly spaced
* Instructor photos have a box shadow effect to make the photos stand out more

**Mobile version**
* Single columns so that page is not overly cluttered
* Users have the choice to just scroll down continuously without having to click on the navbar on top. If they click on the navbar, they will see the exact same content
* Image carousel is replaced with normal images so that users don’t have to constantly click
* For section headers, the background is a black and white gradient instead of an image so that the page loads quicker. It is also difficult to find a suitable background image for jumbotrons this small. 
* Video is removed under the Rates section for quicker loading
* Features are added to reduce the need to constantly click on page, eg, accordion is removed and images are shown individually
* A drop down table is used for the timetable. If the desktop version of the schedule was shown, users would have to scroll right and down (since Javacript is not used)
* The modal on the landing page is removed and the button links to the contact form instead, as the modal may take up too much space when clicked on.
* Images and iframes are all responsive in size
* Dropdown navbar so that users don’t have to scroll right, and to reduce amount of space taken. If users choose not to use it and just scroll down the page, there is a “Back to top” link so they don’t have to scroll all the way up again.

**Tablet version**
* Containers are resized responsively so they fit nicely within iPad and iPad pro
* Text in navbar is reduced so that the "instructors" word and its Font Awesome icon remain inline
* Table is shown for the class schedule, and scroll along x-axis is enabled

**Desktop version**
* Attractive boxing related images are shown in section headers, while still having the text clearly visible as opacity of background image is reduced
* A video is added in the Rates section, with just 10 seconds intended for playing, to match the rough amount of time users would need to read the text in the adjacent column. 
* Information is presented in 2/3-column rows to ensure that page is not too long. Sufficient margins are added between columns to keep layout clean and neat
* A color coded table makes the class schedule information interesting to look at, while still being functional
* Images of the gym are shown in a carousel, with the option for users to click to speed up the rate at which images change.
* A modal is added on the landing page, which users can easily close either by click on the “x” or outside of the modal. The contact form here requires less information to be filled than the full form on the Contact page so that users are less likely to navigate away from the first page. (If they had reached the contact page, it is likely that they are strongly keen in registering their interest)

### Technologies
1. HTML
2. CSS
3. Bootstrap (4.3.1)
4. Font Awesome
5. Google Fonts
6. Google Maps iframe
 
### Features Left to Implement
In the future, I would like to 
* Allow users to book classes online, and also make the timetable more dynamic by allowing users to select the day from a drop down and only see the relevant classes.
* Include an articles/ blog post section
* Have a live chat bot
* Include users testimonials

### Testing
The site is tested to be responsive for 
* Iphone 5/6/7/8
* Ipad
* Ipad Pro
* Safari
* Chrome
* Firefox
* Edge
* IE

During testing, it was found that the flip card does not work on IE. When flipped to the back, the image rotated 180 degrees but the text did not show up.  

Also, for tablets, it was found that the video and google Maps iframes were not responsive and overlapped into adjacent columns. As such, I wrapped them in a div and made the div responsive. 

### Deployment
For deployment, I completed the following checks:

* Ensuring that all the links work and all buttons redirect users to the right pages
* Ensuring that the site looks consistent across all major browsers (IE, Chrome, Safari, Firefox, Edge) and mobile devices of various sizes (extra small mobile screen, average mobile screen, iPad and iPad pro screens)
* Checked that there were no grammatical errors, the right images were showing up at the right places and that content was easy to read

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

### Credits
**Content**

The content was written by me, inspired by Wikipedia various gym websites, namely [Evolve MMA](https://evolve-mma.com)

**Media**

All photos were taken from [Pexels](https://www.pexels.com/), a stock image library. The video was taken from [YouTube](https://youtu.be/AJHAUo-1X54)

**Google Maps**

I used this [Google Maps generator](https://www.maps.ie/create-google-map/)
