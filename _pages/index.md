---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome to My Personal Portfolio
---
This site exists to show-off some of my work as well as anything I might find interesting and worth sharing

## Who am I?
I am hard-working and capable student currently in my 4th and final year of persuing my undergraduate degree in Mechatronic engineering from the University of Cape Town. 

Feel free to [read more about me]({{ site.baseurl}}{% link _pages/about.md %}), peruse my [CV]({{ site.baseurl}}{% link _pages/CV.md %}) or [reach out to me]({{ site.baseurl}}{% link _pages/details.md %})


### Most Recent Project

{% for post in site.posts limit:1 %}
{% include components/post-card.html %}
{% endfor %}


