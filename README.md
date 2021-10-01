# Covid Taichung Frequently Asked Questions Repo
This is not a functioning repo. It is only intended to simplify viewing the code
related specifically to the latest version of the Covid Taichung FAQ page, including the faq search bar and collapsible question/answer pairs.

There is no github pages for this repo.

The original repo can be found at [covid-taichung/cfiw](https://github.com/Covid-Taichung/cfiw).

## File Guide

### faq.html (root)
This is the HTML file for the map page. It contains a script tag which makes fetch requests to get the map data. Then it calls the initMap function to initialize the Google Map. It also contains script tags which link to the JS files that contain the functions that make the map work. [Link to code](https://github.com/markoco14/covid-taichung-faq-repo/blob/main/faq.html).

### dynamic-faq-test.js (faq folder)
This files contains the functions written for both the FAQ search bar and the FAQ content (question/answer pairs). [Link to code](https://github.com/markoco14/covid-taichung-faq-repo/blob/main/faq/dynamic-faq-test.js).

### faqDataJSON.json (faq folder)
This file contains the FAQ content stored in JSON format. Each object in the array contains an ID, along with content for the questions and answers on the page. [Link to code](https://github.com/markoco14/covid-taichung-faq-repo/blob/main/faq/faqDataJSON.json).

### dnu-files.js (faq folder)
This file contains all the *do not use* words, letters, and symbols for the FAQ search bar. These *do not use* words help us clean the users search query to provide them with more accurate search results. [Link to code](https://github.com/markoco14/covid-taichung-faq-repo/blob/main/faq/dnu-files.js).

### the related CSS files are also included in the css folder
 

 
