# **Hello Kitty Online Adventure Guide**

![Responsive Design](assets/Readme-documentation/responsive-design.png)

Hello Kitty Island Adventure Guide is a site that seeks to provide information about the game "Hello Kitty Island Adventure". The site will be targeted towards new and existing players looking to learn about the game and how to progress. The game is playable across 3 different platforms so will be relevant to all players regardless of where they choose to play as it will content-focussed. It will be useful for new players looking to see if the game is something they'd be interested in as well as for existing players looking to find out more.

[View the site here](https://alicejardine95.github.io/milestone-project-1/index.html)

## 1. User Experience
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
### Typography
[Google fonts](https://fonts.google.com/) are used to  create the following: 

Lato - Which is used for the website Heading
![Image of Lato font](assets/readme-documentation/Lato-font.png)
- [Font Awesome](https://fontawesome.com/) is used to create the navbar dropdown and social media links in the footer, as well as the flower icon shown in a browser tab.
- [Free Icons](https://freeicons.io/) is used to create the icons in the events section


### Imagery
All images are referenced in the “credits”. Images featuring gameplay have been specifically selected to accurately depict the game

### Wireframes
Balsamiq has been used to create a visual plan for the website layout. A wireframe has been created for mobile, desktop and tablet to ensure responsive design is considered throughout

#### Index Page
![Index Page Wireframe](assets/Readme-documentation/MP1.png)

#### Characters Page
![Characters page wireframe](assets/Readme-documentation/Characters%20.png)

## Features
The website will feature a landing page with a responsive navbar which will remain across all pages regardless of scrolling. It will become a dropdown menu on mobile devices. A footer with icons linked to corresponding social media pages and game platforms will also remain on all pages, but will only be visable once at the bottom of the page. The navbar will have a logo linked to the homepage, a characters page and a sign-up page for users to fill in a form to sign-up to a newsletter. The navbar functionality means there is no need for a back-button making it easy to navigate to each section of the website.

## General Features 
### Index Page
The index page is split into sections to provide clear information in a concise way, enabling users to browse before accessing further pages.

##### Navigation
A responsive navigation bar is displayed at the top of each page. This was initially fixed however took up too much real estate on the page, so has been changed to remain at the top .Its content remains the same across all pages for easy functionality. The website header is linked to the homepage to eliminate the need for a back button and ensure the user experience is smooth. The current page is highlighted in the navigation bar so that users can be clear about where they currently are within the website. When in mobile view, the navbar becomes a burger icon, and the menu is accessible once clicked. This provides a clearer view of the page on a smaller screen. The navbar was initially blue but has been changed to pink to suit the colour scheme

![image of desktop navbar](assets/readme-documentation/desktop-navbar.png)
![image of mobile navbar](assets/Readme-documentation/mobile-navbar.png)

##### Footer 
The footer contains icons related to corresponding social media pages. Icons were chosen over text as they are immediately recognisable to users of each platform.  Also, it means that the style remains as effective in different screens. They are equally spaced using flexbox to ensure the design is responsive in mobile, desktop and tablet view. The footer remains fixed to the bottom of the page and is only viewable when the page has been scrolled all the way.

![Image of footer](assets/Readme-documentation/footer.png)

#### Hero Image
The hero image displays characters from the game in a bright image. It outlines the aesthetic of the game to give users an idea of its style. Overlay text towards the bottom of the image is placed centrally with links to platforms to access the game so that users know immediately where to find it, without it interrupting the effect of the image.

![Image of hero image](assets/Readme-documentation/landing-image.png)

### About section
This section provides a brief overview of what players can expect from the game. Mentioned characters will be linked to the characters page so that new users can find out more if they are new to the game. The section has an image carousel centrally to break-up text, which is fully responsive and adjusts to mobile/desktop screens.

![Image of about section](assets/Readme-documentation/about-section.png)

##### Image Carousel 
An image carousel has been created using Bootstrap to ensure it is responsive. It shows images from gameplay related to the text surrounding it. This has been used rather than a static image to enable users to view multiple pictures without too much screen space being taken up. It is set to autoplay and moves every few seconds, but also has arrows to go forwards or backwards if users wish to see images sooner.

![carousel image](assets/Readme-documentation/image-carousel.png)

##### Events section
The events section uses a responsive grid layout to show users about upcoming events in the game. Icons have been used to suit the aesthetic of each event. A background image has also been used to give insight into visuals from gameplay. 

![Image of events section](assets/Readme-documentation/events.png)

#### Characters Page
This page uses a responsive grid to display game characters with an image and their name. The character name is a drop-down button which is made clear through an arrow to show when the information is open and closed, as well as a button-like design being given to the text

![Image of characters page](assets/Readme-documentation/characters-page.png)




### Features Left to Implement


### Testing 
## Manual Testing

| Feature       | Test Case            | Outcome                        |
| ------------- |:--------------------:| :----------------------------:  |
| Logo          |Click on the logo     | User is brought to home page 
| Navbar links  |Click on nav links    | User taken to chosen page      | 
| Footer links  |Click on footer icons | User taken to corresponding site|
| Image carousel|Click arrow           | Next image is displayed         |
|Character links|Click name on index   |Taken to characters page         |
|Responsive pages| Devtools            | Site repsonds accordingly       |
- Navbar links all work as intended, directing the user to the intended page

- The github pages site has been accessed on 4 different mobile devices (samsung s21, Samsung fold, IphoneX and Iphone 12)

- Tested on an ipad mini 4 and functions as intended

- Tested on a laptop screen as well as large monitor and functions as intended

## Browsers
- Google chrome displays the website as intended, site is fully responsive and appearence is as intended

- Microsoft Edge displays the website as intended, site is fully responsive and appearence is as intended

- Samsung mobile browser alters the colour scheme however layout is unaffected 

![Samsung mobile browser](assets/Readme-documentation/samsung-browser.jpg)



### Validator Testing 


## Fixed Bugs
- The navbar became stuck to the mobile styling whilst on desktop. Altered the styling to flexbox methods to ensure responsive design which fixed the problem.
![nav bug fix](assets/Readme-documentation/bugfixing.png)

- When styling other areas of the page, noticed that the navbar dropdown had become horizontal instead of vertical
![navbar closed](assets/Readme-documentation/navbarclosed%20(1).png)
![navbaropen](assets/Readme-documentation/readme-documentation/navbaropen.png)

- Padding had to be altered in character section several times as the section took up more space than ancicipated

### Unfixed Bugs
- The bootstrap carousel used in index page is not completely uniform so alters the text around it slightly when moving from each image. Images have been resized as much as possible to prevent this from disrupting the page however it still remains a slight issue

- When the character name is toggled, the surrounding boxes expand with it. A different styling approach was trialled including "cols/rows" but this had similar issues. Bootstrap cards were also trialled but did not suit the level of text input. It is not a visable issue for mobile and does not overly disrupt the flow of the page for larger screens, though.

![character boxes](assets/Readme-documentation/character-boxes.png)

## Deployment

 - The site has been deployed using Github pages as fpllows:
  In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.


## Credits 
- [Favicons](https://favicon.io/emoji-favicons/cherry-blossom/) 
- [Free Icons](https://freeicons.io/)

## Images

- https://www.thegamer.com/hello-kitty-island-adventure-worth-it/hello-kitty-island-adventure-official-picture-perfect-under-the-sea-trailer
- https://www.thegamer.com/hello-kitty-island-adventure-how-to-unlock-use-camera/
- https://www.ign.com/wikis/hello-kitty-island-adventure/Things_to_Do_First_in_Hello_Kitty_Island_Adventure
- https://www.thegamer.com/hello-kitty-island-adventure-best-visitor-cabin-decorating-ideas/
- https://www.wog.ch/fr/index.cfm/details/product/213968-Hello-Kitty-Island-Adventure-Deluxe-Edition
- https://www.ign.com/articles/hello-kitty-island-adventure-is-coming-to-switch-and-pc-in-2025-and-cozy-game-fans-rejoice
- http://cgmagonline.com/news/hello-kitty-island-adventure-new-platform/
- https://www.smythstoys.com/uk/en-gb/gaming-and-tech/pre-order-games/nintendo-switch-pre-order-games/hello-kitty-island-adventure-deluxe-edition-nintendo-switch/p/247065

- Events section icons
https://freeicons.io/


## Acessibility
- Making the website user-friendly has been at the core of design and construction of the site. This has been achieved using semantic html and alt attributes to describe images

- The chrome extension [Web Disability Simulator](https://chromewebstore.google.com/detail/web-disability-simulator/olioanlbgbpmdlgjnnampnnlohigkjla) has been used during building to consider the needs of individuals with conditions which may impact how the website is perceived

