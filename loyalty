<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Glamour Nails by Laura R – Loyalty</title>
  <style>
    :root{
      --beige:#E9D8D0;
      --blush:#F3E7E5;
      --nude:#D8BFB6;
      --black:#111111;
      --muted:#6F6661;
      --white:#ffffff;
      --shadow: 0 12px 30px rgba(17,17,17,.12);
      --radius: 20px;
    }

    *{ box-sizing:border-box; }
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial, "Helvetica Neue", Helvetica, sans-serif;
      background: linear-gradient(180deg, var(--blush), var(--beige));
      color: var(--black);
      min-height: 100vh;
      display:flex;
      align-items:center;
      justify-content:center;
      padding: 24px;
    }

    .app{
      width: min(920px, 100%);
      display:grid;
      grid-template-columns: 1.05fr .95fr;
      gap: 18px;
    }

    @media (max-width: 860px){
      .app{ grid-template-columns: 1fr; }
    }

    .card{
      background: rgba(255,255,255,.82);
      backdrop-filter: blur(10px);
      border: 1px solid rgba(17,17,17,.08);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      padding: 22px;
      position:relative;
      overflow:hidden;
    }

    .brand{
      display:flex;
      align-items:flex-start;
      justify-content:space-between;
      gap: 12px;
      margin-bottom: 14px;
    }

    .logo{
      width: 44px; height: 44px;
      border-radius: 14px;
      background: linear-gradient(135deg, var(--black), #2b2b2b);
      display:flex; align-items:center; justify-content:center;
      color: var(--blush);
      font-weight: 800;
      letter-spacing: .5px;
      flex: 0 0 auto;
    }

    .brand h1{
      font-size: 22px;
      margin: 0;
      line-height: 1.15;
      letter-spacing: .2px;
    }

    .brand .sub{
      margin-top: 6px;
      color: var(--muted);
      font-size: 13px;
      line-height: 1.4;
    }

    .pill{
      display:inline-flex;
      align-items:center;
      gap: 8px;
      padding: 10px 12px;
      border-radius: 999px;
      background: rgba(233,216,208,.55);
      border: 1px solid rgba(17,17,17,.08);
      font-size: 12px;
      color: var(--black);
      white-space: nowrap;
    }

    .row{
      display:flex;
      gap: 10px;
      flex-wrap: wrap;
      align-items:center;
    }

    label{
      display:block;
      font-size: 12px;
      color: var(--muted);
      margin-bottom: 6px;
    }

    input, button{
      font: inherit;
    }

    .input{
      width:100%;
      padding: 12px 12px;
      border-radius: 14px;
      border: 1px solid rgba(17,17,17,.12);
      background: rgba(255,255,255,.9);
      outline: none;
    }
    .input:focus{
      border-color: rgba(17,17,17,.35);
      box-shadow: 0 0 0 4px rgba(216,191,182,.35);
    }

    .btn{
      border:0;
      border-radius: 14px;
      padding: 12px 14px;
      cursor:pointer;
      transition: transform .08s ease, opacity .2s ease, background .2s ease;
      display:inline-flex;
      align-items:center;
      justify-content:center;
      gap: 10px;
      user-select:none;
      font-weight: 650;
    }
    .btn:active{ transform: translateY(1px); }
    .btn.primary{
      background: var(--black);
      color: var(--blush);
    }
    .btn.secondary{
      background: rgba(17,17,17,.07);
      color: var(--black);
      border: 1px solid rgba(17,17,17,.10);
    }
    .btn.danger{
      background: #2b0f10;
      color: #ffe9ea;
    }

    .grid{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }
    @media (max-width: 520px){
      .grid{ grid-template-columns:1fr; }
    }

    .divider{
      height:1px;
      background: rgba(17,17,17,.09);
      margin: 16px 0;
    }

    .stamps{
      margin-top: 8px;
      display:grid;
      grid-template-columns: repeat(5, 1fr);
      gap: 10px;
    }

    .stamp{
      aspect-ratio: 1 / 1;
      border-radius: 16px;
      border: 1.5px dashed rgba(17,17,17,.22);
      background: rgba(243,231,229,.6);
      display:flex;
      align-items:center;
      justify-content:center;
      position:relative;
      overflow:hidden;
    }
    .stamp .num{
      font-size: 12px;
      color: rgba(17,17,17,.55);
      position:absolute;
      top: 8px; left: 10px;
      font-weight: 700;
    }
    .stamp.filled{
      border: 1px solid rgba(17,17,17,.16);
      background: linear-gradient(180deg, rgba(216,191,182,.75), rgba(233,216,208,.55));
    }
    .stamp.filled::after{
      content:"✓";
      font-weight: 900;
      font-size: 26px;
      color: var(--black);
      opacity: .9;
      transform: rotate(-6deg);
    }

    .rewards{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
      margin-top: 14px;
    }
    @media (max-width: 520px){
      .rewards{ grid-template-columns: 1fr; }
    }

    .reward{
      border-radius: 18px;
      border: 1px solid rgba(17,17,17,.10);
      padding: 14px 14px;
      background: rgba(255,255,255,.7);
      position:relative;
      overflow:hidden;
    }
    .reward h3{
      margin:0;
      font-size: 14px;
      letter-spacing:.2px;
    }
    .reward p{
      margin: 6px 0 0;
      color: var(--muted);
      font-size: 12.5px;
      line-height:1.35;
    }
    .reward.locked{
      opacity:.65;
    }
    .badge{
      position:absolute;
      right: 12px;
      top: 12px;
      font-size: 11px;
      padding: 7px 10px;
      border-radius: 999px;
      border: 1px solid rgba(17,17,17,.12);
      background: rgba(233,216,208,.7);
      font-weight: 800;
    }
    .badge.unlocked{
      background: rgba(17,17,17,.92);
      color: var(--blush);
      border-color: rgba(17,17,17,.1);
    }

    .toast{
      position: fixed;
      left: 50%;
      bottom: 18px;
      transform: translateX(-50%);
      background: rgba(17,17,17,.92);
      color: var(--blush);
      padding: 12px 14px;
      border-radius: 999px;
      font-size: 13px;
      opacity: 0;
      pointer-events:none;
      transition: opacity .25s ease, transform .25s ease;
      box-shadow: 0 12px 25px rgba(17,17,17,.25);
      z-index: 50;
    }
    .toast.show{
      opacity: 1;
      transform: translateX(-50%) translateY(-6px);
    }

    /* Confetti */
    .confetti{
      position:absolute;
      inset:0;
      pointer-events:none;
      overflow:hidden;
      z-index: 2;
    }
    .confetti i{
      position:absolute;
      width:10px; height:14px;
      border-radius: 3px;
      opacity:.95;
      animation: fall 900ms linear forwards;
    }
    @keyframes fall{
      0%{ transform: translateY(-20px) rotate(0deg); opacity: 0; }
      8%{ opacity: 1; }
      100%{ transform: translateY(340px) rotate(260deg); opacity: 0; }
    }

    .muted{
      color: var(--muted);
      font-size: 12.5px;
      line-height:1.35;
      margin: 0;
    }

    .small{
      font-size: 12px;
      color: var(--muted);
    }

    .right .card{
      height: 100%;
    }

    .adminBox{
      background: rgba(243,231,229,.65);
      border: 1px solid rgba(17,17,17,.08);
      border-radius: 18px;
      padding: 14px;
    }

    .footer-actions{
      display:flex;
      gap: 10px;
      flex-wrap: wrap;
      margin-top: 12px;
    }

    .mono{
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
    }
  </style>
</head>

<body>
  <div class="app">
    <!-- LEFT: Client Card -->
    <div class="card">
      <div class="brand">
        <div style="display:flex; gap:12px;">
          <div class="logo">GR</div>
          <div>
            <h1>Glamour Nails by Laura R</h1>
            <div class="sub">Loyalty Card • Collect 10 stamps<br/>Rewards at 5th & 10th visit</div>
          </div>
        </div>
        <div class="pill" id="statusPill">Not signed in</div>
      </div>

      <div class="grid" style="align-items:end;">
        <div>
          <label for="email">Client email</label>
          <input class="input" id="email" type="email" placeholder="client@email.com" autocomplete="email" />
        </div>
        <div>
          <label for="pin">Client PIN (optional)</label>
          <input class="input" id="pin" type="password" placeholder="4 digits (optional)" inputmode="numeric" />
        </div>
      </div>

      <div class="footer-actions">
        <button class="btn primary" id="btnOpen">Open my card</button>
        <button class="btn secondary" id="btnCreate">Create new card</button>
        <button class="btn secondary" id="btnSignOut">Sign out</button>
      </div>

      <div class="divider"></div>

      <div class="row" style="justify-content:space-between;">
        <div>
          <div style="font-weight:800; letter-spacing:.2px;">Stamps</div>
          <div class="small">2 rows of 5 • Stamps are added by admin only</div>
        </div>
        <div class="pill"><span>Visits:</span> <strong id="visits">0</strong>/10</div>
      </div>

      <div style="position:relative; margin-top:12px;">
        <div class="confetti" id="confetti"></div>
        <div class="stamps" id="stamps"></div>
      </div>

      <div class="rewards">
        <div class="reward locked" id="reward5">
          <div class="badge" id="badge5">LOCKED</div>
          <h3>5th Visit Reward 🎁</h3>
          <p><strong>10% OFF</strong> your service on your 5th visit.</p>
        </div>
        <div class="reward locked" id="reward10">
          <div class="badge" id="badge10">LOCKED</div>
          <h3>10th Visit Reward 🎉</h3>
          <p><strong>50% OFF</strong> your service on your 10th visit.</p>
        </div>
      </div>

      <div class="divider"></div>
      <p class="muted">
        Tip: Save a screenshot of this card. Show it at your appointment.
      </p>
    </div>

    <!-- RIGHT: Admin Panel -->
    <div class="right">
      <div class="card">
        <div class="brand" style="margin-bottom:10px;">
          <div>
            <h1 style="font-size:18px; margin:0;">Admin Panel</h1>
            <div class="sub">Only you can add stamps</div>
          </div>
          <div class="pill mono">ADMIN</div>
        </div>

        <div class="adminBox">
          <label for="adminPin">Admin PIN</label>
          <input class="input" id="adminPin" type="password" placeholder="Enter admin PIN" inputmode="numeric" />
          <div class="footer-actions" style="margin-top:10px;">
            <button class="btn primary" id="btnUnlock">Unlock</button>
            <button class="btn secondary" id="btnLock">Lock</button>
          </div>
          <p class="small" style="margin-top:10px;">
            Admin actions apply to the <strong>currently opened client card</strong>.
          </p>
        </div>

        <div class="divider"></div>

        <div class="row" style="gap:12px;">
          <button class="btn primary" id="btnAdd" disabled>+ Add stamp</button>
          <button class="btn secondary" id="btnRemove" disabled>- Remove stamp</button>
          <button class="btn danger" id="btnReset" disabled>Reset card</button>
        </div>

        <div class="divider"></div>

        <div class="adminBox">
          <div style="font-weight:800; margin-bottom:6px;">Backup (optional)</div>
          <p class="small" style="margin-top:0;">
            Export/import all cards (for moving to another device).
          </p>
          <div class="footer-actions">
            <button class="btn secondary" id="btnExport">Export JSON</button>
            <button class="btn secondary" id="btnImport">Import JSON</button>
          </div>
          <textarea class="input mono" id="backupArea" rows="6" placeholder="Exported JSON will appear here…"></textarea>
        </div>

        <p class="small" style="margin-top:12px;">
          Current client: <strong id="currentClient">None</strong>
        </p>
      </div>
    </div>
  </div>

  <div class="toast" id="toast"></div>

<script>
  /***************
   * CONFIG
   ***************/
  // Change this to your secret PIN
  const ADMIN_PIN = "2580";

  // Storage key
  const DB_KEY = "gn_loyalty_db_v1";

  /***************
   * STATE
   ***************/
  let db = loadDB();
  let currentKey = null;   // unique per client (email+pin)
  let adminUnlocked = false;
  let lastVisits = 0;

  /***************
   * ELEMENTS
   ***************/
  const elEmail = document.getElementById("email");
  const elPin = document.getElementById("pin");
  const elStatus = document.getElementById("statusPill");
  const elVisits = document.getElementById("visits");
  const elStamps = document.getElementById("stamps");
  const elReward5 = document.getElementById("reward5");
  const elReward10 = document.getElementById("reward10");
  const elBadge5 = document.getElementById("badge5");
  const elBadge10 = document.getElementById("badge10");
  const elConfetti = document.getElementById("confetti");
  const elToast = document.getElementById("toast");
  const elAdminPin = document.getElementById("adminPin");
  const elCurrentClient = document.getElementById("currentClient");

  const btnOpen = document.getElementById("btnOpen");
  const btnCreate = document.getElementById("btnCreate");
  const btnSignOut = document.getElementById("btnSignOut");

  const btnUnlock = document.getElementById("btnUnlock");
  const btnLock = document.getElementById("btnLock");
  const btnAdd = document.getElementById("btnAdd");
  const btnRemove = document.getElementById("btnRemove");
  const btnReset = document.getElementById("btnReset");

  const btnExport = document.getElementById("btnExport");
  const btnImport = document.getElementById("btnImport");
  const backupArea = document.getElementById("backupArea");

  /***************
   * UI BUILD
   ***************/
  function buildStamps(){
    elStamps.innerHTML = "";
    for(let i=1;i<=10;i++){
      const d = document.createElement("div");
      d.className = "stamp";
      d.dataset.n = String(i);
      const n = document.createElement("div");
      n.className = "num";
      n.textContent = i;
      d.appendChild(n);
      elStamps.appendChild(d);
    }
  }
  buildStamps();

  function toast(msg){
    elToast.textContent = msg;
    elToast.classList.add("show");
    setTimeout(()=> elToast.classList.remove("show"), 2200);
  }

  function setAdminButtons(){
    const enabled = adminUnlocked && !!currentKey;
    btnAdd.disabled = !enabled;
    btnRemove.disabled = !enabled;
    btnReset.disabled = !enabled;
  }

  function setStatus(text){
    elStatus.textContent = text;
  }

  function render(){
    // If no current client, show blank
    const visits = currentKey && db[currentKey] ? db[currentKey].visits : 0;

    elVisits.textContent = visits;

    // stamps fill
    [...elStamps.children].forEach((node, idx)=>{
      const n = idx + 1;
      node.classList.toggle("filled", visits >= n);
    });

    // rewards
    const r5 = visits >= 5;
    const r10 = visits >= 10;

    elReward5.classList.toggle("locked", !r5);
    elReward10.classList.toggle("locked", !r10);

    elBadge5.textContent = r5 ? "UNLOCKED" : "LOCKED";
    elBadge10.textContent = r10 ? "UNLOCKED" : "LOCKED";
    elBadge5.classList.toggle("unlocked", r5);
    elBadge10.classList.toggle("unlocked", r10);

    // status pill + current client
    if(currentKey){
      const rec = db[currentKey];
      setStatus(`Signed in: ${rec.email}`);
      elCurrentClient.textContent = rec.email;
    } else {
      setStatus("Not signed in");
      elCurrentClient.textContent = "None";
    }

    // reward effect trigger
    if(visits !== lastVisits){
      if(visits === 5){
        fireConfetti();
        toast("Reward unlocked 🎉 10% OFF");
      }
      if(visits === 10){
        fireConfetti(true);
        toast("Big reward unlocked 🖤 50% OFF");
      }
      lastVisits = visits;
    }

    setAdminButtons();
  }

  /***************
   * CONFETTI
   ***************/
  function fireConfetti(big=false){
    elConfetti.innerHTML = "";
    const count = big ? 42 : 26;
    const colors = ["#111111", "#D8BFB6", "#E9D8D0", "#F3E7E5"];

    for(let i=0;i<count;i++){
      const piece = document.createElement("i");
      const left = Math.random()*100;
      const delay = Math.random()*120;
      const dur = 780 + Math.random()*420;

      piece.style.left = left + "%";
      piece.style.top = (-10 - Math.random()*20) + "px";
      piece.style.background = colors[Math.floor(Math.random()*colors.length)];
      piece.style.animationDuration = dur + "ms";
      piece.style.animationDelay = delay + "ms";
      piece.style.transform = `rotate(${Math.random()*180}deg)`;

      elConfetti.appendChild(piece);
    }
    setTimeout(()=>{ elConfetti.innerHTML=""; }, 1300);
  }

  /***************
   * DB HELPERS
   ***************/
  function loadDB(){
    try{
      const raw = localStorage.getItem(DB_KEY);
      return raw ? JSON.parse(raw) : {};
    }catch(e){
      return {};
    }
  }

  function saveDB(){
    localStorage.setItem(DB_KEY, JSON.stringify(db));
  }

  function makeKey(email, pin){
    const clean = String(email||"").trim().toLowerCase();
    const p = String(pin||"").trim();
    return `client:${clean}#${p}`;
  }

  function ensureEmail(email){
    const clean = String(email||"").trim().toLowerCase();
    return clean.includes("@") && clean.includes(".");
  }

  /***************
   * ACTIONS
   ***************/
  btnCreate.addEventListener("click", ()=>{
    const email = elEmail.value;
    const pin = elPin.value;

    if(!ensureEmail(email)){
      toast("Please enter a valid email.");
      return;
    }

    const key = makeKey(email, pin);
    if(db[key]){
      toast("Card already exists. Open it instead.");
      return;
    }

    db[key] = {
      email: String(email).trim().toLowerCase(),
      pin: String(pin||"").trim(),
      visits: 0,
      createdAt: new Date().toISOString(),
      updatedAt: new Date().toISOString()
    };
    saveDB();
    currentKey = key;
    lastVisits = 0;
    toast("New card created ✅");
    render();
  });

  btnOpen.addEventListener("click", ()=>{
    const email = elEmail.value;
    const pin = elPin.value;

    if(!ensureEmail(email)){
      toast("Please enter a valid email.");
      return;
    }
    const key = makeKey(email, pin);
    if(!db[key]){
      toast("Card not found. Create a new card.");
      return;
    }
    currentKey = key;
    lastVisits = 0;
    toast("Card opened ✅");
    render();
  });

  btnSignOut.addEventListener("click", ()=>{
    currentKey = null;
    toast("Signed out");
    render();
  });

  // Admin lock/unlock
  btnUnlock.addEventListener("click", ()=>{
    if(elAdminPin.value.trim() === ADMIN_PIN){
      adminUnlocked = true;
      toast("Admin unlocked 🔓");
    } else {
      adminUnlocked = false;
      toast("Wrong admin PIN");
    }
    setAdminButtons();
  });

  btnLock.addEventListener("click", ()=>{
    adminUnlocked = false;
    elAdminPin.value = "";
    toast("Admin locked 🔒");
    setAdminButtons();
  });

  // Admin actions
  btnAdd.addEventListener("click", ()=>{
    if(!adminUnlocked || !currentKey) return;
    const rec = db[currentKey];
    if(rec.visits >= 10){
      toast("Already completed (10/10)");
      return;
    }
    rec.visits += 1;
    rec.updatedAt = new Date().toISOString();
    saveDB();
    toast("Stamp added ✅");
    render();
  });

  btnRemove.addEventListener("click", ()=>{
    if(!adminUnlocked || !currentKey) return;
    const rec = db[currentKey];
    if(rec.visits <= 0){
      toast("No stamps to remove");
      return;
    }
    rec.visits -= 1;
    rec.updatedAt = new Date().toISOString();
    saveDB();
    toast("Stamp removed");
    render();
  });

  btnReset.addEventListener("click", ()=>{
    if(!adminUnlocked || !currentKey) return;
    const ok = confirm("Reset this client's card to 0 visits?");
    if(!ok) return;
    db[currentKey].visits = 0;
    db[currentKey].updatedAt = new Date().toISOString();
    saveDB();
    toast("Card reset");
    render();
  });

  // Backup export/import
  btnExport.addEventListener("click", ()=>{
    backupArea.value = JSON.stringify(db, null, 2);
    toast("Exported to JSON");
  });

  btnImport.addEventListener("click", ()=>{
    try{
      const obj = JSON.parse(backupArea.value || "{}");
      if(typeof obj !== "object" || Array.isArray(obj)) throw new Error("Invalid JSON");
      db = obj;
      saveDB();
      toast("Imported ✅");
      render();
    }catch(e){
      toast("Import failed: invalid JSON");
    }
  });

  // Initial render
  render();
</script>
</body>
</html>
