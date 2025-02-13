<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css" >
    <title>Love you!</title>
    
</head>
<body>
    
<div class="flower">
  <div class="f-wrapper">
      <div class="flower__line"></div>
      <div class="f">
          <div class="flower__leaf flower__leaf--1"></div>
          <div class="flower__leaf flower__leaf--2"></div>
          <div class="flower__leaf flower__leaf--3"></div>
          <div class="flower__leaf flower__leaf--4"></div>
          <div class="flower__leaf flower__leaf--5"></div>
          <div class="flower__leaf flower__leaf--6"></div>
          <div class="flower__leaf flower__leaf--7"></div>
          <div class="flower__leaf flower__leaf--8 flower__fall-down--yellow"></div>
      </div>
  </div>

  <div class="f-wrapper f-wrapper--2">
      <div class="flower__line"></div>
      <div class="f">
          <div class="flower__leaf flower__leaf--1"></div>
          <div class="flower__leaf flower__leaf--2"></div>
          <div class="flower__leaf flower__leaf--3"></div>
          <div class="flower__leaf flower__leaf--4"></div>
          <div class="flower__leaf flower__leaf--5"></div>
          <div class="flower__leaf flower__leaf--6"></div>
          <div class="flower__leaf flower__leaf--7"></div>
          <div class="flower__leaf flower__leaf--8 flower__fall-down--pink"></div>
      </div>
  </div>

  <div class="f-wrapper f-wrapper--3">
      <div class="flower__line"></div>
      <div class="f">
          <div class="flower__leaf flower__leaf--1"></div>
          <div class="flower__leaf flower__leaf--2"></div>
          <div class="flower__leaf flower__leaf--3"></div>
          <div class="flower__leaf flower__leaf--4"></div>
          <div class="flower__leaf flower__leaf--5"></div>
          <div class="flower__leaf flower__leaf--6"></div>
          <div class="flower__leaf flower__leaf--7"></div>
          <div class="flower__leaf flower__leaf--8 flower__fall-down--purple"></div>
      </div>
  </div>
  <div class="flower__glass"></div>
</div>
<script>
const glass = document.querySelector('.flower__glass');
let waterLevel = 15; // Starting water level (in vmin)
const decreaseRate = 0.0002; // Water decrease per second
const maxWaterLevel = 23; // Max water level (in vmin)
const minWaterLevel = 0; // Min level (in vmin)
const decreaseInterval = 1000; // 1 second interval for water decrease

// Retrieve stored values
let lastDecreaseTime = localStorage.getItem('lastDecreaseTime');
let lastWaterLevel = localStorage.getItem('waterLevel');

// Restore previous water level if available
if (lastWaterLevel) {
    waterLevel = parseFloat(lastWaterLevel);
}

// Calculate how much time has passed and adjust water level accordingly
if (lastDecreaseTime) {
    const timeElapsed = (Date.now() - parseInt(lastDecreaseTime)) / 1000; // Time in seconds
    waterLevel = Math.max(minWaterLevel, waterLevel - timeElapsed * decreaseRate);
}

// Function to update the water level visually
function updateWaterLevel(level) {
    // Ensure water level stays within bounds
    waterLevel = Math.max(minWaterLevel, Math.min(maxWaterLevel, level));
    
    // Update the water height using the --water-height CSS variable
    document.documentElement.style.setProperty('--water-height', `${waterLevel}vmin`);

    // Save the new water level to localStorage
    localStorage.setItem('waterLevel', waterLevel);
}

// Function to increase water level (when clicked)
function increaseWater() {
    if (waterLevel < maxWaterLevel) {
        waterLevel += 5;
        if (waterLevel > maxWaterLevel) waterLevel = maxWaterLevel;
        updateWaterLevel(waterLevel);
    }
}

// Function to decrease water level over time
function decreaseWater() {
    waterLevel = Math.max(minWaterLevel, waterLevel - decreaseRate);
    updateWaterLevel(waterLevel);
    localStorage.setItem('lastDecreaseTime', Date.now());
}

// Start decreasing water every second
setInterval(decreaseWater, decreaseInterval);

// Handle click event to increase water level
glass.addEventListener('click', () => {
    increaseWater();
});

// Initial update to set correct water level on page load
updateWaterLevel(waterLevel);

</script>


</body>
</html>
