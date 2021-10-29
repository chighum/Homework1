# Homework 1 - Refactoring

## Description

This repository represents all the work I did to complete the Homework 1 of the DU Coding Bootcamp on refactoring an existing code. For this homework assignment, I was tasked by a marketing agency with taking existing index.html and style.css files and editing them to follow accessibility standards. Not only does following accessibility standards allow for people with disabilities to access the website using assistive technologies, but it also makes the site optimized for search engine recognition, thus resulting in more traffic to the site and in turn more business. In order to do this I added accessible alt attributes to each of the images and icons on the website in order to explain what they illustrate.

Beyond that request from the marketing agency, I thought it was a good idea to check the existing codebase and attempt to improve it for long-term sustainability. In checking the existing website I found one of the links in the nav bar was not functioning properly and was able to add the correct id information to make it work. I also noticed website didn't have a descriptive title, so I added the title "Horiseon Marketing Agency". The existing index.html file was full of div tags with classes within them, so I cleaned it up by replacing div with semantic HTML tags header, nav, main, section, aside, and footer. In turn, I had to edit the CSS file by replacing the previously used classes with the new sematic HTML tags. I also found that the existing style.css file had a lot of unneccessary and repetitive aspects that could be consolidated now that I was using semantic HTML tags. Lastly, I reorganized the CSS file by ordering it corresponding to the semantic tags and added comments to help clarify any potentially confusing parts.

Overall, this results in a much cleaner and more concise HTML and CSS file that create a website that is both optimized for search engine recognition and long-term sustainability. Throughout this process I learned new semantic HTML tags such as main and aside in order to replace all the different div tags in the original HTML file. This also allowed me to strengthen my knowledge of how HTML and CSS files work together in order to create a website, because for everything I replaced in index.html, I had to make a corresponding edit in the style.css file.

## Installation and Contribution

In order to download and edit the project repository simply fork this repository into your own GitHub profile and follow the GitHub steps for cloning a repository onto your local hard drive. From there you can edit both the index.html and style.css to your own liking and upload it to your own GitHub repository.

## Usage

This website can be can be accessed at https://chighum.github.io/Homework1-Refactoring/, and is a great stock template for a marketing agency website. You can also see a screen shot of the website below:

`md ![alt text](./assets/images.Screenshot.png)`
