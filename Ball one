<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>2D Realistic Beach Ball</title>
<style>
  body {
    height: 100vh;
    background: linear-gradient(to bottom, #87ceeb 0%, #bde0fe 60%, #fff 100%);
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .beach-ball {
    position: relative;
    width: 200px;
    height: 200px;
    background: radial-gradient(circle at 60px 60px, #fff 0%, #f5f5f5 10%, #ddd 100%);
    border-radius: 50%;
    box-shadow: inset -5px -5px 10px rgba(0,0,0,0.2),
                inset 8px 8px 15px rgba(255,255,255,0.4),
                0 10px 20px rgba(0,0,0,0.3);
    overflow: hidden;
  }

  /* Beach ball colorful panels */
  .panel {
    position: absolute;
    width: 100%;
    height: 100%;
    border-radius: 50%;
    clip-path: polygon(50% 50%, 100% 0, 100% 100%);
    transform-origin: center;
  }

  .panel.red {
    background: linear-gradient(to bottom, #ff4444 0%, #cc0000 100%);
    transform: rotate(0deg);
  }

  .panel.yellow {
    background: linear-gradient(to bottom, #ffe066 0%, #ffcc00 100%);
    transform: rotate(60deg);
  }

  .panel.blue {
    background: linear-gradient(to bottom, #66a3ff 0%, #0066ff 100%);
    transform: rotate(120deg);
  }

  .panel.green {
    background: linear-gradient(to bottom, #99ff99 0%, #33cc33 100%);
    transform: rotate(180deg);
  }

  .panel.orange {
    background: linear-gradient(to bottom, #ff9966 0%, #ff6600 100%);
    transform: rotate(240deg);
  }

  .panel.pink {
    background: linear-gradient(to bottom, #ff80bf 0%, #ff3399 100%);
    transform: rotate(300deg);
  }

  /* White center cap */
  .center {
    position: absolute;
    top: 50%;
    left: 50%;
    width: 40px;
    height: 40px;
    transform: translate(-50%, -50%);
    background: radial-gradient(circle at 10px 10px, #fff 0%, #ddd 80%);
    border-radius: 50%;
    box-shadow: inset -3px -3px 5px rgba(0,0,0,0.2),
                inset 2px 2px 4px rgba(255,255,255,0.6);
  }

  /* Highlight reflection for realism */
  .highlight {
    position: absolute;
    top: 20px;
    left: 30px;
    width: 80px;
    height: 80px;
    background: radial-gradient(circle, rgba(255,255,255,0.7) 0%, transparent 70%);
    border-radius: 50%;
    filter: blur(4px);
  }

  /* Ground shadow */
  .shadow {
    position: absolute;
    bottom: -15px;
    left: 50%;
    transform: translateX(-50%);
    width: 120px;
    height: 25px;
    background: radial-gradient(ellipse at center, rgba(0,0,0,0.3) 0%, transparent 80%);
    filter: blur(2px);
  }
</style>
</head>
<body>

<div class="beach-ball">
  <div class="panel red"></div>
  <div class="panel yellow"></div>
  <div class="panel blue"></div>
  <div class="panel green"></div>
  <div class="panel orange"></div>
  <div class="panel pink"></div>
  <div class="center"></div>
  <div class="highlight"></div>
  <div class="shadow"></div>
</div>

</body>
</html>
