![HTML CSS](https://img.shields.io/badge/HTML-CSS-blue)

<h1 align ="center">Refactoring Horiseon Webpage for better Accessibility</h1>

Horiseon Social Solutions Services, a prominent marketing agency, entrusted us with the task of refactoring their website's code to enhance its accessibility and search engine optimization (SEO).

## Table of Contents

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Process](#process)
- [Output](#output)
- [Screenshot](#screenshot)
- [Installation](#installation)
- [Central Grader Comments](#central-grader-comments)
- [License](#license)

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Process

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

## Central Grader Comments

Grade: 100/100

Marker: Awesome job on the Code Refactor Challenge! You were able to demonstrate your ability to refactor a web app with HTML and CSS. On the same note, great job ensuring your links are all functional and that they correctly navigate users to their desired section of the page. Well done adding 'alt' attributes to all <img> tags for accessibility purposes. You were able to ensure the organization and consolidation of your CSS selector properties. You were also able to properly comment out your CSS code, this will be huge for you when you go back to your work and try to understand the story and approach behind it! Additionally, you were able to correctly deploy your application to a live URL.

Upon deploying your application the browser loads smoothly and without errors. You were able to submit your GitHub URL and your repo contains working organized code! You created a unique name for your repository avoiding words like ‘homework’ and ‘assignment’, and you were able to follow best practices for the file structure and naming conventions. In the same respect, you were able to follow proper coding conventions with indentation, quality commentary and overall structure. You were able to show your work, with multiple descriptive commits, and your repository includes a quality README file that contains a brief description of your application, a screenshot of the completed product and a link to the deployed site. Overall excellent job.

Keep up the great work!

- Sam, Centralized Grading

## License

This project is licensed under the [MIT License](https://github.com/Yukitoshi12345/Code-Refactor-Horiseon/blob/main/LICENSE).
