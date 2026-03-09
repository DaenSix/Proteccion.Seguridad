---
layout: default
title: Protección Medioambiental
---

<style>
  /* --- ESTILOS --- */
  
  /* Animación de entrada suave */
  .fade-in { animation: fadeIn 1s ease-in-out; }
  @keyframes fadeIn {
    0% { opacity: 0; transform: translateY(15px); }
    100% { opacity: 1; transform: translateY(0); }
  }

  /* Caja de introducción con degradado elegante */
  .card-info {
    background: linear-gradient(135deg, #f0f7f4 0%, #e0ece4 100%);
    border-left: 6px solid #2ea44f;
    padding: 20px;
    margin: 25px 0;
    border-radius: 8px;
    color: #2c3e50;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    font-size: 1.05em;
    line-height: 1.6;
  }

  /* Estilo profesional para el desplegable (Details) */
  details.rubrica {
    background: #ffffff;
    border: 1px solid #d1d5da;
    border-radius: 8px;
    padding: 15px;
    margin-bottom: 30px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    transition: border-color 0.3s, box-shadow 0.3s;
  }
  details.rubrica:hover {
    border-color: #2ea44f;
    box-shadow: 0 4px 10px rgba(46, 164, 79, 0.15);
  }
  details.rubrica summary {
    cursor: pointer;
    font-weight: bold;
    color: #24292e;
    font-size: 1.1em;
    outline: none;
  }

  /* Grid para los botones del índice */
  .index-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin-top: 25px;
  }

  /* Estilo base para los botones */
  .btn-indice {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 18px 20px;
    color: white !important;
    text-decoration: none;
    border-radius: 8px;
    font-weight: bold;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition: all 0.3s ease;
  }
  .btn-indice:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 15px rgba(0,0,0,0.2);
    filter: brightness(1.1); /* Hace que el color brille un poco al pasar el ratón */
  }

  /* Paleta de colores temática para cada botón */
  .color-contaminacion { background-color: #0366d6; } 
  .color-residuos { background-color: #586069; } 
  .color-obsolescencia { background-color: #d73a49; } 
  .color-ecologica { background-color: #2ea44f; } 
  .color-referencias { background-color: #6f42c1; } 

</style>

<div class="fade-in" markdown="1">

# Proyecto 1: Protección Medioambiental y Tecnología

<div class="card-info">
  <strong>Sobre este proyecto:</strong> Esta plataforma web explora la intersección entre el avance tecnológico y la conservación del medio ambiente. Analizaremos desde la contaminación global y la gestión de los residuos electrónicos, hasta los retos que plantea la obsolescencia programada, culminando con las soluciones sostenibles que propone la informática ecológica (<em>Green Computing</em>).
</div>

---

## Criterios de Evaluación

<details class="rubrica" markdown="1">
  <summary>Haz clic aquí para consultar la rúbrica del proyecto</summary>
  <br>

| Nº | Criterio | Puntuación |
|----|----------|------------|
| 1 | Estructura completa: **Título, Índice, Referencias y Autores** | 1 punto |
| 2 | Mínimo **4 imágenes** | 1 punto |
| 3 | Desarrollo correcto de los contenidos | 1 punto por apartado |
| 4 | Uso de características de **Markdown no vistas en clase** | 1 punto |
| 5 | Trabajo colaborativo en grupos diferentes | Obligatorio |

</details>

---

## Índice de Contenidos

Selecciona un módulo para acceder a la investigación:

<div class="index-grid">
  <a href="contaminacion.html" class="btn-indice color-contaminacion">1. ¿Qué es la contaminación ambiental?</a>
  <a href="residuos.html" class="btn-indice color-residuos">2. Residuos informáticos</a>
  <a href="obsolescencia.html" class="btn-indice color-obsolescencia">3. Obsolescencia programada</a>
  <a href="ecologica.html" class="btn-indice color-ecologica">4. Informática ecológica</a>
  <a href="referencias_autores.html" class="btn-indice color-referencias">5. Referencias y Autores</a>
</div>

---
</div>
