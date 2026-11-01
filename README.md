<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Đội Xe Tấn Tài Travel - Cho Thuê Xe Du Lịch Huế 4 - 45 Chỗ Uy Tín | tantaitravel.com</title>
    <meta name="description" content="Đội Xe Tấn Tài Travel (tantaitravel.com) chuyên cho thuê xe ô tô du lịch, xe tự lái, xe hợp đồng, xe Limousine, xe cưới hỏi từ 4 - 7 - 16 - 29 - 35 - 45 chỗ tại Huế & Miền Trung. Địa chỉ: 27 Tôn Thất Bật, TP. Huế. Hotline: 0935.325.246 - 0842.565.246.">
    <link rel="canonical" href="https://tantaitravel.com/">

    <!-- Open Graph Thumbnail khi gửi link trang web qua Zalo / Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="tantaitravel.com - Đội Xe Tấn Tài Travel">
    <meta property="og:url" content="https://tantaitravel.com/">
    <meta property="og:title" content="Đội Xe Tấn Tài Travel - Cho Thuê Xe Du Lịch Huế 4 - 45 Chỗ Giá Rẻ">
    <meta property="og:description" content="Chuyên cho thuê xe du lịch, tự lái, hợp đồng, cưới hỏi, Limousine 4-45 chỗ đời mới tại Huế - Đà Nẵng - Hội An. ĐC: 27 Tôn Thất Bật, TP. Huế. ĐT: 0935.325.246 - 0842.565.246">
    <meta property="og:image" content="833852878_1688308149961845_8815609278150210198_n.jpg">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Đội Xe Tấn Tài Travel | tantaitravel.com">
    <meta name="twitter:description" content="Dịch vụ cho thuê xe 4 - 45 chỗ, xe tự lái, hợp đồng, Limousine uy tín tại TP. Huế. Hotline: 0935.325.246 - 0842.565.246">
    <meta name="twitter:image" content="833852878_1688308149961845_8815609278150210198_n.jpg">

    <!-- Tailwind CSS & Font Awesome & Google Fonts -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700;900&display=swap" rel="stylesheet">

    <style>
        /* Cấu hình chuẩn Flatsome Theme để dễ dàng dựng lại trên UX Builder */
        :root {
            --fs-primary: #b8860b;      /* Vàng kim Hoàng Gia theo Logo Tấn Tài */
            --fs-primary-dark: #8f6505;
            --fs-secondary: #d90429;    /* Đỏ giảm giá / Hotline nổi bật */
            --fs-dark: #1a1510;         /* Đen nâu sang trọng đồng bộ nền Logo */
            --fs-container: 1230px;
        }

        html, body {
            font-family: 'Roboto', sans-serif;
            color: #333333;
            background-color: #f8f9fa;
            overflow-x: hidden;
            max-width: 100vw;
        }

        #wrapper {
            overflow-x: hidden;
            width: 100%;
        }

        .fs-container {
            max-width: var(--fs-container);
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        /* Section Title chuẩn Flatsome (style="bold-center") */
        .section-title-container {
            margin-bottom: 1.5rem;
        }
        .section-title-main {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .section-title-main::before,
        .section-title-main::after {
            content: "";
            flex: 1;
            height: 2px;
            background-color: #e5e7eb;
        }
        .section-title-main span {
            padding: 0 18px;
            font-weight: 800;
            text-transform: uppercase;
            color: var(--fs-dark);
            letter-spacing: 0.5px;
        }

        /* Product Box chuẩn Flatsome WooCommerce */
        .box-product {
            background: #ffffff;
            border: 1px solid #ebebeb;
            border-radius: 6px;
            overflow: hidden;
            transition: box-shadow 0.25s ease, transform 0.25s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
            position: relative;
        }
        .box-product:hover {
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            transform: translateY(-2px);
        }
        .box-image {
            position: relative;
            overflow: hidden;
            aspect-ratio: 4 / 3;
            background: #f3f4f6;
        }
        .box-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.45s ease;
        }
        .box-product:hover .box-image img {
            transform: scale(1.06);
        }

        /* Nút XEM NHANH (Quick View) chuẩn Flatsome trượt từ dưới ảnh lên */
        .quick-view-bar {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: rgba(26, 21, 16, 0.88);
            color: #fbbf24;
            text-align: center;
            font-size: 12px;
            font-weight: 700;
            text-transform: uppercase;
            padding: 7px 6px;
            letter-spacing: 0.5px;
            transform: translateY(100%);
            transition: transform 0.25s ease, background 0.2s ease;
            cursor: pointer;
            z-index: 10;
        }
        .quick-view-bar:hover {
            background: var(--fs-primary);
            color: #ffffff;
        }
        .box-product:hover .quick-view-bar {
            transform: translateY(0);
        }
        /* Trên điện thoại hiển thị sẵn thanh Xem Nhanh gọn gàng để dễ bấm */
        @media (max-width: 767px) {
            .quick-view-bar {
                transform: translateY(0);
                background: rgba(26, 21, 16, 0.82);
                font-size: 10.5px;
                padding: 5px 4px;
            }
        }

        /* Vòng tròn % Giảm Giá chuẩn Flatsome (.badge-container) */
        .badge-sale-flatsome {
            position: absolute;
            top: 10px;
            left: 10px;
            z-index: 10;
            width: 44px;
            height: 44px;
            border-radius: 9999px;
            background-color: var(--fs-secondary);
            color: #ffffff;
            font-weight: 800;
            font-size: 13px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(217, 4, 41, 0.35);
            line-height: 1;
        }
        @media (max-width: 767px) {
            .badge-sale-flatsome {
                width: 36px;
                height: 36px;
                font-size: 11px;
                top: 6px;
                left: 6px;
            }
        }

        /* Mega Dropdown Menu trên máy tính */
        .nav-item-has-dropdown {
            position: relative;
        }
        .nav-dropdown-flatsome {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 250px;
            background: #ffffff;
            border-top: 3px solid var(--fs-primary);
            box-shadow: 0 12px 28px rgba(0, 0, 0, 0.15);
            border-radius: 0 0 6px 6px;
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
            z-index: 100;
        }
        .nav-item-has-dropdown:hover .nav-dropdown-flatsome {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Hiệu ứng rung & tỏa sóng cho nút Liên Hệ Nổi Bật */
        @keyframes pulse-ring {
            0% { transform: scale(0.97); box-shadow: 0 0 0 0 rgba(217, 4, 41, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 8px rgba(217, 4, 41, 0); }
            100% { transform: scale(0.97); box-shadow: 0 0 0 0 rgba(217, 4, 41, 0); }
        }
        @keyframes pulse-zalo {
            0% { transform: scale(0.97); box-shadow: 0 0 0 0 rgba(0, 104, 255, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 8px rgba(0, 104, 255, 0); }
            100% { transform: scale(0.97); box-shadow: 0 0 0 0 rgba(0, 104, 255, 0); }
        }
        .btn-float-hotline {
            animation: pulse-ring 1.8s infinite;
        }
        .btn-float-zalo {
            animation: pulse-zalo 2s infinite;
        }
    </style>
</head>
<body>

<!-- =====================================================================
     WRAPPER CHÍNH CHUẨN FLATSOME (#wrapper)
====================================================================== -->
<div id="wrapper">

    <!-- =================================================================
         HEADER (#header) - Gồm Top Bar, Header Main & Header Bottom (Menu)
    ================================================================== -->
    <header id="header" class="sticky top-0 z-40 bg-white shadow-sm">
        
        <!-- 1. TOP BAR (Chỉ hiển thị thông tin khách hàng, KHÔNG có thanh UX Builder) -->
        <div class="bg-[#1a1510] text-amber-100 text-[11px] sm:text-xs py-1.5 sm:py-2 border-b border-amber-900/40">
            <div class="fs-container flex flex-wrap items-center justify-between gap-1.5">
                <div class="flex items-center flex-wrap gap-x-3 gap-y-0.5 min-w-0">
                    <span class="inline-flex items-center gap-1 font-medium text-amber-300">
                        <i class="fa-solid fa-globe"></i> tantaitravel.com
                    </span>
                    <span class="hidden sm:inline text-amber-700">|</span>
                    <span class="inline-flex items-center gap-1 truncate">
                        <i class="fa-solid fa-location-dot text-amber-400"></i>
                        <span>ĐC: <strong>27 Tôn Thất Bật, TP. Huế</strong></span>
                    </span>
                </div>
                <div class="hidden md:flex items-center gap-4">
                    <a href="#bang-gia" class="hover:text-amber-300 transition">Bảng giá thuê xe</a>
                    <span class="text-amber-700">|</span>
                    <a href="#form-bao-gia" class="hover:text-amber-300 transition">Yêu cầu báo giá</a>
                    <span class="text-amber-700">|</span>
                    <a href="#ban-do-google" class="hover:text-amber-300 transition">Chỉ đường Google Maps</a>
                    <span class="text-amber-700">|</span>
                    <a href="https://www.facebook.com/profile.php?id=100063480277479" target="_blank" rel="noopener" class="text-amber-300 hover:text-white font-semibold inline-flex items-center gap-1">
                        <i class="fa-brands fa-facebook"></i> Fanpage Đội Xe Tấn Tài
                    </a>
                </div>
            </div>
        </div>

        <!-- 2. HEADER MAIN (Logo Đội Xe Tấn Tài + Thanh Tìm Kiếm + Hotline) -->
        <div class="bg-white py-2.5 sm:py-3 border-b border-gray-100">
            <div class="fs-container flex items-center justify-between gap-2 sm:gap-3">
                
                <!-- Nút mở Menu Danh Mục trên Điện Thoại -->
                <button onclick="toggleMobileMenu()" class="lg:hidden w-9 h-9 rounded-md bg-amber-50 text-amber-900 border border-amber-200 hover:bg-amber-100 flex items-center justify-center shrink-0" aria-label="Mở danh mục">
                    <i class="fa-solid fa-bars text-base"></i>
                </button>

                <!-- LOGO ĐỘI XE TẤN TÀI TRAVEL (Lấy đúng ảnh logo_2.jpg) -->
                <a href="#" class="flex items-center gap-2 sm:gap-3 group min-w-0 flex-1 lg:flex-initial">
                    <div class="w-12 h-12 sm:w-16 sm:h-16 rounded-lg bg-[#1c150c] p-0.5 shadow-md border border-amber-500/60 flex items-center justify-center overflow-hidden shrink-0">
                        <img src="logo_2.jpg" alt="Logo Du Lịch Tấn Tài 0935 325 246" class="w-full h-full object-cover rounded-md" onerror="this.onerror=null; this.src='logo.jpg';">
                    </div>
                    <div class="min-w-0 flex-1">
                        <div class="text-sm sm:text-xl font-black tracking-tight text-gray-900 uppercase leading-tight truncate">
                            ĐỘI XE <span class="text-amber-600">TẤN TÀI TRAVEL</span>
                        </div>
                        <div class="text-[11px] sm:text-xs text-gray-500 font-medium mt-0.5 truncate">
                            Xe Du Lịch, Hợp Đồng, Limousine 4 - 45 Chỗ Huế
                        </div>
                        <div class="text-[11px] text-red-600 font-bold mt-0.5 sm:hidden truncate">
                            <i class="fa-solid fa-phone-volume"></i> 0935.325.246 - 0842.565.246
                        </div>
                    </div>
                </a>

                <!-- Ô Tìm Kiếm Dòng Xe (Chuẩn Flatsome Search Box) -->
                <div class="hidden md:flex flex-1 max-w-md mx-4">
                    <div class="relative w-full flex">
                        <input id="search-input" type="text" oninput="filterProductsBySearch(this.value)" placeholder="Tìm xe 4 chỗ, 7 chỗ, 16 chỗ, Limousine, 45 chỗ..." class="w-full pl-4 pr-10 py-2.5 text-sm border border-gray-300 rounded-l-md focus:outline-none focus:border-amber-600">
                        <button onclick="filterProductsBySearch(document.getElementById('search-input').value)" class="px-4 bg-amber-600 hover:bg-amber-700 text-white rounded-r-md transition">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </div>
                </div>

                <!-- Cụm Hotline & Báo Giá Nhanh trên Header -->
                <div class="hidden sm:flex items-center gap-3 shrink-0">
                    <a href="tel:0935325246" class="flex items-center gap-2.5 bg-red-50 hover:bg-red-100 border border-red-200 px-3.5 py-2 rounded-lg transition">
                        <span class="w-9 h-9 rounded-full bg-red-600 text-white flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-phone-volume"></i>
                        </span>
                        <div class="leading-tight">
                            <span class="block text-[11px] text-gray-500 font-medium">Hotline / Zalo 24/7</span>
                            <span class="block text-sm font-black text-red-600">0935.325.246</span>
                            <span class="block text-xs font-bold text-gray-800">0842.565.246</span>
                        </div>
                    </a>
                    <a href="#form-bao-gia" class="bg-amber-600 hover:bg-amber-700 text-white font-bold text-xs uppercase px-4 py-3 rounded-lg shadow-sm transition">
                        Nhận Báo Giá
                    </a>
                </div>

                <!-- Nút Gọi Nhanh trên Điện Thoại (Nhỏ gọn, không tràn màn hình) -->
                <a href="tel:0935325246" class="sm:hidden px-2.5 py-2 rounded-md bg-red-600 text-white font-bold text-[11px] flex items-center gap-1 shadow shrink-0">
                    <i class="fa-solid fa-phone"></i>
                    <span>Gọi</span>
                </a>
            </div>
        </div>

        <!-- 3. HEADER BOTTOM - THANH DANH MỤC TỐI ƯU TRÊN MÁY TÍNH (Chuẩn Flatsome Mega Menu) -->
        <div class="hidden lg:block bg-[#1a1510] text-white">
            <div class="fs-container flex items-center justify-between">
                
                <!-- Nút Danh Mục Sản Phẩm (Vertical Menu Dropdown giống Flatsome) -->
                <div class="nav-item-has-dropdown">
                    <button class="bg-amber-600 hover:bg-amber-700 text-white font-bold text-xs uppercase tracking-wider px-5 py-3.5 flex items-center gap-2.5 transition">
                        <i class="fa-solid fa-bars-staggered text-sm"></i>
                        <span>DANH MỤC LOẠI XE</span>
                        <i class="fa-solid fa-chevron-down text-[10px] ml-2"></i>
                    </button>
                    <div class="nav-dropdown-flatsome w-64 py-1 text-gray-800 text-sm">
                        <a href="#xe-4-cho" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-amber-700 border-b border-gray-100">
                            <span><i class="fa-solid fa-car-side w-6 text-amber-600"></i> Chọn Xe 4 Chỗ</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#xe-7-cho" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-amber-700 border-b border-gray-100">
                            <span><i class="fa-solid fa-van-shuttle w-6 text-amber-600"></i> Chọn Xe 7 Chỗ & 5+2 Chỗ</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#xe-ban-tai" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-amber-700 border-b border-gray-100">
                            <span><i class="fa-solid fa-truck-pickup w-6 text-amber-600"></i> Chọn Xe Bán Tải</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#xe-hop-dong" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-amber-700 border-b border-gray-100">
                            <span><i class="fa-solid fa-crown w-6 text-amber-600"></i> Xe Limousine Thượng Đỉnh</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#xe-hop-dong" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-amber-700 border-b border-gray-100">
                            <span><i class="fa-solid fa-bus-simple w-6 text-amber-600"></i> Chọn Xe 16 Chỗ</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#xe-hop-dong" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-amber-700 border-b border-gray-100">
                            <span><i class="fa-solid fa-bus w-6 text-amber-600"></i> Chọn Xe 29 - 35 - 45 Chỗ</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#bang-gia" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-amber-700">
                            <span><i class="fa-solid fa-plane-departure w-6 text-amber-600"></i> Xe Đưa Đón Sân Bay</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                    </div>
                </div>

                <!-- Thanh Menu Ngang Chính lấy theo danh mục web mẫu hopnhattravel.com -->
                <nav class="flex items-center text-xs font-bold uppercase tracking-wide">
                    <a href="#" class="px-3.5 py-3.5 text-amber-400 hover:text-amber-300 transition">Trang Chủ</a>

                    <!-- Dropdown: Cho Thuê Xe -->
                    <div class="nav-item-has-dropdown">
                        <a href="#xe-4-cho" class="px-3.5 py-3.5 hover:text-amber-400 flex items-center gap-1 transition">
                            Cho Thuê Xe <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown-flatsome py-2 text-gray-800 font-medium normal-case">
                            <div class="px-4 py-1.5 text-xs font-bold uppercase text-amber-700 bg-amber-50">Xe Tự Lái & Gia Đình</div>
                            <a href="#xe-4-cho" class="block px-4 py-2 hover:bg-gray-100">Cho Thuê Xe 4 Chỗ</a>
                            <a href="#xe-7-cho" class="block px-4 py-2 hover:bg-gray-100">Cho Thuê Xe 7 Chỗ & 5+2 Chỗ</a>
                            <a href="#xe-ban-tai" class="block px-4 py-2 hover:bg-gray-100">Cho Thuê Xe Bán Tải</a>
                            <div class="px-4 py-1.5 text-xs font-bold uppercase text-amber-700 bg-amber-50 mt-1">Xe Hợp Đồng & Du Lịch</div>
                            <a href="#xe-hop-dong" class="block px-4 py-2 hover:bg-gray-100">Cho Thuê Xe 16 Chỗ</a>
                            <a href="#xe-hop-dong" class="block px-4 py-2 hover:bg-gray-100">Cho Thuê Xe 29 Chỗ</a>
                            <a href="#xe-hop-dong" class="block px-4 py-2 hover:bg-gray-100">Cho Thuê Xe 35 Chỗ</a>
                            <a href="#xe-hop-dong" class="block px-4 py-2 hover:bg-gray-100">Cho Thuê Xe 45 Chỗ</a>
                        </div>
                    </div>

                    <!-- Dropdown: Dịch Vụ -->
                    <div class="nav-item-has-dropdown">
                        <a href="#danh-muc-dich-vu" class="px-3.5 py-3.5 hover:text-amber-400 flex items-center gap-1 transition">
                            Dịch Vụ <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown-flatsome py-2 text-gray-800 font-medium normal-case">
                            <a href="#xe-4-cho" class="block px-4 py-2 hover:bg-amber-50">Cho Thuê Xe Du Lịch Huế - Đà Nẵng</a>
                            <a href="#xe-4-cho" class="block px-4 py-2 hover:bg-amber-50">Cho Thuê Xe Tự Lái Thủ Tục Nhanh</a>
                            <a href="#xe-hop-dong" class="block px-4 py-2 hover:bg-amber-50">Cho Thuê Xe Hợp Đồng Công Ty / Đoàn</a>
                            <a href="#xe-hop-dong" class="block px-4 py-2 hover:bg-amber-50">Cho Thuê Xe Đám Cưới - Rước Dâu</a>
                            <a href="#xe-hop-dong" class="block px-4 py-2 hover:bg-amber-50">Cho Thuê Xe Limousine Thượng Đỉnh</a>
                            <a href="#bang-gia" class="block px-4 py-2 hover:bg-amber-50">Xe Đưa Đón Sân Bay Phú Bài - Đà Nẵng</a>
                        </div>
                    </div>

                    <!-- Dropdown: Chọn Xe -->
                    <div class="nav-item-has-dropdown">
                        <a href="#danh-muc-dich-vu" class="px-3.5 py-3.5 hover:text-amber-400 flex items-center gap-1 transition">
                            Chọn Xe <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown-flatsome py-2 text-gray-800 font-medium normal-case">
                            <a href="#xe-4-cho" class="block px-4 py-2 hover:bg-amber-50">Chọn Xe 4 Chỗ</a>
                            <a href="#xe-7-cho" class="block px-4 py-2 hover:bg-amber-50">Chọn Xe 5+2 Chỗ</a>
                            <a href="#xe-7-cho" class="block px-4 py-2 hover:bg-amber-50">Chọn Xe 7 Chỗ</a>
                            <a href="#xe-ban-tai" class="block px-4 py-2 hover:bg-amber-50">Chọn Xe Bán Tải</a>
                            <a href="#xe-hop-dong" class="block px-4 py-2 hover:bg-amber-50">Chọn Xe 16 Chỗ</a>
                            <a href="#xe-hop-dong" class="block px-4 py-2 hover:bg-amber-50">Chọn Xe 29 Chỗ</a>
                            <a href="#xe-hop-dong" class="block px-4 py-2 hover:bg-amber-50">Chọn Xe 35 Chỗ</a>
                            <a href="#xe-hop-dong" class="block px-4 py-2 hover:bg-amber-50">Chọn Xe 45 Chỗ</a>
                        </div>
                    </div>

                    <!-- Dropdown: Xe Đi Tỉnh -->
                    <div class="nav-item-has-dropdown">
                        <a href="#bang-gia" class="px-3.5 py-3.5 hover:text-amber-400 flex items-center gap-1 transition">
                            Xe Đi Tỉnh <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown-flatsome py-2 text-gray-800 font-medium normal-case w-64">
                            <a href="#bang-gia" class="block px-4 py-2 hover:bg-amber-50">Thuê Xe Huế Đi Đà Nẵng - Hội An</a>
                            <a href="#bang-gia" class="block px-4 py-2 hover:bg-amber-50">Thuê Xe Huế Đi Lăng Cô - Bạch Mã</a>
                            <a href="#bang-gia" class="block px-4 py-2 hover:bg-amber-50">Thuê Xe Huế Đi La Vang - Quảng Trị</a>
                            <a href="#bang-gia" class="block px-4 py-2 hover:bg-amber-50">Thuê Xe Huế Đi Phong Nha - Quảng Bình</a>
                            <a href="#bang-gia" class="block px-4 py-2 hover:bg-amber-50">Thuê Xe Đi Các Tỉnh Miền Trung & Toàn Quốc</a>
                        </div>
                    </div>

                    <a href="#bang-gia" class="px-3.5 py-3.5 hover:text-amber-400 transition">Bảng Giá Xe</a>
                    <a href="#bai-viet-trang-chu" class="px-3.5 py-3.5 hover:text-amber-400 transition">Blog Chia Sẻ</a>
                    <a href="#ban-do-google" class="px-3.5 py-3.5 hover:text-amber-400 transition">Liên Hệ</a>
                </nav>

                <!-- Cam kết nhỏ bên phải Menu -->
                <div class="text-xs text-amber-300 font-semibold hidden xl:flex items-center gap-1.5">
                    <i class="fa-solid fa-shield-halved"></i> 100% Xe Đời Mới - Giao Tận Nơi
                </div>
            </div>
        </div>
    </header>

    <!-- =================================================================
         MENU DRAWER TRÊN ĐIỆN THOẠI (Tối ưu Danh Mục Mobile đẹp & mượt)
    ================================================================== -->
    <div id="mobile-menu-overlay" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/60 z-50 hidden"></div>
    <aside id="mobile-menu-drawer" class="fixed top-0 left-0 bottom-0 w-80 max-w-[85vw] bg-white z-50 transform -translate-x-full transition-transform duration-300 flex flex-col shadow-2xl">
        <!-- Header Menu Mobile -->
        <div class="bg-[#1a1510] text-white p-3.5 flex items-center justify-between gap-2">
            <div class="flex items-center gap-2.5 min-w-0">
                <img src="logo_2.jpg" alt="Logo Du Lịch Tấn Tài" class="w-10 h-10 rounded object-cover border border-amber-500/60 shrink-0" onerror="this.onerror=null; this.src='logo.jpg';">
                <div class="min-w-0">
                    <div class="font-black text-amber-400 text-xs uppercase truncate">ĐỘI XE TẤN TÀI TRAVEL</div>
                    <div class="text-[11px] text-gray-300 truncate">0935.325.246 - 0842.565.246</div>
                </div>
            </div>
            <button onclick="toggleMobileMenu()" class="w-8 h-8 rounded-full bg-white/10 text-white flex items-center justify-center shrink-0">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>

        <!-- Tìm kiếm trên Mobile -->
        <div class="p-3 bg-gray-50 border-b border-gray-200">
            <input type="text" oninput="filterProductsBySearch(this.value)" placeholder="Tìm nhanh loại xe..." class="w-full px-3 py-2 text-sm border border-gray-300 rounded focus:outline-none focus:border-amber-600">
        </div>

        <!-- Danh sách Danh Mục trên Mobile -->
        <div class="flex-1 overflow-y-auto divide-y divide-gray-100 text-sm font-semibold text-gray-800">
            <a href="#" onclick="toggleMobileMenu()" class="flex items-center gap-3 px-4 py-3 text-amber-700 bg-amber-50/50">
                <i class="fa-solid fa-house w-5 text-center"></i> Trang Chủ
            </a>
            <div class="px-4 py-2 text-[11px] font-bold uppercase text-gray-400 bg-gray-50">Danh Mục Chọn Xe</div>
            <a href="#xe-4-cho" onclick="toggleMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-amber-50">
                <span><i class="fa-solid fa-car w-6 text-amber-600"></i> Cho Thuê Xe 4 Chỗ</span>
                <i class="fa-solid fa-chevron-right text-xs text-gray-400"></i>
            </a>
            <a href="#xe-7-cho" onclick="toggleMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-amber-50">
                <span><i class="fa-solid fa-van-shuttle w-6 text-amber-600"></i> Cho Thuê Xe 7 Chỗ & 5+2 Chỗ</span>
                <i class="fa-solid fa-chevron-right text-xs text-gray-400"></i>
            </a>
            <a href="#xe-ban-tai" onclick="toggleMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-amber-50">
                <span><i class="fa-solid fa-truck-pickup w-6 text-amber-600"></i> Cho Thuê Xe Bán Tải</span>
                <i class="fa-solid fa-chevron-right text-xs text-gray-400"></i>
            </a>
            <a href="#xe-hop-dong" onclick="toggleMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-amber-50">
                <span><i class="fa-solid fa-crown w-6 text-amber-600"></i> Thuê Xe Limousine Thượng Đỉnh</span>
                <i class="fa-solid fa-chevron-right text-xs text-gray-400"></i>
            </a>
            <a href="#xe-hop-dong" onclick="toggleMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-amber-50">
                <span><i class="fa-solid fa-bus-simple w-6 text-amber-600"></i> Thuê Xe Hợp Đồng 16 - 29 - 35 - 45 Chỗ</span>
                <i class="fa-solid fa-chevron-right text-xs text-gray-400"></i>
            </a>
            <div class="px-4 py-2 text-[11px] font-bold uppercase text-gray-400 bg-gray-50">Dịch Vụ & Thông Tin</div>
            <a href="#bang-gia" onclick="toggleMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-amber-50">
                <span><i class="fa-solid fa-table-list w-6 text-amber-600"></i> Bảng Giá Xe Đưa Đón & Đi Tỉnh</span>
                <i class="fa-solid fa-chevron-right text-xs text-gray-400"></i>
            </a>
            <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-amber-50">
                <span><i class="fa-solid fa-file-signature w-6 text-amber-600"></i> Form Yêu Cầu & Báo Giá</span>
                <i class="fa-solid fa-chevron-right text-xs text-gray-400"></i>
            </a>
            <a href="#bai-viet-trang-chu" onclick="toggleMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-amber-50">
                <span><i class="fa-solid fa-newspaper w-6 text-amber-600"></i> Danh Mục Bài Viết & Kinh Nghiệm</span>
                <i class="fa-solid fa-chevron-right text-xs text-gray-400"></i>
            </a>
            <a href="#ban-do-google" onclick="toggleMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-amber-50">
                <span><i class="fa-solid fa-map-location-dot w-6 text-amber-600"></i> Bản Đồ: 27 Tôn Thất Bật, TP. Huế</span>
                <i class="fa-solid fa-chevron-right text-xs text-gray-400"></i>
            </a>
        </div>

        <!-- Footer Menu Mobile -->
        <div class="p-4 bg-amber-50 border-t border-amber-200 space-y-2">
            <a href="tel:0935325246" class="w-full py-2.5 bg-red-600 text-white rounded-md font-bold text-center block text-sm">
                <i class="fa-solid fa-phone"></i> 0935.325.246
            </a>
            <a href="tel:0842565246" class="w-full py-2.5 bg-[#1a1510] text-amber-400 rounded-md font-bold text-center block text-sm">
                <i class="fa-solid fa-phone"></i> 0842.565.246
            </a>
        </div>
    </aside>

    <!-- =================================================================
         MAIN CONTENT (#main) - CÁC SECTION ĐƠN GIẢN DỄ DỰNG LẠI TRÊN UX BUILDER
    ================================================================== -->
    <main id="main">

        <!-- =============================================================
             SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT (SỬ DỤNG ẢNH THỰC TẾ NHÀ XE TẤN TÀI)
        ============================================================== -->
        <section class="relative bg-[#1a1510] overflow-hidden">
            <div id="hero-slider" class="relative h-[260px] sm:h-[420px] lg:h-[500px] w-full">
                
                <!-- SLIDE 1: Ảnh thực tế dàn 3 xe VIP Limousine vàng của Đội Xe Tấn Tài -->
                <div class="hero-slide absolute inset-0 transition-opacity duration-700 opacity-100 z-10">
                    <img src="794958057_1656982643094396_7116448109568842488_n.jpg" alt="Dàn Xe VIP Limousine Đội Xe Tấn Tài Travel Huế" class="w-full h-full object-cover object-center opacity-60">
                    <div class="absolute inset-0 bg-gradient-to-r from-[#1a1510]/90 via-[#1a1510]/60 to-black/25"></div>
                    <div class="fs-container h-full flex items-center relative z-20">
                        <div class="max-w-2xl text-white space-y-2 sm:space-y-4 py-3">
                            <p class="text-amber-400 font-bold text-[11px] sm:text-sm uppercase tracking-wider">
                                ĐỘI XE TẤN TÀI TRAVEL - TANTAITRAVEL.COM
                            </p>
                            <h1 class="text-lg sm:text-4xl lg:text-5xl font-black leading-snug sm:leading-tight uppercase">
                                CHO THUÊ XE DU LỊCH HUẾ <span class="text-amber-400">4 - 7 - 16 - 45 CHỖ</span> ĐỜI MỚI
                            </h1>
                            <p class="text-xs sm:text-base text-gray-200 leading-relaxed line-clamp-2 sm:line-clamp-none">
                                Chuyên phục vụ xe du lịch, tự lái, hợp đồng công ty, cưới hỏi, VIP Limousine thượng đỉnh tại Huế - Đà Nẵng - Hội An - Quảng Bình. ĐC: 27 Tôn Thất Bật, TP. Huế.
                            </p>
                            <div class="pt-1 sm:pt-2 flex flex-wrap gap-2 sm:gap-3">
                                <a href="tel:0935325246" class="bg-red-600 hover:bg-red-700 text-white font-bold text-xs sm:text-sm uppercase px-3.5 py-2 sm:px-5 sm:py-3 rounded-md shadow-lg transition inline-flex items-center gap-1.5">
                                    <i class="fa-solid fa-phone-volume"></i> 0935.325.246
                                </a>
                                <a href="#form-bao-gia" class="bg-amber-500 hover:bg-amber-600 text-gray-950 font-bold text-xs sm:text-sm uppercase px-3.5 py-2 sm:px-5 sm:py-3 rounded-md shadow-lg transition inline-flex items-center gap-1.5">
                                    <i class="fa-solid fa-paper-plane"></i> Nhận Báo Giá
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2: Ảnh thực tế xe VIP Limousine Tấn Tài Tourist 75H-036.37 tại TP. Huế -->
                <div class="hero-slide absolute inset-0 transition-opacity duration-700 opacity-0 z-0">
                    <img src="833852878_1688308149961845_8815609278150210198_n.jpg" alt="Xe VIP Limousine Tấn Tài Tourist 75H-036.37 Huế" class="w-full h-full object-cover object-center opacity-60">
                    <div class="absolute inset-0 bg-gradient-to-r from-[#1a1510]/90 via-[#1a1510]/60 to-black/25"></div>
                    <div class="fs-container h-full flex items-center relative z-20">
                        <div class="max-w-2xl text-white space-y-2 sm:space-y-4 py-3">
                            <p class="text-amber-400 font-bold text-[11px] sm:text-sm uppercase tracking-wider">
                                DÀN XE VIP LIMOUSINE & UNIVERSE ĐOÀN LỚN
                            </p>
                            <h2 class="text-lg sm:text-4xl lg:text-5xl font-black leading-snug sm:leading-tight uppercase">
                                ĐƯA ĐÓN SÂN BAY & <span class="text-amber-400">HỢP ĐỒNG TOUR</span> TRỌN GÓI GIÁ RẺ
                            </h2>
                            <p class="text-xs sm:text-base text-gray-200 leading-relaxed line-clamp-2 sm:line-clamp-none">
                                Đồng hành tin cậy cùng các doanh nghiệp, đoàn khách tham quan Lăng Tẩm Huế, Bà Nà Hills, Hội An, La Vang, Phong Nha. Tài xế nhiệt tình, miễn phí thời gian chờ.
                            </p>
                            <div class="pt-1 sm:pt-2 flex flex-wrap gap-2 sm:gap-3">
                                <a href="tel:0842565246" class="bg-amber-500 hover:bg-amber-600 text-gray-950 font-bold text-xs sm:text-sm uppercase px-3.5 py-2 sm:px-5 sm:py-3 rounded-md shadow-lg transition inline-flex items-center gap-1.5">
                                    <i class="fa-solid fa-phone"></i> 0842.565.246
                                </a>
                                <a href="#bang-gia" class="bg-white/15 hover:bg-white/25 text-white border border-white/40 font-bold text-xs sm:text-sm uppercase px-3.5 py-2 sm:px-5 sm:py-3 rounded-md transition inline-flex items-center gap-1.5">
                                    <i class="fa-solid fa-table"></i> Xem Bảng Giá
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Prev / Next của Banner -->
                <button onclick="prevSlide()" aria-label="Slide trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-30 w-8 h-8 sm:w-11 sm:h-11 rounded-full bg-black/40 hover:bg-amber-600 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-base"></i>
                </button>
                <button onclick="nextSlide()" aria-label="Slide tiếp" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-30 w-8 h-8 sm:w-11 sm:h-11 rounded-full bg-black/40 hover:bg-amber-600 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-base"></i>
                </button>

                <!-- Chấm tròn chỉ mục Slide -->
                <div class="absolute bottom-2.5 sm:bottom-4 left-1/2 -translate-x-1/2 z-30 flex items-center gap-2">
                    <button onclick="goToSlide(0)" id="slider-dot-0" class="w-7 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button onclick="goToSlide(1)" id="slider-dot-1" class="w-2 h-2 rounded-full bg-white/50 transition-all"></button>
                </div>
            </div>
        </section>

        <!-- =============================================================
             SECTION 2: 4 CAM KẾT DỊCH VỤ (TỐI ƯU GỌN ĐẸP TRÊN ĐIỆN THOẠI)
        ============================================================== -->
        <section class="py-4 sm:py-6 bg-white border-b border-gray-200">
            <div class="fs-container">
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
                    <div class="flex flex-col sm:flex-row items-center sm:items-start text-center sm:text-left gap-2 sm:gap-3 p-3 rounded-lg bg-gray-50 border border-gray-100">
                        <div class="w-9 h-9 sm:w-11 sm:h-11 rounded-full bg-amber-100 text-amber-700 flex items-center justify-center shrink-0 text-sm sm:text-lg">
                            <i class="fa-solid fa-award"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-gray-900 text-xs sm:text-sm uppercase">Uy Tín Hàng Đầu</h3>
                            <p class="text-[11px] sm:text-xs text-gray-600 mt-0.5">Đội xe lớn mạnh tại Huế, phục vụ tận tâm 24/7.</p>
                        </div>
                    </div>
                    <div class="flex flex-col sm:flex-row items-center sm:items-start text-center sm:text-left gap-2 sm:gap-3 p-3 rounded-lg bg-gray-50 border border-gray-100">
                        <div class="w-9 h-9 sm:w-11 sm:h-11 rounded-full bg-amber-100 text-amber-700 flex items-center justify-center shrink-0 text-sm sm:text-lg">
                            <i class="fa-solid fa-car-on"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-gray-900 text-xs sm:text-sm uppercase">100% Xe Đời Mới</h3>
                            <p class="text-[11px] sm:text-xs text-gray-600 mt-0.5">Đầy đủ 4 - 7 - 16 - 45 chỗ & Limousine sang trọng.</p>
                        </div>
                    </div>
                    <div class="flex flex-col sm:flex-row items-center sm:items-start text-center sm:text-left gap-2 sm:gap-3 p-3 rounded-lg bg-gray-50 border border-gray-100">
                        <div class="w-9 h-9 sm:w-11 sm:h-11 rounded-full bg-amber-100 text-amber-700 flex items-center justify-center shrink-0 text-sm sm:text-lg">
                            <i class="fa-solid fa-user-tie"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-gray-900 text-xs sm:text-sm uppercase">Tài Xế Chuyên Nghiệp</h3>
                            <p class="text-[11px] sm:text-xs text-gray-600 mt-0.5">Vui vẻ, lịch sự, rành điểm du lịch Huế - Miền Trung.</p>
                        </div>
                    </div>
                    <div class="flex flex-col sm:flex-row items-center sm:items-start text-center sm:text-left gap-2 sm:gap-3 p-3 rounded-lg bg-gray-50 border border-gray-100">
                        <div class="w-9 h-9 sm:w-11 sm:h-11 rounded-full bg-amber-100 text-amber-700 flex items-center justify-center shrink-0 text-sm sm:text-lg">
                            <i class="fa-solid fa-hand-holding-dollar"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-gray-900 text-xs sm:text-sm uppercase">Giá Rẻ Cạnh Tranh</h3>
                            <p class="text-[11px] sm:text-xs text-gray-600 mt-0.5">Báo giá trọn gói rõ ràng, không phát sinh chi phí.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- =============================================================
             SECTION 3: DANH MỤC DỊCH VỤ & DÒNG XE (Tối ưu hiển thị đẹp trên cả Máy Tính & Điện Thoại)
        ============================================================== -->
        <section id="danh-muc-dich-vu" class="py-8 sm:py-10 bg-white">
            <div class="fs-container">
                <div class="section-title-container">
                    <h2 class="section-title-main text-lg sm:text-2xl">
                        <span>DANH MỤC DỊCH VỤ CHO THUÊ XE TẤN TÀI TRAVEL</span>
                    </h2>
                    <p class="text-center text-xs sm:text-sm text-gray-500 mt-1">
                        Chọn nhanh danh mục xe phù hợp với nhu cầu di chuyển của Quý khách
                    </p>
                </div>

                <!-- Grid Danh Mục: 2 cột trên Mobile, 4 cột trên Tablet, 8 cột trên Máy tính -->
                <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
                    <a href="#xe-4-cho" class="group bg-gray-50 hover:bg-amber-600 border border-gray-200 hover:border-amber-600 rounded-lg p-3.5 text-center transition flex flex-col items-center justify-center">
                        <div class="w-12 h-12 rounded-full bg-white text-amber-600 flex items-center justify-center text-xl shadow-sm mb-2 group-hover:scale-110 transition">
                            <i class="fa-solid fa-car-side"></i>
                        </div>
                        <span class="font-bold text-xs sm:text-sm text-gray-800 group-hover:text-white">Xe 4 Chỗ</span>
                        <span class="text-[11px] text-gray-500 group-hover:text-amber-100 mt-0.5">Tự lái & Có tài</span>
                    </a>

                    <a href="#xe-7-cho" class="group bg-gray-50 hover:bg-amber-600 border border-gray-200 hover:border-amber-600 rounded-lg p-3.5 text-center transition flex flex-col items-center justify-center">
                        <div class="w-12 h-12 rounded-full bg-white text-amber-600 flex items-center justify-center text-xl shadow-sm mb-2 group-hover:scale-110 transition">
                            <i class="fa-solid fa-van-shuttle"></i>
                        </div>
                        <span class="font-bold text-xs sm:text-sm text-gray-800 group-hover:text-white">Xe 7 Chỗ</span>
                        <span class="text-[11px] text-gray-500 group-hover:text-amber-100 mt-0.5">Gia đình & Tour</span>
                    </a>

                    <a href="#xe-ban-tai" class="group bg-gray-50 hover:bg-amber-600 border border-gray-200 hover:border-amber-600 rounded-lg p-3.5 text-center transition flex flex-col items-center justify-center">
                        <div class="w-12 h-12 rounded-full bg-white text-amber-600 flex items-center justify-center text-xl shadow-sm mb-2 group-hover:scale-110 transition">
                            <i class="fa-solid fa-truck-pickup"></i>
                        </div>
                        <span class="font-bold text-xs sm:text-sm text-gray-800 group-hover:text-white">Xe Bán Tải</span>
                        <span class="text-[11px] text-gray-500 group-hover:text-amber-100 mt-0.5">Mạnh mẽ, gầm cao</span>
                    </a>

                    <a href="#xe-hop-dong" class="group bg-gray-50 hover:bg-amber-600 border border-gray-200 hover:border-amber-600 rounded-lg p-3.5 text-center transition flex flex-col items-center justify-center">
                        <div class="w-12 h-12 rounded-full bg-white text-amber-600 flex items-center justify-center text-xl shadow-sm mb-2 group-hover:scale-110 transition">
                            <i class="fa-solid fa-crown"></i>
                        </div>
                        <span class="font-bold text-xs sm:text-sm text-gray-800 group-hover:text-white">Xe Limousine</span>
                        <span class="text-[11px] text-gray-500 group-hover:text-amber-100 mt-0.5">VIP Thượng Đỉnh</span>
                    </a>

                    <a href="#xe-hop-dong" class="group bg-gray-50 hover:bg-amber-600 border border-gray-200 hover:border-amber-600 rounded-lg p-3.5 text-center transition flex flex-col items-center justify-center">
                        <div class="w-12 h-12 rounded-full bg-white text-amber-600 flex items-center justify-center text-xl shadow-sm mb-2 group-hover:scale-110 transition">
                            <i class="fa-solid fa-bus-simple"></i>
                        </div>
                        <span class="font-bold text-xs sm:text-sm text-gray-800 group-hover:text-white">Xe 16 Chỗ</span>
                        <span class="text-[11px] text-gray-500 group-hover:text-amber-100 mt-0.5">Transit / Solati</span>
                    </a>

                    <a href="#xe-hop-dong" class="group bg-gray-50 hover:bg-amber-600 border border-gray-200 hover:border-amber-600 rounded-lg p-3.5 text-center transition flex flex-col items-center justify-center">
                        <div class="w-12 h-12 rounded-full bg-white text-amber-600 flex items-center justify-center text-xl shadow-sm mb-2 group-hover:scale-110 transition">
                            <i class="fa-solid fa-bus"></i>
                        </div>
                        <span class="font-bold text-xs sm:text-sm text-gray-800 group-hover:text-white">Xe 29 - 45 Chỗ</span>
                        <span class="text-[11px] text-gray-500 group-hover:text-amber-100 mt-0.5">Hợp đồng đoàn</span>
                    </a>

                    <a href="#bang-gia" class="group bg-gray-50 hover:bg-amber-600 border border-gray-200 hover:border-amber-600 rounded-lg p-3.5 text-center transition flex flex-col items-center justify-center">
                        <div class="w-12 h-12 rounded-full bg-white text-amber-600 flex items-center justify-center text-xl shadow-sm mb-2 group-hover:scale-110 transition">
                            <i class="fa-solid fa-plane-arrival"></i>
                        </div>
                        <span class="font-bold text-xs sm:text-sm text-gray-800 group-hover:text-white">Đón Sân Bay</span>
                        <span class="text-[11px] text-gray-500 group-hover:text-amber-100 mt-0.5">Phú Bài - Đà Nẵng</span>
                    </a>

                    <a href="#form-bao-gia" class="group bg-gray-50 hover:bg-amber-600 border border-gray-200 hover:border-amber-600 rounded-lg p-3.5 text-center transition flex flex-col items-center justify-center">
                        <div class="w-12 h-12 rounded-full bg-white text-amber-600 flex items-center justify-center text-xl shadow-sm mb-2 group-hover:scale-110 transition">
                            <i class="fa-solid fa-heart"></i>
                        </div>
                        <span class="font-bold text-xs sm:text-sm text-gray-800 group-hover:text-white">Xe Cưới Hỏi</span>
                        <span class="text-[11px] text-gray-500 group-hover:text-amber-100 mt-0.5">Sang trọng, lịch lãm</span>
                    </a>
                </div>
            </div>
        </section>

        <!-- =============================================================
             SECTION 4: DANH SÁCH SẢN PHẨM THEO DANH MỤC WEB MẪU
             (Chia 2 cột trên Điện Thoại `grid-cols-2`, 4 cột trên Máy Tính `lg:grid-cols-4`)
             (Có % giảm giá, giá gốc gạch ngang, giá khuyến mãi & nút XEM NHANH chuẩn Flatsome)
        ============================================================== -->
        <div id="products-wrapper" class="space-y-10 py-6">
            <!-- Được render tự động từ dữ liệu đội xe bên dưới để code gọn, sạch và dễ chỉnh sửa -->
        </div>

        <!-- =============================================================
             SECTION 5: BẢNG GIÁ DỊCH VỤ THUÊ XE Ô TÔ (Theo mẫu hopnhattravel.com)
        ============================================================== -->
        <section id="bang-gia" class="py-10 bg-white border-t border-b border-gray-200">
            <div class="fs-container">
                <div class="section-title-container">
                    <h2 class="section-title-main text-lg sm:text-2xl">
                        <span>BẢNG GIÁ DỊCH VỤ THUÊ XE DU LỊCH TẤN TÀI HUẾ</span>
                    </h2>
                    <p class="text-center text-xs sm:text-sm text-gray-500 mt-1">
                        Bảng giá tham khảo đưa đón Sân bay, tham quan Nội thành Huế & đi Đà Nẵng - Hội An - Quảng Bình
                    </p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
                    <!-- Bảng 1: Đưa đón sân bay & Nội thành Huế -->
                    <div class="border border-gray-200 rounded-lg overflow-hidden shadow-sm">
                        <div class="bg-[#1a1510] text-amber-400 font-bold text-sm uppercase px-4 py-3 flex items-center justify-between">
                            <span>1. Bảng Giá Xe Sân Bay & Tham Quan Huế</span>
                            <span class="text-xs text-white font-normal">ĐVT: VNĐ</span>
                        </div>
                        <div class="overflow-x-auto">
                            <table class="w-full text-xs sm:text-sm text-left">
                                <thead class="bg-gray-100 text-gray-700 uppercase font-bold border-b border-gray-200">
                                    <tr>
                                        <th class="py-2.5 px-3">Hành Trình</th>
                                        <th class="py-2.5 px-2 text-center">4 Chỗ</th>
                                        <th class="py-2.5 px-2 text-center">7 Chỗ</th>
                                        <th class="py-2.5 px-2 text-center">16 Chỗ</th>
                                    </tr>
                                </thead>
                                <tbody class="divide-y divide-gray-200">
                                    <tr class="hover:bg-amber-50/40">
                                        <td class="py-2.5 px-3 font-medium">Đón / Tiễn Sân Bay Phú Bài - TP. Huế</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">200k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">250k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">450k</td>
                                    </tr>
                                    <tr class="hover:bg-amber-50/40">
                                        <td class="py-2.5 px-3 font-medium">City Tour Nội Thành Huế (Đại Nội - Chùa Thiên Mụ - Lăng)</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">700k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">850k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.200k</td>
                                    </tr>
                                    <tr class="hover:bg-amber-50/40">
                                        <td class="py-2.5 px-3 font-medium">Huế - Vườn Quốc Gia Bạch Mã (2 Chiều)</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">899k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.050k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.350k</td>
                                    </tr>
                                    <tr class="hover:bg-amber-50/40">
                                        <td class="py-2.5 px-3 font-medium">Huế - Vịnh Lăng Cô - Đầm Lập An (2 Chiều)</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">850k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">950k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.300k</td>
                                    </tr>
                                    <tr class="hover:bg-amber-50/40">
                                        <td class="py-2.5 px-3 font-medium">Huế - Thánh Địa La Vang - Quảng Trị (2 Chiều)</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">900k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.050k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.400k</td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                    </div>

                    <!-- Bảng 2: Huế <-> Đà Nẵng - Hội An - Quảng Bình -->
                    <div class="border border-gray-200 rounded-lg overflow-hidden shadow-sm">
                        <div class="bg-[#1a1510] text-amber-400 font-bold text-sm uppercase px-4 py-3 flex items-center justify-between">
                            <span>2. Bảng Giá Xe Huế Đi Đà Nẵng - Hội An - Tỉnh</span>
                            <span class="text-xs text-white font-normal">ĐVT: VNĐ</span>
                        </div>
                        <div class="overflow-x-auto">
                            <table class="w-full text-xs sm:text-sm text-left">
                                <thead class="bg-gray-100 text-gray-700 uppercase font-bold border-b border-gray-200">
                                    <tr>
                                        <th class="py-2.5 px-3">Hành Trình</th>
                                        <th class="py-2.5 px-2 text-center">4 Chỗ</th>
                                        <th class="py-2.5 px-2 text-center">7 Chỗ</th>
                                        <th class="py-2.5 px-2 text-center">16 Chỗ</th>
                                    </tr>
                                </thead>
                                <tbody class="divide-y divide-gray-200">
                                    <tr class="hover:bg-amber-50/40">
                                        <td class="py-2.5 px-3 font-medium">Huế &lt;-&gt; Đà Nẵng (1 Chiều - Đón Tận Nơi)</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">950k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.150k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.450k</td>
                                    </tr>
                                    <tr class="hover:bg-amber-50/40">
                                        <td class="py-2.5 px-3 font-medium">Huế &lt;-&gt; Đà Nẵng (2 Chiều Trong Ngày)</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.299k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.499k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.899k</td>
                                    </tr>
                                    <tr class="hover:bg-amber-50/40">
                                        <td class="py-2.5 px-3 font-medium">Huế &lt;-&gt; Bà Nà Hills / Hội An (2 Chiều)</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.499k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.699k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">2.199k</td>
                                    </tr>
                                    <tr class="hover:bg-amber-50/40">
                                        <td class="py-2.5 px-3 font-medium">Huế &lt;-&gt; Phong Nha - Quảng Bình (Trong Ngày)</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.799k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">1.999k</td>
                                        <td class="py-2.5 px-2 text-center font-bold text-red-600">2.599k</td>
                                    </tr>
                                    <tr class="hover:bg-amber-50/40">
                                        <td class="py-2.5 px-3 font-medium">Thuê Xe Hợp Đồng 29 - 35 - 45 Chỗ & Limousine</td>
                                        <td colspan="3" class="py-2.5 px-2 text-center font-bold text-amber-700">
                                            Liên hệ 0935.325.246 - 0842.565.246 nhận giá ưu đãi
                                        </td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- =============================================================
             SECTION 6: FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ
        ============================================================== -->
        <section id="form-bao-gia" class="py-10 bg-[#1a1510] text-white">
            <div class="fs-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    
                    <!-- Cột thông tin tư vấn bên trái -->
                    <div class="lg:col-span-5 space-y-4">
                        <div class="text-amber-400 font-bold text-xs uppercase tracking-widest">
                            ĐẶT XE NHANH CHÓNG - GIÁ RẺ TẬN GỐC
                        </div>
                        <h2 class="text-2xl sm:text-3xl font-black uppercase leading-tight">
                            YÊU CẦU TƯ VẤN & <span class="text-amber-400">NHẬN BÁO GIÁ NGAY</span>
                        </h2>
                        <p class="text-sm text-gray-300 leading-relaxed">
                            Quý khách cần thuê xe du lịch, xe hợp đồng, xe tự lái, xe cưới hỏi hay đưa đón sân bay tại Huế và Miền Trung? Vui lòng điền thông tin bên cạnh, Đội Xe Tấn Tài Travel sẽ liên hệ báo giá tốt nhất chỉ sau 3 phút!
                        </p>
                        <div class="space-y-2.5 pt-2 text-sm">
                            <div class="flex items-center gap-3">
                                <span class="w-8 h-8 rounded-full bg-amber-500/20 text-amber-400 flex items-center justify-center"><i class="fa-solid fa-location-dot"></i></span>
                                <span>Địa chỉ: <strong>27 Tôn Thất Bật, Thành phố Huế</strong></span>
                            </div>
                            <div class="flex items-center gap-3">
                                <span class="w-8 h-8 rounded-full bg-amber-500/20 text-amber-400 flex items-center justify-center"><i class="fa-solid fa-phone-volume"></i></span>
                                <span>Hotline 1: <a href="tel:0935325246" class="font-bold text-amber-400 hover:underline">0935.325.246</a></span>
                            </div>
                            <div class="flex items-center gap-3">
                                <span class="w-8 h-8 rounded-full bg-amber-500/20 text-amber-400 flex items-center justify-center"><i class="fa-solid fa-phone"></i></span>
                                <span>Hotline 2: <a href="tel:0842565246" class="font-bold text-amber-400 hover:underline">0842.565.246</a></span>
                            </div>
                            <div class="flex items-center gap-3">
                                <span class="w-8 h-8 rounded-full bg-amber-500/20 text-amber-400 flex items-center justify-center"><i class="fa-solid fa-globe"></i></span>
                                <span>Website: <strong>tantaitravel.com</strong></span>
                            </div>
                        </div>
                    </div>

                    <!-- Cột Form Yêu Cầu & Báo Giá bên phải -->
                    <div class="lg:col-span-7 bg-white text-gray-800 rounded-xl p-5 sm:p-7 shadow-xl border-t-4 border-amber-500">
                        <h3 class="text-lg font-extrabold uppercase text-gray-900 mb-4 flex items-center gap-2">
                            <i class="fa-solid fa-clipboard-list text-amber-600"></i>
                            ĐIỀN THÔNG TIN YÊU CẦU BÁO GIÁ THUÊ XE
                        </h3>
                        <form id="quote-request-form" onsubmit="submitQuoteForm(event)" class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-bold uppercase text-gray-600 mb-1">Họ và Tên *</label>
                                <input id="q-name" type="text" required placeholder="Nhập họ và tên của bạn" class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-md focus:outline-none focus:border-amber-600">
                            </div>
                            <div>
                                <label class="block text-xs font-bold uppercase text-gray-600 mb-1">Số Điện Thoại / Zalo *</label>
                                <input id="q-phone" type="tel" required placeholder="Nhập số điện thoại liên hệ" class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-md focus:outline-none focus:border-amber-600">
                            </div>
                            <div>
                                <label class="block text-xs font-bold uppercase text-gray-600 mb-1">Chọn Dịch Vụ Cần Thuê *</label>
                                <select id="q-service" class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-md focus:outline-none focus:border-amber-600 bg-white">
                                    <option value="Thuê xe du lịch có tài xế">Thuê xe du lịch có tài xế</option>
                                    <option value="Thuê xe tự lái (4 - 7 chỗ)">Thuê xe tự lái (4 - 7 chỗ)</option>
                                    <option value="Thuê xe hợp đồng công ty / đoàn">Thuê xe hợp đồng công ty / đoàn</option>
                                    <option value="Thuê xe Limousine thượng đỉnh">Thuê xe Limousine thượng đỉnh</option>
                                    <option value="Thuê xe cưới hỏi - rước dâu">Thuê xe cưới hỏi - rước dâu</option>
                                    <option value="Xe đưa đón sân bay Phú Bài / Đà Nẵng">Xe đưa đón sân bay Phú Bài / Đà Nẵng</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold uppercase text-gray-600 mb-1">Loại Xe Quan Tâm *</label>
                                <select id="q-car" class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-md focus:outline-none focus:border-amber-600 bg-white">
                                    <option value="Xe 4 Chỗ Đời Mới">Xe 4 Chỗ Đời Mới</option>
                                    <option value="Xe 7 Chỗ / 5+2 Chỗ Gia Đình">Xe 7 Chỗ / 5+2 Chỗ Gia Đình</option>
                                    <option value="Xe Bán Tải Gầm Cao">Xe Bán Tải Gầm Cao</option>
                                    <option value="Xe Limousine 9 - 16 Chỗ">Xe Limousine 9 - 16 Chỗ</option>
                                    <option value="Xe 16 Chỗ (Ford Transit / Solati)">Xe 16 Chỗ (Ford Transit / Solati)</option>
                                    <option value="Xe 29 - 35 - 45 Chỗ Đoàn Lớn">Xe 29 - 35 - 45 Chỗ Đoàn Lớn</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold uppercase text-gray-600 mb-1">Lịch Trình (Điểm đón - Điểm đến)</label>
                                <input id="q-route" type="text" placeholder="VD: Huế đi Đà Nẵng - Hội An 2 ngày" class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-md focus:outline-none focus:border-amber-600">
                            </div>
                            <div>
                                <label class="block text-xs font-bold uppercase text-gray-600 mb-1">Ngày Khởi Hành Dự Kiến</label>
                                <input id="q-date" type="date" class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-md focus:outline-none focus:border-amber-600">
                            </div>
                            <div class="sm:col-span-2">
                                <label class="block text-xs font-bold uppercase text-gray-600 mb-1">Ghi Chú Thêm</label>
                                <textarea id="q-note" rows="2" placeholder="Nhập yêu cầu cụ thể (số lượng khách, thời gian đón...)" class="w-full px-3.5 py-2 text-sm border border-gray-300 rounded-md focus:outline-none focus:border-amber-600"></textarea>
                            </div>
                            <div class="sm:col-span-2 flex flex-wrap items-center gap-3 pt-1">
                                <button type="submit" class="flex-1 bg-red-600 hover:bg-red-700 text-white font-extrabold text-sm uppercase py-3 px-6 rounded-md shadow transition flex items-center justify-center gap-2">
                                    <i class="fa-solid fa-paper-plane"></i> GỬI YÊU CẦU BÁO GIÁ
                                </button>
                                <a href="https://zalo.me/0935325246" target="_blank" rel="noopener" class="bg-blue-600 hover:bg-blue-700 text-white font-bold text-sm uppercase py-3 px-5 rounded-md shadow transition flex items-center justify-center gap-2">
                                    <i class="fa-solid fa-comment-dots"></i> Chat Zalo Ngay
                                </a>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- =============================================================
             SECTION 7: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (BLOG POSTS ELEMENT)
        ============================================================== -->
        <section id="bai-viet-trang-chu" class="py-10 bg-gray-50">
            <div class="fs-container">
                <div class="section-title-container">
                    <h2 class="section-title-main text-lg sm:text-2xl">
                        <span>DANH MỤC BÀI VIẾT & CẨM NANG THUÊ XE DU LỊCH</span>
                    </h2>
                    <p class="text-center text-xs sm:text-sm text-gray-500 mt-1">
                        Kinh nghiệm thuê xe du lịch Huế - Đà Nẵng - Hội An và hoạt động thực tế của Đội Xe Tấn Tài Travel
                    </p>
                </div>

                <!-- Thanh Lọc Danh Mục Bài Viết Trang Chủ -->
                <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
                    <button onclick="filterBlogPosts('all')" id="blog-tab-all" class="blog-tab-btn px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-amber-600 text-white transition">
                        Tất Cả Bài Viết
                    </button>
                    <button onclick="filterBlogPosts('hoat-dong')" id="blog-tab-hoat-dong" class="blog-tab-btn px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-white text-gray-700 border border-gray-200 hover:border-amber-600 transition">
                        Hoạt Động Đội Xe Tấn Tài
                    </button>
                    <button onclick="filterBlogPosts('kinh-nghiem')" id="blog-tab-kinh-nghiem" class="blog-tab-btn px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-white text-gray-700 border border-gray-200 hover:border-amber-600 transition">
                        Kinh Nghiệm Thuê Xe
                    </button>
                    <button onclick="filterBlogPosts('cam-nang')" id="blog-tab-cam-nang" class="blog-tab-btn px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-white text-gray-700 border border-gray-200 hover:border-amber-600 transition">
                        Cẩm Nang Du Lịch Huế - Miền Trung
                    </button>
                </div>

                <!-- Grid Bài Viết Trang Chủ (2 cột trên Mobile, 4 cột trên Máy tính giống Flatsome Blog Element) -->
                <div id="blog-posts-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Được render từ danh sách bài viết thực tế bên dưới -->
                </div>
            </div>
        </section>

        <!-- =============================================================
             SECTION 8: ĐƯA ẢNH & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ
             Địa chỉ: 27 Tôn Thất Bật, Thành phố Huế
        ============================================================== -->
        <section id="ban-do-google" class="py-10 bg-white border-t border-gray-200">
            <div class="fs-container">
                <div class="section-title-container">
                    <h2 class="section-title-main text-lg sm:text-2xl">
                        <span>BẢN ĐỒ ĐỊA CHỈ ĐỘI XE TẤN TÀI TRAVEL TẠI HUẾ</span>
                    </h2>
                    <p class="text-center text-xs sm:text-sm text-gray-600 mt-1">
                        <i class="fa-solid fa-location-dot text-red-600"></i> Địa chỉ: <strong>27 Tôn Thất Bật, Thành phố Huế</strong> | Hotline: <strong>0935.325.246 - 0842.565.246</strong>
                    </p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                    <!-- Thông tin Trụ sở & Chỉ đường nhanh -->
                    <div class="lg:col-span-4 bg-gray-50 border border-gray-200 rounded-xl p-5 flex flex-col justify-between">
                        <div class="space-y-4">
                            <div class="flex items-center gap-3 pb-3 border-b border-gray-200">
                                <div class="w-12 h-12 rounded-lg bg-[#1a1510] text-amber-400 flex items-center justify-center text-xl shrink-0">
                                    <i class="fa-solid fa-map-pin"></i>
                                </div>
                                <div>
                                    <h3 class="font-black text-gray-900 text-sm uppercase">ĐỘI XE TẤN TÀI TRAVEL</h3>
                                    <p class="text-xs text-amber-700 font-semibold">CÔNG TY TNHH MTV VẬN TẢI & DU LỊCH TẤN TÀI</p>
                                </div>
                            </div>

                            <div class="space-y-3 text-xs sm:text-sm text-gray-700">
                                <p class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-location-dot text-red-600 mt-1 w-4 text-center"></i>
                                    <span><strong>Địa chỉ văn phòng & bãi xe:</strong><br>27 Tôn Thất Bật, Thành phố Huế</span>
                                </p>
                                <p class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-phone-volume text-amber-600 mt-1 w-4 text-center"></i>
                                    <span><strong>Điện thoại đặt xe 24/7:</strong><br><a href="tel:0935325246" class="text-red-600 font-bold">0935.325.246</a> - <a href="tel:0842565246" class="text-red-600 font-bold">0842.565.246</a></span>
                                </p>
                                <p class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-envelope text-amber-600 mt-1 w-4 text-center"></i>
                                    <span><strong>Email:</strong> dulichtantai@gmail.com</span>
                                </p>
                                <p class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-globe text-amber-600 mt-1 w-4 text-center"></i>
                                    <span><strong>Website:</strong> tantaitravel.com</span>
                                </p>
                            </div>
                        </div>

                        <div class="pt-4 mt-4 border-t border-gray-200 flex flex-col gap-2">
                            <a href="https://www.google.com/maps/search/?api=1&query=27+T%C3%B4n+Th%E1%BA%A5t+B%E1%BA%ADt,+Th%C3%A0nh+ph%E1%BB%91+Hu%E1%BA%BF" target="_blank" rel="noopener" class="w-full py-2.5 bg-amber-600 hover:bg-amber-700 text-white font-bold text-xs uppercase rounded-md text-center transition">
                                <i class="fa-solid fa-diamond-turn-right mr-1"></i> Mở Chỉ Đường Trên Google Maps
                            </a>
                            <a href="https://www.facebook.com/profile.php?id=100063480277479" target="_blank" rel="noopener" class="w-full py-2.5 bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs uppercase rounded-md text-center transition">
                                <i class="fa-brands fa-facebook mr-1"></i> Xem Fanpage Đội Xe Tấn Tài
                            </a>
                        </div>
                    </div>

                    <!-- Bản đồ Google Map hiển thị trực tiếp ngoài Trang Chủ -->
                    <div class="lg:col-span-8 rounded-xl overflow-hidden border border-gray-300 shadow-sm min-h-[320px] sm:min-h-[380px] relative bg-gray-100">
                        <iframe 
                            title="Google Map Địa chỉ 27 Tôn Thất Bật, Thành phố Huế"
                            src="https://maps.google.com/maps?q=27%20T%C3%B4n%20Th%E1%BA%A5t%20B%E1%BA%ADt,%20Th%C3%A0nh%20ph%E1%BB%91%20Hu%E1%BA%BF&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full min-h-[320px] sm:min-h-[380px] border-0"
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- =================================================================
         FOOTER (#footer) - CHUẨN FLATSOME 4 CỘT
    ================================================================== -->
    <footer id="footer" class="bg-[#1a1510] text-gray-300 pt-12 pb-20 sm:pb-10 border-t-4 border-amber-600">
        <div class="fs-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-gray-800">
                
                <!-- Cột 1: Thông tin Đội Xe Tấn Tài Travel -->
                <div class="space-y-3">
                    <h4 class="text-white font-black text-base uppercase tracking-wide border-b-2 border-amber-500 inline-block pb-1">
                        ĐỘI XE TẤN TÀI TRAVEL
                    </h4>
                    <p class="text-xs text-amber-400 font-bold uppercase">
                        CÔNG TY TNHH MTV VẬN TẢI VÀ DU LỊCH TẤN TÀI
                    </p>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i> <strong>Địa chỉ:</strong> 27 Tôn Thất Bật, Thành phố Huế</li>
                        <li><i class="fa-solid fa-phone text-amber-400 w-5"></i> <strong>Hotline/Zalo:</strong> 0935.325.246 - 0842.565.246</li>
                        <li><i class="fa-solid fa-id-card text-amber-400 w-5"></i> <strong>Mã số thuế:</strong> 3301733214</li>
                        <li><i class="fa-solid fa-envelope text-amber-400 w-5"></i> <strong>Email:</strong> dulichtantai@gmail.com</li>
                        <li><i class="fa-solid fa-globe text-amber-400 w-5"></i> <strong>Website:</strong> tantaitravel.com</li>
                    </ul>
                </div>

                <!-- Cột 2: TOP Dịch Vụ Thuê Xe -->
                <div class="space-y-3">
                    <h4 class="text-white font-black text-base uppercase tracking-wide border-b-2 border-amber-500 inline-block pb-1">
                        DỊCH VỤ THUÊ XE CHÍNH
                    </h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#xe-4-cho" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Cho thuê xe tự lái Huế 4 - 7 chỗ</a></li>
                        <li><a href="#xe-4-cho" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Cho thuê xe du lịch Huế có tài xế</a></li>
                        <li><a href="#xe-hop-dong" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Cho thuê xe hợp đồng 16 - 45 chỗ</a></li>
                        <li><a href="#xe-hop-dong" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Cho thuê xe Limousine thượng đỉnh</a></li>
                        <li><a href="#xe-hop-dong" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Cho thuê xe đám cưới, rước dâu</a></li>
                        <li><a href="#bang-gia" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Xe đưa đón sân bay Phú Bài - Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Dịch Vụ Thuê Xe Đi Tỉnh -->
                <div class="space-y-3">
                    <h4 class="text-white font-black text-base uppercase tracking-wide border-b-2 border-amber-500 inline-block pb-1">
                        THUÊ XE ĐI CÁC TỈNH
                    </h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#bang-gia" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Thuê xe Huế đi Đà Nẵng - Hội An</a></li>
                        <li><a href="#bang-gia" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Thuê xe Huế đi Bà Nà Hills</a></li>
                        <li><a href="#bang-gia" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Thuê xe Huế đi Lăng Cô - Bạch Mã</a></li>
                        <li><a href="#bang-gia" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Thuê xe Huế đi Quảng Trị - La Vang</a></li>
                        <li><a href="#bang-gia" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Thuê xe Huế đi Quảng Bình - Phong Nha</a></li>
                        <li><a href="#bang-gia" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Hợp đồng tour xuyên Việt giá tốt</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối Fanpage -->
                <div class="space-y-3">
                    <h4 class="text-white font-black text-base uppercase tracking-wide border-b-2 border-amber-500 inline-block pb-1">
                        KẾT NỐI VỚI CHÚNG TÔI
                    </h4>
                    <p class="text-xs text-gray-400">
                        Theo dõi Fanpage chính thức của Đội Xe Tấn Tài Travel để cập nhật hình ảnh dàn xe thực tế và ưu đãi mới nhất.
                    </p>
                    <div class="bg-white/5 border border-amber-500/30 rounded-lg p-3.5 space-y-2.5">
                        <div class="font-bold text-amber-400 text-sm">Đội Xe Tấn Tài Travel</div>
                        <div class="text-xs text-gray-300">Chuyên xe du lịch 4 - 45 chỗ & Limousine tại TP. Huế</div>
                        <div class="flex flex-wrap gap-2 pt-1">
                            <a href="https://www.facebook.com/profile.php?id=100063480277479" target="_blank" rel="noopener" class="px-3 py-1.5 bg-blue-600 hover:bg-blue-700 text-white rounded text-xs font-bold inline-flex items-center gap-1.5">
                                <i class="fa-brands fa-facebook-f"></i> Fanpage Facebook
                            </a>
                            <a href="https://zalo.me/0935325246" target="_blank" rel="noopener" class="px-3 py-1.5 bg-sky-500 hover:bg-sky-600 text-white rounded text-xs font-bold inline-flex items-center gap-1.5">
                                <i class="fa-solid fa-comment"></i> Chat Zalo
                            </a>
                        </div>
                    </div>
                </div>

            </div>

            <div class="pt-6 text-center text-xs text-gray-400 flex flex-col sm:flex-row items-center justify-between gap-2">
                <p>© Bản quyền thuộc về <strong class="text-amber-400">Đội Xe Tấn Tài Travel (tantaitravel.com)</strong> - Địa chỉ: 27 Tôn Thất Bật, TP. Huế.</p>
                <p>Hotline đặt xe: <strong class="text-white">0935.325.246 - 0842.565.246</strong></p>
            </div>
        </div>
    </footer>

</div>

<!-- =====================================================================
     CÁC NÚT LIÊN HỆ NỔI BẬT (ĐÃ THU NHỎ GỌN GÀNG, KHÔNG CHE NỘI DUNG TRÊN ĐIỆN THOẠI)
====================================================================== -->
<div class="fixed left-2.5 bottom-3 z-40 flex flex-col items-start gap-1.5">
    <!-- Nút Facebook Fanpage -->
    <a href="https://www.facebook.com/profile.php?id=100063480277479" target="_blank" rel="noopener" class="w-fit flex items-center gap-1.5 bg-[#1877F2] hover:bg-blue-700 text-white pl-1.5 pr-2.5 py-1 rounded-full shadow-md transition">
        <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center font-bold text-xs shrink-0">
            <i class="fa-brands fa-facebook-f"></i>
        </span>
        <span class="text-[11px] font-bold leading-none">Fanpage</span>
    </a>

    <!-- Nút Chat Zalo Nổi Bật -->
    <a href="https://zalo.me/0935325246" target="_blank" rel="noopener" class="btn-float-zalo w-fit flex items-center gap-1.5 bg-[#0068ff] hover:bg-blue-600 text-white pl-1.5 pr-2.5 py-1 rounded-full shadow-md transition">
        <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] flex items-center justify-center font-black text-[9px] shrink-0">
            Zalo
        </span>
        <span class="text-[11px] font-bold leading-none">0935.325.246</span>
    </a>

    <!-- Nút Hotline 1 -->
    <a href="tel:0935325246" class="btn-float-hotline w-fit flex items-center gap-1.5 bg-red-600 hover:bg-red-700 text-white pl-1.5 pr-2.5 py-1 rounded-full shadow-md transition">
        <span class="w-6 h-6 rounded-full bg-white text-red-600 flex items-center justify-center text-[11px] shrink-0">
            <i class="fa-solid fa-phone-volume"></i>
        </span>
        <span class="text-[11px] font-black leading-none">0935.325.246</span>
    </a>

    <!-- Nút Hotline 2 -->
    <a href="tel:0842565246" class="w-fit flex items-center gap-1.5 bg-[#1a1510] hover:bg-amber-700 text-amber-400 hover:text-white border border-amber-500/50 pl-1.5 pr-2.5 py-1 rounded-full shadow-md transition">
        <span class="w-6 h-6 rounded-full bg-amber-500 text-gray-950 flex items-center justify-center text-[11px] shrink-0">
            <i class="fa-solid fa-phone"></i>
        </span>
        <span class="text-[11px] font-black leading-none">0842.565.246</span>
    </a>
</div>

<!-- =====================================================================
     MODAL XEM NHANH SẢN PHẨM (QUICK VIEW LIGHTBOX CHUẨN FLATSOME)
====================================================================== -->
<div id="quick-view-modal" class="fixed inset-0 bg-black/70 z-50 hidden items-center justify-center p-3 sm:p-6">
    <div class="bg-white rounded-xl max-w-3xl w-full overflow-hidden shadow-2xl relative animate-fadeIn max-h-[90vh] overflow-y-auto">
        <!-- Nút Đóng Quick View -->
        <button onclick="closeQuickView()" class="absolute top-3 right-3 z-20 w-9 h-9 rounded-full bg-gray-900/80 hover:bg-red-600 text-white flex items-center justify-center transition">
            <i class="fa-solid fa-xmark"></i>
        </button>

        <div class="grid grid-cols-1 md:grid-cols-2">
            <!-- Cột Ảnh Xe -->
            <div class="relative bg-gray-100 min-h-[240px] md:min-h-[360px]">
                <span id="qv-discount" class="badge-sale-flatsome">-20%</span>
                <img id="qv-image" src="" alt="Hình ảnh xe" class="w-full h-full object-cover">
            </div>

            <!-- Cột Thông Tin Chi Tiết Xe -->
            <div class="p-5 sm:p-6 flex flex-col justify-between space-y-4">
                <div>
                    <div id="qv-category" class="text-xs font-bold uppercase text-amber-700 tracking-wide">Danh mục xe</div>
                    <h3 id="qv-title" class="text-lg sm:text-xl font-black text-gray-900 mt-1">Tên xe</h3>
                    <div class="w-10 h-1 bg-amber-500 my-3"></div>

                    <!-- Giá gốc & Giá giảm chuẩn Flatsome -->
                    <div class="flex items-baseline gap-2.5">
                        <del id="qv-old-price" class="text-sm text-gray-400 font-semibold">1.000.000 ₫</del>
                        <span id="qv-price" class="text-xl sm:text-2xl font-black text-red-600">800.000 ₫</span>
                        <span class="text-xs text-gray-500">/ ngày</span>
                    </div>

                    <p id="qv-desc" class="text-xs sm:text-sm text-gray-600 mt-3 leading-relaxed"></p>

                    <ul class="mt-4 space-y-1.5 text-xs sm:text-sm text-gray-700 border-t border-gray-100 pt-3">
                        <li><i class="fa-solid fa-check text-green-600 mr-1.5"></i> Xe đời mới, nội thất sạch đẹp, máy lạnh mát sâu.</li>
                        <li><i class="fa-solid fa-check text-green-600 mr-1.5"></i> Giao xe tận nơi tại TP. Huế hoặc đón tại Sân bay Phú Bài.</li>
                        <li><i class="fa-solid fa-check text-green-600 mr-1.5"></i> Thủ tục nhanh gọn, hỗ trợ tư vấn lịch trình 24/7.</li>
                    </ul>
                </div>

                <div class="space-y-2 pt-3 border-t border-gray-100">
                    <div class="grid grid-cols-2 gap-2">
                        <a href="tel:0935325246" class="py-2.5 px-3 bg-red-600 hover:bg-red-700 text-white font-bold text-xs uppercase rounded text-center transition">
                            <i class="fa-solid fa-phone mr-1"></i> 0935.325.246
                        </a>
                        <a href="tel:0842565246" class="py-2.5 px-3 bg-[#1a1510] hover:bg-gray-800 text-amber-400 font-bold text-xs uppercase rounded text-center transition">
                            <i class="fa-solid fa-phone mr-1"></i> 0842.565.246
                        </a>
                    </div>
                    <button onclick="selectCarToQuote()" class="w-full py-2.5 bg-amber-500 hover:bg-amber-600 text-gray-950 font-extrabold text-xs uppercase rounded transition">
                        <i class="fa-solid fa-calendar-check mr-1"></i> Đặt Xe Này Qua Form Báo Giá
                    </button>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- =====================================================================
     MODAL ĐỌC CHI TIẾT BÀI VIẾT / THÔNG BÁO GỬI FORM
====================================================================== -->
<div id="info-modal" class="fixed inset-0 bg-black/70 z-50 hidden items-center justify-center p-4">
    <div class="bg-white rounded-xl max-w-xl w-full p-6 shadow-2xl relative">
        <button onclick="closeInfoModal()" class="absolute top-3 right-3 w-8 h-8 rounded-full bg-gray-200 hover:bg-red-600 hover:text-white flex items-center justify-center transition">
            <i class="fa-solid fa-xmark"></i>
        </button>
        <h3 id="info-modal-title" class="text-lg font-black text-gray-900 uppercase pr-6">Thông báo</h3>
        <div class="w-10 h-1 bg-amber-500 my-2.5"></div>
        <div id="info-modal-body" class="text-sm text-gray-700 space-y-2 leading-relaxed"></div>
        <div class="mt-5 flex justify-end gap-2">
            <a href="tel:0935325246" class="px-4 py-2 bg-red-600 text-white rounded text-xs font-bold uppercase">Gọi 0935.325.246</a>
            <button onclick="closeInfoModal()" class="px-4 py-2 bg-gray-800 text-white rounded text-xs font-bold uppercase">Đóng</button>
        </div>
    </div>
</div>

<!-- =====================================================================
     JAVASCRIPT XỬ LÝ SLIDER TỰ TRƯỢT, SẢN PHẨM, XEM NHANH, BÀI VIẾT & FORM
====================================================================== -->
<script>
    // 1. DỮ LIỆU DANH MỤC & SẢN PHẨM XE (Theo mẫu hopnhattravel.com + Đội Xe Tấn Tài Travel Huế)
    const PRODUCT_SECTIONS = [
        {
            id: "xe-4-cho",
            title: "MẪU XE Ô TÔ 4 CHỖ HOT",
            subtitle: "Dịch vụ cho thuê xe 4 chỗ tự lái, có tài xế, đưa đón sân bay, cưới hỏi tại Huế",
            items: [
                {
                    id: "vios-4c",
                    name: "Cho Thuê Xe Toyota Vios 4 Chỗ [Tự Lái - Có Tài] Thủ Tục Nhanh",
                    category: "Xe Ô Tô 4 Chỗ",
                    oldPrice: "800.000 ₫",
                    price: "600.000 ₫",
                    discount: "-25%",
                    image: "https://images.unsplash.com/photo-1590362891991-f776e747a588?auto=format&fit=crop&w=700&q=80",
                    desc: "Dòng xe sedan 4 chỗ Toyota Vios bền bỉ, tiết kiệm nhiên liệu, cốp rộng rãi. Phù hợp thuê tự lái hoặc có tài xế đưa đón tham quan Lăng Tẩm Huế, đi Đà Nẵng - Hội An."
                },
                {
                    id: "accent-4c",
                    name: "Cho Thuê Xe Hyundai Accent 4 Chỗ Đời Mới [Tự Lái, Du Lịch, Cưới Hỏi]",
                    category: "Xe Ô Tô 4 Chỗ",
                    oldPrice: "800.000 ₫",
                    price: "600.000 ₫",
                    discount: "-25%",
                    image: "https://images.unsplash.com/photo-1605559424843-9e4c228bf1c2?auto=format&fit=crop&w=700&q=80",
                    desc: "Hyundai Accent số tự động đời mới, kiểu dáng trẻ trung, nội thất bọc da sang trọng, vận hành êm ái trên mọi cung đường Huế - Lăng Cô - Đà Nẵng."
                },
                {
                    id: "mazda3-4c",
                    name: "Cho Thuê Xe Mazda 3 (4 Chỗ) Sang Trọng [Tự Lái, Xe Hoa Cưới Hỏi]",
                    category: "Xe Ô Tô 4 Chỗ",
                    oldPrice: "1.100.000 ₫",
                    price: "900.000 ₫",
                    discount: "-18%",
                    image: "https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=700&q=80",
                    desc: "Mazda 3 thiết kế KODO lịch lãm, rất được ưa chuộng làm xe hoa rước dâu, đi công tác ngoại giao hoặc du lịch gia đình tại TP. Huế."
                },
                {
                    id: "vinfast-4c",
                    name: "Thuê Xe VinFast Lux A2.0 / Honda Civic 4 Chỗ [Tự Lái, Đám Cưới, Hợp Đồng]",
                    category: "Xe Ô Tô 4 Chỗ",
                    oldPrice: "1.400.000 ₫",
                    price: "1.150.000 ₫",
                    discount: "-18%",
                    image: "https://images.unsplash.com/photo-1617788138017-80ad40651399?auto=format&fit=crop&w=700&q=80",
                    desc: "Phân khúc sedan hạng sang, cách âm vượt trội, mang lại trải nghiệm đẳng cấp cho các chuyến công tác VIP và sự kiện cưới hỏi tại Huế."
                }
            ]
        },
        {
            id: "xe-7-cho",
            title: "MẪU XE Ô TÔ 7 CHỖ & 5+2 CHỖ HOT",
            subtitle: "Rộng rãi, gầm cao thoáng mát cho gia đình và nhóm bạn du lịch Huế - Đà Nẵng - Quảng Bình",
            items: [
                {
                    id: "xpander-7c",
                    name: "Cho Thuê Xe Mitsubishi Xpander 7 Chỗ Đời Mới Chỉ 700K/Ngày",
                    category: "Xe Ô Tô 7 Chỗ",
                    oldPrice: "900.000 ₫",
                    price: "700.000 ₫",
                    discount: "-22%",
                    image: "https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?auto=format&fit=crop&w=700&q=80",
                    desc: "Mitsubishi Xpander 7 chỗ đời mới cực kỳ tiết kiệm xăng, điều hòa 2 dàn lạnh sâu, lựa chọn số 1 cho gia đình đi tham quan Huế - Bà Nà - Hội An."
                },
                {
                    id: "innova-7c",
                    name: "Cho Thuê Xe Toyota Innova 7 Chỗ (Hợp Đồng, Du Lịch, Đón Sân Bay)",
                    category: "Xe Ô Tô 7 Chỗ",
                    oldPrice: "1.000.000 ₫",
                    price: "800.000 ₫",
                    discount: "-20%",
                    image: "https://images.unsplash.com/photo-1549399542-7e3f8b79c341?auto=format&fit=crop&w=700&q=80",
                    desc: "Toyota Innova rộng rãi cho 7 hành khách kèm hành lý lớn, cực kỳ đầm chắc khi đi đèo Hải Vân, Vườn Quốc Gia Bạch Mã hay Phong Nha."
                },
                {
                    id: "fortuner-7c",
                    name: "Cho Thuê Xe Toyota Fortuner 7 Chỗ Du Lịch & Công Tác (Gầm Cao)",
                    category: "Xe Ô Tô 7 Chỗ",
                    oldPrice: "1.200.000 ₫",
                    price: "950.000 ₫",
                    discount: "-21%",
                    image: "https://images.unsplash.com/photo-1519641471654-76ce0107ad1b?auto=format&fit=crop&w=700&q=80",
                    desc: "SUV 7 chỗ Toyota Fortuner mạnh mẽ, sang trọng, thích hợp đi công tác đường dài, dự án hoặc du lịch gia đình cao cấp."
                },
                {
                    id: "carnival-7c",
                    name: "Cho Thuê Xe Kia Sedona / Kia Carnival 7 Chỗ VIP Thượng Hạng",
                    category: "Xe Ô Tô 7 Chỗ",
                    oldPrice: "1.600.000 ₫",
                    price: "1.300.000 ₫",
                    discount: "-19%",
                    image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=700&q=80",
                    desc: "Kia Carnival / Sedona cửa lùa điện thông minh, ghế thương gia êm ái, chuyên phục vụ đón khách VIP, đánh Golf tại Lăng Cô - Đà Nẵng."
                }
            ]
        },
        {
            id: "xe-ban-tai",
            title: "DỊCH VỤ CHO THUÊ XE BÁN TẢI",
            subtitle: "Động cơ khỏe, gầm cao, thùng chở đồ tiện lợi cho công trình và phượt trải nghiệm",
            items: [
                {
                    id: "ranger-bt",
                    name: "Cho Thuê Xe Bán Tải Ford Ranger 4 Chỗ Tự Lái [Hầm Hố, Mạnh Mẽ]",
                    category: "Xe Bán Tải",
                    oldPrice: "1.200.000 ₫",
                    price: "950.000 ₫",
                    discount: "-21%",
                    image: "https://images.unsplash.com/photo-1559416523-140ddc3d238c?auto=format&fit=crop&w=700&q=80",
                    desc: "Vua bán tải Ford Ranger số tự động, vượt địa hình đồi núi A Lưới, Khe Sanh, Tây Nguyên cực khỏe."
                },
                {
                    id: "bt50-bt",
                    name: "Cho Thuê Xe Bán Tải Mazda BT-50 4 Chỗ Chỉ 850K/Ngày",
                    category: "Xe Bán Tải",
                    oldPrice: "1.100.000 ₫",
                    price: "850.000 ₫",
                    discount: "-23%",
                    image: "https://images.unsplash.com/photo-1583121274602-3e2820c69888?auto=format&fit=crop&w=700&q=80",
                    desc: "Mazda BT-50 bền bỉ, tiết kiệm dầu, khoang cabin rộng rãi như sedan kèm thùng sau có nắp đậy an toàn."
                },
                {
                    id: "triton-bt",
                    name: "Cho Thuê Xe Bán Tải Mitsubishi Triton 4 Chỗ [Cá Tính, Siêu Chất]",
                    category: "Xe Bán Tải",
                    oldPrice: "1.100.000 ₫",
                    price: "900.000 ₫",
                    discount: "-18%",
                    image: "https://images.unsplash.com/photo-1502877338535-766e1452684a?auto=format&fit=crop&w=700&q=80",
                    desc: "Mitsubishi Triton thiết kế Dynamic Shield mạnh mẽ, vận hành linh hoạt cả trong phố lẫn đường đèo dốc."
                },
                {
                    id: "colorado-bt",
                    name: "Cho Thuê Xe Bán Tải Nissan Navara / Colorado [Bền Bỉ] Giá Rẻ",
                    category: "Xe Bán Tải",
                    oldPrice: "1.100.000 ₫",
                    price: "900.000 ₫",
                    discount: "-18%",
                    image: "https://images.unsplash.com/photo-1494976388531-d1058494cdd8?auto=format&fit=crop&w=700&q=80",
                    desc: "Hỗ trợ thuê theo ngày, theo tuần hoặc hợp đồng tháng cho kỹ sư, công ty xây dựng công trình tại Huế và Miền Trung."
                }
            ]
        },
        {
            id: "xe-hop-dong",
            title: "XE LIMOUSINE, TOUR, CƯỚI HỎI, HỢP ĐỒNG (16 - 45 CHỖ)",
            subtitle: "Hình ảnh thực tế Đội xe Tấn Tài Travel chuyên phục vụ khách đoàn, công ty, tour du lịch và VIP Limousine thượng đỉnh",
            items: [
                {
                    id: "limo-vip",
                    name: "Cho Thuê Xe Hyundai Solati DCar Limousine Thượng Đỉnh [75H-074.63]",
                    category: "Xe Limousine Thượng Đỉnh",
                    oldPrice: "2.200.000 ₫",
                    price: "1.800.000 ₫",
                    discount: "-18%",
                    image: "790505790_1673110141481646_6897180871178837738_n.jpg",
                    desc: "Xe thực tế Hyundai Solati DCar Limousine biển số 75H-074.63 của Đội Xe Tấn Tài Travel: ghế da cao cấp, trần sao LED, cổng sạc từng ghế, wifi tốc độ cao."
                },
                {
                    id: "transit-16c",
                    name: "Cho Thuê Xe VIP Limousine Tấn Tài Tourist 29 Chỗ [75H-036.37]",
                    category: "Xe Hợp Đồng & VIP Limousine",
                    oldPrice: "2.400.000 ₫",
                    price: "1.950.000 ₫",
                    discount: "-19%",
                    image: "833790623_1688308159961844_1732028964222177193_n.jpg",
                    desc: "Xe thực tế Thaco Town VIP Limousine Tấn Tài Tourist (75H-036.37) đời mới, bầu hơi êm ái, chuyên chạy tour Huế - Đà Nẵng - Hội An - Quảng Bình."
                },
                {
                    id: "county-29c",
                    name: "Cho Thuê Xe Hợp Đồng Hyundai Thaco Đời Mới Đèn LED [75H-050.85]",
                    category: "Xe Hợp Đồng 29 - 35 Chỗ",
                    oldPrice: "2.600.000 ₫",
                    price: "2.100.000 ₫",
                    discount: "-19%",
                    image: "753702681_1616384887154172_225715064923287945_n.jpg",
                    desc: "Xe thực tế Hyundai Thaco 75H-050.85 của Đội Xe Tấn Tài Travel với hệ thống đèn LED nội thất sang trọng, âm thanh karaoke, hầm hành lý lớn phục vụ đoàn."
                },
                {
                    id: "universe-45c",
                    name: "Thuê Dàn Xe Hợp Đồng VIP Limousine & Universe 45 Chỗ [75F-001.94]",
                    category: "Xe Hợp Đồng 45 Chỗ Đoàn Lớn",
                    oldPrice: "3.500.000 ₫",
                    price: "2.900.000 ₫",
                    discount: "-17%",
                    image: "794958057_1656982643094396_7116448109568842488_n.jpg",
                    desc: "Dàn xe Universe & VIP Limousine thực tế (75H-051.46, 75H-076.36, 75F-001.94) chuyên đồng hành cùng các đoàn lớn gần 500 khách của doanh nghiệp, trường học."
                }
            ]
        }
    ];

    // 2. DỮ LIỆU DANH MỤC BÀI VIẾT TRANG CHỦ (Sử dụng hình ảnh thực tế từ Fanpage Đội Xe Tấn Tài Travel)
    const BLOG_POSTS = [
        {
            id: "post-1",
            category: "hoat-dong",
            categoryName: "Hoạt Động Đội Xe Tấn Tài",
            date: "18/10",
            title: "Đội Xe Tấn Tài Travel Hân Hạnh Đồng Hành Cùng Gần 500 Nhân Viên Công Ty CP Dệt May Huế",
            image: "780771624_1644397651019562_6296295295226606946_n.jpg",
            excerpt: "Hình ảnh thực tế dàn xe 45 chỗ (75F-001.94) của Đội Xe Tấn Tài Travel xếp hàng đón gần 500 cán bộ công nhân viên Công ty CP Dệt May Huế...",
            content: "Đội Xe Tấn Tài Travel vô cùng vinh dự khi được tin tưởng lựa chọn làm đơn vị vận chuyển đồng hành cùng gần 500 cán bộ, công nhân viên Công ty Cổ phần Dệt May Huế trong kỳ nghỉ dưỡng và teambuilding vừa qua. Với dàn xe 29 - 45 chỗ đồng bộ, đời mới, điều hòa mát lạnh và đội ngũ tài xế giàu kinh nghiệm, chuyến đi đã diễn ra an toàn, đúng giờ và trọn vẹn niềm vui."
        },
        {
            id: "post-2",
            category: "hoat-dong",
            categoryName: "Hoạt Động Đội Xe Tấn Tài",
            date: "24/09",
            title: "Cận Cảnh Khoang Nội Thất Dòng Xe Limousine Thượng Đỉnh Nhà Tấn Tài Travel Tại Huế",
            image: "844826878_1697826339010026_1179047953979607540_n.jpg",
            excerpt: "Khám phá khoang nội thất ghế da thêu logo sang trọng và trần đèn LED hiện đại trên dòng xe Limousine của Đội Xe Tấn Tài Travel...",
            content: "Nhằm nâng tầm chất lượng dịch vụ vận tải du lịch tại Cố đô Huế, Đội Xe Tấn Tài Travel đưa vào khai thác dòng xe Limousine thượng đỉnh với ghế bọc da cao cấp, trần đèn LED nghệ thuật, hệ thống âm thanh sống động và wifi miễn phí suốt hành trình. Liên hệ ngay 0935.325.246 - 0842.565.246 để đặt lịch."
        },
        {
            id: "post-3",
            category: "kinh-nghiem",
            categoryName: "Kinh Nghiệm Thuê Xe",
            date: "10/09",
            title: "Đoàn Xe VIP Limousine Tấn Tài Travel Phục Vụ Khách Đoàn Tham Quan Lăng Cô - Huế - Đà Nẵng",
            image: "796238549_1656982476427746_1111825918020951417_n.jpg",
            excerpt: "Hình ảnh thực tế đoàn xe VIP Limousine (Xe số 1 & Xe số 2) đón đoàn khách công ty tham quan nghỉ dưỡng tại Lăng Cô - Huế...",
            content: "Khi thuê xe hợp đồng đoàn hoặc xe riêng có tài xế tại tantaitravel.com, Quý khách hoàn toàn yên tâm với dàn xe đời mới chính chủ, băng rôn chào mừng đoàn chuyên nghiệp, dừng chụp ảnh tại Đầm Lập An, biển Lăng Cô, Hải Vân Quan thoải mái mà không phát sinh phí chờ."
        },
        {
            id: "post-4",
            category: "cam-nang",
            categoryName: "Cẩm Nang Du Lịch Huế",
            date: "02/09",
            title: "Lịch Trình Tham Quan Đại Nội & Các Lăng Tẩm Cố Đô Huế Cùng Tấn Tài Tourist",
            image: "833852878_1688308149961845_8815609278150210198_n.jpg",
            excerpt: "Gợi ý lịch trình di chuyển hợp lý nhất tại Huế: Đại Nội - Chùa Thiên Mụ - Lăng Minh Mạng - Lăng Khải Định - Lăng Tự Đức cùng Đội Xe Tấn Tài...",
            content: "Với dịch vụ City Tour Huế bằng xe 4 - 7 - 16 - 29 - 45 chỗ của Đội Xe Tấn Tài Travel (27 Tôn Thất Bật, TP. Huế), tài xế bản địa am hiểu lịch sử và ẩm thực Cố đô sẽ đưa Quý khách đi qua cung đường thuận tiện nhất, tiết kiệm thời gian và chi phí."
        }
    ];

    // Biến lưu sản phẩm đang mở Quick View
    let currentQuickViewProduct = null;

    // 3. HÀM RENDER DANH SÁCH SẢN PHẨM CHUẨN FLATSOME (2 CỘT MOBILE, 4 CỘT DESKTOP)
    function renderAllProductSections(searchKeyword = "") {
        const wrapper = document.getElementById("products-wrapper");
        const keyword = searchKeyword.trim().toLowerCase();
        let html = "";

        PRODUCT_SECTIONS.forEach(section => {
            const filteredItems = section.items.filter(item =>
                item.name.toLowerCase().includes(keyword) ||
                item.category.toLowerCase().includes(keyword) ||
                item.desc.toLowerCase().includes(keyword)
            );

            if (filteredItems.length === 0) return;

            html += `
                <section id="${section.id}" class="fs-container">
                    <div class="section-title-container">
                        <h2 class="section-title-main text-base sm:text-2xl">
                            <span>${section.title}</span>
                        </h2>
                        <p class="text-center text-xs sm:text-sm text-gray-500 mt-1">${section.subtitle}</p>
                    </div>

                    <!-- Grid Sản Phẩm: Bắt buộc 2 cột trên Điện Thoại (grid-cols-2) và 4 cột trên Máy Tính (lg:grid-cols-4) -->
                    <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                        ${filteredItems.map(item => `
                            <div class="box-product">
                                <!-- Box Image + % Giảm Giá + Nút XEM NHANH chuẩn Flatsome -->
                                <div class="box-image">
                                    <span class="badge-sale-flatsome">${item.discount}</span>
                                    <img src="${item.image}" alt="${item.name}" loading="lazy" onerror="this.src='https://placehold.co/600x450/1a1510/eab308?text=Tan+Tai+Travel'">
                                    <button type="button" onclick="openQuickView('${item.id}')" class="quick-view-bar">
                                        <i class="fa-regular fa-eye mr-1"></i> Xem Nhanh
                                    </button>
                                </div>

                                <!-- Box Text chuẩn Flatsome -->
                                <div class="box-text p-2.5 sm:p-4 flex-1 flex flex-col justify-between text-center">
                                    <div>
                                        <p class="text-[10px] sm:text-xs uppercase text-gray-400 font-semibold tracking-wider">${item.category}</p>
                                        <h3 class="text-xs sm:text-sm font-bold text-gray-800 hover:text-amber-600 line-clamp-2 mt-1 min-h-[32px] sm:min-h-[40px] cursor-pointer" onclick="openQuickView('${item.id}')">
                                            ${item.name}
                                        </h3>
                                    </div>

                                    <!-- Giá gốc gạch ngang + Giá khuyến mãi chuẩn Flatsome -->
                                    <div class="mt-2.5 pt-2 border-t border-gray-100">
                                        <div class="price-wrapper flex flex-wrap items-center justify-center gap-x-2 gap-y-0.5">
                                            <del class="text-[11px] sm:text-xs text-gray-400">${item.oldPrice}</del>
                                            <ins class="text-xs sm:text-base font-black text-red-600 no-underline">${item.price}</ins>
                                        </div>
                                        <div class="mt-2.5 grid grid-cols-2 gap-1.5">
                                            <a href="tel:0935325246" class="py-1.5 px-2 bg-red-600 hover:bg-red-700 text-white font-bold text-[11px] sm:text-xs rounded transition flex items-center justify-center gap-1">
                                                <i class="fa-solid fa-phone"></i> Gọi Đặt
                                            </a>
                                            <button type="button" onclick="openQuickView('${item.id}')" class="py-1.5 px-2 bg-amber-50 hover:bg-amber-600 text-amber-800 hover:text-white border border-amber-300 font-bold text-[11px] sm:text-xs rounded transition">
                                                Chi Tiết
                                            </button>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        `).join("")}
                    </div>
                </section>
            `;
        });

        wrapper.innerHTML = html || `
            <div class="fs-container text-center py-10 text-gray-500">
                Không tìm thấy mẫu xe phù hợp với từ khóa. Quý khách vui lòng gọi <strong>0935.325.246</strong> để được tư vấn trực tiếp!
            </div>
        `;
    }

    function filterProductsBySearch(value) {
        renderAllProductSections(value);
    }

    // 4. HÀM MỞ / ĐÓNG MODAL XEM NHANH (FLATSOME QUICK VIEW)
    function openQuickView(productId) {
        let found = null;
        for (const sec of PRODUCT_SECTIONS) {
            const match = sec.items.find(i => i.id === productId);
            if (match) { found = match; break; }
        }
        if (!found) return;

        currentQuickViewProduct = found;
        document.getElementById("qv-discount").textContent = found.discount;
        document.getElementById("qv-image").src = found.image;
        document.getElementById("qv-category").textContent = found.category;
        document.getElementById("qv-title").textContent = found.name;
        document.getElementById("qv-old-price").textContent = found.oldPrice;
        document.getElementById("qv-price").textContent = found.price;
        document.getElementById("qv-desc").textContent = found.desc;

        const modal = document.getElementById("quick-view-modal");
        modal.classList.remove("hidden");
        modal.classList.add("flex");
    }

    function closeQuickView() {
        const modal = document.getElementById("quick-view-modal");
        modal.classList.add("hidden");
        modal.classList.remove("flex");
    }

    function selectCarToQuote() {
        closeQuickView();
        if (currentQuickViewProduct) {
            const noteInput = document.getElementById("q-note");
            noteInput.value = "Quan tâm đặt xe: " + currentQuickViewProduct.name + " (" + currentQuickViewProduct.price + ")";
        }
        document.getElementById("form-bao-gia").scrollIntoView({ behavior: "smooth" });
        document.getElementById("q-name").focus();
    }

    // 5. HÀM RENDER & LỌC DANH MỤC BÀI VIẾT TRANG CHỦ
    function filterBlogPosts(cat) {
        document.querySelectorAll(".blog-tab-btn").forEach(btn => {
            btn.className = "blog-tab-btn px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-white text-gray-700 border border-gray-200 hover:border-amber-600 transition";
        });
        const activeBtn = document.getElementById("blog-tab-" + cat);
        if (activeBtn) {
            activeBtn.className = "blog-tab-btn px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-amber-600 text-white transition";
        }

        const list = cat === "all" ? BLOG_POSTS : BLOG_POSTS.filter(p => p.category === cat);
        const grid = document.getElementById("blog-posts-grid");

        grid.innerHTML = list.map(post => `
            <article class="bg-white border border-gray-200 rounded-lg overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                <div>
                    <div class="relative aspect-[16/10] bg-gray-100 overflow-hidden cursor-pointer" onclick="openBlogPost('${post.id}')">
                        <img src="${post.image}" alt="${post.title}" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4">
                        <span class="text-[10px] sm:text-xs font-bold uppercase text-amber-700">${post.categoryName}</span>
                        <h3 onclick="openBlogPost('${post.id}')" class="text-xs sm:text-sm font-bold text-gray-900 hover:text-amber-600 line-clamp-2 mt-1 cursor-pointer">
                            ${post.title}
                        </h3>
                        <p class="text-[11px] sm:text-xs text-gray-500 line-clamp-2 mt-1.5">
                            ${post.excerpt}
                        </p>
                    </div>
                </div>
                <div class="px-3 sm:px-4 pb-3 pt-1">
                    <button type="button" onclick="openBlogPost('${post.id}')" class="text-[11px] sm:text-xs font-bold text-amber-700 hover:text-red-600 uppercase inline-flex items-center gap-1">
                        Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                    </button>
                </div>
            </article>
        `).join("");
    }

    function openBlogPost(postId) {
        const post = BLOG_POSTS.find(p => p.id === postId);
        if (!post) return;
        document.getElementById("info-modal-title").textContent = post.title;
        document.getElementById("info-modal-body").innerHTML = `
            <p class="text-xs font-bold text-amber-700 uppercase">${post.categoryName} | tantaitravel.com</p>
            <img src="${post.image}" alt="${post.title}" class="w-full h-48 object-cover rounded-lg my-2">
            <p>${post.content}</p>
            <p class="pt-2 font-semibold text-gray-900">Liên hệ đặt xe Đội Xe Tấn Tài Travel: 0935.325.246 - 0842.565.246 (27 Tôn Thất Bật, TP. Huế).</p>
        `;
        const modal = document.getElementById("info-modal");
        modal.classList.remove("hidden");
        modal.classList.add("flex");
    }

    function closeInfoModal() {
        const modal = document.getElementById("info-modal");
        modal.classList.add("hidden");
        modal.classList.remove("flex");
    }

    // 6. XỬ LÝ GỬI FORM YÊU CẦU & BÁO GIÁ TRANG CHỦ
    function submitQuoteForm(e) {
        e.preventDefault();
        const name = document.getElementById("q-name").value;
        const phone = document.getElementById("q-phone").value;
        const service = document.getElementById("q-service").value;
        const car = document.getElementById("q-car").value;
        const route = document.getElementById("q-route").value || "Tư vấn hành trình tại Huế";
        const date = document.getElementById("q-date").value || "Sớm nhất";

        document.getElementById("info-modal-title").textContent = "Đã Nhận Yêu Cầu Báo Giá Thuê Xe";
        document.getElementById("info-modal-body").innerHTML = `
            <p>Cảm ơn Quý khách <strong>${name}</strong> (SĐT: <strong>${phone}</strong>) đã gửi yêu cầu tới <strong>Đội Xe Tấn Tài Travel (tantaitravel.com)</strong>.</p>
            <div class="bg-amber-50 border border-amber-200 rounded p-3 text-xs space-y-1 my-2">
                <div><strong>Dịch vụ:</strong> ${service}</div>
                <div><strong>Loại xe:</strong> ${car}</div>
                <div><strong>Lịch trình:</strong> ${route}</div>
                <div><strong>Ngày đi:</strong> ${date}</div>
            </div>
            <p>Bộ phận điều hành xe tại <strong>27 Tôn Thất Bật, TP. Huế</strong> sẽ liên hệ báo giá ưu đãi ngay cho Quý khách qua số <strong>0935.325.246</strong> hoặc <strong>0842.565.246</strong>!</p>
        `;
        const modal = document.getElementById("info-modal");
        modal.classList.remove("hidden");
        modal.classList.add("flex");
        document.getElementById("quote-request-form").reset();
    }

    // 7. SLIDER 2 ẢNH BANNER TỰ TRƯỢT
    let currentSlideIndex = 0;
    const slides = document.querySelectorAll(".hero-slide");

    function showSlide(index) {
        currentSlideIndex = (index + slides.length) % slides.length;
        slides.forEach((slide, i) => {
            if (i === currentSlideIndex) {
                slide.classList.remove("opacity-0", "z-0");
                slide.classList.add("opacity-100", "z-10");
            } else {
                slide.classList.remove("opacity-100", "z-10");
                slide.classList.add("opacity-0", "z-0");
            }
        });

        const dot0 = document.getElementById("slider-dot-0");
        const dot1 = document.getElementById("slider-dot-1");
        if (currentSlideIndex === 0) {
            dot0.className = "w-8 h-2.5 rounded-full bg-amber-400 transition-all";
            dot1.className = "w-2.5 h-2.5 rounded-full bg-white/50 transition-all";
        } else {
            dot1.className = "w-8 h-2.5 rounded-full bg-amber-400 transition-all";
            dot0.className = "w-2.5 h-2.5 rounded-full bg-white/50 transition-all";
        }
    }

    function nextSlide() { showSlide(currentSlideIndex + 1); }
    function prevSlide() { showSlide(currentSlideIndex - 1); }
    function goToSlide(idx) { showSlide(idx); }

    // Tự động trượt giữa 2 banner mỗi 4.5 giây
    setInterval(nextSlide, 4500);

    // 8. ĐÓNG / MỞ MENU MOBILE
    function toggleMobileMenu() {
        const drawer = document.getElementById("mobile-menu-drawer");
        const overlay = document.getElementById("mobile-menu-overlay");
        const isClosed = drawer.classList.contains("-translate-x-full");
        if (isClosed) {
            drawer.classList.remove("-translate-x-full");
            overlay.classList.remove("hidden");
        } else {
            drawer.classList.add("-translate-x-full");
            overlay.classList.add("hidden");
        }
    }

    // Khởi tạo giao diện khi tải trang
    window.onload = function () {
        renderAllProductSections();
        filterBlogPosts("all");
    };
</script>

</body>
</html>
