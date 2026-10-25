
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>كورة الصقر | أخبار ومباريات كرة القدم</title>
<meta name="description" content="كورة الصقر - تابع أخبار كرة القدم ومواعيد المباريات والنتائج وأهم الأحداث الرياضية.">
<style>
:root {
  --bg:#07111f;
  --panel:#101e30;
  --green:#19d38a;
  --white:#f5f7fb;
  --muted:#9aabc0;
}
* {box-sizing:border-box}
body {
  margin:0;
  font-family:Tahoma,Arial,sans-serif;
  background:var(--bg);
  color:var(--white);
  line-height:1.8;
}
a {color:inherit;text-decoration:none}
header {
  background:#0b1829;
  border-bottom:1px solid #203249;
  position:sticky;
  top:0;
  z-index:10;
}
.container {width:min(1120px,92%);margin:auto}
.nav {
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:15px;
  flex-wrap:wrap;
  padding:14px 0;
}
.logo {font-size:24px;font-weight:bold}
.logo span {color:var(--green)}
nav {display:flex;gap:18px;flex-wrap:wrap}
nav a:hover {color:var(--green)}
.hero {
  padding:55px 0;
  background:radial-gradient(ellipse at top left,#154c45 0%,#0c2030 40%,#07111f 78%);
}
.hero h1 {font-size:clamp(30px,5vw,48px);line-height:1.4;margin:0 0 12px}
.hero h1 span {color:var(--green)}
.hero p {color:#c1cede;max-width:650px}
.btn {
  display:inline-block;
  background:var(--green);
  color:#06151a;
  padding:10px 20px;
  border:0;
  border-radius:9px;
  font-weight:bold;
  cursor:pointer;
  font-size:15px;
}
section {padding:30px 0}
.section-head {
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:12px;
  flex-wrap:wrap;
  margin-bottom:18px;
}
h2 {font-size:25px;margin:0}
h2 span {color:var(--green)}
.muted {color:var(--muted)}
.filters {display:flex;gap:8px;flex-wrap:wrap}
.filters button {
  border:1px solid #2b4058;
  background:var(--panel);
  color:white;
  padding:8px 13px;
  border-radius:8px;
  cursor:pointer;
}
.filters button.active,.filters button:hover {
  background:var(--green);color:#06151a;
}
.match-grid,.news-grid {
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
  gap:15px;
}
.card {
  background:var(--panel);
  border:1px solid #203249;
  border-radius:14px;
  padding:18px;
}
.card:hover {border-color:var(--green)}
.match-top {
  display:flex;
  justify-content:space-between;
  color:var(--muted);
  font-size:13px;
  gap:8px;
}
.status {color:var(--green)}
.teams {
  display:grid;
  grid-template-columns:1fr auto 1fr;
  align-items:center;
  text-align:center;
  gap:8px;
  margin:18px 0;
}
.team-name {font-weight:bold}
.score {font-size:25px;font-weight:bold;white-space:nowrap}
.small {font-size:13px;color:var(--muted)}
.news-icon {
  background:#193b3a;
  border-radius:10px;
  display:grid;
  place-items:center;
  min-height:105px;
  font-size:44px;
  margin-bottom:12px;
}
.news-card h3 {margin:5px 0;font-size:18px}
.news-card p {color:var(--muted);font-size:14px}
.notice {
  border-right:4px solid var(--green);
  background:#102a2a;
  padding:12px 15px;
  border-radius:8px;
  color:#c8f7e4;
  font-size:13px;
}
.search {
  background:#0b1829;
  border:1px solid #30445c;
  border-radius:9px;
  color:white;
  padding:11px 14px;
  width:100%;
  max-width:330px;
  font-size:15px;
}
.empty {display:none;color:var(--muted);padding:20px}
footer {
  border-top:1px solid #203249;
  padding:25px 0;
  color:var(--muted);
  text-align:center;
  margin-top:25px;
}
footer strong {color:var(--green)}
@media(max-width:600px) {
  .hero {padding:35px 0}
  .nav {justify-content:center}
  nav {justify-content:center;font-size:14px}
  .section-head {align-items:flex-start}
}
</style>
</head>
<body>

<header>
  <div class="container nav">
    <a class="logo" href="#home">🦅 كورة <span>الصقر</span></a>
    <nav>
      <a href="#home">الرئيسية</a>
      <a href="#matches">المباريات</a>
      <a href="#news">الأخبار</a>
      <a href="#about">عن الموقع</a>
    </nav>
  </div>
</header>

<main>
  <section class="hero" id="home">
    <div class="container">
      <p style="color:#19d38a;font-weight:bold">⚽ عالم كرة القدم بين إيديك</p>
      <h1>أنت في قلب الحدث مع <span>كورة الصقر</span></h1>
      <p>تابع أهم أخبار كرة القدم، ومواعيد المباريات، والنتائج، وأبرز الأحداث الرياضية في مكان واحد.</p>
      <a class="btn" href="#matches">شاهد جدول المباريات ↓</a>
    </div>
  </section>

  <section id="matches">
    <div class="container">
      <div class="section-head">
        <h2>⚽ جدول <span>المباريات</span></h2>
        <div class="filters">
          <button class="active" data-filter="all">الكل</button>
          <button data-filter="upcoming">قادمة</button>
          <button data-filter="finished">منتهية</button>
        </div>
      </div>

      <p class="notice">تنبيه: المباريات والنتائج المعروضة أدناه بيانات تجريبية لتوضيح شكل الموقع، وليست جدولًا حقيقيًا أو مباشرًا.</p>

      <div class="match-grid" id="matchGrid">
        <article class="card match" data-status="upcoming">
          <div class="match-top"><span>الدوري الإنجليزي</span><span class="status">قادمة - مثال</span></div>
          <div class="teams">
            <div class="team-name">مانشستر سيتي</div>
            <div class="score">VS</div>
            <div class="team-name">ليفربول</div>
          </div>
          <div class="small">موعد تجريبي: 8:00 مساءً</div>
        </article>

        <article class="card match" data-status="finished">
          <div class="match-top"><span>الدوري الإسباني</span><span class="status">منتهية - مثال</span></div>
          <div class="teams">
            <div class="team-name">ريال مدريد</div>
            <div class="score">2 - 1</div>
            <div class="team-name">برشلونة</div>
          </div>
          <div class="small">نتيجة تجريبية وليست نتيجة مباراة حقيقية</div>
        </article>

        <article class="card match" data-status="upcoming">
          <div class="match-top"><span>الدوري المصري</span><span class="status">قادمة - مثال</span></div>
          <div class="teams">
            <div class="team-name">الأهلي</div>
            <div class="score">VS</div>
            <div class="team-name">الزمالك</div>
          </div>
          <div class="small">موعد تجريبي - يُرجى تحديثه</div>
        </article>

        <article class="card match" data-status="finished">
          <div class="match-top"><span>دوري أبطال أوروبا</span><span class="status">منتهية - مثال</span></div>
          <div class="teams">
            <div class="team-name">باريس</div>
            <div class="score">3 - 2</div>
            <div class="team-name">بايرن</div>
          </div>
          <div class="small">نتيجة تجريبية وليست نتيجة مباراة حقيقية</div>
        </article>
      </div>
      <p class="empty" id="matchEmpty">لا توجد مباريات في هذا التصنيف.</p>
    </div>
  </section>

  <section id="news">
    <div class="container">
      <div class="section-head">
        <h2>📰 أحدث <span>الأخبار</span></h2>
        <input class="search" id="newsSearch" type="search" placeholder="ابحث في الأخبار التجريبية...">
      </div>

      <p class="notice">الأخبار التالية أمثلة لتصميم الموقع. استبدلها بأخبار حقيقية ومحدثة قبل النشر.</p>

      <div class="news-grid" id="newsGrid">
        <article class="card news-card">
          <div class="news-icon">🏆</div>
          <div class="small">أخبار كرة القدم</div>
          <h3>كل ما تحتاج معرفته عن عالم الساحرة المستديرة</h3>
          <p>مساحة مخصصة لنشر أخبار الأندية والبطولات والتحليلات الرياضية.</p>
        </article>

        <article class="card news-card">
          <div class="news-icon">⚽</div>
          <div class="small">متابعة المباريات</div>
          <h3>كيف تتابع مباريات فريقك المفضل؟</h3>
          <p>أضف هنا موعد المباراة والقنوات الناقلة والتفاصيل المؤكدة من مصادر موثوقة.</p>
        </article>

        <article class="card news-card">
          <div class="news-icon">🦅</div>
          <div class="small">كورة الصقر</div>
          <h3>وجهتك لمعرفة أبرز الأحداث الرياضية</h3>
          <p>انشر ملخصات وتحليلات أصلية ونتائج مؤكدة لتقديم تجربة مفيدة للزوار.</p>
        </article>
      </div>
      <p class="empty" id="newsEmpty">لا توجد نتائج للبحث.</p>
    </div>
  </section>

  <section id="about">
    <div class="container">
      <div class="card">
        <h2>عن <span>كورة الصقر</span> 🦅</h2>
        <p class="muted">موقع رياضي عربي يهتم بأخبار كرة القدم والمباريات والنتائج والتحليلات. يمكنك تطوير الموقع وإضافة أقسام جديدة مثل ترتيب الدوريات والهدافين وملخصات المباريات.</p>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="container">
    <div class="logo">🦅 كورة <span>الصقر</span></div>
    <p>أخبار كرة القدم في مكان واحد</p>
    <p>© <span id="year"></span> كورة الصقر - جميع الحقوق محفوظة.</p>
    <p>الموقع التجريبي يحتاج إلى تحديث المحتوى قبل النشر.</p>
  </div>
</footer>

<script>
document.getElementById("year").textContent = new Date().getFullYear();

const filterButtons = document.querySelectorAll("[data-filter]");
const matches = document.querySelectorAll(".match");
const matchEmpty = document.getElementById("matchEmpty");

filterButtons.forEach(button => {
  button.addEventListener("click", () => {
    filterButtons.forEach(b => b.classList.remove("active"));
    button.classList.add("active");

    const filter = button.dataset.filter;
    let shown = 0;

    matches.forEach(match => {
      const visible = filter === "all" || match.dataset.status === filter;
      match.style.display = visible ? "" : "none";
      if (visible) shown++;
    });

    matchEmpty.style.display = shown ? "none" : "block";
  });
});

const newsSearch = document.getElementById("newsSearch");
const newsCards = document.querySelectorAll(".news-card");
const newsEmpty = document.getElementById("newsEmpty");

newsSearch.addEventListener("input", () => {
  const term = newsSearch.value.trim().toLowerCase();
  let shown = 0;

  newsCards.forEach(card => {
    const visible = card.textContent.toLowerCase().includes(term);
    card.style.display = visible ? "" : "none";
    if (visible) shown++;
  });

  newsEmpty.style.display = shown ? "none" : "block";
});
</script>
</body>
</html>
