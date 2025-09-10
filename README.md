<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple Navbar</title>
  <style>
    
    .navbar {
      display: flex;
      background-color: #9e3434;
      padding: 10px;
    }

    .navbar a {
      color: white;
      text-decoration: none;
      padding: 10px 15px;
      text-align: center;
    }

    
    .navbar a:hover {
      background-color: #f03939;
      border-radius: 10px;
    }
    section {
       padding-bottom: 80px;

    }
    #home {
        padding-bottom: 1000px;
        background-color: aqua;
    }#about {
        padding-bottom: 1000px;
        background-color: rebeccapurple;
    }#services {
        padding-bottom: 1000px;
        background-color: red;
    }#contact {
        padding-bottom: 1000px;
        background-color: green;
    }

   
    @media (max-width: 600px) {
      .navbar {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <div class="navbar">
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </div>
      <section id="home">
        <h2>Welcome to my new page</h2>
        </section>
        <section id="about">
        <h2>Welcome to my new page</h2>
        </section>
        <section id="services">
        <h2>Welcome to my new page</h2>
        </section>
        <section id="contact">
        <h2>Welcome to my new page</h2>
        </section>




  
</body>
</html>
