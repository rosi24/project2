# Project 2 - Quiz

---

## Overview:

This project is an online Quiz about the world. It includes ‘How To’ page with clear instructions and displays a button to 'Play'.
I have used JavaScript for the Quiz functionality.

---

## UX

My website is for teenagers - consolidating information they have learnt in a Georgraphy block of teaching. My online game provides simple, clear instructions about 'How to Play'. I've chosen keep the design of my online game simple, using colours of the world - blues, yellows and greens.

---

## Wireframes

I planned what each page would look like then I sketched it out by hand. This included the function of the buttons, the colour scheme and font. I decided to make my quiz a multiple choice quiz in order to keep it a consolidation exercise and leave as I know that pupils would have previosuly learnt elements of the content and

---

## Pages

Are you ready? - This is a page is the Homepage which welomes the users and gives them two options to choose from clicking. The 'How to Play'? button or the button to 'Play' the game.  
How to Play? button -By clicking on this button gives the user a brief description of how to play the game. The user also has the option to go back to the homepage by clicking the button.
Spinning world - This is purely for a visual effect and gives users areminders of what thw quiz is about.  
Go Back button - This button takes the user to the Homepage.
Play button - Here the user has clicked on the button and has entered the game. The user is able to read the questions and select the answer they think is correct.


Modal with built in form and submit button - The modal is triggered by the 'Book Now' call to action button, and allows users to complete a form and submit their details to receive instructions on how to finalise their ticket booking. Each of the form's fields are required. Currently, no further action is taken when the 'Submit' button is clicked - this is a limitation due to the scope of the project.
'Limited availability' alert - This is a banner above the 'Book Now' button that alerts the user to the fact that there is limited ticket availability for that particular concert.
'Sold Out' disabled button - This button allows the user to see that the particular concert is sold out. The button is disabled and is for information purposes only.
contact.html
Form with submit button - Allows users to book the band to perform at their events by completing the form and submitting their details. Currently, no further action is taken when the 'Submit' button is clicked - this is a limitation due to the scope of the project.
Form dropdowns - Some of the form's input fields have dropdowns, which allows users to select the relevant option from a list of options.
Form date selector - Allows users to choose the desired date that they want to book the band by clicking the date selector icon, which displays a calendar.
Form number input field with min and max range - Allows users to input the number of attendants to the event by either typing the number directly into the input field, or by using the higher or lower selectors. This field has a minimum value of 20 and a maximum value of 999999999.
Features Left to Implement
Once I've learnt JavaScript and back-end web development, I will add further functionality to the existing features on my website.

---

## HTML5

The project uses HTML5 to create the basic elements and content of my website.

## CSS3

The project uses CSS3 to add custom styles to the elements and content of my website.

## Bootstrap v4.3

The project uses Bootstrap v4.3 to add a responsive grid system, prebuilt components, plugins built on jQuery, and Bootstrap styles to my website, before adding my custom styles.

## JavaScript

The project uses JavaScript from Bootstrap which is required to add functionality to some of Bootstrap's components.

## Googleapis.com

The project uses Google Fonts to style the text and suit the style of the quiz.

## Font Awesome

The project uses Font Awesome for the social media links and the hamburger button on my website.

## GitHub

I've used GitHub as a remote repository to push and store the committed changes to my project from Git. I've also used GitHub pages to deploy my website in a live environment.

---

## Testing Checklist

HTML and CSS Validation
I used the W3C HTML Validator tool to validate my HTML code.
I used the W3C CSS Validator tool to validate my CSS code.

---

## Interesting Bugs or Problems

Deploying my project - I found it very challenging to deploy my project to GitHub. >>>>>>>
'Submit' button on Book Us form - Once I entered the information and submitted the form, the form kept routing me through to the index.html page. After speaking with my mentor, he asked me to check the value of the action attribute of the <form> element. The issue was that the value I was using was action="/". Once I changed this to action="contact.html" the issue was resolved.
'Submit' button on Book Us form - Once I entered the information and submitted the form, I kept getting a '405 Not Allowed' error message, but this was only happening in the live environment and not the testing environment. I posted this in the Slack community and was given the advice to change the method value to get instead of post. This resolved the error.

---

## Deployment

The hosting platform that I've used for my project is GitHub Pages. To deploy my website to GitHub pages, I used the following steps:

Loaded the terminal window in my >>>>>> workspace.

Initialised Git using the git init command.

Added all files to the Staging area (Git) using the git add . command.

Committed the files to Git using the git commit -m "Initial commit" command.

Created a new repository in GitHub called 'monkees-milestone-project-one'.

Copied the below code from GitHub into the terminal window in my Cloud9 workspace:

git remote add origin https://github.com/hebs87/monkees-milestone-project-one.git

git push -u origin master

Entered my GitHub username and password to push the files from Git to GitHub.

Went into 'Settings' on my repository page in GitHub.

Selected the 'master branch' option under the 'GitHub Pages' section.

Ran several regular commits throughout my project.

Repository Link
https://hebs87.github.io/monkees-milestone-project-one/

Running Code Locally
To run my code locally, users can download a local copy of my code to their desktop by completing the following steps:

Go to my GitHub repository.
Click on 'Clone or download'.
Click on 'Download ZIP'.
Once dowloaded, extract the zip file's contents and run my website locally.
Credits
