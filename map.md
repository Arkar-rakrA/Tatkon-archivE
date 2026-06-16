---
layout: default
title: တပ်ကုန်းမြို့နယ် ဘက်စုံသုံးမြေပုံ
description: တပ်ကုန်းမြို့နယ်၏ ခေတ်အဆက်ဆက် အုပ်ချုပ်ရေးနယ်နိမိတ်များနှင့် ရွာတည်နေရာ ပြောင်းလဲမှုပြ Interactive မြေပုံ
---

<style>
  /* 🛠 စာမျက်နှာတစ်ခုလုံးကို Scroll ဘားလုံးဝမထွက်ဘဲ မျက်နှာပြင်အပြည့် ပုံသေဖြစ်စေခြင်း */
  html, body {
    overflow: hidden !important;
    height: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }

  /* 🛠 ဝဘ်ဆိုက်ရဲ့ Header (ကာလာဘား) ကို Desktop ရော Mobile မှာပါ တစ်ပြေးညီ လုံးဝဖျောက်ချခြင်း */
  /* (မိုဘိုင်းပေါ်တွင် စာသားများ Content ထဲ လာရှုပ်နေသည့် ပြဿနာကို အမြစ်ပြတ်ဖြေရှင်းချက်) */
  header.page-header, 
  .page-header { 
    display: none !important; 
  }
  
  /* အောက်ခြေ Footer ကို ဖျောက်ခြင်း */
  footer.site-footer,
  .site-footer { 
    display: none !important; 
  }

  /* 🛠 Jekyll ရဲ့ Wrapper ဘောင်အားလုံးကို မျက်နှာပြင်အပြည့် ချဲ့ပြီး Padding များ ဖျက်ခြင်း */
  .main-content, 
  .wrapper, 
  .container,
  #main_content {
    max-width: 100% !important;
    width: 100% !important;
    height: 100vh !important; /* အမြင့်ကို Screen အပြည့်ယူသည် */
    padding: 0px !important;
    margin: 0px !important;
  }

  /* 🛠 မြေပုံ Container ကို ဘရောက်ဆာမျက်နှာပြင်တစ်ခုလုံး (၁၀၀ ရာခိုင်နှုန်း) အပြည့် နေရာချခြင်း */
  .map-frame-container {
    width: 100% !important;
    height: 100vh !important; /* 👈 Header တွေ မရှိတော့လို့ Screen အမြင့် ၁၀၀% ပြည့် ယူလိုက်ပါပြီ */
    position: absolute;
    top: 0;
    left: 0;
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
</style>

<div class="map-frame-container">
  <iframe src="./map/qgis2web_2026_06_06-12_56_09_075256/index.html" class="web-map"></iframe>
</div>
