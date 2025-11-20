# water
Hi
Ideas about Water Conservation and Management

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Blue Water Template</title>
<style>
  /* General Styles */
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
  }

  body {
    background: linear-gradient(to bottom, #0f2027, #203a43, #2c5364); /* deep blue gradient */
    color: #fff;
    overflow-x: hidden;
  }

  nav {
    display: flex;
    justify-content: center;
    background: rgba(0,0,50,0.7);
    padding: 15px 0;
    position: sticky;
    top: 0;
    z-index: 10;
    backdrop-filter: blur(5px);
  }

  nav a {
    margin: 0 20px;
    text-decoration: none;
    color: #fff;
    font-weight: bold;
    transition: transform 0.3s, color 0.3s;
  }

  nav a:hover {
    color: #00f0ff;
    transform: scale(1.1);
  }

  section {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    position: relative;
    padding: 50px 20px;
    perspective: 1000px; /* For 3D effects */
  }

  h1 {
    font-size: 4rem;
    margin-bottom: 20px;
    text-shadow: 2px 2px 8px rgba(0,0,0,0.7);
    transform: rotateX(5deg) rotateY(-5deg);
  }

  p {
    font-size: 1.3rem;
    max-width: 800px;
    margin: 10px auto;
    line-height: 1.6;
    text-shadow: 1px 1px 4px rgba(0,0,0,0.5);
  }

  .card {
    background: rgba(0, 100, 200, 0.3);
    border-radius: 20px;
    padding: 30px;
    margin: 20px;
    width: 300px;
    transform: rotateY(5deg);
    box-shadow: 0 10px 30px rgba(0,0,0,0.5);
    transition: transform 0.5s, box-shadow 0.5s;
  }

  .card:hover {
    transform: rotateY(0deg) translateZ(20px);
    box-shadow: 0 20px 50px rgba(0,0,0,0.7);
  }

  footer {
    background: rgba(0,0,50,0.8);
    text-align: center;
    padding: 20px;
    font-size: 0.9rem;
    margin-top: 50px;
  }

  /* Page specific background waves */
  #home {
    background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') center/cover no-repeat;
  }

  #ideas {
    background: url('https://images.unsplash.com/photo-1506744038136-46273834b3fb') center/cover no-repeat;
  }

  #locations {
    background: url('https://images.unsplash.com/photo-1470770841072-f978cf4d019e') center/cover no-repeat;
  }

  #about {
    background: url('https://images.unsplash.com/photo-1503264116251-35a269479413') center/cover no-repeat;
  }

</style>
</head>
<body>

<!-- Navigation -->
<nav>
  <a href="#home">Home</a>
  <a href="#ideas">Ideas</a>
  <a href="#locations">Location Ideas</a>
  <a href="#about">About Us</a>
</nav>

<!-- Home Section -->
<section id="home">
  <h1>Welcome to BlueWave</h1>
  <p>Immerse yourself in creativity, innovation, and inspiration. Our blue water themed designs bring calmness and clarity to your digital space.</p>
</section>

<!-- Ideas Section -->
<section id="ideas">
  <h1>Ideas</h1>
  <div class="card">Idea 1: Innovative water-themed interface</div>
  <div class="card">Idea 2: Interactive 3D animations</div>
  <div class="card">Idea 3: Modern UI/UX inspired by ocean waves</div>
</section>

<!-- Location Ideas Section -->
<section id="locations">
  <h1>Location Ideas</h1>
  <div class="card">Beachfront resorts</div>
  <div class="card">Underwater exhibits</div>
  <div class="card">Lakeside retreats</div>
</section>

<!-- About Us Section -->
<section id="about">
  <h1>About Us</h1>
  <p>We are passionate designers who love blending the serenity of water with modern technology. Our goal is to craft immersive experiences that feel as refreshing as the ocean breeze.</p>
</section>

<!-- Footer -->
<footer>
  &copy; 2025 BlueWave. All rights reserved.
</footer>

</body>
</html>


           
