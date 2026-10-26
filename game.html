
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no">
<meta name="theme-color" content="#07111b">
<title>Circuit Clash — Multiplayer Electronics Quiz</title>
<style>
:root{--bg:#07111b;--panel:#0d1c29;--light:#122637;--green:#42ff9e;--blue:#39c8ff;--red:#ff536b;--yellow:#ffe47a;--text:#ecf7ff;--muted:#91a9ba;--border:rgba(110,200,235,.2)}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
html,body{margin:0;min-height:100%;background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",sans-serif}
body{min-height:100dvh;overflow-x:hidden;background-image:linear-gradient(rgba(57,200,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(57,200,255,.035) 1px,transparent 1px);background-size:24px 24px}
button,input{font:inherit}button{cursor:pointer;touch-action:manipulation}button:focus-visible,input:focus-visible{outline:2px solid var(--blue);outline-offset:3px}
.hidden{display:none!important}.screen{width:100%;max-width:760px;margin:auto;min-height:100dvh;padding:18px 14px;animation:appear .3s ease}
@keyframes appear{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:translateY(0)}}
@keyframes pulse{50%{opacity:.5}}@keyframes pop{50%{transform:scale(1.02)}}
.brand{text-align:center;margin:10px auto 23px}.chip{display:grid;place-items:center;width:62px;height:62px;margin:0 auto 12px;border:2px solid var(--green);border-radius:17px;color:var(--green);font-size:29px;background:#0a201c;box-shadow:0 0 24px #42ff9e22}
h1{font-size:clamp(27px,7vw,38px);letter-spacing:-1px;margin:0;line-height:1.15}h1 span,.green{color:var(--green)}
.subtitle{color:var(--muted);font-size:12px;margin-top:9px}
.panel{background:rgba(13,28,41,.96);border:1px solid var(--border);border-radius:17px;padding:17px;margin-bottom:13px;box-shadow:0 10px 35px #0002}
.stitle{font-size:12px;letter-spacing:2px;color:var(--blue);font-weight:850;margin:0 0 13px;text-transform:uppercase}
.label{display:block;color:var(--muted);font-size:12px;margin:12px 0 7px}
.field{width:100%;min-height:48px;border:1px solid var(--border);border-radius:11px;background:#07141f;color:var(--text);padding:12px 13px}
.btn{width:100%;min-height:50px;border:0;border-radius:12px;padding:12px 15px;font-weight:850;margin-top:12px}
.primary{background:linear-gradient(110deg,var(--green),#8affc3);color:#03120d;box-shadow:0 5px 22px #42ff9e20}
.secondary{color:var(--blue);background:transparent;border:1px solid var(--border)}
.danger{color:#fff;background:#692535}.btn:disabled{opacity:.4;cursor:not-allowed}
.small{font-size:12px;color:var(--muted);line-height:1.6}
.row{display:flex;gap:9px;align-items:center}.row>*{min-width:0;flex:1}
.row .btn{margin-top:0}.status{font-size:11px;color:var(--muted);display:flex;gap:7px;align-items:center;margin:0 0 12px}
.dot{width:8px;height:8px;background:var(--yellow);border-radius:50%;display:inline-block}.dot.on{background:var(--green)}.dot.off{background:var(--red)}
.room-code{font-size:clamp(35px,12vw,55px);font-weight:950;letter-spacing:10px;text-align:center;color:var(--green);margin:8px 0 5px}
.center{text-align:center}.player-list{list-style:none;padding:0;margin:0}
.player-list li{display:flex;align-items:center;gap:11px;padding:12px 9px;border-bottom:1px solid var(--border)}
.player-list li:last-child{border-bottom:0}.avatar{width:37px;height:37px;border-radius:11px;display:grid;place-items:center;background:#183244;font-weight:900;flex-shrink:0}
.pname{font-weight:800;overflow-wrap:anywhere}.tag{font-size:10px;color:var(--muted);margin-top:3px}
.spacer{flex:1}.game-header{display:flex;justify-content:space-between;gap:10px;align-items:center;margin-bottom:10px}
.mini{font-size:14px;font-weight:950;letter-spacing:.4px}.round{font-size:12px;color:var(--muted);font-weight:750;text-align:right}
.progress{height:4px;border-radius:8px;background:#1b3040;overflow:hidden;margin-bottom:12px}.progress>div{height:100%;background:var(--green);transition:width .3s}
.topic{display:inline-block;border:1px solid #39c8ff55;color:var(--blue);background:#39c8ff10;border-radius:30px;padding:5px 10px;font-size:10px;letter-spacing:1px;font-weight:850;text-transform:uppercase}
.question{font-size:clamp(19px,5.5vw,27px);line-height:1.4;font-weight:850;margin:13px 0 17px}
.timer-row{display:flex;align-items:center;justify-content:center;gap:10px;color:var(--muted);font-size:12px}
.timer{width:47px;height:47px;display:grid;place-items:center;border:2px solid var(--green);border-radius:50%;color:var(--green);font-weight:950;font-size:19px}
.timer.urgent{border-color:var(--red);color:var(--red);animation:pulse .5s infinite}
.answer-grid{display:grid;grid-template-columns:1fr 1fr;gap:9px;margin-top:13px}
.answer{display:flex;align-items:center;gap:9px;text-align:left;min-height:69px;padding:12px 10px;border:1px solid var(--border);border-radius:13px;background:#102535;color:var(--text);font-weight:700;font-size:14px;overflow-wrap:anywhere;transition:transform .15s,border-color .15s}
.answer:active:not(:disabled){transform:scale(.97)}.answer:disabled{cursor:default}
.letter{display:grid;place-items:center;flex-shrink:0;width:27px;height:27px;border-radius:8px;background:#203849;color:#a9c3d3;font-size:11px;font-weight:950}
.answer.chosen{border:2px solid var(--blue);background:#16394b}.answer.correct{border:2px solid var(--green);background:#123729}.answer.wrong{border:2px solid var(--red);background:#4a202b}
.notice{padding:11px 12px;background:#39c8ff0d;border:1px solid var(--border);border-radius:11px;font-size:12px;color:#c5dce9;line-height:1.55;margin-top:12px}
.leader{display:flex;align-items:center;gap:10px;padding:11px 0;border-bottom:1px solid var(--border)}
.leader:last-child{border:0}.rank{width:28px;font-weight:950;color:var(--yellow)}.score{font-weight:950;font-variant-numeric:tabular-nums}
.result-hero{text-align:center;padding:20px 10px}.trophy{font-size:48px}.winner{font-size:27px;font-weight:950;margin:6px 0}
.stat{display:flex;justify-content:space-between;gap:10px;padding:12px 0;border-bottom:1px solid var(--border);font-size:13px}.stat:last-child{border:0}.stat span:first-child{color:var(--muted)}
.review{padding:12px 0;border-bottom:1px solid var(--border);font-size:12px;line-height:1.6}.review:last-child{border:0}
.footer{text-align:center;color:#698396;font-size:11px;margin:18px 0}
#toast{position:fixed;left:12px;right:12px;bottom:16px;z-index:20;background:#193344;border:1px solid var(--border);padding:13px 15px;border-radius:12px;text-align:center;box-shadow:0 8px 25px #0005}
@media(max-width:360px){.panel{padding:13px}.answer{font-size:12px;padding:9px 7px;min-height:62px}.letter{width:23px;height:23px}}
@media(prefers-reduced-motion:reduce){*,*::before,*::after{animation-duration:.01ms!important;transition-duration:.01ms!important}}
</style>
</head>
<body>

<main id="home" class="screen">
 <header class="brand">
  <div class="chip">⌘</div><h1>CIRCUIT <span>CLASH</span></h1>
  <div class="subtitle">ONLINE ELECTRONICS QUIZ · 2–6 PLAYERS · 10 ROUNDS</div>
 </header>
 <div class="status"><i id="connectionDot" class="dot"></i><span id="connectionText">Connecting to game server…</span></div>
 <section class="panel">
  <h2 class="stitle">01 / Identify yourself</h2>
  <label class="label" for="nameInput">PLAYER NAME</label>
  <input id="nameInput" class="field" maxlength="18" autocomplete="nickname" placeholder="Enter your name">
  <label class="label" for="codeInput">ROOM CODE (for joining)</label>
  <input id="codeInput" class="field" maxlength="4" autocapitalize="characters" placeholder="ABCD" style="text-transform:uppercase;letter-spacing:5px">
  <button id="createBtn" class="btn primary">⚡ CREATE ROOM</button>
  <button id="joinBtn" class="btn secondary">JOIN ROOM</button>
  <p class="small">Create a room, share the code, and play from separate phones. No account or app installation required.</p>
 </section>
 <section class="panel">
  <h2 class="stitle">02 / How to play</h2>
  <p class="small">• 10 random questions from the electronics question bank.<br>• Each question has a 25-second shared timer.<br>• Correct answers earn 20–100 points based on speed.<br>• Wrong answers and timeouts earn zero.<br>• The leaderboard updates after every round.</p>
 </section>
 <p class="footer">CIRCUIT CLASH · BUILT FOR ELECTRONICS LEARNERS</p>
</main>

<main id="lobby" class="screen hidden">
 <div class="game-header"><div class="mini">CIRCUIT <span class="green">CLASH</span></div><div class="round">MULTIPLAYER LOBBY</div></div>
 <section class="panel center">
  <div class="stitle">YOUR ROOM CODE</div><div id="roomCode" class="room-code">----</div>
  <p class="small">Share this code with your friends.</p>
  <div class="row" style="margin-top:15px">
   <button id="copyBtn" class="btn secondary">Copy invite link</button>
   <button id="shareBtn" class="btn secondary">Share ↗</button>
  </div>
 </section>
 <section class="panel">
  <h2 class="stitle">PLAYERS <span id="playerCount"></span></h2>
  <ul id="playerList" class="player-list"></ul>
  <p id="lobbyMessage" class="small">Waiting for players…</p>
  <button id="startBtn" class="btn primary hidden">⚡ START GAME</button>
  <button id="leaveBtn" class="btn secondary">Leave room</button>
 </section>
</main>

<main id="game" class="screen hidden">
 <header class="game-header"><div class="mini">CIRCUIT <span class="green">CLASH</span></div><div id="roundLabel" class="round">ROUND 1 / 10</div></header>
 <div class="progress"><div id="progressFill"></div></div>
 <section class="panel">
  <div id="topic" class="topic">ELECTRONICS</div>
  <h2 id="question" class="question">Loading question…</h2>
  <div class="timer-row"><div id="timer" class="timer">25</div><span id="timerMessage">Answer before time runs out</span></div>
  <div id="answerGrid" class="answer-grid"></div>
  <div id="answerNotice" class="notice">Choose your answer. You can answer only once.</div>
 </section>
 <section class="panel">
  <h2 class="stitle">ANSWER STATUS</h2><p id="answeredCount" class="small">0 of 0 players answered</p>
 </section>
</main>

<main id="reveal" class="screen hidden">
 <header class="game-header"><div class="mini">CIRCUIT <span class="green">CLASH</span></div><div id="revealRound" class="round">ROUND 1 / 10</div></header>
 <section class="panel">
  <div class="topic">CORRECT ANSWER</div>
  <h2 id="revealQuestion" class="question"></h2>
  <div id="correctAnswer" class="notice" style="border-color:#42ff9e66;color:var(--green);font-weight:900;font-size:15px"></div>
  <div id="whyText" class="notice"></div>
 </section>
 <section class="panel">
  <h2 class="stitle">POINTS THIS ROUND</h2><div id="roundPoints"></div>
 </section>
 <section class="panel">
  <h2 class="stitle">LIVE LEADERBOARD</h2><div id="revealLeaderboard"></div>
 </section>
 <p id="autoNext" class="small center"></p>
 <button id="nextBtn" class="btn primary hidden">NEXT ROUND →</button>
</main>

<main id="final" class="screen hidden">
 <header class="brand"><div class="chip">⚡</div><h1>DUEL <span>COMPLETE</span></h1><div class="subtitle">FINAL RESULTS · 10 ROUNDS</div></header>
 <section class="panel result-hero"><div class="trophy">🏆</div><div id="winner" class="winner">Winner!</div><p id="winnerSubtitle" class="small"></p></section>
 <section class="panel"><h2 class="stitle">FINAL LEADERBOARD</h2><div id="finalLeaderboard"></div></section>
 <section class="panel"><h2 class="stitle">PERFORMANCE REPORT</h2>
  <div id="finalStats"></div>
  <div class="stat"><span>Fastest correct response</span><strong id="fastest">—</strong></div>
  <div class="stat"><span>Questions played</span><strong>10 / 10</strong></div>
 </section>
 <section class="panel"><h2 class="stitle">ROUND REVIEW</h2><div id="history"></div></section>
 <button id="playAgainBtn" class="btn primary hidden">↻ PLAY AGAIN</button>
 <button id="homeBtn" class="btn secondary">Back to Home</button>
</main>

<div id="toast" class="hidden" role="status"></div>

<script type="module">
import { initializeApp } from "https://www.gstatic.com/firebasejs/13.1.0/firebase-app.js";
import {
 getDatabase, ref, set, update, get, onValue, onDisconnect,
 serverTimestamp, runTransaction
} from "https://www.gstatic.com/firebasejs/13.1.0/firebase-database.js";

/* =========================================================
   FIREBASE CONFIG — your supplied project
   ========================================================= */
const firebaseConfig = {
 apiKey:"AIzaSyDJHWQV-TwOQ3Xi5U96SZqdnFCwRr2dM3A",
 authDomain:"circuit-clash-9d903.firebaseapp.com",
 databaseURL:"https://circuit-clash-9d903-default-rtdb.asia-southeast1.firebasedatabase.app",
 projectId:"circuit-clash-9d903",
 storageBucket:"circuit-clash-9d903.firebasestorage.app",
 messagingSenderId:"242249477222",
 appId:"1:242249477222:web:9b3cd3a3a2d43e35ff11a7"
};
const app=initializeApp(firebaseConfig);
const db=getDatabase(app);
const $=id=>document.getElementById(id);
const TOTAL=10, SECONDS=25, MAX_PLAYERS=6;
const CODE_CHARS="ABCDEFGHJKLMNPQRSTUVWXYZ"; // no O, I, 0 or 1
const COLORS=["#42ff9e","#39c8ff","#ff7a59","#d78bff","#ffe47a","#ff78b5"];
const state={
 roomCode:null, playerId:null, isHost:false, myName:"",
 room:null, serverOffset:0, connected:false, screen:"home",
 roomUnsub:null, infoUnsub:null, offsetUnsub:null, tick:null,
 resolveBusy:false, resolvingRound:null, autoRound:null,
 toastTimer:null, audio:null, ended:false, joining:false
};

/* =========================================================
   QUESTIONS — EDIT THIS ARRAY TO CHANGE THE QUIZ.
   Fields: topic, q, options (four choices), correct (0–3), why.
   The game selects 10 distinct questions each game.
   ========================================================= */
const QUESTIONS=[
["Resistor Colour Code","In a 4-band resistor, what digit does RED represent?",["1","2","3","4"],1,"The colour sequence starts Black 0, Brown 1, Red 2, Orange 3, Yellow 4."],
["Resistor Colour Code","What is the multiplier for the GOLD band?",["× 0.1","× 1","× 10","× 0.01"],0,"Gold is a multiplier of 0.1."],
["Resistor Colour Code","What is Brown–Black–Red–Gold?",["100 Ω","1 kΩ","10 kΩ","100 kΩ"],1,"Brown = 1, Black = 0, Red = ×100. So 10 × 100 = 1,000 Ω. Gold means ±5%."],
["Resistor Colour Code","Which colour represents digit 5?",["Green","Blue","Violet","Grey"],0,"Green = 5, Blue = 6, Violet = 7, Grey = 8, White = 9."],
["Resistor Colour Code","What tolerance does a GOLD band indicate?",["±1%","±2%","±5%","±10%"],2,"Gold indicates ±5% tolerance; silver indicates ±10%."],
["Resistor Colour Code","What is Red–Red–Brown–Gold?",["22 Ω","220 Ω","2.2 kΩ","22 kΩ"],1,"22 × 10 = 220 Ω."],
["Resistor Colour Code","Which colour represents zero?",["Brown","Black","Silver","White"],1,"Black represents digit 0."],
["Resistor Colour Code","What is Yellow–Violet–Orange?",["47 Ω","470 Ω","4.7 kΩ","47 kΩ"],3,"Yellow = 4, Violet = 7, Orange = ×1,000; the result is 47 kΩ."],
["Ohm's Law","What is Ohm's law?",["V = IR","P = I/R","I = VR","R = VI"],0,"Voltage equals current multiplied by resistance: V = IR."],
["Ohm's Law","A 12 V supply is connected across 6 Ω. What current flows?",["0.5 A","2 A","6 A","72 A"],1,"I = V/R = 12/6 = 2 A."],
["Ohm's Law","A current of 3 A flows through 4 Ω. Find voltage.",["0.75 V","7 V","12 V","16 V"],2,"V = IR = 3 × 4 = 12 V."],
["Ohm's Law","What is the SI unit of resistance?",["Ampere","Volt","Watt","Ohm"],3,"Resistance is measured in ohms (Ω)."],
["Ohm's Law","Two 10 Ω resistors are connected in series. Total resistance?",["5 Ω","10 Ω","20 Ω","100 Ω"],2,"Series resistances add: 10 + 10 = 20 Ω."],
["Ohm's Law","Two 10 Ω resistors are connected in parallel. Total resistance?",["5 Ω","10 Ω","20 Ω","100 Ω"],0,"Two equal resistors in parallel have half the resistance: 5 Ω."],
["Ohm's Law","What is power when V = 10 V and I = 2 A?",["5 W","12 W","20 W","100 W"],2,"P = VI = 10 × 2 = 20 W."],
["Ohm's Law","A 1 kΩ resistor has 5 V across it. Find current.",["5 mA","50 mA","500 mA","5 A"],0,"I = 5/1,000 A = 5 mA."],
["Logic Gates","An AND gate outputs 1 when:",["Any input is 1","All inputs are 1","All inputs are 0","Inputs differ"],1,"An AND gate outputs HIGH only when every input is HIGH."],
["Logic Gates","What is a NOT gate output when input is 1?",["1","0","Undefined","Alternating 0 and 1"],1,"A NOT gate inverts its input."],
["Logic Gates","An OR gate receives inputs 0 and 1. Its output is:",["0","1","High impedance","Invalid"],1,"An OR gate outputs 1 if at least one input is 1."],
["Logic Gates","Which gate is called a universal gate?",["XOR only","AND only","NAND","Buffer"],2,"Any Boolean function can be built using NAND gates alone."],
["Logic Gates","An XOR gate outputs 1 when:",["Both inputs are 0","Both inputs are 1","Inputs differ","Inputs are identical"],2,"XOR outputs HIGH when its inputs differ."],
["Logic Gates","What is the output of NOR for inputs 0 and 0?",["0","1","Both 0 and 1","Cannot be determined"],1,"OR(0,0) = 0; NOR inverts it to 1."],
["Logic Gates","For a 2-input AND gate, what is 1 AND 0?",["0","1","2","Undefined"],0,"Both inputs must be 1 for an AND gate to output 1."],
["Logic Gates","Which gate complements an AND gate?",["XOR","NAND","NOR","XNOR"],1,"NAND means NOT-AND."],
["Diodes","What is the main function of a rectifier diode?",["Store charge","Allow current mainly in one direction","Amplify every signal","Measure temperature"],1,"A conventional diode conducts mainly when forward biased and blocks reverse current within its ratings."],
["Diodes","Approximate forward voltage of a silicon diode?",["0.1 V","0.7 V","5 V","12 V"],1,"A silicon diode commonly drops around 0.6–0.7 V; the exact value varies."],
["Diodes","What does an LED do?",["Emits light","Measures resistance","Stores magnetic energy","Amplifies without power"],0,"An LED emits light when forward current flows."],
["Diodes","Which diode is commonly used for voltage regulation?",["Photodiode","Zener diode","LED","Tunnel-free resistor"],1,"A Zener diode maintains an approximately specified reverse voltage in its breakdown region."],
["Transistors","What are the three terminals of a BJT?",["Gate, drain, source","Anode, cathode, gate","Emitter, base, collector","Input, output, ground"],2,"A BJT has emitter, base and collector terminals."],
["Transistors","Which terminal controls BJT collector current?",["Base","Heat sink","Case","Insulator"],0,"In active operation, base current controls a larger collector current."],
["Transistors","Which component is often used as an electronic switch?",["Transistor","Fuse only","Transformer core","Resistor alone"],0,"A transistor can be driven between off and on states to perform switching."],
["Transistors","What is the full form of MOSFET?",["Metal Oxide Semiconductor Field Effect Transistor","Magnetic Output Signal Frequency Electronic Tool","Modulated Oscillator Signal Feedback Electronic Transmitter","Metal Output Switching Frequency Element Type"],0,"MOSFET stands for Metal-Oxide-Semiconductor Field-Effect Transistor."],
["Temperature Sensors","A thermocouple works mainly on which effect?",["Hall effect","Seebeck effect","Piezoelectric effect","Photoelectric effect"],1,"A temperature difference between dissimilar conductors produces thermoelectric voltage through the Seebeck effect."],
["Temperature Sensors","What does an RTD measure?",["Pressure","Light intensity","Temperature","Magnetic field"],2,"An RTD measures temperature through a predictable change in metal resistance."],
["Temperature Sensors","Which material is used in a Pt100 RTD?",["Copper oxide","Platinum","Silicon rubber","Carbon paper"],1,"Pt100 uses platinum."],
["Temperature Sensors","What is the nominal resistance of a Pt100 at 0°C?",["10 Ω","50 Ω","100 Ω","1,000 Ω"],2,"Pt100 has a nominal resistance of 100 Ω at 0°C."],
["Strain Gauges","What does a strain gauge measure?",["Mechanical strain","Sound frequency only","Battery voltage only","Colour"],0,"A strain gauge detects deformation through changes in electrical resistance."],
["Strain Gauges","Mechanical strain in a strain gauge commonly changes:",["Resistance","Atomic number","Gravity","Magnetic pole count"],0,"Strain changes the gauge's geometry and resistivity, causing a resistance change."],
["Sensors","Which sensor is commonly used to detect light?",["LDR","RTD","Strain gauge","Thermocouple"],0,"An LDR typically decreases in resistance as light intensity increases."],
["Sensors","Which device commonly detects magnetic fields?",["Hall-effect sensor","Thermocouple","LDR","Pt100"],0,"A Hall sensor detects magnetic fields using the Hall effect."],
["Instrumentation","What is the SI unit of electric current?",["Volt","Ampere","Ohm","Farad"],1,"The ampere (A) is the SI base unit of electric current."],
["Instrumentation","Which instrument measures voltage?",["Ammeter","Voltmeter","Wattmeter only","Ohmmeter only"],1,"A voltmeter measures potential difference and is connected in parallel."],
["Instrumentation","How should an ideal ammeter be connected?",["In series","In parallel across the supply","Across an open switch","Without a complete circuit"],0,"An ammeter is connected in series so circuit current passes through it."],
["Instrumentation","What is the purpose of a Wheatstone bridge?",["Generate light","Measure unknown resistance","Convert AC into light","Store programs"],1,"An unknown resistance can be found by balancing the bridge circuit."],
["Instrumentation","What does ADC stand for?",["Automatic Diode Control","Analog-to-Digital Converter","Alternating Drive Circuit","Amplified Data Coil"],1,"An ADC converts an analog signal into a digital representation."],
["Instrumentation","What is an operational amplifier used for?",["Amplify the difference between two input voltages","Measure temperature without a sensor","Generate force only","Replace all resistors"],0,"An op-amp amplifies the difference between its inputs, subject to its configuration."],
["Instrumentation","What does calibration compare?",["An instrument against a reference standard","A battery against resistor colour","Two unrelated boards","Only physical size"],0,"Calibration establishes the relationship between readings and a known reference."],
["Instrumentation","Which unit is used for capacitance?",["Henry","Farad","Tesla","Weber"],1,"Capacitance is measured in farads (F)."],
["Instrumentation","What does sensitivity describe in an instrument?",["Output change per input change","Physical weight only","Number of switches","Cable length"],0,"Sensitivity describes output change for a given change in measured input."],
["Instrumentation","Which instrument displays voltage changing over time?",["Oscilloscope","Fixed resistor","Fuse","Potentiometer alone"],0,"An oscilloscope displays electrical signals, commonly voltage versus time."],
["Instrumentation","What does a low-pass filter do?",["Passes low frequencies and attenuates high frequencies","Passes only high frequencies","Converts DC into mechanical energy","Increases all frequencies equally"],0,"A low-pass filter passes lower frequencies more readily than higher frequencies."],
["Instrumentation","What is the common unit of frequency?",["Ohm","Hertz","Coulomb","Volt"],1,"Frequency is measured in hertz (Hz), or cycles per second."]
].map(([topic,q,options,correct,why])=>({topic,q,options,correct,why}));

/* ---------- Utility, UI, sound ---------- */
function toast(message){
 const el=$("toast");el.textContent=message;el.classList.remove("hidden");
 clearTimeout(state.toastTimer);state.toastTimer=setTimeout(()=>el.classList.add("hidden"),4000);
}
function showScreen(name){
 state.screen=name;
 ["home","lobby","game","reveal","final"].forEach(id=>$(id).classList.toggle("hidden",id!==name));
 window.scrollTo(0,0);
}
function cleanName(value){
 return String(value||"").replace(/[<>]/g,"").replace(/\s+/g," ").trim().slice(0,18);
}
function safeCode(value){return String(value||"").toUpperCase().replace(/[^A-Z]/g,"").replace(/[OI]/g,"").slice(0,4)}
function serverNow(){return Date.now()+state.serverOffset}
function randomId(){return "p_"+crypto.randomUUID().replaceAll("-","")}
function randomCode(){return Array.from({length:4},()=>CODE_CHARS[Math.floor(Math.random()*CODE_CHARS.length)]).join("")}
function shuffle(a){const b=[...a];for(let i=b.length-1;i>0;i--){const j=Math.floor(Math.random()*(i+1));[b[i],b[j]]=[b[j],b[i]]}return b}
function playTone(kind){
 try{
  const AC=window.AudioContext||window.webkitAudioContext;if(!AC)return;
  state.audio ||= new AC();const c=state.audio;if(c.state==="suspended")c.resume();
  const o=c.createOscillator(),g=c.createGain();o.connect(g);g.connect(c.destination);
  const t=c.currentTime;
  if(kind==="correct"){o.frequency.setValueAtTime(660,t);o.frequency.setValueAtTime(880,t+.09);g.gain.setValueAtTime(.1,t);g.gain.exponentialRampToValueAtTime(.001,t+.22);o.start(t);o.stop(t+.23)}
  else{o.type="triangle";o.frequency.setValueAtTime(kind==="wrong"?240:440,t);g.gain.setValueAtTime(.08,t);g.gain.exponentialRampToValueAtTime(.001,t+.16);o.start(t);o.stop(t+.17)}
 }catch{}
}
function setConnection(connected){
 state.connected=connected;
 $("connectionDot").className="dot "+(connected?"on":"off");
 $("connectionText").textContent=connected?"Connected to game server":"Offline — checking connection…";
}
onValue(ref(db,".info/connected"),snap=>setConnection(snap.val()===true),()=>setConnection(false));
state.offsetUnsub=onValue(ref(db,".info/serverTimeOffset"),snap=>{state.serverOffset=Number(snap.val())||0});
let connectionTimer=setTimeout(()=>{if(!state.connected){$("connectionText").textContent="Firebase unreachable. Check internet and database rules.";toast("Cannot connect to Firebase. Check internet and try again.")}},15000);

/* ---------- Room lifecycle ---------- */
function stopRoomListener(){
 if(state.roomUnsub){state.roomUnsub();state.roomUnsub=null}
 clearInterval(state.tick);state.tick=null;clearTimeout(state.autoRound);state.autoRound=null;
}
function resetSession(){
 stopRoomListener();
 state.roomCode=null;state.playerId=null;state.isHost=false;state.room=null;
 state.ended=false;state.joining=false;state.resolveBusy=false;state.resolvingRound=null;
}
function roomRef(){return ref(db,"rooms/"+state.roomCode)}
function playerRef(id=state.playerId){return ref(db,`rooms/${state.roomCode}/players/${id}`)}
function answersRef(){return ref(db,`rooms/${state.roomCode}/answers`)}
function normalizeRoom(room){
 if(!room||typeof room!=="object")return null;
 if(!room.players||typeof room.players!=="object")room.players={};
 if(!room.scores||typeof room.scores!=="object")room.scores={};
 if(!room.answers||typeof room.answers!=="object")room.answers={};
 if(!Array.isArray(room.history))room.history=[];
 return room;
}
function listenRoom(){
 stopRoomListener();
 state.roomUnsub=onValue(roomRef(),snap=>{
  if(!snap.exists()){
   if(state.roomCode&&!state.isHost&&!state.ended){
    state.ended=true;toast("Host left, game ended.");
    stopRoomListener();showScreen("home");
    $("lobbyMessage").textContent="Host left, game ended.";
   }else if(state.roomCode&&state.isHost&&!state.ended){
    state.ended=true;showScreen("home");
   }
   return;
  }
  const room=normalizeRoom(snap.val());if(!room)return;
  state.room=room;
  if(room.status==="ended"){state.ended=true;showScreen("home");toast("Host left, game ended.");return}
  renderRoom();
  if(state.isHost&&room.status==="playing")maybeResolveRound(room);
 },error=>{
  console.error(error);toast("Could not read room. Check Firebase rules and internet.");
 });
}
async function makeRoom(){
 if(!state.connected){toast("Wait until Firebase is connected.");return}
 if(state.joining)return;
 const name=cleanName($("nameInput").value);if(!name){toast("Enter your name first.");$("nameInput").focus();return}
 if(QUESTIONS.length<TOTAL){toast("Add at least 10 questions.");return}
 state.joining=true;$("createBtn").disabled=true;
 try{
  let code=null;
  for(let i=0;i<12;i++){const candidate=randomCode();const s=await get(ref(db,"rooms/"+candidate));if(!s.exists()){code=candidate;break}}
  if(!code)throw new Error("Could not find an unused room code. Try again.");
  state.roomCode=code;state.playerId=randomId();state.isHost=true;state.myName=name;
  const player={id:state.playerId,name,color:COLORS[0],host:true,connected:true,joinedAt:serverTimestamp()};
  const room={
   status:"lobby",hostId:state.playerId,createdAt:serverTimestamp(),
   players:{[state.playerId]:player},scores:{[state.playerId]:0},answers:{},history:[],
   roundIndex:0,roundOrder:[],startTime:null,deadline:null,reveal:null,fastest:null
  };
  await set(roomRef(),room);
  await onDisconnect(roomRef()).remove();
  listenRoom();showScreen("lobby");toast("Room created! Share your code.");
 }catch(e){console.error(e);resetSession();toast("Room creation failed: "+(e.message||"check Firebase rules"))}
 finally{state.joining=false;$("createBtn").disabled=false}
}
async function joinRoom(){
 if(!state.connected){toast("Wait until Firebase is connected.");return}
 if(state.joining)return;
 const name=cleanName($("nameInput").value);const code=safeCode($("codeInput").value);
 if(!name){toast("Enter your name first.");$("nameInput").focus();return}
 if(code.length!==4){toast("Enter a valid four-letter room code.");return}
 state.joining=true;$("joinBtn").disabled=true;
 try{
  state.roomCode=code;state.isHost=false;state.myName=name;
  const root=roomRef();let snap=await get(root);
  if(!snap.exists())throw new Error("Room not found. Check the code and retry.");
  let room=snap.val();
  if(room.status!=="lobby")throw new Error("This game has already started. Ask the host for a new lobby.");
  const oldPlayers=room.players||{};
  // On refresh, reuse the current tab's player ID when it is still registered.
  let id=null;
  const previousId=state.playerId;
  if(previousId&&oldPlayers[previousId])id=previousId;
  if(!id){
   const same=Object.values(oldPlayers).find(p=>p&&p.name===name&&p.connected===false);
   if(same)id=same.id;
  }
  if(!id)id=randomId();
  // Transaction prevents two guests taking the same last slot.
  let failure=null;
  const tx=await runTransaction(root,current=>{
   if(!current||current.status!=="lobby"){failure="Game already started.";return}
   current.players ||= {};current.scores ||= {};
   if(!current.players[id]){
    const count=Object.keys(current.players).length;
    if(count>=MAX_PLAYERS){failure="Room is full (maximum 6 players).";return}
    let unique=name,n=2;
    const names=new Set(Object.values(current.players).map(p=>String(p?.name||"").toLowerCase()));
    while(names.has(unique.toLowerCase())){unique=`${name} ${n++}`}
    current.players[id]={id,name:unique,color:COLORS[count%COLORS.length],host:false,connected:true,joinedAt:Date.now()};
    current.scores[id]=0;
   }else{current.players[id].connected=true}
   return current;
  },{applyLocally:false});
  if(!tx.committed||!tx.snapshot.exists())throw new Error(failure||"Could not join this room. Retry.");
  state.playerId=id;state.myName=tx.snapshot.val().players[id].name;
  await onDisconnect(playerRef()).update({connected:false});
  listenRoom();showScreen("lobby");toast("Joined room "+code);
 }catch(e){console.error(e);stopRoomListener();state.roomCode=null;state.isHost=false;showScreen("home");toast(e.message||"Could not join room. Try again.")}
 finally{state.joining=false;$("joinBtn").disabled=false}
}
async function markDisconnected(){
 if(!state.roomCode||!state.playerId)return;
 try{
  if(state.isHost){state.ended=true;await set(roomRef(),null)}
  else await update(playerRef(),{connected:false});
 }catch(e){console.warn("Disconnect cleanup:",e)}
}
async function leaveRoom(){
 const wasHost=state.isHost;
 try{
  if(state.roomCode){
   if(wasHost){state.ended=true;await set(roomRef(),null)}
   else await update(playerRef(),{connected:false});
  }
 }catch(e){console.warn(e)}
 resetSession();showScreen("home");
}
function renderRoom(){
 const r=state.room;if(!r)return;
 if(r.status==="lobby"){renderLobby(r);showScreen("lobby")}
 else if(r.status==="playing"){renderQuestion(r);showScreen("game")}
 else if(r.status==="reveal"){renderReveal(r);showScreen("reveal")}
 else if(r.status==="final"){renderFinal(r);showScreen("final")}
}
function renderLobby(r){
 $("roomCode").textContent=state.roomCode;
 const link=inviteLink();$("copyBtn").disabled=false;
 const list=$("playerList");list.replaceChildren();
 const players=Object.values(r.players||{}).filter(p=>p&&typeof p.name==="string");
 players.sort((a,b)=>a.id===r.hostId?-1:b.id===r.hostId?1:0);
 $("playerCount").textContent=`(${players.length}/${MAX_PLAYERS})`;
 players.forEach(p=>{
  const li=document.createElement("li"),av=document.createElement("div"),details=document.createElement("div"),name=document.createElement("div"),tag=document.createElement("div");
  av.className="avatar";av.style.borderBottom="3px solid "+(p.color||COLORS[0]);av.textContent=p.name.slice(0,1).toUpperCase();
  name.className="pname";name.textContent=p.name;tag.className="tag";tag.textContent=p.id===r.hostId?"HOST · ROOM LEADER":(p.connected===false?"DISCONNECTED":"PLAYER");
  details.append(name,tag);li.append(av,details);list.append(li);
 });
 const start=$("startBtn");start.classList.toggle("hidden",!state.isHost);
 start.disabled=players.filter(p=>p.connected!==false).length<2;
 $("lobbyMessage").textContent=players.filter(p=>p.connected!==false).length<2?"Waiting for at least one more connected player…":(state.isHost?"Ready! Start when everyone has joined.":"Waiting for the host to start…");
}
function inviteLink(){const u=new URL(location.href);u.searchParams.set("room",state.roomCode);return u.toString()}
async function copyInvite(){
 try{await navigator.clipboard.writeText(inviteLink());toast("Invite link copied!")}
 catch{prompt("Copy this invite link:",inviteLink())}
}
async function shareInvite(){
 if(navigator.share){try{await navigator.share({title:"Join Circuit Clash",text:"Join my electronics quiz game! Room "+state.roomCode,url:inviteLink()})}catch(e){if(e.name!=="AbortError")copyInvite()}}
 else copyInvite();
}

/* ---------- Host controls: game start and round authority ---------- */
async function startGame(){
 const r=state.room;if(!state.isHost||!r||r.status!=="lobby")return;
 const players=Object.values(r.players||{}).filter(p=>p&&p.connected!==false);
 if(players.length<2){toast("At least 2 connected players are required.");return}
 const order=shuffle(QUESTIONS).slice(0,TOTAL);
 const scores={};players.forEach(p=>scores[p.id]=0);
 try{
  await update(roomRef(),{
   status:"playing",roundIndex:0,roundOrder:order,
   answers:{},scores,history:[],fastest:null,reveal:null,
   startTime:serverNow(),deadline:serverNow()+SECONDS*1000
  });
  playTone("start");
 }catch(e){toast("Could not start the game. Check your connection.")}
}
function connectedPlayers(r){return Object.values(r.players||{}).filter(p=>p&&p.connected!==false)}
function currentQuestion(r){return Array.isArray(r.roundOrder)?r.roundOrder[r.roundIndex]:null}
function renderQuestion(r){
 const q=currentQuestion(r);if(!q||!Array.isArray(q.options)||q.options.length!==4)return;
 $("roundLabel").textContent=`ROUND ${r.roundIndex+1} / ${TOTAL}`;
 $("progressFill").style.width=`${r.roundIndex/TOTAL*100}%`;
 $("topic").textContent=q.topic;$("question").textContent=q.q;
 const mine=(r.answers||{})[state.playerId];
 const grid=$("answerGrid");grid.replaceChildren();
 q.options.forEach((option,i)=>{
  const b=document.createElement("button");b.className="answer";b.type="button";b.disabled=!!mine;
  const l=document.createElement("span");l.className="letter";l.textContent=String.fromCharCode(65+i);
  const t=document.createElement("span");t.textContent=option;b.append(l,t);
  if(mine&&mine.choice===i)b.classList.add("chosen");
  b.addEventListener("click",()=>submitMyAnswer(i));grid.append(b);
 });
 $("answerNotice").textContent=mine?"✓ Answer submitted. Waiting for the other players…":"Choose your answer. You can answer only once.";
 $("timerMessage").textContent=mine?"Answer locked — waiting for others":"Answer before time runs out";
 $("answeredCount").textContent=`${Object.keys(r.answers||{}).filter(id=>connectedPlayers(r).some(p=>p.id===id)).length} of ${connectedPlayers(r).length} players answered`;
 if(!state.tick)state.tick=setInterval(updateCountdown,100);
 updateCountdown();
}
function updateCountdown(){
 const r=state.room;if(!r||r.status!=="playing")return;
 const remain=Math.max(0,(Number(r.deadline)||serverNow())-serverNow());
 $("timer").textContent=Math.ceil(remain/1000);
 $("timer").classList.toggle("urgent",remain<=3000);
 if(remain<=0&&state.isHost)maybeResolveRound(r);
}
async function submitMyAnswer(choice){
 const r=state.room;if(!r||r.status!=="playing")return;
 const q=currentQuestion(r);if(!q||!Number.isInteger(choice)||choice<0||choice>3)return;
 if((r.answers||{})[state.playerId])return;
 if(serverNow()>Number(r.deadline)){toast("Time is up!");return}
 try{
  // One answer per player per round. Timestamp is assigned by Firebase.
  await set(ref(db,`rooms/${state.roomCode}/answers/${state.playerId}`),{
   choice,submittedAt:serverTimestamp()
  });
  playTone("start");
 }catch(e){toast("Answer was not sent. Check your connection.")}
}
async function maybeResolveRound(r){
 if(!state.isHost||!r||r.status!=="playing"||state.resolveBusy)return;
 const idx=r.roundIndex;
 if(state.resolvingRound===idx)return;
 const players=connectedPlayers(r),answers=r.answers||{};
 const allAnswered=players.length>0&&players.every(p=>answers[p.id]&&Number.isFinite(Number(answers[p.id].submittedAt)));
 if(!allAnswered&&serverNow()<Number(r.deadline))return;
 state.resolveBusy=true;state.resolvingRound=idx;
 try{
  // Re-read the latest answers before the host publishes the reveal.
  const snap=await get(roomRef());if(!snap.exists())return;
  const latest=normalizeRoom(snap.val());
  if(latest.status!=="playing"||latest.roundIndex!==idx)return;
  const q=currentQuestion(latest);if(!q)return;
  const now=serverNow(),all=latest.answers||{},scores={...(latest.scores||{})};
  const results={},newFastest=latest.fastest?{...latest.fastest}:null;
  const active=connectedPlayers(latest);
  for(const p of Object.values(latest.players||{})){
   if(!p||!p.id)continue;
   const a=all[p.id];
   let choice=null,correct=false,points=0,elapsed=SECONDS;
   if(a&&Number.isInteger(a.choice)&&a.choice>=0&&a.choice<4&&Number.isFinite(Number(a.submittedAt))){
    choice=a.choice;elapsed=Math.max(0,(Number(a.submittedAt)-Number(latest.startTime))/1000);
    if(elapsed<=SECONDS&&elapsed>=0&&choice===q.correct){
     correct=true;
     // 100 points at 0s; 20 points at the 25-second deadline.
     points=Math.round(100-80*Math.min(1,elapsed/SECONDS));
     scores[p.id]=(Number(scores[p.id])||0)+points;
     if(!newFastest||elapsed<newFastest.elapsed)newFastest={playerId:p.id,elapsed,round:idx+1};
    }
   }
   results[p.id]={choice,correct,points,elapsed,timeout:!a};
  }
  const history=[...(latest.history||[]),{
   round:idx+1,topic:q.topic,question:q.q,options:q.options,
   correct:q.correct,why:q.why,results
  }];
  const reveal={round:idx+1,question:q.q,topic:q.topic,options:q.options,correct:q.correct,why:q.why,results,at:now};
  await update(roomRef(),{status:"reveal",scores,history,fastest:newFastest,reveal,answers:all});
 }catch(e){console.error(e);toast("Could not reveal this round. Check connection.")}
 finally{state.resolveBusy=false}
}

/* ---------- Reveal and progression ---------- */
function orderedPlayers(r){
 return Object.values(r.players||{}).filter(p=>p&&p.id).sort((a,b)=>(Number(r.scores?.[b.id])||0)-(Number(r.scores?.[a.id])||0)||a.name.localeCompare(b.name));
}
function addLeaderboard(container,r,roundOnly=false){
 container.replaceChildren();
 orderedPlayers(r).forEach((p,i)=>{
  const row=document.createElement("div");row.className="leader";
  const rank=document.createElement("div");rank.className="rank";rank.textContent=["🥇","🥈","🥉"][i]||String(i+1);
  const name=document.createElement("div");name.className="pname";name.textContent=p.name;
  const score=document.createElement("div");score.className="score spacer";score.style.textAlign="right";
  score.style.color=p.color||"var(--green)";
  score.textContent=roundOnly?`+${r.reveal?.results?.[p.id]?.points||0} pts`:`${Number(r.scores?.[p.id])||0} pts`;
  row.append(rank,name,score);container.append(row);
 });
}
function renderReveal(r){
 const v=r.reveal;if(!v)return;
 $("revealRound").textContent=`ROUND ${v.round} / ${TOTAL}`;
 $("revealQuestion").textContent=v.question;
 $("correctAnswer").textContent=String.fromCharCode(65+v.correct)+". "+v.options[v.correct];
 $("whyText").textContent="WHY THIS IS CORRECT: "+v.why;
 addLeaderboard($("roundPoints"),r,true);addLeaderboard($("revealLeaderboard"),r);
 $("nextBtn").classList.toggle("hidden",!state.isHost);
 $("nextBtn").textContent=v.round===TOTAL?"VIEW RESULTS →":"NEXT ROUND →";
 if(state.isHost){
  clearTimeout(state.autoRound);
  const delay=Math.max(0,8000-(serverNow()-(Number(v.at)||serverNow())));
  $("autoNext").textContent=`Automatically continuing in ${Math.ceil(delay/1000)} seconds…`;
  state.autoRound=setTimeout(()=>advanceRound(),delay);
 }else $("autoNext").textContent="Waiting for the host to continue (or auto-advance in 8 seconds)…";
}
async function advanceRound(){
 const r=state.room;if(!state.isHost||!r||r.status!=="reveal")return;
 clearTimeout(state.autoRound);
 if(r.roundIndex>=TOTAL-1){await update(roomRef(),{status:"final"});return}
 await update(roomRef(),{
  status:"playing",roundIndex:r.roundIndex+1,answers:{},reveal:null,
  startTime:serverNow(),deadline:serverNow()+SECONDS*1000
 });
}
function renderFinal(r){
 const players=orderedPlayers(r);
 $("winner").textContent=players.length?(players.length>1&&Number(r.scores?.[players[0].id])===Number(r.scores?.[players[1].id])?"It's a Draw!":players[0].name+" Wins!"):"Game complete";
 $("winnerSubtitle").textContent=players.length?`${Number(r.scores?.[players[0].id])||0} points · Thanks for playing!`:"Thanks for playing!";
 addLeaderboard($("finalLeaderboard"),r);
 const stats=$("finalStats");stats.replaceChildren();
 for(const p of players){
  const correct=(r.history||[]).filter(h=>h.results?.[p.id]?.correct).length;
  const line=document.createElement("div");line.className="stat";
  const a=document.createElement("span");a.textContent=p.name+" · correct answers";
  const b=document.createElement("strong");b.textContent=`${correct} / ${TOTAL}`;
  line.append(a,b);stats.append(line);
 }
 const f=r.fastest;
 $("fastest").textContent=f?`${r.players?.[f.playerId]?.name||"Player"} · ${Number(f.elapsed).toFixed(2)}s (R${f.round})`:"No correct answers";
 const hist=$("history");hist.replaceChildren();
 (r.history||[]).forEach(h=>{
  const item=document.createElement("div");item.className="review";
  const title=document.createElement("strong");title.textContent=`${h.round}. ${h.topic}`;
  const q=document.createElement("div");q.textContent=h.question;
  const answer=document.createElement("div");answer.style.color="var(--green)";answer.textContent="Correct: "+h.options[h.correct];
  item.append(title,q,answer);
  for(const p of players){
   const res=h.results?.[p.id];const line=document.createElement("div");
   line.style.color="var(--muted)";
   line.textContent=`${p.name}: ${res?.correct?"Correct":"No point"} · +${res?.points||0} pts`;
   item.append(line);
  }
  const why=document.createElement("div");why.textContent=h.why;item.append(why);hist.append(item);
 });
 $("playAgainBtn").classList.toggle("hidden",!state.isHost);
}

/* ---------- Replay and navigation ---------- */
async function playAgain(){
 const r=state.room;if(!state.isHost||!r||r.status!=="final")return;
 const scores={};Object.keys(r.players||{}).forEach(id=>scores[id]=0);
 await update(roomRef(),{
  status:"lobby",scores,answers:{},history:[],roundIndex:0,roundOrder:[],
  startTime:null,deadline:null,reveal:null,fastest:null
 });
 toast("New game ready! Share the same room code.");
}
function home(){
 resetSession();showScreen("home");
}
$("createBtn").addEventListener("click",makeRoom);
$("joinBtn").addEventListener("click",joinRoom);
$("startBtn").addEventListener("click",startGame);
$("copyBtn").addEventListener("click",copyInvite);
$("shareBtn").addEventListener("click",shareInvite);
$("leaveBtn").addEventListener("click",leaveRoom);
$("nextBtn").addEventListener("click",advanceRound);
$("playAgainBtn").addEventListener("click",playAgain);
$("homeBtn").addEventListener("click",home);
$("codeInput").addEventListener("input",e=>{e.target.value=safeCode(e.target.value)});
$("nameInput").addEventListener("keydown",e=>{if(e.key==="Enter")makeRoom()});
$("codeInput").addEventListener("keydown",e=>{if(e.key==="Enter")joinRoom()});

// Auto-fill room code from an invite URL such as ?room=ABCD.
const queryRoom=new URLSearchParams(location.search).get("room");
if(queryRoom)$("codeInput").value=safeCode(queryRoom);

// Keep room state in Firebase, not localStorage. A host disconnect removes
// the room via onDisconnect. Guests mark themselves disconnected but retain
// their player record so a refresh/rejoin can preserve their score.
window.addEventListener("pagehide",()=>{
 if(state.roomCode&&state.isHost){
  // Firebase onDisconnect is the reliable fallback when a tab closes.
 }else if(state.roomCode&&state.playerId){
  // The registered onDisconnect handler marks the guest disconnected.
 }
});
window.addEventListener("online",()=>toast("Internet connection restored."));
window.addEventListener("offline",()=>toast("You are offline. Reconnect to continue."));
</script>
</body>
</html>
