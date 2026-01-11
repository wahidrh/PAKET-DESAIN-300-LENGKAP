<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Paket Desain Rumah Lengkap (Produk Digital)</title>

  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap');
    body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
    .gradient-bg { background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); }
    .card-hover:hover { transform: translateY(-5px); transition: all 0.25s ease; }

    .cta-pulse { animation: pulse 2s infinite; }
    @keyframes pulse {
      0% { transform: scale(1); box-shadow: 0 0 0 0 rgba(59,130,246,.6); }
      70% { transform: scale(1.03); box-shadow: 0 0 0 12px rgba(59,130,246,0); }
      100% { transform: scale(1); box-shadow: 0 0 0 0 rgba(59,130,246,0); }
    }

    .faq-content { max-height: 0; overflow: hidden; transition: max-height 0.3s ease-out; }
    .faq-item.active .faq-content { max-height: 260px; }
    .faq-item.active i { transform: rotate(180deg); }
  </style>
</head>

<body class="bg-gray-50 text-gray-900">

  <!-- CONFIG -->
  <script>
    // WA 082325680110 -> internasional tanpa 0
    const WA_NUMBER = "6282325680110";
    const SHOPEE_URL = "https://shopee.co.id/product/292097216/29534427806/";
  </script>

  <!-- HERO -->
  <header class="gradient-bg text-white py-16 px-6 lg:py-24">
    <div class="max-w-6xl mx-auto text-center">
      <span class="inline-flex items-center gap-2 bg-blue-600 text-xs font-bold px-3 py-1 rounded-full mb-4 uppercase tracking-widest">
        <i class="fas fa-bolt"></i> Produk Digital • Akses via Google Drive
      </span>

      <h1 class="text-3xl md:text-5xl lg:text-6xl font-extrabold mb-6 leading-tight">
        Bingung Mau Bangun Rumah<br class="hidden md:block"> di Tanah Sendiri?
      </h1>

      <p class="text-lg md:text-xl text-gray-300 mb-10 max-w-3xl mx-auto">
        Paket desain rumah <b>300+ file</b> berbagai ukuran. Kamu <b>tidak wajib download semua</b> — cukup buka Drive, cari desain sesuai kebutuhan, lalu pakai.
        Tersedia <b>SKP & CAD</b> sehingga <b>bisa diedit</b>.
      </p>

      <div class="flex flex-col sm:flex-row justify-center gap-4">
        <a href="#beli" class="cta-pulse bg-blue-600 hover:bg-blue-700 text-white font-bold py-4 px-8 rounded-xl text-lg transition">
          Ambil Paket Sekarang — Rp 50.000
        </a>
        <a href="#fitur" class="bg-white/10 hover:bg-white/20 text-white font-semibold py-4 px-8 rounded-xl border border-white/30 backdrop-blur-sm transition">
          Lihat Isi Paket
        </a>
      </div>

      <div class="mt-6 flex flex-col sm:flex-row justify-center gap-3 text-sm text-gray-200">
        <span class="inline-flex items-center gap-2 bg-white/10 border border-white/20 px-3 py-2 rounded-xl">
          <i class="fas fa-circle-info text-blue-300"></i>
          Produk Digital • Bukan Barang Fisik • Bukan Jasa Desain Custom
        </span>
        <span class="inline-flex items-center gap-2 bg-white/10 border border-white/20 px-3 py-2 rounded-xl">
          <i class="fas fa-pen-to-square text-emerald-300"></i>
          File Editable: SketchUp (SKP) & AutoCAD (CAD)
        </span>
      </div>
    </div>
  </header>

  <!-- PROBLEM / BENEFIT -->
  <section class="py-16 px-6 bg-white">
    <div class="max-w-5xl mx-auto">
      <div class="text-center mb-12">
        <h2 class="text-3xl font-bold mb-4">Kenapa Paket Ini Kepakai Banget?</h2>
        <div class="h-1 w-20 bg-blue-600 mx-auto"></div>
      </div>

      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="p-6 bg-blue-50 rounded-2xl border border-blue-100 card-hover">
          <div class="w-12 h-12 bg-blue-600 text-white rounded-lg flex items-center justify-center mb-4 text-xl">
            <i class="fas fa-map-marked-alt"></i>
          </div>
          <h3 class="font-bold text-lg mb-2">Baru Beli Tanah</h3>
          <p class="text-gray-600 text-sm">Butuh banyak referensi desain sesuai luas lahan tanpa mulai dari nol.</p>
        </div>

        <div class="p-6 bg-blue-50 rounded-2xl border border-blue-100 card-hover">
          <div class="w-12 h-12 bg-blue-600 text-white rounded-lg flex items-center justify-center mb-4 text-xl">
            <i class="fas fa-calculator"></i>
          </div>
          <h3 class="font-bold text-lg mb-2">Takut Biaya Bengkak</h3>
          <p class="text-gray-600 text-sm">Dengan RAB dan data pendukung, estimasi jadi lebih jelas.</p>
        </div>

        <div class="p-6 bg-blue-50 rounded-2xl border border-blue-100 card-hover">
          <div class="w-12 h-12 bg-blue-600 text-white rounded-lg flex items-center justify-center mb-4 text-xl">
            <i class="fas fa-users-cog"></i>
          </div>
          <h3 class="font-bold text-lg mb-2">Mau Nego ke Tukang</h3>
          <p class="text-gray-600 text-sm">Punya data yang jelas supaya pekerjaan rapi dan sesuai rencana.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- PRODUCT DETAIL -->
  <section id="fitur" class="py-16 px-6 bg-gray-50">
    <div class="max-w-6xl mx-auto">
      <div class="grid lg:grid-cols-2 gap-10 items-center">
        <div class="bg-white rounded-3xl shadow-xl border border-gray-100 overflow-hidden">
          <div class="aspect-video bg-gray-200">
            <!-- GANTI gambar ini kalau mau pakai banner kamu sendiri -->
            <img
              src="https://images.unsplash.com/photo-1503387762-592dea58ef21?auto=format&fit=crop&q=80&w=1400"
              alt="Preview desain rumah"
              class="w-full h-full object-cover"
            />
          </div>
          <div class="p-6 flex items-center justify-between">
            <div class="flex -space-x-2">
              <div class="w-9 h-9 rounded-full bg-blue-600 border-2 border-white flex items-center justify-center text-[11px] text-white font-bold">SKP</div>
              <div class="w-9 h-9 rounded-full bg-red-600 border-2 border-white flex items-center justify-center text-[11px] text-white font-bold">CAD</div>
              <div class="w-9 h-9 rounded-full bg-emerald-600 border-2 border-white flex items-center justify-center text-[11px] text-white font-bold">RAB</div>
            </div>
            <div class="text-sm text-gray-500 font-semibold">300+ File • Berbagai Ukuran</div>
          </div>
        </div>

        <div>
          <h2 class="text-3xl font-extrabold mb-4">Apa yang Kamu Dapatkan?</h2>
          <p class="text-gray-600 mb-6 leading-relaxed">
            Ini adalah <b>produk digital</b> berisi <b>300+ desain bangunan</b> berbagai ukuran yang tersimpan di Google Drive.
            Kamu bisa <b>pilih file sesuai kebutuhan</b> dan <b>edit sendiri</b> karena tersedia format <b>SketchUp (SKP)</b> & <b>AutoCAD (CAD)</b>.
          </p>

          <div class="grid sm:grid-cols-2 gap-4">
            <div class="p-4 bg-white rounded-2xl border border-gray-200">
              <div class="font-bold mb-1"><i class="fas fa-check-circle text-emerald-500 mr-2"></i>Gambar Kerja</div>
              <div class="text-sm text-gray-600">Denah, detail, dan data pendukung (preview/print).</div>
            </div>
            <div class="p-4 bg-white rounded-2xl border border-gray-200">
              <div class="font-bold mb-1"><i class="fas fa-check-circle text-emerald-500 mr-2"></i>Desain 3D</div>
              <div class="text-sm text-gray-600">Bantu visualisasi model sebelum dibangun.</div>
            </div>
            <div class="p-4 bg-white rounded-2xl border border-gray-200">
              <div class="font-bold mb-1"><i class="fas fa-check-circle text-emerald-500 mr-2"></i>RAB</div>
              <div class="text-sm text-gray-600">Estimasi biaya untuk bantu perencanaan.</div>
            </div>
            <div class="p-4 bg-white rounded-2xl border border-gray-200">
              <div class="font-bold mb-1"><i class="fas fa-check-circle text-emerald-500 mr-2"></i>Editable</div>
              <div class="text-sm text-gray-600">SKP & CAD bisa disesuaikan kebutuhan.</div>
            </div>
          </div>

          <div class="mt-6 p-4 bg-white rounded-2xl border border-gray-200 text-sm text-gray-600">
            <i class="fas fa-circle-info text-blue-600 mr-2"></i>
            <b>Catatan:</b> HP bisa untuk lihat preview/dokumen. Untuk edit SKP/CAD lebih nyaman pakai Laptop/PC.
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- BONUS -->
  <section class="py-16 px-6 bg-white">
    <div class="max-w-5xl mx-auto">
      <div class="bg-yellow-50 border-2 border-yellow-200 rounded-3xl p-8 md:p-12">
        <div class="flex items-center justify-between gap-4 flex-wrap">
          <h2 class="text-2xl md:text-3xl font-bold flex items-center gap-3">
            <i class="fas fa-gift text-yellow-600"></i> Bonus Tools & Aset
          </h2>
          <span class="bg-yellow-400 text-yellow-900 font-extrabold px-4 py-2 rounded-xl text-sm">BONUS</span>
        </div>

        <div class="mt-8 grid sm:grid-cols-2 gap-4">
          <div class="flex items-center gap-3 p-4 bg-white rounded-xl border">
            <i class="fas fa-bolt text-blue-600"></i>
            <span class="font-semibold">Autorab Pro + Template Perhitungan</span>
          </div>
          <div class="flex items-center gap-3 p-4 bg-white rounded-xl border">
            <i class="fas fa-couch text-blue-600"></i>
            <span class="font-semibold">Ratusan Aset 3D Interior (SKP)</span>
          </div>
          <div class="flex items-center gap-3 p-4 bg-white rounded-xl border">
            <i class="fas fa-wand-magic-sparkles text-blue-600"></i>
            <span class="font-semibold">Preset Render Lumion</span>
          </div>
          <div class="flex items-center gap-3 p-4 bg-white rounded-xl border">
            <i class="fas fa-folder-open text-blue-600"></i>
            <span class="font-semibold">File Pendukung (Referensi & Learning)</span>
          </div>
        </div>

        <p class="mt-6 text-sm text-yellow-800 italic">
          *File digital untuk tujuan pembelajaran & referensi.
        </p>
      </div>
    </div>
  </section>

  <!-- HOW TO -->
  <section class="py-16 px-6 bg-gray-50">
    <div class="max-w-4xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-12">Cara Pakai Paket Ini</h2>

      <div class="grid md:grid-cols-3 gap-8 relative">
        <div class="flex flex-col items-center">
          <div class="w-16 h-16 bg-blue-600 text-white rounded-full flex items-center justify-center text-2xl font-bold mb-4 shadow-lg z-10">1</div>
          <p class="font-bold mb-2">Akses Google Drive</p>
          <p class="text-gray-500 text-sm">File tersusun rapi berdasarkan kategori/ukuran.</p>
        </div>
        <div class="flex flex-col items-center">
          <div class="w-16 h-16 bg-blue-600 text-white rounded-full flex items-center justify-center text-2xl font-bold mb-4 shadow-lg z-10">2</div>
          <p class="font-bold mb-2">Pilih & Edit (Opsional)</p>
          <p class="text-gray-500 text-sm">Pilih desain yang cocok. Edit via SKP/CAD bila perlu.</p>
        </div>
        <div class="flex flex-col items-center">
          <div class="w-16 h-16 bg-blue-600 text-white rounded-full flex items-center justify-center text-2xl font-bold mb-4 shadow-lg z-10">3</div>
          <p class="font-bold mb-2">Siap Dipakai</p>
          <p class="text-gray-500 text-sm">Gunakan sebagai referensi/pendukung saat pembangunan.</p>
        </div>
        <div class="hidden md:block absolute top-8 left-1/4 right-1/4 h-0.5 bg-blue-200"></div>
      </div>
    </div>
  </section>

  <!-- PRICING / CTA -->
  <section id="beli" class="py-20 px-6">
    <div class="max-w-3xl mx-auto">
      <div class="bg-white rounded-3xl shadow-2xl border-2 border-blue-600 overflow-hidden text-center">
        <div class="bg-blue-600 text-white py-4 px-6">
          <p class="uppercase tracking-widest text-sm font-bold">Harga Spesial</p>
        </div>

        <div class="p-10">
          <p class="text-gray-500 line-through text-xl">Rp 500.000</p>
          <h2 class="text-6xl font-black text-blue-600 my-4">Rp 50.000</h2>
          <p class="text-gray-600 mb-8 font-medium">
            Sekali beli untuk akses database desain + file editable.
          </p>

          <div class="bg-red-50 text-red-700 p-4 rounded-xl text-left mb-8 text-sm">
            <p class="font-bold mb-1"><i class="fas fa-exclamation-triangle mr-2"></i> Catatan Penting:</p>
            <ul class="list-disc ml-5 space-y-1">
              <li>Produk digital (bukan barang fisik).</li>
              <li>Bukan jasa desain custom & tidak termasuk revisi/konsultasi personal.</li>
              <li>300+ desain siap pakai — pilih sesuai kebutuhan, bisa diedit via SKP/CAD.</li>
            </ul>
          </div>

          <div class="grid sm:grid-cols-2 gap-4">
            <a id="shopeeBtn" href="#" target="_blank"
              class="w-full bg-orange-500 hover:bg-orange-600 text-white font-bold py-5 px-8 rounded-2xl text-lg shadow-xl transition-all hover:scale-[1.02]">
              <i class="fas fa-cart-shopping mr-2"></i> Checkout di Shopee
            </a>

            <button id="waBtn"
              class="w-full bg-green-600 hover:bg-green-700 text-white font-bold py-5 px-8 rounded-2xl text-lg shadow-xl transition-all hover:scale-[1.02]">
              <i class="fab fa-whatsapp mr-2"></i> Tanya via WhatsApp
            </button>
          </div>

          <p class="mt-4 text-xs text-gray-400 italic">
            Tips: Checkout via Shopee untuk transaksi aman. Kalau mau tanya dulu, klik WhatsApp.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="py-16 px-6 bg-gray-50">
    <div class="max-w-3xl mx-auto">
      <h2 class="text-3xl font-bold mb-8 text-center">Pertanyaan Umum (FAQ)</h2>

      <div class="space-y-4">
        <div class="faq-item bg-white border border-gray-200 rounded-2xl overflow-hidden cursor-pointer p-4">
          <div class="flex justify-between items-center" onclick="toggleFaq(this)">
            <h4 class="font-bold">Apakah ini barang fisik?</h4>
            <i class="fas fa-chevron-down text-blue-600 transition-transform"></i>
          </div>
          <div class="faq-content text-gray-600 mt-2">
            Tidak. Ini produk digital berupa kumpulan file yang diakses melalui Google Drive.
          </div>
        </div>

        <div class="faq-item bg-white border border-gray-200 rounded-2xl overflow-hidden cursor-pointer p-4">
          <div class="flex justify-between items-center" onclick="toggleFaq(this)">
            <h4 class="font-bold">Apakah harus download semua file?</h4>
            <i class="fas fa-chevron-down text-blue-600 transition-transform"></i>
          </div>
          <div class="faq-content text-gray-600 mt-2">
            Tidak harus. Kamu bisa pilih dan ambil file sesuai kebutuhan.
          </div>
        </div>

        <div class="faq-item bg-white border border-gray-200 rounded-2xl overflow-hidden cursor-pointer p-4">
          <div class="flex justify-between items-center" onclick="toggleFaq(this)">
            <h4 class="font-bold">Apakah bisa edit sesuai ukuran tanah?</h4>
            <i class="fas fa-chevron-down text-blue-600 transition-transform"></i>
          </div>
          <div class="faq-content text-gray-600 mt-2">
            Bisa. Banyak file tersedia dalam format SketchUp (SKP) dan AutoCAD (CAD). Untuk edit disarankan Laptop/PC.
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-gray-900 text-white py-12 px-6 text-center">
    <div class="max-w-4xl mx-auto">
      <h3 class="text-2xl font-bold mb-4">Mulai Bangun Rumah Lebih Pasti</h3>
      <p class="text-gray-400 mb-8">Hemat waktu, dapat referensi banyak, dan lebih percaya diri saat eksekusi.</p>
      <div class="h-px bg-gray-800 w-full mb-8"></div>
      <p class="text-xs text-gray-500">&copy; 2026 Paket Desain Rumah Lengkap. All rights reserved.</p>
    </div>
  </footer>

  <!-- SCRIPTS -->
  <script>
    function toggleFaq(element) {
      const item = element.parentElement;
      item.classList.toggle('active');
    }

    // Link Shopee
    document.getElementById("shopeeBtn").href = SHOPEE_URL;

    // WA
    document.getElementById("waBtn").addEventListener("click", () => {
      const msg = encodeURIComponent(
        "Halo, saya tertarik Paket Desain Rumah Lengkap (Produk Digital). Mohon info cara order & akses Google Drive ya."
      );
      window.open(`https://wa.me/${WA_NUMBER}?text=${msg}`, "_blank");
    });
  </script>

</body>
</html>
