---

layout: default
title: အထင်ကရဖြစ်ရပ်များ
description: တပ်ကုန်းမြို့နယ် ရက်စဉ်သမိုင်း

---

# တပ်ကုန်းမြို့နယ်၏ အထင်ကရဖြစ်ရပ်များ

<br>

<div class="timeline-controls">
  <div class="control-group">
    <label for="categoryFilter">🔍 ကဏ္ဍအလိုက် စစ်ထုတ်ရန်:</label>
    <select id="categoryFilter" onchange="filterTimeline()">
      <option value="all">အားလုံးပြရန်</option>
      <option value="အုပ်ချုပ်ရေး">အုပ်ချုပ်ရေး</option>
      <option value="စီးပွားရေး">စီးပွားရေး</option>
      <option value="လူမှုရေး">လူမှုရေး</option>
      <option value="သဘာဝပတ်ဝန်းကျင်">သဘာဝပတ်ဝန်းကျင်</option>
      <option value="ပညာ/ကျန်းမာ">ပညာကျန်းမာ</option>
      <option value="အခြေခံအဆောက်အအုံ">အခြေခံအဆောက်အအုံ</option>
      <option value="ဘေးအန္တရာယ်">ဘေးအန္တရာယ်</option>
    </select>
  </div>

  <div class="control-group">
    <label>📅 ရက်စွဲ စီရန်:</label>
    <button class="btn-sort active" id="btnSortOld" onclick="sortTimeline('oldest')">⏳ အဟောင်းမှ အသစ်သို့</button>
    <button class="btn-sort" id="btnSortNew" onclick="sortTimeline('newest')">⌛ အသစ်မှ အဟောင်းသို့</button>
  </div>
</div>

<div class="table-container">
  <table id="timelineTable">
    <thead>
      <tr>
        <th style="width: 20%;">ရက်စွဲ / ကာလ</th>
        <th style="width: 20%;">ကဏ္ဍ</th>
        <th style="width: 60%;">ဖြစ်ရပ်မှတ်တမ်းအကျဉ်း</th>
      </tr>
    </thead>
    <tbody id="timelineBody">
      
      <tr data-year="1146" data-category="အုပ်ချုပ်ရေး">
        <td><b>၁၁၄၆ ခုနှစ်</b></td>
        <td><span class="badge badge-admin">အုပ်ချုပ်ရေး</span></td>
        <td>ဘိုးတော်ဘုရားစစ်တမ်းအရ ယနေ့ခေတ် တပ်ကုန်းမြို့တည်ရှိရာ နယ်မြေသည် <b>"တလိုင်းသေရွာ"</b> နယ်နိမိတ်အတွင်း ပါဝင်ခဲ့ကြောင်း အစောဆုံးမှတ်တမ်း တွေ့ရှိရခြင်း။</td>
      </tr>

      <tr data-year="1904" data-category="အခြေခံအဆောက်အအုံ">
        <td><b>၁၉၀၄ ခုနှစ်</b></td>
        <td><span class="badge badge-infra">အခြေခံ<span class="t-break"><br></span>အဆောက်အအုံ</span></td>
        <td>ကိုလိုနီခေတ်ဦး ရန်ကုန်-မန္တလေး ရထားလမ်းနှင့် ကားလမ်းများ ဖောက်လုပ်ခဲ့သဖြင့် တပ်ကုန်းဘူတာ စတင်ပေါ်ပေါက်လာပြီး လမ်းပန်းဆက်သွယ်ရေး အချက်အခြာ ဖြစ်လာခြင်း။</td>
      </tr>

      <tr data-year="1951" data-category="အုပ်ချုပ်ရေး">
        <td><b>၁၉၅၁ ခုနှစ်</b></td>
        <td><span class="badge badge-admin">အုပ်ချုပ်ရေး</span></td>
        <td>လွတ်လပ်ရေးရပြီးနောက် တပ်ကုန်းမြို့၏ ပထမဆုံးမြို့ပိုင်အဖြစ် <b>ဦးထွန်းမောင်</b> စတင် တာဝန်ထမ်းဆောင်ခြင်း။</td>
      </tr>

      <tr data-year="1960" data-category="အုပ်ချုပ်ရေး">
        <td><b>၁၉၆၀ ပြည့်နှစ်</b></td>
        <td><span class="badge badge-admin">အုပ်ချုပ်ရေး</span></td>
        <td>တပ်ကုန်းမြို့နယ်ကို တရားဝင်ဖွဲ့စည်းခဲ့ပြီး တပ်ကုန်းမြို့သည် မြို့နယ်ရုံးစိုက်ရာမြို့အဖြစ် တိုးမြှင့်သတ်မှတ်ခြင်း ခံရခြင်း။</td>
      </tr>

      <tr data-year="2014" data-category="လူမှုရေး">
        <td><b>၂၀၁၄ ခုနှစ်</b></td>
        <td><span class="badge badge-social">လူမှုရေး</span></td>
        <td>ပြည်ထောင်စု သန်းခေါင်စာရင်းအရ တပ်ကုန်းမြို့ပေါ် လူဦးရေ စုစုပေါင်း ၄၁,၆၈၃ ဦး ရှိလာကြောင်း တရားဝင်မှတ်တမ်းတင်ခြင်း။</td>
      </tr>

      <tr data-year="2024" data-category="ဘေးအန္တရာယ်">
        <td><b>၂၀၂၄ ခုနှစ်</b></td>
        <td><span class="badge badge-disaster">ဘေးအန္တရာယ်</span></td>
        <td>ရာဂီမုန်တိုင်းအရှိန်ကြောင့် တပ်ကုန်းမြို့နယ်အတွင်းရှိ ဆင်သေချောင်း ရေလျှံကာ ထူးခြားဆိုးရွားသည့် စက်တင်ဘာလ ရေဘေးမှတ်တမ်း ဖြစ်ပွားခြင်း။</td>
      </tr>

    </tbody>
  </table>
</div>

---

[ပင်မစာမျက်နှာသို့ ပြန်သွားရန်](./index.html)

<script>
  let originalRows = Array.from(document.getElementById('timelineBody').rows);

  function filterTimeline() {
    const selectedCategory = document.getElementById('categoryFilter').value;
    const tableBody = document.getElementById('timelineBody');
    
    originalRows.forEach(row => {
      const rowCat = row.getAttribute('data-category');
      if (selectedCategory === 'all' || rowCat === selectedCategory) {
        row.style.display = "";
      } else {
        row.style.display = "none";
      }
    });
  }

  function sortTimeline(order) {
    const tableBody = document.getElementById('timelineBody');
    const rows = Array.from(tableBody.rows);

    document.getElementById('btnSortOld').classList.toggle('active', order === 'oldest');
    document.getElementById('btnSortNew').classList.toggle('active', order === 'newest');

    rows.sort((a, b) => {
      const yearA = parseInt(a.getAttribute('data-year'));
      const yearB = parseInt(b.getAttribute('data-year'));
      return order === 'oldest' ? yearA - yearB : yearB - yearA;
    });

    rows.forEach(row => tableBody.appendChild(row));
  }
</script>

<style>
  /* 🖥 Layout & Typography */
  .page-header { padding: 2rem 5rem !important; }
  .project-name { font-size: 2.5rem !important; margin-bottom: 1rem !important; }
  .project-tagline { font-size: 1rem !important; margin-bottom: 1rem !important; }
  footer.site-footer, .site-footer { display: none !important; }

  .main-content {
    max-width: 60rem !important; 
    padding: 2.5rem 2rem 3rem !important;
    font-family: sans-serif;
    color: #2b2b2b;
    line-height: 1.65 !important;
  }

  .main-content h1 {
    font-size: 2.2rem !important;
    font-weight: bold;
    margin-top: 1rem !important;
    margin-bottom: 1.5rem !important;
    border-bottom: 1px solid #eaecef;
    padding-bottom: 0.3rem;
  }

  .main-content hr {
    height: 1px !important;
    background-color: #eaecef !important;
    border: none !important;
    margin: 2rem 0 !important;
  }

  /* 🎛 Controls (Filter & Sort UI) */
  .timeline-controls {
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem;
    background: #f8f9fa;
    padding: 1rem;
    border-radius: 6px;
    border: 1px solid #dfe2e5;
    margin-bottom: 1.5rem;
  }

  .control-group {
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .control-group label {
    font-size: 0.9rem;
    font-weight: bold;
    color: #333;
  }

  .control-group select {
    padding: 0.4rem 0.8rem;
    border: 1px solid #dfe2e5;
    border-radius: 4px;
    font-size: 0.9rem;
    background: white;
    outline: none;
  }

  .btn-sort {
    padding: 0.4rem 0.8rem;
    border: 1px solid #dfe2e5;
    background: white;
    border-radius: 4px;
    font-size: 0.85rem;
    cursor: pointer;
    transition: all 0.2s ease;
  }

  .btn-sort:hover {
    background: #f0f0f0;
  }

  .btn-sort.active {
    background: #155799;
    color: white;
    border-color: #155799;
    font-weight: bold;
  }

  /* 📊 Table Styling */
  .table-container {
    width: 100%;
    overflow-x: auto;
    margin-bottom: 2rem;
    border: 1px solid #dfe2e5;
    border-radius: 6px;
  }

  table {
    width: 100%;
    border-collapse: collapse;
    font-size: 0.92rem;
    text-align: left;
  }

  th {
    background-color: #f1f8ff;
    color: #155799;
    font-weight: bold;
    padding: 0.8rem;
    border-bottom: 2px solid #dfe2e5;
  }

  td {
    padding: 0.8rem;
    border-bottom: 1px solid #eaecef;
    line-height: 1.6;
    vertical-align: top;
  }

  tr:hover td {
    background-color: #fcfcfc;
  }

  /* 🏷 Category Badges (Desktop တွင် ပုံမှန်အတိုင်း အပြည့်ပြပါမည်) */
  .badge {
    display: inline-block;
    padding: 0.2rem 0.5rem;
    font-size: 0.78rem;
    font-weight: bold;
    border-radius: 4px;
    color: white;
    white-space: nowrap; 
    line-height: 1.4;
  }
  .badge-admin     { background-color: #28a745; }
  .badge-economy   { background-color: #008080; }
  .badge-social    { background-color: #b8860b; }
  .badge-env       { background-color: #20c997; }
  .badge-healthedu { background-color: #17a2b8; }
  .badge-infra     { background-color: #0366d6; }
  .badge-disaster  { background-color: #d73a49; }

  /* Desktop တွင် HTML ထဲက <br> ကို အလုပ်မလုပ်စေရန် ပိတ်ထားခြင်း */
  .t-break {
    display: none;
  }

  /* 📱 မိုဘိုင်းဖုန်းပေါ်တွင် Responsive ဖြစ်စေရန် ညှိခြင်း */
  @media (max-width: 768px) {
    .page-header { padding: 1.5rem 1rem !important; }
    .project-name { font-size: 1.4rem !important; }
    .project-tagline { font-size: 0.8rem !important; }
    .main-content { padding: 1.5rem 1.2rem 2rem !important; }
    .main-content h1 { font-size: 1.5rem !important; }
    
    .timeline-controls {
      flex-direction: column;
      gap: 0.8rem;
    }
    .control-group {
      flex-direction: column;
      align-items: flex-start;
      width: 100%;
    }
    .control-group select, .btn-sort {
      width: 100%;
      text-align: left;
    }
    
    table { font-size: 0.82rem; }
    th, td { padding: 0.5rem 0.4rem; }
    
    th:nth-child(1), td:nth-child(1) { width: 22% !important; font-size: 0.8rem; }
    th:nth-child(2), td:nth-child(2) { width: 20% !important; text-align: center; } /* ကဏ္ဍကော်လံ */
    th:nth-child(3), td:nth-child(3) { width: 58% !important; }

    /* မိုဘိုင်းဖုန်းအတွက် Badge စနစ်အား သဘာဝအတိုင်း ပြန်ပြောင်းခြင်း */
    .badge {
      font-size: 0.72rem;
      padding: 0.2rem 0.3rem;
      white-space: nowrap !important; /* 👈 ကျန်တဲ့စာလုံးတွေ လုံးဝအောက်မဆင်းစေရန် */
      display: inline-block;
      text-align: center;
    }

    /* 💡 မိုဘိုင်းဖုန်းပေါ်တွင် "အခြေခံအဆောက်အအုံ" ထဲက <br> ကို အသက်သွင်းခြင်း */
    .badge-infra {
      white-space: normal !important; /* အခြေခံအဆောက်အအုံတစ်ခုတည်းကိုပဲ စာကြောင်းဆင်းခွင့်ပေးမည် */
    }
    .t-break {
      display: inline !important; /* <br> ကို မိုဘိုင်းပေါ်မှာ ပေါ်စေခြင်း */
    }
  }
</style>
