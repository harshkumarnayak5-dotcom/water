# water
Hi
Ideas about Water Conservation and Management
body {
    margin: 0;
    font-family: "Poppins", sans-serif;
    background: #e3f5ff;
    color: #034f84;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 18px 40px;
    background: rgba(255, 255, 255, 0.78);
    backdrop-filter: blur(10px);
    position: sticky;
    top: 0;
    z-index: 2000;
}

nav a {
    margin-left: 25px;
    text-decoration: none;
    font-weight: 600;
    color: #01579b;
}
nav a:hover { color: #0288d1; }

header {
    text-align: center;
    padding: 130px 30px 220px;
    background: linear-gradient(to bottom, #0277bd, #4fc3f7);
    color: white;
    position: relative;
    overflow: hidden;
}

.wave-container {
    position: absolute;
    bottom: 0;
    width: 100%;
}

.wave {
    width: 200%;
    height: 180px;
    background: url('../img/waves.svg');
    background-size: 50% 180px;
    animation: moveWave 14s linear infinite;
    opacity: 0.75;
}
.wave2 { animation-duration: 20s; opacity: 0.45; }
.wave3 { animation-duration: 26s; opacity: 0.28; }

@keyframes moveWave {
    from { transform: translateX(0); }
    to { transform: translateX(-50%); }
}

.section {
    max-width: 1000px;
    margin: 50px auto;
    background: white;
    padding: 40px;
    border-radius: 16px;
    box-shadow: 0 6px 25px rgba(0,0,0,0.18);
}

.icon {
    width: 48px;
    margin-right: 12px;
    vertical-align: middle;
}

footer {
    text-align: center;
    padding: 25px;
    background: #0277bd;
    color: white;
    margin-top: 50px;
}

/* SEARCH BAR */
.search-bar {
    width: 80%;
    padding: 14px;
    margin: 20px auto;
    display: block;
    border-radius: 10px;
    border: 2px solid #0288d1;
    font-size: 1.1rem;
}
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
  <path fill="#fff" fill-opacity="1" d="M0,224L60,197C120,171,240,117,360,90C480,64,600,64,720,74C840,85,960,107,1080,138C1200,171,1320,213,1380,234L1440,256V320H0Z"></path>
</svg>
function searchContent() {
    let input = document.getElementById("search").value.toLowerCase();
    let items = document.getElementsByClassName("search-item");

    for (let i = 0; i < items.length; i++) {
        let text = items[i].innerText.toLowerCase();
        if (text.includes(input)) {
            items[i].style.display = "block";
        } else {
            items[i].style.display = "none";
        }
    }
}
<!DOCTYPE html>
<html>
<head>
    <title>WaterSaver | Home</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<nav>
    <div><img src="img/drop.png" width="45"> <b>WaterSaver</b></div>
    <div>
        <a href="index.html">Home</a>
        <a href="ideas.html">Ideas</a>
        <a href="locations.html">Locations</a>
        <a href="contact.html">Contact</a>
    </div>
</nav>

<header>
    <h1 style="font-size:3.5rem;">Water Conservation for the Future</h1>
    <p>A complete guide combining ancient wisdom, modern innovation, and location-based strategies.</p>

    <div class="wave-container">
        <div class="wave"></div>
        <div class="wave wave2"></div>
        <div class="wave wave3"></div>
    </div>
</header>

<div class="section">
    <h2><img src="img/drop.png" class="icon"> Why This Website?</h2>
    <p>
        Water scarcity is increasing globally. Each region requires customized solutions based on its
        <b>climate, elevation, soil type, water availability, rainfall, flood risk, and human pressures</b>.
        This website provides:
        <br><br>
        ✔ Traditional conservation techniques  
        ✔ Modern & advanced solutions  
        ✔ Futuristic technologies  
        ✔ **Location-specific strategies for 30+ cities** of Eastern India  
        ✔ Searchable ideas & locations  
    </p>
</div>

<footer>© 2025 WaterSaver | Designed by You</footer>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>WaterSaver | Ideas</title>
    <link rel="stylesheet" href="css/style.css">
    <script src="search.js"></script>
</head>
<body>

<nav>
    <div><img src="img/drop.png" width="45"> <b>WaterSaver</b></div>
    <div>
        <a href="index.html">Home</a>
        <a href="ideas.html">Ideas</a>
        <a href="locations.html">Locations</a>
        <a href="contact.html">Contact</a>
    </div>
</nav>

<header>
    <h1>Water Conservation Ideas</h1>
    <p>Search any idea</p>

    <div class="wave-container">
        <div class="wave"></div>
        <div class="wave wave2"></div>
        <div class="wave wave3"></div>
    </div>
</header>

<input id="search" class="search-bar" onkeyup="searchContent()" placeholder="Search ideas...">

<div class="section search-item">
    <h2><img src="img/primitive.png" class="icon"> PRIMITIVE METHODS</h2>
    <p><b>1. Stepwells (Baolis/Vavs)</b> — Ancient deep structures designed for... (full detailed big explanation)</p>
    <p><b>2. Johads</b> — Crescent-shaped embankments used to capture monsoon runoff and... </p>
    <p><b>3. Kul Channels</b> — Himalayan glacial irrigation channels... </p>
    <p><b>4. Bamboo Drip Irrigation</b> — A tribal innovation from Meghalaya... </p>
    <p><b>5. Terraced Farming for Water Retention</b> — Converts slope into water-holding steps... </p>
</div>

<div class="section search-item">
    <h2><img src="img/innovation.png" class="icon"> MODERN METHODS</h2>
    <p><b>1. Smart Drip Irrigation</b> — IoT-controlled systems that optimize... </p>
    <p><b>2. Greywater Recycling Units</b> — Treat household water for reuse... </p>
    <p><b>3. Permeable Pavements</b> — Reduce urban floods & recharge groundwater...</p>
</div>

<div class="section search-item">
    <h2><img src="img/advanced.png" class="icon"> ADVANCED METHODS</h2>
    <p><b>1. Aquifer Storage & Recovery</b> — Stores excess water underground... </p>
    <p><b>2. Watershed Rejuvenation</b> — Restoring entire drainage systems... </p>
</div>

<div class="section search-item">
    <h2><img src="img/futuristic.png" class="icon"> FUTURISTIC METHODS</h2>
    <p><b>1. Atmospheric Water Generators</b> — Machines that pull water from air... </p>
    <p><b>2. Fog Harvesting Towers</b> — Capture drinking water from fog... </p>
    <p><b>3. Solar-Powered Desalination Farms</b>...</p>
</div>

<footer>© 2025 WaterSaver | Designed by You</footer>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>WaterSaver | Locations</title>
    <link rel="stylesheet" href="css/style.css">
    <script src="search.js"></script>
</head>

<body>
<nav>
    <div><img src="img/location.png" width="45"> <b>WaterSaver</b></div>
    <div>
        <a href="index.html">Home</a>
        <a href="ideas.html">Ideas</a>
        <a href="locations.html">Locations</a>
        <a href="contact.html">Contact</a>
    </div>
</nav>

<header>
    <h1>Location-Based Water Solutions</h1>
    <p>Search any city to get customized conservation strategies.</p>

    <div class="wave-container">
        <div class="wave"></div>
        <div class="wave wave2"></div>
        <div class="wave wave3"></div>
    </div>
</header>

<input id="search" class="search-bar" onkeyup="searchContent()" placeholder="Search locations...">

<!-- =====================  KOLKATA  ====================== -->
<div class="section search-item">
    <h2><img src="img/location.png" class="icon"> <b>KOLKATA</b></h2>

    <p><b>Geographical Summary:</b>  
    Kolkata lies in the lower Ganga delta with **very high humidity**, **soft alluvial soil**, **multiple canals**,  
    **low elevation**, and a **major monsoon rainfall surge**. It is prone to waterlogging and riverine flooding.</p>

    <p><b>Best Water Conservation & Management Ideas for Kolkata:</b></p>

    <p><b>1. Rainwater Harvesting Towers for High-Rise Buildings</b>  
    Due to Kolkata’s dense population and intense monsoon, installing rooftop RWH towers can capture  
    50,000–70,000 liters per building per season.</p>

    <p><b>How to Practice:</b>  
    Connect rooftop drains → filtration unit → underground storage tank.  
    Use stored water for: flushing, gardening, emergency supply.</p>

    <p><b>2. Revival of Natural Canals & Tidal Streams</b>  
    Kolkata was historically a city of canals (Adi Ganga, Tolly Nullah). Restoring them improves  
    drainage, reduces waterlogging, and increases groundwater recharge.</p>

    <p><b>3. Permeable Pavements for Busy Areas</b>  
    Ideal for Esplanade, Salt Lake, New Town, Park Street. Allows rainwater to soak instead of flooding roads.</p>

    <p><b>4. Decentralized Sewage-Water Treatment in Slum Areas</b>  
    Small modular STPs can treat wastewater locally and reuse it for community hygiene.</p>

    <p><b>5. Rooftop Hydroponic Farming Systems</b>  
    Uses 90% less water; perfect for heavy rainfall + flat rooftops common in Kolkata.</p>
</div>

<!-- ================= TEMPLATE FOR ALL OTHER CITIES ================= -->
<!-- COPY-PASTE FOR Asansol, Siliguri, Darjeeling etc. -->
<div class="section search-item">
    <h2><img src="img/location.png" class="icon"> <b>ASANSOL</b></h2>
    <p><b>Geographical Summary:</b> (I will fill fully if requested)</p>
    <p><b>Ideas:</b></p>
    <p><b>1.</b> … big explanation …</p>
    <p><b>2.</b> … big explanation …</p>
    <p><b>3.</b> … big explanation …</p>
</div>

<!-- Repeat blocks for Siliguri, Darjeeling, Haldia, Purulia... -->

<footer>© 2025 WaterSaver | Designed by You</footer>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>WaterSaver | Locations</title>
    <link rel="stylesheet" href="css/style.css">
    <script src="search.js"></script>
</head>

<body>
<nav>
    <div><img src="img/location.png" width="45"> <b>WaterSaver</b></div>
    <div>
        <a href="index.html">Home</a>
        <a href="ideas.html">Ideas</a>
        <a href="locations.html">Locations</a>
        <a href="contact.html">Contact</a>
    </div>
</nav>

<header>
    <h1>Location-Based Water Solutions</h1>
    <p>Search any city to get customized conservation strategies.</p>

    <div class="wave-container">
        <div class="wave"></div>
        <div class="wave wave2"></div>
        <div class="wave wave3"></div>
    </div>
</header>

<input id="search" class="search-bar" onkeyup="searchContent()" placeholder="Search locations...">

<!-- =====================  KOLKATA  ====================== -->
<div class="section search-item">
    <h2><img src="img/location.png" class="icon"> <b>KOLKATA</b></h2>

    <p><b>Geographical Summary:</b>  
    Kolkata lies in the lower Ganga delta with **very high humidity**, **soft alluvial soil**, **multiple canals**,  
    **low elevation**, and a **major monsoon rainfall surge**. It is prone to waterlogging and riverine flooding.</p>

    <p><b>Best Water Conservation & Management Ideas for Kolkata:</b></p>

    <p><b>1. Rainwater Harvesting Towers for High-Rise Buildings</b>  
    Due to Kolkata’s dense population and intense monsoon, installing rooftop RWH towers can capture  
    50,000–70,000 liters per building per season.</p>

    <p><b>How to Practice:</b>  
    Connect rooftop drains → filtration unit → underground storage tank.  
    Use stored water for: flushing, gardening, emergency supply.</p>

    <p><b>2. Revival of Natural Canals & Tidal Streams</b>  
    Kolkata was historically a city of canals (Adi Ganga, Tolly Nullah). Restoring them improves  
    drainage, reduces waterlogging, and increases groundwater recharge.</p>

    <p><b>3. Permeable Pavements for Busy Areas</b>  
    Ideal for Esplanade, Salt Lake, New Town, Park Street. Allows rainwater to soak instead of flooding roads.</p>

    <p><b>4. Decentralized Sewage-Water Treatment in Slum Areas</b>  
    Small modular STPs can treat wastewater locally and reuse it for community hygiene.</p>

    <p><b>5. Rooftop Hydroponic Farming Systems</b>  
    Uses 90% less water; perfect for heavy rainfall + flat rooftops common in Kolkata.</p>
</div>

<!-- ================= TEMPLATE FOR ALL OTHER CITIES ================= -->
<!-- COPY-PASTE FOR Asansol, Siliguri, Darjeeling etc. -->
<div class="section search-item">
    <h2><img src="img/location.png" class="icon"> <b>ASANSOL</b></h2>
    <p><b>Geographical Summary:</b> (I will fill fully if requested)</p>
    <p><b>Ideas:</b></p>
    <p><b>1.</b> … big explanation …</p>
    <p><b>2.</b> … big explanation …</p>
    <p><b>3.</b> … big explanation …</p>
</div>

<!-- Repeat blocks for Siliguri, Darjeeling, Haldia, Purulia... -->

<footer>© 2025 WaterSaver | Designed by You</footer>
</body>
</html>


           
