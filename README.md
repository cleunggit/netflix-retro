Juno College Web Development Bootcamp - Project 3

## Table of contents

- [Overview](#overview)
  - [Objective](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Authors](#authors)

## Overview

### Objective

A Netflix clone using the MovieDB API that displays new releases

### Screenshot

![](screenshots/screenshot.png)

### Links

- Solution URL: [Code](https://github.com/cleunggit/netflix-retro)
- Live Site URL: [Preview](https://hopeful-nightingale-35991f.netlify.app/)

## Our process
### Pseudo Code
***App Component***

// Create state items to hold data coming from the third-party API
// - movies

// Once the component has been loaded (mounted) call the local method (getMovies) to get a list of New Releases

// A local method (getMovies) to make the third-party API call without user input
// - when successful, update the state (movies) with new data
// - if unsuccessful, display error message

// A local method (addToMyList) to handle adding an item to myList database (firebase)
// - will save movie properties (key?) to db


// Render the application
// - header
// - gallery of new releases
// - modal
// - footer

// ***Result Component***

// Create a component to display data from the API
// This component will get data (movies) passed in as props
// Create a component to display data (modal)from Firebase
// This component will get the data(myList) passed in as props and makes a call to the API to get the image


### MVP
1. Landing page that displays new release titles

### Stretch Goals
1. Allow user to add/remove movies to their watch list
2. Display watch list as a modal


### Wireframe
![](screenshots/wireframe.png)


### Built with

- React
- Semantic HTML5 markup
- SCSS
- JavaScript

### What I learned

- React Hooks
- React Components
- Working with RESTful APIs

## Author

- Twitter - [@CodeLikeChris](https://www.twitter.com/CodeLikeChris)
- LinkedIn - [Christopher Leung](https://www.linkedin.com/in/christopher-leung-55ab8840/)
- Medium  - [@cleungdev](https://cleungdev.medium.com/)