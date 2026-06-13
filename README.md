<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Muhandislik maktabi</title>

  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;800&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Montserrat', sans-serif;
    }

    body {
      background: #0f0f0f;
      color: white;
    }

    /* HERO */
    .hero {
      height: 100vh;
      background: linear-gradient(120deg, #ff7a00, #111);
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 20px;
    }

    .hero h1 {
      font-size: 48px;
      font-weight: 800;
    }

    .hero p {
      margin-top: 15px;
      font-size: 18px;
      opacity: 0.9;
    }

    .btn {
      margin-top: 25px;
      padding: 12px 25px;
      background: black;
      color: white;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: white;
      color: black;
    }

    /* SECTIONS */
    .section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .title {
      font-size: 28px;
      margin-bottom: 20px;
      color: #ff7a00;
    }

    /* CARDS */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: #1c1c1c;
      padding: 20px;
      border-radius: 15px;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      background: #2a2a2a;
    }

    /* FOOTER */
    footer {
      text-align: center;
      padding: 20px;
      background: #000;
      margin-top: 40px;
      font-size: 14px;
    }
  </style>
</head>

<body>

  <!-- HERO -->
  <div class="hero">
    <div>
      <h1>Muhandislik maktabi</h1>
      <p>Robototexnika • Arduino • 3D Modeling • Dronlar</p>
      <button class="btn">Kurslarga yozilish</button>
    </div>
  </div>

  <!-- ABOUT -->
  <div class="section">
    <div class="title">Biz haqimizda</div>
    <p>
      Biz yoshlarni zamonaviy texnologiyalar: robototexnika, elektronika va muhandislik yo‘nalishlariga tayyorlaymiz.
    </p>
  </div>

  <!-- COURSES -->
  <div class="section">
    <div class="title">Kurslar</div>

    <div class="grid">
      <div class="card">🤖 Robototexnika</div>
      <div class="card">🔌 Arduino / ESP32</div>
      <div class="card">🖨 3D Modeling & Printing</div>
      <div class="card">🚁 Dron Texnologiyalari</div>
    </div>
  </div>

  <!-- CONTACT -->
  <div class="section">
    <div class="title">Aloqa</div>

    <div class="grid">
      <div class="card">📍 Jizzax shahar</div>
      <div class="card">📱 Telegram: @XolmurodovBa</div>
      <div class="card">🎓 Muhandislik maktabi</div>
    </div>
  </div>

  <footer>
    © 2026 Muhandislik maktabi | Barcha huquqlar himoyalangan
  </footer>

</body>
</html>
