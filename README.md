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
<section id="locations">
    <h1>Location-Based Water Conservation Ideas</h1>
    <p>Search your city to find useful water conservation practices suited for your region.</p>

    <!-- Search Bar -->
    <input type="text" id="searchBar" placeholder="Search Location or Idea...">

    <div class="card-container" id="locationCards">

        <!-- Kolkata -->
        <div class="card" data-name="Kolkata rainwater recharge">
            <h3>Kolkata</h3>
            <p><strong>Best Idea:</strong> Urban Rainwater Recharge</p>
            <p><strong>Definition:</strong> Capturing rooftop rainwater and directing it underground to replenish aquifers.</p>
            <p><strong>How to Implement:</strong>  
                Kolkata receives high rainfall and has soft alluvial soil. Install rooftop pipes → sand filter → recharge pit → perforated rings to refill groundwater.
            </p>
        </div>

        <!-- Asansol -->
        <div class="card" data-name="Asansol mining water recycling">
            <h3>Asansol</h3>
            <p><strong>Best Idea:</strong> Mining Water Recycling</p>
            <p><strong>Definition:</strong> Treating and reusing water extracted from mining areas.</p>
            <p><strong>How to Implement:</strong>  
                Asansol has numerous mines. Set up settling tanks to remove coal dust, then use filtered water for industrial cooling and roadside irrigation.
            </p>
        </div>

        <!-- Siliguri -->
        <div class="card" data-name="Siliguri watershed conservation forest">
            <h3>Siliguri</h3>
            <p><strong>Best Idea:</strong> Hill Watershed Conservation</p>
            <p><strong>Definition:</strong> Protecting streams and slopes to maintain continuous water flow.</p>
            <p><strong>How to Implement:</strong>  
                The Himalayan foothills region benefits from contour trenches, bamboo check-dams, and reforesting slopes to slow runoff and store water naturally.
            </p>
        </div>

        <!-- Berhampore -->
        <div class="card" data-name="Berhampore riverbank filtration">
            <h3>Berhampore</h3>
            <p><strong>Best Idea:</strong> Riverbank Filtration (RBF)</p>
            <p><strong>Definition:</strong> Purifying river water naturally by passing it through sand, soil, and gravel layers.</p>
            <p><strong>How to Implement:</strong>  
                Near the Bhagirathi River, install wells a few meters inland. River water seeps underground, gets naturally filtered, then pumped as clean water.
            </p>
        </div>

        <!-- Durgapur -->
        <div class="card" data-name="Durgapur industrial reuse">
            <h3>Durgapur</h3>
            <p><strong>Best Idea:</strong> Industrial Greywater Reuse</p>
            <p><strong>Definition:</strong> Treating and reusing lightly used industrial wastewater.</p>
            <p><strong>How to Implement:</strong>  
                Durgapur’s industrial zone can set up membrane filters to reuse water for cooling towers, reducing stress on the Damodar river supply.
            </p>
        </div>
        <!-- Raniganj -->
<div class="card" data-name="Raniganj mine water purification reuse">
    <h3>Raniganj</h3>
    <p><strong>Best Idea:</strong> Mine Water Purification & Reuse</p>
    <p><strong>Definition:</strong> Treating water pumped out from coal mines for safe reuse.</p>
    <p><strong>How to Implement:</strong>
        Raniganj’s mining belt produces substantial seepage water. Use sedimentation tanks + aeration + sand filters to supply clean water to nearby towns.
    </p>
</div>

<!-- Malda -->
<div class="card" data-name="Malda flood plain rainwater harvesting">
    <h3>Malda</h3>
    <p><strong>Best Idea:</strong> Floodplain Rainwater Harvesting</p>
    <p><strong>Definition:</strong> Storing excess monsoon water in ponds for year-long use.</p>
    <p><strong>How to Implement:</strong>
        Malda’s monsoon floods can be turned beneficial by deepening ponds, constructing embankments, and building community water reservoirs.
    </p>
</div>

<!-- Bardhaman -->
<div class="card" data-name="Bardhaman agricultural micro irrigation">
    <h3>Bardhaman</h3>
    <p><strong>Best Idea:</strong> Agricultural Micro-Irrigation</p>
    <p><strong>Definition:</strong> Drip and sprinkler systems to reduce water usage.</p>
    <p><strong>How to Implement:</strong>
        Large paddy fields can adopt solar-powered drip networks to supply controlled water and reduce groundwater pressure.
    </p>
</div>

<!-- Haldia -->
<div class="card" data-name="Haldia industrial water recycling port city">
    <h3>Haldia</h3>
    <p><strong>Best Idea:</strong> Industrial Effluent Recycling</p>
    <p><strong>Definition:</strong> Recycling usable water from industrial discharges.</p>
    <p><strong>How to Implement:</strong>
        Haldia’s petrochemical industries can adopt membrane bioreactors and reuse treated water for cooling and cleaning.
    </p>
</div>

<!-- Darjeeling -->
<div class="card" data-name="Darjeeling hill spring rejuvenation">
    <h3>Darjeeling</h3>
    <p><strong>Best Idea:</strong> Hill Spring Rejuvenation</p>
    <p><strong>Definition:</strong> Restoring natural springs by repairing recharge zones.</p>
    <p><strong>How to Implement:</strong>
        Build contour trenches, bamboo dams, and plant deep-rooted Himalayan trees to revive drying springs.
    </p>
</div>

<!-- Howrah -->
<div class="card" data-name="Howrah urban wastewater treatment">
    <h3>Howrah</h3>
    <p><strong>Best Idea:</strong> Urban Wastewater Treatment</p>
    <p><strong>Definition:</strong> Cleaning wastewater before it enters the Hooghly River.</p>
    <p><strong>How to Implement:</strong>
        Install decentralized treatment plants near drainage outlets to prevent direct discharge into the river.
    </p>
</div>

<!-- Kharagpur -->
<div class="card" data-name="Kharagpur canal modernization irrigation">
    <h3>Kharagpur</h3>
    <p><strong>Best Idea:</strong> Canal Modernization</p>
    <p><strong>Definition:</strong> Improving canal systems to reduce leakage and evaporation.</p>
    <p><strong>How to Implement:</strong>
        Kharagpur’s canal network can be lined with concrete and equipped with gates for controlled irrigation flow.
    </p>
</div>

<!-- Midnapore (Medinipur) -->
<div class="card" data-name="Midnapore Medinipur check dams rainwater storage">
    <h3>Midnapore (Medinipur)</h3>
    <p><strong>Best Idea:</strong> Check Dam Construction</p>
    <p><strong>Definition:</strong> Small barriers across streams to store water.</p>
    <p><strong>How to Implement:</strong>
        Undulating terrain near forests is ideal for stone-based check dams that store monsoon water and recharge groundwater.
    </p>
</div>

<!-- Nabadwip -->
<div class="card" data-name="Nabadwip river sediment management">
    <h3>Nabadwip</h3>
    <p><strong>Best Idea:</strong> River Sediment Management</p>
    <p><strong>Definition:</strong> Removing sediment to improve river water flow and quality.</p>
    <p><strong>How to Implement:</strong>
        The Ganga’s shifting course near Nabadwip requires periodic desilting and riverbank stabilization.
    </p>
</div>

<!-- Dankuni -->
<div class="card" data-name="Dankuni stormwater harvesting urban">
    <h3>Dankuni</h3>
    <p><strong>Best Idea:</strong> Urban Stormwater Harvesting</p>
    <p><strong>Definition:</strong> Collecting city runoff for reuse.</p>
    <p><strong>How to Implement:</strong>
        Surrounded by industries and highways, Dankuni can build roadside recharge wells and stormwater ponds.
    </p>
</div>

<!-- Jalpaiguri -->
<div class="card" data-name="Jalpaiguri watershed river embankments">
    <h3>Jalpaiguri</h3>
    <p><strong>Best Idea:</strong> Riverbank Strengthening & Watershed Care</p>
    <p><strong>Definition:</strong> Protecting riverbanks against floods.</p>
    <p><strong>How to Implement:</strong>
        Construct coir-based embankments and plant native trees along the Teesta to reduce erosion.
    </p>
</div>

<!-- Balurghat -->
<div class="card" data-name="Balurghat groundwater revival ponds">
    <h3>Balurghat</h3>
    <p><strong>Best Idea:</strong> Groundwater Revival Through Pond Renovation</p>
    <p><strong>Definition:</strong> Cleaning and deepening ponds to recharge aquifers.</p>
    <p><strong>How to Implement:</strong>
        Renovate old ponds and create drainage channels to collect rainwater.
    </p>
</div>

<!-- Santipur -->
<div class="card" data-name="Santipur textile industry water reuse">
    <h3>Santipur</h3>
    <p><strong>Best Idea:</strong> Textile Water Recycling</p>
    <p><strong>Definition:</strong> Reusing water from dyeing and washing processes.</p>
    <p><strong>How to Implement:</strong>
        Install color-removal filters and reuse treated water in textile operations.
    </p>
</div>

<!-- Murshidabad -->
<div class="card" data-name="Murshidabad canal restoration jheel conservation">
    <h3>Murshidabad</h3>
    <p><strong>Best Idea:</strong> Canal & Jheel Restoration</p>
    <p><strong>Definition:</strong> Restoring historic water channels.</p>
    <p><strong>How to Implement:</strong>
        Clear silted canals, reconnect jheels, and revive Nawab-era water structures.
    </p>
</div>

<!-- Bolpur -->
<div class="card" data-name="Bolpur Santiniketan red soil rainwater harvesting">
    <h3>Bolpur</h3>
    <p><strong>Best Idea:</strong> Red Soil Rainwater Harvesting</p>
    <p><strong>Definition:</strong> Capturing rainwater in areas with poor water retention.</p>
    <p><strong>How to Implement:</strong>
        Build large contour ponds and rooftop harvesting systems to supplement dry red-soil areas around Shantiniketan.
    </p>
</div>
<!-- Purulia -->
<div class="card" data-name="Purulia drought management rooftop rainwater harvesting">
    <h3>Purulia</h3>
    <p><strong>Best Idea:</strong> Rooftop Rainwater Harvesting</p>
    <p><strong>Definition:</strong> Collecting and storing rainwater from rooftops during monsoon.</p>
    <p><strong>How to Implement:</strong>
        Purulia’s dry climate makes storage crucial. Install rooftop gutters → mesh filter → storage tanks to ensure water availability in summer months.
    </p>
</div>

<!-- Digha -->
<div class="card" data-name="Digha desalination coastal water purification">
    <h3>Digha</h3>
    <p><strong>Best Idea:</strong> Small-Scale Solar Desalination</p>
    <p><strong>Definition:</strong> Using sunlight to remove salt from seawater.</p>
    <p><strong>How to Implement:</strong>
        Coastal geography allows solar stills or community desalination units to supply fresh water for tourism and households.
    </p>
</div>

<!-- Jhargram -->
<div class="card" data-name="Jhargram forest watershed check dams">
    <h3>Jhargram</h3>
    <p><strong>Best Idea:</strong> Small Check Dams in Forest Streams</p>
    <p><strong>Definition:</strong> Building small barriers to slow stream water and recharge the ground.</p>
    <p><strong>How to Implement:</strong>
        Undulating forest terrain is perfect for stone/boulder dams that preserve rainwater for wildlife and villages.
    </p>
</div>

<!-- Kolaghat -->
<div class="card" data-name="Kolaghat thermal power water recycling">
    <h3>Kolaghat</h3>
    <p><strong>Best Idea:</strong> Thermal Power Plant Water Recycling</p>
    <p><strong>Definition:</strong> Reusing treated industrial water in cooling systems.</p>
    <p><strong>How to Implement:</strong>
        Kolaghat’s power plant can adopt circular filtration systems to reduce dependence on the Rupnarayan River.
    </p>
</div>

<!-- Mayapur -->
<div class="card" data-name="Mayapur riverbank filtration ganga">
    <h3>Mayapur</h3>
    <p><strong>Best Idea:</strong> Riverbank Filtration (RBF) along the Ganga</p>
    <p><strong>Definition:</strong> Natural purification of river water through soil layers.</p>
    <p><strong>How to Implement:</strong>
        Build wells slightly away from Ganga banks—water naturally filters through sand and becomes potable.
    </p>
</div>

<!-- Kishanganj -->
<div class="card" data-name="Kishanganj rain-fed agriculture micro irrigation">
    <h3>Kishanganj</h3>
    <p><strong>Best Idea:</strong> Micro-Irrigation for Rain-Fed Agriculture</p>
    <p><strong>Definition:</strong> Using drip lines to reduce dependence on irregular rainfall.</p>
    <p><strong>How to Implement:</strong>
        High rainfall but uneven distribution—install solar-powered drip systems to stabilize farm output.
    </p>
</div>

<!-- Bankura -->
<div class="card" data-name="Bankura drought pond rejuvenation">
    <h3>Bankura</h3>
    <p><strong>Best Idea:</strong> Pond Rejuvenation for Drought Areas</p>
    <p><strong>Definition:</strong> Cleaning and deepening ponds to store monsoon water.</p>
    <p><strong>How to Implement:</strong>
        Bankura’s dry red soil region benefits from deepened tanks with silt removal and catchment channel development.
    </p>
</div>

<!-- Cooch Behar -->
<div class="card" data-name="Cooch Behar flood control embankment reinforcement">
    <h3>Cooch Behar</h3>
    <p><strong>Best Idea:</strong> Flood-Control Embankment Reinforcement</p>
    <p><strong>Definition:</strong> Strengthening riverbanks to reduce monsoon flooding.</p>
    <p><strong>How to Implement:</strong>
        Use geo-bags, bamboo walls, and native grasses along Torsa and other rivers to minimize erosion.
    </p>
</div>

<!-- Alipurduar -->
<div class="card" data-name="Alipurduar forest spring protection">
    <h3>Alipurduar</h3>
    <p><strong>Best Idea:</strong> Forest Spring Protection</p>
    <p><strong>Definition:</strong> Protecting natural water springs in forest reserves.</p>
    <p><strong>How to Implement:</strong>
        Construct spring boxes and reforest surrounding areas to maintain perennial water flow.
    </p>
</div>

<!-- Krishnanagar -->
<div class="card" data-name="Krishnanagar groundwater recharge">
    <h3>Krishnanagar</h3>
    <p><strong>Best Idea:</strong> Groundwater Recharge Pits</p>
    <p><strong>Definition:</strong> Directing clean rainwater into the ground to refill aquifers.</p>
    <p><strong>How to Implement:</strong>
        Clayey soil needs gravel-filled recharge wells near homes, parks, and schools to increase water table levels.
    </p>
</div>

<!-- Chandannagar -->
<div class="card" data-name="Chandannagar heritage water channel restoration">
    <h3>Chandannagar</h3>
    <p><strong>Best Idea:</strong> Heritage Water Channel Restoration</p>
    <p><strong>Definition:</strong> Reviving old French-era drainage and water systems.</p>
    <p><strong>How to Implement:</strong>
        Clean clogged canals and recreate filtration ponds to reduce pressure on Hooghly water.
    </p>
</div>

<!-- Serampore -->
<div class="card" data-name="Serampore stormwater recharge urban">
    <h3>Serampore</h3>
    <p><strong>Best Idea:</strong> Urban Stormwater Recharge</p>
    <p><strong>Definition:</strong> Allowing rainwater to percolate into the ground instead of flowing away.</p>
    <p><strong>How to Implement:</strong>
        Create percolation pits along busy streets to prevent flooding and increase groundwater.
    </p>
</div>

<!-- Barrackpore -->
<div class="card" data-name="Barrackpore ghats water cleaning river management">
    <h3>Barrackpore</h3>
    <p><strong>Best Idea:</strong> Ghat Area Water Cleaning & River Management</p>
    <p><strong>Definition:</strong> Preventing pollution at Hooghly River ghats.</p>
    <p><strong>How to Implement:</strong>
        Install floating trash barriers and treat wastewater before it reaches the ghats.
    </p>
</div>

<!-- Bally -->
<div class="card" data-name="Bally urban drainage rejuvenation">
    <h3>Bally</h3>
    <p><strong>Best Idea:</strong> Urban Drainage Rejuvenation</p>
    <p><strong>Definition:</strong> Clearing and restoring city drainage for clean water flow.</p>
    <p><strong>How to Implement:</strong>
        Desilt drains, install trash traps, and construct small wetlands to purify outflow water.
    </p>
</div>

<!-- Barasat -->
<div class="card" data-name="Barasat groundwater recharge pond restoration">
    <h3>Barasat</h3>
    <p><strong>Best Idea:</strong> Groundwater Recharge Through Pond Restoration</p>
    <p><strong>Definition:</strong> Reviving ponds to allow natural percolation.</p>
    <p><strong>How to Implement:</strong>
        Heavy urbanization has reduced green spaces—restore ponds, plant water-grass, and create feeder channels.
    </p>
</div>


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

<script>
/* SEARCH FUNCTION */
document.getElementById("searchBar").addEventListener("keyup", function () {
    let filter = this.value.toLowerCase();
    let cards = document.querySelectorAll("#locationCards .card");

    cards.forEach(card => {
        let text = card.getAttribute("data-name").toLowerCase();
        card.style.display = text.includes(filter) ? "block" : "none";
    });
});
</script>

</body>
</html>

</body>
</html>




           
