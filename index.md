---
layout: default
title: Protección Medioambiental
---

<style>
  /* Animación general de entrada */
  .animado {
    animation: fadeIn 1.2s ease-in-out;
  }
  @keyframes fadeIn {
    0% { opacity: 0; transform: translateY(15px); }
    100% { opacity: 1; transform: translateY(0); }
  }

  /* Caja de introducción con animación lateral */
  .intro-box {
    background: #f4f9f4;
    border-left: 5px solid #2ea44f;
    padding: 15px 20px;
    margin: 20px 0;
    border-radius: 0 4px 4px 0;
    color: #333;
    line-height: 1.6;
    animation: slideIn 1s ease-out;
  }
  @keyframes slideIn {
    0% { opacity: 0; transform: translateX(-30px); }
    100% { opacity: 1; transform: translateX(0); }
  }

  /* Diseño profesional para el desplegable */
  details {
    background: #fafafa;
    border: 1px solid #eaeaea;
    border-radius: 6px;
    padding: 12px;
    margin-bottom: 25px;
    transition: all 0.3s ease;
  }
  details:hover {
    border-color: #2ea44f;
  }
  summary {
    cursor: pointer;
    font-weight: bold;
    color: #24292e;
    outline: none;
  }

  /* Sistema de Grid para los enlaces del índice */
  .index-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 15px;
    margin-top: 20px;
  }

  /* Estilo avanzado para los botones */
  .indice-link {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 15px;
    background-color: #2ea44f;
    color: white !important;
    text-decoration: none;
    border-radius: 6px;
    transition: transform 0.3s, background-color 0.3s, box-shadow 0.3s;
    font-weight: 600;
    text-align: center;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }
  .indice-link:hover {
    transform: translateY(-4px);
    background-color: #22863a;
    box-shadow: 0 6px 12px rgba(0,0,0,0.15);
  }
</style>

<div class="animado" markdown="1">

# Proyecto 1: Protección Medioambiental y Tecnología

<div class="intro-box">
  <strong>Sobre este proyecto:</strong> Esta página web investiga y expone la estrecha relación entre el desarrollo tecnológico y el medio ambiente. A lo largo de las siguientes secciones, analizaremos los conceptos clave de la contaminación ambiental general, el impacto específico de los residuos informáticos (E-Waste), las estrategias comerciales como la obsolescencia programada y, finalmente, las soluciones y buenas prácticas que ofrece la informática ecológica (Green Computing) para garantizar un futuro sostenible.
</div>

---

## Criterios de Calificación

<details markdown="1">
  <summary>Haz clic aquí para desplegar la rúbrica de evaluación</summary>
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

Selecciona un apartado para acceder a la investigación detallada:

<div class="index-grid">
  <a href="contaminacion.html" class="indice-link">1. ¿Qué es la contaminación ambiental?</a>
  <a href="residuos.html" class="indice-link">2. Residuos informáticos</a>
  <a href="obsolescencia.html" class="indice-link">3. Obsolescencia programada</a>
  <a href="ecologica.html" class="indice-link">4. Informática ecológica</a>
  <a href="referencias_autores.html" class="indice-link">5. Referencias y Autores</a>
</div>

---
</div>
