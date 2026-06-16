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

    <div class="news-card">
      <div class="thumbnail">🖼️</div>
      <div class="content">
        <h3><a href="#">ရပ်ရွာပံ့ပိုးမှုဖြင့် စာကြည့်တိုက်အသစ်ဖွင့်လှစ်</a></h3>
        <p class="date">၂၀၂၆၊ မေ ၂၀</p>
      </div>
    </div>
  </div>

  <hr>
  <p class="back-home"><a href="./index.html">ပင်မစာမျက်နှာသို့ ပြန်သွားရန်</a></p>
</div>

<style>
  /* Page Header အတွက် အဓိကပြင်ဆင်ချက် */
  .page-header { 
    padding: 2rem 5rem !important; 
    background-color: #155799; /* သင့် Theme ရဲ့ header color အတိုင်းဖြစ်စေရန် */
  }
  .project-name { 
    font-size: 2.5rem !important; 
    margin-bottom: 1rem !important; 
    color: white !important; 
  }
  .project-tagline { 
    font-size: 1rem !important; 
    margin-bottom: 1rem !important; 
    color: rgba(255,255,255,0.7) !important; 
  }

  /* ကျန်ရှိသော CSS များ (အရင်ကအတိုင်း) */
  .main-content { max-width: 60rem !important; margin: 0 auto; padding: 2.5rem 2rem 3rem !important; font-family: sans-serif; color: #2b2b2b; }
  .main-content h1 { font-size: 2.2rem !important; font-weight: bold; margin-top: 1rem !important; margin-bottom: 0.5rem !important; text-align: center; border-bottom: 1px solid #eaecef; padding-bottom: 0.3rem; }
  .subtitle { text-align: center; font-size: 1.1rem !important; color: #555; margin-bottom: 2rem !important; }

  /* Mobile Responsive အတွက် Header ချိန်ညှိချက် */
  @media (max-width: 768px) {
    .page-header { padding: 1.5rem 1rem !important; }
    .project-name { font-size: 1.4rem !important; }
    .project-tagline { font-size: 0.8rem !important; }
    
    .main-content { padding: 1.5rem 1.2rem 2rem !important; }
    .main-content h1 { font-size: 1.5rem !important; }
    .subtitle { font-size: 0.9rem !important; }
    .news-grid { grid-template-columns: 1fr; }
  }
</style>
