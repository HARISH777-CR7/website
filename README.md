# Ex.07 Restaurant Website
# Date:3/10/25
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
````
ADMIN.HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title> BRAINROT - Administration</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header><h1>Our Administration Team</h1></header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="cards">
    <div class="card"><img src=" Screenshot 2025-10-03 142117.png "><h2> HARISH K</h2><p>Manager</p></div>
    <div class="card"><img src=" Screenshot 2025-10-03 142820.png "><h2> AATHISHWARAN K</h2><p>Head Chef</p></div>
    <div class="card"><img src=" Screenshot 2025-10-03 142830.png "><h2> ASHWIN BALAJI V K</h2><p>Assistant Chef</p></div>
    <div class="card"><img src=" Screenshot 2025-10-03 142634.png "><h2>  ISHOWSPEED</h2><p>HR</p></div>
    <div class="card"><img src=" Screenshot 2025-10-03 142717.png "><h2> MALAK</h2><p>Finance</p></div>
    <div class="card"><img src=" Screenshot 2025-10-03 142437.png "><h2> ASHTON HALL</h2><p>Marketing</p></div>
  </section>

  <footer><p>Created by Harish</p></footer>
</body>
</html>


 CONTACT.HTML

 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title> CASANDRA - Contact Us</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header><h1>Contact Us</h1></header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="cards">
    <div class="card">
      <h2>Address:</h2>
      <p>  CASANDRA RESTAURANT<br>
         123 Food Street, Cityville, India</p>
    </div>
    <div class="card">
      <h2>Phone:</h2>
      <p>+91 7200247512</p>
    </div>
    <div class="card">
      <h2>Email:</h2>
      <p> rajharish0089@gmail.com</p>
    </div>
  </section>

  <footer><p>CREATED BY 
                    HARISH K(25013390)</p></footer>
</body>
</html>

INDEX.HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title> CASANDRA - Home</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <img src=" Screenshot 2025-10-03 193922.png " alt="CASANDRA Logo" class="logo">
    <h1> CASANDRA</h1>
  </header>

  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="banner">
    <h1>30% Off This Weekend</h1>
    <p>Enjoy delicious meals with an exclusive weekend discount!</p>
  </section>

  <section class="cards">
    <div class="card">
      <h2>Our New Menu</h2>
      <img src=" Screenshot 2025-10-03 202445.png " alt="Menu">
      <p>Discover our latest dishes crafted with fresh ingredients.</p>
      <a href="menu.html">See our menu</a>
    </div>
    <div class="card">
      <h2>Book a Table</h2>
      <img src=" Screenshot 2025-10-03 195307.png " alt="Book a Table">
      <p>Reserve your spot now and enjoy a fine dining experience.</p>
      <a href="contact.html">Book now</a>
    </div>
    <div class="card">
      <h2>Opening Hours</h2>
      <img src="  Screenshot 2025-10-03 195438.png" alt="Opening Hours">
      <p>
        Mon - Fri: 2pm - 10pm <br>
        Sat: 2pm - 11pm <br>
        Sun: 2pm - 9pm
      </p>
    </div>
  </section>

  <footer>
    <p>Created by Harish</p>
  </footer>
</body>
</html>

MENU.HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Little Lemon - Menu</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header><h1>Our Menu</h1></header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="cards">
    <div class="card"><h2>Margherita Pizza</h2><img src="images/pizza.jpg"></div>
    <div class="card"><h2>Grilled Chicken</h2><img src="images/chicken.jpg"></div>
    <div class="card"><h2>Pasta Alfredo</h2><img src="images/pasta.jpg"></div>
    <div class="card"><h2>Caesar Salad</h2><img src="images/salad.jpg"></div>
    <div class="card"><h2>Burger & Fries</h2><img src="images/burger.jpg"></div>
    <div class="card"><h2>Paneer Tikka</h2><img src="images/paneer.jpg"></div>
    <div class="card"><h2>Fish Curry</h2><img src="images/fish.jpg"></div>
    <div class="card"><h2>Veggie Wrap</h2><img src="images/wrap.jpg"></div>
    <div class="card"><h2>Sushi Platter</h2><img src="images/sushi.jpg"></div>
    <div class="card"><h2>Chocolate Cake</h2><img src="images/cake.jpg"></div>
    <div class="card"><h2>Ice Cream Sundae</h2><img src="images/icecream.jpg"></div>
    <div class="card"><h2>Mojito</h2><img src="images/mojito.jpg"></div>
  </section>

  <footer><p>Created by Harish</p></footer>
</body>
</html>

STYLE.CSS
body {
  font-family: Arial, sans-serif;
  margin: 0;
  
   
  background-image: url(" Screenshot 2025-10-03 194325.png");
  background-repeat: no-repeat;
  background-size: cover;
}

header {
  background-color: #333;
  padding: 20px;
  text-align: center;
  color: rgb(27, 8, 240);
}

header img {
  width: 100px;
}
p{
    font-size: 20px;
    font-weight: bold;
    font-style: italic;
    color: rgb(0, 64, 255);
}
nav {
  background-color: #444;
  display: flex;
  justify-content: center;
}

nav a {
  color: white;
  text-decoration: none;
  padding: 14px 25px;
  font-weight: bold;
}

nav a:hover {
  background-color: #e67e22;
}

.banner {
  background: url(" Screenshot 2025-10-03 194325.png ") no-repeat center center/cover;
  padding: 80px 20px;
  color: rgb(235, 247, 7);
  text-align: center;
  font-size: 1.2em;
  position: relative;
}

.banner h1 {
  color: #e67e22;
  font-size: 2.5em;
  margin-bottom: 10px;
}

.cards {
   
  display: flex;
  justify-content: space-around;
  padding: 30px;
  flex-wrap: wrap;
  background-color: rgba(255, 255, 255, 0.8);
}

.card {
  background-color: #fff;
  border-radius: 10px;
  width: 30%;
  margin: 10px;
  padding: 20px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.card img {
  width: 100%;
  border-radius: 10px;
}

footer {
  background-color: #222;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 20px;
}
div.card a {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 15px;
  background-color: #e67e22;
  color: white;
  text-decoration: none;
  border-radius: 5px;
} 

````


# OUTPUT:
![alt text](<Screenshot 2025-10-03 203050.png>)
![alt text](<Screenshot 2025-10-03 203132.png>)
![alt text](<Screenshot 2025-10-03 203148.png>)
![alt text](<Screenshot 2025-10-03 211145.png>)
![alt text](<Screenshot 2025-10-03 211158.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
