---
title: "100 Chair Problem Visualization"
excerpt: "Creating an interactive visualization for the 100 chair problem."
header:
  teaser: /assets/images/projects/chair-th.png
sidebar:
  - title: "<i class=\"fab fa-github\" aria-hidden=\"true\"></i> <a href=\"https://github.com/yashketkar/chair\">GitHub Repo</a>"
    image: /assets/images/projects/chair-sb.png
    image_alt: "thumbnail"
  - title: "<i class=\"fas fa-globe\" aria-hidden=\"true\"></i> <a href=\"https://docs.google.com/document/d/1q56K9KaiSTuBPRT22DO0gkxWXPzhQSOrk0uapPfNCSs/edit\">Requirements</a>"
  - title: "<i class=\"fas fa-globe\" aria-hidden=\"true\"></i> <a href=\"https://blooming-shelf-17126.herokuapp.com/\">Visit Website</a>"
  - title: "<i class=\"fas fa-pencil-alt\" aria-hidden=\"true\"></i> <a href=\"https://codepen.io/yashketkar/full/pWBBrz\">View CodePen</a>"
---
I created this web application as a part of an interview round. I was given the following requirements:

The Problem:

Imagine there are people sitting in N chairs arranged in a circle. Each chair is evenly spaced apart from its neighbors. Additionally, each chair is given an number starting with 1 and increasing by 1 to N, such that the chair to the right of a person sitting in chair 1 is numbered 2.

You are standing in the center of this circle of chairs. You start by pointing at the person in chair number 1. You tell this person to leave. When they leave, they take their chair with them and all of the other people sitting in chairs spread out to maintain an even spacing between the chairs. The chair with the lowest number is always closest to the bottom of the circle. The chairs always maintain their original numbering.

Skipping the person sitting in chair #2, you then tell the person sitting in #3 to leave -- that is, you skipped 1 person and told the next to leave. Once #3 has left, you then skip 2 people and tell #6 to leave. Continuing in this fashion, skipping one more person than you did before and telling people to leave, eventually there will be only one chair remaining. At this point, the process is completed. There are no more eliminations and the person in the remaining chair is declared the winner.

The Challenge:

Your task is to build a visualization of this process using provided chair assets ([PNG](https://media1.popsugar-assets.com/static/imgs/interview/chair.png), [SVG](https://media1.popsugar-assets.com/static/imgs/interview/chair.svg)), HTML, CSS, and JavaScript (feel free to also include any libraries or frameworks) using [codepen](https://codepen.io), [jsfiddle](https://jsfiddle.net), or any other online code editor of your choosing. For this exercise, you may ignore mobile layouts (as we have not provided a mobile mock). Additionally, if you are working on a smaller screen, feel free to scale the project such that it fits on the screen that you are working on. If you do scale the project, make sure to do so proportionally such that relative sizes of all visual elements are the same. If you refer to the [mock](https://media1.popsugar-assets.com/static/imgs/interview/100_Chair_Problem.png), you will see that there is a form on the left side, and a circle of chairs on the right side. The form has two inputs and three buttons. 

You can view my solution and the code for this problem from the links in the sidebar.
