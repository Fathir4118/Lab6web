# Lab6web

# Praktikum Modul Pemrograman Web 1
Nama : Muhammad Fathir Nurcholis

NIM : 312410287

KELAS : TI.24.A.4

![gambar](https://github.com/Abcdeflahhh/LAB6WEBPW/blob/77b2e82f6a6995ddd9c72ec8631f4db12ee9df95/image/Screenshot%202025-10-30%20141724.png)

#1
```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>MyWebsite Luxury Edition</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  <style>
    body {
      background-color: #0a0a0a;
      color: #e5e5e5;
      font-family: 'Poppins', sans-serif;
    }

    /* Navbar */
    .navbar {
      background: linear-gradient(90deg, #000000, #1a1a1a, #000000);
      border-bottom: 1px solid #d4af37;
      box-shadow: 0 3px 15px rgba(212, 175, 55, 0.2);
    }
    .navbar-brand {
      color: #d4af37 !important;
      font-weight: 600;
      font-size: 1.3rem;
      letter-spacing: 1px;
    }
    .nav-link {
      color: #e5e5e5 !important;
      transition: 0.3s;
    }
    .nav-link:hover {
      color: #d4af37 !important;
    }

    /* Card general */
    .card {
      background-color: #141414;
      border: 1px solid #2a2a2a;
      border-radius: 15px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.5);
      transition: all 0.3s ease;
    }
    .card:hover {
      transform: translateY(-6px);
      border-color: #d4af37;
      box-shadow: 0 0 25px rgba(212, 175, 55, 0.3);
    }

    /* Card header */
    .card-header {
      background: linear-gradient(90deg, #2a2a2a, #1a1a1a);
      color: #d4af37;
      border-top-left-radius: 15px;
      border-top-right-radius: 15px;
      font-weight: 500;
      border-bottom: 1px solid #d4af37;
    }

    /* Titles */
    h3.card-title, h5.box-title {
      color: #d4af37;
      font-weight: 600;
    }

    /* Button gold */
    .btn-gold {
      background: linear-gradient(90deg, #d4af37, #c5a028);
      color: #000;
      font-weight: 500;
      border: none;
      border-radius: 25px;
      transition: 0.3s;
    }
    .btn-gold:hover {
      background: linear-gradient(90deg, #e8c55c, #d4af37);
      color: #000;
      box-shadow: 0 0 15px rgba(212,175,55,0.6);
    }

    /* Footer */
    footer {
      background: #000000;
      color: #b3b3b3;
      text-align: center;
      padding: 20px 0;
      border-top: 1px solid #2a2a2a;
      margin-top: 60px;
    }
    footer span {
      color: #d4af37;
      font-weight: 500;
    }

    /* Smooth hover effect for texts */
    .card-body p {
      color: #ccc;
    }
  </style>
</head>
<body>

  <!-- NAVBAR -->
  <nav class="navbar navbar-expand-lg navbar-dark py-3">
    <div class="container">
      <a class="navbar-brand" href="#">MyWebsite ✨</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="navbarNav" class="collapse navbar-collapse">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Gallery</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- MAIN CONTENT + SIDEBAR -->
  <div class="container my-5">
    <div class="row g-4">
      <!-- MAIN CONTENT -->
      <div class="col-md-8">
        <div class="card">
          <div class="card-body">
            <h3 class="card-title mb-3">Selamat Datang di Dunia Mewah</h3>
            <p class="card-text">Nikmati tampilan website dengan gaya elegan dan modern, menggunakan kombinasi warna emas dan hitam yang memancarkan kesan eksklusif dan profesional. Desain ini cocok untuk brand fashion, bisnis premium, atau portofolio berkelas.</p>
            <a href="#" class="btn btn-gold px-4 mt-3">Jelajahi Sekarang</a>
          </div>
        </div>
      </div>

      <!-- SIDEBAR -->
      <div class="col-md-4">
        <div class="card">
          <div class="card-header">Informasi Tambahan</div>
          <div class="card-body">
            <p>Gunakan sidebar ini untuk promo, link sosial media, atau pengumuman spesial.</p>
            <ul class="list-unstyled mb-0">
              <li><a href="#" class="text-decoration-none text-light">› Tentang Kami</a></li>
              <li><a href="#" class="text-decoration-none text-light">› Layanan</a></li>
              <li><a href="#" class="text-decoration-none text-light">› Dukungan</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <!-- TIGA BOX -->
    <div class="row mt-5 text-center g-4">
      <div class="col-md-4">
        <div class="card py-4">
          <div class="card-body">
            <h5 class="box-title">💫 Kualitas Premium</h5>
            <p class="card-text">Desain profesional dengan warna emas berkilau dan gaya eksklusif.</p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card py-4">
          <div class="card-body">
            <h5 class="box-title">⚙️ Teknologi Modern</h5>
            <p class="card-text">Dibangun menggunakan Bootstrap 5 dengan performa optimal dan ringan.</p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card py-4">
          <div class="card-body">
            <h5 class="box-title">🌍 Desain Responsif</h5>
            <p class="card-text">Tampil elegan di semua perangkat — dari smartphone hingga laptop.</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- FOOTER -->
  <footer>
    <p>© 2025 <span>MyWebsite Luxury Edition</span>. All Rights Reserved.</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

#OUTPUT HASIL 

![gambar](https://github.com/Fathir4118/Lab6web/blob/main/Image/IMG_20251106_150213.jpg)

#2
```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Form Praktikum 5 - Elegant Style</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  <style>
    body {
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      font-family: 'Poppins', sans-serif;
      color: #f1f1f1;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .card {
      background-color: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 215, 0, 0.2);
      border-radius: 20px;
      backdrop-filter: blur(12px);
      box-shadow: 0 8px 25px rgba(0,0,0,0.5);
      color: #fff;
      transition: all 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 30px rgba(212,175,55,0.3);
      border-color: rgba(255, 215, 0, 0.4);
    }

    .card-header {
      background: linear-gradient(90deg, #d4af37, #c59f2b);
      color: #000;
      border-top-left-radius: 20px;
      border-top-right-radius: 20px;
      font-weight: 600;
      text-shadow: 0 0 5px rgba(255,255,255,0.6);
    }

    .form-control {
      background-color: rgba(255,255,255,0.1);
      border: 1px solid rgba(255,255,255,0.3);
      color: #fff;
      transition: 0.3s;
      border-radius: 10px;
    }

    .form-control::placeholder {
      color: #aaa;
    }

    .form-control:focus {
      background-color: rgba(255,255,255,0.15);
      border-color: #d4af37;
      box-shadow: 0 0 10px rgba(212,175,55,0.6);
      color: #fff;
    }

    label {
      font-weight: 500;
    }

    .btn-gold {
      background: linear-gradient(90deg, #d4af37, #c59f2b);
      color: #000;
      border: none;
      border-radius: 30px;
      font-weight: 600;
      letter-spacing: 0.5px;
      transition: 0.3s;
    }

    .btn-gold:hover {
      background: linear-gradient(90deg, #e4c157, #d4af37);
      box-shadow: 0 0 15px rgba(212,175,55,0.6);
      transform: translateY(-2px);
    }

    h4 {
      letter-spacing: 1px;
    }
  </style>
</head>
<body>

  <div class="container py-5">
    <div class="row justify-content-center">
      <div class="col-md-6">
        <div class="card p-0 shadow-lg">
          <div class="card-header text-center py-3">
            <h4>💫 Form Input Data Elegan</h4>
          </div>
          <div class="card-body p-4">
            <form>
              <div class="mb-3">
                <label for="nama" class="form-label">Nama Lengkap</label>
                <input type="text" id="nama" class="form-control" placeholder="Masukkan nama Anda">
              </div>

              <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" id="email" class="form-control" placeholder="nama@email.com">
              </div>

              <div class="mb-3">
                <label for="pesan" class="form-label">Pesan</label>
                <textarea id="pesan" class="form-control" rows="3" placeholder="Tulis pesan Anda"></textarea>
              </div>

              <button type="submit" class="btn btn-gold w-100 py-2 mt-2">Kirim Sekarang ✉️</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>

</body>
</html>
```

#OUTPUT HASIL

![gambar](https://github.com/Fathir4118/Lab6web/blob/main/Image/Screenshot_20251106_150246.jpg)

#3
```
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Portfolio Muhammad Fathir Nurcholis ✨</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: #0a0a0a;
      color: #eaeaea;
      font-family: 'Poppins', sans-serif;
      scroll-behavior: smooth;
    }

    /* NAVBAR */
    .navbar {
      background: linear-gradient(90deg, #000, #1a1a1a, #000);
      border-bottom: 1px solid #d4af37;
      box-shadow: 0 3px 15px rgba(212, 175, 55, 0.2);
    }
    .navbar-brand {
      color: #d4af37 !important;
      font-weight: 600;
      letter-spacing: 1px;
    }
    .nav-link {
      color: #eaeaea !important;
      transition: 0.3s;
    }
    .nav-link:hover {
      color: #d4af37 !important;
    }

    /* SECTION TITLE */
    h2, h3 {
      color: #d4af37;
      font-weight: 600;
      letter-spacing: 1px;
    }

    /* ABOUT SECTION */
    #tentang img {
      border: 3px solid #d4af37;
      box-shadow: 0 0 20px rgba(212,175,55,0.3);
      transition: transform 0.3s;
    }
    #tentang img:hover {
      transform: scale(1.05);
    }
    #tentang p {
      font-size: 1.05rem;
      color: #cfcfcf;
    }

    /* PORTFOLIO CARDS */
    .card {
      background-color: #141414;
      border: 1px solid #2a2a2a;
      border-radius: 15px;
      transition: 0.3s;
      box-shadow: 0 5px 15px rgba(0,0,0,0.6);
    }
    .card:hover {
      transform: translateY(-6px);
      border-color: #d4af37;
      box-shadow: 0 0 25px rgba(212,175,55,0.3);
    }
    .card-title {
      color: #d4af37;
      font-weight: 600;
    }
    .card-text {
      color: #ccc;
    }

    /* FOOTER */
    footer {
      background: #000;
      color: #bdbdbd;
      border-top: 1px solid #2a2a2a;
      box-shadow: 0 -2px 10px rgba(0,0,0,0.6);
    }
    footer span {
      color: #d4af37;
    }

    /* BUTTON GOLD */
    .btn-gold {
      background: linear-gradient(90deg, #d4af37, #b8901e);
      color: #000;
      border: none;
      border-radius: 25px;
      font-weight: 500;
      padding: 10px 20px;
      transition: all 0.3s;
    }
    .btn-gold:hover {
      background: linear-gradient(90deg, #e7c65a, #d4af37);
      box-shadow: 0 0 15px rgba(212,175,55,0.5);
    }

    /* ANIMATION */
    .fade-in {
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.8s ease-out, transform 0.8s ease-out;
    }
    .fade-in.visible {
      opacity: 1;
      transform: translateY(0);
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">Fathir <span style="color:#fff;">Portfolio</span></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="navMenu" class="collapse navbar-collapse">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#tentang">Tentang</a></li>
          <li class="nav-item"><a class="nav-link" href="#portfolio">Portfolio</a></li>
          <li class="nav-item"><a class="nav-link" href="#kontak">Kontak</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Tentang Saya -->
  <section id="tentang" class="container py-5 mt-5 fade-in">
    <div class="row align-items-center">
      <div class="col-md-4 text-center mb-4 mb-md-0">
        <img src="https://via.placeholder.com/250" class="img-fluid rounded-circle" alt="Foto Fathir">
      </div>
      <div class="col-md-8">
        <h2>Muhammad Fathir Nurcholis (Felix)</h2>
        <p>Halo! Aku <span style="color:#d4af37;">Fathir</span>, seorang mahasiswa yang tertarik di dunia <b>Menulis</b>. Aku fokus pada <b>Karya Novel</b> dan suka bikin sebuah tulisan/kisah yang menyentuh hati para pembaca. 
        Aku percaya menulis bukan cuma soal tulisan baku — tapi juga soal rasa bagi para pembaca.</p>
        <a href="#portfolio" class="btn btn-gold mt-3">Lihat Karya ✨</a>
      </div>
    </div>
  </section>

  <!-- Portfolio -->
  <section id="portfolio" class="container py-5 fade-in">
    <h3 class="text-center mb-5">💼 Portfolio Saya</h3>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card h-100">
          <img src="https://via.placeholder.com/350x200" class="card-img-top" alt="Proyek 1">
          <div class="card-body">
            <h5 class="card-title">Proyek 1</h5>
            <p class="card-text">Psikolog tanpa gelar.</p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card h-100">
          <img src="https://via.placeholder.com/350x200" class="card-img-top" alt="Proyek 2">
          <div class="card-body">
            <h5 class="card-title">Proyek 2</h5>
            <p class="card-text">yang masih bersinggah di hati.</p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card h-100">
          <img src="https://via.placeholder.com/350x200" class="card-img-top" alt="Proyek 3">
          <div class="card-body">
            <h5 class="card-title">Proyek 3</h5>
            <p class="card-text">The thing.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Kontak -->
  <section id="kontak" class="container py-5 fade-in">
    <h3 class="text-center mb-4">📩 Hubungi Saya</h3>
    <div class="row justify-content-center">
      <div class="col-md-6">
        <form>
          <div class="mb-3">
            <label class="form-label">Nama</label>
            <input type="text" class="form-control" placeholder="Masukkan nama Anda">
          </div>
          <div class="mb-3">
            <label class="form-label">Email</label>
            <input type="email" class="form-control" placeholder="nama@email.com">
          </div>
          <div class="mb-3">
            <label class="form-label">Pesan</label>
            <textarea class="form-control" rows="3" placeholder="Tulis pesan Anda"></textarea>
          </div>
          <button type="submit" class="btn btn-gold w-100 mt-2">Kirim Pesan 💌</button>
        </form>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center py-4 mt-4">
    <p>&copy; 2025 <span>fathir</span> | Dibuat dengan ❤️ & Bootstrap</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script>
    // animasi muncul saat scroll
    const faders = document.querySelectorAll('.fade-in');
    const appearOnScroll = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) entry.target.classList.add('visible');
      });
    });
    faders.forEach(fade => appearOnScroll.observe(fade));
  </script>
</body>
</html>
```

#OUTPUT HASIL

![gambar](https://github.com/Abcdeflahhh/LAB6WEBPW/blob/79f8e392ff837491278c4b2606f482f19446963d/image/Screenshot%202025-10-30%20143807.png)
