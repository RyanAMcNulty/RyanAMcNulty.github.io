---
layout: page
title: Build
permalink: /how-to-build-a-website/
---
## How to build a website with Github Pages, Jekyll, & custom domain

This page will describe all the steps that went into building this website for self reference as well as guidance for others.

A lot of this was achieved by following a Jekyll tutorial series produced by Mike Dane (formerly Giraffe Academy) on Youtube: [Jekyll - Static Site Generator - Tutorial](https://youtu.be/T1itpPvFWHI).

To update gh repository (and subsequently the website itself) navigate to directory housing all documents pertaining to website (created with Jekyll build command) in terminal and, after making any edit, type:
{% highlight bash %}
% git add .
% git commit -m "message goes here"
% git push origin gh-pages #gh-pages is name of branch where all website files are stored in gh repository
{% endhighlight %}

Cool so that little code snippet worked. Onwards and upwards...
