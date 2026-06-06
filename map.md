---
layout: none
---
<!DOCTYPE html>
<html lang="my">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>တပ်ကုန်းမြို့နယ် ဘက်စုံသုံးမြေပုံ</title>
  <style>
    /* မျက်နှာပြင်တစ်ခုလုံး ဘေးဘောင် အဖြူထွက်တာတွေ အကုန်ဖျောက်ခြင်း */
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      overflow: hidden;
      font-family: sans-serif;
    }

    /* 🛠 ရှေ့က စာမျက်နှာတွေအတိုင်း Title Bar (Header) ကို အတင်း ကိုယ်တိုင်ဆောက်ခြင်း */
    .custom-header {
      background-color: #157575; /* အစ်ကို့ Theme က သုံးထားတဲ့ စိမ်းပြာရောင် ကာလာဘား */
      background-image: linear-gradient(120deg, #155799, #159957); /* ကာလာဘား Gradient အလှ */
      color: #ffffff;
      padding: 15px 20px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    
    .custom-header h1 {
      margin: 0 0 5px 0;
      font-size: 1.6rem;
      font-weight: bold;
    }
    
    .custom-header p {
      margin: 0;
      font-size: 0.95rem;
      opacity: 0.9;
    }

    /* 🛠 မြေပုံကို လက်ကျန် Screen အပြည့် (Full Screen) ပေးခြင်း */
    .map-container {
      width: 100%;
      height: calc(100vh - 80px); /* Screen အမြင့်ထဲက Header အမြင့်ကို နှုတ်ပြီး အပြည့်ယူသည် */
      margin: 0;
      padding: 0;
    }

    iframe.web-map {
      width: 100%;
      height: 100%;
      border: none;
      display: block;
    }
  </style>
</head>
<body>

  <header class="custom-header">
    <h1>📄 တပ်ကုန်းမြို့နယ် ဘက်စုံသုံးမြေပုံ</h1>
    <p>တပ်ကုန်းမြို့နယ်၏ ခေတ်အဆက်ဆက် အုပ်ချုပ်ရေးနယ်နိမိတ်များနှင့် ရွာတည်နေရာ ပြောင်းလဲမှုပြ Interactive မြေပုံ</p>
  </header>

  <div class="map-container">
    <iframe src="./map/qgis2web_2026_06_06-11_43_43_866084/index.html" class="web-map"></iframe>
  </div>

</body>
</html>
