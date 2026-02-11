# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM


```
intex.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Business</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="header">
    <h1>My Business</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html">Services</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-text">
      <h2>Grow Your Business With Us</h2>
      <p>We provide modern web solutions for your business growth.</p>
      <button>Get Started</button>
    </div>
    <div class="hero-img">
      <img src="buss.jpg" alt="Business" />
    </div>
  </section>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Services - My Business</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="header">
    <h1>My Business</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html" class="active">Services</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="services">
    <h2>Our Services</h2>
    <div class="service-container">
      <div class="card">
        <h3>Web Design</h3>
        <p>Beautiful, mobile-friendly designs that attract customers and build trust.</p>
      </div>
      <div class="card">
        <h3>Web Development</h3>
        <p>Fast, secure, and scalable websites built with modern technologies.</p>
      </div>
      <div class="card">
        <h3>SEO & Marketing</h3>
        <p>Increase your online visibility and reach more customers.</p>
      </div>
    </div>
  </section>

  <footer class="footer">
    <p>© 2026 My Business. All Rights Reserved.</p>
  </footer>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About - My Business</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="header">
    <h1>My Business</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html">Services</a>
      <a href="about.html" class="active">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="services">
    <h2>About Us</h2>
    <p>We are a team passionate about building modern, responsive websites for businesses.</p>
  </section>

  <footer class="footer">
    <p>© 2026 My Business. All Rights Reserved.</p>
  </footer>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contact - My Business</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="header">
    <h1>My Business</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html">Services</a>
      <a href="about.html">About</a>
      <a href="contact.html" class="active">Contact</a>
    </nav>
  </header>

  <section class="services">
    <h2>Contact Us</h2>
    <div class="service-container">
      <div class="card">
        <h3>Address</h3>
        <p>Chennai, Tamil Nadu, India</p>
      </div>
      <div class="card">
        <h3>Email</h3>
        <p>mybusiness@gmail.com</p>
      </div>
      <div class="card">
        <h3>Phone</h3>
        <p>+91 98765 43210</p>
      </div>
    </div>
  </section>

  <footer class="footer">
    <p>© 2026 My Business. All Rights Reserved.</p>
  </footer>
</body>
</html>

```

```

service.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Business</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Header -->
  <header class="header">
    <h1>My Business</h1>
    <nav>
  <a href="index.html">Home</a>
  <a href="services.html">Services</a>
  <a href="about.html">About</a>
  <a href="contact.html">Contact</a>
</nav>

  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-text">
      <h2>Grow Your Business With Us</h2>
      <p>We provide modern web solutions for your business growth.</p>
      <button>Get Started</button>
    </div>
    <div class="hero-img">
      <img src="buss.jpg" alt="Business" />
    </div>
  </section>

  <!-- Services -->
  <section class="services">
    <h2>Our Services</h2>
    <div class="service-container">
      <div class="card">
        <h3>Web Design</h3>
        <p>Modern and responsive website design.</p>
      </div>
      <div class="card">
        <h3>Development</h3>
        <p>Fast and secure web development.</p>
      </div>
      <div class="card">
        <h3>Marketing</h3>
        <p>Grow your business with digital marketing.</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <p>© 2026 My Business. All Rights Reserved.</p>
  </footer>

</body>
</html>


```
```
about.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About - My Business</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header class="header">
    <h1>My Business</h1>
    <nav>
      <a href="index.html">Home</a>
<a href="services.html">Services</a>
<a href="about.html" class="active">About</a>
<a href="contact.html">Contact</a>

    </nav>
  </header>

  <section class="hero">
    <div class="hero-text">
      <h2>About Our Company</h2>
      <p>
        We are a team of passionate developers and designers who help
        businesses grow online. Our mission is to create modern,
        user-friendly websites that give real results.
      </p>
      <p>
        Founded in 2026, we have worked with many clients and delivered
        quality projects on time.
      </p>
    </div>
    <div class="hero-img">
      <img src="human.jpg" alt="About Us" />
    </div>
  </section>

  <footer class="footer">
    <p>© 2026 My Business. All Rights Reserved.</p>
  </footer>

</body>
</html>


```

```
contact.html


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contact - My Business</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header class="header">
    <h1>My Business</h1>
    <nav>
      <a href="index.html">Home</a>
<a href="services.html">Services</a>
<a href="about.html">About</a>
<a href="contact.html" class="active">Contact</a>

    </nav>
  </header>

  <section class="services">
    <h2>Contact Us</h2>
    <div class="service-container">

      <div class="card">
        <h3>Address</h3>
        <p>Chennai, Tamil Nadu, India</p>
      </div>

      <div class="card">
        <h3>Email</h3>
        <p>mybusiness@gmail.com</p>
      </div>

      <div class="card">
        <h3>Phone</h3>
        <p>+91 98765 43210</p>
      </div>

    </div>
  </section>

  <footer class="footer">
    <p>© 2026 My Business. All Rights Reserved.</p>
  </footer>

</body>
</html>

```

## OUTPUT

![alt text](<commercial_website/Screenshot 2026-02-11 183847.png>) 
![alt text](<commercial_website/Screenshot 2026-02-11 183858.png>) 
![alt text](<commercial_website/Screenshot 2026-02-11 183908.png>) 
![alt text](<commercial_website/Screenshot 2026-02-11 183918.png>)
## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
