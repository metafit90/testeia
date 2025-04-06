<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gabriel Oliveira - Personal Trainer</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" integrity="sha512-VpO5j1z/VvNk3lfFdqzUxyZ8rF6c8eA8cZvmMc3rYGlKuybPfl4gADJZ6kR3RtU3u8f5F5/wD5L5+YtD1M8aGw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background: linear-gradient(135deg, #ff5722, #ff9800);
      color: #fff;
      line-height: 1.6;
      overflow-x: hidden;
    }

    header {
      text-align: center;
      padding: 60px 20px 20px;
      animation: fadeInDown 1s ease;
    }

    header img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #fff;
      margin-bottom: 20px;
    }

    header h1 {
      font-size: 2.8rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      color: #ffd8c2;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
      animation: fadeInUp 1.5s ease;
    }

    h2 {
      font-size: 2.2rem;
      margin-bottom: 20px;
      border-bottom: 2px solid #fff;
      display: inline-block;
      padding-bottom: 5px;
    }

    .sobre, .servicos, .redes {
      margin-top: 40px;
    }

    .servicos ul {
      list-style: none;
      margin-top: 20px;
    }

    .servicos ul li {
      background: rgba(255, 255, 255, 0.1);
      padding: 15px;
      margin-bottom: 15px;
      border-radius: 10px;
      transition: transform 0.3s, background 0.3s;
      cursor: pointer;
    }

    .servicos ul li:hover {
      background: rgba(255, 255, 255, 0.2);
      transform: translateY(-5px);
    }

    .redes a {
      display: inline-block;
      margin: 10px;
      padding: 12px 20px;
      background: #fff;
      color: #ff5722;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s, color 0.3s;
    }

    .redes a:hover {
      background: #ff5722;
      color: #fff;
    }

    .redes a i {
      margin-right: 8px;
    }

    footer {
      text-align: center;
      padding: 30px 20px;
      font-size: 0.9rem;
      background: rgba(0, 0, 0, 0.2);
      margin-top: 40px;
    }

    /* Botão WhatsApp flutuante */
    .whatsapp-float {
      position: fixed;
      width: 60px;
      height: 60px;
      bottom: 20px;
      right: 20px;
      background-color: #25d366;
      color: #fff;
      border-radius: 50%;
      text-align: center;
      font-size: 30px;
      box-shadow: 2px 2px 3px #999;
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: background 0.3s;
    }

    .whatsapp-float:hover {
      background-color: #20b358;
    }

    /* Animações */
    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="DA813479-8B37-475B-92A1-24BF2481E3BD.jpeg" alt="Gabriel Oliveira">
    <h1>Gabriel Oliveira</h1>
    <p>Personal Trainer - Transforme seu corpo e sua mente!</p>
  </header>

  <section class="sobre">
    <h2>Sobre Mim</h2>
    <p>
      Olá! Sou Gabriel Oliveira, personal trainer dedicado a ajudar você a alcançar o seu melhor desempenho físico e mental. Com anos de experiência em treinamento funcional, musculação e condicionamento, meu foco é personalizar cada plano para garantir resultados reais e duradouros.
    </p>
  </section>

  <section class="servicos">
    <h2>Serviços</h2>
    <ul>
      <li>Treinamento Funcional Personalizado</li>
      <li>Consultoria Online de Treinos</li>
      <li>Acompanhamento Nutricional em Parceria</li>
      <li>Preparação Física para Atletas</li>
    </ul>
  </section>

  <section class="redes">
    <h2>Redes Sociais</h2>
    <a href="https://www.instagram.com/ptgabriel.oliveira?igsh=OGZvOW9ldjVpMm40&utm_source=qr" target="_blank">
      <i class="fab fa-instagram"></i>Instagram
    </a>
  </section>

  <footer>
    &copy; 2025 Gabriel Oliveira. Todos os direitos reservados.
  </footer>

  <!-- Botão WhatsApp Flutuante -->
  <a href="https://wa.me/message/4LJ2OQGJ7MYTM1" class="whatsapp-float" target="_blank">
    <i class="fab fa-whatsapp"></i>
  </a>

</body>
</html>
