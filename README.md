# water
ideas about water conservation and management
hi
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Water Conservation</title>

    <style>
        /* BASIC RESET */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #e8f6ff;
            color: #003d66;
            line-height: 1.7;
        }

        /* HEADER WITH WAVES */
        header {
            background: linear-gradient(to bottom, #0099ff, #0066cc);
            color: white;
            text-align: center;
            padding: 80px 20px 120px;
            position: relative;
        }

        header h1 {
            font-size: 45px;
            font-weight: bold;
        }

        header p {
            font-size: 20px;
            margin-top: 10px;
        }

        /* WAVES SVG */
        .wave {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
        }

        /* CONTENT SECTIONS */
        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        section h2 {
            color: #005c99;
            margin-bottom: 10px;
            font-size: 30px;
        }

        section p {
            font-size: 18px;
            margin-bottom: 20px;
        }

        /* CARDS */
        .card-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h3 {
            color: #0077cc;
            margin-bottom: 10px;
        }

        footer {
            background-color: #004d80;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>

<body>

    <!-- HEADER -->
    <header>
        <h1>Water Conservation & Awareness</h1>
        <p>Protecting Earth's most precious resource</p>

        <!-- WAVES EFFECT -->
        <svg class="wave" viewBox="0 0 1440 320">
            <path fill="#e8f6ff" fill-opacity="1" 
                  d="M0,256L48,245.3C96,235,192,213,288,197.3C384,181,480,171,576,170.7C672,171,768,181,864,202.7C960,224,1056,256,1152,245.3C1248,235,1344,181,1392,154.7L1440,128L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z">
            </path>
        </svg>
    </header>

    <!-- SECTION 1 -->
    <section>
        <h2>💧 Why Water Conservation Matters</h2>
        <p>
            Water is essential for life, agriculture, biodiversity, and human survival.
            With increasing population and climate change, freshwater sources are under
            serious pressure. Conservation helps maintain ecological balance and ensures
            sustainable use for future generations.
        </p>
    </section>

    <!-- SECTION 2: CARDS -->
    <section>
        <h2>🌍 Key Conservation Ideas</h2>
        <div class="card-container">
            <div class="card">
                <h3>Rainwater Harvesting</h3>
                <p>Collecting and storing rainwater helps reduce dependency on groundwater and prevents floods.</p>
            </div>

            <div class="card">
                <h3>Wetland Protection</h3>
                <p>Wetlands act as natural water filters and biodiversity hotspots that must be preserved.</p>
            </div>

            <div class="card">
                <h3>Reducing Water Pollution</h3>
                <p>Preventing industrial waste, plastics, and chemicals from entering rivers keeps ecosystems healthy.</p>
            </div>

            <div class="card">
                <h3>Smart Irrigation</h3>
                <p>Techniques like drip irrigation reduce water waste in agriculture by up to 60%.</p>
            </div>
        </div>
    </section>

    <!-- SECTION 3 -->
    <section>
        <h2>🚰 How You Can Help</h2>
        <p>
            Every individual can contribute through small daily actions—fixing leaks,
            taking shorter showers, using water-efficient appliances, and supporting
            conservation policies.
        </p>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>© 2025 Water Conservation Project | Made with 💙</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <title>Water Conservation and Management</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
    }
    
    #container {
      width: 50%;
      margin: 40px auto;
      padding: 20px;
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    
    #location-input {
      width: 100%;
      height: 40px;
      padding: 10px;
      font-size: 18px;
      border: 1px solid #ccc;
    }
    
    #submit-btn {
      width: 100%;
      height: 40px;
      background-color: #4CAF50;
      color: #fff;
      padding: 10px;
      font-size: 18px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    
    #submit-btn:hover {
      background-color: #3e8e41;
    }
    
    #result {
      margin-top: 20px;
      padding: 20px;
      background-color: #f9f9f9;
      border: 1px solid #ddd;
      border-radius: 10px;
    }
  </style>
</head>
<body>
  <div id="container">
    <h1>Water Conservation and Management</h1>
    <input id="location-input" type="text" placeholder="Enter your location">
    <button id="submit-btn">Get Conservation Ideas</button>
    <div id="result"></div>
  </div>

  <script>
    const locationInput = document.getElementById('location-input');
    const submitBtn = document.getElementById('submit-btn');
    const resultDiv = document.getElementById('result');

    submitBtn.addEventListener('click', () => {
      const location = locationInput.value;
      if (location === '') {
        alert('Please enter a location');
        return;
      }

      // Sample data for demonstration purposes only
      const conservationIdeas = {
        'Delhi': 'Rainwater harvesting, Greywater recycling, Water-efficient appliances',
        'Mumbai': 'Water-saving techniques in industries, Rainwater harvesting, Wastewater treatment',
        'Bangalore': 'Groundwater recharge, Water conservation awareness, Leaks detection',
        // Add more locations and ideas here...
      };

      const ideas = conservationIdeas[location];
      if (ideas) {
        resultDiv.innerHTML = `<h2>Conservation Ideas for ${location}:</h2><p>${ideas}</p>`;
      } else {
        resultDiv.innerHTML = `<h2>No conservation ideas found for ${location}.</h2>`;
      }
        <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Geographic Conservation and Management Ideas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 15px;
        }
        main {
            padding: 20px;
        }
        .location-select {
            margin-bottom: 20px;
        }
        .location-info {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            max-width: 1000px;
            margin: auto;
            display: none;
        }
        select {
            padding: 10px;
            font-size: 16px;
            border-radius: 5px;
            width: 100%;
            max-width: 300px;
        }
        h2 {
            color: #333;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <header>
        <h1>Geographic Conservation and Management Ideas</h1>
        <p>Learn about the best conservation strategies for the geography of West Bengal's cities</p>
    </header>

    <main>
        <div class="location-select">
            <label for="location">Select a Location:</label>
            <select id="location" onchange="showLocationInfo()">
                <option value="">-- Choose a location --</option>
                <option value="Kolkata">Kolkata</option>
                <option value="Asansol">Asansol</option>
                <option value="Siliguri">Siliguri</option>
                <option value="Berhampore">Berhampore</option>
                <option value="Durgapur">Durgapur</option>
                <option value="Raiganj">Raiganj</option>
                <option value="Malda">Malda</option>
                <option value="Bardhaman">Bardhaman</option>
                <option value="Haldia">Haldia</option>
                <option value="Darjeeling">Darjeeling</option>
                <option value="Howrah">Howrah</option>
                <option value="Kharagpur">Kharagpur</option>
                <option value="Midnapore">Midnapore</option>
                <option value="Nabadwip">Nabadwip</option>
                <option value="Dankuni">Dankuni</option>
                <option value="Jalpaiguri">Jalpaiguri</option>
                <option value="Balurghat">Balurghat</option>
                <option value="Santipur">Santipur</option>
                <option value="Murshidabad">Murshidabad</option>
                <option value="Bolpur">Bolpur</option>
                <option value="North Barrackpur">North Barrackpur</option>
                <option value="Purba Bardhaman">Purba Bardhaman</option>
                <option value="Purulia">Purulia</option>
                <option value="Bankura">Bankura</option>
            </select>
        </div>

        <div id="location-info" class="location-info">
            <h2 id="location-title">Location Details</h2>
            <p id="location-description">Select a location to view conservation ideas based on its geography.</p>
        </div>
    </main>

    <script>
        const locationData = {
            "Kolkata": {
                title: "Kolkata",
                description: "Kolkata, the capital city of West Bengal, is known for its rich cultural heritage and urban sprawl. Conservation efforts here should focus on sustainable urban development, waste management, and green spaces. Protecting the Hooghly river from pollution is crucial, alongside urban greening initiatives like rooftop gardens and community parks."
            },
            "Asansol": {
                title: "Asansol",
                description: "Asansol is a prominent industrial city. To maintain a balance between industry and ecology, it is essential to focus on air quality control, water conservation, and rehabilitation of mining areas. Green buffers around industrial zones and the promotion of renewable energy can improve environmental conditions."
            },
            "Siliguri": {
                title: "Siliguri",
                description: "Located near the foothills of the Himalayas, Siliguri is a gateway to North Bengal. Conservation efforts should include preservation of the Teesta River, promoting forest conservation in the surrounding Darjeeling hills, and ensuring sustainable tourism practices to protect biodiversity."
            },
            "Berhampore": {
                title: "Berhampore",
                description: "As a historical city, Berhampore’s conservation should include preserving its heritage sites. Focus on controlling river erosion along the Bhagirathi River, enhancing solid waste management, and promoting afforestation programs in urban areas."
            },
            "Durgapur": {
                title: "Durgapur",
                description: "Durgapur is an industrial city with major steel plants. Sustainable industrial practices should be implemented here, including reducing emissions and improving waste treatment. Additionally, reforesting the areas around the industrial zones will help improve air quality and biodiversity."
            },
            // Add more locations as per your list following the above pattern
        };

        function showLocationInfo() {
            const location = document.getElementById("location").value;
            const infoContainer = document.getElementById("location-info");

            if (location && locationData[location]) {
                const data = locationData[location];
                document.getElementById("location-title").innerText = data.title;
                document.getElementById("location-description").innerText = data.description;
                infoContainer.style.display = "block";
            } else {
                infoContainer.style.display = "none";
            }
        }
    </script>
</body>
</html>
    });
  </script>
</body>
</html>
