# SENSEI-SS-DYNAMIC-x-SS-DYNAMIC-CARGO
SENSEI SS DYNAMIC x SS DYNAMIC CARGO
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SS DYNAMIC SENSEI BORONG CHINA & SS DYNAMIC CARGO | Official Ecosystem</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@700;900&family=Montserrat:wght@400;600;700;800;900&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brandRed: '#DC2626',
                        brandCrimson: '#991B1B',
                        brandDark: '#070709',
                        brandCard: '#111116',
                        brandGold: '#F59E0B',
                    },
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif'],
                        display: ['Cinzel', 'serif'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Custom Ecosystem Styling */
        body {
            background-color: #070709;
            color: #F3F4F6;
            overflow-x: hidden;
        }

        /* China & Malaysia Flag Fusion Background Layer */
        .flag-ecosystem-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            z-index: -2;
            background: 
                radial-gradient(circle at 15% 20%, rgba(220, 38, 38, 0.22) 0%, transparent 45%),
                radial-gradient(circle at 85% 80%, rgba(220, 38, 38, 0.18) 0%, transparent 50%),
                linear-gradient(135deg, #070709 0%, #140505 50%, #070709 100%);
        }

        .flag-watermark-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            opacity: 0.08;
            pointer-events: none;
            display: flex;
            justify-content: space-between;
            align-items: center;
            overflow: hidden;
        }

        .flag-left, .flag-right {
            width: 50%;
            height: 100%;
            background-size: cover;
            background-position: center;
            filter: contrast(130%) saturate(120%);
        }

        /* High-Contrast SVG Data URIs for China & Malaysia Flags */
        .flag-left {
            background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 900 600'%3E%3Crect width='900' height='600' fill='%23de2910'/%3E%3Cpolygon points='150,60 172,128 244,128 186,170 208,238 150,196 92,238 114,170 56,128 128,128' fill='%23ffde00'/%3E%3Cpolygon points='300,45 307,67 330,67 311,81 318,103 300,89 282,103 289,81 270,67 293,67' fill='%23ffde00'/%3E%3Cpolygon points='360,105 367,127 390,127 371,141 378,163 360,149 342,163 349,141 330,127 353,127' fill='%23ffde00'/%3E%3Cpolygon points='360,195 367,217 390,217 371,231 378,253 360,239 342,253 349,231 330,217 353,217' fill='%23ffde00'/%3E%3Cpolygon points='300,255 307,277 330,277 311,291 318,313 300,299 282,313 289,291 270,277 293,277' fill='%23ffde00'/%3E%3C/svg%3E");
            mask-image: linear-gradient(to right, rgba(0,0,0,1), rgba(0,0,0,0));
            -webkit-mask-image: linear-gradient(to right, rgba(0,0,0,1), rgba(0,0,0,0));
        }

        .flag-right {
            background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 1400 700'%3E%3Crect width='1400' height='700' fill='%23fff'/%3E%3Cpath d='M0,0h1400v50H0zm0,100h1400v50H0zm0,100h1400v50H0zm0,100h1400v50H0zm0,100h1400v50H0zm0,100h1400v50H0zm0,100h1400v50H0z' fill='%23cc0001'/%3E%3Crect width='700' height='400' fill='%23010066'/%3E%3Ccircle cx='310' cy='200' r='110' fill='%23ffcc00'/%3E%3Ccircle cx='340' cy='200' r='95' fill='%23010066'/%3E%3Cpolygon points='450,110 468,165 525,150 485,192 530,230 472,225 475,282 440,235 405,282 408,225 350,230 395,192 355,150 412,165' fill='%23ffcc00'/%3E%3C/svg%3E");
            mask-image: linear-gradient(to left, rgba(0,0,0,1), rgba(0,0,0,0));
            -webkit-mask-image: linear-gradient(to left, rgba(0,0,0,1), rgba(0,0,0,0));
        }

        /* Ecosystem Grid Lines */
        .ecosystem-grid {
            background-size: 50px 50px;
            background-image: 
                linear-gradient(to right, rgba(220, 38, 38, 0.06) 1px, transparent 1px),
                linear-gradient(to bottom, rgba(220, 38, 38, 0.06) 1px, transparent 1px);
        }

        /* Glassmorphism & Red Glow Cards */
        .pro-card {
            background: rgba(17, 17, 22, 0.85);
            backdrop-filter: blur(14px);
            border: 1px solid rgba(220, 38, 38, 0.25);
            box-shadow: 0 10px 30px -10px rgba(0, 0, 0, 0.8);
            transition: all 0.35s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .pro-card:hover {
            border-color: #DC2626;
            box-shadow: 0 0 25px rgba(220, 38, 38, 0.35);
            transform: translateY(-4px);
        }

        .red-glow-btn {
            background: linear-gradient(135deg, #DC2626 0%, #991B1B 100%);
            box-shadow: 0 0 20px rgba(220, 38, 38, 0.45);
            transition: all 0.3s ease;
        }

        .red-glow-btn:hover {
            box-shadow: 0 0 32px rgba(220, 38, 38, 0.75);
            transform: scale(1.02);
        }

        /* Ticker Animation */
        @keyframes marquee {
            0% { transform: translateX(0%); }
            100% { transform: translateX(-50%); }
        }
        .animate-marquee {
            display: flex;
            width: max-content;
            animation: marquee 30s linear infinite;
        }
        .animate-marquee:hover {
            animation-play-state: paused;
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #070709; }
        ::-webkit-scrollbar-thumb { background: #991B1B; border-radius: 4px; }
        ::-webkit-scrollbar-thumb:hover { background: #DC2626; }
    </style>
</head>
<body class="font-sans antialiased selection:bg-brandRed selection:text-white">

    <!-- Background Layers -->
    <div class="flag-ecosystem-bg"></div>
    <div class="flag-watermark-overlay">
        <div class="flag-left"></div>
        <div class="flag-right"></div>
    </div>
    <div class="fixed inset-0 ecosystem-grid pointer-events-none z-[-1]"></div>

    <!-- Live Ecosystem Status Bar -->
    <div class="bg-black/95 border-b border-red-900/50 text-xs py-2 overflow-hidden relative z-50">
        <div class="animate-marquee flex items-center space-x-10 text-gray-300 font-medium">
            <span class="flex items-center gap-2"><span class="w-2 h-2 rounded-full bg-green-500 animate-ping"></span> 🇨🇳 GUANGZHOU & YIWU WAREHOUSE: <strong class="text-white">OPERATIONAL (24/7)</strong></span>
            <span class="flex items-center gap-2">🇲🇾 ALOR GAJAH MELAKA HUB: <strong class="text-brandRed">ACTIVE DISPATCH</strong></span>
            <span>💱 LIVE EXCHANGE RATE: <strong class="text-brandGold">1 RMB = RM 0.645</strong></span>
            <span>🚢 SEA FREIGHT (LCL/FCL): <strong class="text-white">12 - 18 DAYS DOOR-TO-DOOR</strong></span>
            <span>✈️ AIR CARGO EXPRESS: <strong class="text-white">3 - 5 WORKING DAYS</strong></span>
            <span class="text-brandRed font-bold">#SSDYNAMICSENSEIBORONGCHINA #SENSEISSDYNAMIC #SSDYNAMICCARGO</span>
            <!-- Duplicate for seamless loop -->
            <span class="flex items-center gap-2"><span class="w-2 h-2 rounded-full bg-green-500 animate-ping"></span> 🇨🇳 GUANGZHOU & YIWU WAREHOUSE: <strong class="text-white">OPERATIONAL (24/7)</strong></span>
            <span class="flex items-center gap-2">🇲🇾 ALOR GAJAH MELAKA HUB: <strong class="text-brandRed">ACTIVE DISPATCH</strong></span>
            <span>💱 LIVE EXCHANGE RATE: <strong class="text-brandGold">1 RMB = RM 0.645</strong></span>
            <span>🚢 SEA FREIGHT (LCL/FCL): <strong class="text-white">12 - 18 DAYS DOOR-TO-DOOR</strong></span>
            <span>✈️ AIR CARGO EXPRESS: <strong class="text-white">3 - 5 WORKING DAYS</strong></span>
        </div>
    </div>

    <!-- Navigation Header -->
    <header class="sticky top-0 z-40 bg-black/85 backdrop-blur-xl border-b border-red-900/40">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <!-- Brand Identity -->
                <a href="#" class="flex items-center gap-3 group">
                    <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-brandRed to-black border border-red-500/50 flex items-center justify-center shadow-lg shadow-red-900/30 group-hover:scale-105 transition">
                        <span class="font-display font-black text-xl text-white tracking-wider">SS</span>
                    </div>
                    <div>
                        <div class="font-heading font-black text-sm sm:text-base tracking-wider text-white leading-tight">
                            SS DYNAMIC <span class="text-brandRed">SENSEI</span>
                        </div>
                        <div class="text-[10px] sm:text-xs font-semibold tracking-widest text-gray-400 uppercase">
                            Borong China 🇨🇳 & Cargo 🇲🇾
                        </div>
                    </div>
                </a>

                <!-- Desktop Navigation -->
                <nav class="hidden lg:flex items-center space-x-7 text-sm font-semibold">
                    <a href="#ecosystem" class="text-gray-300 hover:text-brandRed transition">Ecosystem</a>
                    <a href="#services" class="text-gray-300 hover:text-brandRed transition">Kepakaran</a>
                    <a href="#calculator" class="text-gray-300 hover:text-brandRed transition">Kalkulator Cargo & RMB</a>
                    <a href="#tracking" class="text-gray-300 hover:text-brandRed transition">Live Tracking</a>
                    <a href="#location" class="text-gray-300 hover:text-brandRed transition">HQ Melaka</a>
                </nav>

                <!-- CTA Button -->
                <div class="flex items-center gap-3">
                    <a href="https://wa.me/601151453147?text=Salam%20Sensei%20SS%20Dynamic,%20saya%20berminat%20dengan%20servis%20Borong%20China%20%26%20Cargo." target="_blank" class="red-glow-btn px-4 sm:px-6 py-2.5 rounded-lg font-heading font-bold text-xs sm:text-sm text-white flex items-center gap-2">
                        <i class="fa-brands fa-whatsapp text-lg"></i>
                        <span>HUBUNGI SENSEI</span>
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative pt-14 pb-20 lg:pt-24 lg:pb-28 overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid lg:grid-cols-12 gap-12 items-center">
                
                <!-- Left Hero Content -->
                <div class="lg:col-span-7 space-y-6">
                    <div class="inline-flex items-center gap-2.5 px-4 py-1.5 rounded-full bg-red-950/80 border border-brandRed/50 text-xs font-bold tracking-wider uppercase text-red-200">
                        <span>🇨🇳 DIRECT KILANG CHINA</span>
                        <span class="text-brandRed">•</span>
                        <span>🇲🇾 HQ ALOR GAJAH, MELAKA</span>
                    </div>

                    <h1 class="font-heading font-black text-4xl sm:text-5xl lg:text-6xl tracking-tight text-white leading-[1.1]">
                        SS DYNAMIC <span class="text-transparent bg-clip-text bg-gradient-to-r from-brandRed via-red-500 to-brandGold">SENSEI BORONG CHINA</span> & CARGO
                    </h1>

                    <p class="text-base sm:text-lg text-gray-300 leading-relaxed max-w-2xl">
                        Ekosistem Perdagangan Rentas Sempadan China–Malaysia Paling Berkuasa. Dari pencarian kilang VIP (1688, Taobao, Canton Fair), rundingan harga OEM, pembayaran Alipay/RMB hingga penghantaran <strong class="text-white">Sea & Air Cargo terus ke pintu anda</strong>.
                    </p>

                    <!-- Hashtags Pill Row -->
                    <div class="flex flex-wrap gap-2 text-xs font-bold text-brandRed">
                        <span class="bg-black/80 border border-red-900/60 px-3 py-1 rounded-md">#SSDYNAMICSENSEIBORONGCHINA</span>
                        <span class="bg-black/80 border border-red-900/60 px-3 py-1 rounded-md">#SENSEISSDYNAMIC</span>
                        <span class="bg-black/80 border border-red-900/60 px-3 py-1 rounded-md">#SSDYNAMICCARGO</span>
                    </div>

                    <!-- Action Buttons -->
                    <div class="flex flex-col sm:flex-row gap-4 pt-2">
                        <a href="https://wa.me/601151453147?text=Hi%20SS%20Dynamic%20Sensei,%20saya%20nak%20mula%20borong%20barang%20dari%20China!" target="_blank" class="red-glow-btn px-8 py-4 rounded-xl font-heading font-extrabold text-sm tracking-wider uppercase text-white text-center flex items-center justify-center gap-3">
                            <i class="fa-solid fa-crown text-brandGold"></i>
                            <span>KONSULTASI VIP BERSAMA SENSEI</span>
                        </a>
                        <a href="#calculator" class="px-8 py-4 rounded-xl bg-white/5 hover:bg-white/10 border border-white/15 font-heading font-bold text-sm tracking-wider uppercase text-white text-center transition flex items-center justify-center gap-2">
                            <i class="fa-solid fa-calculator text-brandRed"></i>
                            <span>KIRA KOS CARGO & RMB</span>
                        </a>
                    </div>

                    <!-- Trust Metrics -->
                    <div class="grid grid-cols-3 gap-4 pt-6 border-t border-red-900/30">
                        <div>
                            <div class="font-heading font-black text-2xl sm:text-3xl text-white">10,000+</div>
                            <div class="text-xs text-gray-400 font-medium">Kilang Disahkan China</div>
                        </div>
                        <div>
                            <div class="font-heading font-black text-2xl sm:text-3xl text-brandRed">99.8%</div>
                            <div class="text-xs text-gray-400 font-medium">Kadar Ketibaan Selamat</div>
                        </div>
                        <div>
                            <div class="font-heading font-black text-2xl sm:text-3xl text-white">24/7</div>
                            <div class="text-xs text-gray-400 font-medium">Gudang Guangzhou & Yiwu</div>
                        </div>
                    </div>
                </div>

                <!-- Right Hero Command Panel -->
                <div class="lg:col-span-5">
                    <div class="pro-card rounded-2xl p-6 sm:p-8 relative overflow-hidden">
                        <div class="absolute top-0 right-0 w-32 h-32 bg-brandRed/20 blur-3xl rounded-full"></div>
                        
                        <div class="flex items-center justify-between border-b border-red-900/40 pb-4 mb-6">
                            <div>
                                <span class="text-xs font-bold text-brandRed uppercase tracking-widest">OFFICIAL COMMAND HUB</span>
                                <h2 class="font-heading font-extrabold text-xl text-white">PUSAT OPERASI & LOGISTIK</h2>
                            </div>
                            <div class="text-2xl">🇨🇳🤝🇲🇾</div>
                        </div>

                        <div class="space-y-4 text-sm">
                            <div class="p-4 rounded-xl bg-black/60 border border-red-900/30 flex items-start gap-3.5">
                                <i class="fa-solid fa-location-dot text-brandRed text-lg mt-1"></i>
                                <div>
                                    <div class="font-bold text-white uppercase text-xs tracking-wider mb-1">Alamat Ibu Pejabat (HQ)</div>
                                    <p class="text-gray-300 leading-relaxed font-medium">
                                        NO 2, BANGUNAN TERMINAL BAS, KOMPLEKS AG SENTRAL, 78000, ALOR GAJAH, MELAKA
                                    </p>
                                </div>
                            </div>

                            <div class="p-4 rounded-xl bg-black/60 border border-red-900/30 flex items-center justify-between">
                                <div class="flex items-center gap-3.5">
                                    <i class="fa-solid fa-phone-volume text-brandRed text-lg"></i>
                                    <div>
                                        <div class="font-bold text-white uppercase text-xs tracking-wider">Hotline Rasmi Sensei</div>
                                        <a href="tel:+601151453147" class="text-lg font-heading font-black text-brandGold hover:underline">+6011-5145 3147</a>
                                    </div>
                                </div>
                                <a href="https://wa.me/601151453147" target="_blank" class="px-3 py-2 bg-green-600 hover:bg-green-500 text-white rounded-lg text-xs font-bold transition">
                                    Chat Now
                                </a>
                            </div>

                            <!-- Quick Track Mini Widget -->
                            <div class="p-4 rounded-xl bg-gradient-to-r from-red-950/60 to-black border border-brandRed/40">
                                <label class="block text-xs font-bold uppercase tracking-wider text-gray-300 mb-2">
                                    <i class="fa-solid fa-satellite-dish text-brandRed mr-1"></i> Semak Status Tracking Cargo
                                </label>
                                <div class="flex gap-2">
                                    <input type="text" id="heroTrackInput" placeholder="Masukkan No. Tracking (cth: SSD-8892)" class="w-full bg-black/80 border border-red-900/60 rounded-lg px-3 py-2 text-xs text-white focus:outline-none focus:border-brandRed">
                                    <button onclick="quickTrackHero()" class="red-glow-btn px-4 py-2 rounded-lg text-xs font-bold text-white whitespace-nowrap">
                                        SEMAK
                                    </button>
                                </div>
                                <div id="heroTrackResult" class="mt-2 text-xs hidden"></div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Core Ecosystem Pillars -->
    <section id="ecosystem" class="py-16 border-t border-red-900/30 bg-black/40">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-14">
                <span class="text-brandRed font-bold text-xs tracking-widest uppercase">FULL END-TO-END ECOSYSTEM</span>
                <h2 class="font-heading font-black text-3xl sm:text-4xl text-white mt-2">
                    4 TUNJANG KUASA <span class="text-brandRed">SS DYNAMIC</span>
                </h2>
                <p class="text-gray-400 text-sm sm:text-base mt-3">
                    Sistem bersepadu yang menghubungkan pembekal utama di Tanah Besar China terus ke usahawan & pemborong di seluruh Malaysia.
                </p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Pillar 1 -->
                <div class="pro-card rounded-2xl p-6">
                    <div class="w-12 h-12 rounded-xl bg-red-950 border border-brandRed/50 flex items-center justify-center text-brandRed text-xl mb-5">
                        <i class="fa-solid fa-industry"></i>
                    </div>
                    <h3 class="font-heading font-bold text-lg text-white mb-2">1. Direct Factory Sourcing</h3>
                    <p class="text-sm text-gray-400 leading-relaxed">
                        Akses terus ke kilang Tier-1 di Guangzhou, Yiwu, Shenzhen & Foshan tanpa orang tengah. Harga modal paling rendah untuk margin keuntungan maksimum.
                    </p>
                </div>

                <!-- Pillar 2 -->
                <div class="pro-card rounded-2xl p-6">
                    <div class="w-12 h-12 rounded-xl bg-red-950 border border-brandRed/50 flex items-center justify-center text-brandRed text-xl mb-5">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <h3 class="font-heading font-bold text-lg text-white mb-2">2. Quality Control (QC) & Repack</h3>
                    <p class="text-sm text-gray-400 leading-relaxed">
                        Pasukan gudang kami di China memeriksa kuantiti, spesifikasi, dan pembungkusan semula (wooden crate / waterproof wrap) sebelum belayar.
                    </p>
                </div>

                <!-- Pillar 3 -->
                <div class="pro-card rounded-2xl p-6">
                    <div class="w-12 h-12 rounded-xl bg-red-950 border border-brandRed/50 flex items-center justify-center text-brandRed text-xl mb-5">
                        <i class="fa-solid fa-ship"></i>
                    </div>
                    <h3 class="font-heading font-bold text-lg text-white mb-2">3. SS Dynamic Cargo</h3>
                    <p class="text-sm text-gray-400 leading-relaxed">
                        Penghantaran Laut (Sea Freight LCL/FCL) & Udara (Air Freight Express) termasuk urusan pelepasan kastam (Custom Clearance) sehingga ke alamat anda.
                    </p>
                </div>

                <!-- Pillar 4 -->
                <div class="pro-card rounded-2xl p-6">
                    <div class="w-12 h-12 rounded-xl bg-red-950 border border-brandRed/50 flex items-center justify-center text-brandRed text-xl mb-5">
                        <i class="fa-solid fa-graduation-cap"></i>
                    </div>
                    <h3 class="font-heading font-bold text-lg text-white mb-2">4. Akademi & Trip Borong Sensei</h3>
                    <p class="text-sm text-gray-400 leading-relaxed">
                        Bimbingan intensif borong online (1688/Taobao/WeChat) serta Trip Bisnes Eksklusif ke Canton Fair & Pasar Borong China bersama Sensei.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Comprehensive Services Matrix -->
    <section id="services" class="py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-12 gap-4">
                <div>
                    <span class="text-brandRed font-bold text-xs tracking-widest uppercase">EXPERT SOLUTIONS</span>
                    <h2 class="font-heading font-black text-3xl sm:text-4xl text-white mt-1">
                        PERKHIDMATAN <span class="text-brandRed">PREMIUM</span> KAMI
                    </h2>
                </div>
                <a href="https://wa.me/601151453147" target="_blank" class="text-sm font-bold text-brandGold hover:text-white transition flex items-center gap-2">
                    <span>Tempah Slot Konsultasi</span>
                    <i class="fa-solid fa-arrow-right"></i>
                </a>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Service Card 1 -->
                <div class="pro-card rounded-2xl p-7 flex flex-col justify-between">
                    <div>
                        <div class="flex justify-between items-center mb-4">
                            <span class="px-3 py-1 rounded bg-brandRed/20 text-brandRed text-xs font-bold">LOGISTICS</span>
                            <i class="fa-solid fa-plane-departure text-gray-500 text-xl"></i>
                        </div>
                        <h3 class="font-heading font-extrabold text-xl text-white mb-3">Sea & Air Cargo China – Malaysia</h3>
                        <ul class="space-y-2.5 text-sm text-gray-300 mb-6">
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brandRed"></i> Sea Freight (Semenanjung & Sabah/Sarawak)</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brandRed"></i> Air Express (3–5 Hari Bekerja)</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brandRed"></i> Sensitive Goods & Commercial Cargo</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brandRed"></i> Tiada Caj Tersembunyi (All-In Doorstep)</li>
                        </ul>
                    </div>
                    <a href="https://wa.me/601151453147?text=Saya%20nak%20tanya%20rate%20SS%20Dynamic%20Cargo" target="_blank" class="w-full py-3 rounded-xl bg-white/5 hover:bg-brandRed text-white font-bold text-xs uppercase tracking-wider text-center transition">
                        Dapatkan Rate Cargo
                    </a>
                </div>

                <!-- Service Card 2 -->
                <div class="pro-card rounded-2xl p-7 flex flex-col justify-between border-brandRed/60 relative">
                    <div class="absolute -top-3 right-6 bg-brandRed text-white text-[10px] font-black px-3 py-1 rounded-full uppercase tracking-wider">
                        PALING POPULAR
                    </div>
                    <div>
                        <div class="flex justify-between items-center mb-4">
                            <span class="px-3 py-1 rounded bg-brandGold/20 text-brandGold text-xs font-bold">SOURCING & OEM</span>
                            <i class="fa-solid fa-handshake text-brandGold text-xl"></i>
                        </div>
                        <h3 class="font-heading font-extrabold text-xl text-white mb-3">Servis Belian & OEM Jenama Sendiri</h3>
                        <ul class="space-y-2.5 text-sm text-gray-300 mb-6">
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brandGold"></i> Carian Produk Viral & Kilang OEM</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brandGold"></i> Custom Logo, Kotak & Pembungkusan</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brandGold"></i> Rundingan MOQ Rendah dengan Kilang</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brandGold"></i> Jaminan Pembayaran Selamat ke Pembekal</li>
                        </ul>
                    </div>
                    <a href="https://wa.me/601151453147?text=Saya%20berminat%20dengan%20servis%20Sourcing%20%26%20OEM%20China" target="_blank" class="w-full py-3 rounded-xl red-glow-btn text-white font-bold text-xs uppercase tracking-wider text-center">
                        Mula Projek OEM Anda
                    </a>
                </div>

                <!-- Service Card 3 -->
                <div class="pro-card rounded-2xl p-7 flex flex-col justify-between">
                    <div>
                        <div class="flex justify-between items-center mb-4">
                            <span class="px-3 py-1 rounded bg-brandRed/20 text-brandRed text-xs font-bold">FINTECH & TRAINING</span>
                            <i class="fa-solid fa-yen-sign text-gray-500 text-xl"></i>
                        </div>
                        <h3 class="font-heading font-extrabold text-xl text-white mb-3">Topup Alipay/RMB & Coaching</h3>
                        <ul class="space-y-2.5 text-sm text-gray-300 mb-6">
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brandRed"></i> Tukaran MYR ke RMB / Alipay / WeChat Pay</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brandRed"></i> Kelas Personal & Berkumpulan Borong China</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brandRed"></i> Pakej Trip Borong Guangzhou / Yiwu</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brandRed"></i> Khidmat Jurubahasa & Pemandu di China</li>
                        </ul>
                    </div>
                    <a href="https://wa.me/601151453147?text=Saya%20nak%20tanya%20tentang%20Topup%20RMB%20%2F%20Kelas%20Sensei" target="_blank" class="w-full py-3 rounded-xl bg-white/5 hover:bg-brandRed text-white font-bold text-xs uppercase tracking-wider text-center transition">
                        Sertai Ekosistem Sensei
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Interactive Tools Section: Cargo & RMB Calculator + Tracking -->
    <section id="calculator" class="py-20 bg-black/60 border-y border-red-900/40">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-10">
                
                <!-- Smart Freight & CBM Calculator -->
                <div class="pro-card rounded-2xl p-6 sm:p-8">
                    <div class="flex items-center gap-3 mb-6">
                        <div class="w-10 h-10 rounded-lg bg-brandRed flex items-center justify-center text-white">
                            <i class="fa-solid fa-calculator"></i>
                        </div>
                        <div>
                            <h3 class="font-heading font-extrabold text-xl text-white">KALKULATOR ESTIMASI CARGO (CBM & KG)</h3>
                            <p class="text-xs text-gray-400">Anggaran kos penghantaran dari Gudang China ke Malaysia</p>
                        </div>
                    </div>

                    <div class="space-y-4">
                        <div class="grid grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-bold text-gray-300 uppercase mb-1.5">Jenis Penghantaran</label>
                                <select id="freightType" class="w-full bg-black border border-red-900/60 rounded-lg px-3 py-2.5 text-sm text-white focus:outline-none focus:border-brandRed">
                                    <option value="sea">Sea Freight (Laut - CBM)</option>
                                    <option value="air">Air Freight (Udara - KG)</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-300 uppercase mb-1.5">Destinasi Malaysia</label>
                                <select id="destination" class="w-full bg-black border border-red-900/60 rounded-lg px-3 py-2.5 text-sm text-white focus:outline-none focus:border-brandRed">
                                    <option value="west">Semenanjung Malaysia</option>
                                    <option value="east">Sabah & Sarawak</option>
                                </select>
                            </div>
                        </div>

                        <div id="seaInputs" class="grid grid-cols-3 gap-3">
                            <div>
                                <label class="block text-xs text-gray-400 mb-1">Panjang (cm)</label>
                                <input type="number" id="dimL" value="50" class="w-full bg-black border border-red-900/60 rounded-lg px-3 py-2 text-sm text-white">
                            </div>
                            <div>
                                <label class="block text-xs text-gray-400 mb-1">Lebar (cm)</label>
                                <input type="number" id="dimW" value="40" class="w-full bg-black border border-red-900/60 rounded-lg px-3 py-2 text-sm text-white">
                            </div>
                            <div>
                                <label class="block text-xs text-gray-400 mb-1">Tinggi (cm)</label>
                                <input type="number" id="dimH" value="50" class="w-full bg-black border border-red-900/60 rounded-lg px-3 py-2 text-sm text-white">
                            </div>
                        </div>

                        <div id="airInputs" class="hidden">
                            <label class="block text-xs text-gray-400 mb-1">Berat Kasar (KG)</label>
                            <input type="number" id="weightKg" value="5" class="w-full bg-black border border-red-900/60 rounded-lg px-3 py-2 text-sm text-white">
                        </div>

                        <button onclick="calculateCargo()" class="w-full red-glow-btn py-3 rounded-xl font-heading font-bold text-sm text-white uppercase tracking-wider">
                            KIRA ANGGARAN KOS SEKARANG
                        </button>

                        <div id="calcOutput" class="p-4 rounded-xl bg-black/90 border border-brandRed/40 flex items-center justify-between">
                            <div>
                                <div class="text-xs text-gray-400">Anggaran Isipadu / Berat:</div>
                                <div id="calcMetric" class="font-bold text-white text-sm">0.100 CBM</div>
                            </div>
                            <div class="text-right">
                                <div class="text-xs text-gray-400">Anggaran Kos Cargo:</div>
                                <div id="calcPrice" class="font-heading font-black text-2xl text-brandGold">RM 48.00</div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Live RMB Converter & Shipment Tracking Portal -->
                <div id="tracking" class="space-y-6">
                    <!-- RMB Converter -->
                    <div class="pro-card rounded-2xl p-6 sm:p-7">
                        <div class="flex items-center justify-between mb-4">
                            <h3 class="font-heading font-extrabold text-lg text-white flex items-center gap-2">
                                <i class="fa-solid fa-money-bill-transfer text-brandRed"></i> PENUKAR MATA WANG (RMB ⇄ MYR)
                            </h3>
                            <span class="text-xs bg-red-950 text-brandGold px-2.5 py-1 rounded font-bold">Rate: 0.645</span>
                        </div>
                        <div class="grid grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs text-gray-400 mb-1">🇨🇳 Chinese Yuan (RMB)</label>
                                <input type="number" id="rmbInput" value="1000" oninput="convertRMB('rmb')" class="w-full bg-black border border-red-900/60 rounded-lg px-3 py-2.5 text-white font-bold">
                            </div>
                            <div>
                                <label class="block text-xs text-gray-400 mb-1">🇲🇾 Ringgit Malaysia (MYR)</label>
                                <input type="number" id="myrInput" value="645.00" oninput="convertRMB('myr')" class="w-full bg-black border border-red-900/60 rounded-lg px-3 py-2.5 text-brandGold font-bold">
                            </div>
                        </div>
                    </div>

                    <!-- Detailed Shipment Tracker -->
                    <div class="pro-card rounded-2xl p-6 sm:p-7">
                        <h3 class="font-heading font-extrabold text-lg text-white mb-2 flex items-center gap-2">
                            <i class="fa-solid fa-truck-fast text-brandRed"></i> SS DYNAMIC CARGO TRACKER
                        </h3>
                        <p class="text-xs text-gray-400 mb-4">Masukkan nombor waybill / tracking untuk status masa nyata (Cuba: <span class="text-white font-mono">SSD-8892</span>)</p>
                        
                        <div class="flex gap-2 mb-4">
                            <input type="text" id="mainTrackInput" placeholder="Contoh: SSD-8892" class="w-full bg-black border border-red-900/60 rounded-lg px-4 py-2.5 text-sm text-white focus:outline-none focus:border-brandRed">
                            <button onclick="runMainTracker()" class="red-glow-btn px-6 py-2.5 rounded-lg font-heading font-bold text-xs text-white uppercase">
                                JEJAK
                            </button>
                        </div>

                        <div id="mainTrackBox" class="hidden p-4 rounded-xl bg-black/80 border border-red-900/50 space-y-3 text-xs">
                            <div class="flex justify-between items-center border-b border-gray-800 pb-2">
                                <span class="font-bold text-white" id="trackCodeDisplay">WAYBILL: SSD-8892</span>
                                <span class="px-2 py-0.5 rounded bg-green-900/60 text-green-400 font-bold">IN TRANSIT - CUSTOM CLEARED</span>
                            </div>
                            <div class="space-y-2 text-gray-300">
                                <div class="flex items-center gap-2.5">
                                    <span class="w-2.5 h-2.5 rounded-full bg-brandRed"></span>
                                    <span><strong>🇲🇾 Alor Gajah Hub, Melaka:</strong> Dijadualkan untuk penghantaran kurier tempatan.</span>
                                </div>
                                <div class="flex items-center gap-2.5">
                                    <span class="w-2.5 h-2.5 rounded-full bg-gray-600"></span>
                                    <span><strong>🇲🇾 Port Klang Customs:</strong> Pelepasan kastam selesai tanpa sekatan.</span>
                                </div>
                                <div class="flex items-center gap-2.5">
                                    <span class="w-2.5 h-2.5 rounded-full bg-gray-600"></span>
                                    <span><strong>🇨🇳 Guangzhou Warehouse:</strong> Kontena berlepas menuju Malaysia.</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- HQ Location & Contact Section -->
    <section id="location" class="py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="pro-card rounded-3xl p-8 sm:p-12 border-brandRed/50">
                <div class="grid lg:grid-cols-12 gap-10 items-center">
                    <div class="lg:col-span-7 space-y-6">
                        <div class="inline-block px-3 py-1 rounded bg-brandRed/20 text-brandRed text-xs font-extrabold uppercase tracking-widest">
                            HUB UTAMA MALAYSIA
                        </div>
                        <h2 class="font-heading font-black text-3xl sm:text-4xl text-white">
                            KUNJUNGI PEJABAT URUSAN <span class="text-brandRed">SS DYNAMIC SENSEI</span>
                        </h2>
                        <p class="text-gray-300 text-sm sm:text-base leading-relaxed">
                            Ingin berbincang secara bersemuka mengenai strategi borong China, penghantaran kontena, atau kerjasama bisnes? Temui pasukan pakar kami di Alor Gajah, Melaka.
                        </p>

                        <div class="space-y-4 pt-2">
                            <div class="flex items-start gap-4">
                                <div class="w-10 h-10 rounded-lg bg-red-950 border border-brandRed/40 flex items-center justify-center text-brandRed shrink-0">
                                    <i class="fa-solid fa-map-location-dot"></i>
                                </div>
                                <div>
                                    <div class="text-xs font-bold text-gray-400 uppercase">Alamat Rasmi</div>
                                    <div class="font-bold text-white text-sm sm:text-base">
                                        NO 2, BANGUNAN TERMINAL BAS, KOMPLEKS AG SENTRAL, 78000, ALOR GAJAH, MELAKA
                                    </div>
                                </div>
                            </div>

                            <div class="flex items-start gap-4">
                                <div class="w-10 h-10 rounded-lg bg-red-950 border border-brandRed/40 flex items-center justify-center text-brandRed shrink-0">
                                    <i class="fa-brands fa-whatsapp"></i>
                                </div>
                                <div>
                                    <div class="text-xs font-bold text-gray-400 uppercase">Talian Terus & WhatsApp</div>
                                    <a href="https://wa.me/601151453147" target="_blank" class="font-heading font-black text-xl text-brandGold hover:underline">
                                        +601151453147
                                    </a>
                                </div>
                            </div>
                        </div>

                        <div class="pt-4 flex flex-wrap gap-3">
                            <a href="https://maps.google.com/?q=Kompleks+AG+Sentral,+78000+Alor+Gajah,+Melaka" target="_blank" class="px-6 py-3 rounded-xl bg-white text-black font-heading font-extrabold text-xs uppercase tracking-wider hover:bg-gray-200 transition flex items-center gap-2">
                                <i class="fa-solid fa-diamond-turn-right text-brandRed"></i>
                                <span>Buka Google Maps</span>
                            </a>
                            <a href="https://wa.me/601151453147?text=Salam%20Sensei,%20saya%20nak%20set%20appointment%20di%20HQ%20AG%20Sentral%20Melaka." target="_blank" class="red-glow-btn px-6 py-3 rounded-xl text-white font-heading font-extrabold text-xs uppercase tracking-wider flex items-center gap-2">
                                <i class="fa-solid fa-calendar-check"></i>
                                <span>Set Temujanji HQ</span>
                            </a>
                        </div>
                    </div>

                    <!-- Interactive Map Frame -->
                    <div class="lg:col-span-5">
                        <div class="rounded-2xl overflow-hidden border-2 border-red-900/60 shadow-2xl h-80 bg-black relative">
                            <iframe 
                                title="Lokasi SS Dynamic Sensei Alor Gajah Melaka"
                                src="https://maps.google.com/maps?q=Kompleks%20AG%20Sentral,%20Alor%20Gajah,%20Melaka&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                                class="w-full h-full border-0 filter invert contrast-90 hue-rotate-180" 
                                loading="lazy">
                            </iframe>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-black border-t border-red-900/50 pt-14 pb-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-8 pb-10 border-b border-gray-900">
                <div>
                    <div class="font-heading font-black text-xl text-white tracking-wider">
                        SS DYNAMIC <span class="text-brandRed">SENSEI BORONG CHINA</span> & SS DYNAMIC CARGO
                    </div>
                    <p class="text-xs text-gray-400 mt-2 max-w-xl">
                        NO 2, BANGUNAN TERMINAL BAS, KOMPLEKS AG SENTRAL, 78000, ALOR GAJAH, MELAKA | TEL: +601151453147
                    </p>
                </div>
                <div class="flex flex-wrap gap-2 text-xs font-bold text-brandRed">
                    <span>#SSDYNAMICSENSEIBORONGCHINA</span>
                    <span>•</span>
                    <span>#SENSEISSDYNAMIC</span>
                    <span>•</span>
                    <span>#SSDYNAMICCARGO</span>
                </div>
            </div>

            <div class="pt-6 flex flex-col sm:flex-row justify-between items-center text-xs text-gray-500 gap-4">
                <div>© 2026 SS DYNAMIC SENSEI BORONG CHINA & SS DYNAMIC CARGO. Hak Cipta Terpelihara.</div>
                <div class="flex items-center gap-2 text-gray-400">
                    <span>China 🇨🇳</span>
                    <span class="text-brandRed font-bold">⇄</span>
                    <span>Malaysia 🇲🇾 Cross-Border Ecosystem</span>
                </div>
            </div>
        </div>
    </footer>

    <!-- Floating WhatsApp Concierge Button -->
    <a href="https://wa.me/601151453147?text=Salam%20SS%20Dynamic%20Sensei,%20saya%20nak%20bertanya%20tentang%20Borong%20China%20%26%20Cargo." target="_blank" aria-label="WhatsApp SS Dynamic Sensei" class="fixed bottom-6 right-6 z-50 flex items-center gap-3 bg-green-600 hover:bg-green-500 text-white px-5 py-3.5 rounded-full shadow-2xl shadow-green-900/50 transition transform hover:scale-105">
        <i class="fa-brands fa-whatsapp text-2xl"></i>
        <span class="font-heading font-bold text-xs uppercase tracking-wider hidden sm:inline">Chat Sensei (+601151453147)</span>
    </a>

    <!-- Interactive Ecosystem Scripts -->
    <script>
        // Toggle Sea vs Air Calculator Inputs
        const freightType = document.getElementById('freightType');
        const seaInputs = document.getElementById('seaInputs');
        const airInputs = document.getElementById('airInputs');

        freightType.addEventListener('change', () => {
            if (freightType.value === 'sea') {
                seaInputs.classList.remove('hidden');
                airInputs.classList.add('hidden');
            } else {
                seaInputs.classList.add('hidden');
                airInputs.classList.remove('hidden');
            }
            calculateCargo();
        });

        // Cargo Rate Calculator Logic
        function calculateCargo() {
            const type = freightType.value;
            const dest = document.getElementById('destination').value;
            const metricEl = document.getElementById('calcMetric');
            const priceEl = document.getElementById('calcPrice');

            if (type === 'sea') {
                const l = parseFloat(document.getElementById('dimL').value) || 0;
                const w = parseFloat(document.getElementById('dimW').value) || 0;
                const h = parseFloat(document.getElementById('dimH').value) || 0;
                let cbm = (l * w * h) / 1000000;
                if (cbm < 0.05) cbm = 0.05; // Minimum chargeable CBM

                const rate = dest === 'west' ? 480 : 680;
                const total = cbm * rate;

                metricEl.textContent = cbm.toFixed(3) + ' CBM';
                priceEl.textContent = 'RM ' + total.toFixed(2);
            } else {
                const kg = parseFloat(document.getElementById('weightKg').value) || 1;
                const rate = dest === 'west' ? 18 : 26;
                const total = kg * rate;

                metricEl.textContent = kg.toFixed(1) + ' KG';
                priceEl.textContent = 'RM ' + total.toFixed(2);
            }
        }

        // RMB <-> MYR Live Converter
        const EXCHANGE_RATE = 0.69;
        function convertRMB(source) {
            const rmbInput = document.getElementById('rmbInput');
            const myrInput = document.getElementById('myrInput');
            if (source === 'rmb') {
                const val = parseFloat(rmbInput.value) || 0;
                myrInput.value = (val * EXCHANGE_RATE).toFixed(2);
            } else {
                const val = parseFloat(myrInput.value) || 0;
                rmbInput.value = (val / EXCHANGE_RATE).toFixed(2);
            }
        }

        // Hero Quick Tracker
        function quickTrackHero() {
            const code = document.getElementById('heroTrackInput').value.trim();
            const res = document.getElementById('heroTrackResult');
            res.classList.remove('hidden');
            if (!code) {
                res.innerHTML = '<span class="text-red-400">Sila masukkan nombor tracking waybill anda.</span>';
                return;
            }
            res.innerHTML = `<span class="text-green-400 font-semibold">✔ Waybill <strong>${code.toUpperCase()}</strong>: Dalam perjalanan ke Hub Alor Gajah, Melaka.</span>`;
        }

        // Main Tracker
        function runMainTracker() {
            const code = document.getElementById('mainTrackInput').value.trim();
            const box = document.getElementById('mainTrackBox');
            const label = document.getElementById('trackCodeDisplay');
            if (!code) {
                alert('Sila masukkan nombor waybill / tracking terlebih dahulu.');
                return;
            }
            label.textContent = 'WAYBILL: ' + code.toUpperCase();
            box.classList.remove('hidden');
        }
    </script>
</body>
