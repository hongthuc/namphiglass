<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH MTV NĂM PHI GLASS | Cửa Nhôm Xingfa &amp; Kính Cường Lực Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH MTV NĂM PHI GLASS (namphiglass.com) - Đơn vị thiết kế, thi công cửa nhôm Xingfa nhập khẩu, cửa kính cường lực, cầu thang kính, phòng tắm kính, kính ốp bếp uy tín tại Hòa Tiến, Đà Nẵng. Hotline: 0938.363.345.">

    <!-- Meta Tags Thumbnail khi chia sẻ link trang web (sử dụng Logo Năm Phi Glass) -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://namphiglass.com/">
    <meta property="og:title" content="CÔNG TY TNHH MTV NĂM PHI GLASS - Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng">
    <meta property="og:description" content="Chuyên tư vấn, thiết kế, thi công lắp đặt cửa nhôm Xingfa, cửa kính cường lực, cầu thang kính, phòng tắm kính, kính ốp bếp tại Đà Nẵng. Hotline: 0938.363.345.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1owRe16iBfMIQhi78Zmpg_kwaW6rsVUKJ=w1200">
    <meta property="og:image:alt" content="Logo CÔNG TY TNHH MTV NĂM PHI GLASS">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH MTV NĂM PHI GLASS | namphiglass.com">
    <meta name="twitter:description" content="Cửa Nhôm Xingfa & Kính Cường Lực Uy Tín Tại Đà Nẵng - Hotline: 0938.363.345">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1owRe16iBfMIQhi78Zmpg_kwaW6rsVUKJ=w1200">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1owRe16iBfMIQhi78Zmpg_kwaW6rsVUKJ=w256">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        /* Cấu hình màu sắc chủ đạo theo tông thương hiệu Nhôm Kính Năm Phi Glass */
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#eff6ff',
                            100: '#dbeafe',
                            200: '#bfdbfe',
                            500: '#1d63b8',
                            600: '#134e96',
                            700: '#0d3b75',
                            800: '#092c59',
                            900: '#061f40',
                        },
                        accent: {
                            500: '#e11d48',
                            600: '#be123c',
                        }
                    }
                }
            }
        };
    </script>

    <style>
        /* Chống tràn viền ngang và lệch trang trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }

        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            scroll-behavior: smooth;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
        }

        /* Khung chuẩn Flatsome: 95% chiều ngang màn hình trên máy tính */
        .ux-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        @media (min-width: 1024px) {
            .ux-container {
                width: 95%;
                max-width: 95vw;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tối ưu thanh menu máy tính: chữ gọn, không xuống dòng từng tên danh mục */
        .desktop-nav-list {
            display: flex;
            align-items: center;
            justify-content: flex-end;
            flex-wrap: nowrap;
            gap: 0.35rem;
        }

        @media (min-width: 1200px) {
            .desktop-nav-list {
                gap: 0.65rem;
            }
        }

        @media (min-width: 1400px) {
            .desktop-nav-list {
                gap: 1.1rem;
            }
        }

        .desktop-nav-link {
            white-space: nowrap;
            font-size: 11.5px;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: -0.01em;
            padding: 0.55rem 0.45rem;
            color: #0d3b75;
            transition: color 0.2s ease, background-color 0.2s ease;
            border-radius: 6px;
            display: inline-flex;
            align-items: center;
            gap: 4px;
        }

        @media (min-width: 1280px) {
            .desktop-nav-link {
                font-size: 12.5px;
                padding: 0.55rem 0.55rem;
            }
        }

        @media (min-width: 1536px) {
            .desktop-nav-link {
                font-size: 13.5px;
                padding: 0.6rem 0.75rem;
            }
        }

        .desktop-nav-link:hover,
        .desktop-nav-link.active {
            color: #1d63b8;
            background-color: #eff6ff;
        }

        /* Dropdown Flatsome mượt mà */
        .ux-dropdown {
            position: relative;
        }

        .ux-dropdown-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 225px;
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-top: 3px solid #0d3b75;
            border-radius: 0 0 10px 10px;
            box-shadow: 0 12px 28px rgba(13, 59, 117, 0.14);
            z-index: 60;
            padding: 6px 0;
        }

        .ux-dropdown:hover .ux-dropdown-menu,
        .ux-dropdown:focus-within .ux-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        .ux-dropdown-item {
            display: block;
            padding: 9px 16px;
            font-size: 13px;
            font-weight: 500;
            color: #334155;
            white-space: nowrap;
            transition: all 0.15s ease;
        }

        .ux-dropdown-item:hover {
            background-color: #eff6ff;
            color: #0d3b75;
            padding-left: 20px;
        }

        /* Tiêu đề Section chuẩn Flatsome có gạch nhấn ở giữa */
        .ux-section-title {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }

        .ux-section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 64px;
            height: 3px;
            background: linear-gradient(90deg, #0d3b75, #1d63b8);
            border-radius: 99px;
        }

        /* Banner Slider 2 slide đồng nhất kích thước, không tràn chữ */
        .banner-viewport {
            position: relative;
            width: 100%;
            overflow: hidden;
            border-radius: 14px;
        }

        .banner-track {
            display: flex;
            width: 100%;
            transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
        }

        .banner-slide {
            flex: 0 0 100%;
            width: 100%;
            min-width: 100%;
        }

        /* Hiệu ứng nhịp nhẹ cho nút Hotline nổi */
        @keyframes pulseRing {
            0% {
                box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.55);
            }
            70% {
                box-shadow: 0 0 0 12px rgba(220, 38, 38, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(220, 38, 38, 0);
            }
        }

        .hotline-pulse {
            animation: pulseRing 2s infinite;
        }

        /* Khoảng trống dưới cùng trên mobile để thanh liên hệ nổi không che nội dung */
        @media (max-width: 767px) {
            body {
                padding-bottom: 62px;
            }
        }
    </style>
</head>
<body class="antialiased selection:bg-brand-600 selection:text-white">

    <!-- =====================================================================
         UX BUILDER: TOP BAR THÔNG TIN NHANH (KHÔNG CÓ THANH CHỈNH SỬA UXBUILDER)
    ====================================================================== -->
    <div class="bg-brand-800 text-white text-xs py-2 border-b border-brand-700">
        <div class="ux-container flex flex-wrap items-center justify-between gap-y-1">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-sky-300"></i>
                    <span>Hòa Tiến, Đà Nẵng</span>
                </span>
                <span class="hidden sm:inline-flex items-center gap-1.5">
                    <i class="fa-regular fa-clock text-sky-300"></i>
                    <span>Làm việc 24/7</span>
                </span>
            </div>
            <div class="flex items-center gap-x-4">
                <a href="tel:0938363345" class="inline-flex items-center gap-1.5 font-semibold text-white hover:text-sky-200 transition">
                    <i class="fa-solid fa-phone-volume text-sky-300"></i>
                    <span>0938.363.345</span>
                </a>
                <span class="hidden md:inline-flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-globe text-sky-300"></i>
                    <span>namphiglass.com</span>
                </span>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         UX BUILDER: HEADER CHÍNH (LOGO GỌN NHỎ + MENU 1 HÀNG + KHÔNG NÚT GỌI NGAY)
    ====================================================================== -->
    <header id="main-header" class="sticky top-0 z-50 bg-white/98 backdrop-blur border-b border-slate-200 shadow-sm">
        <div class="ux-container">
            <div class="flex items-center justify-between h-16 lg:h-[72px] gap-2">
                <!-- Logo Công ty gọn nhỏ -->
                <a href="#trang-chu" class="flex items-center gap-2 shrink-0 py-1 group" aria-label="Trang chủ Năm Phi Glass">
                    <img
                        src="https://lh3.googleusercontent.com/d/1owRe16iBfMIQhi78Zmpg_kwaW6rsVUKJ=w400"
                        data-drive-id="1owRe16iBfMIQhi78Zmpg_kwaW6rsVUKJ"
                        alt="Logo CÔNG TY TNHH MTV NĂM PHI GLASS"
                        class="h-10 sm:h-11 lg:h-11 w-auto max-w-[140px] object-contain rounded transition-transform duration-200 group-hover:scale-105"
                        onerror="handleDriveFallback(this, 'NAM PHI GLASS', '0d3b75', 'ffffff')"
                    >
                    <div class="flex flex-col leading-tight lg:hidden xl:flex">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-800 tracking-tight whitespace-nowrap">NĂM PHI GLASS</span>
                        <span class="text-[10px] font-medium text-slate-500 whitespace-nowrap">namphiglass.com</span>
                    </div>
                </a>

                <!-- Menu Máy Tính: Viết liền trên 1 hàng, chữ nhỏ gọn, không xuống dòng -->
                <nav class="hidden lg:block flex-1 min-w-0" aria-label="Menu chính">
                    <ul class="desktop-nav-list">
                        <li>
                            <a href="#trang-chu" class="desktop-nav-link active">Trang chủ</a>
                        </li>
                        <li>
                            <a href="#gioi-thieu" class="desktop-nav-link">Giới thiệu</a>
                        </li>
                        <!-- Dropdown: Cửa nhôm xingfa -->
                        <li class="ux-dropdown">
                            <a href="#san-pham-xingfa" class="desktop-nav-link">
                                <span>Cửa nhôm xingfa</span>
                                <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                            </a>
                            <div class="ux-dropdown-menu">
                                <a href="#san-pham-xingfa" onclick="filterProductByKey('1-canh')" class="ux-dropdown-item">Cửa nhôm xingfa 1 cánh</a>
                                <a href="#san-pham-xingfa" onclick="filterProductByKey('2-canh')" class="ux-dropdown-item">Cửa nhôm xingfa 2 cánh</a>
                                <a href="#san-pham-xingfa" onclick="filterProductByKey('3-canh')" class="ux-dropdown-item">Cửa nhôm xingfa 3 cánh</a>
                                <a href="#san-pham-xingfa" onclick="filterProductByKey('4-canh')" class="ux-dropdown-item">Cửa nhôm xingfa 4 cánh</a>
                                <a href="#san-pham-xingfa" onclick="filterProductByKey('5-canh')" class="ux-dropdown-item">Cửa nhôm xingfa 5 cánh</a>
                            </div>
                        </li>
                        <li>
                            <a href="#danh-muc-san-pham" class="desktop-nav-link">Cửa kính cường lực</a>
                        </li>
                        <!-- Dropdown: Sản phẩm -->
                        <li class="ux-dropdown">
                            <a href="#danh-muc-san-pham" class="desktop-nav-link">
                                <span>Sản phẩm</span>
                                <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                            </a>
                            <div class="ux-dropdown-menu">
                                <a href="#san-pham-xingfa" class="ux-dropdown-item">Cửa nhôm xingfa</a>
                                <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa nhựa lõi thép')" class="ux-dropdown-item">Cửa nhựa lõi thép</a>
                                <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa kính tự động')" class="ux-dropdown-item">Cửa kính tự động</a>
                                <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cầu thang kính')" class="ux-dropdown-item">Cầu thang kính</a>
                                <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Kính ốp bếp')" class="ux-dropdown-item">Kính ốp bếp</a>
                                <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Phòng tắm kính')" class="ux-dropdown-item">Phòng tắm kính</a>
                            </div>
                        </li>
                        <li>
                            <a href="#cong-trinh" class="desktop-nav-link">Công trình</a>
                        </li>
                        <li>
                            <a href="#bao-gia" class="desktop-nav-link">Báo giá</a>
                        </li>
                        <li>
                            <a href="#tin-tuc" class="desktop-nav-link">Tin tức</a>
                        </li>
                        <li>
                            <a href="#lien-he" class="desktop-nav-link">Liên hệ</a>
                        </li>
                    </ul>
                </nav>

                <!-- Nút mở Menu trên Điện thoại / Tablet -->
                <button
                    id="mobile-menu-btn"
                    type="button"
                    onclick="toggleMobileMenu()"
                    class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-800 hover:bg-brand-50 transition"
                    aria-label="Mở menu điều hướng"
                    aria-expanded="false"
                >
                    <i id="mobile-menu-icon" class="fa-solid fa-bars text-lg"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Drawer Menu -->
        <div id="mobile-menu-panel" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-xl max-h-[82vh] overflow-y-auto">
            <nav class="px-4 py-3 space-y-1 text-sm font-semibold text-slate-800" aria-label="Menu di động">
                <a href="#trang-chu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-brand-50 text-brand-800">Trang chủ</a>
                <a href="#gioi-thieu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-brand-50">Giới thiệu</a>

                <!-- Accordion: Cửa nhôm xingfa -->
                <div class="border-y border-slate-100 py-1">
                    <button type="button" onclick="toggleMobileSubmenu('sub-xingfa', 'icon-xingfa')" class="w-full flex items-center justify-between px-3 py-2.5 rounded-lg hover:bg-brand-50 text-left">
                        <span>Cửa nhôm xingfa</span>
                        <i id="icon-xingfa" class="fa-solid fa-chevron-down text-xs text-slate-500 transition-transform"></i>
                    </button>
                    <div id="sub-xingfa" class="hidden pl-5 pr-2 pb-2 space-y-1 text-[13px] font-medium text-slate-600">
                        <a href="#san-pham-xingfa" onclick="filterProductByKey('1-canh'); closeMobileMenu();" class="block py-1.5 hover:text-brand-700">+ Cửa nhôm xingfa 1 cánh</a>
                        <a href="#san-pham-xingfa" onclick="filterProductByKey('2-canh'); closeMobileMenu();" class="block py-1.5 hover:text-brand-700">+ Cửa nhôm xingfa 2 cánh</a>
                        <a href="#san-pham-xingfa" onclick="filterProductByKey('3-canh'); closeMobileMenu();" class="block py-1.5 hover:text-brand-700">+ Cửa nhôm xingfa 3 cánh</a>
                        <a href="#san-pham-xingfa" onclick="filterProductByKey('4-canh'); closeMobileMenu();" class="block py-1.5 hover:text-brand-700">+ Cửa nhôm xingfa 4 cánh</a>
                        <a href="#san-pham-xingfa" onclick="filterProductByKey('5-canh'); closeMobileMenu();" class="block py-1.5 hover:text-brand-700">+ Cửa nhôm xingfa 5 cánh</a>
                    </div>
                </div>

                <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-brand-50">Cửa kính cường lực</a>

                <!-- Accordion: Sản phẩm -->
                <div class="border-y border-slate-100 py-1">
                    <button type="button" onclick="toggleMobileSubmenu('sub-sanpham', 'icon-sanpham')" class="w-full flex items-center justify-between px-3 py-2.5 rounded-lg hover:bg-brand-50 text-left">
                        <span>Sản phẩm</span>
                        <i id="icon-sanpham" class="fa-solid fa-chevron-down text-xs text-slate-500 transition-transform"></i>
                    </button>
                    <div id="sub-sanpham" class="hidden pl-5 pr-2 pb-2 space-y-1 text-[13px] font-medium text-slate-600">
                        <a href="#san-pham-xingfa" onclick="closeMobileMenu()" class="block py-1.5 hover:text-brand-700">+ Cửa nhôm xingfa</a>
                        <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa nhựa lõi thép'); closeMobileMenu();" class="block py-1.5 hover:text-brand-700">+ Cửa nhựa lõi thép</a>
                        <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa kính tự động'); closeMobileMenu();" class="block py-1.5 hover:text-brand-700">+ Cửa kính tự động</a>
                        <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cầu thang kính'); closeMobileMenu();" class="block py-1.5 hover:text-brand-700">+ Cầu thang kính</a>
                        <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Kính ốp bếp'); closeMobileMenu();" class="block py-1.5 hover:text-brand-700">+ Kính ốp bếp</a>
                        <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Phòng tắm kính'); closeMobileMenu();" class="block py-1.5 hover:text-brand-700">+ Phòng tắm kính</a>
                    </div>
                </div>

                <a href="#cong-trinh" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-brand-50">Công trình</a>
                <a href="#bao-gia" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-brand-50">Báo giá</a>
                <a href="#tin-tuc" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-brand-50">Tin tức</a>
                <a href="#lien-he" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-brand-50">Liên hệ</a>
            </nav>
        </div>
    </header>

    <main id="trang-chu">

        <!-- =====================================================================
             UX BUILDER: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP - ĐỒNG NHẤT KÍCH THƯỚC
             Đảm bảo chữ & ảnh nằm trọn trong banner, cách xa viền, không mất chữ
        ====================================================================== -->
        <section class="pt-3 pb-6 sm:pt-4 sm:pb-8 bg-slate-50">
            <div class="ux-container">
                <div class="banner-viewport shadow-lg border border-slate-200 bg-brand-900" id="hero-slider">
                    <div class="banner-track" id="banner-track">

                        <!-- BANNER 1 -->
                        <div class="banner-slide bg-gradient-to-br from-brand-900 via-brand-800 to-brand-700 text-white">
                            <div class="grid grid-cols-1 lg:grid-cols-12 items-center gap-6 lg:gap-8 px-7 py-9 sm:px-12 sm:py-11 lg:px-16 lg:py-12 min-h-[380px] sm:min-h-[400px] lg:min-h-[430px]">
                                <!-- Nội dung chữ cách xa viền banner -->
                                <div class="lg:col-span-7 space-y-3 sm:space-y-4 text-left">
                                    <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-sky-300">
                                        CÔNG TY TNHH MTV NĂM PHI GLASS • ĐÀ NẴNG
                                    </p>
                                    <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                                        THI CÔNG CỬA NHÔM XINGFA &amp; KÍNH CƯỜNG LỰC CHÍNH HÃNG
                                    </h1>
                                    <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-2xl">
                                        Chuyên thiết kế, sản xuất và lắp đặt cửa nhôm Xingfa nhập khẩu 100%, kính cường lực, phòng tắm kính, cầu thang kính với giá gốc trực tiếp tại xưởng Hòa Tiến, Đà Nẵng.
                                    </p>
                                    <div class="pt-2 flex flex-wrap items-center gap-3">
                                        <a href="#bao-gia" class="inline-flex items-center gap-2 bg-white text-brand-800 hover:bg-sky-50 font-bold text-xs sm:text-sm px-5 py-2.5 rounded-lg shadow transition">
                                            <i class="fa-solid fa-file-invoice-dollar"></i>
                                            <span>Nhận Báo Giá Ngay</span>
                                        </a>
                                        <a href="#san-pham-xingfa" class="inline-flex items-center gap-2 border border-white/50 text-white hover:bg-white/10 font-semibold text-xs sm:text-sm px-5 py-2.5 rounded-lg transition">
                                            <span>Xem Sản Phẩm</span>
                                            <i class="fa-solid fa-arrow-right text-xs"></i>
                                        </a>
                                    </div>
                                </div>

                                <!-- Hình ảnh nằm trọn trong khung bên phải -->
                                <div class="lg:col-span-5 flex justify-center">
                                    <div class="w-full max-w-[440px] aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl bg-brand-800">
                                        <img
                                            src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w900"
                                            data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                                            alt="Cửa nhôm Xingfa Năm Phi Glass Đà Nẵng"
                                            class="w-full h-full object-cover"
                                            onerror="handleDriveFallback(this, 'Cua Nhom Xingfa Nam Phi Glass', '134e96', 'ffffff')"
                                        >
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- BANNER 2 (Cùng kích thước và khoảng cách an toàn như Banner 1) -->
                        <div class="banner-slide bg-gradient-to-br from-slate-900 via-brand-900 to-brand-700 text-white">
                            <div class="grid grid-cols-1 lg:grid-cols-12 items-center gap-6 lg:gap-8 px-7 py-9 sm:px-12 sm:py-11 lg:px-16 lg:py-12 min-h-[380px] sm:min-h-[400px] lg:min-h-[430px]">
                                <!-- Nội dung chữ cách xa viền banner -->
                                <div class="lg:col-span-7 space-y-3 sm:space-y-4 text-left">
                                    <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-sky-300">
                                        CHẤT LƯỢNG LÀ SỐ 1 • THƯƠNG HIỆU LÀ MÃI MÃI
                                    </p>
                                    <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                                        NHÀ THẦU NHÔM KÍNH CHO KHÁCH SẠN, RESORT &amp; NHÀ PHỐ
                                    </h2>
                                    <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-2xl">
                                        Hệ thống máy móc đồng bộ hiện đại, đội ngũ kỹ thuật viên giàu kinh nghiệm. Khảo sát tận nơi miễn phí, bảo hành dài hạn và tiến độ thi công chuẩn xác tại Đà Nẵng.
                                    </p>
                                    <div class="pt-2 flex flex-wrap items-center gap-3">
                                        <a href="#cong-trinh" class="inline-flex items-center gap-2 bg-white text-brand-800 hover:bg-sky-50 font-bold text-xs sm:text-sm px-5 py-2.5 rounded-lg shadow transition">
                                            <i class="fa-solid fa-building"></i>
                                            <span>Xem Công Trình Thực Tế</span>
                                        </a>
                                        <a href="tel:0938363345" class="inline-flex items-center gap-2 border border-white/50 text-white hover:bg-white/10 font-semibold text-xs sm:text-sm px-5 py-2.5 rounded-lg transition">
                                            <i class="fa-solid fa-phone"></i>
                                            <span>Hotline: 0938.363.345</span>
                                        </a>
                                    </div>
                                </div>

                                <!-- Hình ảnh nằm trọn trong khung bên phải -->
                                <div class="lg:col-span-5 flex justify-center">
                                    <div class="w-full max-w-[440px] aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl bg-brand-800">
                                        <img
                                            src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ=w900"
                                            data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                                            alt="Dự án nhôm kính Năm Phi Glass Đà Nẵng"
                                            class="w-full h-full object-cover"
                                            onerror="handleDriveFallback(this, 'Du An Thi Cong Nam Phi Glass', '0d3b75', 'ffffff')"
                                        >
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Nút điều hướng Slide (đặt sát mép ngoài vùng chữ) -->
                    <button
                        type="button"
                        onclick="moveSlide(-1)"
                        aria-label="Banner trước"
                        class="hidden sm:flex absolute left-2.5 top-1/2 -translate-y-1/2 w-9 h-9 rounded-full bg-black/35 hover:bg-black/60 text-white items-center justify-center transition z-10"
                    >
                        <i class="fa-solid fa-chevron-left text-sm"></i>
                    </button>
                    <button
                        type="button"
                        onclick="moveSlide(1)"
                        aria-label="Banner tiếp theo"
                        class="hidden sm:flex absolute right-2.5 top-1/2 -translate-y-1/2 w-9 h-9 rounded-full bg-black/35 hover:bg-black/60 text-white items-center justify-center transition z-10"
                    >
                        <i class="fa-solid fa-chevron-right text-sm"></i>
                    </button>

                    <!-- Chấm chỉ báo Slide -->
                    <div class="absolute bottom-3 left-1/2 -translate-x-1/2 flex items-center gap-2 z-10">
                        <button type="button" onclick="goToSlide(0)" id="dot-0" aria-label="Chuyển tới banner 1" class="w-6 h-2 rounded-full bg-white transition-all"></button>
                        <button type="button" onclick="goToSlide(1)" id="dot-1" aria-label="Chuyển tới banner 2" class="w-2.5 h-2 rounded-full bg-white/45 hover:bg-white/75 transition-all"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- =====================================================================
             UX BUILDER: DANH MỤC SẢN PHẨM NỔI BẬT (THEO WEB MẪU - CHỮ NHỎ GỌN)
        ====================================================================== -->
        <section id="danh-muc-san-pham" class="py-8 sm:py-10 bg-white border-y border-slate-200/80">
            <div class="ux-container">
                <div class="text-center mb-6 sm:mb-8">
                    <h2 class="ux-section-title text-lg sm:text-2xl font-extrabold text-brand-800 uppercase">
                        Danh Mục Sản Phẩm Nổi Bật
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2">
                        Giải pháp nhôm kính đồng bộ cho nhà phố, biệt thự, văn phòng và khách sạn tại Đà Nẵng
                    </p>
                </div>

                <!-- 2 cột trên điện thoại, 3 cột trên tablet, 6 cột trên máy tính -->
                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
                    <!-- Danh mục 1: Cửa nhôm xingfa -->
                    <a href="#san-pham-xingfa" class="group bg-slate-50 border border-slate-200 rounded-xl overflow-hidden hover:border-brand-500 hover:shadow-md transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                            <img
                                src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w600"
                                data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                                alt="Cửa nhôm xingfa"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveFallback(this, 'Cua Nhom Xingfa', 'e2e8f0', '0d3b75')"
                            >
                        </div>
                        <div class="p-2.5 text-center flex-1 flex items-center justify-center">
                            <h3 class="text-[11px] sm:text-xs font-bold text-brand-800 uppercase leading-tight group-hover:text-brand-600">
                                Cửa Nhôm Xingfa
                            </h3>
                        </div>
                    </a>

                    <!-- Danh mục 2: Cửa nhựa lõi thép -->
                    <button type="button" onclick="selectCategoryQuote('Cửa nhựa lõi thép')" class="group bg-slate-50 border border-slate-200 rounded-xl overflow-hidden hover:border-brand-500 hover:shadow-md transition flex flex-col text-left">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                            <img
                                src="https://lh3.googleusercontent.com/d/1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA=w600"
                                data-drive-id="1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA"
                                alt="Cửa nhựa lõi thép"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveFallback(this, 'Cua Nhua Loi Thep', 'e2e8f0', '0d3b75')"
                            >
                        </div>
                        <div class="p-2.5 text-center flex-1 flex items-center justify-center w-full">
                            <h3 class="text-[11px] sm:text-xs font-bold text-brand-800 uppercase leading-tight group-hover:text-brand-600">
                                Cửa Nhựa Lõi Thép
                            </h3>
                        </div>
                    </button>

                    <!-- Danh mục 3: Cửa kính tự động -->
                    <button type="button" onclick="selectCategoryQuote('Cửa kính tự động')" class="group bg-slate-50 border border-slate-200 rounded-xl overflow-hidden hover:border-brand-500 hover:shadow-md transition flex flex-col text-left">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                            <img
                                src="https://lh3.googleusercontent.com/d/1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ=w600"
                                data-drive-id="1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ"
                                alt="Cửa kính tự động"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveFallback(this, 'Cua Tu Dong', 'e2e8f0', '0d3b75')"
                            >
                        </div>
                        <div class="p-2.5 text-center flex-1 flex items-center justify-center w-full">
                            <h3 class="text-[11px] sm:text-xs font-bold text-brand-800 uppercase leading-tight group-hover:text-brand-600">
                                Cửa Kính Tự Động
                            </h3>
                        </div>
                    </button>

                    <!-- Danh mục 4: Cầu thang kính -->
                    <button type="button" onclick="selectCategoryQuote('Cầu thang kính')" class="group bg-slate-50 border border-slate-200 rounded-xl overflow-hidden hover:border-brand-500 hover:shadow-md transition flex flex-col text-left">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                            <img
                                src="https://lh3.googleusercontent.com/d/1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul=w600"
                                data-drive-id="1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul"
                                alt="Cầu thang kính"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveFallback(this, 'Cau Thang Kinh', 'e2e8f0', '0d3b75')"
                            >
                        </div>
                        <div class="p-2.5 text-center flex-1 flex items-center justify-center w-full">
                            <h3 class="text-[11px] sm:text-xs font-bold text-brand-800 uppercase leading-tight group-hover:text-brand-600">
                                Cầu Thang Kính
                            </h3>
                        </div>
                    </button>

                    <!-- Danh mục 5: Kính ốp bếp -->
                    <button type="button" onclick="selectCategoryQuote('Kính ốp bếp')" class="group bg-slate-50 border border-slate-200 rounded-xl overflow-hidden hover:border-brand-500 hover:shadow-md transition flex flex-col text-left">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                            <img
                                src="https://lh3.googleusercontent.com/d/1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb=w600"
                                data-drive-id="1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb"
                                alt="Kính ốp bếp"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveFallback(this, 'Kinh Op Bep', 'e2e8f0', '0d3b75')"
                            >
                        </div>
                        <div class="p-2.5 text-center flex-1 flex items-center justify-center w-full">
                            <h3 class="text-[11px] sm:text-xs font-bold text-brand-800 uppercase leading-tight group-hover:text-brand-600">
                                Kính Ốp Bếp
                            </h3>
                        </div>
                    </button>

                    <!-- Danh mục 6: Phòng tắm kính -->
                    <button type="button" onclick="selectCategoryQuote('Phòng tắm kính')" class="group bg-slate-50 border border-slate-200 rounded-xl overflow-hidden hover:border-brand-500 hover:shadow-md transition flex flex-col text-left">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                            <img
                                src="https://lh3.googleusercontent.com/d/1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH=w600"
                                data-drive-id="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
                                alt="Phòng tắm kính"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveFallback(this, 'Phong Tam Kinh', 'e2e8f0', '0d3b75')"
                            >
                        </div>
                        <div class="p-2.5 text-center flex-1 flex items-center justify-center w-full">
                            <h3 class="text-[11px] sm:text-xs font-bold text-brand-800 uppercase leading-tight group-hover:text-brand-600">
                                Phòng Tắm Kính
                            </h3>
                        </div>
                    </button>
                </div>
            </div>
        </section>

        <!-- =====================================================================
             UX BUILDER: BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG
             2 cột trên điện thoại, có Giá + Giảm giá % góc trên bên trái, không cắt chữ
        ====================================================================== -->
        <section id="san-pham-xingfa" class="py-10 sm:py-12 bg-slate-50">
            <div class="ux-container">
                <div class="text-center mb-6">
                    <h2 class="ux-section-title text-lg sm:text-2xl font-extrabold text-brand-800 uppercase">
                        Báo Giá Cửa Nhôm Xingfa Đà Nẵng
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-600 mt-2">
                        Nhôm Xingfa nhập khẩu tem đỏ chính hãng, phụ kiện đồng bộ, lắp đặt miễn phí tại Đà Nẵng
                    </p>
                </div>

                <!-- Bộ lọc nhanh sản phẩm -->
                <div class="flex flex-wrap items-center justify-center gap-2 mb-6" id="product-filters">
                    <button type="button" onclick="filterProductByKey('all')" data-filter="all" class="product-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-brand-700 text-white transition">
                        Tất cả mẫu cửa
                    </button>
                    <button type="button" onclick="filterProductByKey('mo-quay')" data-filter="mo-quay" class="product-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-white text-slate-700 border border-slate-300 hover:border-brand-600 transition">
                        Cửa đi mở quay
                    </button>
                    <button type="button" onclick="filterProductByKey('xep-truot')" data-filter="xep-truot" class="product-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-white text-slate-700 border border-slate-300 hover:border-brand-600 transition">
                        Cửa đi xếp trượt
                    </button>
                    <button type="button" onclick="filterProductByKey('mo-hat')" data-filter="mo-hat" class="product-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-white text-slate-700 border border-slate-300 hover:border-brand-600 transition">
                        Cửa sổ mở hất
                    </button>
                </div>

                <!-- Lưới Sản phẩm: 2 cột trên mobile, 3 cột trên tablet/desktop -->
                <div id="product-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                    <!-- Được render bằng JavaScript để hỗ trợ lọc & xem chi tiết nhanh -->
                </div>
            </div>
        </section>

        <!-- =====================================================================
             UX BUILDER: GIỚI THIỆU CÔNG TY TNHH MTV NĂM PHI GLASS & THỐNG KÊ
        ====================================================================== -->
        <section id="gioi-thieu" class="py-10 sm:py-12 bg-white border-y border-slate-200/80">
            <div class="ux-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                    <!-- Cột trái: Nội dung giới thiệu doanh nghiệp -->
                    <div class="lg:col-span-7 space-y-4">
                        <p class="text-xs font-bold uppercase tracking-wider text-brand-600">
                            Giới Thiệu Về Chúng Tôi
                        </p>
                        <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-800 leading-tight">
                            CÔNG TY TNHH MTV NĂM PHI GLASS – NHÔM KÍNH UY TÍN ĐÀ NẴNG
                        </h2>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            <strong>NĂM PHI GLASS</strong> tiền thân là xưởng sản xuất nhôm kính với nhiều năm kinh nghiệm trong lĩnh vực tư vấn, thiết kế và thi công lắp đặt các hạng mục: <strong>Cửa nhôm Xingfa nhập khẩu 100%, cửa kính cường lực, cửa nhựa lõi thép, cửa kính tự động, cầu thang kính, phòng tắm kính và kính ốp bếp</strong> tại Đà Nẵng và khu vực Miền Trung.
                        </p>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Với phương châm <strong>“Chất lượng là số 1, thương hiệu là mãi mãi”</strong> cùng hệ thống máy móc gia công đồng bộ hiện đại và đội ngũ kỹ sư, thợ lành nghề tận tâm, chúng tôi cam kết mang đến công trình đạt chuẩn kỹ thuật, thẩm mỹ tinh tế, an toàn tuyệt đối và giá thành cạnh tranh nhất.
                        </p>

                        <!-- Cam kết dịch vụ ngắn gọn -->
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 pt-2">
                            <div class="flex items-start gap-2.5 p-3 rounded-xl bg-slate-50 border border-slate-200/80">
                                <i class="fa-solid fa-circle-check text-brand-600 mt-0.5"></i>
                                <div>
                                    <p class="text-xs sm:text-sm font-bold text-slate-800">Khảo sát &amp; Lắp đặt miễn phí</p>
                                    <p class="text-xs text-slate-500">Đo đạc tận nơi tại Đà Nẵng</p>
                                </div>
                            </div>
                            <div class="flex items-start gap-2.5 p-3 rounded-xl bg-slate-50 border border-slate-200/80">
                                <i class="fa-solid fa-shield-halved text-brand-600 mt-0.5"></i>
                                <div>
                                    <p class="text-xs sm:text-sm font-bold text-slate-800">Bảo hành chính hãng dài hạn</p>
                                    <p class="text-xs text-slate-500">Hỗ trợ bảo trì nhanh 24/7</p>
                                </div>
                            </div>
                            <div class="flex items-start gap-2.5 p-3 rounded-xl bg-slate-50 border border-slate-200/80">
                                <i class="fa-solid fa-award text-brand-600 mt-0.5"></i>
                                <div>
                                    <p class="text-xs sm:text-sm font-bold text-slate-800">Vật tư chuẩn 100% chính hãng</p>
                                    <p class="text-xs text-slate-500">Nhôm Xingfa, phụ kiện Kinlong, kính chuẩn</p>
                                </div>
                            </div>
                            <div class="flex items-start gap-2.5 p-3 rounded-xl bg-slate-50 border border-slate-200/80">
                                <i class="fa-solid fa-tags text-brand-600 mt-0.5"></i>
                                <div>
                                    <p class="text-xs sm:text-sm font-bold text-slate-800">Giá gốc trực tiếp tại xưởng</p>
                                    <p class="text-xs text-slate-500">Báo giá minh bạch, không phát sinh</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Cột phải: Khối số liệu Flatsome -->
                    <div class="lg:col-span-5">
                        <div class="bg-brand-800 text-white rounded-2xl p-6 sm:p-8 shadow-lg">
                            <div class="flex items-center gap-3 pb-5 mb-5 border-b border-white/15">
                                <div class="bg-white rounded-lg p-1.5 shrink-0">
                                    <img
                                        src="https://lh3.googleusercontent.com/d/1owRe16iBfMIQhi78Zmpg_kwaW6rsVUKJ=w300"
                                        data-drive-id="1owRe16iBfMIQhi78Zmpg_kwaW6rsVUKJ"
                                        alt="Năm Phi Glass"
                                        class="h-9 w-auto object-contain"
                                        onerror="handleDriveFallback(this, 'NPG', '0d3b75', 'ffffff')"
                                    >
                                </div>
                                <div>
                                    <p class="font-bold text-sm sm:text-base">NĂM PHI GLASS ĐÀ NẴNG</p>
                                    <p class="text-xs text-sky-200">Mang thương hiệu đến mọi công trình</p>
                                </div>
                            </div>

                            <div class="grid grid-cols-2 gap-4">
                                <div class="bg-white/10 rounded-xl p-4 text-center">
                                    <p class="text-2xl sm:text-3xl font-extrabold text-sky-300">150+</p>
                                    <p class="text-xs text-slate-100 mt-1">Dự án đã hoàn thành</p>
                                </div>
                                <div class="bg-white/10 rounded-xl p-4 text-center">
                                    <p class="text-2xl sm:text-3xl font-extrabold text-sky-300">50+</p>
                                    <p class="text-xs text-slate-100 mt-1">Nhân sự kinh nghiệm</p>
                                </div>
                                <div class="bg-white/10 rounded-xl p-4 text-center">
                                    <p class="text-2xl sm:text-3xl font-extrabold text-sky-300">100+</p>
                                    <p class="text-xs text-slate-100 mt-1">Sản phẩm chất lượng</p>
                                </div>
                                <div class="bg-white/10 rounded-xl p-4 text-center">
                                    <p class="text-2xl sm:text-3xl font-extrabold text-sky-300">100%</p>
                                    <p class="text-xs text-slate-100 mt-1">Khách hàng hài lòng</p>
                                </div>
                            </div>

                            <div class="mt-5 pt-4 border-t border-white/15 flex flex-wrap items-center justify-between gap-2 text-xs">
                                <span class="text-sky-200"><i class="fa-solid fa-location-dot mr-1"></i> Hòa Tiến, Đà Nẵng</span>
                                <a href="tel:0938363345" class="font-bold text-white hover:text-sky-200">
                                    <i class="fa-solid fa-phone mr-1"></i> 0938.363.345
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- =====================================================================
             UX BUILDER: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (6 CÔNG TRÌNH THỰC TẾ)
        ====================================================================== -->
        <section id="cong-trinh" class="py-10 sm:py-12 bg-slate-50">
            <div class="ux-container">
                <div class="text-center mb-7">
                    <h2 class="ux-section-title text-lg sm:text-2xl font-extrabold text-brand-800 uppercase">
                        Các Dự Án Tiêu Biểu Tại Đà Nẵng
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-600 mt-2">
                        Những công trình khách sạn, resort và tổ hợp cao cấp được thi công bởi đội ngũ kỹ thuật Năm Phi Glass
                    </p>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-6" id="projects-grid">
                    <!-- Dự án 1 -->
                    <article onclick="openProjectModal('DỰ ÁN KHÁCH SẠN RUBY LIGHT', '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ', 'Thi công toàn bộ hệ thống cửa nhôm Xingfa nhập khẩu, vách kính mặt dựng và phòng tắm kính cường lực 10mm cho Khách sạn Ruby Light Đà Nẵng.')" class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition flex flex-col">
                        <div class="aspect-[16/10] overflow-hidden bg-slate-200">
                            <img
                                src="https://lh3.googleusercontent.com/d/1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ=w800"
                                data-drive-id="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ"
                                alt="DỰ ÁN KHÁCH SẠN RUBY LIGHT"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                                onerror="handleDriveFallback(this, 'Khach San Ruby Light', '0d3b75', 'ffffff')"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <h3 class="text-sm font-bold text-brand-800 leading-snug group-hover:text-brand-600">
                                DỰ ÁN KHÁCH SẠN RUBY LIGHT
                            </h3>
                            <p class="text-xs text-slate-500 mt-2 flex items-center justify-between">
                                <span><i class="fa-solid fa-location-dot text-brand-600 mr-1"></i>Đà Nẵng</span>
                                <span class="text-brand-600 font-semibold">Xem chi tiết &rarr;</span>
                            </p>
                        </div>
                    </article>

                    <!-- Dự án 2 -->
                    <article onclick="openProjectModal('DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”', '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ', 'Cung cấp và lắp đặt hạng mục cửa đi nhôm Xingfa chống ăn mòn, vách kính lớn đón sáng tự nhiên và cabin tắm kính cao cấp đạt chuẩn Resort 4 sao.')" class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition flex flex-col">
                        <div class="aspect-[16/10] overflow-hidden bg-slate-200">
                            <img
                                src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ=w800"
                                data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                                alt="DỰ ÁN RESORT MỸ SƠN 4 SAO MY SON HERITAGE RESORT & SPA"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                                onerror="handleDriveFallback(this, 'My Son Heritage Resort', '0d3b75', 'ffffff')"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <h3 class="text-sm font-bold text-brand-800 leading-snug group-hover:text-brand-600">
                                DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT &amp; SPA”
                            </h3>
                            <p class="text-xs text-slate-500 mt-2 flex items-center justify-between">
                                <span><i class="fa-solid fa-location-dot text-brand-600 mr-1"></i>Đà Nẵng - Quảng Nam</span>
                                <span class="text-brand-600 font-semibold">Xem chi tiết &rarr;</span>
                            </p>
                        </div>
                    </article>

                    <!-- Dự án 3 -->
                    <article onclick="openProjectModal('THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE', '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy', 'Hoàn thiện mặt dựng kính cường lực chịu lực gió biển, cửa nhôm Xingfa cách âm chuẩn khách sạn và lan can kính an toàn tại Khách sạn Goden Line.')" class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition flex flex-col">
                        <div class="aspect-[16/10] overflow-hidden bg-slate-200">
                            <img
                                src="https://lh3.googleusercontent.com/d/1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy=w800"
                                data-drive-id="1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy"
                                alt="THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                                onerror="handleDriveFallback(this, 'Khach San Goden Line', '0d3b75', 'ffffff')"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <h3 class="text-sm font-bold text-brand-800 leading-snug group-hover:text-brand-600">
                                THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE
                            </h3>
                            <p class="text-xs text-slate-500 mt-2 flex items-center justify-between">
                                <span><i class="fa-solid fa-location-dot text-brand-600 mr-1"></i>Đà Nẵng</span>
                                <span class="text-brand-600 font-semibold">Xem chi tiết &rarr;</span>
                            </p>
                        </div>
                    </article>

                    <!-- Dự án 4 -->
                    <article onclick="openProjectModal('THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA', '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64', 'Thi công trọn gói cửa nhôm Xingfa hệ 55, cửa kính tự động sảnh chính và vách kính phòng tắm cho Khách sạn & Căn hộ Jolia Đà Nẵng.')" class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition flex flex-col">
                        <div class="aspect-[16/10] overflow-hidden bg-slate-200">
                            <img
                                src="https://lh3.googleusercontent.com/d/1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64=w800"
                                data-drive-id="1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64"
                                alt="THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                                onerror="handleDriveFallback(this, 'Khach San Jolia', '0d3b75', 'ffffff')"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <h3 class="text-sm font-bold text-brand-800 leading-snug group-hover:text-brand-600">
                                THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA
                            </h3>
                            <p class="text-xs text-slate-500 mt-2 flex items-center justify-between">
                                <span><i class="fa-solid fa-location-dot text-brand-600 mr-1"></i>Đà Nẵng</span>
                                <span class="text-brand-600 font-semibold">Xem chi tiết &rarr;</span>
                            </p>
                        </div>
                    </article>

                    <!-- Dự án 5 -->
                    <article onclick="openProjectModal('THI CÔNG DỰ ÁN KHÁCH SẠN SOHO', '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt', 'Thiết kế và lắp đặt hệ cửa nhôm kính cao cấp cách âm tuyệt đối, lan can kính cường lực mặt tiền sang trọng cho Khách sạn Soho Boutique Đà Nẵng.')" class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition flex flex-col">
                        <div class="aspect-[16/10] overflow-hidden bg-slate-200">
                            <img
                                src="https://lh3.googleusercontent.com/d/1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt=w800"
                                data-drive-id="1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt"
                                alt="THI CÔNG DỰ ÁN KHÁCH SẠN SOHO"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                                onerror="handleDriveFallback(this, 'Khach San Soho', '0d3b75', 'ffffff')"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <h3 class="text-sm font-bold text-brand-800 leading-snug group-hover:text-brand-600">
                                THI CÔNG DỰ ÁN KHÁCH SẠN SOHO
                            </h3>
                            <p class="text-xs text-slate-500 mt-2 flex items-center justify-between">
                                <span><i class="fa-solid fa-location-dot text-brand-600 mr-1"></i>Đà Nẵng</span>
                                <span class="text-brand-600 font-semibold">Xem chi tiết &rarr;</span>
                            </p>
                        </div>
                    </article>

                    <!-- Dự án 6 -->
                    <article onclick="openProjectModal('THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL', '1za_IJpAm850uulT6IuhBsk1THb3LuPuc', 'Thi công đồng bộ cửa nhôm Xingfa chịu mặn vùng biển, cửa kính cường lực sảnh đón khách và toàn bộ kính nội thất tại Raon Đà Nẵng Beach Hotel.')" class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition flex flex-col">
                        <div class="aspect-[16/10] overflow-hidden bg-slate-200">
                            <img
                                src="https://lh3.googleusercontent.com/d/1za_IJpAm850uulT6IuhBsk1THb3LuPuc=w800"
                                data-drive-id="1za_IJpAm850uulT6IuhBsk1THb3LuPuc"
                                alt="THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                                onerror="handleDriveFallback(this, 'Raon Da Nang Beach Hotel', '0d3b75', 'ffffff')"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <h3 class="text-sm font-bold text-brand-800 leading-snug group-hover:text-brand-600">
                                THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL
                            </h3>
                            <p class="text-xs text-slate-500 mt-2 flex items-center justify-between">
                                <span><i class="fa-solid fa-location-dot text-brand-600 mr-1"></i>Đà Nẵng</span>
                                <span class="text-brand-600 font-semibold">Xem chi tiết &rarr;</span>
                            </p>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <!-- =====================================================================
             UX BUILDER: FORM YÊU CẦU TƯ VẤN & ĐĂNG KÝ NHẬN BÁO GIÁ TRANG CHỦ
        ====================================================================== -->
        <section id="bao-gia" class="py-10 sm:py-12 bg-brand-800 text-white">
            <div class="ux-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    <!-- Cột thông tin hỗ trợ báo giá -->
                    <div class="lg:col-span-5 space-y-4">
                        <p class="text-xs font-bold uppercase tracking-widest text-sky-300">
                            Tư Vấn Miễn Phí 24/7
                        </p>
                        <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold leading-tight">
                            ĐĂNG KÝ NHẬN BÁO GIÁ &amp; KHẢO SÁT CÔNG TRÌNH
                        </h2>
                        <p class="text-sm text-slate-200 leading-relaxed">
                            Quý khách vui lòng để lại thông tin hạng mục cần thi công. Kỹ thuật viên <strong>Năm Phi Glass</strong> sẽ liên hệ tư vấn phương án tối ưu và gửi bảng báo giá chi tiết trong vòng 15 phút.
                        </p>
                        <div class="space-y-2.5 pt-2 text-sm">
                            <div class="flex items-center gap-3">
                                <span class="w-9 h-9 rounded-lg bg-white/10 flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-phone-volume text-sky-300"></i>
                                </span>
                                <div>
                                    <p class="text-xs text-sky-200">Hotline / Zalo tư vấn nhanh</p>
                                    <a href="tel:0938363345" class="font-bold text-base hover:text-sky-200">0938.363.345</a>
                                </div>
                            </div>
                            <div class="flex items-center gap-3">
                                <span class="w-9 h-9 rounded-lg bg-white/10 flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-location-dot text-sky-300"></i>
                                </span>
                                <div>
                                    <p class="text-xs text-sky-200">Xưởng sản xuất &amp; Văn phòng</p>
                                    <p class="font-semibold">Hòa Tiến, Đà Nẵng</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Cột Form Báo Giá -->
                    <div class="lg:col-span-7">
                        <form id="quote-form" onsubmit="handleQuoteSubmit(event)" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl space-y-4">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="quote-name" class="block text-xs font-bold text-slate-700 mb-1.5">Họ và tên *</label>
                                    <input
                                        id="quote-name"
                                        type="text"
                                        required
                                        placeholder="Nhập họ tên của bạn"
                                        class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none"
                                    >
                                </div>
                                <div>
                                    <label for="quote-phone" class="block text-xs font-bold text-slate-700 mb-1.5">Số điện thoại / Zalo *</label>
                                    <input
                                        id="quote-phone"
                                        type="tel"
                                        required
                                        placeholder="Ví dụ: 0938.363.345"
                                        class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none"
                                    >
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="quote-category" class="block text-xs font-bold text-slate-700 mb-1.5">Hạng mục quan tâm</label>
                                    <select
                                        id="quote-category"
                                        class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none"
                                    >
                                        <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa</option>
                                        <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                                        <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                                        <option value="Cửa kính tự động">Cửa kính tự động</option>
                                        <option value="Cầu thang kính">Cầu thang kính</option>
                                        <option value="Kính ốp bếp">Kính ốp bếp</option>
                                        <option value="Phòng tắm kính">Phòng tắm kính</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="quote-address" class="block text-xs font-bold text-slate-700 mb-1.5">Địa chỉ công trình</label>
                                    <input
                                        id="quote-address"
                                        type="text"
                                        placeholder="Quận / Huyện tại Đà Nẵng..."
                                        class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none"
                                    >
                                </div>
                            </div>

                            <div>
                                <label for="quote-note" class="block text-xs font-bold text-slate-700 mb-1.5">Yêu cầu chi tiết (kích thước, số lượng bộ cửa...)</label>
                                <textarea
                                    id="quote-note"
                                    rows="3"
                                    placeholder="Nhập yêu cầu hoặc kích thước dự kiến để nhận báo giá chính xác nhất..."
                                    class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none resize-none"
                                ></textarea>
                            </div>

                            <div id="quote-feedback" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium"></div>

                            <button
                                type="submit"
                                class="w-full bg-brand-700 hover:bg-brand-800 text-white font-bold text-sm py-3 px-6 rounded-lg shadow transition flex items-center justify-center gap-2"
                            >
                                <i class="fa-solid fa-paper-plane"></i>
                                <span>GỬI YÊU CẦU BÁO GIÁ NGAY</span>
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- =====================================================================
             UX BUILDER: DANH MỤC CÁC BÀI VIẾT & TIN TỨC NỔI BẬT TRANG CHỦ
        ====================================================================== -->
        <section id="tin-tuc" class="py-10 sm:py-12 bg-white border-b border-slate-200/80">
            <div class="ux-container">
                <div class="text-center mb-6">
                    <h2 class="ux-section-title text-lg sm:text-2xl font-extrabold text-brand-800 uppercase">
                        Tin Tức &amp; Kiến Thức Nhôm Kính
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2">
                        Cập nhật kinh nghiệm lựa chọn cửa nhôm Xingfa, kính cường lực và báo giá mới nhất
                    </p>
                </div>

                <!-- Danh mục bài viết -->
                <div class="flex flex-wrap items-center justify-center gap-2 mb-7">
                    <button type="button" onclick="filterArticles('all')" data-article-cat="all" class="article-cat-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-brand-700 text-white transition">
                        Tất cả bài viết
                    </button>
                    <button type="button" onclick="filterArticles('xingfa')" data-article-cat="xingfa" class="article-cat-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 transition">
                        Kiến thức nhôm Xingfa
                    </button>
                    <button type="button" onclick="filterArticles('kinh')" data-article-cat="kinh" class="article-cat-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 transition">
                        Kính cường lực &amp; Nội thất
                    </button>
                    <button type="button" onclick="filterArticles('kinh-nghiem')" data-article-cat="kinh-nghiem" class="article-cat-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 transition">
                        Kinh nghiệm thi công
                    </button>
                </div>

                <!-- Lưới bài viết -->
                <div id="articles-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
                    <!-- Được render bằng JavaScript -->
                </div>
            </div>
        </section>

        <!-- =====================================================================
             UX BUILDER: ĐỐI TÁC CỦA CHÚNG TÔI (6 LOGO ĐỐI TÁC)
        ====================================================================== -->
        <section class="py-9 sm:py-10 bg-slate-50 border-b border-slate-200/80">
            <div class="ux-container">
                <div class="text-center mb-6">
                    <h2 class="ux-section-title text-lg sm:text-xl font-extrabold text-brand-800 uppercase">
                        Đối Tác Của Chúng Tôi
                    </h2>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
                    <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:shadow transition">
                        <img src="https://lh3.googleusercontent.com/d/13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk=w400" data-drive-id="13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" alt="Đối tác Năm Phi Glass 1" class="max-h-full max-w-full object-contain" onerror="handleDriveFallback(this, 'Doi Tac 1', 'f1f5f9', '0d3b75')">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:shadow transition">
                        <img src="https://lh3.googleusercontent.com/d/1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq=w400" data-drive-id="1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" alt="Đối tác Năm Phi Glass 2" class="max-h-full max-w-full object-contain" onerror="handleDriveFallback(this, 'Doi Tac 2', 'f1f5f9', '0d3b75')">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:shadow transition">
                        <img src="https://lh3.googleusercontent.com/d/1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn=w400" data-drive-id="1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" alt="Đối tác Năm Phi Glass 3" class="max-h-full max-w-full object-contain" onerror="handleDriveFallback(this, 'Doi Tac 3', 'f1f5f9', '0d3b75')">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:shadow transition">
                        <img src="https://lh3.googleusercontent.com/d/1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT=w400" data-drive-id="1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" alt="Đối tác Năm Phi Glass 4" class="max-h-full max-w-full object-contain" onerror="handleDriveFallback(this, 'Doi Tac 4', 'f1f5f9', '0d3b75')">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:shadow transition">
                        <img src="https://lh3.googleusercontent.com/d/1SDcarhnX0yypmqdbawICjYBRtFnKngn-=w400" data-drive-id="1SDcarhnX0yypmqdbawICjYBRtFnKngn-" alt="Đối tác Năm Phi Glass 5" class="max-h-full max-w-full object-contain" onerror="handleDriveFallback(this, 'Doi Tac 5', 'f1f5f9', '0d3b75')">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:shadow transition">
                        <img src="https://lh3.googleusercontent.com/d/1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg=w400" data-drive-id="1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" alt="Đối tác Năm Phi Glass 6" class="max-h-full max-w-full object-contain" onerror="handleDriveFallback(this, 'Doi Tac 6', 'f1f5f9', '0d3b75')">
                    </div>
                </div>
            </div>
        </section>

        <!-- =====================================================================
             UX BUILDER: BẢN ĐỒ GOOGLE MAPS & FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ
        ====================================================================== -->
        <section id="lien-he" class="py-10 sm:py-12 bg-white">
            <div class="ux-container">
                <div class="text-center mb-7">
                    <h2 class="ux-section-title text-lg sm:text-2xl font-extrabold text-brand-800 uppercase">
                        Bản Đồ Chỉ Đường &amp; Fanpage Chính Thức
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2">
                        Ghé thăm xưởng sản xuất tại Hòa Tiến, Đà Nẵng hoặc theo dõi các công trình mới nhất trên Fanpage
                    </p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                    <!-- Cột 1: Google Map trực quan ngoài trang chủ -->
                    <div class="lg:col-span-7 bg-slate-50 border border-slate-200 rounded-2xl overflow-hidden shadow-sm flex flex-col">
                        <div class="px-4 py-3 bg-brand-800 text-white flex flex-wrap items-center justify-between gap-2">
                            <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
                                <i class="fa-solid fa-map-location-dot text-sky-300"></i>
                                <span>Bản Đồ Google Maps – Hòa Tiến, Đà Nẵng</span>
                            </div>
                            <a
                                href="https://www.google.com/maps/search/?api=1&query=Hòa+Tiến,+Đà+Nẵng"
                                target="_blank"
                                rel="noopener noreferrer"
                                class="text-xs text-sky-200 hover:text-white underline"
                            >
                                Mở chỉ đường &rarr;
                            </a>
                        </div>
                        <div class="w-full h-[300px] sm:h-[360px] flex-1 bg-slate-200">
                            <iframe
                                title="Bản đồ CÔNG TY TNHH MTV NĂM PHI GLASS - Hòa Tiến, Đà Nẵng"
                                src="https://maps.google.com/maps?q=H%C3%B2a+Ti%E1%BA%BFn,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=14&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade"
                            ></iframe>
                        </div>
                    </div>

                    <!-- Cột 2: Fanpage Facebook trực tiếp ngoài trang chủ -->
                    <div class="lg:col-span-5 bg-slate-50 border border-slate-200 rounded-2xl overflow-hidden shadow-sm flex flex-col">
                        <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between gap-2">
                            <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
                                <i class="fa-brands fa-facebook text-base"></i>
                                <span>Fanpage Facebook Năm Phi Glass</span>
                            </div>
                            <a
                                href="https://www.facebook.com/profile.php?id=61596061495317"
                                target="_blank"
                                rel="noopener noreferrer"
                                class="text-xs bg-white/20 hover:bg-white/30 px-2.5 py-1 rounded-md font-semibold transition"
                            >
                                Truy cập
                            </a>
                        </div>

                        <!-- Khung nhận diện Fanpage luôn hiển thị đẹp + Facebook Page Plugin -->
                        <div class="p-4 flex-1 flex flex-col justify-between gap-4">
                            <div class="bg-white border border-slate-200 rounded-xl p-4 shadow-sm">
                                <div class="flex items-center gap-3">
                                    <img
                                        src="https://lh3.googleusercontent.com/d/1owRe16iBfMIQhi78Zmpg_kwaW6rsVUKJ=w300"
                                        data-drive-id="1owRe16iBfMIQhi78Zmpg_kwaW6rsVUKJ"
                                        alt="Fanpage CÔNG TY TNHH MTV NĂM PHI GLASS"
                                        class="w-14 h-14 rounded-xl object-contain border border-slate-200 p-1 bg-white shrink-0"
                                        onerror="handleDriveFallback(this, 'NPG', '0d3b75', 'ffffff')"
                                    >
                                    <div class="min-w-0">
                                        <h3 class="text-sm font-extrabold text-brand-800 leading-snug">
                                            CÔNG TY TNHH MTV NĂM PHI GLASS
                                        </h3>
                                        <p class="text-xs text-slate-500 mt-0.5">
                                            Nhôm Kính Xingfa • Kính Cường Lực Đà Nẵng
                                        </p>
                                        <p class="text-xs text-brand-600 font-semibold mt-1">
                                            <i class="fa-solid fa-phone mr-1"></i>0938.363.345
                                        </p>
                                    </div>
                                </div>

                                <!-- Nhúng Facebook Page Plugin chuẩn -->
                                <div class="mt-3 rounded-lg overflow-hidden border border-slate-100 bg-slate-50">
                                    <iframe
                                        title="Fanpage Facebook CÔNG TY TNHH MTV NĂM PHI GLASS"
                                        src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D61596061495317&tabs=timeline&width=500&height=175&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                        class="w-full h-[175px] border-0"
                                        scrolling="no"
                                        frameborder="0"
                                        allowfullscreen="true"
                                        allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                                        loading="lazy"
                                    ></iframe>
                                </div>
                            </div>

                            <div class="grid grid-cols-2 gap-2.5">
                                <a
                                    href="https://www.facebook.com/profile.php?id=61596061495317"
                                    target="_blank"
                                    rel="noopener noreferrer"
                                    class="inline-flex items-center justify-center gap-2 bg-[#1877F2] hover:bg-[#1465cc] text-white text-xs sm:text-sm font-bold py-2.5 px-3 rounded-lg transition"
                                >
                                    <i class="fa-brands fa-facebook-f"></i>
                                    <span>Theo dõi Fanpage</span>
                                </a>
                                <a
                                    href="https://zalo.me/0938363345"
                                    target="_blank"
                                    rel="noopener noreferrer"
                                    class="inline-flex items-center justify-center gap-2 bg-[#0068FF] hover:bg-[#0054cc] text-white text-xs sm:text-sm font-bold py-2.5 px-3 rounded-lg transition"
                                >
                                    <i class="fa-solid fa-comment-dots"></i>
                                    <span>Nhắn tin Zalo</span>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- =====================================================================
         UX BUILDER: FOOTER 4 CỘT CHUẨN FLATSOME
    ====================================================================== -->
    <footer class="bg-brand-900 text-slate-200 pt-10 pb-6 border-t-4 border-brand-600">
        <div class="ux-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin liên hệ -->
                <div class="space-y-3">
                    <div class="inline-flex items-center gap-2.5 bg-white px-3 py-2 rounded-xl">
                        <img
                            src="https://lh3.googleusercontent.com/d/1owRe16iBfMIQhi78Zmpg_kwaW6rsVUKJ=w300"
                            data-drive-id="1owRe16iBfMIQhi78Zmpg_kwaW6rsVUKJ"
                            alt="Logo Năm Phi Glass"
                            class="h-9 w-auto object-contain"
                            onerror="handleDriveFallback(this, 'NAM PHI GLASS', '0d3b75', 'ffffff')"
                        >
                        <span class="text-xs font-extrabold text-brand-800">NĂM PHI GLASS</span>
                    </div>
                    <h3 class="text-sm font-bold text-white uppercase pt-1">
                        CÔNG TY TNHH MTV NĂM PHI GLASS
                    </h3>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-sky-400 mt-1"></i>
                            <span>Địa chỉ: Hòa Tiến, Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-sky-400"></i>
                            <a href="tel:0938363345" class="hover:text-white font-semibold">Hotline: 0938.363.345</a>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-sky-400"></i>
                            <span>Website: namphiglass.com</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Cửa nhôm Xingfa -->
                <div>
                    <h3 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">
                        Cửa Nhôm Xingfa
                    </h3>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li><a href="#san-pham-xingfa" onclick="filterProductByKey('1-canh')" class="hover:text-sky-300 transition">Cửa nhôm xingfa 1 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProductByKey('2-canh')" class="hover:text-sky-300 transition">Cửa nhôm xingfa 2 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProductByKey('3-canh')" class="hover:text-sky-300 transition">Cửa nhôm xingfa 3 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProductByKey('4-canh')" class="hover:text-sky-300 transition">Cửa nhôm xingfa 4 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProductByKey('5-canh')" class="hover:text-sky-300 transition">Cửa nhôm xingfa 5 cánh</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục sản phẩm -->
                <div>
                    <h3 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">
                        Danh Mục Sản Phẩm
                    </h3>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li><a href="#san-pham-xingfa" class="hover:text-sky-300 transition">Cửa nhôm xingfa</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa nhựa lõi thép')" class="hover:text-sky-300 transition">Cửa nhựa lõi thép</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa kính tự động')" class="hover:text-sky-300 transition">Cửa kính tự động</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cầu thang kính')" class="hover:text-sky-300 transition">Cầu thang kính</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Kính ốp bếp')" class="hover:text-sky-300 transition">Kính ốp bếp</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Phòng tắm kính')" class="hover:text-sky-300 transition">Phòng tắm kính</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Liên kết nhanh -->
                <div>
                    <h3 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">
                        Hỗ Trợ Khách Hàng
                    </h3>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li><a href="#gioi-thieu" class="hover:text-sky-300 transition">Giới thiệu công ty</a></li>
                        <li><a href="#cong-trinh" class="hover:text-sky-300 transition">Công trình tiêu biểu</a></li>
                        <li><a href="#bao-gia" class="hover:text-sky-300 transition">Yêu cầu báo giá nhanh</a></li>
                        <li><a href="#tin-tuc" class="hover:text-sky-300 transition">Tin tức &amp; Tư vấn kỹ thuật</a></li>
                        <li>
                            <a href="https://www.facebook.com/profile.php?id=61596061495317" target="_blank" rel="noopener noreferrer" class="hover:text-sky-300 transition">
                                Fanpage Facebook chính thức
                            </a>
                        </li>
                    </ul>
                </div>
            </div>

            <!-- Bản quyền -->
            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
                <p>Copyright &copy; 2026 CÔNG TY TNHH MTV NĂM PHI GLASS (namphiglass.com). All rights reserved.</p>
                <p>Chuyên Nhôm Kính Xingfa &amp; Kính Cường Lực Tại Đà Nẵng</p>
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         - Trên máy tính: Cụm nút nổi gọn đẹp góc dưới bên phải
         - Trên điện thoại: Thanh liên hệ cố định dưới đáy dễ bấm bằng ngón tay
    ====================================================================== -->
    <!-- Phiên bản Máy tính / Tablet -->
    <div class="hidden md:flex fixed bottom-6 right-5 z-40 flex-col items-end gap-2.5">
        <a
            href="https://www.facebook.com/profile.php?id=61596061495317"
            target="_blank"
            rel="noopener noreferrer"
            class="group flex items-center gap-2.5 bg-[#1877F2] hover:bg-[#1465cc] text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition-transform hover:-translate-y-0.5"
            aria-label="Facebook Năm Phi Glass"
        >
            <i class="fa-brands fa-facebook-f text-base w-5 text-center"></i>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <a
            href="https://zalo.me/0938363345"
            target="_blank"
            rel="noopener noreferrer"
            class="group flex items-center gap-2.5 bg-[#0068FF] hover:bg-[#0054cc] text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition-transform hover:-translate-y-0.5"
            aria-label="Zalo 0938.363.345"
        >
            <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] text-[10px] font-extrabold inline-flex items-center justify-center">Z</span>
            <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <a
            href="tel:0938363345"
            class="hotline-pulse flex items-center gap-2.5 bg-red-600 hover:bg-red-700 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition-transform hover:-translate-y-0.5"
            aria-label="Gọi Hotline 0938.363.345"
        >
            <i class="fa-solid fa-phone-volume text-base w-5 text-center"></i>
            <span class="text-xs font-bold whitespace-nowrap">0938.363.345</span>
        </a>
    </div>

    <!-- Phiên bản Điện thoại: Thanh liên hệ nổi cố định dưới cùng -->
    <div class="md:hidden fixed bottom-0 left-0 right-0 z-40 bg-white border-t border-slate-200 shadow-[0_-4px_16px_rgba(0,0,0,0.08)] px-2 py-2">
        <div class="grid grid-cols-3 gap-2">
            <a
                href="tel:0938363345"
                class="flex items-center justify-center gap-1.5 bg-red-600 active:bg-red-700 text-white font-bold text-xs py-2.5 rounded-xl shadow-sm"
            >
                <i class="fa-solid fa-phone-volume"></i>
                <span>Hotline</span>
            </a>
            <a
                href="https://zalo.me/0938363345"
                target="_blank"
                rel="noopener noreferrer"
                class="flex items-center justify-center gap-1.5 bg-[#0068FF] active:bg-[#0054cc] text-white font-bold text-xs py-2.5 rounded-xl shadow-sm"
            >
                <span class="w-4 h-4 rounded-full bg-white text-[#0068FF] text-[9px] font-extrabold inline-flex items-center justify-center">Z</span>
                <span>Zalo</span>
            </a>
            <a
                href="https://www.facebook.com/profile.php?id=61596061495317"
                target="_blank"
                rel="noopener noreferrer"
                class="flex items-center justify-center gap-1.5 bg-[#1877F2] active:bg-[#1465cc] text-white font-bold text-xs py-2.5 rounded-xl shadow-sm"
            >
                <i class="fa-brands fa-facebook-f"></i>
                <span>Facebook</span>
            </a>
        </div>
    </div>

    <!-- =====================================================================
         MODAL CHI TIẾT SẢN PHẨM / DỰ ÁN / BÀI VIẾT (KHÔNG DÙNG ALERT)
    ====================================================================== -->
    <div id="detail-modal" class="hidden fixed inset-0 z-50 bg-slate-900/65 backdrop-blur-xs flex items-center justify-center p-3 sm:p-5" onclick="closeDetailModal(event)">
        <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[88vh] overflow-y-auto shadow-2xl border border-slate-200" onclick="event.stopPropagation()">
            <div class="sticky top-0 bg-white px-5 py-3.5 border-b border-slate-200 flex items-center justify-between gap-3">
                <h3 id="modal-title" class="text-sm sm:text-base font-extrabold text-brand-800 leading-snug"></h3>
                <button type="button" onclick="hideDetailModal()" class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-600 flex items-center justify-center shrink-0" aria-label="Đóng cửa sổ">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="modal-body" class="p-5 space-y-4"></div>
        </div>
    </div>

    <!-- =====================================================================
         JAVASCRIPT ĐIỀU KHIỂN SLIDER, SẢN PHẨM, BÀI VIẾT, FORM & FALLBACK ẢNH
    ====================================================================== -->
    <script>
        /**
         * Cơ chế tải ảnh dự phòng cho Google Drive:
         * Lần 1 chuyển sang thumbnail Google Drive, lần 2 chuyển sang ảnh placeholder rõ ràng.
         */
        function handleDriveFallback(img, label, bgHex, textHex) {
            try {
                const attempt = parseInt(img.dataset.fallbackStep || '0', 10);
                const driveId = img.dataset.driveId;
                if (attempt === 0 && driveId) {
                    img.dataset.fallbackStep = '1';
                    img.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1000';
                } else {
                    img.onerror = null;
                    const encoded = encodeURIComponent(label || 'Nam Phi Glass');
                    img.src = 'https://placehold.co/800x600/' + (bgHex || '0d3b75') + '/' + (textHex || 'ffffff') + '?text=' + encoded;
                }
            } catch (err) {
                img.onerror = null;
            }
        }

        /* =========================================================
           1. DỮ LIỆU SẢN PHẨM CỬA NHÔM XINGFA (KÈM GIÁ & GIẢM GIÁ %)
        ========================================================== */
        const PRODUCTS = [
            {
                id: 'xingfa-1-canh',
                name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
                category: 'mo-quay',
                wingsKey: '1-canh',
                driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
                originalPrice: 2450000,
                salePrice: 2080000,
                discount: 15,
                unit: '₫/m²',
                specs: 'Nhôm Xingfa hệ 55 dày 2.0mm nhập khẩu, kính cường lực 8mm–10mm, phụ kiện Kinlong đồng bộ, gioăng EPDM kín khít cách âm.'
            },
            {
                id: 'xingfa-2-canh',
                name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
                category: 'mo-quay',
                wingsKey: '2-canh',
                driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
                originalPrice: 2480000,
                salePrice: 2100000,
                discount: 15,
                unit: '₫/m²',
                specs: 'Thiết kế mở quay 2 cánh thông thoáng cho mặt tiền nhà phố, ban công. Chống nước mưa tuyệt đối, sơn tĩnh điện bền màu.'
            },
            {
                id: 'xingfa-3-canh',
                name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
                category: 'mo-quay',
                wingsKey: '3-canh',
                driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
                originalPrice: 2520000,
                salePrice: 2150000,
                discount: 14,
                unit: '₫/m²',
                specs: 'Cửa đi mở quay 3 cánh kết cấu vững chắc, phù hợp không gian rộng, cách âm cách nhiệt vượt trội, khóa đa điểm an toàn.'
            },
            {
                id: 'xingfa-4-canh',
                name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
                category: 'mo-quay',
                wingsKey: '4-canh',
                driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                originalPrice: 2580000,
                salePrice: 2180000,
                discount: 16,
                unit: '₫/m²',
                specs: 'Dòng cửa chính 4 cánh sang trọng cho biệt thự, nhà phố hiện đại. Mở rộng tối đa diện tích đi lại, chịu áp lực gió mạnh.'
            },
            {
                id: 'xingfa-xep-truot',
                name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
                category: 'xep-truot',
                wingsKey: '5-canh',
                driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
                originalPrice: 2700000,
                salePrice: 2240000,
                discount: 17,
                unit: '₫/m²',
                specs: 'Nhôm Xingfa hệ 63 xếp trượt linh hoạt (3 cánh, 4 cánh, 5 cánh, 6 cánh), ray trượt êm nhẹ, tối ưu không gian mở cho resort và nhà vườn.'
            },
            {
                id: 'xingfa-mo-hat',
                name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
                category: 'mo-hat',
                wingsKey: '2-canh',
                driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
                originalPrice: 2350000,
                salePrice: 1950000,
                discount: 17,
                unit: '₫/m²',
                specs: 'Nhôm Xingfa hệ 55 dày 1.4mm, mở hất góc 45° có thanh hạn vị chống va đập gió bão, tránh hắt nước mưa hiệu quả.'
            }
        ];

        /* =========================================================
           2. DỮ LIỆU BÀI VIẾT TRANG CHỦ
        ========================================================== */
        const ARTICLES = [
            {
                id: 'bai-1',
                cat: 'xingfa',
                catLabel: 'Kiến thức nhôm Xingfa',
                date: '20/11/2026',
                driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
                title: 'Cửa nhôm Xingfa có phù hợp với khí hậu biển Đà Nẵng không?',
                excerpt: 'Tìm hiểu khả năng chống ăn mòn muối biển, chịu gió bão và độ bền sơn tĩnh điện của cửa nhôm Xingfa chính hãng.',
                content: 'Nhôm Xingfa nhập khẩu chính hãng được phủ lớp sơn tĩnh điện ngoài trời cao cấp theo tiêu chuẩn quốc tế, giúp bề mặt chống oxy hóa và chịu được hơi muối vùng biển Đà Nẵng. Kết hợp hệ gioăng EPDM kép và phụ kiện inox chống gỉ giúp cửa luôn kín nước, vận hành êm ái nhiều năm.'
            },
            {
                id: 'bai-2',
                cat: 'kinh',
                catLabel: 'Kính cường lực & Nội thất',
                date: '16/11/2026',
                driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
                title: 'Hướng dẫn chọn độ dày kính cường lực 8mm, 10mm, 12mm chuẩn kỹ thuật',
                excerpt: 'Nên chọn độ dày kính nào cho cửa chính, phòng tắm kính, cầu thang kính và kính ốp bếp để vừa an toàn vừa tiết kiệm?',
                content: 'Tùy theo từng vị trí lắp đặt: Kính ốp bếp thường dùng kính cường lực 8mm sơn chịu nhiệt; Phòng tắm kính và cửa nhôm Xingfa ưu tiên kính 8mm–10mm; Cửa kính cường lực bản lề sàn, mặt dựng và lan can cầu thang kính nên dùng kính 10mm–12mm để đảm bảo độ cứng vững tuyệt đối.'
            },
            {
                id: 'bai-3',
                cat: 'xingfa',
                catLabel: 'Kiến thức nhôm Xingfa',
                date: '10/11/2026',
                driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                title: 'So sánh cửa nhôm Xingfa với cửa gỗ và cửa nhựa lõi thép',
                excerpt: 'Phân tích ưu nhược điểm về độ bền, khả năng chống mối mọt, cong vênh và chi phí đầu tư giữa các loại cửa phổ biến.',
                content: 'So với cửa gỗ truyền thống dễ cong vênh, co ngót khi nắng mưa và tốn công bảo dưỡng, cửa nhôm Xingfa vượt trội về độ ổn định kích thước, không mối mọt, cách âm tốt và lấy sáng hiện đại. So với cửa nhựa lõi thép, khung nhôm Xingfa mảnh hơn nhưng chịu lực cao hơn rõ rệt cho các bộ cửa kích thước lớn.'
            },
            {
                id: 'bai-4',
                cat: 'kinh-nghiem',
                catLabel: 'Kinh nghiệm thi công',
                date: '05/11/2026',
                driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
                title: 'Quy trình khảo sát, sản xuất và nghiệm thu nhôm kính tại Năm Phi Glass',
                excerpt: '5 bước tiêu chuẩn giúp công trình hoàn thiện sắc nét, kín khít và bàn giao đúng tiến độ cam kết.',
                content: 'Tại CÔNG TY TNHH MTV NĂM PHI GLASS, mỗi công trình đều tuân thủ 5 bước: (1) Khảo sát đo đạc bằng thước laser miễn phí; (2) Lên bản vẽ kỹ thuật & báo giá minh bạch; (3) Gia công ép góc CNC tại xưởng Hòa Tiến; (4) Lắp đặt bơm keo chống thấm chuyên dụng; (5) Nghiệm thu bàn giao & kích hoạt bảo hành.'
            }
        ];

        function formatVND(num) {
            return num.toString().replace(/\B(?=(\d{3})+(?!\d))/g, '.');
        }

        /* Render danh sách sản phẩm (2 cột trên điện thoại, đầy đủ tên không bị cắt) */
        function renderProducts(filterKey) {
            const grid = document.getElementById('product-grid');
            if (!grid) return;

            const filtered = PRODUCTS.filter(function (item) {
                if (!filterKey || filterKey === 'all') return true;
                return item.category === filterKey || item.wingsKey === filterKey;
            });

            const listToRender = filtered.length > 0 ? filtered : PRODUCTS;

            grid.innerHTML = listToRender.map(function (p) {
                return `
                    <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-300 transition flex flex-col">
                        <!-- Khung ảnh sản phẩm kèm giảm giá % góc trên bên trái -->
                        <div class="relative aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <span class="absolute top-2 left-2 z-10 bg-red-600 text-white text-[11px] sm:text-xs font-extrabold px-2 py-0.5 rounded-md shadow">
                                -${p.discount}%
                            </span>
                            <img
                                src="https://lh3.googleusercontent.com/d/${p.driveId}=w700"
                                data-drive-id="${p.driveId}"
                                alt="${p.name}"
                                onclick="openProductModal('${p.id}')"
                                class="w-full h-full object-cover cursor-pointer hover:scale-105 transition duration-300"
                                onerror="handleDriveFallback(this, '${p.name}', 'f1f5f9', '0d3b75')"
                            >
                        </div>

                        <!-- Thông tin sản phẩm: Tên đầy đủ không bị tràn hay thiếu chữ -->
                        <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                            <div>
                                <h3
                                    onclick="openProductModal('${p.id}')"
                                    class="cursor-pointer text-[12.5px] sm:text-sm font-bold text-slate-800 hover:text-brand-700 leading-snug break-words"
                                >
                                    ${p.name}
                                </h3>
                            </div>

                            <div class="space-y-2 pt-1">
                                <!-- Giá khuyến mãi và giá gốc -->
                                <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                    <span class="text-sm sm:text-base font-extrabold text-red-600">
                                        ${formatVND(p.salePrice)}${p.unit}
                                    </span>
                                    <span class="text-[11px] sm:text-xs text-slate-400 line-through">
                                        ${formatVND(p.originalPrice)}₫
                                    </span>
                                </div>

                                <!-- Nút hành động gọn đẹp -->
                                <div class="grid grid-cols-2 gap-1.5">
                                    <button
                                        type="button"
                                        onclick="openProductModal('${p.id}')"
                                        class="w-full py-1.5 px-2 rounded-lg border border-brand-600 text-brand-700 hover:bg-brand-50 text-[11px] sm:text-xs font-bold transition"
                                    >
                                        Chi tiết
                                    </button>
                                    <button
                                        type="button"
                                        onclick="requestQuoteForProduct('${p.name}')"
                                        class="w-full py-1.5 px-2 rounded-lg bg-brand-700 hover:bg-brand-800 text-white text-[11px] sm:text-xs font-bold transition"
                                    >
                                        Báo giá
                                    </button>
                                </div>
                            </div>
                        </div>
                    </article>
                `;
            }).join('');
        }

        function filterProductByKey(key) {
            renderProducts(key);
            const buttons = document.querySelectorAll('.product-filter-btn');
            buttons.forEach(function (btn) {
                const active = btn.dataset.filter === key;
                if (active) {
                    btn.className = 'product-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-brand-700 text-white transition';
                } else {
                    btn.className = 'product-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-white text-slate-700 border border-slate-300 hover:border-brand-600 transition';
                }
            });
        }

        /* Render bài viết trang chủ */
        function renderArticles(catKey) {
            const grid = document.getElementById('articles-grid');
            if (!grid) return;

            const list = ARTICLES.filter(function (a) {
                return !catKey || catKey === 'all' || a.cat === catKey;
            });

            grid.innerHTML = list.map(function (art) {
                return `
                    <article onclick="openArticleModal('${art.id}')" class="group cursor-pointer bg-slate-50 rounded-xl border border-slate-200 overflow-hidden hover:shadow-md transition flex flex-col">
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img
                                src="https://lh3.googleusercontent.com/d/${art.driveId}=w600"
                                data-drive-id="${art.driveId}"
                                alt="${art.title}"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveFallback(this, 'Tin Tuc Nam Phi Glass', 'e2e8f0', '0d3b75')"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between gap-2">
                            <div>
                                <div class="flex items-center justify-between text-[11px] text-slate-500 mb-1.5">
                                    <span class="font-semibold text-brand-600">${art.catLabel}</span>
                                    <span>${art.date}</span>
                                </div>
                                <h3 class="text-sm font-bold text-slate-800 group-hover:text-brand-700 leading-snug">
                                    ${art.title}
                                </h3>
                                <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                    ${art.excerpt}
                                </p>
                            </div>
                            <span class="text-xs font-bold text-brand-700 pt-1 inline-flex items-center gap-1">
                                Đọc bài viết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </span>
                        </div>
                    </article>
                `;
            }).join('');
        }

        function filterArticles(catKey) {
            renderArticles(catKey);
            const buttons = document.querySelectorAll('.article-cat-btn');
            buttons.forEach(function (btn) {
                const active = btn.dataset.articleCat === catKey;
                if (active) {
                    btn.className = 'article-cat-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-brand-700 text-white transition';
                } else {
                    btn.className = 'article-cat-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 transition';
                }
            });
        }

        /* =========================================================
           3. ĐIỀU KHIỂN 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT MOBILE
        ========================================================== */
        let currentSlide = 0;
        const totalSlides = 2;
        let autoSlideTimer = null;

        function updateBannerUI() {
            const track = document.getElementById('banner-track');
            if (!track) return;
            track.style.transform = 'translateX(-' + (currentSlide * 100) + '%)';

            for (let i = 0; i < totalSlides; i++) {
                const dot = document.getElementById('dot-' + i);
                if (!dot) continue;
                if (i === currentSlide) {
                    dot.className = 'w-6 h-2 rounded-full bg-white transition-all';
                } else {
                    dot.className = 'w-2.5 h-2 rounded-full bg-white/45 hover:bg-white/75 transition-all';
                }
            }
        }

        function moveSlide(step) {
            currentSlide = (currentSlide + step + totalSlides) % totalSlides;
            updateBannerUI();
            resetAutoSlide();
        }

        function goToSlide(index) {
            currentSlide = index;
            updateBannerUI();
            resetAutoSlide();
        }

        function resetAutoSlide() {
            if (autoSlideTimer) clearInterval(autoSlideTimer);
            autoSlideTimer = setInterval(function () {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateBannerUI();
            }, 5000);
        }

        /* Hỗ trợ vuốt cảm ứng trái/phải cho banner trên điện thoại */
        function initBannerTouch() {
            const slider = document.getElementById('hero-slider');
            if (!slider) return;
            let startX = 0;

            slider.addEventListener('touchstart', function (e) {
                startX = e.changedTouches[0].screenX;
            }, { passive: true });

            slider.addEventListener('touchend', function (e) {
                const endX = e.changedTouches[0].screenX;
                const diff = startX - endX;
                if (Math.abs(diff) > 45) {
                    moveSlide(diff > 0 ? 1 : -1);
                }
            }, { passive: true });
        }

        /* =========================================================
           4. MENU ĐIỆN THOẠI
        ========================================================== */
        function toggleMobileMenu() {
            const panel = document.getElementById('mobile-menu-panel');
            const icon = document.getElementById('mobile-menu-icon');
            const btn = document.getElementById('mobile-menu-btn');
            if (!panel) return;
            const isHidden = panel.classList.contains('hidden');
            panel.classList.toggle('hidden');
            if (icon) {
                icon.className = isHidden ? 'fa-solid fa-xmark text-lg' : 'fa-solid fa-bars text-lg';
            }
            if (btn) {
                btn.setAttribute('aria-expanded', isHidden ? 'true' : 'false');
            }
        }

        function closeMobileMenu() {
            const panel = document.getElementById('mobile-menu-panel');
            const icon = document.getElementById('mobile-menu-icon');
            const btn = document.getElementById('mobile-menu-btn');
            if (panel) panel.classList.add('hidden');
            if (icon) icon.className = 'fa-solid fa-bars text-lg';
            if (btn) btn.setAttribute('aria-expanded', 'false');
        }

        function toggleMobileSubmenu(subId, iconId) {
            const sub = document.getElementById(subId);
            const icon = document.getElementById(iconId);
            if (!sub) return;
            sub.classList.toggle('hidden');
            if (icon) icon.classList.toggle('rotate-180');
        }

        /* =========================================================
           5. MODAL XEM CHI TIẾT SẢN PHẨM, DỰ ÁN, BÀI VIẾT
        ========================================================== */
        function showDetailModal(title, htmlContent) {
            document.getElementById('modal-title').textContent = title;
            document.getElementById('modal-body').innerHTML = htmlContent;
            document.getElementById('detail-modal').classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function hideDetailModal() {
            document.getElementById('detail-modal').classList.add('hidden');
            document.body.style.overflow = '';
        }

        function closeDetailModal(e) {
            if (e.target.id === 'detail-modal') hideDetailModal();
        }

        function openProductModal(productId) {
            const p = PRODUCTS.find(function (item) { return item.id === productId; });
            if (!p) return;
            const html = `
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 items-start">
                    <div class="relative rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                        <span class="absolute top-2 left-2 bg-red-600 text-white text-xs font-extrabold px-2.5 py-0.5 rounded-md shadow">
                            -${p.discount}%
                        </span>
                        <img
                            src="https://lh3.googleusercontent.com/d/${p.driveId}=w800"
                            data-drive-id="${p.driveId}"
                            alt="${p.name}"
                            class="w-full h-56 object-cover"
                            onerror="handleDriveFallback(this, '${p.name}', 'f1f5f9', '0d3b75')"
                        >
                    </div>
                    <div class="space-y-3">
                        <div class="flex items-baseline gap-2.5">
                            <span class="text-xl font-extrabold text-red-600">${formatVND(p.salePrice)}${p.unit}</span>
                            <span class="text-xs text-slate-400 line-through">${formatVND(p.originalPrice)}₫</span>
                        </div>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">${p.specs}</p>
                        <ul class="text-xs text-slate-600 space-y-1.5 bg-slate-50 p-3 rounded-lg border border-slate-200">
                            <li><i class="fa-solid fa-check text-brand-600 mr-1.5"></i>Miễn phí đo đạc &amp; tư vấn tại Đà Nẵng</li>
                            <li><i class="fa-solid fa-check text-brand-600 mr-1.5"></i>Bảo hành chính hãng phụ kiện &amp; khung nhôm</li>
                            <li><i class="fa-solid fa-check text-brand-600 mr-1.5"></i>Thi công chuẩn kỹ thuật bởi Năm Phi Glass</li>
                        </ul>
                        <div class="grid grid-cols-2 gap-2 pt-1">
                            <a href="tel:0938363345" class="text-center py-2.5 rounded-lg bg-red-600 hover:bg-red-700 text-white text-xs font-bold">
                                <i class="fa-solid fa-phone mr-1"></i>0938.363.345
                            </a>
                            <button type="button" onclick="hideDetailModal(); requestQuoteForProduct('${p.name}');" class="py-2.5 rounded-lg bg-brand-700 hover:bg-brand-800 text-white text-xs font-bold">
                                Yêu cầu báo giá
                            </button>
                        </div>
                    </div>
                </div>
            `;
            showDetailModal(p.name, html);
        }

        function openProjectModal(title, driveId, description) {
            const html = `
                <div class="space-y-4">
                    <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/${driveId}=w900"
                            data-drive-id="${driveId}"
                            alt="${title}"
                            class="w-full max-h-80 object-cover"
                            onerror="handleDriveFallback(this, '${title}', '0d3b75', 'ffffff')"
                        >
                    </div>
                    <p class="text-sm text-slate-600 leading-relaxed">${description}</p>
                    <div class="flex flex-wrap items-center justify-between gap-3 pt-2 border-t border-slate-200">
                        <span class="text-xs font-semibold text-slate-500">Đơn vị thi công: CÔNG TY TNHH MTV NĂM PHI GLASS</span>
                        <a href="#bao-gia" onclick="hideDetailModal()" class="px-4 py-2 rounded-lg bg-brand-700 text-white text-xs font-bold hover:bg-brand-800">
                            Nhận tư vấn công trình tương tự
                        </a>
                    </div>
                </div>
            `;
            showDetailModal(title, html);
        }

        function openArticleModal(articleId) {
            const art = ARTICLES.find(function (a) { return a.id === articleId; });
            if (!art) return;
            const html = `
                <div class="space-y-4">
                    <div class="flex items-center gap-3 text-xs text-slate-500">
                        <span class="px-2.5 py-0.5 rounded-full bg-brand-50 text-brand-700 font-semibold">${art.catLabel}</span>
                        <span>Ngày đăng: ${art.date}</span>
                    </div>
                    <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/${art.driveId}=w800"
                            data-drive-id="${art.driveId}"
                            alt="${art.title}"
                            class="w-full max-h-64 object-cover"
                            onerror="handleDriveFallback(this, '${art.title}', 'e2e8f0', '0d3b75')"
                        >
                    </div>
                    <p class="text-sm text-slate-700 leading-relaxed">${art.content}</p>
                    <div class="p-3.5 rounded-xl bg-brand-50 border border-brand-100 flex flex-wrap items-center justify-between gap-2">
                        <span class="text-xs sm:text-sm font-semibold text-brand-800">Cần tư vấn &amp; báo giá chi tiết tại Đà Nẵng?</span>
                        <a href="tel:0938363345" class="px-4 py-2 rounded-lg bg-brand-700 text-white text-xs font-bold hover:bg-brand-800">
                            Gọi ngay 0938.363.345
                        </a>
                    </div>
                </div>
            `;
            showDetailModal(art.title, html);
        }

        /* =========================================================
           6. XỬ LÝ FORM BÁO GIÁ & CHỌN DANH MỤC TỰ ĐỘNG ĐIỀN
        ========================================================== */
        function selectCategoryQuote(categoryName) {
            const select = document.getElementById('quote-category');
            if (select) {
                for (let i = 0; i < select.options.length; i++) {
                    if (select.options[i].value.toLowerCase() === categoryName.toLowerCase()) {
                        select.selectedIndex = i;
                        break;
                    }
                }
            }
            const target = document.getElementById('bao-gia');
            if (target) target.scrollIntoView({ behavior: 'smooth' });
        }

        function requestQuoteForProduct(productName) {
            const note = document.getElementById('quote-note');
            if (note) {
                note.value = 'Tôi muốn nhận báo giá mẫu: ' + productName;
            }
            selectCategoryQuote('Cửa nhôm Xingfa');
        }

        function handleQuoteSubmit(event) {
            event.preventDefault();
            try {
                const name = document.getElementById('quote-name').value.trim();
                const phone = document.getElementById('quote-phone').value.trim();
                const category = document.getElementById('quote-category').value;
                const feedback = document.getElementById('quote-feedback');

                if (!name || !phone) {
                    feedback.className = 'p-3 rounded-lg bg-red-50 border border-red-200 text-red-700 text-xs sm:text-sm font-medium';
                    feedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để Năm Phi Glass liên hệ báo giá.';
                    feedback.classList.remove('hidden');
                    return;
                }

                feedback.className = 'p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium';
                feedback.innerHTML = '<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn <strong>' + name + '</strong>! Yêu cầu báo giá hạng mục <strong>' + category + '</strong> đã được ghi nhận. Kỹ thuật viên Năm Phi Glass sẽ gọi lại qua số <strong>' + phone + '</strong> trong ít phút.';
                feedback.classList.remove('hidden');
                event.target.reset();
            } catch (err) {
                console.error('Lỗi gửi form báo giá:', err);
            }
        }

        /* Khởi chạy toàn bộ tính năng khi trang tải xong */
        window.addEventListener('DOMContentLoaded', function () {
            renderProducts('all');
            renderArticles('all');
            updateBannerUI();
            resetAutoSlide();
            initBannerTouch();
        });
    </script>
</body>
</html>
