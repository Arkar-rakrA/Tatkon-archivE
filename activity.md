---
layout: default
title: သတင်းနှင့် လှုပ်ရှားမှုများ
description: မော်ကွန်းတိုက်၏ လှုပ်ရှားဆောင်ရွက်မှုများနှင့် ရပ်ရွာ၏ကူညီပံ့ပိုးမှုများ
---

<div class="main-content">
  <h1>သတင်းနှင့် လှုပ်ရှားမှုများ</h1>
  <p class="subtitle">မော်ကွန်းတိုက်၏ လှုပ်ရှားဆောင်ရွက်မှုများနှင့် ရပ်ရွာ၏ကူညီပံ့ပိုးမှုများ</p>

  <div class="news-ticker">
    <span>📢 နောက်ဆုံးရသတင်း - တပ်ကုန်းမြို့နယ်အတွင်း မိုးရာသီသစ်ပင်စိုက်ပျိုးပွဲတော် ကျင်းပပြီးစီး</span>
  </div>

  <div class="news-grid">
    <div class="news-card">
      <div class="thumbnail">🖼️</div>
      <div class="content">
        <h3><a href="#">နဝင်းချောင်းသန့်ရှင်းရေးလှုပ်ရှားမှု</a></h3>
        <p class="date">၂၀၂၆၊ ဇွန် ၁၅</p>
      </div>
    </div>
    </div>

  <hr>
  <p class="back-home"><a href="./index.html">← ပင်မစာမျက်နှာသို့ ပြန်သွားရန်</a></p>
</div>

<style>
  /* 🖥 Layout & Typography */
  .main-content { max-width: 60rem; margin: 0 auto; padding: 2.5rem 2rem; font-family: sans-serif; }
  
  .main-content h1 { font-size: 2.2rem; text-align: center; margin-bottom: 0.5rem; }
  .subtitle { text-align: center; font-size: 1.1rem; color: #555; margin-bottom: 2rem; }

  /* Dynamic Marquee */
  .news-ticker { background: #fff3cd; padding: 10px; border-left: 5px solid #ffc107; margin-bottom: 2rem; overflow: hidden; white-space: nowrap; font-size: 1rem; }
  .news-ticker span { display: inline-block; padding-left: 100%; animation: marquee 15s linear infinite; }
  @keyframes marquee { 0% { transform: translate(0, 0); } 100% { transform: translate(-100%, 0); } }

  /* Grid Layout */
  .news-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
  .news-card { display: flex; align-items: center; background: #f9f9f9; padding: 15px; border-radius: 8px; border: 1px solid #ddd; }
  .thumbnail { width: 80px; height: 80px; background: #ccc; flex-shrink: 0; display: flex; align-items: center; justify-content: center; margin-right: 15px; border-radius: 4px; }
  
  .content h3 { margin: 0 0 5px 0; font-size: 1.1rem; line-height: 1.4; }
  .content h3 a { text-decoration: none; color: #155799; }
  .date { font-size: 0.85rem; color: #777; margin: 0; }

  .back-home { margin-top: 2rem; font-size: 0.95rem; }

  /* 📱 Mobile Adjustment */
  @media (max-width: 768px) {
    .main-content { padding: 1.5rem 1rem; }
    .main-content h1 { font-size: 1.6rem; }
    .subtitle { font-size: 0.95rem; }
    .news-grid { grid-template-columns: 1fr; }
    .news-ticker { font-size: 0.9rem; }
    .content h3 { font-size: 1rem; }
    .date { font-size: 0.75rem; }
  }
</style>
