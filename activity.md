---
layout: default
title: သတင်းနှင့် လှုပ်ရှားမှုများ
description: မော်ကွန်းတိုက်၏ လှုပ်ရှားဆောင်ရွက်မှုများနှင့် ရပ်ရွာ၏ကူညီပံ့ပိုးမှုများ
---

# သတင်းနှင့် လှုပ်ရှားမှုများ

<p class="subtitle">မော်ကွန်းတိုက်၏ လှုပ်ရှားဆောင်ရွက်မှုများနှင့် ရပ်ရွာ၏ကူညီပံ့ပိုးမှုများ</p>

<div class="news-ticker">
  <span>📢 နောက်ဆုံးရသတင်း - တပ်ကုန်းမြို့နယ်အတွင်း မိုးရာသီသစ်ပင်စိုက်ပျိုးပွဲတော် ကျင်းပပြီးစီး</span>
</div>

<br>

<div class="news-grid">
  <div class="news-card">
    <div class="thumbnail">🖼️</div>
    <div class="content">
      <h3><a href="#">နဝင်းချောင်းသန့်ရှင်းရေးလှုပ်ရှားမှု</a></h3>
      <p class="date">၂၀၂၆၊ ဇွန် ၁၅</p>
    </div>
  </div>

  <div class="news-card">
    <div class="thumbnail">🖼️</div>
    <div class="content">
      <h3><a href="#">ရပ်ရွာပံ့ပိုးမှုဖြင့် စာကြည့်တိုက်အသစ်ဖွင့်လှစ်</a></h3>
      <p class="date">၂၀၂၆၊ မေ ၂၀</p>
    </div>
  </div>
</div>

<br>
<hr>

<p class="back-home"><a href="./index.html">← ပင်မစာမျက်နှာသို့ ပြန်သွားရန်</a></p>

<style>
  .subtitle { text-align: center; font-weight: bold; color: #555; margin-bottom: 2rem; }
  
  /* Dynamic Marquee */
  .news-ticker { background: #fff3cd; padding: 10px; border-left: 5px solid #ffc107; margin-bottom: 2rem; overflow: hidden; white-space: nowrap; }
  .news-ticker span { display: inline-block; padding-left: 100%; animation: marquee 15s linear infinite; }
  @keyframes marquee { 0% { transform: translate(0, 0); } 100% { transform: translate(-100%, 0); } }

  /* Grid Layout */
  .news-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
  .news-card { display: flex; align-items: center; background: #f9f9f9; padding: 15px; border-radius: 8px; border: 1px solid #ddd; }
  .thumbnail { width: 80px; height: 80px; background: #ccc; display: flex; align-items: center; justify-content: center; margin-right: 15px; border-radius: 4px; }
  .content h3 { margin: 0; font-size: 1.1rem; }
  .content h3 a { text-decoration: none; color: #155799; }
  .date { font-size: 0.8rem; color: #777; margin: 5px 0 0 0; }

  /* Mobile Adjustment */
  @media (max-width: 768px) {
    .news-grid { grid-template-columns: 1fr; }
  }
  
  .back-home { margin-top: 2rem; }
</style>
