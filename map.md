---
layout: default
title: တပ်ကုန်းမြို့နယ် ဘက်စုံသုံးမြေပုံ
description: တပ်ကုန်းမြို့နယ်၏ ပထဝီဝင်နှင့် သမိုင်းကြောင်းဆိုင်ရာ အချက်အလက်များအား Layer ပြောင်းလဲ၍ ကြည့်ရှုပါရန်
---

<style>
  /* 🛠 တစ်မျက်နှာလုံးမှာ မလိုအပ်ဘဲ Scroll Bar ထွက်တာကို လုံးဝ ပိတ်ပစ်ခြင်း */
  html, body {
    overflow: hidden !important;
    height: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }

  /* 🖥 ကာလာဘား (Header) ထဲက ခေါင်းစဉ်ကြီးကို Desktop ရော Mobile မှာပါ ပေါ်အောင် ပြန်ဖွင့်ခြင်း */
  header.page-header h1,
  .page-header h1 { 
    display: block !important; 
    font-size: 1.8rem !important; /* စာလုံးအရွယ်အစားကို အနေတော် ပြန်ညှိထားပါသည် */
    font-weight: bold !important;
    color: #ffffff !important;
    margin-bottom: 0.5rem !important;
    text-align: center !important;
  }
  
  /* အောက်က စာတန်းအသေးလေးကိုပါ စနစ်တကျ တွဲပြခြင်း */
  .page-header .project-tagline {
    display: block !important;
    font-size: 1rem !important;
    font-weight: normal !important;
    opacity: 0.9 !important;
    line-height: 1.5 !important;
    margin: 0 auto !important;
    max-width: 900px !important;
    text-align: center !important;
  }
  
  .page-header {
    padding: 1.5rem 1rem !important; /* Header အမြင့်ကို ပိုကျစ်လစ်အောင် ညှိခြင်း */
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
    height: calc(100vh - 140px) !important; /* 👈 Header အောက်ကနေ မျက်နှာပြင်အပြည့် ကွက်တိယူခြင်း */
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
    /* မိုဘိုင်းပေါ်တွင် ခေါင်းစဉ်အရွယ်အစားများ ထပ်မနေဘဲ ကျစ်လစ်သွားစေရန် */
    header.page-header h1,
    .page-header h1 { 
      font-size: 1.25rem !important; 
    }
    .project-tagline { 
      font-size: 0.85rem !important; 
    }
    .page-header { 
      padding: 1rem 0.8rem !important; 
    }
    
    /* မိုဘိုင်းအမြင့်နှင့် ကိုက်ညီအောင် မြေပုံ Container ကို ပြန်ညှိခြင်း */
    .map-frame-container { 
      height: calc(100vh - 110px) !important; 
    }
  }
</style>

<div class="map-frame-container">
  <iframe src="./map/qgis2web_2026_06_06-12_56_09_075256/index.html" class="web-map"></iframe>
</div>
