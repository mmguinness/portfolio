---
layout: post
title:  "Remote book club, Part 1"
date:   2022-05-12 23:23:00 +0100
categories: projects
---

<p align="center">
<img src="../../../../public/Mvp.png" alt="MVP" width="800" />
</p>

Model View Controller (MVC) sketch above from my notes for week 3 of Makers Academy. It is nice to look back and realise how far I have come from needing to map out every step of the development process.

To ensure my understanding of concepts like the common MVC software development pattern, I have started a [new project](https://github.com/mmguinness/remote-book-club). It is a simple website to host a remote book club. 

I sketched up a few wireframes and ideas for my MVP. At first I want it to be really simple, just a bulletin-board of the current book, and a history of what has been read. After I achieve this I would like to add a sign-in option where my friends can log in and add their own book suggestions. This could be a good opportunity to add a database to store this info and ensure everyone can access and contribute to the site.

<p align="center">
<img src="../../../../public/Mvp-wireframe.png" alt="MVP" width="800" />
</p>

For practice, I have chosen JavaScript as my base language. Starting with Node, to setup and manage my project environment, I used Express (web framework for Node.js), ESBuild (to bundle my files), Jest (for testing), and Bulma (for html styling).  

You can see the work-in-process site on [GitHub here](https://github.com/mmguinness/remote-book-club). Some screenshots of my working files below, showing my test driven development (TDD) process. All information about the books is hard-coded for now and to the model object in the main (controller) file.

## Model

<figure>
  <img src="../../../../public/Mvp-model.png" 
  alt="Model" 
  width="100%">
</figure>

## View

<figure>
  <img src="../../../../public/Mvp-view.png" 
  alt="View" 
  width="100%">
</figure>

## Controller

<figure>
  <img src="../../../../public/Mvp-controller.png" 
  alt="Controller" 
  width="100%">
</figure>


