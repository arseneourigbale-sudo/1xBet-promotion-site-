<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>1xBet | Offre Spéciale avec le Code PARA3</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial Black', sans-serif;
      background: linear-gradient(135deg, #0a0a23, #1e1e3f);
      color: white;
      text-align: center;
    }

    header {
      background: #007bff;
      padding: 15px;
      font-size: 1.5rem;
      font-weight: bold;
    }

    .hero {
      padding: 50px 20px;
    }

    .hero h1 {
      font-size: 2.5rem;
      animation: fadeIn 1.5s ease-in-out;
    }

    .hero p {
      margin: 15px 0 25px;
      font-size: 1.2rem;
    }

    .promo {
      font-size: 2rem;
      background: yellow;
      color: black;
      padding: 12px 25px;
      border-radius: 10px;
      font-weight: bold;
      display: inline-block;
      animation: glow 1.5s infinite alternate;
      cursor: pointer;
    }

    @keyframes glow {
      from { box-shadow: 0 0 10px yellow; }
      to { box-shadow: 0 0 25px yellow; }
    }

    .btn {
      display: inline-block;
      margin: 30px auto;
      padding: 18px 40px;
      background: #E10600; /* bouton rouge */
      color: white; /* texte blanc */
      font-size: 1.4rem;
      font-weight: bold;
      border-radius: 10px;
      text-decoration: none;
      animation: pulse 1.8s infinite, bounce 3s infinite;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.12); }
      100% { transform: scale(1); }
    }

    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-5px); }
    }

    .countdown {
      margin-top: 20px;
      font-size: 1.3rem;
      color: #ffcc00;
    }

    .features {
      margin: 40px 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: rgba(255,255,255,0.1);
      padding: 20px;
      border-radius: 12px;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .social-proof {
      margin: 40px 20px;
    }

    .progress-bar {
      width: 80%;
      background: #444;
      border-radius: 20px;
      margin: 15px auto;
      overflow: hidden;
    }

    .progress {
      height: 20px;
      width: 70%;
      background: linear-gradient(90deg, #ffcc00, #ff9900);
      animation: progressAnim 2s ease-in-out forwards;
    }

    @keyframes progressAnim {
      from { width: 30%; }
      to { width: 70%; }
    }

    footer {
      background: #111;
      padding: 15px;
      font-size: 0.9rem;
      color: #aaa;
      margin-top: 40px;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>
  <header>🔥 Offre Spéciale 1xBet - Code PARA3 🔥</header>

  <section class="hero">
    <h1>Obtiens ton BONUS exclusif 🎁</h1>
    <p>Entre ton premier pari et la victoire, il n’y a qu’un pas. Utilise le code promo <b>PARA3</b> et démarre fort !</p>

    <div class="promo" onclick="copyCode()">👉 PARA3 👈</div>
    <p><em>(Clique pour copier le code)</em></p>

    <div class="countdown">
      ⏳ Offre limitée : <span id="timer">00:05:00</span>
    </div>

    <a href="https://refpa58144.com/L?tag=d_2046307m_1599c_&site=2046307&ad=1599" target="_blank" class="btn">🚀 S’INSCRIRE MAINTENANT</a>
  </section>

  <section class="features">
    <div class="card">💰 <h3>Bonus Immédiat</h3> Multiplie tes dépôts dès ton inscription.</div>
    <div class="card">⚡ <h3>Inscription Ultra-Rapide</h3> En moins de 2 minutes, tu es prêt à jouer.</div>
    <div class="card">🏆 <h3>Exclusivité</h3> Le code <b>PARA3</b> te garantit plus d’avantages.</div>
  </section>

  <section class="social-proof">
    <h2>🔥 Plus de <span style="color:#ffcc00">3 500</span> nouveaux inscrits aujourd’hui !</h2>
    <div class="progress-bar">
      <div class="progress"></div>
    </div>
    <p>👉 Rejoins-les dès maintenant avant la fin de l’offre.</p>
    <a href="https://refpa58144.com/L?tag=d_2046307m_1599c_&site=2046307&ad=1599" target="_blank" class="btn">✅ Je m’inscris avec PARA3</a>
  </section>

  <footer>
    ⚠️ Jeu responsable – Réservé aux +18 ans | Conditions générales sur 1xBet
  </footer>

  <script>
    // Compte à rebours 5 minutes
    function startCountdown() {
      let duration = 5 * 60;
      function updateTimer() {
        let minutes = Math.floor(duration / 60);
        let seconds = duration % 60;
        document.getElementById("timer").textContent =
          "00:" + String(minutes).padStart(2, '0') + ":" + String(seconds).padStart(2, '0');
        if (duration > 0) {
          duration--;
        } else {
          duration = 5 * 60; // reset à 5 min
        }
      }
      setInterval(updateTimer, 1000);
    }
    startCountdown();

    // Copier le code promo
    function copyCode() {
      navigator.clipboard.writeText("PARA3").then(() => {
        alert("✅ Code PARA3 copié !");
      });
    }
  </script>
</body>
</html>