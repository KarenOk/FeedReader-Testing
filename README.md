# FeedReader-Testing


## Project Overview

This project is a web-based application that reads RSS feeds. I have written various tes suitess using Jasmine to ensure that everything works as should.

## Getting Started

- Clone or download this project. 
- Open the index.html to launch on your browser.
- All the test specifications are written in feedreader.js
- The main website is integrated with the SpecRunner (which provides a visual interface to test the website).
- Carry out various tests as seen in the SpecRunner. 

## Included Tests
1. Tests for all feeds:
    - *Check that all URLs are defined in the AllFeeds array.*
    - *Check that all names are defined in the AllFeeds array.*

2. Tests for the menu:
    - *Check that menu is hidden initially*
    - *Check that clicking the menu icon toggles the menu visibility.*

3. Tests for in initial entries:
    - *Check that on a successful feed load, there is at least one entry*.

2. Tests for news feed selection:
    - *Check that there's a content change when a different feed is selected.*

