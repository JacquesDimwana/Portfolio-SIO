Title: Parcours scolaire

<title>Parcours</title>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<style>
/* ===== TIMELINE STYLE ===== */
.timeline {
  position: relative;
  margin: 2rem 0;
  padding: 0;
  list-style: none;
}
.timeline::before {
  content: '';
  position: absolute;
  top: 0;
  bottom: 0;
  width: 4px;
  background: #0d6efd;
  left: 50%;
  margin-left: -2px;
}
.timeline-item {
  position: relative;
  margin: 2rem 0;
  width: 50%;
  padding: 1rem 2rem;
}
.timeline-item.left { left: 0; text-align: right; }
.timeline-item.right { left: 50%; }
.timeline-item::before {
  content: '';
  position: absolute;
  top: 20px;
  width: 20px;
  height: 20px;
  border-radius: 50%;
  background: #0d6efd;
  border: 3px solid #fff;
  box-shadow: 0 0 0 2px #0d6efd;
}
.timeline-item.left::before { right: -10px; }
.timeline-item.right::before { left: -10px; }
.timeline-item h3 { margin: 0; font-size: 1.25rem; font-weight: bold; }
.timeline-item p, .timeline-item ul { margin: 0.5rem 0 0; font-size: 0.95rem; }
.timeline-item ul { padding-left: 1.2rem; }
</style>

<body class="bg-light">
  <main class="container my-5">
    <h2 class="text-center mb-4">Mon Parcours Scolaire</h2>
    <ul class="timeline">     
      <!-- Présentation -->
      <li class="timeline-item left">
        <h3>Présentation</h3>
        <p>Bonjour, je m'appelle <strong>Jacques Dimwana</strong>. Mon cheminement a débuté par un 
        <strong>Baccalauréat STMG</strong> (Sciences et Technologies du Management et de la Gestion), 
        spécialité <strong>SIG</strong> (Systèmes d’Informations et de Gestion).</p>
        <p>J’y ai découvert la gestion, la comptabilité et les technologies des SI. C’est là que j’ai développé un premier intérêt pour l’informatique.</p>
      </li>   
      <!-- Bac STMG -->
      <li class="timeline-item right">
        <h3>Baccalauréat STMG (SIG)</h3>
        <p>Formation orientée vers le management, la gestion et les systèmes d’information.</p>
        <p>Acquisition de bases solides en économie, droit, gestion et informatique appliquée.</p>
      </li>    
      <!-- BTS SIO -->
      <li class="timeline-item left">
        <h3>BTS SIO</h3>
        <p>Intégré en <strong>2024</strong> après mon bac, pour me spécialiser dans l’informatique.</p>
        <ul>
          <li><strong>Durée :</strong> 2 ans (cours + projets + stages en entreprise).</li>
          <li><strong>Options disponibles :</strong>
            <ul>
              <li><strong>SISR</strong> : administration réseaux, cybersécurité, cloud, virtualisation.</li>
              <li><strong>SLAM</strong> : développement web, bases de données, solutions logicielles.</li>
            </ul>
          </li>
          <li><strong>Compétences acquises :</strong> développement, gestion de projets, administration systèmes.</li>
        </ul>
      </li>     
      <!-- Débouchés -->
      <li class="timeline-item right">
        <h3>Débouchés</h3>
        <p>Le BTS SIO ouvre plusieurs opportunités :</p>
        <ul>
          <li><em>Technicien support</em></li>
          <li><em>Administrateur systèmes et réseaux</em></li>
          <li><em>Développeur junior</em></li>
        </ul>
        <p>Possibilité de poursuite d’études : <strong>Bachelor, BUT, Licence, Master</strong>.</p>
      </li>     
      <!-- Projet d'avenir -->
      <li class="timeline-item left">
        <h3>Projet d’Avenir</h3>
        <p>À la suite de ce BTS, je souhaite continuer mes études pour me spécialiser davantage.</p>
        <p>Objectif : renforcer mes compétences en développement et gestion de projets numériques, 
        et évoluer vers un métier à responsabilités dans le secteur IT.</p>
      </li>     
    </ul>
  </main>
</body>
