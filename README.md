<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>XV Años de Samantha</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background: linear-gradient(to bottom, #fbeaea, #fff);
      color: #333;
      overflow-x: hidden;
    }
    .hero {
      height: 100vh;
      background: url('https://images.unsplash.com/photo-1529335764857-3f1164d1cb24') no-repeat center center/cover;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      animation: fadeIn 2s ease-in;
    }
    .hero h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 4em;
      background-color: rgba(0, 0, 0, 0.5);
      padding: 20px;
      border-radius: 20px;
    }
    .content {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
      animation: slideUp 2s ease-out;
    }
    .section {
      margin-bottom: 40px;
    }
    h2 {
      font-family: 'Great Vibes', cursive;
      font-size: 2.5em;
      color: #c0392b;
      text-align: center;
    }
    p {
      font-size: 1.2em;
      text-align: center;
    }
    .map {
      width: 100%;
      height: 300px;
      margin-bottom: 20px;
      border-radius: 12px;
      overflow: hidden;
    }
    audio {
      display: none;
    }
    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
    @keyframes slideUp {
      from {transform: translateY(30px); opacity: 0;}
      to {transform: translateY(0); opacity: 1;}
    }
  </style>
</head>
<body>
  <audio autoplay loop>
    <source src="https://your-audio-link.com/a-thousand-years.mp3" type="audio/mpeg">
    Tu navegador no soporta el audio.
  </audio>  <div class="hero">
    <h1>Mis XV Años - Samantha</h1>
  </div>  <div class="content">
    <div class="section">
      <h2>¡Estás Invitado!</h2>
      <p>Te invito a celebrar conmigo el día de mis 15 años. Será una noche llena de magia y alegría, y no quiero que te la pierdas. ¡Contigo, esta celebración será aún más inolvidable!</p>
    </div><div class="section">
  <h2>🕊 Ceremonia Religiosa</h2>
  <p><strong>Parroquia de Nuestra Señora del Carmen</strong><br />
  Av Benito Juárez S/N, Cuautepec Barrio Bajo,<br />
  Gustavo A. Madero, Ciudad de México</p>
  <div class="map">
    <iframe src="https://www.google.com/maps?q=Parroquia+de+Nuestra+Señora+del+Carmen,+Gustavo+A.+Madero,+CDMX&output=embed" width="100%" height="100%" style="border:0;" allowfullscreen></iframe>
  </div>
</div>

<div class="section">
  <h2>🎉 Recepción</h2>
  <p><strong>Salón Paraíso Casa de Piedra</strong><br />
  Esquina, Avenida del Castillo, Morelos 1,<br />
  Gustavo A. Madero, Ciudad de México</p>
  <div class="map">
    <iframe src="https://www.google.com/maps?q=Salón+Paraíso+Casa+de+Piedra,+Gustavo+A.+Madero,+CDMX&output=embed" width="100%" height="100%" style="border:0;" allowfullscreen></iframe>
  </div>
</div>

  </div>
</body>
</html>