---
layout: page
title: Car purchase recommender
description: A project to recommend cars
img: assets/img/12.jpg
importance: 1
category: work
---

This web application involves a page that accepts input regarding the car features from the user. The user is expected to enter the car company name and can then select various the criterion for their search based on mileage, fuel type, seating capacity and transmission. Based on the specified filters the search will be performed and the data would be retrieved from a website . The scraped data can be stored in a CSV file, an Excel spreadsheet, or a database It scrapes details about the various cars available in the market from the carwaale.com website. The project also features a web application built using Flask that allows the user to get car recommendations based on selected filters.

<!-- To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/home.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/specificcar.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
      <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/search.png" title="Search" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   At the top is the Home page, center is specific car page and lastly the search results
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/car.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Search results for a car
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/getapi.png" title="Home page" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/getid.png" title="Specific car" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/postapi.png" title="Search" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Api endpoints
</div>

This project was worked as part of Application development using Python mini-project.

Contributors:  Oren, Pratheek, Samriddhi





<!-- The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above: -->

<!-- {% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %} -->
