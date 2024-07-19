<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Le Voyage Linguistique</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 0;
            line-height: 1.5;
            text-align: center;
        }

        header {
            background-color: #0056b3;
            color: white;
            padding: 20px 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            animation: fadeInDown 1s ease-out;
        }

        nav {
            background-color: #333;
            display: flex;
            justify-content: center;
            position: fixed;
            width: 100%;
            top: 60px;
            z-index: 1000;
            animation: slideInDown 1s ease-out;
        }

        nav a {
            color: white;
            padding: 15px;
            text-decoration: none;
            transition: background-color 0.3s ease;
        }

        nav a:hover {
            background-color: #0056b3;
        }

        main {
            padding-top: 120px;
            text-align: left;
            margin: 20px;
            animation: slideInUp 1s ease-out;
        }

        section {
            background-color: #fff;
            margin: 20px auto;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 800px;
            animation: fadeIn 1s ease-out;
        }

        h2 {
            color: #0056b3;
            margin-top: 0;
        }

        ul {
            padding-left: 20px;
        }

        ul li {
            margin: 8px 0;
            cursor: pointer;
            transition: color 0.3s ease;
        }

        ul li:hover {
            color: #0056b3;
        }

        img {
            width: 100%;
            height: auto;
            max-width: 300px;
            border-radius: 8px;
            margin-top: 10px;
        }

        @media (max-width: 600px) {
            nav {
                flex-direction: column;
                align-items: center;
                top: 100px;
            }
            nav a {
                margin-bottom: 10px;
            }
            main {
                padding-top: 180px;
            }
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideInUp {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        @keyframes slideInDown {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        @keyframes fadeInDown {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
    </style>
</head>

<body>
    <header>
        <h1>Le Voyage Linguistique: Petualangan Belajar Bahasa Prancis bersama Dini :)</h1>
    </header>
    <nav>
        <a href="#grammar">Dasar-dasar Bahasa Prancis</a>
        <a href="#conversation">Contoh Percakapan</a>
        <a href="#culture">Budaya Prancis</a>
        <a href="#resources">Sumber Belajar</a>
    </nav>
    <main>
        <section id="grammar">
            <h2>Dasar-dasar Bahasa Prancis</h2>
            <p>Mempelajari dasar-dasar bahasa Prancis.</p>
            <ul>
                <li>Mengenal jenis kelamin kata benda (Féminin, masculin et jamak)</li>
            </ul>
        </section>
        <section id="conversation">
            <h2>Contoh Percakapan dalam Bahasa Prancis</h2>
            <p>Berikut adalah beberapa contoh percakapan sehari-hari dalam bahasa Prancis.</p>
            <ul>
                <li>Salut, comment ça va? (Halo, apa kabar?)</li>
            </ul>
        </section>
        <section id="culture">
            <h2>Budaya Prancis</h2>
            <p>Jelajahi kebudayaan Prancis yang beragam.</p>
            <ul>
                <li>Masakan khas Prancis</li>
                <ul>
                    <li><strong>Coq au Vin</strong></li>
                    <li>Coq au Vin adalah salah satu hidangan klasik dari Prancis yang terkenal di seluruh dunia. Secara harfiah berarti "ayam dengan anggur," hidangan ini memiliki akar yang dalam di wilayah Burgundy, terkenal dengan anggurnya yang berkualitas tinggi. Awalnya, hidangan ini dibuat untuk memanfaatkan ayam jantan tua yang dagingnya lebih keras, dimasak perlahan dalam anggur merah untuk melembutkannya.</li>
                    <li>Hidangan ini mencerminkan gaya memasak tradisional Prancis yang menekankan penggunaan bahan lokal yang segar dan teknik memasak yang tepat untuk menghasilkan rasa yang dalam dan kompleks. Ada berbagai variasi regional, seperti Coq au Vin Blanc dari Alsace yang menggunakan anggur putih.</li>
                    <li><img src="https://telegra.ph/file/272fc5e0dcc71d4046083.jpg" alt="Coq au Vin"></li>
                </ul>
            </ul>
        </section>
        <section id="resources">
            <h2>Sumber Belajar Online</h2>
            <p>Rekomendasi aplikasi, website, dan buku untuk belajar bahasa Prancis.</p>
            <ul>
                <li>Duolingo</li>
            </ul>
        </section>
    </main>
    <footer>
        <p>Created by Dini Setia Wati, 2024</p>
    </footer>
</body>
</html>
