<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Profil Professionnel - Arnaud Oltra</title>
  <!-- Lien vers votre feuille de style personnalisée -->
  <link rel="stylesheet" href="styles.css">
  <!-- Optionnel : Lien vers Font Awesome pour les icônes -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">
</head>
<body>
  <!-- Navigation principale -->
  <header>
    <nav>
      <ul class="navbar">
        <li><a href="#accueil">Accueil</a></li>
        <li><a href="#apropos">À propos</a></li>
        <li><a href="#competences">Compétences</a></li>
        <li><a href="#projets">Projets</a></li>
        <li><a href="#stats">Statistiques</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>
  
<!-- Section Home -->
<section id="home" class="section home">
  <div class="container">
    <h1>Arnaud Oltra</h1>
    <h3>
      Backend Developer | PHP &amp; Symfony Specialist<br>
      Advocate for Clean Code, Efficiency &amp;<br>
      Open Source Contributor
    </h3>
  </div>
</section>

<!-- Section About Me -->
<section id="about" class="section about">
  <div class="container">
    <h2>About Me</h2>
    <p>
      I am a dedicated PHP developer with a passion for clean code and SOLID principles. While I remain a staunch advocate for PHP, I’m always ready to switch technologies when the need arises.
    </p>
    <p>
      My professional life is a balanced blend of working as an in-house developer—helping companies with seamless migrations and the implementation of robust, scalable architectures—and dedicating my personal time to innovative projects. One of these projects is <strong>TerpsiConnect</strong>, a platform designed to connect amateur dancers with engaging social events.
    </p>
    <p>
      I am available to support businesses from pre-startup to scale-up with my expertise. Additionally, I author a newsletter that explores the balance between corporate life and the journey of building SaaS products.
    </p>
  </div>
</section>

  
  <!-- Section Compétences -->
  <section id="competences" class="section competences">
    <div class="container">
      <h2>Mes Compétences</h2>
      <div class="skills">
        <div class="skill">
          <i class="fab fa-html5"></i>
          <h3>HTML5</h3>
        </div>
        <div class="skill">
          <i class="fab fa-css3-alt"></i>
          <h3>CSS3</h3>
        </div>
        <div class="skill">
          <i class="fab fa-js-square"></i>
          <h3>JavaScript</h3>
        </div>
        <div class="skill">
          <i class="fab fa-python"></i>
          <h3>Python</h3>
        </div>
        <div class="skill">
          <i class="fas fa-database"></i>
          <h3>SQL</h3>
        </div>
        <!-- Vous pouvez ajouter d'autres compétences -->
      </div>
    </div>
  </section>
  
  <!-- Section Projets -->
  <section id="projets" class="section projets">
    <div class="container">
      <h2>Mes Projets</h2>
      <div class="projects-grid">
        <div class="project">
          <img src="projet1.jpg" alt="Projet 1">
          <h3>Terpsi Connect</h3>
          <p>Terspi'Connect transforme la façon dont tu expérimentes la vie nocturne en te offrant une carte interactive dynamique pour découvrir les soirées de danse près de chez toi. Que tu sois passionné de danse ou à la recherche d'une soirée animée, notre application te permet de trouver facilement les meilleurs lieux de danse et d'ajouter de nouveaux événements en temps réel.</p>
          <a href="https://terpsiconnect.com/" target="_blank">Voir le projet</a>
        </div>
        <div class="project">
          <img src="projet2.jpg" alt="Projet 2">
          <h3>Funny-quote</h3>
          <p>Une librairie pour generer des citations rigolotes.</p></p>
          <a href="https://packagist.org/packages/ol.arno/funny-quote-lib" target="_blank">Voir le projet</a>
        </div>
        <!-- Ajoutez d'autres projets si nécessaire -->
      </div>
    </div>
  </section>
  
  <!-- Section Statistiques GitHub -->
  <section id="stats" class="section stats">
    <div class="container">
      <h2>Mes Statistiques GitHub</h2>
      <div class="github-stats">
        <img src="https://github-readme-stats.vercel.app/api?username=olarno&show_icons=true&theme=light" alt="GitHub Stats">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=olarno&layout=compact&theme=light" alt="Top Langages">
      </div>
    </div>
  </section>
  
  <!-- Section Contact -->
  <section id="contact" class="section contact">
    <div class="container">
      <h2>Contactez-moi</h2>
      <p>Pour toute demande de collaboration ou d'informations complémentaires, n'hésitez pas à me contacter via le formulaire ci-dessous ou par email à <a href="mailto:votre.email@example.com">votre.email@example.com</a>.</p>
      <form action="https://formspree.io/f/yourFormID" method="POST">
        <div class="form-group">
          <label for="name">Nom</label>
          <input type="text" id="name" name="name" required placeholder="Votre nom">
        </div>
        <div class="form-group">
          <label for="email">Email</label>
          <input type="email" id="email" name="_replyto" required placeholder="Votre email">
        </div>
        <div class="form-group">
          <label for="message">Message</label>
          <textarea id="message" name="message" rows="5" required placeholder="Votre message"></textarea>
        </div>
        <button type="submit">Envoyer</button>
      </form>
    </div>
  </section>
  
  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2025 [Votre Nom]. Tous droits réservés.</p>
      <div class="social-links">
        <a href="https://github.com/olarno" target="_blank"><i class="fab fa-github"></i></a>
        <a href="https://linkedin.com/in/votreprofile" target="_blank"><i class="fab fa-linkedin"></i></a>
        <!-- Ajoutez d'autres liens sociaux si besoin -->
      </div>
    </div>
  </footer>
  
  <!-- Optionnel : inclusion d'un script JavaScript pour des interactions supplémentaires -->
  <script src="script.js"></script>
</body>
</html>
