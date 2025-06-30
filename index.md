---
title: CPBMF
nav_order: 1
has_children: true
permalink: /
layout: minimal
---

<style>
.title {
  font-size: 40px;
  text-align: center;
  padding: 50px;
}

.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 24px;
  margin-top: 2rem;
}

.card {
  background-color: #ffffff;
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  padding: 20px;
  text-decoration: none;
  color: inherit;
  transition: box-shadow 0.2s ease, transform 0.1s ease;
  display: flex;
  flex-direction: column;
  flex-grow: 1;
  justify-content: space-between;
  /*height: 100%;*/
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.02);
  box-sizing: border-box;
}

.card:hover {
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.08);
  transform: translateY(-4px);
}

.card h3 {
  margin: 0 0 12px 0;
  font-size: 1.1rem;
  display: flex;
  align-items: center;
  gap: 0.5rem;
  color: #0366d6;
}

.card p {
  margin: 0;
  font-size: 0.9rem;
  color: #586069;
}
</style>

<body>

<div class="title"> 
  CPBMF
</div>


<div class="card-grid">
  <div class="subheading">
  <h3> Tutoriais </h3>
  <a class="card" href="/docs/rp3-install">
    <h3>⚙️ RP3 Instalação</h3>
    <p>Guia de instalação da RP3 e dependências</p>
  </a>

  <a class="card" href="/docs/env-setup">
    <h3>🖥️ uProteins</h3>
    <p>pipeline.</p>
  </a>
  </div>
  
</div>

</body>
