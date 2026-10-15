<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Libby Signor | Portfolio</title>
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css">
<style>
:root{--bg:#fafaf7;--fg:#1d2420;--mut:#5b665f;--acc:#500000;--card:#fff;--line:#dcdcd4;--navy:#14284b}
@media(prefers-color-scheme:dark){:root{--bg:#161a17;--fg:#ecefe9;--mut:#a3aea6;--acc:#e8a0a0;--card:#1f2521;--line:#333c36;--navy:#9db4e0}}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--fg);font:16px/1.6 Georgia,serif}
header,section,footer{max-width:760px;margin:0 auto;padding:28px 16px}
header{padding-top:48px;border-bottom:1px solid var(--line);display:flex;gap:16px;align-items:center}
.photo{width:84px;height:108px;border-radius:50%;object-fit:cover;flex:none;border:2px solid var(--line);display:flex;align-items:center;justify-content:center;font-size:.8rem;color:var(--mut)}
h1,h2,h3{color:var(--navy)}
h1{margin:0;font-size:2rem;line-height:1.2}
h2{font-size:1.3rem;margin:0 0 12px;border-bottom:1px solid var(--line);padding-bottom:6px}
p{margin:0 0 12px}
.mut{color:var(--mut)}
a{color:var(--acc)}
details{background:var(--card);border:1px solid var(--line);border-radius:8px;margin-bottom:10px}
summary{cursor:pointer;padding:14px 16px;font-weight:bold;list-style:none}
summary::after{content:"+";float:right}
details[open] summary::after{content:"\2212"}
summary small{display:block;font-weight:normal;color:var(--mut)}
.body{padding:0 16px 14px}
.body h3{font-size:.8rem;text-transform:uppercase;letter-spacing:.06em;margin:12px 0 2px}
.body p{margin:0}
#map{height:320px;border:1px solid var(--line);border-radius:8px}
.job{margin-bottom:14px}
.job b{display:block}
ul{margin:4px 0 0;padding-left:20px}
.chips span{display:inline-block;border:1px solid var(--line);border-radius:99px;padding:1px 10px;margin:0 6px 6px 0;font-size:.9rem}
</style>
</head>
<body>
<header>
  <img class="photo" src="data:image/jpeg;base64,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" alt="Headshot of Libby Signor">
  <div>
  <h1>Elizabeth (Libby) Signor</h1>
  <p class="mut">Geographic Information Science and Technology student at Texas A&amp;M University with GIS internship experience in energy and real estate.</p>
  </div>
</header>

<section id="about">
  <h2>About</h2>
  <p>I am completing a BS in Geographic Information Science and Technology at Texas A&amp;M University (December 2026 candidate, 3.65 major GPA). I transferred in as a junior from the College of Engineering to the Department of Geography.</p>
  <p>I have interned as the first GIS intern at Matador Resources Company (Summer 2026) and Republic Property Group (Summer 2025), working with ArcGIS Pro, Esri Field Maps and Python. Outside of GIS, my interests are fly fishing, literature, baking and travel.</p>
</section>

<section id="projects">
  <h2>Projects</h2>
  <p class="mut">Tap a card to open it.</p>

  <details>
    <summary>[ADD] School project 1 title<small>[ADD] course, term</small></summary>
    <div class="body">
      <h3>The problem</h3>
      <p>[ADD]</p>
      <h3>What I did</h3>
      <p>[ADD]</p>
      <h3>What I found</h3>
      <p>[ADD]</p>
      <h3>What I would do differently</h3>
      <p>[ADD]</p>
    </div>
  </details>

  <details>
    <summary>[ADD] School project 2 title<small>[ADD] course, term</small></summary>
    <div class="body">
      <h3>The problem</h3>
      <p>[ADD]</p>
      <h3>What I did</h3>
      <p>[ADD]</p>
      <h3>What I found</h3>
      <p>[ADD]</p>
      <h3>What I would do differently</h3>
      <p>[ADD]</p>
    </div>
  </details>

  <details>
    <summary>[ADD] School project 3 title<small>[ADD] course, term</small></summary>
    <div class="body">
      <h3>The problem</h3>
      <p>[ADD]</p>
      <h3>What I did</h3>
      <p>[ADD]</p>
      <h3>What I found</h3>
      <p>[ADD]</p>
      <h3>What I would do differently</h3>
      <p>[ADD]</p>
    </div>
  </details>
</section>

<section id="map">
  <h2>Map</h2>
  <p class="mut">No project map data was provided yet: [ADD]. Put each point in the <code>POINTS</code> list in the script below and it will appear here with a popup.</p>
  <div id="map" role="region" aria-label="Interactive project map"></div>
  <!-- ArcGIS Online map or StoryMap: none provided. [ADD] link, then use:
  <iframe src="[ADD]" width="100%" height="420" style="border:0" title="[ADD]" allowfullscreen></iframe> -->
</section>

<section id="resume">
  <h2>Resume</h2>

  <h3 style="margin:0 0 4px">Education</h3>
  <div class="job"><b>Texas A&amp;M University, College of Arts and Sciences, College Station, TX</b>
    BS, Geographic Information Science and Technology. December 2026 Candidate, 3.65 Major GPA. Junior transfer from College of Engineering to Department of Geography.</div>

  <h3 style="margin:16px 0 4px">Work Experience</h3>
  <div class="job"><b>GIS Intern, Matador Resources Company, Dallas, TX (Summer 2026)</b>
    <ul>
      <li>Mapped communization agreement data and linked agreement information to corresponding network segments, enabling publication of accurate, accessible data on a company-wide GIS platform.</li>
      <li>Tested and evaluated Esri Field Maps to improve field workflows and strengthen collaboration between GIS and field operations teams to gather real-time data and ensure data accuracy.</li>
      <li>Created and maintained custom GIS maps and spatial data products for multiple departments, supporting operational planning, asset management, and cross-functional decision-making.</li>
    </ul></div>
  <div class="job"><b>GIS Intern, Republic Property Group, Dallas, TX (Summer 2025)</b>
    <ul>
      <li>Designed marketing collateral and related site maps for a 116-unit build-to-rent community in the Denver MSA set to deliver in Aug. 2025.</li>
      <li>Programmed with Python a bridge between an AI-enabled application to GIS software and developed an instruction manual to enable employees without GIS capabilities to use the system more efficiently.</li>
      <li>Created an animated temporal map which displayed the growth of construction permits by geographic regions within the DFW metro over the past 50 years.</li>
    </ul></div>
  <div class="job"><b>Shift Lead, Guest Activity Services and Lifeguard, A Bar A Ranch, Encampment, WY (Summers 2023 and 2024)</b>
    <ul>
      <li>Managed the schedule for the youth program and created activities to fully utilize the 100k+ acre property.</li>
      <li>Led groups with 20-30 guests of varying ages through rigorous activities while challenging their potential.</li>
    </ul></div>

  <h3 style="margin:16px 0 4px">Leadership and Philanthropy</h3>
  <div class="job"><b>Sorority Member, Kappa Kappa Gamma - Epsilon Rho, College Station, TX (August 2022 – May 2026)</b>
    <ul>
      <li>Philanthropy Committee: planned and ran a philanthropic event that raised $40,000, allocated to the National Alliance on Mental Illness.</li>
      <li>Public Relations Committee: promoted sorority events and created merchandise for members, which raised money for the chapter.</li>
      <li>Organization Committee: organized 375 members into each committee and monitored their productivity and efficiency.</li>
      <li>Songfest: participated in the 2022, 2023, and 2024 philanthropic event.</li>
    </ul></div>

  <h3 style="margin:16px 0 6px">Skills</h3>
  <div class="chips"><span>Python</span><span>SQL</span><span>Java</span><span>ArcGIS Pro</span><span>QGIS</span><span>Customer Service</span><span>Teaching</span><span>Collaboration</span><span>Analytics</span></div>
</section>

<footer id="contact">
  <h2>Contact</h2>
  <p>Email: <a href="mailto:libbysignor@gmail.com">libbysignor@gmail.com</a></p>
  <p>LinkedIn: <a href="https://www.linkedin.com/in/libbysignor/" target="_blank" rel="noopener">libbysignor</a></p>
  <p>GitHub: <a href="https://github.com/libbysignor" target="_blank" rel="noopener">libbysignor</a></p>
</footer>

<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
<script>
// Map data lives here. [ADD] points as {name, lat, lng, note}, for example:
// {name:"[ADD]", lat:0, lng:0, note:"[ADD]"}
var POINTS = [];

(function () {
  var el = document.getElementById("map");
  if (!window.L) { el.innerHTML = "<p style='padding:16px'>Map library could not load.</p>"; return; }
  var map = L.map("map").setView([32.78, -96.8], 9); // Dallas, TX area (home city on resume)
  L.tileLayer("https://server.arcgisonline.com/ArcGIS/rest/services/World_Topo_Map/MapServer/tile/{z}/{y}/{x}", {
    attribution: "Tiles © Esri", maxZoom: 19
  }).addTo(map);
  var group = L.featureGroup();
  POINTS.forEach(function (p) {
    var m = L.marker([p.lat, p.lng]);
    var box = document.createElement("div");
    var b = document.createElement("b"); b.textContent = p.name;
    var t = document.createElement("div"); t.textContent = p.note || "";
    box.appendChild(b); box.appendChild(t);
    m.bindPopup(box).addTo(group);
  });
  group.addTo(map);
  if (POINTS.length) map.fitBounds(group.getBounds().pad(0.2));
})();
</script>
</body>
</html>
