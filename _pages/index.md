---
layout: defaults/page
permalink: index.html
narrow: false
title: Welcome to My Personal Portfolio
---
This site exists to show-off some of my work as well as anything I might find interesting and worth sharing

## Who am I?
I am hard-working and capable student currently in my 4th and final year of persuing my undergraduate degree in Mechatronic engineering from the University of Cape Town. 

My goal is to always be an asset to any team I am a part of. I believe my level-headedness and ability to look analytically to observe patterns and solutions through chaoes allows me to achieve this. 

Thus far, my education has primarily been centred around mechatronics and and control systems engineering, these are fields I find very interesting but I also seem to have a knack for signal processing as well as an interested in embedded systems engineering and machine learning. 

Feel free to [read more about me]({{ site.baseurl}}{% link _pages/about.md %}), peruse my [CV]({{ site.baseurl}}{% link _pages/CV.md %}) or [reach out to me]({{ site.baseurl}}{% link _pages/details.md %})


### Most Recent Project

{% for post in site.posts limit:1 %}
{% include components/post-card.html %}
{% endfor %}


