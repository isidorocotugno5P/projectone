# CurryHouse Concept Restaurant 

![CurryHouse Logo](assets/images/readme-media/curryhouse-logo.png)

The CurryHouse website was developed for a concept restaurant that serves different style curries from around the world in a fun, Asian-influenced hygge-style environment, offering branded merchandise and constantly changing menus in order to attract new as well as retain returning customers. This site will be targeted towards customers that value curry-related culture and their stylistic influences, especially from India and Southeast Asia, even if the menu choices are not limited to those areas. These are customers who are looking for an authentic dining experience but do not want to limit themselves to one country's food. CurryHouse hopes to attract dedicated customers to attain a large social media presence through merchandising and recognizable branding. Constantly changing available menu items to retain exclusivity and excitement for returning customers, as well as an incentive for new customers. 

![Responsive Mockup](assets/images/readme-media/responsive-design.png)

[Link to Live Site](https://isidorocotugno5p.github.io/projectone/index.html)

## Table of Content
- [CurryHouse Concept Restaurant](#curryhouse-concept-restaurant)
  - [Table of Content](#table-of-content)
  - [User Stories](#user-stories)
    - [1. Responsive Website and Easy Access to Key Pages](#1-responsive-website-and-easy-access-to-key-pages)
    - [2. Interactive Menu with Limited-Time Specials](#2-interactive-menu-with-limited-time-specials)
    - [3. Merchandise Display for CurryHouse Fans](#3-merchandise-display-for-curryhouse-fans)
    - [4. Newsletter Signup for Restaurant Updates](#4-newsletter-signup-for-restaurant-updates)
    - [5. Social Media Links \& Contact Information](#5-social-media-links--contact-information)
  - [Features](#features)
    - [Navigation Bar](#navigation-bar)
      - [Dropdown Menu](#dropdown-menu)
    - [Landing Page](#landing-page)
    - [Home Page](#home-page)
      - [Menu Section](#menu-section)
      - [Monthly Curry Section](#monthly-curry-section)
      - [Merch Section](#merch-section)
      - [Newsletter Section](#newsletter-section)
    - [Menu Page](#menu-page)
    - [Gallery Page](#gallery-page)
    - [Contact Page](#contact-page)
    - [Merch Page](#merch-page)
    - [Modal](#modal)
      - [Newsletter Modal](#newsletter-modal)
      - [Merch Modal](#merch-modal)
    - [Success Page](#success-page)
    - [404 Page](#404-page)
    - [Footer](#footer)
  - [Styles](#styles)
    - [Fonts](#fonts)
      - [Primary Font](#primary-font)
      - [Secondary Font](#secondary-font)
    - [Color Schemes](#color-schemes)
      - [Color Psychology](#color-psychology)
      - [Other Colors](#other-colors)
      - [Contrast Score](#contrast-score)
    - [Wireframes Layout](#wireframes-layout)
      - [Homepage](#homepage)
        - [Mobile](#mobile)
        - [Desktop](#desktop)
      - [Menu](#menu)
        - [Mobile](#mobile-1)
        - [Desktop](#desktop-1)
      - [Gallery](#gallery)
        - [Mobile](#mobile-2)
        - [Desktop](#desktop-2)
  - [Technologies Used](#technologies-used)
    - [Languages](#languages)
    - [Frameworks](#frameworks)
    - [Libraries](#libraries)
    - [Platforms](#platforms)
    - [Other Tools](#other-tools)
  - [Credits](#credits)
  - [Testing](#testing)
    - [Lighthouse](#lighthouse)
      - [Homepage](#homepage-1)
        - [Mobile](#mobile-3)
        - [Desktop](#desktop-3)
      - [Menu](#menu-1)
        - [Mobile](#mobile-4)
        - [Desktop](#desktop-4)
      - [Gallery](#gallery-1)
        - [Mobile](#mobile-5)
        - [Desktop](#desktop-5)
      - [Contact](#contact)
        - [Mobile](#mobile-6)
        - [Desktop](#desktop-6)
      - [Merch](#merch)
        - [Mobile](#mobile-7)
        - [Desktop](#desktop-7)
    - [HTML Validation](#html-validation)
      - [Home](#home)
      - [Menu](#menu-2)
      - [Gallery](#gallery-2)
      - [Contact](#contact-1)
      - [Merch](#merch-1)
    - [CSS Validation](#css-validation)
    - [General Testing](#general-testing)
    - [Mobile Testing](#mobile-testing)
    - [Desktop Testing](#desktop-testing)
  - [Bugs](#bugs)
    - [Fixed Bugs](#fixed-bugs)
  - [Future Features](#future-features)
  - [Deployment](#deployment)


## User Stories 

### 1. Responsive Website and Easy Access to Key Pages

- User Story: As a first-time visitor to the website I need a simple layout allowing me to access all key pages, making sure all relevant information is readily available without much effort. 

    - Acceptance Critera

        * Site layout and navigation is intuitive, allowing easy access to key pages and sections.
        * The website adapts for mobile, tablet, and desktop and is fully reponsive for all screen sizes.
        * Adapting features for the majority of the population 

    - Key Tasks

        * Implement responsive design for all screen sizes for accessibility on multiple screen sizes.
        * Ensure key pages are easily accessible on navigation bar or homepage site.
        * Use clean practices to ensure professional and seemless website layout. 

### 2. Interactive Menu with Limited-Time Specials

- User Story: As an interested customer I want to know current offers, specials, pricing, and any information relevant to the food available depicted in an appetizing and intriguing manner. 

    - Acceptance Criteria

        * A carousel on the homepage showcasing the current curries available.
        * The "Menu" page is organized into categories (Curries, Shareables, Sides) with pricing and spice level indicators.
        * Monthly or limited-time specials are highlighted on the homepage and menu page.

    - Key Tasks 

        * Design and implement a homepage carousel displaying current menu items.
        * Create a well-structured menu page with clear categories and colorful item details.
        * Highlight special offers and integrate them into the homepage.

### 3. Merchandise Display for CurryHouse Fans

- User Story: As a loyal and returning customer I want to be able to support my local CurryHouse by purchasing branded merchandise that aids the restaurant in marketing through exxlusive promo products. 

    - Acceptance Criteria 

        * A "Merch" section that is featured on the homepage with a sample image of the merch as a bundle.
        * Easy access to the merch page from the homepage.
        * A simple layout of the merch for effective overview with the possibility to check availability on individual items.
        * The option of signing onto the newsletter for notification upon receiving new merchandise. 

    - Key Tasks 

        * Create a merch section on the homepage to attract loyal customers and interested parties, include a button that leads right to the merch page.
        * Implement a dedicated merch page with clear product images and descriptions, as well as stock availability.
        * Adding a subscription form to the newsletter, if items have been sold out. 

### 4. Newsletter Signup for Restaurant Updates

- User Story: As an interested returning customer, I want to easily subscribe to the CurryHouse newsletter, so I can receive updates about new menu items, promotions, and events.

    - Acceptance Criteria 

        * A simple email subscription form is available on the homepage and merch page. 
        * Upon sign-up, users receive a confirmation that they are added to the mailing list.

    - Key Tasks 

        * Design a newsletter signup form that pops up as a modal on screen.
        * Integrate the form with an email marketing service (e.g., Mailchimp). - yet to learn
        * Display a success message after subscription.

### 5. Social Media Links & Contact Information

- User Story: As a customer, I want easy access to CurryHouse’s social media and contact details, so I can contact the restaurant for reservations, requests, etc.

    - Acceptance Critera 

        * The large and visible footer contains links to CurryHouse’s social media profiles, attracting most customers to these links rather than the contact page.
        * The Contact page includes a Google Maps embed, address, and phone number.

    - Key Tasks 

        * Ensure the Contact page includes a map, clickable phone number, and address.
        * Make footer large and visually attention grabbing at the bottom of every page, possibly with a call-to-action. 
        * Ensure footer has opposing color scheme to stand out from the rest of website. 


## Features 

This section will include the features of this CurryHouse project and how they effectively aided in achieving all goals. 

### Navigation Bar

![Navigation Bar Mobile](assets/images/readme-media/navbar-mobile.png)
![Navigation Bar Tablet](assets/images/readme-media/navbar-tablet.png)
![Navigation Bar Desktop](assets/images/readme-media/navbar-desktop.png)

As seen above the navigation bar of the CurryHouse website implements an icon for the mobile and tablet device revealing all of its pages, for desktop it shows all of its options without having a dropdown list, except for the menu page which leads you to the different sections of the menu. 

On the left side of each navigation bar presented above you see our CurryHouse logo with its famous and recognizable chili attached at the end of the brand name, reminding our customers what we stand for, who we are, and what we offer. 

The dropdown menu for the "Menu" page specifically presents a fun and interactive way to tell our customers what we offer, including a section titled "Shareables" indicating that our dining experience is an immersive one. 

We have also added a visible "Merch" page to our navigation bar for easy access to ensure our customers have the opportunity to support us outside of dining with us. Adding this page to the navigation bar enables us to intrigue new customers because it is uncommon for non-chain restaurants to have branded merchandise available for purchase. 

#### Dropdown Menu

![Dropdown Navigation Bar Menu Mobile](assets/images/readme-media/dropdown-mobile.png)
![Dropdown Navigation Bar Menu Tablet](assets/images/readme-media/dropdown-tablet.png)

The navigation bar dropdown menu, and sub-dropdown menu of the "Menu" page has its text fall on the right side of the page enabling easy interaction on tablet and mobile devices. This is because most individuals are right-handed this was a conscious choice in the website design, ensuring customer satisfaction. 

### Landing Page 

![Landing Page Mobile](assets/images/readme-media/homepage-mobile.png)
![Landing Page Tablet](assets/images/readme-media/homepage-tablet.png)
![Landing Page Desktop](assets/images/readme-media/homepage-desktop.png)

As you can clearly see in the pictures above, it was important to double-down on the branding in the header of the landing page and restate "CurryHouse" supported by its chili logo repeatedly in the background to very aggressively imprint its branding into the customers memory. 

Calling it "Home of the Curry" supports the idea of it being the one-stop-shop for all dining experiences curry related, and reinforcing the message that in fact CurryHouse wants to feel like the home away from home for curry lovers. 

In the opening design one sees the representative, colors, fonts, and schemes that are supposed to strengthen all of the goals. A fun font, an immersive and culturally accurate color scheme, as well as Southeast Asian style golden laces on each side of the website for desktop and tablet users to emphasize the experience. 

Lastly on the opening page one can clearly see the beginning of a carousel displaying different pictures of currently available curries, creating a visual respresentation of CurryHouses' vast ability to represent different nations and their curries authentically, as well as submissively telling the customer that this menu is everchanging. Since the carousel is only partially displayed, it incentivizes the customer to enagage with the website and scroll down, to not only view the carousel in full display, but also interact with the rest of the website. 

### Home Page

Below is a breakdown of the entire Homepage. 

#### Menu Section 

![Menu Section Home Page Mobile](assets/images/readme-media/menusection-mobile.png)
![Menu Section Home Page Tablet](assets/images/readme-media/menusection-tablet.png)
![Menu Section Home Page Desktop](assets/images/readme-media/menusection-desktop.png)

The homepage opens up with a section specifically about the currently available curries at the restaurant giving the customer a simple overview of what CurryHouse has to offer right off the bat with a visually appealing display of the food in a carousel. Tablet and desktop version include little tags indicating the type of curry as well as its origin for an informative experience. 

Directly below the carousel there is an appropriately stylized button leading a customer to the menu page directly to have an overview of all the offers available. The goal is to intrigue the customer with the pictures and make the menu readily available at the click of a button without having to access the navbar for the menu page. This simplifies the customers experience, making the process of viewing the current offers available a seemless task. 

Directly below the carousel and menu-linked button is a short description offering information about the restaurant, its beliefs, and what they are offering. The desktop version offers an extra paragraph with slightly more information. Tablet and mobile do not to, this was done in order to limit space, make the interaction more visually appealing as well as reducing text related clutter. 

#### Monthly Curry Section 

![Curry Section Home Page Mobile](assets/images/readme-media/currysection-mobile.png)
![Curry Section Home Page Tablet](assets/images/readme-media/currysection-tablet.png)
![Curry Section Home Page Desktop](assets/images/readme-media/currysection-desktop.png)

This section supports the goal of indicating to the customer that CurryHouse has a menu that changes on a regular basis. An image is presented to present this months available special in conjunction with a title that indcludes the curries name and place of origin keeping consistent with the goal of representing global cuisines, in a authentic and informative manner. In addition, there is a short educational text on the special. Also the website includes a small bordered and highlighted message indicating that this curry is a limited special, further aiding the goal of representing to the customer that CurryHouse is always current and consistently interactive with its food for the sake of keeping the customer intrigued and on their feet. 

#### Merch Section 

![Merch Section Home Page Mobile](assets/images/readme-media/merchsection-mobile.png)
![Merch Section Home Page Tablet](assets/images/readme-media/merchsection-tablet.png)
![Merch Section Home Page Desktop](assets/images/readme-media/merchsection-desktop.png)

This section lets the customer know that CurryHouse has merchandise offering the customer the possibility to represent its favorite restaurant. The call-to-action title incentivizes the customer to purchase the product. 

In this section one will find a text describing what the offers could possibly include written in an approachable and fun manner, as well as a button leading them directly to the merch page. This make the customer interaction seemless, similar to the menu section that has a button leading to menu page, this helps the customer act immediately upon interest without having to seek out the merch page on the navbar. Included in the section is also a picture of the CurryHouse merch bundle representing all the possible varities of merch potentially available in the store. 

#### Newsletter Section 

![Newsletter Section Home Page Mobile](assets/images/readme-media/newsletter-mobile.png)
![Newsletter Section Home Page Tablet](assets/images/readme-media/newsletter-tablet.png)
![Newsletter Section Home Page Desktop](assets/images/readme-media/newsletter-desktop.png)

At the bottom of the page the customer will find another call-to-action asking them to subscribe to the newsletter. This leads them to a modal with an extremely simple form asking for email only, ensuring simplicity and effectiveness. The modal was added in order to keep the customer on the homepage, in case of wanting to revert back they would just have to press "cancel". Successful completion of the form would then lead the customer to a notification page, letting the customer know CurryHouse has successfully added them to their newsletter list. 

Keeping the form extremely short and simple allows the customer to have an easy and non-intrusive experience, therefore yielding a higher return of interested parties for CurryHouse, enabling them to receive more information for targeted ads. 

The modal that has been mentioned in this section is revised below the merch page content.

### Menu Page 

![Menu Page Mobile](assets/images/readme-media/menupage-mobile.png)
![Menu Page Tablet](assets/images/readme-media/menupage-tablet.png)
![Menu Page Desktop](assets/images/readme-media/menupage-desktop.png)

The pictures above show the customer that the menu page is consistently styled with the rest of the website, adhering to the overall branding, font choice, and color scheme of CurryHouse. 

Menu title headers are linked in the navbar for easy and direct access to an individual section of the menu page seperating the menu page in three distinct parts (shareables, curries, and sides). Each title header is stylized to appear more important to indicate a new section, as well as the fact that it has its own color scheme, a border, and a text-decoration. 

The menu item title is underlined and larger to let the customer know this is the item in question. The price below is in the secondary font, but this is the only time on the website that the secondary font does not have bold font weight in order to make the price seem less important and not attract attention. The individual menu items stick to the traditional color scheme chosen for the overall branding of the website. 

Additionally the chili logo has been used on individual menu items to lets the customer know of its spiciness level. A fun and purposefully memorable way to remind the customer of the branding and simultaneously being informative. 

### Gallery Page 

![Gallery Page Mobile](assets/images/readme-media/gallerypage-mobile.png)
![Gallery Page Tablet](assets/images/readme-media/gallerypage-tablet.png)
![Gallery Page Desktop](assets/images/readme-media/gallerypage-desktop.png)

It was important for the project to add a gallery page to enable the customer to have access to a visual experience at the restaurant without having to visit it in order to make a dining experience at CurryHouse more appealing and attractive. With pictures of the kitchen, dining space, dishes, and customers the visitor of the website is more informed as to what is to be expected, and depicts the restaurant in a positive light. As one can see above it is a responsive design, sizes and layout stays structured and consistent throughout each screen size. 

### Contact Page

![Contact Page Mobile](assets/images/readme-media/contactpage-mobile.png)
![Contact Page Tablet](assets/images/readme-media/contactpage-tablet.png)
![Contact Page Desktop](assets/images/readme-media/contactpage-desktop.png)

Keeping consistent with the color scheme and design elements, the contact page is also as seen above responsive to all screen sizes. On the contact page the customer has a opportunity to quickly access a google maps link embedded into the html of the website, showing the customer the map itself making it easier for them to have a better overview of the restaurants location. Also the customer has the possibility of clicking onto the phone number which is linked a telephone number, enabling the customer to call quickly without having to copy paste the number when interacting with the website on a mobile device, ensuring a straight forward and satisfactory customer experience, potentially leading to more reservations. Icons have been added to the address and phone number to visually represent their purpose to the customer. 

### Merch Page 

![Merch Page Mobile](assets/images/readme-media/merchpage-mobile.png)
![Merch Page Tablet](assets/images/readme-media/merchpage-tablet.png)
![Merch Page Desktop](assets/images/readme-media/merchpage-desktop.png)

Again, the final page of this site is stylistically and visually consistent with the rest of the website, guaranteeing consistent visual branding and a memorable interactive experience. Card border have been removed, as well as the card body has been color the same as the background to remove appearance of "Bootstrap" cards, for a more seemlessly unique look consistent with what has been seen so far. The card buttons have been stylized like the rest, and just like all the other buttons have a hover effect to indicate to the customer you can engage this with a click of a mouse, or in the tablet and mobile case, with a click of a finger. 

There is a clear overview and layout of the cards showing what merchandise is available to purchase with picture and a fun text explaining the item, as well as a item title. 

The button reads "Check Availability" indicating that there is limited availability of these items, intriguing the customer to see if they are still able acquire one, making this a very exclusive aspect, differentiating this restaurant brand from most of the other ones. 

The modal included on this page has been added below this content.

### Modal

This basic modal is supposed to make it very easy for the customer to sign up to the newsletter without having to fill out a long and pesky form. The modal conforms to styles that have been set so far, same background color and button designs, as well as header choices in order to create a unified experience. 

#### Newsletter Modal

![Modal Newsletter Home Page](assets/images/readme-media/modal-home.png)

#### Merch Modal

![Modal Merch Page](assets/images/readme-media/modal-merch.png)

In comparison to the modal above a small text was added indicating to the customer that this item has been sold out and giving them the possibility to subscribe to the newsletter in order to find out when the next shipment of merchandise has come in. 

### Success Page

![Success Page Mobile](assets/images/readme-media/success-mobile.png)
![Success Page Tablet](assets/images/readme-media/success-tablet.png)
![Success Page Desktop](assets/images/readme-media/success-desktop.png)

The success page helps to let the customer know that they have successfully filled out and subscribed to our newsletter. The modal on the homepage or the one of the merchandise page leads to the same success message. Included is a button to lead you back to the homepage to continue browsing and interacting with the website. 

### 404 Page

![404 Page](assets/images/readme-media/404.png)

Similar to the success page the 404 error page indicates to the user that something went wrong, but gives them the option of clicking on the button which easily brings them back to the homepage without having to give it much thought. 

### Footer

![Footer Mobile](assets/images/readme-media/footer-mobile.png)
![Footer Tablet](assets/images/readme-media/footer-tablet.png)
![Footer Desktop](assets/images/readme-media/footer-desktop.png)

Found on each and every single page of the website is the footer which leads them to the social media apps that CurryHouse can be found on, which is one of the biggest goals. Which is why the footer only includes social media links, without address or phone number to focus the customer and lead them towards their social media profiles. In order to aid that goal, the style compliments the header in a contrasting manner by using the same stylistic theme and outline, but switching up the color scheme and using the other available colors that are still in line with the representation of the CurryHouse brand. 

The social media links open in a new tab in order to keep the CurryHouse website open and make it easier for the user to get back to the website if necessary. Each individual social media app has its own icon, name, as well as border and background color making them all stand out individually to make the overview easier for the user to choose their preferred destination. As well as a clear footerheader indicating what the footer consists of, styled in the same manner as the social media links themselves. 

The social media have a hover effect indicating to the user that this is a clickable link. Also on larger screen sizes the call to action "Follow Us on" has been added to try and drive more engagement through the social media links. To avoid a crowded footer and make the aesthetic overall more appealing the "Follow Us on" appears only or larger screen sizes. Furthermore on mobile screen sizes the boxed social media links appear below each other instead of next to each other, leaving the opporunity of clearly titling each social media app, instead of just using icons. 

## Styles

### Fonts

Below you will find a breakdown of the primary and secondary font

#### Primary Font

![Primary Font](assets/images/readme-media/font1.png)

The primary font was chosen due to its fun and unintimidating nature that makes it seem like it was hand drawn, creating a sort of a raw authentic feeling, making the experience of the design more personal. This connects with the idea and goal that the brand is simple but traditionally authentic, but also has a childlike approachable nature while maintaining professionality and consistency.  

#### Secondary Font

![Secondary Font](assets/images/readme-media/font2.png)

The secondary font was chosen also for its simplicity and ability to aesthetically work well in combination with the primary font. Almost all text using the secondary fon has been boldened, this was done to give the secondary font more presence in light of a very strong and attention grabbing primary font. Although the boldness allows for the secondary font to stick out more, it creates a perfect balance of seeming important but not robbing the primary font of its spotlight. 

### Color Schemes

Below you will find a breakdown of each color and its purpose, as well as their contrast score. 

#### Color Psychology 

![Primary Color](assets/images/readme-media/primary-color.png)
![Secondary Color](assets/images/readme-media/secondary-color.png)



[Quote from Blog:](https://www.stellendesign.com/hungry-colors-red-and-yellow/#:~:text=Using%20various%20shades%20of%20yellow,particularly%20when%20we're%20eating.)

 > And it’s not just used in branding. Using various shades of yellow and red in the environment have also been shown to increase energy and stimulate appetite. Both colors are known for creating strong associations, both mentally and emotionally. In other words, they make us feel good, particularly when we’re eating. So when we see them, we are reminded we felt good when we were eating, and the cycle perpetuates itself. 

The primary and secondary colors were chosen based on simple color psychology used by most fast-food chain restaurants known to the average person. Red and yellow are known to stimulate appetite and are the primary branding colors of most chain restaurants. Also, it helps build the brand goals because the colors remind the user of curry in it of itself. Red and yellow curry are globally known and relate to not only the use of color psychology but also the restaurants food as well. 

#### Other Colors

![Tertiary Color](assets/images/readme-media/tertiary-color.png)
![Highlight Color](assets/images/readme-media/highlight-color.png)

The tertiary color was chosen to be beige to give the primary text, which uses the primary color, a strong enough contrast for visibility and accessibility, making it easy for the user to read. The off-white nature of the color also helps add warmth, without the use of a boring blinding white. 

The highlight color in this case was choosen for the far background of the page as well as individual and specific design choices like the button hover color in order to include a refreshing aspect. Green in contract to the warm colors of beige, yellow, and red has a freshness to it, similar to herbs used in food, specifically curry in this case. 

#### Contrast Score

![Contrast Score](assets/images/readme-media/contrast-score.png)

This picture is evident of a satisfactory contrast score, ensuring readability on the website. 

### Wireframes Layout 

This sub-section depicts the basic layout used for the website (not all pages were designed using wireframe - some details may have been altered).

#### Homepage 

##### Mobile

![Homepage Wireframes Layout Mobile](assets/images/readme-media/basic-homepage-layout-mobile.png)

##### Desktop 

![Homepage Wireframes Layout Desktop](assets/images/readme-media/basic-homepage-layout-desktop.png)

#### Menu

##### Mobile

![Menu Wireframes Layout Mobile](assets/images/readme-media/basic-menu-layout-mobile.png)

##### Desktop

![Menu Wireframes Layout Desktop](assets/images/readme-media/basic-menu-layout-desktop.png)

#### Gallery

##### Mobile

![Gallery Wireframes Layout Mobile](assets/images/readme-media/basic-gallery-layout-mobile.png)

##### Desktop

![Gallery Wireframes Layout Desktop](assets/images/readme-media/basic-gallery-layout-desktop.png)

## Technologies Used 

### Languages 

1. HTML 

    * Page Markup

2. CSS

    * Styling

3. Javascript 

    * Interactive Design (Autoclosing Navigation Bar)

### Frameworks 

1. Bootstrap 

    * Used for basic styling and outline (cards, navbar, carousel, etc.).

### Libraries 

1. Pexels 

    * Used for all basic images on homepage and gallery

2. Google Fonts 

    * Font Styles     

3. Font Awesome 

    * Icons

4. Freepik

    * Title Icon 

5. PNGTree

    * Golden Thai-style Lace

### Platforms 

1. Github

    * Storing code remotely and deployment

2. Gitpod

    * IDE for project developemnt 

### Other Tools 

1. Balsamiq 

    * To develop wireframes 

2. DeepAi

    * All CurryHouse Merch Pictures

3. Compress or Die

    * Image compression and optimization 

4. W3Schools

    * HTML and CSS educational content

5. WebAIM - Contrast Checker

    * Check contrast of website

6. Online PNG Tools

    * Change color of PNG (Font Awesome Icons)

7. WebAIM - WAVE

    * Test accessibility 

8. Google - Google Developer (Lighthouse)

    * For testing

9. Google - Pagespeed 

    * For testing

10. W3C Validation Service

    * For both HTML and CSS validation 

## Credits 

1. Code Insitute - Boardwalk Games Project

    * Javascript code for autoclosing navbar on mobile and tablet devices.

2. ChatGPT

    * Writing the paragraphs on homepage of website. 

## Testing 

### Lighthouse 

#### Homepage 

##### Mobile 

![Homepage Lighthouse Mobile](assets/images/readme-media/homepage-lighthouse-mobile.png)

##### Desktop

![Homepage Lighthouse Desktop](assets/images/readme-media/homepage-lighthouse-desktop.png)

#### Menu

##### Mobile 

![Menupage Lighthouse Mobile](assets/images/readme-media/menupage-lighthouse-mobile.png)

##### Desktop

![Menupage Lighthouse Desktop](assets/images/readme-media/menupage-lighthouse-desktop.png)

#### Gallery 

##### Mobile 

![Gallerypage Lighthouse Mobile](assets/images/readme-media/gallerypage-lighthouse-mobile.png)

##### Desktop

![Gallerypage Lighthouse Desktop](assets/images/readme-media/gallerypage-lighthouse-desktop.png)

#### Contact 

##### Mobile 

![Contactpage Lighthouse Mobile](assets/images/readme-media/contactpage-lighthouse-mobile.png)

##### Desktop

![Contactpage Lighthouse Desktop](assets/images/readme-media/contactpage-lighthouse-desktop.png)

#### Merch

##### Mobile

![Merchpage Lighthouse Mobile](assets/images/readme-media/merchpage-lighthouse-mobile.png)

##### Desktop

![Merchpage Lighthouse Desktop](assets/images/readme-media/merchpage-lighthouse-desktop.png)

### HTML Validation 

#### Home

![Homepage HTML Validation](assets/images/readme-media/index-html-validation.png)

#### Menu 

![Menu HTML Validation](assets/images/readme-media/menu-html-validation.png)

#### Gallery 

![Gallery HTML Validation](assets/images/readme-media/gallery-html-validation.png)

#### Contact 

![Contact HTML Validation](assets/images/readme-media/contact-html-validation.png)

#### Merch

![Merch HTML Validation](assets/images/readme-media/merch-html-validation.png)

### CSS Validation 

![CSS Validation](assets/images/readme-media/css-validation.png)

### General Testing 

- Both forms require email for submission and arrive on success.html upon successful submission.
- All buttons function as intended.
- All social media links function as intended, lead to the correct website and open in a new tab.
- All navbar elements lead to the intended page, and menu dropdown lands above menu-section header making it clearly visible.
- Carousel autoplays and has working "previous" and "next" functions.
- CurryHouse navbar logo leads back to homepage upon clicking.
- Formdump alternative (commented in) works properly.
- Every page is responsive relative to all screen sizes.
 
### Mobile Testing

- I tested the site personally on an Android device as well as an iOS device, making sure all processes function properly including buttons, links, phone number, google maps, etc. 
- The site was sent to friends who tested on their devices of different screen sizes. 

### Desktop Testing 

- The majority of the testing occured and was optimized using Chrome. 
- I personally tested the website on Chrome, Safari, and Firefox.
- The site was tested by friends on several desktop devices with different screen sizes.

## Bugs

### Fixed Bugs 

1. Merch cards were going over given background frame.
   * Fix: Setting a max-width for smaller screen sizes.

2. Carousel was shifting size due to alternating picture sizes.
   * Fix: Adjusting and setting an overall frame size for the pictures in CSS.

3. Overlapping text and images due to golden lace png (decoration) on sides of website.
   * Fix: Adjusting padding/width for each screen size individually for a fully responsive website.

4. Non-functioning phone number link on Contact page.
   * Fix: Added "-" inbetween number sets on phone number.

5. Unequally aligned pictures on gallery page laeding to badly pixelated images after forced adjustments.
   * Fix: Cropping the images, or replacing them to have an even layout.

6. Bad contrast/accessibility issues on footer for both header and social media links
   * Fix: Created background on each element with set size and border.

7. Secondary paragraph on first section of homepage titled "Hurry for our Curry" created an unpleasing amount of text for smaller screen sizes.
   * Fix: Removed visibility of secondary paragraph for smaller screen sizes.

8. Individual menu items were difficult to read due to contrast issues between primary and secondary color.
   * Fix: Added and changed background color for each individual item to create more readable contrast.

9. Clicking on "Shareables, Curries, Sides" of "Menu" dropdown in navbar covered menu section titles.
    * Fix: Added padding top to the HTML in CSS to reveal each section title. 

10. Submit button on form in modal was not working.
    * Fix: Adjusting form element closing bracket location beneath the submit button.

11. Items in navbar "Menu" section dropdown options were not properly visible due to contrast issues between primary and secondary color.
    * Fix: Added hover element to CSS to ensure a color switch to tertiary and primary colors for better contrast.

12. Background image on website caused the site to have a poor performance on lighthouse.
    * Fix: Switch background image to background color.

13. Poor mobile lighthouse performance on certain pages with pictures.
    * Using fetchpriority (high/low) to improve LCP.

14. Label element in footer was causing validation errors on W3C.
    * Fix: Changed to a div.

15. Accessibility issues due to headers not being used sequentially.
    * Fix: Adjusted to proper sequence.

16. "Menu" in navbar was turning black on hover which looked aesthetically unpleasing and inconsistent with rest of website
    * Fix: Added "navbar-dark" bootstrap class to navbar element.

17. Contrast of primary and tertiary color was not good enough causing accessibility score to suffer.
    * Fix: Darkened the primary color enough to get a satisfactory score.

18. Call-to-action ("Follow Us on") text in footer was using up to much space on smaller screen sizes, crowding the footer
    * Removed visibility for smaller screen sizes

## Future Features

1. Using mailchimp to retrieve email information for newsletter and merch form.
2. Zoom/Enlarge carousel feature for Gallery page so users can view pictures in larger sizes.
3. Hover description effect for pictures in gallery with small complimentary text.
4. Engagement customer form with choice options on what next months "Monthly Curry" would be including options to opt-in the newsletter. 
5. Adding a customer review section.
6. 

## Deployment

* The site was deployed to Github pages. Follow steps in order to deploy:
  * From the Github repository, navigate to the Settings section
  * From the source section dropdown-menu, select "Master Branch"
  * Once master branch has been selected, the page will provide a link to the website.
