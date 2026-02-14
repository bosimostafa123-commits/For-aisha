<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Aisha ❤️</title>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
<style>
/* نفس التنسيقات السابقة مع تحسينات بسيطة */
* { margin:0; padding:0; box-sizing:border-box; font-family:'Cairo',sans-serif; }
body {
    overflow:hidden;
    background: linear-gradient(135deg, #ff7eb3, #ff4d94);
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    animation: bgMove 12s infinite alternate;
}
@keyframes bgMove { 0%{background-position:0% 0%} 100%{background-position:100% 100%} }
#flowers { position:fixed; top:0; left:0; width:100%; height:100%; z-index:0; pointer-events:none; }
.flower { position:absolute; top:-50px; font-size:24px; animation: fall linear infinite; }
@keyframes fall { to{ transform: translateY(110vh) rotate(360deg); } }
.content { position:relative; z-index:2; text-align:center; color:white; width:100%; padding:20px; }
h2 { font-size:1.8rem; margin-bottom:30px; text-shadow: 0 2px 15px rgba(0,0,0,0.2); }
.heart-container { width:220px; margin:0 auto; cursor:pointer; transition: transform 0.2; }
.heart-container:active { transform: scale(0.9); }
.explode { animation: explodeAnim 0.8s forwards; }
@keyframes explodeAnim { 0%{transform:scale(1);} 100%{transform:scale(0); opacity:0;} }
#loveText {
    position:absolute; top:50%; left:50%; transform:translate(-50%,-50%) scale(0);
    font-size:40px; font-weight:bold; opacity:0; transition: all 0.8s cubic-bezier(0.175,0.885,0.32,1.275);
}
.showLove { opacity:1 !important; transform:translate(-50%,-50%) scale(1) !important; }
#finalPage { display:none; flex-direction:column; align-items:center; }
#timer {
    margin-top:20px; background: rgba(255,255,255,0.15); padding:25px;
    border-radius:25px; backdrop-filter: blur(15px); border:1px solid rgba(255,255,255,0.3);
}
#loveBtn {
    margin-top:20px; padding:15px 30px; font-size:18px; font-weight:bold;
    color:#fff; background: linear-gradient(45deg, #ff2e8b, #ff7eb3);
    border:none; border-radius:30px; cursor:pointer;
}
#lovePage {
    display:none; position:fixed; top:0; left:0; width:100%; height:100%;
    background: linear-gradient(135deg, #ff4d94, #ff7eb3); color:white;
    text-align:center; padding:50px 20px; overflow-y:auto;
}
#lovePage.show { display:block; }
#loveMessage { font-size:22px; line-height:1.8; white-space:pre-wrap; }
.spark { position:absolute; pointer-events:none; animation: sparkAnim 1s forwards; }
@keyframes sparkAnim { 0%{transform:translate(0,0) scale(1); opacity:1;} 100%{transform:translate(var(--x),var(--y)) scale(0); opacity:0;} }
</style>
</head>
<body>

<audio id="bgMusic" loop>
    <source src="http://googleusercontent.com/file_content/0" type="audio/mpeg">
</audio>

<div id="flowers"></div>

<div class="content" id="mainPage">
    <h2>اضغطي على القلب لتملئيه بالحب ❤️</h2>
    <p style="margin-bottom: 10px; font-size: 0.9rem;">(سيتم تشغيل الموسيقى عند أول لمسة)</p>
    <div class="heart-container" id="heartBox" onclick="fillHeart()">
        <svg viewBox="0 0 512 512">
            <defs>
                <clipPath id="clipHeart">
                    <path d="M256 472l-35-32C118 346 32 269 32 181 32 115 83 64 149 64c39 0 76 18 107 46 31-28 68-46 107-46 66 0 117 51 117 117 0 88-86 165-189 259l-35 32z"/>
                </clipPath>
            </defs>
            <path d="M256 472l-35-32C118 346 32 269 32 181 32 115 83 64 149 64c39 0 76 18 107 46 31-28 68-46 107-46 66 0 117 51 117 117 0 88-86 165-189 259l-35 32z"
                  fill="none" stroke="white" stroke-width="15"/>
            <rect id="fillRect" x="0" y="512" width="512" height="0" fill="#ff2e8b" clip-path="url(#clipHeart)" style="transition: all 0.3s ease;"/>
        </svg>
    </div>
    <div id="loveText">بحبك يا قلب بابا ❤️</div>
</div>

<div class="content" id="finalPage">
    <h2>الوقت اللي قلبي رجع فيه للحياة 😍❤️</h2>
    <div id="timer">جارِ الحساب...</div>
    <button id="loveBtn" onclick="showLovePage()">اضغطي هنا لتري رسالة حبي 💖</button>
</div>

<div class="content" id="lovePage">
    <div id="loveMessage"></div>
</div>

<script>
let fill = 0;
let musicStarted = false;
const heartBox = document.getElementById("heartBox");
const fillRect = document.getElementById("fillRect");
const bgMusic = document.getElementById("bgMusic");

function fillHeart() {
    // تشغيل الموسيقى عند أول ضغطة
    if (!musicStarted) {
        bgMusic.play().catch(e => console.log("Audio play failed:", e));
        musicStarted = true;
    }

    if (fill < 512) {
        fill += 64; // زيادة سرعة الملء قليلاً
        fillRect.setAttribute("y", 512 - fill);
        fillRect.setAttribute("height", fill);
        heartBox.style.transform = "scale(1.1)";
        setTimeout(() => heartBox.style.transform = "scale(1)", 100);
    }
    if (fill >= 512) { explodeHeart(); }
}

function explodeHeart() {
    heartBox.onclick = null;
    heartBox.classList.add("explode");
    createSparks();
    setTimeout(() => document.getElementById("loveText").classList.add("showLove"), 400);
    setTimeout(() => {
        document.getElementById("mainPage").style.display = "none";
        document.getElementById("finalPage").style.display = "flex";
        startTimer();
    }, 3000);
}

function createSparks() {
    for (let i = 0; i < 40; i++) {
        let s = document.createElement("div");
        s.className = "spark";
        s.innerHTML = ["❤️", "✨", "🌸", "💖"][Math.floor(Math.random() * 4)];
        s.style.left = "50%"; s.style.top = "50%";
        const x = (Math.random() - 0.5) * 500 + "px";
        const y = (Math.random() - 0.5) * 500 + "px";
        s.style.setProperty('--x', x); s.style.setProperty('--y', y);
        document.body.appendChild(s);
        setTimeout(() => s.remove(), 1200);
    }
}

function createFlowers() {
    const container = document.getElementById("flowers");
    for (let i = 0; i < 50; i++) {
        let f = document.createElement("div");
        f.className = "flower";
        f.innerHTML = ["🌸", "🌹", "💮"][Math.floor(Math.random() * 3)];
        f.style.left = Math.random() * 100 + "%";
        f.style.animationDuration = (5 + Math.random() * 5) + "s";
        f.style.animationDelay = (Math.random() * 5) + "s";
        container.appendChild(f);
    }
}
createFlowers();

function startTimer() {
    const startDate = new Date(2025, 5, 19, 20, 0, 0);
    setInterval(() => {
        const now = new Date();
        let years = now.getFullYear() - startDate.getFullYear();
        let months = now.getMonth() - startDate.getMonth();
        let days = now.getDate() - startDate.getDate();
        let hours = now.getHours() - startDate.getHours();
        let minutes = now.getMinutes() - startDate.getMinutes();
        let seconds = now.getSeconds() - startDate.getSeconds();

        if (seconds < 0) { seconds += 60; minutes--; }
        if (minutes < 0) { minutes += 60; hours--; }
        if (hours < 0) { hours += 24; days--; }
        if (days < 0) { const lastMonth = new Date(now.getFullYear(), now.getMonth(), 0); days += lastMonth.getDate(); months--; }
        if (months < 0) { months += 12; years--; }

        document.getElementById("timer").innerHTML = `
            <div style="font-size:24px; font-weight:bold;">${years} سنة • ${months} شهر • ${days} يوم</div>
            <div style="font-size:18px;">${hours} ساعة : ${minutes} دقيقة : ${seconds} ثانية</div>
        `;
    }, 1000);
}

const fullText = `بحبك ي عيوشه ❤️\nي احلي حاجه حصلتلي ف حياتي ي امي و صحبتي و واختي 💕\nبجد لو فضلت اوصفلك بحبك قد اي مش هيكفي من هنا للسنه الجايه 😍\nبحب ديما اشوفك مبسوطه و بحس بفرحه و في جزء مني فرحان 🌸\nبقيت بحس كل يوم حبي بيزيد ليكي 💖\nو لله بموت فيكي 💘\nبقيت بتمني اليوم الي يجمعنا بيت واحد اوضه وحده اخدك ف حضني طول الوقت ❤️\nحقيقي الوحيده الي مش ببقي مهتم اني اتاسفلها اهم حاجه انك متناميش زعلانه 😘\nبجد بعشقككك و بموت فيكي 😍\nربنا يخليكي ليا و يزيد محبتنا لبعض 💞\nو يارب نفضل مع بعض لاخر عمرنا\nمستني بقي اليوم الي هنبقي في مع بعض او حاجه حضن كتب الكتاب دا الحضن الاول دي هتبقي كتر حاجه حلوه ف حياتي بعد انك بقيتي مراتي و همتعك متعه عمرك ما تتخليله حرفيا هخليكي تدمني حاجه اسمها يوسف .. هقطعكك 😍🫣🤤💖`;

function showLovePage() {
    document.getElementById("finalPage").style.display = "none";
    const lovePage = document.getElementById("lovePage");
    lovePage.classList.add("show");
    const msg = document.getElementById("loveMessage");
    let index = 0;
    const interval = setInterval(() => {
        msg.innerHTML += fullText[index];
        index++;
        if (index >= fullText.length) clearInterval(interval);
    }, 40);
}
</script>
</body>
</html>
