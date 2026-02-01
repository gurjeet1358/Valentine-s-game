<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>How Much Do You Love Me? 💖</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #ff758c, #ff7eb3);
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      color: #fff;
      text-align: center;
    }
    .card {
      background: rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(10px);
      padding: 30px 25px;
      border-radius: 20px;
      max-width: 340px;
      width: 90%;
      box-shadow: 0 20px 40px rgba(0,0,0,0.25);
    }
    h1 {
      font-size: 1.8rem;
      margin-bottom: 10px;
    }
    p {
      font-size: 1rem;
      margin-bottom: 25px;
    }
    button {
      background: #fff;
      color: #ff4f7a;
      border: none;
      border-radius: 30px;
      padding: 12px 20px;
      font-size: 1rem;
      margin: 8px 0;
      width: 100%;
      cursor: pointer;
      transition: transform 0.15s ease, box-shadow 0.15s ease;
    }
    button:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
    }
    .hidden { display: none; }
  </style>
</head>
<body>
  <div class="card">
    <div id="step1">
      <h1>Hey Love 💕</h1>
      <p>Quick game before Valentine’s Day… ready?</p>
      <button onclick="nextStep()">I’m Ready 😍</button>
    </div><div id="step2" class="hidden">
  <h1>Question 💌</h1>
  <p>How much do you love me?</p>
  <button onclick="finalStep('A LOT 😘')">A LOT 😘</button>
  <button onclick="finalStep('TO THE MOON 🌙')">To the Moon 🌙</button>
  <button onclick="finalStep('INFINITE ♾️')">Infinite ♾️</button>
</div>

<div id="step3" class="hidden">
  <h1>❤️❤️❤️</h1>
  <p id="result"></p>
  <p>That’s exactly what I hoped you’d say.</p>
  <p><strong>Happy Valentine’s Day 💖</strong></p>
</div>

  </div>  <script>
    function nextStep() {
      document.getElementById('step1').classList.add('hidden');
      document.getElementById('step2').classList.remove('hidden');
    }

    function finalStep(answer) {
      document.getElementById('step2').classList.add('hidden');
      document.getElementById('step3').classList.remove('hidden');
      document.getElementById('result').innerText = `You chose: ${answer}`;
    }
  </script></body>
</html>
