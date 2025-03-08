# haleyhill.github.io
<!DOCTYPE html>
<html lang="en">
/* Basic Styling */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}
/*Navigation Bar */
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #222;
    padding: 15px 20px;
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 1000;
}
/*Logo */
.logo {
    color: white;
    font-size: 24px;
    font-weight: bold;
}
/* navigation Links */
.nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
}
.nav-links li {
  display: inline;
}
.nav-links a {
  text-decoration: none;
  color: white;
  font-size: 18px;
  transition: color: 0.3s;
}
.nav-links a:hover {
  color: # #f4a261; /* Accent color */
}
/* Responsive Menu for Mobile */
@media (max-width: 768px) {
  .navbar {
    flex-direction: column;
    align-itmes: center;
}
.nav-links {
  flex-direction: column;
  gap: 10px;
}
}
<head>
  <meta charset="UTF-8">
  <meta name="viewpoint" content="width=device-width,initial-scale=1.0">
  <title> Haley Hill - Portfolio </title> 
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<nav class="navbar">
  <div class="logo"> Haley Hill </div>
  <ul class="nav-links">
    <li><a href='#home">Home</a></li>
    <li><a href='#about">About </a></li>
    <li><a href='#portfolio">Portfolio</a></li>
    <li><a href='#resume>Resume </a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>
<section id="home">
<h1> Haley Hill | HRIS Specialist | Data Analyst | UX Design </h1>
<p> Welcome to my portfolio! I am Haley, I have a background in HR Information Systems, Data Analytics, Marketing, HTML and UX Design. I am creative, empathetic, hard-working, reliable, and driven. I believe the end user is the center of any successful design solution for UX, and that my mission is not complete unless I have full customer satisfaction within HRIS. </p>
</section>


</body>
</html>

