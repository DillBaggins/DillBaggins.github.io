---
layout: defaults/page
permalink: CV.html
narrow: false
title: My CV
images:
  - https://images.unsplash.com/photo-1421789665209-c9b2a435e3dc?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=5b1016b885e7438c4633109d77368d4d&auto=format&fit=crop&w=1651&q=80
  - https://images.unsplash.com/photo-1476514525535-07fb3b4ae5f1?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=468a8c18f5d811cf03c654b653b5089e&auto=format&fit=crop&w=1650&q=80
  - https://images.unsplash.com/photo-1504626835342-6b01071d182e?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=975855d515c9d56352ee3bfe74287f2b&auto=format&fit=crop&w=1651&q=80
---

## Education
- **2019 - Present**:  University of Cape Town, Mechatronic Engineering Undergraduate degree
  - Deans Merit List (2019)
  - Deans Merit List (2021)
  - Peralex Electronics Prize for top achiever in Embedded Systems II (2021)
  - Deans Merit List (2022)
- **2014 - 2018**: HeronBridge High School, IEB Matric Certificate
  - Graduate with 6 Distinctions  

<br/>
## Skills 
##### █ Programming 
<p class="d-flex align-items-center indent">
  <b>Python</b>
<span class="icon green ml-2">
  {% include entypo/check.svg %}
</span>
<span class="icon green ml-2">
  {% include entypo/check.svg %}
</span>
<span class="icon green ml-2">
  {% include entypo/check.svg %}
</span>
</p>


<p class="d-flex align-items-center indent">
  <b>Java</b>
<span class="icon green ml-2">
  {% include entypo/check.svg %}
</span>
<span class="icon green ml-2">
  {% include entypo/check.svg %}
</span>
<span class="icon green ml-2">
  {% include entypo/check.svg %}
</span>
</p>

<p class="d-flex align-items-center indent">
  <b>Julia</b>
<span class="icon green ml-2">
  {% include entypo/check.svg %}
</span>
<span class="icon green ml-2">
  {% include entypo/check.svg %}
</span>
</p>

<p class="d-flex align-items-center indent">
  <b>MATLAB</b>
<span class="icon green ml-2">
  {% include entypo/check.svg %}
</span>
<span class="icon green ml-2">
  {% include entypo/check.svg %}
</span>
</p>

<p class="d-flex align-items-center indent">
  <b>C</b>
<span class="icon green ml-2">
  {% include entypo/check.svg %}
</span>
</p>

##### █ Electronic Circuit Design and Soldering
##### █ Rudimentary Embedded System Design
##### █ Mechatronics / Feedback Control Systems 

<br/>
## Work Experience
- **December 2019 - January 2020**: EE Intern at Lanced Labratories, Auckland Park, Johannesburg
  - Used KiCAD to assist with the designing of hardware for the monitoring of temperature of medical samples in transit
  - Developed a Java program for communicating with temperature logging hardware
- **December 2020- March 2021** : Electronic Engineering Intern At ThingKing, Cape Town
  - Completed Several lighting projects involving indivudually adressable LEDs using teensy microcontrollers and the Arduino environment
  - Was part of a team that built a 2 axis pen plotter using an Arduino running GRBL
- **December 2021 - February 2022**: Software Engineering Intern at African Robotics Unit, University of Cape Town
  - Wrote a Python application for the display and annotation of point cloud data



## Testing a table 

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      


## Full Feature List

- Installation
  - Designed for Jekyll 3.8
  - Compatible with GitHub Pages
- Configuration
  - Useful data files to quickly generate the profile sidebar and site navigation
  - Easy to configure, minimal options, sensible defaults
- Styling
  - Styled with Bootstrap, proven to work cross-platform
  - Minimal additional SCSS to get in the way
  - Entirely customisable by tweaking the Boostrap SCSS variables
- Layout
  - 2 column layout
  - Context-sensitive sidebars for blogs, documentation pages and normal content
  - Narrow/wide page options
  - Responsive layout built in
  - Lots of helpful includes and components to build out your site
- JavaScript and Components
  - jQuery and Bootstrap JS included
  - Use all the Bootstrap components
- Other goodies
  - Entypo SVG icons included
  - Syntax highlighting for code fragments using Rougify for over 100 different languages
- Blog
  - A collection layout to build a blog with full support for tagging
  - Interactive tag filtering for the blog
- Projects
  - A layout to list your projects, with a documentation-like layout for each project
  - Table of contents generation for documentation pages
- Permalinks
  - Permalinks using baseurl throughout for deployment under a subdir or on GitHub pages
  - Permalinks using .html throughout for deployment to environments not using default directory indexes

## Examples

Here's some quick examples of what it can do.

### Code Highlighting

{% highlight javascript %}
var modulePattern = (function() {
    // your module code goes here
    var sum = 0 ;

    return {
        add:function() {
            sum = sum + 1;
            return sum;
        },
        reset:function() {
            return sum = 0;
        }
    }
}());
{% endhighlight %}

### Bootstrap Components

Here's a CSS component, it's an alert box with the info color:

<div class="alert alert-info">
    A simple info alert!
</div>

And this is a more sophisticated example, using the JS to include a carousel of images:

<div id="carouselExampleControls" class="carousel slide mb-4" data-ride="carousel">
    <div class="carousel-inner">
        {% for img in page.images %}
            <div class="carousel-item {% if forloop.first %}active{% endif %}">
                <img src="{{ img }}" class="d-block w-100" alt="">
            </div>
        {% endfor %}
    </div>
    <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>

The spinner.

<div class="spinner-border text-dark mb-4" role="status">
  <span class="sr-only">Loading...</span>
</div>

### Icons

There's a suite of hundreds of Entypo icons included, here's just a few.

<div class="d-flex align-items-center indent mb-4">
    <span class="icon grey mr-2">
        {% include entypo/clock.svg %}
    </span>
    <span class="icon grey mr-2">
        {% include entypo/cycle.svg %}
    </span>
    <span class="icon grey mr-2">
        {% include entypo/chevron-up.svg %}
    </span>
    <span class="icon grey mr-2">
        {% include entypo/new-message.svg %}
    </span>
    <span class="icon grey mr-2">
        {% include entypo/shopping-cart.svg %}
    </span>
</div>


