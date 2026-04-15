<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Opice</title>
  <style>
    body {
      background-color: #1a0a00;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
      flex-direction: column;
    }

    .opice-container {
      position: relative;
      text-align: center;
    }

    .opice-emoji {
      font-size: 200px;
      animation: houpani 1s ease-in-out infinite;
      display: block;
    }

    @keyframes houpani {
      0%   { transform: rotate(-10deg); }
      50%  { transform: rotate(10deg); }
      100% { transform: rotate(-10deg); }
    }

    .bublina {
      position: absolute;
      top: -60px;
      left: 50%;
      transform: translateX(-50%);
      background: white;
      color: #333;
      padding: 12px 20px;
      border-radius: 20px;
      font-size: 18px;
      font-weight: bold;
      white-space: nowrap;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
    }

    /* Šipka bubliny dolů */
    .bublina::after {
      content: '';
      position: absolute;
      bottom: -12px;
      left: 50%;
      transform: translateX(-50%);
      border: 6px solid transparent;
      border-top-color: white;
    }

    .banany {
      font-size: 40px;
      margin-top: 20px;
      animation: padani 0.5s ease-in-out infinite alternate;
    }

    @keyframes padani {
      0%   { transform: translateY(0px); }
      100% { transform: translateY(10px); }
    }

    h2 {
      color: #ffaa00;
      font-family: Arial;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <div class="opice-container">
    <div class="bublina">Máš ho? Espresso macchiato por favére! ☕</div>
    <span class="opice-emoji">🐒</span>
  </div>

  <div class="banany">🍌🍌🍌</div>
  <h2>Děkuji za stažení!</h2>

</body>
</html>
