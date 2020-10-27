# Javascript DOM

# Table of Content

- [Javascript DOM](#javascript-dom)
- [Table of Content](#table-of-content)
  - [About](#about)
  - [Prerequisites](#prerequisites)
  - [Instructions](#instructions)
    - [Task/Requirements](#taskrequirements)
        - [First Objective: Landing page](#first-objective-landing-page)
        - [Second Objective: Main Content Page](#second-objective-main-content-page)
        - [CSS Objectives](#css-objectives)
        - [Dom Utilization](#dom-utilization)
  - [Submission](#submission)


## About

In this unit you learned about the DOM and how to manipulate it. This lab will reinforce that knowledge allowing for you to have a better understanding of using the DOM to your advantage.

## Prerequisites

- The DOM
- Events and event listeners

## Instructions

1. Fork and clone this repository.
2. Switch into the lib directory. 
3. Follow below.

The starter code has been provided for you, a static webpage. The `lib/index.html` and `lib/styles.css` include the initial structure and styling. In `lib/script.js`, you will find an array of objects that contain various prominent people of color in the technology field. In order to complete this lab you will need to modify the HTML, CSS, and JavaScript. The twist to this will be to reimagine this static site, incorporating some of your own ideas utilizing the DOM.

### Task/Requirements 
You are to add an additional 3-5 people of your choosing, all of which have to be in the technology and/or engineering field, that you admire to this site and it can be someone you know personally as well. You are to make this site two pages, which incorporate a landing page and a content/main page showcasing the prominent people on your site. 
  
##### First Objective: Landing page
- This page should incorporate an about section, explaining what the site is and your personal connection to it as well. 
- Include a simple navigation bar or two navigation buttons with functionality that users can use to switch between landing page and content/main page. 
- Remove the two icons in top right and left, you can either replace them or remove completely. 
- Change title/heading of page to something of your choosing. 
- Change pre-existing class/id names and create your own. 

##### Second Objective: Main Content Page
- This page should incorporate the people that you are highlighting on the site in addition to those already generated for you. 
- Each person should have a name, bio, and contribution section. (Bios should only be a paragraph or two at most)
- Add text to name, bio, and contribution sections. 
- Add a button with functionality that when clicked it shows the person's bio and their contribution. 
- Add a picture for each of the additional people you have added.
- Change pre-existing class/id names and create your own.

##### CSS Objectives
The CSS of the site is at your leisure as we would like you to make this site your own as it should draw from your own taste. 

##### Dom Utilization 
As stated above, you will be utilizing the DOM to accomplish majority of the task above, in doing so the following must be utilized:
```js
getElementById() – select an element by id.

getElementsByName() – select elements by name.

getElementsByTagName()  – select elements by a tag name.

getElementsByClassName() – select elements by one or more `class` names.

querySelector() – select elements by CSS selectors.

createElement() – create a new element.

appendChild()  – append a node to a list of child nodes of a specified parent node.

append() – insert a node after the last child node of a parent node.

innerHTML – get and set the HTML content of an element.

replaceChild() – replace a child element by a new element.

removeChild() – remove child elements of a node

Dom Event Listeners (this will be needed for button functionality amongst other things.)
```

## Submission
Please submit an issue on this repository. 