# Personal Resume Website

![alt text](https://github.com/yipmunallen/First-Milestone-Project/blob/master/assets/images/websitescreenshot.png "Website Screenshot")

This is a static (front-end) personal resume website for Yip Mun Allen, the creator of the site. It is designed to be a creative way for prospective recruiters to find out more about the website owner. 
The responsive nature of the site means that it easy to read on all media devices and a single-page design was chosen in order to make it easy to quickly jump 
to the sections that the recruiter may be interested in without the need for opening new pages. 

## Table of Contents
1. [Ux](#ux)
   1. [Users stories](#users-stories)
   1. [Design](#design)
      1. [Wireframes](#design)
      1. [List of Sections](#list-of-sections)
      1. [Colour Scheme](#colour-scheme)
      1. [Typography](#typography)
      1. [Menu Bar](#menubar)
1. [Technologies used](#technologies-used)
   1. [Languages Used](#languages-used)
   1. [Frameworks, Libraries & Programs Used](#frameworks-libraries-&-programs-used)
1. [Testing](#testing)
   1. [User stories](#testing-user-stories)
   1. [Functionality](#functionality)
   1. [Compatibility](#compatibility)
   1. [Validation](#validation)
1. [Content](#content)
1. [Acknowledgements](#acknowledgements)

## UX

The primary target audience is recruiters who will use the site to find out more information about the website owner and potentially contact them with a job opportunity. The website was created to be intuitive and provide easy access to any information the recruiters may be looking for.

 ### Users Stories
As a recruiter I want to:

1. Get all of the information I'm looking for quickly and easily as there will be lots of potential applicants.
1. Find out more about the creator's work experience and education history to see if they have relevant experience and qualifications for the role.
1. Clearly see what the creator's skills are in order to match them to a suitable role.
1. Have access to a CV that can be saved offline.
1. Be able to contact the creator with potential opportunities.

### Design

- #### Wireframes

  - [Hero Image/About](https://github.com/yipmunallen/First-Milestone-Project/blob/master/assets/images/heroabout.png)
  - [Education](https://github.com/yipmunallen/First-Milestone-Project/blob/master/assets/images/education.png)
  - [Skills/Projects](https://github.com/yipmunallen/First-Milestone-Project/blob/master/assets/images/skillsprojects.png)
  - [Contact](https://github.com/yipmunallen/First-Milestone-Project/blob/master/assets/images/contact.png)

- #### List of Sections 

  -  __About__ -
Provides some basic information about the site owner along with a summary written to introduce them.

  - __Experience__ -
Gives an overview of the owner's work experience and education history.

  - __Skills__ -
Highlights some of the core skill of the site owner that recruiters may be looking out for.

  - __Projects__ -
Designed to show certain projects that the website owner has worked on. Text giving a summary of the project is paired with an image / screenshot of the project. 
Both the image and text are links to the website/project that is being described. 

  - __Contact__ -
Contains a form that allows users to quickly and easily contact the site owner without having to navigate away from the page.

-   #### Colour Scheme
    -   The two main colours used are white and turqoise. This scheme complements the colours within the hero image and is used to differentiate between the sections, making them easy to identify as you scroll down the page.

 -   #### Typography
      -   The main font used throughout the site is "Noto San JP". "Roboto" is also used for the section headings and the name in the hero section as well as the navbar. Sans-serif has been used as the fallback font throughout. These fonts are chosen as they are easy to read and appropriate for a professional look.

## Technologies Used

### Languages Used

- **HTML5** - Used to structure and present the website.
- **CSS** - Used to style the website.
- **JavaScript** - Used for the navbar so that when a link was selected, or the user clicked outside the menu, the navbar would collapse again.

### Frameworks, Libraries & Programs Used

- **Mockflow** - Used to create the wireframes during the planning stage of the project.

- **Bootstrap Framework** - This was certain features such as the navbar and project cards. The grid design was also used throughout the sections in order to facilitate the responsive design.

- **JQuery** - Added with Bootstrap in order to make the navbar responsive.

- **Google Fonts** - Used to import the "Noto San JP" and "Roboto" fonts used throughout the site.

- **Font Awesome** - Used to import the linkedin icon used in the About section, and the circles in the Skills section.

- **Git** - Used for version control.

- **Github** - Used to store all website code once pushed from Git.

### Testing

The W3C Markup Validator and W3C CSS Validator Services were used to identify any syntax errors in the project

#### User Stories

1. As a recruiter I want to get all of the information I'm looking for quickly and easily as there will be lots of potential applicants.
    1. The menu bar at the top of the page makes it easy for users to quickly jump to the sections of the page that they are interested in. The bar has been made "sticky" so it is accessible wherever the user is on the page.
    2. The alternating colours between the sections as well as large section titles mean that information is easily found when scrolling down the page.
2. As a recruiter I want to find out more about the creator's work experience and education history to see if they have relevant experience and qualifications for the role.
   1. The Experience section is accessible from the menu bar.
   2. The section is clearly divided into "Work" and "Education".
   3. The design of this section provides a clear timeline to all prospective users, with additional information available for wider screen sizes.
1. As a recruiter I want to clearly see what the creator's skills are in order to match them to a suitable role.
   1. The skills section is accessible from the menu bar.
   2. The skills section of the site uses coloured circles to clearly indicate skill level
1. As a recruiter I want to have access to a CV that can be saved offline.
   1. A "Download CV" button is available wherever the user is on the site via the menu bar. It opens in another page so the original site is not lost.
   2. A "Download CV" button is also available in the About section.
1. As a recruiter I want to be able to contact the creator with potential opportunities.
   1. The contact section is accessible from the menu bar.
   2. The form in the contact section means that the user does not have to leave the site in order to contact the site owner. 
   3. A link to the site owner's LinkedIn profile is in the About section which provides another means of contact.

#### Functionality

  - __Contact Form__ - This has been tested to ensure that if the "submit" button is selected without any of the fields being filled, an error will appear asking the user to complete fields. Similarly, if an email address is inputted without an "@" sign, an error will also appear, stating that this is not a valid email.

  - __Links__ - The "Download CV" button, LinkedIn icon, and Project cards have been tested to ensure they open in new windows to valid pages.


  - __Menubar__ - The menu bar has been tested to ensure that it collapses and takes users to the correct sections on the page once a link is clicked. Users can also close the menu bar by clicking out of the menu.

#### Compatibility

  - __Devices__ - The website has been viewed and tested on a range of devices including Desktop, Laptop, Iphone 6/7/8/X, Ipad and Samsumg Galaxy Tab, retaining structure and functionality.

  - __Browsers__ - The website has been viewed and tested on a range of browsers including Google Chrome, Internet Explorer and Firefox, retaining structure and functionality.

#### Bugs

  - __Iphone 5__ - When emulating using the website on an Iphone 5, a white strip appears down the right side of the screen. However, this could be due to the browser's emulation of the device. Structure and functionality remain the same. 

  - __Menubar__ - Whilst the menu bar collapses once a link or somewhere outside the bar is clicked, clicking on the hamburger icon once inside the menu does not collapse it again. 


#### Validation

  - __CSS__ - Validated using [Jigsaw](https://jigsaw.w3.org/css-validator/#validate_by_input) with no errors found.

  - __HTML__ - Whilst the menu bar collapses once a link or somewhere outside the bar is clicked, clicking on the hamburger icon once inside the menu does not collapse it again. 

## Credits

### Media

The hero image was downloaded from [Pixabay](https://pixabay.com/photos/desktop-tidy-clean-mockup-white-2325627).

The second screenshot in the projects is taken from [CloudTrade](https://cloudtrade.com), and the website was not actually built by myself.

The third screenshot in the projects is taken from [The Wellesly](https://www.marriott.co.uk/hotels/travel/lonwb-the-wellesley-knightsbridge-a-luxury-collection-hotel-london/) and the website 
was not actually built by myself.

### Acknowledgements
- Spencer Barriball - Mentor 
- [Code Institute](https://www.codeinstitute.net/)
- [Pascal Van Gemert](http://www.pascalvangemert.nl/) - His resume provided the inspiration behind the design of the website.
