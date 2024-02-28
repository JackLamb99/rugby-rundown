# Rugby Rundown

*Rugby Rundown* is a website that allows users to develop an understanding for the sport of Rugby Union. It explains the core values of the sport, the rules by which it is governed and the various positions that that can be played. The website also offers the options to sign up for a newsletter that will update the user on new articles, social media posts and more. View the live site [**here**](https://jacklamb99.github.io/rugby-rundown/)

![Mockup](docs/readme_images/mockup.PNG)

## Features

### Site Wide

#### Navigation Menu

* The navigation menu contains the Rugby Rundown logo, which takes users to the *Home* page when clicked, as well as individual links to the *Home*, *Positions* and *Rules* pages.
* All of these options are accessible to visually impaired users who may be using a screen reader, by the use of aria-labels.
* It uses a drop-down tab option for convenient space-saving on smaller screens (less than 768px wide), making it responsive on all devices.
* This allows users to easily navigate between pages, with the current page clearly highlighted.

![Navigation Menu](docs/readme_images/navigation_menu.PNG)

![Navigation Menu - Mobile](docs/readme_images/navigation_menu_mobile.PNG)

#### Footer

* The footer contains links to social media websites that will open in a new tab and a form to sign up for a newsletter.
* The newsletter form has a required text input for user's *First Name*, an optional text input for the user's *Last Name* and a required *Email* input. A reset button labelled *Clear* can be used to reset the form and a submit button labelled *Sign up* will submit the form and take the user to the *Newsletter* page which contains a thank you message.
* All interactive features within the footer are accessible to visually impaired users, by the use of aria-labels.

![Footer](docs/readme_images/footer.PNG)

#### Favicon

* A favicon with the icon of a rugby ball is used site wide and is displayed alongside the *Rugby Rundown* name in the tab header.
* This allows users to easily identify the website if multiple tabs are open.

![Favicon](docs/readme_images/favicon.PNG)

#### 404 Page

* A 404 page has been implemented and will display if the user navigates to a broken link.
* The page contains a simple message to explain the error and a button with a link back to the *Home* page.
* This allows the users to easily navigate back to the main website if they try to access a broken link or missing page.

![404 Page](docs/readme_images/404_page.PNG)

### Landing Page

#### Gallery

* The image gallery contains a variety of images that capture different elements of the Rugby Union sport.
* A single image is visible on smaller screens (less than 1000px) and two images are visible at a time on larger screens, so the gallery is responsive on all devices. The images are in a carousel format and change on a timer.
* The purpose of the gallery is to clearly indicate the subject of the website to the user.

![Landing Page Gallery](docs/readme_images/landing_page_gallery.PNG)

#### Reasons To Love The Sport

* This section describes the reasons we *(Rugby Rundown)* love the sport and it highlights four core values. These reasons are short and direct in order to gain the users initial interest in the website.
* The boxes stack on smaller screens (less than 1000px) and form a grid on larger screens, making it responsive on all devices.

![Reasons](docs/readme_images/reasons.PNG)

#### Club Finder

* This section has a logo for each of the British and Irish national rugby teams and links to their rugby club finder tools, which open in a new tab.
* These links are accessible for visually impaired users by the use of aria-labels.

![Club Finder](docs/readme_images/club_finder_links.PNG)

### Rules Page

#### Rules Hero Image

* The hero image for the *Rules* page features referees to highlight the importance of the laws in the sport, therefore the importance of the following content.
* An image with a more centralised focus is used for smaller screens (under 1000px) and a wider image is used for larger screens to make this section responsive and visually appealing on all devices.

![Rules Hero Image](docs/readme_images/rules_hero_image.PNG)

![Rules Hero Image - Mobile](docs/readme_images/rules_hero_image_mobile.PNG)

#### Rules Accordion

* An accordion structure is used to list the major rules of the sport. The user has full control over the opening and closing of each rule through the use of checkbox inputs that toggle the display property of the content.
* A related image is incorporated into each rule to help the user visualise the content, these images are hidden on mobile devices (under 768px) for space-saving.

![Rules Accordion](docs/readme_images/rules_accordion.PNG)

#### Rules Video

* A video is included from the *England Rugby* YouTube page that explains the basics of Rugby Union.
* The video includes controls and is responsive on all devices.

![Rules Video](docs/readme_images/rules_video.PNG)

### Positions Page

#### Positions Hero Image

* The page features a hero image that shows various players and their position numbers. An image with a more centralised focus is used for smaller screens (under 1000px) and a wider image is used for larger screens to make this section responsive and visually appealing on all devices.

![Positions Hero Image](docs/readme_images/positions_hero_image.PNG)

![Positions Hero Image - Mobile](docs/readme_images/positions_hero_image_mobile.PNG)

#### Forwards Accordion

* An accordion structure is used to list the *Forwards* positions. The user has full control over the opening and closing of each position through the use of checkbox inputs that toggle the display property of the content.
* An image is incorporated into each content section to highlight each position's place on the pitch, these images are hidden on mobile devices (under 768px) for space-saving.

![Forwards Accordion](docs/readme_images/forwards_accordion.PNG)

#### Backs Accordion

* The same accordion structure is used to list the *Backs* positions and the user has the same control over the opening and closing of each position.
* The images highlighting each position's place on the pitch are continued and are also hidden on mobile devices (under 768px) for space-saving.

![Backs Accordion](docs/readme_images/backs_accordion.PNG)

#### Positions Video

* A video is included from the *Leicester Tigers* YouTube page that explains the player's positions in Rugby Union.
* The video includes controls and is responsive on all devices.

![Positions Video](docs/readme_images/positions_video.PNG)

### Newsletter Page

* Once the form within the footer is completed and submitted, users will be taken to this page as confirmation of their sign up and to thank them.
* The image and text stack on smaller screens (less than 1000px), so the page is responsive on all devices.

![Newsletter Page](docs/readme_images/newsletter_page.PNG)

![Newsletter Page - Mobile](docs/readme_images/newsletter_page_mobile.PNG)

### Existing Features

* Clearly structured and easily accessible information
* Hidden interactive sections to display the information
* Newsletter form and success page
* Responsive design

### Features Left to Implement

* In the future, the accordion design used to display the information could be updated with JavaScript to have smoother and more animated opening/closing transitions.
* JavaScript could also be used within the *Positions* content to allow users to interact with player icons to open and close the relevant tab.

## Design

### Wireframes

#### Home Page

![Home Page Design](docs/readme_images/home_page_design.png)

#### Rules Page

![Rules Page Design](docs/readme_images/rules_page_design.png)

#### Positions Page

![Positions Page Design](docs/readme_images/positions_page_design.png)

### Imagery

The images throughout the website have been taken from multiple sources due to the lack of relevant contextual images available from free image sources, all are credited below.

### Typography

* The *Jockey One* font from Google Fonts was used for all header elements; bold and “blocky” to create a more striking appearance.
* The *Lexend* font from Google Fonts was used for all paragraph elements; clear and simple to make the information easy to read.

### Colour Palette

![Colour Palette](docs/readme_images/colour_palette.png)

## Technologies

The following technologies were used in the creation of the website:

**HTML** - The structure of the website was developed using HTML

**CSS** - The website was styled using custom CSS in an external file

[**Gitpod**](https://www.gitpod.io/) - The website was developed using the Gitpod cloud-based IDE

[**GitHub**](https://github.com/) - The source code is hosted on GitHub and deployed using Git Pages

**Git** - Used to commit and push code during the development of the website

[**Balsamiq**](https://balsamiq.com/wireframes/desktop/) - Wireframes were created using the Balsamiq desktop application

[**Google Fonts**](https://fonts.google.com/) - Used to find and import the *Jockey One* and *Lexend* fonts used throughout the website

[**Favicon.io**](https://favicon.io/) - Used to find and import the rugby ball favicon

[**Font Awesome**](https://fontawesome.com/) - Used to find and import all icons used throughout the website

[**Free Convert**](https://www.freeconvert.com/) - Used to convert the images used in the website to WEBP format

[**Tinify**](https://tinypng.com/) - Used to compress the images to reduce file sizes for improved performance

## Testing

### Responsiveness

All pages were tested using *Chrome*, *Edge*, *Opera* and *Firefox* browsers to ensure responsiveness on screen sizes from 320px and upwards as defined in [**WCAG 2.1 Reflow**](https://www.w3.org/WAI/WCAG21/Understanding/reflow.html) criteria for responsive design.

Steps to test:

1. Open selected browser and navigate to the [**Rugby Rundown Website**](https://jacklamb99.github.io/rugby-rundown/)
2. Open the developer tools to inspect
3. Set the width to responsive at 320px
4. Set the zoom to 50% to fit the larger screen sizes
5. Click and drag the width toggle at the side of the page to maximum width

Expected:

Website is responsive on all screen sizes and no horizontal scroll is present. No elements overlap and no images are stretched or oversized. 

Actual:

The website behaved as expected with the exception of the carousel gallery image size on Mozilla Firefox. Further details can be found in the [**Unfixed Bugs**](#Unfixed-Bugs) section.

The website was also opened on the following devices and no responsive issues were observed:

* Samsung Galaxy S20
* Apple iPhone 12
* Apple iPad Air
* Google Chromebook

### Accessibility

[**Wave Accessibility**](https://wave.webaim.org/) tool was used to ensure all pages met the needs for any screen readers or accessibility aids for visually impaired users. `aria-hidden="true"` labels were applied to icons and some elements used only for visual design purposes to remove unnecessary clutter for screen-readers.

Below are the results for each page, all received a positive score and no errors were found:

#### Home Page

![Home Page Wave Results](docs/readme_images/home_wave.PNG)

#### Rules Page

![Rules Page Wave Results](docs/readme_images/rules_wave.PNG)

#### Positions Page

![Positions Page Wave Results](docs/readme_images/positions_wave.PNG)

#### Newsletter Page

![Newsletter Page Wave Results](docs/readme_images/newsletter_wave.PNG)

#### 404 Page

![404 Page Wave Results](docs/readme_images/404_wave.PNG)

### Lighthouse Testing

The *Lighthouse* extension on *Google DevTools* was used to test the overall functionality and performance of the website:

#### Home Page

![Home Page Lighthouse Results](docs/readme_images/home_lighthouse.PNG)

#### Rules Page

![Rules Page Lighthouse Results](docs/readme_images/rules_lighthouse.PNG)

#### Positions Page

![Positions Page Lighthouse Results](docs/readme_images/positions_lighthouse.PNG)

#### Newsletter Page

![Newsletter Page Lighthouse Results](docs/readme_images/newsletter_lighthouse.PNG)

#### 404 Page

![404 Page Lighthouse Results](docs/readme_images/404_lighthouse.PNG)

### Functional Testing

#### Navigation Links

Testing was performed to ensure all navigation links directed the user to the correct pages as designed:

| Navigation Link | Directed to Page |
| :---- | :---- |
| Rugby Rundown Logo | index.html |
| Home | index.html |
| Aventures | adventures.html |
| Gallery | gallery.html |