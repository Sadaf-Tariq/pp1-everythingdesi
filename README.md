# Index - Table Of Contents:

1. [General Information](#About-everything-DESI)
2. [Features](#Features)
3. [Technologies Used](#Technologies-Used)
4. [Testing](#Testing)
5. [Bugs](#Bugs)
6. [Unfixed bugs](#Unfixed-Bugs)
7. [Validator Testing](#Validator-Testing)
8. [Deployment](#Deployment)
9. [Credits](#Credits)

# About everything DESI
The everything DESI website is a catering website for anyone who loves desi food. When deciding on a topic for the project. I wanted to do something I am passionate about. I love desi food and I love to cook, and catering service is something I want to do in the future so I concluded to do a catering website. The website offers spicy, rich, flavourful, and diverse desi cuisine.

Users of this website will be able to find all the information they need to know about everything DESI website: About the kitchen, specialty, full menu, the service gallery, contact information, and an enquiry form. This site is targeted towards people who love to eat desi food and wants a reliable catering service to cater their events.

![Responsive image](/images/amiresponsive.png)

# Features
* The Header

  * Featured at the top of the page, the header shows the logo of the website at the right of the right corner: everything DESI that links to the home page

  * The logo image is present at the left corner of the header that also links to the home page

  * The header clearly shows the name of the website with a font easy to understand and a color that contrasts with the background

    ![Header Image](/images/header.png)

* Navigation

  * Featured after the header, it contains the navigation links for the website present at the center of the navigation bar

  * The navigation links are: Home, Menu, Gallery and contact us that links to the different pages of the website

  * The navigation links make it easy for the user to find the different pages of the website and use the same color theme but different font

    ![Navigation Bar](/images/navigationbar.png)

* Main Image and Banner

  * This section of the page provides us with a delicate photograph of biryani in a dish, surrounded by spices. The image with an eyecatching animation lets the user envision that the goal of the website is desi food industry oriented

  * The main image also contains a banner with a semi-transparent background of the same color theme

  * The cover image on the banner sums up the tone and premise of the website and strengthens the User's memory of the brand itself

    ![Main image and banner](/images/main-image.png)

* The Kitchen

  * This section of the page contains a brief description of what happens inside the kitchen to make the user feel trusted

    ![The kitchen](/images/kitchen.png)

* The Highlight

  * The highlight section gives the detail of everything DESI's specialty, this section ensures that the user do not loose their interest

    ![our speciality](/images/highlight.png)

* The Footer

  * The footer section encourages the user to keep in contact and provides a phone number, and street address where they can be found

  * The footer section also includes social media icons so that users can find the catering service on Facebook, Twitter, Youtube, and Instagram

  * The  contact information on the footer section is valuable to users as it helps them to find or contact them if they need to

    ![The footer](/images/footer.png)

* Menu Page

  * The menu link on the navigation bar links the age to the Menu page, where a detailed menu is available for users to help them to find the right desi food they want to order for their important event

  * It is the most important premise of the website as the majority of the users will be interested in this page hence why there is a separate page dedicated to this section and made in detail with a beautiful food background with the white font to ease accessibility

    ![The menu](/images/menu.png)

​    

* The Gallery

  * The gallery link on the navigation bar takes the user to the gallery page where there are images available for the users 

  * The gallery images of food served by everything DESI and their catering service give a clear picture to users to make an informed decision

    ![The gallery](/images/gallery.png)

* The Contact-us Page

  * The contact-us link on the navigation bar takes the user to the Contact us page, which consists of two sections. The contact section encourages the user to keep in contact and provides a phone number, email address, and street address where they can be found

  * It also includes information about its opening to help the users to know when they should be contacted

  * The enquiry section has a form for the users to give all the relevant information about the enquiry they want to make. This form feature establishes a connection between the user and the site

    ![The contact us page](/images/contact.png)

  * When the user presses the submit with all the information, they are taken to a Thank you window, further, emphasizing interaction 

    ![Thank you window](/images/thankyou.png)
# Technologies Used

#### Languages Used

* HTML5
* CSS3

# Testing

* I tested the website on different browsers such as Microsoft Edge, Opera, Firefox, Chrome, and Safari and it works on all browser
* I confirm that this project is responsive, functions on all standard screen sizes, tested responsiveness using the developer tools, and looks good 

<img src="/images/responsive(1).png"  width="750" height="500"> <img src="/images/responsive(2).png"  width="300" height="500"> <img src="/images/responsive(3).png"  width="500" height="700">

* I confirm that the header, navigation bar, highlights, footer, menu, and form text are all readable and easy to understand
* I have confirmed that the form works: requires entries in every field, will only accept emails in an email field, and the submit button works

# Bugs
* When I tested my HTML code for the index.html page on html validator, I got the error that one of the div element was unclosed which was causing another section to give another error, I solved the problem by removing that div element
* Another error I found for the menu.html page, where I put an anchor element inside a button element, I solved that error by replacing the button to form 
* For the style.css for the header element in a media query, I got an error because there was a margin selector that had a negative value, I solved that error by removing that selector

# Unfixed Bugs
There is no unfixed bugs but there is a warning indicated by html validator for gallery.html page of the website, for my design I do not need any header for this section of the page that is why this warning was not entertained
![Warning Image](/images/warning.png)

# Validator Testing
* HTML
  * No errors were returned when passing through the official [W3C validator](https://validator.w3.org/)
* CSS
  * No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/)
* Accessibility
  * I confirmed that the colors and fonts chosen are easy to read and accessible by running it through lighthouse in developer tools

    ![Lighthouse report](/images/lighthouse.png)

# Deployment
- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - https://sadaf-tariq.github.io/pp1-everythingdesi/

# Credits
* Content
  * [Font awesome](https://fontawesome.com/) provided the icon for my header and cover text on the hero-image element
  * [w3schools](https://www.w3schools.com/) helped me in creating my form
  * [w3schools](https://www.w3schools.com/) helped me in creating my button for the menu page
  * [StackOverflow](www.stackoverflow.com) helped me to create a custom bottom border on the speciality section heading
  * [StackOverflow](www.stackoverflow.com) helped me to remove the error I was getting for an anchor element inside the button element
  * The code for the social media link for the footer was taken from Code Institute [Love Running](https://github.com/Sadaf-Tariq/love-running/blob/main/index.html) project
  * The text for the home page was taken from [Wikipedia](www.wikipedia .com) and some open-source sites
  * The logo image for the website was taken from [Wix](www.wix.com)
  * I got the inspiration for the website from Zouq restaurant, Koyla restaurant, and David Smyth Catering
  * [w3schools](https://www.w3schools.com/), [StackOverflow](www.stackoverflow.com),  and Code Institute's walkthrough project [Love Running](https://github.com/Sadaf-Tariq/love-running) helped me so much throughout my project

* Media
  * The images used in the website were taken from [Pexels](https://www.pexels.com/)


