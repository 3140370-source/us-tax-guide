<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>מדריך מיסוי ופיננסים לאמריקאים בישראל</title>
  <style>
    :root {
      --primary-color: #1a365d;
      --secondary-color: #2b6cb0;
      --accent-color: #d69e2e;
      --bg-color: #f7fafc;
      --card-bg: #ffffff;
      --text-color: #2d3748;
      --border-color: #e2e8f0;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      margin: 0;
      padding: 20px;
      line-height: 1.6;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
    }

    header {
      text-align: center;
      margin-bottom: 30px;
      background-color: var(--primary-color);
      color: white;
      padding: 25px 20px;
      border-radius: 12px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    header h1 {
      margin: 0 0 10px 0;
      font-size: 1.8rem;
    }

    header p {
      margin: 0;
      font-size: 0.95rem;
      opacity: 0.9;
    }

    .search-box {
      width: 100%;
      padding: 12px 16px;
      font-size: 1rem;
      border: 2px solid var(--border-color);
      border-radius: 8px;
      margin-bottom: 20px;
      box-sizing: border-box;
      outline: none;
      transition: border-color 0.2s;
    }

    .search-box:focus {
      border-color: var(--secondary-color);
    }

    .faq-card {
      background-color: var(--card-bg);
      border: 1px solid var(--border-color);
      border-radius: 8px;
      margin-bottom: 15px;
      padding: 18px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.02);
      transition: box-shadow 0.2s;
    }

    .faq-card:hover {
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
    }

    .question {
      font-weight: bold;
      font-size: 1.1rem;
      color: var(--primary-color);
      margin-bottom: 10px;
    }

    .short-answer {
      margin-bottom: 12px;
    }

    .expand-btn {
      background-color: #edf2f7;
      color: var(--secondary-color);
      border: none;
      padding: 8px 14px;
      border-radius: 6px;
      cursor: pointer;
      font-weight: 600;
      font-size: 0.85rem;
      transition: background-color 0.2s;
    }

    .expand-btn:hover {
      background-color: #e2e8f0;
    }

    .full-details {
      display: none;
      margin-top: 15px;
      padding-top: 15px;
      border-top: 1px dashed var(--border-color);
      background-color: #f8fafc;
      padding: 12px;
      border-radius: 6px;
    }

    .source-link {
      display: inline-block;
      margin-top: 8px;
      color: var(--secondary-color);
      text-decoration: none;
      font-weight: bold;
    }

    .source-link:hover {
      text-decoration: underline;
    }

    /* עיצוב מונחים לחיצים */
    .term {
      color: #c53030;
      border-bottom: 1px dashed #c53030;
      cursor: pointer;
      font-weight: 600;
      padding: 0 2px;
    }

    .term:hover {
      background-color: #fff5f5;
    }

    /* Modal / Pop-up מילון מונחים */
    .modal-overlay {
      display: none;
      position: fixed;
      top: 0; left: 0; width: 100%; height: 100%;
      background: rgba(0,0,0,0.5);
      justify-content: center;
      align-items: center;
      z-index: 1000;
    }

    .modal-content {
      background: white;
      padding: 25px;
      border-radius: 10px;
      max-width: 450px;
      width: 90%;
      box-shadow: 0 10px 25px rgba(0,0,0,0.2);
      position: relative;
    }

    .modal-title {
      font-size: 1.3rem;
      font-weight: bold;
      color: var(--primary-color);
      margin-bottom: 10px;
    }

    .close-btn {
      position: absolute;
      top: 10px; left: 15px;
      font-size: 1.5rem;
      cursor: pointer;
      color: #718096;
    }

    .close-btn:hover {
      color: #000;
    }
  </style>
</head>
<body>

<div class="container">
  <header>
    <h1>אזרחים אמריקאים בישראל</h1>
    <p>מדריך שאלות ותשובות פשוט, נגיש ומוסמך</p>
  </header>

  <input type="text" id="searchInput" class="search-box" placeholder="חפש נושא (למשל: בנק, דירה, ילדים, PFIC)..." onkeyup="filterQuestions()">

  <div id="faqContainer"></div>
</div>

<!-- חלונית מילון מונחים (Pop-up) -->
<div id="modalOverlay" class="modal-overlay">
  <div class="modal-content">
    <span class="close-btn" onclick="closeModal()">&times;</span>
    <div id="modalTitle" class="modal-title"></div>
    <div id="modalBody"></div>
  </div>
</div>

<script>
  // מילון מונחים למונחים מורכבים
  const glossary = {
    "IRS": "רשות המסים של ארה\"ב (Internal Revenue Service) האחראית על גביית מסים ואכיפת חוקי המס.",
    "FBAR": "דיווח שנתי חובה על חשבונות פיננסיים מחוץ לארה\"ב (בנקים, פנסיות) במידה וסך כל החשבונות הגיע ל-10,000 דולר בשנה.",
    "PFIC": "כינוי להשקעות זרות פסיביות (כמו קרנות נאמנות ישראליות או קופת גמל להשקעה). ארה\"ב מטילה עליהן מיסוי גבוה ודיווח מורכב.",
    "FATCA": "חוק אמריקאי המחייב בנקים ומוסדות פיננסיים בכל העולם (כולל בישראל) לדווח ל-IRS על חשבונות של אזרחים אמריקאים.",
    "Form 1040": "טופס דוח המס האישי השנתי שכל אזרח אמריקאי חייב להגיש לרשות המסים האמריקאית.",
    "SSN": "מספר ביטוח לאומי אמריקאי (Social Security Number) המשמש כמספר זיהוי מס ייחודי לכל אזרח.",
    "ITIN": "מספר זיהוי מס (Individual Taxpayer Identification Number) הניתן לבני זוג או ילדים שאינם אזרחים אמריקאים לצורך הכללתם בדוח המס.",
    "Child Tax Credit": "מענק/החזר מס אמריקאי הניתן להורים אזרחי ארה\"ב עבור ילדים מתחת לגיל 17.",
    "CFC": "חברה זרה שבשליטת אזרחים אמריקאים (Controlled Foreign Corporation), המגררת חובות דיווח ומיסוי ייחודיות (כמו Form 5471)."
  };

  // מאגר השאלות והתשובות
  const faqData = [
    {
      q: "1. חייבים לדווח ל-<span class='term' onclick='showTerm(\"IRS\")'>IRS</span> גם אם גרים ועובדים רק בישראל?",
      short: "<b>כן.</b> ארה\"ב ממסה לפי אזרחות. כל אזרח שחצה את סף ההכנסה הבסיסי חייב בהגשת <span class='term' onclick='showTerm(\"Form 1040\")'>Form 1040</span> שנתי.",
      full: "חובת הדיווח חלה על אזרחי ארה\"ב בכל העולם. עם זאת, ברוב המקרים אמנת המס בין ישראל לארה\"ב מונעת תשלום כפול של מס.",
      sourceText: "IRS – Tax Obligations of U.S. Citizens Abroad",
      sourceUrl: "https://www.irs.gov/individuals/international-taxpayers/u-s-citizens-and-resident-aliens-abroad",
      focus: "מיקוד במקור: סעיף 'Filing Requirements' שמבהיר כי חובת הדיווח חלה ללא קשר למקום המגורים."
    },
    {
      q: "2. דיווח <span class='term' onclick='showTerm(\"FBAR\")'>FBAR</span>: מה זה ומתי חייבים לדווח?",
      short: "דיווח הצהרתי שנתי מחוץ ל-IRS על חשבונות זרים (בנקים, פנסיות) אם הסך הכולל הגיע ל-<b>$10,000</b> בשנה.",
      full: "הדיווח מוגש מקוונת לרשת FinCEN ולא לרשות המסים. אי-דיווח עלול לגרור קנסות כבדים מאוד.",
      sourceText: "FinCEN – FBAR Guidance",
      sourceUrl: "https://www.fincen.gov/report-foreign-bank-and-financial-accounts",
      focus: "מיקוד במקור: קטגוריית 'Who Must File the FBAR' המגדירה את סף $10,000."
    },
    {
      q: "3. ממה צריך להיזהר בהשקעות בישראל (מלכודת ה-<span class='term' onclick='showTerm(\"PFIC\")'>PFIC</span>)?",
      short: "קרנות נאמנות, תעודות סל, וקופות גמל להשקעה בישראל נחשבות כ-PFIC וגוררות מיסוי עונשי גבוה.",
      full: "החוק האמריקאי ממסה רווחים מקרנות זרות בשיעור המס המרבי בתוספת ריבית פיגורים. מומלץ להשקיע בקרנות אמריקאיות או מניות פרטניות.",
      sourceText: "IRS Instructions for Form 8621",
      sourceUrl: "https://www.irs.gov/instructions/i8621",
      focus: "מיקוד במקור: חלק 'Who Must File' המגדיר הגדרת קרן זרה פסיבית."
    },
    {
      q: "4. מגיע לי מענק ילדים מ-ארה\"ב (<span class='term' onclick='showTerm(\"Child Tax Credit\")'>Child Tax Credit</span>)?",
      short: "<b>כן.</b> אזרחים עם ילדים מתחת לגיל 17 עם <span class='term' onclick='showTerm(\"SSN\")'>SSN</span> בתוקף זכאים להחזר עד $1,700–$2,000 לילד בשנה.",
      full: "התנאי לקבלת המענק הוא קיום הכנסה מיגיעה אישית (משכורת כעובד או עסק עצמאי).",
      sourceText: "IRS – Child Tax Credit Guide",
      sourceUrl: "https://www.irs.gov/credits-deductions/individuals/child-tax-credit",
      focus: "מיקוד במקור: טאב 'Qualifying Child Requirements'."
    },
    {
      q: "5. בנקים בישראל: למה הבנק דורש למלא טופס W-9?",
      short: "בגלל חוק ה-<span class='term' onclick='showTerm(\"FATCA\")'>FATCA</span>. הבנקים מחויבים לדווח לרשויות בארה\"ב על חשבונות אזרחים.",
      full: "טופס W-9 מספק לבנק את מספר ה-SSN שלך ומאשר את זהותך כמדווח אמריקאי.",
      sourceText: "U.S. Department of the Treasury – FATCA",
      sourceUrl: "https://home.treasury.gov/policy-issues/tax-policy/foreign-account-tax-compliance-act",
      focus: "מיקוד במקור: סעיף 'FATCA Information for Individuals'."
    }
  ];

  // רינדור השאלות למסך
  function renderFAQ(data) {
    const container = document.getElementById('faqContainer');
    container.innerHTML = '';

    data.forEach((item, index) => {
      const card = document.createElement('div');
      card.className = 'faq-card';
      card.innerHTML = `
        <div class="question">${item.q}</div>
        <div class="short-answer">${item.short}</div>
        <button class="expand-btn" onclick="toggleExpand(${index})">להרחבה ומקור מוסמך ▼</button>
        <div id="details-${index}" class="full-details">
          <p>${item.full}</p>
          <hr style="border:0; border-top:1px solid #e2e8f0; margin:10px 0;">
          <a href="${item.sourceUrl}" target="_blank" class="source-link">🔗 מקור מוסמך: ${item.sourceText}</a>
          <div style="font-size:0.85rem; color:#4a5568; margin-top:4px;">${item.focus}</div>
        </div>
      `;
      container.appendChild(card);
    });
  }

  // פתיחה/סגירה של הרחבה
  function toggleExpand(index) {
    const details = document.getElementById(`details-${index}`);
    const btn = details.previousElementSibling;
    if (details.style.display === 'block') {
      details.style.display = 'none';
      btn.innerHTML = 'להרחבה ומקור מוסמך ▼';
    } else {
      details.style.display = 'block';
      btn.innerHTML = 'סגור הרחבה ▲';
    }
  }

  // סינון לפי חיפוש
  function filterQuestions() {
    const term = document.getElementById('searchInput').value.toLowerCase();
    const filtered = faqData.filter(item => 
      item.q.toLowerCase().includes(term) || 
      item.short.toLowerCase().includes(term) ||
      item.full.toLowerCase().includes(term)
    );
    renderFAQ(filtered);
  }

  // הצגת חלונית מונחון
  function showTerm(key) {
    if (glossary[key]) {
      document.getElementById('modalTitle').innerText = key;
      document.getElementById('modalBody').innerText = glossary[key];
      document.getElementById('modalOverlay').style.display = 'flex';
    }
  }

  function closeModal() {
    document.getElementById('modalOverlay').style.display = 'none';
  }

  // טעינה ראשונית
  renderFAQ(faqData);
</script>

</body>
</html>
