# Reading Club

![Reading Club website shown on a variety of screen sizes](/assets/images/reading-club.jpg)

Visit the deployed site: [Reading Club](https://github.com/KatVolkova/reading-club)

Reading Club is a website created to attract those interested in reading. The target audience for this site is avid readers who would like to expand their knowledge on numerous literary genres, express their thoughts by sharing reviews and participating in the readers' community, enjoy book quizzes and take part in reading challenges.

## Table of Contents
  
- [Reading Club](#reading-club)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
    - [General](#general)
    - [Navigation bar](#navigation-bar)
    - [Hero Image](#hero-image)
    - [The summary section](#the-summary-section)
    - [Footer](#footer)
    - [About Us page](#about-us-page)
    - [Reading Challenge page](#reading-challenge-page)
    - [Join Us page](#join-us-page)
  - [Design](#design)
  - [Wireframes](#wireframes)
    - [Colour Scheme](#colour-scheme)
    - [Typography](#typography)
    - [Images](#images)
  - [Technologies Used](#technologies-used)
    - [Languages Used](#languages-used)
    - [Programs/Applications/Software Used](#programsapplicationssoftware-used)
  - [Deployment](#deployment)
  - [Testing](#testing)
    - [Solved Bugs](#solved-bugs)
  - [Credits](#credits)

- - -

## Features

### General

The Reading club website consists of four pages:

- Home page
- About Us
- Reading Challenge
- Join Us

The wibsite is fully responsive.
Each page has a navigation bar and footer as well as:

- favicon in the browser tab:

- Logo located inside the navigation section that acts as a link to the Home page:

### Navigation bar

![Navigation Section](/assets/images/navigation-reading-club.jpg)
![Navigation Section for Mobile Phones](/assets/images/navigation-mobile-reading-club.jpg)

Each of four pages has a responsive navigation bar that consists of:

- Logo used as a toggler for mobile phone screens
Links to:

- Home page
- About Us page
- Reading  Challenge page
- Join Us page

The navigation section is intuitive to use and provides users with easy access to all website pages. For mobile phone users the navigation links are replaced by a dropdown menu.

### Hero Image

![Hero Image](/assets/images/hero-page-reading-club.jpg)

The hero section includes an image with Reading Club heading and a quote. Both suit the purpose of conveying the main idea of the site.

### The summary section

![Summary Section](/assets/images/summary2-section-reading-club.jpg)

The summary section provides a very brief introduction to what users can expect from the website. About us and Reading Challenge Learn More links direct users to the relevant pages of the website.

### Footer

![Footer](/assets/images/footer-reading-club.jpg)
The footer section features:

- an email link so the users can directly ask their specific questions.
- social network links to ensure that users can get updates on the events organised by the Reading club community.
- join us button is presented in both navigation and footer sections for easy access.

### About Us page

![About Us Page](/assets/images/about-page-reading-club.jpg)

About Us page provides the description of activities that Reading Club can offer their audience:

- Book recommendations
- Readers community
- Readers reviews
- Quizzes
Activities section gives a more detailed description of each activity and also includes the image in the middle.

### Reading Challenge page

![Reading Challenge Page](/assets/images/reading-challenge-page-reading-club.jpg)

Reading challenge page introduces the idea of the reading challenges and explains the reasons it could be interesting to people.
The Monthly schedule section provides a list of reading challenges for the specific genre for each month.
The meet up point section is targeted at those who live or visit London at the time meetups take place, it also provides a map where the meetups could be hosted for a small group of people.

### Join Us page

![Join Us Page](/assets/images/join-us-page-reading-club.jpg)

Join us page includes the simple sign up form for those who want to be a part of the readers community and benefit from the various events and activities.Both fields in the form are required to be completed.

## Design

## Wireframes

Balsamic software was used to create wireframes for both desktop and mobile phones. Please note these wireframes represent the very first draft of the website. Quite a few features have been changed/removed/added.
![Desktop Design](/assets/images/readme/balsamic-wireframe-desktop.jpg)
![Mobile phone design](/assets/images/readme/balsamic-wireframe-mobile.jpg)

### Colour Scheme

Colours used:

- background colour `#1f1f24`  
- font colour `#FAEBD7`
The colours above create the right contrast and contribute to the site's readability. The screen shot below is an example of these two colours combination:
![Colour Scheme](/assets/images/readme/colour-pallete-example.jpg)

### Typography

Google fonts have been used for this website

- Hind Siliguri font style has been used as the general font.
  ![Hind Siliguri](/assets/images/readme/hind-siliguri-google-fonts.jpg)
- Crimson Text font style has been used for the h1 heading.
  ![Crimson](/assets/images/readme/crimson-google-fonts.jpg)
- Niconne has font style been used for all heading apart from the h1 heading.
  ![Niconne](/assets/images/readme/niconne-goole-fonts.jpg)

### Images

Pictures have been taken from [Pexels](https://www.pexels.com/search/books/)

## Technologies Used

### Languages Used

HTML, CSS

### Programs/Applications/Software Used

- [Git](https://git-scm.com/) - For version control.
- [Github](https://github.com/) - To save and store the files for the website.
- [Google Fonts](https://fonts.google.com/) - To import the fonts used on the website.
- [Google Developer Tools](https://developers.google.com/web/tools) - To troubleshoot and test features, solve issues with responsiveness and styling.
- [Canva.com](https://canva.com/) To create and customise favicon and logo
- [Am I Responsive?](http://ami.responsivedesign.is/) To show the website image on a range of devices.
- [Pixlr](https://pixlr.com/) To re-size and convert pictures into webp format
- [Grammarly](https://app.grammarly.com/ ) - has been used for spell-checking
- [Balsamiq](https://balsamiq.com/) - Used to create wireframes.
- Codeanywhere has been used as IDE

- - -

## Deployment

The site is deployed using GitHub Pages - [Reading Club](https://github.com/KatVolkova/reading-club/).

To Deploy the site using GitHub Pages:

1. Login (or signup) to Github.
2. Go to the repository for this project, [KatVolkova/Reading-Club](https://github.com/KatVolkova/reading-club/).
3. Click the settings button.
4. Select pages in the left hand navigation menu.
5. From the source dropdown select main branch and press save.
6. The site has now been deployed, please note that this process may take a few minutes before the site goes live.

## Testing

Validator testing was carried out using the following:

- HTML files of all four pages do not contain either errors or warnings according to the official [W3C validator](https://validator.w3.org)
- CSS file does not contain either errors or warnings according to the official [Jigsaw validator](https://jigsaw.w3.org/css-validator/)
  
### Solved Bugs

- The error identified in the middle of the project is the use of a combination of a button and a link element, as the button element cannot be a child decendent of a link and vice versa. This error has been fixed by leaving the link only and styling it as a button using CSS.
	 
- Join Us button had the same colour applied for both the background and the border properties. This error has been fixed by removing the border colour.
	 
- Spelling mistake for align-items attribute value:center has been corrected.

- Trailing slashes have been removed from meta elements.
  
- - -

## Credits

- Templates for a Logo and favicov were taken and customised using [Canva](https://www.canva.com/)
- Pictures were taken from [Pexels](https://www.pexels.com/)
- Fonts were taken from [Google Fonts](https://fonts.google.com/)
- Icons for drop-down menu were taken form [Font Awesome](https://fontawesome.com/)
- Picture were re-sized and converted into webp format using [Pixlr](https://pixlr.com/)
- "Pixels or rem in CSS" article [Austingil](https://austingil.com/px-or-rem-in-css/)
- "Transition property in CSS" article [W3school](https://www.w3schools.com/css/css3_transitions.asp)
- "Breakpoints for responsive Web Design in 2023" article [Browserstack](https://www.browserstack.com/guide/responsive-design-breakpoints)
- The list of literary genres was taken from [Wikipedia](https://en.wikipedia.org/wiki/List_of_writing_genres)
