---
layout: default
title: တပ်ကုန်းမြို့နယ် ဘက်စုံသုံးမြေပုံ
description: တပ်ကုန်းမြို့နယ်၏ ခေတ်အဆက်ဆက် အုပ်ချုပ်ရေးနယ်နိမိတ်များနှင့် ရွာတည်နေရာ ပြောင်းလဲမှုပြ Interactive မြေပုံ
---

<style>
  /* 🛠 တစ်မျက်နှာလုံးမှာ မလိုအပ်ဘဲ Scroll Bar ထွက်တာကို လုံးဝ ပိတ်ပစ်ခြင်း */
  body {
    overflow: hidden !important;
  }

  /* 🛠 ကာလာဘား (Header) ကို ရှေ့က စာမျက်နှာများနှင့် Format တစ်ထပ်တည်းညှိခြင်း */
  header.page-header h1 { 
    display: none !important; 
  }
  
  .page-header .project-tagline {
    display: block !important;
    font-size: 1.1rem !important;
    font-weight: normal !important;
    opacity: 0.95 !important;
    line-height: 1.6 !important;
    margin: 0 auto !important;
    max-width: 900px !important;
    text-align: center !important;
  }
  
  .page-header {
    padding: 1.8rem 1rem !important;
  }

  /* အောက်ခြေ Footer ကို ဖျောက်ခြင်း */
  .site-footer { 
    display: none !important; 
  }

  /* 🛠 မြေပုံကို ဘေးအပြည့် ကပ်သွားအောင် ဘောင်အားလုံးကို ဖျက်ချခြင်း */
  .main-content, 
  .wrapper, 
  .container,
  #main_content {
    max-width: 100% !important;   /* ဘေးဘောင်ကို ရာခိုင်နှုန်းအပြည့် ချဲ့သည် */
    width: 100% !important;
    padding: 0px !important;      /* ဘေးက Padding ဖြူဖြူတွေကို လုံးဝ ဖျက်သည် */
    margin: 0px !important;       /* Margin ကြောင့် ပိုထွက်နေတာကိုပါ အကုန်ဖျက်သည် */
  }

  /* စာမျက်နှာတွင်း ခေါင်းစဉ်စတိုင် (ဘေးဘောင် Padding နည်းနည်းပြန်ထည့်ပေးထားပါသည်) */
  .main-content .my-custom-title {
    display: block !important;
    font-size: 1.5rem !important;
    font-weight: bold !important;
    color: #222222 !important;
    margin-top: 25px !important;
    margin-bottom: 15px !important;
    line-height: 1.3 !important;
    padding-left: 20px !important; /* ဘေးကပ်မနေအောင် Padding ထည့်ခြင်း */
  }

  /* 🛠 မြေပုံ Frame အလှအပအတွက် CSS (စာမျက်နှာခေါင်းစဉ်နှင့် လင့်ခ်စာသားအတွက် အမြင့်ကို ၂၃၀ သို့ ထပ်မံညှိထားပါသည်) */
  .map-frame-container {
    width: 100% !important;
    height: calc(100vh - 230px) !important;   
    position: relative;
    overflow: hidden;
    padding: 0px !important;
    margin: 0px !important;
  }

  iframe.web-map {
    width: 100% !important;
    height: 100% !important;
    border: none !important;
    display: block !important;
  }

  /* 🔗 ပြန်သွားရန်လင့်ခ်စတိုင် (ရှေ့စာမျက်နှာများနှင့် Format အတူတူပင်ဖြစ်ပါသည်) */
  .custom-return-link {
    display: inline-block !important;
    visibility: visible !important;
    opacity: 1 !important;
    margin-top: 15px !important;
    margin-bottom: 15px !important;
    font-size: 0.95rem !important;
    padding-left: 20px !important; /* ဘေးကပ်မနေအောင် Padding ထည့်ခြင်း */
  }
  .custom-return-link a {
    color: #0366d6 !important;
    text-decoration: none !important;
  }
  .custom-return-link a:hover {
    text-decoration: underline !important;
  }

  /* 📱 မိုဘိုင်းဖုန်းပေါ်တွင် Responsive ဖြစ်စေရန် ညှိခြင်း */
  @media (max-width: 768px) {
    .page-header { padding: 1.5rem 1rem !important; }
    .project-tagline { font-size: 0.85rem !important; }
    
    /* မိုဘိုင်းပေါ်တွင် ခေါင်းစဉ်အရွယ်အစား လျှော့ချခြင်း */
    .main-content .my-custom-title { font-size: 1.15rem !important; margin-top: 15px !important; margin-bottom: 10px !important; }
    
    /* မိုဘိုင်းပေါ်တွင် မြေပုံအမြင့်ကို ပိုမိုကျဉ်းပေးခြင်း */
    .map-frame-container { height: calc(100vh - 210px) !important; }
    .custom-return-link { font-size: 0.88rem !important; }
  }
</style>

<div class="my-custom-title">🗺️ တပ်ကုန်းမြို့နယ် ဘက်စုံသုံးမြေပုံ</div>

<div class="map-frame-container">
  <iframe src="./map/qgis2web_2026_06_06-12_56_09_075256/index.html" class="web-map"></iframe>
</div>

<div class="custom-return-link">
  <a href="../../index.html">ပင်မစာမျက်နှာသို့ ပြန်သွားရန်</a>
</div>
