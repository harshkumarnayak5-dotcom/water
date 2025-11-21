 HI! WELCOME
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Blue Water Template</title>
<style>
  /* Reset & Base Styles */
  * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
  body { background: #0a3d62; color: #fff; scroll-behavior: smooth; }
  a { text-decoration: none; color: inherit; }

  /* Navigation */
  nav { position: sticky; top: 0; background: rgba(0,0,50,0.8); display: flex; justify-content: center; padding: 15px 0; z-index: 1000; }
  nav a { margin: 0 20px; font-weight: bold; transition: color 0.3s; }
  nav a:hover { color: #00f0ff; }

  /* Sections */
  section { min-height: 100vh; display: flex; flex-direction: column; align-items: center; justify-content: center; text-align: center; padding: 50px 20px; background-size: cover; background-position: center; }
  h1 { font-size: 3rem; margin-bottom: 20px; text-shadow: 2px 2px 8px rgba(0,0,0,0.5); }
  h2 { margin-top: 40px; margin-bottom: 20px; font-size: 2rem; color: #a0e7ff; }
  h3 { margin-bottom: 10px; color: #fff; }
  p { font-size: 1.1rem; max-width: 900px; margin-bottom: 15px; line-height: 1.6; }

  /* Card Layout */
  .card-container { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin-top: 20px; }
  .card { background: rgba(0, 150, 255, 0.3); padding: 20px; border-radius: 15px; width: 300px; transition: transform 0.3s, box-shadow 0.3s; text-align: left; }
  .card:hover { transform: translateY(-10px); box-shadow: 0 10px 20px rgba(0,0,0,0.5); }

  /* Footer */
  footer { background: rgba(0,0,50,0.8); text-align: center; padding: 20px; font-size: 0.9rem; }

  /* Section Backgrounds */
  #home { background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') center/cover no-repeat; }
  #ideas { background: url('https://images.unsplash.com/photo-1506744038136-46273834b3fb') center/cover no-repeat; }
  #locations { background: url('https://images.unsplash.com/photo-1470770841072-f978cf4d019e') center/cover no-repeat; }
  #about { background: url('https://images.unsplash.com/photo-1503264116251-35a269479413') center/cover no-repeat; }

  /* Quotes */
  .quote { font-style: italic; margin: 10px 0; color: #cceeff; }
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
  <p>Greetings! Dive into the world of water, a vital resource that sustains life and inspires innovation.</p>
  <div class="quote">"Thousands have lived without love, not one without water." – W.H. Auden</div>
  <div class="quote">"Water is the driving force of all nature." – Leonardo da Vinci</div>
  <div class="quote">"When the well is dry, we know the worth of water." – Benjamin Franklin</div>
</section>

<!-- Ideas Section -->
<section id="ideas">
  <h1>Water Conservation & Management Ideas</h1>

  <!-- Primitive Ideas -->
  <h2>Primitive Ideas</h2>
  <div class="card-container">
    <div class="card">
      <h3>Rainwater Harvesting</h3>
      <p><strong>Definition:</strong> Collecting and storing rainwater in tanks, barrels, or ponds.</p>
      <p><strong>Usage:</strong> Provides water for irrigation, cleaning, and household use in areas without advanced water supply systems.</p>
    </div>
    <div class="card">
      <h3>Clay Pot Storage</h3>
      <p><strong>Definition:</strong> Using porous clay pots to naturally cool and store water.</p>
      <p><strong>Usage:</strong> Preserves water quality and reduces evaporation, especially in rural households.</p>
    </div>
    <div class="card">
      <h3>Canal Irrigation</h3>
      <p><strong>Definition:</strong> Directing river water through canals to agricultural fields.</p>
      <p><strong>Usage:</strong> Efficiently waters crops in rural areas and reduces dependency on rainfall.</p>
    </div>
  </div>

  <!-- New & Innovative Ideas -->
  <h2>New & Innovative Ideas</h2>
  <div class="card-container">
    <div class="card">
      <h3>Smart Water Meters</h3>
      <p><strong>Definition:</strong> Digital devices that track water usage and detect leaks.</p>
      <p><strong>Usage:</strong> Helps households and industries reduce wastage and monitor consumption efficiently.</p>
    </div>
    <div class="card">
      <h3>Desalination</h3>
      <p><strong>Definition:</strong> Removing salt and impurities from seawater to make it drinkable.</p>
      <p><strong>Usage:</strong> Provides freshwater in coastal and arid regions with limited natural sources.</p>
    </div>
    <div class="card">
      <h3>Solar-Powered Purification</h3>
      <p><strong>Definition:</strong> Using solar energy to purify contaminated water.</p>
      <p><strong>Usage:</strong> Provides sustainable clean drinking water in remote and rural areas.</p>
    </div>
  </div>

  <!-- Present Ideas -->
  <h2>Present Ideas</h2>
  <div class="card-container">
    <div class="card">
      <h3>Water Recycling</h3>
      <p><strong>Definition:</strong> Treating and reusing wastewater for non-drinking purposes.</p>
      <p><strong>Usage:</strong> Conserves water for irrigation, industrial processes, and urban landscaping.</p>
    </div>
    <div class="card">
      <h3>Rain Gardens & Permeable Pavements</h3>
      <p><strong>Definition:</strong> Urban designs that absorb stormwater and reduce runoff.</p>
      <p><strong>Usage:</strong> Helps manage flooding, recharge groundwater, and prevent pollution in cities.</p>
    </div>
    <div class="card">
      <h3>Community Awareness Campaigns</h3>
      <p><strong>Definition:</strong> Educating the public about responsible water usage.</p>
      <p><strong>Usage:</strong> Promotes conservation practices and community involvement in sustainable water management.</p>
    </div>
    <div class="card">
      <h3>Greywater Reuse</h3>
      <p><strong>Definition:</strong> Reusing lightly used water from sinks, showers, and laundry.</p>
      <p><strong>Usage:</strong> Reduces freshwater demand and supplies water for irrigation or toilet flushing.</p>
    </div>
  </div>
</section>

<!-- Location Ideas Section -->

  </div>
</section>

<!-- About Us Section -->
<section id="about">
  <h1>About Us</h1>
  <p>We are passionate designers and environmental enthusiasts who love blending the serenity of water with sustainable practices. Our goal is to inspire responsible water use and create immersive, refreshing digital experiences.</p>
  <!-- Profile Block -->
  <div style="margin-top: 30px; background: rgba(0, 150, 255, 0.25); padding: 20px; border-radius: 15px; width: 320px; text-align: left;">
    <h3 style="color: #a0e7ff;">Profile Information</h3>
    <p><strong>Name:</strong> Harsh Kumar Nayak</p>
    <p><strong>Profession:</strong> Student</p>
    <p><strong>Location:</strong> Durgapur</p>
  </div>

</section>


<!-- Footer -->
<footer>
  &copy; 2025 BlueWave. All rights reserved.
</footer>

</body>
</html>




           
