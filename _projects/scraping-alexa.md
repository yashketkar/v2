---
title: "Scraping Alexa"
excerpt: "Scraping top 500 websites from Alexa Internet using a python script."
header:
  teaser: /assets/images/projects/alexa-top-500-th.png
sidebar:
  - title: "<i class=\"fab fa-github\" aria-hidden=\"true\"></i> <a href=\"https://github.com/yashketkar/AlexaTop500\">GitHub Repo</a>"
    image: /assets/images/projects/alexa-top-500-sb.png
    image_alt: "thumbnail"
  - title: "Languages/Technologies Used"
    text: "Python"
---
I wrote this script as a part of an interview round. I was given the following requirements:

> The task at hand is to gather the list of top N sites from Alexa (http://www.alexa.com/topsites).  Please be sure to read the following requirements carefully:
> * You will receive input via the command line as to the size of N
> * You will be interfacing with the Alexa website, and will be reading through the HTML files they produce
> * You will need to account for paging
> * You will need to make the process as robust as possible
> * You may not use any external libraries
> * The output will be printed to stdout
> * You are free to ask any questions throughout the process

The python script which I wrote prints the top N links from Alexa Top 500 websites given the value of N. The value of N would be read from the command line if no command line arguments are specified. It would then print the top N websites from http://www.alexa.com/topsites to stdout.

04/02/2018 Update:
It seems like Alexa does not manually specify pages listing the top 500 websites anymore.
So http://www.alexa.com/topsites/global;1 would be redirected to http://www.alexa.com/topsites/global;0
So this script should now only scrape top 50 websites from the Alexa page.
For more websites you can use the Alexa API https://aws.amazon.com/awis/ or buy the Alexa service subscription: https://www.alexa.com/plans
