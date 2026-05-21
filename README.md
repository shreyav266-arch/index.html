<!DOCTYPE html>
<html>

<head>
<title>Shreya's Website</title>

<style>

body{
background-color: #121212;
color: white;
font-family: Arial;
margin: 0;
text-align: center;
}

/* Navigation Bar */
nav{
background-color: black;
padding: 15px;
}

nav a{
color: white;
text-decoration: none;
margin: 15px;
font-size: 18px;
}

/* Profile Image */
img{
width: 150px;
height: 150px;
border-radius: 50%;
margin-top: 20px;
border: 4px solid white;
}

/* Button */
button{
background-color: #ff4d4d;
color: white;
padding: 12px 25px;
border: none;
border-radius: 25px;
font-size: 18px;
margin-top: 20px;
}

/* About Section */
.about{
padding: 20px;
font-size: 18px;
}

/* Animation */
h1{
animation: glow 2s infinite alternate;
}

@keyframes glow{
from{
color: white;
}
to{
color: cyan;
}
}

</style>
</head>

<body>

<!-- Navigation Bar -->
<nav>
<a href="">Home</a>
<a href="">About</a>
<a href="">Contact</a>
</nav>

<!-- Photo -->
<img src="https://via.placeholder.com/150">

<!-- Heading -->
<h1>Welcome to Shreya's Website 🌸</h1>

<!-- About Section -->
<div class="about">
<p>
Hello! I am Shreya.  
I am learning Web Development using my phone.
</p>
</div>

<!-- Contact Button -->
<button onclick="alert('Thanks for visiting!')">
Contact Me
</button>

<br><br>

<!-- Instagram Link -->
<a href="https://instagram.com">
<button>Instagram</button>
</a>

<!-- LinkedIn Link -->
<a href="https://linkedin.com">
<button>LinkedIn</button>
</a>

</body>
</html>
<img src="https://picsum.photos/200">
