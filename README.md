# Responsive Personal Portfolio Site February 4, 2020

This repository contains all of the code for my personal website featuring my latest web development projects, as well as a medium bio about myself, and a contact page for visitors to my site. The code is built primarily from Bootstrap 4 code snippets, but also includes a custom .css to address some styling issues. The site is meant to be 100% responsive across all devices, however there are some additional edits that still need to be made to readch 100% responsiveness.

## 1.Customizations:

Navbar: I preferred having a navbar that is fixed across all screens featuring a hamburger menu on smaller screens. In the screenshot, you can see that the hamburger menu is displayed at the tablet size when I would like the menu links to still show. I would like to add media query or add to my style.css file to get the hamburger menu to only display on phone screens, not on tablet screens. ![image](https://user-images.githubusercontent.com/57377678/73813161-25f5c700-47ad-11ea-97d3-9b1922da347b.png)

Footer: I attempted a sticky footer, but due to my lack of knowledge of Bootstrap internal customizations I could not figure out the media query to make it stay appropriately fixed with regards to responsiveness. The site currently looks great on desktop only. Issues still need to be resolved for smaller screens. The footer moves depending on the size of the screen

## 2.Edits to be made:

About Me: I would like to redo my grid (rows and columns) to fix the responsiveness issues.
Jumbotron: there appears to be a slight margin-left when I am looking in the inspector tools
![image](https://user-images.githubusercontent.com/57377678/73813245-6a816280-47ad-11ea-9e2f-00782a65ae7f.png)

Portfolio: There are small but noticeable white borders that need to be removed from .cardbodies.They are also are different sizes which I think means I used the wrong card component
![image](https://user-images.githubusercontent.com/57377678/73813367-c1873780-47ad-11ea-9c32-9c0d2cedac3b.png)

Contact: I do not see any changes that need to be made to the contact form other than the sometimes "floating" footer issue.
Comments: I would like to clean up my comments so they are more comprehensible to other viewers
Media Queries and style.css: customizations via my style.css should resolve most responsive design issues. I left comment reminders to myself.

## 3. Challenges faced:

Mostly around adjusting classes and custom css to make everything fit beautifully on the screen. I successfully created a responsive hamburger menu, but need to add javescript to increase functionality. For example, the hamburger menu when clicked only goes away once clicked again. I will add custom .js to add an eventListener to animate the hamburger menu only for a few seconds then disappearing on its on instead of the user having to click again.
![image](https://user-images.githubusercontent.com/57377678/73813487-25116500-47ae-11ea-9627-06cb0842048f.png)

## 4. Goals

-To make it more responsive
-Redo my entire grid on my portfolio.html
-Add other pages
-possible change jumbotron color
-figure out how to take better screenshots, my apologies i forgot i had extended display to a second monitor to it did a print screen for both screens and i didn't realize until after I uploaded
