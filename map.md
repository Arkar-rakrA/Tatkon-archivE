---
layout: default
title: တပ်ကုန်းမြို့နယ် ဘက်စုံသုံးမြေပုံ
description: တပ်ကုန်းမြို့နယ်၏ ခေတ်အဆက်ဆက် အုပ်ချုပ်ရေးနယ်နိမိတ်များနှင့် ရွာတည်နေရာ ပြောင်းလဲမှုပြ Interactive မြေပုံ
---

<style>
  /* ကာလာဘားကို ရှေ့က စာမျက်နှာတွေလိုပဲ လှပအောင် ပြန်ညှိခြင်း */
  .page-header {
    padding: 1.8rem 1rem !important;
  }
  .page-header h1 {
    font-size: 1.8rem !important;
    font-weight: bold !important;
    color: #ffffff !important;
    display: block !important;
  }
  .page-header .project-tagline {
    display: block !important;
    font-size: 1.1rem !important;
    opacity: 0.95 !important;
  }

  /* အောက်ခြေ Footer ကို ဖျောက်ခြင်း */
  .site-footer { 
    display: none !important; 
  }

  /* 🛠 🔥 မြေပုံကို ဘေးအပြည့် ကပ်သွားအောင် ဖြစ်နိုင်ခြေရှိသမျှ ဘောင်အားလုံးကို ဖျက်ချခြင်း */
  .main-content, 
  .wrapper, 
  .container,
  #main_content {
    max-width: 100% !important;   /* ဘေးဘောင်ကို ရာခိုင်နှုန်းအပြည့် ချဲ့သည် */
    width: 100% !important;
    padding: 0px !important;       /* ဘေးက Padding ဖြူဖြူတွေကို လုံးဝ ဖျက်သည် */
    margin: 0px auto !important;
  }

  /* 🛠 မြေပုံ Frame အလှအပအတွက် CSS */
  .map-frame-container {
    width: 100% !important;
    height: calc(100vh - 140px);   /* Screen အမြင့်အပြည့် ယူသည် */
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
</style>

<div class="map-frame-container">
  <iframe src="./map/qgis2web_2026_06_06-11_43_43_866084/index.html" class="web-map"></iframe>
</div>
