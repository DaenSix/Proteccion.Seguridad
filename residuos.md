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

  /* --- CAJA TEMÁTICA GRIS (Residuos = Hardware/Metales) --- */
  .caja-gris {
    background: linear-gradient(135deg, #f3f4f6 0%, #e5e7eb 100%);
    border-left: 6px solid #586069;
    padding: 20px;
    margin: 20px 0;
    border-radius: 8px;
    color: #24292e;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    font-size: 1.1em;
    line-height: 1.6;
  }

  /* --- ESTILO DE IMÁGENES --- */
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

  /* --- TARJETAS DE METALES TÓXICOS (GRID) --- */
  .grid-metales {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin: 25px 0;
  }
  .tarjeta-metal {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.03);
    border-top: 4px solid #586069;
    transition: transform 0.3s;
  }
  .tarjeta-metal:hover {
    transform: translateY(-3px);
    box-shadow: 0 6px 15px rgba(88, 96, 105, 0.15);
  }

  /* --- CITA DESTACADA --- */
  .cita-destacada {
    background-color: #fafbfc;
    border-left: 4px solid #d1d5da;
    padding: 15px 20px;
    font-style: italic;
    color: #586069;
    margin: 30px 0;
    font-size: 1.1em;
  }

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
    background-color: #586069;
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
    background-color: #444d56;
    transform: translateY(-2px);
    box-shadow: 0 4px 10px rgba(0,0,0,0.15);
  }
  .btn-nav.volver {
    background-color: #6a737d; /* Gris más claro para los botones de retroceso */
  }
  .btn-nav.volver:hover {
    background-color: #586069;
  }
  .btn-nav.siguiente {
    background-color: #d73a49; /* Color ROJO preparado para la sección de Obsolescencia de Álvaro */
  }
  .btn-nav.siguiente:hover {
    background-color: #cb2431;
  }
</style>

<div markdown="1">

<div class="retraso-1" markdown="1">

# Residuos informáticos (E-Waste)

<div class="caja-gris">
  Los <strong>residuos informáticos</strong>, conocidos internacionalmente como <em>E-Waste</em> (Electronic Waste), abarcan todos aquellos dispositivos electrónicos, ordenadores, teléfonos móviles, baterías y periféricos que han llegado al final de su vida útil y son desechados.
</div>

<img src="https://images.unsplash.com/photo-1550041526-70e2815152a5?q=80&w=800&auto=format&fit=crop" width="800" class="img-estilo" alt="Montaña de placas base y residuos electrónicos">

</div>

<div class="retraso-2" markdown="1">

## El Gran Problema: La Toxicidad Oculta

A diferencia de la basura común, los dispositivos tecnológicos están compuestos por una compleja mezcla de materiales. Aunque contienen elementos valiosos como oro, plata y cobre, también albergan **metales pesados altamente tóxicos**. 



Si estos residuos acaban en vertederos comunes y no se reciclan adecuadamente, los componentes se degradan y liberan toxinas al suelo y a las aguas subterráneas:

<div class="grid-metales" markdown="1">

<div class="tarjeta-metal" markdown="1">
### Plomo
Utilizado tradicionalmente en soldaduras y monitores antiguos. Su acumulación en el cuerpo humano daña gravemente el sistema nervioso central y los riñones.
</div>

<div class="tarjeta-metal" markdown="1">
### Mercurio
Presente en pantallas planas, interruptores y baterías. Es altamente volátil; contamina los ecosistemas acuáticos y afecta al desarrollo cerebral.
</div>

<div class="tarjeta-metal" markdown="1">
### Cadmio
Común en baterías recargables antiguas y semiconductores. Es un elemento cancerígeno y altamente tóxico para los pulmones.
</div>

</div>

</div>

<div class="retraso-3" markdown="1">

## Minería Urbana: La Solución Necesaria

Ante la avalancha de dispositivos desechados, surge el concepto de **Minería Urbana**. Este proceso consiste en recuperar los metales preciosos y materiales reutilizables directamente de los aparatos electrónicos desechados, en lugar de extraerlos de minas naturales.

<div class="cita-destacada">
  "Se estima que cada año se generan más de 50 millones de toneladas de residuos electrónicos a nivel mundial, pero apenas se recicla el 20% de forma documentada y segura."
</div>

Recuperar estos materiales no solo evita la contaminación por toxinas, sino que reduce la inmensa huella de carbono asociada a la extracción de nuevos recursos naturales. Sin embargo, para que se generen tantos residuos en tan poco tiempo, existe un factor impulsado por la industria que nos obliga a cambiar de dispositivos constantemente: **la obsolescencia programada**.

</div>

<div class="retraso-4" markdown="1">

---

<div class="nav-botones">
  <a href="contaminacion.html" class="btn-nav volver">⬅️ Anterior</a>
  <a href="index.html" class="btn-nav volver">🏠 Índice</a>
  <a href="obsolescencia.html" class="btn-nav siguiente">Siguiente: Obsolescencia ➡️</a>
</div>

</div>
</div>
