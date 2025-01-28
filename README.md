# The-Rebellion
A website where people can read up on mythological facts
---

### **Folder Structure**
```
mythology-philosophy-website/
│
├── index.html          (Homepage)
├── mythology.html      (Mythology Section)
├── philosophy.html     (Philosophy Section)
├── about.html          (About Page)
├── contact.html        (Contact Page)
├── styles/             (CSS Folder)
│   └── style.css       (Main CSS File)
├── scripts/            (JavaScript Folder)
│   └── script.js       (Main JavaScript File)
└── images/             (Images Folder)
```

---

### **1. `index.html` (Homepage)**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mythology & Philosophy</title>
  <link rel="stylesheet" href="styles/style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="mythology.html">Mythology</a></li>
        <li><a href="philosophy.html">Philosophy</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
    <h1>Welcome to Mythology & Philosophy</h1>
    <p>Explore the fascinating worlds of myths and philosophical ideas.</p>
  </header>

  <main>
    <section class="featured">
      <h2>Featured Articles</h2>
      <div class="article-card">
        <img src="images/greek-mythology.jpg" alt="Greek Mythology">
        <h3><a href="mythology.html">Greek Mythology: The Olympian Gods</a></h3>
        <p>Discover the powerful gods and goddesses of ancient Greece.</p>
      </div>
      <div class="article-card">
        <img src="images/stoicism.jpg" alt="Stoicism">
        <h3><a href="philosophy.html">Stoicism: The Art of Resilience</a></h3>
        <p>Learn how Stoic philosophy can help you navigate life's challenges.</p>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 Mythology & Philosophy. All rights reserved.</p>
  </footer>
</body>
</html>
```

---

### **2. `mythology.html` (Mythology Section)**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mythology</title>
  <link rel="stylesheet" href="styles/style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="mythology.html">Mythology</a></li>
        <li><a href="philosophy.html">Philosophy</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
    <h1>Mythology</h1>
    <p>Explore myths from different cultures around the world.</p>
  </header>

  <main>
    <section class="articles">
      <h2>Popular Mythologies</h2>
      <div class="article-card">
        <img src="images/norse-mythology.jpg" alt="Norse Mythology">
        <h3><a href="#">Norse Mythology: The Tales of Odin and Thor</a></h3>
        <p>Dive into the world of Norse gods and their epic adventures.</p>
      </div>
      <div class="article-card">
        <img src="images/egyptian-mythology.jpg" alt="Egyptian Mythology">
        <h3><a href="#">Egyptian Mythology: Gods of the Nile</a></h3>
        <p>Learn about the deities of ancient Egypt and their significance.</p>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 Mythology & Philosophy. All rights reserved.</p>
  </footer>
</body>
</html>
```

---

### **3. `philosophy.html` (Philosophy Section)**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Philosophy</title>
  <link rel="stylesheet" href="styles/style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="mythology.html">Mythology</a></li>
        <li><a href="philosophy.html">Philosophy</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
    <h1>Philosophy</h1>
    <p>Delve into the profound ideas of great thinkers.</p>
  </header>

  <main>
    <section class="articles">
      <h2>Philosophical Schools</h2>
      <div class="article
