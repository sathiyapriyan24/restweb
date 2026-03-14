# Ex.06 Restaurant Website
## Date:14.03.2026

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
Publish the website in Localhost.

## PROGRAM:
~~~
home.html

<html>
    <head>
        <title>Saveetha Hotel</title>
        <style>
            .container
{
    background-color: rgb(247, 11, 247)
   
}
.navbar
{
    background:black;
    width:420px;
    padding:10px;
    float:right;
    text-align:center;
}
.navbar a
{
    margin:15px;
    color:white;
    text-decoration:underline;
    font-weight:bold;
}
.para
{
    margin-top:120px;
    margin-left:40px;
}
.para h1
{
    color: black;
}
.para h2
{
    color: blue;
}
.quote
{
    color:red;
    text-align:center;
    font-style:italic;
    margin-top:30px;
}
.p1
{
    color:white;
    text-align:center;
    margin-top:10px;
}
.image
{
    display:flex;
    justify-content:space-evenly;
    gap:40px;
    margin-top:40px;
}
.image img
{
    width:450px;
    height:260px;
    border-radius:5px;
}
footer
{
    text-align:center;
    padding:10px;
    background:grey;
}
        </style>
    </head>
    <body>
        <div class="container">
            <div class="navbar">
                <a href="home.html">HOME</a>
                <a href="menu.html">MENU</a>
                <a href="admin.html">ADMIN</a>
                <a href="contact.html">CONTACT</a>
            </div>
            <div class="para">
                <h1>Saveetha Hotel</h1>
                <h2>Known for consistency, hygiene, and traditional tastes,</h2>
                <h3 class="quote">" Known for high-quality, authentic flavors that resemble home-cooked food "</h3>
                <p class="p1">Saveetha Restaurant is a renowned Chennai-based chain founded in 1985, celebrated for authentic South Indian, North Indian, and Indo-Chinese vegetarian cuisine. </p>
            </div>
            <div class="image">
                <img src="adrien-olichon-ZgREXhl8ER0-unsplash.jpg">
                <img src="jason-leung-poI7DelFiVA-unsplash.jpg">
            </div>
        </div>
        <footer>
            Sathiya Priyan G
        </footer>
    </body>
</html>

menu.html

<html>
    <head>
        <title>Saveetha Hotel</title>
        <style>
            .container
            {
                background-color:rgb(247, 11, 247)
               
            }
            .navbar
            {
                background:black;
                width:420px;
                padding:10px;
                float:right;
                text-align:center;
            }
            .navbar a
            {
                margin:15px;
                color:white;
                text-decoration:underline;
                font-weight:bold;
            }
            .para
            {
                color: blue;
            }
            .menu-container
            {
                display:flex;
                justify-content:center;
                gap:10px;
            }
            .card
            {
                background:rgb(222, 161, 161);
                padding:20px;
                border-radius:10px;
                text-align:center;
                width:200px;
                margin-top: 100px;
            }
            .card img
            {
                width:140px;
                height:120px;
                border-radius:10px;
            }
            .card h2
            {
                color:red;
            }
            footer
            {
                text-align:center;
                padding:10px;
                background:grey;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <div class="navbar">
                <a href="home.html">HOME</a>
                <a href="menu.html">MENU</a>
                <a href="admin.html">ADMIN</a>
                <a href="contact.html">CONTACT</a>
            </div>
            <div class="para">
                <h1>ITEMS</h1>
            </div>
            <div class="menu-container">
            <div class="card">
                <img src="shreyak-singh-0j4bisyPo3M-unsplash.jpg">
                <h2>Briyani</h2>
                <p>Rs.200</p>
            </div>
            <div class="card">
                <img src="christopher-alvarenga-rQX9eVpSFz8-unsplash.jpg">
                <h2>chicken Rice</h2>
                <p>Rs.150</p>
            </div>
            <div class="card">
                <img src="zoshua-colah-VIqcVqZ1uxM-unsplash.jpg">
                <h2>Masala dosa</h2>
                <p>Rs.70</p>
            </div>
            <div class="card">
                <img src="ranga-it6umceV33w-unsplash.jpg">
                <h2>idly</h2>
                <p>Rs.50</p>
            </div>
            <div class="card">
                <img src="ananthan-chithiraikani-ovguktgGqDU-unsplash.jpg">
                <h2>Paratha</h2>
                <p>Rs.70</p>
            </div>
            <div class="card">
                <img src="veg.jpeg">
                <h2>Veg meal</h2>
                <p>Rs.150</p>
            </div>
            </div>
        </div>
    </div>
    <footer>
        Sathiya Priyan G
    </footer>
    </body>
</html>

admin.html

<html>
    <head>
        <title>Saveetha Hotel</title>
        <style>
            .container
            {
                background-color:rgb(247, 11, 247)
              
            }
            .navbar
            {
                background:black;
                width:420px;
                padding:10px;
                float:right;
                text-align:center;
            }
            .navbar a
            {
                margin:15px;
                color:white;
                text-decoration:underline;
                font-weight:bold;
            }
            .para
            {
                color: green;
            }
            .admin-container
            {
                display:flex;
                justify-content:center;
                gap:20px;
            }
            .card
            {
                background:blue;
                padding:20px;
                border-radius:10px;
                text-align:center;
                width:180px;
                height:300px;
                margin-top: 100px;
            }
            .card img
            {
                width:180px;
                height:200px;
                border-radius:10px;
            }
            .card h2
            {
                color:red;
            }
            footer
            {
                text-align:center;
                padding:10px;
                background:grey;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <div class="navbar">
                <a href="home.html">HOME</a>
                <a href="menu.html">MENU</a>
                <a href="admin.html">ADMIN</a>
                <a href="contact.html">CONTACT</a>
            </div>
            <div class="para">
                <h1>STAFF</h1>
            </div>
            <div class="admin-container">
            <div class="card">
                <img src="me.jpg">
                <h2>Sathiya Priyan</h2>
                <p>CEO</p>
            </div>
            <div class="card">
                <img src="klim-musalimov-6ol9usQj7uQ-unsplash.jpg">
                <h2>Iron man</h2>
                <p>manager</p>
            </div>
            <div class="card">
                <img src="gabriel-tovar-oTKanDGugaA-unsplash.jpg">
                <h2>Hulk</h2>
                <p>HR</p>
            </div>
            <div class="card">
                <img src="deepak-rastogi-dpnQQ4rlDj8-unsplash.jpg">
                <h2>Thor</h2>
                <p>Chef</p>
            </div>
            <div class="card">
                <img src="colton-sturgeon-DRjK9Mvac20-unsplash.jpg">
                <h2>Captain America</h2>
                <p>cheif Manager</p>
            </div>
            <div class="card">
                <img src="WANDA.jpeg">
                <h2>Wanda</h2>
                <p>Customer service manager</p>
            </div>
            </div>
        </div>
    </div>
    <footer>
        Sathiya Priyan G
    </footer>
    </body>
</html>

contact.html

<html>
    <head>
        <title>Saveetha Hotel</title>
        <style>
            .container
            {
                background-color:rgb(247, 11, 247)
               
            }
            .navbar
            {
                background:black;
                width:420px;
                padding:10px;
                float:right;
                text-align:center;
            }
            .navbar a
            {
                margin:15px;
                color:white;
                text-decoration:underline;
                font-weight:bold;
            }
            .para h1
            {
                color:blue;
            }
            .para h2
            {
                color:red;
            }
            .para p
            {
                color: red;
            }
            footer
            {
                text-align:center;
                padding:10px;
                background:grey;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <div class="navbar">
                <a href="home.html">HOME</a>
                <a href="menu.html">MENU</a>
                <a href="admin.html">ADMIN</a>
                <a href="contact.html">CONTACT</a>
            </div>
            <div class="para">
                <h1>Contact</h1>
                <h2>Visit us at:</h2>
                <p>Saveetha college,<p>
                <p>Thandalam,</p>
                <p>Chennai</p>
                <h2>Phone:</h2>
                <p>+91 9256781001</p>
                <h2>Email ID:</h2>
                <p>saveetha.ac.in</p>
            </div>
        </div>
        <footer>
            Sathiya Priyan G
        </footer>
    </body>
</html>
~~~

## OUTPUT:
![alt text](<Screenshot (37).png>) ![alt text](<Screenshot (38).png>) ![alt text](<Screenshot (39).png>) ![alt text](<Screenshot (40).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
