---

layout: default
title: တပ်ကုန်းမြို့နယ်၏ အထင်ကရဖြစ်ရပ်များ Timeline
description: သမိုင်းဖြစ်ရပ်များ၊ အုပ်ချုပ်ရေးနှင့် သာသနာရေးဆိုင်ရာ ခေတ်ပြိုင်မှတ်တမ်း

---

# တပ်ကုန်းမြို့နယ်၏ အထင်ကရဖြစ်ရပ်များ Timeline

<br>

<div class="timeline-controls">
  <div class="control-group">
    <label for="categoryFilter">🔍 ကဏ္ဍအလိုက် စစ်ထုတ်ရန်:</label>
    <select id="categoryFilter" onchange="filterTimeline()">
      <option value="all">အားလုံးပြရန်</option>
      <option value="သမိုင်းဦး">သမိုင်းဦး / နောက်ခံ</option>
      <option value="အုပ်ချုပ်ရေး">အုပ်ချုပ်ရေး</option>
      <option value="လမ်းပန်းဆက်သွယ်ရေး">လမ်းပန်းဆက်သွယ်ရေး</option>
      <option value="သာသနာရေး">သာသနာရေး</option>
      <option value="သဘာဝဘေး">သဘာဝဘေးအန္တရာယ်</option>
    </select>
  </div>

  <div class="control-group">
    <label>📅 ရက်စွဲ စီရန်:</label>
    <button class="btn-sort active" id="btnSortOld" onclick="sortTimeline('oldest')">⏳ ရှေးကျရာမှ အသစ်သို့</button>
    <button class="btn-sort" id="btnSortNew" onclick="sortTimeline('newest')">⌛ အသစ်မှ ရှေးကျရာသို့</button>
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
      <tr data-year="1146" data-category="သမိုင်းဦး">
        <td><b>၁၁၄၆ ခုနှစ်</b></td>
        <td><span class="badge badge-history">သမိုင်းဦး</span></td>
        <td>ဘိုးတော်ဘုရားစစ်တမ်းအရ ယနေ့ခေတ် တပ်ကုန်းမြို့သည် <b>"တလိုင်းသေရွာ"</b> နယ်နိမိတ်အတွင်း ပါဝင်ခဲ့ကြောင်း သမိုင်းဦးမှတ်တမ်း တွေ့ရှိရခြင်း။</td>
      </tr>
      <tr data-year="1904" data-category="လမ်းပန်းဆက်သွယ်ရေး">
        <td><b>၁၉၀၄ ခုနှစ်</b></td>
        <td><span class="badge badge-transit">လမ်းပန်းဆက်သွယ်ရေး</span></td>
        <td>ကိုလိုနီခေတ်ဦး ရန်ကုန်-မန္တလေး ရထားလမ်းနှင့် ကားလမ်းများ ဖောက်လုပ်ခဲ့သဖြင့် လမ်းပန်းဆက်သွယ်ရေး အချက်အခြာကျပြီး ထင်ရှားလာခြင်း။</td>
      </tr>
      <tr data-year="1951" data-category="အုပ်ချုပ်ရေး">
        <td><b>၁၉၅၁ ခုနှစ်</b></td>
        <td><span class="badge badge-admin">အုပ်ချုပ်ရေး</span></td>
        <td>လွတ်လပ်ရေးရပြီးနောက် ပထမဆုံးမြို့ပိုင်အဖြစ် <b>ဦးထွန်းမောင်</b> စတင် တာဝန်ထမ်းဆောင်ခြင်း။</td>
      </tr>
      <tr data-year="1960" data-category="အုပ်ချုပ်ရေး">
        <td><b>၁၉၆၀ ပြည့်နှစ်</b></td>
        <td><span class="badge badge-admin">အုပ်ချုပ်ရေး</span></td>
        <td>တပ်ကုန်းမြို့နယ်ကို တရားဝင်ဖွဲ့စည်းခဲ့ပြီး တပ်ကုန်းမြို့သည် မြို့နယ်ရုံးစိုက်ရာမြို့ ဖြစ်လာခြင်း။</td>
      </tr>
      <tr data-year="2014" data-category="အုပ်ချုပ်ရေး">
        <td><b>၂၀၁၄ ခုနှစ်</b></td>
        <td><span class="badge badge-admin">အုပ်ချုပ်ရေး</span></td>
        <td>ပြည်ထောင်စု သန်းခေါင်စာရင်းအရ တပ်ကုန်းမြို့ပေါ် လူဦးရေ စုစုပေါင်း ၄၁,၆၈၃ ဦး ရှိလာကြောင်း မှတ်တမ်းတင်ခြင်း။</td>
      </tr>
      <tr data-year="2024" data-category="သဘာဝဘေး">
        <td><b>၂၀၂၄ ခုနှစ်</b></td>
        <td><span class="badge badge-disaster">သဘာဝဘေး</span></td>
        <td>ရာဂီမုန်တိုင်းကြောင့် တပ်ကုန်းမြို့နယ်အတွင်း ဆင်သေချောင်း ရေလျှံကာ ထူးခြားဆိုးရွားသည့် စက်တင်ဘာလ ရေဘေးမှတ်တမ်း ဖြစ်ပွားခြင်း။</td>
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

    // Active Button Style ပြောင်းခြင်း
    document.getElementById('btnSortOld').classList.toggle('active', order === 'oldest');
    document.getElementById('btnSortNew').classList.toggle('active', order === 'newest');

    rows.sort((a, b) => {
      const yearA = parseInt(a.getAttribute('data-year'));
      const yearB = parseInt(b.getAttribute('data-year'));
      return order === 'oldest' ? yearA - yearB : yearB - yearA;
    });

    // ဇယားကို ပြန်စီခြင်း
    rows.forEach(row => tableBody.appendChild(row));
  }
</script>

<style>
  /* 🖥 Layout & Typography ကို ရှေးစာမျက်နှာများနှင့် တစ်ပြေးညီ ညှိခြင်း */
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

  /* 🎛 Controls (Filter & Sort UI) အလှဆင်ခြင်း */
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

  /* 📊 Table Styling (ဇယားပုံစံအလှဆင်ခြင်း) */
  .table-container {
    width: 100%;
    overflow-x: auto; /* မိုဘိုင်းဖုန်းပေါ်တွင် ဘေးတိုက် Scroll ဆွဲနိုင်ရန် */
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

  /* 🏷 Category Badges (ကဏ္ဍအလိုက် အရောင်လေးများခွဲခြင်း) */
  .badge {
    display: inline-block;
    padding: 0.2rem 0.5rem;
    font-size: 0.78rem;
    font-weight: bold;
    border-radius: 4px;
    color: white;
  }
  .badge-history { background-color: #6f42c1; }
  .badge-transit { background-color: #0366d6; }
  .badge-admin { background-color: #28a745; }
  .badge-disaster { background-color: #d73a49; }

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
    table { font-size: 0.85rem; }
    th, td { padding: 0.6rem; }
  }
</style>
