-events:none;animation:float 4s ease-in-out infinite}

.d1{top:8%;left:9%;font-size:32px} .d2{top:17%;right:10%;font-size

:25px;animation-delay:1s}.d3{bottom

:16%;left:12%;font-size:24px

;animation-delay:2s}.d4{bottom:10%

;right:12%;font-size:34px;animation

-delay:.5s}

.brand{font-size:18px;font-weight

:bold;background: #ffffffb8;border :1px solid #ffd0e3;border-radius :30px;padding:10px 17px;margin -bottom:22px;box-shadow:0 5px 18px

h1{font-size:clamp(35px,8vw,58px );line-height:1.1;margin-bottom :14px;color: #d94387;text-shadow:0

3px 0 #fff}

.intro{font-size:17px;line-height:1.6 ;max-width:470px;margin:0 auto 30px}

16

17 .frogs{display:flex;align-items :center;justify-content:center;gap :clamp(12px,4vw,25px);flex-wrap :wrap;max-width:520px}

18 .frog{width:clamp(86px,24vw,125px );height:clamp(86px,24vw,125px

Ln 1, Col 1

Sp: 2

HTML

LF

UTF<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>🐸 Żabkowy Świat 💗</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--pink:#ff9fc9;--deep:#c83b76;--pale:#fff0f7;--border:#ffc4dc}
body{min-height:100vh;font-family:Arial,sans-serif;color:var(--deep);background:radial-gradient(circle at 15% 15%,#fff 0 2px,transparent 3px),linear-gradient(135deg,#fff0f7,#ffd9e9);background-size:34px 34px,auto;overflow-x:hidden}
main{min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:35px 18px 55px;position:relative}
.decor{position:absolute;color:#ff8fbe;opacity:.75;pointer-events:none;animation:float 4s ease-in-out infinite}
.d1{top:8%;left:9%;font-size:32px}.d2{top:17%;right:10%;font-size:25px;animation-delay:1s}.d3{bottom:16%;left:12%;font-size:24px;animation-delay:2s}.d4{bottom:10%;right:12%;font-size:34px;animation-delay:.5s}
.brand{font-size:18px;font-weight:bold;background:#ffffffb8;border:1px solid #ffd0e3;border-radius:30px;padding:10px 17px;margin-bottom:22px;box-shadow:0 5px 18px #eec3d455}
h1{font-size:clamp(35px,8vw,58px);line-height:1.1;margin-bottom:14px;color:#d94387;text-shadow:0 3px 0 #fff}
.intro{font-size:17px;line-height:1.6;max-width:470px;margin:0 auto 30px}
.frogs{display:flex;align-items:center;justify-content:center;gap:clamp(12px,4vw,25px);flex-wrap:wrap;max-width:520px}
.frog{width:clamp(86px,24vw,125px);height:clamp(86px,24vw,125px);border:3px solid #ffffff;border-radius:34px;display:flex;align-items:center;justify-content:center;font-size:clamp(48px,13vw,75px);box-shadow:0 9px 20px #bd699333;cursor:pointer;transition:transform .2s,box-shadow .2s;animation:hop 2.3s ease-in-out infinite;user-select:none}
.frog:nth-child(2){animation-delay:.3s}.frog:nth-child(3){animation-delay:.6s}
.frog:hover{transform:translateY(-7px) scale(1.05);box-shadow:0 13px 25px #bd699355}
.green{background:#c6f3a4}.blue{background:#a4e5ff}.pink{background:#ffafd2}
.hint{margin-top:22px;font-size:14px;background:#ffffffa8;padding:9px 15px;border-radius:20px}
.heartBtn,.closeBtn{border:0;background:#ec5b99;color:white;padding:12px 21px;border-radius:25px;font-size:15px;font-weight:bold;cursor:pointer;box-shadow:0 5px 12px #e8a0bd66;margin-top:22px}
footer{margin-top:34px;font-size:14px;color:#cf6494}
.modal{display:none;position:fixed;inset:0;background:#51132dcc;z-index:10;align-items:center;justify-content:center;padding:16px}
.modalBox{width:min(680px,100%);max-height:90vh;overflow:auto;background:#fff9fc;border:3px solid var(--border);border-radius:27px;padding:22px;text-align:center;box-shadow:0 12px 40px #45102c55}
.modalBox h2{font-size:25px;margin-bottom:16px;color:#d94387}
.modalBox video{display:block;width:100%;max-height:65vh;border-radius:16px;background:#222}
.article{background:var(--pale);border-radius:18px;padding:18px;text-align:left;line-height:1.65;color:#63364d}
.article h3{color:#d94387;margin:14px 0 5px}.article p{margin:8px 0}.article ul{padding-left:22px;margin:8px 0}
.heart{position:fixed;bottom:-35px;font-size:25px;pointer-events:none;z-index:20;animation:up 2.8s ease-out forwards}
@keyframes hop{0%,100%{translate:0 0}50%{translate:0 -9px}}
@keyframes float{0%,100%{transform:translateY(0) rotate(-5deg)}50%{transform:translateY(-12px) rotate(7deg)}}
@keyframes up{to{transform:translateY(-110vh) rotate(25deg);opacity:0}}
@media(prefers-reduced-motion:reduce){*,*::before,*::after{animation:none!important;scroll-behavior:auto!important;transition:none!important}}
</style>
</head>
<body>
<main>
  <span class="decor d1">💗</span><span class="decor d2">💕</span><span class="decor d3">🌸</span><span class="decor d4">♡</span>
  <div class="brand">🐸 Żabkowy Świat 💗</div>
  <h1>Witaj w<br>żabkowym świecie!</h1>
  <p class="intro">Róż, serduszka i kolorowe żabki! 🌸<br>Kliknij żabkę, żeby otworzyć coś fajnego.</p>
  <div class="frogs" aria-label="Wybierz żabkę">
    <button class="frog green" onclick="openVideo()" aria-label="Otwórz film lub podcast" title="Film / podcast">🐸</button>
    <button class="frog blue" onclick="openArticle()" aria-label="Otwórz wpis edukacyjny" title="Wpis edukacyjny">🐸</button>
    <button class="frog pink" onclick="openPresentation()" aria-label="Otwórz prezentację" title="Prezentacja">🐸</button>
  </div>
  <p class="hint">💚 Film/podcast · 💙 Wpis · 💗 Prezentacja</p>
  <button class="heartBtn" onclick="hearts()">Więcej serduszek 💕</button>
  <footer>Małe żabki, wielkie szczęście ♡</footer>
</main>

<div class="modal" id="mediaModal" onclick="closeModal('mediaModal',event)">
  <div class="modalBox">
    <h2>🎬 Film / podcast 🐸💗</h2>
    <video id="podcastVideo" controls playsinline preload="metadata"><source src="Messenger_creation_927149730189873.mp4" type="video/mp4">Twoja przeglądarka nie obsługuje odtwarzania filmu.</video>
    <button class="closeBtn" onclick="closeModal('mediaModal')">Zamknij 💗</button>
  </div>
</div>

<div class="modal" id="articleModal" onclick="closeModal('articleModal',event)">
  <div class="modalBox">
    <h2>🌷 Człowiek jest istotą społeczną</h2>
    <div class="article">
      <p>Żyjemy wśród innych ludzi, tworzymy relacje i uczymy się od siebie nawzajem. Potrzeba przynależności sprawia, że chcemy być częścią grupy, czuć się akceptowani i mieć osoby, na których możemy polegać.</p>
      <h3>💗 Czym są postawy prospołeczne?</h3>
      <p>To zachowania, dzięki którym pomagamy innym i dbamy o wspólne dobro. Czasem wystarczy drobny gest, życzliwe słowo albo poświęcenie komuś chwili uwagi.</p>
      <h3>🌱 Jak możemy pomagać na co dzień?</h3>
      <ul><li>wysłuchać kogoś, kto potrzebuje rozmowy,</li><li>pomóc koledze lub koleżance w nauce,</li><li>reagować, gdy ktoś jest niesprawiedliwie traktowany,</li><li>współpracować i dbać o wspólne otoczenie.</li></ul>
      <h3>🤝 Dlaczego to ważne?</h3>
      <p>Życzliwość, empatia i współpraca wzmacniają więzi między ludźmi. Nawet mały dobry uczynek może mieć znaczenie — wspólne dobro zaczyna się od codziennych decyzji każdego z nas. 🌸</p>
    </div>
    <button class="closeBtn" onclick="closeModal('articleModal')">Zamknij 💗</button>
  </div>
</div>
<script>
function openVideo(){const modal=document.getElementById('mediaModal');const video=document.getElementById('podcastVideo');modal.style.display='flex';video.currentTime=0;video.play().catch(()=>{});}
function openArticle(){document.getElementById('articleModal').style.display='flex';}
function openPresentation(){window.open('https://canva.link/ynw851xbnq95apr','_blank');}
function closeModal(id,event){const modal=document.getElementById(id);if(event&&event.target!==modal)return;if(id==='mediaModal')document.getElementById('podcastVideo').pause();modal.style.display='none';}
function hearts(){for(let i=0;i<18;i++){const h=document.createElement('span');h.className='heart';h.textContent=['💗','💕','💖','♡'][Math.floor(Math.random()*4)];h.style.left=Math.random()*100+'vw';h.style.animationDelay=Math.random()*.8+'s';document.body.appendChild(h);setTimeout(()=>h.remove(),3500);}}
document.addEventListener('keydown',e=>{if(e.key==='Escape'){closeModal('mediaModal');closeModal('articleModal');}});
</script>
</body>
</html>

