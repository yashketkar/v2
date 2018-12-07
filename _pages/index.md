---
layout: splash
title: "Hello World"
permalink: /
date: 2017-11-01T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-1.jpg
  caption: "Photo credit: [**Negative Space**](https://www.pexels.com/photo/coffee-writing-computer-blogging-34676/)"
excerpt: "I'm Yash Ketkar, a software engineer focused on building efficient &amp; beautiful experiences."
intro:
  - image_path: assets/images/crop.jpg
    alt: "placeholder image 1"
    title: "Background"
    excerpt: "I am currently working as a Software Engineer at Cerner Corporation. I have a Master's degree in Computer Science from Indiana University, Bloomington and a Bachelor's degree in IT Engineering from University of Mumbai. Previously, I worked as a Software Engineering Intern at Telenotes Inc. and later as a Web Developer at the Kelley School of Business. My goal is always to write efficient and scalable code while providing engaging user experiences."
feature_row:
  - image_path: assets/images/code.png
    alt: "Programming Languages"
    title: "Code"
    excerpt: "Proficient in Python, Java, Ruby and Javascript."
  - image_path: /assets/images/tools.png
    alt: "Tools and Frameworks"
    title: "Tools and Frameworks"
    excerpt: "Experienced in a variety of frameworks and platforms."
  - image_path: /assets/images/devops.png
    alt: "Agile &amp; DevOps"
    title: "Agile &amp; DevOps"
    excerpt: "Comfortable in using agile development tools."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "Projects Cover Photo"
    title: "Projects"
    excerpt: 'Have a look at my various professional and academic projects.'
    url: "/projects"
    btn_label: "View Projects"
    btn_class: "btn--primary"
we_0:
  - title: "Work Experience :briefcase:"
    image_path: /assets/images/timeline/cerner.png
    alt: "Cerner Corporation Logo"
    excerpt: '**Cerner Corporation** - Kansas City, MO<br/>*Software Engineer* - Jun 2017 to Present<br/><br/>**HealtheLife Notifications**: Working on the HealtheLife Notifications team to build REST APIs using Ruby on Rails for sending push, email and text notifications.<br/> **Jenkins Console Parser**: Developed a Jenkins plugin which allows a user to view the diff between console outputs of two Jenkins builds dynamically in order to easily find if new warnings or errors added to a build.'
we_1:
  - image_path: /assets/images/timeline/kelley.png
    alt: "Kelley School of Business Logo"
    excerpt: '**Kelley School of Business** - Bloomington, IN<br/>*Web Developer* - Aug 2016 to May 2017<br/><br/>Performed responsive web development in multiple web environments and complex analysis of legacy code to build updated web content using modern standards. Participated in Agile Software Development Life Cycle (SDLC) and communicated with technical partners as well as business stakeholders.'
we_2:
  - image_path: /assets/images/timeline/telenotes.png
    alt: "Telenotes Inc. Logo"
    excerpt: '**Telenotes Inc.** - Taylorsville, UT<br/>*Software Engineer Intern (Android)* - May 2016 to Aug 2016<br/><br/>Collaborated with cross-functional teams to define, design and build applications for the Android platform. Unit-tested code for robustness, including edge cases, usability, and general reliability. Worked with external data sources and REST APIs, fixed bugs and improved performance.'
feature_row4:
  - title: "Contact"
    excerpt: 'Send me an email if you would like to get in touch, hire me for your next project, have questions or feedback on my work, or just want to say hello.'
    url: "mailto:yashketkar@hotmail.com"
    btn_label: "Email me"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="left" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="we_0" type="left" %}

{% include feature_row id="we_1" type="left" %}

{% include feature_row id="we_2" type="left" %}

{% include feature_row id="feature_row4" type="center" %}
