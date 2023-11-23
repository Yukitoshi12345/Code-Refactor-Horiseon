# Refactoring Horiseon Webpage for better Accessibility

Horiseon Social Solutions Services, a prominent marketing agency, entrusted us with the task of refactoring their website's code to enhance its accessibility and search engine optimization (SEO).

## Table of Contents

- [Objectives](#objectives)
- [The Process](#the-process)
- [Output](#output)
- [Screenshot](#screenshot)
- [Installation](#installation)
- [License](#license)

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

 <!-- Navigation Menu -->

 <!-- Figure -->

 <!-- Section -->

 <!-- Image with Alternative Text  -->

Included alt properties with related description for each image.

Changed title from "website" to "Horiseon".

Changed <div> for <header> tag and removing the class.

Changed <div>  for <nav> tag.

Changed <div> for <figure> tag.

Added some empty lines for making the HTML sections easier to identify.

Changed <div class = "content"> to <main> tag to group the main content.

Changed <div class = "search-engine-optimization">, <div class = "online-reputation-management">, and <div class = "social-media-marketing"> to just <section class = "services"> tag.

Changed <div class = "benefits"> to <aside> tag to group the aside content.

Changed <div class = "benefit-lead">, <div class = "benefit-brand">, and <div class = "benefit-cost"> to just <section class = "benefits"> tag.

Changed <div class = "footer"> to <footer> tag to group the footer content.
```
\
The specific findings and modifications to the CSS file
```
Structure and descriptive comments were added to the CSS file, and the css rules were clasified accordingly:

/* ================================= 
 Global rules and element rules
==================================== */

/* ---------- Universal Selector ---------- */

/* ---------- Body ---------- */

/* ---------- Links ---------- */

/* ---------- Paragraphs ---------- */

/* ---------- Marketing Meeting Image ---------- */

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

Changed ".search-engine-optimization", ".online-reputation-management", and ".social-media-marketing" to ".services". Inside main section, for <h2> and <img> tags, changed to ".services h2" and ".services img" respectively.

Changed ".benefits" to "aside".

Changed ".benefit-lead", ".benefit-brand", and ".benefit-cost" to ".benefits". Inside aside section, for <h3> and <img> tags, changed to ".benefits h3" and ".benefits img" respectively.

Changed ".footer" to "footer" and ".footer h2" to "footer h2".

Rules that were simplified into one rule:

.services {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.services img {
    max-height: 200px;
}

.services h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.benefits {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefits h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefits img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```

## Output
By implementing relevant concepts and making precise modifications to the source files, we successfully created a project that is highly accessible, efficient, and easy to understand.

## Screenshot

![](./assets/images/webpage.png)

## Installation
The project was uploaded to [GitHub](https://github.com/) at the following repository:
[https://github.com/yukitoshi12345/Code-Refactor-Horiseon](https://github.com/yukitoshi12345/Code-Refactor-Horiseon)

You can access the deployed application with the GitHub Pages link:
[https://yukitoshi12345.github.io/Code-Refactor-Horiseon/](https://yukitoshi12345.github.io/Code-Refactor-Horiseon/)

## License
This project is licensed under the [MIT License](https://github.com/Yukitoshi12345/Code-Refactor-Horiseon/blob/main/LICENSE).