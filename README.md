<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Irham & Gita Wedding Invitation</title>

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;600;700&family=Montserrat:wght@300;400;500;600&family=Playfair+Display:wght@400;600&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background: #F7F5F2;
      color: #2C2C2C;
      scroll-behavior: smooth;
    }

    section {
      padding: 80px 20px;
      text-align: center;
      max-width: 900px;
      margin: auto;
      animation: fade 1s ease;
    }

    h1, h2, h3 {
      font-family: 'Cormorant Garamond', serif;
      color: #2C2C2C;
    }

    .fade { animation: fade 2s ease; }
    @keyframes fade { from {opacity: 0;} to {opacity: 1;} }

    .slide-up { animation: slideUp 1.2s ease; }
    @keyframes slideUp { from {opacity: 0; transform: translateY(20px);} to {opacity: 1; transform: translateY(0);} }

    .zoom { animation: zoomIn 1.2s ease; }
    @keyframes zoomIn { from {transform: scale(0.94); opacity: 0;} to {transform: scale(1); opacity: 1;} }

    .card {
      background: #EDEAE6;
      padding: 25px;
      border-radius: 14px;
      margin: 20px auto;
      width: 80%;
      animation: slideUp 1s ease;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 15px;
      padding: 20px;
    }

    .gallery img {
      width: 100%;
      border-radius: 6px;
      animation: fade 1s ease;
    }

    .btn {
      display: inline-block;
      background: #2C2C2C;
      padding: 14px 28px;
      color: white;
      border-radius: 8px;
      margin-top: 20px;
      transition: 0.3s;
      font-size: 18px;
    }

    .btn:hover {
      background: #3b3b3b;
    }

    .pulse {
      animation: pulse 2s infinite ease-in-out;
    }
    @keyframes pulse {
      0% {transform: scale(1);}
      50% {transform: scale(1.03);}
      100% {transform: scale(1);}
    }

    iframe {
      width: 90%;
      height: 360px;
      border-radius: 10px;
    }
  </style>
</head>

<body>

<!-- BACKSOUND -->
<audio autoplay loop hidden>
  <source src="URL_BACKSOUND.mp3" type="audio/mp3">
</audio>

<!-- 1. COVER PAGE -->
<section id="cover" style="background:#F7F5F2;">
  <h1 style="font-size:70px; margin-bottom:10px;" class="fade">A Timeless Promise of Irham & Gita</h1>
  <div style="width:160px; height:1px; background:#2C2C2C; margin:20px auto;"></div>
</section>

<!-- 2. OPENING INVITATION -->
<section class="slide-up">
  <h2 style="font-family:'Playfair Display'; font-size:36px;">
    Dengan penuh syukur
  </h2>
  <p style="font-size:22px; max-width:700px; margin:auto;">
    kami mengundang Bapak/Ibu/Saudara/i untuk hadir dan memberi doa terbaik pada hari pernikahan kami
  </p>
</section>

<!-- 3. COUPLE SECTION -->
<section class="zoom">
  <img src="URL_FOTO_COUPE" style="width:85%; border-radius:12px; margin-bottom:25px;">
  <h2 style="font-family:'Playfair Display'; font-size:46px;">
    Irham Purnama & Anggitasari S
  </h2>
</section>

<!-- 4. PREWEDDING VIDEO -->
<section class="fade">
  <iframe src="YOUTUBE_URL" frameborder="0" allowfullscreen></iframe>
</section>

<!-- 5. COUNTDOWN -->
<section class="fade">
  <h1 style="font-size:60px;">07 DESEMBER 2025, Saturday</h1>
  <p style="font-size:22px;">Save the Date</p>
</section>

<!-- 6. AGENDA -->
<section>
  <div class="card">
    <h3>Akad Nikah</h3>
    <p>Minggu, 7 Desember 2025<br>08.00 WIB – selesai<br>Lokasi: (isi lokasi)</p>
  </div>
  <div class="card">
    <h3>Resepsi</h3>
    <p>Minggu, 7 Desember 2025<br>09.00 WIB – selesai<br>Lokasi: (isi lokasi)</p>
  </div>
</section>

<!-- 7. OUR STORY -->
<section class="fade">
  <h2 style="font-size:38px;">Our Story</h2>

  <p style="font-size:22px;">
    <b>Perkenalan:</b><br>
    (isi cerita)
    <br><br>

    <b>Awal Hubungan:</b><br>
    (isi cerita)
    <br><br>

    <b>Keyakinan:</b><br>
    (isi cerita)
  </p>
</section>

<!-- 8. GALLERY -->
<section>
  <h2 style="font-size:38px;">Gallery</h2>
  <div class="gallery">
    <img src="URL_FOTO_1">
    <img src="URL_FOTO_2">
    <img src="URL_FOTO_3">
    <img src="URL_FOTO_4">
    <img src="URL_FOTO_5">
    <img src="URL_FOTO_6">
    <img src="URL_FOTO_7">
    <img src="URL_FOTO_8">
    <img src="URL_FOTO_9">
  </div>
</section>

<!-- 9. MAP -->
<section class="fade">
  <h2 style="font-size:38px;">Lokasi</h2>
  <iframe src="GOOGLE_MAPS_EMBED_URL" allowfullscreen loading="lazy"></iframe>
</section>

<!-- 10. RSVP -->
<section>
  <h2 style="font-size:38px;">RSVP</h2>
  <form style="max-width:500px; margin:auto; text-align:left;">
    <label>Nama</label>
    <input type="text" style="width:100%; padding:12px; margin-bottom:12px; border-radius:6px; border:1px solid #ccc;">
    
    <label>Kehadiran</label>
    <select style="width:100%; padding:12px; margin-bottom:12px; border-radius:6px; border:1px solid #ccc;">
      <option>Hadir</option>
      <option>Tidak Hadir</option>
    </select>

    <label>Pesan / Doa</label>
    <textarea style="width:100%; padding:12px; height:100px; border-radius:6px; border:1px solid #ccc;"></textarea>

    <br><br>
    <button class="btn">Kirim</button>
  </form>
</section>

<!-- 11. DIGITAL GIFT -->
<section style="background:#D9CBB326;" class="fade">
  <h2 style="font-size:38px;">Digital Envelope</h2>
  <p style="font-size:22px;">Bagi yang ingin berbagi, dapat melalui rekening / e-wallet berikut:</p>

  <p style="font-size:20px; margin-top:20px;">
    <b>Bank / E-wallet:</b><br>
    (Isi nomor rekening atau QR)
  </p>

  <a class="btn pulse">Kirim Tanda Kasih</a>
</section>

<!-- 12. CLOSING -->
<section class="fade">
  <p style="font-size:24px;">
    Terima kasih atas doa dan kehadiran Anda, yang menyempurnakan hari bahagia kami.
  </p>
</section>

</body>
</html>
