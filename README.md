<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>CV Eka Novi Kartika</title>
  <style>
    :root {
      --primary: #2c3e50;
      --accent: #3498db;
      --light-bg: #ecf0f1;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background-color: var(--light-bg);
      color: #2c3e50;
    }

    .container {
      max-width: 900px;
      margin: 40px auto;
      background-color: white;
      padding: 30px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
      border-radius: 12px;
    }

    .header {
      text-align: center;
      border-bottom: 2px solid var(--accent);
      padding-bottom: 20px;
    }

    .header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 10px;
      border: 3px solid var(--accent);
    }

    h1 {
      margin: 0;
      font-size: 26px;
    }

    h2 {
      color: var(--primary);
      border-bottom: 2px solid #ddd;
      padding-bottom: 5px;
      margin-top: 40px;
    }

    .section p {
      margin: 6px 0;
    }

    .flex-wrap {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 10px;
    }

    .card {
      background-color: #f9f9f9;
      border-left: 4px solid var(--accent);
      padding: 10px 15px;
      border-radius: 6px;
      flex: 1 1 40%;
    }

    .skills {
      margin-top: 20px;
    }

    .skill-bar {
      background: #ddd;
      height: 10px;
      border-radius: 5px;
      margin-top: 5px;
      overflow: hidden;
    }

    .skill-fill {
      height: 100%;
      background: var(--accent);
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <img src="profile.jpg" alt="Foto Profil" />
      <h1>Eka Novi Kartika</h1>
      <p>Mahasiswi Sistem Informasi • Admin di Ekka Boutique</p>
    </div>

    <div class="section">
      <h2>📌 Data Diri</h2>
      <p>Tempat, Tanggal Lahir: Subang, 03 Oktober 2005</p>
      <p>Jenis Kelamin: Perempuan</p>
      <p>Status: Belum menikah</p>
      <p>Kewarganegaraan: Indonesia</p>
    </div>

    <div class="section">
      <h2>📞 Kontak</h2>
      <p>Telepon: +62 821 9495 3329</p>
      <p>Email: kanzakim534@gmail.com</p>
      <p>Alamat: Cikampek, Jl. SMU PGRI No.46, Jomin Bar, Karawang</p>
    </div>

    <div class="section">
      <h2>📚 Pendidikan</h2>
      <div class="flex-wrap">
        <div class="card">S1 Sistem Informasi – Bina Sarana Informatika (2023 – sekarang)</div>
        <div class="card">SMAS Al-Muhajirin Purwakarta (2020)</div>
        <div class="card">SMPS Nihayatul Amal Karawang (2017)</div>
        <div class="card">SDS Tarbiyatul Wildan Karawang (2012)</div>
      </div>
    </div>

    <div class="section">
      <h2>🎤 Seminar</h2>
      <div class="flex-wrap">
        <div class="card">Entrepreneur UML & ERD Basis Data (65 - Cukup Baik)</div>
        <div class="card">Sertifikasi Guru Qur'an Metode Ummi (2023-2025)</div>
      </div>
    </div>

    <div class="section">
      <h2>💼 Pengalaman Kerja</h2>
      <p>Ekka Boutique – Admin (2023 – sekarang)</p>
    </div>

    <div class="section">
      <h2>🧠 Tentang Saya</h2>
      <p>Saya bertanggung jawab, pekerja keras, dan antusias belajar hal baru. Saya siap berkembang dan memberikan kontribusi terbaik untuk masa depan saya.</p>
    </div>

    <div class="section">
      <h2>🔧 Keterampilan</h2>
      <div class="skills">
        <p>Microsoft Word</p>
        <div class="skill-bar"><div class="skill-fill" style="width: 85%"></div></div>
        <p>Public Speaking</p>
        <div class="skill-bar"><div class="skill-fill" style="width: 80%"></div></div>
        <p>Desain Canva</p>
        <div class="skill-bar"><div class="skill-fill" style="width: 90%"></div></div>
      </div>
    </div>
  </div>
</body>
</html>
