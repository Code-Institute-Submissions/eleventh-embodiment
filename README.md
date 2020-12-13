# Eleventh Embodiment

Live project can be found here [Eleventh Embodiment]()

Main purpose of this project was to build a website for my First Milestone Project as a part of Full Stack Web Developer Diploma course, using knowldge of HTML and CSS only.
I have decided to build a website for a friend of mine who is a yoga teacher and an alternative healer. Idea was to create a place where people can learn about different types of yoga, 
different healing techniques, and to be able to book yoga or healing sessions, workshops and/or retreats.
Website owner's goal is to attract more visitiors to the website wich will result in a bigger community, larger following on social media, and ultimately more people booking her classes, healing seassions and/or retreats.  

# UX
 
Website should be easy to navigate and should encourage the user to explore all the pages to learn all about site owner's skills and experience. 
The site should be simple but elegant and bright, which will be accomplished with using white, gold and warm brown colours.

# User Stories

#### As a first time user,
  As a first time user,
* I want to be able to  navigate through the site easily to find information and services available
* I want to learn more about the site owner and their skills and offering
* I want to be able to see this website clearly on my mobile device
* I want to find ways to follow the owner on social media platforms


#### Returning User
  As a returning user,
* I want to check if there are any new classes and/or retreats 
* I want to book online classes, workshops and/or retreats 
* I want to contact the owner to find out more information about their services

#### Frequent User
  As a Frequent user,
* I want to see if there are any new upcoming events
* I want to sign up to the newsletter to get latest news and offers/discounts
---

#### Structure

- Each page will contain the navigation bar at the top of the page so that user can easily navigate the site and
know which site they are on at all times.\
    Purpose is to fulfill the user story - I want to be able to  navigate through the site easily to find information and services available
- Home page will contain information about the owner and their experience in the industry\
   Purpose is to fulfill the user story - I want to learn more about the site owner and their skills.
- At the bottom of the home page user will have the option to view the upcoming events.\
    Purpose is to fulfill the user story - I want to check if there are any new classes and/or retreats
- Footer will remain the same across all pages and will contain contact information as well as social media links so user can easily contact or connect with the site owner.\
    Purpose is to fulfill the user stories:\
    I want to find ways to follow the owner on social media platforms and \
    I want to contact the owner to find out more information about their services
- "What I do" page will contain details about each of the yoga styles and healing techniques site owner is providing and teaching. 
   Purpose is to fulfill the user story - I want to learn more about the site owner and their skills.
- Site will be made responsive using Bootstrap grid and media queries to fulfill the user story\
    I want to be able to see this website clearly on my mobile device

## Design 

 #### Typogroaphy 
 Google font Acme was used trought the website 

#### Colors
  An off white shade #fafafa  was used for the text to contrast the gold #c4881be3 backgrounds.
  Same gold color was used for borders and titles and quotes
  For the text, the greyish/brown hsla(38, 38%, 25%, 0.89) color was used for easier reading as a lot of backgrounds are white
  There was a need to use grey text shadow rgba(0, 0, 0, 0.281) on some titles and navigation menu for easier reading of gold or white letters.

## Wireframes 

[Home Page](https://github.com/TanYa-Go/eleventh-embodiment/tree/master/assets/wireframes)\
[About Page](https://github.com/TanYa-Go/eleventh-embodiment/blob/master/assets/wireframes/about.pdf)\
[What I Do Page]\
[Gallery Page](https://github.com/TanYa-Go/eleventh-embodiment/blob/master/assets/wireframes/gallery.pdf)\
[Events Page](https://github.com/TanYa-Go/eleventh-embodiment/blob/master/assets/wireframes/events.pdf)\
[Contact Page](https://github.com/TanYa-Go/eleventh-embodiment/blob/master/assets/wireframes/contact.pdf)

### Differences from the original design
In the original design there was a Home page, About page and separate pages for Yoga and Healing. Also a separate page for classes and one for Retreats. 
After testing some options and considering user stories and consulting with the site owner, we realized that the purpose of the website was not clear and we decided to change it. 
Now, the parts of the old About page moved to the Home page and About page became "What I Do" page. 
I decided not to change the wireframes becaue they show the original idea which led us to current design and layout. 


## Features
- On home page under "Methods I use in my practice" there is a "Learn More" button that leads to a "What I Do" page where all methods 
   are explained in detial.
- User can click a button on the "Home" page and browse upcoming events - the "Browse Events" button leads to a separate "Events" page where all upcoming events are listed
- User can book a class on "What I do" page - the "Book Class" button opens a modal where user can open account and book a class. Idea was to 
   have user open the account first and then book a class so they can become a member. This will make it easier for them to book next time, 
   plus the owner will collect their email for future marketing campaigns
- Buttons for booking a class (and creating account) and buttons that lead to a different page within a website, purposely have different hover effect as they do different things
- Option to sign up to the newsletter is in the footer across all pages, offering free session to attract more subscribers
- Option to contact the site owner through the form located on the "Contact" page or links in the footer
- "What I Do" page has an "Ask for Advice" button where user can contact the site owner and ask for advice regarding their services
- There is a video on "Events" page that shows one of the previous retreats, user needs to click the video to play, it is not set to autoplay


 
### Features Left to Implement
- Currently the forms do not send any information so site owner is not collecting any information about users as of yet 
- Plan is to implement a payment system where a user can pay for a class, workshop or a retreat through the website


## Technologies Used

1. [HTML](https://en.wikipedia.org/wiki/HTML#:~:text=Hypertext%20Markup%20Language%20(HTML)%20is,scripting%20languages%20such%20as%20JavaScript.)

1. [CSS](https://en.wikipedia.org/wiki/CSS)

1. [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Acme' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used to add icons.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive.
1. [Gitpod](https://www.gitpod.io/)
   - Gitpod was used to create the code for the project.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/) during the design process.
1. [TinyPNG](https://tinypng.com/)
    - TinyPNG was used to reduce the overall total image size
1. [Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
 - Used during the process of creating website to help with design and debugging some issues

## Testing

Testing was planned to be completed in few stages: 
1. Test all code is working and passes through the validators without errors
1. Test website responsiveness across various browsers and various devices to confirm that the website is fully responsive.
2. Test all the features to make sure they function as intended 
3. Test user stories 

### Code validators

[HTML validator](https://validator.w3.org/) returned the following errors:

1. "The document is not mappable to XML 1.0 due to two consecutive hyphens in a comment" 
    Solution was found [here](https://www.experts-exchange.com/questions/28661509/The-document-is-not-mappable-to-XML-1-0-due-to-two-consecutive-hyphens-in-a-comment.html)
 
2. "Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections." 
    Solution was found on [stackoverflow](https://stackoverflow.com/questions/24155024/w3c-html-validation-error-section-lacks-heading-consider-using-h2-h6-elements)

3. "The aria-labelledby attribute must point to an element in the same document"
Solution found on [stackoverflow](https://stackoverflow.com/questions/39831658/how-to-fix-the-aria-labelledby-attribute-must-point-to-an-element-in-the-same-d)

[CSS Validator](https://jigsaw.w3.org/css-validator/)

No errors found

### Responsiveness

1. Initial tests were done using Chrome Dev Tools to make sure website was responding properly on all screen sizes from 320px onwards
2. Then an app called [Responsively](https://responsively.app/) was used to test multiple screen sizes in one place once more\
   Screen sizes tested:
    - iPhone X           ---- 375 x 812
    - Pixel 2            ---- 411 x 731
    - iPad               ---- 768 x 1024
    - Generic Laptop     --- 1280 x 950
    - Moto G4            ---- 360 x 640
    - Surface Duo        ---- 540 x 720  

3. Then I preformed tested the following actual devices:
  - Lenovo Laptop G780 ---- 1600 x 900 
  - iPhone 7           ----  375 x 667
  - Huawei P10         ----  360 x 640
  - A1 Alpha 20+       ----  720 x 1520
  

4. The following Browsers were tested:
   - Google Chrome
   - Microsoft Edge
   - Mozilla
   - Safari
   - Opera

#### Bugs and fixes

- Navbar collapsed menu button was not showing but was there and working. With help of my mentor we found the solution - adding the class "navbar-light" in the html solved the problem
- Navigation menu items were hovering outside of the page border on screens smaller then 992px, so I had to reduce grow hover function "transform" from scale(1.1)to (0.9)
- Font awesome icons were not showing in footer of the home page while they were showing on other pages. I then realized I had different font awesome version on 
 the home page and after I replaced it, it was working
- There was a need to align the images and text depedning on the screen size, which was acomplished with combination of Bootstrap grid and media queries

## Deployment


## Credits

### Code

#### Code Institute
- Navbar menu items "active" effect borrowed from Love Running challenge
- Code for hero image and animation borrowed from the Love Running challenge and adapted to suit my project
- Code for the form on the contact page is a combination of the forms from Love Running and Resume projects
- Code for social media icons borrowed from Love Running challenge then adapted to suit my project 

#### Other Sources
- "Grow hover" effect on navbar menu items, borrowed from [Travis Media](https://travis.media/how-to-make-an-item-grow-on-hover-with-css/) 
- Idea on how to insert a video borrowed from this [W3 Schools](https://www.w3schools.com/html/html5_video.asp) post
- Idea for making images responsive borrowed from [W3 Schools](https://www.w3schools.com/howto/howto_css_image_responsive.asp) and [Bootstrap](https://bootstrapcreative.com/make-image-responsive-bootstrap-4/#:~:text=In%20Bootstrap%204%20you%20would,than%20the%20image%20pixel%20width.)
- Code for modal borrowed from [Bootstrap](https://getbootstrap.com/docs/4.5/components/modal/) and adapted to suit the desegn of my website
- Code for linkable button borrowed from this [Stackoverflow](https://stackoverflow.com/questions/2906582/how-to-create-an-html-button-that-acts-like-a-link#:~:text=The%20plain%20HTML%20way%20is,URL%20in%20the%20action%20attribute.&text=If%20necessary%2C%20set%20CSS%20display,type%3D%22submit%22%3E%20) post
- How to center image how to center image [W3 Schools](https://www.w3schools.com/howto/howto_css_image_center.asp)
- How to center a button [W3 Schools](https://stackoverflow.com/questions/11799159/trying-to-align-html-button-at-the-center-of-the-my-page)


### Content
- All content was provided by the site owner 

### Media

- For idea on how to insert a favicon I used this [YouTube video](https://www.youtube.com/watch?v=kEf1xSwX5D8)
- Logo and favicon image was found online but I forgot to save the exact source at the time and then I couldn't locate it again
- Sourced images are from:\
  Yoga pose image - Unsplash - <span>Photo by <a href="https://unsplash.com/@sonniehiles?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Sonnie Hiles</a> on <a href="https://unsplash.com/s/photos/yoga?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>\
  Reiki image - Pixabay - <a href="https://pixabay.com/users/rhythmuswege-185829/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=285590">Jürgen Rübig</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=285590">Pixabay</a>\
  Beach Hut image -  <span>Photo by <a href="https://unsplash.com/@sjcbrn?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">SJ .
</a> on <a href="https://unsplash.com/s/photos/beach-hut?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>\
- Beach hut interior - <a href="https://pixabay.com/users/annamos-2406836/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1505461">Anna Moskowitz</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1505461">Pixabay</a>
- The other images are  all from the private collection of the site owner Ana Trajkovic herself
- Video on the events page is also provided by the site owner and is her private recording

### Acknowledgements

I'd like to say a big thank you to 
- My mentor Ignatius Ukwuama for guidance and advice
- Anna and Jim from Code Institute for amazing tutorials on how to prepare the MS1
- CI tutors and Slack students
- My paretns for minding my son while I work on this project
- And of course my friend and site owner Ana Trajkovic for trusting me to build the website and for her ideas and suggestions to make it better


