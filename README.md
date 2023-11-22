# 01 HTML, CSS, and Git: Code Refactor

## Description

Horiseon Social Solutions Services, a prominent marketing agency, entrusted us with the task of refactoring their website's code to enhance its accessibility and search engine optimization (SEO).

## Objectives

The following criteria has to be met:

- The webpage meets accessibility standards.
- When viewing the source code, semantic HTML elements are present.
- The structure of the HTML elements follows a logical order independent of styling and positioning.
- All icon and image elements have accessible alt attributes.
- Heading attributes are in sequential order.
- The title element provides a concise and descriptive title.


## The Process

The specific findings and modifications to the HTML file
```
Structure and descriptive comments were added:

<!-- Header -->

<!-- Main Content -->

<!-- Additional Content -->

<!-- Page Footer -->

Included alt properties with related description for each image.

Changed title from "website" to "Horiseon".

Changed <div> for <header> tag and removing the class.

Changed <div>  for <nav> tag.

Changed <div> for <figure> tag.

Added some empty lines for making the HTML sections easier to identify.

Changed <div class = "content> to <main> tag to group the main content.

Changed <div class = "search-engine-optimization">, <div class = "online-reputation-management">, and <div class = "social-media-marketing"> to just <section> tag.

Changed <div class = "benefits"> to <aside> tag to group the aside content.

Changed <div class = "benefit-lead">, <div class = "benefit-brand">, and <div class = "benefit-cost"> to just <section> tag.

Changed <div class = "footer"> to <footer> tag to group the footer content.
```
\
The specific findings and modifications to the CSS file
```
Structure and descriptive comments were added to the CSS file, and the css rules were clasified accordingly:

/* ================================= 
 Global rules and element rules
==================================== */

/* ================================= 
 Structural content style
==================================== */

/* ---------- The Header ---------- */

/* ---------- Main Content ---------- */

/* ------- Additional Content ------- */

/* --------- The Page Footer --------- */

Changed ".header" for "header".

Changed "header div" to "header nav".

Changed ".hero" for ".marketing-meeting-image".

Changed ".search-engine-optimization", ".online-reputation-management", and ".social-media-marketing" to "main section". Inside main section, for <h2> and <img> tags, changed to "main section h2" and "main section img" respectively.

Changed ".benefits" to "aside".

Changed ".benefit-lead", ".benefit-brand", and ".benefit-cost" to "aside section". Inside aside section, for <h3> and <img> tags, changed to "aside section h3" and "aside section img" respectively.

Changed ".footer" to "footer" and ".footer h2" to "footer h2".

Rules that were simplified into one rule:

main section {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

main section img {
    max-height: 200px;
}

main section h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

aside section {
    margin-bottom: 32px;
    color: #ffffff;
}

aside section h3 {
    margin-bottom: 10px;
    text-align: center;
}

aside section img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```

## Webpage Image

![](./assets/images/webpage.png)

## Installation
The project was uploaded to [GitHub](https://github.com/) at the following repository:
[https://github.com/yukitoshi12345/Code-Refactor-Horiseon](https://github.com/yukitoshi12345/Code-Refactor-Horiseon)

You can access the deployed application with the GitHub Pages link:
[https://yukitoshi12345.github.io/Code-Refactor-Horiseon/](https://yukitoshi12345.github.io/Code-Refactor-Horiseon/)

## License
This project is licensed under the MIT License.