<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Surprise! 🍌</title>
  <style>
    body {
      margin: 0;
      background: #1a0a00;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      font-family: Arial;
      text-align: center;
    }

    .bublina {
      background: white;
      color: #333;
      padding: 16px 28px;
      border-radius: 20px;
      font-size: 22px;
      font-weight: bold;
      margin-bottom: 20px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.4);
      animation: skakani 0.6s ease-in-out infinite alternate;
    }

    @keyframes skakani {
      0%   { transform: translateY(0px); }
      100% { transform: translateY(-10px); }
    }

    .bublina::after {
      content: '▼';
      display: block;
      color: white;
      font-size: 24px;
      margin-top: 8px;
    }

    img {
      width: 420px;
      border-radius: 20px;
      box-shadow: 0 8px 40px rgba(0,0,0,0.6);
      animation: rotace 1.5s ease-in-out infinite alternate;
    }

    @keyframes rotace {
      0%   { transform: rotate(-3deg) scale(1); }
      100% { transform: rotate(3deg) scale(1.03); }
    }

    h1 {
      color: #ffaa00;
      font-size: 28px;
      margin-top: 24px;
    }

    p {
      color: #aaa;
      font-size: 16px;
    }
  </style>
</head>
<body>

  <div class="bublina">
    Máš ho? Espresso macchiato por favére! ☕🍌
  </div>

  <img src="opice.jpg" alt="Opice">

  <h1>Děkuji za stažení! 🎉</h1>
  <p>Teď jdi udělat kafe. 🐒</p>

</body>
</html>
