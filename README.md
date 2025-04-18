# Hydrofusion-beta-1.0
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Space Dragon Technology | HydroFusion MVP</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600&family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      background-color: #0b0c10;
      color: #ffffff;
    }
    header {
      background-color: #1f2833;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      font-family: 'Orbitron', sans-serif;
      color: #66fcf1;
      margin: 0;
    }
    section.hero {
      padding: 60px 20px;
      text-align: center;
      background: linear-gradient(to right, #0b0c10, #1f2833);
    }
    .hero h2 {
      font-size: 2em;
      color: #c5c6c7;
    }
    .hero p {
      font-size: 1.2em;
      max-width: 700px;
      margin: 20px auto;
    }
    section.features {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      padding: 40px 20px;
    }
    .feature {
      background-color: #45a29e;
      padding: 20px;
      border-radius: 10px;
      width: 280px;
      text-align: center;
    }
    .feature h3 {
      margin-top: 0;
    }
    section.cta {
      background-color: #66fcf1;
      color: #0b0c10;
      text-align: center;
      padding: 40px 20px;
    }
    .cta a {
      display: inline-block;
      background: #1f2833;
      color: #ffffff;
      padding: 15px 25px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    .cta a:hover {
      background: #0b0c10;
    }
    section.contact {
      padding: 60px 20px;
      background-color: #1f2833;
      text-align: center;
    }
    .contact h2 {
      color: #66fcf1;
    }
    form {
      max-width: 600px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    input, textarea {
      padding: 10px;
      border-radius: 5px;
      border: none;
      font-size: 1em;
    }
    button {
      padding: 12px;
      background-color: #45a29e;
      color: #0b0c10;
      font-weight: bold;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    button:hover {
      background-color: #66fcf1;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #1f2833;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Space Dragon Technology</h1>
  </header>

  <section class="hero">
    <h2>HydroFusion MVP: Energia Verde + Fusão Nuclear</h2>
    <p>
      Estamos construindo o futuro energético com a união da produção de hidrogênio verde e a promessa da fusão nuclear. Conheça nosso MVP e faça parte da revolução energética.
    </p>
  </section>

  <section class="features">
    <div class="feature">
      <h3>Hidrogênio Verde</h3>
      <p>Produzido via eletrólise com energia renovável e monitorado em tempo real.</p>
    </div>
    <div class="feature">
      <h3>Simulador de Fusão</h3>
      <p>Visualize como nosso futuro reator de fusão integrará à produção de energia limpa.</p>
    </div>
    <div class="feature">
      <h3>Dashboard Inteligente</h3>
      <p>Dados ao vivo de eficiência, consumo e produção energética em uma plataforma intuitiva.</p>
    </div>
  </section>

  <section class="cta">
    <h2>Quer conhecer nosso MVP de perto?</h2>
    <p>Agende uma demonstração exclusiva com nossa equipe e veja o futuro em ação.</p>
    <a href="mailto:contato@spacedragon.tech">Agendar Demonstração</a>
  </section>

  <section class="contact">
    <h2>Entre em Contato</h2>
    <form action="mailto:contato@spacedragon.tech" method="POST" enctype="text/plain">
      <input type="text" name="nome" placeholder="Seu nome" required />
      <input type="email" name="email" placeholder="Seu email" required />
      <textarea name="mensagem" rows="5" placeholder="Sua mensagem" required></textarea>
      <button type="submit">Enviar Mensagem</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Space Dragon Technology. Todos os direitos reservados.
  </footer>
</body>
</html>
