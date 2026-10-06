gangimario112255
<html lang="ja">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>百合大好き協会</title>
<link href="https://fonts.googleapis.com/css2?family=Zen+Maru+Gothic:wght@400;700&family=Yomogi&display=swap" rel="stylesheet">
<style>
:root{box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);
--bg1:#ffe3f0;--bg2:#e8dcff;--bg3:#d9f5ea;--card:rgba(255,255,255,.82);--text:#6b4a66;--pink:#ff8fbf;--purple:#a98be8;--mint:#7fd6b8;--shadow:0 10px 30px rgba(214,97,154,.2)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg1:#3a2236;--bg2:#2b2447;--bg3:#1f3a38;--card:rgba(70,48,80,.75);--text:#ffe9f5;--shadow:0 10px 30px rgba(0,0,0,.4)}}
:root[data-theme="dark"]{--bg1:#3a2236;--bg2:#2b2447;--bg3:#1f3a38;--card:rgba(70,48,80,.75);--text:#ffe9f5;--shadow:0 10px 30px rgba(0,0,0,.4)}
html{scroll-padding-top:env(safe-area-inset-top,0px);scroll-behavior:smooth}
*{box-sizing:border-box}
body{margin:0;font-family:"Zen Maru Gothic","Hiragino Maru Gothic ProN","Yu Gothic",sans-serif;color:var(--text);line-height:1.9;background:linear-gradient(160deg,var(--bg1),var(--bg2) 55%,var(--bg3));background-attachment:fixed;overflow-x:hidden}
.petals{position:fixed;inset:0;pointer-events:none;z-index:0;overflow:hidden}
.petal{position:absolute;top:-40px;font-size:20px;animation:fall linear infinite;opacity:.8}
@keyframes fall{to{transform:translate(60px,110vh) rotate(360deg)}}
main,header,footer{position:relative;z-index:1}
nav{display:flex;gap:8px;flex-wrap:wrap;justify-content:center;padding:14px 12px}
nav a{background:var(--card);color:var(--text);text-decoration:none;padding:6px 16px;border-radius:99px;font-size:14px;box-shadow:var(--shadow);transition:.3s}
nav a:hover{transform:translateY(-3px) scale(1.05)}
.hero{text-align:center;padding:40px 20px 70px}
.rings{position:relative;width:200px;height:120px;margin:0 auto 10px}
.rings i{position:absolute;top:10px;width:100px;height:100px;border-radius:50%;mix-blend-mode:multiply;animation:float 5s ease-in-out infinite}
.rings i:first-child{left:20px;background:radial-gradient(circle at 35% 30%,#fff 0 8%,#ffb3d3 40%,#ff8fbf)}
.rings i:last-child{right:20px;background:radial-gradient(circle at 35% 30%,#fff 0 8%,#d3c2ff 40%,#a98be8);animation-delay:-2.5s}
@keyframes float{50%{transform:translateY(-14px)}}
h1{font-family:"Yomogi","Zen Maru Gothic",sans-serif;font-size:clamp(34px,9vw,60px);margin:6px 0;line-height:1.3;background:linear-gradient(90deg,#ff7fb5,#a98be8,#5ec9a8);-webkit-background-clip:text;background-clip:text;color:transparent}
.sub{font-size:clamp(15px,4vw,19px)}
.btn{display:inline-block;margin-top:22px;padding:14px 36px;border:0;border-radius:99px;font:700 17px inherit;font-family:inherit;color:#fff;background:linear-gradient(135deg,#ff8fbf,#b49aff);box-shadow:0 8px 20px rgba(255,143,191,.5);cursor:pointer;transition:.3s}
.btn:hover{transform:scale(1.08) rotate(-2deg)}
section{max-width:900px;margin:0 auto 54px;padding:0 18px}
h2{text-align:center;font-family:"Yomogi","Zen Maru Gothic",sans-serif;font-size:28px;margin-bottom:22px}
h2::before,h2::after{content:"🌸";margin:0 10px;font-size:20px}
.card{background:var(--card);border-radius:32px;padding:26px 28px;box-shadow:var(--shadow);backdrop-filter:blur(6px)}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:18px}
.grid .card{text-align:center;transition:.4s}
.grid .card:hover{transform:translateY(-8px) rotate(1.5deg)}
.grid .e{font-size:40px;display:block}
.grid b{display:block;margin:4px 0;color:var(--pink)}
.steps{display:flex;gap:10px;flex-wrap:wrap;justify-content:center}
.step{flex:1 1 150px;text-align:center;padding:18px 10px;border-radius:50% 50% 28px 28px/60% 60% 28px 28px;background:var(--card);box-shadow:var(--shadow)}
.step span{font-size:34px;display:block}
ol{margin:0;padding-left:1.3em}
li::marker{color:var(--pink);font-weight:700}
.toast{position:fixed;left:50%;bottom:calc(30px + env(safe-area-inset-bottom,0px));transform:translate(-50%,120px);background:#ff8fbf;color:#fff;padding:14px 26px;border-radius:99px;box-shadow:var(--shadow);transition:.5s;z-index:5;max-width:90vw;text-align:center}
.toast.on{transform:translate(-50%,0)}
footer{text-align:center;padding:30px 16px 50px;font-size:14px}
@media (prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
</style>
  <link rel="icon" type="image/png" href="icon.png">
<link rel="apple-touch-icon" href="apple-touch-icon.png">
<meta name="theme-color" content="#ffb7d5">
<meta name="description" content="女の子同士のやわらかくて尊い関係を愛でる、ふわふわの集まり。百合大好き協会へようこそ🌸">
<meta property="og:type" content="website">
<meta property="og:site_name" content="百合大好き協会">
<meta property="og:title" content="百合大好き協会 🌸">
<meta property="og:description" content="ふわふわ、きらきら、ゆりゆり。好きって言っていいんだよ、ここでは。">
<meta property="og:url" content="https://babamagogonin-lang.github.io/gangimario112255/">
<meta property="og:image" content="https://babamagogonin-lang.github.io/gangimario112255/ogp.png">
<meta name="twitter:card" content="summary_large_image">
  <link rel="icon" type="image/png" href="icon.png?v=3">
</head>
<body>
<div class="petals" id="petals"></div>
<header>
<nav><a href="#about">協会とは</a><a href="#act">活動</a><a href="#rank">会員ランク</a><a href="#rule">やくそく</a><a href="#join">入会</a><a href="#card">会員証</a><a href="#gacha">ガチャ</a></nav>
<div class="hero">
<div class="rings"><i></i><i></i></div>
<h1>百合大好き協会</h1>
<p class="sub">ふわふわ、きらきら、ゆりゆり。<br>好きって言っていいんだよ、ここでは 🫧</p>
<button class="btn" onclick="toast('ようこそ、つぼみさん！🌷 いっしょにお茶しましょうね')">🌸 なかまになる</button>
</div>
</header>
  <section id="card"><h2>会員証をつくろう</h2>
<div class="card tool">
<p>ニックネームとランクを選ぶと、あなただけの会員証ができるよ🎀</p>
<input id="cName" type="text" maxlength="12" placeholder="ニックネーム">
<select id="cRank"><option>つぼみ</option><option>ひらき</option><option>まんかい</option><option>ゆりぞの</option></select>
<br><button class="btn" id="cMake">✨ つくる</button>
<canvas id="cCanvas" width="640" height="400" hidden></canvas>
<a class="btn" id="cSave" download="yuri-kai-card.png" hidden>💾 画像を保存</a>
</div></section>

<section id="gacha"><h2>今日の尊い一言ガチャ</h2>
<div class="card tool">
<p>ボタンをぽんっと押してね。今日のあなたに、ふわっとした一言をお届け🫧</p>
<button class="btn" id="gBtn">🎰 ガチャをまわす</button>
<div class="gacha-box" id="gBox">ここに今日の一言がでるよ✨</div>
</div></section>
<section id="rec"><h2>おすすめ作品ガチャ</h2>
<div class="card rec">
<p>ボタンを押すと、協会おすすめの作品がひとつ出てくるよ📚<br>ネタバレなしのひとこと紹介つき！</p>
<button class="btn" id="recBtn">🎰 作品をひく</button>
<div class="rec-box" id="recBox">ここにおすすめ作品がでるよ✨</div>
</div></section>
<main>
<section id="about"><h2>協会とは</h2>
<div class="card"><p>女の子同士の、やわらかくて尊い関係をみんなで愛でる、ふわふわの集まりです。恋でも友情でも、名前のつかない気持ちでも、ここでは全部まるごと「尊い」と呼びます。むずかしいルールはありません。紅茶でも片手に、ゆっくりしていってくださいね ☁️</p></div></section>

<section id="act"><h2>みんなの活動</h2>
<div class="grid">
<div class="card"><span class="e">💎</span><b>今月の尊いコーナー</b>集まった「尊かった！」をご紹介</div>
<div class="card"><span class="e">📚</span><b>おすすめ作品ひろば</b>ネタバレ配慮つきで紹介</div>
<div class="card"><span class="e">☕</span><b>おしゃべりサロン</b>お題でゆるっと語り合い</div>
<div class="card"><span class="e">🎨</span><b>ふわふわ創作部屋</b>絵も小説も、感想は「好き」から</div>
<div class="card"><span class="e">🌷</span><b>季節のお花まつり</b>春は桜、冬は雪の企画も</div>
</div></section>

<section id="rank"><h2>会員ランク</h2>
<div class="steps">
<div class="step"><span>🌱</span><b>つぼみ</b><br>入会したて</div>
<div class="step"><span>🌷</span><b>ひらき</b><br>好きを語る</div>
<div class="step"><span>🌸</span><b>まんかい</b><br>常連さん</div>
<div class="step"><span>👑</span><b>ゆりぞの</b><br>名誉会員</div>
</div></section>

<section id="rule"><h2>みんなのやくそく</h2>
<div class="card"><ol>
<li>好きなものを好きと言える場所にします</li>
<li>誰かの「好き」を笑いません</li>
<li>作品と作者さんへの敬意を忘れません</li>
<li>ネタバレは、ひとこと声をかけてから</li>
<li>しんどい日は休んでOK。頑張る場所じゃないよ</li>
</ol></div></section>

<section id="join"><h2>入会案内</h2>
<div class="card" style="text-align:center"><p>入会資格は「百合が好き」という気持ちだけ。<br>会費はありません 🤍</p>
<button class="btn" onclick="toast('入会ありがとう！🎀 ゆりっこ名簿にそっと書きました')">🎀 ゆりっこになる</button></div></section>
</main>
<section id="discord"><h2>Discordでおしゃべり</h2>
<div class="card discord">
<p>協会のみんなは、Discordサーバーでおしゃべりしています💬<br>おすすめ作品の話も、今日の「尊い」も、気軽に聞かせてくださいね。</p>
<a class="btn" href="https://discord.gg/DythYmXWHp" target="_blank" rel="noopener">🫧 Discordにあそびにいく</a>
<small>リンク：discord.gg/DythYmXWHp</small>
</div></section>
<footer>© 百合大好き協会 ｜ みんなの「好き」で育つお花畑 🌸</footer>
<button class="fab" id="themeBtn" aria-label="ライト・ダーク切り替え">🌙</button>
<button class="fab" id="topBtn" aria-label="ページの一番上へ">🌷</button>
<div class="toast" id="toast"></div>
<script>
var p=document.getElementById('petals'),e=['🌸','🌷','🤍','🫧','💮'];
for(var i=0;i<18;i++){var s=document.createElement('span');s.className='petal';s.textContent=e[i%5];
s.style.left=Math.random()*100+'%';s.style.fontSize=(14+Math.random()*16)+'px';
s.style.animationDuration=(9+Math.random()*10)+'s';s.style.animationDelay=(-Math.random()*15)+'s';p.appendChild(s)}
function toast(m){var t=document.getElementById('toast');t.textContent=m;t.classList.add('on');setTimeout(function(){t.classList.remove('on')},3200)}
  var ranks={'つぼみ':['🌱','#d9f5ea','#ffe3f0'],'ひらき':['🌷','#ffe3f0','#e8dcff'],'まんかい':['🌸','#ffd0e6','#d9c9ff'],'ゆりぞの':['👑','#ffe9a8','#ffc2de']};
document.getElementById('cMake').onclick=function(){
var n=(document.getElementById('cName').value||'').trim()||'ゆりっこ',r=document.getElementById('cRank').value,v=ranks[r];
var c=document.getElementById('cCanvas'),x=c.getContext('2d'),W=640,H=400,f='"Zen Maru Gothic","Yu Gothic",sans-serif';
var g=x.createLinearGradient(0,0,W,H);g.addColorStop(0,v[1]);g.addColorStop(1,v[2]);
x.fillStyle=g;x.fillRect(0,0,W,H);
x.globalAlpha=.55;x.fillStyle='#ff8fbf';x.beginPath();x.arc(500,110,70,0,7);x.fill();
x.fillStyle='#a98be8';x.beginPath();x.arc(560,110,70,0,7);x.fill();x.globalAlpha=1;
x.strokeStyle='#fff';x.lineWidth=10;x.strokeRect(14,14,W-28,H-28);
x.fillStyle='#6b4a66';x.textAlign='left';
x.font='700 30px '+f;x.fillText('百合大好き協会 会員証',40,70);
x.font='700 28px '+f;x.fillText(v[0]+' '+r+'会員',40,145);
var s=56;x.font='700 '+s+'px '+f;
while(x.measureText(n).width>540&&s>20){s-=2;x.font='700 '+s+'px '+f}
x.fillText(n,40,250);
x.font='20px '+f;
x.fillText('No.'+('000'+Math.floor(Math.random()*10000)).slice(-4)+'　入会日 '+new Date().toLocaleDateString('ja-JP'),40,320);
x.fillText('🌸 好きって言っていいんだよ、ここでは',40,355);
c.hidden=false;var a=document.getElementById('cSave');a.href=c.toDataURL('image/png');a.hidden=false;
toast('会員証ができたよ！🎀');
};
var gN=['今日はふたりで、おそろいのものをひとつ見つけられそう🍓','ふと目が合ったとき、時間がゆっくり流れるかも☁️','おすすめの百合作品を、だれかに1つ教えてみよう📚','帰り道で同じ歩幅になる、そんな尊さに出会えるよ🌆','「好き」を隠さなくていい日。思いっきり語ろう🌸','となりの席の気配だけで、胸がきゅっとするかも🫧','紅茶を2つ淹れて、ひとくちずつ分け合う日🍵','今日の尊いは、きっと何気ない会話の中にあるよ💬','ちいさな「ありがとう」が、だれかの花を咲かせます🌷','しんどい日は休んで大丈夫。尊いは逃げないよ🤍','名前を呼ぶ声が、いつもより少しやさしい日🎀','雨の日に1本の傘を分け合う、そんな物語に出会えそう☔','好きな作品をもう一度ひらくと、新しい発見があるよ📖','今日のあなたは、それだけで誰かの推しです💐'];
var gR=['ふたりの影が、夕焼けの中でそっと重なる…そんな奇跡の予感🌇','星空の下で交わす内緒話。今日は世界でいちばん尊い夜🌙','大好きな作品の新しい展開に、思わず叫んじゃうかも！🎆','ゆりぞの名誉会員レベルの尊さが、今日あなたに降ってきます👑'],gLast='';
document.getElementById('gBtn').onclick=function(){
var b=document.getElementById('gBox'),rare=Math.random()<.12,a=rare?gR:gN,t;
do{t=a[Math.floor(Math.random()*a.length)]}while(t===gLast);
gLast=t;b.textContent=(rare?'✨レア！✨ ':'')+t;
b.classList.remove('pop');void b.offsetWidth;b.classList.add('pop');
};
  var recs=[
['やがて君になる','「好き」がわからない子と、まっすぐな先輩の、ゆっくり進む学園ものだよ🌙'],
['私の百合はお仕事です！','「百合を演じるお仕事」と、本当の気持ちのあいだで揺れるお話だよ☕'],
['ささやくように恋を唄う','そっと育っていく気持ちを、やさしい空気で描く恋の物語だよ🎶'],
['青い花','少女たちの揺れる気持ちをていねいに描いた、静かで美しい名作だよ💐'],
['マリア様がみてる','学園の「姉妹」の絆を描く、百合の定番として愛される作品だよ🌹'],
['ゆるゆり','ほのぼのした日常で、ふわっと広がる女の子たちの距離感が魅力だよ🍥'],
['安達としまむら','ふたりの時間が、ゆっくり特別になっていく物語だよ🏀']
],recLast=-1;
document.getElementById('recBtn').onclick=function(){
var i;do{i=Math.floor(Math.random()*recs.length)}while(recs.length>1&&i===recLast);
recLast=i;var b=document.getElementById('recBox');
b.innerHTML='<b>'+recs[i][0]+'</b><span>'+recs[i][1]+'</span>';
b.classList.remove('pop');void b.offsetWidth;b.classList.add('pop');
};
var sp=['✨','🌸','⭐','💖','🫧'],lastS=0;
function spark(x,y,n){for(var k=0;k<n;k++){var el=document.createElement('span');el.className='sparkle';
el.textContent=sp[Math.floor(Math.random()*sp.length)];el.style.left=x+'px';el.style.top=y+'px';
el.style.setProperty('--dx',(Math.random()*80-40)+'px');el.style.setProperty('--dy',(Math.random()*80-10)+'px');
document.body.appendChild(el);setTimeout(function(t){t.remove()},900,el)}}
document.addEventListener('pointerdown',function(ev){spark(ev.clientX,ev.clientY,6)});
document.addEventListener('pointermove',function(ev){if(ev.pointerType!=='mouse')return;var now=Date.now();if(now-lastS<70)return;lastS=now;spark(ev.clientX,ev.clientY,1)});
var th=document.getElementById('themeBtn');
th.textContent=matchMedia('(prefers-color-scheme:dark)').matches?'☀️':'🌙';
th.onclick=function(){var d=document.documentElement.getAttribute('data-theme');
var dark=d?d==='dark':matchMedia('(prefers-color-scheme:dark)').matches;
document.documentElement.setAttribute('data-theme',dark?'light':'dark');th.textContent=dark?'🌙':'☀️'};
var tb=document.getElementById('topBtn');
tb.onclick=function(){scrollTo({top:0,behavior:'smooth'})};
addEventListener('scroll',function(){tb.classList.toggle('show',scrollY>300)});
</script>
</body>
</html>
