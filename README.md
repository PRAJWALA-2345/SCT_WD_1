<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* Navigation menu styles */
    body{
      background-color: cyan;
      text-align: center;
    }
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: #333;
      color: white;
      display: flex;
      justify-content: center;
      padding: 1rem;
    }
    nav a {
      text-decoration: none;
      color: white;
      margin: 0 1rem;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: yellow;
    }
    /* Simple page sections */
    section {
      height: 100vh;
      padding: 2rem;
      text-align: center;
    }
    #home { background-color: #f4f4f4; }
    #about { background-color: #ddd; }
    #services { background-color: #bbb; }
    #contact { background-color: #999; }
  </style>
</head>
<body>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>
  <section id="home">Home Section</section>
  <section id="about">About Section</section>
  <section id="services">Services Section</section>
  <section id="contact">Contact Section</section>
</body>
</html>
