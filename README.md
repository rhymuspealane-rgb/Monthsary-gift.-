<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy First Monthsary, Bebii ♡</title>
<style>
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0; min-height:100vh; color:#fff4f7;
  font-family:Georgia,"Times New Roman",serif;
  background:radial-gradient(circle at 50% 0%,#512738 0%,#21121b 38%,#08070a 100%);
  overflow-x:hidden;
}
body:before{
  content:""; position:fixed; inset:0; pointer-events:none; opacity:.12;
  background-image:radial-gradient(#fff 1px,transparent 1px);
  background-size:28px 28px;
}
#hearts{position:fixed;inset:0;pointer-events:none;overflow:hidden}
.heart{
  position:absolute;bottom:-30px;font-size:22px;opacity:.7;
  animation:float 7s linear forwards;
}
@keyframes float{
  0%{transform:translateY(0) rotate(0);opacity:0}
  15%{opacity:.75}
  100%{transform:translateY(-110vh) rotate(25deg);opacity:0}
}
.screen{
  min-height:100vh;display:flex;align-items:center;justify-content:center;
  padding:25px;
}
.hero{
  width:min(720px,100%);text-align:center;padding:55px 25px;
  border:1px solid rgba(255,190,210,.28);border-radius:32px;
  background:rgba(255,255,255,.065);
  box-shadow:0 25px 80px rgba(0,0,0,.55);
  backdrop-filter:blur(14px);
}
.big-heart{font-size:68px;animation:pulse 1.6s infinite}
@keyframes pulse{50%{transform:scale(1.12)}}
.kicker{
  letter-spacing:5px;text-transform:uppercase;color:#f4aec5;
  font-size:12px;margin-top:10px
}
h1{
  font-size:clamp(42px,10vw,82px);line-height:1.02;
  margin:18px 0 14px;color:#ffd5e2
}
.subtitle{font-size:19px;line-height:1.8;color:#e9d5dc;max-width:590px;margin:auto}
button{
  margin-top:28px;padding:15px 29px;border:0;border-radius:999px;
  background:#f5aec7;color:#28131c;font-weight:bold;font-size:16px;
  cursor:pointer;box-shadow:0 10px 30px rgba(245,174,199,.25);
  transition:.25s
}
button:hover{transform:translateY(-3px) scale(1.03)}
#gift{display:none}
.wrap{max-width:850px;margin:auto;padding:25px 18px 60px}
.card{
  margin-bottom:22px;padding:34px 25px;border-radius:27px;
  background:rgba(255,255,255,.065);
  border:1px solid rgba(255,190,210,.22);
  box-shadow:0 18px 55px rgba(0,0,0,.35);
  backdrop-filter:blur(10px)
}
h2{color:#ffc0d3;margin-top:0}
.letter{font-size:18px;line-height:1.9;color:#f8e8ed}
.signature{text-align:right;color:#ffb4ca;font-style:italic;margin-top:20px}
.reasons{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:12px}
.reason{
  padding:17px;border-radius:17px;
  background:rgba(255,182,205,.075);
  border:1px solid rgba(255,182,205,.15);line-height:1.55
}
.future{text-align:center;line-height:1.8;color:#ead6dc}
.secret{text-align:center;display:none;line-height:1.8;color:#ffd7e3}
.footer{text-align:center;color:#bfa3ad;font-size:13px;margin-top:35px}
</style>
</head>
<body>
<div id="hearts"></div>

<section class="screen" id="opening">
  <div class="hero">
    <div class="big-heart">♡</div>
    <div class="kicker">A little surprise made just for you</div>
    <h1>Happy First<br>Monthsary, Bebii</h1>
    <p class="subtitle">
      It's only been one month, but somehow you've already become
      such a beautiful part of my life. ♡
    </p>
    <button onclick="openGift()">Open Your Gift ♡</button>
  </div>
</section>

<main id="gift">
<div class="wrap">

  <section class="card">
    <h2>💌 A Letter For My Bebii</h2>
    <div class="letter">
      <p>To my dearest bebii,</p>
      <p>
        Happy first monthsary, my love. Even though we're miles apart,
        you have a way of making me feel close to you every single day.
        I'm grateful for every conversation, every laugh, every little
        moment, and every memory we're creating together.
      </p>
      <p>
        This first month may only be the beginning, but it already means
        so much to me. Thank you for your patience, your understanding,
        your kindness, and for choosing to stay even when distance makes
        things difficult.
      </p>
      <p>
        I may not always be beside you physically, but please remember
        that you're always in my thoughts and in my heart. I promise to
        keep choosing you, supporting you, and making our relationship
        worth every mile between us.
      </p>
      <p>
        I hope this is only the beginning of many more months, memories,
        dreams, calls, laughs, and adventures together. And someday,
        I hope we won't have to count the miles anymore because we'll
        finally be together.
      </p>
      <p>
        Thank you for being you, bebii. You make my days brighter, and
        I'm genuinely happy that I get to call you mine.
      </p>
      <div class="signature">I love you, always. ♡<br>— Your Boy</div>
    </div>
  </section>

  <section class="card">
    <h2>♡ Why You're Special To Me</h2>
    <div class="reasons">
      <div class="reason">♡ You make me smile even on difficult days.</div>
      <div class="reason">♡ You make the distance feel a little smaller.</div>
      <div class="reason">♡ You listen to me and understand me.</div>
      <div class="reason">♡ You make ordinary moments feel special.</div>
      <div class="reason">♡ You support me and my dreams.</div>
      <div class="reason">♡ You're simply you — and that's enough.</div>
    </div>
  </section>

  <section class="card future">
    <h2>🌙 Our Little Future</h2>
    <p>
      More calls. More laughs. More memories.<br>
      More monthsaries. More adventures.<br><br>
      And one day...<br>
      <strong>we'll finally be together. ♡</strong>
    </p>
  </section>

  <section class="card" style="text-align:center">
    <h2>🎁 One Last Surprise</h2>
    <button onclick="secretMessage()">Open My Secret Message ♡</button>
    <div class="secret" id="secret">
      <br>
      No matter how many miles are between us, my heart will always
      find its way back to you.<br><br>
      <strong>Happy First Monthsary, Bebii. ♡</strong><br>
      Here's to us, and to all the beautiful months ahead.
    </div>
  </section>

  <div class="footer">Made with love, especially for my bebii ♡</div>
</div>
</main>

<script>
function openGift(){
  document.getElementById("gift").style.display="block";
  document.getElementById("gift").scrollIntoView({behavior:"smooth"});
}
function secretMessage(){
  const x=document.getElementById("secret");
  x.style.display=x.style.display==="block"?"none":"block";
}
function floatingHeart(){
  const h=document.createElement("span");
  h.className="heart";
  h.textContent=["♡","♥","✦"][Math.floor(Math.random()*3)];
  h.style.left=Math.random()*100+"vw";
  h.style.fontSize=(14+Math.random()*22)+"px";
  h.style.animationDuration=(5+Math.random()*5)+"s";
  document.getElementById("hearts").appendChild(h);
  setTimeout(()=>h.remove(),10000);
}
setInterval(floatingHeart,850);
</script>
</body>
</html>
