# Milestone project 1: Building a websitie for a gym ADZ Fitness

## The purpose of the project

* To create a unique responsive website using HTML and CSS for a gym which will aim to attract potential members who are looking to get fit and healthy and what to sign up to a gym, they will also want to know more about the gym and what the gym has to offer including facilities, training sessions, which they will then have the option to sign up with the gym. The website will also aim to be useable for visting users and member who are already signed with the gym.

***

## User Experience (UX)

## Strategy
### User Stories

#### First time visitor goals:

* As a first time visitor im looking to sign up to a gym as i feel that i need to keep myself fit and healthy, i want to easily understand how to navigate the site annd switch to other pages with ease aswel as being able to use the site on other devices
* I Want to understand what the gym has to offer such as their aims for their members aswell as what training session they run during the week
* I also want to know the location of the gym and the opening hours as i need to see if i can find a time that works for me
* I would also like to see what facilities the gym has to offer 
* I would like to also have an option to sign up for the gym and become a member

#### Visting User goals:

* As a visting user to the site, i want to find the information on the training sessions that the gym have on a weekly basis to see if there are any changes to the schedules
* Being a visting user and a member of the gym i want to have easy access to the contact information of the gym if i have any issues or queries, also be able to check the opening hours of the gym 
* Also as a visting user i want to be able to use the site on other devices when im on the go without having any viewing issues

#### Reasons for the website:

* To bring in more members
* To showcase work
* To allow new and exisiting members to contact us and connect with us

## Scope
#### What a user may expect:

* Easy to navigate website aswell as being responsive
* A site that is visually appealing on all devices
* Information about the gym and what they aim to do for members 
* links and function working as expected
* Ways to access and contact information with the gym aswell as their opening times

#### What a user may want:

* To be able to find links to the gyms social media pages and connect with them
* To see reviews of from exisiting members of the gym and how they rate the gyms facilites and staff
* To be able to chat with someone online if any queries may occur
* To be able to sign up to the gym and become a member same day
* To be be able to see what activitys and sessions the gym offers during the week

#### As a developer / business I expect:

* To provide information about the gym
* To provide an easy way for new and existing members to contact us
* To showcase images of the gyms facilites and staff aswell as members
* To provide an easy to navigate website with links that work as expected
* To encourage new users to sign up and become a member of the gym

## Structure
The website will consist of 3 separate pages:
* A home page with a hero image and with slogan "Every rep counts...", a section with the heading “Why join ADZ fitness” explaining reasons to join the gym with the gyms aims and goals for members, a Gym training schedules sections which will showcase the gyms training sessions during the week 
* A gallery page that will showcase images of the gyms facilities and members  
* A sign up page with a form for new users to fill out that want to join the gym 

***

## Features

### Navigation Bar:

The Navigation bar will be vibrant and easy to use with the name of ADZ fitness with a home, signup and gallery button which users will be able to click to navigate from page to page, aswell as having a dropdown button when being viewed on smaller screen devices making it fully responsive

### Footer:

The Footer will contain social media links for users to browse and connect even further with the gym aswell as vibrant design matching with the navigation bar, it will also have and about us section and the opening hours of the gym aswell as also having the contact information of the gym. The footer wil also be repsonsive for all devices aswell

### Home:

Home page will include details about the gyms goals and aims for members and new users with showcase images aswell as having a bold hero image, it will also contain the gyms training schedules that is done during the week

### Sign up page:

Sign up page will include a sign up form for new members to fill in their details so that they will be contacted with an induction date

### Gallery Page:

The Gallery page will showcase images of the gym and facilities aswell as photos of members of the gym working out

***

## Future Features 

A future feature that i would like to add to my website would be a login portal for members so that they can see for example their stats on their gym usage for the week aswell as them being able to log in their progress and make a sort of timetable that suits them

***
## Skeleton

### Wireframes:
Note: Wireframes for the desktop share the same strucuture for tablet

* Wireframes for desktop have been created for all three pages and can be viewed through this link: (https://github.com/adilkhr/my-ms1-project/blob/master/wireframes/wireframesMS1desktop.pdf)

* Wireframes for mobile phone have been created for all three pages and can be viewed through this link: (https://github.com/adilkhr/my-ms1-project/blob/master/wireframes/wireframesMS1phone.pdf)

### Mockup:

![Mock ups](README-files/mockuphomepge.png)
![Mock ups](README-files/mockupgallerypage.png)
![Mock ups](README-files/mockupsignuppage.png)

***

### Typography and color scheme

* For Typography i used google fonts and used the font familys of russo one and robboto with the russo one font being the main font family used across the site as its font that i felt stands out alot
* The color scheme used throughout the page were mainly white, black and a royal dark blue as i felt there was no need to overcomplicate the site with too many colors otherwise it wouldnt look visually appealing, i used the hex values of #fff for an offwhite color and #001684 for a nice dark royal blue shade across the page

***

## Technonologies Used

* The Languages used to code my project were HTML5 to create the Mark-up language using sematic structure, and CCS3 for the Cascading style sheet used to style the content look visually appealing
* I used Google fonts and fontawesome icon links in my pages to add specific font styles aswell as icons to my page to make it look appealing and not dull and boring
* I used bootstrap version 4.6 to create sections of the pages so that it would be resonsive for all screens  
* I used Github to host the repository and Gitpod.io to write the code, and using the command line for committing and pushing the code to Github
* I used GIT for version control of the project
* I used Balsamiq wireframes to create wireframes for my site
* I used Paint to create design the hero image of the home page of the site

***

## Testing

### Supported screens and browsers:

After using bootstrap to build my pages and the use of CSS media queries styles, my site is supported for all screens with a width of 280px and above and is supported for all browsers

### Test cases:

### Code validation:

I had used the w3schools validator tool to see if there was any issues with my HTML and CSS codes, (https://validator.w3.org/)

* When inputing my index.html code through w3schools validator i had noticed there was erros with the images used for the gyms aims section as they did not have alt attributes, after adding the alt attributes there is no erros with the index html code
* When inputing gallery.html code through w3schools validator there was no errors
* When inputing signup.html code through w3schools validator i had a 2 major problems, i had a typo error with the for attributes for the label tags and i had also had the name attributes empty for the input tags in the sign up form, after resolving that issue, there is no erros with the signup html code 
* When inputing CSS coding through w3schools validator there was no erros

### Fixed bugs:

* An issue i was having with my home page was that i found that the gym trainning schedule table was not responsive for the galaxy fold screen which has a 280px screen width causing some horizontal scrolling to occur, i had fixed this issue by adding a media query to reduce the font size when viewed on smaller screen sizes

***

## Deployment

The deployment process of my project was simple, when creating my html pages through gitpod i had made sure that i had added the file and then git commit it with a message then done a git push, once that was done i ensured that i had deployed the github pages by going on the github pages section and changing the source branch to master so that the site would be live and published giving me the live sight URL. I had ensured that git commit adds and git commit messages were done regurlaly and nessecary with relevant comments and then pushed out with the git push comand through git pod

***

## Credits

* All images were taken from https://unsplash.com/images/stock
* I had taken some inspirtation from the code institute project Love running to help give me an idea on how to strucutre my site and what to include in my pages
* I had used bootstrap version 4.6 to help me create a responsive site by using bootsrap navigation to build the nav bar, bootstrap cards to create the gyms goals and aims section in the home page, bootstrap table to create a responsive gym training schedule in the home page aswell as using bootsrap carousel to showcase the gyms photos in the gallery page aswell as using bootstrap forms to create a responsive signup form and bootstrap footer for the responsive footer https://getbootstrap.com/docs/4.6/getting-started/introduction/



