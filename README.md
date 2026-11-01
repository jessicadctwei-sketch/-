# -<!DOCTYPE html>
<html lang="zh-Hant">
<head>
<meta charset="utf-8">
<meta name="format-detection" content="telephone=no">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>靜心品的製作過程與小知識</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+TC:wght@500;700&family=Noto+Sans+TC:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#EEF1EE; --surface:#F8FAF8; --ink:#222E29; --muted:#5C6B64; --line:#D3DBD6; --accent:#4A6A5B; --accent-soft:#DCE6E0; --note:#8A6D3B; --note-bg:#F3EBD9;
  box-sizing:border-box; padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){--bg:#171D1A; --surface:#1F2723; --ink:#E6ECE8; --muted:#9FAEA6; --line:#33413A; --accent:#8DB7A0; --accent-soft:#26332C; --note:#E0C68A; --note-bg:#33301F;}
}
:root[data-theme="dark"]{--bg:#171D1A; --surface:#1F2723; --ink:#E6ECE8; --muted:#9FAEA6; --line:#33413A; --accent:#8DB7A0; --accent-soft:#26332C; --note:#E0C68A; --note-bg:#33301F;}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:"Noto Sans TC","PingFang TC","Microsoft JhengHei",sans-serif;line-height:1.85;font-size:17px}
main{max-width:640px;margin:0 auto;padding:0 22px 72px}
h1,h2,h3{font-family:"Noto Serif TC","Songti TC",serif;line-height:1.4;margin:0}
.hero{padding:72px 0 48px;border-bottom:1px solid var(--line)}
.hero h1{font-size:clamp(34px,9vw,48px);font-weight:700;letter-spacing:.04em}
.hero p{margin:20px 0 0;color:var(--muted);max-width:30em}
section{padding:48px 0 0}
h2{font-size:26px;font-weight:700;letter-spacing:.03em;margin-bottom:8px}
.lead{color:var(--muted);margin:0 0 28px}
.todo{background:var(--note-bg);color:var(--note);border-radius:6px;padding:1px 8px;font-size:.92em}
.steps{list-style:none;margin:0;padding:0;counter-reset:s}
.steps li{counter-increment:s;position:relative;padding:0 0 30px 56px;border-left:0}
.steps li::before{content:counter(s);position:absolute;left:0;top:0;width:36px;height:36px;border-radius:50%;background:var(--accent);color:var(--bg);font-family:"Noto Serif TC",serif;font-weight:700;display:grid;place-items:center}
.steps li::after{content:"";position:absolute;left:17px;top:44px;bottom:8px;width:2px;background:var(--line)}
.steps li:last-child::after{display:none}
.steps h3{font-size:19px;margin-bottom:4px}
.steps p{margin:0;color:var(--muted)}
.photo{margin-top:12px;aspect-ratio:4/3;border-radius:10px;background:var(--accent-soft);color:var(--muted);display:grid;place-items:center;font-size:14px;text-align:center;padding:12px}
.mat{display:grid;gap:12px}
.mat div{background:var(--surface);border:1px solid var(--line);border-radius:10px;padding:16px 18px}
.mat strong{display:block;font-family:"Noto Serif TC",serif;font-size:18px;margin-bottom:2px}
.mat span{color:var(--muted);font-size:15px}
details{border-bottom:1px solid var(--line);padding:4px 0}
summary{cursor:pointer;list-style:none;padding:14px 28px 14px 0;font-family:"Noto Serif TC",serif;font-weight:500;font-size:18px;position:relative}
summary::-webkit-details-marker{display:none}
summary::after{content:"+";position:absolute;right:4px;top:12px;font-size:24px;color:var(--accent);transition:transform .2s}
details[open] summary::after{transform:rotate(45deg)}
summary:focus-visible,a:focus-visible{outline:2px solid var(--accent);outline-offset:3px;border-radius:4px}
details p{margin:0 0 16px;color:var(--muted)}
.note{background:var(--surface);border-left:3px solid var(--accent);padding:16px 18px;border-radius:0 10px 10px 0;color:var(--muted);font-size:15px}
.contact{margin-top:48px;padding:28px 22px;background:var(--accent);color:var(--bg);border-radius:14px}
.contact h2{color:var(--bg);font-size:22px}
.contact p{margin:8px 0 0;opacity:.92}
footer{margin-top:40px;color:var(--muted);font-size:13px;text-align:center}
@media (prefers-reduced-motion:reduce){summary::after{transition:none}}
.hero-img{margin:32px 0 0;border-radius:14px;overflow:hidden}.hero-img img{display:block;width:100%;height:auto;max-height:560px;object-fit:cover;object-position:50% 70%}
.step-img{margin:12px 0 0;border-radius:10px;overflow:hidden}.step-img img{display:block;width:100%;aspect-ratio:4/3;object-fit:cover;object-position:50% 72%}
.proof{margin:14px 0 0}.proof img{display:block;width:100%;height:auto;border-radius:8px}.proof figcaption{margin-top:6px;font-size:13px;color:var(--muted)}
</style>
</head>

<body>
<main>
<header class="hero">
  <h1>天然的香，<br>安心地用</h1>
  <p style="font-family:'Noto Serif TC','Songti TC',serif;font-weight:700;font-size:20px;letter-spacing:.06em;color:var(--accent)">竹云 Zu Yun<br><span style="font-size:16px;font-weight:500;letter-spacing:.08em">靜心首選沉香品牌</span></p>
  <p>香從哪裡來、裡面有什麼、怎麼用才安心，這一頁一次說清楚。</p>
  <figure class="hero-img"><img src="images/hero.jpg" alt="桌上點燃的線香，輕煙緩緩上升，背景有人坐在窗邊安靜閱讀"></figure>
</header>

<section id="care">
  <h2>我們在意的三件事</h2>
  <p class="lead">選香，最重要的是知道自己點的是什麼。</p>
  <div class="mat">
    <div><strong>看得見的天然香材</strong><span>以沉香等天然香材為主，樣貌與來源都能清楚說明。</span><br><span><strong style="display:inline;font-size:inherit;font-family:inherit;color:var(--accent)">香材產地：</strong>越南、柬埔寨、新馬地區、印尼</span></div>
    <div><strong>配方越單純越好</strong><span>嚴格堅持天然與認證規範。</span><br><span>不含香精、化學成分、化學黏著劑、染色劑，並經過 SGS 認證，符合 CNS 標準。</span></div>
    <div><strong>公開、透明地說明</strong><span>從選材、製作到使用方式都公開說明，也誠實提醒香氣感受因人而異，讓你自己判斷適不適合。</span><br><figure class="proof"><img src="images/brand.webp" alt="竹云品牌介紹：台灣靜心沉香品牌首選，五十年老香廠製香底蘊，線香、盤香與無黏香產品"><figcaption>品牌介紹</figcaption></figure><figure class="proof"><img src="images/process.webp" alt="從原料到成香，層層把關：五步驟製作流程、純天然原料標示、SGS 與 CNS 15047 檢驗、品牌據點與香道文化"><figcaption>從原料到成香，層層把關</figcaption></figure></div>
  </div>
</section>

<section id="process">
  <h2>製作過程</h2>
  <p class="lead">從選材到出貨，每一步都想讓你看得安心。</p>
  <ol class="steps">
    <li><h3>挑選天然香材</h3><p><span>早期收購於原始沉香林，所以天然野生的沉香數量極為稀少。竹云的香品並非量產化，會有斷貨或絕版的情況，這是天然沉香的特色。做沉香是事業，更是善業，期望客人買到純天然野生香品，是我們的堅持。</span></p><figure class="step-img"><img src="images/step1.jpg" alt="一堆深褐色的木片近拍，可見細密的木紋"></figure></li>
    <li><h3>清潔與前置處理</h3><p><span>挑除雜質、陰乾、研磨等繁複嚴謹工序。</span></p><figure class="step-img"><img style="object-position:50% 40%" src="images/step2.jpg" alt="製香工坊裡的篩粉器具與袋裝香料粉"></figure></li>
    <li><h3>成形與自然陰乾</h3><p>製成線香、盤香、立香等各種形式香品。</p><p style="margin-top:10px">竹云以單品沉香為主，除了獨立沉香材料以外，線香或盤香會添加適量比例的天然黏粉。黏粉份量多寡會影響其韻味，竹云以最少比例製作，需要精準、獨家的配比，並無再添加額外物質，保存最優質的沉香天選氣韻。</p><p style="margin-top:10px">而無黏香品成分更單純，連黏粉都未添加，是資深或對氣味講究的香友首選。</p><figure class="step-img"><img style="object-position:50% 60%" src="images/step3.jpg" alt="工坊裡金屬網盤上整齊排列、等待陰乾的盤香"></figure></li>
    <li><h3>品質檢查與靜置</h3><p><span>成型完工後進行品質檢驗，通過 SGS 與 CNS 檢驗規範，符合 CNS 15047。</span></p></li>
    <li><h3>包裝出貨</h3><p><span>香品包裝，放入香心語詩籤。<br>出貨包裝，提供客戶優質體驗與商品。</span></p></li>
  </ol>
</section>

<section id="kinds">
  <h2>香品種類，怎麼選</h2>
  <p class="lead">我們提供以下四種香品，簡單介紹給你參考。</p>
  <div class="mat">
    <div><strong>盤香</strong><span>盤成一圈圈的香，燃燒時間較長，適合在家安靜獨處時點。</span></div>
    <div><strong>臥香、線香</strong><span>橫放或直立使用，搭配香器點燃，是最常見的形式。</span></div>
    <div><strong>無黏香</strong><span>不另外加入黏粉，主要以香材本身製成，味道更接近原料。</span></div>
    <div><strong>香粉</strong><span>香材研磨成粉，搭配香爐或香篆使用。</span></div>
  </div>
</section>

<section id="safety">
  <h2>安心使用小提醒</h2>
  <p class="lead">天然不等於零風險，任何燃燒都會產生煙霧，正確使用更重要。</p>
  <details><summary>點香時要注意通風</summary><p>點香時請保持空氣流通，避免在密閉的小空間長時間燃燒。</p></details>
  <details><summary>防火與擺放</summary><p>請使用耐熱香器，遠離窗簾、紙張與易燃物。人離開前務必確認香已熄滅。</p></details>
  <details><summary>哪些人要特別小心？</summary><p>孕婦、嬰幼兒、寵物，以及氣喘或呼吸道敏感的人，使用前請先諮詢醫師，或改在通風處短時間使用。</p></details>
  <details><summary>選購時可以問什麼？</summary><p>可以請店家說明香材名稱、產地，以及是否含有香精、黏粉或染色劑，說得清楚的比較讓人放心。</p></details>
  <details><summary>要怎麼保存？</summary><p>放在乾燥、避光的地方並密封，避免受潮，香味與燃燒狀況會比較穩定。</p></details>
</section>

<section>
  <p class="note">本頁為品牌理念與生活分享，香氣與靜心的感受因人而異。香品非醫療用途，不具治療或改善疾病的功能，也不能取代專業醫療建議。</p>
</section>

<div class="contact">
  <h2>想多了解一點？</h2>
  <p style="margin-top:14px"><a href="https://lin.ee/u8qrQbv" target="_blank" rel="noopener noreferrer" style="display:block;color:inherit;text-decoration:none;border:1px solid currentColor;border-radius:10px;padding:10px 14px">LINE 加好友領 300 元券：@zuyun</a><a href="https://www.instagram.com/zuyunincense/" target="_blank" rel="noopener noreferrer" style="display:block;color:inherit;text-decoration:none;border:1px solid currentColor;border-radius:10px;padding:10px 14px;margin-top:10px">Instagram</a><a href="https://reurl.cc/MWEXQn" target="_blank" rel="noopener noreferrer" style="display:block;color:inherit;text-decoration:none;border:1px solid currentColor;border-radius:10px;padding:10px 14px;margin-top:10px">Facebook</a><a href="https://www.zuyunincense.com/" target="_blank" rel="noopener noreferrer" style="display:block;color:inherit;text-decoration:none;border:1px solid currentColor;border-radius:10px;padding:10px 14px;margin-top:10px">竹云官網</a><span style="display:block;margin-top:14px;padding:0 2px">客服電話：0985-965-795</span><span style="display:block;margin-top:14px;padding:0 2px"><strong>實體門市</strong><br>台南大遠百成功店 6F<br>高雄夢時代店 3F<br>高雄漢神百貨本館 6F</span></p>
</div>
<footer>© 竹云沉香 ZuYunIncense</footer>
</main>
</body>
</html>
