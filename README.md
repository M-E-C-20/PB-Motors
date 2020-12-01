# Pearson's Bridge Motors

![Responsive](https://github.com/M-E-C-20/PB-Motors/blob/master/screenshots/responsive-screens.jpg?raw=true)

This is my website which will be used to advertise a small local garage.
It should feature the services offered and a price guide, an about page, a gallery and a contact page.
the primary goal is to intice customers to make contact with the garage via the contact page.

To do this I will need to make a comprehensive guide of services are available and use the price guide to give the customer confidence in what they are spending they're money on.
To bolster this confidence, I will include an about page and a gallery.
On the gallery page I will include some images of the garage and some helpful tips for self maintenance for the customer.

[Live Website](https://m-e-c-20.github.io/PB-Motors/)

## UX

_Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things._

_In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:_

### User Stories

- As a new user, I want to find out what work can I get done to my vehicle?
- As a new user, I want to know if there is a breakdown service?
- As a new user, I want to know how much will the work cost me?
- As a new user, I want to know how can I contact you?
- As a new user, I want to know how do I book an appointment?
- As a user, I want to be able to sign up and sign in to avail of member discounts etc.
- As the owner, I want to advertise the services I offer to new customers.
- As the owner, I want to continue to maintain my existing customer base with loyalty rewards.
- As the owner, I want my site to be easily navigable to both new and existing users.

### Strategy

The main goal of the website is to make an easy way for the user to get a general idea of work that can be done to their car and to get an idea of the price structure in place.
I wish to design an intuitive, easily navigable website to create an enjoyable user experience, which wil benefit both users and the owner.
I wish to make it easy for the user to see what services are available to them and to provide details of the team and facilities to give confidence to the user while browsing on any device.

### Scope

I want to use a minimalist design to demonstrate to customers services offered,
and to ensure customer confidence using the about section. It is important to use a clear, simple interface to avoid delivering a poor user experience.
The option to contact the garage needs to be included also.

### Structure

In each section I want to keep a common navbar and a common footer.
In the header there will be a navbar with site links and a company logo.
In the footer section there will be copyright mark and social media icons which will act as buttons linking to their respective sites.

### Skeleton

- Home
- About
- Gallery
- Contact

---

_I will need to make these links to wireframes_

---

### Surface

I wish to use a simple grey and white colour scheme which contrasts well together and is easily read.
This should create an accessible interface and suits a website for a small organisation with a limited needs, which is to get the user to try to make contact with the business.

_This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser._

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.

### Existing Features

- Navbar - allows the user to navigate the site using the listed buttons. The company name/logo also acts as a home button.
- What we do - This section on the home page gives a general view of the services offered which includes a button which links to the contact page or, if trying to contact breakdown services, links to a phone number.
- Price Guide - A table which gives a general price range to inform the customer of costs before they choose to make contact.
- Footer - This will include social links which open in an new tab when selected.
- About - This section will give some information on the technicians and their credentials, which should help to inspire confidence in a user.
- Gallery - The gallery will include pictures which indicate the kind of work that is performed in the workshop, and help inspire customer confidence.
- Embeded Video - The embedded video at the bottom of the gallery is one that includes car maintenence tips for an ordinary person. This is designed to inspire trust between the user and business, by educating them.
- Contact Form - Allows users to make contact with the business, by having them fill out the form.
- Embedded Map - Allows users to locate the garage easily without having to leave the website to input the location manually themselves.

## Technologies Used

_In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used._

- [Balsamiq Wireframes](https://balsamiq.com/wireframes/?gclid=Cj0KCQiAhs79BRD0ARIsAC6XpaVYvwCWIORZNFLa4ZbfPQf8gAchZhdlP10mZeYDFooTFk1sW1Pua4caAgsmEALw_wcB)
  - The project uses Balsamiq Wireframes for desktop to generate wireframes for the website.
- [Gitpod](https://www.gitpod.io/)
  - I used Gitpod to write my code for this project.
- [Git](https://git-scm.com/)
  - The project uses Git to update records to any changes to files.
- [GitHub](https://github.com/)
  - The project uses Github as a hosting service for version control.
- [GitHub Pages](https://pages.github.com/)
  - The project uses GitHub Pages to host the website.
- [Bootstrap](https://getbootstrap.com/)
  - The project uses Bootstrap heavily to help build the site.
- [Google Fonts](https://fonts.google.com/)
  - The project uses Google Fonts to style the fonts on the website.
- [Font Awesome](https://fontawesome.com/)
  - The project uses Font Awesome to add to my navigation buttons.
- [Pexels](https://www.pexels.com/)
  - Many of the photos used in this project came from this website.
- [CSS Lint](http://csslint.net/)
  - The project uses CSS Lint as an extra testing step after initially manual checks.
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
  - The project uses this to test CSS by direct input.
- [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input)
  - The project uses this to pinpoint errors in HTML markup.
- [ResizeImage.net](https://resizeimage.net/)
  - The project uses ResizeImage.net to resize the images used on the site.
- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools)
  - The project uses Chrome DevTools to analyse performance, accessibility, and best practices.

## Testing

1. ### Fixed Issues:

   - I decided to change the way the nav buttons appear on mobile as they were taking too much of the screen and hiding site content underneath, and could have been confusing for a user to use. Under advice from my mentor, there is now a navbar which is fixed to the top of the screen.
   - My mentor Rohit discovered that, suing the Galaxy Fold virtual device on Chrome DevTools, the screen had a horizontal scroll bar. This was due to the narrowness of the screen comined with more content than could be compressed causingthe table to overflow the window.
     This was fixed by removing some uneccessary words which were bloating the cell sizes in the table.
   - Rohit advised me to redirect my form submission from the contact page to go back to my home page when tested. Previously it was redirecting to an external source, Code Institute's form dump page, which he advised me against.

2. ### CSS:

- First I manually examined my CSS structure and removed uneccessary items and arranged them in a more understandable and easy to read manner.
- I ran my CSS through [CSS Lint](http://csslint.net/) and found 4 errors.
- I ran my CSS by direct input through [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) which passed.

3. ### HTML:

   1. #### Home:

   - I ran index.html through [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input) by direct input. It resulted in two errors, which were br elements within ul on the address and opening hours.
   - Removed br elements re-ran tests and received no errors.

   2. #### About:

   - I ran about.html through [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input) by direct input. I found errors relating to invalid test elements.
   - Removed test elements, re-ran tests and received no errors.

   3. #### Gallery:

   - I ran gallery.html through [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input) by direct input. I found errors relating to invalid test elements. I also found an error relating to an invalid main element.
   - Removed invalid elements re-ran tests and received no errors.

   4. #### Contact:

   - I ran contact.html through [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input) by direct input. I found an error relating to an invalid row attribute within an input element.
   - Removed row attribute from input element, re-ran tests and received no errors.

4. ### [Chrome DevTools:](https://developers.google.com/web/tools/chrome-devtools)

   - I used the Lighthouse feature within Chrome DevTools to simulate real world conditions and analyse performance, accessibility, and best practices on both mobileand desktop while doing so.
   - This resulted in adding the rel attribute to the social links in the footer on each page, which improved the websites best practices score all round.

5. ### [Color Contrast Accessibility Validator](https://color.a11y.com/?wc3)

   - I ran each page of the website through Color Contrast Accessibility Validator. Each page passed.

6. ### [Web Accessibility](https://www.webaccessibility.com/results/?url=https%3A%2F%2Fm-e-c-20.github.io%2FPB-Motors%2Fgallery.html)

   - I ran each page of the website through Web Accessibility. The gallery page showed one violation due to an iframe element missing a title attribute. Added title attribute, re-ran and found no violations. The contact page showed three violations, one for a missing title attribute within an iframe element and two for missing descriptions of a link.
     Added title attribute, added sr-only class to links, and re-ran test. Each page now has no violations.

7. ### Website Functionality

   - Each webpage on the website was tested using the same steps outlined below on desktop using Chrome, Opera, Firefox and Microsoft Edge.
   - Mobile testing was performed using the [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools) virtual phone. I used three different virtual phones to ensure that the website functioned correctly through different screen sizes, as my mentor Rohit had found an erroron my homepage which was only visible using the Galaxy Fold virtual device.
   - With this in mind, the three virtual mobile devices I used were:

   1. iPad (768x1024)
   2. Moto G4 (360x640)
   3. Galaxy Fold (280x653)

   4. #### Home

   - Use navbar buttons and verify that navigation to other pages works.
   - Use browser back and forward buttons to verify navigation is possible through the website without problems.
   - Try to use social links in footer and verify they open in a new tab to the requested sites: Facebook, Youtube, and Instagram.
   - Try to use the "book now" button under service and repair and verify it navigates to the "Contact" page.
   - Try to use the "book now" button under diagnostics and verify it navigates to the "Contact" page.
   - Try to use the "call now" button under breakdown and verify the telephone link works as expected.

   Home page screenshots:

   - [desktop](https://github.com/M-E-C-20/PB-Motors/blob/master/screenshots/home-desktop.jpg)
   - [mobile](https://github.com/M-E-C-20/PB-Motors/blob/master/screenshots/home-mobile.jpg)

   2. #### About

   - Use navbar buttons and verify that navigation to other pages works.
   - Use browser back and forward buttons to verify navigation is possible through the website without problems.
   - Try to use social links in footer and verify they open in a new tab to the requested sites: Facebook, Youtube, and Instagram.

   About page screenshots:

   - [desktop](https://github.com/M-E-C-20/PB-Motors/blob/master/screenshots/about-desktop.jpg)
   - [mobile](https://github.com/M-E-C-20/PB-Motors/blob/master/screenshots/about-mobile.jpg)

   3. #### Gallery

   - Use navbar buttons and verify that navigation to other pages works.
   - Use browser back and forward buttons to verify navigation is possible through the website without problems.
   - Try to use social links in footer and verify they open in a new tab to the requested sites: Facebook, Youtube, and Instagram.
   - Try to use embedded Youtube video and verify that all video controls are working.

   Gallery page screenshots:

   - [desktop](https://github.com/M-E-C-20/PB-Motors/blob/master/screenshots/gallery-desktop.jpg)
   - [mobile](https://github.com/M-E-C-20/PB-Motors/blob/master/screenshots/gallery-mobile.jpg)

   4. #### Contact

   - Use navbar buttons and verify that navigation to other pages works.
   - Use browser back and forward buttons to verify navigation is possible through the website without problems.
   - Try to use social links in footer and verify they open in a new tab to the requested sites: Facebook, Youtube, and Instagram.
   - Try to submit the empty form and verify that an error message about the required fields appears
   - Try to submit the form with an invalid email address and verify that a relevant error message appears
   - Try to submit the form with all inputs valid and verify that a success message appears.
   - Ensure embedded map loads in the correct location.
   - Verify that embedded map control work as expected.

   Contact page screenshots:

   - [desktop](https://github.com/M-E-C-20/PB-Motors/blob/master/screenshots/contact-desktop.jpg)
   - [mobile](https://github.com/M-E-C-20/PB-Motors/blob/master/screenshots/contact-mobile.jpg)

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits

### Content

### Media

- The photos used in this site were obtained from [Pexels](https://www.pexels.com/). In particular the content creators:
  - [Mídia](https://www.pexels.com/@multimediayreaccion) - Images used in gallery page and in about page in the employee profiles.
  - [Pixabay](https://www.pexels.com/@pixabay) - Image was used for the background of the home page.
  - [Andrea Piacquadio](https://www.pexels.com/@olly) - Images used in the about page for employee profiles and the gallery page.
  - [Mike](https://www.pexels.com/@mikebirdy) - Image used in the gallery page.

### Acknowledgements

- I used the [Code Institute](https://github.com/Code-Institute-Solutions/readme-template) README template as a base for my own.
- I received inspiration for this project from my first job, which was in my family garage. I noticed that many small garages have no way of being contacted or even noticed unless through word of mouth.
- I took inspiration for the navbar styling from the UCD resume project, using the box style for the navigation buttons, symbols from font awseome, and a transition effect also as in the project.
- One of the main automotive websites I took note of was [Quick Fit](https://quickfit.ie/). In particular on the home page, I took from the opening hours and address at the top, and a row of services performed underneath.
  I borrowed the underline styling in the address and opening hours sub headers, and three separate columns with buttons that link to the contact page or to a phone number.
- The css for hovering the social media icons was copied and pasted directly from [w3schools.com](https://www.w3schools.com/cssref/sel_hover.asp).
- I copied the css for the backgound image on the home page from the Whiskey Drop project.
- I copied the html snippet for the contact form from [MDBootstrap.com](https://mdbootstrap.com/snippets/jquery/temp/2746217?action=prism_export). I changed one of the icons, made the input fields required, and used my own text decorations.
- I also took note of [Pep Boys](https://www.pepboys.com/), [AA](https://www.theaa.ie/aa-membership.aspx?gclid=Cj0KCQiAhZT9BRDmARIsAN2E-J196kNgel1r2a3OZ1FP-m1-zD2rYuhpq-vEXjsWwIMJGivOowi3RFYaAm_ZEALw_wcB) and [JohnMcCarthy Recovery](https://www.johnmccarthyrecovery.com/services).
