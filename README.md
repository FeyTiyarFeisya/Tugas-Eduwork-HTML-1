# Tugas-Eduwork-HTML-1
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Saya</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #f4f4f4;
            color: #333;
        }
        /* Section 1: Menu */
        .menu {
            background: #007BFF;
            color: white;
            padding: 15px;
            text-align: center;
        }
        .menu a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        /* Section 2: Judul dan Gambar */
        .hero {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 50px;
            background: #fff;
        }
        .hero .text {
            flex: 1;
        }
        .hero img {
            width: 300px;
            height: auto;
            border-radius: 10px;
        }
        /* Section 3: Biodata */
        .biodata {
            background: #fff;
            padding: 40px;
            text-align: center;
        }
        .biodata h2 {
            margin-bottom: 20px;
        }
        .biodata-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }
        .biodata-box {
            background: #007BFF;
            color: white;
            padding: 20px;
            border-radius: 10px;
        }
        /* Section 4: Portofolio */
        .portfolio {
            padding: 40px;
            text-align: center;
        }
        .portfolio h2 {
            margin-bottom: 20px;
        }
        .portfolio-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .portfolio-item {
            width: 30%;
            background: white;
            padding: 20px;
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>

    <!-- Section 1: Menu -->
    <nav class="menu">
        <a href="#">Home</a>
        <a href="#">Biodata</a>
        <a href="#">Portofolio</a>
        <a href="#">Kontak</a>
    </nav>

    <!-- Section 2: Judul di kiri, Gambar di kanan -->
    <section class="hero">
        <div class="text">
            <h1>Selamat Datang di Profil Saya</h1>
            <p>Saya adalah seorang web developer yang berpengalaman dalam HTML, CSS, dan JavaScript.</p>
        </div>
        <img src="https://via.placeholder.com/300" alt="Foto Profil">
    </section>

    <!-- Section 3: Biodata dengan 6 Box -->
    <section class="biodata">
        <h2>Biodata</h2>
        <div class="biodata-container">
            <div class="biodata-box">Nama: Purwo Estiarto</div>
            <div class="biodata-box">Umur: 37 Tahun</div>
            <div class="biodata-box">Profesi: Web Developer</div>
            <div class="biodata-box">Alamat: Jakarta, Indonesia</div>
            <div class="biodata-box">Email: purwo.estiarto@gmail.com</div>
            <div class="biodata-box">Telepon: +62 8111215758</div>
        </div>
    </section>

    <!-- Section 4: Portofolio -->
    <section class="portfolio">
        <h2>Portofolio</h2>
        <div class="portfolio-container">
            <div class="portfolio-item">
                <h3>Project 1</h3>
                <p>Website Company Profile untuk perusahaan teknologi.</p>
            </div>
            <div class="portfolio-item">
                <h3>Project 2</h3>
                <p>Website E-commerce untuk toko online fashion.</p>
            </div>
            <div class="portfolio-item">
                <h3>Project 3</h3>
                <p>Aplikasi Web untuk manajemen tugas tim.</p>
            </div>
        </div>
    </section>

</body>
</html>
