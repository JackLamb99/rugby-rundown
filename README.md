# Rugby Rundown

'Rugby Rundown' is a website that allows users to develop an understanding for the sport of rugby union. It explains the core values of the sport, the rules by which it is governed and the various positions that that can be played. The website also offers the options to sign up for a newsletter that will update the user on new articles, social media posts and more. View the live site [here](https://jacklamb99.github.io/rugby-rundown/)

![Mockup](docs/readme_images/mockup.PNG)

## Table of Contents

* [Features](#features)
    * [Site Wide](#site-wide)
    * [Landing Page](#landing-page)
    * [Rules Page](#rules-page)
    * [Positions Page](#positions-page)
    * [Newsletter Page](#newsletter-page)
    * [Existing Features](#existing-features)
    * [Features Left to Implement](#features-left-to-implement)
* [Design](#design)
    * [Wireframes](#wireframes)
    * [Imagery](#imagery)
    * [Typography](#typography)
    * [Colour Palette](#colour-palette)
* [Technologies](#technologies)
* [Testing](#testing)
    * [Responsiveness](#responsiveness)
    * [Accessibility](#accessibility)
    * [Lighthouse Testing](#lighthouse-testing)
    * [Functional Testing](#functional-testing)
    * [Validator Testing](#validator-testing)
    * [Unfixed Bugs](#unfixed-bugs)
* [Deployment](#deployment)
    * [Version Control](#version-control)
    * [Deployment to GitHub Pages](#deployment-to-github-pages)
    * [Clone the Repository Code Locally](#clone-the-repository-code-locally)
* [Credits](#credits)
    * [Guidance](#guidance)
    * [Content](#content)
    * [Media](#media)
    * [Code Used](#code-used)
    * [Acknowledgement](#acknowledgement)

## Features

### Site Wide

#### Navigation Menu

* The navigation menu contains the Rugby Rundown logo, which takes users to the 'Home' page when clicked, as well as individual links to the 'Home', 'Positions' and 'Rules' pages.
* All of these options are accessible to visually impaired users who may be using a screen reader, by the use of aria-labels.
* It uses a drop-down tab option for convenient space-saving on smaller screens (less than 768px wide), making it responsive on all devices.
* This allows users to easily navigate between pages, with the current page clearly highlighted.

![Navigation Menu](docs/readme_images/navigation_menu.PNG)

![Navigation Menu - Mobile](docs/readme_images/navigation_menu_mobile.PNG)

#### Footer

* The footer contains links to social media websites that will open in a new tab and a form to sign up for a newsletter.
* The newsletter form has a required text input for user's 'First Name', an optional text input for the user's 'Last Name' and a required 'Email' input. A reset button labelled 'Clear' can be used to reset the form and a submit button labelled 'Sign up' will submit the form and take the user to the 'newsletter.html' page if done successfully.
* All interactive features within the footer are accessible to visually impaired users, by the use of aria-labels.

![Footer](docs/readme_images/footer.PNG)

#### Favicon

* A favicon with the icon of a rugby ball is used site wide and is displayed alongside the 'Rugby Rundown' name in the tab header.
* This allows users to easily identify the website if multiple tabs are open.

![Favicon](docs/readme_images/favicon.PNG)

#### 404 Page

* A '404.html' page has been implemented and will display if the user navigates to a broken link.
* The page contains a simple message to explain the error and a button with a link back to the 'Home' page.
* This allows the users to easily navigate back to the main website if they try to access a broken link or missing page.

![404 Page](docs/readme_images/404_page.PNG)

### Landing Page

#### Gallery

* The image gallery contains a variety of images that capture different elements of the rugby union sport.
* A single image is visible on smaller screens (less than 1000px) and two images are visible at a time on larger screens, so the gallery is responsive on all devices. The images are in a carousel format and change on a timer.
* The purpose of the gallery is to clearly indicate the subject of the website to the user.

![Landing Page Gallery](docs/readme_images/landing_page_gallery.PNG)

#### Reasons To Love The Sport

* This section describes the reasons we, 'Rugby Rundown', love the sport and it highlights four core values. These reasons are short and direct in order to gain the users initial interest in the website.
* The boxes stack on smaller screens (less than 1000px) and form a grid on larger screens, making it responsive on all devices.

![Reasons](docs/readme_images/reasons.PNG)

#### Club Finder

* This section has a logo for each of the British and Irish national rugby teams and links to their rugby club finder tools, which open in a new tab.
* These links are accessible for visually impaired users by the use of aria-labels.

![Club Finder](docs/readme_images/club_finder_links.PNG)

### Rules Page

#### Rules Hero Image

* The hero image for the 'Rules' page features referees to highlight the importance of the laws in the sport, therefore the importance of the following content.
* An image with a more centralised focus is used for smaller screens (under 1000px) and a wider image is used for larger screens to make this section responsive and visually appealing on all devices.

![Rules Hero Image](docs/readme_images/rules_hero_image.PNG)

![Rules Hero Image - Mobile](docs/readme_images/rules_hero_image_mobile.PNG)

#### Rules Accordion

* An accordion structure is used to list the major rules of the sport. The user has full control over the opening and closing of each rule through the use of checkbox inputs that toggle the display property of the content.
* The initial design for the accordion structure used radio buttons, but after feedback from multiple users, the general consensus was a desire for more control over each individual tab. I achieved this by replacing the radio buttons with checkboxes and altering the relevant CSS code to suit this change.
* A related image is incorporated into each rule to help the user visualise the content, these images are hidden on mobile devices (under 768px) for space-saving.

![Rules Accordion](docs/readme_images/rules_accordion.PNG)

#### Rules Video

* A video is included from the 'England Rugby' YouTube page that explains the basics of rugby union.
* The video includes controls and is responsive on all devices.

![Rules Video](docs/readme_images/rules_video.PNG)

### Positions Page

#### Positions Hero Image

* The page features a hero image that shows various players and their position numbers. An image with a more centralised focus is used for smaller screens (under 1000px) and a wider image is used for larger screens to make this section responsive and visually appealing on all devices.

![Positions Hero Image](docs/readme_images/positions_hero_image.PNG)

![Positions Hero Image - Mobile](docs/readme_images/positions_hero_image_mobile.PNG)

#### Forwards Accordion

* An accordion structure is used to list the 'Forwards' positions. The user has full control over the opening and closing of each position through the use of checkbox inputs that toggle the display property of the content.
* The initial design for the accordion structure used radio buttons, but after feedback from multiple users, the general consensus was a desire for more control over each individual tab. I achieved this by replacing the radio buttons with checkboxes and altering the relevant CSS code to suit this change.
* An image is incorporated into each content section to highlight each position's place on the pitch. Originally these images were hidden on screens under 768px for space-saving, however this was changed after user feedback to incorporate them on mobile devices.

![Forwards Accordion](docs/readme_images/forwards_accordion.PNG)

#### Backs Accordion

* The same accordion structure is used to list the 'Backs' positions and the user has the same control over the opening and closing of each position.
* The images highlighting each position's place on the pitch are continued.

![Backs Accordion](docs/readme_images/backs_accordion.PNG)

#### Positions Video

* A video is included from the 'Leicester Tigers' YouTube page that explains the player's positions in rugby union.
* The video includes controls and is responsive on all devices.

![Positions Video](docs/readme_images/positions_video.PNG)

### Newsletter Page

* Once the form within the footer is completed and submitted, users will be taken to the 'newsletter.html' page as confirmation of their sign up and to thank them.
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
* JavaScript could also be used within the 'Positions' content to allow users to interact with player icons to open and close the relevant tab.

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

* The 'Jockey One' font from Google Fonts was used for all header elements; bold and 'blocky' to create a more striking appearance.
* The 'Lexend' font from Google Fonts was used for all paragraph elements; clear and simple to make the information easy to read.

### Colour Palette

![Colour Palette](docs/readme_images/colour_palette.png)

## Technologies

The following technologies were used in the creation of the website:

HTML - The structure of the website was developed using HTML

CSS - The website was styled using custom CSS in an external file

[Gitpod](https://www.gitpod.io/) - The website was developed using the Gitpod cloud-based IDE

[GitHub](https://github.com/) - The source code is hosted on GitHub and deployed using Git Pages

Git - Used to commit and push code during the development of the website

[Balsamiq](https://balsamiq.com/wireframes/desktop/) - Wireframes were created using the Balsamiq desktop application

[Google Fonts](https://fonts.google.com/) - Used to find and import the 'Jockey One' and 'Lexend' fonts used throughout the website

[Favicon.io](https://favicon.io/) - Used to find and import the rugby ball favicon

[Font Awesome](https://fontawesome.com/) - Used to find and import all icons used throughout the website

[Free Convert](https://www.freeconvert.com/) - Used to convert the images used in the website to WEBP format

[Tinify](https://tinypng.com/) - Used to compress the images to reduce file sizes for improved performance

## Testing

### Responsiveness

All pages were tested using Google Chrome, Microsoft Edge, Opera and Mozilla Firefox browsers to ensure responsiveness on screen sizes from 320px and upwards as defined in [WCAG 2.1 Reflow](https://www.w3.org/WAI/WCAG21/Understanding/reflow.html) criteria for responsive design.

Steps to test:

1. Open selected browser and navigate to the 'Rugby Rundown' website
2. Open the developer tools to inspect
3. Set the width to responsive at 320px
4. Set the zoom to 50% to fit the larger screen sizes
5. Click and drag the width toggle at the side of the page to maximum width

Expected:

Website is responsive on all screen sizes and no horizontal scroll is present. No elements overlap and no images are stretched or oversized. 

Actual:

The website behaved as expected with the exception of the carousel gallery image size on Mozilla Firefox. Further details can be found in the [Unfixed Bugs](#Unfixed-Bugs) section.

The website was also opened on the following devices and no responsive issues were observed:

* Samsung Galaxy S20
* Apple iPhone 12
* Apple iPad Air
* Google Chromebook

### Accessibility

[Wave Accessibility](https://wave.webaim.org/) tool was used to ensure all pages met the needs for any screen readers or accessibility aids for visually impaired users. `aria-hidden="true"` labels were applied to icons and some elements used only for visual design purposes to remove unnecessary clutter for screen-readers.

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

The 'Lighthouse' extension on Google DevTools was used to test the overall functionality and performance of the website:

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
| Rugby Rundown Logo | [index.html](https://jacklamb99.github.io/rugby-rundown/index.html) |
| Home | [index.html](https://jacklamb99.github.io/rugby-rundown/index.html) |
| Rules | [rules.html](https://jacklamb99.github.io/rugby-rundown/rules.html) |
| Positions | [positions.html](https://jacklamb99.github.io/rugby-rundown/positions.html) |

#### Newsletter Form

The form within the footer to sign up for the newsletter was tested to ensure it functioned as expected when correct and incorrect data was input.

##### Test One – Correct Inputs

| Input | Requirement | Data |
| :---- | :---- | :---- |
| First Name | Required | John |
| Last Name | Optional | Smith |
| Email | Required | johnsmith@testing.com |

Expected:

The form submits with no errors and user is redirected to the 'newsletter.html' page.

Actual:

The website performed as expected, no errors occurred and the user was redirected to the 'newsletter.html' page.

##### Test Two – Missing First Name Field

| Input | Requirement | Data |
| :---- | :---- | :---- |
| First Name | Required |  |
| Last Name | Optional | Smith |
| Email | Required | johnsmith@testing.com |

Expected:

The form does not submit and an error message is displayed to tell the user that the 'First Name' field is required.

Actual:

The website performed as expected, an error message was displayed and the form did not submit.

##### Test Three – Missing Last Name Field

| Input | Requirement | Data |
| :---- | :---- | :---- |
| First Name | Required | John |
| Last Name | Optional |  |
| Email | Required | johnsmith@testing.com |

Expected:

The form submits with no errors and user is redirected to the 'newsletter.html' page.

Actual:

The website performed as expected, no errors occurred and the user was redirected to the 'newsletter.html' page.

##### Test Four – Missing Email Field

| Input | Requirement | Data |
| :---- | :---- | :---- |
| First Name | Required | John |
| Last Name | Optional | Smith |
| Email | Required |  |

Expected:

The form does not submit and an error message is displayed to tell the user that the 'Email' field is required.

Actual:

The website performed as expected, an error message was displayed and the form did not submit.

##### Test Five – Incorrect Email Format

| Input | Requirement | Data |
| :---- | :---- | :---- |
| First Name | Required | John |
| Last Name | Optional | Smith |
| Email | Required | johnsmithtesting.com |

Expected:

The form does not submit and an error message is displayed to tell the user to use a valid email format that includes an @ symbol.

Actual:

The website performed as expected, an error message was displayed and the form did not submit.

#### Footer Social Media Links

Testing was performed on the four social media icons within the footer to ensure that each link opened in a new tab and directed the user to the correct website.

Each link acted as expected, opening the correct site in a new tab.

#### Rugby Club Finder Links

Testing was performed on the four national rugby logos at the bottom of the 'Home' page to ensure that each link opened in a new tab and directed the user to the correct page within the website.

Each link acted as expected, opening the correct page on the website in a new tab.

#### Accordions

Testing was performed on the three accordion structures used on the 'Rules' and 'Positions' pages to ensure each individual tab could be opened and closed on command by clicked anywhere on the tab's header container.

All of the accordions acted as expected, allowing the user to have full control over of each tab and the display of its content.

#### Embedded Videos

The embedded YouTube videos at the bottom of the 'Rules' and 'Positions' pages were tested to ensure the user has full control over the pause/play, audio and other settings.

Both videos acted as expected, allowing the user to have full control over all playback controls and settings.

#### 404 Home Button

The 'Home' button on the '404.html' page was tested to ensure it redirected the user to the 'Home' page and that it had the styled hover effect with alternate colours. The button performed as expected.

### Validator Testing

#### HTML

No errors occurred when passing each page through the official [W3C Markup Validation Service](https://validator.w3.org/)

#### Home Page

![Home Page HTML Validator Results](docs/readme_images/home_validator.PNG)

#### Rules Page

![Rules Page HTML Validator Results](docs/readme_images/rules_validator.PNG)

#### Positions Page

![Positions Page HTML Validator Results](docs/readme_images/positions_validator.PNG)

#### Newsletter Page

![Newsletter Page HTML Validator Results](docs/readme_images/newsletter_validator.PNG)

#### 404 Page

![404 Page HTML Validator Results](docs/readme_images/404_validator.PNG)

#### CSS

No errors occurred when passing through the official [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)

![CSS Validator Results](docs/readme_images/css_validator.PNG)

### Unfixed Bugs

The website functions as expected on all browsers with the exception of the gallery carousel on the Mozilla Firefox browser. The image sizes do not display as expected and so the carousel does not function accodingly. I was unable to resolve this bug on time but will address in a future release.

## Deployment

### Version Control

The website was developed using the [Gitpod](https://www.gitpod.io/) cloud-based IDE and pushed to the remote repository ['rugby-rundown'](https://github.com/JackLamb99/rugby-rundown) on [GitHub](https://github.com/).

The following git commands were used throughout its creation to push code to the remote repository:

* `git add file` or `git add .` - This command was used to add the file(s) to the staging area before they were committed.
* `git commit –m “commit message”` - This command was used to commit changes to the local repository queue.
* `git push` - This command was used to push all committed code to the remote repository on GitHub.

### Deployment to GitHub Pages

The site was deployed to GitHub Pages, the steps to deploy are as follows:

1. In the GitHub repository, navigate to the 'Settings' tab
2. Select the 'Pages' option from the menu to the left
3. Under 'Branch', in the 'Build and deployment' section, select the 'main' dropdown option
4. Click 'Save'
5. Refresh the page and live link will be displayed at the top of the page when published successfully

The live link can be found here - https://jacklamb99.github.io/rugby-rundown/

### Clone the Repository Code Locally

Open the selected GitHub repository you want to clone locally:

1. Click on the 'Code' drop-down button
2. Click on the 'HTTPS' option
3. Copy the repository link
4. Open your IDE
5. Type `git clone copied-url` into the IDE terminal (Git must be installed for this step)

## Credits

### Guidance

* [ChatGPT](https://chat.openai.com/) – Used to understand and assist in developing the carousel structure for the landing page gallery, this was then adapted myself for the larger device media queries.
* [Accordion Tutorial Video](https://youtu.be/oCx4gtYe410?si=MyWuYZVreYRLSh1s) – Used to assist in developing the accordion structures used on the 'Rules' and 'Positions' pages. The code was adapted and styled as required to follow the site design and to use checkbox inputs, rather than radio buttons, for improved user control.

### Content

* [World Rugby Website](https://www.world.rugby/the-game/beginners-guide/game) - Used to guide the content for the 'Rules' page, I adapted the content myself to further explain each rule.
* [Rugby Pass Website](https://www.rugbypass.com/) and [Rugby Fix Website](https://rugbyfix.com/rugby-positions-explained/) - Used to guide the content for the 'Positions' page, I adapted the content myself to further explain each position and their role.

### Media

#### Home Page

* [carousel_image_1.webp](https://unsplash.com/photos/men-playing-soccers-8381YR5nfiE)
* [carousel_image_2.webp](https://unsplash.com/photos/group-of-people-playing-soccer-W4Jqc2Uxj3Y)
* [carousel_image_3.webp](https://unsplash.com/photos/womens-rugby-uniforms-uWU5QHeTNvc)
* [carousel_image_4.webp](https://unsplash.com/photos/team-playing-rugby-sport-XAlKHW9ierw)
* [carousel_image_5.webp](https://unsplash.com/photos/children-playing-football-Ag36XuTuARM)
* [england_rugby_logo.webp](https://freebiesupply.com/logos/england-rugby-logo/)
* [ireland_rugby_logo.webp](https://en.wikipedia.org/wiki/Irish_Rugby_Football_Union#/media/File:Irish_Rugby_Football_Union_logo.svg)
* [scotland_rugby_logo.webp](https://en.wikipedia.org/wiki/Scotland_national_rugby_union_team#/media/File:Scotlandlogo.png)
* [wales_rugby_logo.webp](https://en.wikipedia.org/wiki/Logo_of_the_Welsh_Rugby_Union#/media/File:Welsh_Rugby_Union_logo.svg)

#### Rules Page

* [rugby_ref.webp](https://d2cx26qpfwuhvu.cloudfront.net/nsl/wp-content/uploads/2022/10/31123836/Nika-Amashukeli-999x562.jpg)
* [rugby_ref_wide.webp](https://www.telegraph.co.uk/content/dam/rugby-union/2023/05/24/TELEMMGLPICT000336685234_16849495745620_trans_NvBQzQNjv4Bq_4lZL6XGyKd1IzVfh-3zqkklW67ZKazFSUg_RL8azUI.jpeg?imwidth=1280)
* [rules_open_play.webp](https://sport360.com/wp-content/uploads/2018/03/GettyImages-926595950-1024x683.jpg)
* [rules_scoring.webp](https://static.independent.co.uk/2023/03/04/10/GettyImages-1469522006.jpg?quality=75&width=990&crop=3%3A2%2Csmart&auto=webp)
* [rules_tackle.webp](https://www.therugbypaper.co.uk/wp-content/uploads/epub_importer/data/TRP/trp_20210328_213507/ops/images/img_26-1.jpg)
* [rules_ruck.webp](https://upload.wikimedia.org/wikipedia/commons/b/b8/USO-Gloucester_Rugby_-_20141025_-_Ruck_6.jpg)
* [rules_offside.webp](https://resources.world.rugby/worldrugby/photo/2020/11/04/2a4f6b35-c009-4e65-8cb1-0cfea2c5212a/ruck-offside.jpg)
* [rules_scrum.webp](https://keyassets.timeincuk.net/inspirewp/live/wp-content/uploads/sites/7/2022/02/GettyImages-77427964-1-630x420.jpg)
* [rules_lineout.webp](https://upload.wikimedia.org/wikipedia/commons/2/2b/ST_vs_LOU_-_21.jpg)
* [rugby_pitch.webp](https://images.ctfassets.net/usvb7o98ifrz/7mezNyl1CMPCKTOSqc1MYd/59ef81e2989620c5b5e0ca0c9c017503/World_Rugby_Pitch_Dimensions_Graphic.jpeg)
* [Rugby for beginners: a guide to the rules of rugby union](https://youtu.be/FOJejnPI0p0?si=O0f8bvVWHzxmdcPk)

#### Positions Page

* [rugby_positions.webp](https://carltonsportstravel.com/wp-content/uploads/2023/07/shutterstock_2124737-1-scaled.jpg)
* [rugby_positions_wide.webp](https://www.canterburyrugby.co.nz/news/canterburys-npc-squad-announced-for-2022-season)
* All images within the 'The Forward Pack' and 'The Back Line' accordions use [this image](https://rugby.web.unc.edu/wp-content/uploads/sites/12201/2016/05/rugbypositions-1-768x614.png) which was then edited using Adobe Photoshop to remove the text, change player shirt colours and highlight each position as needed
* [Rugby Explained: Rugby Players and Positions](https://youtu.be/5bTdxWhgQdM?si=tqsYB5a7sLzRY7vt)

#### Newsletter Page

* [newsletter_image.webp](https://classroomclipart.com/image/vector-clipart/email-icons-on-a-laptop-computer-screen-59670.htm)

### Code Used

* `<iframe>` code for videos on the 'Rules' and 'Positions' pages copied from YouTube's 'Embed Video' tool.

### Acknowledgement

[Gareth McGirr](https://github.com/Gareth-McGirr) - My Code Institute mentor