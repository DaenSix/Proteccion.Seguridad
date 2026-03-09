---
layout: default
title: Referencias y Autores
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

  /* --- CAJA TEMÁTICA MORADA (Punto 5) --- */
  .caja-morada {
    background: linear-gradient(135deg, #f3e8ff 0%, #e9d5ff 100%);
    border-left: 6px solid #6f42c1;
    padding: 20px;
    margin: 20px 0;
    border-radius: 8px;
    color: #2c1a4d;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    font-size: 1.1em;
    line-height: 1.6;
  }

  /* --- LISTA DE REFERENCIAS --- */
  .lista-referencias {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    padding: 25px 40px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.03);
    margin: 20px 0;
  }
  .lista-referencias li {
    margin-bottom: 12px;
    color: #444d56;
    line-height: 1.5;
  }
  .lista-referencias a {
    color: #6f42c1;
    text-decoration: none;
    font-weight: bold;
  }
  .lista-referencias a:hover {
    text-decoration: underline;
  }

  /* --- TARJETAS DE AUTORES (GRID Y COLORES) --- */
  .grid-autores {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    margin: 25px 0;
  }
  .tarjeta-autor {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.03);
    transition: transform 0.3s;
  }
  .tarjeta-autor:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 15px rgba(0,0,0,0.1);
  }
  .tarjeta-autor h3 {
    margin-top: 0;
    padding-bottom: 10px;
    border-bottom: 1px solid #eaecef;
  }
  
  /* Colores específicos para cada autor (Bordes superiores y títulos) */
  .borde-joaquin { border-top: 5px solid #0366d6; }
  .borde-joaquin h3 { color: #0366d6; }
  
  .borde-alvaro { border-top: 5px solid #d73a49; }
  .borde-alvaro h3 { color: #d73a49; }
  
  .borde-juan { border-top: 5px solid #6f42c1; }
  .borde-juan h3 { color: #6f42c1; }

  /* --- BOTONES DE NAVEGACIÓN INFERIOR --- */
  .nav-botones {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 50px;
    border-top: 2px solid #eaecef;
    padding-top: 20px;
  }
  .btn-nav {
    padding: 12px 20px;
    color: white !important;
    text-decoration: none;
    border-radius: 6px;
    font-weight: bold;
    transition: all 0.3s;
    text-align: center;
    flex: 1;
    margin: 0 5px;
    min-width: 150px;
  }
  .btn-nav:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 10px rgba(0,0,0,0.15);
  }
  .btn-nav.volver {
    background-color: #6a737d;
  }
  .btn-nav.volver:hover {
    background-color: #586069;
  }
  .btn-nav.anterior {
    background-color: #2ea44f; /* Verde, porque viene de Informática Ecológica */
  }
  .btn-nav.anterior:hover {
    background-color: #22863a;
  }
</style>

<div markdown="1">

<div class="retraso-1" markdown="1">

# Referencias y Autores

<div class="caja-morada">
  La realización de este proyecto de investigación ha requerido la consulta de diversas fuentes bibliográficas, bases de datos sobre sostenibilidad y la aplicación de metodologías de trabajo colaborativo mediante el control de versiones en GitHub.
</div>

</div>

<div class="retraso-2" markdown="1">

## Fuentes de Investigación y Referencias

Toda la información, datos y cifras expuestos a lo largo de este proyecto han sido extraídos, contrastados y adaptados de las siguientes fuentes documentales y plataformas libres:

<div class="lista-referencias" markdown="1">

* **Naciones Unidas (ONU) Medio Ambiente:** Informes sobre el impacto de los residuos electrónicos globales (E-Waste Monitor).
* **Greenpeace Internacional:** Documentación sobre la obsolescencia programada y su impacto en la huella de carbono tecnológica.
* **Unsplash & Pexels:** Repositorios de imágenes libres de derechos de autor utilizadas para ilustrar los diferentes apartados.
* **Asistencia por IA:** Se ha utilizado asistencia de modelos de lenguaje (ChatGPT) para la estructuración avanzada en Markdown, generación de código CSS y revisión ortotipográfica del texto.
* **Documentación de GitHub Pages:** Guías oficiales para la implementación de sitios web estáticos y diseño *responsive*.

</div>

</div>

<div class="retraso-3" markdown="1">

## Equipo de Trabajo y Autores

Este proyecto cumple con el criterio de **"Trabajo colaborativo en grupos diferentes"**. El desarrollo de la plataforma web `informática-ambiental` se ha dividido metodológicamente de la siguiente manera:

<div class="grid-autores" markdown="1">

<div class="tarjeta-autor borde-joaquin" markdown="1">
### Joaquín
**Desarrollo Inicial y Estructura**
* Configuración del repositorio y menú de navegación lateral.
* **Punto 1:** Investigación sobre la contaminación ambiental.
* **Punto 2:** Desarrollo del apartado sobre residuos informáticos y toxicidad.
</div>

<div class="tarjeta-autor borde-alvaro" markdown="1">
### Álvaro
**Análisis y Soluciones**
* **Punto 3:** Investigación profunda sobre la obsolescencia programada.
* **Punto 4:** Desarrollo del apartado de Informática Ecológica (Green Computing) y medidas sostenibles.
</div>

<div class="tarjeta-autor borde-juan" markdown="1">
### Juan Antonio
**Documentación y Cierre**
* **Punto 5:** Recopilación de fuentes, formato final de referencias.
* Revisión de los criterios de la rúbrica de evaluación.
* Auditoría de diseño y coherencia visual del proyecto.
</div>

</div>

</div>

<div class="retraso-4" markdown="1">

---

<div class="nav-botones">
  <a href="ecologica.html" class="btn-nav anterior">⬅️ Anterior: Informática Ecológica</a>
  <a href="index.html" class="btn-nav volver">🏠 Volver al Índice Principal</a>
</div>

</div>
</div>
