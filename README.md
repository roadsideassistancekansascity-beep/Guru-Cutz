# Guru-Cutz <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Guru Cutz - Lawn & Landscaping</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f3f3f3;
    color: #333;
  }
  header {
    background-color: #0a1d2d; /* blackish blue */
    color: #ff6f00; /* orange */
    padding: 30px;
    text-align: center;
  }
  header h1 {
    margin: 0;
    font-size: 2.5em;
  }
  header p {
    font-size: 1.2em;
    margin: 5px 0 0;
  }
  section {
    padding: 20px;
    max-width: 600px;
    margin: auto;
    text-align: center;
  }
  .services {
    display: grid;
    grid-gap: 15px;
    margin: 20px 0;
  }
  .service {
    background-color: #fff;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0px 2px 6px rgba(0,0,0,0.1);
  }
  form {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    text-align: left;
    box-shadow: 0px 2px 6px rgba(0,0,0,0.1);
  }
  input, textarea {
    width: 100%;
    padding: 10px;
    margin: 5px 0 15px;
    border-radius: 5px;
    border: 1px solid #ccc;
  }
  button {
    background-color: #ff6f00;
    color: #fff;
    border: none;
    padding: 15px 25px;
    border-radius: 5px;
    font-size: 1em;
    cursor: pointer;
  }
  button:hover {
    background-color: #e65c00;
  }
  footer {
    text-align: center;
    padding: 15px;
    font-size: 0.9em;
    color: #777;
  }
</style>
</head>
<body>

<header>
  <h1>Guru Cutz</h1>
  <p>"We Treat Every Lawn Like Our Own"</p>
  <p>Call/Text: 816-970-1777</p>
</header>

<section>
  <h2>Our Services</h2>
  <div class="services">
    <div class="service">Mowing & Edging</div>
    <div class="service">Leaf & Walnut Cleanup</div>
    <div class="service">Bush & Shrub Trimming</div>
    <div class="service">Yard Clean-Up</div>
  </div>
</section>

<section>
  <h2>Get a Quote / Book Now</h2>
  <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
    <label for="name">Full Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="phone">Phone Number:</label>
    <input type="text" id="phone" name="phone" required>

    <label for="address">Address:</label>
    <input type="text" id="address" name="address" required>

    <label for="service">Service Interested In:</label>
    <textarea id="service" name="service" rows="3" required></textarea>

    <label for="date">Preferred Date:</label>
    <input type="date" id="date" name="date" required>

    <button type="submit">Submit</button>
  </form>
</section>

<footer>
  &copy; 2025 Guru Cutz | Kansas City, MO
</footer>

</body>
</html>