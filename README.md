<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>صفحة الطالب — عبدالله المطيري</title>
  <style>
    :root{ --accent:#2b6cb0; --muted:#6b7280; --bg:#f7fafc; --card:#ffffff; font-family: "Segoe UI", Tahoma, Arial, sans-serif; }
    html,body{ height:100%; margin:0; background:var(--bg); color:#111827; direction:rtl; }
    .container{ max-width:900px; margin:30px auto; padding:20px; }
    header{ display:flex; gap:20px; align-items:center; background:linear-gradient(90deg,var(--card),#f0f6ff); border-radius:12px; padding:18px; box-shadow:0 6px 18px rgba(16,24,40,0.06); }
    .photo { width:140px; height:140px; border-radius:50%; overflow:hidden; flex:0 0 140px; border:4px solid #fff; box-shadow:0 6px 18px rgba(43,108,176,0.16); background:#e6eefc; display:flex; align-items:center; justify-content:center; }
    .photo img{ width:100%; height:100%; object-fit:cover; display:block; }
    .heading{ flex:1; }
    h1{ margin:0; font-size:1.4rem; color:var(--accent); }
    p.subtitle{ margin:6px 0 0; color:var(--muted); }
    .card{ margin-top:20px; background:var(--card); border-radius:12px; padding:18px; box-shadow:0 6px 18px rgba(15,23,42,0.05); }
    .grid{ display:grid; grid-template-columns: 1fr 1fr; gap:14px; }
    .field{ padding:12px; border-radius:8px; background:#fbfdff; border:1px solid #eef2ff; }
    .field h3{ margin:0 0 6px 0; font-size:0.95rem; color:#0f172a; }
    .field p{ margin:0; color:var(--muted); font-size:0.95rem; }
    .full{ grid-column:1 / -1; }
    .skills{ display:flex; flex-wrap:wrap; gap:8px; }
    .skill{ background:#eef2ff; color:var(--accent); padding:6px 10px; border-radius:999px; font-size:0.85rem; }
    footer{ margin-top:18px; text-align:center; color:var(--muted); font-size:0.9rem; }
    @media (max-width:640px){ .grid{ grid-template-columns: 1fr; } .photo{ width:110px; height:110px; flex:0 0 110px; } }
  </style>
</head>
<body>
  <div class="container">
    <header role="banner" aria-label="معلومات الطالب">
      <div class="photo" aria-hidden="false">
        <!-- استبدل الصورة المدمجة بصورة حقيقية بوضع abdullah.jpg في نفس المجلد -->
        <img src="abdullah.jpg" alt="عبدالله المطيري" onerror="this.style.display='none'">
      </div>
      <div class="heading">
        <h1>الاسم: عبدالله المطيري</h1>
        <p class="subtitle">طالب في كلية التجارة — التخصص: إدارة أعمال</p>
        <p class="subtitle">السنة الدراسية: الثالثة — الرقم الجامعي: 2444312</p>
      </div>
    </header>

    <section class="card" aria-labelledby="about-heading">
      <h2 id="about-heading" style="margin-top:0; color:#0f172a;">نبذة مختصرة</h2>
      <p style="color:var(--muted); margin:8px 0 14px;">
        مرحباً، اسمي عبدالله المطيري طالب في كلية التجارة مهتم بالتسويق والتحليل المالي. يمكنك تعديل هذا النص لوصف اهتماماتك الأكاديمية والعملية أو إضافة مشاريع وتجارب تدريبية.
      </p>

      <div class="grid" role="list">
        <div class="field" role="listitem">
          <h3>معلومات الاتصال</h3>
          <p>البريد الإلكتروني: your.email@example.com</p>
          <p>الهاتف: 05X-XXX-XXXX</p>
        </div>

        <div class="field" role="listitem">
          <h3>الكلية / الجامعة</h3>
          <p>كلية التجارة — جامعة المثال</p>
          <p>القسم: إدارة أعمال</p>
        </div>

        <div class="field">
          <h3>المواد الرئيسية الحالية</h3>
          <p>محاسبة مالية، تسويق، اقتصاد إداري، نظم معلومات إدارية</p>
        </div>

        <div class="field">
          <h3>المعدل التراكمي</h3>
          <p>مثال: 3.75 / 5.0</p>
        </div>

        <div class="field full">
          <h3>المهارات</h3>
          <div class="skills" aria-hidden="false">
            <span class="skill">تحليل بيانات</span>
            <span class="skill">عروض تقديمية</span>
            <span class="skill">تسويق رقمي</span>
            <span class="skill">إتقان Excel</span>
          </div>
        </div>
      </div>

      <footer>
        لتغيير أي نص، افتح index.html وعدل. لحذف SVG أو استبدال الصورة: ضع abdullah.jpg في نفس المجلد.
      </footer>
    </section>
  </div>
</body>
</html>
