

<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Archivo Histórico Hondureño: memoria, historia y documentación de Honduras.">
<title>Archivo Histórico Hondureño</title>

<style>
:root {
  --navy:#102638;
  --blue:#164b69;
  --gold:#d5a84c;
  --cream:#f4f0e7;
  --paper:#fffdf8;
  --ink:#26343c;
  --red:#9c3939;
}
* {box-sizing:border-box}
html {scroll-behavior:smooth}
body {
  margin:0;
  background:var(--cream);
  color:var(--ink);
  font-family:Georgia,serif;
  line-height:1.65;
}
header {
  background:var(--navy);
  color:white;
  padding:17px 5%;
  display:flex;
  justify-content:space-between;
  align-items:center;
  flex-wrap:wrap;
  gap:15px;
}
.brand {font:bold 14px Arial;letter-spacing:1px}
nav {display:flex;flex-wrap:wrap;gap:15px}
nav a {
  color:white;
  text-decoration:none;
  font:13px Arial;
}
nav a:hover {color:var(--gold)}
.hero {
  min-height:480px;
  padding:75px 7%;
  display:flex;
  flex-direction:column;
  align-items:center;
  justify-content:center;
  text-align:center;
  color:white;
  background:linear-gradient(130deg,#091b29,#164b69);
}
.eyebrow {
  color:var(--gold);
  letter-spacing:4px;
  font:12px Arial;
}
.hero h1 {
  font-size:clamp(38px,7vw,68px);
  line-height:1.08;
  max-width:900px;
}
.hero p {max-width:700px;font-size:18px;color:#e1e9ed}
.motto {
  max-width:780px;
  margin-top:25px;
  padding-top:20px;
  border-top:1px solid #ffffff55;
  color:#f1d18a;
  font-size:17px;
  font-style:italic;
}
.button {
  display:inline-block;
  background:var(--gold);
  color:#172b38;
  padding:12px 22px;
  margin-top:20px;
  text-decoration:none;
  font:bold 13px Arial;
  border-radius:3px;
}
main {max-width:1100px;margin:auto;padding:0 22px}
section {padding:60px 0}
.section-label {
  color:var(--red);
  text-transform:uppercase;
  letter-spacing:2px;
  font:bold 11px Arial;
}
h2 {color:var(--navy);font-size:clamp(28px,4vw,40px);line-height:1.2}
.intro {font-size:18px;max-width:780px}
.note {
  padding:17px;
  background:#f9eecf;
  border-left:4px solid var(--gold);
}
.cards {
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
  gap:17px;
  margin-top:25px;
}
.card {
  background:var(--paper);
  border:1px solid #e5dfd2;
  padding:21px;
  border-radius:4px;
}
.card h3 {color:var(--navy)}
.card p {font-size:14px}
.tag {
  color:var(--red);
  font:bold 10px Arial;
  letter-spacing:1px;
}
.dark {
  background:var(--navy);
  color:white;
  margin:0 -22px;
  padding:55px max(22px,calc((100% - 1056px)/2));
}
.dark h2 {color:white}
.dark .section-label {color:var(--gold)}
.searchbar {display:flex;gap:10px;margin:25px 0;flex-wrap:wrap}
.searchbar input,.searchbar select {
  padding:13px;
  border:1px solid #ccc;
  background:white;
  border-radius:3px;
  font-size:14px;
}
.searchbar input {flex:1;min-width:200px}
.timeline {
  border-left:2px solid var(--gold);
  margin-left:10px;
  padding-left:25px;
}
.event {
  background:var(--paper);
  border:1px solid #e5dfd2;
  padding:20px;
  margin-bottom:25px;
  position:relative;
}
.event:before {
  content:"";
  position:absolute;
  left:-33px;
  top:23px;
  width:12px;
  height:12px;
  background:var(--gold);
  border-radius:50%;
}
.event h3 {color:var(--navy)}
.date {font:bold 11px Arial;color:var(--red)}
.source {color:var(--blue);font:bold 12px Arial}
.gallery {
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(210px,1fr));
  gap:15px;
}
.gallery-item {
  min-height:175px;
  padding:18px;
  display:flex;
  flex-direction:column;
  justify-content:end;
  color:white;
  background:linear-gradient(145deg,#31576b,#102638);
}
.gallery-item:nth-child(2) {background:linear-gradient(145deg,#75634b,#302c29)}
.gallery-item:nth-child(3) {background:linear-gradient(145deg,#526b61,#1e3430)}
.gallery-item:nth-child(4) {background:linear-gradient(145deg,#765252,#35282b)}
.gallery-item small {color:#f1d18a}
.gallery-item strong {font-size:19px}
.sources li {margin:13px 0}
.sources a {color:var(--blue)}
.small {font-size:12px;color:#687780}
.hidden {display:none}
footer {
  background:#091b28;
  color:#dce4e8;
  text-align:center;
  padding:40px 20px;
  font-size:13px;
}
footer strong {color:var(--gold)}
@media(max-width:600px) {
  header {justify-content:center}
  nav {justify-content:center}
  .hero {padding:60px 20px}
}
</style>
</head>

<body>

<header>
  <div class="brand">🇭🇳 ARCHIVO HISTÓRICO HONDUREÑO</div>
  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#cronologia">Cronología</a>
    <a href="#temas">Temas</a>
    <a href="#galeria">Galería</a>
    <a href="#fuentes">Fuentes</a>
  </nav>
</header>

<div class="hero" id="inicio">
  <div class="eyebrow">MEMORIA DOCUMENTAL DE UNA NACIÓN</div>
  <h1>ARCHIVO HISTÓRICO HONDUREÑO</h1>
  <p>
    Un espacio independiente para documentar los acontecimientos
    que han marcado Honduras, conservar la memoria de las víctimas
    y conocer nuestra historia.
  </p>
  <div class="motto">
    QUE CAMBIEN LOS GOBIERNOS CAÓTICOS.
    LOS ERRORES NO LOS CAMBIAREMOS EN LA HISTORIA,
    PERO SÍ EN EL FUTURO.
  </div>
  <a class="button" href="#cronologia">EXPLORAR EL ARCHIVO</a>
</div>

<main>

<section id="presentacion">
  <div class="section-label">Nuestra razón de existir</div>
  <h2>La memoria también es justicia</h2>
  <p class="intro">
    Honduras ha atravesado crisis políticas, conflictos sociales,
    protestas, denuncias de corrupción, violencia y luchas por los
    derechos humanos. Este archivo busca reunir documentación
    para que los acontecimientos puedan conocerse y comprenderse.
  </p>
  <div class="note">
    <strong>Nuestro compromiso:</strong> no favorecer ni proteger
    a ningún partido, gobierno o figura política. Diferenciar
    hechos comprobados, denuncias, testimonios e investigaciones
    pendientes. No atribuir culpabilidad sin pruebas.
  </div>
</section>

<section id="cronologia">
  <div class="section-label">Línea del tiempo</div>
  <h2>Acontecimientos que debemos recordar</h2>
  <p>Una cronología inicial que crecerá con documentación y fuentes verificadas.</p>

  <div class="searchbar">
    <input id="search" type="search" placeholder="Buscar acontecimiento o año...">
    <select id="filter">
      <option value="todos">Todos los temas</option>
      <option value="politica">Política</option>
      <option value="derechos">Derechos humanos</option>
      <option value="protestas">Protestas</option>
      <option value="justicia">Justicia</option>
    </select>
  </div>

  <div class="timeline" id="timeline">

    <article class="event" data-category="politica">
      <span class="date">28 DE JUNIO DE 2009 · POLÍTICA</span>
      <h3>La crisis política y el golpe de Estado</h3>
      <p>
        Honduras atravesó una ruptura del orden constitucional
        tras la salida forzada del presidente Manuel Zelaya.
        El acontecimiento abrió un período de profunda crisis
        política y social.
      </p>
      <a class="source" href="https://www.oas.org/es/cidh/" target="_blank" rel="noopener">
        Consultar documentación de la CIDH →
      </a>
    </article>

    <article class="event" data-category="derechos">
      <span class="date">2 DE MARZO DE 2016 · DERECHOS HUMANOS</span>
      <h3>Asesinato de Berta Cáceres</h3>
      <p>
        La defensora indígena y ambientalista Berta Cáceres fue
        asesinada. Su caso se convirtió en un referente internacional
        de la lucha por la protección de quienes defienden los
        territorios y los derechos humanos.
      </p>
      <a class="source" href="https://www.globalwitness.org/" target="_blank" rel="noopener">
        Consultar investigaciones de Global Witness →
      </a>
    </article>

    <article class="event" data-category="protestas">
      <span class="date">2017 · PROTESTAS Y CRISIS ELECTORAL</span>
      <h3>Protestas después de las elecciones</h3>
      <p>
        El proceso electoral de 2017 estuvo acompañado de una crisis
        política, manifestaciones y denuncias de violaciones de
        derechos humanos. Se incorporarán informes y registros
        individuales de víctimas.
      </p>
      <a class="source" href="https://www.ohchr.org/es/countries/honduras" target="_blank" rel="noopener">
        Consultar informes de Naciones Unidas →
      </a>
    </article>

    <article class="event" data-category="protestas">
      <span class="date">2019 · PROTESTAS SOCIALES</span>
      <h3>Movilizaciones y denuncias de represión</h3>
      <p>
        Diversas manifestaciones sociales y protestas tuvieron lugar
        durante 2019. El archivo documentará los acontecimientos,
        las personas afectadas y las investigaciones disponibles.
      </p>
      <a class="source" href="https://www.ohchr.org/es/countries/honduras" target="_blank" rel="noopener">
        Consultar documentación de Naciones Unidas →
      </a>
    </article>

    <article class="event" data-category="politica">
      <span class="date">2021–2022 · TRANSICIÓN POLÍTICA</span>
      <h3>Elecciones y cambio de gobierno</h3>
      <p>
        Las elecciones generales de 2021 marcaron una nueva etapa
        política en Honduras. El archivo recogerá resultados,
        antecedentes y acontecimientos relacionados con la transición.
      </p>
      <a class="source" href="https://www.oas.org/es/" target="_blank" rel="noopener">
        Consultar documentación de la OEA →
      </a>
    </article>

  </div>
  <p class="small">
    Esta cronología es introductoria y no constituye una lista completa
    de víctimas, protestas o acontecimientos.
  </p>
</section>

<div class="dark" id="temas">
  <div class="section-label">Secciones del archivo</div>
  <h2>Una historia que merece ser documentada</h2>
  <div class="cards">

    <article class="card">
      <span class="tag">SECCIÓN 01</span>
      <h3>Víctimas de protestas</h3>
      <p>Registro de personas fallecidas o heridas durante manifestaciones, con fechas, lugares y fuentes.</p>
    </article>

    <article class="card">
      <span class="tag">SECCIÓN 02</span>
      <h3>Defensores de derechos humanos</h3>
      <p>Historias y documentación de personas que defendieron comunidades, territorios y derechos fundamentales.</p>
    </article>

    <article class="card">
      <span class="tag">SECCIÓN 03</span>
      <h3>Casos emblemáticos</h3>
      <p>Casos que marcaron la memoria nacional, sus investigaciones y el estado conocido de sus procesos.</p>
    </article>

    <article class="card">
      <span class="tag">SECCIÓN 04</span>
      <h3>Corrupción y poder</h3>
      <p>Investigaciones, auditorías, procesos judiciales y denuncias atribuidas a sus fuentes originales.</p>
    </article>

    <article class="card">
      <span class="tag">SECCIÓN 05</span>
      <h3>Desapariciones y homicidios</h3>
      <p>Expedientes documentales con información verificable y respeto a las víctimas y sus familias.</p>
    </article>

    <article class="card">
      <span class="tag">SECCIÓN 06</span>
      <h3>Memoria de las comunidades</h3>
      <p>Testimonios y acontecimientos locales de distintas regiones de Honduras.</p>
    </article>

  </div>
</div>

<section id="pendientes">
  <div class="section-label">Investigación en desarrollo</div>
  <h2>Casos que debemos verificar</h2>
  <p>
    Las referencias aportadas por ciudadanos también merecen
    investigación. Antes de publicar nombres y circunstancias,
    necesitamos confirmar los datos con fuentes independientes.
  </p>

  <div class="cards">
    <article class="card">
      <span class="tag">PENDIENTE DE IDENTIFICACIÓN</span>
      <h3>Caso de una muerte en Sabá, Colón</h3>
      <p>
        Se necesita confirmar identidad, fecha, circunstancias
        y documentación independiente.
      </p>
    </article>

    <article class="card">
      <span class="tag">PENDIENTE DE IDENTIFICACIÓN</span>
      <h3>Estudiante que protestó contra JOH</h3>
      <p>
        Referencia a una estudiante que habría sido asesinada
        días después de participar en una protesta. Debemos
        confirmar identidad, cronología y fuentes.
      </p>
    </article>
  </div>
  <p class="small">
    La inclusión de una referencia no implica una conclusión
    sobre responsables ni circunstancias.
  </p>
</section>

<section id="galeria">
  <div class="section-label">Memoria visual</div>
  <h2>Galería documental</h2>
  <p>
    Las fotografías se incorporarán con fuente, fecha, lugar,
    descripción y condiciones de uso. No se presentarán imágenes
    sin confirmar su contexto.
  </p>

  <div class="gallery">
    <div class="gallery-item">
      <small>GALERÍA 01</small>
      <strong>Memoria de 2009</strong>
      <span>Fotografías por incorporar</span>
    </div>
    <div class="gallery-item">
      <small>GALERÍA 02</small>
      <strong>Protestas sociales</strong>
      <span>Fotografías por incorporar</span>
    </div>
    <div class="gallery-item">
      <small>GALERÍA 03</small>
      <strong>Defensa del territorio</strong>
      <span>Fotografías por incorporar</span>
    </div>
    <div class="gallery-item">
      <small>GALERÍA 04</small>
      <strong>Corrupción y poder</strong>
      <span>Documentos e imágenes por incorporar</span>
    </div>
  </div>
  <p class="small">
    Estas tarjetas son espacios de organización, no fotografías históricas.
  </p>
</section>

<section id="metodologia">
  <div class="section-label">Nuestro compromiso</div>
  <h2>La verdad exige responsabilidad</h2>
  <div class="cards">
    <article class="card">
      <h3>Verificación</h3>
      <p>Contrastamos información con documentos, informes y fuentes independientes.</p>
    </article>
    <article class="card">
      <h3>Contexto</h3>
      <p>Explicamos cuándo y dónde ocurrió cada hecho y qué se conoce de su desarrollo.</p>
    </article>
    <article class="card">
      <h3>Transparencia</h3>
      <p>Diferenciamos hechos comprobados, denuncias, testimonios y asuntos pendientes.</p>
    </article>
  </div>
</section>

<section id="fuentes">
  <div class="section-label">Consulta documental</div>
  <h2>Fuentes de referencia</h2>
  <p>
    Estos organismos ofrecen materiales que pueden ayudar a
    documentar los acontecimientos. Cada expediente deberá
    incorporar referencias específicas.
  </p>
  <ul class="sources">
    <li><a href="https://www.ohchr.org/es/countries/honduras" target="_blank" rel="noopener">Naciones Unidas – Derechos Humanos en Honduras</a></li>
    <li><a href="https://www.oas.org/es/cidh/" target="_blank" rel="noopener">Comisión Interamericana de Derechos Humanos</a></li>
    <li><a href="https://www.oas.org/es/" target="_blank" rel="noopener">Organización de los Estados Americanos</a></li>
    <li><a href="https://www.cofadeh.org/" target="_blank" rel="noopener">COFADEH</a></li>
    <li><a href="https://www.globalwitness.org/" target="_blank" rel="noopener">Global Witness</a></li>
  </ul>
</section>

<section>
  <div class="note">
    <strong>Recordar para comprender. Comprender para no repetir.</strong>
    <br>
    El pasado es imborrable, pero el futuro todavía está en nuestras manos.
  </div>
</section>

</main>

<footer>
  <strong>ARCHIVO HISTÓRICO HONDUREÑO</strong>
  <p>Memoria, documentación y reflexión para las futuras generaciones.</p>
  <p>Un proyecto documental independiente. La historia pertenece al pueblo.</p>
  <p>© 2026 · Archivo Histórico Hondureño</p>
</footer>

<script>
const search = document.getElementById("search");
const filter = document.getElementById("filter");
const events = document.querySelectorAll(".event");

function filterEvents() {
  const term = search.value.toLowerCase().trim();
  const category = filter.value;

  events.forEach(event => {
    const matchesText = event.innerText.toLowerCase().includes(term);
    const matchesCategory =
      category === "todos" ||
      event.dataset.category === category;

    event.classList.toggle(
      "hidden",
      !(matchesText && matchesCategory)
    );
  });
}

search.addEventListener("input", filterEvents);
filter.addEventListener("change", filterEvents);
</script>

</body>
</html>
