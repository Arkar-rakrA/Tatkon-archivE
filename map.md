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

  /* 🛠 မြေပုံကို မျက်နှာပြင်အပြည့် (Full Width) ဖြစ်အောင် Main Layout ကို ချဲ့ခြင်း */
  .main-content {
    max-width: 100% !important; /* ဘေးဘောင်တွေကို အစွန်းအထိ ကပ်ပစ်ခြင်း */
    padding: 0 !important;      /* ဘေးပတ်ပတ်လည် ကွက်လပ် (Padding) အကုန်ဖြုတ်ခြင်း */
    margin: 0 !important;
  }

  /* 🛠 မြေပုံ Frame အလှအပအတွက် CSS */
  .map-frame-container {
    width: 100%;
    height: calc(100vh - 140px); /* ကွန်ပျူတာ Screen ရဲ့ အမြင့်အပြည့်ထဲက ကာလာဘားအမြင့်ကို နှုတ်ပြီး နေရာယူခြင်း */
    position: relative;
    overflow: hidden;
  }

  iframe.web-map {
    width: 100%;
    height: 100%;
    border: none;
    display: block;
  }
</style>

<div class="map-frame-container">
  <iframe src="./map/qgis2web_2026_06_06-11_43_43_866084/index.html" class="web-map"></iframe>
</div>
