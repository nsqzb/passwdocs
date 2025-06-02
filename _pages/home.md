---
layout: home
title: Accueil
nav_order: 1
permalink: /
---

<style>
.hero-section {
  text-align: center;
  padding: 60px 20px;
  margin-bottom: 80px;
}

.logo {
  width: 160px;
  height: 160px;
  margin: 0 auto 30px;
  display: block;
}

.hero-title {
  font-size: 3rem;
  font-weight: 300;
  color: #2c3e50;
  margin: 20px 0;
}

.hero-subtitle {
  font-size: 1.3rem;
  color: #7f8c8d;
  margin-bottom: 40px;
}

.cta-button {
  display: inline-block;
  background: linear-gradient(135deg, #3498db, #2980b9);
  color: white;
  padding: 15px 30px;
  border-radius: 25px;
  text-decoration: none;
  font-weight: 500;
  font-size: 1.1rem;
  transition: transform 0.2s;
}

.cta-button:hover {
  transform: translateY(-2px);
  text-decoration: none;
  color: white;
}

.features-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 60px;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.feature-item {
  text-align: left;
}

.feature-title {
  font-size: 1.4rem;
  font-weight: 600;
  color: #2c3e50;
  margin-bottom: 15px;
}

.feature-description {
  color: #7f8c8d;
  line-height: 1.6;
  font-size: 1rem;
}

.bottom-section {
  margin-top: 100px;
  padding: 40px 20px;
  background-color: #f8f9fa;
  border-radius: 10px;
  text-align: center;
}
</style>

<div class="hero-section">
  <img src="logo.png" alt="Logo Passwd!" class="logo">
  
  <h1 class="hero-title">Passwd!</h1>
  
  <p class="hero-subtitle">Gérez vos mots de passe en toute simplicité</p>
  
  <a href="/guide/installation" class="cta-button">👉 Commencer</a>
</div>

<div class="features-container">
  <div class="feature-item">
    <h3 class="feature-title">Mises à jour proches du natif</h3>
    <p class="feature-description">
      Installez les mises à jour directement depuis l'application avec seulement quelques étapes supplémentaires par rapport aux applications natives.
    </p>
  </div>
  
  <div class="feature-item">
    <h3 class="feature-title">Aucune modification du système</h3>
    <p class="feature-description">
      Grâce à notre architecture modulaire, aucune modification permanente du système n'est nécessaire. Tout fonctionne en mémoire.
    </p>
  </div>
  
  <div class="feature-item">
    <h3 class="feature-title">Support étendu du matériel</h3>
    <p class="feature-description">
      Profitez de votre ancien matériel avec des fonctionnalités modernes : chiffrement AES-256, synchronisation cloud, interface moderne et bien plus encore !
    </p>
  </div>
</div>

<div class="bottom-section">
  <h2>Les dernières fonctionnalités</h2>
  <p>Découvrez toutes les nouveautés et améliorations de Passwd!</p>
</div>
