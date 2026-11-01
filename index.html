
<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#58cc02">
<title>Japanese Learning</title>

<style>
*{box-sizing:border-box}

body{
 margin:0;
 font-family:Arial,sans-serif;
 background:#f5f7fa;
 color:#333;
}

header{
 background:#58cc02;
 color:white;
 padding:25px 18px;
 text-align:center;
}

header h1{margin:5px}

.container{
 max-width:700px;
 margin:auto;
 padding:15px;
}

.card{
 background:white;
 padding:20px;
 margin:15px 0;
 border-radius:16px;
 box-shadow:0 2px 8px #ddd;
}

h2{color:#328600}

button{
 border:0;
 padding:13px;
 border-radius:10px;
 cursor:pointer;
 font-size:16px;
}

.green{
 background:#58cc02;
 color:white;
}

.menu{
 display:grid;
 grid-template-columns:1fr 1fr;
 gap:12px;
}

.menu button{
 background:#e8fbdc;
 color:#328600;
 min-height:75px;
 font-weight:bold;
}

.character{
 font-size:55px;
 text-align:center;
 margin:15px;
}

.lesson{
 background:#f4f8f1;
 padding:15px;
 margin:12px 0;
 border-radius:12px;
}

.answers{
 display:grid;
 grid-template-columns:1fr 1fr;
 gap:10px;
}

.answers button{
 background:#e8fbdc;
}

.hidden{display:none}

.progress{
 background:#eee;
 height:12px;
 border-radius:20px;
 overflow:hidden;
}

#progressBar{
 background:#58cc02;
 height:100%;
 width:0%;
}

nav{
 display:flex;
 justify-content:space-around;
 background:white;
 padding:12px;
 position:sticky;
 bottom:0;
 border-top:1px solid #ddd;
}

nav button{
 background:white;
 font-size:13px;
}

footer{
 text-align:center;
 padding:20px;
 color:#777;
}
</style>
</head>

<body>

<header>
<h1>🇯🇵 Japanese Learning</h1>
<h2 style="color:white">日本語学習</h2>
<p>বাংলা ও ইংরেজিতে জাপানি ভাষা শিখুন</p>
</header>

<div class="container">

<section id="home">

<div class="card">
<h2>ようこそ! স্বাগতম</h2>
<p>জাপানি ভাষা শেখা শুরু করুন।</p>

<h3>আপনার অগ্রগতি</h3>
<div class="progress">
<div id="progressBar"></div>
</div>

<p>পয়েন্ট: <span id="points">0</span></p>
</div>

<div class="card">
<h2>শেখার কোর্স</h2>

<div class="menu">
<button onclick="show('hiragana')">あ Hiragana</button>
<button onclick="show('katakana')">ア Katakana</button>
<button onclick="show('kanji')">漢字 Kanji</button>
<button onclick="show('vocabulary')">শব্দভান্ডার</button>
<button onclick="show('n5')">JLPT N5</button>
<button onclick="show('n4')">JLPT N4</button>
<button onclick="show('quiz')">📝 পরীক্ষা</button>
</div>
</div>

</section>

<section id="hiragana" class="hidden">
<div class="card">
<h2>Hiragana - ひらがな</h2>
<div id="hiraList"></div>
</div>
</section>

<section id="katakana" class="hidden">
<div class="card">
<h2>Katakana - カタカナ</h2>
<div id="kataList"></div>
</div>
</section>

<section id="kanji" class="hidden">
<div class="card">
<h2>Kanji - 漢字</h2>
<div id="kanjiList"></div>
</div>
</section>

<section id="vocabulary" class="hidden">
<div class="card">
<h2>Japanese Vocabulary</h2>
<div id="wordList"></div>
</div>
</section>

<section id="n5" class="hidden">
<div class="card">
<h2>JLPT N5 Course</h2>
<div id="n5List"></div>
</div>
</section>

<section id="n4" class="hidden">
<div class="card">
<h2>JLPT N4 Course</h2>
<div id="n4List"></div>
</div>
</section>

<section id="quiz" class="hidden">
<div class="card">
<h2>Japanese Quiz</h2>
<div id="question"></div>
<div id="answers" class="answers"></div>
<p id="result"></p>
<button class="green" onclick="nextQuestion()">পরবর্তী প্রশ্ন</button>
</div>
</section>

</div>

<nav>
<button onclick="show('home')">🏠<br>Home</button>
<button onclick="show('hiragana')">あ<br>Learn</button>
<button onclick="show('quiz')">📝<br>Quiz</button>
</nav>

<footer>
<p>Japanese Learning | 日本語学習</p>
<p>Learn Japanese Every Day</p>
</footer>

<script>

const hira=[
["あ","আ"],["い","ই"],["う","উ"],["え","এ"],["お","ও"],
["か","কা"],["き","কি"],["く","কু"],["け","কে"],["こ","কো"],
["さ","সা"],["し","শি"],["す","সু"],["せ","সে"],["そ","সো"],
["た","তা"],["ち","চি"],["つ","ৎসু"],["て","তে"],["と","তো"],
["な","না"],["に","নি"],["ぬ","নু"],["ね","নে"],["の","নো"],
["は","হা"],["ひ","হি"],["ふ","ফু"],["へ","হে"],["ほ","হো"],
["ま","মা"],["み","মি"],["む","মু"],["め","মে"],["も","মো"],
["や","ইয়া"],["ゆ","ইউ"],["よ","ইয়ো"],
["ら","রা"],["り","রি"],["る","রু"],["れ","রে"],["ろ","রো"],
["わ","ওয়া"],["を","ও"],["ん","ন"]
];

const kata=[
["ア","আ"],["イ","ই"],["ウ","উ"],["エ","এ"],["オ","ও"],
["カ","কা"],["キ","কি"],["ク","কু"],["ケ","কে"],["コ","কো"],
["サ","সা"],["シ","শি"],["ス","সু"],["セ","সে"],["ソ","সো"],
["タ","তা"],["チ","চি"],["ツ","ৎসু"],["テ","তে"],["ト","তো"],
["ナ","না"],["ニ","নি"],["ヌ","নু"],["ネ","নে"],["ノ","নো"],
["ハ","হা"],["ヒ","হি"],["フ","ফু"],["ヘ","হে"],["ホ","হো"],
["マ","মা"],["ミ","মি"],["ム","মু"],["メ","মে"],["モ","মো"],
["ヤ","ইয়া"],["ユ","ইউ"],["ヨ","ইয়ো"],
["ラ","রা"],["リ","রি"],["ル","রু"],["レ","রে"],["ロ","রো"],
["ワ","ওয়া"],["ヲ","ও"],["ン","ন"]
];

const kanji=[
["日","দিন","ひ"],
["月","চাঁদ","つき"],
["山","পাহাড়","やま"],
["川","নদী","かわ"],
["水","পানি","みず"],
["火","আগুন","ひ"],
["木","গাছ","き"],
["人","মানুষ","ひと"]
];

const words=[
["こんにちは","হ্যালো","Hello"],
["ありがとう","ধন্যবাদ","Thank you"],
["おはよう","সুপ্রভাত","Good morning"],
["こんばんは","শুভ সন্ধ্যা","Good evening"],
["さようなら","বিদায়","Goodbye"],
["はい","হ্যাঁ","Yes"],
["いいえ","না","No"],
["わたし","আমি","I"]
];

const n5=[
["学生","がくせい","শিক্ষার্থী","Student"],
["学校","がっこう","বিদ্যালয়","School"],
["先生","せんせい","শিক্ষক","Teacher"],
["友達","ともだち","বন্ধু","Friend"],
["日本","にほん","জাপান","Japan"],
["水","みず","পানি","Water"]
];

const n4=[
["勉強","べんきょう","পড়াশোনা","Study"],
["旅行","りょこう","ভ্রমণ","Travel"],
["料理","りょうり","রান্না","Cooking"],
["病院","びょういん","হাসপাতাল","Hospital"],
["会社","かいしゃ","কোম্পানি","Company"],
["質問","しつもん","প্রশ্ন","Question"]
];

let points=Number(localStorage.getItem("points")||0);
let learned=JSON.parse(localStorage.getItem("learned")||"[]");

function show(id){
 document.querySelectorAll(".container section")
 .forEach(s=>s.classList.add("hidden"));

 document.getElementById(id).classList.remove("hidden");
 window.scrollTo(0,0);
}

function speak(text){
 if(!window.speechSynthesis){
 alert("আপনার ব্রাউজারে অডিও সমর্থিত নয়");
 return;
 }

 speechSynthesis.cancel();

 let voice=new SpeechSynthesisUtterance(text);
 voice.lang="ja-JP";
 voice.rate=0.8;

 speechSynthesis.speak(voice);
}

function complete(id){
 if(!learned.includes(id)){
 learned.push(id);
 points+=10;

 localStorage.setItem("learned",JSON.stringify(learned));
 localStorage.setItem("points",points);
 }

 update();
}

function update(){
 document.getElementById("points").innerText=points;

 document.getElementById("progressBar").style.width=
 Math.min(100,learned.length/100*100)+"%";
}

function renderLetters(data,id){
 document.getElementById(id).innerHTML=data.map((x,i)=>`
 <div class="lesson">
 <div class="character">${x[0]}</div>
 <h3>${x[1]}</h3>
 <button class="green" onclick="speak('${x[0]}')">
 🔊 উচ্চারণ শুনুন
 </button>
 <button onclick="complete('${id}${i}')">
 ✓ শিখেছি
 </button>
 </div>
 `).join("");
}

function renderKanji(){
 document.getElementById("kanjiList").innerHTML=
 kanji.map(x=>`
 <div class="lesson">
 <div class="character">${x[0]}</div>
 <p>${x[1]}</p>
 <p>${x[2]}</p>
 <button class="green" onclick="speak('${x[2]}')">🔊 শুনুন</button>
 </div>
 `).join("");
}

function renderWords(){
 document.getElementById("wordList").innerHTML=
 words.map(x=>`
 <div class="lesson">
 <h2>${x[0]}</h2>
 <p>বাংলা: ${x[1]}</p>
 <p>English: ${x[2]}</p>
 <button class="green" onclick="speak('${x[0]}')">🔊 শুনুন</button>
 </div>
 `).join("");
}

function renderCourse(data,id){
 document.getElementById(id).innerHTML=
 data.map(x=>`
 <div class="lesson">
 <h2>${x[0]}</h2>
 <p>${x[1]}</p>
 <p>বাংলা: ${x[2]}</p>
 <p>English: ${x[3]}</p>
 <button class="green" onclick="speak('${x[1]}')">🔊 শুনুন</button>
 </div>
 `).join("");
}

const questions=[
["あ","আ",["আ","ই","উ"]],
["い","ই",["ও","ই","এ"]],
["う","উ",["আ","উ","ও"]],
["え","এ",["এ","ই","আ"]],
["お","ও",["উ","ও","এ"]],
["か","কা",["কি","কা","কু"]],
["き","কি",["কে","কি","কা"]],
["く","কু",["কু","কি","কে"]],
["し","শি",["সি","শি","সু"]],
["ね","নে",["না","নু","নে"]]
];

let qIndex=0;
let answered=false;

function loadQuestion(){
 answered=false;

 let q=questions[qIndex];

 document.getElementById("question").innerHTML=
 `<div class="character">${q[0]}</div>
 <h3>এই অক্ষরের উচ্চারণ কী?</h3>`;

 document.getElementById("answers").innerHTML=
 q[2].map(a=>`
 <button onclick="answer('${a}')">${a}</button>
 `).join("");

 document.getElementById("result").innerText="";
}

function answer(a){
 if(answered)return;

 answered=true;

 let q=questions[qIndex];

 if(a===q[1]){
 points+=10;
 localStorage.setItem("points",points);
 document.getElementById("result").innerText="সঠিক উত্তর! +১০ পয়েন্ট 🎉";
 }else{
 document.getElementById("result").innerText="সঠিক উত্তর: "+q[1];
 }

 update();
}

function nextQuestion(){
 qIndex=(qIndex+1)%questions.length;
 loadQuestion();
}

renderLetters(hira,"hiraList");
renderLetters(kata,"kataList");
renderKanji();
renderWords();
renderCourse(n5,"n5List");
renderCourse(n4,"n4List");
loadQuestion();
update();

</script>

</body>
</html>
