<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Libby Signor | Portfolio</title>
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css">
<style>
:root{--bg:#fafaf7;--fg:#1d2420;--mut:#5b665f;--acc:#500000;--card:#fff;--line:#dcdcd4}
@media(prefers-color-scheme:dark){:root{--bg:#161a17;--fg:#ecefe9;--mut:#a3aea6;--acc:#e8a0a0;--card:#1f2521;--line:#333c36}}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--fg);font:16px/1.6 Georgia,serif}
header,section,footer{max-width:760px;margin:0 auto;padding:28px 16px}
header{padding-top:48px;border-bottom:1px solid var(--line)}
h1{margin:0;font-size:2rem;line-height:1.2}
h2{font-size:1.3rem;color:var(--acc);margin:0 0 12px;border-bottom:1px solid var(--line);padding-bottom:6px}
p{margin:0 0 12px}
.mut{color:var(--mut)}
a{color:var(--acc)}
details{background:var(--card);border:1px solid var(--line);border-radius:8px;margin-bottom:10px}
summary{cursor:pointer;padding:14px 16px;font-weight:bold;list-style:none}
summary::after{content:"+";float:right}
details[open] summary::after{content:"\2212"}
summary small{display:block;font-weight:normal;color:var(--mut)}
.body{padding:0 16px 14px}
.body h3{font-size:.8rem;text-transform:uppercase;letter-spacing:.06em;color:var(--acc);margin:12px 0 2px}
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
  <h1>Elizabeth (Libby) Signor</h1>
  <p class="mut">Geographic Information Science and Technology student at Texas A&amp;M University with GIS internship experience in energy and real estate.</p>
</header>

<section id="about">
  <h2>About</h2>
  <p>I am completing a BS in Geographic Information Science and Technology at Texas A&amp;M University (December 2026 candidate, 3.65 major GPA). I transferred in as a junior from the College of Engineering to the Department of Geography.</p>
  <p>I have interned as a GIS analyst at Matador Resources Company (Summer 2026) and Republic Property Group (Summer 2025), working with ArcGIS Pro, Esri Field Maps and Python. Outside of GIS, my interests are fly fishing, literature, baking and travel.</p>
</section>

<section id="projects">
  <h2>Projects</h2>
  <p class="mut">Tap a card to open it.</p>

  <details>
    <summary>Communization agreement mapping<small>Matador Resources Company, Summer 2026</small></summary>
    <div class="body">
      <h3>The problem</h3>
      <p>Communization agreement data needed to be tied to the right network segments so accurate data could be published on a company-wide GIS platform.</p>
      <h3>What I did</h3>
      <p>I mapped communization agreement data and linked the agreement information to the corresponding network segments, so it could be published on the company-wide GIS platform. I also tested Esri Field Maps to improve field workflows and collaboration between the GIS and field operations teams.</p>
      <h3>What I found</h3>
      <p>[ADD]</p>
      <h3>What I would do differently</h3>
      <p>[ADD]</p>
    </div>
  </details>

  <details>
    <summary>AI-to-GIS Python bridge<small>Republic Property Group, Summer 2025</small></summary>
    <div class="body">
      <h3>The problem</h3>
      <p>Employees without GIS capabilities needed a way to use GIS software more efficiently.</p>
      <h3>What I did</h3>
      <p>I programmed a bridge between an AI-enabled application and GIS software using Python, and wrote an instruction manual so employees without GIS capabilities could use the system.</p>
      <h3>What I found</h3>
      <p>[ADD]</p>
      <h3>What I would do differently</h3>
      <p>[ADD]</p>
    </div>
  </details>

  <details>
    <summary>Animated map of DFW construction permits<small>Republic Property Group, Summer 2025</small></summary>
    <div class="body">
      <h3>The problem</h3>
      <p>[ADD]</p>
      <h3>What I did</h3>
      <p>I created an animated temporal map showing the growth of construction permits by geographic region within the DFW metro over the past 50 years.</p>
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
  <p>LinkedIn / GitHub: <a href="libbysignor">https://www.linkedin.com/in/libbysignor/</a></p>
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
