<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>أرشيف الشخصيات — مدمج</title>

  <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#2f2a3a;
      --panel:#3a3244;
      --accent:#ffbf00;
      --muted:#bdb6c6;
      --card-width: 170px;
      --card-aspect: 1.3;
      --gap: 18px;
      --radius:12px;
      font-family: "Tajawal", system-ui, sans-serif;
    }
    html,body{height:100%; margin:0; background:var(--bg); color:#fff; -webkit-font-smoothing:antialiased;}
    a{color:inherit}
    .topbar{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:12px;
      padding:18px;
    }
    .brand{
      display:flex;
      gap:12px;
      align-items:center;
    }
    .brand h1{font-size:18px;margin:0;color:#fff}
    .controls{
      display:flex;
      gap:10px;
      align-items:center;
    }
    .langBtn{
      background:transparent;border:1px solid rgba(255,255,255,0.08);padding:8px 10px;border-radius:8px;color:var(--muted);cursor:pointer;
    }
    .countdown{
      display:flex;
      gap:10px;
      align-items:center;
      padding:10px 14px;
      background:linear-gradient(90deg, rgba(255,255,255,0.03), rgba(255,255,255,0.02));
      border-radius:10px;
      color:var(--muted);
      font-size:14px;
    }
    .countdown b{color:var(--accent);margin:0 6px;font-weight:700}
    .container{
      padding:18px;
      display:grid;
      grid-template-columns: 300px 1fr;
      gap:18px;
    }
    .sidebar{
      padding:14px;
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:12px;
      min-height:220px;
    }
    .filter-group{margin-bottom:14px}
    .filter-group h3{margin:0 0 8px 0;font-size:14px;color:var(--muted)}
    .chips{display:flex;flex-wrap:wrap;gap:8px}
    .chip{
      padding:8px 10px;border-radius:8px;background:transparent;border:1px solid rgba(255,255,255,0.06);
      cursor:pointer;color:var(--muted);font-size:13px;
    }
    .chip.active{background:var(--accent); color:#111; border-color:var(--accent); font-weight:700}
    .searchBox{
      display:flex; gap:8px; margin-bottom:12px;
    }
    .searchBox input{
      flex:1;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.06);
      background:transparent;color:#fff;
    }
    .searchBox button{padding:10px 12px;border-radius:8px;border:none;background:var(--accent);color:#111;cursor:pointer}

    .panel{
      padding:14px;
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:12px;
    }
    .grid{
      display:grid;
      gap:var(--gap);
      grid-template-columns: repeat(5, minmax(0,1fr));
      align-items:start;
    }

    .card{
      background:var(--panel);
      border-radius:var(--radius);
      overflow:visible;
      transform-origin:center;
      transition:transform .18s ease, box-shadow .18s ease;
      cursor:pointer;
      user-select:none;
      -webkit-user-select:none;
      display:flex;
      flex-direction:column;
      align-items:stretch;
      position:relative;
      padding:10px;
      min-height: calc(var(--card-width) * var(--card-aspect));
    }
    .card:focus{outline:2px solid rgba(255,255,255,0.06)}
    .card:hover{ transform: translateY(-6px) scale(1.02); box-shadow: 0 10px 30px rgba(0,0,0,0.45); border:1px solid rgba(255,255,255,0.06);}
    .avatar-wrap{
      position:relative;
      border-radius:10px;
      overflow:hidden;
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(0,0,0,0.04));
      display:block;
      width:100%;
      height:100%;
    }
    .avatar{
      width:100%;
      height:100%;
      object-fit:cover;
      display:block;
      transition:transform .22s ease, outline .22s ease, box-shadow .22s ease;
    }
    .card-footer{
      margin-top:8px;
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:8px;
    }
    .name{font-weight:700;font-size:14px}
    .meta{display:flex;gap:8px;align-items:center}
    .stars{display:flex;gap:3px;align-items:center}
    .star{width:14px;height:14px;display:inline-block}

    .pagination{display:flex;gap:8px;justify-content:center;padding:14px;margin-top:10px}
    .pageBtn{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:8px 12px;border-radius:8px;color:var(--muted);cursor:pointer}
    .pageBtn.active{background:var(--accent);color:#111;border-color:var(--accent)}

    /* modal */
    .overlay{
      position:fixed;inset:0;background:rgba(0,0,0,0.7);display:none;align-items:center;justify-content:center;z-index:9999;padding:20px;
    }
    .overlay.open{display:flex}

    .detailCard{
      width:100%;max-width:1000px; background: rgba(255,255,255,0.94);
      color: #111; border-radius:16px; padding:18px; display:grid; grid-template-columns: 360px 1fr; gap:18px;
      box-shadow: 0 20px 60px rgba(0,0,0,0.45); border: 1px solid rgba(0,0,0,0.08);
    }
    .detail-image{
      border-radius:10px;overflow:hidden;background:#f4f4f4;height:100%;cursor:pointer;display:flex;align-items:center;justify-content:center;
    }
    .detail-image img{width:100%;height:100%;object-fit:cover;display:block}
    .detail-body{display:flex;flex-direction:column;gap:10px}
    .detail-title{display:flex;align-items:center;justify-content:space-between;gap:10px}
    .closeBtn{background:transparent;border:none;color:var(--muted);font-size:16px;cursor:pointer;padding:8px}
    .detail-desc{background:rgba(0,0,0,0.02);padding:12px;border-radius:8px;color:#333;font-size:14px;line-height:1.5}
    .detail-stars{display:flex;gap:4px;align-items:center;margin-top:6px}
    .detail-stars svg{width:16px;height:16px}

    /* full image overlay */
    .img-fullscreen{position:fixed;inset:0;background:rgba(0,0,0,0.9);display:none;align-items:center;justify-content:center;z-index:10000}
    .img-fullscreen.open{display:flex}
    .img-fullscreen img{max-width:95%;max-height:95%;border-radius:8px;box-shadow:0 10px 40px rgba(0,0,0,0.6)}
    .img-fullscreen .closeFull{position:absolute;top:20px;right:20px;background:#fff;color:#000;font-size:18px;font-weight:bold;border:none;border-radius:50%;width:36px;height:36px;cursor:pointer}

    @media (max-width:1100px){
      .container{grid-template-columns: 1fr; padding:12px}
      .grid{grid-template-columns: repeat(4, minmax(0,1fr))}
      .panel{margin-top:12px}
      .detailCard{grid-template-columns:1fr}
    }
    @media (max-width:850px){
      .grid{grid-template-columns: repeat(3, minmax(0,1fr))}
    }
    @media (max-width:560px){
      .grid{grid-template-columns: repeat(2, minmax(0,1fr))}
      .card{min-height: 180px}
      .brand h1{font-size:16px}
    }
    .muted{color:var(--muted);font-size:13px}
  </style>
</head>
<body>

  <div class="topbar">
    <div class="brand">
      <svg width="36" height="36" viewBox="0 0 24 24" fill="none" style="transform:rotate(10deg)">
        <rect width="24" height="24" rx="6" fill="#141215"/>
        <path d="M4 12h16" stroke="#ffbf00" stroke-width="1.4" stroke-linecap="round"/>
      </svg>
      <div>
        <h1 id="siteTitle">أرشيف الشخصيات</h1>
        <div class="muted" id="siteSub">قائمة شخصيات قابلة للفرز والبحث</div>
      </div>
    </div>

    <div class="controls">
      <div class="countdown" id="countdownBox">
        <div id="countdownLabel">موعد التحديث القادم</div>
        <div id="countdownTimer"><b id="cd-days">--</b> أيام  <span id="cd-hms">—</span></div>
      </div>

      <button class="langBtn" id="langToggle">English</button>
    </div>
  </div>

  <div class="container">

    <aside class="sidebar">
      <div class="searchBox">
        <input type="search" id="searchInput" placeholder="ابحث عن اسم الشخصية..." />
        <button id="clearSearch">بحث</button>
      </div>

      <div class="filter-group">
        <h3>فلترة حسب السلاح</h3>
        <div class="chips" id="weaponChips"></div>
      </div>

      <div class="filter-group">
        <h3>فلترة حسب العنصر</h3>
        <div class="chips" id="elementChips"></div>
      </div>

      <div class="filter-group">
        <h3>فلترة حسب النجوم</h3>
        <div class="chips" id="rarityChips"></div>
      </div>

      <div style="margin-top:12px">
        <h3>تصفية سريعة</h3>
        <div class="chips" id="quickFilters">
          <button class="chip" data-quick="all">عرض الكل</button>
          <button class="chip" data-quick="5">خمس نجوم</button>
          <button class="chip" data-quick="4">أربع نجوم</button>
          <button class="chip" data-quick="geo">عنصر الحجر</button>
          <button class="chip" data-quick="sword">سيف</button>
        </div>
      </div>

    </aside>

    <main class="panel">
      <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:12px">
        <div class="muted" id="resultsInfo">عرض 10 من 20 شخصية</div>
        <div class="muted">صفحة <span id="currentPage">1</span> من <span id="totalPages">2</span></div>
      </div>

      <div class="grid" id="grid"></div>

      <div class="pagination" id="pagination"></div>
    </main>

  </div>

  <!-- modal -->
  <div class="overlay" id="overlay">
    <div class="detailCard" role="dialog" aria-modal="true">
      <div class="detail-image" id="detailImage"></div>
      <div class="detail-body">
        <div class="detail-title">
          <div>
            <h2 id="detailName" style="margin:0"></h2>
            <div class="detail-stars" id="detailStars"></div>
            <div class="muted" id="detailMeta"></div>
          </div>
          <div>
            <button class="closeBtn" id="closeDetail">إغلاق ✕</button>
          </div>
        </div>

        <div class="detail-info" id="detailInfo"></div>

        <div class="detail-desc" id="detailDesc"></div>

        <div style="margin-top:auto;display:flex;gap:8px;align-items:center">
          <div class="muted">تم التصميم من قبل فادي الشراري</div>
        </div>
      </div>
    </div>
  </div>

  <!-- full image overlay -->
  <div class="img-fullscreen" id="imgFullscreen">
    <button class="closeFull" id="closeFull">✕</button>
    <img src="" alt="صورة كاملة" id="fullImg">
  </div>

<script>
const characters = [
  { id: "10000101", name_ar:"شيلونين", name_en:"Xilonen", element:"Geo", element_ar:"الحجر", weapon:"Sword", weapon_ar:"سيف", rarity:5, type_ar:"مساعدة", city:"ناتلان",
    headerImg:"https://i.postimg.cc/13JgSmHP/image.png", detailImg:"https://live.staticflickr.com/65535/54708068932_f8edc85f71_c.jpg", avatar:"https://i.postimg.cc/13JgSmHP/image.png", rightIcon:"https://live.staticflickr.com/65535/54708068932_f8edc85f71_c.jpg",
    description_ar:"شيلونين شخصية سبورت بالاساس ويمكن استخدامها كشخصية هجوميه ." },

  { id: "10000102", name_ar:"ايميلي", name_en:"Emilie", element:"Dendro", element_ar:"النبات", weapon:"Polearm", weapon_ar:"رمح", rarity:5, type_ar:"ضرر خارج الميدان", city:"فونتين",
    headerImg:"https://i.postimg.cc/nL99pLMF/image.png", detailImg:"https://i.postimg.cc/Df8HFkPC/image.png", avatar:"https://picsum.photos/seed/p2/420/520", leftIcon:"https://picsum.photos/seed/l2/64/64", rightIcon:"https://picsum.photos/seed/r2/64/64",
    description_ar:"ايميلي شخصية  تسبب ضرر وهي خارج الميدان و مهم يكون فيه تفاعل احتراق لكي تكون بكامل قوتها." },

  { id: "10000103", name_ar:"فلينس", name_en:"Flins", element:"Pyro", element_ar:"النار", weapon:"Catalyst", weapon_ar:"كتاب", rarity:4, type_ar:"هجومي", city:"سوميرو",
    headerImg:"https://picsum.photos/seed/79814/300/400", detailImg:"https://picsum.photos/seed/49371/600/800", avatar:"https://picsum.photos/seed/p3/420/520", leftIcon:"https://picsum.photos/seed/l3/64/64", rightIcon:"https://picsum.photos/seed/r3/64/64",
    description_ar:"فلينس ساحر ناري، هجماته سريعة ومتكاملة." },

  { id: "10000104", name_ar:"آينو", name_en:"Aino", element:"Hydro", element_ar:"الماء", weapon:"Polearm", weapon_ar:"رمح", rarity:4, type_ar:"دعم", city:"تاليا",
    headerImg:"https://picsum.photos/seed/97681/300/400", detailImg:"https://picsum.photos/seed/49913/600/800", avatar:"https://picsum.photos/seed/p4/420/520", leftIcon:"https://picsum.photos/seed/l4/64/64", rightIcon:"https://picsum.photos/seed/r4/64/64",
    description_ar:"آينو محاربة مياه، مرنة وسريعة الحركة." },

  { id: "10000105", name_ar:"اينيفا", name_en:"Ineffa", element:"Cryo", element_ar:"الثّلج", weapon:"Sword", weapon_ar:"سيف", rarity:5, type_ar:"دعم/هجومي", city:"فالق",
    headerImg:"https://picsum.photos/seed/79642/300/400", detailImg:"https://picsum.photos/seed/49895/600/800", avatar:"https://picsum.photos/seed/p5/420/520", leftIcon:"https://picsum.photos/seed/l5/64/64", rightIcon:"https://picsum.photos/seed/r5/64/64",
    description_ar:"اينيفا مهيبة، سيفها يجمّد الأعداء." },

  { id: "10000106", name_ar:"سكيرك", name_en:"Skirk", element:"Electro", element_ar:"الكهرباء", weapon:"Claymore", weapon_ar:"سيف ثقيل", rarity:4, type_ar:"هجومي", city:"أركان",
    headerImg:"https://picsum.photos/seed/55960/300/400", detailImg:"https://picsum.photos/seed/18664/600/800", avatar:"https://picsum.photos/seed/p6/420/520", leftIcon:"https://picsum.photos/seed/l6/64/64", rightIcon:"https://picsum.photos/seed/r6/64/64",
    description_ar:"سكيرك له هجمات عاصفة وكهربائية." },

  { id: "10000107", name_ar:"داهليا", name_en:"Dahlia", element:"Dendro", element_ar:"النبات", weapon:"Catalyst", weapon_ar:"كتاب", rarity:5, type_ar:"دعم", city:"غريندل",
    headerImg:"https://picsum.photos/seed/15208/300/400", detailImg:"https://picsum.photos/seed/21531/600/800", avatar:"https://picsum.photos/seed/p7/420/520", leftIcon:"https://picsum.photos/seed/l7/64/64", rightIcon:"https://picsum.photos/seed/r7/64/64",
    description_ar:"داهليا ساحرة نباتية تمتلك قوى شافية." },

  { id: "10000108", name_ar:"ايسكوفير", name_en:"Escoffier", element:"Pyro", element_ar:"النار", weapon:"Polearm", weapon_ar:"رمح", rarity:4, type_ar:"هجومي", city:"كلايف",
    headerImg:"https://picsum.photos/seed/49304/300/400", detailImg:"https://picsum.photos/seed/40695/600/800", avatar:"https://picsum.photos/seed/p8/420/520", leftIcon:"https://picsum.photos/seed/l8/64/64", rightIcon:"https://picsum.photos/seed/r8/64/64",
    description_ar:"مقاتل قوي بنيران تحترق كالطهي! (مثال وهمي)" },

  { id: "10000109", name_ar:"ايفا", name_en:"Ifa", element:"Hydro", element_ar:"الماء", weapon:"Bow", weapon_ar:"قوس", rarity:5, type_ar:"دعم/رامي", city:"مارينا",
    headerImg:"https://picsum.photos/seed/45782/300/400", detailImg:"https://picsum.photos/seed/64098/600/800", avatar:"https://picsum.photos/seed/p9/420/520", leftIcon:"https://picsum.photos/seed/l9/64/64", rightIcon:"https://picsum.photos/seed/r9/64/64",
    description_ar:"رامية ماهرة تتحكم بتدفق المياه." },

  { id: "10000110", name_ar:"يان فان", name_en:"Lan Yan", element:"Anemo", element_ar:"الهواء", weapon:"Sword", weapon_ar:"سيف", rarity:4, type_ar:"رشيق", city:"بادا",
    headerImg:"https://picsum.photos/seed/72312/300/400", detailImg:"https://picsum.photos/seed/71442/600/800", avatar:"https://picsum.photos/seed/p10/420/520", leftIcon:"https://picsum.photos/seed/l10/64/64", rightIcon:"https://picsum.photos/seed/r10/64/64",
    description_ar:"مقاتل رشيق يتحرك كالنسيم." },

  { id: "10000111", name_ar:"مفاويكا", name_en:"Mavuika", element:"Dendro", element_ar:"النبات", weapon:"Bow", weapon_ar:"قوس", rarity:4, type_ar:"رامي", city:"غريندل",
    headerImg:"https://picsum.photos/seed/25716/300/400", detailImg:"https://picsum.photos/seed/98372/600/800", avatar:"https://picsum.photos/seed/p11/420/520", leftIcon:"https://picsum.photos/seed/l11/64/64", rightIcon:"https://picsum.photos/seed/r11/64/64",
    description_ar:"رامية نباتية" },

  { id: "10000112", name_ar:"سيتشالي", name_en:"Citlali", element:"Geo", element_ar:"الحجر", weapon:"Claymore", weapon_ar:"سيف ثقيل", rarity:5, type_ar:"دفاعي", city:"ليوا",
    headerImg:"https://picsum.photos/seed/41752/300/400", detailImg:"https://picsum.photos/seed/80893/600/800", avatar:"https://picsum.photos/seed/p12/420/520", leftIcon:"https://picsum.photos/seed/l12/64/64", rightIcon:"https://picsum.photos/seed/r12/64/64",
    description_ar:"مقاتلة حجرية ذات دفاع عالٍ" },

  { id: "10000113", name_ar:"شاسكا", name_en:"Chasca", element:"Cryo", element_ar:"الثّلج", weapon:"Catalyst", weapon_ar:"كتاب", rarity:4, type_ar:"دعم", city:"فالق",
    headerImg:"https://picsum.photos/seed/56500/300/400", detailImg:"https://picsum.photos/seed/42370/600/800", avatar:"https://picsum.photos/seed/p13/420/520", leftIcon:"https://picsum.photos/seed/l13/64/64", rightIcon:"https://picsum.photos/seed/r13/64/64",
    description_ar:"ساحرة ثلج لديها مهارات تجميد" },

  { id: "10000114", name_ar:"اورورون", name_en:"Ororon", element:"Electro", element_ar:"الكهرباء", weapon:"Polearm", weapon_ar:"رمح", rarity:5, type_ar:"هجومي", city:"أركان",
    headerImg:"https://picsum.photos/seed/90932/300/400", detailImg:"https://picsum.photos/seed/68613/600/800", avatar:"https://picsum.photos/seed/p14/420/520", leftIcon:"https://picsum.photos/seed/l14/64/64", rightIcon:"https://picsum.photos/seed/r14/64/64",
    description_ar:"مقاتل كهربائي فائق السرعة" },

  { id: "10000115", name_ar:"زيلونين", name_en:"Xilonen", element:"Dendro", element_ar:"النبات", weapon:"Sword", weapon_ar:"سيف", rarity:4, type_ar:"رشيق", city:"سوميرو",
    headerImg:"https://picsum.photos/seed/32933/300/400", detailImg:"https://picsum.photos/seed/30628/600/800", avatar:"https://picsum.photos/seed/p15/420/520", leftIcon:"https://picsum.photos/seed/l15/64/64", rightIcon:"https://picsum.photos/seed/r15/64/64",
    description_ar:"مقاتل نباتي سريع" },

  { id: "10000116", name_ar:"كينيتش", name_en:"Kinich", element:"Geo", element_ar:"الحجر", weapon:"Claymore", weapon_ar:"سيف ثقيل", rarity:5, type_ar:"دفاعي", city:"ليوا",
    headerImg:"https://picsum.photos/seed/26325/300/400", detailImg:"https://picsum.photos/seed/91689/600/800", avatar:"https://picsum.photos/seed/p16/420/520", leftIcon:"https://picsum.photos/seed/l16/64/64", rightIcon:"https://picsum.photos/seed/r16/64/64",
    description_ar:"جندي حجر قوي" },

  { id: "10000117", name_ar:"كاتشينا", name_en:"Kachina", element:"Anemo", element_ar:"الهواء", weapon:"Bow", weapon_ar:"قوس", rarity:4, type_ar:"رامي", city:"بادا",
    headerImg:"https://picsum.photos/seed/31535/300/400", detailImg:"https://picsum.photos/seed/2539/600/800", avatar:"https://picsum.photos/seed/p17/420/520", leftIcon:"https://picsum.photos/seed/l17/64/64", rightIcon:"https://picsum.photos/seed/r17/64/64",
    description_ar:"رامية هوائية بارعة" },

  { id: "10000118", name_ar:"مولاني", name_en:"Mualani", element:"Hydro", element_ar:"الماء", weapon:"Catalyst", weapon_ar:"كتاب", rarity:5, type_ar:"دعم", city:"مارينا",
    headerImg:"https://picsum.photos/seed/235/300/400", detailImg:"https://picsum.photos/seed/53636/600/800", avatar:"https://picsum.photos/seed/p18/420/520", leftIcon:"https://picsum.photos/seed/l18/64/64", rightIcon:"https://picsum.photos/seed/r18/64/64",
    description_ar:"ساحرة مياه متخصصة بالتحكم" },

  { id: "10000119", name_ar:"إميلي", name_en:"Emilie", element:"Cryo", element_ar:"الثّلج", weapon:"Sword", weapon_ar:"سيف", rarity:4, type_ar:"هجومي", city:"فالق",
    headerImg:"https://picsum.photos/seed/42530/300/400", detailImg:"https://picsum.photos/seed/84470/600/800", avatar:"https://picsum.photos/seed/p19/420/520", leftIcon:"https://picsum.photos/seed/l19/64/64", rightIcon:"https://picsum.photos/seed/r19/64/64",
    description_ar:"محاربة ثلج شجاعة" },

  { id: "10000120", name_ar:"سيثوس", name_en:"Sethos", element:"Electro", element_ar:"الكهرباء", weapon:"Polearm", weapon_ar:"رمح", rarity:5, type_ar:"هجومي", city:"أركان",
    headerImg:"https://picsum.photos/seed/28781/300/400", detailImg:"https://picsum.photos/seed/10164/600/800", avatar:"https://picsum.photos/seed/p20/420/520", leftIcon:"https://picsum.photos/seed/l20/64/64", rightIcon:"https://picsum.photos/seed/r20/64/64",
    description_ar:"مقاتل كهربائي ذو تقنيات متقدمة" }
];

const pageSize = 15;
let currentPage = 1;
let currentLang = 'ar';
let filters = { weapons: new Set(), elements: new Set(), rarities: new Set(), text: '' };

const UI = {
  ar: {
    searchPlaceholder: "ابحث عن اسم الشخصية...",
    updateLabel: "موعد التحديث القادم",
    showResults: (count, total)=> `عرض ${count} من ${total} شخصية`,
    pageOf: (p, total)=> `صفحة ${p} من ${total}`,
    btnSearch: "بحث",
    btnClose: "إغلاق",
  },
  en: {
    searchPlaceholder: "Search character name...",
    updateLabel: "Next update",
    showResults: (count, total)=> `Showing ${count} of ${total}`,
    pageOf: (p,total)=> `Page ${p} of ${total}`,
    btnSearch: "Search",
    btnClose: "Close",
  }
};

const weaponsList = [
  {en:'Sword', ar:'سيف خفيف'}, {en:'Catalyst', ar:'كتاب'}, {en:'Claymore', ar:'سيف ثقيل'}, {en:'Bow', ar:'قوس'}, {en:'Polearm', ar:'رمح'}
];
const elementsList = [
  {en:'Dendro', ar:'النبات'}, {en:'Pyro', ar:'النار'}, {en:'Electro', ar:'الكهرباء'}, {en:'Cryo', ar:'الثّلج'}, {en:'Hydro', ar:'الماء'}, {en:'Geo', ar:'الحجر'}, {en:'Anemo', ar:'الهواء'}
];

function createFilterChips(){
  const wc = document.getElementById('weaponChips');
  const ec = document.getElementById('elementChips');
  const rc = document.getElementById('rarityChips');

  weaponsList.forEach(w=>{
    const b = document.createElement('button');
    b.className='chip'; b.textContent = (currentLang==='ar' ? w.ar : w.en);
    b.dataset.weapon = w.en;
    b.addEventListener('click', ()=>{ toggleFilter('weapons', w.en, b) });
    wc.appendChild(b);
  });

  elementsList.forEach(e=>{
    const b = document.createElement('button');
    b.className='chip'; b.textContent = (currentLang==='ar' ? e.ar : e.en);
    b.dataset.element = e.en;
    b.addEventListener('click', ()=>{ toggleFilter('elements', e.en, b) });
    ec.appendChild(b);
  });

  [5,4].forEach(r=>{
    const b = document.createElement('button');
    b.className='chip'; b.textContent = r + " ★";
    b.dataset.rarity = r;
    b.addEventListener('click', ()=>{ toggleFilter('rarities', String(r), b) });
    rc.appendChild(b);
  });
}

function toggleFilter(type, value, btn){
  if(filters[type].has(value)){ filters[type].delete(value); btn.classList.remove('active'); }
  else{ filters[type].add(value); btn.classList.add('active'); }
  currentPage = 1;
  render();
}

document.getElementById('quickFilters').addEventListener('click', (e)=>{
  const t = e.target.closest('.chip'); if(!t) return;
  const key = t.dataset.quick;
  filters = {weapons:new Set(), elements:new Set(), rarities:new Set(), text: ''};
  document.querySelectorAll('.chip').forEach(n=>n.classList.remove('active'));
  if(key==='all'){ }
  else if(key==='5'){ filters.rarities.add('5'); document.querySelectorAll('[data-rarity="5"]')[0]?.classList.add('active'); }
  else if(key==='4'){ filters.rarities.add('4'); document.querySelectorAll('[data-rarity="4"]')[0]?.classList.add('active'); }
  else if(key==='geo'){ filters.elements.add('Geo'); document.querySelectorAll('[data-element="Geo"]')[0]?.classList.add('active'); }
  else if(key==='sword'){ filters.weapons.add('Sword'); document.querySelectorAll('[data-weapon="Sword"]')[0]?.classList.add('active'); }
  currentPage=1; render();
});

const searchInput = document.getElementById('searchInput');
document.getElementById('clearSearch').addEventListener('click', ()=>{
  filters.text = searchInput.value.trim();
  currentPage = 1;
  render();
});
searchInput.addEventListener('input', ()=>{
  filters.text = searchInput.value.trim();
  currentPage = 1;
  render();
});

document.getElementById('langToggle').addEventListener('click', ()=>{
  currentLang = (currentLang==='ar'?'en':'ar');
  applyLang();
  document.getElementById('weaponChips').innerHTML=''; document.getElementById('elementChips').innerHTML=''; document.getElementById('rarityChips').innerHTML='';
  createFilterChips();
});

function applyLang(){
  document.getElementById('langToggle').textContent = (currentLang==='ar'?'English':'العربية');
  document.getElementById('searchInput').placeholder = UI[currentLang].searchPlaceholder;
  document.getElementById('countdownLabel').textContent = UI[currentLang].updateLabel;
  document.getElementById('siteTitle').textContent = (currentLang==='ar'?'أرشيف الشخصيات':'Character Archive');
  render();
}

function getFiltered(){
  const text = filters.text.toLowerCase();
  return characters.filter(c=>{
    if(filters.weapons.size && !filters.weapons.has(c.weapon)) return false;
    if(filters.elements.size && !filters.elements.has(c.element)) return false;
    if(filters.rarities.size && !filters.rarities.has(String(c.rarity))) return false;
    if(text){
      const inName = (c.name_ar + ' ' + (c.name_en||'')).toLowerCase().includes(text);
      if(!inName) return false;
    }
    return true;
  });
}

function render(){
  const all = getFiltered();
  const total = all.length;
  const totalPages = Math.max(1, Math.ceil(total / pageSize));
  if(currentPage > totalPages) currentPage = totalPages;
  const start = (currentPage - 1) * pageSize;
  const pageItems = all.slice(start, start + pageSize);

  document.getElementById('resultsInfo').textContent = UI[currentLang].showResults(pageItems.length, characters.length);
  document.getElementById('currentPage').textContent = currentPage;
  document.getElementById('totalPages').textContent = totalPages;

  const grid = document.getElementById('grid'); grid.innerHTML = '';
  pageItems.forEach(c => {
    const card = document.createElement('div'); card.className='card'; card.tabIndex=0;
    card.dataset.id = c.id;

    const avatarWrap = document.createElement('div'); avatarWrap.className='avatar-wrap';
    avatarWrap.style.minHeight = '180px';
    avatarWrap.style.height = '240px';
    avatarWrap.style.display='block';
    avatarWrap.style.position='relative';

    const img = document.createElement('img'); img.className='avatar'; img.src=c.headerImg; img.alt=c.name_ar;
    avatarWrap.appendChild(img);

    card.appendChild(avatarWrap);

    const footer = document.createElement('div'); footer.className='card-footer';
    const name = document.createElement('div'); name.className='name'; name.textContent = (currentLang==='ar' ? c.name_ar : (c.name_en||c.name_ar));
    footer.appendChild(name);

    const stars = document.createElement('div');
    stars.className = 'stars';
    stars.style.marginLeft = '8px';
    for(let i=0;i<c.rarity;i++){
      const s = document.createElement('svg');
      s.className='star';
      s.setAttribute('viewBox','0 0 24 24');
      s.innerHTML = '<path fill="#ffd700" d="M12 .587l3.668 7.431L24 9.748l-6 5.837L19.335 24 12 20.019 4.665 24 6 15.585 0 9.748l8.332-1.73z"/>';
      stars.appendChild(s);
    }
    const nameStarsWrap = document.createElement('div');
    nameStarsWrap.style.display = 'flex';
    nameStarsWrap.style.alignItems = 'center';
    nameStarsWrap.appendChild(name);
    nameStarsWrap.appendChild(stars);
    footer.appendChild(nameStarsWrap);

    card.appendChild(footer);

    card.addEventListener('click', ()=>openDetail(c.id));
    card.addEventListener('keydown', (ev)=>{ if(ev.key==='Enter'){ openDetail(c.id); }});

    grid.appendChild(card);
  });

  const pg = document.getElementById('pagination'); pg.innerHTML = '';
  for(let p=1;p<=totalPages;p++){
    const b = document.createElement('button'); b.className='pageBtn' + (p===currentPage? ' active':''); b.textContent = p;
    b.addEventListener('click', ()=>{ currentPage = p; render(); window.scrollTo({top:0,behavior:'smooth'}); });
    pg.appendChild(b);
  }
}

const overlay = document.getElementById('overlay');
const imgFullscreen = document.getElementById('imgFullscreen');
const fullImg = document.getElementById('fullImg');

function renderStarsHtml(count){
  let html = '';
  for(let i=0;i<count;i++){
    html += '<svg viewBox="0 0 24 24'+'" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill="#FFD700" d="M12 .587l3.668 7.431L24 9.748l-6 5.837L19.335 24 12 20.019 4.665 24 6 15.585 0 9.748l8.332-1.73z"/></svg>';
  }
  return html;
}

function openDetail(id){
  const c = characters.find(x=>x.id===id); if(!c) return;
  const imgWrap = document.getElementById('detailImage'); imgWrap.innerHTML = `<img src="${c.detailImg}" alt="${c.name_ar}">`;
  document.getElementById('detailName').textContent = (currentLang==='ar'? c.name_ar : (c.name_en||c.name_ar));
  document.getElementById('detailStars').innerHTML = renderStarsHtml(c.rarity);
  document.getElementById('detailMeta').textContent = `${c.element_ar} • ${c.weapon_ar} • ${c.rarity} ★`;
  document.getElementById('detailDesc').textContent = c.description_ar || '';
  document.getElementById('detailInfo').innerHTML = `<b>العنصر:</b> ${c.element_ar}  |  <b>السلاح:</b> ${c.weapon_ar}  |  <b>النوع:</b> ${c.type_ar || '-'}  |  <b>المدينة:</b> ${c.city || '-'}`;

  // set current image for fullscreen
  fullImg.src = c.detailImg;

  overlay.classList.add('open');
  history.pushState({character:id}, '', `#character-${id}`);
}

document.getElementById('closeDetail').addEventListener('click', closeDetail);
overlay.addEventListener('click', (e)=>{ if(e.target === overlay) closeDetail(); });

function closeDetail(){
  overlay.classList.remove('open');
  history.pushState({}, '', window.location.pathname + window.location.search);
}

// open fullscreen when clicking the image inside modal
document.getElementById('detailImage').addEventListener('click', (e)=>{
  // prevent if clicked on overlay container outside image (safety)
  const img = e.target.closest('img');
  if(!img) return;
  imgFullscreen.classList.add('open');
});

// close fullscreen by button or clicking outside image
document.getElementById('closeFull').addEventListener('click', ()=> imgFullscreen.classList.remove('open'));
imgFullscreen.addEventListener('click', (e)=>{
  if(e.target === imgFullscreen) imgFullscreen.classList.remove('open');
});

// load handlers
window.addEventListener('load', ()=>{
  applyLang();
  createFilterChips();
  render();
  if(location.hash && location.hash.startsWith("#character-")){
    const id = location.hash.replace('#character-','');
    setTimeout(()=> openDetail(id), 300);
  }
});

window.addEventListener('popstate', (ev)=>{
  if(location.hash && location.hash.startsWith("#character-")){ /* stay open */ }
  else{ overlay.classList.remove('open'); imgFullscreen.classList.remove('open'); }
});

/* countdown */
const eventDate = new Date("2025-08-15T18:00:00").getTime();
function updateCountdown(){
  const now = Date.now();
  let diff = eventDate - now;
  if(diff <= 0){
    document.getElementById('cd-days').textContent = '0';
    document.getElementById('cd-hms').textContent = (currentLang==='ar' ? 'انتهى التحديث' : 'Event passed');
    return;
  }
  const days = Math.floor(diff / (1000*60*60*24));
  diff -= days * (1000*60*60*24);
  const hours = Math.floor(diff / (1000*60*60));
  diff -= hours * (1000*60*60);
  const minutes = Math.floor(diff / (1000*60));
  diff -= minutes * (1000*60);
  const seconds = Math.floor(diff/1000);

  document.getElementById('cd-days').textContent = days;
  document.getElementById('cd-hms').textContent = `${String(hours).padStart(2,'0')}:${String(minutes).padStart(2,'0')}:${String(seconds).padStart(2,'0')}`;
}
setInterval(updateCountdown, 1000);
updateCountdown();
</script>
</body>
</html>
