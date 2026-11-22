<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nhà Thầu Xây Dựng Tâm Tiến | Thiết Kế & Thi Công Trọn Gói Đà Nẵng - xaydungtamtien.com</title>
  <meta name="description" content="Nhà thầu xây dựng Tâm Tiến (xaydungtamtien.com) - Chuyên thiết kế kiến trúc, thi công phần thô, thi công hoàn thiện và xây nhà trọn gói uy tín tại TP Đà Nẵng. Hotline: 0906.440.277." />

  <!-- Meta Open Graph & Thumbnail chia sẻ link lấy từ Logo trang web -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="Nhà Thầu Xây Dựng Tâm Tiến - xaydungtamtien.com" />
  <meta property="og:title" content="Nhà Thầu Xây Dựng Tâm Tiến - Thiết Kế & Thi Công Trọn Gói TP Đà Nẵng" />
  <meta property="og:description" content="Uy tín - Chất lượng - Tiến độ. Chuyên xây dựng nhà phố, biệt thự, căn hộ, khách sạn, văn phòng tại TP Đà Nẵng. Hotline: 0906.440.277" />
  <meta property="og:url" content="https://xaydungtamtien.com" />
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1XIs9WpfN9nE45u8n0EkAHpeKHcLOOTO5=w1200" />
  <meta property="og:image:alt" content="Logo Nhà Thầu Xây Dựng Tâm Tiến" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Nhà Thầu Xây Dựng Tâm Tiến - xaydungtamtien.com" />
  <meta name="twitter:description" content="Nhà thầu thiết kế & thi công xây dựng trọn gói uy tín tại TP Đà Nẵng. Hotline: 0906.440.277" />
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1XIs9WpfN9nE45u8n0EkAHpeKHcLOOTO5=w1200" />
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1XIs9WpfN9nE45u8n0EkAHpeKHcLOOTO5=s128" />

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              dark: '#0E2A47',     /* Xanh Navy đậm chủ đạo ngành xây dựng */
              primary: '#164E87',  /* Xanh thương hiệu chuẩn Flatsome */
              accent: '#D97706',   /* Vàng cam điểm nhấn kiến trúc */
              gold: '#B45309',
              light: '#F4F7FA',
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Đảm bảo toàn trang không bao giờ tràn viền hay lệch sang phải */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      color: #1E293B;
      background-color: #FFFFFF;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng đúng 95% kích thước màn hình */
    .flatsome-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }
    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Ẩn thanh cuộn cho dải danh mục trượt ngang trên mobile */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }

    /* Tiêu đề Section phong cách Flatsome UX Builder */
    .section-title-bar {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      margin-bottom: 1.75rem;
    }
    .section-title-bar h2 {
      font-weight: 700;
      color: #0E2A47;
      text-transform: uppercase;
      letter-spacing: 0.02em;
    }
    .section-divider {
      width: 56px;
      height: 3px;
      background: #D97706;
      border-radius: 9999px;
      margin-top: 0.6rem;
    }

    /* Menu Dropdown mượt mà kiểu Flatsome */
    .nav-dropdown-wrap {
      position: relative;
    }
    .nav-dropdown-menu {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
    }
    .nav-dropdown-wrap:hover .nav-dropdown-menu {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Banner Slider 2 ảnh kích thước bằng nhau tuyệt đối */
    .hero-slider-viewport {
      position: relative;
      width: 100%;
      overflow: hidden;
      border-radius: 12px;
    }
    .hero-slider-track {
      display: flex;
      width: 200%;
      transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
    }
    .hero-slide {
      width: 50%;
      flex-shrink: 0;
      position: relative;
      min-height: 330px;
      display: flex;
      align-items: center;
    }
    @media (min-width: 640px) {
      .hero-slide {
        min-height: 390px;
      }
    }
    @media (min-width: 1024px) {
      .hero-slide {
        min-height: 460px;
      }
    }

    /* Hiệu ứng rung nhẹ nút Hotline nổi bật */
    @keyframes phonePulse {
      0%, 100% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.55); }
      70% { box-shadow: 0 0 0 12px rgba(220, 38, 38, 0); }
    }
    .hotline-pulse {
      animation: phonePulse 2s infinite;
    }

    /* Đảm bảo tên sản phẩm / dự án không bao giờ bị cắt chữ hoặc tràn khung */
    .card-title-safe {
      word-break: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      line-height: 1.4;
    }
  </style>
</head>
<body class="bg-white text-slate-800 antialiased">

  <!-- ==================== TOPBAR THÔNG TIN MỎNG (FLATSOME STYLE) ==================== -->
  <div class="bg-brand-dark text-white text-xs py-2 border-b border-white/10">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-brand-accent"></i>
          <span>TP Đà Nẵng</span>
        </span>
        <span class="hidden sm:inline text-white/30">|</span>
        <a href="tel:0906440277" class="inline-flex items-center gap-1.5 hover:text-brand-accent transition">
          <i class="fa-solid fa-phone text-brand-accent"></i>
          <span>0906.440.277</span>
        </a>
        <span class="hidden md:inline text-white/30">|</span>
        <span class="hidden md:inline-flex items-center gap-1.5">
          <i class="fa-solid fa-globe text-brand-accent"></i>
          <span>xaydungtamtien.com</span>
        </span>
      </div>
      <div class="flex items-center gap-3">
        <a href="https://www.facebook.com/profile.php?id=100064749650010" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 hover:text-brand-accent transition">
          <i class="fa-brands fa-facebook"></i>
          <span class="hidden sm:inline">Fanpage Tâm Tiến</span>
        </a>
        <span class="text-white/30">|</span>
        <a href="https://zalo.me/0906440277" target="_blank" rel="noopener noreferrer" class="hover:text-brand-accent transition font-medium">
          Zalo Tư Vấn
        </a>
      </div>
    </div>
  </div>

  <!-- ==================== HEADER CHÍNH (KHÔNG CÓ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ==================== -->
  <header class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm w-full">
    <div class="flatsome-container flex items-center justify-between gap-3 py-2.5">
      <!-- Logo gọn nhỏ -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0">
        <img
          src="https://lh3.googleusercontent.com/d/1XIs9WpfN9nE45u8n0EkAHpeKHcLOOTO5=s300"
          alt="Logo Nhà Thầu Xây Dựng Tâm Tiến"
          class="h-10 sm:h-11 w-auto max-w-[130px] object-contain rounded"
          onerror="handleImgError(this, '1XIs9WpfN9nE45u8n0EkAHpeKHcLOOTO5', 'TÂM TIẾN')"
        />
        <div class="leading-tight">
          <span class="block text-sm sm:text-[15px] font-extrabold text-brand-dark tracking-tight whitespace-nowrap">XÂY DỰNG TÂM TIẾN</span>
          <span class="block text-[11px] text-slate-500 font-medium whitespace-nowrap">xaydungtamtien.com</span>
        </div>
      </a>

      <!-- Menu trên máy tính: chữ nhỏ gọn, từng tên danh mục viết liền 1 hàng không xuống dòng -->
      <nav aria-label="Menu chính" class="hidden lg:flex flex-wrap items-center justify-end gap-x-4 xl:gap-x-6 gap-y-1.5">
        <a href="#trang-chu" class="whitespace-nowrap text-[12.5px] xl:text-[13.5px] font-semibold text-brand-dark hover:text-brand-accent transition py-1">
          Trang chủ
        </a>
        <a href="#gioi-thieu" class="whitespace-nowrap text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-accent transition py-1">
          Giới thiệu
        </a>

        <!-- Dropdown Công trình thực tế -->
        <div class="nav-dropdown-wrap py-1">
          <a href="#cong-trinh-thuc-te" class="whitespace-nowrap text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-accent transition inline-flex items-center gap-1">
            <span>Công trình thực tế</span>
            <i class="fa-solid fa-chevron-down text-[10px]"></i>
          </a>
          <div class="nav-dropdown-menu absolute left-0 top-full pt-2 w-56 z-50">
            <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-2 flex flex-col">
              <a href="#du-an-da-nang" onclick="filterProjects('khach-san')" class="px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Khách sạn – Căn hộ – Phòng trọ</a>
              <a href="#du-an-da-nang" onclick="filterProjects('biet-thu')" class="px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Biệt thự</a>
              <a href="#du-an-da-nang" onclick="filterProjects('nha-pho')" class="px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Nhà phố</a>
              <a href="#du-an-da-nang" onclick="filterProjects('van-phong')" class="px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Văn phòng</a>
            </div>
          </div>
        </div>

        <!-- Dropdown Lĩnh vực hoạt động -->
        <div class="nav-dropdown-wrap py-1">
          <a href="#linh-vuc" class="whitespace-nowrap text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-accent transition inline-flex items-center gap-1">
            <span>Lĩnh vực hoạt động</span>
            <i class="fa-solid fa-chevron-down text-[10px]"></i>
          </a>
          <div class="nav-dropdown-menu absolute left-0 top-full pt-2 w-56 z-50">
            <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-2 flex flex-col">
              <a href="#cong-trinh-thuc-te" onclick="filterProducts('thiet-ke')" class="px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Thiết kế Kiến trúc – Nội thất</a>
              <a href="#cong-trinh-thuc-te" onclick="filterProducts('phan-tho')" class="px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Thi công phần thô</a>
              <a href="#cong-trinh-thuc-te" onclick="filterProducts('hoan-thien')" class="px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Thi công hoàn thiện</a>
              <a href="#cong-trinh-thuc-te" onclick="filterProducts('tron-goi')" class="px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Thi công trọn gói</a>
            </div>
          </div>
        </div>

        <a href="#du-an-da-nang" class="whitespace-nowrap text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-accent transition py-1">
          Dự án Đà Nẵng
        </a>
        <a href="#bao-gia" class="whitespace-nowrap text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-accent transition py-1">
          Báo giá
        </a>
        <a href="#tin-tuc" class="whitespace-nowrap text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-accent transition py-1">
          Tin tức
        </a>
        <a href="#doi-tac" class="whitespace-nowrap text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-accent transition py-1">
          Đối tác
        </a>
        <a href="#lien-he" class="whitespace-nowrap text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-accent transition py-1">
          Liên hệ
        </a>
      </nav>

      <!-- Nút mở menu trên điện thoại & máy tính bảng -->
      <button
        id="mobileMenuBtn"
        type="button"
        aria-label="Mở danh mục"
        class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-dark hover:bg-brand-light transition shrink-0"
      >
        <i class="fa-solid fa-bars text-lg"></i>
      </button>
    </div>

    <!-- Drawer Menu cho Mobile -->
    <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg w-full">
      <div class="flatsome-container py-3 flex flex-col divide-y divide-slate-100">
        <a href="#trang-chu" onclick="closeMobileMenu()" class="py-2.5 text-sm font-semibold text-brand-dark">Trang chủ</a>
        <a href="#gioi-thieu" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-slate-700">Giới thiệu</a>
        <a href="#linh-vuc" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-slate-700">Lĩnh vực hoạt động</a>
        <a href="#cong-trinh-thuc-te" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-slate-700">Thi công thực tế &amp; Sản phẩm</a>
        <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-slate-700">Dự án tại Đà Nẵng</a>
        <a href="#bao-gia" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-slate-700">Yêu cầu báo giá</a>
        <a href="#tin-tuc" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-slate-700">Tin tức &amp; Bài viết</a>
        <a href="#doi-tac" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-slate-700">Đối tác tiêu biểu</a>
        <a href="#lien-he" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-slate-700">Liên hệ &amp; Bản đồ</a>
      </div>
    </div>
  </header>

  <!-- ==================== BANNER SLIDER 2 ẢNH TỰ TRƯỢT CHUYÊN NGHIỆP ==================== -->
  <!-- Thiết kế chữ cách xa viền ảnh banner, hình ảnh và chữ nằm gọn bên trong banner trên cả mobile và desktop -->
  <section id="trang-chu" class="pt-3 sm:pt-4 pb-6 bg-slate-50">
    <div class="flatsome-container">
      <div class="hero-slider-viewport shadow-md bg-brand-dark">
        <div id="heroSliderTrack" class="hero-slider-track">

          <!-- BANNER 1 -->
          <div class="hero-slide">
            <!-- Ảnh nền công trình thực tế -->
            <img
              src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w1400"
              alt="Nhà thầu xây dựng Tâm Tiến Đà Nẵng"
              class="absolute inset-0 w-full h-full object-cover"
              onerror="handleImgError(this, '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv', 'XÂY DỰNG TÂM TIẾN')"
            />
            <!-- Lớp phủ chuyển sắc đảm bảo chữ nổi bật rõ ràng -->
            <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/95 via-brand-dark/85 to-brand-dark/55"></div>

            <!-- Vùng nội dung đệm lớn, cách xa 4 viền banner và tránh hoàn toàn nút mũi tên -->
            <div class="relative z-10 w-full px-10 sm:px-14 md:px-20 lg:px-24 py-10 sm:py-12 md:py-14">
              <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                <div class="lg:col-span-7 text-white space-y-3 sm:space-y-4">
                  <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-amber-400">
                    NHÀ THẦU XÂY DỰNG TÂM TIẾN – TP ĐÀ NẴNG
                  </p>
                  <h1 class="text-xl sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug">
                    Thiết Kế &amp; Thi Công Xây Dựng Trọn Gói Chuyên Nghiệp
                  </h1>
                  <p class="text-xs sm:text-sm md:text-[15px] text-slate-200 leading-relaxed max-w-xl">
                    Đặt chữ Tâm lên hàng đầu trong từng công trình nhà phố, biệt thự, căn hộ, khách sạn tại Đà Nẵng. Cam kết đúng kỹ thuật, đúng tiến độ và chi phí minh bạch.
                  </p>
                  <div class="pt-1 flex flex-wrap items-center gap-3">
                    <a href="#bao-gia" class="inline-flex items-center gap-2 bg-brand-accent hover:bg-amber-700 text-white text-xs sm:text-sm font-semibold px-4 sm:px-5 py-2.5 rounded-lg transition shadow">
                      <span>Nhận báo giá miễn phí</span>
                      <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                    <a href="#du-an-da-nang" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold px-4 sm:px-5 py-2.5 rounded-lg transition">
                      <span>Xem dự án Đà Nẵng</span>
                    </a>
                  </div>
                </div>
                <!-- Khung ảnh thực tế thu gọn nằm hoàn toàn trong banner (hiện từ màn hình lớn) -->
                <div class="hidden lg:block lg:col-span-5">
                  <div class="rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl aspect-[16/10] bg-slate-900">
                    <img
                      src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1000"
                      alt="Công trình tiêu biểu Tâm Tiến tại Đà Nẵng"
                      class="w-full h-full object-cover"
                      onerror="handleImgError(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'CÔNG TRÌNH ĐÀ NẴNG')"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- BANNER 2 -->
          <div class="hero-slide">
            <!-- Ảnh nền công trình thực tế số 2 -->
            <img
              src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t=w1400"
              alt="Thi công phần thô và hoàn thiện Tâm Tiến"
              class="absolute inset-0 w-full h-full object-cover"
              onerror="handleImgError(this, '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t', 'THI CÔNG TRỌN GÓI')"
            />
            <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/95 via-brand-dark/85 to-brand-dark/55"></div>

            <!-- Vùng nội dung đệm lớn, đồng nhất tuyệt đối với Banner 1 -->
            <div class="relative z-10 w-full px-10 sm:px-14 md:px-20 lg:px-24 py-10 sm:py-12 md:py-14">
              <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                <div class="lg:col-span-7 text-white space-y-3 sm:space-y-4">
                  <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-amber-400">
                    AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – BỀN VỮNG
                  </p>
                  <h2 class="text-xl sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug">
                    Kiến Tạo Tổ Ấm Bền Vững Với Đội Ngũ Kỹ Sư Giàu Kinh Nghiệm
                  </h2>
                  <p class="text-xs sm:text-sm md:text-[15px] text-slate-200 leading-relaxed max-w-xl">
                    Thi công phần thô, hoàn thiện nội ngoại thất và cải tạo công trình trọn gói tại TP Đà Nẵng. Bảo hành kết cấu dài hạn, hỗ trợ tư vấn 24/7 qua Hotline 0906.440.277.
                  </p>
                  <div class="pt-1 flex flex-wrap items-center gap-3">
                    <a href="#cong-trinh-thuc-te" class="inline-flex items-center gap-2 bg-brand-accent hover:bg-amber-700 text-white text-xs sm:text-sm font-semibold px-4 sm:px-5 py-2.5 rounded-lg transition shadow">
                      <span>Xem công trình thực tế</span>
                      <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                    <a href="tel:0906440277" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold px-4 sm:px-5 py-2.5 rounded-lg transition">
                      <i class="fa-solid fa-phone text-xs"></i>
                      <span>0906.440.277</span>
                    </a>
                  </div>
                </div>
                <div class="hidden lg:block lg:col-span-5">
                  <div class="rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl aspect-[16/10] bg-slate-900">
                    <img
                      src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w1000"
                      alt="Biệt thự nhà phố thi công tại Đà Nẵng"
                      class="w-full h-full object-cover"
                      onerror="handleImgError(this, '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff', 'THI CÔNG THỰC TẾ')"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút chuyển slide gọn nhỏ sát mép ngoài vùng đệm chữ -->
        <button
          type="button"
          onclick="moveSlide(-1)"
          aria-label="Banner trước"
          class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-brand-accent text-white flex items-center justify-center transition"
        >
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button
          type="button"
          onclick="moveSlide(1)"
          aria-label="Banner tiếp theo"
          class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-brand-accent text-white flex items-center justify-center transition"
        >
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm chỉ báo 2 slide nằm gọn ở mép đáy -->
        <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" onclick="goToSlide(0)" id="dot-0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-brand-accent transition-all"></button>
          <button type="button" onclick="goToSlide(1)" id="dot-1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== DANH MỤC DỊCH VỤ TIÊU BIỂU (THEO WEB MẪU TÍN TRƯỜNG THỊNH) ==================== -->
  <section id="linh-vuc" class="py-10 sm:py-12 bg-white">
    <div class="flatsome-container">
      <div class="section-title-bar">
        <h2 class="text-lg sm:text-2xl">Dịch Vụ Tiêu Biểu</h2>
        <div class="section-divider"></div>
      </div>

      <!-- Lưới 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <!-- Dịch vụ 1 -->
        <a href="#cong-trinh-thuc-te" onclick="filterProducts('thiet-ke')" class="group block bg-brand-light hover:bg-brand-dark rounded-xl p-4 sm:p-6 text-center border border-slate-200/80 transition duration-300 shadow-sm">
          <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-white text-brand-primary group-hover:bg-brand-accent group-hover:text-white flex items-center justify-center text-xl sm:text-2xl shadow-sm transition">
            <i class="fa-solid fa-compass-drafting"></i>
          </div>
          <h3 class="text-xs sm:text-sm font-bold text-brand-dark group-hover:text-white uppercase card-title-safe">
            Thiết Kế Kiến Trúc – Nội Thất
          </h3>
          <p class="mt-1.5 text-[11px] sm:text-xs text-slate-600 group-hover:text-slate-200 leading-relaxed">
            Hồ sơ bản vẽ 2D, phối cảnh 3D tối ưu công năng và thẩm mỹ hiện đại.
          </p>
        </a>

        <!-- Dịch vụ 2 -->
        <a href="#cong-trinh-thuc-te" onclick="filterProducts('phan-tho')" class="group block bg-brand-light hover:bg-brand-dark rounded-xl p-4 sm:p-6 text-center border border-slate-200/80 transition duration-300 shadow-sm">
          <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-white text-brand-primary group-hover:bg-brand-accent group-hover:text-white flex items-center justify-center text-xl sm:text-2xl shadow-sm transition">
            <i class="fa-solid fa-trowel-bricks"></i>
          </div>
          <h3 class="text-xs sm:text-sm font-bold text-brand-dark group-hover:text-white uppercase card-title-safe">
            Thi Công Phần Thô
          </h3>
          <p class="mt-1.5 text-[11px] sm:text-xs text-slate-600 group-hover:text-slate-200 leading-relaxed">
            Kết cấu móng, cột, dầm, sàn chuẩn kỹ thuật, vật tư chính hãng.
          </p>
        </a>

        <!-- Dịch vụ 3 -->
        <a href="#cong-trinh-thuc-te" onclick="filterProducts('hoan-thien')" class="group block bg-brand-light hover:bg-brand-dark rounded-xl p-4 sm:p-6 text-center border border-slate-200/80 transition duration-300 shadow-sm">
          <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-white text-brand-primary group-hover:bg-brand-accent group-hover:text-white flex items-center justify-center text-xl sm:text-2xl shadow-sm transition">
            <i class="fa-solid fa-paint-roller"></i>
          </div>
          <h3 class="text-xs sm:text-sm font-bold text-brand-dark group-hover:text-white uppercase card-title-safe">
            Thi Công Hoàn Thiện
          </h3>
          <p class="mt-1.5 text-[11px] sm:text-xs text-slate-600 group-hover:text-slate-200 leading-relaxed">
            Ốp lát, sơn nước, chống thấm, điện nước, cửa nhôm kính tinh xảo.
          </p>
        </a>

        <!-- Dịch vụ 4 -->
        <a href="#cong-trinh-thuc-te" onclick="filterProducts('tron-goi')" class="group block bg-brand-light hover:bg-brand-dark rounded-xl p-4 sm:p-6 text-center border border-slate-200/80 transition duration-300 shadow-sm">
          <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-white text-brand-primary group-hover:bg-brand-accent group-hover:text-white flex items-center justify-center text-xl sm:text-2xl shadow-sm transition">
            <i class="fa-solid fa-house-chimney"></i>
          </div>
          <h3 class="text-xs sm:text-sm font-bold text-brand-dark group-hover:text-white uppercase card-title-safe">
            Thi Công Trọn Gói
          </h3>
          <p class="mt-1.5 text-[11px] sm:text-xs text-slate-600 group-hover:text-slate-200 leading-relaxed">
            Chìa khóa trao tay không phát sinh chi phí, bảo hành dài hạn.
          </p>
        </a>
      </div>
    </div>
  </section>

  <!-- ==================== GIỚI THIỆU NHÀ THẦU & THẾ MẠNH (THEO WEB MẪU) ==================== -->
  <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-light border-y border-slate-200/70">
    <div class="flatsome-container">
      <!-- Giới thiệu công ty -->
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-12">
        <div class="lg:col-span-5">
          <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 bg-white aspect-[4/3]">
            <img
              src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1000"
              alt="Đội ngũ thi công Nhà thầu xây dựng Tâm Tiến"
              class="w-full h-full object-cover"
              onerror="handleImgError(this, '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz', 'NHÀ THẦU TÂM TIẾN')"
            />
          </div>
        </div>
        <div class="lg:col-span-7 space-y-4">
          <div>
            <p class="text-xs font-bold uppercase tracking-wider text-brand-accent">Về chúng tôi</p>
            <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-dark mt-1">
              NHÀ THẦU XÂY DỰNG TÂM TIẾN
            </h2>
            <div class="w-14 h-1 bg-brand-accent rounded-full mt-2.5"></div>
          </div>
          <p class="text-sm sm:text-[15px] text-slate-700 leading-relaxed">
            <strong>Nhà thầu xây dựng Tâm Tiến</strong> chuyên Thiết kế – Xây dựng – Hoàn thiện các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê, Văn phòng và Cải tạo sửa chữa tại khu vực <strong>TP Đà Nẵng</strong> và lân cận.
          </p>
          <p class="text-sm sm:text-[15px] text-slate-700 leading-relaxed">
            Với phương châm đặt chữ <strong>“TÂM”</strong> trong nghề lên hàng đầu, mỗi công trình do Tâm Tiến thực hiện đều đảm bảo nghiêm ngặt các tiêu chuẩn: <strong>AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – SỰ HÀI LÒNG CỦA KHÁCH HÀNG</strong>. Đội ngũ kỹ sư và thợ thi công lành nghề luôn đồng hành cùng chủ đầu tư từ khâu tư vấn ý tưởng, xin phép xây dựng đến bàn giao chìa khóa trao tay.
          </p>
          <div class="grid grid-cols-3 gap-3 pt-2">
            <div class="bg-white rounded-lg p-3 text-center border border-slate-200">
              <span class="block text-lg sm:text-2xl font-extrabold text-brand-primary">10+</span>
              <span class="block text-[11px] sm:text-xs text-slate-600 mt-0.5">Năm kinh nghiệm</span>
            </div>
            <div class="bg-white rounded-lg p-3 text-center border border-slate-200">
              <span class="block text-lg sm:text-2xl font-extrabold text-brand-primary">150+</span>
              <span class="block text-[11px] sm:text-xs text-slate-600 mt-0.5">Công trình bàn giao</span>
            </div>
            <div class="bg-white rounded-lg p-3 text-center border border-slate-200">
              <span class="block text-lg sm:text-2xl font-extrabold text-brand-primary">100%</span>
              <span class="block text-[11px] sm:text-xs text-slate-600 mt-0.5">Đúng tiến độ</span>
            </div>
          </div>
        </div>
      </div>

      <!-- 6 Thế mạnh của chúng tôi (chuẩn web mẫu tintruongthinh.com) -->
      <div class="section-title-bar">
        <h2 class="text-lg sm:text-2xl">Thế Mạnh Của Chúng Tôi</h2>
        <div class="section-divider"></div>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
        <div class="bg-white rounded-xl p-5 border border-slate-200/80 shadow-sm flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0 text-lg">
            <i class="fa-solid fa-helmet-safety"></i>
          </div>
          <div>
            <h3 class="text-sm font-bold text-brand-dark">Đội ngũ kỹ sư, thợ lành nghề</h3>
            <p class="text-xs text-slate-600 mt-1 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư giám sát và công nhân nhiều năm kinh nghiệm thực chiến tại Đà Nẵng.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-slate-200/80 shadow-sm flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0 text-lg">
            <i class="fa-solid fa-layer-group"></i>
          </div>
          <div>
            <h3 class="text-sm font-bold text-brand-dark">Cập nhật xu hướng hiện đại</h3>
            <p class="text-xs text-slate-600 mt-1 leading-relaxed">Áp dụng giải pháp thiết kế tối ưu, vật liệu chất lượng cao và kỹ thuật thi công tiên tiến nhất.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-slate-200/80 shadow-sm flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0 text-lg">
            <i class="fa-solid fa-clipboard-check"></i>
          </div>
          <div>
            <h3 class="text-sm font-bold text-brand-dark">Giám sát tiến độ chuẩn xác</h3>
            <p class="text-xs text-slate-600 mt-1 leading-relaxed">Báo cáo hình ảnh thi công hằng ngày giúp chủ nhà dễ dàng theo dõi sát sao công trình từ xa.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-slate-200/80 shadow-sm flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0 text-lg">
            <i class="fa-solid fa-shield-halved"></i>
          </div>
          <div>
            <h3 class="text-sm font-bold text-brand-dark">Bảo hành công trình lâu dài</h3>
            <p class="text-xs text-slate-600 mt-1 leading-relaxed">Chính sách bảo hành kết cấu và chống thấm rõ ràng, hỗ trợ bảo trì nhanh chóng khi khách hàng cần.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-slate-200/80 shadow-sm flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0 text-lg">
            <i class="fa-solid fa-file-invoice-dollar"></i>
          </div>
          <div>
            <h3 class="text-sm font-bold text-brand-dark">Chi phí hợp lý, minh bạch</h3>
            <p class="text-xs text-slate-600 mt-1 leading-relaxed">Dự toán chi tiết từng hạng mục vật tư, tối ưu ngân sách và cam kết không phát sinh chi phí ẩn.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-slate-200/80 shadow-sm flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0 text-lg">
            <i class="fa-solid fa-headset"></i>
          </div>
          <div>
            <h3 class="text-sm font-bold text-brand-dark">Hỗ trợ tư vấn miễn phí 24/7</h3>
            <p class="text-xs text-slate-600 mt-1 leading-relaxed">Luôn sẵn sàng khảo sát mặt bằng, tư vấn phương án thi công và báo giá tận tâm qua Hotline 0906.440.277.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== SẢN PHẨM & HẠNG MỤC THI CÔNG THỰC TẾ (9 ẢNH THỰC TẾ) ==================== -->
  <!-- Chữ danh mục nhỏ gọn, 1 hàng trên desktop, 2 cột trên mobile, không nhãn dán đè ảnh -->
  <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-white">
    <div class="flatsome-container">
      <div class="section-title-bar">
        <h2 class="text-lg sm:text-2xl">Sản Phẩm &amp; Hạng Mục Thi Công Thực Tế</h2>
        <div class="section-divider"></div>
      </div>

      <!-- Thanh danh mục lọc: tối ưu đẹp trên máy tính (1 hàng gọn) và trượt mượt trên mobile -->
      <div class="flex items-center justify-start md:justify-center gap-2 overflow-x-auto no-scrollbar pb-2 mb-6">
        <button type="button" onclick="filterProducts('all')" data-prod-tab="all" class="prod-tab active whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-dark text-white transition shrink-0">
          Tất cả hạng mục
        </button>
        <button type="button" onclick="filterProducts('phan-tho')" data-prod-tab="phan-tho" class="prod-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition shrink-0">
          Thi công phần thô
        </button>
        <button type="button" onclick="filterProducts('hoan-thien')" data-prod-tab="hoan-thien" class="prod-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition shrink-0">
          Thi công hoàn thiện
        </button>
        <button type="button" onclick="filterProducts('tron-goi')" data-prod-tab="tron-goi" class="prod-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition shrink-0">
          Thi công trọn gói
        </button>
        <button type="button" onclick="filterProducts('thiet-ke')" data-prod-tab="thiet-ke" class="prod-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition shrink-0">
          Thiết kế &amp; Cải tạo
        </button>
      </div>

      <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột trên desktop -->
      <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- Dữ liệu được render tự động từ mảng 9 ảnh thực tế trong JS -->
      </div>
    </div>
  </section>

  <!-- ==================== DỰ ÁN TIÊU BIỂU TẠI TP ĐÀ NẴNG (10 ẢNH DỰ ÁN ĐÀ NẴNG) ==================== -->
  <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-light border-y border-slate-200/70">
    <div class="flatsome-container">
      <div class="section-title-bar">
        <h2 class="text-lg sm:text-2xl">Các Dự Án Tiêu Biểu Tại Đà Nẵng</h2>
        <div class="section-divider"></div>
      </div>

      <!-- Danh mục dự án (giống mẫu Tín Trường Thịnh): chữ nhỏ gọn, không xuống dòng -->
      <div class="flex items-center justify-start md:justify-center gap-2 overflow-x-auto no-scrollbar pb-2 mb-6">
        <button type="button" onclick="filterProjects('all')" data-proj-tab="all" class="proj-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-dark text-white transition shrink-0">
          Tất cả dự án
        </button>
        <button type="button" onclick="filterProjects('nha-pho')" data-proj-tab="nha-pho" class="proj-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:bg-slate-100 transition shrink-0">
          Nhà phố
        </button>
        <button type="button" onclick="filterProjects('biet-thu')" data-proj-tab="biet-thu" class="proj-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:bg-slate-100 transition shrink-0">
          Biệt thự
        </button>
        <button type="button" onclick="filterProjects('khach-san')" data-proj-tab="khach-san" class="proj-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:bg-slate-100 transition shrink-0">
          Khách sạn – Căn hộ
        </button>
        <button type="button" onclick="filterProjects('van-phong')" data-proj-tab="van-phong" class="proj-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:bg-slate-100 transition shrink-0">
          Văn phòng – Cải tạo
        </button>
      </div>

      <!-- Lưới dự án: 2 cột trên điện thoại, 4 cột trên desktop -->
      <div id="projectGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-3 sm:gap-4">
        <!-- Dữ liệu được render tự động từ mảng 10 ảnh dự án Đà Nẵng trong JS -->
      </div>
    </div>
  </section>

  <!-- ==================== FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ ==================== -->
  <section id="bao-gia" class="py-10 sm:py-14 bg-brand-dark text-white">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
        <!-- Cột trái: Thông tin tư vấn & Cam kết báo giá -->
        <div class="lg:col-span-5 space-y-4">
          <p class="text-xs font-bold uppercase tracking-widest text-amber-400">Miễn phí tư vấn &amp; dự toán</p>
          <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold leading-snug">
            Đăng Ký Nhận Báo Giá Xây Dựng Chi Tiết Tại Đà Nẵng
          </h2>
          <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
            Quý khách vui lòng để lại thông tin loại công trình và ngân sách dự kiến. Kỹ sư của <strong>Nhà thầu xây dựng Tâm Tiến</strong> sẽ liên hệ khảo sát thực tế và gửi bảng dự toán chi tiết hoàn toàn miễn phí.
          </p>
          <div class="space-y-2.5 pt-2 text-xs sm:text-sm text-slate-100">
            <div class="flex items-center gap-2.5">
              <i class="fa-solid fa-check-circle text-amber-400"></i>
              <span>Báo giá thiết kế kiến trúc – nội thất chuẩn xác</span>
            </div>
            <div class="flex items-center gap-2.5">
              <i class="fa-solid fa-check-circle text-amber-400"></i>
              <span>Báo giá thi công phần thô &amp; nhân công hoàn thiện</span>
            </div>
            <div class="flex items-center gap-2.5">
              <i class="fa-solid fa-check-circle text-amber-400"></i>
              <span>Báo giá xây nhà trọn gói chìa khóa trao tay</span>
            </div>
            <div class="flex items-center gap-2.5">
              <i class="fa-solid fa-phone-volume text-amber-400"></i>
              <span>Hotline hỗ trợ nhanh: <a href="tel:0906440277" class="font-bold text-amber-300 underline">0906.440.277</a></span>
            </div>
          </div>
        </div>

        <!-- Cột phải: Form báo giá (chuẩn trường dữ liệu mẫu Tín Trường Thịnh) -->
        <div class="lg:col-span-7">
          <form id="quoteForm" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl space-y-4">
            <h3 class="text-base sm:text-lg font-bold text-brand-dark border-b border-slate-100 pb-3">
              Yêu Cầu Tư Vấn &amp; Báo Giá
            </h3>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                <input id="qName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-primary focus:ring-1 focus:ring-brand-primary" />
              </div>
              <div>
                <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại *</label>
                <input id="qPhone" type="tel" required placeholder="VD: 0906.440.277" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-primary focus:ring-1 focus:ring-brand-primary" />
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="qType" class="block text-xs font-semibold text-slate-700 mb-1">Loại công trình</label>
                <select id="qType" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:outline-none focus:border-brand-primary">
                  <option value="Nhà phố">Nhà phố</option>
                  <option value="Biệt thự">Biệt thự</option>
                  <option value="Khách sạn - Căn hộ - Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                  <option value="Văn phòng">Văn phòng / Mặt bằng kinh doanh</option>
                  <option value="Cải tạo sửa chữa">Cải tạo – Sửa chữa trọn gói</option>
                  <option value="Chưa xác định">Chưa xác định</option>
                </select>
              </div>
              <div>
                <label for="qBudget" class="block text-xs font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                <select id="qBudget" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:outline-none focus:border-brand-primary">
                  <option value="Chưa xác định">Chưa xác định</option>
                  <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                  <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                  <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                  <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                  <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                </select>
              </div>
            </div>

            <div>
              <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1">Diện tích đất / Nội dung yêu cầu</label>
              <textarea id="qNote" rows="3" placeholder="VD: Đất 5x20m tại Hòa Xuân, dự kiến xây nhà 3 tầng trọn gói..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-primary focus:ring-1 focus:ring-brand-primary"></textarea>
            </div>

            <div id="quoteFeedback" class="hidden rounded-lg p-3 text-xs sm:text-sm font-medium"></div>

            <button type="submit" class="w-full bg-brand-accent hover:bg-amber-700 text-white font-bold text-sm py-3 rounded-lg transition shadow-md flex items-center justify-center gap-2">
              <i class="fa-solid fa-paper-plane"></i>
              <span>Gửi Yêu Cầu Báo Giá Ngay</span>
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ ==================== -->
  <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
    <div class="flatsome-container">
      <div class="section-title-bar">
        <h2 class="text-lg sm:text-2xl">Tin Tức &amp; Kinh Nghiệm Xây Dựng</h2>
        <div class="section-divider"></div>
      </div>

      <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div id="newsGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <!-- Render tự động từ mảng bài viết chuẩn ngành xây dựng -->
      </div>
    </div>
  </section>

  <!-- ==================== DANH MỤC CÁC ĐỐI TÁC ==================== -->
  <section id="doi-tac" class="py-10 sm:py-12 bg-brand-light border-y border-slate-200/70">
    <div class="flatsome-container">
      <div class="section-title-bar">
        <h2 class="text-lg sm:text-2xl">Đối Tác Vật Tư &amp; Xây Dựng Tiêu Biểu</h2>
        <div class="section-divider"></div>
      </div>

      <!-- Lưới logo/thương hiệu đối tác gọn đẹp, dễ dựng lại bằng Row/Col trên UX Builder -->
      <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-3 sm:gap-4">
        <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-primary transition">
          <span class="text-sm sm:text-base font-extrabold text-brand-primary tracking-wide">HÒA PHÁT</span>
          <span class="text-[11px] text-slate-500 mt-1">Thép xây dựng</span>
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-primary transition">
          <span class="text-sm sm:text-base font-extrabold text-emerald-700 tracking-wide">SÔNG GIANH</span>
          <span class="text-[11px] text-slate-500 mt-1">Xi măng cao cấp</span>
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-primary transition">
          <span class="text-sm sm:text-base font-extrabold text-blue-700 tracking-wide">DULUX</span>
          <span class="text-[11px] text-slate-500 mt-1">Sơn nội ngoại thất</span>
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-primary transition">
          <span class="text-sm sm:text-base font-extrabold text-amber-600 tracking-wide">JOTUN</span>
          <span class="text-[11px] text-slate-500 mt-1">Sơn bảo vệ công trình</span>
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-primary transition">
          <span class="text-sm sm:text-base font-extrabold text-red-700 tracking-wide">CADIVI</span>
          <span class="text-[11px] text-slate-500 mt-1">Dây cáp điện</span>
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-primary transition">
          <span class="text-sm sm:text-base font-extrabold text-slate-800 tracking-wide">VIGLACERA</span>
          <span class="text-[11px] text-slate-500 mt-1">Gạch ốp lát &amp; TBVS</span>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== FANPAGE FACEBOOK & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ ==================== -->
  <section id="lien-he" class="py-10 sm:py-14 bg-white">
    <div class="flatsome-container">
      <div class="section-title-bar">
        <h2 class="text-lg sm:text-2xl">Kết Nối Fanpage &amp; Bản Đồ TP Đà Nẵng</h2>
        <div class="section-divider"></div>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
        <!-- Cột trái: Fanpage Facebook Nhà Thầu Xây Dựng Tâm Tiến -->
        <div class="lg:col-span-5 flex flex-col bg-brand-light rounded-xl border border-slate-200 overflow-hidden shadow-sm">
          <div class="bg-brand-dark text-white px-5 py-3.5 flex items-center justify-between">
            <div class="flex items-center gap-2.5">
              <i class="fa-brands fa-facebook text-xl text-blue-400"></i>
              <span class="text-sm font-bold">Fanpage Chính Thức</span>
            </div>
            <a href="https://www.facebook.com/profile.php?id=100064749650010" target="_blank" rel="noopener noreferrer" class="text-xs text-amber-300 hover:underline font-medium">
              Mở Facebook <i class="fa-solid fa-arrow-up-right-from-square ml-1 text-[10px]"></i>
            </a>
          </div>

          <div class="p-4 sm:p-5 flex-1 flex flex-col justify-between space-y-4">
            <!-- Khung giới thiệu trực quan Fanpage luôn hiển thị đẹp ngay cả khi trình duyệt chặn iframe Facebook -->
            <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
              <div class="relative h-28 sm:h-32 bg-brand-dark">
                <img
                  src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w800"
                  alt="Ảnh bìa Fanpage Nhà thầu xây dựng Tâm Tiến"
                  class="w-full h-full object-cover opacity-80"
                  onerror="handleImgError(this, '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_', 'FANPAGE TÂM TIẾN')"
                />
              </div>
              <div class="p-4 flex items-center gap-3.5 -mt-8 relative z-10">
                <div class="w-16 h-16 rounded-xl bg-white p-1.5 shadow border border-slate-200 shrink-0 flex items-center justify-center">
                  <img
                    src="https://lh3.googleusercontent.com/d/1XIs9WpfN9nE45u8n0EkAHpeKHcLOOTO5=s200"
                    alt="Avatar Fanpage Tâm Tiến"
                    class="w-full h-full object-contain"
                    onerror="handleImgError(this, '1XIs9WpfN9nE45u8n0EkAHpeKHcLOOTO5', 'TT')"
                  />
                </div>
                <div class="pt-5 min-w-0">
                  <h3 class="text-sm sm:text-base font-bold text-brand-dark card-title-safe">Nhà Thầu Xây Dựng Tâm Tiến</h3>
                  <p class="text-xs text-slate-500">TP Đà Nẵng • Hotline: 0906.440.277</p>
                </div>
              </div>
              <div class="px-4 pb-4 space-y-3">
                <p class="text-xs text-slate-600 leading-relaxed">
                  Cập nhật liên tục tiến độ thi công thực tế, hình ảnh bàn giao nhà phố, biệt thự, căn hộ và kinh nghiệm xây nhà tại TP Đà Nẵng.
                </p>
                <div class="flex flex-wrap gap-2">
                  <a href="https://www.facebook.com/profile.php?id=100064749650010" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold py-2.5 px-3 rounded-lg transition">
                    <i class="fa-brands fa-facebook-f"></i>
                    <span>Theo dõi Fanpage</span>
                  </a>
                  <a href="https://zalo.me/0906440277" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-2 bg-brand-primary hover:bg-brand-dark text-white text-xs font-semibold py-2.5 px-3 rounded-lg transition">
                    <i class="fa-solid fa-comments"></i>
                    <span>Nhắn tin Zalo</span>
                  </a>
                </div>
              </div>
            </div>

            <!-- Nhúng plugin Facebook Page chính thức -->
            <div class="w-full overflow-hidden rounded-lg border border-slate-200 bg-white">
              <iframe
                title="Fanpage Nhà thầu xây dựng Tâm Tiến"
                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100064749650010&tabs=&width=500&height=130&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                width="100%"
                height="130"
                style="border:none;overflow:hidden;width:100%;max-width:100%;"
                scrolling="no"
                frameborder="0"
                allowfullscreen="true"
                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
              ></iframe>
            </div>
          </div>
        </div>

        <!-- Cột phải: Bản đồ Google Maps TP Đà Nẵng -->
        <div class="lg:col-span-7 flex flex-col bg-brand-light rounded-xl border border-slate-200 overflow-hidden shadow-sm">
          <div class="bg-brand-dark text-white px-5 py-3.5 flex items-center justify-between">
            <div class="flex items-center gap-2.5">
              <i class="fa-solid fa-map-location-dot text-lg text-amber-400"></i>
              <span class="text-sm font-bold">Bản Đồ Khu Vực Hoạt Động – TP Đà Nẵng</span>
            </div>
            <a href="https://maps.google.com/?q=TP+Da+Nang,+Vietnam" target="_blank" rel="noopener noreferrer" class="text-xs text-amber-300 hover:underline font-medium">
              Xem bản đồ lớn <i class="fa-solid fa-arrow-up-right-from-square ml-1 text-[10px]"></i>
            </a>
          </div>
          <div class="flex-1 min-h-[320px] sm:min-h-[380px] w-full bg-slate-200">
            <iframe
              title="Bản đồ Google Maps TP Đà Nẵng - Nhà thầu xây dựng Tâm Tiến"
              src="https://maps.google.com/maps?q=%C4%90%C3%A0%20N%E1%BA%B5ng,%20Vi%E1%BB%87t%20Nam&t=&z=12&ie=UTF8&iwloc=&output=embed"
              width="100%"
              height="100%"
              style="border:0; min-height: 360px; width: 100%; max-width: 100%; display: block;"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
            ></iframe>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== FOOTER CHUYÊN NGHIỆP (FLATSOME STYLE) ==================== -->
  <footer class="bg-brand-dark text-slate-300 pt-12 pb-20 lg:pb-8 border-t-4 border-brand-accent">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/10">
        <!-- Cột 1: Thông tin công ty -->
        <div class="space-y-3">
          <div class="flex items-center gap-2.5 bg-white/95 p-2 rounded-lg w-fit">
            <img
              src="https://lh3.googleusercontent.com/d/1XIs9WpfN9nE45u8n0EkAHpeKHcLOOTO5=s200"
              alt="Logo Xây Dựng Tâm Tiến"
              class="h-9 w-auto object-contain"
              onerror="handleImgError(this, '1XIs9WpfN9nE45u8n0EkAHpeKHcLOOTO5', 'TÂM TIẾN')"
            />
            <span class="text-xs font-extrabold text-brand-dark pr-1">XÂY DỰNG TÂM TIẾN</span>
          </div>
          <p class="text-xs leading-relaxed text-slate-300">
            Nhà thầu xây dựng uy tín tại TP Đà Nẵng, chuyên thiết kế kiến trúc – nội thất, thi công phần thô, hoàn thiện và xây nhà trọn gói.
          </p>
          <ul class="space-y-2 text-xs">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-amber-400 mt-0.5"></i>
              <span>Địa chỉ: TP Đà Nẵng, Việt Nam</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-phone text-amber-400"></i>
              <a href="tel:0906440277" class="hover:text-white font-semibold">Hotline / Zalo: 0906.440.277</a>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-globe text-amber-400"></i>
              <span>Website: xaydungtamtien.com</span>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div>
          <h3 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">Lĩnh Vực Hoạt Động</h3>
          <ul class="space-y-2 text-xs">
            <li><a href="#cong-trinh-thuc-te" onclick="filterProducts('thiet-ke')" class="hover:text-amber-400 transition">Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterProducts('phan-tho')" class="hover:text-amber-400 transition">Thi công phần thô nhà ở</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterProducts('hoan-thien')" class="hover:text-amber-400 transition">Thi công hoàn thiện công trình</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterProducts('tron-goi')" class="hover:text-amber-400 transition">Xây nhà trọn gói Đà Nẵng</a></li>
            <li><a href="#bao-gia" class="hover:text-amber-400 transition">Cải tạo – Sửa chữa nhà cũ</a></li>
          </ul>
        </div>

        <!-- Cột 3: Công trình & Dự án -->
        <div>
          <h3 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">Dự Án Tại Đà Nẵng</h3>
          <ul class="space-y-2 text-xs">
            <li><a href="#du-an-da-nang" onclick="filterProjects('nha-pho')" class="hover:text-amber-400 transition">Dự án Nhà phố hiện đại</a></li>
            <li><a href="#du-an-da-nang" onclick="filterProjects('biet-thu')" class="hover:text-amber-400 transition">Dự án Biệt thự sang trọng</a></li>
            <li><a href="#du-an-da-nang" onclick="filterProjects('khach-san')" class="hover:text-amber-400 transition">Dự án Khách sạn – Căn hộ</a></li>
            <li><a href="#du-an-da-nang" onclick="filterProjects('van-phong')" class="hover:text-amber-400 transition">Dự án Văn phòng – Cải tạo</a></li>
            <li><a href="#tin-tuc" class="hover:text-amber-400 transition">Cẩm nang xây dựng</a></li>
          </ul>
        </div>

        <!-- Cột 4: Kết nối nhanh -->
        <div>
          <h3 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">Kết Nối Với Tâm Tiến</h3>
          <p class="text-xs text-slate-300 leading-relaxed mb-3">
            Liên hệ trực tiếp để được kỹ sư tư vấn giải pháp thi công tối ưu và nhận bảng báo giá miễn phí ngay hôm nay.
          </p>
          <div class="flex items-center gap-2.5">
            <a href="https://www.facebook.com/profile.php?id=100064749650010" target="_blank" rel="noopener noreferrer" aria-label="Facebook" class="w-9 h-9 rounded-lg bg-[#1877F2] hover:opacity-90 text-white flex items-center justify-center transition">
              <i class="fa-brands fa-facebook-f"></i>
            </a>
            <a href="https://zalo.me/0906440277" target="_blank" rel="noopener noreferrer" aria-label="Zalo" class="h-9 px-3 rounded-lg bg-[#0068FF] hover:opacity-90 text-white text-xs font-bold flex items-center justify-center transition">
              Zalo
            </a>
            <a href="tel:0906440277" aria-label="Hotline" class="w-9 h-9 rounded-lg bg-red-600 hover:opacity-90 text-white flex items-center justify-center transition">
              <i class="fa-solid fa-phone"></i>
            </a>
          </div>
        </div>
      </div>

      <div class="pt-5 text-center text-xs text-slate-400">
        Copyright © 2026 <strong>Nhà Thầu Xây Dựng Tâm Tiến</strong> – <span class="text-slate-300">xaydungtamtien.com</span>. TP Đà Nẵng.
      </div>
    </div>
  </footer>

  <!-- ==================== CỤM NÚT LIÊN HỆ NỔI BẬT (ZALO - FACEBOOK - HOTLINE) ==================== -->
  <!-- Tương thích hoàn hảo trên máy tính (góc dưới phải) và điện thoại (thanh công cụ gọn ở đáy màn hình) -->
  <!-- Phiên bản Máy tính (Desktop) -->
  <div class="hidden lg:flex fixed right-4 bottom-6 z-50 flex-col items-end gap-2.5">
    <a
      href="https://www.facebook.com/profile.php?id=100064749650010"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center gap-2.5 bg-[#1877F2] hover:bg-blue-700 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition transform hover:-translate-y-0.5"
    >
      <i class="fa-brands fa-facebook-messenger text-lg"></i>
      <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
    </a>

    <a
      href="https://zalo.me/0906440277"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center gap-2.5 bg-[#0068FF] hover:bg-blue-600 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition transform hover:-translate-y-0.5"
    >
      <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center">Z</span>
      <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
    </a>

    <a
      href="tel:0906440277"
      class="hotline-pulse flex items-center gap-2.5 bg-red-600 hover:bg-red-700 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition transform hover:-translate-y-0.5"
    >
      <i class="fa-solid fa-phone-volume text-base"></i>
      <span class="text-xs font-bold whitespace-nowrap">0906.440.277</span>
    </a>
  </div>

  <!-- Phiên bản Điện thoại (Mobile Sticky Contact Bar - Không tràn viền, dễ chạm) -->
  <div class="lg:hidden fixed bottom-0 left-0 right-0 z-50 bg-white border-t border-slate-200 shadow-[0_-4px_12px_rgba(0,0,0,0.08)] px-2 py-2">
    <div class="grid grid-cols-3 gap-2 max-w-full">
      <a
        href="tel:0906440277"
        class="flex items-center justify-center gap-1.5 bg-red-600 active:bg-red-700 text-white text-xs font-bold py-2.5 px-2 rounded-lg shadow-sm"
      >
        <i class="fa-solid fa-phone-volume"></i>
        <span>Hotline</span>
      </a>
      <a
        href="https://zalo.me/0906440277"
        target="_blank"
        rel="noopener noreferrer"
        class="flex items-center justify-center gap-1.5 bg-[#0068FF] active:bg-blue-700 text-white text-xs font-bold py-2.5 px-2 rounded-lg shadow-sm"
      >
        <span class="w-4 h-4 rounded-full bg-white text-[#0068FF] font-extrabold text-[9px] flex items-center justify-center">Z</span>
        <span>Zalo</span>
      </a>
      <a
        href="https://www.facebook.com/profile.php?id=100064749650010"
        target="_blank"
        rel="noopener noreferrer"
        class="flex items-center justify-center gap-1.5 bg-[#1877F2] active:bg-blue-800 text-white text-xs font-bold py-2.5 px-2 rounded-lg shadow-sm"
      >
        <i class="fa-brands fa-facebook-f"></i>
        <span>Facebook</span>
      </a>
    </div>
  </div>

  <!-- ==================== MODAL XEM CHI TIẾT ẢNH / BÀI VIẾT (KHÔNG DÙNG ALERT) ==================== -->
  <div id="detailModal" class="fixed inset-0 z-[60] hidden items-center justify-center bg-black/70 p-3 sm:p-5">
    <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
      <button
        type="button"
        onclick="closeDetailModal()"
        aria-label="Đóng hộp thoại"
        class="sticky top-3 float-right mr-3 z-10 w-8 h-8 rounded-full bg-slate-900/75 hover:bg-brand-accent text-white flex items-center justify-center transition"
      >
        <i class="fa-solid fa-xmark"></i>
      </button>
      <div id="detailModalBody" class="p-4 sm:p-6"></div>
    </div>
  </div>

  <!-- ==================== JAVASCRIPT XỬ LÝ TƯƠNG TÁC ==================== -->
  <script>
    /**
     * Hàm xử lý lỗi tải ảnh Google Drive an toàn nhiều lớp:
     * Bước 1: Chuyển sang URL thumbnail của Google Drive
     * Bước 2: Nếu vẫn lỗi (do quyền chia sẻ/mạng), dùng ảnh placeholder đẹp
     */
    function handleImgError(img, driveId, labelText) {
      const step = parseInt(img.dataset.errStep || '0', 10);
      if (step === 0 && driveId) {
        img.dataset.errStep = '1';
        img.src = `https://drive.google.com/thumbnail?id=${driveId}&sz=w1000`;
      } else {
        img.onerror = null;
        const safeText = encodeURIComponent(labelText || 'XÂY DỰNG TÂM TIẾN');
        img.src = `https://placehold.co/800x600/0E2A47/FFFFFF?text=${safeText}`;
      }
    }

    /**
     * Tạo URL ảnh trực tiếp từ Google Drive File ID
     */
    function driveImgUrl(id) {
      return `https://lh3.googleusercontent.com/d/${id}=w900`;
    }

    // ==================== DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG ====================
    const constructionProducts = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: 'Thi công kết cấu phần thô & đổ bê tông sàn nhà phố',
        category: 'phan-tho',
        categoryLabel: 'Thi công phần thô',
        desc: 'Triển khai cốp pha, cốt thép sàn đúng bản vẽ kết cấu, đầm dùi kỹ lưỡng đảm bảo cường độ chịu lực tối đa cho nhà ở tại Đà Nẵng.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Thi công xây tô tường bao & hoàn thiện mặt tiền',
        category: 'hoan-thien',
        categoryLabel: 'Thi công hoàn thiện',
        desc: 'Công tác xây gạch đúng mạch, tô trát phẳng mịn, chống nứt chân chim và xử lý bề mặt chuẩn bị sơn hoàn thiện ngoại thất.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Xây dựng nhà phố trọn gói chìa khóa trao tay',
        category: 'tron-goi',
        categoryLabel: 'Thi công trọn gói',
        desc: 'Gói dịch vụ trọn gói từ thiết kế kiến trúc, xin phép xây dựng, thi công thô đến hoàn thiện bàn giao vào ở ngay.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: 'Thi công hệ thống móng băng & gia công cốt thép',
        category: 'phan-tho',
        categoryLabel: 'Thi công phần thô',
        desc: 'Xử lý nền móng vững chắc phù hợp địa chất khu vực Đà Nẵng, kiểm tra nghiệm thu cốt thép nghiêm ngặt trước khi đổ bê tông.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Thi công hoàn thiện không gian nội ngoại thất',
        category: 'hoan-thien',
        categoryLabel: 'Thi công hoàn thiện',
        desc: 'Hoàn thiện trần thạch cao, chiếu sáng, cầu thang, cửa nhôm kính và vật liệu trang trí đồng bộ theo phối cảnh 3D.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        title: 'Thi công xây dựng biệt thự & nhà ở gia đình',
        category: 'tron-goi',
        categoryLabel: 'Thi công trọn gói',
        desc: 'Thi công nhà ở dân dụng chuẩn kỹ thuật công trình, tối ưu thông gió tự nhiên và ánh sáng cho khí hậu miền Trung.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        title: 'Thiết kế cải tạo, nâng tầng & sửa chữa trọn gói',
        category: 'thiet-ke',
        categoryLabel: 'Thiết kế & Cải tạo',
        desc: 'Khảo sát hiện trạng kết cấu, lên phương án cải tạo công năng và nâng cấp thẩm mỹ tiết kiệm tối đa chi phí.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        title: 'Thi công chống thấm, ốp lát gạch & sơn nước cao cấp',
        category: 'hoan-thien',
        categoryLabel: 'Thi công hoàn thiện',
        desc: 'Quy trình chống thấm 3 lớp cho sân thượng, nhà vệ sinh, ban công kết hợp ốp lát gạch sắc nét bền đẹp theo thời gian.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        title: 'Thiết kế & thi công căn hộ dịch vụ, văn phòng',
        category: 'thiet-ke',
        categoryLabel: 'Thiết kế & Cải tạo',
        desc: 'Giải pháp thiết kế và xây dựng tối ưu số lượng phòng, công năng kinh doanh và đảm bảo tiêu chuẩn an toàn công trình.'
      }
    ];

    // ==================== DỮ LIỆU 10 ẢNH CÁC DỰ ÁN Ở ĐÀ NẴNG ====================
    const danangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Nhà phố hiện đại 3 tầng – Khu đô thị Hòa Xuân, Đà Nẵng',
        category: 'nha-pho',
        location: 'Hòa Xuân, Cẩm Lệ, TP Đà Nẵng',
        desc: 'Công trình nhà phố diện tích 5x20m thi công trọn gói với mặt tiền thoáng sáng, bố trí 3 phòng ngủ và sân vườn nhỏ.'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Biệt thự phố sân vườn – Quận Ngũ Hành Sơn, Đà Nẵng',
        category: 'biet-thu',
        location: 'Ngũ Hành Sơn, TP Đà Nẵng',
        desc: 'Biệt thự thiết kế hiện đại kết hợp không gian xanh, hoàn thiện vật tư cao cấp và hệ thống chống thấm tiêu chuẩn.'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Tòa nhà căn hộ dịch vụ – Quận Sơn Trà, Đà Nẵng',
        category: 'khach-san',
        location: 'Sơn Trà, TP Đà Nẵng',
        desc: 'Thi công phần thô và hoàn thiện tòa nhà căn hộ cho thuê gần biển Mỹ Khê, tối ưu công suất khai thác cho chủ đầu tư.'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Nhà phố 2 mặt tiền – Quận Hải Châu, Đà Nẵng',
        category: 'nha-pho',
        location: 'Hải Châu, TP Đà Nẵng',
        desc: 'Nhà phố trung tâm TP Đà Nẵng kết hợp không gian sinh hoạt gia đình và mặt bằng kinh doanh hiện đại.'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Nhà ở gia đình trọn gói – Khu Nam Việt Á, Đà Nẵng',
        category: 'nha-pho',
        location: 'Nam Việt Á, Ngũ Hành Sơn, Đà Nẵng',
        desc: 'Hoàn thiện nhà phố 3 tầng theo phong cách tối giản, thi công đúng tiến độ cam kết 4,5 tháng.'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Khách sạn Boutique ven biển – Mỹ Khê, Đà Nẵng',
        category: 'khach-san',
        location: 'Mỹ Khê, Sơn Trà, TP Đà Nẵng',
        desc: 'Công trình khách sạn lưu trú thiết kế tinh tế, hệ thống kỹ thuật điện nước – PCCC đạt chuẩn nghiệm thu.'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Biệt thự phố tân cổ điển – Quận Cẩm Lệ, Đà Nẵng',
        category: 'biet-thu',
        location: 'Cẩm Lệ, TP Đà Nẵng',
        desc: 'Biệt thự đường nét kiến trúc sang trọng, tỉ mỉ từng chi tiết phào chỉ mặt tiền và nội thất gỗ ấm cúng.'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Thi công hoàn thiện văn phòng – Quận Thanh Khê, Đà Nẵng',
        category: 'van-phong',
        location: 'Thanh Khê, TP Đà Nẵng',
        desc: 'Cải tạo và hoàn thiện tòa nhà văn phòng làm việc với không gian mở, hiện đại và chuyên nghiệp.'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Nhà phố 4 tầng kết hợp kinh doanh – Khu Phước Lý, Đà Nẵng',
        category: 'nha-pho',
        location: 'Phước Lý, Liên Chiểu, Đà Nẵng',
        desc: 'Thiết kế và thi công trọn gói nhà phố 4 tầng kiên cố, tối ưu ánh sáng giếng trời và thông gió tự nhiên.'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Căn hộ cho thuê & phòng trọ cao cấp – Quận Liên Chiểu, Đà Nẵng',
        category: 'khach-san',
        location: 'Liên Chiểu, TP Đà Nẵng',
        desc: 'Xây dựng khu căn hộ mini khép kín bền vững, tối ưu chi phí đầu tư ban đầu và dễ dàng vận hành.'
      }
    ];

    // ==================== DỮ LIỆU BÀI VIẾT / TIN TỨC TRANG CHỦ ====================
    const newsArticles = [
      {
        imgId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        date: 'Cẩm nang xây dựng',
        title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật',
        summary: 'Bảo dưỡng bê tông đúng thời điểm giúp hạn chế rạn nứt bề mặt và đạt cường độ chịu lực tối đa cho toàn bộ ngôi nhà.',
        content: 'Trong 7 ngày đầu sau khi đổ bê tông móng, cột và sàn, việc giữ ẩm liên tục bằng nước sạch và che phủ bạt/bao tải ẩm là vô cùng quan trọng, đặc biệt trong điều kiện thời tiết nắng nóng tại Đà Nẵng. Quá trình thủy hóa xi măng diễn ra đều sẽ giúp kết cấu bê tông đặc chắc, tăng khả năng chống thấm và tuổi thọ công trình lên hàng chục năm.'
      },
      {
        imgId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        date: 'Kinh nghiệm xây nhà',
        title: '03 nỗi lo lớn nhất khi xây nhà trọn gói và cách phòng tránh',
        summary: 'Phát sinh chi phí, chậm tiến độ và vật tư không đúng cam kết là 3 vấn đề chủ nhà cần lưu ý trước khi ký hợp đồng.',
        content: 'Để tránh phát sinh chi phí khi xây nhà tại Đà Nẵng, chủ đầu tư nên thống nhất bản vẽ thiết kế chi tiết 2D/3D và bảng chủng loại vật tư ghi rõ thương hiệu ngay từ đầu. Lựa chọn nhà thầu uy tín có hợp đồng minh bạch, tiến độ thanh toán theo từng giai đoạn nghiệm thu thực tế sẽ giúp bạn hoàn toàn an tâm.'
      },
      {
        imgId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        date: 'Thiết kế kiến trúc',
        title: 'Kinh nghiệm thiết kế nhà phố Đà Nẵng thoáng mát quanh năm',
        summary: 'Giải pháp giếng trời, thông gió chéo và chống nóng hướng Tây giúp ngôi nhà luôn mát mẻ, tiết kiệm điện năng.',
        content: 'Với đặc trưng khí hậu miền Trung có mùa hè nắng gắt và mùa mưa bão lớn, nhà phố tại Đà Nẵng cần chú trọng thiết kế giếng trời kết hợp cầu thang, sử dụng gạch chống nóng tường hướng Tây, lam chắn nắng mặt tiền và hệ thống thoát nước mái tiêu chuẩn để đảm bảo không gian sống luôn dễ chịu và khô ráo.'
      },
      {
        imgId: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        date: 'Báo giá & Dự toán',
        title: 'Cách tính diện tích xây dựng và dự trù ngân sách chuẩn xác',
        summary: 'Nắm rõ cách tính hệ số móng, tầng trệt, các tầng lầu và mái giúp gia chủ chủ động chuẩn bị tài chính hợp lý.',
        content: 'Tổng chi phí xây dựng thường được tính bằng tổng diện tích sàn quy đổi nhân với đơn giá thi công phần thô hoặc trọn gói. Trong đó móng băng/móng đơn tính từ 30%–50%, các tầng có mái che tính 100%, sân thượng có giàn phẹt tính 50%–70%. Liên hệ Nhà thầu Xây dựng Tâm Tiến qua hotline 0906.440.277 để nhận bảng dự toán chi tiết miễn phí.'
      }
    ];

    // ==================== RENDER SẢN PHẨM / THI CÔNG THỰC TẾ ====================
    function renderProducts(filter = 'all') {
      const grid = document.getElementById('productGrid');
      const items = filter === 'all'
        ? constructionProducts
        : constructionProducts.filter(p => p.category === filter);

      grid.innerHTML = items.map((item) => `
        <article
          onclick="openProjectModal('${item.id}', \`${item.title}\`, '${item.categoryLabel}', \`${item.desc}\`)"
          class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-primary hover:shadow-md transition flex flex-col"
        >
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveImgUrl(item.id)}"
              alt="${item.title}"
              loading="lazy"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              onerror="handleImgError(this, '${item.id}', 'THI CÔNG TÂM TIẾN')"
            />
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-[13px] sm:text-sm font-bold text-brand-dark group-hover:text-brand-primary transition card-title-safe">
              ${item.title}
            </h3>
            <p class="mt-1.5 text-[11px] sm:text-xs text-slate-500">
              ${item.categoryLabel}
            </p>
          </div>
        </article>
      `).join('');
    }

    function filterProducts(category) {
      document.querySelectorAll('.prod-tab').forEach(btn => {
        const isActive = btn.dataset.prodTab === category;
        btn.className = isActive
          ? 'prod-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-dark text-white transition shrink-0'
          : 'prod-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition shrink-0';
      });
      renderProducts(category);
    }

    // ==================== RENDER 10 DỰ ÁN Ở ĐÀ NẴNG ====================
    function renderProjects(filter = 'all') {
      const grid = document.getElementById('projectGrid');
      const items = filter === 'all'
        ? danangProjects
        : danangProjects.filter(p => p.category === filter);

      grid.innerHTML = items.map((item) => `
        <article
          onclick="openProjectModal('${item.id}', \`${item.title}\`, '${item.location}', \`${item.desc}\`)"
          class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-primary hover:shadow-md transition flex flex-col"
        >
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveImgUrl(item.id)}"
              alt="${item.title}"
              loading="lazy"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              onerror="handleImgError(this, '${item.id}', 'DỰ ÁN ĐÀ NẴNG')"
            />
          </div>
          <div class="p-3 sm:p-3.5 flex-1 flex flex-col justify-between">
            <h3 class="text-[12.5px] sm:text-[13.5px] font-bold text-brand-dark group-hover:text-brand-primary transition card-title-safe">
              ${item.title}
            </h3>
            <p class="mt-1.5 text-[11px] text-slate-500 flex items-start gap-1">
              <i class="fa-solid fa-location-dot text-brand-accent mt-0.5 shrink-0"></i>
              <span class="card-title-safe">${item.location}</span>
            </p>
          </div>
        </article>
      `).join('');
    }

    function filterProjects(category) {
      document.querySelectorAll('.proj-tab').forEach(btn => {
        const isActive = btn.dataset.projTab === category;
        btn.className = isActive
          ? 'proj-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-dark text-white transition shrink-0'
          : 'proj-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:bg-slate-100 transition shrink-0';
      });
      renderProjects(category);
    }

    // ==================== RENDER BÀI VIẾT TRANG CHỦ ====================
    function renderNews() {
      const grid = document.getElementById('newsGrid');
      grid.innerHTML = newsArticles.map((art, idx) => `
        <article
          onclick="openArticleModal(${idx})"
          class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-primary hover:shadow-md transition flex flex-col"
        >
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveImgUrl(art.imgId)}"
              alt="${art.title}"
              loading="lazy"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              onerror="handleImgError(this, '${art.imgId}', 'TIN TỨC XÂY DỰNG')"
            />
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <p class="text-[11px] font-semibold text-brand-accent mb-1">${art.date}</p>
              <h3 class="text-[13px] sm:text-sm font-bold text-brand-dark group-hover:text-brand-primary transition card-title-safe">
                ${art.title}
              </h3>
              <p class="mt-1.5 text-[11px] sm:text-xs text-slate-600 leading-relaxed hidden sm:block">
                ${art.summary}
              </p>
            </div>
            <span class="mt-2.5 inline-flex items-center gap-1 text-xs font-semibold text-brand-primary">
              Đọc chi tiết <i class="fa-solid fa-angle-right text-[11px]"></i>
            </span>
          </div>
        </article>
      `).join('');
    }

    // ==================== SLIDER 2 BANNER TỰ TRƯỢT ====================
    let currentSlide = 0;
    const totalSlides = 2;
    let slideInterval = null;

    function updateSliderUI() {
      const track = document.getElementById('heroSliderTrack');
      track.style.transform = `translateX(-${currentSlide * 50}%)`;
      for (let i = 0; i < totalSlides; i++) {
        const dot = document.getElementById(`dot-${i}`);
        if (dot) {
          dot.className = i === currentSlide
            ? 'w-6 h-2 rounded-full bg-brand-accent transition-all'
            : 'w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
        }
      }
    }

    function moveSlide(step) {
      currentSlide = (currentSlide + step + totalSlides) % totalSlides;
      updateSliderUI();
      resetSlideTimer();
    }

    function goToSlide(index) {
      currentSlide = index;
      updateSliderUI();
      resetSlideTimer();
    }

    function resetSlideTimer() {
      if (slideInterval) clearInterval(slideInterval);
      slideInterval = setInterval(() => {
        currentSlide = (currentSlide + 1) % totalSlides;
        updateSliderUI();
      }, 5500);
    }

    // Hỗ trợ vuốt cảm ứng (swipe) cho banner trên điện thoại
    (function setupBannerSwipe() {
      const viewport = document.querySelector('.hero-slider-viewport');
      let touchStartX = 0;
      viewport.addEventListener('touchstart', (e) => {
        touchStartX = e.changedTouches[0].screenX;
      }, { passive: true });
      viewport.addEventListener('touchend', (e) => {
        const diff = e.changedTouches[0].screenX - touchStartX;
        if (Math.abs(diff) > 45) {
          moveSlide(diff < 0 ? 1 : -1);
        }
      }, { passive: true });
    })();

    // ==================== MENU MOBILE ====================
    const mobileMenuBtn = document.getElementById('mobileMenuBtn');
    const mobileMenuDrawer = document.getElementById('mobileMenuDrawer');
    mobileMenuBtn.addEventListener('click', () => {
      mobileMenuDrawer.classList.toggle('hidden');
    });
    function closeMobileMenu() {
      mobileMenuDrawer.classList.add('hidden');
    }

    // ==================== MODAL CHI TIẾT CÔNG TRÌNH / BÀI VIẾT ====================
    function openProjectModal(imgId, title, subtitle, desc) {
      const modal = document.getElementById('detailModal');
      const body = document.getElementById('detailModalBody');
      body.innerHTML = `
        <div class="rounded-lg overflow-hidden bg-slate-100 mb-4 aspect-[16/10]">
          <img
            src="${driveImgUrl(imgId)}"
            alt="${title}"
            class="w-full h-full object-cover"
            onerror="handleImgError(this, '${imgId}', 'XÂY DỰNG TÂM TIẾN')"
          />
        </div>
        <p class="text-xs font-semibold text-brand-accent mb-1">${subtitle}</p>
        <h3 class="text-lg sm:text-xl font-extrabold text-brand-dark mb-2.5">${title}</h3>
        <p class="text-sm text-slate-700 leading-relaxed mb-5">${desc}</p>
        <div class="flex flex-wrap gap-2.5 pt-3 border-t border-slate-100">
          <a href="tel:0906440277" class="inline-flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white text-xs sm:text-sm font-bold px-4 py-2.5 rounded-lg transition">
            <i class="fa-solid fa-phone"></i> Gọi tư vấn: 0906.440.277
          </a>
          <a href="https://zalo.me/0906440277" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 bg-[#0068FF] hover:bg-blue-700 text-white text-xs sm:text-sm font-bold px-4 py-2.5 rounded-lg transition">
            Nhắn Zalo nhận báo giá
          </a>
        </div>
      `;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function openArticleModal(index) {
      const art = newsArticles[index];
      openProjectModal(art.imgId, art.title, art.date, art.content);
    }

    function closeDetailModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    document.getElementById('detailModal').addEventListener('click', (e) => {
      if (e.target.id === 'detailModal') closeDetailModal();
    });

    // ==================== XỬ LÝ FORM BÁO GIÁ (KHÔNG DÙNG ALERT) ====================
    document.getElementById('quoteForm').addEventListener('submit', function (e) {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const type = document.getElementById('qType').value;
      const budget = document.getElementById('qBudget').value;
      const feedback = document.getElementById('quoteFeedback');

      if (!name || !phone) {
        feedback.className = 'rounded-lg p-3 text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
        feedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để Tâm Tiến liên hệ báo giá.';
        feedback.classList.remove('hidden');
        return;
      }

      feedback.className = 'rounded-lg p-3.5 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
      feedback.innerHTML = `Cảm ơn <strong>${name}</strong>! Yêu cầu báo giá hạng mục <strong>${type}</strong> (${budget}) đã được ghi nhận. Kỹ sư Nhà thầu xây dựng Tâm Tiến sẽ liên hệ số <strong>${phone}</strong> trong thời gian sớm nhất, hoặc gọi trực tiếp Hotline <strong>0906.440.277</strong>.`;
      feedback.classList.remove('hidden');
      this.reset();
    });

    // ==================== KHỞI TẠO TRANG ====================
    window.addEventListener('DOMContentLoaded', () => {
      renderProducts('all');
      renderProjects('all');
      renderNews();
      resetSlideTimer();
    });
  </script>
</body>
</html>
