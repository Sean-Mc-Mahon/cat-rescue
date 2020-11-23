# Phibsboro Cat Rescue

### [Live Site]()

### [GitHub](https://github.com/Sean-Mc-Mahon/cat-rescue)

![Various Devices]()

Phibsboro Cat Rescue is a Milestone 3 project, it is part of the Fullstack Software Development Course of [Code Institute](https://codeinstitute.net/).

## Table of Contents

1. [**Project overview**](#project-overview)

   - [**User Stories**](#user-stories)

2. [**UX Planes**](#ux-planes)

   - [**Strategy Plane**](#strategy-plane)
   - [**Scope Plane**](#scope-plane)
   - [**Structure Plane**](#structure-plane)
   - [**Skeleton Plane**](#skeleton-plane)
   - [**Surface Plane**](#surface-plane)
     - [**_*Color Scheme*_**](#color-scheme)
     - [**_*Typography*_**](#typography)
     - [**_*Media*_**](#Media)
     - [**_Wireframes_**](#wireframes)

3. [**Features**](#features)

   - [**Existing Features**](#existing-features)
   - [**Features Left to Implement**](#features-left-to-implement)

4. [**Technologies Used**](#technologies-used)

   - [**_Libraries_**](#libraries)
   - [**_Version Control_**](#version-control)

5. [**Testing**](#testing)

   - [**_Problems and Solutions_**](#problems-and-solutions)
   - [**_Validators_**](#validators)
   - [**_Manual Testing_**](#manual-testing)

6. [**Deployment**](#deployment)

7. [**Credits**](#credits)

   - [**_Content_**](#content)
   - [**_Acknowledgements_**](#acknowledgements)

---

## Project Overview

Phibsboro Cat Rescue is a site where cat fosterers can create profiles for cats in their care to be viewed by potential adopters. PCR is a real charity which I am a member of as a fosterer. The flow of data in the organisation is a complicated system of social media, emails spreadsheets and folders and I aim to simplify this process. 

### User Stories

_- User Story A: Joe is a fosterer with PCR and wants to create a profile and add data for a cat in his care. _  
_- User Story B: Liz is looking to adopt a cat and wants to view cats that are available for adoption and contact PCR about adopting. _  
_- User Story C: Harry adopted a cat from PCR last year and wants to show how well his cat is doing and share his story with other potential adopters. _  
_- User Story D: Hazel runs PCR and wants all available information on cats and fosterers to be easily located and retrieveable on a beautiful website. _

## UX Planes



### Strategy Plane

#### Project Goals:

- 
- 
- 

#### User Goals:

- 
- 
- 
- 

#### Personal Goals

- To learn and practice frontend and backend programming together for the first time. To combine the use of HTML, CSS, Materialize and JavaScript with Python, MongoDB, Flask and Jinja.

### Scope Plane



### Structure Plane



### Skeleton Plane

- Nav Bar: 
- Main: 
- Footer: Displays copyright information and provides links to social pages.

Each page may be navigated to eachother with one click.

### Surface Plane

#### Design

A standard layout is fully responsive on mobile devices and larger screens.

#### Color Scheme

Color scheme is based on existing PCR branding and my color scheme can be found on my Coolors profile: [Coolors](https://coolors.co/u/sean_mcmahon)

![Color Palette]()

#### Typography

2 [Google Fonts](https://fonts.google.com/) were used across the site:

- [Lily Script One](https://fonts.google.com/specimen/Lily+Script+One?query=lily) : Logo & Headings, used for it's bold style.
- [Montserrat](https://fonts.google.com/specimen/Montserrat?query=montse) : Body, used for it's excellent readability.

Font sizes for the headings are mostly responsive using the calc() function.

#### Media

All images, models and featured products are the authors own. Logos are also produced by the author.

#### Wireframes

I used Balsamiq and figma to create the wireframes. The layout has altered since I created the wireframes as I decided against displaying all pages along side each other on the home page.

- [Balsamiq Wireframe]()

- [Figma Wireframe]()

##### back to [top](#table-of-contents)

---

# Features

## Existing Features

### Elements on every page
- Navbar
    - The navigation bar features the PCR logo in the top left corner. The logo and name are links to the home page.

    - For visitors to the site who are not logged in, list items links are available for them to use.
        1. Adopt
        2. Volunteer
        3. Gallery
        4. Contact
        5. Login

    - For users who are logged in, the list items are as follows: 
        1. Adopt
        2. Volunteer
        3. Gallery
        4. Contact
        5. Add Cat
        6. Profile
        7. Sign Out

    - Python determines if the user is logged in or not by checking `if 'user' in session` and passes this data to Jinja to display the correct navbar for the user.

    - On small screens the navbar is collapsed into a burger icon on small screens.

- Footer
    - The footer features:
        - Copyright Information
        - Links to existing social media platforms of the charity.

- All Pages - 

- Index - 

Carousel

Map

Social Media iFrame

- Adopt - 

This section contains a gallery of cats available for adoption with some basic information about the cats.

- Contact - 

This section has a form where users can enquire about volunteering as well as a google map.

- Volunteer - 

This section contains information on volunteering as well as a form that potential volunteets may fill out.

- Gallery - 

This section contains images and descriptions of cats succesfully rehomed by PCR.

- Contact - 

This section contains a form where people may get in contact with PCR as well as a Google Map.

- Login - 

This section contains a form where users may login and be redirected to their profile, alternatively they will have the option of registering an account.

- Profile - 

This section contains a form where users may update their information and current availability to foster cats.

- Add Cats - 

This section contains a form where users may provide details for cats currently in their care.


## Features Left to Implement

- Option to donate online.

- Floating to top button:
    - A floating button appears on the lower right of the screen when the user starts to scroll downwards. Clicking this moves the view back up to the top of the page. I added this feature because some pages can be quite long and the navbar is not fixed to the top of the page.
    - Adding the class `.active` to the `#to-top-button` changes it's `opacity` from `0` to `0.5`, which gave me the ability to animate the change gently. The opacity is increased again to `1` on hover. 

##### back to [top](#table-of-contents)

## Technologies Used

1. **HTML (Hyper Text Markup Language):** Used throughout the site;  
   https://developer.mozilla.org/en-US/docs/Web/HTML
2. **CSS (Cascading Style Sheets):** Used throughout the site;
   https://www.w3.org/Style/CSS/Overview.en.html
3. **Bootstrap:** Used to aid responsive design and for componants such as carousels and buttons https://getbootstrap.com/
4. **Visual Studio Code:** Code Editor used to create the site.
   https://code.visualstudio.com/
5. **GitHub:** Used to host repos for the site https://https://github.com/Sean-Mc-Mahon/ms2-seanmcmahon-digital-design
6. **Chrome/Firefox/Bing DevTools:** Regularly used to test the site https://developers.google.com/web/tools/chrome-devtools
7. **W3C Markup Validation Service** Used to test code for errors; https://validator.w3.org/https://jigsaw.w3.org/css-validator/validator
8. **Affinity Designer** Illustration software used to create ...; https://affinity.serif.com/en-gb/
9. **Figma** Collaborative interface design tool used for creating wireframes as well logos and SVGs; https://figma.com
10. **Balsamiq** Used to create wireframes; https://balsamiq.com/?gclid=EAIaIQobChMIuoqlhfWi6wIV6YBQBh2f9w7DEAAYASAAEgLUTfD_BwE
11. **Tinypng** Used to compress images; https://tinypng.com/
12. **Croppola** Used to crop images; https://croppola.com/
13. **Randomkeygen/** Used to generate random keys; https://randomkeygen.com/

### Libraries

- [Bootstrap 4](https://getbootstrap.com/) - is a framework for building responsive, mobile-first websites. I primarily used bootstrap to format layouts and for certain components such as image carousels and buttons.

- [JQuery](https://jquery.com/) - is a Javascirpt library. I primarily used JQuery to add and remove classes on hover states.

- [Flask](https://flask.palletsprojects.com/en/1.1.x/) - is a lightweight WSGI web application framework. I primarily used it to construct and render pages.

- [Jinja](https://flask.palletsprojects.com/en/1.1.x/) - is a templating language for Python. I primarily used it to display data from the backend in HTML.

- [PyMongo](https://flask.palletsprojects.com/en/1.1.x/) - is the recommended way to work with MongoDB from Python, used to make communication between Python and MongoDB.

- [dnspython](https://pypi.org/project/dnspython/) - is a DNS toolkit for Python.

### Version Control

- [Git](https://git-scm.com/) - used for version control

- Branches were used to ...

## Testing

### User Stories

_- User Story A: ._   
Joe can ...

_- User Story B: Liz would also like to..._  
Liz can...

_- User Story C: Harry is interested in..._  
Harry can ...

_- User Story D: Hazel would like to..._
Hazel can ...

### Problems and Solutions

- 

- 

- 

### Validators

1. **HTML:** [W3C HTML Validator](https://validator.w3.org/) Used to identify HTML errors.

2. **CSS:** [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) Used to identify CSS errors.

3. **Javascript:** [JSHint](https://jshint.com/) Used to identify Javascript errors.

### Manual Testing

1. **Developer Tools:** Chrome, Firefox and Microsoft Edge web dev tools using iPhone 5 and Ipad as toggle devices to test responsiveness.

2. **Lighthouse:** A number of issues were resolved using lighthouse.

3. **Mobile Devices:** I used my Google Pixel 3a phone and Amazon Fire tablet to test the site.

4. **amiresponsive:** [Am I Responsive](http://ami.responsivedesign.is/) Used to test responsiveness across a range of devices.

5. **Friends and family:** I asked for feedback from friends and family in order to get a users perspective.

6. **Contact Form:** On the contact page the form may not be submitted without using correct syntax for the e-mail input or if either input is blank. Once inputs are filled properly and submit is clicked the form will clear without the page being refreshed and an alert will inform user that the message has been sent.

9. **Navigation:** Clicked through all links to ensure they all go to the correct location.

## Deployment

CHANGE DEBUG=TRUE TO FALSE IN APP.PY PRIOR TO DEPLOYMENT

1. I Created a Github account at https://github.com
   My account url; https://github.com/Sean-Mc-Mahon

2. I installed Git and set up a username and password.

3. I created a repository on Github (https://github.com/Sean-Mc-Mahon/cat-rescue)

4. On VS Code I opened the command pallette and selected Git Clone, I pasted in the URL for the repo on GitHub and selected a folder on my computer to sync to.

5. I uploaded all files to my Github repository.

6. To publish the project to see it on the web, I then went into the Settings on my respository, scrolled down to the heading, GitHub Pages. Under the Source setting, I used the drop-down menu to select master branch as a publishing source and saved it. Refreshed the github page, and you are then given a url where your page is published;
   Your site is published at https://github.com/Sean-Mc-Mahon/

7. To run this code on a local machine, you would go to my respository at
   https://github.com/Sean-Mc-Mahon/cat-rescue and on the home page on the right hand side just above all the files, you will see a green button that says,
   "Clone or download", this button will give you options to clone with HTTPS, open in desktop or download as a zip file.
   To continue with cloning, you would;

- Open Git Bash
- Change the current working directory to the location where you want the cloned directory to be made.
- Type git clone, and then paste this URL; https://github.com/Sean-Mc-Mahon/ Press Enter. Your local clone will be created.

For more information about the above process; https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository

---

## Credits

### Content

1.  Google Fonts for font styles; https://fonts.google.com/

2.  Youtube; ... inspired by youtube tutorial by [...](...)

3.  Stack Overfow; Code to implement ... taken from answer by ... [Stack Overflow](https://stackoverflow.com/)

7.  Slack; ... inspired by tutorial via ....

8.  Youtube; Bootstrap Carousel inspired by youtube tutorial by [Clever Techie](https://youtu.be/AvMl3StAju4)

9.  developedbyed.com; burger animation and page transitions modified from tutorial @ [developedbyed](https://developedbyed.com/) 

### Acknowledgements

1.  My mentor Adegbenga Adeye for his support and input.

2.  My peers on slack for their generosity in sharing their knowledge and experience.

##### back to [top](#table-of-contents)