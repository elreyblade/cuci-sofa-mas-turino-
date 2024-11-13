<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cuci Sofa Mas Turino</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            background-color: #34495e;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
        }
        .container {
            padding: 20px;
        }
        .hero {
            background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            font-size: 2rem;
        }
        .service-card {
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 15px;
            margin: 15px;
            text-align: center;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Cuci Sofa Mas Turino</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">Tentang Kami</a>
        <a href="#services">Layanan</a>
        <a href="#contact">Hubungi Kami</a>
    </nav>
    <section id="home" class="hero">
        <div>
            <h2>Sofa Bersih, Nyaman, dan Seperti Baru!</h2>
            <p><a href="#contact" style="background: #e74c3c; color: white; padding: 10px 20px; text-decoration: none;">Pesan Sekarang</a></p>
        </div>
    </section>
    <section id="about" class="container">
        <h2>Tentang Kami</h2>
        <p>Cuci Sofa Mas Turino menyediakan layanan cuci sofa profesional dengan hasil maksimal dan pelayanan terbaik. Tim kami berpengalaman dan menggunakan teknologi terkini untuk membersihkan sofa Anda.</p>
    </section>
    <section id="services" class="container">
        <h2>Layanan Kami</h2>
        <div class="service-card">
            <h3>Cuci Sofa Standar</h3>
            <p>Pembersihan dasar untuk menghilangkan debu dan kotoran.</p>
        </div>
        <div class="service-card">
            <h3>Cuci Sofa Premium</h3>
            <p>Pembersihan mendalam dengan perlindungan ekstra terhadap noda.</p>
        </div>
        <div class="service-card">
            <h3>Pengeringan Cepat</h3>
            <p>Proses pengeringan cepat untuk kenyamanan lebih.</p>
        </div>
    </section>
    <section id="contact" class="container">
        <h2>Hubungi Kami</h2>
        <p>Telepon/WhatsApp: 0812-XXXX-XXXX</p>
        <p>Email: info@cucisofamasturino.com</p>
        <form>
            <label for="name">Nama:</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="message">Pesan:</label><br>
            <textarea id="message" name="message" required></textarea><br><br>
            <input type="submit" value="Kirim">
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Cuci Sofa Mas Turino. All rights reserved.</p>
    </footer>
</body>
</html>
