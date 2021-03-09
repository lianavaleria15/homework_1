# Code refactor for Horiseon - Marketing Agency

## Description

In this project I refactored the code of a marketing agency's landing page. For this, I improved the codebase to increase its accessibility, by committing a series of changes in both HTML and CSS file.

## Changes I did

### In the HTML file

- I replaced non-semantic elements with their semantic version in both html and css files. For example, in the navigation bar, I replaced elements like 'div' with 'nav'. I also declared a 'main' section, inside which I replaced some of the 'div' with 'section' selectors.
- I deleted extra closing tags that were added after self-closing tags in the main section.

- I corrected links that weren't functioning correctly. To do this, I added property names and values to declaration in the header.
- I added alt attributes to image selectors in order to increase the accessibility of the landing webpage.

### In the CSS file

- In the css file, I updated the class declarations to fit the changes I made in the html file, by renaming the class attributes.
- To signpost the changes made, I added comments before the declaration blocks.
- To avoid the repetition of declaration blocks for image and heading child classes inside 'benefits' class, I applied the class group property.

## Screenshots of the refactored webpage

![Screenshot 1](/assets/images/horiseon_1.png)
![Screenshot 2](/assets/images/horiseon_2.png)
![Screenshot 3](/assets/images/horiseon_3.png)

## Link to deployed application

Click [here](https://lianavaleria15.github.io/code-refactor-horiseon/) to visit the deployed application on GitHub pages.
