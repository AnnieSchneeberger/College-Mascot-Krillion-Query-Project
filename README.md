# College-Mascot-Krillion-Query-Project
By: Annie Schneeberger

This is an in-progress project for my INFO 4617: Web Data Science course. The goal of this project is to produce a data table of U.S. college mascot "species" or categories, similar to the data table structure of the web trivia game "Krillion". I plan to use url-join functions to navigate from https://en.wikipedia.org/wiki/Lists_of_American_colleges_and_universities to specific colleges to pull their mascots listed in Wikipedia's information boxes. Once I have scraped that data, I plan to order it based on how common the mascot type is in order to answer my research question:
"What is the rarest type of college mascot?"
Taking it one step further, I would like to assign point values to each answer, similar to how the actual web game does.

**Data:** I am collecting my data solely from Wikipedia in order to keep naming and scraping methods consistent and logical on my end. My final collection was completed on November 8th, 2026. There were several points at which I cleaned the data. Initially, I scraped a list of 4224 universities across all 50 states, beginning by creating a list of links each state's list of colleges and universities. Of those 4224 returned universities, 8 of them were obviously not actual universities. Of the remaining 4216, 360 did not have Wikipedia links. After I had a list of every university's valid Wikipedia link, I scraped the mascot names from each page. Only 1591 of the universities with a valid link had a listed mascot. After that, I put it into an Excel sheet and formatted it into a final table. Every one of the 1591 mascots, their university, their state, and the university Wikipedia link is currently available in the repository. Nothing has been left out, as there is no sensitive data. 

Methods:

Findings:

How to Reproduce:
