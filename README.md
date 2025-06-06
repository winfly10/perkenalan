<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Perkenalan Diri - Hammam</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }

    .container {
      max-width: 900px;
      margin: 40px auto;
      background-color: #fff;
      padding: 40px;
      border-radius: 12px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    }

    h1, h2 {
      color: #2c3e50;
    }

    p {
      color: #555;
      line-height: 1.6;
    }

    .highlight {
      color: #16a085;
      font-weight: bold;
    }

    .socials a {
      margin-right: 10px;
      text-decoration: none;
      color: #3498db;
    }

    .section {
      margin-bottom: 40px;
    }

    .cta-button {
      display: inline-block;
      background-color: #3498db;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      margin-top: 20px;
    }

    .cta-button:hover {
      background-color: #2980b9;
    }

    .fun-fact {
      background-color: #f9f9f9;
      padding: 10px;
      border-left: 4px solid #16a085;
      margin-top: 20px;
    }

    #about img.profile {
      max-width: 200px;
      border-radius: 50%;
      margin-top: 20px;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }

    .photo-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }

    .photo-gallery img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }

    .photo-gallery img:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>

  <div class="container">
    <!-- Landing Page / Hero Section -->
    <div class="section" id="landing">
      <h1>Halo, saya Hammam 👋</h1>
      <p>Saya seorang <span class="highlight">Mahasiswa Teknik Listrik Industri</span> yang sedang fokus belajar dan berkembang di bidang kelistrikan. Passion saya di dunia teknik dan filsafat membuat saya selalu berusaha memahami dunia dengan cara yang lebih dalam.</p>
      <p>"Membangun masa depan lewat listrik dan logika." 💡</p>
      <a href="#about" class="cta-button">Kenalan Lebih Lanjut</a>
    </div>

    <!-- About Me Section -->
    <div class="section" id="about">
      <h2>About Me</h2>
      <p>Halo! Nama saya <strong>Hammam</strong>, mahasiswa <strong>Teknik Listrik Industri</strong> di Universitas Diponegoro. Saat ini, saya sangat fokus untuk mempelajari dan menguasai berbagai konsep kelistrikan yang nantinya bisa diterapkan di dunia industri. Saya tidak hanya belajar teori, tetapi juga berusaha mengaplikasikan ilmu yang dipelajari dalam pengalaman nyata, seperti yang saya lakukan di bengkel motor keluarga.</p>
      <p>Selain kuliah, saya juga memiliki ketertarikan yang besar pada <strong>filsafat</strong>. Saya sangat tertarik dengan epistemologi, cara orang berpikir, dan bagaimana kita dapat memahami dunia. Saya percaya bahwa filsafat dapat membantu saya untuk lebih bijak dalam menghadapi berbagai tantangan hidup, baik dalam kehidupan pribadi maupun profesional.</p>
      <p>Saya adalah pribadi yang <strong>tekun</strong> dan <strong>mandiri</strong>. Saya tidak mudah menyerah saat menghadapi masalah dan selalu berusaha mencari solusi. Saya juga tidak suka terjebak dalam zona nyaman, jadi saya terus berusaha berkembang dan mencari peluang baru. Itulah mengapa saya lebih memilih untuk fokus pada apa yang sedang saya kerjakan, ketimbang terlibat dalam organisasi besar yang dapat mengganggu fokus saya.</p>
      <p>Selain itu, saya juga memiliki hobi yang membuat hidup lebih seru, yaitu <strong>mendaki gunung</strong>. Mendaki gunung bukan hanya soal fisik, tetapi juga soal mental. Saya merasa lebih dekat dengan alam dan mendapatkan banyak pelajaran hidup dari setiap perjalanan saya. Jika Anda pernah mendaki, pasti tahu bagaimana rasanya.</p>
      
      <h2 style="text-align: center;">Ini bukan galeri model, cuma potongan hidup saya yang kadang serius, kadang ngaco, tapi selalu jujur. Selamat menilai sendiri </h2>
      <!-- Galeri Foto -->
      <div class="photo-gallery">
        <img src="WhatsApp Image 2025-04-22 at 19.53.08_d2c296f9.jpg" alt="Foto  1">
        <img src="WhatsApp Image 2025-04-22 at 19.53.07_59304ba5.jpg" alt="Foto  2">
        <img src="WhatsApp Image 2025-04-22 at 19.53.07_31d98843.jpg" alt="Foto  3">
        <img src="WhatsApp Image 2025-04-22 at 20.19.01_02990815.jpg" alt="Foto  4">
      </div>

      <!-- Foto Profil -->
      <img src="WhatsApp Image 2025-04-22 at 19.53.08_e2f1eb58.jpg" alt="Foto Hammam" class="profile">
    </div>

    <!-- Skills & Interests Section -->
    <div class="section" id="skills">
      <h2>Apa yang Saya Lakukan?</h2>
      <p>Saya memiliki berbagai keahlian yang mendukung studi dan minat saya di bidang teknik serta teknologi:</p>
      <ul>
        <li><strong>Keahlian Teknis:</strong> Sistem kelistrikan, Pengoperasian alat ukur listrik, Pemrograman dasar (Arduino, Mikrocontroller)</li>
        <li><strong>Tools yang Dikuasai:</strong> AutoCAD, Fusion 360, Eagle, Microsoft Office</li>
        <li><strong>Minat:</strong> Mikrocontroller, Pengembangan sistem kelistrikan, Desain teknik, Filsafat Epistemologi</li>
      </ul>
    </div>

    <!-- Contact Section -->
    <div class="section" id="contact">
      <h2>Hubungi Saya</h2>
      <p>Untuk pertanyaan, kerja sama, atau sekadar ngobrol-ngobrol, Anda bisa menghubungi saya melalui cara-cara berikut:</p>
      <div class="socials">
        <a href="mailto:fathyhammam106@email.com">Email</a>
        <a href="http://wa.me//6282134458051">WhatsApp</a>
        <a href="https://www.instagram.com/fathy.hammam?igsh=MXA5MzJtdXBneG9qcg==">Instagram</a>
      </div>
    </div>

    <!-- Thank You Section -->
    <div class="section" id="thankyou">
      <h2>Terima Kasih!</h2>
      <p>Terima kasih telah meluangkan waktu untuk mengenal saya. Semoga kita bisa saling berbagi pengetahuan dan pengalaman di masa depan. Jangan ragu untuk menghubungi saya jika ada hal yang ingin dibicarakan!</p>
    </div>

  </div>

</body>
</html>
