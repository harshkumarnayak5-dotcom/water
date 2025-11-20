# water
ideas about water conservation and management
hi
PK
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
    });
  </script>
</body>
</html>
