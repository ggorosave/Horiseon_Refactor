# 01 Module 1 Challenge: Horiseon Websie Code Refactor

## Description

This project is a challenge from the U of A coding boot camp. In this project, I refactored the HTML and CSS of the Horiseon website for better accessibility. In the process of reaching this goal, I made the following changes:

1. The website was given a more concise `<title>` in the `<head>`.
2. All `<div>`s were changed to more semantic elements (`<header>`, `<nav>`, `<figure>`, `<main>`, `<section>`, `<aside>`, and `<footer>`).
3. The feature image was called through HTML instead of CSS so an alt attribute could be added to the image. (The CCS was edited to accommodate these changes.)
4. All images were given alt attributes.
5. Any superfluous class attributes were deleted.
6. The CSS sheet was reorganized to follow the semantic flow of the HTML.
7. Various edits were made to selectors to match changes in the HTML.
8. Selectors and properties were simplified and consolidated where possible.
9. The background colors were darkened in some elements for better contrast. 
10. The font-size of the `<p>` elements was increased for better readability.

While not necessarily a priority to improving accessibility, a `<meta>` tag for viewport and description was added for better SEO.

Through the process of trying to deploy the website, I discovered that GitHub pages did not look for the index file in the Development folder and instead called the README file. In order to fix this problem, I tried several solutions including using a dummy HTML page to lead to the index file in the Development folder. However, these attempted fixes caused many other issues. I decided that moving the index file and assets folder to the root folder would be the simplest solution.

[Refactored Horiseon Website](https://ggorosave.github.io/M1-Challenge/) 

![Mock-up of Horiseon website](./assets/images/01-html-css-git-homework-demo.png)