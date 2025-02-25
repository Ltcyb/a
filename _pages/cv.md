---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
* B.A. in Computer Science, University of California, Berkeley, 2026

## Work experience
### Berkeley Brothers
#### Data Research Intern Jun 2024 – Aug 2024
* Implemented an algorithm to efficiently filter and analyze 20 GB of market data using Polars/Pandas, Numpy
* Built webcrawler to gather multiple exchanges’ market data for analysis using NodeJs
* Created a system in C++ to receive and decode SBE packets from broker apis
* Analyzed high volatility market options and designed algorithm to detect volatility spikes

### IBM Accelerate
#### Software Engineer Track Jun 2024 – Aug 2024
* IBM’s univeristy program for training students how to navigate the corporate world and software engineering
* Learned how to communicate and network with fellow colleagues from the same industry
* Learned how to integrate generative AI into React and Nodejs applications and developing with cloud based
solutions

### ezML
#### Machine Learning Intern Feb 2024 – May 2024
* Interned for a computer vision as a service Berkeley Skydeck startup
* Trained computer vision YOLOv8 and TrackNet keypoint models with PyTorch
* Designed object detection algorithms fast moving small objections for live video feeds
* Utilized OpenCV to visualize bounding boxes and keypoints

<!-- #### UC Berkeley EECS Department
##### CS 61A Undergraduate Course Staff I Aug 2023 – Dec 2023
* Hosted Office Hours and Tutor Sessions for a 1300+ student class
* Drafted and wrote Discussion, Lab, Homework, and Project problems
* Content Covered: Recursion, High Order Functions and Currying, Iterators and Generators, Trees, Linked Lists,
Object-Oriented Programming, Interpreters
* Languages Covered: Python, Scheme, SQL -->

<!-- Skills
====== -->

## Projects
<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Talks
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

## Teaching
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>