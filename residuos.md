---
layout: default
title: Residuos Informáticos
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

  /* --- MINI ÍNDICE INTERNO --- */
  .mini-indice {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    padding: 20px;
    border-radius: 12px;
    margin-bottom: 30px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    border-left: 5px solid #586069;
  }
  .mini-indice h4 { margin-top: 0; color: #24292e; font-size: 1.2em; }
  .mini-indice ul { list-style: none; padding-left: 0; }
  .mini-indice li { margin: 8px 0; }
  .mini-indice a { color: #0366d6; text-decoration: none; font-weight: 500; }
  .mini-indice a:hover { text-decoration: underline; color: #586069; }

  /* --- CAJA TEMÁTICA GRIS --- */
  .caja-gris {
    background: linear-gradient(135deg, #f6f8fa 0%, #e1e4e8 100%);
    border-left: 6px solid #586069;
    padding: 25px;
    margin: 25px 0;
    border-radius: 10px;
    color: #24292e;
    line-height: 1.7;
  }

  /* --- ESTILO DE IMÁGENES --- */
  .img-estilo {
    border-radius: 12px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    display: block;
    margin: 30px auto;
    max-width: 100%;
    height: auto;
  }

  /* --- GRID DE TARJETAS TÓXICAS --- */
  .grid-metales {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin: 30px 0;
  }
  .tarjeta-metal {
    background: #ffffff;
    border: 1px solid #d1d5da;
    padding: 20px;
    border-radius: 10px;
    border-top: 5px solid #586069;
    transition: all 0.3s ease;
  }
  .tarjeta-metal:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
  }
  .tarjeta-metal h3 { margin-top: 0; color: #444d56; }

  /* --- SECCIONES DE TEXTO --- */
  .seccion-contenido { margin-bottom: 50px; }
  .destacado-texto {
    background-color: #fff9db;
    padding: 15px;
    border-radius: 6px;
    border: 1px solid #ffe066;
    margin: 20px 0;
  }
</style>

<div markdown="1">

<div class="retraso-1" markdown="1">

# Residuos informáticos (E-Waste)

<div class="mini-indice">
  <h4>Navegación rápida:</h4>
  <ul>
    <li><a href="#que-es">1. Definición y Clasificación del E-Waste</a></li>
    <li><a href="#componentes">2. Componentes Críticos y Toxicidad</a></li>
    <li><a href="#impacto">3. El Viaje de la Basura: Impacto Global</a></li>
    <li><a href="#soluciones">4. Ciclo de Reciclaje y Soluciones</a></li>
  </ul>
</div>

<div id="que-es" class="seccion-contenido" markdown="1">

## 1. Definición y Clasificación del E-Waste

<div class="caja-gris">
  Se considera <strong>residuo electrónico o E-Waste</strong> a cualquier dispositivo que funcione con corriente eléctrica o baterías y que su dueño decide desechar. No solo hablamos de ordenadores; hoy en día, desde un cepillo de dientes eléctrico hasta un servidor de datos gigante entran en esta categoría.
</div>

El crecimiento de estos residuos es exponencial. Según el *Global E-waste Monitor*, generamos más de **62 millones de toneladas** al año, y lo peor es que esta cifra sube un 82% más rápido de lo que sube nuestra capacidad para reciclarlos.

Podemos clasificar los residuos informáticos en tres grandes grupos:
* **Equipos de informática y telecomunicaciones:** Servidores, portátiles, tablets y móviles.
* **Periféricos y accesorios:** Teclados, ratones, cables, cargadores y auriculares.
* **Electrónica de consumo:** Monitores, televisores y dispositivos inteligentes (IoT).



<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/E-waste_in_a_dumpster.jpg/800px-E-waste_in_a_dumpster.jpg" class="img-estilo" alt="Contenedor lleno de residuos electrónicos variados">

</div>

</div>

<div id="componentes" class="retraso-2 seccion-contenido" markdown="1">

## 2. Componentes Críticos y Toxicidad

Un ordenador moderno es una "joya química". Contiene metales preciosos como **oro, plata y paladio**, pero para que funcionen, también necesitan elementos que, fuera de su carcasa, son venenosos.

<div class="grid-metales" markdown="1">

<div class="tarjeta-metal" markdown="1">
### Plomo y Antimonio
Se encuentran principalmente en las soldaduras de las placas base y en los tubos de monitores antiguos. Son peligrosos para la sangre y el sistema reproductor.
</div>

<div class="tarjeta-metal" markdown="1">
### Mercurio y Arsénico
Presentes en interruptores, bombillas de retroiluminación de pantallas LCD y algunos procesadores. Son potentes neurotóxicos que contaminan el agua potable.
</div>

<div class="tarjeta-metal" markdown="1">
### Retardantes de llama
Plásticos tratados con bromo para que los cables no ardan. Al quemarse en vertederos, liberan dioxinas que se quedan en el aire y los pulmones.
</div>

</div>

</div>

<div id="impacto" class="retraso-3 seccion-contenido" markdown="1">

## 3. El Viaje de la Basura: Impacto Global

Uno de los mayores escándalos de los residuos informáticos es su **transporte ilegal**. Muchos países desarrollados envían contenedores de "equipos usados para donar" a países en desarrollo (como Ghana, Nigeria o India). En realidad, son basura tecnológica inservible.

<img src="giga.jpg" class="img-estilo" alt="Trabajadores en el vertedero de Agbogbloshie, Ghana">



En estos lugares, miles de personas (incluidos niños) trabajan quemando plásticos para recuperar el cobre de los cables, exponiéndose a enfermedades crónicas y destruyendo el suelo local de forma permanente.

</div>

<div id="soluciones" class="retraso-4 seccion-contenido" markdown="1">

## 4. Ciclo de Reciclaje y Soluciones

El reciclaje de un ordenador no es como el de un cartón. Sigue un proceso complejo:
1.  **Recogida:** Los usuarios llevan el equipo al **Punto Limpio**.
2.  **Descontaminación:** Se extraen manualmente las baterías, cartuchos de tinta y componentes con mercurio.
3.  **Trituración:** El resto se tritura en pequeñas piezas.
4.  **Separación electromagnética:** Mediante imanes y corrientes de aire, se separan los plásticos de los metales (hierro, aluminio, cobre y metales preciosos).



[Image of electronic waste recycling process flowchart]


<div class="destacado-texto">
  <strong>¿Qué podemos hacer nosotros?</strong> Lo más importante es alargar la vida útil del equipo. Si un PC va lento, podemos ampliar la RAM o poner un disco SSD en lugar de comprar uno nuevo. Si realmente ya no sirve, el 100% debe ir a una planta de tratamiento autorizada.
</div>

---

<div class="nav-botones">
  <a href="contaminacion.html" class="btn-nav volver">⬅️ Anterior: Contaminación</a>
  <a href="index.html" class="btn-nav volver">🏠 Inicio</a>
  <a href="obsolescencia.html" class="btn-nav siguiente">Siguiente: Obsolescencia ➡️</a>
</div>

</div>
</div>
