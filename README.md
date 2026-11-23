## Hi there 👋

<!--
**muhsetiawan/muhsetiawan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CV - Muhamad Rehan Setiawan</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: #e8edf5;
    color: #333;
    padding: 30px 10px;
}

.cv {
    max-width: 850px;
    margin: auto;
    background: white;
    display: grid;
    grid-template-columns: 280px 1fr;
    box-shadow: 0 5px 25px rgba(0,0,0,0.15);
}

.sidebar {
    background: #102b4e;
    color: white;
    padding: 30px 22px;
}

.photo {
    width: 145px;
    height: 175px;
    border: 3px solid white;
    margin: 0 auto 25px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #ddd;
    background: #29496d;
    font-size: 14px;
}

.photo img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.sidebar h2 {
    font-size: 17px;
    border-bottom: 2px solid #58b9ff;
    padding-bottom: 8px;
    margin: 25px 0 15px;
}

.sidebar p {
    font-size: 13px;
    line-height: 1.8;
    overflow-wrap: anywhere;
}

.content {
    padding: 40px 30px;
}

.name {
    font-size: 28px;
    color: #102b4e;
    text-transform: uppercase;
    margin-bottom: 8px;
}

.subtitle {
    color: #2788d3;
    font-weight: bold;
    font-size: 14px;
    margin-bottom: 25px;
}

.section {
    margin-bottom: 25px;
}

.section h2 {
    color: #102b4e;
    font-size: 17px;
    border-bottom: 2px solid #2788d3;
    padding-bottom: 8px;
    margin-bottom: 13px;
}

.section p, .section li {
    font-size: 13px;
    line-height: 1.8;
}

.section ul {
    padding-left: 20px;
}

.job, .education {
    margin-bottom: 15px;
}

.job h3, .education h3 {
    color: #205b91;
    font-size: 15px;
    margin-bottom: 5px;
}

footer {
    margin-top: 30px;
    font-size: 12px;
    text-align: right;
    color: #555;
}

@media (max-width: 650px) {
    .cv {
        grid-template-columns: 1fr;
    }

    .content {
        padding: 25px 20px;
    }

    .name {
        font-size: 24px;
    }
}

@media print {
    body {
        padding: 0;
        background: white;
    }

    .cv {
        box-shadow: none;
        max-width: 100%;
    }

    @page {
        size: A4;
        margin: 0;
    }
}
</style>
</head>

<body>

<div class="cv">

    <aside class="sidebar">

        <div class="photo">
            <!-- Ganti foto.jpg dengan foto kamu -->
            <img src="foto.jpg" alt="Foto Rehan"
                 onerror="this.style.display='none'; this.parentElement.innerHTML='FOTO<br>ANDA';">
        </div>

        <h2>DATA PRIBADI</h2>
        <p>
            <b>Nama:</b><br>
            Muhamad Rehan Setiawan
        </p>
        <p>
            <b>Tempat, Tanggal Lahir:</b><br>
            Ciamis, 24 Mei 2009
        </p>
        <p>
            <b>Jenis Kelamin:</b><br>
            Laki-laki
        </p>
        <p>
            <b>Alamat:</b><br>
            Bekasi
        </p>
        <p>
            <b>Agama:</b><br>
            Islam
        </p>
        <p>
            <b>Status:</b><br>
            Pelajar
        </p>

        <h2>KONTAK</h2>
        <p>
            <b>Telepon:</b><br>
            081234567890
        </p>
        <p>
            <b>Email:</b><br>
            reylahhh395@gmail.com
        </p>

        <h2>KEAHLIAN</h2>
        <p>
            • Microsoft Office<br>
            • Microsoft Excel<br>
            • Instalasi Windows<br>
            • Konfigurasi Jaringan<br>
            • Apache2<br>
            • Troubleshooting Komputer
        </p>

    </aside>

    <main class="content">

        <h1 class="name">Muhamad Rehan Setiawan</h1>
        <p class="subtitle">
            STUDENT | TEKNIK KOMPUTER DAN JARINGAN
        </p>

        <section class="section">
            <h2>PROFIL DIRI</h2>
            <p>
                Saya merupakan siswa SMK KARYA GUNA 2 BEKASI
                jurusan Teknik Komputer dan Jaringan (TKJ).
                Memiliki ketertarikan dalam bidang teknologi
                informasi, khususnya instalasi sistem operasi,
                konfigurasi jaringan, dan pengelolaan web server.
                Memiliki pengalaman sebagai staff Building
                Management di PATRAJASA serta kemampuan
                mengoperasikan aplikasi perkantoran.
            </p>
        </section>

        <section class="section">
            <h2>PENDIDIKAN</h2>
            <div class="education">
                <h3>SMK KARYA GUNA 2 BEKASI</h3>
                <p>Teknik Komputer dan Jaringan (TKJ)</p>
                <p>2024 - 2027</p>
            </div>
        </section>

        <section class="section">
            <h2>PENGALAMAN KERJA</h2>
            <div class="job">
                <h3>PATRAJASA</h3>
                <p><b>Staff Building Management</b></p>
                <ul>
                    <li>Memiliki pengalaman sebagai staff di bagian Building Management.</li>
                    <li>Mendapatkan pengalaman di lingkungan kerja profesional.</li>
                </ul>
            </div>
        </section>

        <section class="section">
            <h2>KEMAMPUAN TEKNIS</h2>
            <ul>
                <li>Instalasi dan konfigurasi Windows.</li>
                <li>Konfigurasi jaringan komputer.</li>
                <li>Instalasi dan konfigurasi web server Apache2.</li>
                <li>Penggunaan Microsoft Word dan Excel.</li>
                <li>Troubleshooting komputer.</li>
            </ul>
        </section>

        <section class="section">
            <h2>PENGALAMAN ORGANISASI</h2>
            <p>Belum dicantumkan.</p>
        </section>

        <section class="section">
            <h2>PRESTASI & SERTIFIKAT</h2>
            <p>Belum dicantumkan.</p>
        </section>

        <footer>
            Bekasi, 23 November 2026
            <br><br><br>
            <b>Muhamad Rehan Setiawan</b>
        </footer>

    </main>

</div>

</body>
</html>
