
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Informática Ecológica | Proyecto Medioambiental</title>
  <meta name="description" content="Sección profesional sobre Informática Ecológica para el proyecto informática-ambiental." />
  <style>
    :root{
      --bg:#f7faf7;
      --card:#ffffff;
      --text:#1f2937;
      --muted:#4b5563;
      --green:#0f766e;
      --green-2:#14b8a6;
      --line:#d1d5db;
      --shadow:0 10px 24px rgba(0,0,0,.08);
      --radius:14px;
    }

  *{box-sizing:border-box}
  body{
   margin:0;
  font-family:"Segoe UI",system-ui,-apple-system,sans-serif;
  background: radial-gradient(circle at top right, #d1fae5 0%, var(--bg) 35%);
  color:var(--text);
  line-height:1.65;
  }

   .container{max-width:1100px;margin:auto;padding:28px 20px 60px}
 .hero{
   background:linear-gradient(135deg,#0f766e,#115e59);
  color:#fff;
   padding:32px;
  border-radius:20px;
  box-shadow:var(--shadow);
  animation:fadeUp .8s ease both;
  }
  .hero h1{margin:0 0 10px;font-size:clamp(1.8rem,3vw,2.6rem)}
  .hero p{margin:0;opacity:.95}

  .toc,.card{
   background:var(--card);
   border:1px solid #e5e7eb;
   border-radius:var(--radius);
   padding:22px;
   margin-top:20px;
   box-shadow:var(--shadow);
  animation:fadeUp .8s ease both;
  }

.toc h2,.card h2{margin:0 0 12px;color:#0f766e}
.toc a{color:#0f766e;text-decoration:none}
.toc a:hover{text-decoration:underline}

.highlight{
   border-left:6px solid var(--green-2);
   background:#ecfeff;
   padding:14px 16px;
   border-radius:10px;
   color:#0f172a;
   margin:10px 0 18px;
   }

.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:16px;
  }

  .mini{
  border:1px solid var(--line);
  border-top:4px solid var(--green);
  border-radius:10px;
  padding:14px;
  background:#fff;
   }

   .images,
   .images-principios,
 .images-acciones{
   display:grid;
   grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
   gap:14px;
   margin-top:14px;
   }

   .images img{
   width:70%;
   height:auto;
   object-fit:cover;
   border-radius:12px;
   box-shadow:0 6px 14px rgba(0,0,0,.12);
   transition:transform .25s ease;
   margin: auto;
  }
    
  .images-acciones img{
  width:100%;
  height:250px;
  object-fit:cover;
  border-radius:12px;
  box-shadow:0 6px 14px rgba(0,0,0,.12);
  transition:transform .25s ease;
  }
    
 .images-principios img{
  width:100%;
  height:300px;
  object-fit:cover;
   border-radius:12px;
   box-shadow:0 6px 14px rgba(0,0,0,.12);
   transition:transform .25s ease;
   }
  .images img:hover,
  .images-principios img:hover,
  .images-acciones img:hover{transform:scale(1.02)}

blockquote{
  margin:16px 0;
  padding:12px 16px;
  border-left:4px solid #14b8a6;
  background:#f0fdfa;
  color:#134e4a;
  border-radius:8px;
  font-style:italic;
  }

.meta{color:var(--muted);font-size:.96rem}
.nav{
   margin-top:24px;
  display:flex;
  flex-wrap:wrap;
  gap:10px;
  }
  .btn{
  flex:1;
  min-width:180px;
  text-align:center;
  text-decoration:none;
  color:#fff;
  background:#0f766e;
  padding:12px 14px;
   border-radius:10px;
  font-weight:600;
   }
  .btn:hover{background:#115e59}
  .btn.alt{background:#6b7280}
  .btn.alt:hover{background:#4b5563}

  @keyframes fadeUp{
  from{opacity:0;transform:translateY(14px)}
  to{opacity:1;transform:translateY(0)}
  }
  </style>
</head>
<body>
  <div class="container">
    <div class="hero">
      <h1>Informática Ecológica (Green Computing)</h1>
      <p>Tecnología eficiente, responsable y sostenible para reducir el impacto ambiental digital.</p>
    </div>

  <div class="card" id="que-es">
      <h2>¿Qué es la informática ecológica?</h2>
      <div class="highlight">
        La informática ecológica reúne estrategias para diseñar, usar, mantener y reciclar tecnología con menor consumo energético, menos residuos y menor huella de carbono.<br>
        Lo que distingue a la tecnología ecológica de la convencional no es solo el producto final, sino el enfoque desde el que se diseña: ¿cuántos recursos consume? ¿cuánto dura? ¿qué pasa cuando llega al fin de su vida útil?
      </div>
      <div class="images">
        <img src="https://plus.unsplash.com/premium_photo-1728135850536-fd8c8a0eff59?q=80&w=1332&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Green Computing">
      </div>
    </div>

  <div class="card" id="principios">
      <h2>Principios clave</h2>
      <div class="grid">
        <div class="mini"><strong>Eficiencia energética:</strong> reducir el consumo en dispositivos y servidores.</div>
        <div class="mini"><strong>Economía circular:</strong> reparar, reutilizar y reacondicionar antes de desechar.</div>
        <div class="mini"><strong>Software optimizado:</strong> aplicaciones más ligeras y menos demandantes.</div>
        <div class="mini"><strong>Gestión RAEE:</strong> reciclaje seguro de residuos electrónicos.</div>
      </div>
      
  <div class="images-principios">
        <img src="https://images.unsplash.com/photo-1466611653911-95081537e5b7?q=80&w=1200&auto=format&fit=crop" alt="Energías renovables">
        <img src="https://images.unsplash.com/photo-1666804830091-56ba0e22becf?q=80&w=1170&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Economía circular">
      </div>
    </div>

  <div class="card" id="acciones">
      <h2>Acciones prácticas</h2>
      <ul>
        <li>Activar modos de ahorro y apagado automático en equipos.</li>
        <li>Comprar hardware reparable y con certificación energética.</li>
        <li>Usar servicios cloud con energía renovable.</li>
        <li>Crear planes de reciclaje y donación de equipos.</li>
      </ul>
      <div class="images-acciones">
        <img src="https://plus.unsplash.com/premium_photo-1681487942927-e1a2786e6036?q=80&w=1170&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Servicios Cloud">
        <img src="https://plus.unsplash.com/premium_photo-1681433419747-f5c114430ab5?q=80&w=1760&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Modo Ahorro">
      </div>
      
  <blockquote>“La tecnología más sostenible es la que dura más y consume menos.”</blockquote>
    </div>

<div class="card" id="impacto">
	<h2>Impacto positivo</h2>
	<p>
		Aplicar <strong>Green Computing</strong> genera beneficios ambientales, económicos y sociales. 
		En el plano ambiental, disminuye el consumo energético y las emisiones de CO₂ al optimizar
		equipos, software e infraestructura digital. Además, reduce la generación de residuos electrónicos
		al fomentar la reparación, reutilización y reciclaje responsable.
	</p>

<h3>Beneficios concretos</h3>
	<ul>
		<li><strong>Menor huella de carbono digital:</strong> reducción de emisiones asociadas al uso de TIC.</li>
		<li><strong>Ahorro energético real:</strong> equipos y centros de datos más eficientes.</li>
		<li><strong>Reducción de RAEE:</strong> menos desechos electrónicos y más recuperación de materiales.</li>
		<li><strong>Optimización de costes:</strong> menor consumo eléctrico y mayor durabilidad de dispositivos.</li>
		<li><strong>Mejora reputacional:</strong> cumplimiento de objetivos ambientales y responsabilidad social.</li>
	</ul>

  <h3>Indicadores sugeridos para medir el impacto</h3>
  <ul>
    <li>Consumo eléctrico mensual (kWh) antes y después de aplicar medidas.</li>
    <li>Emisiones estimadas de CO₂ equivalentes por año.</li>
    <li>Porcentaje de equipos reutilizados o reacondicionados.</li>
    <li>Cantidad de residuos electrónicos reciclados correctamente.</li>
    <li>Vida útil media de ordenadores y periféricos.</li>
  </ul>

  <p class="meta">
    <strong>Conclusión:</strong> la informática ecológica no solo protege el medioambiente; también mejora la eficiencia y la sostenibilidad a largo plazo de cualquier proyecto tecnológico.
  </p>
</div>

  <div class="card" id="referencias">
      <h2>Referencias</h2>
      <ol>
        <li><a href="https://evernex.com/es/blog-es/la-creciente-importancia-de-la-it-ecologica/" target="_blank" rel="noopener">Evernex</a></li>
        <li><a href="https://nexteducacion.com/noticias/tecnologia-verde-innovaciones-que-estan-salvando-el-planeta/" target="_blank" rel="noopener">NextEducacion</a></li>
        <li><a href="https://www.unep.org/" target="_blank" rel="noopener">UNEP - Global E-waste Monitor</a></li>
        <li><a href="https://www.energystar.gov/" target="_blank" rel="noopener">ENERGY STAR</a></li>
      </ol>
    </div>

  <div class="card" id="autores">
		
<h2>Autores</h2>
		<p>Juan Antonio Fernández</p>
    
  <div class="nav">
        <a class="btn alt" href="obsolescencia.html">⬅ Anterior</a>
        <a class="btn alt" href="index.html">🏠 Índice</a>
      </div>
    </div>
  </div>
</body>
</html>
