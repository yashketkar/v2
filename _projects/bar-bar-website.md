---
title: "Xinu (Embedded OS)"
excerpt: "Enhancing and adding features using C."
header:
  image: /assets/images/foo-bar-identity.jpg
  teaser: /assets/images/projects/xinu.png
sidebar:
  - title: "Github Link"
    image: http://placehold.it/350x250
    image_alt: "logo"
    text: "(https://github.com/yashketkar/OS-P536-S17)[https://github.com/yashketkar/OS-P536-S17]"
  - title: "Responsibilities"
    text: "Modifying and upgrading various aspects of Xinu OS"
gallery:
  - url: /assets/images/unsplash-gallery-image-1.jpg
    image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
  - url: /assets/images/unsplash-gallery-image-2.jpg
    image_path: assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
  - url: /assets/images/unsplash-gallery-image-3.jpg
    image_path: assets/images/unsplash-gallery-image-3-th.jpg
    alt: "placeholder image 3"
---
In my advanced operating systems course, we worked on enhancing several system level features in the Xinu OS. The OS ran on an ARM based BeagleBoneBlack unit. Using C Programming language, me and my friend Tejas Kumthekar worked on adding features to the memory management modules, built in-memory file systems along with Futures and Semaphores to provide mutual exclusion to user level programs.

{% include gallery caption="Gallery of Xinu OS images." %}

The enhancements were made available through syscalls which could be used by any user level programs. We also added shell commands to the OS, giving us insight into the internal clockwork of an Operating System.