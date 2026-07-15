<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SMP Negeri 4 Tojo - Cerdas, Berkarakter, Berprestasi</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 flex flex-col min-h-screen">

    <!-- TOP BAR -->
    <div class="bg-blue-900 text-white text-xs py-2 px-4 sm:px-8 flex justify-between items-center">
        <div class="flex items-center gap-4">
            <span><i class="fa-solid fa-envelope text-yellow-400 mr-1"></i> info@smpn4tojo.sch.id</span>
            <span class="hidden md:inline"><i class="fa-solid fa-phone text-yellow-400 mr-1"></i> +62 812-3456-7890</span>
        </div>
        <div class="flex items-center gap-3">
            <a href="#" class="hover:text-yellow-400 transition"><i class="fa-brands fa-facebook"></i></a>
            <a href="#" class="hover:text-yellow-400 transition"><i class="fa-brands fa-instagram"></i></a>
            <a href="#" class="hover:text-yellow-400 transition"><i class="fa-brands fa-youtube"></i></a>
        </div>
    </div>

    <!-- HEADER / NAVIGATION -->
    <header class="sticky top-0 z-50 bg-white/95 backdrop-blur-md shadow-md">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex justify-between items-center py-4">
            <!-- Logo & Brand -->
            <div class="flex items-center gap-3">
                <div class="bg-blue-600 text-white p-2.5 rounded-lg shadow-md">
                    <i class="fa-solid fa-graduation-cap text-2xl"></i>
                </div>
                <div>
                    <h1 class="text-lg font-bold tracking-tight text-blue-900 leading-none">SMP NEGERI 4 TOJO</h1>
                    <span class="text-xs text-slate-500 font-medium tracking-widest">KABUPATEN TOJO UNA-UNA</span>
                </div>
            </div>

            <!-- Desktop Menu -->
            <nav class="hidden md:flex items-center gap-6 font-medium text-slate-600">
                <a href="#beranda" class="hover:text-blue-600 transition duration-300">Beranda</a>
                <a href="#profil" class="hover:text-blue-600 transition duration-300">Profil</a>
                <a href="#akademik" class="hover:text-blue-600 transition duration-300">Akademik</a>
                <a href="#berita" class="hover:text-blue-600 transition duration-300">Pengumuman & Berita</a>
                <a href="#galeri" class="hover:text-blue-600 transition duration-300">Galeri</a>
                <a href="#kontak" class="bg-blue-600 text-white px-5 py-2.5 rounded-full hover:bg-blue-700 transition duration-300 shadow-md">Hubungi Kami</a>
            </nav>

            <!-- Mobile Menu Button -->
            <button id="menu-btn" class="md:hidden text-slate-700 focus:outline-none">
                <i class="fa-solid fa-bars text-2xl"></i>
            </button>
        </div>

        <!-- Mobile Menu (Hidden by default) -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-slate-100 py-4 px-6 flex flex-col gap-4 shadow-inner">
            <a href="#beranda" class="hover:text-blue-600 py-1 transition font-medium">Beranda</a>
            <a href="#profil" class="hover:text-blue-600 py-1 transition font-medium">Profil</a>
            <a href="#akademik" class="hover:text-blue-600 py-1 transition font-medium">Akademik</a>
            <a href="#berita" class="hover:text-blue-600 py-1 transition font-medium">Pengumuman & Berita</a>
            <a href="#galeri" class="hover:text-blue-600 py-1 transition font-medium">Galeri</a>
            <a href="#kontak" class="bg-blue-600 text-white text-center py-2.5 rounded-lg hover:bg-blue-700 transition font-medium">Hubungi Kami</a>
        </div>
    </header>

    <!-- MAIN CONTENT -->
    <main class="flex-grow">

        <!-- HERO SECTION (BERANDA) -->
        <section id="beranda" class="relative bg-gradient-to-r from-blue-900 to-indigo-850 text-white min-h-[550px] flex items-center overflow-hidden">
            <!-- Background Overlay Pattern -->
            <div class="absolute inset-0 bg-cover bg-center opacity-10" style="background-image: url('https://images.unsplash.com/photo-1541339907198-e08756dedf3f?auto=format&fit=crop&q=80');"></div>
            
            <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20 flex flex-col md:flex-row items-center gap-12 z-10">
                <div class="md:w-1/2 space-y-6">
                    <span class="bg-blue-500/30 text-blue-300 px-4 py-1.5 rounded-full text-sm font-semibold tracking-wide uppercase border border-blue-500/20">Selamat Datang</span>
                    <h2 class="text-4xl sm:text-5xl font-extrabold leading-tight">Mewujudkan Generasi Cerdas dan Berkarakter</h2>
                    <p class="text-lg text-slate-300 leading-relaxed">Selamat datang di portal resmi SMP Negeri 4 Tojo. Wadah belajar yang inklusif, inovatif, dan berdedikasi tinggi untuk mencetak lulusan yang unggul dalam prestasi dan kuat dalam karakter.</p>
                    <div class="flex gap-4 pt-2">
                        <a href="#profil" class="bg-yellow-500 hover:bg-yellow-600 text-slate-900 font-semibold px-6 py-3 rounded-lg shadow-lg hover:shadow-xl transition transform hover:-translate-y-0.5">Jelajahi Profil</a>
                        <a href="#akademik" class="bg-transparent hover:bg-white/10 text-white font-semibold px-6 py-3 rounded-lg border-2 border-white/80 transition">Program Kami</a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <!-- Hero Image Wrapper -->
                    <div class="relative w-full max-w-md">
                        <div class="absolute -inset-1 bg-gradient-to-r from-yellow-400 to-blue-500 rounded-2xl blur opacity-30"></div>
                        <img class="relative rounded-2xl shadow-2xl border-4 border-white/10" src="https://images.unsplash.com/photo-1523050854058-8df90110c9f1?auto=format&fit=crop&q=80" alt="Siswa SMP">
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTIONS - SEKILAS INFO -->
        <section class="bg-blue-50 py-10 border-b border-slate-200">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row items-center justify-between gap-6">
                <div class="flex items-center gap-4">
                    <span class="bg-red-500 text-white text-xs font-bold uppercase px-3 py-1.5 rounded animate-pulse">PENTING</span>
                    <p class="text-slate-700 font-medium">Penerimaan Peserta Didik Baru (PPDB) Tahun Pelajaran Baru Telah Dibuka!</p>
                </div>
                <a href="#kontak" class="text-blue-600 hover:text-blue-800 font-bold flex items-center gap-2 text-sm">Info Pendaftaran <i class="fa-solid fa-arrow-right"></i></a>
            </div>
        </section>

        <!-- PROFIL SECTION -->
        <section id="profil" class="py-20">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <span class="text-blue-600 font-bold uppercase tracking-widest text-sm">Tentang Kami</span>
                    <h2 class="text-3xl sm:text-4xl font-extrabold mt-2 text-slate-900">Mengenal SMP Negeri 4 Tojo</h2>
                    <p class="text-slate-600 mt-4 text-lg">Berdiri dengan kokoh di wilayah Kabupaten Tojo Una-Una, kami berkomitmen memberikan pendidikan tingkat menengah terbaik bagi putra-putri bangsa.</p>
                </div>

                <div class="grid md:grid-cols-3 gap-8">
                    <!-- Sambutan Kepala Sekolah -->
                    <div class="md:col-span-1 bg-white p-6 rounded-2xl shadow-md border border-slate-100 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xl font-bold text-slate-800 mb-4 border-b pb-2">Sambutan Kepsek</h3>
                            <p class="text-slate-600 italic text-sm leading-relaxed">"Pendidikan bukan sekadar mengisi wadah yang kosong, tapi menyalakan api pemikiran. Kami menyambut hangat kehadiran Anda di website ini."</p>
                        </div>
                        <div class="flex items-center gap-3 mt-6 pt-4 border-t">
                            <div class="w-12 h-12 rounded-full bg-slate-300 flex items-center justify-center font-bold text-slate-600">Kepsek</div>
                            <div>
                                <h4 class="font-bold text-slate-800 text-sm">Nama Kepala Sekolah, S.Pd.</h4>
                                <p class="text-xs text-slate-500">Kepala Sekolah SMPN 4 Tojo</p>
                            </div>
                        </div>
                    </div>

                    <!-- Visi & Misi -->
                    <div class="md:col-span-2 bg-gradient-to-br from-blue-900 to-indigo-900 text-white p-8 rounded-2xl shadow-xl">
                        <h3 class="text-2xl font-bold mb-6 flex items-center gap-3"><i class="fa-solid fa-bullseye text-yellow-400"></i> Visi & Misi Kami</h3>
                        
                        <div class="space-y-6">
                            <div>
                                <h4 class="text-yellow-400 font-bold uppercase tracking-wider text-sm mb-1">Visi</h4>
                                <p class="text-lg font-medium leading-relaxed">"Terwujudnya insan yang bertakwa, cerdas, berkarakter mulia, dan berwawasan lingkungan."</p>
                            </div>
                            <div>
                                <h4 class="text-yellow-400 font-bold uppercase tracking-wider text-sm mb-2">Misi</h4>
                                <ul class="list-disc pl-5 space-y-2 text-slate-300 text-sm">
                                    <li>Menyelenggarakan pembelajaran berkualitas yang berorientasi pada pengembangan Iptek dan Imtak.</li>
                                    <li>Membina karakter peserta didik melalui program keagamaan dan pembiasaan budaya positif.</li>
                                    <li>Mendorong potensi minat dan bakat non-akademik siswa melalui ekstrakurikuler yang aktif.</li>
                                    <li>Mewujudkan lingkungan sekolah yang bersih, sehat, rindang, dan ramah anak.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- AKADEMIK & EKSTRAKURIKULER -->
        <section id="akademik" class="py-20 bg-slate-100">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <span class="text-blue-600 font-bold uppercase tracking-widest text-sm">Program Unggulan</span>
                    <h2 class="text-3xl sm:text-4xl font-extrabold mt-2 text-slate-900">Akademik & Ekstrakurikuler</h2>
                    <p class="text-slate-600 mt-4">Kami memfasilitasi perkembangan akademik maupun non-akademik siswa melalui fasilitas terbaik yang kami sediakan.</p>
                </div>

                <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
                    <!-- Card 1 -->
                    <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-slate-200/60 group">
                        <div class="w-12 h-12 rounded-lg bg-blue-100 text-blue-650 flex items-center justify-center mb-5 text-xl font-bold group-hover:bg-blue-600 group-hover:text-white transition duration-300">
                            <i class="fa-solid fa-flask"></i>
                        </div>
                        <h3 class="text-lg font-bold text-slate-800 mb-2">Laboratorium IPA</h3>
                        <p class="text-sm text-slate-600">Eksperimen langsung yang seru dan interaktif untuk mendukung pemahaman saintek secara nyata.</p>
                    </div>
                    <!-- Card 2 -->
                    <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-slate-200/60 group">
                        <div class="w-12 h-12 rounded-lg bg-emerald-100 text-emerald-650 flex items-center justify-center mb-5 text-xl font-bold group-hover:bg-emerald-600 group-hover:text-white transition duration-300">
                            <i class="fa-solid fa-laptop-code"></i>
                        </div>
                        <h3 class="text-lg font-bold text-slate-800 mb-2">Lab Komputer</h3>
                        <p class="text-sm text-slate-600">Melatih literasi digital siswa dengan teknologi ter-update serta koneksi internet yang lancar.</p>
                    </div>
                    <!-- Card 3 -->
                    <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-slate-200/60 group">
                        <div class="w-12 h-12 rounded-lg bg-yellow-100 text-yellow-650 flex items-center justify-center mb-5 text-xl font-bold group-hover:bg-yellow-600 group-hover:text-white transition duration-300">
                            <i class="fa-solid fa-trophy"></i>
                        </div>
                        <h3 class="text-lg font-bold text-slate-800 mb-2">Ekstrakurikuler</h3>
                        <p class="text-sm text-slate-600">Pramuka, Olahraga, Kesenian, dan PMR untuk mengasah minat, bakat, serta jiwa kepemimpinan.</p>
                    </div>
                    <!-- Card 4 -->
                    <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-slate-200/60 group">
                        <div class="w-12 h-12 rounded-lg bg-purple-100 text-purple-650 flex items-center justify-center mb-5 text-xl font-bold group-hover:bg-purple-600 group-hover:text-white transition duration-300">
                            <i class="fa-solid fa-book-reader"></i>
                        </div>
                        <h3 class="text-lg font-bold text-slate-800 mb-2">Perpustakaan Digital</h3>
                        <p class="text-sm text-slate-600">Koleksi buku pembelajaran terlengkap untuk menumbuhkan minat literasi membaca harian siswa.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- BERITA & PENGUMUMAN -->
        <section id="berita" class="py-20">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="flex flex-col md:flex-row justify-between items-start md:items-end mb-12">
                    <div>
                        <span class="text-blue-600 font-bold uppercase tracking-widest text-sm">Informasi Terkini</span>
                        <h2 class="text-3xl sm:text-4xl font-extrabold mt-2 text-slate-900">Berita & Pengumuman Sekolah</h2>
                    </div>
                    <a href="#" class="mt-4 md:mt-0 bg-blue-50 text-blue-600 font-bold px-5 py-2.5 rounded-lg hover:bg-blue-100 transition flex items-center gap-2">Arsip Berita <i class="fa-solid fa-folder-open"></i></a>
                </div>

                <div class="grid md:grid-cols-3 gap-8">
                    <!-- Berita 1 -->
                    <article class="bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-lg transition border border-slate-200 flex flex-col justify-between">
                        <div>
                            <img class="w-full h-48 object-cover" src="https://images.unsplash.com/photo-1427504494785-3a9ca7044f45?auto=format&fit=crop&q=80" alt="Kegiatan Siswa">
                            <div class="p-6">
                                <span class="text-xs text-blue-600 font-semibold tracking-widest uppercase">Kegiatan Sekolah</span>
                                <h3 class="text-lg font-bold text-slate-800 mt-2 hover:text-blue-600 transition duration-200"><a href="#">Pekan Kreativitas Siswa Menjelang Akhir Semester</a></h3>
                                <p class="text-sm text-slate-600 mt-3 line-clamp-3">Siswa-siswi SMPN 4 Tojo unjuk kreativitas melalui pentas seni dan pameran kewirausahaan yang diselenggarakan meriah minggu ini...</p>
                            </div>
                        </div>
                        <div class="px-6 py-4 border-t border-slate-100 flex items-center justify-between text-xs text-slate-500">
                            <span><i class="fa-solid fa-calendar-days mr-1"></i> 14 Juli 2026</span>
                            <span>Oleh: Admin</span>
                        </div>
                    </article>

                    <!-- Berita 2 -->
                    <article class="bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-lg transition border border-slate-200 flex flex-col justify-between">
                        <div>
                            <img class="w-full h-48 object-cover" src="https://images.unsplash.com/photo-1517245386807-bb43f82c33c4?auto=format&fit=crop&q=80" alt="Prestasi Siswa">
                            <div class="p-6">
                                <span class="text-xs text-emerald-600 font-semibold tracking-widest uppercase">Prestasi</span>
                                <h3 class="text-lg font-bold text-slate-800 mt-2 hover:text-blue-600 transition duration-200"><a href="#">Selamat! SMPN 4 Tojo Borong Juara di FLS2N Tingkat Kabupaten</a></h3>
                                <p class="text-sm text-slate-600 mt-3 line-clamp-3">Siswa berprestasi kita berhasil menyabet juara pertama dalam kategori cipta puisi dan tari kreasi tradisi tahun ini...</p>
                            </div>
                        </div>
                        <div class="px-6 py-4 border-t border-slate-100 flex items-center justify-between text-xs text-slate-500">
                            <span><i class="fa-solid fa-calendar-days mr-1"></i> 10 Juli 2026</span>
                            <span>Oleh: Kesiswaan</span>
                        </div>
                    </article>

                    <!-- Berita 3 -->
                    <article class="bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-lg transition border border-slate-200 flex flex-col justify-between">
                        <div>
                            <img class="w-full h-48 object-cover" src="https://images.unsplash.com/photo-1577896851231-70ef18881754?auto=format&fit=crop&q=80" alt="Sosialisasi">
                            <div class="p-6">
                                <span class="text-xs text-purple-600 font-semibold tracking-widest uppercase">Akademik</span>
                                <h3 class="text-lg font-bold text-slate-800 mt-2 hover:text-blue-600 transition duration-200"><a href="#">Sosialisasi Kurikulum Merdeka Untuk Wali Murid Baru</a></h3>
                                <p class="text-sm text-slate-600 mt-3 line-clamp-3">Guna mengoptimalkan transisi belajar, sekolah mengadakan audiensi santai terkait sistem asesmen terbaru bersama jajaran komite sekolah...</p>
                            </div>
                        </div>
                        <div class="px-6 py-4 border-t border-slate-100 flex items-center justify-between text-xs text-slate-500">
                            <span><i class="fa-solid fa-calendar-days mr-1"></i> 08 Juli 2026</span>
                            <span>Oleh: Wakasek Kurikulum</span>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <!-- GALERI SEKOLAH -->
        <section id="galeri" class="py-20 bg-slate-100">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <span class="text-blue-600 font-bold uppercase tracking-widest text-sm">Dokumentasi</span>
                    <h2 class="text-3xl sm:text-4xl font-extrabold mt-2 text-slate-900">Galeri Aktivitas Siswa</h2>
                    <p class="text-slate-600 mt-4">Keseruan dan potret kehangatan proses belajar mengajar kami.</p>
                </div>

                <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                    <div class="overflow-hidden rounded-xl shadow-sm group relative">
                        <img class="w-full h-56 object-cover transform group-hover:scale-105 transition duration-500" src="https://images.unsplash.com/photo-1509062522246-3755977927d7?auto=format&fit=crop&q=80" alt="Kelas">
                    </div>
                    <div class="overflow-hidden rounded-xl shadow-sm group relative">
                        <img class="w-full h-56 object-cover transform group-hover:scale-105 transition duration-500" src="https://images.unsplash.com/photo-1544717305-2782549b5136?auto=format&fit=crop&q=80" alt="Membaca">
                    </div>
                    <div class="overflow-hidden rounded-xl shadow-sm group relative">
                        <img class="w-full h-56 object-cover transform group-hover:scale-105 transition duration-500" src="https://images.unsplash.com/photo-1529156069898-49953e39b3ac?auto=format&fit=crop&q=80" alt="Komunitas">
                    </div>
                    <div class="overflow-hidden rounded-xl shadow-sm group relative">
                        <img class="w-full h-56 object-cover transform group-hover:scale-105 transition duration-500" src="https://images.unsplash.com/photo-1511629091441-ee46146481b6?auto=format&fit=crop&q=80" alt="Guru">
                    </div>
                </div>
            </div>
        </section>

        <!-- HUBUNGI KAMI (KONTAK) -->
        <section id="kontak" class="py-20">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="bg-white rounded-3xl shadow-xl border border-slate-100 overflow-hidden flex flex-col lg:flex-row">
                    <!-- Form Kontak -->
                    <div class="p-8 sm:p-12 lg:w-1/2">
                        <span class="text-blue-600 font-bold uppercase tracking-widest text-sm">Hubungi Kami</span>
                        <h2 class="text-2xl sm:text-3xl font-extrabold mt-2 text-slate-900 mb-8">Kirim Pesan atau Pertanyaan</h2>
                        
                        <form class="space-y-5">
                            <div>
                                <label class="block text-sm font-semibold text-slate-700 mb-1" for="nama">Nama Lengkap</label>
                                <input class="w-full px-4 py-3 rounded-lg border border-slate-300 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition" type="text" id="nama" placeholder="Contoh: Budi Santoso" required>
                            </div>
                            <div>
                                <label class="block text-sm font-semibold text-slate-700 mb-1" for="email">Alamat Email</label>
                                <input class="w-full px-4 py-3 rounded-lg border border-slate-300 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition" type="email" id="email" placeholder="contoh@gmail.com" required>
                            </div>
                            <div>
                                <label class="block text-sm font-semibold text-slate-700 mb-1" id="pesan">Pesan Anda</label>
                                <textarea class="w-full px-4 py-3 rounded-lg border border-slate-300 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition" rows="4" placeholder="Tuliskan detail pertanyaan atau masukan Anda..." required></textarea>
                            </div>
                            <button type="submit" class="w-full bg-blue-600 text-white font-bold py-3 rounded-lg hover:bg-blue-700 transition shadow-md flex items-center justify-center gap-2">Kirim Sekarang <i class="fa-solid fa-paper-plane text-sm"></i></button>
                        </form>
                    </div>

                    <!-- Peta & Detail Kontak -->
                    <div class="bg-gradient-to-br from-blue-900 to-indigo-950 text-white p-8 sm:p-12 lg:w-1/2 flex flex-col justify-between">
                        <div class="space-y-6">
                            <h3 class="text-2xl font-bold mb-4">Informasi Kontak</h3>
                            <div class="flex items-start gap-4">
                                <i class="fa-solid fa-map-location-dot text-yellow-400 text-xl mt-1"></i>
                                <div>
                                    <h4 class="font-bold">Alamat Sekolah</h4>
                                    <p class="text-sm text-slate-300">Jl. Trans Sulawesi, Kecamatan Tojo, Kabupaten Tojo Una-Una, Provinsi Sulawesi Tengah.</p>
                                </div>
                            </div>
                            <div class="flex items-start gap-4">
                                <i class="fa-solid fa-phone-volume text-yellow-400 text-xl mt-1"></i>
                                <div>
                                    <h4 class="font-bold">Telepon / WhatsApp</h4>
                                    <p class="text-sm text-slate-300">+62 812-3456-7890</p>
                                </div>
                            </div>
                            <div class="flex items-start gap-4">
                                <i class="fa-solid fa-clock text-yellow-400 text-xl mt-1"></i>
                                <div>
                                    <h4 class="font-bold">Jam Kerja</h4>
                                    <p class="text-sm text-slate-300">Senin - Sabtu: 07.15 s.d 14.00 WITA</p>
                                </div>
                            </div>
                        </div>

                        <!-- Embedded Simple Map (Mockup Area / Info) -->
                        <div class="mt-8 bg-white/10 p-4 rounded-xl border border-white/10 flex items-center gap-4">
                            <i class="fa-solid fa-map-marked-alt text-3xl text-yellow-400"></i>
                            <div>
                                <h4 class="font-bold text-sm">Lokasi SMPN 4 Tojo</h4>
                                <p class="text-xs text-slate-300">Hubungi kami melalui nomor di atas untuk petunjuk arah langsung.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- FOOTER -->
    <footer class="bg-slate-900 text-white pt-16 pb-8 border-t-4 border-yellow-500">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid md:grid-cols-4 gap-8 mb-12">
            <!-- Col 1 -->
            <div class="md:col-span-2 space-y-4">
                <div class="flex items-center gap-3">
                    <div class="bg-blue-600 text-white p-2 rounded-lg">
                        <i class="fa-solid fa-graduation-cap text-xl"></i>
                    </div>
                    <span class="text-lg font-bold">SMP NEGERI 4 TOJO</span>
                </div>
                <p class="text-sm text-slate-400 max-w-sm">Berkomitmen melahirkan talenta-talenta muda yang berintegritas tinggi, bermartabat, dan siap menghadapi tantangan masa depan.</p>
            </div>
            <!-- Col 2 -->
            <div>
                <h3 class="text-base font-bold text-yellow-400 uppercase tracking-widest mb-4">Pintasan Link</h3>
                <ul class="space-y-2 text-sm text-slate-400">
                    <li><a href="#profil" class="hover:text-white transition">Visi & Misi</a></li>
                    <li><a href="#akademik" class="hover:text-white transition">Program Pendidikan</a></li>
                    <li><a href="#berita" class="hover:text-white transition">Pengumuman & Berita</a></li>
                    <li><a href="#kontak" class="hover:text-white transition">Lokasi Map</a></li>
                </ul>
            </div>
            <!-- Col 3 -->
            <div>
                <h3 class="text-base font-bold text-yellow-400 uppercase tracking-widest mb-4">Media Sosial</h3>
                <div class="flex gap-4">
                    <a href="#" class="w-10 h-10 rounded-full bg-slate-800 flex items-center justify-center hover:bg-blue-600 transition text-sm"><i class="fa-brands fa-facebook-f"></i></a>
                    <a href="#" class="w-10 h-10 rounded-full bg-slate-800 flex items-center justify-center hover:bg-pink-600 transition text-sm"><i class="fa-brands fa-instagram"></i></a>
                    <a href="#" class="w-10 h-10 rounded-full bg-slate-800 flex items-center justify-center hover:bg-red-600 transition text-sm"><i class="fa-brands fa-youtube"></i></a>
                </div>
            </div>
        </div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 border-t border-slate-800 pt-8 text-center text-xs text-slate-500">
            <p>&copy; 2026 SMP Negeri 4 Tojo. Hak Cipta Dilindungi Undang-Undang.</p>
            <p class="mt-1">Dibuat dengan penuh dedikasi untuk masa depan generasi Tojo.</p>
        </div>
    </footer>

    <!-- JAVASCRIPT FOR MOBILE MENU TOGGLE -->
    <script>
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when clicking a link
        const mobileLinks = mobileMenu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>

