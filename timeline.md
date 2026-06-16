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
      
      <tr data-year="-300" data-category="သဘာဝပတ်ဝန်းကျင်">
        <td><b>ဘီစီ ၃ ရာစုခန့်</b></td>
        <td><span class="badge badge-env">သဘာဝ<span class="t-break"><br></span>ပတ်ဝန်းကျင်</span></td>
        <td>တပ်ကုန်းမြို့နယ်တဝိုက် ကုန်းတွင်းပိုင်း ရေဝေရေလဲဒေသများနှင့် ချောင်းရိုးမြောင်းရိုးများ ပထမဆုံး စတင်ဖြစ်ပေါ်လာခြင်း။<sup><a href="#ref-1" class="cite-link">[၁]</a></sup></td>
      </tr>

      <tr data-year="400" data-category="လူမှုရေး">
        <td><b>ပျူခေတ် (အေဒီ ၅ ရာစု)</b></td>
        <td><span class="badge badge-social">လူမှုရေး</span></td>
        <td>ညောင်ကိုင်းကျေးရွာအနီးနှင့် ပတ်ဝန်းကျင်ဒေသများတွင် ရှေးမြို့ဟောင်းရာများနှင့် ပျူခေတ်အသုံးအဆောင်ပစ္စည်းများ စတင်တွေ့ရှိရခြင်း။<sup><a href="#ref-2" class="cite-link">[၂]</a></sup></td>
      </tr>

      <tr data-year="1057" data-category="အုပ်ချုပ်ရေး">
        <td><b>ပုဂံခေတ် (အနော်ရထာမင်း)</b></td>
        <td><span class="badge badge-admin">အုပ်ချုပ်ရေး</span></td>
        <td>အနော်ရထာမင်းစော တည်ထောင်ခဲ့သော ကင်းမြို့ (၄၃) မြို့အနက် ယနေ့ခေတ် တပ်ကုန်းမြို့နယ်အတွင်းရှိ <b>"ရွှေမြို့"</b> သည် တစ်ခုအပါအဝင် ဖြစ်ခဲ့ခြင်း။<sup><a href="#ref-3" class="cite-link">[၃]</a></sup></td>
      </tr>

      <tr data-year="1146" data-category="အုပ်ချုပ်ရေး">
        <td><b>၁၁၄၆ ခုနှစ် (မြန်မာသက္ကရာဇ်)</b></td>
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

<br>
<hr>

<div class="references-section">
  <h3>📚 ကိုးကားစာရင်း</h3>
  <ol class="references-list">
    <li id="ref-1">ဒေါက်တာသန်းထွန်း၊ <i>ခေတ်ဟောင်းမြန်မာရာဇဝင်</i>၊ ၂၀၀၂ ခုနှစ်။</li>
    <li id="ref-2">ညောင်ကိုင်းကျေးရွာ သမိုင်းသုတေသနအစီရင်ခံစာ (မြန်မာ့သမိုင်းအဖွဲ့)။</li>
    <li id="ref-3">မှန်နန်းမဟာရာဇဝင်တော်ကြီး (ပထမတွဲ)။</li>
  </ol>
</div>

<br>

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
      const yearA = parseInt(a.getAttribute('data-year'), 10);
      const yearB = parseInt(b.getAttribute('data-year'), 10);
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

  /* 🏷 Category Badges */
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

  .t-break {
    display: none;
  }

  /* 🔗 In-text Citation Link Styling */
  .cite-link {
    color: #0366d6;
    font-weight: bold;
    text-decoration: none;
    margin-left: 2px;
    font-size: 0.8rem;
  }
  .cite-link:hover {
    text-decoration: underline;
    color: #d73a49;
  }

  /* 📚 References Section Styling */
  .references-section {
    background-color: #fafbfc;
    padding: 1.5rem;
    border-radius: 6px;
    border: 1px solid #e1e4e8;
    margin-top: 2rem;
  }
  .references-section h3 {
    margin-top: 0 !important;
    font-size: 1.2rem !important;
    color: #155799;
    border-bottom: 1px solid #e1e4e8;
    padding-bottom: 0.5rem;
  }
  .references-list {
    margin-bottom: 0;
    padding-left: 2rem; /* မြန်မာစာလုံးဝိုင်းဝိုင်းလေးတွေ ဆန့်အောင် နေရာနည်းနည်းတိုးပေးခြင်း */
    font-size: 0.9rem;
    line-height: 1.6;
    
    /* 💡 🆕 အင်္ဂလိပ်နံပါတ် (1,2,3) မှ မြန်မာနံပါတ် (၁၊ ၂၊ ၃) သို့ ပြောင်းလဲခြင်း စနစ်အသစ် */
    list-style-type: myanmar !important; 
  }
  .references-list li {
    margin-bottom: 0.5rem;
  }
  /* Target highlight effect when clicked */
  .references-list li:target {
    background-color: #fffbdd;
    padding: 2px 5px;
    border-radius: 3px;
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
    th:nth-child(2), td:nth-child(2) { width: 20% !important; text-align: center; } 
    th:nth-child(3), td:nth-child(3) { width: 58% !important; }

    .badge {
      font-size: 0.72rem;
      padding: 0.2rem 0.3rem;
      white-space: nowrap !important; 
      display: inline-block;
      text-align: center;
    }

    .badge-infra, .badge-env {
      white-space: normal !important; 
    }
    .t-break {
      display: inline !important; 
    }
  }
</style>
