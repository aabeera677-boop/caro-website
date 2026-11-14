<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#090611">
<meta name="description" content="CARO Technologies — Connecting All Regions Online.">
<title>CARO Technologies | Official Website</title>

<style>
:root{
--bg:#090611;
--panel:#151020;
--purple:#8b5cf6;
--light:#bd9aff;
--silver:#c3bdce;
--border:#342344;
}
*{box-sizing:border-box;margin:0;padding:0;scroll-behavior:smooth}
body{background:var(--bg);color:white;font-family:Arial,sans-serif;line-height:1.7}
a{text-decoration:none;color:inherit}
header{position:sticky;top:0;z-index:1000;background:#090611ee;border-bottom:1px solid var(--border)}
nav{max-width:1200px;margin:auto;padding:15px 6%;display:flex;align-items:center;justify-content:space-between}
.logo{font-size:28px;font-weight:900;letter-spacing:5px}
.logo span,.heading span{color:var(--purple)}
.nav-links{display:flex;gap:20px}
.nav-links a{color:var(--silver);font-size:14px}
.nav-links a:hover{color:var(--light)}
.menu-btn{display:none;background:none;color:white;border:1px solid var(--purple);padding:8px;border-radius:8px}
.hero{min-height:650px;display:grid;place-items:center;text-align:center;padding:80px 7%;background:radial-gradient(ellipse at center,#45216b,transparent 65%),linear-gradient(135deg,#090611,#150b24)}
.hero-inner{max-width:850px}
.eyebrow{color:var(--light);letter-spacing:5px;font-size:13px}
.hero h1{font-size:clamp(65px,12vw,110px);letter-spacing:12px;margin:20px 0}
.hero h1 span{color:var(--purple)}
.hero p,.intro{color:var(--silver)}
.hero p{font-size:19px;margin-bottom:30px}
.btn{display:inline-block;padding:13px 25px;border-radius:30px;background:linear-gradient(90deg,#8b5cf6,#6033b5);color:white;font-weight:bold;border:0;cursor:pointer}
.btn.secondary{background:transparent;border:1px solid var(--purple);margin-left:10px}
section{padding:85px 7%;scroll-margin-top:75px}
.container{max-width:1150px;margin:auto}
.heading{text-align:center;font-size:38px;margin-bottom:12px}
.intro{text-align:center;max-width:730px;margin:0 auto 40px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
.card{background:var(--panel);padding:27px;border:1px solid var(--border);border-radius:17px;transition:.3s}
.card:hover{transform:translateY(-6px);border-color:var(--purple)}
.card .icon{font-size:32px}
.card h3{color:var(--light);margin:10px 0}
.card p{color:var(--silver);font-size:15px}
.two-col{display:grid;grid-template-columns:1fr 1fr;gap:35px;align-items:center}
.copy p{color:var(--silver);margin-bottom:16px}
.vision,.product-card{background:#151020;border:1px solid #68409a;padding:35px;border-radius:20px;text-align:center}
.vision h3{color:var(--light);font-size:28px}
.product{background:radial-gradient(ellipse at center,#25123b,#090611 70%)}
.product-card{max-width:800px;margin:auto}
.product-art{height:180px;width:180px;margin:0 auto 25px;border-radius:50%;display:grid;place-items:center;font-size:65px;background:#38205b;border:2px solid var(--purple)}
.product-card p{color:var(--silver);margin:15px auto 25px}
.demo,.contact-form{max-width:800px;margin:auto;background:var(--panel);padding:28px;border:1px solid #50316f;border-radius:20px}
label{display:block;color:var(--light);margin:12px 0 5px}
textarea,input,select{width:100%;background:#090611;color:white;border:1px solid #50316f;border-radius:10px;padding:13px}
textarea{min-height:100px;resize:vertical}
.controls{display:grid;grid-template-columns:1fr 1fr;gap:15px}
.action-row{display:flex;gap:10px;flex-wrap:wrap;margin-top:17px}
.result{min-height:65px;background:#090611;border:1px solid var(--border);border-radius:10px;padding:14px;overflow-wrap:anywhere}
.status,.note{font-size:12px;color:var(--light);margin-top:12px}
.timeline{max-width:760px;margin:auto}
.step{padding:20px 24px;background:var(--panel);border-left:3px solid var(--purple);margin-bottom:17px}
.step h3{color:var(--light)}
.step p{color:var(--silver)}
.faq{max-width:800px;margin:auto}
details{background:var(--panel);border:1px solid var(--border);border-radius:12px;padding:18px;margin:12px 0}
summary{cursor:pointer;color:var(--light);font-weight:bold}
details p{color:var(--silver);padding-top:12px}
.contact{background:linear-gradient(180deg,#140b20,#090611);text-align:center}
.contact-form{text-align:left}
.email{color:var(--light);font-weight:bold;overflow-wrap:anywhere}
footer{border-top:1px solid var(--border);padding:30px 7%;text-align:center;color:var(--silver);font-size:13px}
footer strong{color:var(--light)}
#topBtn{position:fixed;right:20px;bottom:20px;display:none;background:var(--purple);color:white;border:0;border-radius:50%;width:45px;height:45px;font-size:20px}
@media(max-width:850px){
.menu-btn{display:block}
.nav-links{display:none;position:absolute;top:65px;left:0;width:100%;background:#100b19;padding:22px;flex-direction:column}
.nav-links.show{display:flex}
.grid,.two-col{grid-template-columns:1fr}
}
@media(max-width:560px){
.hero h1{letter-spacing:6px}
section{padding:65px 6%}
.heading{font-size:31px}
.controls{grid-template-columns:1fr}
.btn.secondary{margin:10px 0 0}
}
</style>
</head>

<body>
<header>
<nav>
<a class="logo" href="#home">CAR<span>O</span></a>
<button class="menu-btn" onclick="toggleMenu()">☰ Menu</button>
<div class="nav-links" id="navLinks">
<a href="#home" onclick="closeMenu()">Home</a>
<a href="#about" onclick="closeMenu()">About</a>
<a href="#technology" onclick="closeMenu()">Technology</a>
<a href="#product" onclick="closeMenu()">Product</a>
<a href="#demo" onclick="closeMenu()">Demo</a>
<a href="#roadmap" onclick="closeMenu()">Roadmap</a>
<a href="#faq" onclick="closeMenu()">FAQ</a>
<a href="#contact" onclick="closeMenu()">Contact</a>
</div>
</nav>
</header>

<main>
<section class="hero" id="home">
<div class="hero-inner">
<div class="eyebrow">CARO TECHNOLOGIES</div>
<h1>CAR<span>O</span></h1>
<p><strong>No Language Barrier. Just Connection.</strong><br>
Connecting All Regions Online through the future of translation technology.</p>
<a class="btn" href="#technology">Explore Technology</a>
<a class="btn secondary" href="#about">Discover CARO</a>
</div>
</section>

<section id="about">
<div class="container">
<h2 class="heading">About <span>CARO</span></h2>
<p class="intro">A technology concept focused on helping people communicate across languages and cultures.</p>
<div class="two-col">
<div class="copy">
<p>CARO stands for <strong>Connecting All Regions Online</strong>.</p>
<p>Our vision is to make communication easier for people around the world through translation technology and accessible digital tools.</p>
<p>We are developing a concept for translation earbuds and a companion mobile application.</p>
</div>
<div class="vision">
<h3>Our Vision</h3>
<p>A connected world where language differences do not stop people from sharing ideas, learning and building friendships.</p>
</div>
</div>
</div>
</section>

<section id="technology">
<div class="container">
<h2 class="heading">Our <span>Technology</span></h2>
<p class="intro">Planned features for the CARO translation ecosystem.</p>
<div class="grid">
<div class="card"><div class="icon">🌐</div><h3>Language Translation</h3><p>Explore Urdu, English, Korean, Japanese and other languages.</p></div>
<div class="card"><div class="icon">🎙️</div><h3>Voice Translation</h3><p>A planned voice-based multilingual conversation experience.</p></div>
<div class="card"><div class="icon">📷</div><h3>Camera Translation</h3><p>A future feature for understanding text in photographs.</p></div>
<div class="card"><div class="icon">🎧</div><h3>Smart Earbuds</h3><p>Wireless earbuds connected to the CARO mobile application.</p></div>
<div class="card"><div class="icon">📱</div><h3>Mobile Application</h3><p>A planned app experience for Android and iPhone.</p></div>
<div class="card"><div class="icon">🔋</div><h3>Device Management</h3><p>Planned battery monitoring and device management features.</p></div>
</div>
</div>
</section>

<section class="product" id="product">
<div class="container">
<h2 class="heading">Meet the <span>CARO Concept</span></h2>
<p class="intro">Our vision for connected translation technology.</p>
<div class="product-card">
<div class="product-art">🎧</div>
<h2>CARO Translation Earbuds</h2>
<p>A proposed wireless translation device with a companion app, designed to explore two-way multilingual communication.</p>
<a class="btn" href="#contact">Contact CARO</a>
<p class="note">Product shown as a concept. Hardware development and testing are future goals.</p>
</div>
</div>
</section>

<section id="demo">
<div class="container">
<h2 class="heading">Translation <span>Demo</span></h2>
<p class="intro">Try a simple online text translation demonstration.</p>
<div class="demo">
<div class="controls">
<div><label for="fromLang">Translate from</label>
<select id="fromLang">
<option value="auto">Detect language</option>
<option value="en">English</option><option value="ur">Urdu</option><option value="ko">Korean</option>
<option value="ja">Japanese</option><option value="ar">Arabic</option><option value="zh">Chinese</option>
<option value="fr">French</option><option value="de">German</option><option value="es">Spanish</option>
<option value="hi">Hindi</option><option value="tr">Turkish</option><option value="bn">Bengali</option>
</select></div>
<div><label for="toLang">Translate to</label>
<select id="toLang">
<option value="ur">Urdu</option><option value="en">English</option><option value="ko">Korean</option>
<option value="ja">Japanese</option><option value="ar">Arabic</option><option value="zh">Chinese</option>
<option value="fr">French</option><option value="de">German</option><option value="es">Spanish</option>
<option value="hi">Hindi</option><option value="tr">Turkish</option><option value="bn">Bengali</option>
</select></div>
</div>
<label for="sourceText">Your text</label>
<textarea id="sourceText" placeholder="Type something to translate..."></textarea>
<div class="action-row">
<button class="btn" id="translateBtn" onclick="translateText()">Translate Text</button>
<button class="btn secondary" onclick="swapLanguages()">Swap Languages</button>
</div>
<label>Translation result</label>
<div class="result" id="result" aria-live="polite">Your translation will appear here.</div>
<div class="action-row">
<button class="btn" onclick="copyResult()">Copy Translation</button>
<button class="btn secondary" onclick="speakResult()">Read Aloud</button>
</div>
<div class="status" id="translateStatus"></div>
<p class="note">Demo uses an external translation service and requires internet access. Do not enter private information.</p>
</div>
</div>
</section>

<section id="roadmap">
<div class="container">
<h2 class="heading">Our <span>Roadmap</span></h2>
<p class="intro">The planned journey from an idea to a tested product.</p>
<div class="timeline">
<div class="step"><h3>01 — Concept and Research</h3><p>Develop the product vision and research translation technology.</p></div>
<div class="step"><h3>02 — App Development</h3><p>Build and improve the CARO mobile application prototype.</p></div>
<div class="step"><h3>03 — Prototype Exploration</h3><p>Explore safe hardware design and professional engineering support.</p></div>
<div class="step"><h3>04 — Testing and Improvement</h3><p>Test usability, translation quality and device performance.</p></div>
<div class="step"><h3>05 — Future Collaboration</h3><p>Explore potential partnerships with technology companies around the world.</p></div>
</div>
</div>
</section>

<section id="faq">
<div class="container">
<h2 class="heading">Frequently Asked <span>Questions</span></h2>
<p class="intro">Learn more about the CARO project.</p>
<div class="faq">
<details><summary>What does CARO stand for?</summary><p>CARO stands for Connecting All Regions Online.</p></details>
<details><summary>What is CARO building?</summary><p>CARO is exploring a translation-earbuds concept and a companion mobile application.</p></details>
<details><summary>Is the product available to buy?</summary><p>No. CARO is an early-stage concept and prototype project.</p></details>
<details><summary>Which languages are planned?</summary><p>Planned language interests include Urdu, English, Korean, Japanese, Arabic, Chinese, French, German, Spanish, Hindi, Turkish and Bengali.</p></details>
<details><summary>Can companies discuss collaboration?</summary><p>Potential professional research and technology collaboration inquiries are welcome.</p></details>
</div>
</div>
</section>

<section class="contact" id="contact">
<div class="container">
<h2 class="heading">Connect With <span>CARO</span></h2>
<p class="intro">Interested in translation technology, research or potential collaboration?</p>

<p>Email: <a class="email" href="mailto:abbeera677@gmail.com">abbeera677@gmail.com</a></p>

<form class="contact-form" onsubmit="sendEmail(event)">
<label for="visitorName">Your name</label>
<input id="visitorName" type="text" placeholder="Your name" required>

<label for="visitorEmail">Your email</label>
<input id="visitorEmail" type="email" placeholder="you@example.com" required>

<label for="visitorMessage">Your message</label>
<textarea id="visitorMessage" placeholder="Write your message..." required></textarea>

<button class="btn" type="submit">Send Email</button>
<p class="note">This opens your email application with your message prepared. It does not send automatically.</p>
</form>
</div>
</section>
</main>

<footer>
<strong>CARO TECHNOLOGIES</strong>
<p>Connecting All Regions Online</p>
<p>No Language Barrier. Just Connection.</p>
<p><a href="mailto:abbeera677@gmail.com">abbeera677@gmail.com</a></p>
<p>© <span id="year"></span> CARO. All rights reserved.</p>
<p class="note">CARO is an early-stage project concept. Planned features are not yet guaranteed or commercially available.</p>
</footer>

<button id="topBtn" onclick="window.scrollTo({top:0,behavior:'smooth'})" aria-label="Back to top">↑</button>

<script>
const CONTACT_EMAIL = "abbeera677@gmail.com";

function toggleMenu(){
document.getElementById("navLinks").classList.toggle("show");
}
function closeMenu(){
document.getElementById("navLinks").classList.remove("show");
}

document.getElementById("year").textContent = new Date().getFullYear();

window.addEventListener("scroll",()=>{
document.getElementById("topBtn").style.display =
window.scrollY > 400 ? "block" : "none";
});

async function translateText(){
const text = document.getElementById("sourceText").value.trim();
const from = document.getElementById("fromLang").value;
const to = document.getElementById("toLang").value;
const result = document.getElementById("result");
const status = document.getElementById("translateStatus");
const button = document.getElementById("translateBtn");

if(!text){status.textContent="Please enter some text first.";return;}
if(from===to){status.textContent="Choose two different languages.";return;}

button.disabled=true;
button.textContent="Translating...";
status.textContent="Connecting to translation service...";

try{
const response=await fetch("https://translate.argosopentech.com/translate",{
method:"POST",
headers:{"Content-Type":"application/json"},
body:JSON.stringify({q:text,source:from,target:to,format:"text"})
});
if(!response.ok)throw new Error("Translation unavailable");
const data=await response.json();
if(!data.translatedText)throw new Error("No result");
result.textContent=data.translatedText;
status.textContent="Translation complete.";
}catch(error){
result.textContent="Translation is unavailable right now. Please try again later.";
status.textContent="Check your internet connection or try again later.";
}finally{
button.disabled=false;
button.textContent="Translate Text";
}
}

function swapLanguages(){
const from=document.getElementById("fromLang");
const to=document.getElementById("toLang");
if(from.value==="auto"){
document.getElementById("translateStatus").textContent="Choose a source language before swapping.";
return;
}
const old=from.value;
from.value=to.value;
to.value=old;
}

async function copyResult(){
const text=document.getElementById("result").textContent;
try{
await navigator.clipboard.writeText(text);
document.getElementById("translateStatus").textContent="Translation copied.";
}catch(error){
document.getElementById("translateStatus").textContent="Please select and copy the translation manually.";
}
}

function speakResult(){
const text=document.getElementById("result").textContent;
if(!("speechSynthesis" in window)){
document.getElementById("translateStatus").textContent="Read aloud is not supported in this browser.";
return;
}
const languages={
en:"en-US",ur:"ur-PK",ko:"ko-KR",ja:"ja-JP",ar:"ar-SA",
zh:"zh-CN",fr:"fr-FR",de:"de-DE",es:"es-ES",hi:"hi-IN",
tr:"tr-TR",bn:"bn-BD"
};
const lang=document.getElementById("toLang").value;
const utterance=new SpeechSynthesisUtterance(text);
utterance.lang=languages[lang]||"en-US";
speechSynthesis.cancel();
speechSynthesis.speak(utterance);
}

function sendEmail(event){
event.preventDefault();
const name=document.getElementById("visitorName").value.trim();
const email=document.getElementById("visitorEmail").value.trim();
const message=document.getElementById("visitorMessage").value.trim();
const subject=encodeURIComponent("CARO Website Inquiry");
const body=encodeURIComponent(
"Name: "+name+"\nEmail: "+email+"\n\nMessage:\n"+message
);
window.location.href="mailto:"+CONTACT_EMAIL+"?subject="+subject+"&body="+body;
}
</script>
</body>
</html>
