<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>VIPZEXNET — پرسرعت، پایدار و همیشه آنلاین</title>
  <meta name="description" content="VIPZEXNET: سرویس‌های VPN پرسرعت و پایدار برای اندروید، iOS و ویندوز. خرید اشتراک، آموزش راه‌اندازی، پشتیبانی و شبکه‌های اجتماعی." />
  <link rel="preconnect" href="https://cdn.fontcdn.ir" />
  <link href="https://cdn.fontcdn.ir/Font/Persian/Vazirmatn/Vazirmatn.css" rel="stylesheet" />
  <style>
    :root{
      --bg-dark:#0b0f14;
      --glass:rgba(255,255,255,.06);
      --muted:#c9d4e3;
      --brand:#00c853;
      --brand-2:#11e070;
      --brand-hover:#00ffa3;
      --danger:#ff5252;
      --card:rgba(255,255,255,.08);
      --shadow:0 10px 30px rgba(0,0,0,.35);
      --radius:16px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      background: linear-gradient(135deg, #0b0f14, #061218) no-repeat fixed;
      background-size: cover;
      color:#fff;
      font-family:'Vazirmatn',system-ui,-apple-system,Segoe UI,Roboto,'Tahoma',sans-serif;
      line-height:1.85;
    }
    body::before{
      content:"";
      position:fixed;
      inset:0;
      background:radial-gradient(80% 120% at 50% 0%,rgba(0,200,83,.12),transparent 70%),linear-gradient(180deg,rgba(0,0,0,.5),rgba(0,0,0,.65));
      z-index:-1;
    }
    a{color:var(--brand)}
    img{max-width:100%;height:auto;border-radius:8px}
    .nav{position:sticky;top:0;z-index:50;backdrop-filter:blur(12px);background:rgba(10,14,18,.8);border-bottom:1px solid rgba(255,255,255,.08)}
    .nav .wrap{max-width:1100px;margin:auto;display:flex;align-items:center;justify-content:space-between;padding:12px 16px}
    .brand{display:flex;align-items:center;gap:10px;font-weight:900;letter-spacing:.2px}
    .brand-logo{width:36px;height:36px;border-radius:10px;background:linear-gradient(135deg,var(--brand),#0affb3);display:grid;place-items:center;box-shadow:var(--shadow)}
    .brand-logo span{font-weight:900;color:#072216}
    .menu{display:flex;gap:8px;align-items:center}
    .menu a{color:#fff;text-decoration:none;padding:8px 12px;border-radius:10px;transition:.25s}
    .menu a:hover{background:var(--glass)}
    .menu .cta{background:linear-gradient(135deg,var(--brand),var(--brand-hover));color:#062015;font-weight:800}
    .menu .cta:hover{transform:translateY(-1px);background:linear-gradient(135deg,var(--brand-2),#00ffa3)}
    .burger{display:none;cursor:pointer;border:1px solid rgba(255,255,255,.1);padding:8px 10px;border-radius:10px;color:#fff}
    @media (max-width:840px){
      .menu{display:none}
      .burger{display:block}
      .drawer{position:fixed;inset:56px 0 auto 0;background:rgba(10,14,18,.96);display:none;padding:18px;border-top:1px solid rgba(255,255,255,.08)}
      .drawer a{display:block;padding:12px 10px;border-radius:12px;text-decoration:none;color:#fff}
      .drawer a:hover{background:var(--glass)}
      .drawer.show{display:block}
    }
    .hero{max-width:1100px;margin:24px auto 10px;display:grid;grid-template-columns:1.2fr .8fr;gap:18px;padding:0 16px}
    .hero-card{background:var(--card);border:1px solid rgba(255,255,255,.08);border-radius:20px;padding:22px;box-shadow:var(--shadow)}
    .hero h1{margin:0 0 10px;font-size:clamp(22px,4.3vw,34px)}
    .hero p.lead{color:var(--muted);margin-top:6px}
    .badges{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}
    .badge{background:rgba(255,255,255,.08);padding:6px 10px;border-radius:999px;font-size:.9rem}
    .slider{position:relative;overflow:hidden;height:160px;border-radius:16px;border:1px solid rgba(255,255,255,.08)}
    .slides{display:flex;width:300%;height:100%;transition:transform .6s ease}
    .slide{flex:1 0 100%;display:grid;place-items:center;background:linear-gradient(135deg,rgba(0,200,83,.18),rgba(0,200,83,.05));color:#eafff3;text-align:center;padding:16px}
    @media (max-width:940px){.hero{grid-template-columns:1fr}}
    .wrap{max-width:1100px;margin:auto;padding:10px 16px}
    .section-title{font-size:clamp(18px,3.4vw,26px);margin:28px 0 14px}
    .pricing{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:16px}
    .card{background:var(--card);border:1px solid rgba(255,255,255,.08);border-radius:20px;padding:18px;box-shadow:var(--shadow);transition:.25s}
    .card:hover{transform:translateY(-3px)}
    .card h3{margin:4px 0 8px}
    .price{font-size:1.25rem;font-weight:900}
    .features{margin:10px 0 14px;color:var(--muted)}
    .btn{display:inline-block;padding:10px 14px;border-radius:12px;background:linear-gradient(135deg,var(--brand),var(--brand-hover));color:#062015;text-decoration:none;font-weight:800;box-shadow:0 6px 18px rgba(0,200,83,.35);transition:.25s}
    .btn:hover{background:linear-gradient(135deg,var(--brand-2),#00ffa3)}
    .tag{display:inline-block;margin-bottom:8px;padding:6px 10px;border-radius:999px;background:rgba(255,255,255,.08);border:1px dashed rgba(255,255,255,.15)}
    .faq{display:grid;gap:10px}
    .faq-item{background:var(--card);border:1px solid rgba(255,255,255,.08);border-radius:14px}
    .faq-q{cursor:pointer;padding:14px 16px;font-weight:700;display:flex;justify-content:space-between;align-items:center}
    .faq-a{padding:0 16px 14px;color:var(--muted);display:none}
    .faq-item.open .faq-a{display:block}
    .testimonials{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:14px}
    .review{background:var(--card);border:1px solid rgba(255,255,255,.08);border-radius:16px;padding:14px}
    .socials{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px}
    .soc{background:var(--card);border:1px solid rgba(255,255,255,.08);border-radius:14px;padding:14px;display:flex;gap:10px;align-items:center}
    .soc img{width:36px;height:36px;border-radius:10px}
    .float-chat{position:fixed;bottom:20px;left:20px;background:linear-gradient(135deg,var(--brand),var(--brand-hover));color:#062015;padding:10px 14px;border-radius:999px;font-weight:800;text-decoration:none;box-shadow:var(--shadow);transition:.3s}
    .float-chat:hover{transform:translateY(-2px)}
    .to-top{position:fixed;bottom:20px;right:20px;background:#121820;color:#fff;padding:10px 12px;border-radius:12px;text-decoration:none;border:1px solid rgba(255,255,255,.12)}
    footer{margin:34px 0 20px;text-align:center;color:#b7c5d8}
    footer a{color:#a9ffd0}
  </style>
</head>
<body>
  <nav class="nav" aria-label="Main navigation">
    <div class="wrap">
      <a class="brand" href="#home" aria-label="VIPZEXNET Home">
        <div class="brand-logo" aria-hidden="true"><span>V</span></div>
        <span>VIPZEXNET</span>
      </a>
      <div class="menu" role="menubar">
        <a href="#plans" role="menuitem">پلن‌ها</a>
        <a href="#guide" role="menuitem">آموزش</a>
        <a href="#faq" role="menuitem">سوالات</a>
        <a href="#socials" role="menuitem">شبکه‌های اجتماعی</a>
        <a class="cta" href="https://rubika.ir/Mahdi_shami89" target="_blank" rel="noopener">خرید سریع</a>
      </div>
      <button class="burger" id="burger" aria-label="باز کردن منو" aria-expanded="false">☰</button>
    </div>
    <div class="drawer" id="drawer">
      <a href="#plans">پلن‌ها</a>
      <a href="#guide">آموزش</a>
      <a href="#faq">سوالات</a>
      <a href="#socials">شبکه‌های اجتماعی</a>
      <a class="cta" href="https://rubika.ir/Mahdi_shami89" target="_blank" rel="noopener">خرید سریع</a>
    </div>
  </nav>

  <section class="hero" id="home">
    <div class="hero-card">
      <h1>🔋 با VIPZEXNET بهترین سرعت VPN را تجربه کنید — بدون قطعی</h1>
      <p class="lead">اتصال پرسرعت، پایدار، بدون محدودیت و قابل استفاده در تمامی دستگاه‌ها</p>
      <div class="badges" aria-label="Supported locations and devices">
        <span class="badge">🌍 لوکیشن‌ها: 🇩🇪 🇦🇪 🇹🇷 🇸🇪 🇫🇷 🇬🇧 🇺🇸</span>
        <span class="badge">📱 دستگاه‌ها: اندروید، iOS، ویندوز</span>
        <span class="badge">🎯 مناسب: اینستاگرام، یوتیوب، گیم</span>
      </div>
      <div class="ticker" style="margin-top:10px">
        <div class="tick">⚡️ آپتایم بالا و پینگ پایین</div>
        <div class="tick">🛡️ پروتکل‌های امن و ضد فیلتر</div>
        <div class="tick">♾️ ترافیک نامحدود</div>
        <div class="tick">🎁 پشتیبانی سریع تلگرام</div>
      </div>
    </div>

    <div class="hero-card">
      <div class="slider" aria-roledescription="carousel">
        <div class="slides" id="slides">
          <div class="slide">🔥 پیشنهاد ویژه: اشتراک سه‌کاربره — فقط <b>۳۰٬۰۰۰</b> تومان</div>
          <div class="slide">🎮 مخصوص گیمرها: مسیرهای کم‌پینگ برای بازی‌های آنلاین</div>
          <div class="slide">🎓 آموزش قدم‌به‌قدم رایگان در آپارات — راه‌اندازی در ۱ دقیقه</div>
        </div>
      </div>
    </div>
  </section>

  <section class="wrap" id="plans">
    <h2 class="section-title">💎 پلن‌های نامحدود</h2>
    <div class="pricing">
      <article class="card">
        <div class="tag">⭐️ تک‌کاربر</div>
        <h3>نامحدود تک‌کاربر</h3>
        <div class="price">۱۰۰,۰۰۰ تومان</div>
        <ul class="features">
          <li>ترافیک نامحدود</li>
          <li>پشتیبانی تلگرام</li>
          <li>مناسب استریم و سوشال</li>
        </ul>
        <a class="btn" href="https://rubika.ir/Mahdi_shami89" target="_blank" rel="noopener">خرید</a>
      </article>

      <article class="card">
        <div class="tag">⭐️ دوکاربر</div>
        <h3>نامحدود دوکاربر</h3>
        <div class="price">۵۰,۰۰۰ تومان</div>
        <ul class="features">
          <li>فعال روی دو دستگاه</li>
          <li>پشتیبانی تلگرام</li>
          <li>سرعت پایدار</li>
        </ul>
        <a class="btn" href="https://rubika.ir/Mahdi_shami89" target="_blank" rel="noopener">خرید</a>
      </article>

      <article class="card">
        <div class="tag">⭐️ سه‌کاربر</div>
        <h3>نامحدود سه‌کاربر</h3>
        <div class="price">۳۰,۰۰۰ تومان</div>
        <ul class="features">
          <li>فعال روی سه دستگاه</li>
          <li>پشتیبانی تلگرام</li>
          <li>برای خانواده/تیم کوچک</li>
        </ul>
        <a class="btn" href="https://rubika.ir/Mahdi_shami89" target="_blank" rel="noopener">خرید</a>
      </article>
    </div>
  </section>

  <section class="wrap" id="guide">
    <h2 class="section-title">🎓 آموزش وارد کردن کانفیگ</h2>
    <p>برای یادگیری نحوه وارد کردن کانفیگ VPN، روی دکمه زیر کلیک کنید. ویدیوها کوتاه و مرحله‌به‌مرحله هستند.</p>
    <p>
      <a class="btn" href="https://www.aparat.com/playlist/21562118" target="_blank" rel="noopener">مشاهده آموزش در آپارات</a>
      <a class="btn" id="copy-buy" href="#" style="background:#1bd67a;margin-right:8px">کپی لینک خرید</a>
    </p>
    <small style="color:#a7b6c9">نکته: برای بهترین سرعت، نزدیک‌ترین لوکیشن به خودتان را انتخاب کنید.</small>
  </section>

  <section class="wrap" id="reviews">
    <h2 class="section-title">💬 نظرات کاربران</h2>
    <div class="testimonials">
      <div class="review">«از وقتی VIPZEXNET گرفتم، پینگ پابجی خیلی بهتر شده. عالی بود!» — <b>سینا</b></div>
      <div class="review">«برای یوتیوب و اینستاگرام بدون قطعی کار می‌کنه. سپاس!» — <b>ریحانه</b></div>
      <div class="review">«نصب راحت، پشتیبانی سریع. پیشنهاد می‌کنم.» — <b>مهدی</b></div>
    </div>
  </section>

  <section class="wrap" id="faq">
    <h2 class="section-title">❓ سوالات متداول</h2>
    <div class="faq">
      <div class="faq-item">
        <div class="faq-q">روی چه دستگاه‌هایی کار می‌کند؟ <span>＋</span></div>
        <div class="faq-a">اندروید، iOS و ویندوز پشتیبانی می‌شود. راهنمای نصب را در بخش آموزش ببینید.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q">آیا سرعت محدود می‌شود؟ <span>＋</span></div>
        <div class="faq-a">خیر، پلن‌ها نامحدود هستند و برای استریم و بازی بهینه شده‌اند.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q">پشتیبانی از کجا انجام می‌شود؟ <span>＋</span></div>
        <div class="faq-a">از طریق تلگرام در آیدی <a href="https://t.me/Mahdi_shami" target="_blank" rel="noopener">@Mahdi_shami</a>.</div>
      </div>
    </div>
  </section>

  <section class="wrap" id="socials">
    <h2 class="section-title">🌐 شبکه‌های اجتماعی VIPZEX
