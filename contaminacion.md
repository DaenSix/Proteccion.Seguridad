---
layout: default
title: Contaminación Ambiental
---

<style>
  /* --- ANIMACIONES EN CASCADA --- */
  @keyframes fadeInUp {
    0% { opacity: 0; transform: translateY(20px); }
    100% { opacity: 1; transform: translateY(0); }
  }
  .retraso-1 { animation: fadeInUp 0.8s ease-out forwards; }
  .retraso-2 { opacity: 0; animation: fadeInUp 0.8s ease-out 0.2s forwards; }
  .retraso-3 { opacity: 0; animation: fadeInUp 0.8s ease-out 0.4s forwards; }
  .retraso-4 { opacity: 0; animation: fadeInUp 0.8s ease-out 0.6s forwards; }

  /* --- CAJA TEMÁTICA AZUL (Contaminación = Agua/Aire) --- */
  .caja-azul {
    background: linear-gradient(135deg, #e3f2fd 0%, #bbdefb 100%);
    border-left: 6px solid #0366d6;
    padding: 20px;
    margin: 20px 0;
    border-radius: 8px;
    color: #0c2d48;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    font-size: 1.1em;
    line-height: 1.6;
  }

  /* --- ESTILO DE IMÁGENES MEJORADO --- */
  .img-estilo {
    border-radius: 12px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    transition: transform 0.4s ease, box-shadow 0.4s ease;
    display: block;
    margin: 20px auto;
  }
  .img-estilo:hover {
    transform: scale(1.02);
    box-shadow: 0 12px 24px rgba(0,0,0,0.2);
  }

  /* --- TARJETAS DE CONTENIDO (GRID) --- */
  .grid-tipos {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    margin: 25px 0;
  }
  .tarjeta-tipo {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.03);
    border-top: 4px solid #0366d6;
    transition: transform 0.3s;
  }
  .tarjeta-tipo:hover {
    transform: translateY(-3px);
    box-shadow: 0 6px 15px rgba(3, 102, 214, 0.15);
  }

  /* --- BOTONES DE NAVEGACIÓN INFERIOR --- */
  .nav-botones {
    display: flex;
    justify-content: space-between;
    margin-top: 50px;
    border-top: 2px solid #eaecef;
    padding-top: 20px;
  }
  .btn-nav {
    padding: 12px 20px;
    background-color: #0366d6;
    color: white !important;
    text-decoration: none;
    border-radius: 6px;
    font-weight: bold;
    transition: all 0.3s;
  }
  .btn-nav:hover {
    background-color: #0056b3;
    transform: translateY(-2px);
    box-shadow: 0 4px 10px rgba(0,0,0,0.15);
  }
  .btn-nav.volver {
    background-color: #6a737d;
  }
  .btn-nav.volver:hover {
    background-color: #586069;
  }
</style>

<div markdown="1">

<div class="retraso-1" markdown="1">

# ¿Qué es la contaminación ambiental?

<div class="caja-azul">
  La <strong>contaminación ambiental</strong> es la introducción de sustancias químicas, físicas o biológicas en el medio ambiente que alteran su equilibrio natural, haciéndolo inseguro o no apto para su uso. Este deterioro afecta directamente a los ecosistemas y a la salud de todos los seres vivos[^1].
</div>

<img src="suelo_746x419.jpg" width="700" class="img-estilo" alt="Imagen de suelo contaminado">

</div>

<div class="retraso-2" markdown="1">

## Tipos Principales de Contaminación

Para entender el impacto global, debemos clasificar la contaminación según el medio al que afecta:



[Image of types of environmental pollution diagram]


<div class="grid-tipos" markdown="1">

<div class="tarjeta-tipo" markdown="1">
### 💨 Aire (Atmosférica)
Causada principalmente por la emisión de gases de fábricas, vehículos y la quema de combustibles fósiles (CO2, metano). Es la principal causa del calentamiento global.
</div>

<div class="tarjeta-tipo" markdown="1">
### 💧 Agua (Hídrica)
Vertidos industriales, plásticos y productos químicos agrícolas que acaban en ríos y océanos, destruyendo la biodiversidad marina y limitando el agua potable.
</div>

<div class="tarjeta-tipo" markdown="1">
### 🌍 Suelo (Terrestre)
Acumulación de basura, pesticidas y, de forma cada vez más alarmante, **basura tecnológica** que filtra metales pesados a la tierra.
</div>

</div>

</div>

<div class="retraso-3" markdown="1">

## El Impacto Invisible: La Nueva Era de la Contaminación

Históricamente, asociábamos la contaminación a chimeneas humeantes y tuberías vertiendo residuos. Sin embargo, en el siglo XXI nos enfrentamos a un nuevo desafío: **la contaminación tecnológica**. 

> *"El desarrollo digital ha traído innumerables ventajas, pero también ha generado una huella ecológica silenciosa a través de la extracción de minerales y el desecho masivo de dispositivos."*

Es vital aplicar medidas urgentes: desde la transición a energías renovables hasta la economía circular (reducir, reutilizar, reciclar). Precisamente, este aumento del consumo tecnológico nos lleva directamente al siguiente gran problema medioambiental que analizaremos en este proyecto.

</div>

<div class="retraso-4" markdown="1">

---

<div class="nav-botones">
  <a href="index.html" class="btn-nav volver">⬅️ Volver al Índice</a>
  <a href="residuos.html" class="btn-nav">Siguiente: Residuos Informáticos ➡️</a>
</div>

[^1]: **Nota técnica:** Un contaminante puede ser una sustancia química, energía (como sonido, calor o luz), o incluso radiactividad.

</div>
</div>
