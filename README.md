![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)
---

# Pokemon Island Resort

![Mockups of Home Page on various screen sizes](assets/images/readme/mockups/mockups-home-page.png)

I am looking to create this website to showcase a fictional tropical island resort designed for Pokémon and their trainers.

The goal is to create a visually engaging and appealing platform that captures the essence of a tropical getaway for Pokémon and Pokémon enthusiasts, which allows customers to get a feel for the resort, viewing the various activities the island has to offer, seeing and learning about the trainers, and booking suites/enrolling their Pokémon in classes.

View live website [here](https://anerkiki.github.io/pokemon-island-resort/) (Hosted on GitHub pages)

---

# Table of Contents

- [Design and Planning](#design-and-planning)
  - [Objectives](#objectives)
  - [Design and Brand Identity](#design-and-brand-identity)
  - [User Experience/User Interface(UX/UI)](#user-experienceuser-interfaceuxui)
    - [Typical Customer Profile](#typical-customer-profile)
    - [User Stories](#user-stories)
  - [Wireframes](#wireframes)
  - [Typography/Fonts](#typographyfonts)
  - [Colour Scheme/Design](#colour-schemedesign)
    - [Background](#background)
    - [Colour Pallet](#colour-pallet)
    - [Font Colouring](#font-colouring)
    - [Favicon](#favicon)
    - [Header/Navbar and Footer](#headernavbar-and-footer)

- [Features](#features)
  - [Key Features](#key-features)
  - [Site Wide Features](#site-wide-features)
  - [Pages](#pages)

- [Testing](#testing)
  - [Lighthouse Performance](#lighthouse-performance)
  - [WAVE Test](#wave-test)
  - [WebAIM Contrast Checker Test](#webaim-contrast-checker-test)
  - [W3C Markup/HTML Validation Service](#w3c-markuphtml-validation-service)
  - [W3C CSS Validation Service](#w3c-css-validation-service)
  - [Manual Testing](#manual-testing)

- [Fixed Issues](#fixed-issues)
  - [Extra fixes for ease of use](#extra-fixes-for-ease-of-use)

- [Deployment](#deployment)

- [Credits](#credits)
  - [Technologies Used](#technologies-used)
  - [Images Used](#images-used)

- [Other](#other)
  - [Full Navbar Button Dropdown List](#full-navbar-button-dropdown-list)

---

# Design and Planning

---

## Objectives

The main objectives of the Pokémon Island Resort website are:

- **Showcase the Resort:** Present a vibrant, engaging overview of the fictional island resort, highlighting its unique features, activities, and accommodations for both Pokémon and their trainers.
- **Enhance User Engagement:** Create an interactive and visually appealing experience that encourages users to explore the site, learn about the trainers, and discover the variety of classes and suites available.
- **Facilitate Booking Requests and Enquiries:** Provide clear, accessible forms for users to enquire to book suites, enroll Pokémon in classes, or contact the resort, ensuring a smooth and user-friendly process.
- **Promote Accessibility and Responsiveness:** Ensure the website is fully responsive and accessible across all devices and screen sizes, offering an optimal experience for every visitor.
- **Build Trust and Credibility:** Use professional design, clear navigation, and transparent information to build user confidence in the resort and its offerings.

These objectives should guide the design, content, and functionality of the website to deliver a memorable and effective user experience.

---

## Design and Brand Identity

The website is designed to have a fun, playful feel, aiming to get potential visitors excited about everything the island has to offer. The overall aesthetic draws inspiration from tropical resorts and the vibrant world of Pokémon, using bright, cheerful colours and whimsical design elements throughout.

A key part of the design is the use of text bubbles - these are partially transparent with curved, chunky coloured borders that help them stand out against the background. On larger screens, images are also framed with thick, colourful borders, creating a cohesive and lively look. The layout is intentionally dynamic: as you scroll down the page, the text bubbles and images alternate from left to right, giving the site a playful, quirky, and engaging flow that encourages exploration.

To further enhance the playful atmosphere, I incorporated a variety of colourful images. These visuals not only make the site more visually appealing but also help communicate the resort's unique offerings and the sense of adventure awaiting visitors. The combination of bold typography, vibrant colour palette, and interactive elements (like dropdown menus and responsive layouts) ensures that the site feels welcoming and accessible to users of all ages, especially Pokémon fans and trainers looking for a fun getaway with their Pokémon.

Overall, every design choice - from the fonts and colours to the arrangement of content was made to capture the essence of a tropical Pokémon paradise, making the website both inviting and memorable.

---

## User Experience/User Interface(UX/UI)

### Typical Customer Profile

A typical customer for the Pokémon Island Resort is:

- A Pokémon owner or trainer
- Young and free spirited/eager for adventure
- Someone who enjoys traveling and exploring new destinations
- Enthusiastic about trying new and unique experiences and activities

### User Stories

- **As a new visitor:**
  - I want to quickly find out if the island has the activities and amenities I'm interested in, and feel assured that my stay will give me everything I'm looking for.

- **As a first-time user:**
  - I want the website to be easy to navigate, with a clear layout and intuitive links between pages, so I can move seamlessly through the site and find what I need without confusion and plan my trip effectively.
  
- **As a Pokémon trainer:**
  - I want to easily discover classes tailored to my Pokémon’s type and abilities, and find trainers with the right expertise to help them master their moves, develop new skills and reach their full potential.

- **As a guest or potential guest looking to contact or request to book:**
  - I want to feel assured that my message or booking request has been received and will be responded to.

- **As a past visitor:**
  - I want to easily share everything I have experienced at the resort with friends and family, including trainers I've met and activities/classes my Pokémon and I have taken part in.

---

## Wireframes

### Home Page
<details>
<summary>Click for wireframe images of Home Page</summary>

| Home Page on larger screens (laptops & larger): | Home Page on smaller screens (mobile & tablet): |
| :---: | :---: |
| ![Home Page Wireframe - large screens](assets/images/readme/wireframes/wireframe-large-home-page.png) | ![Home Page Wireframe - small screens](assets/images/readme/wireframes/wireframe-small-home-page.png) |
|  | *I removed some of the extra text bubbles that will be on <br>the finished website so that the image isn't too long* |
</details>

**Changes I made to this page**

I decided to change the 'Island Features' title to 'Our Activities' instead to be more exciting and engaging for potential customers. The term 'Island Features' felt a bit generic and didn't fully capture the fun, adventurous spirit I wanted to convey. By renaming it to 'Our Activities', the section immediately communicates that there are a variety of things to do at the resort, inviting visitors to imagine themselves taking part in these experiences.

I also changed the section title from 'Our Trainers and Pokémon' to just 'Our Trainers' to streamline the layout and make it more concise. Instead of listing both trainers and Pokémon together, I opted to highlight the trainers in the main section, and then specify which Pokémon are involved in each class within the relevant text bubbles.

I also decided to add a 'Contact Us' button to the left of the navbar menu, as thought this would be better to be more immediately visible for users of the website, and then decided to change the navbar menu button names so they were shorter and more concise (from 'About Us' to 'Home', 'Our Trainers' to 'Trainers' and 'Contact Us' to 'Contact'), taking less room and balancing better with the longer buttons on the right side 'Book a Room' and 'Book a Class'.

### Rooms (/Suites) Page
<details>
<summary>Click for wireframe images of Rooms Page</summary>

| Rooms Page on large screens (laptop & larger): | Rooms Page on smaller screens (mobile & tablet): |
| :---: | :---: |
| ![Rooms Page Wireframe - large screens](assets/images/readme/wireframes/wireframe-large-rooms-page.png) | ![Rooms Page Wireframe - small screens](assets/images/readme/wireframes/wireframe-small-rooms-page.png) |
</details>

**Changes I made to this page**

Later, I decided to change the name of this page from 'Rooms' to 'Suites', as I felt having apartments and chalets, etc. would give a more luxurious feel than simply having rooms to book.

I also decided to simplify this page to keep the images inside the boxes at both screen sizes, instead of popping out to be at the side, like I have in my Home and Classes pages, as I was only using 1 image per room, so it worked better at all screen sizes.

**Changes to both this page and the Classes Page**

I decided to change the titles in the Rooms and Classes pages, instead of having both a page title in the navbar and on the main page to the navbar page title only showing at smaller screens, and switching to a larger title bubble at larger screens, so that the titles weren't duplicated and made best use of the available screen space.

I also changed the navbar button options in these pages to reduce the 2/3 dropdown buttons on the left side of the navbar (was 'About Us' & 'Our Trainers', then 'Home', 'Trainers' and 'Contact') to just 1 normal 'Back to Home' button, and also changed the other page button on the right side to be a normal button instead of a dropdown button, leaving only dropdown buttons for the active page, which made navigating simpler and cleaner.

### Classes Page

<details>
<summary>Click for wireframe images of Classes Page</summary>

| Classes Page on large screens (laptop & larger): | Classes Page on smaller screens (mobile & tablet): |
| :---: | :---: |
| ![Classes Page Wireframe - large screens](assets/images/readme/wireframes/wireframe-large-classes-page.png) | ![Classes Page Wireframe - small screens](assets/images/readme/wireframes/wireframe-small-classes-page.png) |
</details>

### Success Page

<details>
<summary>Click for wireframe images of Success Page</summary>

| Success Page on large screens (laptop & larger): | Success Page on smaller screens (mobile & tablet): |
| :---: | :---: |
| ![Success Page Wireframe - large screens](assets/images/readme/wireframes/wireframe-large-success-page.png) | ![Success Page Wireframe - small screens](assets/images/readme/wireframes/wireframe-small-success-page.png) |
</details>

### 404 Page

<details>
<summary>Click for wireframe images of 404 Page</summary>

| 404 Page on large screens (laptop & larger): | 404 Page on smaller screens (mobile & tablet): |
| :---: | :---: |
| ![404 Page Wireframe - large screens](assets/images/readme/wireframes/wireframe-large-404-page.png) | ![404 Page Wireframe - small screens](assets/images/readme/wireframes/wireframe-small-404-page.png) |
</details>

---

## Typography/Fonts

I wanted to pick a playful and tropical font with a seaside feel for my headings, so I used **Google Fonts** to explore options. Using their preview tool, I tested the phrase "Pokémon Island Resort" - the main site title - to ensure it looked just right, especially the (é) character, which appeared odd in some fonts. I ultimately chose 'Skranji' because it perfectly captures the exotic, tropical, and beachy vibe I wanted, and even has a hint of bamboo reminiscent of island shacks.

For paragraph text, I wanted a simple, clear, and unfussy font that would complement 'Skranji' without competing for attention. Again using **Google Fonts**, I browsed sans-serif options and selected 'Roboto' for its versatility and readability across devices. Its straightforward design and spacious lettering make it easy to read, even in longer paragraphs.

---

## Colour Scheme/Design

### Background

I wanted the website's colour scheme to evoke a welcoming and relaxing island holiday feeling, so I decided on a background in either a sandy tone or a blue sea colour.

I also liked the idea of having a background image, so I began by searching on some of the free image websites for a suitable image that would set the tone for the site. After browsing through a few options, I found a [background image](#background-photo) on [Freepik](https://www.freepik.com/) that felt like it perfectly matched the tropical vibe I envisioned. I instantly loved the colours in this image (and how well they worked together) - from the golden sand background colour, the vibrant green of the palm leaves, and the range of other colours in the smaller details such as the shells and footprints - and decided to make a colour palette from these to use throughout the website for consistency.

To be able to use each of these specific colours from the image throughout the website, I used the [ColorZilla Chrome Extension](https://www.colorzilla.com/), which allowed me to pinpoint and extract exact colour codes directly from any online image. I added many different colours, then refined my choices by previewing them on the site to ensure they complemented each other and provided good contrast.

### Colour Pallet

![Colour Pallet](assets/images/readme/colour-pallet.jpg)

For future maintainability, I defined each colour as a CSS variable (e.g., `var(--colour-name)`). This approach made it easy to update the palette later if needed - changing a single variable would update the colour everywhere it was used. This was especially helpful when testing text contrast for accessibility, as I did end up changing the colour I had selected for the paragraph text when testing against the background colour of the text 'bubbles', so that it would pass all of the tests in the [add link] contrast test as it didn't originally.

I also used a couple of colours outside of this colour pallet, one which was a shade in between 2 of the colours from my colour pallet, and one which is a lighter version of the original - in places where the original colours didn't look quite right (either too light or too dark).

I used a [Color Blender tool](https://meyerweb.com/eric/tools/color-blend/#FFD8B7:FEEDDC:5:hex) to find a colour between my `--primary-sand` and `--secondary-sand` colours by inputting their 2 hex codes - producing the perfect middle tone which I named `--tertiary-sand`.

<!-- add a bit about the colour lightener I used -->

<details>
<summary>Click for Image of Color Blender showing the two colours I inputted to find midpoint colour</summary>

![Color Blender showing the two colours I inputted to find midpoint colour](assets/images/readme/tools/color-blender.png)
</details>

### Font Colouring

The only colour (in the Colour Pallet) not from the background image was the dark brown shade `#674A18`, originally `#84644B`, which I chose because all of the other colours (apart from the leaf colour) were too pale to stand out against a pale sandy background (which I used as a background for all blocks of text), and it still matches the aesthetic nicely, but doesn't compete for attention from any of the more important headers, that I want the attention to initially be drawn to.

For this reason I kept the headings (Skranji) as more colourful, in a brighter green/golden sandy colour depending on the background shade, e.g. the bolder leaf colour on a paler background and the lighter sand colour on a darker background, so that the contrast is enough to be read easily.

I tested the colours using [WebAIM Contrast Checker Test](https://webaim.org/resources/contrastchecker), and amended the colours slightly later on so that I would pass tests that I'd failed with the previous colour. [This is where I show the Contrast Test Outcomes](#webaim-contrast-checker-test) in the [Testing](#testing) section.

### Favicon

The favicon for this site is a small palm tree icon, chosen to reflect the tropical island theme of the resort. It appears in the browser tab and bookmarks, helping users quickly identify the site. The favicon was sourced from IconArchive and is free to use under an open source license. Its playful design complements the overall branding and adds a professional touch to the website.

### Header/Navbar and Footer

For the Header and Footer of the site, I decided I wanted it to have a bit of a bamboo shack feel, so started looking for images with horizontally lined up bamboo. Eventually found an image (link to bamboo image) I was happy with, but the colouring was wrong, so I decided to use an image and add a coloured overlay of one of the colours I'd decided on using before from the leaves the background image.

[edit this and add images]



I decided to use this too for the footer, as it gave the site a bit more of a 'beach shack' type feel, and looked nice and dark enough for lighter content to show up well. 

---

# Features

---

## Key Features

- **Fully Responsive at any screen size:** This includes a hero image that switches from landscape to portrait at mobile and tablet view, and text 'bubbles' that change order and location trainsitioning from different screen sizes, such as from mobile to laptop, and images which go from being inside the floating text bubbles, to outside, next to the text, in their own "bubbles".
<!-- - **Responsive Design**: Ensures the website is accessible and visually appealing on all devices, including mobile, tablet, and desktop. -->

[HeroExample]

<details>
<summary>Example at small screen sizes (tablet & mobile) - showing the image inside the text box</summary>

![Responsive Images on Small Screens](assets/images/readme/responsiveness-screenshots/responsive-images-small.png)
</details>

<details>
<summary>Example at medium screen sizes (small laptop) - showing 4 images to match the text height, now to the side of the text box</summary>

![Responsive Images on Medium Screens](assets/images/readme/responsiveness-screenshots/responsive-images-medium.png)
</details>

<details>
<summary>Example at large screen sizes (laptop) - showing 3 images to match the text height, to the side of the text box</summary>

![Responsive Images on Medium Screens](assets/images/readme/responsiveness-screenshots/responsive-images-large.png)
</details>

<details>
<summary>Example at XL screen sizes (monitor/TV) - showing 2 images to match the text height, to the side of the text box</summary>

![Responsive Images on Medium Screens](assets/images/readme/responsiveness-screenshots/responsive-images-xl.png)
</details>

The paragraphs inside the text box and images are all inside a Bootstrap flexbox, which will adjust to the screen size accordingly, and if gaps are needed, they will be evenly distributed between so there are never any large unsightly gaps, no matter the viewing dimensions.

---

## Site Wide Features

### Navbar:

This has links to all of the main pages and is always fixed to the top, so is accessible from anywhere in the website. It has links to all of the pages (with exception to the Success/Thank You page - which you access after submitting any of the forms) - [see full list](#full-navbar-button-dropdown-list)

**Larger Screen (Full Sized) Navbar:**

![Full Sized Navbar](assets/images/readme/navbar-full-size.png)

**Larger Screen (Full Sized) Navbar: with open Dropdown Menu:**

![Full Sized Navbar with open dropdown menu](assets/images/readme/navbar-full-size-dropdown.png)

Below is an interactive feature to show you the buttons in the navbar and dropdown options of each (tap the arrow to see dropdown options):

<details>
<summary>Home - (Dropdown arrow only shows when on Home Page, on other pages the button changes to 'Back to Home')</summary>
  - Our Activities<br>
  - Our Trainers<br>
  - Message Us <br>
</details>
<details>
<summary>Trainers - (Entire button with dropdown arrow only shows when on Home Page)</summary>
- Trainer Kiawe<br>
- Trainer Mallow<br>
- Trainer Lana<br>
</details>
<details>
<summary>Contact - (Entire button with dropdown arrow only shows when on Home Page)</summary>
- Message Us<br>
- Book a Class<br>
- Book a Suite<br>
- Social Media<br>
</details>
<details>
<summary>Book a Suite - (Dropdown arrow only shows when on Suites Page)</summary>
- Luxury Sea View Penthouse<br>
- Mountain View Apartment<br>
- Garden View Chalet<br>
- Arena View Apartment<br>
- Book Now!<br>
</details>
<details>
<summary>Book a Class - (Dropdown arrow only shows when on Classes Page)</summary>
- Flying Skills<br>
- Surfing & Water Skills<br>
- Beach & Dune Riding<br>
- Fire Breathing & Fire Skills<br>
- Snorkeling & Deep Sea Diving<br>
- Book Now!<br>
</details><br>

| Smaller Screen (Collapsed) Navbar: | Open Smaller Screen (Collapsed) Navbar: |
| :---: | :---: |
| ![Collapsed Navbar](assets/images/readme/navbar-collapsed.png) | ![Collapsed Navbar](assets/images/readme/navbar-collapsed-open.png) |

### Footer:

This has links to social media, and is shown at the bottom of each page, although not fixed in place over the content like the **Navbar** is

| Larger Screen Footer: | Smaller Screen Footer: |
| :---: | :---: |
| ![Full Sized Footer](assets/images/readme/footer-full-size.png) | ![Collapsed Footer](assets/images/readme/footer-collapsed.png) |

---

## Pages
***Note:*** *Pages/sections marked with **\*** can be accessed through the navbar buttons or their dropdown menu options*

**Home Page*** - Highlights the resort's unique offerings and provides a welcoming introduction.

Featuring:
- A fun and colourful **Hero Image** with small floating 'Welcome' text bubble.
- Different Navbar options depending on the screen size.
- A responsive Hero image that changes orientation at different sizes to fill the screen (portrait for mobile/tablet and landscape for laptop and larger screens)

![Mockups of Home Page on various screen sizes](assets/images/readme/mockups/mockups-home-page.png)

  - Responsive so that the center content doesn't stretch too large on XXL Screens

![The Home Page on XXL Screens](assets/images/readme/mockups/xxl-screens.png)

  - An **Activities** Section* with responsive floating text bubbles and images which multiply to up to 3, or appear inside the text boxes/bubbles at different screen sizes.
    - Image shows open 'Our Activities' dropdown menu option selected.

![Mockups of Home Page Activities Section on various screen sizes](assets/images/readme/mockups/mockups-home-page-activities.png)

  - An **Our Trainers** Section* with group image, and then individual images, descriptions, and links to their classes, which are fully responsive, and the images also multiply to up to 3, or appear inside the text boxes/bubbles at different screen sizes.*

  **Home Page Trainers Section** mockups:
  You can get to this section of the Home Page by clicking the 'Trainers' button, or selecting the 'Our Trainers' option in the Home dropdown menu.
  - As you can see, when the 'Trainers' button is hovered over, there is a hover effect that changes the colouring/background, like in the dropdown menus.
![Mockups of Home Page Trainers Section on various screen sizes](assets/images/readme/mockups/mockups-home-page-trainers.png)

  - A **Contact Form*** to get in touch, with an adjustable message box, which links to the **Success/Thank You Page** when correctly submitted.

  **Home Page Contact Form** mockups showing one of the dropdown menu options that directs there from the Home button:<br>
*(you can also use the Contact button or 'Send Us a Message' option in the Contact dropdown menu)*
![Mockups of Home Page Contact Form on various screen sizes](assets/images/readme/mockups/mockups-home-page-form.png)

---

**Suites Page*** - Lists the suites, complete with descriptions and images, and also has a booking request form.

Featuring:
- A large bubble **Page Title** which disappears and is instead incorporated into the navbar on smaller (mobile) devices.
- **4 Suite Options*** with images, descriptions, [[[-----links to nearby activities??----]]] and a 'Book Now' button, which links directly down to the Booking Form at the bottom of the page.

  **Suites Page** mockups:
  - As you can see the selected page (Suites) is underlined on the navbar button to show that this is the current page, and the dropdown menu arrow has appeared beside it
![Mockups of Suites Page on various screen sizes](assets/images/readme/mockups/mockups-suites-page.png)

  - A Suite **Booking Form*** with dropdown menu to pick a suite to enquire about, which link to the **Success/Thank You Page** when correctly submitted.

  **Suites Page Enquiry Form** mockups showing open dropdown menu with Suites 'Book Now' option selected:
![Mockups of Suites Page Enquiry Form on various screen sizes](assets/images/readme/mockups/mockups-suites-page-form.png)

---

**Classes Page*** - Lists the classes, complete with descriptions, images and trainers teaching the classes and has a booking request form.

Featuring:
- **5 Class Options*** which are all fully responsive, so the image is inside the description box in a mobile/tablet screen, and then on larger screens the images pop out of the text box and appear beside, increasing/decreasing from 1 to 4 depending on the screen size, to match the height of the description bubble. As well as related images, these all have titles, descriptions, which trainer/trainers that will take the class (including a link to the specific trainer on the main home page), and a 'Book Now' button, which links directly down to the Booking Form at the bottom of the page.

  **Classes Page** mockups:
![Mockups of Classes Page on various screen sizes](assets/images/readme/mockups/mockups-classes-page.png)

  - A Class **Booking Form*** with dropdown menu to pick a suite to enquire about, which link to the **Success/Thank You Page** when correctly submitted.

  **Classes Page Enquiry Form** mockups showing open dropdown menu with Classes 'Book Now' option selected:
  <!-- remove this and all others like it - combine with bulletpoints/text above -->
![Mockups of Classes Page Enquiry Form on various screen sizes](assets/images/readme/mockups/mockups-classes-page-form.png)

---

**Success/Thank You Page** – Confirms successful form submission with a friendly thank you message and offers links to explore more of the site.

Feauturing:
- A large bubble **Page Title** saying 'Thank You' which disappears and is instead incorporated into the navbar on smaller (mobile) devices.
- A message of gratitude to the customer, including links to other places on the website that they can look at.
- An image of all of the Trainers/Team

  **Success Page** mockups:
![Mockups of Success Page on various screen sizes](assets/images/readme/mockups/mockups-success-page.png)

---

**404 Page** - A custom error page with a playful message and links to help users return to the main sections of the site.

Featuring:
- Links back to different pages in a fun paragraph of text.

![Mockups of 404 Page on various screen sizes](assets/images/readme/mockups/mockups-404-page.png)

---

# Testing

---

## Lighthouse Performance

When testing my website with Lighthouse, I encountered an issue, which I fixed (fixed scores below) which affected the 'Best Practices' score, as shown below:

<details>
<summary>Click for old test results</summary>

![Issue Description](assets/images/readme/testing/lighthouse/lighthouse-best-practices-issue.png)
</details><br>

This was due to `h1` elements being used within a `section` element, so by changing all the `h2`s to `h3`s and `h1`s in my `section`s to `h2`s, this fixed the issue, giving me the scores below for each of the pages:

Home Page:

![Home Page Lighthouse](assets/images/readme/testing/lighthouse/lighthouse-home-page.png)

Suites Page:

![Suites Page Lighthouse](assets/images/readme/testing/lighthouse/lighthouse-suites-page.png)

Classes Page:

![Classes Page Lighthouse](assets/images/readme/testing/lighthouse/lighthouse-classes-page.png)

Success Page:

![Success Page Lighthouse](assets/images/readme/testing/lighthouse/lighthouse-success-page.png)

404 Page:

![404 Page Lighthouse](assets/images/readme/testing/lighthouse/lighthouse-404-page.png)

---

## WAVE Test

---

## WebAIM Contrast Checker Test

I changed the original dark brown colour I had chosen for my paragraph text colour after testing from `#84644B` to `#674A18` due to the original colour not passing all of the contrast checker tests on the [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) website, and I wanted my website to be as accessible as possible for all users.

Below is an image of the new, slightly darker brown colour passing all of the tests on this website:

![Checking Contrast of text colour and background](assets/images/readme/testing/webaim-contrast-checker-pass.png)

[WebAIM Contrast Checker link showing the 2 colours I compared](https://webaim.org/resources/contrastchecker/?fcolor=674A18&bcolor=FEEDDC)

<!-- maybe put these in hidden dropdown? -->
| Original text colour which didn't pass the AAA test: | Original Colour Pallet before testing: |
| :---: | :---: |
| ![Checking Contrast of text colour and background](assets/images/readme/testing/webaim-contrast-checker-fail.png) | ![Old Colour Pallet](assets/images/readme/colour-pallet-original.jpg) |

---

## W3C Markup/HTML Validation Service
<!-- (HTML and readme?) -->

---

## W3C CSS Validation Service

---

## Manual Testing

<!-- Look at BrowserStack(?) -->

**(Expected Outcome/Did it pass?)**

  - Navigation Links
  *What I'm testing:*
  Do all links navigate to the correct page/section?
  Do all buttons lead to the intended destination?
  - Forms
  *What I'm testing:*
  Does all the validation work, so the form can't be submitted without all required fields filled and with valid/the correct characters?
  Once submitted does it navigate to the success.html page?
  - External Links (Social Media Icons)
  Do they all lead to the intended website?
  Do they open in a new tab?
  - Responsive Design
  Does the website adapt as intended at all screen sizes?
  Does the burger menu work as it should, including closing when a link has been clicked?

**User Stories** (?)

---

# Fixed Issues
<!-- Problems/Challenges/Bugs -->

### VS Code Extension *'Prettier'* adding unneccessary closing tags

<details>
<summary>Issue & Solution:</summary>

**Issue:** As part of the course material, I installed a code refactoring extension called 'Prettier' in VS Code, but had issues with this adding unneccessary closing tags (`/>`) to all of the self-closing elements, such as `meta` and `img`.

These were added every time I formatted my pages, and resulted in errors in the [W3C Testing](#w3c-markuphtml-validation-service) stage, wasting time with having to remove each time I formatted.

**Solution:** I uninstalled this extension and opted to use the default formatter, which worked a lot better.
</details>

---

### Unable to change/remove background of Navbar
<details>
<summary>Issue & Solution:</summary>

**Issue:** When I had added the bamboo background image to the header section, I noticed the navbar from Bootstrap I had added within this had it's own white colour background, which stopped the image being shown as a background for the whole thing, even if I tried to change it to transparent using my CSS stylesheet.

![Navbar background being overridden by Bootstrap](assets/images/readme/issue/issue-removing-navbar-background.png)

**Solution:** I checked using Devtools and noticed that the background colour was being set my a bootstrap scss file, and that this was set as `!important;` so would override any background I added. Looking further I spotted it was being added because of the `bg-body-tertiary` class, so once I removed this, the background image covered the whole title & nav section, including the navbar.
![Code causing the issue](assets/images/readme/issue/issue-removing-navbar-background-code.png)
</details>

---

### Bootstrap's Active page not visible

<details>
<summary>Issue & Solution:</summary>

**Issue:** When customising the navbar from bootstrap, I changed the font/button border/hover colours, which meant the active page colour wasn't visible anymore, but I still wanted users to be able to see clearly from a glance which page they were on just from looking at the navbar.

**Solution:** I decided to add in my own effect, by adding an underline to the button text of the current page.

I did this by ...

</details>

---

### Page Title inside Navbar not appearing centralised

<details>
<summary>Issue & Solution:</summary>

**Issue:** Because of the burger icon being to the right of the same navbar section that the page title appears in on smaller screens (mobile and tablet), the title wasn't appearing centralised, it was being pushed too far to the left.

**Solution:** I fixed this by adding padding to the left of the page title which matched the width of the burger icon, centralising it correctly to match the title above.
I added a class to the page title, and added `padding-left` of the same width of the burger icon.

| Page Title too far to the left: | Page title centralised with left-padding added: |
| :---: | :---: |
| ![Page Title with no padding](assets/images/readme/issue/page-title-center/issue-page-title-no-padding.png) | ![Page Title centralised with left padding](assets/images/readme/issue/page-title-center/issue-page-title-left-padding.png) |
```css
.page-title {
    padding-left: 28.4px;
}
```
This also had to be amended to match the burger icon's new width on a larger screen as I added padding to the x-axis at the mobile to tablet breakpoint. I checked the width of the burger icon at each breakpoint using Chrome DevTools (shown below).
| Smaller burger icon without added padding in the x-axis: | Smaller burger icon with added padding in the x-axis: |
| :---: | :---: |
| ![Smaller burger icon without added padding in the x-axis](assets/images/readme/issue/page-title-center/issue-burger-icon-small.png) | ![Smaller burger icon with added padding in the x-axis](assets/images/readme/issue/page-title-center/issue-burger-icon-large.png) |
```css
@media (max-width: 426px) {
    .page-title {
    padding-left: 36px;
    }

    /* Burger Icon (makes smaller) */
    .burger-icon {
        padding: 0 0.5rem 0.15rem 0.5rem;
    }
}
```
</details>

---

### Dropdown Menu in navbar being cut off

<details>
<summary>Issue & Solution:</summary>

**Issue:**  When the right dropdown menu is opened, some of the menu text is cut off by the edge of the screen. This occurs because the dropdown button is positioned close to the screen edge, and the menu options are too long to fit within the visible area. By default, Bootstrap dropdown menus are left-aligned. If a dropdown is near the right edge and the menu options are lengthy, the menu will overflow and appear clipped, making some text not fully visible.

![Dropdown Menu being cut off](assets/images/readme/issue-right-align1.png)

**Solution:**  After consulting the Bootstrap documentation, I discovered that adding the `dropdown-menu-end` class to the same element as `dropdown-menu` changes the alignment of the dropdown menu to the right, instead of the default left alignment. This prevents the menu from being cut off at the edge of the screen. I applied this fix only to the two rightmost navbar dropdown menus, while keeping the left-side dropdowns left-aligned. This approach maintains visual consistency across the navbar and avoids potential overflow issues on either side.

![Dropdown Menu fixed](assets/images/readme/issue-right-align2.png)

Later, I also updated the navbar alignment to better match the rest of the site's layout by changing `container-fluid` to `container` in the navbar, which added more space between the buttons and edges of the screen and helped the navbar appear more consistent with the more centralised page content.

</details>

---

### Background Image too zoomed on pages with more content (especially on mobile view)

<details>
<summary>Issue & Solution:</summary>

**Issue:**
When deploying the website, I noticed that the background image whilst on main was far too zoomed in when on mobile/tablet view and looked pixelated

I fixed this by applying the background image as a background to each section instead

This results in multiple images for each section, but none too high so that it ends up too zoomed in



The background image I used as a background was being stretched too much for pages where there was a lot of content, especially on mobile screens where boxes being stacked on top of each other made the page longer still, which resulted in the background image being very zoomed in, making it look pixelated, which didn't look good.

|  |  |
| :---: | :---: |
| ![Image showing background image appearing too zoomed in and pixelated](assets/images/readme/issue/background-too-zoomed/issue-background-too-zoomed-before.png) | ![Image showing background image appearing too zoomed in and pixelated](assets/images/readme/issue/background-too-zoomed/issue-background-too-zoomed-before-two.png) |

**Solution:** I resolved this issue by splitting the content into seperate sections, and adding the background image to each section, instead of having all of the content in one huge section. I found that having around 2 of the text boxes in each worked well on all screen sizes, eliminating the need to change the amount of sections depending on screen sizes, which I did consider, but would have added a lot more code and been more complex than necessary.

**New Issue**

When doing this I encountered an issue, in which the image didn’t spread all the way to the edges of the screen, and we were left with quite a large gap around the edges at certain screen sizes

![Background image not stretched to edges of screen](assets/images/readme/issue/background-too-zoomed/issue-background-not-covering.png)

**Solution**

I used Chrome DevTools to inspect this, and by removing the container class realised this took away the gap around the edges.

I attempted to fix this by changing the section with the container attribute to a div, and wrapping this div inside a section.

I also moved the id from one of the divs further down to this new section tag, so that it was clearer which section was which

Before:

```html
 <!-- Island Features -->
        <section class="container m-4 mx-auto">
            <div class="row justify-content-center">
            
                <div class="col-12 text-center title-bubble" id="our-island">
                    <h2 class="display-4 floating-section title-bubble-text">Our Island</h2>
                </div>

                <article class="col-12 col-lg-5 text-center floating-section p-4">
                    <h2 class="display-6">Island Feature</h2>
                    <p class="lead">Our resort is nice!</p>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam maxime laboriosam,
                        quae dolores voluptate nisi sed cumque cupiditate tenetur veniam beatae magnam iure. Quo, nam?
                        Fugit, laboriosam aperiam. Accusantium,&nbsp;debitis.</p>
                </article>
```

After:

```html
<!-- Our Island & Features Section -->
    <section id="our-island">
        <div class="container m-4 mx-auto">
            <div class="row justify-content-center">

                <div class="col-12 text-center title-bubble">
                    <h2 class="display-4 floating-section title-bubble-text">Our Island</h2>
                </div>

                <article class="col-12 col-lg-5 text-center floating-section p-4">
                    <h2 class="display-6">Island Feature</h2>
                    <p class="lead">Our resort is nice!</p>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam maxime laboriosam,
                        quae dolores voluptate nisi sed cumque cupiditate tenetur veniam beatae magnam iure. Quo, nam?
                        Fugit, laboriosam aperiam. Accusantium,&nbsp;debitis.</p>
                </article>
```
<!-- remove this from notion -->
</details>

---

### Added gaps interfering with Bootstrap flexbox spacing

<details>
<summary>Issue & Solution:</summary>

**Issue:** After I decided to add universal gaps and spacing between all items in my text bubbles (I added `gap: 20px;` to the `.row` class), I noticed that some of the bootstrap flexbox items weren't appearing correctly, for example. the input boxes in my forms didn't appear side by side anymore, even though the column sizes didn't add up to more than 12.

![Image showing 2 col-6 text boxes not appearing in line](assets/images/readme/issue/added-gaps-interfering-with-flex/columns-appearing-wrong.png)

**Solution:** To fix this issue I changed the column size numbers (eg. `col-6`) to numbers that added up to 11 instead of 12 per row, to account for the added gap, so instead of 2 `col-6`s in a row I changed it to `col-6` and `col-5` or 2 `col-5`s. This fixed the issue, and after altering the other text boxes to match these new sizes, the forms looked great again.
</details>

---

### Issue Title

<details>
<summary>Issue & Solution:</summary>

**Issue:**

**Solution:**

</details>

---


### Issue Title

<details>
<summary>Issue & Solution:</summary>

**Issue:**

**Solution:**

</details>

---

### Text box/bubble height mismatched with height of images

**Issue:** At certain screen sizes, the text box was either too long or too short compared to the adjacent images, causing unwanted gaps, either between images or within the text box.

**Solution:** I solved this problem by setting some of the images to appear/disappear depending on the size of the screen, using bootstrap classes.

```html
CODE HERE
```

I also added space between images with [code] so that the gap was dispersed between each image, making it appear less, rather than showing as an obvious gap at the bottom.

I then did the same to the titles, paragraphs and buttons in the text boxes/bubbles by adding `d-flex flex-column justify-content-evenly` to all article elements which contain the headers and paragraphs so that the content is aligned correctly vertically, with even gaps at the top and bottom, rather than just squashed to the top if the box is too big.

| | |
| :---: | :---: |
| ![Text box gaps before](assets/images/readme/issue/textbox-and-images-gaps/text-gaps-before.png) | [Text box gaps after](assets/images/readme/issue/textbox-and-images-gaps/text-gaps-after.png) |

I chose `justify-content-evenly` instead of `center`, as it worked better to spread the items better, leaving less gaps, and then by adding/removing images at certain screen sizes I made it so that there were never any noticeable gaps, no matter the screen size.

[Justify Content explanation on Bootstrap](assets/images/readme/issue/textbox-and-images-gaps/justify-content.png)

**New Issue**

After I had done this, I noticed that the buttons and text above didn't look as good spread out, so I added a div around these 2 so that the gap wouldn't affect inbetween these.

[Text box gaps before](assets/images/readme/issue/textbox-and-images-gaps/added-jc-evenly-before-divs.png)

<!-- add after image and put in table -->

---

## Extra fixes for ease of use


### Added Universal margins/padding/gaps instead of to each individual element

<details>
<summary>Issue & Solution:</summary>

**Issue:** [add]

**Solution:** [add]

</details>

---

### Fix Title

<details>
<summary>Issue & Solution:</summary>

**Issue:**

**Solution:**

</details>

---

### Fix Title

<details>
<summary>Issue & Solution:</summary>

**Issue:**

**Solution:**

</details>

---


### Fix Title

<details>
<summary>Issue & Solution:</summary>

**Issue:**

**Solution:**

</details>

---

# Deployment
<!-- Maybe make numbered list -->
- Firstly, I made a new repository in GitHub from the code institute template, with my chosen name for my project, which is `pokemon-island-resort`
    - I ensured that this was in snake case so it would all be coordinated.
- Once I had made a new repository, in *File Explorer* on my local device, I then navigated to the folder I wanted my project to be in, and right clicked to ‘Open in Terminal’

![image](assets/images/readme/deployment-creating.png)

- Then, after making sure I was still in the correct folder, I typed `git clone [link copied from GitHub]`

![image](assets/images/readme/deployment-terminal1.png)

![image](assets/images/readme/deployment-terminal2.png)

- Now a new folder has been added which is linked to the GitHub repository

![image](assets/images/readme/deployment-folder.png)

- I then opened my new folder in VS Code, added some of the starter files such as `index.html` and the `assets` & `css` folders, linked to bootstrap, font awesome, and linked my own custom css sheets, where I also added in my chosen fonts from google fonts, and added colours and fonts to the stylesheet to make sure these were all linked correctly.
- I then added, committed and pushed the changes to my GitHub repository.

![Image of the commits on Git](assets/images/readme/deployment-commits.png)

---

# **Credits**

# Technologies Used

### [GitHub](https://github.com/):
- GitHub has been used to store this project.

### [VScode](https://code.visualstudio.com/):
- I used this as my IDE to code and develop this website and to push to GitHub.

### [Google Fonts](https://fonts.google.com/):
- I used this to find and create an import url so that I could use by 2 chosen fonts - [Skranji](https://fonts.google.com/specimen/Skranji) (Designed by Neapolitan) and [Roboto](https://fonts.google.com/specimen/Roboto) (Designed by Christian Robertson, Paratype, & Font Bureau).

### [Font Awesome](https://fontawesome.com/):
- I used this to add icons to the website so that they could be coloured to match my design, specifically in the navbar (for the burger icon and dropdown menu arrows) and for the social media links in the footer.

### [Bootstrap](https://getbootstrap.com/):
- I used this to design my navbar and as a flexbox/grid in my navbar, main content and forms.

### [Notion](https://www.notion.com/)
- I used this to write up ideas, to do lists/issues that needed fixing, and paste screenshots, images and their links, etc.

### [ColorZilla (Chrome Extension)](https://www.colorzilla.com/)
- I used this to pinpoint exact colour codes from images etc on websites.

### [Color Blender](https://meyerweb.com/eric/tools/color-blend/#:::hex)
- I used this website to find a colour between my background and highlight colours using their hex codes.

### [Balsamiq](https://balsamiq.com/)
- I used this to make my wireframes.

<!-- TO ASK MENTOR -->
<!-- Should I also add testing applications such as WebAIM Contrast Checker here or leave just in Testing(?) -->

---

# Images Used

## Site Wide

### [Freepik](https://www.freepik.com/)
- I used this website for page background image and Bamboo background used in Header and Footer.

#### **Background Image for main sections**: 
<details>
<summary>*click to view image*</summary>

![Background image with sand and palm leaves](./assets/images/site-wide/beach-background.jpg)

</details>

[Freepik - Tropical Summer Design](https://www.freepik.com/free-vector/tropical-summer-design_4413927.htm)

#### **Bamboo Image used as Header and Footer background**:
<details>
<summary>*click to view image*</summary>

![Bamboo image from Header and Footer](assets/images/site-wide/bamboo-background.jpg)

</details>

[Freepik - Bamboo Backdrop](https://www.freepik.com/free-photo/bamboo-patterned-curtain-textured-backdrop_15653469.htm)

---

### [IconArchive](https://www.iconarchive.com/)
- I used this website to find my favicon.

#### **Favicon**:
<details>
<summary>*click to view image*</summary>

![Palm Tree Favicon](./assets/images/site-wide/palm.ico)

</details>

[IconArchive - Palm Tree Icon](https://www.iconarchive.com/show/noto-emoji-animals-nature-icons-by-google/22331-palm-tree-icon.html)

---

## Home Page

### **Hero Images**:
Landscape Image - (Laptop and larger screens):

<details>
<summary>*click to view image*</summary>

![Palm Tree Favicon](./assets/images/hero/hero-landscape.jpeg)

</details>

[Landscape Hero Image from Pokémon Sun and Moon Game (Nintendo)](https://www.redbull.com/au-en/new-game-releases-november-2016)

<!-- [Landscape Hero Image from Pokémon Sun and Moon Game (Nintendo)](https://img.redbull.com/images/c_crop,x_0,y_0,h_1498,w_2999/c_fill,w_1700,h_765/q_auto,f_jpg/redbullcom/2016/10/31/1331826758607_2/scene-from-the-new-pok%C3%A9mon-sun-and-moon-game-for-nintendo-ds3) -->

Portrait Image - (Mobile and Tablet screens):

<details>
<summary>*click to view image*</summary>

![Palm Tree Favicon](./assets/images/hero/hero-portrait.jpg)

</details>

[Portrait Image illustrated by [Saro Orfali](https://x.com/saro__black)](https://www.nintendo-difference.com/news/pokemon-go-le-debut-de-la-saison-sous-un-meme-ciel-et-les-evenements-de-juin-2024-detailles/)
---

## Suites Page

**Sea View Penthouse**

[](link)

**Mountain View Apartment**

https://www.google.com/imgres?q=pokemonmountains&imgurl=https%3A%2F%2Fw0.peakpx.com%2Fwallpaper%2F532%2F280%2FHD-wallpaper-pokemon-flygon-waterfall-mountains-trees-anime.jpg&imgrefurl=https%3A%2F%2Fwww.peakpx.com%2Fen%2Fhd-wallpaper-desktop-vqazu&docid=diiFN9gyBwUtKM&tbnid=V_goH3H8_tnxwM&vet=12ahUKEwjSq-n0rM6NAxUuX0EAHR8BLLEQM3oECH8QAA..i&w=800&h=435&hcb=2&ved=2ahUKEwjSq-n0rM6NAxUuX0EAHR8BLLEQM3oECH8QAA

<!-- Tidied up - check is working before replacing link above -->
<!-- [Flygon Waterfall Mountains](https://www.peakpx.com/en/hd-wallpaper-desktop-vqazu) -->

**Garden View Chalet**

[](link)

**Battle Arena Apartment**

[Battle Arena Charizard and Pikachu image/Bulbapedia - Kiawe's Charizard using Aerial Ace](https://bulbapedia.bulbagarden.net/wiki/User:BigDocFan/List_of_moves_used_by_major_characters_Pok%C3%A9mon_in_Sun_%26_Moon)

https://archives.bulbagarden.net/wiki/File:Kiawe_Charizard_Aerial_Ace.png

![Photo Licensing](assets/images/readme/battle-arena-licensing.png)

---

## Classes Page

**Flying Skills Class**

[](link)
[](link)
[](link)

**Surfing & Water Skills Class**

[](link)
[](link)
[](link)

**Beach & Dune Riding Class**

[](link)
[](link)
[](link)

**Fire Breathing & Fire Skills Class**

[](link)
[](link)
[](link)
[](link)

**Snorkeling & Deep Sea Diving Class**

[](link)
[](link)
[](link)
[](link)

---

# Other

## Future Enhancements

- Implement interactive maps to help users navigate the resort.
- Include a gallery page to showcase more images of the resort and its amenities.

---

### Full Navbar Button Dropdown List

  - **Home** Button - (Dropdown arrow only shows when on Home page, on Classes and Suites pages, the button changes to **Back to Home**)
    - Dropdown Option 1 - **Our Activities**
    - Dropdown Option 2 - **Our Trainers**
    - Dropdown Option 3 - **Message Us**
  - **Trainers** - (Entire button with dropdown arrow only shows when on Home page)
    - Dropdown Option 1 - **Trainer Kiawe**
    - Dropdown Option 2 - **Trainer Mallow**
    - Dropdown Option 3 - **Trainer Lana**
  - **Contact** - (Entire button with dropdown arrow only shows when on Home page)
    - Dropdown Option 1 - **Message Us**
    - Dropdown Option 2 - **Book a Class**
    - Dropdown Option 3 - **Book a Suite**
    - Dropdown Option 4 - **Social Media**
  - **Book a Suite** - (Dropdown arrow only shows when on Suites page)
    - Dropdown Option 1 - **Luxury Sea View Penthouse**
    - Dropdown Option 2 - **Mountain View Apartment**
    - Dropdown Option 3 - **Garden View Chalet**
    - Dropdown Option 4 - **Arena View Apartment**
    - Dropdown Option 5 - **Book Now!**
  - **Book a Class** - (Dropdown arrow only shows when on Classes page)
    - Dropdown Option 1 - **Flying Skills**
    - Dropdown Option 2 - **Surfing & Water Skills**
    - Dropdown Option 3 - **Beach & Dune Riding**
    - Dropdown Option 4 - **Fire Breathing & Fire Skills**
    - Dropdown Option 5 - **Snorkeling & Deep Sea Diving**
    - Dropdown Option 6 - **Book Now!**