# **Hello Kitty Island Adventure: Online Guide**

![Responsive Design](assets/Readme-documentation/responsive-design.png)

## Table of Contents
- [Overview](#overview)
- [User Experience](#user-experience)
- [User Stories](#user-stories)
- [Typography](#typography)
- [Imagery](#imagery)
- [Colour Scheme](#colour-scheme)
- [Wireframes](#wireframes)
- [Features](#features)
- [General Features](#general-features)
- [Tools and Technologies Used](#tools-and-technologies-used)
- [Features Left to Implement](#features-left-to-implement)
- [Testing](#testing)
- [Manual Testing](#manual-testing)
- [Browser Testing](#browser-testing)
- [Lighthouse Testing](#lighthouse-test)
- [Validator Testing](#validator-testing)
- [Fixed Bugs](#fixed-bugs)
- [Unfixed Bugs](#unfixed-bugs)
- [Accessibility](#accessibility)
- [Deployment](#deployment)
- [Credits](#credits)

# Overview 

Hello Kitty Island Adventure: Online Guide is a site that seeks to provide information about the game "Hello Kitty Island Adventure". The site will be targeted towards new and existing players looking to learn about the game and how to progress. The game is playable across 3 different platforms so will be relevant to all players regardless of where they choose to play as it will be content-focussed. It will be useful for new players looking to see if the game is something they'd be interested in as well as for existing players looking to find out more.

Exising websites featuring content for Hello Kitty Island Adventure are visually plain, so the purpose of this website is to be just as informative as these sites but provide an aesthetic that is in-line with the style of the game. 

[View the site here](https://alicejardine95.github.io/milestone-project-1/index.html)

# User Experience
The website is created for fans of Hello Kitty wishing to find out more about the game “Hello Kitty Island Adventure”. It is appropriate for both new and existing players.

The site provides imagery and information about gameplay, with links to relevant platforms to access the game. There is a page about characters for users to find out how to progress in the game as well as a form to sign-up to a newsletter.

### User Stories
#### User Goals 
- To be able to view the site on different devices and screen sizes
- To access relevant information and be directed to relevant sites, such as where to find the game and where to find social media related to the game

#### Potential User Goals 
- To access an informative website about a game I want to learn more about
- To see images of gameplay to establish if it is something I am interested in
- To access further information from the website such as official pages

#### Returning User Goals
- Factually correct information
- Access information that isn’t immediately available within the game
- Check the events section for updates
# Typography
[Google fonts](https://fonts.google.com/) are used to  create the following: 

- Lato - Which is used for the website Heading
<details>
<summary>View screenshot of font in use here</summary>

![Image of Lato font](assets/readme-documentation/Lato-font.png)
</details>

#### Icons
- [Font Awesome](https://fontawesome.com/) is used to create the navbar dropdown and social media links in the footer, as well as the flower icon shown in a browser tab.
- [Free Icons](https://freeicons.io/) is used to create the icons in the events section


# Imagery
All images are referenced in the “credits”. Images featuring gameplay have been specifically selected to accurately depict the game

# Colour scheme
Colours predominantly seen within the game have been used throughout the site to remain congruent with its style, as well as providing users with expected familiarity if they already play the game. Contrast has been considered throughout to ensure text remains readable

# Wireframes
[Balsamiq](https://balsamiq.com) has been used to create a visual plan for the website layout. A wireframe has been created for mobile, desktop and tablet to ensure responsive design is considered throughout

#### Index Page
![Index Page Wireframe](assets/Readme-documentation/MP1.png)

#### Characters Page
![Characters page wireframe](assets/Readme-documentation/Characters%20.png)

#### Sign up Page
![Sign up Wireframe](assets/Readme-documentation/Form%20Wireframe.png)

#### Thank you/Subscribe Page
![thank you/subscribe page](assets/Readme-documentation/subscribe_sign-up.png)

# Features
The website will feature a landing page with a responsive navbar with uniform styling across all pages. The navbar remains at the top of the page and out of view once scrolled to maxemise screen space. It will become a dropdown menu on mobile devices for a clearer view on a smaller screen. A footer with icons linked to corresponding social media pages will also remain on all pages, and will only be visable once at the bottom of the page. The navbar will have a logo linked to the homepage, a characters page and a sign-up page for users to fill in a form to sign-up to a newsletter. The navbar functionality means there is no need for a back-button making it easy to navigate to each section of the website.

## General Features 
### Index Page
The index page is split into sections to provide clear information in a concise way, enabling users to browse before accessing further pages.

##### Navigation
A responsive navigation bar is displayed at the top of each page. This was initially fixed however took up too much real estate on the page, so has been changed to remain at the top. Its content remains the same across all pages for easy functionality. The website header is linked to the homepage to eliminate the need for a back button and ensure the user experience is smooth. The current page is underlined in the navigation bar so that users can be clear about where they currently are within the website. When in mobile view, the navbar becomes a burger icon, and the menu is accessible once clicked. This provides a clearer view of the page on a smaller screen. The navbar was initially blue but has been changed to pink to suit the colour scheme

![image of desktop navbar](assets/Readme-documentation/desktop-navbar.png)
![image of mobile navbar](assets/Readme-documentation/mobile-navbar.png)

For easier navivation on mobile especially, a "return to top" button has been added to the characters page due to the scrolling required with the information on the screen. Having a fixed navbar took up too much real estate on smaller screens so this prevents users having to scroll all the way back up once at the bottom

![Back to top button](assets/Readme-documentation/back-to-top.png)

##### Footer 
The footer contains icons related to corresponding social media pages. Icons were chosen over text as they are immediately recognisable to users of each platform.  Also, it means that the style remains as effective in different screens. They are equally spaced using flexbox to ensure the design is responsive in mobile, desktop and tablet view. The footer remains fixed to the bottom of the page and is only viewable when the page has been scrolled all the way.

![Image of footer](assets/Readme-documentation/footer.png)

#### Hero Image
The hero image displays characters from the game in a bright image. It outlines the aesthetic of the game to give users an idea of its style. Overlay text towards is placed centrally with links to platforms to access the game so that users know immediately where to find it, without it interrupting the effect of the image. The linked text changes to white once hovered over so that it is clear that these are links.

##### Large screens
![Image of hero image](assets/Readme-documentation/hero-improved.png)

###### Mobile 
![Image of hero image on mobile screen](assets/Readme-documentation/hero-mobile.png)

Initially, a different hero image was used however the colours within it did not suit the colour scheme of the website. This can be seen below
<details>
<summary>Previous hero image</summary>

![previous hero image](assets/Readme-documentation/landing-image.png)
</details>

### About section
This section provides a brief overview of what players can expect from the game. Mentioned characters will be linked to the characters page so that new users can find out more if they are new to the game. The section has an image carousel centrally to break-up text.

##### Large screens 
![Image of about section](assets/Readme-documentation/about-improved.png)

##### Mobile
![Image of about section on mobile screen](assets/Readme-documentation/about-mobile.png)

The "about" section initially had a block colour background but was difficult to read and didn't suit the page. This can be seen below
<details>
<summary>Previous "about" section</summary>

![Image of previous about section](assets/Readme-documentation/about-section.png)
</details>

##### Image Carousel 
An image carousel has been created using Bootstrap to ensure it is responsive. It shows images from gameplay related to the text surrounding it. This has been used rather than a static image to enable users to view multiple pictures without too much screen space being taken up. It is set to autoplay and moves every few seconds, but also has arrows to go forwards or backwards if users wish to see images sooner.

![carousel image](assets/Readme-documentation/image-carousel.png)

##### Events section
The events section uses a responsive grid layout to show users about upcoming events in the game. Icons have been used to suit the aesthetic of each event. A background image has also been used to give insight into visuals from gameplay. On larger screens, the events line up horiozontally. This adjusts to being vertically stacked on mobile to ensure information is readable

##### Large screens
![Image of events section](assets/Readme-documentation/events-section.png)

##### Mobile Screens
![Image of events section on mobile screens](assets/Readme-documentation/events-mobile.png)

## Characters Page
This page uses a responsive grid to display game characters with an image and their name. The character name is a drop-down button to prevent the page being too text-heavy. This is made clear through an arrow to show when the information is open and closed, as well as a button-like design being given to the text. The colours are the same as the "about" section on the index page for a more uniform design. On larger screems, characters are displayed in rows of 4. This changes to 3 on tablets, and to 1 on mobile to ensure content is clear and not crowded. Note: the screeshot displayed below is with the browser at 67% in order to display the full page for reference

##### Large Screens
![Image of characters page](assets/Readme-documentation/characters-page.png)

##### Tablet Screens
![Image of characters page on tablet](assets/Readme-documentation/characters-tablet.png)

##### Mobile Screens
![Image of characters page on mobile screens](assets/Readme-documentation/characters-mobile.png)

## Sign-up Page
This page provides users with a form to fill out to subscribe to a newsletter. Users are given the choice of weekly or monthly updates. The form requires all fields to be filled out before it can be deemed complete

##### Large Screens
![Image of sign-up page on large screen](assets/Readme-documentation/form.png)

##### Mobile Screens
![Image of form on mobile screens](assets/Readme-documentation/form-mobile.png)

## Thank you Page
This page displays once the user has filled in all areas of the form. It remains simple as it is not a page that will have much time spent on it, but serves as a confirmation that the form has been sent

##### Large Screens
![Image of thank-you page on large screen](assets/Readme-documentation/thank-you-page.png)

##### Mobile Screens
![Image of thank-you page on mobile](assets/Readme-documentation/Thank-you-mobile.png)


# Tools and Technologies Used
- [Chrome Dev Tools](https://developer.chrome.com/docs/devtools) has been used for inspecting elements and debugging code. When adjusting media queries, utilising Dev Tools meant that potential bugs could be addressed 
- [Balsamiq](https://balsamiq.com) has been used to create mock-up designs of each page
- [Bootstrap](https://getbootstrap.com) has been used to create a responsive image carousel 
- The following browsers were used for testing: [Google Chrome](https://www.google.com/chrome/),[Microsoft Edge](https://www.microsoft.com/edge),  [Mozilla Firefox](https://www.mozilla.org/firefox/) as well as Samsung default mobile browser
- [CSS Gradient.io](https://cssgradient.io/)to create CSS gradient backgrounds
- [Visual Studio Code](https://code.visualstudio.com/) has been used for writing code
- [GitHub](https://github.com) has been used for storing and deploying code

# Features Left to Implement
The following ideas would enhance the user experience of the site, building on the content which exists currently

#### Frequently asked questions 
- This would be beneficial for both new and existing users as a future implementation

#### Game reviews
- An opportunity for players to leave reviews and read existing reviews would enable users to gain further insight into the experience of gameplay

#### Videos
- Imported videos of gameplay would provide further visual insight into the game 

#### Game map
- A page with information about areas in the game would expand on existing information

#### Dark mode settings
- The current colours do not look good in dark mode so alternatives could be looked into to ensure the site is effective for people who struggle with bright colours


# Testing 
### Manual Testing

| Feature       | Test Case            | Outcome                        |
| ------------- |:--------------------:| :----------------------------:  |
| Logo          |Click on the logo     | User is brought to home page 
| Navbar links  |Click on nav links    | User taken to chosen page      | 
| Footer links  |Click on footer icons | User taken to corresponding site|
| Image carousel|Click arrow           | Next image is displayed         |
|Character links|Click name on index   |Taken to characters page         |
|Responsive pages| Devtools            | Site repsonds accordingly       |
|Form input     |Filling in form       |Taken to intended page           |
|Button/link hovers| Hovered over      | Colours change as intended      |

- The github pages site has been accessed on 4 different mobile devices (samsung s21, Samsung fold, IphoneX and Iphone 12). All devices responded as intended

- Tested on an ipad mini 4 and functions as intended

- Tested on a laptop screen as well as large monitor and functions as intended

### Browsers
#### Google chrome 
- Displays the website as intended, site is fully responsive and appearence is as intended

####  Microsoft Edge 
- Displays the website as intended, site is fully responsive and appearence is as intended

### Firefox
- Displays the website as intended, site is fully responsive and appearence is as intended

#### Samsung mobile browser 
- Responds as intended however dark mode alters the colours significantly, which is something that could be built upon as a futue implementation
<details>
<summary>Click here to view the samsung browser display</summary> 

![Samsung mobile browser](assets/Readme-documentation/samsung-browser.jpg)
</details>

### Lighthouse Test
[Lighthouse](https://chromewebstore.google.com/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk) is a Chrome extension which enables the performance of each page to be analysed. The results for each page can be seen below:

#### Mobile
<details>
<summary>Index Page</summary

![index report](assets/Readme-documentation/lighthouse-mobile1.png)
</details>
<details>
<summary>Characters Page</summary>

![characters summary](assets/Readme-documentation/lighthouse-mobile2.png)
</details>
<details>
<summary>Sign-up Page</summary>

![sign-up summary](assets/Readme-documentation/lighthouse-mobile3.png)
</details>
<details>
<summary>Thank you Page</summary>

![thank-you page](assets/Readme-documentation/lighthouse-mobile4.png)
</details>


##### Desktop
<details>
<summary>Index Page</summary>

![Index page](assets/Readme-documentation/lighthouse-desktop1.png)
</details>
<details>
<summary>Characters Page</summary>

![Characters Page](assets/Readme-documentation/lighthouse-desktop2.png)
</details>
<details>
<summary>Sign-up Page</summary>

![Sign-up Page](assets/Readme-documentation/lighthouse-desktop3.png)
</details>
<details>
<summary>Thank-you Page</summary>

![Thank-you Page](assets/Readme-documentation/lighthouse-desktop4.png)
</details>
<br>
 It appears to be image type that reduces the overall performance on the characters page on mobile and the thank-you page on desktop. Ideally these files would be WebP, however time constraints mean that they have had to remain in jpeg in this instance.

### Validator Testing 
[W3C CSS Validator](https://jigsaw.w3.org/css-validator) has been used to validate CSS and no errors were found

[W3C Markup Validation Service](https://validator.w3.org/#validate_by_input) has been used to validate HTML files and all errors/warnings have been rectified. Warnings included:
- Unneccessary closing div tags added in error
- Missed closing tags in header
- Missed alt attributes on images

## Fixed Bugs
#### Navbar Toggle
- The navbar became stuck to the mobile styling whilst on desktop. Altered the styling to flexbox methods to ensure responsive design which fixed the problem.

<details>
<summary>View solution here</summary> 

![nav bug fix](assets/Readme-documentation/bugfixing.png)
</details>     

#### Screen size and layout
When styling the "subscribe" page which users are taken to once filling in the form, it was difficult to create suitable padding that looked effective across all devices. I tested this page on my mobile throughout,as well as Google Chrome Dev Tools, to establish which screen sizes needed a different approach. I created an additional media query with a minimum width of 380px to account for varying phone screen sizes, particularly as content is commonly viewed on mobile devices 

#### Navbar Layout
- When styling other areas of the page, noticed that the navbar dropdown had become horizontal instead of vertical. This was corrected as corresponding code had been accidentally altered, so reverted to what it was previously
<details>
<summary>See navbar before corrections</summary>

![navbar closed](assets/Readme-documentation/navbarclosed%20(1).png)
![navbaropen](assets/Readme-documentation/navbaropen.png)
</details>

#### Sizing
- Padding had to be altered in character section several times as the section took up more space than ancicipated. Utilising media queries resolved this

## Unfixed Bugs
- The bootstrap carousel used in the index page is not completely uniform so alters the text around it slightly when moving from each image. Images have been resized as much as possible to prevent this from disrupting the page however it still remains a slight issue

- When the character name is toggled in the characters page, the surrounding boxes expand with it. A different styling approach was trialled including "cols/rows" but this had similar issues. Bootstrap cards were also trialled but did not suit the level of text input. It is not a visable issue for mobile and does not overly disrupt the flow of the page for larger screens, though.
<details>
<summary>See this below</summary>

![character boxes](assets/Readme-documentation/characters-boxes.png)
</details>

# Accessibility
- Making the website user-friendly has been at the core of design and construction of the site. This has been achieved using semantic html and alt attributes to describe images

- The Chrome extension [Wave](https://chromewebstore.google.com/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh) has been used to provide visual feedback on overall accessiblity 

- The Chrome extension [Web Disability Simulator](https://chromewebstore.google.com/detail/web-disability-simulator/olioanlbgbpmdlgjnnampnnlohigkjla) has been used during building to consider the needs of individuals with conditions which may impact how the website is perceived

# Deployment

 - The site has been deployed using Github pages as fpllows:
  In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

# Credits 

#### Icons
- [Favicons](https://favicon.io/emoji-favicons/cherry-blossom/) 
- [Free Icons](https://freeicons.io/)

#### Images

- [Am I responsive](https://ui.dev/amiresponsive?url=https://alicejardine95.github.io/milestone-project-1/index.html) for responsive mock-up
- https://www.thegamer.com/hello-kitty-island-adventure-worth-it/hello-kitty-island-adventure-official-picture-perfect-under-the-sea-trailer
- https://www.thegamer.com/hello-kitty-island-adventure-how-to-unlock-use-camera/
- https://www.ign.com/wikis/hello-kitty-island-adventure/Things_to_Do_First_in_Hello_Kitty_Island_Adventure
- https://www.thegamer.com/hello-kitty-island-adventure-best-visitor-cabin-decorating-ideas/
- https://www.wog.ch/fr/index.cfm/details/product/213968-Hello-Kitty-Island-Adventure-Deluxe-Edition
- https://www.ign.com/articles/hello-kitty-island-adventure-is-coming-to-switch-and-pc-in-2025-and-cozy-game-fans-rejoice
- http://cgmagonline.com/news/hello-kitty-island-adventure-new-platform/
- https://www.smythstoys.com/uk/en-gb/gaming-and-tech/pre-order-games/nintendo-switch-pre-order-games/hello-kitty-island-adventure-deluxe-edition-nintendo-switch/p/247065

#### Additional Resources
- [Code Institute Readme Template](https://github.com/code-institute-solutions/readme-template) for guidance on Readme content
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/markdown-cheatsheet) for markdown reference
- [CSS Tricks](https://css-tricks.com/guides/) for further learning around CSS
- [CSS Gradient.io](https://cssgradient.io/) for creating gradient backgrounds in CSS
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS) for further learning around CSS
- [Chat GPT](https://openai.com/index/chatgpt/) for troubleshooting and exploring ideas
- [Image Resizer](https://imageresizer.com/bulk-resize) to alter image sizing
- [validation](https://validator.w3.org/) for debugging code 
- [Stack Overflow](https://stackoverflow.com/questions) for troubleshooting and exploring options for layout
-[Wave]https://chromewebstore.google.com/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh for understanding accessibility requirments within the site
- [Web Disability Simulator](https://chromewebstore.google.com/detail/web-disability-simulator/olioanlbgbpmdlgjnnampnnlohigkjla) as mentioned in "accessiblity"




