---
title: "Edge Detection in Images"
excerpt: "Finding edge seperating the ridge of mountain from the sky using AI."
header:
  teaser: /assets/images/projects/edge-detection-th.jpg
sidebar:
  - title: "<i class=\"fab fa-github\" aria-hidden=\"true\"></i> <a href=\"https://github.com/yashketkar/B551-Elements-Of-Artificial-Intelligence/tree/master/pssapre-sdarekar-yketkar-a3/part2\">GitHub Repo</a>"
    image: /assets/images/projects/edge-detection-sb.png
    image_alt: "thumbnail"
gallery:
  - url: /assets/images/projects/edge-detection/mountain1-input.jpg
    image_path: assets/images/projects/edge-detection/mountain1-input.jpg
    alt: "Mountain 1 - Input"
  - url: /assets/images/projects/edge-detection/mountain1-output.jpg
    image_path: assets/images/projects/edge-detection/mountain1-output.jpg
    alt: "Mountain 1 - Output"
  - url: /assets/images/projects/edge-detection/mountain2-input.jpg
    image_path: assets/images/projects/edge-detection/mountain2-input.jpg
    alt: "Mountain 2 - Input"
  - url: /assets/images/projects/edge-detection/mountain2-output.jpg
    image_path: assets/images/projects/edge-detection/mountain2-output.jpg
    alt: "Mountain 2 - Output"
  - url: /assets/images/projects/edge-detection/mountain3-input.jpg
    image_path: assets/images/projects/edge-detection/mountain3-input.jpg
    alt: "Mountain 3 - Input"
  - url: /assets/images/projects/edge-detection/mountain3-output.jpg
    image_path: assets/images/projects/edge-detection/mountain3-output.jpg
    alt: "Mountain 3 - Output"
---
Performed Edge detection on images of mountains. That is, found the edge seperating the mountain from the sky. Gradient taken using Sobel Filter on images of mountains. Later used Markov Chain Monte Carlo (Gibbs Sampling) to find the ridge of a Mountain. Implementation in Python using NumPy and SciPy.

{% include gallery caption="Edge detection performed on images of mountains." %}
