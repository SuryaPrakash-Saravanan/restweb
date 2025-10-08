# Ex.07 Restaurant Website
## Date:07/10/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Zeno Cafe</title>
  <style>
    body {
      margin: 0;
      background-color: black;
      color: white;
    }
    header {
      background-color: black;
      padding: 20px;
      text-align: center;
      font-size: 28px;
      font-weight: bold;
    }
    nav {
      background-color: black;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 20px;
      font-weight: bold;
    }
    nav a:hover {
      color: yellow;
    }
    .container {
      text-align: center;
      padding: 40px;
    }
    .quote {
      font-weight: bold;
      font-size: 20px;
      margin-top: 20px;
    }
    .normal-text {
      font-size: 16px;
      margin-top: 10px;
    }
    img {
      margin-top: 30px;
      border-radius: 15px;
      width: 70%;
      max-width: 700px;
    }
  </style>
</head>
<body>
  <header> ZENO CAFE </header>
  <nav>
    <a href="index.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="admin.html">ADMIN</a>
    <a href="contact.html">CONTACT US</a>
  </nav>

  <div class="container">
    <div class="quote">“GOOD FOOD IS THE FOUNDATION OF GENUINE HAPPINESS.”</div>
    <div class="quote">“AT ZENO, EVERY BITE TELLS A STORY.”</div>
    <div class="normal-text">Welcome to Zeno Cafe — where taste meets tranquility.</div>
    <div class="normal-text">Enjoy our carefully crafted dishes made with love and passion.</div>
    <img src="home.jpg">
  </div>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - Zeno Cafe</title>
  <style>
    body {
      margin: 0;
      background-color: black;
      color: white;
    }
    header {
      background-color: black;
      padding: 20px;
      text-align: center;
      font-size: 28px;
      font-weight: bold;
      letter-spacing: 2px;
    }
    nav {
      background-color: black;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 20px;
      font-weight: bold;
    }
    nav a:hover {
      color: yellow;
    }
    .menu-section {
      text-align: center;
      padding: 30px;
    }
    .menu-section h2 {
      color: yellow;
      margin-bottom: 20px;
    }
    .item {
      margin: 15px 0;
    }
    img {
      width: 200px;
      border-radius: 10px;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <header> ZENO CAFE </header>
  <nav>
    <a href="index.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="admin.html">ADMIN</a>
    <a href="contact.html">CONTACT US</a>
  </nav>

  <div class="menu-section">
    <h2>PIZZA</h2>
    <div class="item">CHICKEN PIZZA – ₹120 <br><img src="cp.jpg" alt="Chicken Pizza"></div>
    <div class="item">CHEESE PIZZA – ₹120 <br><img src="cpi.jpg" alt="Cheese Pizza"></div>
    <div class="item">VEG PIZZA – ₹100 <br><img src="vp.jpg" alt="Veg Pizza"></div>

    <h2>BURGER</h2>
    <div class="item">CHICKEN BURGER – ₹100 <br><img src="cb.jpg" alt="Chicken Burger"></div>
    <div class="item">VEG BURGER – ₹80 <br><img src="vb.jpg" alt="Veg Burger"></div>
    <div class="item">PANEER BURGER – ₹100 <br><img src="pb.jpg" alt="Paneer Burger"></div>

    <h2>NOODLES</h2>
    <div class="item">CHICKEN NOODLES – ₹100 <br><img src="cr.jpg" alt="Chicken Noodles"></div>
    <div class="item">EGG NOODLES – ₹100 <br><img src="en.jpg" alt="Egg Noodles"></div>
  </div>
</body>
</html>

admin.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Admin - Zeno Cafe</title>
  <style>
    body {
      margin: 0;
      background-color: black;
      color: white;
      text-align: center;
    }
    header {
      background-color: black;
      padding: 20px;
      font-size: 28px;
      font-weight: bold;
    }
    nav {
      background-color: #222;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: double;
      margin: 0 20px;
      font-weight: bold;
    }
    nav a:hover {
      color: yellow;
    }
    .member {
      display: inline-block;
      margin: 30px;
    }
    img {
      width: 200px;
      height: 200px;
      border-radius: 10px;
    }
    .role {
      font-weight: 900;
      margin-top: 10px;
    }
    .name {
        font-weight: bolder;
      margin-top: 5px;
      font-size: 18px;
    }
  </style>
</head>
<body>
  <header> ZENO CAFE </header>
  <nav>
    <a href="index.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="admin.html">ADMIN</a>
    <a href="contact.html">CONTACT US</a>
  </nav>

  <div class="member">
    <img src="ceo.jpg" alt="CEO">
    <div class="role">CEO</div>
    <div class="name">SURYA</div>
  </div>
  <div class="member">
    <img src="fo.jpg" alt="FOUNDER">
    <div class="role">FOUNDER</div>
    <div class="name">AASHIF</div>
  </div>
  <div class="member">
    <img src="ec.jpg" alt="EXECUTIVE CHEF">
    <div class="role">EXECUTIVE CHEF</div>
    <div class="name">DANIEL</div>
  </div>
</body>
</html>

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - Zeno Cafe</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
      color: white;
      background-color: black;
    }
    header {
      background-color: black;
      padding: 20px;
      text-align: center;
      font-size: 28px;
      font-weight: bold;
    }
    nav {
      background-color: black;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 20px;
      font-weight: bold;
    }
    nav a:hover {
      color: yellow;
    }
    .contact-box {
      background-color: grey;
      padding: 30px;
      margin: 50px auto;
      width: 60%;
      border-radius: 15px;
      text-align: center;
    }
  </style>
</head>
<body>
  <header> ZENO CAFE </header>
  <nav>
    <a href="index.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="admin.html">ADMIN</a>
    <a href="contact.html">CONTACT US</a>
  </nav>

  <div class="contact-box">
    <h2>CONTACT NUMBER: 9876543210</h2>
    <p>ADDRESS: NO 210/A, ZENO STREET, GREEN AVENUE, CHENNAI - 600045</p>
  </div>
</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot (40).png>) 
![alt text](<Screenshot (37).png>) 
![alt text](<Screenshot (38).png>) 
![alt text](<Screenshot (39).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
