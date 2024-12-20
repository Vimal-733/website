# Ex.07 Restaurant Website
# Date:
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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vimal's Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffe6cc; 
        }

        header {
            background-color: #ff6347;
            color: white;
            text-align: center;
            padding: 20px 10px;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            background-color: #333;
            overflow: hidden;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }

        nav a:hover {
            background-color: #575757;
        }

        .hero {
            text-align: center;
            padding: 50px;
            background: url"c:\Users\admin\Desktop\home image.jpeg" no-repeat center center/cover; /* Updated background image path */
            color: white;
        }

        .hero h2 {
            font-size: 2em;
            margin: 0;
        }

        .hero p {
            font-size: 1.2em;
            margin: 10px 0;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .about {
            text-align: center;
        }

        .about h2 {
            color: #ff6347;
            margin-bottom: 10px;
        }

        .about p {
            font-size: 1.1em;
            line-height: 1.6;
        }

        .offer {
            text-align: center;
            margin-top: 20px;
        }

        .offer img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
<header>
    <h1>Vimal's Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
</nav>

<section class="hero">
    <h2>Welcome to Vimal's Restaurant</h2>
    <p>Where flavor meets tradition</p>
</section>

<div class="container">
    <section class="about">
        <h2>Today's Special Offer</h2>
        <p>At Vimal's Restaurant, we serve the finest cuisines with a blend of traditional and modern flavors. Experience a memorable dining journey with us.</p>
    </section>

    <section class="offer">
        <h1>70% off</h1>
        <img src="c:\Users\admin\Desktop\home image.jpeg" alt="Special Offer" width="500" hight="500"> <!-- Updated image path -->
    </section>
</div>

<footer>
    <p>&copy; 2024 Vimal's Restaurant. All rights reserved.</p>
</footer>

</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Vimal's Restaurant</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffe6cc; /* Light peach background */
        }

        header {
            background-color: #ff6347;
            color: white;
            text-align: center;
            padding: 20px 10px;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            background-color: #333;
            overflow: hidden;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }

        nav a:hover {
            background-color: #575757;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .menu {
            text-align: center;
        }

        .menu h2 {
            color: #ff6347;
            margin-bottom: 20px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }

        .gallery-item {
            text-align: center;
        }

        .gallery-item img {
            width: 100%;
            height: 200px; /* Uniform height */
            object-fit: cover; /* Ensures consistent aspect ratio */
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .gallery-item p {
            margin-top: 10px;
            font-size: 1.1em;
            color: #333;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }
    </style>
</head>
<body>

<header>
    <h1>Vimal's Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="about.html">About Us</a>
    <a href="contact.html">Contact</a>
</nav>

<div class="container">
    <section class="menu">
        <h2>Menu</h2>
        <div class="gallery">
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\ice cream.jpeg" alt="Ice Cream">
                <p>Ice Cream</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\pizza.jpeg" alt="Pizza">
                <p>Pizza</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\burger.jpeg" alt="Burger">
                <p>Burger</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\chicken.jpeg" alt="Chicken">
                <p>Chicken</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\frinch fries.jpeg" alt="French Fries">
                <p>French Fries</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\sandwich.jpeg" alt="Sandwich">
                <p>Sandwich</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\shawarma.webp" alt="Shawarma">
                <p>Shawarma</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\naan.jpeg" alt="Naan">
                <p>Naan</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\paneer.jpg" alt="Paneer">
                <p>Paneer</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\faluda.jpeg" alt="Faluda">
                <p>Faluda</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\biryani.jpeg" alt="Biryani">
                <p>Biryani</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\tandoori.jpeg" alt="Tandoori">
                <p>Tandoori</p>
            </div>
        </div>
    </section>
</div>

<footer>
    <p>&copy; 2024 Vimal's Restaurant. All rights reserved.</p>
</footer>

</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Vimal's Restaurant</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffe6cc; /* Light peach background */
        }

        header {
            background-color: #ff6347;
            color: white;
            text-align: center;
            padding: 20px 10px;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            background-color: #333;
            overflow: hidden;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }

        nav a:hover {
            background-color: #575757;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .menu {
            text-align: center;
        }

        .menu h2 {
            color: #ff6347;
            margin-bottom: 20px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }

        .gallery-item {
            text-align: center;
        }

        .gallery-item img {
            width: 100%;
            height: 200px; /* Uniform height for images */
            object-fit: cover; /* Ensures aspect ratio is preserved */
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .gallery-item p {
            margin-top: 10px;
            font-size: 1.1em;
            color: #333;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }
    </style>
</head>
<body>

<header>
    <h1>Vimal's Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="about.html">About Us</a>
    <a href="contact.html">Contact</a>
</nav>

<div class="container">
    <section class="menu">
        <h2>Menu</h2>
        <div class="gallery">
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\chef 11.jpeg" alt="Kavin">
                <p>Kavin</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\chef 12.jpeg" alt="Tresha">
                <p>Tresha</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\chef 13.jpeg" alt="Antony">
                <p>Antony</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\chef 14.jpeg" alt="Nissar">
                <p>Nissar</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\chef 16.jpeg" alt="Ravi">
                <p>Ravi</p>
            </div>
            <div class="gallery-item">
                <img src="c:\Users\admin\Desktop\chef 15.jpeg" alt="jai">
                <p>shree</p>
            </div>
        </div>
    </section>
</div>

<footer>
    <p>&copy; 2024 Vimal's Restaurant. All rights reserved.</p>
</footer>

</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vimal's Restaurant - Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffe6cc;
        }

        header {
            background-color: #ff6347;
            color: white;
            text-align: center;
            padding: 20px 10px;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            background-color: #333;
            overflow: hidden;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }

        nav a:hover {
            background-color: #575757;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .contact-section {
            text-align: center;
        }

        .contact-section h2 {
            color: #ff6347;
            margin-bottom: 20px;
        }

        .contact-info {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin: 20px 0;
        }

        .contact-card {
            width: 250px;
            padding: 20px;
            border-radius: 10px;
            background-color: #fff5e6;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            margin: 10px;
            text-align: center;
        }

        .contact-card h3 {
            color: #ff6347;
            margin-bottom: 10px;
        }

        .contact-card p {
            margin: 0;
            font-size: 1.1em;
        }

        .contact-image {
            text-align: center;
            margin-top: 30px;
        }

        .contact-image img {
            max-width: 90%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }
    </style>
</head>
<body>

<header>
    <h1>Vimal's Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
</nav>

<div class="container">
    <section class="contact-section">
        <h2>Contact Us</h2>
        <p>We'd love to hear from you! Reach out to us through the following:</p>

        <div class="contact-info">
            <div class="contact-card">
                <h3>Phone</h3>
                <p>+1 (234) 567-890</p>
                <p>+1 (234) 567-891</p>
            </div>

            <div class="contact-card">
                <h3>Email</h3>
                <p>info@vimalsrestaurant.com</p>
                <p>support@vimalsrestaurant.com</p>
            </div>

            <div class="contact-card">
                <h3>Location</h3>
                <p>123 Flavor Street</p>
                <p>Food Town, Culinary City</p>
            </div>
        </div>
    </section>

    <section class="contact-image">
        <img src="c:\Users\admin\Desktop\food image 13.jpeg" alt="Restaurant Location" style="height: 500px;: fit: content 500px;;">
    </section>
</div>

<footer>
    <p>&copy; 2024 Vimal's Restaurant. All rights reserved.</p>
</footer>

</body>
</html>
```

# OUTPUT:

![Screenshot 2024-11-29 110651](https://github.com/user-attachments/assets/86e474ad-3015-4b62-886d-d6d35130c736)

![Screenshot 2024-11-29 110718](https://github.com/user-attachments/assets/31164842-4046-4cc2-9b3a-d945ef2f6267)
![Screenshot 2024-11-29 110737](https://github.com/user-attachments/assets/3ddf2b40-d8b1-4445-ac3f-07317845fb01)
![Screenshot 2024-11-29 110748](https://github.com/user-attachments/assets/fcc4554d-8e1f-4218-a0c7-59a1734581e4)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
