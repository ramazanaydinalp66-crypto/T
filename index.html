<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TakipPort - Rol Tabanlı Etkinlik ve Duyuru Platformu</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        .fade-in { animation: fadeIn 0.3s ease-in-out forwards; }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(8px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 min-h-screen flex flex-col justify-between">

    <!-- LOGIN SCREEN WRAPPER -->
    <div id="login-screen" class="fixed inset-0 bg-slate-900/60 backdrop-blur-md z-50 flex items-center justify-center p-4">
        <div class="bg-white rounded-3xl max-w-md w-full p-8 space-y-6 shadow-2xl fade-in border border-slate-100">
            <div class="text-center space-y-2">
                <div class="bg-indigo-600 text-white w-14 h-14 rounded-2xl mx-auto flex items-center justify-center shadow-lg shadow-indigo-200 text-2xl">
                    <i class="fa-solid fa-users-gear"></i>
                </div>
                <h2 class="text-2xl font-bold text-slate-900">TakipPort Üye Girişi</h2>
                <p class="text-xs text-slate-400">Yetkili hesabınızla oturum açın.</p>
            </div>
            
            <form onsubmit="handleLogin(event)" class="space-y-4">
                <div>
                    <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Kullanıcı Adı</label>
                    <div class="relative">
                        <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-slate-400">
                            <i class="fa-solid fa-user text-xs"></i>
                        </span>
                        <input type="text" id="login-username" required placeholder="admin, ahmet, zeynep..." class="w-full pl-10 pr-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                    </div>
                </div>
                <div>
                    <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Şifre</label>
                    <div class="relative">
                        <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-slate-400">
                            <i class="fa-solid fa-key text-xs"></i>
                        </span>
                        <input type="password" id="login-password" required placeholder="Şifreniz" class="w-full pl-10 pr-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                    </div>
                </div>
                <div id="login-error" class="hidden text-xs text-rose-600 bg-rose-50 p-2.5 rounded-lg border border-rose-100 text-center font-medium">
                    Kullanıcı adı veya şifre hatalı!
                </div>
                <button type="submit" class="w-full bg-indigo-600 hover:bg-indigo-700 text-white font-medium py-3 rounded-xl shadow-lg shadow-indigo-100 transition-all flex items-center justify-center space-x-2">
                    <span>Giriş Yap</span>
                    <i class="fa-solid fa-arrow-right text-xs"></i>
                </button>
            </form>

            <div class="border-t border-slate-100 pt-4 text-xs text-slate-500 space-y-1.5">
                <p class="font-semibold text-slate-700">Örnek Giriş Bilgileri:</p>
                <div class="grid grid-cols-2 gap-1 text-[11px] text-slate-600">
                    <div><b>Admin:</b> admin / 1234</div>
                    <div><b>Yazılımcı:</b> ahmet / 1234</div>
                    <div><b>İK Uzmanı:</b> zeynep / 1234</div>
                    <div><b>Eğitmen:</b> mehmet / 1234</div>
                </div>
            </div>
        </div>
    </div>

    <!-- MAIN APP WRAPPER -->
    <div id="app-wrapper" class="hidden flex flex-col min-h-screen justify-between">
        <header class="bg-white/80 backdrop-blur-md sticky top-0 z-40 border-b border-slate-200">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
                <div class="flex items-center space-x-3 cursor-pointer" onclick="switchTab('anasayfa')">
                    <div class="bg-indigo-600 text-white p-2 rounded-xl shadow-md shadow-indigo-200">
                        <i class="fa-solid fa-compass text-lg"></i>
                    </div>
                    <div>
                        <span class="font-bold text-lg tracking-tight text-slate-900 block leading-tight">Takip<span class="text-indigo-600">Port</span></span>
                        <span id="header-user-role" class="text-[10px] font-semibold text-slate-400 uppercase">Rol</span>
                    </div>
                </div>
                
                <!-- Navigation Links -->
                <nav class="hidden md:flex space-x-1">
                    <button onclick="switchTab('anasayfa')" id="nav-anasayfa" class="nav-btn px-3 py-2 rounded-lg text-sm font-medium transition-all bg-indigo-50 text-indigo-700">Anasayfa</button>
                    <button onclick="switchTab('duyurular')" id="nav-duyurular" class="nav-btn px-3 py-2 rounded-lg text-sm font-medium transition-all text-slate-600 hover:bg-slate-100">Duyurular</button>
                    <button onclick="switchTab('etkinlikler')" id="nav-etkinlikler" class="nav-btn px-3 py-2 rounded-lg text-sm font-medium transition-all text-slate-600 hover:bg-slate-100">Etkinlikler</button>
                    <button onclick="switchTab('uyeler')" id="nav-uyeler" class="nav-btn px-3 py-2 rounded-lg text-sm font-medium transition-all text-slate-600 hover:bg-slate-100 admin-only">Üye Listesi</button>
                    <button onclick="switchTab('profil')" id="nav-profil" class="nav-btn px-3 py-2 rounded-lg text-sm font-medium transition-all text-slate-600 hover:bg-slate-100 admin-only">Profilim</button>
                    <button onclick="switchTab('giristakip')" id="nav-giristakip" class="nav-btn px-3 py-2 rounded-lg text-sm font-medium transition-all text-slate-600 hover:bg-slate-100 admin-only flex items-center space-x-1.5">
                        <i class="fa-solid fa-shield-halved text-xs"></i>
                        <span>Giriş Takip</span>
                    </button>
                </nav>

                <!-- Action Button & User Info -->
                <div class="flex items-center space-x-3">
                    <div class="flex items-center space-x-2 pl-2 border-l border-slate-200">
                        <span id="logged-user-name" class="hidden sm:inline text-xs font-bold text-slate-700">Kullanıcı</span>
                        <button onclick="handleLogout()" title="Çıkış Yap" class="bg-slate-100 hover:bg-rose-50 hover:text-rose-600 text-slate-600 p-2.5 rounded-xl transition-all">
                            <i class="fa-solid fa-right-from-bracket"></i>
                        </button>
                    </div>
                    <!-- Mobile Menu Toggle -->
                    <button onclick="toggleMobileMenu()" class="md:hidden p-2 rounded-lg text-slate-600 hover:bg-slate-100">
                        <i class="fa-solid fa-bars text-xl"></i>
                    </button>
                </div>
            </div>

            <!-- Mobile Navigation Menu Dropdown -->
            <div id="mobile-menu" class="hidden md:hidden bg-white border-b border-slate-200 px-4 pt-2 pb-4 space-y-1">
                <button onclick="switchTab('anasayfa'); toggleMobileMenu();" class="block w-full text-left px-3 py-2 rounded-lg text-base font-medium text-indigo-700 bg-indigo-50">Anasayfa</button>
                <button onclick="switchTab('duyurular'); toggleMobileMenu();" class="block w-full text-left px-3 py-2 rounded-lg text-base font-medium text-slate-600 hover:bg-slate-100">Duyurular</button>
                <button onclick="switchTab('etkinlikler'); toggleMobileMenu();" class="block w-full text-left px-3 py-2 rounded-lg text-base font-medium text-slate-600 hover:bg-slate-100">Yaklaşan Etkinlikler</button>
                <button onclick="switchTab('uyeler'); toggleMobileMenu();" class="admin-only block w-full text-left px-3 py-2 rounded-lg text-base font-medium text-slate-600 hover:bg-slate-100">Üye Listesi</button>
                <button onclick="switchTab('profil'); toggleMobileMenu();" class="admin-only block w-full text-left px-3 py-2 rounded-lg text-base font-medium text-slate-600 hover:bg-slate-100">Profilim</button>
                <button onclick="switchTab('giristakip'); toggleMobileMenu();" class="admin-only block w-full text-left px-3 py-2 rounded-lg text-base font-medium text-slate-600 hover:bg-slate-100">Giriş Takip Listesi</button>
            </div>
        </header>

        <main class="flex-grow max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8 py-8">

            <!-- SECTION: ANASAYFA -->
            <section id="tab-anasayfa" class="tab-content space-y-8 fade-in">
                <!-- Welcome Banner -->
                <div class="relative overflow-hidden rounded-3xl bg-gradient-to-r from-indigo-900 via-indigo-800 to-violet-900 text-white p-8 sm:p-10 shadow-xl">
                    <div class="absolute -right-12 -bottom-12 w-96 h-96 bg-indigo-600/30 rounded-full blur-3xl pointer-events-none"></div>
                    <div class="relative z-10 max-w-2xl space-y-3">
                        <span id="welcome-badge" class="bg-indigo-500/30 text-indigo-200 text-xs font-semibold px-3 py-1 rounded-full border border-indigo-400/30 uppercase tracking-wider">Yetkili Paneli</span>
                        <h1 id="welcome-title" class="text-3xl sm:text-4xl font-extrabold tracking-tight leading-tight">Hoş Geldiniz</h1>
                        <p id="welcome-desc" class="text-indigo-100 text-sm sm:text-base font-light">Görev tanımınıza ve izinlerinize uygun duyuruları ve etkinlikleri bu platform üzerinden takip edebilirsiniz.</p>
                    </div>
                </div>

                <!-- Quick Stats -->
                <div class="grid grid-cols-1 sm:grid-cols-3 gap-6">
                    <div class="bg-white p-6 rounded-2xl border border-slate-200 shadow-sm flex items-center space-x-4">
                        <div class="w-12 h-12 bg-amber-50 text-amber-600 rounded-xl flex items-center justify-center text-xl font-bold">
                            <i class="fa-solid fa-bullhorn"></i>
                        </div>
                        <div>
                            <p class="text-sm font-medium text-slate-500">Görülebilir Duyurular</p>
                            <h3 id="stat-duyuru-count" class="text-2xl font-bold text-slate-800">0</h3>
                        </div>
                    </div>
                    <div class="bg-white p-6 rounded-2xl border border-slate-200 shadow-sm flex items-center space-x-4">
                        <div class="w-12 h-12 bg-emerald-50 text-emerald-600 rounded-xl flex items-center justify-center text-xl font-bold">
                            <i class="fa-solid fa-calendar-days"></i>
                        </div>
                        <div>
                            <p class="text-sm font-medium text-slate-500">Yaklaşan Etkinlikler</p>
                            <h3 id="stat-etkinlik-count" class="text-2xl font-bold text-slate-800">0</h3>
                        </div>
                    </div>
                    <div class="bg-white p-6 rounded-2xl border border-slate-200 shadow-sm flex items-center space-x-4">
                        <div class="w-12 h-12 bg-indigo-50 text-indigo-600 rounded-xl flex items-center justify-center text-xl font-bold">
                            <i class="fa-solid fa-user-check"></i>
                        </div>
                        <div>
                            <p class="text-sm font-medium text-slate-500">Yetkili Kategorilerim</p>
                            <h3 id="stat-kategori-count" class="text-2xl font-bold text-slate-800">0</h3>
                        </div>
                    </div>
                </div>

                <!-- Recent Previews -->
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
                    <div class="bg-white rounded-2xl p-6 border border-slate-200 shadow-sm space-y-4">
                        <div class="flex items-center justify-between">
                            <h3 class="font-bold text-lg text-slate-800 flex items-center space-x-2">
                                <i class="fa-solid fa-bolt text-amber-500"></i>
                                <span>İzinli Olduğunuz Son Duyurular</span>
                            </h3>
                            <button onclick="switchTab('duyurular')" class="text-sm text-indigo-600 hover:text-indigo-800 font-semibold">Tümü</button>
                        </div>
                        <div id="home-duyurular-list" class="space-y-3"></div>
                    </div>

                    <div class="bg-white rounded-2xl p-6 border border-slate-200 shadow-sm space-y-4">
                        <div class="flex items-center justify-between">
                            <h3 class="font-bold text-lg text-slate-800 flex items-center space-x-2">
                                <i class="fa-solid fa-calendar-check text-emerald-500"></i>
                                <span>Yaklaşan Etkinlikler</span>
                            </h3>
                            <button onclick="switchTab('etkinlikler')" class="text-sm text-indigo-600 hover:text-indigo-800 font-semibold">Tümü</button>
                        </div>
                        <div id="home-etkinlikler-list" class="space-y-3"></div>
                    </div>
                </div>
            </section>

            <!-- SECTION: DUYURULAR -->
            <section id="tab-duyurular" class="tab-content hidden space-y-6 fade-in">
                <div class="flex flex-col sm:flex-row sm:items-center sm:justify-between gap-4">
                    <div>
                        <h2 class="text-2xl font-bold text-slate-900">Duyuru Panosu</h2>
                        <p class="text-sm text-slate-500">Görev tanımınıza (<span id="user-task-badge" class="font-semibold text-indigo-600"></span>) ve kategorilerinize özel duyurular.</p>
                    </div>
                    <div class="flex items-center space-x-3">
                        <input type="text" id="duyuru-search" oninput="renderDuyurular()" placeholder="Duyurularda ara..." class="px-4 py-2 bg-white border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500 w-full sm:w-64">
                        <button onclick="openDuyuruModal()" id="btn-add-duyuru" class="hidden bg-amber-600 hover:bg-amber-700 text-white px-4 py-2 rounded-xl text-sm font-medium shadow-sm flex items-center space-x-2 shrink-0">
                            <i class="fa-solid fa-plus"></i>
                            <span>Duyuru Ekle</span>
                        </button>
                    </div>
                </div>

                <div id="duyurular-grid" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6"></div>
            </section>

            <!-- SECTION: YAKLAŞAN ETKİNLİKLER -->
            <section id="tab-etkinlikler" class="tab-content hidden space-y-6 fade-in">
                <div class="flex flex-col sm:flex-row sm:items-center sm:justify-between gap-4">
                    <div>
                        <h2 class="text-2xl font-bold text-slate-900">Yaklaşan Etkinlikler</h2>
                        <p class="text-sm text-slate-500">Planlanan etkinlik takvimi.</p>
                    </div>
                    <div class="flex items-center space-x-3">
                        <input type="text" id="etkinlik-search" oninput="renderEtkinlikler()" placeholder="Etkinlik ara..." class="px-4 py-2 bg-white border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500 w-full sm:w-64">
                        <button onclick="openEtkinlikModal()" id="btn-add-etkinlik" class="hidden bg-emerald-600 hover:bg-emerald-700 text-white px-4 py-2 rounded-xl text-sm font-medium shadow-sm flex items-center space-x-2 shrink-0">
                            <i class="fa-solid fa-plus"></i>
                            <span>Yeni Ekle</span>
                        </button>
                    </div>
                </div>

                <div id="etkinlikler-grid" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6"></div>
            </section>

            <!-- SECTION: ÜYE LİSTESİ -->
            <section id="tab-uyeler" class="tab-content hidden space-y-6 fade-in">
                <div class="flex flex-col sm:flex-row sm:items-center sm:justify-between gap-4">
                    <div>
                        <h2 class="text-2xl font-bold text-slate-900">Üye Listesi ve Görev Tanımları</h2>
                        <p class="text-sm text-slate-500">Platformdaki üyeler, e-posta adresleri, görevleri ve görebildikleri kategoriler.</p>
                    </div>
                    <button onclick="openUserModal()" class="bg-indigo-600 hover:bg-indigo-700 text-white px-4 py-2 rounded-xl text-sm font-medium shadow-sm flex items-center space-x-2">
                        <i class="fa-solid fa-user-plus text-xs"></i>
                        <span>Yeni Üye Ekle</span>
                    </button>
                </div>

                <div class="bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden">
                    <div class="overflow-x-auto">
                        <table class="w-full text-left border-collapse">
                            <thead>
                                <tr class="bg-slate-50 border-b border-slate-200 text-slate-500 text-xs uppercase tracking-wider font-semibold">
                                    <th class="py-3.5 px-6">Ad Soyad / Kullanıcı</th>
                                    <th class="py-3.5 px-6">E-posta</th>
                                    <th class="py-3.5 px-6">Şifre</th>
                                    <th class="py-3.5 px-6">Görev Tanımı</th>
                                    <th class="py-3.5 px-6">Görülebilir Kategoriler</th>
                                    <th class="py-3.5 px-6">Rolü</th>
                                    <th class="py-3.5 px-6 text-right">İşlemler</th>
                                </tr>
                            </thead>
                            <tbody id="uyeler-tbody" class="divide-y divide-slate-100 text-sm text-slate-700"></tbody>
                        </table>
                    </div>
                </div>
            </section>

            <!-- SECTION: PROFİLİM -->
            <section id="tab-profil" class="tab-content hidden space-y-6 fade-in max-w-2xl mx-auto">
                <div class="bg-white rounded-3xl p-8 border border-slate-200 shadow-sm space-y-6">
                    <div class="flex items-center space-x-4 border-b border-slate-100 pb-6">
                        <div class="w-16 h-16 rounded-2xl bg-indigo-600 text-white flex items-center justify-center text-2xl font-bold shadow-lg shadow-indigo-200">
                            <i class="fa-solid fa-user-shield"></i>
                        </div>
                        <div>
                            <h2 id="profile-name" class="text-2xl font-bold text-slate-900"></h2>
                            <p id="profile-role-desc" class="text-sm text-indigo-600 font-medium"></p>
                        </div>
                    </div>

                    <div class="space-y-4">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-semibold text-slate-400 uppercase tracking-wider mb-1">Kullanıcı Adı</label>
                                <input type="text" id="profile-username" readonly class="w-full px-4 py-2.5 bg-slate-100 border border-slate-200 rounded-xl text-sm text-slate-600 font-medium cursor-not-allowed">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-400 uppercase tracking-wider mb-1">E-posta Adresi</label>
                                <input type="text" id="profile-email" readonly class="w-full px-4 py-2.5 bg-slate-100 border border-slate-200 rounded-xl text-sm text-slate-600 font-medium cursor-not-allowed">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-semibold text-slate-400 uppercase tracking-wider mb-1">Görev Tanımı</label>
                            <input type="text" id="profile-task" readonly class="w-full px-4 py-2.5 bg-slate-100 border border-slate-200 rounded-xl text-sm text-slate-600 font-medium cursor-not-allowed">
                        </div>

                        <div>
                            <label class="block text-xs font-semibold text-slate-400 uppercase tracking-wider mb-2">Erişebileceğiniz Kategoriler</label>
                            <div id="profile-categories" class="flex flex-wrap gap-2"></div>
                        </div>

                        <div class="border-t border-slate-100 pt-6 space-y-4">
                            <h3 class="font-bold text-slate-900 text-base">Şifre Değiştir</h3>
                            <form onsubmit="handlePasswordChange(event)" class="space-y-3">
                                <div>
                                    <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Yeni Şifre</label>
                                    <input type="password" id="new-password" required placeholder="Yeni şifrenizi girin" class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                                </div>
                                <button type="submit" class="bg-indigo-600 hover:bg-indigo-700 text-white font-medium px-5 py-2.5 rounded-xl text-sm shadow-md shadow-indigo-100 transition-all">Şifreyi Güncelle</button>
                            </form>
                        </div>
                    </div>
                </div>
            </section>

            <!-- SECTION: GİRİŞ TAKİP LİSTESİ -->
            <section id="tab-giristakip" class="tab-content hidden space-y-6 fade-in">
                <div class="flex flex-col sm:flex-row sm:items-center sm:justify-between gap-4">
                    <div>
                        <h2 class="text-2xl font-bold text-slate-900">Giriş / Çıkış Takip Listesi (Admin Logları)</h2>
                        <p class="text-sm text-slate-500">Sisteme giriş yapan ve çıkış yapan tüm kullanıcıların erişim logları.</p>
                    </div>
                    <button onclick="clearLoginLogs()" class="bg-rose-50 hover:bg-rose-100 text-rose-600 px-4 py-2 rounded-xl text-sm font-medium transition-all flex items-center space-x-2 border border-rose-200">
                        <i class="fa-solid fa-trash-can"></i>
                        <span>Kayıtları Temizle</span>
                    </button>
                </div>

                <div class="bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden">
                    <div class="overflow-x-auto">
                        <table class="w-full text-left border-collapse">
                            <thead>
                                <tr class="bg-slate-50 border-b border-slate-200 text-slate-500 text-xs uppercase tracking-wider font-semibold">
                                    <th class="py-3.5 px-6">Kullanıcı Adı</th>
                                    <th class="py-3.5 px-6">Ad Soyad</th>
                                    <th class="py-3.5 px-6">İşlem</th>
                                    <th class="py-3.5 px-6">Oturum Bilgisi</th>
                                    <th class="py-3.5 px-6">Tarih & Saat</th>
                                </tr>
                            </thead>
                            <tbody id="giris-takip-tbody" class="divide-y divide-slate-100 text-sm text-slate-700"></tbody>
                        </table>
                    </div>
                </div>
            </section>

        </main>

        <footer class="bg-white border-t border-slate-200 mt-12 py-6">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row items-center justify-between text-sm text-slate-500 space-y-3 sm:space-y-0">
                <p>&copy; 2026 TakipPort. Rol Tabanlı Güvenli Platform.</p>
                <div class="flex space-x-6">
                    <a href="#" class="hover:text-indigo-600 transition-colors">Gizlilik</a>
                    <a href="#" class="hover:text-indigo-600 transition-colors">Şartlar</a>
                    <a href="#" class="hover:text-indigo-600 transition-colors">Destek</a>
                </div>
            </div>
        </footer>
    </div>

    <!-- MODAL: YENİ ÜYE EKLE / DÜZENLE -->
    <div id="user-modal" class="fixed inset-0 bg-slate-900/50 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-white rounded-3xl max-w-lg w-full p-6 sm:p-8 space-y-6 shadow-2xl fade-in">
            <div class="flex items-center justify-between border-b border-slate-100 pb-4">
                <h3 id="user-modal-title" class="text-xl font-bold text-slate-900 flex items-center space-x-2">
                    <i class="fa-solid fa-user-plus text-indigo-600"></i>
                    <span>Yeni Üye Ekle</span>
                </h3>
                <button onclick="closeUserModal()" class="text-slate-400 hover:text-slate-600 p-2 rounded-lg">
                    <i class="fa-solid fa-xmark text-xl"></i>
                </button>
            </div>
            <form id="user-form" onsubmit="handleUserSubmit(event)" class="space-y-4">
                <input type="hidden" id="edit-original-username">
                <div class="grid grid-cols-2 gap-3">
                    <div>
                        <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Ad Soyad</label>
                        <input type="text" id="modal-user-name" required placeholder="Örn: Ali Yılmaz" class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                    </div>
                    <div>
                        <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Kullanıcı Adı</label>
                        <input type="text" id="modal-user-username" required placeholder="kullaniciadi" class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                    </div>
                </div>
                <div class="grid grid-cols-2 gap-3">
                    <div>
                        <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">E-posta</label>
                        <input type="email" id="modal-user-email" required placeholder="ornek@takipport.com" class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                    </div>
                    <div>
                        <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Şifre</label>
                        <input type="text" id="modal-user-pass" required placeholder="Şifre" class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                    </div>
                </div>
                <div>
                    <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Görev Tanımı</label>
                    <input type="text" id="modal-user-task" required placeholder="Örn: Proje Yöneticisi" class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                </div>
                <div class="grid grid-cols-2 gap-3">
                    <div>
                        <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Rol</label>
                        <select id="modal-user-role" class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                            <option value="Üye">Üye</option>
                            <option value="Admin">Admin</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Kategoriler (Yetkiler)</label>
                        <div class="text-[11px] text-slate-500 mb-1">Seçim için kutucukları işaretleyin:</div>
                    </div>
                </div>
                <div id="modal-user-categories-container" class="grid grid-cols-3 gap-2 bg-slate-50 p-3 rounded-xl border border-slate-200 text-xs"></div>
                <div class="flex justify-end space-x-3 pt-2">
                    <button type="button" onclick="closeUserModal()" class="px-5 py-2.5 rounded-xl border border-slate-300 text-sm font-medium text-slate-700 hover:bg-slate-100 transition-all">İptal</button>
                    <button type="submit" class="px-5 py-2.5 rounded-xl bg-indigo-600 hover:bg-indigo-700 text-sm font-medium text-white shadow-md shadow-indigo-100 transition-all">Kaydet</button>
                </div>
            </form>
        </div>
    </div>

    <!-- MODAL: ETKİNLİK EKLE / DÜZENLE -->
    <div id="etkinlik-modal" class="fixed inset-0 bg-slate-900/50 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-white rounded-3xl max-w-lg w-full p-6 sm:p-8 space-y-6 shadow-2xl fade-in">
            <div class="flex items-center justify-between border-b border-slate-100 pb-4">
                <h3 id="etkinlik-modal-title" class="text-xl font-bold text-slate-900 flex items-center space-x-2">
                    <i class="fa-solid fa-calendar-days text-emerald-600"></i>
                    <span>Yeni Etkinlik Ekle</span>
                </h3>
                <button onclick="closeEtkinlikModal()" class="text-slate-400 hover:text-slate-600 p-2 rounded-lg">
                    <i class="fa-solid fa-xmark text-xl"></i>
                </button>
            </div>
            <form id="etkinlik-form" onsubmit="handleEtkinlikSubmit(event)" class="space-y-4">
                <input type="hidden" id="edit-original-etkinlik-id">
                <div>
                    <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Etkinlik Başlığı</label>
                    <input type="text" id="etkinlik-modal-title" required placeholder="Etkinlik adı..." class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                </div>
                <div class="grid grid-cols-2 gap-3">
                    <div>
                        <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Tarih ve Saat</label>
                        <input type="text" id="etkinlik-modal-date" required placeholder="Örn: 15 Ekim 2026 - 14:00" class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                    </div>
                    <div>
                        <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Kategori</label>
                        <input type="text" id="etkinlik-modal-category" required placeholder="Örn: Teknoloji, Seminer" class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                    </div>
                </div>
                <div>
                    <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Yer / Konum</label>
                    <input type="text" id="etkinlik-modal-location" required placeholder="Örn: Konferans Salonu A" class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                </div>
                <div>
                    <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Açıklama</label>
                    <textarea id="etkinlik-modal-desc" rows="3" required placeholder="Etkinlik detayları..." class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500"></textarea>
                </div>
                <div class="flex justify-end space-x-3 pt-2">
                    <button type="button" onclick="closeEtkinlikModal()" class="px-5 py-2.5 rounded-xl border border-slate-300 text-sm font-medium text-slate-700 hover:bg-slate-100 transition-all">İptal</button>
                    <button type="submit" class="px-5 py-2.5 rounded-xl bg-emerald-600 hover:bg-emerald-700 text-sm font-medium text-white shadow-md shadow-emerald-100 transition-all">Kaydet</button>
                </div>
            </form>
        </div>
    </div>

    <!-- MODAL: DUYURU EKLE / DÜZENLE -->
    <div id="duyuru-modal" class="fixed inset-0 bg-slate-900/50 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-white rounded-3xl max-w-lg w-full p-6 sm:p-8 space-y-6 shadow-2xl fade-in">
            <div class="flex items-center justify-between border-b border-slate-100 pb-4">
                <h3 id="duyuru-modal-title" class="text-xl font-bold text-slate-900 flex items-center space-x-2">
                    <i class="fa-solid fa-bullhorn text-amber-600"></i>
                    <span>Yeni Duyuru Ekle</span>
                </h3>
                <button onclick="closeDuyuruModal()" class="text-slate-400 hover:text-slate-600 p-2 rounded-lg">
                    <i class="fa-solid fa-xmark text-xl"></i>
                </button>
            </div>
            <form id="duyuru-form" onsubmit="handleDuyuruSubmit(event)" class="space-y-4">
                <input type="hidden" id="edit-original-duyuru-id">
                <div>
                    <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Duyuru Başlığı</label>
                    <input type="text" id="duyuru-modal-title" required placeholder="Duyuru başlığı..." class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                </div>
                <div class="grid grid-cols-2 gap-3">
                    <div>
                        <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Kategori</label>
                        <select id="duyuru-modal-category" class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                            <option value="Genel">Genel</option>
                            <option value="Önemli">Önemli</option>
                            <option value="Sistem">Sistem</option>
                            <option value="Yazılım">Yazılım</option>
                            <option value="İK">İK</option>
                            <option value="Eğitim">Eğitim</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Tarih</label>
                        <input type="text" id="duyuru-modal-date" required placeholder="Örn: 05 Ekim 2026" class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500">
                    </div>
                </div>
                <div>
                    <label class="block text-xs font-semibold text-slate-600 uppercase tracking-wider mb-1">Duyuru İçeriği</label>
                    <textarea id="duyuru-modal-desc" rows="4" required placeholder="Duyuru detayları..." class="w-full px-4 py-2.5 bg-slate-50 border border-slate-300 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500"></textarea>
                </div>
                <div class="flex justify-end space-x-3 pt-2">
                    <button type="button" onclick="closeDuyuruModal()" class="px-5 py-2.5 rounded-xl border border-slate-300 text-sm font-medium text-slate-700 hover:bg-slate-100 transition-all">İptal</button>
                    <button type="submit" class="px-5 py-2.5 rounded-xl bg-amber-600 hover:bg-amber-700 text-sm font-medium text-white shadow-md shadow-amber-100 transition-all">Kaydet</button>
                </div>
            </form>
        </div>
    </div>

    <!-- MODAL: DETAY -->
    <div id="detail-modal" class="fixed inset-0 bg-slate-900/50 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-white rounded-3xl max-w-lg w-full p-6 sm:p-8 space-y-6 shadow-2xl fade-in">
            <div class="flex items-center justify-between border-b border-slate-100 pb-4">
                <span id="detail-badge" class="text-xs font-semibold px-3 py-1 rounded-full"></span>
                <button onclick="closeDetailModal()" class="text-slate-400 hover:text-slate-600 p-2 rounded-lg">
                    <i class="fa-solid fa-xmark text-xl"></i>
                </button>
            </div>
            <div class="space-y-3">
                <h3 id="detail-title" class="text-xl font-bold text-slate-900"></h3>
                <p id="detail-date" class="text-xs text-slate-400 flex items-center space-x-1">
                    <i class="fa-regular fa-clock"></i> <span id="detail-date-text"></span>
                </p>
                <p id="detail-desc" class="text-sm text-slate-600 leading-relaxed pt-2"></p>
            </div>
            <div class="flex justify-end pt-2">
                <button type="button" onclick="closeDetailModal()" class="px-5 py-2.5 rounded-xl bg-slate-900 text-white text-sm font-medium hover:bg-slate-800 transition-all">Kapat</button>
            </div>
        </div>
    </div>

    <script>
        // Üye ve Rol Veritabanı
        let users = [
            { username: "admin", pass: "1234", name: "Sistem Yöneticisi", email: "admin@takipport.com", task: "Genel Sistem Yönetimi", categories: ["Genel", "Sistem", "Yazılım", "İK", "Eğitim", "Önemli"], role: "Admin" },
            { username: "ahmet", pass: "1234", name: "Ahmet Yılmaz", email: "ahmet@takipport.com", task: "Kıdemli Yazılım Geliştirici", categories: ["Genel", "Sistem", "Yazılım", "Önemli"], role: "Üye" },
            { username: "zeynep", pass: "1234", name: "Zeynep Demir", email: "zeynep@takipport.com", task: "İnsan Kaynakları Uzmanı", categories: ["Genel", "İK", "Eğitim", "Önemli"], role: "Üye" },
            { username: "mehmet", pass: "1234", name: "Mehmet Kaya", email: "mehmet@takipport.com", task: "Eğitmen & Teknik Danışman", categories: ["Genel", "Eğitim", "Yazılım"], role: "Üye" },
            { username: "elif", pass: "1234", name: "Elif Çelik", email: "elif@takipport.com", task: "Destek ve Operasyon Sorumlusu", categories: ["Genel"], role: "Üye" }
        ];

        const allAvailableCategories = ["Genel", "Sistem", "Yazılım", "İK", "Eğitim", "Önemli", "Teknoloji", "Sunum"];

        let duyurular = [
            { id: 1, title: "Yaz Dönemi Çalışma Takvimi Güncellendi", category: "Önemli", date: "03 Ekim 2026", desc: "Yeni dönem çalışma takvimi yönetim kurulu kararıyla güncellenmiştir. Tüm departmanların dikkatle incelemesi rica olunur." },
            { id: 2, title: "Sunucu Bakım ve Sürüm Güncellemesi", category: "Sistem", date: "01 Ekim 2026", desc: "Altyapımızı güçlendirmek amacıyla bu hafta sonu 02:00 - 05:00 saatleri arasında kısa süreli kesintiler yaşanabilir." },
            { id: 3, title: "Yeni React ve Tailwind Atölye Çalışması", category: "Yazılım", date: "30 Eylül 2026", desc: "Yazılım ekibi için planlanan modern arayüz geliştirme eğitim programı detayları paylaşılmıştır." },
            { id: 4, title: "Personel Yan Haklar ve Sigorta Bilgilendirmesi", category: "İK", date: "28 Eylül 2026", desc: "İK departmanımız tarafından yenilenen özel sağlık sigortası kapsamları hakkındaki duyuru." },
            { id: 5, title: "Liderlik ve İletişim Semineri", category: "Eğitim", date: "25 Eylül 2026", desc: "Tüm katılımcılara açık olacak olan gelişim semineri önümüzdeki Salı günü konferans salonunda." }
        ];

        let etkinlikler = [
            { id: 1, title: "Ekim etkinliği", date: "07 Ekim 2026 - 10:00", location: "balık... et....", category: "Hayır Çarşısı", desc: "yapılan bu etkinlikte yapıldı..." },
            { id: 2, title: "Yapay Zeka ve Geleceğin İş Modelleri", date: "15 Ekim 2026 - 14:00", location: "Konferans Salonu A", category: "Teknoloji", desc: "Yapay zeka araçlarının iş süreçlerine entegrasyonu." },
            { id: 3, title: "Sonbahar Proje Sunumları", date: "22 Ekim 2026 - 10:30", location: "Ana Salon", category: "Sunum", desc: "Ekiplerin son çeyrekte geliştirdiği yenilikçi projeler." },
            { id: 4, title: "Yazılım Ekibi Sprint Değerlendirmesi", date: "28 Ekim 2026 - 15:00", location: "Toplantı Odası 2", category: "Yazılım", desc: "Sprint hedefleri ve yeni mimari kararların gözden geçirilmesi." }
        ];

        let loginLogs = [
            { username: "admin", name: "Sistem Yöneticisi", action: "Başarılı Giriş", info: "127.0.0.1 (Admin Oturumu)", date: "03 Ekim 2026 - 18:10" }
        ];

        let currentUser = null;

        window.onload = function() {
            const savedUser = sessionStorage.getItem('currentUser');
            if(savedUser) {
                currentUser = JSON.parse(savedUser);
                startApp();
            }
        };

        function handleLogin(e) {
            e.preventDefault();
            const u = document.getElementById('login-username').value.trim();
            const p = document.getElementById('login-password').value.trim();
            const errBox = document.getElementById('login-error');

            const found = users.find(x => x.username === u && x.pass === p);
            if(found) {
                errBox.classList.add('hidden');
                currentUser = found;
                sessionStorage.setItem('currentUser', JSON.stringify(currentUser));

                loginLogs.unshift({
                    username: found.username,
                    name: found.name,
                    action: "Başarılı Giriş",
                    info: "Güvenli Oturum",
                    date: new Date().toLocaleDateString('tr-TR', { day: 'numeric', month: 'long', year: 'numeric' }) + " - " + new Date().toLocaleTimeString('tr-TR', { hour: '2-digit', minute: '2-digit' })
                });

                startApp();
            } else {
                errBox.classList.remove('hidden');
            }
        }

        function handleLogout() {
            if(currentUser) {
                loginLogs.unshift({
                    username: currentUser.username,
                    name: currentUser.name,
                    action: "Çıkış Yapıldı",
                    info: "Oturum Kapatıldı",
                    date: new Date().toLocaleDateString('tr-TR', { day: 'numeric', month: 'long', year: 'numeric' }) + " - " + new Date().toLocaleTimeString('tr-TR', { hour: '2-digit', minute: '2-digit' })
                });
            }

            sessionStorage.removeItem('currentUser');
            currentUser = null;
            document.getElementById('app-wrapper').classList.add('hidden');
            document.getElementById('login-screen').classList.remove('hidden');
            document.getElementById('login-username').value = '';
            document.getElementById('login-password').value = '';
            document.getElementById('login-error').classList.add('hidden');
        }

        function startApp() {
            document.getElementById('login-screen').classList.add('hidden');
            document.getElementById('app-wrapper').classList.remove('hidden');

            document.getElementById('logged-user-name').innerText = currentUser.name;
            document.getElementById('header-user-role').innerText = currentUser.role + " • " + currentUser.task;

            if(currentUser.role === 'Admin') {
                document.querySelectorAll('.admin-only').forEach(el => el.classList.remove('hidden'));
                document.getElementById('btn-add-etkinlik').classList.remove('hidden');
                document.getElementById('btn-add-duyuru').classList.remove('hidden');
            } else {
                document.querySelectorAll('.admin-only').forEach(el => el.classList.add('hidden'));
                document.getElementById('btn-add-etkinlik').classList.add('hidden');
                document.getElementById('btn-add-duyuru').classList.add('hidden');
                const activeTab = document.querySelector('.tab-content:not(.hidden)').id;
                if(activeTab === 'tab-uyeler' || activeTab === 'tab-profil' || activeTab === 'tab-giristakip') {
                    switchTab('anasayfa');
                }
            }

            document.getElementById('welcome-title').innerText = "Hoş Geldiniz, " + currentUser.name;
            document.getElementById('welcome-desc').innerText = "Görev tanımınız (" + currentUser.task + ") doğrultusunda yetkili olduğunuz kategoriler filtrelenmiştir.";
            document.getElementById('user-task-badge').innerText = currentUser.task;
            document.getElementById('stat-kategori-count').innerText = currentUser.categories.length;

            renderDuyurular();
            renderEtkinlikler();
            renderUyeler();
            renderProfil();
            renderLoginLogs();
            renderHomeLists();
        }

        function switchTab(tabId) {
            if(tabId !== 'anasayfa' && tabId !== 'duyurular' && tabId !== 'etkinlikler' && currentUser.role !== 'Admin') {
                return;
            }
            document.querySelectorAll('.tab-content').forEach(el => el.classList.add('hidden'));
            document.getElementById('tab-' + tabId).classList.remove('hidden');

            document.querySelectorAll('.nav-btn').forEach(btn => {
                btn.classList.remove('bg-indigo-50', 'text-indigo-700');
                btn.classList.add('text-slate-600', 'hover:bg-slate-100');
            });

            const activeBtn = document.getElementById('nav-' + tabId);
            if(activeBtn) {
                activeBtn.classList.remove('text-slate-600', 'hover:bg-slate-100');
                activeBtn.classList.add('bg-indigo-50', 'text-indigo-700');
            }
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        function toggleMobileMenu() {
            document.getElementById('mobile-menu').classList.toggle('hidden');
        }

        function getAccessibleDuyurular() {
            if(currentUser.role === 'Admin') return duyurular;
            return duyurular.filter(d => currentUser.categories.includes(d.category));
        }

        // Render Duyurular
        function renderDuyurular() {
            const container = document.getElementById('duyurular-grid');
            container.innerHTML = '';

            const query = document.getElementById('duyuru-search') ? document.getElementById('duyuru-search').value.toLowerCase() : '';
            let list = getAccessibleDuyurular().filter(d => d.title.toLowerCase().includes(query) || d.desc.toLowerCase().includes(query));

            if (list.length === 0) {
                container.innerHTML = `<div class="col-span-full py-12 text-center text-slate-400">Bu kategoride veya aramanızda görüntülenebilecek duyuru bulunmuyor.</div>`;
                document.getElementById('stat-duyuru-count').innerText = 0;
                return;
            }

            list.forEach(item => {
                let badgeColor = 'bg-indigo-50 text-indigo-700 border-indigo-100';
                if(item.category === 'Önemli') badgeColor = 'bg-rose-50 text-rose-700 border-rose-100';
                if(item.category === 'Sistem') badgeColor = 'bg-amber-50 text-amber-700 border-amber-100';
                if(item.category === 'Yazılım') badgeColor = 'bg-blue-50 text-blue-700 border-blue-100';
                if(item.category === 'İK') badgeColor = 'bg-purple-50 text-purple-700 border-purple-100';

                const card = document.createElement('div');
                card.className = "bg-white p-6 rounded-2xl border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col justify-between space-y-4";
                
                let adminActions = '';
                if(currentUser.role === 'Admin') {
                    adminActions = `
                        <div class="flex items-center space-x-2 pt-2 border-t border-slate-100">
                            <button onclick="editDuyuru(${item.id})" class="flex-1 bg-amber-50 hover:bg-amber-100 text-amber-700 text-xs font-semibold py-2 rounded-xl transition-all flex items-center justify-center space-x-1">
                                <i class="fa-solid fa-pen text-[10px]"></i><span>Düzenle</span>
                            </button>
                            <button onclick="deleteDuyuru(${item.id})" class="bg-rose-50 hover:bg-rose-100 text-rose-600 px-3 py-2 rounded-xl transition-all text-xs" title="Sil">
                                <i class="fa-solid fa-trash-can"></i>
                            </button>
                        </div>
                    `;
                }

                card.innerHTML = `
                    <div class="space-y-3">
                        <div class="flex items-center justify-between">
                            <span class="text-xs font-semibold px-3 py-1 rounded-full border ${badgeColor}">${item.category}</span>
                            <span class="text-xs text-slate-400">${item.date}</span>
                        </div>
                        <h3 class="font-bold text-slate-900 text-base line-clamp-2">${item.title}</h3>
                        <p class="text-sm text-slate-500 line-clamp-3">${item.desc}</p>
                    </div>
                    <div class="space-y-2">
                        <button onclick="openDetailModal('duyuru', ${item.id})" class="text-indigo-600 hover:text-indigo-800 text-sm font-semibold flex items-center space-x-1">
                            <span>Detayı İncele</span>
                            <i class="fa-solid fa-arrow-right text-xs"></i>
                        </button>
                        ${adminActions}
                    </div>
                `;
                container.appendChild(card);
            });
            document.getElementById('stat-duyuru-count').innerText = list.length;
        }

        // Render Etkinlikler
        function renderEtkinlikler() {
            const container = document.getElementById('etkinlikler-grid');
            container.innerHTML = '';

            const query = document.getElementById('etkinlik-search') ? document.getElementById('etkinlik-search').value.toLowerCase() : '';
            let list = etkinlikler.filter(e => e.title.toLowerCase().includes(query) || e.desc.toLowerCase().includes(query));

            if (list.length === 0) {
                container.innerHTML = `<div class="col-span-full py-12 text-center text-slate-400">Etkinlik bulunamadı.</div>`;
                document.getElementById('stat-etkinlik-count').innerText = 0;
                return;
            }

            list.forEach(item => {
                const card = document.createElement('div');
                card.className = "bg-white p-6 rounded-2xl border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col justify-between space-y-4";
                
                let adminActions = '';
                if(currentUser.role === 'Admin') {
                    adminActions = `
                        <div class="flex items-center space-x-2 pt-2 border-t border-slate-100">
                            <button onclick="editEtkinlik(${item.id})" class="flex-1 bg-emerald-50 hover:bg-emerald-100 text-emerald-700 text-xs font-semibold py-2 rounded-xl transition-all flex items-center justify-center space-x-1">
                                <i class="fa-solid fa-pen text-[10px]"></i><span>Düzenle</span>
                            </button>
                            <button onclick="deleteEtkinlik(${item.id})" class="bg-rose-50 hover:bg-rose-100 text-rose-600 px-3 py-2 rounded-xl transition-all text-xs" title="Sil">
                                <i class="fa-solid fa-trash-can"></i>
                            </button>
                        </div>
                    `;
                }

                card.innerHTML = `
                    <div class="space-y-3">
                        <div class="flex items-center justify-between">
                            <span class="text-xs font-semibold px-3 py-1 rounded-full bg-emerald-50 text-emerald-700 border border-emerald-100">${item.category}</span>
                            <span class="text-xs font-medium text-emerald-600 bg-emerald-50/50 px-2 py-0.5 rounded"><i class="fa-solid fa-clock"></i> Aktif</span>
                        </div>
                        <h3 class="font-bold text-slate-900 text-base line-clamp-2">${item.title}</h3>
                        <div class="space-y-1 text-xs text-slate-500">
                            <p class="flex items-center space-x-2"><i class="fa-regular fa-calendar text-indigo-500"></i> <span>${item.date}</span></p>
                            <p class="flex items-center space-x-2"><i class="fa-solid fa-location-dot text-rose-500"></i> <span>${item.location}</span></p>
                        </div>
                        <p class="text-sm text-slate-500 line-clamp-2">${item.desc}</p>
                    </div>
                    <div class="space-y-2">
                        <button onclick="openDetailModal('etkinlik', ${item.id})" class="text-indigo-600 hover:text-indigo-800 text-sm font-semibold flex items-center space-x-1">
                            <span>Etkinlik Detayı</span>
                            <i class="fa-solid fa-arrow-right text-xs"></i>
                        </button>
                        ${adminActions}
                    </div>
                `;
                container.appendChild(card);
            });
            document.getElementById('stat-etkinlik-count').innerText = list.length;
        }

        // Üye Listesi & Yetkilendirme
        function renderUyeler() {
            const tbody = document.getElementById('uyeler-tbody');
            tbody.innerHTML = '';

            users.forEach(u => {
                const isMe = u.username === currentUser.username;
                const tr = document.createElement('tr');
                tr.className = isMe ? "bg-indigo-50/40 font-medium" : "hover:bg-slate-50/80 transition-colors";
                
                let catsHtml = u.categories.map(c => `<span class="px-2 py-0.5 rounded text-[10px] font-bold bg-slate-100 text-slate-700 mr-1">${c}</span>`).join('');

                tr.innerHTML = `
                    <td class="py-4 px-6 text-slate-800 flex items-center space-x-2">
                        <span class="w-8 h-8 rounded-full bg-indigo-100 text-indigo-700 flex items-center justify-center font-bold text-xs"><i class="fa-solid fa-user"></i></span>
                        <div>
                            <span class="block font-bold">${u.name} ${isMe ? '<span class="text-indigo-600 text-xs">(Siz)</span>' : ''}</span>
                            <span class="text-xs text-slate-400">@${u.username}</span>
                        </div>
                    </td>
                    <td class="py-4 px-6 text-slate-600 text-xs">${u.email}</td>
                    <td class="py-4 px-6 text-slate-600 text-xs font-mono">••••</td>
                    <td class="py-4 px-6 text-slate-700 text-xs font-semibold">${u.task}</td>
                    <td class="py-4 px-6">${catsHtml}</td>
                    <td class="py-4 px-6">
                        <span class="px-2.5 py-1 rounded-full text-xs font-bold ${u.role === 'Admin' ? 'bg-purple-50 text-purple-700 border border-purple-100' : 'bg-slate-100 text-slate-700'}">${u.role}</span>
                    </td>
                    <td class="py-4 px-6 text-right space-x-2">
                        <button onclick="editUser('${u.username}')" class="text-indigo-600 hover:text-indigo-900 bg-indigo-50 p-2 rounded-lg transition-all" title="Düzenle"><i class="fa-solid fa-pen text-xs"></i></button>
                        ${!isMe ? `<button onclick="deleteUser('${u.username}')" class="text-rose-600 hover:text-rose-900 bg-rose-50 p-2 rounded-lg transition-all" title="Sil"><i class="fa-solid fa-trash text-xs"></i></button>` : ''}
                    </td>
                `;
                tbody.appendChild(tr);
            });
        }

        function openUserModal(editUsername = null) {
            const container = document.getElementById('modal-user-categories-container');
            container.innerHTML = '';
            
            allAvailableCategories.forEach(cat => {
                container.innerHTML += `
                    <label class="flex items-center space-x-1.5 cursor-pointer">
                        <input type="checkbox" name="user-cat" value="${cat}" class="rounded text-indigo-600 focus:ring-indigo-500">
                        <span class="text-slate-700">${cat}</span>
                    </label>
                `;
            });

            if(editUsername) {
                const target = users.find(u => u.username === editUsername);
                if(!target) return;

                document.getElementById('user-modal-title').innerHTML = `<i class="fa-solid fa-user-pen text-indigo-600"></i> <span>Üye Bilgilerini Düzenle</span>`;
                document.getElementById('edit-original-username').value = target.username;
                document.getElementById('modal-user-name').value = target.name;
                document.getElementById('modal-user-username').value = target.username;
                document.getElementById('modal-user-email').value = target.email;
                document.getElementById('modal-user-pass').value = target.pass;
                document.getElementById('modal-user-task').value = target.task;
                document.getElementById('modal-user-role').value = target.role;

                document.querySelectorAll('input[name="user-cat"]').forEach(chk => {
                    if(target.categories.includes(chk.value)) chk.checked = true;
                });
            } else {
                document.getElementById('user-modal-title').innerHTML = `<i class="fa-solid fa-user-plus text-indigo-600"></i> <span>Yeni Üye Ekle</span>`;
                document.getElementById('user-form').reset();
                document.getElementById('edit-original-username').value = '';
            }

            document.getElementById('user-modal').classList.remove('hidden');
        }

        function closeUserModal() {
            document.getElementById('user-modal').classList.add('hidden');
            document.getElementById('user-form').reset();
        }

        function handleUserSubmit(e) {
            e.preventDefault();
            const originalUsername = document.getElementById('edit-original-username').value;
            const name = document.getElementById('modal-user-name').value.trim();
            const username = document.getElementById('modal-user-username').value.trim();
            const email = document.getElementById('modal-user-email').value.trim();
            const pass = document.getElementById('modal-user-pass').value.trim();
            const task = document.getElementById('modal-user-task').value.trim();
            const role = document.getElementById('modal-user-role').value;

            const selectedCategories = [];
            document.querySelectorAll('input[name="user-cat"]:checked').forEach(chk => {
                selectedCategories.push(chk.value);
            });

            if(originalUsername) {
                const target = users.find(u => u.username === originalUsername);
                if(target) {
                    target.name = name;
                    target.username = username;
                    target.email = email;
                    target.pass = pass;
                    target.task = task;
                    target.role = role;
                    target.categories = selectedCategories;
                }
            } else {
                if(users.some(u => u.username === username)) {
                    alert("Bu kullanıcı adı zaten kullanımda!");
                    return;
                }
                users.push({ username, pass, name, email, task, categories: selectedCategories, role });
            }

            renderUyeler();
            closeUserModal();
        }

        function editUser(username) {
            openUserModal(username);
        }

        function deleteUser(username) {
            if(confirm("Bu üyeyi silmek istediğinize emin misiniz?")) {
                users = users.filter(u => u.username !== username);
                renderUyeler();
            }
        }

        // Profilim
        function renderProfil() {
            document.getElementById('profile-name').innerText = currentUser.name;
            document.getElementById('profile-role-desc').innerText = currentUser.role + " Hesabı";
            document.getElementById('profile-username').value = currentUser.username;
            document.getElementById('profile-email').value = currentUser.email;
            document.getElementById('profile-task').value = currentUser.task;

            const catContainer = document.getElementById('profile-categories');
            catContainer.innerHTML = '';
            currentUser.categories.forEach(c => {
                const span = document.createElement('span');
                span.className = "px-3 py-1 rounded-xl text-xs font-bold bg-indigo-50 text-indigo-700 border border-indigo-100";
                span.innerText = c;
                catContainer.appendChild(span);
            });
        }

        function handlePasswordChange(e) {
            e.preventDefault();
            const newP = document.getElementById('new-password').value.trim();
            if(!newP) return;

            currentUser.pass = newP;
            const target = users.find(u => u.username === currentUser.username);
            if(target) target.pass = newP;

            sessionStorage.setItem('currentUser', JSON.stringify(currentUser));
            alert("Şifreniz başarıyla güncellendi!");
            document.getElementById('new-password').value = '';
        }

        // Login Logs
        function renderLoginLogs() {
            const tbody = document.getElementById('giris-takip-tbody');
            tbody.innerHTML = '';

            if(loginLogs.length === 0) {
                tbody.innerHTML = `<tr><td colspan="5" class="py-6 text-center text-slate-400">Kayıt bulunamadı.</td></tr>`;
                return;
            }

            loginLogs.forEach(log => {
                const tr = document.createElement('tr');
                tr.className = "hover:bg-slate-50/80 transition-colors";
                
                let badgeStyle = "bg-emerald-50 text-emerald-700 border-emerald-100";
                if(log.action === "Çıkış Yapıldı") {
                    badgeStyle = "bg-rose-50 text-rose-700 border-rose-100";
                }

                tr.innerHTML = `
                    <td class="py-4 px-6 font-semibold text-slate-800">@${log.username}</td>
                    <td class="py-4 px-6 text-slate-700 text-xs">${log.name}</td>
                    <td class="py-4 px-6"><span class="px-2.5 py-1 rounded-full text-xs font-semibold border ${badgeStyle}">${log.action}</span></td>
                    <td class="py-4 px-6 text-slate-500 text-xs">${log.info}</td>
                    <td class="py-4 px-6 text-slate-500 text-xs">${log.date}</td>
                `;
                tbody.appendChild(tr);
            });
        }

        function clearLoginLogs() {
            loginLogs = [];
            renderLoginLogs();
        }

        function renderHomeLists() {
            const homeDuyuru = document.getElementById('home-duyurular-list');
            homeDuyuru.innerHTML = '';
            getAccessibleDuyurular().slice(0, 3).forEach(item => {
                const div = document.createElement('div');
                div.className = "p-3 rounded-xl hover:bg-slate-50 transition-all border border-transparent hover:border-slate-100 cursor-pointer flex items-start justify-between space-x-3";
                div.onclick = () => openDetailModal('duyuru', item.id);
                div.innerHTML = `
                    <div class="space-y-1">
                        <span class="text-[10px] font-bold px-2 py-0.5 rounded bg-indigo-50 text-indigo-700">${item.category}</span>
                        <h4 class="text-sm font-semibold text-slate-800">${item.title}</h4>
                        <p class="text-xs text-slate-400">${item.date}</p>
                    </div>
                    <i class="fa-solid fa-chevron-right text-xs text-slate-300 self-center"></i>
                `;
                homeDuyuru.appendChild(div);
            });

            const homeEtkinlik = document.getElementById('home-etkinlikler-list');
            homeEtkinlik.innerHTML = '';
            etkinlikler.slice(0, 3).forEach(item => {
                const div = document.createElement('div');
                div.className = "p-3 rounded-xl hover:bg-slate-50 transition-all border border-transparent hover:border-slate-100 cursor-pointer flex items-start justify-between space-x-3";
                div.onclick = () => openDetailModal('etkinlik', item.id);
                div.innerHTML = `
                    <div class="space-y-1">
                        <span class="text-[10px] font-bold px-2 py-0.5 rounded bg-emerald-50 text-emerald-700">${item.category}</span>
                        <h4 class="text-sm font-semibold text-slate-800">${item.title}</h4>
                        <p class="text-xs text-slate-400">${item.date.split(' - ')[0]}</p>
                    </div>
                    <i class="fa-solid fa-chevron-right text-xs text-slate-300 self-center"></i>
                `;
                homeEtkinlik.appendChild(div);
            });
        }

        // Etkinlik Ekle / Düzenle / Sil
        function openEtkinlikModal(editId = null) {
            if(currentUser.role !== 'Admin') return;
            
            if(editId) {
                const item = etkinlikler.find(e => e.id === editId);
                if(!item) return;
                document.getElementById('etkinlik-modal-title').innerHTML = `<i class="fa-solid fa-pen text-emerald-600"></i> <span>Etkinliği Düzenle</span>`;
                document.getElementById('edit-original-etkinlik-id').value = item.id;
                document.getElementById('etkinlik-modal-title').value = item.title;
                document.getElementById('etkinlik-modal-date').value = item.date;
                document.getElementById('etkinlik-modal-category').value = item.category;
                document.getElementById('etkinlik-modal-location').value = item.location;
                document.getElementById('etkinlik-modal-desc').value = item.desc;
            } else {
                document.getElementById('etkinlik-modal-title').innerHTML = `<i class="fa-solid fa-calendar-days text-emerald-600"></i> <span>Yeni Etkinlik Ekle</span>`;
                document.getElementById('etkinlik-form').reset();
                document.getElementById('edit-original-etkinlik-id').value = '';
            }
            document.getElementById('etkinlik-modal').classList.remove('hidden');
        }

        function closeEtkinlikModal() {
            document.getElementById('etkinlik-modal').classList.add('hidden');
            document.getElementById('etkinlik-form').reset();
        }

        function handleEtkinlikSubmit(e) {
            e.preventDefault();
            const editId = document.getElementById('edit-original-etkinlik-id').value;
            const title = document.getElementById('etkinlik-modal-title').value.trim();
            const date = document.getElementById('etkinlik-modal-date').value.trim();
            const category = document.getElementById('etkinlik-modal-category').value.trim();
            const location = document.getElementById('etkinlik-modal-location').value.trim();
            const desc = document.getElementById('etkinlik-modal-desc').value.trim();

            if(editId) {
                const target = etkinlikler.find(e => e.id == editId);
                if(target) {
                    target.title = title;
                    target.date = date;
                    target.category = category;
                    target.location = location;
                    target.desc = desc;
                }
            } else {
                etkinlikler.unshift({
                    id: Date.now(),
                    title,
                    date,
                    location,
                    category,
                    desc
                });
            }

            renderEtkinlikler();
            renderHomeLists();
            closeEtkinlikModal();
        }

        function editEtkinlik(id) {
            openEtkinlikModal(id);
        }

        function deleteEtkinlik(id) {
            if(confirm("Bu etkinliği silmek istediğinize emin misiniz?")) {
                etkinlikler = etkinlikler.filter(e => e.id !== id);
                renderEtkinlikler();
                renderHomeLists();
            }
        }

        // Duyuru Ekle / Düzenle / Sil
        function openDuyuruModal(editId = null) {
            if(currentUser.role !== 'Admin') return;

            if(editId) {
                const item = duyurular.find(d => d.id === editId);
                if(!item) return;
                document.getElementById('duyuru-modal-title').innerHTML = `<i class="fa-solid fa-pen text-amber-600"></i> <span>Duyuruyu Düzenle</span>`;
                document.getElementById('edit-original-duyuru-id').value = item.id;
                document.getElementById('duyuru-modal-title').value = item.title;
                document.getElementById('duyuru-modal-category').value = item.category;
                document.getElementById('duyuru-modal-date').value = item.date;
                document.getElementById('duyuru-modal-desc').value = item.desc;
            } else {
                document.getElementById('duyuru-modal-title').innerHTML = `<i class="fa-solid fa-bullhorn text-amber-600"></i> <span>Yeni Duyuru Ekle</span>`;
                document.getElementById('duyuru-form').reset();
                document.getElementById('edit-original-duyuru-id').value = '';
            }
            document.getElementById('duyuru-modal').classList.remove('hidden');
        }

        function closeDuyuruModal() {
            document.getElementById('duyuru-modal').classList.add('hidden');
            document.getElementById('duyuru-form').reset();
        }

        function handleDuyuruSubmit(e) {
            e.preventDefault();
            const editId = document.getElementById('edit-original-duyuru-id').value;
            const title = document.getElementById('duyuru-modal-title').value.trim();
            const category = document.getElementById('duyuru-modal-category').value;
            const date = document.getElementById('duyuru-modal-date').value.trim();
            const desc = document.getElementById('duyuru-modal-desc').value.trim();

            if(editId) {
                const target = duyurular.find(d => d.id == editId);
                if(target) {
                    target.title = title;
                    target.category = category;
                    target.date = date;
                    target.desc = desc;
                }
            } else {
                duyurular.unshift({
                    id: Date.now(),
                    title,
                    category,
                    date,
                    desc
                });
            }

            renderDuyurular();
            renderHomeLists();
            closeDuyuruModal();
        }

        function editDuyuru(id) {
            openDuyuruModal(id);
        }

        function deleteDuyuru(id) {
            if(confirm("Bu duyuruyu silmek istediğinize emin misiniz?")) {
                duyurular = duyurular.filter(d => d.id !== id);
                renderDuyurular();
                renderHomeLists();
            }
        }

        function openDetailModal(type, id) {
            let item = (type === 'duyuru') ? duyurular.find(d => d.id === id) : etkinlikler.find(e => e.id === id);
            if(!item) return;

            document.getElementById('detail-badge').innerText = item.category;
            document.getElementById('detail-title').innerText = item.title;
            document.getElementById('detail-date-text').innerText = item.date + (item.location ? ` • ${item.location}` : '');
            document.getElementById('detail-desc').innerText = item.desc;
            document.getElementById('detail-modal').classList.remove('hidden');
        }

        function closeDetailModal() {
            document.getElementById('detail-modal').classList.add('hidden');
        }
    </script>
</body>
</html>
