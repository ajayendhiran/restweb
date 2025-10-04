# Ex.07 Restaurant Website
## Date:04.10.2025

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
administration .html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - BURJ KHALIFA</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>OUR PRIDE CHEF</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="admin-grid">
    <div class="admin-card">
      <img src="IMG-20250929-WA0017.jpg" alt="Admin 1">
      <h3>John Smith</h3>
      <p>Manager</p>
    </div>
    <div class="admin-card">
      <img src="IMG-20250929-WA0018.jpg" alt="Admin 2">
      <h3>Mike Jordan</h3>
      <p>Head Chef</p>
    </div>
    <div class="admin-card">
      <img src="IMG-20250929-WA0019.jpg" alt="Admin 3">
      <h3>David Lee</h3>
      <p>Assistant Chef</p>
    </div>
    <div class="admin-card">
      <img src="IMG-20250929-WA0020.jpg" alt="Admin 4">
      <h3>Turner</h3>
      <p>Cashier</p>
    </div>
    <div class="admin-card">
      <img src="IMG-20250929-WA0021.jpg" alt="Admin 5">
      <h3>Emily Rose</h3>
      <p>Inventory Manager</p>
    </div>
    <div class="admin-card">
      <img src="IMG-20250929-WA0022.jpg" alt="Admin 6">
      <h3>Lisa Kim</h3>
      <p>Customer Service</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by jayendhiran</p>
  </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us -BURJ KHALIFA</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="contact-info">
    <h2>for more details</h2>
    <p>📍 <strong>Address:</strong>Dubai ,dubai main road,dubai</p>
    <p>📞 <strong>Phone:7598758582</strong></p>
    <p>✉ <strong>Email:ajayendhiranbabloo@gmail.com</strong></p>
  </section>
  <footer>
    <p>&copy; 2025. Designed by jayendhiran</p>
  </footer>

</body>
</html>

index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home -BURJ KHALIFA</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>BURJ KHALIFA </h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="banner">
    <img src="WhatsApp Image 2025-09-29 at 20.32.10_3004b1e5.jpg" alt="Delicious Food Banner">
  </section>

  <section class="content">
    <h2>Welcome!</h2>
    <p>The best food in town, made with best quality and fresh ingredients.</p>
  </section>

  <footer>
    <p>&copy; 2025. Designed by jayendhiran</p>
  </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu -BURJ KHALIFA </title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>special Menu</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="menu-grid">
    <div class="menu-item">
      <img src="IMG-20250929-WA0007.jpg" alt="Pizza">
      <h3>Chicken Pizza</h3>
      <p>Classic chicken pizza with tomato sauce.</p>
    </div>
    <div class="menu-item">
      <img src="IMG-20250929-WA0004.jpg" alt=" mutton briyani">
      <h3>Mutton briyani</h3>
      <p>Mutton Biryani is a rich and flavorful South Asian dish made with tender marinated mutton, fragrant basmati rice, and a blend of aromatic spices, cooked in layers for a delicious, multi-layered rice and meat dish.</p>
    </div>
    <div class="menu-item">
      <img src="IMG-20250929-WA0005.jpg" alt="chicken">
      <h3>Grilled chicken</h3>
      <p>Dipe with mayo enjoy it.</p>
    </div>
    <div class="menu-item">
      <img src="IMG-20250929-WA0008.jpg" alt="puttu">
      <h3>kerala puttu</h3>
      <p>Traditional South Indian steamed breakfast dish made from ground rice flour and grated coconut, layered and steamed in a cylindrical mould.</p>
    </div>
    <div class="menu-item">
      <img src="IMG-20250929-WA0006.jpg" alt="fish">
      <h3>vanjaram fire</h3>
      <p> strong thin, flexible string or cord, typically made of plastic, that is used for fishing by attaching it to a hook, bait, or lure to catch fish.</p>
    </div>
    <div class="menu-item">
      <img src="IMG-20250929-WA0009.jpg" alt="dosa">
      <h3>Dosa</h3>
      <p>is a thin, savory, crispy, and often golden-brown flatbread made from a fermented batter of rice and lentils. It is a staple of South Indian cuisine, typically served hot with accompaniments like coconut chutney and lentil-based vegetable stew, sambar.</p>
    </div>
    <div class="menu-item">
      <img src="IMG-20250929-WA0010.jpg" alt="lappa">
      <h3>Lappa</h3>
      <p>Spicy beef tacos with salsa.</p>
    </div>
    <div class="menu-item">
      <img src="IMG-20250929-WA0011.jpg" alt="idly">
      <h3>Idly</h3>
      <p>Idli is a steamed, savory South Indian rice cake, typically made from a fermented batter of rice and urad dal (black lentils), and is often served with chutney and sambar.</p>
    </div>
    <div class="menu-item">
      <img src="IMG-20250929-WA0012.jpg" alt="idiyappam">
      <h3>idiyappam</h3>
      <p>Layered sandwich with chicken and bacon.</p>
    </div>
    <div class="menu-item">
      <img src="IMG-20250929-WA0013.jpg" alt="parotta">
      <h3>Parotta</h3>
      <p> take a small piece of parotta and dip with chicken chettinad .</p>
    </div>
    <div class="menu-item">
      <img src="IMG-20250929-WA0014.jpg" alt="pani poori">
      <h3>Pani poori</h3>
      <p>The perfect bite of crispy, spicy, tangy, and sweet.</p>
    </div>
    <div class="menu-item">
      <img src="IMG-20250929-WA0015.jpg" alt="briyani">
      <h3>Chicken briyani</h3>
      <p>Crispy golden fries and bit of soft chicken.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by jayendhiran</p>
  </footer>
</body>
</html>

style.css

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #fdf6f0;
  color: #333;
}

header {
  background-color: #fb0909;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
}

.banner img {
  width: 100%;
  height: auto;
}

section.content {
  padding: 40px;
  text-align: center;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  padding: 40px;
}

.menu-item {
  background-color: #fff;
  border: 1px solid #ccc;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
}

.menu-item img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
}

.admin-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  padding: 40px;
  justify-content: center;
}

.admin-card {
  width: 200px;
  background-color: #fff;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  border: 1px solid #ccc;
}

.admin-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
}

.contact-info {
  padding: 40px;
  text-align: center;
  line-height: 1.8;
}

footer {
  background-color: #170606;
  color: white;
  text-align: center;
  padding: 10px;
}
```
## OUTPUT:
![alt text](<Screenshot 2025-10-04 112246.png>)
![alt text](<Screenshot 2025-10-04 112309.png>)
![alt text](<Screenshot 2025-10-04 112336.png>)
![alt text](<Screenshot 2025-10-04 112208.png>)
![alt text](<Screenshot 2025-10-04 112454.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
