![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)
---

# Pokemon Island Resort

![Mockups of Home Page on various screen sizes](assets/images/readme/mockups/mockups-home-page.png)

## Introduction

---

I am looking to create this website to showcase a fictional tropical island resort designed for Pokémon and their trainers.

The goal is to create a visually engaging and appealing platform that captures the essence of a tropical getaway for Pokemon and Pokémon enthusiasts, which allows customers to get a feel for the resort, viewing the various activities the island has to offer, seeing and learning about the trainers, and booking suites/enrolling their Pokémon in classes.

View live website [here](https://anerkiki.github.io/pokemon-island-resort/) (Hosted on GitHub pages)



---

# Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
  - [Frameworks, Programs, and Libraries](#frameworks-programs-and-libraries)
- [Features](#features)
  - [Key Features](#key-features)
  - [Site Wide Features](#site-wide-features)
  - [Pages](#pages)
- [Design and Planning](#design-and-planning)
  - [User Experience/User Interface(UX/UI)](#user-experienceuser-interfaceuxui)
  - [Design and Brand Identity](#design-and-brand-identity)
  - [Wireframes](#wireframes)
  - [Typography](#typography)
  - [Colour Scheme](#colour-scheme)
- [Testing](#testing)
- [Bugs](#bugs)
- [Deployment](#deployment)
- [Credits](#credits)
- [Other](#other)

---

# Technologies Used

---

### Frameworks, Programs, and Libraries

- [GitHub](link):
  - GitHub has been used to store this project.

- [VScode](link):
  - I used this as my IDE to code and develop this website and to push to GitHub.

- [Google Fonts](link):
  - I used this to find and create an import url so that I could use by 2 chosen fonts in the project.

- [Font Awesome](link):
  - I used this to add icons to the website so that they could be coloured to match my design, specifically in the navbar (for the burger icon and dropdown menu arrows) and for the social media links in the footer.

- [Bootstrap](link):
  - I used this to design my navbar and as a flexbox/grid in my navbar, main content and forms.

- [Notion](link)
  - I used this to write up ideas, to do lists/issues that needed fixing, and paste screenshots, images and their links, etc.

#### **Color Tools**:

<!-- add this to the design and planning colour pallet section? -->

- [ColorZilla - Chrome Extension](https://www.colorzilla.com/)
  - I used this to pinpoint exact colour codes from images etc on websites.

- [Color Blender](https://meyerweb.com/eric/tools/color-blend/#:::hex)
- [Color Blender](https://meyerweb.com/eric/tools/color-blend/#FFD8B7:FEEDDC:5:hex)
  - I used this website to find a colour between my background and highlight colours using their hex codes.

![Color Blender showing the two colours I inputted to find midpoint](assets/images/readme/color-blender.png)

---

## Features

### Key Features

- **Fully Responsive at any screen size:** This includes a hero image that switches from landscape to portrait at mobile and tablet view, and text 'bubbles' that change order and location trainsitioning from different screen sizes, such as from mobile to laptop, and images which go from being inside the floating text bubbles, to outside, next to the text, in their own "bubbles".

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

### Site Wide Features

#### Navbar:

This has links to all of the main pages and is always fixed to the top, so is accessible from anywhere in the website. It has links to all of the pages (with exception to the Success/Thank You page - which you access after submitting any of the forms) - [see full list](#full-navbar-button-dropdown-list)

Larger Screen (Full Sized) Navbar:

![Full Sized Navbar](assets/images/readme/navbar-full-size.png)

Below is an interactive feature to show you the buttons in the navbar and dropdown options of each (tap the arrow to see dropdown options):

<details>
<summary>Home - (Dropdown arrow only shows when on Home Page, on Classes and Suites Pages, the button changes to 'Back to Home')</summary>
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

Smaller Screen (Collapsed) Navbar:

![Collapsed Navbar](assets/images/readme/navbar-collapsed.png)

Open Smaller Screen (Collapsed) Navbar:

![Collapsed Navbar](assets/images/readme/navbar-collapsed-open.png)

#### Footer:

This has links to social media, and is shown at the bottom of each page, although not fixed in place over the content like the **Navbar** is

Larger Screen Footer:

![Full Sized Footer](assets/images/readme/footer-full-size.png)

Smaller Screen Footer:

![Collapsed Footer](assets/images/readme/footer-collapsed.png)

---

### Pages
***Note:*** *Pages/sections marked with **\*** can be accessed through the navbar buttons or their dropdown menu options*

- **Home Page*** featuring:
  - A fun and colourful **Hero Image** with small 'Welcome' text bubble.
  - Different Navbar options depending on the screen size.
  - A responsive Hero image that changes orientation at different sizes to fill the screen (portrait for mobile/tablet and landscape for laptop +)

![Mockups of Home Page on various screen sizes](assets/images/readme/mockups/mockups-home-page.png)

  - Responsive so that it doesn't stretch to large on XXL Screens
![The Home Page on XXL Screens](assets/images/readme/mockups/xxl-screens.png)

  - An **Activities** Section* with responsive "floating" text bubbles and images which multiply to up to 3, or appear inside the text boxes/bubbles at different screen sizes.
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

- **Suites Page*** featuring:
  - A large bubble **Page Title** which disappears and is instead incorporated into the navbar on smaller (mobile) devices.
  - **4 Suite Options*** with images, descriptions, [[[links to nearby activities??]]] and a 'Book Now' button, which links directly down to the Booking Form at the bottom of the page.

  **Suites Page** mockups:
  - As you can see the selected page (Suites) is underlined on the navbar button to show that this is the current page, and the dropdown menu arrow has appeared beside it
![Mockups of Suites Page on various screen sizes](assets/images/readme/mockups/mockups-suites-page.png)

  - A Suite **Booking Form*** with dropdown menu to pick a suite to enquire about, which link to the **Success/Thank You Page** when correctly submitted.

  **Suites Page Enquiry Form** mockups showing open dropdown menu with Suites 'Book Now' option selected:
![Mockups of Suites Page Enquiry Form on various screen sizes](assets/images/readme/mockups/mockups-suites-page-form.png)

- **Classes Page*** featuring:
  - **5 Class Options*** which are all fully responsive, so the image is inside the description box in a mobile/tablet screen, and then on larger screens the images pop out of the text box and appear beside, increasing/decreasing from 1 to 4 depending on the screen size, to match the height of the description bubble. As well as related images, these all have titles, descriptions, which trainer/trainers that will take the class (including a link to the specific trainer on the main home page), and a 'Book Now' button, which links directly down to the Booking Form at the bottom of the page.

  **Classes Page** mockups:
![Mockups of Classes Page on various screen sizes](assets/images/readme/mockups/mockups-classes-page.png)

  - A Class **Booking Form*** with dropdown menu to pick a suite to enquire about, which link to the **Success/Thank You Page** when correctly submitted.

  **Classes Page Enquiry Form** mockups showing open dropdown menu with Classes 'Book Now' option selected:
![Mockups of Classes Page Enquiry Form on various screen sizes](assets/images/readme/mockups/mockups-classes-page-form.png)

- **Success/Thank You Page** feauturing:
  - A large bubble **Page Title** saying 'Thank You' which disappears and is instead incorporated into the navbar on smaller (mobile) devices.
  - A message of gratitude to the customer, including links to other places on the website that they can look at.
  - An image of all of the Trainers/Team

  **Success Page** mockups:
![Mockups of Success Page on various screen sizes](assets/images/readme/mockups/mockups-success-page.png)

- **404 Page** featuring:
  - Links back to different pages in a fun paragraph of text.

![Mockups of 404 Page on various screen sizes](assets/images/readme/mockups/mockups-404-page.png)

---

## Design and Planning

**Objectives**

The main objectives of the Pokemon Island Resort website are:

- **Showcase the Resort:** Present a vibrant, engaging overview of the fictional island resort, highlighting its unique features, activities, and accommodations for both Pokémon and their trainers.
- **Enhance User Engagement:** Create an interactive and visually appealing experience that encourages users to explore the site, learn about the trainers, and discover the variety of classes and suites available.
- **Facilitate Booking Requests and Inquiries:** Provide clear, accessible forms for users to enquire to book suites, enroll Pokémon in classes, or contact the resort, ensuring a smooth and user-friendly process.
- **Promote Accessibility and Responsiveness:** Ensure the website is fully responsive and accessible across all devices and screen sizes, offering an optimal experience for every visitor.
- **Build Trust and Credibility:** Use professional design, clear navigation, and transparent information to build user confidence in the resort and its offerings.

These objectives should guide the design, content, and functionality of the website to deliver a memorable and effective user experience.

---

**Design and Brand Identity**

The website is designed to have a fun, playful feel, aiming to get potential visitors excited about everything the island has to offer. The overall aesthetic draws inspiration from tropical resorts and the vibrant world of Pokémon, using bright, cheerful colours and whimsical design elements throughout.

A key part of the design is the use of text bubbles - these are partially transparent with curved, chunky colored borders that help them stand out against the background. On larger screens, images are also framed with thick, colorful borders, creating a cohesive and lively look. The layout is intentionally dynamic: as you scroll down the page, the text bubbles and images alternate from left to right, giving the site a playful, quirky, and engaging flow that encourages exploration.

To further enhance the playful atmosphere, I incorporated a variety of colorful images. These visuals not only make the site more visually appealing but also help communicate the resort's unique offerings and the sense of adventure awaiting visitors. The combination of bold typography, vibrant color palette, and interactive elements (like dropdown menus and responsive layouts) ensures that the site feels welcoming and accessible to users of all ages, especially Pokémon fans and trainers looking for a fun getaway with their Pokémon.

Overall, every design choice - from the fonts and colours to the arrangement of content was made to capture the essence of a tropical Pokémon paradise, making the website both inviting and memorable.

---

### User Experience/User Interface(UX/UI)

#### Typical Customer Profile

A typical customer for the Pokémon Island Resort is:

- A Pokémon owner or trainer
- Young and free spirited/eager for adventure
- Someone who enjoys traveling and exploring new destinations
- Enthusiastic about trying new and unique experiences and activities

#### User Stories

#### User Stories

- **As a new visitor:**
  - I want to quickly find out if the island has the activities and amenities I'm interested in, and feel assured that my stay will give me everything I'm looking for.

- **As a first-time user:**
  - I want the website to be easy to navigate, with a clear layout and intuitive links between pages, so I can move seamlessly through the site and find what I need without confusion.
  
- **As a Pokémon trainer:**
  - I want to easily discover classes tailored to my Pokémon’s type and abilities, and find trainers with the right expertise to help them master their moves, develop new skills and reach their full potential.

- **As a guest or potential guest looking to contact or request to book:**
  - I want to feel assured that my message or booking request has been received and will be responded to.

- **As a past visitor:**
  - I want to easily share everything I have experienced at the resort with friends and family, including trainers I've met and activities/classes my Pokémon and I have taken part in.

---

### Wireframes

TO DO

---

### Typography

**Fonts**

I wanted to pick a playful and tropical font with a seaside feel for my headings, so I used **Google Fonts** to explore options. Using their preview tool, I tested the phrase "Pokémon Island Resort" - the main site title - to ensure it looked just right, especially the (é) character, which appeared odd in some fonts. I ultimately chose 'Skranji' because it perfectly captures the exotic, tropical, and beachy vibe I wanted, and even has a hint of bamboo reminiscent of island shacks.

For paragraph text, I wanted a simple, clear, and unfussy font that would complement 'Skranji' without competing for attention. Again using **Google Fonts**, I browsed sans-serif options and selected 'Roboto' for its versatility and readability across devices. Its straightforward design and spacious lettering make it easy to read, even in longer paragraphs.

---
### Colour Scheme

**Background**

I wanted the website’s colour scheme to evoke a welcoming and relaxing island holiday feeling, so I decided on a background in either a sandy tone or a blue sea colour.

I also liked the idea of having a background image, so I began by searching on some of the free image websites for a suitable image that would set the tone for the site. After browsing through a few options, I found a [background image](#background-photo) on [Freepik (add link)](link) that felt like it perfectly matched the tropical vibe I envisioned. I instantly loved the colours in this image (and how well they worked together) - from the golden sand background colour, the vibrant green of the palm leaves, and the range of other colours in the smaller details such as the shells and footprints - and decided to make a colour palette from these to use throughout the website for consistency.

To be able to use each of these specific colours from the image throughout the website, I used the **ColorZilla** Chrome extension, which allowed me to pinpoint and save <!-- extract -->exact colour codes directly from any online image. I added many different colours, then refined my choices by previewing them on the site to ensure they complemented each other and provided good contrast.

The only colour (in the Colour Pallet) not from the background image is the dark brown, which I used for paragraphs of text. For improved readability I added a darker colour that still matched the aesthetic, as the colours in the image were all a little too pale (except the leaf green colour) but I decided this would be better to use for just headers, to help them stand out.

For future maintainability, I defined each colour as a CSS variable (e.g., `var(--colour-name)`). This approach made it easy to update the palette later if needed - changing a single variable would update the colour everywhere it was used. This was especially helpful when testing text contrast for accessibility, as did end up changing the colour I had selected for the paragraph text when testing against the background colour of the text 'bubbles', so that it would pass all of the tests in the [add link] contrast test as it didn't originally.

**Colour Pallet**

![Colour Pallet](assets/images/readme/colour-pallet.png)

**Favicon**

The favicon for this site is a small palm tree icon, chosen to reflect the tropical island theme of the resort. It appears in the browser tab and bookmarks, helping users quickly identify the site. The favicon was sourced from IconArchive and is free to use under an open source license. Its playful design complements the overall branding and adds a professional touch to the website.

**Header (including navbar) and Footer**

For the Header and Footer of the site, I decided I wanted it to have a bit of a bamboo shack feel, so started looking for images with horizontally lined up bamboo. Eventually found an image (link to bamboo image) I was happy with, but the colouring was wrong, so I decided to use an an partly overlay of one of the colours I'd decided on using before from the leaves the background image.

I decided to use this too for the footer, as it gave the site a bit more of a 'beach shack' type feel, and looked nice and dark enough for lighter content to show up well. 

**Font Colouring**

The only colour that wasn't from the background was the dark brown I chose for the paragraph text, as the rest of the colours were a bit light against the pale background apart from the leaf colour, but I was already planning to use this only on the header/footer, and some of the headings to make them pop, so it wasn't an option for the main bodies of text/description text colour.

I chose a dark brown, so that it doesn't clash or compete for attention from any of the more important headers, that I want the attention to initially be drawn to.

For this reason I kept the headings (Skranji) as more colourful, in a brighter green/golden sandy colour depending on the background shade, e.g. the bolder leaf colour on a paler background and the lighter sand colour on a darker background, so that the contrast is enough to be read easily.

I tested the colors using [wave link] [contrast test link], and amended the colours slightly later on so that I would pass tests that I'd failed with the previous colour. [this is mentioned here](link to #testing / #contrast#test)

---

## Testing

### Lighthouse Performance

When testing my website with Lighthouse, I encountered an issue which affected the 'Best Practices' score, as shown below
![Issue Description](assets/images/readme/lighthouse/lighthouse-best-practices-issue.png)
This was due to `h1` elements being used within a `section` element, so by changing all the `h2`s to `h3`s and `h1`s in my `section`s to `h2`s, this fixed the issue, giving me the scores below for each of the pages:

Home Page:
![Home Page Lighthouse](assets/images/readme/lighthouse/lighthouse-home-page.png)

Suites Page:
![Suites Page Lighthouse](assets/images/readme/lighthouse/lighthouse-suites-page.png)

Classes Page:
![Classes Page Lighthouse](assets/images/readme/lighthouse/lighthouse-classes-page.png)

Success Page:
![Success Page Lighthouse](assets/images/readme/lighthouse/lighthouse-success-page.png)

404 Page:
![404 Page Lighthouse](assets/images/readme/lighthouse/lighthouse-404-page.png)

### WAVE Test

### WebAIM Contrast Checker
[WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)

[WebAIM Contrast Checker showing the 2 colours I compared](https://webaim.org/resources/contrastchecker/?fcolor=674A18&bcolor=FEEDDC)

Original Colour Pallet:
![Colour Pallet](assets/images/readme/original-colour-pallet.png)

<!-- Add here screenshot of old pallet not passing AAA test -->

![Checking Contrast of text colour and background](assets/images/readme/webaim-contrast-checker.png)

### W3C Markup Validation Service (HTML and readme?)

### W3C CSS Validation Service

### Manual Testing (Expected Outcome/Did it pass?)
  - Navigation Links
  *What I'm testing:*
  Do all links navigate to the correct page/section?
  Do all buttons lead to the intended destination?
  - Forms
  *What I'm testing:*
  Does all the validation work, so the form can't be submitted without all required fields filled and with valid/the correct characters?
  Once submktted does it navigate to the success.html page?
  - External Links (Social Media Icons)
  Do they all lead to the intended website?
  Do they open in a new tab?
  - Responsive Design
  Does the website adapt as intended at all screen sizes?
  Does the burger menu work as it should, including closing when a link has been clicked?

### Manual Testing user stories

---

## Bugs

### Issues I Fixed

---

---

<details>
<summary>Dropdown Menu being cut off</summary>
**Issue:**
When the right dropdown menu is opened, some of the menu text is cut off by the edge of the screen. This happens because the dropdown button is positioned close to the screen edge, and the menu options are too long to fit within the visible area.

![Dropdown Menu being cut off](assets/images/readme/issue-right-align1.png)

**Why:**
Bootstrap dropdown menus are left-aligned by default. If the dropdown is near the right edge of the screen and the menu options are long, the menu will overflow and appear clipped, making some text not fully visible.

**Solution:**
By reading the documentation about Bootstrap dropdown menus, I found a fix to change the alignment of a menu to right-aligned instead, by simply adding the class `dropdown-menu-end` to the same element with the `dropdown-menu` class. This right-aligns the dropdown menu, ensuring it stays within the visible area of the screen.

**Outcome:**
![Dropdown Menu fixed](assets/images/readme/issue-right-align2.png)
This has fixed the issue. I decided to change only the 2 right navbar dropdown button menus to right alignment, and kept the left side buttons as their default left alignment so that the dropdown menus are visually consistent and it also prevents any potential future overflow issues on the other side.

This solution resolved the problem. I chose to apply right alignment only to the two dropdown menus on the right side of the navbar, while keeping the left-side dropdowns left-aligned. This approach keeps the dropdown menus visually consistent and also helps prevent any future overflow issues on either side of the screen.

Later, I also updated the navbar alignment to better match the rest of the site's layout by changing `container-fluid` to `container` in the navbar, which added more space between the buttons and edges of the screen and helped the navbar appear more consistent with the more centered page content.

</details>

---

---

## Deployment
<!-- Maybe make numbered list -->
- Firstly, I made a new repository in GitHub from the code institute template, with my chosen name for my project, which is `pokemon-island-resort`
    - I ensured that this was in snake case so it would all be ….
- Once I had made a new repository, in File Explorer on my local device, I then navigated to the folder I wanted my project to be in, and right clicked to ‘Open in Terminal’

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

# Credits

---

## Site Wide

Icons from - Font Awesome
Fonts imported from - Google Fonts

---

## Images Used

### Home Page

![alt text](assets/images/readme/battle-arena-licensing.png)

#### **Freepik for page background image and Bamboo background used in Header and Footer**
##### Background Photo: 
<details>
<summary>*click to view image*</summary>

![Background image with sand and palm leaves](./assets/images/beach-background.jpg)

</details>

[Freepik - Tropical Summer Design](https://www.freepik.com/free-vector/tropical-summer-design_4413927.htm)

##### Bamboo Image Used in Header and Footer:
<details>
<summary>*click to view image*</summary>

![Bamboo image from Header and Footer](./assets/images/bamboo-background.jpg)

</details>
[Freepik - Bamboo Patterned Curtain](https://www.freepik.com/free-photo/bamboo-patterned-curtain-textured-backdrop_15653469.htm)

#### **IconArchive for Favicon**
##### Favicon:
<details>
<summary>*click to view image*</summary>

![Palm Tree Favicon](./assets/images/palm.ico)

</details>

[IconArchive - Palm Tree Icon](https://www.iconarchive.com/show/noto-emoji-animals-nature-icons-by-google/22331-palm-tree-icon.html)
Favicon:
https://www.iconarchive.com/show/noto-emoji-animals-nature-icons-by-google/22331-palm-tree-icon.html
apache open source

- #### **Hero Image**: [RedBull - Pokemon Sun and Moon Game](https://www.redbull.com/au-en/new-game-releases-november-2016)
Hero Image:
https://www.redbull.com/au-en/new-game-releases-november-2016
https://img.redbull.com/images/c_crop,x_0,y_0,h_1498,w_2999/c_fill,w_1700,h_765/q_auto,f_jpg/redbullcom/2016/10/31/1331826758607_2/scene-from-the-new-pok%C3%A9mon-sun-and-moon-game-for-nintendo-ds3

Hero Image - Mobile:
https://www.google.com/imgres?imgurl=https%3A%2F%2Fwww.nintendo-difference.com%2Fwp-content%2Fuploads%2F2024%2F06%2FPokemon-GO-Fond-decran-Sous-un-meme-ciel.jpg&tbnid=yPOpOBrJxAe-BM&vet=12ahUKEwiV2IzlzfuMAxUMXkEAHeMkMK4QxiAoB3oECAAQJw..i&imgrefurl=https%3A%2F%2Fwww.nintendo-difference.com%2Fnews%2Fpokemon-go-le-debut-de-la-saison-sous-un-meme-ciel-et-les-evenements-de-juin-2024-detailles%2F&docid=d8prKse_oTl7ZM&w=1080&h=1920&itg=1&q=pokemon%20beach%20portrait&ved=2ahUKEwiV2IzlzfuMAxUMXkEAHeMkMK4QxiAoB3oECAAQJw

- **Garden View Chalet**
    [Freepik - 3D Rendering Illustration Botanic Garden](https://www.freepik.com/free-ai-image/3d-rendering-illustration-botanic-garden_196493972.htm#fromView=search&page=2&position=39&uuid=52c17b35-c035-4347-baa9-c40592085e85&query=Garden+Wallpaper+anime)

Garden Suite Image:
Freepik -
https://www.freepik.com/free-ai-image/3d-rendering-illustration-botanic-garden_196493972.htm#fromView=search&page=2&position=39&uuid=52c17b35-c035-4347-baa9-c40592085e85&query=Garden+Wallpaper+anime

- **Battle Arena Apartment**
[Battle Arena Charizard and Pikachu image](https://bulbapedia.bulbagarden.net/wiki/User:BigDocFan/List_of_moves_used_by_major_characters_Pok%C3%A9mon_in_Sun_%26_Moon)

https://archives.bulbagarden.net/wiki/File:Kiawe_Charizard_Aerial_Ace.png

**Mountain View Apartment**
https://www.google.com/imgres?q=pokemon mountains&imgurl=https%3A%2F%2Fw0.peakpx.com%2Fwallpaper%2F532%2F280%2FHD-wallpaper-pokemon-flygon-waterfall-mountains-trees-anime.jpg&imgrefurl=https%3A%2F%2Fwww.peakpx.com%2Fen%2Fhd-wallpaper-desktop-vqazu&docid=diiFN9gyBwUtKM&tbnid=V_goH3H8_tnxwM&vet=12ahUKEwjSq-n0rM6NAxUuX0EAHR8BLLEQM3oECH8QAA..i&w=800&h=435&hcb=2&ved=2ahUKEwjSq-n0rM6NAxUuX0EAHR8BLLEQM3oECH8QAA

---
---

## Other

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

---

---

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

<!-- Dropdown Template -->
<details>
<summary>Dropdown Template</summary>
Inner Hidden Content
</details>

to change size of markup image - not working though:
![Alt text](image-url.jpg){width=300 height=200}

Can I link an image to a URL in Markdown?
Yes, wrap the image syntax in link syntax: [![Alt Text](Image URL)](Link URL)