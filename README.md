# jyua9844-tracker

## About the Interface Design 
color used: C1E961, 0B1C2E, 1E2E3D, FFFFFF
Basically,  the design of the components in the ,mobile version remains the same as the web version. However, the size and scale of the elements are different to fit the different screen sizes. 

 Screen Size for the application 
 2560 px x 1600 px for web version
 414 px x 896 px for mobile version

## About the Application
![Alt text](Readme%20Img/starting%20page.png)
The user input and selects information, mainly including name and time, etc. Clicking the complete button, the user information will be saved in the page container and displayed on the right side of the page.

![Alt text](Readme%20Img/delete.png)
The user can view the information that has been added to the system on the right side of the page and can select the input values and click the delete button to delete it. The information will be deleted from the page and will no longer be saved in the container.

## Build the Application
(1) HTML (HyperText Markup Language): a markup language used to create and organize the content of Web pages, HTML can define text, images, links, tables, forms and other elements, so that Web pages can present a variety of rich content and interactive effects.
(2) CSS (Cascading Style Sheets): is a style sheet language used to control the style and layout of Web pages. CSS can define text, colors, fonts, borders, backgrounds, layouts and other styles, so that Web pages can present a variety of beautiful, clear appearance and typographic effects.
(3) JavaScript: a scripting language used to achieve interactive and dynamic effects on Web pages. JavaScript can modify HTML and CSS elements, respond to user events, achieve dynamic effects and data interaction, and other functions, making Web pages more interactive and dynamic.
(4) Bootstrap: is a front-end development framework based on HTML, CSS and JavaScript. bootstrap provides a rich CSS and JavaScript components, including grid systems, forms, buttons, navigation, drop-down menus, etc., can help developers quickly build responsive, mobile-first Web applications.
(5) jQuery: A rapid and concise JavaScript library that simplifies HTML document traversal, event handling, animation effects, and Ajax interactions, making it easier for developers to manipulate page elements and improve the interactivity and user experience of Web applications.

##  Deployment Procedure

# Importing jQuery and Bootstrap
To use jQuery and Bootstrap, you need to download the latest versions of the jQuery library and Bootstrap library from the official website. Unzip the downloaded files and you will get the jquery.min.js file and bootstrap.min.css file respectively. Copy these files into the project to use the third-party libraries.

# Project directory

The project can be divided into three folders: css, js, images and index.html file, where the css folder stores the element styles defined in Bootstrap framework and our own element selectors and their element styles for the html file; the imgaes folder stores the image files needed in the project; the js folder stores the Bootstrap framework and the Jquery framework defined in the javascript script, in order to make the main file more convenient to complete the functional design; index.html is the main file that we need to use.

# Operating the Application
The main file used is index.html. This html file displays the main interface layout required by the system, including the text field and the multi-line theme layout as well as the complete button. The html file uses js, css and other files from other folders, each of which is required for operating.

The html file is written in div + css blocks. The main part can be divided into five blocks, which is: defining the heading information of the interface, displaying the content of the header, displaying information such as Drill Tracker Record and track your tennis training program and user input.  The user can enter information, and by clicking the user can enter information, click on the complete button to display it on the page, and delete the information added by the user; define the View Training Summaries and other information; define the Buy Category information; define the Groundstroke Footwork. 

In addition to the js script file in Bootstrap and Jquery framework that we need to use, we also define individual JavaScript functions in this file, which is mainly used to add, delete, and check the data in the container and the display of the page. At the same time, the js function will be triggered with the button click event binding. By clicking the complete button, the information entered by the user is processed, saved in the container and displayed on the page. By clicking the delete button, the information entered by the user is processed, deleted in the container and no longer displayed on the page.

## App Configuration and Guidance to Future Development
Resolution and screen size are very important considerations in web project development, as they directly affect the presentation of the user interface and user experience. The current development environment for the web project is a 15-inch laptop with a resolution of 1920x1080, which is the most suitable platform for viewing application information. It was also important to ensure that the size and layout of the interface could be adapted to different devices and resolutions to ensure that it would render well on a variety of platforms.

The web page can interact with other applications to achieve more complex and better functionality. The web page is not currently set up with a Web API. However, users can invoke the project's functionality in an automated program through the project's interaction path in order to provide services for other projects. 
