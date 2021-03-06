# Delivery and Transport Services 

Welcome to [Safe-Transport website!](https://mihaielisei.github.io/transport-services/)

# Introduction

Delivery and Transport Services is a company that offers delivery and transportation services for both individuals and other companies. These services consist of transporting various types of goods from small packages such as letters to large packages such as furniture or appliances.
Our services are available throughout entire country of Ireland!

The aim of this project is to create a website that presents the services of a company in an attractive and simple way for users to navigate on it.

Live version of the website: [Safe Transport](https://mihaielisei.github.io/transport-services/)


![responsivnes image](assets/images/responsive.png)


# Table of Contents

# 1. User Expereince (UX) design

The website has been created in such a way that users can easily navigate from one page to another and the information presented is visible, easy to understand and easy to find.

The following users types can be benifitted from the website:

* Individuals who need transportation in case of a change of home or any other personal needs;
* Large and medium-sized companies that need contractors to provide them with daily transportation of goods or deliveries.

# 1.1 User Goals

The main purpose of this website is to present the services offered by the company in order to obtain new contracts and collaborations with potential clients.

# 1.2 User Expectations 


The content of this website presents the services offered by a product delivery company. This website is ideal for people who are planning to start a small business and want to present their services online. Folloiwng user's expections ware considered while designing the site:

* The site structure is designed considering the expectation of users to be simple and easy to use;
* The user interface is easy to navigate;
* Responsive design for all screen/device sizes like mobile, tablet and desktop;
* A application page is provided for those users who will be contacted if they are interested in company services.

# 1.3 Color Scheme

The choice of website right foreground and background colour is essential that decides the site visitors wheather to emote the site or not. I used [Color Hunt](https://colorhunt.co/) to select the background and foreground color. Colors that i used are:

 * #614124 - for text and footer background;
 * rgba(159, 192, 136, .8) and rgba(232, 192, 125, .8) : a linear gradient with opacity of 0.8 over the hero image;
 * #E8C07D - for main content background;

# 1.4 Images and Logo

This website was created for academic purposes, all photos were searched and downloaded from the google platform and the logo was created and downloaded from [Looka](https://looka.com).

# 1.5 Site Skeleton
[Balsamiq](https://balsamiq.com/) was used to create wireframes of the website. This was very useful as it gives the template of the UI. Wireframes were designed for web browser and a mobile browser format:

## Header:
![Header Whireframe image](assets/images/header.png)

## Home Page:
![Home page whireframe image](assets/images/home-page.png)

## Gallery Page:
![Gallery page whireframe image](assets/images/gallery-page.png)

## Contact Page:
![Contact page whireframe image](assets/images/contact-page.png)

# 2.Features

## All 3 pages:

* Navigation bar is placed at the top right corner of the page, and cosnidered a hover effect that changes the font size of menu items and add bottom border. The hover effect is placed to improve the user expereince. Background color for the navigation menu is white with a 0.4 opacity;
* Logo is placed on the top left corner;
* Header background is an image with two color over it (linear-gradient) with 0.8 opacity. This makes the background look modern and attractive to users.
* For page title and small presentation i have created animations to make text translate and change it`s opacity;
* Social media links (Facebook, Instagram, Twitter and Youtube) are placed at the bottom of the each page in the footer. All the links will be opened in a new tab.

## Home Page

* In addition to the other pages in the header part of the home page under the title and the presentation text, we have created a button that leads to the services section. When hover the button this will translate a few px up and create an box shadow;
* I used for the whole website but especially for the home page the clip path property to create nice polygons and give the website a nice design;
* In policies section every division have a hover effect that translate the division and create a box shadow;
* In the bottom of the page I used bootstrap 5.2 framework to import and create a carousel.

The screenshots of Home page are below:

![home page](assets/images/README-images/home-page1.png)
![home page](assets/images/README-images/home-page2.png)
![home page](assets/images/README-images/home-page3.png)
![home page](assets/images/README-images/home-page4.png)

## Gallery page
* For gallery section I used clip path to create a nice design to the page;
* For gallery I used the code from Love Running project;
* Every image in the gallery have a hover effect of increasing the size with 10%.

The screenshot of Gallery page is below:
![gallery page](assets/images/README-images/gallery-page.png)

## Contact page
* Include contact form that provides the user the ability to message site owner, provide feedback and suggestions.
* For contact section I used clip path to create a nice design to the page;
* Left image have a hover effect that rotates the img with 180deg (this will create a good experience for users while navigate on the website);
* Hover effect for submit button;
* The form use the method="POST" action="https://formdump.codeinstitute.net/";
* I use the placeholder attribute for textarea;
* I added iframe with Dublin City map (as an general address).

The screenshot of Gallery page is below:
![contact page](assets/images/README-images/contact-page.png)
![contact page](assets/images/README-images/contact-page1.png)

# 3. Technologies Used

* HTML5 was used for structuring and presenting content of the website;
* CSS3 was used to provide the style to the content written in a HTML;
* Balsamiq was used to create wireframes of the website;
* Google Fonts was used to import font-family "Nunito" and "Ubuntu" into style,css file and which was used throughout the pages of the website;
* Font Awsome was used to improt icons to the sites;
* Chrome was used to debug and test the source code using HTML5 as well as to test site responsiveness;
* Github was used to create the repository and to store the cproject's code after pushed from Git;
* Git was used as the Code Editor for the site;
* Color Hunt was used to select the background and font color in the website;
* W3C Markup and Jigsaw validation tools were used to validate the HTML code and CSS style used in the proejct;
* Ami was used to develop a Mockup screenshot generator.

# 4. Testing

## 4.1 Testing tools:
* Google Developer Tools for debug and test css code;
* [I Am Responsive](https://ui.dev/amiresponsive) site to check if website is responsive on all devices screen sizes;
* W3C Validator Tools was used to check for any errors within my HTML pages:
![w3C validator pic](assets/images/README-images/W3C-1.png)
![w3C validator pic](assets/images/README-images/W3C-2.png)
![w3C validator pic](assets/images/README-images/W3C-3.png)
* W3C CSS Validation was used to check for any error within my CSS stylesheet:
![Css validator pic](assets/images/README-images/CSS-validator.png)

## 4.2 Manual Testing

I have tested my site on multiple devices. These include:
* Galaxy Fold (280 x 653);
* Iphone 6/7/8 Plus (414 x 736);
* Ipad (768 x 1024);
* Nest Hub (1024 x 600);

## Header 

| TEST | OUTCOME | PASS / FAIL |
|:---:|:---:|:---:|
| Home Page | On click to "Home", the browser redirects me to the Home page. The hoever effect (bottom border and font size increase) appears when mouse is on "Home". | PASS |
| Gallery Page | On click to "Gallery", the browser redirects me to the Gallery page. The hoever effect (bottom border and font size increase) appears when mouse is on "Gallery". | PASS |
| Contact Page | On click to "Contact", the browser redirects me to the Gallery page. The hoever effect (bottom border and font size increase) appears when mouse is on "Contact". | PASS |
| Responsive | All pages and elements are responsive (mobile and desktop) using differnt breakpoints. | PASS |
| Text | Checked if all fonts and colors used are consistent or not | PASS |
| Animations | All animations effects works on all pages | PASS |
| Header Button | When hover button chages position and creates box shadow, when clicked it goes to Services section | PASS |

## Footer

| TEST | OUTCOME | PASS / FAIL |
|:---:|:---:|:---:|
|Facebook| On clicking Facebook icon, a new tab opens and redirects to the Facebook website.|PASS|
|Twitter| On clicking Twitter icon, a new tab opens and redirects to the Twitter website.|PASS|
|Youtube| On clicking youtube icon, a new tab opens and redirects to the youtube website.|PASS|
|Instagram|	On clicking instagram icon, a new tab opens and redirects to the instagram website.|PASS|
| Hover | When hover all icons change font size.|PASS|

## Home Page

| TEST | OUTCOME | PASS / FAIL |
|:---:|:---:|:---:|
|Media| All images on the pages load. Carousel images change every 5sec.|PASS|
|Responsive|Responsiveness of the page in different screen sizes (mobile and desktop) using differnt breakpoints were checked.|PASS|
|Accessibility|Checked the accessibility of the page using lighthouse.|PASS|

## Gallery Page

| TEST | OUTCOME | PASS / FAIL |
|:---:|:---:|:---:|
|Media| All images on the page load. All images were checked if it blurred in differnt screen sizes.|PASS|
|Hover|When hover all images changes width.|PASS|
|Responsive|Responsiveness of the page in different screen sizes (mobile and desktop) using differnt breakpoints were checked.|PASS|
|Accessibility|Checked the accessibility of the page using lighthouse.|PASS|

## Contact Page

| TEST | OUTCOME | PASS / FAIL |
|:---:|:---:|:---:|
|Media| Image on the page load. When hover image rotate 180deg.|PASS|
|Submit| Checked if submit button works. When hover style change.|PASS|
|Placeholder|Checked if placeholder on the textarea works.|PASS|
|Google map| Checked of google map is displayed.|PASS|
|Responsive|Responsiveness of the page in different screen sizes (mobile and desktop) using differnt breakpoints were checked.|PASS|
|Accessibility|Checked the accessibility of the page using lighthouse.|PASS|



## 4.3 Lighthouse Reports:

* For Desktop:

![Lighthouse report](assets/images/README-images/Lighthouse1.png)
![Lighthouse report](assets/images/README-images/Lighthouse2.png)
![Lighthouse report](assets/images/README-images/Lighthouse3.png)

* For Mobiles:

![Lighthouse report](assets/images/README-images/Lighthouse4.png)
![Lighthouse report](assets/images/README-images/Lighthouse5.png)
![Lighthouse report](assets/images/README-images/Lighthouse6.png)


# 5. Bugs

## Solved Bugs

* When I checked the accessibility in the Lighthouse reports discovered I forget to add title to iframe (google map). I solved it by adding title "Dublin map";
* The action atribute frome the form was misspelled and when I clicked submit nothing happend, fixed the attribute all working fine;
* When the screen size reached 360px width footer was no longer responsive, change the display property footer is responsive to all screen sizes; 
* Images from the carousel ware streched, changed the css property to "object-fit: contain;" problem solved.


# 6. Deployment
 The site was deployed to GitHub pages using the following steps: 
 * Sign up to GutHub;
 * Create a new repository on GitHub;
 * Click on settings on the navigation bar under the repository title;
 * Select pages on the left menu bar;
 * Click on the master branch and save;
 * This will now generate a link with your website live;

 # 7. Acknowledgement

* The header was inspired by Jonas Schmedtmann from Advanced CSS and Sass: Flexbox, Grid, Animations and More! course from Udemy!;
* Icnons, footer and gallery section was inspired from Love Running project;
* This website was created for academic purposes, all photos were searched and downloaded from the google platform;
* For README.md file, reference of https://github.com/dhakal79/Portfolio-project-MS1 was considered; 
* Thanks to my mentor Marcel Mulders for his support and feedback.
