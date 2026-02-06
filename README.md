# Restaurant-menu
# homepage

<!DOCTYPE html>
<html>
<head>
<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display:block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color:BLUE;
}

body {
  background-image: url("Restaurant.jpg");
  background-repeat: no-repeat;
  background-attachment: fixed;  
  background-size: cover;
}


</style>
</head>
<body>
<center><h1 style="font-family:Algerian; color:white; ">RESTAURANT</h1></center>

<ul>
  <li><a href="home.html">HOME</a></li>
  <li><a href="menu.html">MENU</a></li>
 
  <li><a href="we.html">ABOUT US</a></li>
</ul>
<div class="container">
<center><h1 style="color:white;font-family:Algerian;">ENJOY YOUR MEAL</h1></center>
<center><h1 style="color:white;font-family:Algerian;">NOTHING<br>
BRINGS PEOPLE<br>
TOGETHER LIKE<br>
GOOD FOOD</h1></center>
</div>
<a href="Menu.html">
    <img src=" (data:image/png;) style="width:50%"/></a>
</body>
</html>

# menupage

<!DOCTYPE html>
<html>
<html lang="en">
<style>
body {
  background-image: url("back.jpg");
  background-repeat: no-repeat;
  background-attachment: fixed;  
  background-size: cover;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color:cyan;
}

li {
  float: left;
}

li a, .dropbtn {
  display: inline-block;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover, .dropdown:hover .dropbtn {
  background-color: red;
}

li.dropdown {
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {background-color: #f1f1f1;}

.dropdown:hover .dropdown-content {
  display: block;
}
</style>
</head>
<body>

<ul>
  <li class="dropdown">
    <a href="javascript:void(0)" class="dropbtn">INDIAN</a>
    <div class="dropdown-content">
      <a href="#">dosa</a>
      <a href="#">idli</a>
      <a href="#">poori</a>
      <a href="#">pada pav</a>
     <a href="#">palak paneer</a>
     <a href="#">panipuri</a>
 <li class="dropdown">
    <a href="javascript:void(0)" class="dropbtn">CHINESE</a>
    <div class="dropdown-content">
      <a href="#">noodles</a>
      <a href="#">chicken fried rice</a>
      <a href="#">chilli chicken</a>
      <a href="#">sweet sore chicken</a>
      <a href="#">chowman</a>
        <a href="#">kung pao chicken</a>
<li class="dropdown">
    <a href="javascript:void(0)" class="dropbtn">DESSERTS</a>
    <div class="dropdown-content">
      <a href="#">cakes</a>
      <a href="#">brownies</a>
      <a href="#">muffins</a>
      <a href="#">cookies</a>
     <a href="#">pastries</a>
     <a href="#">ice creams</a>
<li class="dropdown">
    <a href="javascript:void(0)" class="dropbtn">SOFT DRINKS</a>
    <div class="dropdown-content">
      <a href="#">coca-cola</a>
      <a href="#">sprite</a>
      <a href="#">pepsi</a>
      <a href="#">fanta</a>
     <a href="#">7up</a>
     <a href="#">mountain dew</a>
    </div>
  </li>
</ul>
</style>
  <div class="container">
    <div class="menu">
      <CENTER><h2 style="font-family:Algerian;font-size:500%;color:white;"class="menu-group-heading">
        MENU
     </center>
</h2>
      <div class="menu-group">
        <div class="menu-item">
          <img src="indian.jpg" width="250" height="250"> 
          <div class="menu-item-text">
            <h3 style="color:white;" class="menu-item-heading">
              <span class="menu-item-name">the indian style</span>
              <span class="menu-item-price">$12.90</span>
            </h3>
          <div class="menu-item">
          <img src="chines.jpg" width="250" height="250">
          <div class="menu-item-text">
            <h3 style="color:white;" >
              <span class="menu-item-name">chines style</span>
              <span class="menu-item-price">$12.90</span>
            </h3>
            </div>
        </div>
      </div>
      <h2 class="menu-group-heading">
      </h2>
      <div class="menu-group">
        <div class="menu-item">
          <img src="dessert.jpg" width="250" height="250">
          <div class="menu-item-text">
            <h3 style="color:white;"  class="menu-item-heading">
              <span class="menu-item-name">sweet time/dessert</span>
              <span class="menu-item-price">$12.90</span>
            </h3>
          </div>
        </div>
        <div class="menu-item">
          <img src="soft drinks.jpg" width="250" height="250">
          <div class="menu-item-text">
            <h3 style="color:white;" class="menu-item-heading">
              <span class="menu-item-name">refreshment/soft drinks</span>
              <span class="menu-item-price">$12.90</span>
            </h3>
    </div>
  </div>
</body>

</html>

# aboutpage
<!DOCTYPE html>
<html>

<head>
<title>About us Page</title>
</head>
<style>
body {
  background-image: url("about.jpg");
  background-repeat: no-repeat;
  background-attachment: fixed;  
  background-size: cover;
}
</style>
<nav class="navbar background">

<div class="rightNav">
<input type="text" name="search" id="search">
<button class="btn btn-sm">Search</button>
</div>
</nav>
<secAtion class="background firstsection">
<div class="box-main">
<div class="firstHalf">
<h1 style="font-family:Algerian;color:white;">About US</h1>

<h1 style="font-family:Algerian;color:white;">
Here you will get to know the team
members of our company
</h1>
<br>

</div>
</div>
</section>
<section class="service">
<h1 class="h-primary center" style="margin-top:10px;font-family:Algerian;color:white;">
Our Team
</h1>
<div id="services">
<div class="box">
<img src="pranathi2.jpg" width="150" height="150"  alt="picture goes here">

<p class="center">
<a href="Pranathi M S" style="text-decoration:none;color:black;
font-weight:bold;font-family: 'Langar', cursive;color:white;">
Pranathi M S
</a>
</p>
<p style="font-family: sans-serif;color:white;">coe and founder</p>
</div>
<div class="box">
<img src="manya.jpg" width="150" heigth="150"

alt="picture goes here">

<p class="center">
<a href="Manya J" style="text-decoration:none;color:black;
font-weight:bold;font-family: 'Langar', cursive;color:white;">
Manya J
</a>
</p>

<p style="font-family: sans-serif;color:white; ">co-founder</p>
<p style="font-family: sans-serif ;color:white;">Our EMAIL-RESTAURANT@gmail.com</p>


</div>

</section>

<footer class="background">
<p class="text-footer">
                                   

<p class="text-footer">
Copyright ©-All rights are reserved
</p>

</footer>
</body>

</html>





