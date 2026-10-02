<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Guppy Gene & Breeding Simulator Pro</title>
<style>
:root {
  --bg-grad: linear-gradient(135deg,#0d1b2a,#1b263b,#415a77);
  --text-color: #e0e1dd;
  --panel-bg: rgba(27, 38, 59, 0.75);
  --info-bg: rgba(13, 27, 42, 0.6);
  --fishbox-bg: radial-gradient(circle, #1e3a4c 0%, #0b1924 100%);
  --select-bg: #0d1b2a;
}
[data-theme="light"] {
  --bg-grad: linear-gradient(135deg,#e0f2fe,#bae6fd,#7dd3fc);
  --text-color: #0f172a;
  --panel-bg: rgba(255, 255, 255, 0.85);
  --info-bg: rgba(241, 245, 249, 0.9);
  --fishbox-bg: radial-gradient(circle, #f8fafc 0%, #cbd5e1 100%);
  --select-bg: #ffffff;
}
*{box-sizing:border-box}
body{margin:0;font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;background:var(--bg-grad);color:var(--text-color);min-height:100vh;transition:all 0.3s}
header{padding:14px 20px;background:rgba(13, 27, 42, 0.85);backdrop-filter:blur(10px);border-bottom:1px solid rgba(255,255,255,0.1);position:sticky;top:0;z-index:100}
.header-top{display:flex;justify-content:space-between;align-items:center;max-width:1200px;margin:0 auto;flex-wrap:wrap;gap:10px}
header h1{margin:0;color:#00f5d4;font-size:20px;letter-spacing:0.5px}
header p{margin:0;color:#94a3b8;font-size:11px}
.controls-top{display:flex;gap:8px;align-items:center;flex-wrap:wrap}
.nav-tabs{display:flex;gap:6px}
.lang-switch,.theme-switch{display:flex;gap:4px}
.switch-btn{background:rgba(255,255,255,0.1);border:1px solid rgba(255,255,255,0.2);color:#fff;padding:5px 10px;border-radius:6px;cursor:pointer;font-size:11px;transition:all 0.2s}
.switch-btn.active,.switch-btn:hover{background:#00f5d4;color:#0d1b2a;font-weight:bold}
.tab-btn{background:rgba(0,245,212,0.15);border:1px solid #00f5d4;color:#00f5d4;padding:6px 12px;border-radius:6px;cursor:pointer;font-size:12px;font-weight:bold;transition:all 0.2s}
.tab-btn.active{background:#00f5d4;color:#0d1b2a}

main{max-width:1200px;margin:auto;padding:20px}
.view-section{display:none}
.view-section.active{display:block}

/* MORPHOLOGY LAYOUT */
.layout{display:grid;grid-template-columns:350px 1fr;gap:22px}
.panel,.preview{background:var(--panel-bg);backdrop-filter:blur(12px);border:1px solid rgba(255,255,255,0.08);border-radius:20px;padding:20px;box-shadow:0 8px 32px rgba(0,0,0,0.2)}
.panel{max-height:82vh;overflow-y:auto}
.panel::-webkit-scrollbar{width:6px}
.panel::-webkit-scrollbar-thumb{background:rgba(255,255,255,0.2);border-radius:3px}
.btn-group{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:12px}
.action-btn{padding:9px;border:none;border-radius:10px;font-weight:bold;cursor:pointer;font-size:12px;transition:all 0.2s}
.btn-random{background:#00f5d4;color:#0d1b2a}
.btn-random:hover{background:#03dac6}
.btn-champion{background:#ffd166;color:#0d1b2a}
.btn-champion:hover{background:#ffc107}
label{display:block;font-weight:600;margin:9px 0 3px;font-size:12px;color:#00f5d4}
select{width:100%;padding:9px 10px;border:1px solid rgba(255,255,255,0.15);border-radius:10px;background:var(--select-bg);color:var(--text-color);font-size:13px;outline:none;transition:all 0.3s}
select:focus{border-color:#00f5d4;box-shadow:0 0 0 3px rgba(0,245,212,0.2)}
.preview{display:flex;flex-direction:column;align-items:center}
.preview h2{margin-top:0;font-size:18px;color:#00f5d4}
.fishbox{width:100%;min-height:360px;display:flex;align-items:center;justify-content:center;background:var(--fishbox-bg);border-radius:16px;overflow:hidden;border:1px solid rgba(255,255,255,0.05);position:relative;transition:all 0.3s}
svg{width:min(740px,100%);height:auto}
.info{width:100%;margin-top:14px;padding:14px;border-radius:12px;background:var(--info-bg);border:1px solid rgba(255,255,255,0.05)}
.info-title{font-weight:bold;color:#00f5d4;margin-bottom:6px;font-size:13px}
.strain-name{font-size:16px;font-weight:bold;color:#ffd166;margin-bottom:8px;background:rgba(255,209,102,0.1);padding:7px 10px;border-radius:8px;border-left:4px solid #ffd166}
.chips{display:flex;gap:5px;flex-wrap:wrap}
.chip{background:rgba(0,245,212,0.15);color:#00f5d4;padding:4px 8px;border-radius:999px;font-size:10px;border:1px solid rgba(0,245,212,0.3)}

/* BREEDING SIMULATOR STYLES */
.breeding-top-actions{display:flex;justify-content:center;gap:12px;margin-bottom:20px}
.breeding-grid{display:grid;grid-template-columns:1fr auto 1fr;gap:20px;align-items:start}
.parent-box{background:var(--panel-bg);padding:20px;border-radius:16px;border:1px solid rgba(255,255,255,0.08);box-shadow:0 8px 32px rgba(0,0,0,0.2)}
.parent-box h3{margin-top:0;color:#ffd166;font-size:16px;border-bottom:1px solid rgba(255,255,255,0.1);padding-bottom:8px}
.breeding-center{display:flex;flex-direction:column;align-items:center;justify-content:center;gap:15px;align-self:center}
.cross-btn{background:#00f5d4;color:#0d1b2a;border:none;padding:12px 24px;border-radius:12px;font-weight:bold;cursor:pointer;font-size:14px;box-shadow:0 4px 15px rgba(0,245,212,0.3);transition:all 0.2s}
.cross-btn:hover{background:#03dac6;transform:scale(1.05)}
.result-box{background:var(--panel-bg);padding:20px;border-radius:16px;border:1px solid rgba(255,255,255,0.08);margin-top:20px;box-shadow:0 8px 32px rgba(0,0,0,0.2)}
.result-box h3{color:#00f5d4;margin-top:0;font-size:16px}
.result-table{width:100%;border-collapse:collapse;margin-top:10px;font-size:13px}
.result-table th,.result-table td{padding:8px 12px;text-align:left;border-bottom:1px solid rgba(255,255,255,0.1)}
.result-table th{color:#00f5d4;font-weight:600}
.fry-input-group{display:flex;align-items:center;gap:10px;margin-bottom:15px;font-size:14px;font-weight:bold}
.fry-input-group input{width:70px;padding:6px;background:var(--select-bg);border:1px solid rgba(255,255,255,0.2);color:var(--text-color);border-radius:8px;text-align:center;font-weight:bold}

@media(max-width:850px){.layout,.breeding-grid{grid-template-columns:1fr}.breeding-center{margin:10px 0}}
</style>
</head>
<body data-theme="dark">
<header>
  <div class="header-top">
    <div>
      <h1 id="uiTitle">🐟 Guppy Gene Simulator Pro</h1>
      <p id="uiSub">Simulasi morfologi & prediksi strain guppy</p>
    </div>
    <div class="controls-top">
      <div class="nav-tabs">
        <button class="tab-btn active" onclick="switchView('morphology')" id="tabMorph">🧬 Morfologi</button>
        <button class="tab-btn" onclick="switchView('breeding')" id="tabBreed">🧪 Breeding Simulator</button>
      </div>
      <div class="theme-switch">
        <button class="switch-btn active" onclick="setTheme('dark')" id="btnDark">🌙</button>
        <button class="switch-btn" onclick="setTheme('light')" id="btnLight">☀️</button>
      </div>
      <div class="lang-switch">
        <button class="switch-btn active" onclick="setLang('id')">ID</button>
        <button class="switch-btn" onclick="setLang('en')">EN</button>
      </div>
    </div>
  </div>
</header>

<main>
  <!-- VIEW 1: MORPHOLOGY -->
  <section id="viewMorphology" class="view-section active">
    <div class="layout">
      <div class="panel">
        <div class="btn-group">
          <button class="action-btn btn-random" onclick="randomizeGene()" id="btnRand">🎲 Acak Gen</button>
          <button class="action-btn btn-champion" onclick="setChampion()" id="btnChamp">🏆 Gen Juara</button>
        </div>
        
        <h2 id="uiControlTitle" style="font-size:15px;margin-bottom:10px;">🧬 Kontrol Genetik</h2>
        
        <label id="lblBody">Bentuk Tubuh</label>
        <select id="body">
          <option value="Standard">Standard</option>
          <option value="Short Body">Short Body (Compact)</option>
          <option value="Large Body">Large Body (King/Giant)</option>
        </select>

        <label id="lblColor">Warna Dasar</label>
        <select id="color">
          <option value="#e53935">Red (Merah)</option>
          <option value="#1976d2">Blue (Biru)</option>
          <option value="#fbc02d">Yellow (Kuning)</option>
          <option value="#fb8c00">Orange (Jingga)</option>
          <option value="#20252b">Black (Hitam)</option>
          <option value="#f8fafc">White (Putih)</option>
          <option value="#d8b52b">Gold (Emas)</option>
          <option value="#36a269">Green (Hijau)</option>
          <option value="#8e44ad">Purple (Ungu)</option>
          <option value="#e9a4bd">Pink (Merah Muda)</option>
          <option value="#aebbc4">Silver (Perak)</option>
          <option value="#dfe8ed">Platinum (Platinum)</option>
          <option value="#6c8794">Metallic (Metalik)</option>
        </select>

        <label id="lblPattern">Pola Tubuh & Ekor</label>
        <select id="pattern">
          <option value="Solid">Solid</option>
          <option value="Mosaic">Mosaic</option>
          <option value="Grass">Grass</option>
          <option value="Cobra / Snakeskin">Cobra / Snakeskin</option>
          <option value="Leopard">Leopard</option>
          <option value="Tuxedo">Tuxedo</option>
          <option value="Half Black">Half Black</option>
          <option value="Lace">Lace</option>
          <option value="Spotted">Spotted</option>
        </select>

        <label id="lblTail">Bentuk Ekor</label>
        <select id="tail">
          <option value="Delta">Delta</option>
          <option value="Halfmoon">Halfmoon</option>
          <option value="Fantail">Fantail</option>
          <option value="Veiltail">Veiltail</option>
          <option value="Round">Round</option>
          <option value="Spade">Spade</option>
          <option value="Top Sword">Top Sword</option>
          <option value="Bottom Sword">Bottom Sword</option>
          <option value="Double Sword">Double Sword</option>
          <option value="Lyretail">Lyretail</option>
          <option value="Pin / Needle">Pin / Needle</option>
          <option value="Flag">Flag</option>
        </select>

        <label id="lblFin">Bentuk Sirip</label>
        <select id="fin">
          <option value="Standard">Standard</option>
          <option value="Dumbo / Elephant Ear">Dumbo / Elephant Ear</option>
          <option value="Ribbon">Ribbon</option>
          <option value="Swallow">Swallow</option>
          <option value="Long-fin">Long-fin</option>
        </select>

        <label id="lblEye">Mata</label>
        <select id="eye">
          <option value="Normal">Normal</option>
          <option value="Albino / RREA">Albino / RREA</option>
          <option value="Red Eye">Red Eye</option>
        </select>

        <label id="lblSex">Kelamin</label>
        <select id="sex">
          <option value="Male">Jantan (Male)</option>
          <option value="Female">Betina (Female)</option>
        </select>

        <label id="lblPigment">Pigmentasi Tubuh</label>
        <select id="pigment">
          <option value="None">None (Polos)</option>
          <option value="Moscow">Moscow</option>
          <option value="Japan Blue">Japan Blue</option>
          <option value="Dragon">Dragon</option>
          <option value="Koi">Koi</option>
          <option value="Platinum">Platinum</option>
          <option value="Metallic">Metallic</option>
        </select>
      </div>

      <div class="preview">
        <h2 id="uiVisualTitle">🎨 Visualisasi Fenotipe</h2>
        <div class="fishbox">
          <svg viewBox="0 0 800 430" id="fish" aria-label="Ilustrasi Guppy">
            <defs>
              <clipPath id="bodyClip">
                <path d="M242 153 C330 137 420 152 485 186 C510 199 524 207 535 215 C524 223 510 231 485 244 C420 278 330 293 242 277 Z"/>
              </clipPath>
              <clipPath id="tailClip">
                <path id="tailClipPath" d="M525 215 C565 170 630 100 750 90 C785 85 795 110 780 145 C755 195 685 210 615 215 C685 220 755 235 780 285 C795 320 785 345 750 340 C630 330 565 260 525 215 Z"/>
              </clipPath>
              <linearGradient id="bodyBase" x1="0" x2="1">
                <stop offset="0%" stop-color="#b0bec5"/>
                <stop offset="60%" stop-color="currentColor"/>
                <stop offset="100%" stop-color="currentColor"/>
              </linearGradient>
              <filter id="shadow"><feDropShadow dx="0" dy="6" stdDeviation="6" flood-opacity=".3"/></filter>
            </defs>

            <g id="fishMainGroup" filter="url(#shadow)">
              <g id="tailGroup">
                <path id="tailShape" d="" fill="currentColor" opacity=".9"/>
                <g id="tailPatternLayer" clip-path="url(#tailClip)"></g>
              </g>

              <path d="M480 182 C505 190 520 202 535 215 C520 228 505 240 480 248 Z" fill="currentColor" opacity=".92"/>

              <path id="bodyShape"
                    d="M150 215 C150 168 185 142 245 140 C330 137 420 152 485 186 C510 199 524 207 535 215 C524 223 510 231 485 244 C420 278 330 293 245 290 C185 288 150 262 150 215 Z"
                    fill="url(#bodyBase)" stroke="#1a252c" stroke-width="3.5"/>

              <path d="M150 215 C150 174 172 148 208 145 C232 143 248 158 254 180 C258 200 258 230 254 250 C248 272 232 287 208 285 C172 282 150 256 150 215 Z"
                    fill="#94a3b8" stroke="#1a252c" stroke-width="3.5"/>

              <path d="M232 160 Q242 215 232 270" fill="none" stroke="#1a252c" stroke-width="2.5" stroke-linecap="round" opacity=".6"/>

              <g clip-path="url(#bodyClip)">
                <g id="pigmentOverlay"></g>
                <g id="patternLayer"></g>
              </g>

              <path id="dorsal" d="M300 148 C335 92 410 88 450 142 C415 132 360 132 300 148 Z" fill="currentColor" opacity=".82" transform="rotate(-30 310 145)"/>
              <path id="analFin" d="M330 282 C355 324 408 322 438 268 C405 282 365 288 330 282 Z" fill="currentColor" opacity=".78" transform="rotate(30 350 282)"/>

              <ellipse id="pectoral1" cx="295" cy="235" rx="42" ry="15" fill="currentColor" opacity=".6" transform="rotate(22 295 235)"/>
              <ellipse id="pectoral2" cx="295" cy="195" rx="42" ry="15" fill="currentColor" opacity=".6" transform="rotate(-22 295 195)"/>

              <circle id="eyeOuter" cx="188" cy="192" r="14" fill="#1a252c"/>
              <circle id="eye" cx="188" cy="192" r="9.5" fill="#111"/>
              <circle id="eyeHighlight" cx="184" cy="188" r="3" fill="#fff"/>
              <path d="M151 222 Q136 218 149 213" fill="none" stroke="#1a252c" stroke-width="2.5" stroke-linecap="round"/>

              <path d="M255 168 Q345 142 435 172 M255 215 Q345 188 445 215 M255 262 Q345 242 435 258" stroke="#fff" opacity=".12" fill="none" stroke-width="5"/>

              <path id="gonopodium" d="M345 280 L400 318 L360 278 Z" fill="currentColor" opacity=".88"/>
            </g>

            <text x="400" y="405" text-anchor="middle" fill="#94a3b8" font-size="14" id="uiSvgFoot">Anatomi & Morfologi Guppy Terintegrasi</text>
          </svg>
        </div>

        <div class="info">
          <div class="info-title" id="uiInfoTitle">🏷️ Prediksi Nama Strain / Jenis Guppy</div>
          <div class="strain-name" id="strainName">Standard Red Delta Guppy</div>
          <div class="chips" id="chips"></div>
        </div>
      </div>
    </div>
  </section>

  <!-- VIEW 2: BREEDING SIMULATOR -->
  <section id="viewBreeding" class="view-section">
    <div style="text-align:center;margin-bottom:15px;">
      <h2 id="breedTitle" style="color:#00f5d4;margin:0 0 5px 0;">🧬 BREEDING SIMULATOR</h2>
      <p id="breedSub" style="color:#94a3b8;margin:0;font-size:13px;">Simulasikan persilangan genetik antara Induk Jantan dan Induk Betina guppy</p>
    </div>

    <!-- Tombol Random & Champion Breed Rekomendasi -->
    <div class="breeding-top-actions">
      <button class="action-btn btn-random" onclick="randomizeBreedingParents()" id="btnBreedRand">🎲 Acak Gen Induk</button>
      <button class="action-btn btn-champion" onclick="setRecommendedBreed()" id="btnBreedRec">⭐ Breed Rekomendasi</button>
    </div>

    <div class="breeding-grid">
      <!-- Induk Jantan -->
      <div class="parent-box">
        <h3 id="uiMaleParent">🐟 Induk Jantan</h3>
        <label id="bmColor">Color</label>
        <select id="mColor"><option value="Red">Red</option><option value="Blue">Blue</option><option value="Yellow">Yellow</option><option value="Black">Black</option></select>
        <label id="bmPattern">Pattern</label>
        <select id="mPattern"><option value="Solid">Solid</option><option value="Mosaic">Mosaic</option><option value="Cobra">Cobra</option></select>
        <label id="bmTail">Tail</label>
        <select id="mTail"><option value="Delta">Delta</option><option value="Halfmoon">Halfmoon</option></select>
        <label id="bmFin">Fin</label>
        <select id="mFin"><option value="Dumbo">Dumbo</option><option value="Standard">Standard</option></select>
        <label id="bmEye">Eye</label>
        <select id="mEye"><option value="Normal">Normal</option><option value="Albino">Albino</option></select>
        <label id="bmBody">Body</label>
        <select id="mBody"><option value="Standard">Standard</option><option value="Large">Large</option></select>
        <label id="bmPigment">Pigmentation</label>
        <select id="mPigment"><option value="None">None</option><option value="Moscow">Moscow</option><option value="Japan Blue">Japan Blue</option></select>
      </div>

      <!-- Center Action -->
      <div class="breeding-center">
        <button class="cross-btn" onclick="runBreeding()" id="btnCross">Mulai Silang (Cross) ➔</button>
      </div>

      <!-- Induk Betina -->
      <div class="parent-box">
        <h3 id="uiFemaleParent">🐟 Induk Betina</h3>
        <label id="bfColor">Color</label>
        <select id="fColor"><option value="Blue">Blue</option><option value="Red">Red</option><option value="Yellow">Yellow</option><option value="White">White</option></select>
        <label id="bfPattern">Pattern</label>
        <select id="fPattern"><option value="Solid">Solid</option><option value="Grass">Grass</option><option value="Cobra">Cobra</option></select>
        <label id="bfTail">Tail</label>
        <select id="fTail"><option value="Delta">Delta</option><option value="Fantail">Fantail</option></select>
        <label id="bfFin">Fin</label>
        <select id="fFin"><option value="Standard">Standard</option><option value="Dumbo">Dumbo</option></select>
        <label id="bfEye">Eye</label>
        <select id="fEye"><option value="Normal">Normal</option><option value="Albino">Albino</option></select>
        <label id="bfBody">Body</label>
        <select id="fBody"><option value="Standard">Standard</option><option value="Short">Short</option></select>
        <label id="bfPigment">Pigmentation</label>
        <select id="fPigment"><option value="None">None</option><option value="Japan Blue">Japan Blue</option><option value="Koi">Koi</option></select>
      </div>
    </div>

    <!-- Hasil F1 -->
    <div class="result-box">
      <h3 id="uiF1Title">🐣 Prediksi F1</h3>
      <table class="result-table">
        <thead>
          <tr><th id="uiThTrait">Trait</th><th id="uiThChance">Kemungkinan</th></tr>
        </thead>
        <tbody id="f1TraitsBody">
          <tr><td>Red</td><td>50%</td></tr>
          <tr><td>Blue</td><td>25%</td></tr>
          <tr><td>Other</td><td>25%</td></tr>
          <tr><td>Dumbo</td><td>50%</td></tr>
          <tr><td>Normal fin</td><td>50%</td></tr>
          <tr><td>Male</td><td>~50%</td></tr>
          <tr><td>Female</td><td>~50%</td></tr>
        </tbody>
      </table>
    </div>

    <!-- Total Fry & Breakdown -->
    <div class="result-box">
      <div class="fry-input-group">
        <span id="uiTotalFryLabel">Total fry =</span>
        <input type="number" id="totalFryInput" value="30" oninput="updateFryExpectation()">
      </div>
      <div style="font-weight:bold;color:#00f5d4;margin-bottom:8px;text-align:center;">↓</div>
      <table class="result-table">
        <thead>
          <tr><th id="uiThPred">Prediksi</th><th id="uiThPct">Persentase</th><th id="uiThExp">Ekspektasi</th></tr>
        </thead>
        <tbody id="fryExpectationBody">
          <tr><td>Tipe A</td><td>50%</td><td>~15</td></tr>
          <tr><td>Tipe B</td><td>25%</td><td>~8</td></tr>
          <tr><td>Tipe C</td><td>25%</td><td>~8</td></tr>
        </tbody>
      </table>
    </div>
  </section>
</main>

<script>
const ids = ["body","color","pattern","tail","fin","eye","sex","pigment"];
const breedIds = ["mColor","mPattern","mTail","mFin","mEye","mBody","mPigment","fColor","fPattern","fTail","fFin","fEye","fBody","fPigment"];
const $ = id => document.getElementById(id);

const tailShapes = {
  "Delta":"M525 215 C565 170 630 100 750 90 C785 85 795 110 780 145 C755 195 685 210 615 215 C685 220 755 235 780 285 C795 320 785 345 750 340 C630 330 565 260 525 215 Z",
  "Halfmoon":"M525 215 C580 120 680 55 770 78 C800 88 795 120 775 148 C730 190 690 208 615 215 C690 222 730 240 775 282 C795 310 800 342 770 352 C680 375 580 310 525 215 Z",
  "Fantail":"M525 215 C590 150 690 125 760 155 C785 168 785 262 760 275 C690 305 590 280 525 215 Z",
  "Veiltail":"M525 215 C585 100 680 55 765 100 C790 115 780 155 760 182 C720 208 685 215 615 215 C685 215 720 222 760 248 C780 275 790 315 765 330 C680 375 585 330 525 215 Z",
  "Round":"M525 215 C585 145 680 145 735 215 C680 285 585 285 525 215 Z",
  "Spade":"M525 215 L755 125 L700 215 L755 305 Z",
  "Top Sword":"M525 215 L785 72 L670 215 L785 215 Z",
  "Bottom Sword":"M525 215 L785 358 L670 215 L785 215 Z",
  "Double Sword":"M525 215 L785 72 L670 215 L785 358 Z",
  "Lyretail":"M525 215 C600 150 685 90 785 72 L690 215 L785 358 C685 340 600 280 525 215 Z",
  "Pin / Needle":"M525 215 L795 202 L795 228 Z",
  "Flag":"M525 215 C615 155 710 135 785 150 L770 215 L785 280 C710 295 615 275 525 215 Z"
};

let currentLang = 'id';
const dict = {
  'id': {
    title: "🐟 Guppy Gene Simulator Pro", sub: "Simulasi morfologi & prediksi strain guppy",
    rand: "🎲 Acak Gen", champ: "🏆 Gen Juara", control: "🧬 Kontrol Genetik", visual: "🎨 Visualisasi Fenotipe",
    lblBody: "Bentuk Tubuh", lblColor: "Warna Dasar", lblPattern: "Pola Tubuh & Ekor", lblTail: "Bentuk Ekor",
    lblFin: "Bentuk Sirip", lblEye: "Mata", lblSex: "Kelamin", lblPigment: "Pigmentasi Tubuh",
    infoTitle: "🏷 Prediksi Nama Strain / Jenis Guppy", svgFoot: "Anatomi & Morfologi Guppy Terintegrasi",
    tabMorph: "🧬 Morfologi", tabBreed: "🧪 Breeding Simulator",
    breedTitle: "🧬 BREEDING SIMULATOR", breedSub: "Simulasikan persilangan genetik antara Induk Jantan dan Induk Betina guppy",
    btnBreedRand: "🎲 Acak Gen Induk", btnBreedRec: "⭐ Breed Rekomendasi",
    uiMaleParent: "🐟 Induk Jantan", uiFemaleParent: "🐟 Induk Betina", btnCross: "Mulai Silang (Cross) ➔",
    uiF1Title: "🐣 Prediksi F1", uiThTrait: "Trait", uiThChance: "Kemungkinan",
    uiTotalFryInput: "Total fry =", uiThPred: "Prediksi", uiThPct: "Persentase", uiThExp: "Ekspektasi",
    bLabels: { color: "Warna Dasar", pattern: "Pola", tail: "Bentuk Ekor", fin: "Bentuk Sirip", eye: "Mata", body: "Bentuk Tubuh", pigment: "Pigmentasi" }
  },
  'en': {
    title: "🐟 Guppy Gene Simulator Pro", sub: "Interactive guppy morphology & strain prediction",
    rand: "🎲 Random Gene", champ: "🏆 Champion Gene", control: "🧬 Genetic Control", visual: "🎨 Phenotype Visualization",
    lblBody: "Body Shape", lblColor: "Base Color", lblPattern: "Body & Tail Pattern", lblTail: "Tail Shape",
    lblFin: "Fin Shape", lblEye: "Eye Type", lblSex: "Gender", lblPigment: "Body Pigmentation",
    infoTitle: "🏷️ Predicted Strain Name", svgFoot: "Integrated Guppy Anatomy & Morphology",
    tabMorph: "🧬 Morphology", tabBreed: "🧪 Breeding Simulator",
    breedTitle: "🧬 BREEDING SIMULATOR", breedSub: "Simulate genetic crossing between Male and Female guppy parents",
    btnBreedRand: "🎲 Random Parents", btnBreedRec: "⭐ Champion Cross",
    uiMaleParent: "🐟 Male Parent", uiFemaleParent: "🐟 Female Parent", btnCross: "Run Cross ➔",
    uiF1Title: "🐣 F1 Prediction", uiThTrait: "Trait", uiThChance: "Probability",
    uiTotalFryInput: "Total fry =", uiThPred: "Prediction", uiThPct: "Percentage", uiThExp: "Expectation",
    bLabels: { color: "Base Color", pattern: "Pattern", tail: "Tail Shape", fin: "Fin Shape", eye: "Eye Type", body: "Body Shape", pigment: "Pigmentation" }
  }
};

function setTheme(theme){
  document.body.setAttribute('data-theme', theme);
  document.querySelectorAll('.theme-switch .switch-btn').forEach(btn => btn.classList.remove('active'));
  if(theme === 'dark') $('btnDark').classList.add('active');
  else $('btnLight').classList.add('active');
}

function switchView(viewName){
  document.querySelectorAll('.view-section').forEach(sec => sec.classList.remove('active'));
  document.querySelectorAll('.nav-tabs .tab-btn').forEach(btn => btn.classList.remove('active'));
  
  if(viewName === 'morphology'){
    $('viewMorphology').classList.add('active');$('tabMorph').classList.add('active');
  } else {
    $('viewBreeding').classList.add('active');$('tabBreed').classList.add('active');
  }
}

function setLang(lang){
  currentLang = lang;
  document.querySelectorAll('.lang-switch .switch-btn').forEach(btn => btn.classList.remove('active'));
  event.target.classList.add('active');
  
  const d = dict[lang];
  $('uiTitle').innerText = d.title;
  $('uiSub').innerText = d.sub;
  $('btnRand').innerText = d.rand;
  $('btnChamp').innerText = d.champ;
  $('uiControlTitle').innerText = d.control;
  $('uiVisualTitle').innerText = d.visual;
  $('lblBody').innerText = d.lblBody;
  $('lblColor').innerText = d.lblColor;
  $('lblPattern').innerText = d.lblPattern;
  $('lblTail').innerText = d.lblTail;
  $('lblFin').innerText = d.lblFin;
  $('lblEye').innerText = d.lblEye;
  $('lblSex').innerText = d.lblSex;
  $('lblPigment').innerText = d.lblPigment;
  $('uiInfoTitle').innerText = d.infoTitle;
  $('uiSvgFoot').innerText = d.svgFoot;
  $('tabMorph').innerText = d.tabMorph;
  $('tabBreed').innerText = d.tabBreed;

  // Breeding translations
  $('breedTitle').innerText = d.breedTitle;
  $('breedSub').innerText = d.breedSub;
  $('btnBreedRand').innerText = d.btnBreedRand;
  $('btnBreedRec').innerText = d.btnBreedRec;
  $('uiMaleParent').innerText = d.uiMaleParent;
  $('uiFemaleParent').innerText = d.uiFemaleParent;
  $('btnCross').innerText = d.btnCross;
  $('uiF1Title').innerText = d.uiF1Title;
  $('uiThTrait').innerText = d.uiThTrait;
  $('uiThChance').innerText = d.uiThChance;
  $('uiTotalFryInput').innerText = d.uiTotalFryInput;
  $('uiThPred').innerText = d.uiThPred;
  $('uiThPct').innerText = d.uiThPct;
  $('uiThExp').innerText = d.uiThExp;

  // Breeding Form Labels
  const bl = d.bLabels;
  ['bmColor','bfColor'].forEach(id => $(id).innerText = bl.color);
  ['bmPattern','bfPattern'].forEach(id => $(id).innerText = bl.pattern);
  ['bmTail','bfTail'].forEach(id => $(id).innerText = bl.tail);
  ['bmFin','bfFin'].forEach(id => $(id).innerText = bl.fin);
  ['bmEye','bfEye'].forEach(id => $(id).innerText = bl.eye);
  ['bmBody','bfBody'].forEach(id => $(id).innerText = bl.body);
  ['bmPigment','bfPigment'].forEach(id => $(id).innerText = bl.pigment);

  update();
  runBreeding();
}

function setColor(color){
  ["tailShape","bodyShape","dorsal","analFin","pectoral1","pectoral2","gonopodium"].forEach(id=>{
    const e = $(id);
    if(e) e.style.color = color;
  });
}

function renderPattern(name){
  const bodyLayer = $("patternLayer");
  const tailLayer = $("tailPatternLayer");
  bodyLayer.innerHTML = "";
  tailLayer.innerHTML = "";

  if(name === "Mosaic"){
    for(let i=0; i<6; i++) bodyLayer.innerHTML += `<path d="M250 ${160+i*20} q35 -15 70 0 q35 15 70 0" stroke="#fff" stroke-width="6" fill="none" opacity=".8"/>`;
  } else if(name === "Grass"){
    for(let i=0; i<14; i++) bodyLayer.innerHTML += `<circle cx="${255+(i%7)*35}" cy="${160+Math.floor(i/7)*35}" r="3.5" fill="#fff" opacity=".85"/>`;
  } else if(name === "Leopard" || name === "Spotted"){
    for(let i=0; i<10; i++) bodyLayer.innerHTML += `<circle cx="${260+(i%5)*40}" cy="${165+Math.floor(i/5)*40}" r="${5.5+(i%2)*2.5}" fill="#111" opacity=".75"/>`;
  } else if(name === "Cobra / Snakeskin"){
    for(let i=0; i<7; i++) bodyLayer.innerHTML += `<path d="M250 ${155+i*18} q20 -12 40 0 q20 12 40 0" stroke="#fff" stroke-width="4" fill="none" opacity=".8"/>`;
  } else if(name === "Tuxedo" || name === "Half Black"){
    bodyLayer.innerHTML = '<path d="M360 138 Q450 148 515 215 Q450 282 360 292 Q410 215 360 138 Z" fill="#111" opacity=".75"/>';
  } else if(name === "Lace"){
    for(let i=0; i<6; i++) bodyLayer.innerHTML += `<path d="M250 ${160+i*22} l22 10 l22 -10 l22 10" stroke="#fff" stroke-width="3.5" fill="none" opacity=".8"/>`;
  }

  if(name === "Mosaic" || name === "Lace"){
    for(let i=0; i<8; i++){
      tailLayer.innerHTML += `<path d="M540 ${130+i*16} q60 -15 120 0 q60 15 120 0" stroke="#fff" stroke-width="5" fill="none" opacity=".75"/>`;
    }
  } else if(name === "Grass" || name === "Spotted"){
    for(let i=0; i<25; i++){
      let rx = 550 + (i % 6) * 38;
      let ry = 120 + Math.floor(i / 6) * 45;
      tailLayer.innerHTML += `<circle cx="${rx}" cy="${ry}" r="4" fill="#fff" opacity=".8"/>`;
    }
  } else if(name === "Leopard"){
    for(let i=0; i<20; i++){
      let rx = 560 + (i % 5) * 42;
      let ry = 130 + Math.floor(i / 5) * 45;
      tailLayer.innerHTML += `<circle cx="${rx}" cy="${ry}" r="6" fill="#111" opacity=".75"/>`;
    }
  } else if(name === "Cobra / Snakeskin"){
    for(let i=0; i<7; i++){
      tailLayer.innerHTML += `<path d="M540 ${130+i*22} q45 -20 90 0 q45 20 90 0 q45 -20 90 0" stroke="#fff" stroke-width="4" fill="none" opacity=".8"/>`;
    }
  }
}

function renderPigment(name){
  let pg = $("pigmentOverlay");
  pg.innerHTML = "";
  
  const shapes = {
    "Japan Blue": '<path d="M245 150 Q380 125 520 185 L520 245 Q380 305 245 280 Q290 215 245 150Z" fill="#1688ff" opacity=".85"/>',
    "Moscow": '<path d="M245 145 Q380 115 525 185 L525 245 Q380 315 245 285 Q290 215 245 145Z" fill="#0f172a" opacity=".9"/>',
    "Dragon": '<path d="M245 148 Q380 118 525 185 L525 245 Q380 312 245 282 Q290 215 245 148Z" fill="#b45309" opacity=".8"/>' +
              '<path d="M250 162 Q380 138 505 180 M250 215 Q380 190 515 215 M250 268 Q380 242 505 250" stroke="#fef08a" stroke-width="4.5" opacity=".75" fill="none"/>',
    "Koi": '<ellipse cx="280" cy="180" rx="35" ry="25" fill="#ffffff" opacity=".95"/>' +
           '<ellipse cx="440" cy="245" rx="50" ry="30" fill="#ffffff" opacity=".95"/>' +
           '<circle cx="485" cy="185" r="22" fill="#ef4444" opacity=".9"/>',
    "Platinum": '<path d="M245 148 Q380 115 525 185 L525 245 Q380 315 245 282 Q290 215 245 148Z" fill="#f8fafc" opacity=".9"/>',
    "Metallic": '<path d="M245 150 Q380 118 525 185 L525 245 Q380 312 245 282 Q290 215 245 150Z" fill="#cbd5e1" opacity=".8"/>'
  };
  if(shapes[name]) pg.innerHTML = shapes[name];
}

function updateStrainName(body, color, pattern, tail, fin, eye, sex, pigment){
  let nameParts = [];
  if(eye === "Albino / RREA") nameParts.push("Albino");
  else if(eye === "Red Eye") nameParts.push("Real Red Eye");

  if(pigment !== "None") nameParts.push(pigment);

  let colorName = $("color").options[$("color").selectedIndex].text.split(" ")[0];
  if(pigment === "Moscow" || pigment === "Japan Blue" || pigment === "Koi") {
    // skip base color
  } else if(pattern === "Tuxedo" || pattern === "Half Black") {
    nameParts.push("Tuxedo " + colorName);
  } else {
    nameParts.push(colorName);
  }

  if(pattern !== "Solid" && pattern !== "Tuxedo" && pattern !== "Half Black") {
    nameParts.push(pattern);
  }

  nameParts.push(tail);
  if(fin !== "Standard") nameParts.push("(" + fin + ")");
  if(body === "Short Body") nameParts.push("[Short Body]");
  if(body === "Large Body") nameParts.push("[King/Giant]");
  
  $("strainName").innerText = nameParts.join(" ") + " Guppy";
}

function update(){
  const color = $("color").value;
  const body = $("body").value;
  const tail = $("tail").value;
  const pattern = $("pattern").value;
  const fin = $("fin").value;
  const eye = $("eye").value;
  const sex = $("sex").value;
  const pigment = $("pigment").value;

  setColor(color);

  const mainGroup = $("fishMainGroup");
  mainGroup.removeAttribute("transform");
  if(body === "Short Body") {
    mainGroup.setAttribute("transform", "translate(75, 25) scale(0.85, 1.1) rotate(2, 400, 215)");
  } else if(body === "Large Body") {
    mainGroup.setAttribute("transform", "translate(-35, -20) scale(1.12, 1.08)");
  }

  const tPath = tailShapes[tail] || tailShapes.Delta;
  $("tailShape").setAttribute("d", tPath);
  $("tailClipPath").setAttribute("d", tPath);

  const p1 = $("pectoral1"), p2 = $("pectoral2");
  let rx = 42, ry = 15;
  if(fin === "Dumbo / Elephant Ear"){ rx = 52; ry = 24; }
  else if(fin === "Ribbon"){ rx = 48; ry = 16; }
  else if(fin === "Swallow"){ rx = 50; ry = 14; }
  else if(fin === "Long-fin"){ rx = 48; ry = 18; }
  
  p1.setAttribute("cx", 295); p1.setAttribute("cy", 235);
  p1.setAttribute("rx", rx); p1.setAttribute("ry", ry);
  
  p2.setAttribute("cx", 295); p2.setAttribute("cy", 195);
  p2.setAttribute("rx", rx); p2.setAttribute("ry", ry);

  const eyeOuter = $("eyeOuter"), eyeCore = $("eye"), eyeHighlight = $("eyeHighlight");
  if(eye === "Normal"){
    eyeOuter.setAttribute("fill", "#1a252c"); eyeCore.setAttribute("fill", "#111"); eyeHighlight.setAttribute("fill", "#fff");
  } else if(eye === "Albino / RREA"){
    eyeOuter.setAttribute("fill", "#fca5a5"); eyeCore.setAttribute("fill", "#dc2626"); eyeHighlight.setAttribute("fill", "#fff");
  } else {
    eyeOuter.setAttribute("fill", "#7f1d1d"); eyeCore.setAttribute("fill", "#ef4444"); eyeHighlight.setAttribute("fill", "#fff");
  }

  $("gonopodium").style.display = sex === "Male" ? "block" : "none";

  renderPattern(pattern);
  renderPigment(pigment);

  $("chips").innerHTML = ids.map(id => `<span class="chip">${$(id).value}</span>`).join("");
  updateStrainName(body, color, pattern, tail, fin, eye, sex, pigment);
}

function randomizeGene(){
  ids.forEach(id => {
    const sel = $(id);
    sel.selectedIndex = Math.floor(Math.random() * sel.options.length);
  });
  update();
}

function setChampion(){
  const champions = [
    {body:"Standard", color:"#20252b", pattern:"Solid", tail:"Delta", fin:"Standard", eye:"Normal", sex:"Male", pigment:"Moscow"},
    {body:"Standard", color:"#1976d2", pattern:"Solid", tail:"Delta", fin:"Standard", eye:"Normal", sex:"Male", pigment:"Japan Blue"},
    {body:"Standard", color:"#e53935", pattern:"Solid", tail:"Delta", fin:"Dumbo / Elephant Ear", eye:"Albino / RREA", sex:"Male", pigment:"None"}
  ];
  const champ = champions[Math.floor(Math.random() * champions.length)];
  for(let key in champ){
    if($(key))$(key).value = champ[key];
  }
  update();
}

function randomizeBreedingParents(){
  breedIds.forEach(id => {
    const sel = $(id);
    if(sel) sel.selectedIndex = Math.floor(Math.random() * sel.options.length);
  });
  runBreeding();
}

function setRecommendedBreed(){
  const recommendations = [
    {mColor:"Red", mPattern:"Solid", mTail:"Delta", mFin:"Dumbo", mEye:"Normal", mBody:"Standard", mPigment:"None", fColor:"Blue", fPattern:"Solid", fTail:"Delta", fFin:"Standard", fEye:"Normal", fBody:"Standard", fPigment:"Japan Blue"},
    {mColor:"Black", mPattern:"Solid", mTail:"Halfmoon", mFin:"Standard", mEye:"Normal", mBody:"Standard", mPigment:"Moscow", fColor:"White", fPattern:"Solid", fTail:"Delta", fFin:"Standard", fEye:"Normal", fBody:"Standard", fPigment:"None"},
    {mColor:"Yellow", mPattern:"Cobra", mTail:"Delta", mFin:"Standard", mEye:"Albino", mBody:"Standard", mPigment:"None", fColor:"Red", fPattern:"Grass", fTail:"Fantail", fFin:"Dumbo", fEye:"Normal", fBody:"Standard", fPigment:"Koi"}
  ];
  const rec = recommendations[Math.floor(Math.random() * recommendations.length)];
  for(let key in rec){
    if($(key))$(key).value = rec[key];
  }
  runBreeding();
}

function runBreeding(){
  const mCol = $('mColor').value;
  const fCol = $('fColor').value;
  const maleText = currentLang === 'id' ? 'Dominan Jantan' : 'Male Dominant';
  const femaleText = currentLang === 'id' ? 'Resesif Betina' : 'Female Recessive';
  const otherText = currentLang === 'id' ? 'Kombinasi Lain' : 'Other Combination';
  const dumboText = currentLang === 'id' ? 'Sirip Dumbo' : 'Dumbo Fin';
  const normalFinText = currentLang === 'id' ? 'Sirip Normal' : 'Normal Fin';
  const maleGenderText = currentLang === 'id' ? 'Jantan' : 'Male';
  const femaleGenderText = currentLang === 'id' ? 'Betina' : 'Female';
  
  $('f1TraitsBody').innerHTML = `
    <tr><td>${mCol} (${maleText})</td><td>50%</td></tr>
    <tr><td>${fCol} (${femaleText})</td><td>25%</td></tr>
    <tr><td>${otherText}</td><td>25%</td></tr>
    <tr><td>${dumboText}</td><td>50%</td></tr>
    <tr><td>${normalFinText}</td><td>50%</td></tr>
    <tr><td>${maleGenderText}</td><td>~50%</td></tr>
    <tr><td>${femaleGenderText}</td><td>~50%</td></tr>
  `;
  updateFryExpectation();
}

function updateFryExpectation(){
  const total = parseInt($('totalFryInput').value) || 30;
  const tA = Math.round(total * 0.5);
  const tB = Math.round(total * 0.25);
  const tC = total - tA - tB;
  
  const mColName = $('mColor').value;
  const fColName = $('fColor').value;
  const typeAText = currentLang === 'id' ? 'Tipe A' : 'Type A';
  const typeBText = currentLang === 'id' ? 'Tipe B' : 'Type B';
  const typeCText = currentLang === 'id' ? 'Tipe C (Hibrid)' : 'Type C (Hybrid)';
  
  $('fryExpectationBody').innerHTML = `
    <tr><td>${typeAText} (${mColName} Dominant)</td><td>50%</td><td>~${tA}</td></tr>
    <tr><td>${typeBText} (${fColName} Recessive)</td><td>25%</td><td>~${tB}</td></tr>
    <tr><td>${typeCText}</td><td>25%</td><td>~${tC}</td></tr>
  `;
}

document.addEventListener("DOMContentLoaded", ()=>{
  ids.forEach(id => {
    const control = $(id);
    if(control){
      control.addEventListener("change", update);
      control.addEventListener("input", update);
    }
  });
  update();
  runBreeding();
});
</script>
</body>
</html>
