---
permalink: /spatialA/
title: "Spatial Data Assignment"
---
## Settling on a Topic

We’d been given a pretty large repository of data from the Zanzibar Gazette, and it was difficult to settle on a single topic. There was such a wide range of possible topics, and I spent some time going through the data we had been given. I eventually settled on two pages from the 1919 version of the gazette, which was the Statement of Imports into Zanzibar in August, 1919. Here they are, pictured below:

![Image 1](/assets/images/Spatial/s1.png "Image 1")

![Image 2](/assets/images/Spatial/s2.png "Image 2")

## Modeling the Data with the Help of LLMs

Counting the row at the bottom that tallies the overall sum, there is a total of 113 rows of data in these two pages. There are 22 columns—the first one is the name/type of merchandise, and the rest are seven sets of three columns that respectively represent the weight, number of packages, and value of the merchandise. The first six sets are split up based on regions of the world (UK; rest of Europe; America; India and Burma; rest of Asia; Africa), and the last set calculates the total values for each row of merchandise.

I enlisted the help of LLMs to give me a good start on modeling the data into digital spreadsheets. The general method was to provide the LLM with images of the two pages and ask it to create a spreadsheet/text for a csv file for me using the data provided in said pages. I tested this out on multiple models in search of the best one.

A necessary disclaimer: I have minimal experience using LLMs—in fact, ~90% of my total LLM usage stems from the exercises and assignments from our class. I fear that I may have been unable to utilize the LLMs as well as many others due to my comparative unfamiliarity with these tools. On the bright side, this was a great exercise and an interesting experiment for me.

ChatGPT

As most of my limited experience using LLMs is with ChatGPT, this is the first LLM I tried.
