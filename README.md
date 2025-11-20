HI! WELCOME
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Blue Water Website</title>
<style>
  /* Reset & Base Styles */
  * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
  body { background: #0a3d62; color: #fff; scroll-behavior: smooth; }
  a { text-decoration: none; color: inherit; }
  nav { position: sticky; top: 0; background: rgba(0,0,50,0.8); display: flex; justify-content: center; padding: 15px 0; z-index: 1000; }
  nav a { margin: 0 20px; font-weight: bold; transition: color 0.3s; }
  nav a:hover { color: #00f0ff; }

  /* Sections */
  section { min-height: 100vh; display: flex; flex-direction: column; align-items: center; justify-content: center; text-align: center; padding: 50px 20px; background-size: cover; background-position: center; }
  h1 { font-size: 3.5rem; margin-bottom: 20px; text-shadow: 2px 2px 8px rgba(0,0,0,0.5); }
  p { font-size: 1.2rem; max-width: 800px; margin-bottom: 20px; }

  /* Cards */
  .card-container { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; }
  .card { background: rgba(0, 150, 255, 0.3); padding: 20px; border-radius: 15px; width: 250px; transition: transform 0.3s, box-shadow 0.3s; }
  .card:hover { transform: translateY(-10px); box-shadow: 0 10px 20px rgba(0,0,0,0.5); }

  /* Footer */
  footer { background: rgba(0,0,50,0.8); text-align: center; padding: 20px; font-size: 0.9rem; }

  /* Section Backgrounds */
  #home { background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') center/cover no-repeat; }
  #ideas { background: url('https://images.unsplash.com/photo-1506744038136-46273834b3fb') center/cover no-repeat; }
  #locations { background: url('https://images.unsplash.com/photo-1470770841072-f978cf4d019e') center/cover no-repeat; }
  #about { background: url('https://images.unsplash.com/photo-1503264116251-35a269479413') center/cover no-repeat; }

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
  <p>Immerse yourself in a serene blue water environment with inspiring ideas and locations.</p>
</section>

<!-- Ideas Section -->
<section id="ideas">
  <h1>Ideas</h1>
  <div class="card-container">
    <div class="card">Innovative water-themed interface</div>
    <div class="card">Interactive 3D animations</div>
    <div class="card">Modern UI/UX inspired by ocean waves</div>
  </div>
</section>

<!-- Location Ideas Section -->
<section id="locations">
  <h1>Location Ideas</h1>
  <div class="card-container">
    <div class="card">Beachfront resorts</div>
    <div class="card">Underwater exhibits</div>
    <div class="card">Lakeside retreats</div>
  </div>
</section>

<!-- About Us Section -->
<section id="about">
  <h1>About Us</h1>
  <p>We are passionate designers who love blending the serenity of water with modern digital experiences, crafting immersive and refreshing designs.</p>
</section>

<!-- Footer -->
<footer>
  &copy; 2025 BlueWave. All rights reserved.
</footer>

</body>
</html>


           
