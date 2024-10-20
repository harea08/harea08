<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Halaman pribadi yang menampilkan informasi umum dan karya saya.">
    <title>Halaman Pribadi</title>
    <style>
        body {
            font-family: 'Times New Roman', serif;
            background-color: #f9f8f6;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #8b7d6b;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            font-size: 2.5em;
            margin: 0;
        }
        nav {
            margin: 20px;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #8b7d6b;
            font-weight: bold;
        }
        .content {
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        .content h2 {
            color: #8b7d6b;
            font-size: 2em;
        }
        .content p {
            line-height: 1.6;
        }
        .works {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .work-item {
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 15px;
            width: 30%;
            margin: 10px;
            text-align: center;
        }
        footer {
            background-color: #8b7d6b;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Halaman Pribadi</h1>
    <p>Klasik, Modern, & Elegan</p>
</header>

<nav>
    <a href="#about">Tentang Saya</a>
    <a href="#works">Karya</a>
    <a href="#contact">Kontak</a>
</nav>

<section class="content" id="about">
    <h2>Tentang Saya</h2>
    <p>Selamat datang di halaman pribadi saya. Di sini, saya akan berbagi sedikit tentang siapa saya dan perjalanan saya. Saya mengusung tema klasik modern, berbaur dengan konsep old money, yang menggambarkan gaya hidup sederhana namun berkelas.</p>
</section>

<section class="content" id="works">
    <h2>Karya</h2>
    <div class="works">
        <div class="work-item">
            <h3>Judul Karya 1</h3>
            <p>Deskripsi singkat tentang karya pertama.</p>
        </div>
        <div class="work-item">
            <h3>Judul Karya 2</h3>
            <p>Deskripsi singkat tentang karya kedua.</p>
        </div>
        <div class="work-item">
            <h3>Judul Karya 3</h3>
            <p>Deskripsi singkat tentang karya ketiga.</p>
        </div>
    </div>
</section>

<section class="content" id="contact">
    <h2>Kontak</h2>
    <p>Untuk berhubungan lebih lanjut, silakan kirimkan email ke: <strong>emailmu@example.com</strong>.</p>
</section>

<footer>
    <p>&copy; 2024 Halaman Pribadi. Semua Hak Dilindungi.</p>
</footer>

</body>
</html>
