---
layout: page
title: ATM Simulation 
description: a project to demonstrate the working of an A.T.M
img: assets/img/3.jpg
importance: 2
category: work
---

The ATM will service one customer at a time. A customer will be required to enter an account number, personal identification number (PIN) – both of which will be sent to the database for validation on login. The customer will then be able to perform one or more transactions. If the database determines that the customer’s Account Number and PIN is invalid at login, the customer will be required to re-enter the credentials before logging in. The ATM application will communicate with the database on each transaction and verify the same. In the case of an amount withdrawal, a second message will be sent after the transaction is completed indicating successful transaction completion. The ATM will provide the customer details of each successful transaction, showing the auto generated transaction id, date, time, amount, type of transaction and account number thus providing easy access to the data for the customer. Users can also view their account balance.

<!-- To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/atm1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/atm2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/atm3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    At the top is the Authentication page, center is the Home page , lastly the balance page.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/atm5.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/atm6.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/atm8.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    left is the withdraw page, centre is the loading page, lastly the pin change
</div>
<div class="row justify-content-sm-center">
   <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/atm7.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Mini statement
</div>

This project was worked as part of Object oriented concepts mini-project.

Contributors:  Oren, Pratheek.




<!-- 
The code is simple.
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
