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
</body>
</html>


Explanation


HTML Structure:

The <div> with the class navbar acts as the container for the navigation links.
Each <a> tag represents a link in the navbar.



CSS Styling:

The .navbar class uses flexbox for layout, making it easy to align items horizontally or vertically.
The .navbar a styles the links with padding, color, and hover effects.
A media query ensures the navbar adapts to smaller screens by stacking links vertically.




This is a simple yet effective way to create a navbar. You can further enhance it with dropdown menus, animations, or JavaScript for interactivity!
