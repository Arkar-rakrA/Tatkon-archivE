---
layout: default
title: တပ်ကုန်းမြို့နယ် ဘက်စုံသုံးမြေပုံ
description: တပ်ကုန်းမြို့နယ်၏ ခေတ်အဆက်ဆက် အုပ်ချုပ်ရေးနယ်နိမိတ်များနှင့် ရွာတည်နေရာ ပြောင်းလဲမှုပြ Interactive မြေပုံ
---

<style>
  /* 🛠 တစ်မျက်နှာလုံးမှာ မလိုအပ်ဘဲ Scroll Bar ထွက်တာကို လုံးဝ ပိတ်ပစ်ခြင်း */
  html, body {
    overflow: hidden !important;
    height: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }

  /* 🖥 ကာလာဘား (Header) ကို ရှေ့က သန်းခေါင်စာရင်းစာမျက်နှာများနှင့် Format တစ်ထပ်တည်း ပြန်ညှိခြင်း */
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
  footer.site-footer,
  .site-footer { 
    display: none !important; 
  }

  /* 🛠 Jekyll Wrapper ဘောင်များကို အကျယ်အပြည့်ချဲ့ပြီး Padding ဖျက်ခြင်း */
  .main-content, 
  .wrapper, 
  .container,
  #main_content {
    max-width: 100% !important;
    width: 100% !important;
    padding: 0px !important;
    margin: 0px !important;
  }

  /* 🛠 မြေပုံ Frame ကို အပေါ်က ကာလာဘားအောက်ကနေ ကွက်တိ အပြည့်နေရာချခြင်း */
  .map-frame-container {
    width: 100% !important;
    height: calc(100vh - 120px) !important; /* 👈 Header အောက်ကနေ မျက်နှာပြင်အပြည့် ယူထားပါသည် */
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

  /* 📱 မိုဘိုင်းဖုန်းပေါ်တွင် Responsive ဖြစ်စေရန် ညှိခြင်း */
  @media (max-width: 768px) {
    /* မိုဘိုင်းပေါ်တွင် Theme ကြောင့် စာသားများ အောက်သို့ လာရှုပ်နေခြင်းကို တားဆီးရန် */
    .page-header { 
      padding: 1.2rem 1rem !important; 
    }
    .project-tagline { 
      font-size: 0.9rem !important; 
    }
    
    /* မိုဘိုင်းအမြင့်နှင့် ကိုက်ညီအောင် မြေပုံ Container ကို ပြန်ညှိခြင်း */
    .map-frame-container { 
      height: calc(100vh - 90px) !important; 
    }
  }
</style>

<div class="map-frame-container">
  <iframe src="./map/qgis2web_2026_06_06-12_56_09_075256/index.html" class="web-map"></iframe>
</div>
