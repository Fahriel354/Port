<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV-IRVAN</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body, html {
            height: 100%;
        }

        body {
            display: flex;
            flex-direction: column;
            min-height: 100vh;
            background-color: #f4f4f4;
        }

        header {
            background-color: white;
            padding: 20px 30px;
            font-size: 28px;
            color: #1976D2;
            font-weight: bold;
        }

        .hero {
            background-color: #19284c;
            color: white;
            text-align: center;
            padding: 60px 30px;
        }

        .hero h1 {
            margin-bottom: 10px;
            font-size: 32px;
        }

        .navbar {
            background-color: #33416b;
            display: flex;
            justify-content: center;
            gap: 50px;
            padding: 15px 0;
        }

        .navbar a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            font-size: 18px;
        }

        .section {
            background-color: white;
            margin: 40px auto;
            padding: 30px;
            max-width: 1000px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .section h2 {
            margin-bottom: 15px;
            font-size: 24px;
        }

        .section p, .section li {
            font-size: 18px;
            line-height: 1.8;
        }

        ul {
        	<a href="https://www.contohwebsite.com" style="color:blue;">Lihat Produk Kami</a>
            padding-left: 20px;
        }

        .content {
            flex: 1;
        }

        footer {
            background-color: #263238;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 16px;
        }

        @media (max-width: 768px) {
            .navbar {
                flex-direction: column;
                gap: 15px;
            }

            .hero h1 {
                font-size: 24px;
            }

            .navbar a {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>

    

    <div class="hero">
        <h1>Selamat Datang di Portofolio Saya</h1>
        <hr style="margin: 15px auto; width: 50%; border: 1px solid white;">
        <p>Desainer Web & Pengembang Front-End</p>
    </div>

    <nav class="navbar">
        <a href="#tentang">ㅤTentang Saya</a>
        <a href="#proyek">ㅤProyek</a>
        <a href="#kontak">ㅤKontak</a>
    </nav>

    <div class="content">
        <div class="section" id="tentang">
            <h2>Tentang Saya</h2>
            <hr style="margin: 15px 0;">
            <p>Halo! Saya seorang pengembang web yang berfokus pada pembuatan website responsif dan menarik. Saya memiliki pengalaman dalam HTML, CSS, JavaScript, dan berbagai framework front-end modern.</p>
        </div>

        <div class="section" id="proyek">
            <h2>Proyek Terbaru</h2>
            <hr style="margin: 15px 0;">
            <ul>
                <li>Website Toko Online - cek di <a href="https://lynk.id/rhiel" style="color:blue;">sini</a></li>
                <li>Blog Pribadi - Dibuat dengan HTML, CSS, dan JavaScript</li>
                <li>Dashboard Admin - Menggunakan Bootstrap dan Chart.js</li>
            </ul>
        </div>

        <div class="section" id="kontak">
            <h2>Kontak</h2>
            <hr style="margin: 15px 0;">
            <p>Email: @fahriismail004.com</p>
            <p>Instagram: <a href="https://www.instagram.com/ir.rhiel_?igsh=MWp3NmplbDU0djgzeQ==" style="color:blue;">ir.rhiel_</a></p>
            
        </div>
    </div>

    <footer>&copy; 2025 Portofolio Saya. All rights reserved.</footer>

</body>
