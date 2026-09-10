<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Just For You ❤️</title>
<style>
*{box-sizing:border-box}body{margin:0;min-height:100vh;display:flex;align-items:center;justify-content:center;
font-family:Georgia,serif;color:#fff;background:linear-gradient(135deg,#180016,#64123e,#ff6b91);overflow:hidden}
.card{width:min(92%,720px);padding:38px 26px;text-align:center;border:1px solid #ffffff40;border-radius:28px;
background:#ffffff14;backdrop-filter:blur(16px);box-shadow:0 25px 80px #0007}
h1{font-size:clamp(38px,9vw,70px);margin:5px 0 12px}.sub{font-size:21px}.heart{font-size:64px;animation:p 1.3s infinite}
p{font-size:19px;line-height:1.7;color:#ffe9f1}button{padding:15px 25px;border:0;border-radius:30px;background:#fff;
color:#8d2456;font-weight:bold;font-size:17px;cursor:pointer}.hidden{display:none}.note{margin-top:24px}
@keyframes p{50%{transform:scale(1.18)}}.float{position:fixed;top:-30px;animation:f linear forwards}
@keyframes f{to{top:110vh;transform:rotate(360deg)}}
</style>
</head>
<body>
<div class="card">
<div class="heart">❤️</div>
<div class="sub">Hey beautiful...</div>
<h1>This is for you.</h1>
<p>
I know you're feeling a little low lately. I won't ask you to suddenly be happy.
I just want you to remember that you don't have to handle everything alone.
</p>
<p>
You are important. You are loved. And you deserve soft days, genuine smiles,
beautiful memories and people who remind you how special you are.
</p>
<p><b>Your birthday is on the 12th...</b><br>
but I don't need a birthday to celebrate you. 🥹❤️</p>
<button onclick="surprise()">Tap for your little surprise 💌</button>
<div id="x" class="hidden note">
<p>
If today feels heavy, take it slowly. Breathe. Rest. Smile when you can.
And remember: <b>there is someone who is genuinely grateful that you exist.</b>
</p>
<p>So for today, forget about being perfect. Just be you. 🫶🏻</p>
<p><b>You're worth celebrating. Always. ❤️</b></p>
</div>
</div>
<script>
function surprise(){
document.getElementById('x').classList.remove('hidden');
for(let i=0;i<35;i++){let e=document.createElement('span');e.className='float';
e.textContent=['❤️','💕','✨','🌸'][Math.floor(Math.random()*4)];
e.style.left=Math.random()*100+'vw';e.style.animationDuration=3+Math.random()*4+'s';
document.body.appendChild(e);setTimeout(()=>e.remove(),8000)}
}
</script>
</body></html>
