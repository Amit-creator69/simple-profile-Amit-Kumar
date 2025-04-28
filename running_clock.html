<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Digital Clock</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: linear-gradient(145deg, #0f172a, #1e3a8a);
      margin: 0;
      color: #f8fafc;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    .clock-container {
      position: relative;
      display: inline-block;
    }

    .digital {
      background: #ffffff;
      padding: 50px 100px;
      border-radius: 32px;
      font-size: 96px;
      font-weight: bold;
      color: #1e293b;
      text-align: center;
      transition: background 0.3s, box-shadow 0.3s, transform 0.2s;
      position: relative;
      z-index: 2;

      /* Green shadow effect */
      box-shadow: 
        0 0 20px rgba(0, 255, 0, 1.7),
        0 8px 24px rgba(0, 255, 0, 1.3);

      /* Optional text glow */
      text-shadow: 
        1px 1px 2px rgba(0, 0, 0, 0.2),
        2px 2px 4px rgba(0, 0, 0, 0.2);
    }

    .digital:hover {
      background: #facc15;
      transform: scale(1.03);
      box-shadow: 
        0 0 30px rgba(0, 255, 0, 0.9),
        0 10px 30px rgba(0, 255, 0, 0.4);
    }

    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.5);
      opacity: 0;
      transition: opacity 0.3s;
      z-index: 1;
    }

    .clock-container:hover .overlay {
      opacity: 1;
    }
  </style>
</head>
<body>
  <div class="clock-container">
    <div class="digital" id="digital-time" role="timer" aria-label="Digital clock showing current time">00:00:00</div>
    <div class="overlay"></div>
  </div>

  <script>
    const digitalTime = document.getElementById('digital-time');
    let interval;
    let hasAlerted = false;

    function updateClock() {
      const now = new Date();
      const formatTime = num => num.toString().padStart(2, '0');
      const hours = formatTime(now.getHours());
      const minutes = formatTime(now.getMinutes());
      const seconds = formatTime(now.getSeconds());
      digitalTime.textContent = `${hours}:${minutes}:${seconds}`;
    }

    function startClock() {
      interval = setInterval(updateClock, 1000);
    }

    function stopClock() {
      clearInterval(interval);
    }

    function showAlert() {
      alert("You have stopped the clock time");
    }

    digitalTime.addEventListener('mouseover', () => {
      if (!hasAlerted) {
        stopClock();
        showAlert();
        hasAlerted = true;
      }
    });

    digitalTime.addEventListener('mouseout', () => {
      startClock();
      hasAlerted = false;
    });

    startClock(); // Initialize clock on load
  </script>
</body>
</html>
