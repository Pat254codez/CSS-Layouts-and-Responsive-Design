# CSS-Layouts-and-Responsive-Design
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Decoding code</title>

  <!-- Add internal CSS here -->
  <style>
    body {
      font-family: Century gothic, sans-serif;
      margin: 0;
      padding: 0;
    }

    .navbar {
      background-color: #333;
      padding: 10px;
    }

    .navbar ul {
      list-style: none;
      display: flex;
      justify-content: center;
      margin: 0;
      padding: 0;
    }

    .navbar ul li {
      margin: 0 15px;
    }

    .navbar ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .responsive-image {
      width: 100%;
      max-width: 600px;
      display: block;
      margin: 20px auto;
      border-radius: 10px;
    }

    h1 {
      text-align: center;
      font-size: 2rem;
    }

    /* Media query for smaller screens */
    @media (max-width: 768px) {
      body {
        background-color: lightgreen;
      }

      .navbar ul {
        flex-direction: column;
        align-items: center;
      }

      h1 {
        font-size: 1.5rem;
      }
    }
  </style>
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

  <h1>Welcome to Decoding Code</h1>

  <img
    src="https://media.istockphoto.com/id/1439993254/photo/happy-little-african-american-girl-blowing-a-flower-in-outside-cheerful-child-having-fun.jpg?b=1&s=612x612&w=0&k=20&c=-3suPruojzUbRE1sYZ3wDAv79wUw6161P56iPIGDUmY="
    alt="Happy Girl"
    class="responsive-image"
  >
</body>
</html>
