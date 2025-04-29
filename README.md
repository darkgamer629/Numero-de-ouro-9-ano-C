
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Número de Ouro</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #fff8f0;
      color: #333;
    }
    header {
      background-color: #ffcc00;
      padding: 1rem;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 1000;
      text-align: center;
    }
    header h1 {
      font-size: 1.5rem;
    }
    nav {
      margin-top: 60px;
      background-color: #fff4b8;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 1rem;
      padding: 1rem;
      position: sticky;
      top: 60px;
    }
    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    section {
      padding: 1.5rem;
    }
    .galeria {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      margin-top: 1rem;
    }
    .obra, .artista {
      background-color: #fff;
      border-radius: 8px;
      padding: 1rem;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .obra img, .artista img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      margin-top: 0.5rem;
    }
    footer {
      text-align: center;
      padding: 2rem;
      font-weight: bold;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 1.2rem;
      }
      nav {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>O Número de Ouro (Φ)</h1>
  </header>

  <nav>
    <a href="#oque">O que é</a>
    <a href="#obras">Obras Famosas</a>
    <a href="#artistas">Artistas</a>
  </nav>

  <section id="oque">
    <h2>O que é o Número de Ouro?</h2>
    <p>O número de ouro, ou número phi, é uma constante matemática que desempenha um papel crucial na criação de harmonia visual na pintura e em outras formas de arte. Quando os artistas aplicam deliberadamente a proporção áurea em suas composições, as obras resultantes muitas vezes têm uma qualidade estética que cativa os observadores. O número de ouro é representado pelos gregos através do pentagrama, que contém a proporção áurea em todos os segmentos. Ele é um objeto matemático que tem forte presença nas artes, principalmente na arquitetura e na pintura.</p>
  </section>

  <section id="obras">
    <h2>Obras Famosas com a Proporção Áurea</h2>
    <div class="galeria">
      <div class="obra">
        <h3>Mona Lisa</h3>
        <p><strong>Artista:</strong> Leonardo da Vinci</p>
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/Mona_Lisa.jpg" alt="Mona Lisa">
      </div>
      <div class="obra">
        <h3>O Homem Vitruviano</h3>
        <p><strong>Artista:</strong> Leonardo da Vinci</p>
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Da_Vinci_Vitruve_Luc_Viatour.jpg" alt="Homem Vitruviano">
      </div>
      <div class="obra">
        <h3>Parthenon de Atenas</h3>
        <p><strong>Autor:</strong> Arquitetos da Grécia Antiga</p>
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/1a/Parthenon_in_Athens.jpg" alt="Parthenon de Atenas">
      </div>
      <div class="obra">
        <h3>A Criação de Adão</h3>
        <p><strong>Artista:</strong> Michelangelo</p>
        <img src="https://upload.wikimedia.org/wikipedia/commons/2/20/Michelangelo_-_Creation_of_Adam_%28cropped%29.jpg" alt="A Criação de Adão">
      </div>
      <div class="obra">
        <h3>O Nascimento de Vênus</h3>
        <p><strong>Artista:</strong> Sandro Botticelli</p>
        <img src="https://upload.wikimedia.org/wikipedia/commons/2/22/Sandro_Botticelli_-_La_nascita_di_Venere_-_Google_Art_Project_-_edited.jpg" alt="O Nascimento de Vênus">
      </div>
    </div>
  </section>

  <section id="artistas">
    <h2>Artistas que utilizaram o Número de Ouro</h2>
    <div class="galeria">
      <div class="artista">
        <h3>Leonardo da Vinci</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e2/Leonardo_da_Vinci_-_presumed_self-portrait_-_WGA12798.jpg/440px-Leonardo_da_Vinci_-_presumed_self-portrait_-_WGA12798.jpg" alt="Leonardo da Vinci">
      </div>
      <div class="artista">
        <h3>Michelangelo</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/14/Miguel_%C3%81ngel%2C_por_Daniele_da_Volterra_%28detalle%29.jpg" alt="Michelangelo">
      </div>
      <div class="artista">
        <h3>Salvador Dalí</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/5f/Salvador_Dali_NYWTS.jpg" alt="Salvador Dalí">
      </div>
      <div class="artista">
        <h3>René Descartes</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Frans_Hals_-_Portret_van_Ren%C3%A9_Descartes.jpg" alt="René Descartes">
      </div>
      <div class="artista">
        <h3>Le Corbusier</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/d/d8/Le_Corbusier.jpg" alt="Le Corbusier">
      </div>
    </div>
  </section>

  <footer>
    <p><strong>Obrigado por ler! Criado por 9º ano C</strong></p>
  </footer>

</body>
</html>
