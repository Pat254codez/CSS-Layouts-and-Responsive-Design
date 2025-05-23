# CSS-Layouts-and-Responsive-Design
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Decoding code</title>
</head>
<body>

  <nav class="navbar">
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Photos</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
   <img src="[https://via.placeholder.com/600x300](https://media.istockphoto.com/id/1439993254/photo/happy-little-african-american-girl-blowing-a-flower-in-outside-cheerful-child-having-fun.jpg?b=1&s=612x612&w=0&k=20&c=-3suPruojzUbRE1sYZ3wDAv79wUw6161P56iPIGDUmY=)" alt="Sample Image" class="responsive-image">
   
@media (max-width: 768px) {
  /* CSS rules for screen sizes 768px and smaller */
  body {
    background-color: lightgreen;
  }

  .nav {
    flex-direction: column;
    align-items: center;
  }
  body {
  font-size: 1rem; /* Adjusts with the base font size */
}
h1 {
  font-size: 2rem;
}
}

</body>
</html>
