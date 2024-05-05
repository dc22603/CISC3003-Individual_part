# CISC3003-Individual_part
This individual project is to develop a shopping cart in full-stack web development.<br>
Attention: this project is for education purpose.

<br>

>The project uses the following tools to develop: <br>
>* HTML5
>* CSS3
>* Javascript and jQuery
>* PHP
>* MySQL
<br>

## Database Setup:
Create a database called "cart" in your database system.<br>
![](https://github.com/dc22603/CISC3003-Individual_part/raw/main/readmeimg/setup1.jpg)
<br>
Then import the file called "cart_system.sql" in the downloadable content.<br>
![](https://github.com/dc22603/CISC3003-Individual_part/raw/main/readmeimg/setup2.jpg)
<br>
Finally you will have something like this<br>
![](https://github.com/dc22603/CISC3003-Individual_part/raw/main/readmeimg/setup3.jpg)
<br>
Remember to change the port of config.php (Which you can find in the above downloadable content) to your MySQL's port!<br>
>\<?php
$conn = new mysqli("localhost:3316","root","","cart"); // Change the port here <br> 
&nbsp;&nbsp;&nbsp;&nbsp;if($conn->connect_error){<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;die("Connection Failed!".$conn->connect_error);<br>
&nbsp;&nbsp;&nbsp;&nbsp;}<br>
?>

### This is the main page<br>
>You can add items here into cart by pressing "Add to cart" here.
<br>

![](https://github.com/dc22603/CISC3003-Individual_part/raw/main/readmeimg/index.jpeg)

### This is the cart page<br>
>This page shows user what you have added to the cart and provide a button for user to checkout.
<br>

![](https://github.com/dc22603/CISC3003-Individual_part/raw/main/readmeimg/cart.jpeg)
### This is the checkout page<br>
>By pressing the checkout button in cart page, user will see this page.
<br>

![](https://github.com/dc22603/CISC3003-Individual_part/raw/main/readmeimg/checkout.jpeg)

<br>

## Showcase
![](https://github.com/dc22603/CISC3003-Individual_part/raw/main/readmeimg/showcase.gif)

