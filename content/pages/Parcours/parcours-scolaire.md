Title: Parcours 

<h1 id="h1">Mon parcours scolaire :</h1>

<ul class="parcours-list">
    <li><a href="/pages/parcours-scolaire" class="parcours-link">Présentation de ma scolarité avant BTS SIO</a></li>
    <li><a href="/pages/bts-sio" class="parcours-link">Présentation du BTS SIO</a></li>
</ul>

<style>
/* TITRE */
#h1 {
  font-family: 'Kanit', sans-serif; /* même style que tes titres */
  font-size: 2.5rem;
  color: rgb(0, 123, 255); /* bleu vif, cohérent avec ton site */
  text-align: center;
  margin-bottom: 25px;
  border-bottom: 3px solid rgb(0, 123, 255);
  padding-bottom: 8px;
}

/* LISTE */
.parcours-list {
  list-style: none;
  text-align: center;
  padding: 0;
  margin: 20px 0;
}

.parcours-list li {
  display: inline-block;
  margin: 10px;
}

/* LIENS */
.parcours-link {
  display: inline-block;
  padding: 10px 20px;
  border: 2px solid rgba(255, 255, 255, 0.8);
  border-radius: 20px;
  text-decoration: none;
  color: rgba(255, 255, 255, 0.9);
  font-weight: 600;
  backdrop-filter: blur(5px); /* effet verre dépoli comme tes cards */
  transition: all 0.3s ease;
}

.parcours-link:hover {
  background-color: rgba(255, 255, 255, 0.9);
  color: rgb(0, 123, 255);
  transform: scale(1.05);
}
</style>
