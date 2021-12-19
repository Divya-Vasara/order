<!DOCTYPE html>
<html>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box;}

.bg-img{

  min-height: 500px;

  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
 
  position: relative;
}


.navbar {
  width: 100%;
  background-color: #555;
  overflow: auto;
}
.navbar a {
  float: left;
  padding: 12px;
  color: white;
  text-decoration: none;
  font-size: 17px;
}
.navbar a:hover {
  background-color: #000;
}
.active {
  background-color: #4CAF50;
}
@media screen and (max-width: 500px) {
  .navbar a {
    float: none;
    display: block;
  }
}
.dropdown {
  float: left;
  overflow: hidden;
}
.dropdown .dropbtn {
  font-size: 16px;
  border: none;
  outline: none;
  color: white;
  padding: 14px 16px;
  background-color: inherit;
  font-family: inherit; 
  margin: 0; 
}
.navbar a:hover, .dropdown:hover .dropbtn {
  background-color: red;
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
  float: none;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {
  background-color: #ddd;
}
.dropdown:hover .dropdown-content {
  display: block;
}
h1
{
color:tomato;
font-size20px;
}
.bottom-right {
  position: absolute;
  bottom: 8px;
  left: 16px;
}
.container {
  position: absolute;
  margin: 20px;
  width: auto;
}
</style>
<body background="C:\Users\Divya\Desktop\book.jfif">
<div class="bg-img">
  <div class="container">
    <div class="navbar">
      <a class="active" href="#"><i class="fa fa-fw fa-home"></i> Home</a> 
  <a href="C:\Users\Divya\Desktop\HTML\">About Us</a> 
  <a href="C:\Users\Divya\Desktop\HTML\contact.html"><i class="fa fa-fw fa-envelope"></i> Contact</a> 
  <a href="C:\Users\Divya\Desktop\HTML\loginreg.html"><i class="fa fa-fw fa-user"></i> Login/Register</a>
  <a href="#"><i class="fa fa-fw fa-search"></i> Search</a>
</div>
</div>
</div>
</body>
</html>
