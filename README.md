# Casa Dolce Vita
(Developer: Kamil Wojciechowski)

![Mockup image](docs/am-i-responsive.jpg)

[Live webpage](https://wojtekkamilowski.github.io/CI_PP1_CDVMR/)

## Table of Contents

1. [Project Goals](#project-goals)
    - [User Goals](#user-goals)
    - [Business Owner Goals](#business-owner-goals)
2. [User Experience](#user-experience)
    - [Target Audience](#target-audience)
    - [User Requirements and Expectations](#user-requirements-and-expectations)
    - [User Stories](#user-stories)
3. [Design](#design)
    - [Design Choices](#design-choices)
    - [Color](#color)
    - [Fonts](#fonts)
    - [Structure](#structure)
    - [Wireframes](#wireframes)
4. [Languages](#languages)
5. [Technologies Used](#technologies-used)
6. [Features](#features)
7. [Validation](#validation)
    - [HTML Validation](#HTML-validation)
    - [CSS Validation](#CSS-validation)
    - [Accessibility](#accessibility)
    - [Performance](#performance)
    - [Device testing](#device-testing)
    - [Browser compatibility](#browser-compatibility)
    - [Testing user stories](#testing-user-stories)
 8. [Bugs](#Bugs)
 9. [Deployment](#deployment)
 10. [Credits](#credits)
 11. [Acknowledgements](#acknowledgements)

## Project Goals

### User Goals
- Find a restaurant located in Cork city which offers a unique dining experience from Mediterranean cuisines. 
- Find the exact location of the restaurant and the neighbouring area with a scenic view of the city where it is located.
- Find useful information: important notices (e.g. about a temporary closure due to a refurbishment), special offers or opening hours.
- Get a feeling of what type of atmosphere, food offer, pricing range, building interior to expect during the visit in the restaurant.
- Understand the name of the restaurant which originates from different languages than the most commonly used in the country where it is located. 
- Communicate with the restaurant management to provide feedback, ask questions or suggest some changes.

### Business Owner Goals
- Present the establishment for a potential customer.
- Convince users to visit the restaurant by letting them familiarise with the product and feel welcome to visit.
- Inform users about important notices, special offers and when the restaurant can be visited.
- Receive feedback/questions/suggestions and collect contact details to possibly address them when needed.

[Back to Table Of Contents](#table-of-contents)

## User Experience

### Target Audience

- People who would like to visit a Mediterranean  restaurant in Cork.
- Individuals, couples or groups who would like to try a different type of food originating from abroad. 
- People who are looking for a scenic spot to eat with the view of Cork city.
- Customers who already visited the restaurant and would like to contact the business.

### User Requirements and Expectations

- Accessible website.
- Intuitive website with a layout allowing to easily navigate through it.
- Easy access to useful information. 
- Links and features that function in accordance with their intended purpose. 
- Welcoming visual appearance which follows the principles of responsive design.
- Easy to understand and informative content.
- A simple mean of contacting the staff.

[Back to Table Of Contents](#table-of-contents)

### User Stories

#### First-time User

As a first time user I want to:

1. Know if there is some disruption to the usual opening times or other very important information. 
2. Know when I can visit the place.
3. Know how to contact the restaurant via phone or email.
4. Know the address of the premises. 
5. Visit restaurant's social media platforms and check the activity on them.

#### Returning User

As a returning user I want to:

6. Contact the management and inform about my feedback after a visit.
7. Check if there is a special offer available. 
8. Check if the restaurant menu is same as during the last visit.

#### Business Owner 

As the restaurant owner I want to:

9. Advertise the place through presentation of food and drink served. 
10. Introduce what type of place the user can expect during the visit.
11. Reveal the interior design of the restaurant. 
12. Present the head chef to the user.
13. Inform the user who manages preparation of the dishes and the professional background of this person. 
14. Share other guests reviews and what they felt during their dining experience. 
15. Explain how to get to the restaurant and present its unique location. 
16. Make the user feel welcomed and invited to visit the restaurant.

[Back to Table Of Contents](#table-of-contents)

## Design

### Design Choices 
The main thought when designing the website was to introduce the restaurant as a fresh, welcoming, and warm place in a contemporary style with a mediterranean inspiration.
The logo contains a lemon icon for users to associate the place with the freshness of this fruit commonly grown in the Mediterranean region.
Restaurant's name displayed in the logo "Casa Dolce Vita" is a combination of "casa" which in Latin languages means "house" to let the user associate it with the warm and welcoming atmosphere of home, and "dolce vita" from Italian "sweet life" to suggest a tasteful dining experience.
On the top of the home page the user can observe the word "Welcome!" with a dish plate in the background to feel the website has been designed for the users to eventually bring them to the introduced dining experience, stimulating consumer expectations and curiosity to visit the place which is aimed to add a marketing value for the business owner as a mean of gaining possible competitive advantage over the competition.
Images on the menu page were chosen to present the food served in aesthetic way representing the quality of the product. 
On the About us page the user can get to known the chef and restaurant's interior which was aimed to represent the friendly environment of the establishment and its staff. 
The design choice for other elements of the website such Announcements, Opening hours, Food/Drinks Menus, Our Place/Chef/Guests, the contact form and the map was decided to clearly display relevant information for the user in a simple and easy to understand way.

[Back to Table Of Contents](#table-of-contents)

### Color
The chosen color scheme was a combination of white and blue tones which is to symbolize the mediterranean theme, they are the colors of the mediterranean sea, and white houses which could be well known as a part of the Greek landscape. The initially chosen blue color was found on color-hex.com and was different to the one on the final version of the website as it was changed during accessibility tests and checking their contrast on WebAIM. 

![Color scheme](docs/features/colors.jpg)

[Back to Table Of Contents](#table-of-contents)

### Fonts
Fonts were found using fonts.google.com
The font chosen for the logo h1 and the Welcome h2 was _Great Vibes_ to match the mediterranean theme of the restaurant. 
For h2, h3, nav id menu a, footer, class cuisine type p on the menu page, and class message-box legend elements _Raleway_ was used to differentiate them.
The font chosen for the body was _Roboto_.
_Sans-serif_ was chosen as the fallback font for all elements.

[Back to Table Of Contents](#table-of-contents)

### Structure
The structure was chosen to follow the common pattern of placing the website logo in the top left corner and the navigation links on the top right corner of the website.
There are four pages that are parts of the website:
- Home with two sections: first is the Welcome! h2 with its food_plate image in the background and second with id notice-board containing Announcements and Opening hours.
- Menu presenting the menu carte with food served in three distinctive divs id: restaurant-menu-header, menu-images and restaurant-menu.
- About us with three sections for Our Place, Our Chef and Our Guests.
- Contact consisting with a contact form and an iframe map.

[Back to Table Of Contents](#table-of-contents)

## Wireframes
<details>
    <summary>Home</summary>
    <img src="docs/wireframes/wireframe-home-desktop.png">
    <img src="docs/wireframes/wireframe-home-tablet.png">
    <img src="docs/wireframes/wireframe-home-smartphone.png">
</details>
<details>
    <summary>Menu</summary>
    <img src="docs/wireframes/wireframe-menu-desktop.png">
    <img src="docs/wireframes/wireframe-menu-tablet.png">
    <img src="docs/wireframes/wireframe-menu-smartphone.png">
</details>
<details>
    <summary>About us</summary>
    <img src="docs/wireframes/wireframe-about-us-desktop.png">
    <img src="docs/wireframes/wireframe-about-us-tablet.png">
    <img src="docs/wireframes/wireframe-about-us-smartphone.png">
</details>
<details>
    <summary>Contact</summary>
    <img src="docs/wireframes/wireframe-contact-desktop.png">
    <img src="docs/wireframes/wireframe-contact-tablet.png">
    <img src="docs/wireframes/wireframe-contact-smartphone.png">
</details>
<details>
    <summary>404</summary>
    <img src="docs/wireframes/wireframe-404-desktop.png">
    <img src="docs/wireframes/wireframe-404-tablet.png">
    <img src="docs/wireframes/wireframe-404-smartphone.png">
</details>

[Back to Table Of Contents](#table-of-contents)

## Languages
- HTML
- CSS

## Technologies Used
- GitHub
- Gitpod
- Balsamiq - to create the wireframes.
- Font Awesome - to add logo, address, social media, and restaurant menu icons.
- favicon.io - to create the favicon.
- Google Maps to add the link to the map.
- Google Fonts to find and add Great Vibes, Raleway and Roboto fonts. 
- TinyPNG to compress the images.
- color-hex to find the initial color's hex value.
- WebAIM to identify the color that would match the design choice and accessibility requirements. 

[Back to Table Of Contents](#table-of-contents)

## Features
On the website there are four pages with twelve features in total.

<details>
    <summary>Logo and Navigation Bar</summary>  
    It is included on all four pages.<br> 
    The logo consists of the icon and restaurant's name is a clickable link to Home page which is a common feature and users expect it.<br> 
    On the right there are four links to each of the pages: Home, Menu, About us and Contact so the user can easily navigate through.<br> 
    To indicate for the user on which page is currently viewed it is underlined.<br> 
    When the user hovers the mouse over the other pages links it also underlines informing the user that the link will bring to the named page.<br> 
    Logo and Navigation Bar are responsive, the page links slide to the left under the logo for smaller screens.<br>
    User stories covered: 6, 8, 9, 10, 11, 12, 13, 14, 15.
    <img src="docs/features/feature-logo-and-navbar.jpg">
</details> 
<details>
    <summary>Footer</summary> 
    Appears on all four pages.<br>
    Divided by three divs with their id: phone-email, address and social.<br> 
    div id phone-email displays restaurant's phone number and email address on the left side.<br>
    In the center of the footer there is div id address consists of the location dot icon and restaurant's location address and clicking it links to the map view on       Google Maps opened in a new tab.<br>
    From the right side of the id social div, there are icons with clickable links to the social media. Footer is responsive, id address and social divs slide under       the id phone-email div from footer's top to its bottom.<br>
    User stories covered: 3, 4, 5. 
    <img src="docs/features/feature-footer.jpg">
</details>
<details>   
    <summary>Plate image</summary>     
    Placed on the top of the Home page.<br>
    Displays "Welcome!" h2 on the top center with a plate image in the background welcoming the user to the website and the restaurant.<br> 
    It is responsive, the background image is resized and font-size reduced for smaller screens.<br>
    User stories covered: 9, 16. 
    <img src="docs/features/feature-plate-image.jpg">
</details>
<details>
    <summary>Announcements</summary>
    Included on the Home page in the center of its section, under the plate image feature.<br> 
    Consists of two notifications displayed in the fieldsets for the user: the first one with its legend "!" an important urgent notice regarding a temporary               closure, and the other one is a special offer of the restaurant.<br> 
    It is responsive, text content for both notifications reduces its width and increases the height.<br>
    User stories covered: 1, 7.
    <img src="docs/features/feature-announcements.jpg">
</details>
<details>
    <summary>Opening hours</summary> 
    Included on the Home page in the center of its section, under the announcements feature.<br>
    Dispalys opening hours during weekdays and weekends.<br>
    It is responsive, reducing its font-size, weekend opening hours information slides under the weekdays opening hours for smaller screens.<br>
    User stories covered: 2.
    <img src="docs/features/feature-opening-hours.jpg">
</details>
<details>
    <summary>Restaurant menu header and menu images</summary>
    Positioned on the top of the menu page.<br>
    Displays MENU h2 and three menu images presenting food and drink.<br>
    They are reponsive, the images wrap reverse for medium size screens so the third image from the left displayes on top of the two other images. For smaller screens     the images are position from the top to the bottom. <br>
    User stories covered: 8, 9.
    <img src="docs/features/feature-restaurant-menu-header-and-menu-images.jpg">
</details>
<details>    
    <summary>Food Menu and Drinks Menu</summary>
    Can be found on the menu page below the restaurant menu header and menu images feature.<br> 
    Lists the food and drinks offer and the prices of the restaurant.<br>
    They are responsive, Drinks Menu slides under Food Menu for smaller screens.<br>
    User stories covered: 8, 9.
    <img src="docs/features/feature-food-menu-and-drinks-menu.jpg">
</details>
<details>
    <summary>Our Place</summary> 
    First section of the About us page, appears under the logo and navigation bar feature.<br>
    Consists of a text describing what is the place and an image of restaurant's interior.<br>
    They are responsive, the text content reduces its width and increases the height, and the image slides under the text for smaller screens.<br>
    User stories covered: 10, 11.
    <img src="docs/features/feature-our-place.jpg">
</details>
<details> 
    <summary>Our Chef</summary>
    Second section of the About us page, appears under the our place feature.<br>
    Consists of a text describing who is the chef and his image.<br>
    They are responsive, the text content reduces its width and increases the height, and the image slides above the text for smaller screens.<br>
    User stories covered: 12, 13.
    <img src="docs/features/feature-our-chef.jpg">
</details>
<details>  
    <summary>Our Guests</summary>
    Third section of the About us page, appears under the our chef feature.<br>
    Consists of a text with other guests reviews of the restaurant. <br>
    It is responsive, the text content reduces its width and increases the height.<br>
    User stories covered: 14.
    <img src="docs/features/feature-our-guests.jpg">
</details>
<details>
    <summary>Contact form</summary>
    Placed in the center of the page,, on the left side of the Contact page.<br>
    Includes a form with name, email, and phone inputs, a textarea, and a submit button for the user.<br>
    The form is responsive, adjusting the size to the viewport and moves above the map for medium size screens.<br>
    User stories covered: 6.
    <img src="docs/features/feature-contact-form.jpg">
</details>
<details>
    <summary>Map</summary>
    Placed in the center of the page, on the right side of the Contact page.<br>
    Includes an iframe map from Google Maps.<br>
    The map is responsive, moves below the form for medium size screens and reduces its size for smaller screens.<br>
    User stories covered: 15.
    <img src="docs/features/feature-map.jpg">
</details>

[Back to Table Of Contents](#table-of-contents)

## Validation

### HTML Validation
To validate HTML of the website the W3C Markup Validation Service was used. The results have no errors.

#### Home
![HTML Validation Home](docs/validation/validation-html-index.jpg)

#### Menu
![HTML Validation Menu](docs/validation/validation-html-menu.jpg)

#### About us
![HTML Validation About us](docs/validation/validation-html-about.jpg)

#### Contact
![HTML Validation Contact](docs/validation/validation-html-contact.jpg)

#### 404
![HTML Validation 404](docs/validation/validation-html-404.jpg)

### CSS Validation
To validate style.css the W3C Jigsaw CSS Validation Service was used. There were no errors found.

![CSS Validation](docs/validation/validation-css-style.jpg)

[Back to Table Of Contents](#table-of-contents)

## Accessibility
Accessibility was tested using WAVE - Web Accessibility Evaluation Tool. All of the pages have no errors.
An initial error regarding the contrast was fixed using WebAIM where a similar, however with a better contrast color was found for the background.

### Home
![Accessibility Validation Home](docs/validation/validation-accessibility-index.jpg)

### Menu
![Accessibility Validation Menu](docs/validation/validation-accessibility-menu.jpg)

### About us
![Accessibility Validation About us](docs/validation/validation-accessibility-about.jpg)

### Contact
![Accessibility Validation Contact](docs/validation/validation-accessibility-contact.jpg)

### 404
![Accessibility Validation 404](docs/validation/validation-accessibility-404.jpg)

[Back to Table Of Contents](#table-of-contents)

## Performance
The tool used to test the performance of the website was Google Lighthouse from Google Chrome Developer Tools.

### Home

#### Desktop
![Performance Home Desktop](docs/validation/lighthouse-performance-desktop-index.jpg)

#### Mobile
![Performance Home Mobile](docs/validation/lighthouse-performance-mobile-index.jpg)

### Menu

#### Desktop
![Performance Menu Desktop](docs/validation/lighthouse-performance-desktop-menu.jpg)

#### Mobile
![Performance Menu Mobile](docs/validation/lighthouse-performance-mobile-menu.jpg)

### About us

#### Desktop
![Performance About us Desktop](docs/validation/lighthouse-performance-desktop-about.jpg)

#### Mobile
![Performance About us Mobile](docs/validation/lighthouse-performance-mobile-about.jpg)

### Contact

#### Desktop
![Performance Contact Desktop](docs/validation/lighthouse-performance-desktop-contact.jpg)

#### Mobile
![Performance Contact Mobile](docs/validation/lighthouse-performance-mobile-contact.jpg)

### 404

#### Desktop
![Performance 404 Desktop](docs/validation/lighthouse-performance-desktop-404.jpg)

#### Mobile
![Performance 404 Mobile](docs/validation/lighthouse-performance-mobile-404.jpg)

[Back to Table Of Contents](#table-of-contents)

## Device testing
List of devices used to test the website:
- HP Pavilion 14 
- Sony Xperia L2
- Motorola Moto G20

The website was also tested using Google Chrome Developer Tools, Toggle Device Toolbar simulating view from twenty-five listed devices, including popular amongst users iPad and iPhone 5.

## Browser compatibility
Following browsers were used to test the website:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge

[Back to Table Of Contents](#table-of-contents)

## Testing user stories 

1. As a first time user I want to know if there is some disruption to the usual opening times or other very important information:

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Announcements | On the home page scroll down to the Announcements | Find the information if the business is open as usual | Works as expected |

![Testing user story 1](docs/user-story-testing/user-story-1.jpg)

2. As a first time user I want to know when I can visit the place.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Opening hours | On the home page scroll down to the Opening hours | Find the information about restaurant's opening hours | Works as expected |

![Testing user story 2](docs/user-story-testing/user-story-2.jpg)

3. As a first time user I want to know how to contact the restaurant via phone or email.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Footer | On any page of the website scroll down to the very bottom to see restaurant's email address and phone number | Find restaurant's email address and phone number | Works as expected |

![Testing user story 3](docs/user-story-testing/user-story-3.jpg)

4. As a first time user I want to know the address of the premises.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Footer | On any page of the website scroll down to the very bottom to see restaurant's address, click on it to open Google Maps with its location in a separate tab | Find restaurant's address and find its location on the map | Works as expected |

![Testing user story 4](docs/user-story-testing/user-story-4.jpg)

5. As a first time user I want to visit restaurant's social media platforms and check the activity on them.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Footer | On any page of the website scroll down to the very bottom to see social media icons and click on them to open links of any of the pictured social media platforms | The social media websites open in a separate browser tab | Works as expected |

![Testing user story 5](docs/user-story-testing/user-story-5.jpg)

6. As a returning user I want to contact the management and inform about my feedback after a visit.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Logo and Navigation Bar | Navigate to the contact page by clicking on Contact | Contact page opens | Works as expected  |
| Contact form | Fill up the form with the requested details | The input values are submitted via form correctly | Works as expected  |

![Testing user story 6](docs/user-story-testing/user-story-6.jpg)

7. As a returning user I want to check if there is a special offer available.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Announcements | On the home page scroll down to the Announcements | Find if a special offer is available | Works as expected  |

![Testing user story 7](docs/user-story-testing/user-story-7.jpg)

8. As a returning user I want to check if the restaurant menu is same as during the last visit.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Logo and Navigation Bar | Navigate to the menu page by clicking on Menu | Menu page opens | Works as expected  |
| Restaurant menu header and menu images | Navigate to the menu page using the Logo and Navigation Bar feature | See the images displaying what kind of food is served in the restaurant | Works as expected |
| Food Menu and Drinks Menu | On the menu page scroll below menu images | Find what is the food and drink offered and what is the price range | Works as expected  |


![Testing user story 8](docs/user-story-testing/user-story-8.jpg)

9. As the restaurant owner I want to advertise the place through presentation of food and drink served.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Logo and Navigation Bar | Navigate to the menu page by clicking on Menu | Menu page opens | Works as expected  |
| Restaurant menu header and menu images | Navigate to the menu page using the Logo and Navigation Bar feature | The images display what kind of food guests can expect in the restaurant | Works as expected |
| Food Menu and Drinks Menu | On the menu page scroll below menu images | Present the offered food and drink with their prices | Works as expected |
| Plate image | Open the home page | Welcome the user and a potential guest of the restaurant wih a food plate in the background | Works as expected  |

![Testing user story 9](docs/user-story-testing/user-story-9.jpg)

10. As the restaurant owner I want to introduce what type of place the user can expect during the visit.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Logo and Navigation Bar | Navigate to the about us page by clicking on About | About page opens | Works as expected  |
| Our Place | Navigate to the about us page using the Logo and Navigation Bar feature | Display the text descrbing the restaurant | Works as expected |

![Testing user story 10](docs/user-story-testing/user-story-10.jpg)

11. As the restaurant owner I want to reveal the interior design of the restaurant.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Logo and Navigation Bar | Navigate to the about us page by clicking on About | About page opens | Works as expected  |
| Our Place | Navigate to the about us page using the Logo and Navigation Bar feature | Show the image of restaurant's interior | Works as expected |

![Testing user story 11](docs/user-story-testing/user-story-11.jpg)

12. As the restaurant owner I want to present the head chef to the user.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Logo and Navigation Bar | Navigate to the about us page by clicking on About | About page opens | Works as expected  |
| Our Chef | Navigate to the about us page using the Logo and Navigation Bar feature and scroll below Our Place | Show the photo of restaurant's head chef | Works as expected |

![Testing user story 12](docs/user-story-testing/user-story-12.jpg)

13. As the restaurant owner I want to inform the user who manages preparation of the dishes and the professional background of this person.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Logo and Navigation Bar | Navigate to the about us page by clicking on About | About page opens | Works as expected  |
| Our Chef | Navigate to the about us page using the Logo and Navigation Bar feature and scroll below Our Place | Display the text describing restaurant's head chef | Works as expected |

![Testing user story 13](docs/user-story-testing/user-story-13.jpg)

14. As the restaurant owner I want to share other guests reviews and what they felt during their dining experience.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Logo and Navigation Bar | Navigate to the about us page by clicking on About | About page opens | Works as expected  |
| Our Guests | Navigate to the about us page using the Logo and Navigation Bar feature and scroll below Our Chef | Show restaurant's guests reviews | Works as expected |

![Testing user story 14](docs/user-story-testing/user-story-14.jpg)

15. As the restaurant owner I want to explain how to get to the restaurant and present its unique location.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Logo and Navigation Bar | Navigate to the contact page by clicking on Contact | Contact page opens | Works as expected  |
| Map | Open the contact page using Logo and Navigation Bar feature | Present the location of the restaurant on Google Maps map | Works as expected |

![Testing user story 15](docs/user-story-testing/user-story-15.jpg)

16. As the restaurant owner I want to make the user feel welcomed and invited to visit the restaurant.

| Feature | Action  | Expected Result | Actual Result |
| ------- | ------- | --------------- | ------------- |
| Plate image | Open the home page | Welcome the user and a potential guest of the restaurant wih a food plate in the background | Works as expected  |

![Testing user story 16](docs/user-story-testing/user-story-16.jpg)

[Back to Table Of Contents](#table-of-contents)

## Bugs
| Bug  | Fix  |
| ------- | ------- |
| When viewed on mobile devices the pages have a white line on the right side that goes after the header and footer | Remove excessive paddings & change some paddings values from px to vh/vw |
| Opening hours fieldset narrower than the Announcements fieldset and do not match on smaller screens | Adjust opening hours margins using media queries for 300px wide screens | 
| Low colors contrast | Find a similar tone of blue color using WebAIM | 
| Welcome! background image not visible on smaller screens, too dark not matching design choices | Find a brighter image with a more distanced focus on a plate with food | 
| Google Maps iframe map do not fit on the page for smaller screens | Add max-width & height properties for media queries | 

[Back to Table Of Contents](#table-of-contents)

## Deployment 
The website was deployed on GitHub Pages as per following steps:
1. From the GitHub repository open the settings tab.
2. Select Pages from the options on the left (Code and automation section).
3. Source: deploy from a branch.
4. Branch: main.
5. Once the page is reloaded there was a notification "Your site is live at https://wojtekkamilowski.github.io/CI_PP1_CDVMR/"

To fork the repository you should:

1. Open the repository: https://github.com/WojtekKamilowski/CI_PP1_CDVMR
2. Select Fork from the options on the right.

To clone the GitHub repository you should:
1. Open the repository: https://github.com/WojtekKamilowski/CI_PP1_CDVMR
2. In the Code tab select click on Code button and select the preferred option (HTTPS/SSH/Github CLI) and click the copy button on the right of URL
3. Open Git Bash and change the current working directory to the desired one.
6. Type git clone and paste the previously copied URL from GitHub then pressing the enter button should create a local clone.

[Back to Table Of Contents](#table-of-contents)

## Credits 

### Media

- <a href="assets/images/food_plate.jpg">food_plate</a> photo by <a href="https://unsplash.com/@jaywennington">Jay Wennington</a> on <a href="https://unsplash.com/photos/N_Y88TWmGwA">Unsplash</a>
- <a href="assets/images/apetizers.jpg">apetizers</a> photo by <a href="https://www.pexels.com/@lina/">Lina Kivaka</a> on <a href="https://www.pexels.com/photo/assorted-color-ceramic-tea-set-1813504/">Pexels</a>
- <a href="assets/images/gelato.jpg">gelato</a> photo by <a href="https://unsplash.com/@shibataskaterock2018">Flavio Shibata</a> on <a href="https://unsplash.com/photos/z_eoi3ppf5U">Unsplash</a>
- <a href="assets/images/wine.jpg">wine</a> photo by <a href="https://unsplash.com/@brett_jordan">Brett Jordan</a> on <a href="https://unsplash.com/photos/b-BtDwZO1YU">Unsplash</a>
- <a href="assets/images/our_place.jpg">our_place</a> photo by <a href="https://www.pexels.com/@reneasmussen/">Rene Asmussen</a> on <a href="https://www.pexels.com/photo/restaurant-interior-filled-with-tables-and-chairs-2504963/">Pexels</a>
- <a href="assets/images/our_chef.jpg">our_chef</a> photo by <a href="https://www.pexels.com/@kampus/">Kampus Production</a> on <a href="https://www.pexels.com/photo/a-chef-wearing-a-flat-cap-6605423/">Pexels</a>
- <a href="assets/images/broken_plate.jpg">broken_plate</a> photo by <a href="https://pixabay.com/users/brrt-122519/">BRRT</a> on <a href="https://pixabay.com/photos/plate-broken-plate-broken-food-1902604/">Pixabay</a>
- <a href="assets/images/favicon.png">favicon</a> generated from <a href="https://favicon.io/favicon-generator/">Favicon.io</a>
- All icons were found on <a href="https://fontawesome.com/icons">Font Awesome</a> 

### Code
- HTML and CSS was inspired by <a href="https://github.com/Code-Institute-Solutions/love-running-2.0-sourcecode">Love Running CI Project</a>
- Footer was inspired by the material available at <a href="https://css-tricks.com/couple-takes-sticky-footer/">css-tricks</a>
- How to use flex was based on the information from <a href="https://css-tricks.com/snippets/css/a-guide-to-flexbox/">css-tricks</a> and <a href="https://blog.hubspot.com/website/center-div-css#:~:text=To%20center%20a%20div%20horizontally,equally%20between%20the%20two%20margins">HubSpot</a>
- The 404 page was inspired from the project of <a href="https://github.com/4n4ru/CI_MS1_BodelschwingherHof">Ana Runje</a>
- Use of the CSS Grid was based on <a href="https://www.w3schools.com/css/css_grid.asp">W3Schools</a> and <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout">Mozilla</a>

[Back to Table Of Contents](#table-of-contents)

## Acknowledgements
I would like to thank you those who were a great support and inspiration during writing this project:
- My mentor Mo Shami.
- Code Institute for preparing the materials and providing a wide range of available means of learning for the students.
- My family who were the first users to test the website.








