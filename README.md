# Ex.07 Restaurant Website
## Date:04/12/2024

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


index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gourmet Bliss</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="home-header">
        <div class="banner">
            <h1>Gourmet Bliss</h1>
            <p>Delightful Food, Memorable Experiences</p>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="welcome">
            <h2>Welcome to Gourmet Bliss</h2>
            <p>Discover the finest dishes crafted with passion and precision, served with love to tantalize your taste buds.</p>
        </section>
        <section class="featured">
            <h2>Our Specialties</h2>
            <div class="featured-items">
                <div class="featured-item">
                    <img src="grilledsalmon.jpg" alt="Grilled Salmon">
                    <p>Grilled Salmon</p>
                </div>
                <div class="featured-item">
                    <img src="pizzamargherita.jpg" alt="Margherita Pizza">
                    <p>Margherita Pizza</p>
                </div>
                <div class="featured-item">
                    <img src="lavacake.jpg" alt="Chocolate Lava Cake">
                    <p>Chocolate Lava Cake</p>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <p>Designed by INDHUMATHI L | Gourmet Bliss © 2024</p>
    </footer>
</body>
</html>
```

menu.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Gourmet Bliss</title>
    <link rel="stylesheet" href="styless.css">
</head>
<body>
    <header>
        <div class="banner">
            <h1>Gourmet Bliss</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Our Menu</h2>
        <div class="menu-card">
            <div class="menu-item">
                <img src="grilledsalmon.jpg" alt="Grilled Salmon">
                <div class="menu-details">
                    <h3>Grilled Salmon</h3>
                    <p>Freshly grilled salmon served with a lemon butter sauce.</p>
                    <p class="price">$15.99</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Vegan-Pasta-Primavera-04.jpg" alt="Pasta Primavera">
                <div class="menu-details">
                    <h3>Pasta Primavera</h3>
                    <p>A classic Italian pasta tossed with fresh seasonal vegetables.</p>
                    <p class="price">$12.99</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="mozzarella-pizza-margherita.jpg" alt="Margherita Pizza">
                <div class="menu-details">
                    <h3>Margherita Pizza</h3>
                    <p>Wood-fired pizza topped with fresh mozzarella and basil.</p>
                    <p class="price">$10.99</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Tandoori-Chicken.jpg" alt="Tandoori Chicken">
                <div class="menu-details">
                    <h3>Tandoori Chicken</h3>
                    <p>Marinated chicken cooked in a traditional clay oven.</p>
                    <p class="price">$14.99</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="choco lava.jpg" alt="Chocolate Lava Cake">
                <div class="menu-details">
                    <h3>Chocolate Lava Cake</h3>
                    <p>Rich chocolate cake with a molten center served with ice cream.</p>
                    <p class="price">$7.99</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="veg-burgers.jpg" alt="Veggie Burger">
                <div class="menu-details">
                    <h3>Veggie Burger</h3>
                    <p>A delicious plant-based burger served with crispy fries.</p>
                    <p class="price">$9.99</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Caesar-salad.jpg" alt="Caesar Salad">
                <div class="menu-details">
                    <h3>Caesar Salad</h3>
                    <p>Fresh Romaine lettuce with Caesar dressing, croutons, and Parmesan.</p>
                    <p class="price">$7.99</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="french fries.jpg" alt="French Fries">
                <div class="menu-details">
                    <h3>French Fries</h3>
                    <p>Golden, crispy fries served with your choice of dipping sauces.</p>
                    <p class="price">$4.99</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Grilled-Beef-Steak.jpg" alt="Beef Steak">
                <div class="menu-details">
                    <h3>Beef Steak</h3>
                    <p>Juicy beef steak grilled to perfection, served with mashed potatoes.</p>
                    <p class="price">$18.99</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Chicken-Alfredo.jpg" alt="Chicken Alfredo">
                <div class="menu-details">
                    <h3>Chicken Alfredo</h3>
                    <p>Creamy Alfredo pasta with grilled chicken and Parmesan cheese.</p>
                    <p class="price">$13.99</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="choco lava.jpg" alt="Chocolate Lava Cake">
                <div class="menu-details">
                    <h3>Chocolate Lava Cake</h3>
                    <p>Rich chocolate cake with a molten center served with vanilla ice cream.</p>
                    <p class="price">$7.99</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="creame brulee.jpg" alt="Creme Brulee">
                <div class="menu-details">
                    <h3>Creme Brulee</h3>
                    <p>Classic French dessert with a rich custard base and caramelized top.</p>
                    <p class="price">$8.99</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="sundae-a-la-creme.jpg" alt="Ice Cream Sundae">
                <div class="menu-details">
                    <h3>Ice Cream Sundae</h3>
                    <p>Delicious ice cream topped with chocolate sauce, nuts, and cherries.</p>
                    <p class="price">$6.99</p>
                </div>
            </div>
        </div>
    </main>
    <footer>
        <p>Designed by INDHUMATHI L | Gourmet Bliss © 2024</p>
    </footer>
</body>
</html>
```

administration.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Gourmet Bliss</title>
    <link rel="stylesheet" href="sty.css">
</head>
<body>
    <header>
        <div class="banner">
            <h1>Gourmet Bliss</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <div class="admin-container">
            <div class="admin-header">
                <h2>Meet Our Team</h2>
                <p>Our exceptional team is dedicated to delivering the finest dining experience with expertise and passion.</p>
            </div>
            <div class="admin-grid">
                <!-- Team Member 1 -->
                <div class="admin-card">
                    <img src="gm.jpg" alt="John Davidson">
                    <h3>John Doe</h3>
                    <p>General Manager</p>
                    <p class="experience">John has over 15 years of experience in hospitality management, ensuring excellence in every detail of our service.</p>
                </div>
                <!-- Team Member 2 -->
                <div class="admin-card">
                    <img src="jane.jpg" alt="Jane Smith">
                    <h3>Jane Smith</h3>
                    <p>Head Chef</p>
                    <p class="experience">Jane is a culinary expert with a passion for innovative dishes, leading our kitchen with creativity and precision.</p>
                </div>
                <!-- Team Member 3 -->
                <div class="admin-card">
                    <img src="mk.jpg" alt="Mithun Kumar">
                    <h3>Mithun Kumar</h3>
                    <p>Pastry Chef</p>
                    <p class="experience">Mithun specializes in desserts, creating memorable sweet treats that delight our guests every day.</p>
                </div>
                <!-- Team Member 4 -->
                <div class="admin-card">
                    <img src="sg.jpg" alt="Sarah George">
                    <h3>Sarah George</h3>
                    <p>Event Coordinator</p>
                    <p class="experience">Sarah has organized hundreds of events, ensuring every celebration at Gourmet Bliss is extraordinary.</p>
                </div>
            </div>
        </div>
    </main>
    <footer>
        <p>Designed by INDHUMATHI L | Gourmet Bliss © 2024</p>
    </footer>
</body>
</html>
```

contact.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Gourmet Bliss</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="banner">
            <h1>Gourmet Bliss</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Contact Us</h2>
        <p>Address: 123 Culinary Street, Foodie Town, FL 56789</p>
        <p>Phone: (123) 456-7890</p>
        <p>Email: contact@gourmetbliss.com</p>
    </main>
    <footer>
        <p>Designed by INDHUMATHI L | Gourmet Bliss © 2024</p>
    </footer>
</body>
</html>
```

css

```
/* Background Image for Home Page */
.home-header {
    background: url('photobg.jpg') no-repeat center center/cover;
    height: 100vh; /* Full screen height */
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
}

.home-header .banner h1 {
    font-size: 3em;
    margin-bottom: 10px;
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
}

.home-header .banner p {
    font-size: 1.2em;
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
}

/* Navigation Styles */
nav ul {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 10px;
    background: rgba(0, 0, 0, 0.5);
    list-style: none;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.1em;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Featured Section */
.featured {
    margin: 20px 0;
    text-align: center;
    color: #333;
}

.featured-items {
    display: flex;
    justify-content: space-around;
    gap: 20px;
}

.featured-item img {
    width: 200px;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
}

.featured-item p {
    text-align: center;
    margin-top: 5px;
    font-weight: bold;
}

/* Menu Card Layout */
.menu-card {
    max-width: 1000px;
    margin: 20px auto;
    padding: 20px;
}

.menu-item {
    display: flex;
    align-items: center;
    gap: 20px;
    margin-bottom: 20px;
    padding: 10px;
    background: #f9f9f9;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.menu-item img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
}

.menu-details {
    flex: 1;
}

.menu-details h3 {
    font-size: 1.5em;
    color: #333;
}

.menu-details p {
    color: #666;
    margin-top: 5px;
}

.menu-details .price {
    color: #333;
    font-size: 1.2em;
    font-weight: bold;
    margin-top: 10px;
}

/* Administration Page */
.admin-container {
    max-width: 1200px;
    margin: 20px auto;
    padding: 20px;
}

.admin-header {
    text-align: center;
    margin-bottom: 30px;
}

.admin-header h2 {
    font-size: 2em;
    color: #333;
}

.admin-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); /* Responsive columns */
    gap: 20px;
    padding: 10px;
}

.admin-card {
    text-align: center;
    background: #f9f9f9;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    padding: 15px;
    transition: transform 0.2s;
}

.admin-card:hover {
    transform: scale(1.05); /* Subtle zoom on hover */
}

.admin-card img {
    width: 100%;
    height: 200px;
    object-fit: cover; /* Ensures consistent image size */
    border-radius: 8px;
    margin-bottom: 10px;
}

.admin-card h3 {
    font-size: 1.4em;
    color: #333;
    margin-bottom: 5px;
}

.admin-card p {
    font-size: 1em;
    color: #666;
    margin: 5px 0;
}

.admin-card .experience {
    font-size: 0.9em;
    color: #555;
    margin-top: 10px;
    line-height: 1.4;
}

/* Footer */
footer {
    text-align: center;
    padding: 15px;
    background: #333;
    color: white;
    margin-top: 20px;
}
```

## OUTPUT:

![alt text](indhu/restapp/static/s1.png)

![alt text](indhu/restapp/static/s2.png)

![alt text](indhu/restapp/static/image.png)

![alt text](indhu/restapp/static/s4.png)

![alt text](indhu/restapp/static/s5.png)

![alt text](indhu/restapp/static/s6.png)

![alt text](<indhu/restapp/static/Screenshot 2024-12-16 135034.png>)

![alt text](indhu/restapp/static/s8.png)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
