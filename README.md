<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>VLXD Gia Khánh - Tổng Kho Vật Liệu Xây Dựng & Trang Trí Nội Thất Đà Nẵng | giakhanh.com</title>
  <meta name="description" content="Cửa hàng VLXD Gia Khánh (giakhanh.com) - 32 Nguyễn Trung Ngạn, Cẩm Lệ, Đà Nẵng. Chuyên cung cấp Sơn, Thiết bị vệ sinh, Gạch men, Ngói lợp, Bồn nước, Bình nóng lạnh, Keo dán gạch và VLXD thô chính hãng giá sỉ. Hotline: 0766 663 294.">
  
  <!-- Open Graph / Thumbnail Logo khi gửi link trang web giakhanh.com -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://giakhanh.com/">
  <meta property="og:title" content="Cửa Hàng VLXD Gia Khánh - Vật Liệu Xây Dựng & Nội Thất Uy Tín Đà Nẵng">
  <meta property="og:description" content="Địa chỉ: 32 Nguyễn Trung Ngạn, Cẩm Lệ, Đà Nẵng - Hotline/Zalo: 0766 663 294. Phân phối Sơn, Thiết bị vệ sinh, Gạch men, Bồn nước, Keo dán gạch & VLXD tổng hợp.">
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=1SlkIo25aXVZlRNVPXhzM_qJiCtPM1jBv&sz=w1200">
  <meta property="og:image:alt" content="Logo Cửa Hàng VLXD Gia Khánh - giakhanh.com">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="Cửa Hàng VLXD Gia Khánh - giakhanh.com">
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1SlkIo25aXVZlRNVPXhzM_qJiCtPM1jBv&sz=w1200">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <!-- Google Fonts: Roboto & Montserrat chuẩn Flatsome Việt Nam -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@600;700;800&family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              navy: '#0c3559',      /* Màu Xanh Navy đậm theo tông Logo Gia Khánh */
              blue: '#134e82',      /* Màu Xanh dương chủ đạo Flatsome */
              orange: '#e65100',    /* Màu Cam Đỏ Gạch điểm nhấn theo Logo */
              amber: '#f59e0b',     /* Màu Vàng Cam kim loại */
              light: '#f4f7fa'
            }
          },
          fontFamily: {
            sans: ['Roboto', 'sans-serif'],
            heading: ['Montserrat', 'sans-serif']
          }
        }
      }
    }
  </script>

  <style>
    /* Chống tràn viền và lệch phải tuyệt đối trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      width: 100%;
      max-width: 100vw;
      overflow-x: hidden;
      margin: 0;
      padding: 0;
      font-family: 'Roboto', sans-serif;
      background-color: #f5f7fa;
      color: #222;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .flatsome-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 10px;
      padding-right: 10px;
    }
    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Menu danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không gãy dòng trong tên danh mục */
    .desktop-nav-list {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: flex-start;
      gap: 2px;
    }
    .desktop-nav-item {
      white-space: nowrap;
      font-size: 12px;
      font-weight: 700;
      letter-spacing: 0.01em;
      padding: 9px 9px;
      line-height: 1.2;
      transition: all 0.2s ease;
    }
    @media (min-width: 1280px) {
      .desktop-nav-item {
        font-size: 12.5px;
        padding: 10px 12px;
      }
    }

    /* Dropdown Submenu kiểu Flatsome */
    .has-dropdown {
      position: relative;
    }
    .dropdown-menu {
      display: none;
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 220px;
      background: #ffffff;
      box-shadow: 0 10px 25px rgba(0,0,0,0.14);
      border-top: 3px solid #e65100;
      z-index: 100;
      border-radius: 0 0 6px 6px;
      padding: 6px 0;
    }
    .has-dropdown:hover .dropdown-menu {
      display: block;
    }

    /* Banner Slider 2 ảnh kích thước bằng nhau tuyệt đối, chữ cách xa viền, không mất chữ */
    .hero-slider-wrapper {
      position: relative;
      width: 100%;
      overflow: hidden;
      border-radius: 8px;
    }
    .hero-slide {
      width: 100%;
      min-height: 250px;
      height: 250px;
      display: none;
      position: relative;
    }
    .hero-slide.active {
      display: flex;
    }
    @media (min-width: 640px) {
      .hero-slide {
        min-height: 310px;
        height: 310px;
      }
    }
    @media (min-width: 1024px) {
      .hero-slide {
        min-height: 380px;
        height: 380px;
      }
    }

    /* Badge giảm giá góc trên bên trái chuẩn Flatsome */
    .flatsome-sale-badge {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background: linear-gradient(135deg, #e65100, #d32f2f);
      color: #ffffff;
      font-weight: 700;
      font-size: 11px;
      line-height: 1;
      padding: 5px 7px;
      border-radius: 4px;
      box-shadow: 0 2px 6px rgba(211, 47, 47, 0.35);
    }

    /* Tên sản phẩm không bị tràn hoặc thiếu chữ */
    .product-title-full {
      white-space: normal;
      word-wrap: break-word;
      overflow-wrap: break-word;
      line-height: 1.38;
      display: block;
    }

    /* Tiêu đề Section chuẩn Flatsome (noithatngonguyen.com) */
    .flatsome-section-header {
      border-bottom: 2px solid #0c3559;
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      gap: 8px;
      margin-bottom: 14px;
      background: #ffffff;
      border-radius: 6px 6px 0 0;
    }
    .flatsome-section-title {
      background: #0c3559;
      color: #ffffff;
      font-family: 'Montserrat', sans-serif;
      font-weight: 700;
      font-size: 13px;
      padding: 9px 16px;
      text-transform: uppercase;
      letter-spacing: 0.03em;
      border-radius: 6px 0 0 0;
      position: relative;
      display: inline-flex;
      align-items: center;
      gap: 8px;
    }
    .flatsome-section-title::after {
      content: "";
      position: absolute;
      right: -12px;
      top: 0;
      width: 0;
      height: 0;
      border-top: 37px solid #0c3559;
      border-right: 12px solid transparent;
    }

    /* Hiệu ứng sóng cho nút liên hệ nổi */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(230, 81, 0, 0.7); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(230, 81, 0, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(230, 81, 0, 0); }
    }
    .pulse-btn {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body class="pb-14 md:pb-0">

  <!-- TOP BAR CHUẨN FLATSOME -->
  <div class="bg-brand-navy text-white text-xs py-1.5 border-b border-white/10">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3 overflow-hidden">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-brand-amber"></i>
          <span>32 Nguyễn Trung Ngạn, Cẩm Lệ, TP. Đà Nẵng</span>
        </span>
        <span class="hidden md:inline-block text-white/30">|</span>
        <span class="hidden md:inline-flex items-center gap-1.5">
          <i class="fa-solid fa-globe text-brand-amber"></i>
          <span>Website: <strong>giakhanh.com</strong></span>
        </span>
      </div>
      <div class="flex items-center gap-4 ml-auto">
        <a href="#hinh-anh-cua-hang" class="hover:text-brand-amber transition">Hình ảnh kho</a>
        <a href="#tin-tuc" class="hover:text-brand-amber transition">Tin tức</a>
        <a href="#bao-gia" class="hover:text-brand-amber transition">Báo giá sỉ</a>
        <a href="https://www.facebook.com/vo.thi.len.740204/" target="_blank" rel="noopener noreferrer" class="hover:text-brand-amber transition inline-flex items-center gap-1">
          <i class="fa-brands fa-facebook"></i> <span>Facebook</span>
        </a>
      </div>
    </div>
  </div>

  <!-- HEADER CHÍNH (Logo chỉnh gọn nhỏ lại, KHÔNG để nút gọi ngay trên header tránh tràn viền) -->
  <header class="bg-white shadow-sm sticky top-0 z-50">
    <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">
      
      <!-- Nút mở Menu Mobile -->
      <button id="mobileMenuBtn" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-md border border-slate-200 text-brand-navy hover:bg-slate-100">
        <i class="fa-solid fa-bars text-lg"></i>
      </button>

      <!-- LOGO MỚI CHUYÊN NGHIỆP - ĐÃ CHỈNH GỌN NHỎ LẠI -->
      <a href="#" class="flex items-center gap-2.5 shrink-0 group">
        <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect width="100" height="100" rx="18" fill="#0c3559"/>
          <path d="M18 66L50 34L82 66" stroke="#f59e0b" stroke-width="8" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M30 66V80H70V66" stroke="#ffffff" stroke-width="6" stroke-linecap="round" stroke-linejoin="round"/>
          <rect x="42" y="54" width="16" height="16" rx="2" fill="#e65100"/>
          <path d="M34 32L50 18L66 32" stroke="#e65100" stroke-width="6" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
        <div class="leading-tight">
          <div class="font-heading font-extrabold text-sm sm:text-base text-brand-navy tracking-tight flex items-center gap-1">
            <span>VLXD GIA KHÁNH</span>
          </div>
          <div class="text-[10px] sm:text-[11px] font-medium text-brand-orange uppercase tracking-wider">
            giakhanh.com • Đà Nẵng
          </div>
        </div>
      </a>

      <!-- Ô TÌM KIẾM SẢN PHẨM TRÊN HEADER CHUẨN FLATSOME -->
      <div class="hidden md:flex flex-1 max-w-xl mx-4">
        <div class="relative w-full flex">
          <input id="searchInputDesktop" oninput="filterProductsBySearch(this.value)" type="text" placeholder="Tìm kiếm sơn, gạch men, thiết bị vệ sinh, cát đá, xi măng..." class="w-full pl-3.5 pr-10 py-2 text-xs sm:text-sm border border-slate-300 rounded-l-md focus:outline-none focus:border-brand-navy">
          <button onclick="filterProductsBySearch(document.getElementById('searchInputDesktop').value)" class="bg-brand-orange hover:bg-orange-700 text-white px-4 rounded-r-md text-sm font-medium transition">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </div>
      </div>

      <!-- Thông tin địa chỉ & SĐT dạng chữ gọn (KHÔNG để nút gọi ngay tránh tràn viền) -->
      <div class="hidden xl:flex items-center gap-4 text-right shrink-0">
        <div class="text-xs text-slate-600 leading-snug">
          <div class="font-bold text-brand-navy">TỔNG KHO VLXD CẨM LỆ</div>
          <div>32 Nguyễn Trung Ngạn - 0766 663 294</div>
        </div>
      </div>

      <!-- Nút tìm kiếm nhanh trên điện thoại -->
      <button onclick="toggleMobileSearch()" aria-label="Tìm kiếm" class="md:hidden p-2 rounded-md border border-slate-200 text-brand-navy">
        <i class="fa-solid fa-magnifying-glass text-base"></i>
      </button>
    </div>

    <!-- Thanh tìm kiếm trên điện thoại -->
    <div id="mobileSearchBar" class="hidden md:hidden px-3 pb-2.5 bg-white border-t border-slate-100">
      <div class="flex mt-2">
        <input id="searchInputMobile" oninput="filterProductsBySearch(this.value)" type="text" placeholder="Nhập tên vật liệu xây dựng cần tìm..." class="w-full px-3 py-1.5 text-xs border border-slate-300 rounded-l-md focus:outline-none focus:border-brand-navy">
        <button onclick="filterProductsBySearch(document.getElementById('searchInputMobile').value)" class="bg-brand-orange text-white px-3 rounded-r-md text-xs">
          <i class="fa-solid fa-magnifying-glass"></i>
        </button>
      </div>
    </div>

    <!-- MENU DANH MỤC TRÊN MÁY TÍNH (Viết liền trên 1 hàng chữ nhỏ gọn, không gãy dòng tên danh mục) -->
    <nav class="hidden lg:block bg-brand-navy text-white border-t border-brand-blue">
      <div class="flatsome-container">
        <ul class="desktop-nav-list">
          <li>
            <a href="#" onclick="filterCategory('ALL'); return false;" class="desktop-nav-item inline-block bg-brand-orange text-white">
              <i class="fa-solid fa-house mr-1"></i>TRANG CHỦ
            </a>
          </li>
          <li class="has-dropdown">
            <a href="#sec-son" class="desktop-nav-item inline-block hover:bg-brand-orange text-white">
              SƠN <i class="fa-solid fa-angle-down text-[10px] ml-0.5 opacity-80"></i>
            </a>
            <div class="dropdown-menu text-slate-800 text-xs">
              <a href="#sec-son" class="block px-4 py-2 hover:bg-slate-100 font-semibold text-brand-navy">Sơn Jotun (Nội & Ngoại thất)</a>
              <a href="#sec-son" class="block px-4 py-2 hover:bg-slate-100 font-semibold text-brand-navy">Sơn Dulux - Maxilite</a>
              <a href="#sec-son" class="block px-4 py-2 hover:bg-slate-100 font-semibold text-brand-navy">Sơn Tito & Bột Trét</a>
              <a href="#sec-son" class="block px-4 py-2 hover:bg-slate-100 font-semibold text-brand-navy">Chống thấm Sika / Bestmix / Mapei</a>
            </div>
          </li>
          <li class="has-dropdown">
            <a href="#sec-tbvs" class="desktop-nav-item inline-block hover:bg-brand-orange text-white">
              THIẾT BỊ VỆ SINH <i class="fa-solid fa-angle-down text-[10px] ml-0.5 opacity-80"></i>
            </a>
            <div class="dropdown-menu text-slate-800 text-xs">
              <a href="#sec-tbvs" class="block px-4 py-2 hover:bg-slate-100">Bồn cầu Inax / Viglacera / Caesar</a>
              <a href="#sec-tbvs" class="block px-4 py-2 hover:bg-slate-100">Sen vòi & Sen cây nóng lạnh</a>
              <a href="#sec-tbvs" class="block px-4 py-2 hover:bg-slate-100">Chậu rửa Lavabo & Bàn đá</a>
              <a href="#sec-tbvs" class="block px-4 py-2 hover:bg-slate-100">Gương & Phụ kiện nhà tắm</a>
            </div>
          </li>
          <li class="has-dropdown">
            <a href="#sec-gach" class="desktop-nav-item inline-block hover:bg-brand-orange text-white">
              GẠCH MEN <i class="fa-solid fa-angle-down text-[10px] ml-0.5 opacity-80"></i>
            </a>
            <div class="dropdown-menu text-slate-800 text-xs">
              <a href="#sec-gach" class="block px-4 py-2 hover:bg-slate-100">Gạch Đồng Tâm (80x80, 60x60, 30x60)</a>
              <a href="#sec-gach" class="block px-4 py-2 hover:bg-slate-100">Gạch Kimgres & Porcelain kháng khuẩn</a>
              <a href="#sec-gach" class="block px-4 py-2 hover:bg-slate-100">Gạch lát sân vườn & Gạch ốp tường</a>
            </div>
          </li>
          <li class="has-dropdown">
            <a href="#sec-ngoi" class="desktop-nav-item inline-block hover:bg-brand-orange text-white">
              NGÓI LỢP <i class="fa-solid fa-angle-down text-[10px] ml-0.5 opacity-80"></i>
            </a>
            <div class="dropdown-menu text-slate-800 text-xs">
              <a href="#sec-ngoi" class="block px-4 py-2 hover:bg-slate-100">Ngói màu DIC</a>
              <a href="#sec-ngoi" class="block px-4 py-2 hover:bg-slate-100">Ngói Đất Việt</a>
            </div>
          </li>
          <li class="has-dropdown">
            <a href="#sec-bonnuoc" class="desktop-nav-item inline-block hover:bg-brand-orange text-white">
              BỒN NƯỚC <i class="fa-solid fa-angle-down text-[10px] ml-0.5 opacity-80"></i>
            </a>
            <div class="dropdown-menu text-slate-800 text-xs">
              <a href="#sec-bonnuoc" class="block px-4 py-2 hover:bg-slate-100">Bồn nước Sơn Hà</a>
              <a href="#sec-bonnuoc" class="block px-4 py-2 hover:bg-slate-100">Bồn nước Tân Á Đại Thành</a>
              <a href="#sec-bonnuoc" class="block px-4 py-2 hover:bg-slate-100">Bồn nước Letton</a>
            </div>
          </li>
          <li class="has-dropdown">
            <a href="#sec-binhnonglanh" class="desktop-nav-item inline-block hover:bg-brand-orange text-white">
              BÌNH NÓNG LẠNH <i class="fa-solid fa-angle-down text-[10px] ml-0.5 opacity-80"></i>
            </a>
            <div class="dropdown-menu text-slate-800 text-xs">
              <a href="#sec-binhnonglanh" class="block px-4 py-2 hover:bg-slate-100">Bình nóng lạnh Ariston</a>
              <a href="#sec-binhnonglanh" class="block px-4 py-2 hover:bg-slate-100">Bình nóng lạnh Ferroli</a>
            </div>
          </li>
          <li class="has-dropdown">
            <a href="#sec-keo" class="desktop-nav-item inline-block hover:bg-brand-orange text-white">
              DÁN GẠCH, CHÀ RON <i class="fa-solid fa-angle-down text-[10px] ml-0.5 opacity-80"></i>
            </a>
            <div class="dropdown-menu text-slate-800 text-xs">
              <a href="#sec-keo" class="block px-4 py-2 hover:bg-slate-100">Keo dán gạch Bestmix & Đồng Tâm</a>
              <a href="#sec-keo" class="block px-4 py-2 hover:bg-slate-100">Keo chà ron Cá Sấu (Crocodile)</a>
              <a href="#sec-keo" class="block px-4 py-2 hover:bg-slate-100">Phụ gia & Vữa Sika</a>
            </div>
          </li>
          <li class="has-dropdown">
            <a href="#sec-vlxd-tho" class="desktop-nav-item inline-block hover:bg-brand-orange text-white">
              VLXD & PHỤ KIỆN <i class="fa-solid fa-angle-down text-[10px] ml-0.5 opacity-80"></i>
            </a>
            <div class="dropdown-menu text-slate-800 text-xs">
              <a href="#sec-vlxd-tho" class="block px-4 py-2 hover:bg-slate-100">Cát xây tô, Đá 1x2, Đá 4x6, Xi măng</a>
              <a href="#sec-vlxd-tho" class="block px-4 py-2 hover:bg-slate-100">Phụ kiện cấp thoát nước & Điện nước</a>
            </div>
          </li>
          <li>
            <a href="#lien-he-map" class="desktop-nav-item inline-block hover:bg-brand-orange text-white">
              LIÊN HỆ
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- DRAWER MENU DANH MỤC TRÊN ĐIỆN THOẠI -->
  <div id="mobileMenuOverlay" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/50 z-50 hidden"></div>
  <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-72 max-w-[82vw] bg-white z-50 transform -translate-x-full transition-transform duration-300 overflow-y-auto shadow-2xl">
    <div class="p-3.5 bg-brand-navy text-white flex items-center justify-between">
      <span class="font-heading font-bold text-sm uppercase tracking-wider">DANH MỤC SẢN PHẨM</span>
      <button onclick="toggleMobileMenu()" class="w-7 h-7 rounded bg-white/10 flex items-center justify-center">
        <i class="fa-solid fa-xmark"></i>
      </button>
    </div>
    <ul class="divide-y divide-slate-100 text-xs font-semibold text-slate-800">
      <li><a href="#" onclick="toggleMobileMenu(); filterCategory('ALL');" class="block px-4 py-3 text-brand-orange"><i class="fa-solid fa-house mr-2"></i>TRANG CHỦ</a></li>
      <li><a href="#sec-son" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-fill-drip mr-2 text-brand-navy"></i>SƠN (Jotun, Dulux, Tito, Sika)</a></li>
      <li><a href="#sec-tbvs" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-shower mr-2 text-brand-navy"></i>THIẾT BỊ VỆ SINH</a></li>
      <li><a href="#sec-gach" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-border-all mr-2 text-brand-navy"></i>GẠCH MEN (Đồng Tâm, Kimgres)</a></li>
      <li><a href="#sec-ngoi" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-tents mr-2 text-brand-navy"></i>NGÓI LỢP (DIC, Đất Việt)</a></li>
      <li><a href="#sec-bonnuoc" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-database mr-2 text-brand-navy"></i>BỒN NƯỚC (Sơn Hà, Tân Á, Letton)</a></li>
      <li><a href="#sec-binhnonglanh" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-temperature-three-quarters mr-2 text-brand-navy"></i>BÌNH NÓNG LẠNH (Ariston, Ferroli)</a></li>
      <li><a href="#sec-keo" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-trowel-bricks mr-2 text-brand-navy"></i>DÁN GẠCH, CHÀ RON</a></li>
      <li><a href="#sec-vlxd-tho" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-truck-ramp-box mr-2 text-brand-navy"></i>VLXD THÔ & PHỤ KIỆN CÔNG TRÌNH</a></li>
      <li><a href="#hinh-anh-cua-hang" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-store mr-2 text-brand-navy"></i>HÌNH ẢNH CỬA HÀNG THỰC TẾ</a></li>
      <li><a href="#bao-gia" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-file-invoice-dollar mr-2 text-brand-navy"></i>YÊU CẦU BÁO GIÁ</a></li>
      <li><a href="#lien-he-map" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-map-location-dot mr-2 text-brand-navy"></i>BẢN ĐỒ & LIÊN HỆ</a></li>
    </ul>
  </aside>

  <!-- MAIN CONTENT CONTAINER (95% MÀN HÌNH MÁY TÍNH) -->
  <main class="flatsome-container py-3 sm:py-5 space-y-6">

    <!-- 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU -->
    <!-- Thiết kế hình ảnh và chữ nằm gọn trong lòng banner, cách xa viền, không bao giờ bị thiếu chữ trên điện thoại & máy tính -->
    <section aria-label="Banner chính">
      <div class="hero-slider-wrapper shadow-md bg-brand-navy">
        
        <!-- SLIDE 1 -->
        <div class="hero-slide active bg-gradient-to-r from-[#08243e] via-[#0c3559] to-[#164e7f] items-center justify-between px-7 sm:px-14 lg:px-20 py-6">
          <div class="w-full md:w-3/5 text-white z-10 pr-2 sm:pr-6">
            <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-brand-amber mb-1.5">
              TỔNG KHO VẬT LIỆU XÂY DỰNG & NỘI THẤT ĐÀ NẴNG
            </p>
            <h1 class="font-heading font-extrabold text-base sm:text-2xl lg:text-3xl leading-snug mb-2 text-white">
              CỬA HÀNG VLXD GIA KHÁNH <br class="hidden sm:inline">CHÍNH HÃNG - GIÁ SỈ TẬN KHO
            </h1>
            <p class="text-xs sm:text-sm text-slate-200 mb-3.5 leading-relaxed">
              Chuyên Sơn Nước, Thiết Bị Vệ Sinh, Gạch Men, Ngói Lợp, Bồn Nước, Keo Chà Ron & Cát Đá Xi Măng. Giao tận chân công trình tại Cẩm Lệ & Đà Nẵng.
            </p>
            <div class="flex flex-wrap items-center gap-2 sm:gap-3 text-[11px] sm:text-xs">
              <a href="#bao-gia" class="bg-brand-orange hover:bg-orange-600 text-white font-bold px-3.5 py-2 rounded transition">
                NHẬN BÁO GIÁ NGAY
              </a>
              <span class="bg-white/10 border border-white/20 text-white px-3 py-2 rounded font-medium">
                Đ/C: 32 Nguyễn Trung Ngạn, Cẩm Lệ
              </span>
            </div>
          </div>
          <!-- Cụm ảnh thực tế nằm gọn trong lòng banner bên phải -->
          <div class="hidden md:flex md:w-2/5 items-center justify-center pl-4">
            <div class="grid grid-cols-2 gap-2.5 max-w-[320px] w-full bg-white/10 p-2.5 rounded-lg border border-white/20">
              <img data-drive-id="1SlkIo25aXVZlRNVPXhzM_qJiCtPM1jBv" src="https://drive.google.com/thumbnail?id=1SlkIo25aXVZlRNVPXhzM_qJiCtPM1jBv&sz=w600" alt="Cửa hàng VLXD Gia Khánh" class="w-full h-28 object-cover rounded">
              <img data-drive-id="1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY" src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w600" alt="Sản phẩm VLXD Gia Khánh" class="w-full h-28 object-cover rounded">
              <img data-drive-id="1TLOVdGeawzpiP65IiVy1r0P30MXhKhL7" src="https://drive.google.com/thumbnail?id=1TLOVdGeawzpiP65IiVy1r0P30MXhKhL7&sz=w600" alt="Kho VLXD Gia Khánh" class="w-full h-28 object-cover rounded col-span-2">
            </div>
          </div>
        </div>

        <!-- SLIDE 2 (Kích thước bằng nhau 100% với Slide 1) -->
        <div class="hero-slide bg-gradient-to-r from-[#102a45] via-[#154360] to-[#0c3559] items-center justify-between px-7 sm:px-14 lg:px-20 py-6">
          <div class="w-full md:w-3/5 text-white z-10 pr-2 sm:pr-6">
            <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-brand-amber mb-1.5">
              ĐẦY ĐỦ VẬT TƯ XÂY THÔ & HOÀN THIỆN NỘI THẤT
            </p>
            <h2 class="font-heading font-extrabold text-base sm:text-2xl lg:text-3xl leading-snug mb-2 text-white">
              CHIẾT KHẤU CAO CHO THỢ THẦU <br class="hidden sm:inline">& GIA CHỦ XÂY NHÀ TRỌN GÓI
            </h2>
            <p class="text-xs sm:text-sm text-slate-200 mb-3.5 leading-relaxed">
              Đội xe ben vận chuyển linh hoạt vào mọi kiệt hẻm Đà Nẵng. Cam kết đúng khối lượng, vật tư chính hãng 100% từ Jotun, Dulux, Inax, Đồng Tâm, Sika.
            </p>
            <div class="flex flex-wrap items-center gap-2 sm:gap-3 text-[11px] sm:text-xs">
              <a href="#sec-vlxd-tho" class="bg-brand-amber hover:bg-amber-500 text-slate-900 font-bold px-3.5 py-2 rounded transition">
                XEM SẢN PHẨM THỰC TẾ
              </a>
              <span class="bg-white/10 border border-white/20 text-white px-3 py-2 rounded font-medium">
                Hotline/Zalo: 0766 663 294
              </span>
            </div>
          </div>
          <!-- Cụm ảnh thực tế nằm gọn trong lòng banner bên phải -->
          <div class="hidden md:flex md:w-2/5 items-center justify-center pl-4">
            <div class="grid grid-cols-2 gap-2.5 max-w-[320px] w-full bg-white/10 p-2.5 rounded-lg border border-white/20">
              <img data-drive-id="1ocI6IdQfhaAEyAxMfBJT-CQ_p9tQR2-C" src="https://drive.google.com/thumbnail?id=1ocI6IdQfhaAEyAxMfBJT-CQ_p9tQR2-C&sz=w600" alt="Kho hàng VLXD Gia Khánh" class="w-full h-28 object-cover rounded">
              <img data-drive-id="11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP" src="https://drive.google.com/thumbnail?id=11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP&sz=w600" alt="Vật tư thực tế Gia Khánh" class="w-full h-28 object-cover rounded">
              <img data-drive-id="1RSgwCB3Is2l_tFR-vJDANLL8fjB7kP1-" src="https://drive.google.com/thumbnail?id=1RSgwCB3Is2l_tFR-vJDANLL8fjB7kP1-&sz=w600" alt="Bãi vật liệu Gia Khánh" class="w-full h-28 object-cover rounded col-span-2">
            </div>
          </div>
        </div>

        <!-- Nút điều hướng Trái/Phải Banner (Đặt sát mép ngoài cùng, không đè lên chữ) -->
        <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-1.5 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-brand-orange text-white flex items-center justify-center z-20 transition">
          <i class="fa-solid fa-chevron-left text-xs"></i>
        </button>
        <button onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-1.5 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-brand-orange text-white flex items-center justify-center z-20 transition">
          <i class="fa-solid fa-chevron-right text-xs"></i>
        </button>

        <!-- Dots chỉ mục Slide -->
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
          <button onclick="goToSlide(0)" class="slide-dot w-2.5 h-2.5 rounded-full bg-brand-amber transition"></button>
          <button onclick="goToSlide(1)" class="slide-dot w-2.5 h-2.5 rounded-full bg-white/40 transition"></button>
        </div>
      </div>
    </section>

    <!-- DANH MỤC SẢN PHẨM TRANG CHỦ (Chữ nhỏ gọn, thiết kế đẹp trên máy tính & điện thoại) -->
    <section class="bg-white p-3.5 sm:p-4 rounded-lg shadow-sm border border-slate-200/80">
      <div class="flex items-center justify-between mb-3 pb-2 border-b border-slate-100">
        <h2 class="font-heading font-bold text-xs sm:text-sm text-brand-navy uppercase flex items-center gap-2">
          <i class="fa-solid fa-layer-group text-brand-orange"></i>
          <span>DANH MỤC SẢN PHẨM CHÍNH</span>
        </h2>
        <span class="text-[11px] text-slate-500">Chọn nhanh danh mục vật tư</span>
      </div>
      <div class="grid grid-cols-4 sm:grid-cols-4 md:grid-cols-8 gap-2 sm:gap-2.5">
        <a href="#sec-son" class="group flex flex-col items-center justify-center p-2 rounded-md bg-slate-50 hover:bg-brand-navy hover:text-white border border-slate-200/70 transition text-center">
          <i class="fa-solid fa-fill-drip text-base sm:text-lg text-brand-orange group-hover:text-brand-amber mb-1.5"></i>
          <span class="text-[11px] font-semibold leading-tight">SƠN NƯỚC</span>
        </a>
        <a href="#sec-tbvs" class="group flex flex-col items-center justify-center p-2 rounded-md bg-slate-50 hover:bg-brand-navy hover:text-white border border-slate-200/70 transition text-center">
          <i class="fa-solid fa-shower text-base sm:text-lg text-brand-orange group-hover:text-brand-amber mb-1.5"></i>
          <span class="text-[11px] font-semibold leading-tight">TB VỆ SINH</span>
        </a>
        <a href="#sec-gach" class="group flex flex-col items-center justify-center p-2 rounded-md bg-slate-50 hover:bg-brand-navy hover:text-white border border-slate-200/70 transition text-center">
          <i class="fa-solid fa-border-all text-base sm:text-lg text-brand-orange group-hover:text-brand-amber mb-1.5"></i>
          <span class="text-[11px] font-semibold leading-tight">GẠCH MEN</span>
        </a>
        <a href="#sec-ngoi" class="group flex flex-col items-center justify-center p-2 rounded-md bg-slate-50 hover:bg-brand-navy hover:text-white border border-slate-200/70 transition text-center">
          <i class="fa-solid fa-tents text-base sm:text-lg text-brand-orange group-hover:text-brand-amber mb-1.5"></i>
          <span class="text-[11px] font-semibold leading-tight">NGÓI LỢP</span>
        </a>
        <a href="#sec-bonnuoc" class="group flex flex-col items-center justify-center p-2 rounded-md bg-slate-50 hover:bg-brand-navy hover:text-white border border-slate-200/70 transition text-center">
          <i class="fa-solid fa-database text-base sm:text-lg text-brand-orange group-hover:text-brand-amber mb-1.5"></i>
          <span class="text-[11px] font-semibold leading-tight">BỒN NƯỚC</span>
        </a>
        <a href="#sec-binhnonglanh" class="group flex flex-col items-center justify-center p-2 rounded-md bg-slate-50 hover:bg-brand-navy hover:text-white border border-slate-200/70 transition text-center">
          <i class="fa-solid fa-temperature-three-quarters text-base sm:text-lg text-brand-orange group-hover:text-brand-amber mb-1.5"></i>
          <span class="text-[11px] font-semibold leading-tight">NÓNG LẠNH</span>
        </a>
        <a href="#sec-keo" class="group flex flex-col items-center justify-center p-2 rounded-md bg-slate-50 hover:bg-brand-navy hover:text-white border border-slate-200/70 transition text-center">
          <i class="fa-solid fa-trowel-bricks text-base sm:text-lg text-brand-orange group-hover:text-brand-amber mb-1.5"></i>
          <span class="text-[11px] font-semibold leading-tight">KEO & RON</span>
        </a>
        <a href="#sec-vlxd-tho" class="group flex flex-col items-center justify-center p-2 rounded-md bg-slate-50 hover:bg-brand-navy hover:text-white border border-slate-200/70 transition text-center">
          <i class="fa-solid fa-truck-ramp-box text-base sm:text-lg text-brand-orange group-hover:text-brand-amber mb-1.5"></i>
          <span class="text-[11px] font-semibold leading-tight">VLXD THÔ</span>
        </a>
      </div>
    </section>

    <!-- KHU VỰC HIỂN THỊ CÁC DANH MỤC SẢN PHẨM CHUẨN FLATSOME (GIỐNG WEB MẪU NOITHATNGONGUYEN.COM) -->
    <!-- Điện thoại chia 2 cột (grid-cols-2), Máy tính chia 4-5 cột, có % giảm giá góc trên bên trái, tên sản phẩm đầy đủ không mất chữ -->
    <div id="catalogContainer" class="space-y-7"></div>

    <!-- HÌNH ẢNH THỰC TẾ CỬA HÀNG & KHO BÃI VLXD GIA KHÁNH (5 ẢNH CỬA HÀNG TỪ GOOGLE DRIVE) -->
    <section id="hinh-anh-cua-hang" class="bg-white p-4 sm:p-5 rounded-lg shadow-sm border border-slate-200">
      <div class="flatsome-section-header">
        <h2 class="flatsome-section-title">
          <i class="fa-solid fa-store"></i> HÌNH ẢNH THỰC TẾ CỬA HÀNG VLXD GIA KHÁNH
        </h2>
        <span class="text-xs text-slate-600 pr-2">Địa chỉ: 32 Nguyễn Trung Ngạn, Cẩm Lệ, Đà Nẵng</span>
      </div>
      <p class="text-xs sm:text-sm text-slate-600 mb-4 leading-relaxed">
        VLXD Gia Khánh đóng vai trò là trạm cung ứng vật tư tổng hợp uy tín tại quận Cẩm Lệ, Đà Nẵng. Chúng tôi cung cấp đầy đủ các nhóm vật liệu xây dựng thô (cát xây, cát tô sạch hạt mịn, đá 1x2, đá 4x6, xi măng, gạch xây) và vật tư hoàn thiện nội thất (sơn nước, thiết bị vệ sinh, gạch men, bồn nước, keo dán gạch, phụ kiện điện nước) với đội xe ben giao hàng tận công trình.
      </p>
      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3">
        <div class="border border-slate-200 rounded-md overflow-hidden bg-slate-50">
          <img data-drive-id="1SlkIo25aXVZlRNVPXhzM_qJiCtPM1jBv" src="https://drive.google.com/thumbnail?id=1SlkIo25aXVZlRNVPXhzM_qJiCtPM1jBv&sz=w800" alt="Cửa hàng VLXD Gia Khánh - Ảnh 1" class="w-full h-36 sm:h-44 object-cover">
          <div class="p-2 text-[11px] font-medium text-center text-slate-700">Mặt tiền & Kho VLXD Gia Khánh</div>
        </div>
        <div class="border border-slate-200 rounded-md overflow-hidden bg-slate-50">
          <img data-drive-id="1TLOVdGeawzpiP65IiVy1r0P30MXhKhL7" src="https://drive.google.com/thumbnail?id=1TLOVdGeawzpiP65IiVy1r0P30MXhKhL7&sz=w800" alt="Cửa hàng VLXD Gia Khánh - Ảnh 2" class="w-full h-36 sm:h-44 object-cover">
          <div class="p-2 text-[11px] font-medium text-center text-slate-700">Khu trưng bày vật tư & thiết bị</div>
        </div>
        <div class="border border-slate-200 rounded-md overflow-hidden bg-slate-50">
          <img data-drive-id="1ocI6IdQfhaAEyAxMfBJT-CQ_p9tQR2-C" src="https://drive.google.com/thumbnail?id=1ocI6IdQfhaAEyAxMfBJT-CQ_p9tQR2-C&sz=w800" alt="Cửa hàng VLXD Gia Khánh - Ảnh 3" class="w-full h-36 sm:h-44 object-cover">
          <div class="p-2 text-[11px] font-medium text-center text-slate-700">Kho hàng vật liệu xây dựng</div>
        </div>
        <div class="border border-slate-200 rounded-md overflow-hidden bg-slate-50">
          <img data-drive-id="1RSgwCB3Is2l_tFR-vJDANLL8fjB7kP1-" src="https://drive.google.com/thumbnail?id=1RSgwCB3Is2l_tFR-vJDANLL8fjB7kP1-&sz=w800" alt="Cửa hàng VLXD Gia Khánh - Ảnh 4" class="w-full h-36 sm:h-44 object-cover">
          <div class="p-2 text-[11px] font-medium text-center text-slate-700">Vật tư sẵn kho số lượng lớn</div>
        </div>
        <div class="border border-slate-200 rounded-md overflow-hidden bg-slate-50 col-span-2 sm:col-span-1">
          <img data-drive-id="1ktciOZwlenlL10HHt0t23hlyRQAQ58QM" src="https://drive.google.com/thumbnail?id=1ktciOZwlenlL10HHt0t23hlyRQAQ58QM&sz=w800" alt="Cửa hàng VLXD Gia Khánh - Ảnh 5" class="w-full h-36 sm:h-44 object-cover">
          <div class="p-2 text-[11px] font-medium text-center text-slate-700">Vận chuyển giao hàng tận nơi</div>
        </div>
      </div>
    </section>

    <!-- FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ + KẾT NỐI FACEBOOK & GOOGLE MAP TRỰC QUAN -->
    <section id="bao-gia" class="grid grid-cols-1 lg:grid-cols-12 gap-5">
      
      <!-- Form Yêu Cầu & Báo Giá (6 cột) -->
      <div class="lg:col-span-6 bg-white p-4 sm:p-5 rounded-lg shadow-sm border border-slate-200">
        <div class="flatsome-section-header">
          <h2 class="flatsome-section-title">
            <i class="fa-solid fa-file-signature"></i> YÊU CẦU TƯ VẤN & BÁO GIÁ VẬT TƯ
          </h2>
        </div>
        <p class="text-xs text-slate-600 mb-3.5">
          Quý khách hàng, chủ thầu xây dựng cần báo giá sỉ các hạng mục VLXD thô hoặc hoàn thiện tại Đà Nẵng vui lòng điền thông tin bên dưới. Cửa hàng Gia Khánh sẽ phản hồi ngay!
        </p>
        <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3 text-xs sm:text-sm">
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Họ và tên khách hàng *</label>
              <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-brand-navy">
            </div>
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
              <input id="qPhone" type="tel" required placeholder="Ví dụ: 0905 xxx xxx" class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-brand-navy">
            </div>
          </div>
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Danh mục vật tư cần báo giá</label>
              <select id="qCategory" class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-brand-navy bg-white">
                <option value="Báo giá tổng hợp VLXD xây thô & hoàn thiện">Báo giá tổng hợp xây thô & hoàn thiện</option>
                <option value="Sơn nước & Chống thấm (Jotun, Dulux, Sika)">Sơn nước & Chống thấm (Jotun, Dulux, Sika)</option>
                <option value="Thiết bị vệ sinh & Phòng tắm">Thiết bị vệ sinh & Phòng tắm</option>
                <option value="Gạch men ốp lát & Ngói lợp">Gạch men ốp lát & Ngói lợp</option>
                <option value="Bồn nước & Bình nóng lạnh">Bồn nước & Bình nóng lạnh</option>
                <option value="Keo dán gạch, chà ron & Phụ gia">Keo dán gạch, chà ron & Phụ gia</option>
                <option value="Cát, Đá, Xi măng, Gạch xây thô">Cát, Đá, Xi măng, Gạch xây thô</option>
              </select>
            </div>
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Địa chỉ giao tới công trình</label>
              <input id="qAddress" type="text" placeholder="Phường/Quận tại Đà Nẵng..." class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-brand-navy">
            </div>
          </div>
          <div>
            <label class="block font-semibold text-slate-700 mb-1">Chi tiết khối lượng / Mã sản phẩm cần báo giá</label>
            <textarea id="qNote" rows="3" placeholder="Nhập danh sách vật tư, số lượng dự kiến hoặc yêu cầu xe vận chuyển..." class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-brand-navy"></textarea>
          </div>
          <div class="flex flex-wrap items-center gap-2.5 pt-1">
            <button type="submit" class="bg-brand-orange hover:bg-orange-700 text-white font-bold px-5 py-2.5 rounded transition inline-flex items-center gap-2">
              <i class="fa-solid fa-paper-plane"></i> GỬI YÊU CẦU BÁO GIÁ
            </button>
            <a href="https://zalo.me/0766663294" target="_blank" rel="noopener noreferrer" class="bg-brand-navy hover:bg-brand-blue text-white font-semibold px-4 py-2.5 rounded transition inline-flex items-center gap-1.5">
              <i class="fa-solid fa-comment-dots"></i> Gửi nhanh qua Zalo: 0766 663 294
            </a>
          </div>
          <div id="quoteSuccessMsg" class="hidden p-3 rounded bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-medium"></div>
        </form>
      </div>

      <!-- Đưa Google Map & Facebook ra ngoài Trang Chủ (6 cột) -->
      <div id="lien-he-map" class="lg:col-span-6 bg-white p-4 sm:p-5 rounded-lg shadow-sm border border-slate-200 flex flex-col justify-between space-y-4">
        <div>
          <div class="flatsome-section-header">
            <h2 class="flatsome-section-title">
              <i class="fa-solid fa-map-location-dot"></i> BẢN ĐỒ GOOGLE MAPS & FACEBOOK
            </h2>
          </div>

          <!-- Khung Google Map trực quan ngoài trang chủ -->
          <div class="border border-slate-200 rounded-lg overflow-hidden bg-slate-50 mb-3">
            <div class="p-2.5 bg-slate-100 flex flex-wrap items-center justify-between gap-2 text-xs">
              <div>
                <strong class="text-brand-navy">VLXD GIA KHÁNH:</strong> 32 Nguyễn Trung Ngạn, Cẩm Lệ, Đà Nẵng
              </div>
              <a href="https://share.google/Ejrvsw2yxguZE1soE" target="_blank" rel="noopener noreferrer" class="bg-brand-orange text-white px-2.5 py-1 rounded text-[11px] font-bold hover:bg-orange-700 transition inline-flex items-center gap-1">
                <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps chỉ đường
              </a>
            </div>
            <iframe
              title="Bản đồ Cửa hàng VLXD Gia Khánh 32 Nguyễn Trung Ngạn, Cẩm Lệ, Đà Nẵng"
              src="https://maps.google.com/maps?q=32%20Nguy%E1%BB%85n%20Trung%20Ng%E1%BA%A1n,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              class="w-full h-48 sm:h-52 border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade">
            </iframe>
          </div>
        </div>

        <!-- Khung Kết Nối Facebook chính thức ngoài trang chủ -->
        <div class="p-3.5 rounded-lg bg-[#f0f5ff] border border-blue-200 flex flex-col sm:flex-row items-start sm:items-center justify-between gap-3">
          <div class="flex items-center gap-3">
            <div class="w-11 h-11 rounded-full bg-[#1877F2] text-white flex items-center justify-center text-xl shrink-0">
              <i class="fa-brands fa-facebook-f"></i>
            </div>
            <div class="text-xs">
              <div class="font-bold text-brand-navy text-sm">Facebook Cửa Hàng VLXD Gia Khánh</div>
              <div class="text-slate-600">Kết nối trực tiếp qua Facebook để xem hàng mới về & nhắn tin báo giá</div>
              <div class="text-[11px] text-blue-700 font-medium break-all">facebook.com/vo.thi.len.740204</div>
            </div>
          </div>
          <a href="https://www.facebook.com/vo.thi.len.740204/" target="_blank" rel="noopener noreferrer" class="shrink-0 bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold px-3.5 py-2 rounded transition inline-flex items-center gap-1.5">
            <i class="fa-brands fa-facebook"></i> Truy cập Facebook
          </a>
        </div>
      </div>
    </section>

    <!-- DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM XÂY DỰNG) -->
    <section id="tin-tuc" class="bg-white p-4 sm:p-5 rounded-lg shadow-sm border border-slate-200">
      <div class="flatsome-section-header">
        <h2 class="flatsome-section-title">
          <i class="fa-solid fa-newspaper"></i> DANH MỤC BÀI VIẾT & KINH NGHIỆM XÂY DỰNG
        </h2>
        <span class="text-xs text-brand-navy font-semibold pr-2">Cập nhật kiến thức & Bảng giá VLXD Đà Nẵng</span>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <article class="border border-slate-200 rounded-lg overflow-hidden hover:shadow-md transition flex flex-col">
          <img data-drive-id="1SlkIo25aXVZlRNVPXhzM_qJiCtPM1jBv" src="https://drive.google.com/thumbnail?id=1SlkIo25aXVZlRNVPXhzM_qJiCtPM1jBv&sz=w600" alt="Kinh nghiệm chọn VLXD Cẩm Lệ Đà Nẵng" class="w-full h-40 object-cover">
          <div class="p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <span class="text-[11px] text-brand-orange font-bold uppercase">Kinh nghiệm xây thô</span>
              <h3 class="font-bold text-sm text-brand-navy mt-1 mb-2 leading-snug">
                Kinh nghiệm chọn đại lý vật liệu xây dựng uy tín tại Cẩm Lệ, Đà Nẵng tránh thất thoát khối lượng
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                Hướng dẫn kiểm tra chất lượng cát xây tô hạt mịn không lẫn bùn, đá 1x2 xanh chịu lực và lựa chọn đội xe ben giao hàng tận hẻm nhỏ tại Khuê Trung, Hòa Xuân.
              </p>
            </div>
            <div class="mt-3 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] text-slate-500">
              <span><i class="fa-regular fa-calendar mr-1"></i>VLXD Gia Khánh</span>
              <a href="#bao-gia" class="text-brand-orange font-semibold hover:underline">Nhận tư vấn &rarr;</a>
            </div>
          </div>
        </article>

        <article class="border border-slate-200 rounded-lg overflow-hidden hover:shadow-md transition flex flex-col">
          <img data-drive-id="171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O" src="https://drive.google.com/thumbnail?id=171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O&sz=w600" alt="Cách chọn sơn và chống thấm Đà Nẵng" class="w-full h-40 object-cover">
          <div class="p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <span class="text-[11px] text-brand-orange font-bold uppercase">Sơn & Chống thấm</span>
              <h3 class="font-bold text-sm text-brand-navy mt-1 mb-2 leading-snug">
                Quy trình chống thấm Sika & chọn sơn ngoại thất Jotun, Dulux bền màu cho khí hậu miền Trung
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                Khí hậu Đà Nẵng nắng mưa thất thường đòi hỏi quy trình xử lý chống thấm tường, sàn mái bằng hóa chất Sika, Bestmix kết hợp sơn lót chống kiềm chính hãng.
              </p>
            </div>
            <div class="mt-3 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] text-slate-500">
              <span><i class="fa-regular fa-calendar mr-1"></i>Kỹ thuật thi công</span>
              <a href="#sec-son" class="text-brand-orange font-semibold hover:underline">Xem sản phẩm &rarr;</a>
            </div>
          </div>
        </article>

        <article class="border border-slate-200 rounded-lg overflow-hidden hover:shadow-md transition flex flex-col">
          <img data-drive-id="1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h" src="https://drive.google.com/thumbnail?id=1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h&sz=w600" alt="Chọn gạch men và thiết bị vệ sinh" class="w-full h-40 object-cover">
          <div class="p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <span class="text-[11px] text-brand-orange font-bold uppercase">Hoàn thiện nội thất</span>
              <h3 class="font-bold text-sm text-brand-navy mt-1 mb-2 leading-snug">
                Bí quyết phối gạch men Porcelain 80x80 và chọn combo thiết bị vệ sinh Inax, Viglacera tiết kiệm
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                Tổng hợp cách chọn gạch lát nền chống trầy xước, keo dán gạch chống bong tróc và trọn bộ bồn cầu, sen cây tắm nóng lạnh bền đẹp cho nhà phố hiện đại.
              </p>
            </div>
            <div class="mt-3 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] text-slate-500">
              <span><i class="fa-regular fa-calendar mr-1"></i>Tư vấn hoàn thiện</span>
              <a href="#sec-tbvs" class="text-brand-orange font-semibold hover:underline">Xem bảng giá &rarr;</a>
            </div>
          </div>
        </article>
      </div>
    </section>

    <!-- DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI -->
    <section class="bg-white p-4 sm:p-5 rounded-lg shadow-sm border border-slate-200">
      <div class="flatsome-section-header">
        <h2 class="flatsome-section-title">
          <i class="fa-solid fa-handshake"></i> ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI CHÍNH HÃNG
        </h2>
      </div>
      <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 gap-2.5 text-center">
        <div class="p-3 border border-slate-200 rounded bg-slate-50 hover:border-brand-navy transition">
          <div class="font-heading font-extrabold text-sm text-brand-navy">JOTUN</div>
          <div class="text-[10px] text-slate-500">Sơn Nội Ngoại Thất</div>
        </div>
        <div class="p-3 border border-slate-200 rounded bg-slate-50 hover:border-brand-navy transition">
          <div class="font-heading font-extrabold text-sm text-blue-800">DULUX</div>
          <div class="text-[10px] text-slate-500">Sơn & Bột Trét</div>
        </div>
        <div class="p-3 border border-slate-200 rounded bg-slate-50 hover:border-brand-navy transition">
          <div class="font-heading font-extrabold text-sm text-sky-700">INAX</div>
          <div class="text-[10px] text-slate-500">Thiết Bị Vệ Sinh</div>
        </div>
        <div class="p-3 border border-slate-200 rounded bg-slate-50 hover:border-brand-navy transition">
          <div class="font-heading font-extrabold text-sm text-red-700">ĐỒNG TÂM</div>
          <div class="text-[10px] text-slate-500">Gạch Men & Keo</div>
        </div>
        <div class="p-3 border border-slate-200 rounded bg-slate-50 hover:border-brand-navy transition">
          <div class="font-heading font-extrabold text-sm text-amber-600">SIKA</div>
          <div class="text-[10px] text-slate-500">Phụ Gia Chống Thấm</div>
        </div>
        <div class="p-3 border border-slate-200 rounded bg-slate-50 hover:border-brand-navy transition">
          <div class="font-heading font-extrabold text-sm text-emerald-700">BESTMIX</div>
          <div class="text-[10px] text-slate-500">Keo Dán Gạch & Vữa</div>
        </div>
        <div class="p-3 border border-slate-200 rounded bg-slate-50 hover:border-brand-navy transition">
          <div class="font-heading font-extrabold text-sm text-blue-900">SƠN HÀ</div>
          <div class="text-[10px] text-slate-500">Bồn Nước Inox & Nhựa</div>
        </div>
        <div class="p-3 border border-slate-200 rounded bg-slate-50 hover:border-brand-navy transition">
          <div class="font-heading font-extrabold text-sm text-orange-700">TÂN Á</div>
          <div class="text-[10px] text-slate-500">Bồn Nước Đại Thành</div>
        </div>
        <div class="p-3 border border-slate-200 rounded bg-slate-50 hover:border-brand-navy transition">
          <div class="font-heading font-extrabold text-sm text-red-600">ARISTON</div>
          <div class="text-[10px] text-slate-500">Bình Nóng Lạnh Ý</div>
        </div>
        <div class="p-3 border border-slate-200 rounded bg-slate-50 hover:border-brand-navy transition">
          <div class="font-heading font-extrabold text-sm text-orange-600">FERROLI</div>
          <div class="text-[10px] text-slate-500">Máy Nước Nóng</div>
        </div>
        <div class="p-3 border border-slate-200 rounded bg-slate-50 hover:border-brand-navy transition">
          <div class="font-heading font-extrabold text-sm text-rose-800">ĐẤT VIỆT</div>
          <div class="text-[10px] text-slate-500">Ngói Lợp Cao Cấp</div>
        </div>
        <div class="p-3 border border-slate-200 rounded bg-slate-50 hover:border-brand-navy transition">
          <div class="font-heading font-extrabold text-sm text-teal-800">VIGLACERA</div>
          <div class="text-[10px] text-slate-500">Sứ Vệ Sinh & Sen Vòi</div>
        </div>
      </div>
    </section>

  </main>

  <!-- FOOTER CHUẨN FLATSOME (GIỐNG WEB MẪU NOITHATNGONGUYEN.COM) -->
  <footer class="bg-brand-navy text-white mt-8 border-t-4 border-brand-orange">
    <div class="flatsome-container py-8 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 text-xs sm:text-sm">
      
      <!-- Cột 1: Thông tin cửa hàng -->
      <div>
        <div class="flex items-center gap-2.5 mb-3">
          <svg class="w-8 h-8 shrink-0" viewBox="0 0 100 100" fill="none">
            <rect width="100" height="100" rx="16" fill="#ffffff"/>
            <path d="M18 66L50 34L82 66" stroke="#e65100" stroke-width="8" stroke-linecap="round" stroke-linejoin="round"/>
            <path d="M30 66V80H70V66" stroke="#0c3559" stroke-width="6" stroke-linecap="round" stroke-linejoin="round"/>
            <rect x="42" y="54" width="16" height="16" rx="2" fill="#f59e0b"/>
          </svg>
          <div>
            <div class="font-heading font-extrabold text-sm text-white uppercase">CỬA HÀNG VLXD GIA KHÁNH</div>
            <div class="text-[11px] text-brand-amber">Website: giakhanh.com</div>
          </div>
        </div>
        <ul class="space-y-2 text-slate-200 text-xs">
          <li><i class="fa-solid fa-location-dot text-brand-amber mr-2"></i><strong>Địa chỉ:</strong> 32 Nguyễn Trung Ngạn, Q. Cẩm Lệ, TP. Đà Nẵng</li>
          <li><i class="fa-solid fa-phone-volume text-brand-amber mr-2"></i><strong>Hotline / Zalo:</strong> <a href="tel:0766663294" class="text-brand-amber font-bold">0766 663 294</a></li>
          <li><i class="fa-solid fa-globe text-brand-amber mr-2"></i><strong>Website:</strong> giakhanh.com</li>
          <li><i class="fa-brands fa-facebook text-brand-amber mr-2"></i><strong>Facebook:</strong> <a href="https://www.facebook.com/vo.thi.len.740204/" target="_blank" rel="noopener noreferrer" class="underline hover:text-brand-amber">Võ Thị Lên (VLXD Gia Khánh)</a></li>
        </ul>
      </div>

      <!-- Cột 2: Danh mục sản phẩm -->
      <div>
        <h3 class="font-heading font-bold text-sm uppercase text-brand-amber mb-3 pb-1.5 border-b border-white/15">DANH MỤC SẢN PHẨM</h3>
        <ul class="space-y-1.5 text-xs text-slate-200">
          <li><a href="#sec-son" class="hover:text-brand-amber transition">&rsaquo; Sơn Jotun, Dulux, Tito & Chống thấm</a></li>
          <li><a href="#sec-tbvs" class="hover:text-brand-amber transition">&rsaquo; Thiết bị vệ sinh Inax, Viglacera</a></li>
          <li><a href="#sec-gach" class="hover:text-brand-amber transition">&rsaquo; Gạch men Đồng Tâm, Kimgres</a></li>
          <li><a href="#sec-ngoi" class="hover:text-brand-amber transition">&rsaquo; Ngói lợp DIC, Ngói Đất Việt</a></li>
          <li><a href="#sec-bonnuoc" class="hover:text-brand-amber transition">&rsaquo; Bồn nước Sơn Hà, Tân Á, Letton</a></li>
          <li><a href="#sec-binhnonglanh" class="hover:text-brand-amber transition">&rsaquo; Bình nóng lạnh Ariston, Ferroli</a></li>
          <li><a href="#sec-keo" class="hover:text-brand-amber transition">&rsaquo; Keo dán gạch, Chà ron, Phụ gia Sika</a></li>
          <li><a href="#sec-vlxd-tho" class="hover:text-brand-amber transition">&rsaquo; Cát, Đá, Xi măng & Vật tư tổng hợp</a></li>
        </ul>
      </div>

      <!-- Cột 3: Liên kết & Hỗ trợ -->
      <div>
        <h3 class="font-heading font-bold text-sm uppercase text-brand-amber mb-3 pb-1.5 border-b border-white/15">LIÊN KẾT HỖ TRỢ</h3>
        <ul class="space-y-1.5 text-xs text-slate-200">
          <li><a href="#" class="hover:text-brand-amber transition">&rsaquo; Trang chủ giakhanh.com</a></li>
          <li><a href="#hinh-anh-cua-hang" class="hover:text-brand-amber transition">&rsaquo; Hình ảnh thực tế kho bãi</a></li>
          <li><a href="#bao-gia" class="hover:text-brand-amber transition">&rsaquo; Gửi yêu cầu báo giá công trình</a></li>
          <li><a href="#tin-tuc" class="hover:text-brand-amber transition">&rsaquo; Kinh nghiệm chọn vật tư xây dựng</a></li>
          <li><a href="https://share.google/Ejrvsw2yxguZE1soE" target="_blank" rel="noopener noreferrer" class="hover:text-brand-amber transition">&rsaquo; Chỉ đường Google Maps</a></li>
        </ul>
      </div>

      <!-- Cột 4: Kết nối nhanh -->
      <div>
        <h3 class="font-heading font-bold text-sm uppercase text-brand-amber mb-3 pb-1.5 border-b border-white/15">KẾT NỐI VỚI GIA KHÁNH</h3>
        <p class="text-xs text-slate-200 mb-3 leading-relaxed">
          Cam kết cung cấp vật tư chính hãng, cát sạch đá chuẩn, giao hàng nhanh bằng xe ben lớn nhỏ vào tận mọi công trình tại Cẩm Lệ & TP. Đà Nẵng.
        </p>
        <div class="flex flex-wrap gap-2">
          <a href="https://www.facebook.com/vo.thi.len.740204/" target="_blank" rel="noopener noreferrer" class="bg-[#1877F2] hover:bg-blue-600 text-white px-3 py-1.5 rounded text-xs font-semibold inline-flex items-center gap-1.5">
            <i class="fa-brands fa-facebook-f"></i> Facebook
          </a>
          <a href="https://zalo.me/0766663294" target="_blank" rel="noopener noreferrer" class="bg-sky-500 hover:bg-sky-600 text-white px-3 py-1.5 rounded text-xs font-semibold inline-flex items-center gap-1.5">
            <i class="fa-solid fa-comment-dots"></i> Chat Zalo
          </a>
          <a href="https://share.google/Ejrvsw2yxguZE1soE" target="_blank" rel="noopener noreferrer" class="bg-brand-orange hover:bg-orange-600 text-white px-3 py-1.5 rounded text-xs font-semibold inline-flex items-center gap-1.5">
            <i class="fa-solid fa-location-dot"></i> Bản Đồ Map
          </a>
        </div>
      </div>

    </div>
    <div class="bg-[#07223b] py-3 text-center text-xs text-slate-300 border-t border-white/10">
      Copyright 2026 &copy; <strong>CỬA HÀNG VLXD GIA KHÁNH (giakhanh.com)</strong> - 32 Nguyễn Trung Ngạn, Cẩm Lệ, Đà Nẵng. Hotline: 0766 663 294.
    </div>
  </footer>

  <!-- CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE, MAP) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI -->
  <!-- Trên Máy Tính: Cột nút nổi góc dưới bên phải -->
  <div class="hidden md:flex fixed right-4 bottom-5 z-50 flex-col gap-2.5">
    <a href="https://share.google/Ejrvsw2yxguZE1soE" target="_blank" rel="noopener noreferrer" title="Chỉ đường Google Maps" class="flex items-center gap-2 bg-emerald-600 hover:bg-emerald-700 text-white px-3.5 py-2.5 rounded-full shadow-lg text-xs font-bold transition">
      <i class="fa-solid fa-location-dot text-sm"></i>
      <span>Chỉ đường Map</span>
    </a>
    <a href="https://www.facebook.com/vo.thi.len.740204/" target="_blank" rel="noopener noreferrer" title="Chat Facebook" class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3.5 py-2.5 rounded-full shadow-lg text-xs font-bold transition">
      <i class="fa-brands fa-facebook-f text-sm"></i>
      <span>Facebook</span>
    </a>
    <a href="https://zalo.me/0766663294" target="_blank" rel="noopener noreferrer" title="Chat Zalo 0766 663 294" class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white px-3.5 py-2.5 rounded-full shadow-lg text-xs font-bold transition">
      <i class="fa-solid fa-comment-dots text-sm"></i>
      <span>Chat Zalo</span>
    </a>
    <a href="tel:0766663294" title="Gọi Hotline 0766 663 294" class="pulse-btn flex items-center gap-2 bg-brand-orange hover:bg-orange-700 text-white px-4 py-2.5 rounded-full shadow-xl text-xs font-extrabold transition">
      <i class="fa-solid fa-phone-volume text-sm"></i>
      <span>0766 663 294</span>
    </a>
  </div>

  <!-- Trên Điện Thoại: Thanh liên hệ nổi bật cố định dưới đáy màn hình chuẩn Flatsome (giống noithatngonguyen.com) -->
  <div class="md:hidden fixed bottom-0 left-0 right-0 bg-white border-t border-slate-200 shadow-[0_-4px_12px_rgba(0,0,0,0.08)] z-50 grid grid-cols-4 py-1.5 text-center">
    <a href="https://share.google/Ejrvsw2yxguZE1soE" target="_blank" rel="noopener noreferrer" class="flex flex-col items-center justify-center text-[11px] font-semibold text-slate-700">
      <i class="fa-solid fa-map-location-dot text-emerald-600 text-base mb-0.5"></i>
      <span>Tìm đường</span>
    </a>
    <a href="https://zalo.me/0766663294" target="_blank" rel="noopener noreferrer" class="flex flex-col items-center justify-center text-[11px] font-semibold text-slate-700">
      <i class="fa-solid fa-comment-dots text-[#0068ff] text-base mb-0.5"></i>
      <span>Chat Zalo</span>
    </a>
    <a href="https://www.facebook.com/vo.thi.len.740204/" target="_blank" rel="noopener noreferrer" class="flex flex-col items-center justify-center text-[11px] font-semibold text-slate-700">
      <i class="fa-brands fa-facebook text-[#1877F2] text-base mb-0.5"></i>
      <span>Facebook</span>
    </a>
    <a href="tel:0766663294" class="flex flex-col items-center justify-center text-[11px] font-bold text-brand-orange">
      <i class="fa-solid fa-phone-volume text-brand-orange text-base mb-0.5"></i>
      <span>Gọi điện</span>
    </a>
  </div>

  <!-- MODAL XEM CHI TIẾT SẢN PHẨM & NHẬN BÁO GIÁ -->
  <div id="productModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3">
    <div class="bg-white rounded-lg max-w-lg w-full overflow-hidden shadow-2xl border border-slate-200">
      <div class="bg-brand-navy text-white px-4 py-3 flex items-center justify-between">
        <h3 id="modalTitle" class="font-heading font-bold text-sm">Chi tiết sản phẩm</h3>
        <button onclick="closeProductModal()" class="w-7 h-7 rounded bg-white/10 flex items-center justify-center hover:bg-white/20">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4 space-y-3">
        <img id="modalImg" src="" alt="" class="w-full h-56 object-contain bg-slate-50 rounded border border-slate-200">
        <div class="flex items-center gap-3">
          <span id="modalSalePrice" class="text-lg font-extrabold text-brand-orange"></span>
          <span id="modalOldPrice" class="text-xs text-slate-400 line-through"></span>
          <span id="modalDiscount" class="bg-red-600 text-white text-[11px] font-bold px-2 py-0.5 rounded"></span>
        </div>
        <p id="modalDesc" class="text-xs text-slate-600 leading-relaxed"></p>
        <div class="pt-2 flex flex-wrap gap-2">
          <a id="modalQuoteBtn" href="#bao-gia" onclick="closeProductModal()" class="bg-brand-orange hover:bg-orange-700 text-white text-xs font-bold px-4 py-2.5 rounded transition">
            Đặt hàng / Nhận báo giá sỉ
          </a>
          <a href="https://zalo.me/0766663294" target="_blank" rel="noopener noreferrer" class="bg-[#0068ff] hover:bg-blue-700 text-white text-xs font-bold px-4 py-2.5 rounded transition">
            Tư vấn qua Zalo: 0766 663 294
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- JAVASCRIPT XỬ LÝ DỮ LIỆU 19 ẢNH SẢN PHẨM THỰC TẾ, SLIDER, TÌM KIẾM & FALLBACK ẢNH GOOGLE DRIVE -->
  <script>
    /*
     * Danh sách 19 file ID ảnh sản phẩm thực tế từ Google Drive do khách hàng cung cấp:
     * 1. 1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY
     * 2. 11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP
     * 3. 1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr
     * 4. 1X31hmhpLVVORV-tmMSZYzBO-qtpyusry
     * 5. 171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O
     * 6. 1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg
     * 7. 1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4
     * 8. 1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54
     * 9. 19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r
     * 10. 1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h
     * 11. 1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN
     * 12. 1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c
     * 13. 1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP
     * 14. 1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-
     * 15. 17YrxXteZmzhvVRYgfaklNGC2hKjN09N8
     * 16. 19k5uWHn_xeas2_BMP_JgBDwwu-IysSRP
     * 17. 1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf
     * 18. 15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_
     * 19. 1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh
     */

    const catalogSections = [
      {
        id: 'sec-son',
        title: 'SƠN',
        subtabs: ['Jotun', 'Dulux - Maxilite', 'Tito', 'Chống thấm'],
        products: [
          {
            name: 'Sơn Ngoại Thất Jotun Jotashield Bền Màu Tối Ưu Chính Hãng',
            driveId: '1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY',
            oldPrice: '2.450.000đ',
            salePrice: '1.960.000đ',
            discount: '-20%',
            desc: 'Dòng sơn ngoại thất cao cấp chống tia UV, chống bám bụi và rêu mốc vượt trội cho công trình tại Đà Nẵng.'
          },
          {
            name: 'Sơn Nội Thất Jotun Essence Che Phủ Tối Đa Bóng Cao Cấp',
            driveId: '11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP',
            oldPrice: '1.650.000đ',
            salePrice: '1.350.000đ',
            discount: '-18%',
            desc: 'Sơn nội thất màng sơn bóng sang trọng, dễ lau chùi và độ che phủ cao.'
          },
          {
            name: 'Sơn Nước Ngoại Thất Jotun Tough Shield Max Chống Phai Màu',
            driveId: '1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr',
            oldPrice: '1.890.000đ',
            salePrice: '1.550.000đ',
            discount: '-18%',
            desc: 'Bảo vệ tường ngoại thất bền bỉ trước thời tiết nắng mưa miền Trung.'
          },
          {
            name: 'Sơn Lót Chống Kiềm Nội Ngoại Thất Dulux & Maxilite Chính Hãng',
            driveId: '1X31hmhpLVVORV-tmMSZYzBO-qtpyusry',
            oldPrice: '1.420.000đ',
            salePrice: '1.180.000đ',
            discount: '-17%',
            desc: 'Tăng cường độ bám dính, kháng kiềm và giữ màu sơn phủ bền lâu.'
          }
        ]
      },
      {
        id: 'sec-tbvs',
        title: 'THIẾT BỊ VỆ SINH',
        subtabs: ['Bồn cầu', 'Sen vòi', 'Lavabo', 'Gương', 'Phụ kiện nhà tắm'],
        products: [
          {
            name: 'Bồn Cầu Liền Khối Men Tuyết Kháng Khuẩn Nắp Đóng Êm Cao Cấp',
            driveId: '171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O',
            oldPrice: '4.500.000đ',
            salePrice: '3.600.000đ',
            discount: '-20%',
            desc: 'Bồn cầu 1 khối xả xoáy mạnh mẽ, tiết kiệm nước, lớp men sứ chống bám bẩn bảo hành dài hạn.'
          },
          {
            name: 'Sen Cây Tắm Đứng Nóng Lạnh Inax BFV-615S-8C Chính Hãng',
            driveId: '1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg',
            oldPrice: '4.200.000đ',
            salePrice: '3.360.000đ',
            discount: '-20%',
            desc: 'Sen cây tắm đứng nóng lạnh mạ Crom-Niken sáng bóng, bát sen lớn tạo áp lực nước êm ái.'
          },
          {
            name: 'Sen Cây Viglacera Nóng Lạnh VG583 & Bộ Vòi Lavabo Đồng Thau',
            driveId: '1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4',
            oldPrice: '3.450.000đ',
            salePrice: '2.820.000đ',
            discount: '-18%',
            desc: 'Thiết bị phòng tắm đồng bộ chống gỉ sét, vận hành bền bỉ.'
          },
          {
            name: 'Bộ Phụ Kiện Phòng Tắm Inox 304, Chậu Rửa Lavabo & Gương Soi',
            driveId: '1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54',
            oldPrice: '1.950.000đ',
            salePrice: '1.560.000đ',
            discount: '-20%',
            desc: 'Trọn bộ phụ kiện nhà tắm chất liệu Inox 304 cao cấp sáng đẹp.'
          }
        ]
      },
      {
        id: 'sec-gach',
        title: 'GẠCH MEN',
        subtabs: ['Đồng Tâm', 'Gạch 80x80', 'Gạch 60x60', 'Gạch 30x60', 'Kimgres'],
        products: [
          {
            name: 'Gạch Porcelain Kháng Khuẩn Đồng Tâm 80x80 Vân Đá Bóng Kính',
            driveId: '19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r',
            oldPrice: '340.000đ/m²',
            salePrice: '275.000đ/m²',
            discount: '-19%',
            desc: 'Gạch lát nền khổ lớn 80x80 xương đá Porcelain cứng chắc, chống thấm và chống trầy xước.'
          },
          {
            name: 'Gạch Porcelain 2 Da 8080PLATINUM & Gạch Lát Nền 60x60 Cao Cấp',
            driveId: '1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h',
            oldPrice: '295.000đ/m²',
            salePrice: '245.000đ/m²',
            discount: '-17%',
            desc: 'Mẫu gạch men vân đá tự nhiên sang trọng cho phòng khách và sảnh lớn.'
          },
          {
            name: 'Gạch Ốp Tường 30x60 & Gạch Sân Vườn Chống Trơn Trượt Kimgres',
            driveId: '1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN',
            oldPrice: '230.000đ/m²',
            salePrice: '190.000đ/m²',
            discount: '-17%',
            desc: 'Độ bền màu cao, bề mặt chống rêu mốc và chống trơn hiệu quả.'
          }
        ]
      },
      {
        id: 'sec-ngoi',
        title: 'NGÓI LỢP',
        subtabs: ['DIC', 'Ngói Đất Việt'],
        products: [
          {
            name: 'Ngói Màu Cao Cấp DIC Đỏ Tươi DT10S & Xám Tro XT07S Chống Rêu',
            driveId: '1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c',
            oldPrice: '38.000đ/viên',
            salePrice: '31.500đ/viên',
            discount: '-17%',
            desc: 'Ngói màu công nghệ sơn phủ ướt bền màu, chịu lực uốn cao, chống thấm dột tuyệt đối.'
          },
          {
            name: 'Ngói Đất Sét Nung Đất Việt Cao Cấp Lợp Mái Biệt Thự & Nhà Phố',
            driveId: '1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP',
            oldPrice: '26.000đ/viên',
            salePrice: '21.500đ/viên',
            discount: '-17%',
            desc: 'Ngói Đất Việt chính hãng mát nhà mùa hè, chống rêu mốc vĩnh viễn.'
          }
        ]
      },
      {
        id: 'sec-bonnuoc',
        title: 'BỒN NƯỚC',
        subtabs: ['Letton', 'Sơn Hà', 'Tân Á'],
        products: [
          {
            name: 'Bồn Nước Inox Tân Á & Sơn Hà Đứng / Ngang 1000L - 2000L Chính Hãng',
            driveId: '1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-',
            oldPrice: '4.150.000đ',
            salePrice: '3.450.000đ',
            discount: '-17%',
            desc: 'Chế tạo từ Inox SUS 304 siêu bền, đảm bảo an toàn vệ sinh nguồn nước sinh hoạt.'
          }
        ]
      },
      {
        id: 'sec-binhnonglanh',
        title: 'BÌNH NÓNG LẠNH',
        subtabs: ['Ariston', 'Ferroli'],
        products: [
          {
            name: 'Máy Nước Nóng Ariston & Ferroli 15L - 30L Thanh Đốt Đồng Chống Giật ELCB',
            driveId: '17YrxXteZmzhvVRYgfaklNGC2hKjN09N8',
            oldPrice: '3.250.000đ',
            salePrice: '2.650.000đ',
            discount: '-18%',
            desc: 'Làm nóng nhanh, giữ nhiệt lâu, tích hợp hệ thống chống giật ELCB an toàn tuyệt đối.'
          }
        ]
      },
      {
        id: 'sec-keo',
        title: 'KEO DÁN GẠCH, CHÀ RON',
        subtabs: ['Bestmix', 'Đồng Tâm', 'Keo cá sấu', 'Sika'],
        products: [
          {
            name: 'Keo Dán Gạch Gecko Floor Đồng Tâm & Sika Tilebond GP Bao 25Kg',
            driveId: '19k5uWHn_xeas2_BMP_JgBDwwu-IysSRP',
            oldPrice: '265.000đ/bao',
            salePrice: '215.000đ/bao',
            discount: '-19%',
            desc: 'Độ bám dính cực cao cho gạch Porcelain khổ lớn, chống bongộp nền và tường.'
          },
          {
            name: 'Keo Chà Ron Cá Sấu Crocodile Silver & Phụ Gia Chống Thấm Bestmix',
            driveId: '1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf',
            oldPrice: '95.000đ/bịch',
            salePrice: '75.000đ/bịch',
            discount: '-21%',
            desc: 'Đường ron mịn đẹp, chống thấm nước, chống nấm mốc đen mạch gạch.'
          }
        ]
      },
      {
        id: 'sec-vlxd-tho',
        title: 'VLXD THÔ & VẬT TƯ TỔNG HỢP TẠI KHO GIA KHÁNH',
        subtabs: ['Cát xây tô', 'Đá 1x2 & 4x6', 'Xi măng', 'Phụ kiện công trình'],
        products: [
          {
            name: 'Cát Xây Tô Hạt Mịn Sạch, Đá 1x2, Đá 4x6 Chịu Lực & Xi Măng Bao Chuẩn',
            driveId: '15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_',
            oldPrice: 'Giá sỉ tận bãi',
            salePrice: 'Liên hệ 0766 663 294',
            discount: '-15%',
            desc: 'Nguồn cát sạch không lẫn tạp chất, đá xanh chịu lực cao, giao bằng xe ben tận chân công trình Cẩm Lệ & Đà Nẵng.'
          },
          {
            name: 'Vật Tư Phụ Kiện Xây Dựng, Ống Nước & Thiết Bị Hoàn Thiện Tổng Hợp',
            driveId: '1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh',
            oldPrice: 'Báo giá theo đơn',
            salePrice: 'Chiết khấu cao',
            discount: '-20%',
            desc: 'Đầy đủ phụ kiện phục vụ xây thô và hoàn thiện nhà dân dụng, dự án với giá đại lý cấp 1.'
          }
        ]
      }
    ];

    function renderCatalog(filterCat = 'ALL', searchKeyword = '') {
      const container = document.getElementById('catalogContainer');
      const kw = searchKeyword.trim().toLowerCase();
      let html = '';

      catalogSections.forEach(sec => {
        if (filterCat !== 'ALL' && sec.id !== filterCat) return;

        const filteredProducts = sec.products.filter(p => {
          if (!kw) return true;
          return p.name.toLowerCase().includes(kw) || sec.title.toLowerCase().includes(kw) || p.desc.toLowerCase().includes(kw);
        });

        if (filteredProducts.length === 0) return;

        const subtabsHtml = sec.subtabs.map(sub =>
          `<a href="#${sec.id}" class="text-[11px] sm:text-xs font-medium text-slate-600 hover:text-brand-orange px-2 py-1 rounded hover:bg-slate-100 whitespace-nowrap transition">${sub}</a>`
        ).join('');

        const productsHtml = filteredProducts.map((prod) => {
          const thumbUrl = `https://drive.google.com/thumbnail?id=${prod.driveId}&sz=w700`;
          const safeName = prod.name.replace(/'/g, "\\'");
          const safeDesc = prod.desc.replace(/'/g, "\\'");
          return `
            <div class="bg-white border border-slate-200/90 rounded-md overflow-hidden hover:shadow-md transition flex flex-col justify-between group relative">
              <!-- Phần trăm giảm giá góc trên bên trái chuẩn Flatsome -->
              <span class="flatsome-sale-badge">${prod.discount}</span>

              <a href="#bao-gia" onclick="openProductModal('${safeName}', '${prod.driveId}', '${prod.salePrice}', '${prod.oldPrice}', '${prod.discount}', '${safeDesc}'); return false;" class="block overflow-hidden bg-slate-50 border-b border-slate-100">
                <img
                  data-drive-id="${prod.driveId}"
                  src="${thumbUrl}"
                  alt="${prod.name}"
                  loading="lazy"
                  class="w-full h-36 sm:h-44 object-cover group-hover:scale-105 transition duration-300"
                >
              </a>

              <!-- Thông tin sản phẩm: Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc thiếu chữ -->
              <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[10px] text-slate-400 uppercase font-semibold mb-0.5">${sec.title}</div>
                  <h3 class="product-title-full text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-brand-navy mb-2">
                    <a href="#bao-gia" onclick="openProductModal('${safeName}', '${prod.driveId}', '${prod.salePrice}', '${prod.oldPrice}', '${prod.discount}', '${safeDesc}'); return false;">
                      ${prod.name}
                    </a>
                  </h3>
                </div>

                <div class="pt-1.5 border-t border-slate-100">
                  <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                    <span class="text-xs sm:text-sm font-extrabold text-brand-orange">${prod.salePrice}</span>
                    <span class="text-[10px] sm:text-[11px] text-slate-400 line-through">${prod.oldPrice}</span>
                  </div>
                  <button
                    onclick="openProductModal('${safeName}', '${prod.driveId}', '${prod.salePrice}', '${prod.oldPrice}', '${prod.discount}', '${safeDesc}')"
                    class="w-full bg-brand-navy hover:bg-brand-orange text-white text-[11px] font-semibold py-1.5 px-2 rounded transition">
                    Xem & Báo Giá
                  </button>
                </div>
              </div>
            </div>
          `;
        }).join('');

        html += `
          <section id="${sec.id}" class="bg-white p-3.5 sm:p-4 rounded-lg shadow-sm border border-slate-200">
            <div class="flatsome-section-header">
              <h2 class="flatsome-section-title">
                <span>${sec.title}</span>
              </h2>
              <div class="flex items-center gap-1 overflow-x-auto py-1 pr-2">
                ${subtabsHtml}
                <a href="#bao-gia" class="text-[11px] sm:text-xs font-bold text-brand-orange pl-2 whitespace-nowrap hover:underline">
                  Xem thêm &rsaquo;
                </a>
              </div>
            </div>
            <!-- Sản phẩm chia thành 2 cột trên giao diện điện thoại (grid-cols-2), 4 cột trên máy tính -->
            <div class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-3.5">
              ${productsHtml}
            </div>
          </section>
        `;
      });

      if (!html) {
        html = `
          <div class="bg-white p-8 rounded-lg text-center border border-slate-200">
            <p class="text-sm text-slate-600 mb-3">Không tìm thấy sản phẩm khớp với từ khóa "<strong>${searchKeyword}</strong>".</p>
            <button onclick="filterCategory('ALL')" class="bg-brand-navy text-white text-xs font-bold px-4 py-2 rounded">Hiển thị tất cả sản phẩm</button>
          </div>
        `;
      }

      container.innerHTML = html;
      attachDriveImageFallbacks();
    }

    /* Cơ chế tự động chuyển đổi link dự phòng cho ảnh Google Drive để đảm bảo hiển thị 100% */
    function attachDriveImageFallbacks() {
      const imgs = document.querySelectorAll('img[data-drive-id]');
      imgs.forEach(img => {
        if (img.dataset.boundFallback) return;
        img.dataset.boundFallback = 'true';
        img.dataset.tryStep = '0';

        img.onerror = function() {
          const id = this.getAttribute('data-drive-id');
          const step = parseInt(this.dataset.tryStep || '0', 10);
          if (step === 0) {
            this.dataset.tryStep = '1';
            this.src = `https://lh3.googleusercontent.com/d/${id}=w800`;
          } else if (step === 1) {
            this.dataset.tryStep = '2';
            this.src = `https://drive.google.com/uc?export=view&id=${id}`;
          } else {
            this.onerror = null;
            this.src = `https://placehold.co/600x450/0c3559/ffffff?text=VLXD+Gia+Khanh`;
          }
        };
      });
    }

    function filterCategory(catId) {
      document.getElementById('searchInputDesktop').value = '';
      const mobInput = document.getElementById('searchInputMobile');
      if (mobInput) mobInput.value = '';
      renderCatalog(catId, '');
    }

    function filterProductsBySearch(val) {
      renderCatalog('ALL', val);
    }

    /* Điều khiển Banner Tự Trượt (2 Slide kích thước bằng nhau) */
    let currentSlideIndex = 0;
    let slideInterval = null;

    function showSlide(index) {
      const slides = document.querySelectorAll('.hero-slide');
      const dots = document.querySelectorAll('.slide-dot');
      if (!slides.length) return;

      currentSlideIndex = (index + slides.length) % slides.length;
      slides.forEach((sl, idx) => {
        if (idx === currentSlideIndex) {
          sl.classList.add('active');
        } else {
          sl.classList.remove('active');
        }
      });
      dots.forEach((dot, idx) => {
        dot.className = idx === currentSlideIndex
          ? 'slide-dot w-2.5 h-2.5 rounded-full bg-brand-amber transition'
          : 'slide-dot w-2.5 h-2.5 rounded-full bg-white/40 transition';
      });
    }

    function changeSlide(step) {
      showSlide(currentSlideIndex + step);
      resetSlideTimer();
    }

    function goToSlide(index) {
      showSlide(index);
      resetSlideTimer();
    }

    function resetSlideTimer() {
      if (slideInterval) clearInterval(slideInterval);
      slideInterval = setInterval(() => {
        showSlide(currentSlideIndex + 1);
      }, 5000);
    }

    /* Điều khiển Menu Điện Thoại & Tìm Kiếm Điện Thoại */
    function toggleMobileMenu() {
      const drawer = document.getElementById('mobileMenuDrawer');
      const overlay = document.getElementById('mobileMenuOverlay');
      const isClosed = drawer.classList.contains('-translate-x-full');
      if (isClosed) {
        drawer.classList.remove('-translate-x-full');
        overlay.classList.remove('hidden');
      } else {
        drawer.classList.add('-translate-x-full');
        overlay.classList.add('hidden');
      }
    }

    function toggleMobileSearch() {
      const bar = document.getElementById('mobileSearchBar');
      bar.classList.toggle('hidden');
    }

    /* Modal Chi tiết sản phẩm */
    function openProductModal(name, driveId, salePrice, oldPrice, discount, desc) {
      const modal = document.getElementById('productModal');
      document.getElementById('modalTitle').textContent = name;
      const modalImg = document.getElementById('modalImg');
      modalImg.setAttribute('data-drive-id', driveId);
      modalImg.dataset.tryStep = '0';
      modalImg.src = `https://drive.google.com/thumbnail?id=${driveId}&sz=w900`;
      document.getElementById('modalSalePrice').textContent = salePrice;
      document.getElementById('modalOldPrice').textContent = oldPrice;
      document.getElementById('modalDiscount').textContent = discount;
      document.getElementById('modalDesc').textContent = desc;
      document.getElementById('qNote').value = `Yêu cầu báo giá sản phẩm: ${name}`;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeProductModal() {
      const modal = document.getElementById('productModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    /* Xử lý Form Yêu cầu báo giá trang chủ */
    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const category = document.getElementById('qCategory').value;
      const address = document.getElementById('qAddress').value.trim();
      const msgBox = document.getElementById('quoteSuccessMsg');

      msgBox.innerHTML = `Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá hạng mục <strong>${category}</strong> ${address ? 'tại ' + address : ''} đã được ghi nhận. Cửa hàng VLXD Gia Khánh (Hotline/Zalo: <strong>0766 663 294</strong>) sẽ liên hệ báo giá tốt nhất ngay!`;
      msgBox.classList.remove('hidden');
      e.target.reset();
    }

    window.addEventListener('DOMContentLoaded', () => {
      renderCatalog('ALL', '');
      attachDriveImageFallbacks();
      resetSlideTimer();
    });
  </script>
</body>
</html>
