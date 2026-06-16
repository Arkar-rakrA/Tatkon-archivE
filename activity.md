---
layout: default
title: သတင်းနှင့် လှုပ်ရှားမှုများ
description: မော်ကွန်းတိုက်၏ လှုပ်ရှားဆောင်ရွက်မှုနှင့် ရပ်ရွာ၏ကူညီပံ့ပိုးမှုများ
---

<div class="main-content">
  <h1>သတင်းနှင့် လှုပ်ရှားမှုများ</h1>
  <p class="subtitle">မော်ကွန်းတိုက်၏ လှုပ်ရှားဆောင်ရွက်မှုများနှင့် ရပ်ရွာ၏ကူညီပံ့ပိုးမှုများ</p>

  <div class="news-ticker">
    <span>📢 ယခုလအတွက် လှုပ်ရှားမှု - ဇမ္ဗူဒီပဥဆောင်းကျမ်းမှ တပ်ကုန်းမြို့နယ်ဆိုင်ရာ အချက်အလက်များ ထုတ်နှုတ်တင်ပြထားပြီးဖြစ် </span>
  </div>

  <div class="news-grid">
    <div class="news-card">
      <div class="thumbnail">🖼️</div>
      <div class="content">
        <h3><a href="#"> တပ်ကုန်းမြို့နယ်အတွက် Hydrological Analysis ရလဒ်များ လွှင့်တင် </a></h3>
        <p class="date">၂၀၂၆၊ မေ ၁၅</p>
      </div>
    </div>

    <div class="news-card">
      <div class="thumbnail">🖼️</div>
      <div class="content">
        <h3><a href="#">ညောင်လွန့်ကျေးရွာဒေသခံတစ်ဦးမှ မဟာမုနိဘုရားကြီးသမိုင်းမှတ်တမ်းအား ပေးပို့ကူညီ</a></h3>
        <p class="date">၂၀၂၆၊ ဧပြီ ၂၀</p>
      </div>
    </div>
  </div>

  <hr>
  <p class="back-home"><a href="./index.html">ပင်မစာမျက်နှာသို့ ပြန်သွားရန်</a></p>
</div>

<style>
  /* 🖥 Layout & Typography (Global consistency) */
  footer.site-footer, .site-footer { display: none !important; }

  .page-header { padding: 2rem 5rem !important; }
  .project-name { font-size: 2.5rem !important; margin-bottom: 1rem !important; }
  .project-tagline { font-size: 1rem !important; margin-bottom: 1rem !important; }

  .main-content {
    max-width: 60rem !important; 
    margin: 0 auto; 
    padding: 2.5rem 2rem 3rem !important; 
    font-family: sans-serif; 
    color: #2b2b2b; 
    line-height: 1.65 !important;
  }
  
  .main-content h1 { 
    font-size: 2.2rem !important; 
    font-weight: bold; 
    margin-top: 1rem !important; 
    margin-bottom: 0.5rem !important; 
    text-align: center; 
    border-bottom: 1px solid #eaecef; 
    padding-bottom: 0.3rem; 
  }
  
  .subtitle { text-align: center; font-size: 1.1rem !important; color: #555; margin-bottom: 2rem !important; }

  /* Dynamic Marquee */
  .news-ticker { background: #fff3cd; padding: 10px; border-left: 5px solid #ffc107; margin-bottom: 2rem; overflow: hidden; white-space: nowrap; font-size: 1rem !important; }
  .news-ticker span { display: inline-block; padding-left: 100%; animation: marquee 15s linear infinite; }
  @keyframes marquee { 0% { transform: translate(0, 0); } 100% { transform: translate(-100%, 0); } }

  /* Grid Layout */
  .news-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
  .news-card { display: flex; align-items: center; background: #f9f9f9; padding: 15px; border-radius: 8px; border: 1px solid #ddd; }
  .thumbnail { width: 80px; height: 80px; background: #ccc; display: flex; align-items: center; justify-content: center; margin-right: 15px; border-radius: 4px; flex-shrink: 0; }
  
  .content h3 { margin: 0 !important; font-size: 1.1rem !important; color: #155799; }
  .content h3 a { text-decoration: none; color: #155799; }
  .content h3 a:hover { text-decoration: underline; }
  
  .date { font-size: 0.85rem !important; color: #777; margin: 5px 0 0 0 !important; }

  hr { height: 1px !important; background-color: #eaecef !important; border: none !important; margin: 2rem 0 !important; }
  .back-home { font-size: 0.95rem !important; margin-bottom: 1.2rem !important; }
  .back-home a { color: #0366d6; text-decoration: none; }
  .back-home a:hover { text-decoration: underline; }

  /* 📱 Mobile Responsive */
  @media (max-width: 768px) {
    .page-header { padding: 1.5rem 1rem !important; }
    .project-name { font-size: 1.4rem !important; }
    .project-tagline { font-size: 0.8rem !important; }
    .main-content { padding: 1.5rem 1.2rem 2rem !important; }
    .main-content h1 { font-size: 1.5rem !important; }
    .subtitle { font-size: 0.9rem !important; }
    .news-grid { grid-template-columns: 1fr; }
    .news-ticker { font-size: 0.9rem !important; }
    .content h3 { font-size: 1rem !important; }
    .date { font-size: 0.75rem !important; }
    .back-home { font-size: 0.8rem !important; }
  }
</style>
