# Ex.08 Design of Interactive Image Gallery
## Date:28.5.25

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
[Uploading res<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Delicious Bites - Restaurant</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@400;600&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Quicksand', sans-serif;
    }

    body {
      background: #f8f8f8;
      color: #441e1e;
    }

    header {
      background-image: url('C:\Users\admin\Videos\New folder\restweb\rest\restapp\static\images.png\bgrest.png');
      background-size: cover;
      background-position: center;
      color: rgb(191, 204, 165);
      text-align: center;
      padding: 80px 20px;
    }

    nav {
      background: #333;
      color: rgb(195, 176, 176);
      display: flex;
      justify-content: space-around;
      padding: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .search-bar {
      text-align: center;
      margin: 20px;
    }

    .search-bar input {
      padding: 10px;
      width: 300px;
      border: 1px solid #75dca5;
      border-radius: 4px;
    }

    .section {
      padding: 40px 20px;
    }

    .menu-items {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .dish {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(212, 141, 86, 0.1);
      width: 250px;
      text-align: center;
      padding: 20px;
    }

    .dish img {
      width: 100%;
      border-radius: 10px;
      height: 150px;
      object-fit: cover;
    }

    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to Delicious Bites</h1>
    <p>Your go-to place for amazing food!</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#contact">Contact</a>
    <a href="#location">Location</a>
  </nav>

  <div class="search-bar">
    <input type="text" placeholder="Search for dishes...">
  </div>

  <section class="section" id="home">
    <h2>About Us</h2>
    <p>Delicious Bites offers a variety of mouth-watering dishes made with the freshest ingredients. Join us for a memorable dining experience.Get offers on our exclusive cuisine and get the best offers on our premium beverages</p>
  </section>

  <section class="section" id="menu">
    <h2>Our Menu</h2>
    <div class="menu-items">
      <div class="dish">
        <img src="C: restaurant/calciapp/static/png-transparent-pizza-margherita-sushi-pizza-pizza-delivery-pizza.png  " alt="Pizza">
        <h3>Pizza</h3>
        <p>Pizza is a classic Italian dish loved worldwide, featuring a crispy crust topped with savory ingredients like cheese, sauce, and various meats or veggies.</p>
      </div>
      <div class="dish">
        <img src="C:restaurant/calciapp/static/pngtree-sushi-set-on-plate-png-image_13126480.png" alt ="Sushi">
        <h3>Sushi</h3>
        <p> A popular Japanese dish made with vinegared rice and various ingredients, such as raw fish, vegetables, and seafood, often wrapped in seaweed</p>
      </div>
      <div class="dish">
        <img src="C: restaurant/calciapp/static/pngtree-mexican-taco-crepes-with-lemon-sauce-psd-transparent-png-image_6720528.png " alt="Tacos">
        <h3>Tacos</h3>
        <p>A delicious Mexican dish consisting of a small, folded corn tortilla filled with various ingredients, such as seasoned meats</p>
      </div>
    </div>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>Email: contact@deliciousbites.com</p>
    <p>Phone: +91-9563543210</p>
  </section>

  <section class="section" id="location">
    <h2>Our Location</h2>
    <p>123 Food Street, Flavor Town, India</p>
  </section>

  <footer>
    &copy; Developed by Varshinee.S
  </footer>
</body>
</html>t.html…]()


```

## OUTPUT:

![Screenshot 2025-05-28 230241](https://github.com/user-attachments/assets/a4ee8f17-a52b-458f-aa77-709c87c7deed)




## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
