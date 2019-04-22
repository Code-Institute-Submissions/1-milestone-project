# Sajanek ART website
First milestone project: User-Centric Frontend Development - Code Institute

This is my website where I present my artworks. The website allows the visitors to downloand few of my digital prints for free and leads visitors to my shops in other ecommerce websites where I sell my prints and original paintings. The website is in an English version and it is divided to five sections and covers more technologies. 

## Demo
A live demo can be found [here](https://vladkosajanek.github.io/1-milestone-project/).

Desktop Demo

## UX
I decided for a single scrolling one page website where different sections are separated areas so comming visitors can orientate themselves very quickly. My goal in the design was to make it as easy as possible to access information. The combination of colors was chosen to make a design come alive. I choosed eye-catching color combinations which are balanced with contrasting link colors to bring attention to important components.  

For visitors via a user friendly eye-catching design, I wanted to show a bit of my portfolio with attention to lead them to other websites where they can purchase my art.  

This way, they would be able to see what kind of art I do, who I am and they have option to contact me, to see my comming exibitions or sign up for my newsletter in which I present my new artworks and see more art on websites where i sell my prints or original paintings. In five different sections of my website I wanted them to be able to do following:
 
##### 1. SLIDESHOW section 
Here visitors can see cycling images with some of my artworks.
##### 2. ABOUT section 
In this section I describe a bit about myself so they can access information about what styles of painting techniques I like using, what material I use, what commposition I am interested in etc.
##### 3. PORTFOLIO section 
In this section I highhligt only few of my artworks with possibility of free download and lead people via highlited links to my other ecommerce website where I sell my art.   
##### 4. EVENTS section
Here I wanted to promote my comming gallery exibitions so visitors can see my art in person if they want.
##### 5. SUBSCRIPTION section
Important part of my site is also Subscription section where people can sign up for a newsletter so they can stay in touch with my art.

Links to my social media profiles are also provided for their ease of access.

## Technologies
HTML

CSS

Bootstrap (4.3.1)

## Features
This site uses the navbar feature from Bootstrap with an extra Navbar toggler function so navbar collapses in small screens.
Another features which are used in this website comming also from Bootstrap and those are modal components which were used to add an extra information (in ABOUT section) and add options to reserve a ticket for event (in EVENT section).

## Features Left to Implement
In the future, I would like to add e-commerse function so comming visitors can potentialy buy my art on my web so they do not have to be linked to other websites. 
Furthermore I want to also add more of my artworks to Portfolio section. 

## Testing

The employer and recruiter user story achieved the intended outcome of providing them with a showcase of myself and my work. In the about me section, they can read a bit about my background, and if they're viewing on a desktop, the background of this section is a photo of me. They are able to see my showcased projects via the project cards in the "Work" section. They can view both the live version and the GitHub repository by clicking on the Font Awesome icons. They are also able to view my social media profiles via clicking on the icons in the footer. They are also able to download my CV by either clicking on CV in the navbar dropdown, or by clicking on the document icon in the footer.

If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name,' 'email,' and 'message' fields, so if those fields are not filled in, the form will not submit. If all field are valid, the page will reload. If an employer or recruiter is interested in contacting me, they will have to fill out all fields in order for the form to go through.

All links will open in a new tab using 'target="_blank"' and the CV will download to your default folder for downloads on click using the 'download' attribute. All links have been manually tested to ensure that they are pointing to the correct destination.

By clicking on the links in the navbar, the scrollSpy effect will work regardless of whether or not you're viewing the sections in the same order they are listed in the dropdown navbar.

This site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple mobile devices (iPhone 4, 5, 7: Chrome and Safari, iPad, Samsung Galaxy) to ensure compatibility and responsiveness. During the testing phase, I realized that background-attachment: fixed was not compatible with iOS browsers. On Chrome and Safari in iOS, the background photos appeared zoomed-in and blurry. To fix this, the background-attachment: scroll property value was added in a media query.

Deployment

## Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. 
In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://github.com/hschafer2017/HSCHAFER-Portfolio.git into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

## Credits
### Content
All content in all sections on this website were written by me.

### Media
All photos were taken by me from my original artworks, with the exception of the one photo from "Carousel" which was taken from Pexels. A blue filter to carousel photos was applied to preserve the blue-yellow theme.

### Acknowledgements
The navbar toggler function was showed through this tutorial but I used it from [here](https://getbootstrap.com/docs/4.0/components/modal/#events).

The idea of using modals also comming from code-institute tutorials but found [here](https://getbootstrap.com/docs/4.0/components/modal/#events).

All used components were after styled according to needs of the website.

The media query was tried by me on different screen sizes.

This is for educational use.