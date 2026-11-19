
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Company Profile | Zhaira</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            background: #faf7ff;
            color: #302442;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 22px 8%;
            background: white;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 3px 15px #0000000d;
        }

        .logo {
            font-size: 25px;
            font-weight: bold;
            color: #9362d9;
        }

        nav a {
            text-decoration: none;
            color: #443454;
            margin-left: 25px;
            font-weight: 500;
            transition: .3s;
        }

        nav a:hover {
            color: #a36be8;
        }

        .hero {
            min-height: 85vh;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 60px 10%;
            gap: 40px;
        }

        .hero-text {
            max-width: 550px;
        }

        .hero-text span {
            color: #a36be8;
            font-weight: bold;
        }

        .hero h1 {
            font-size: 55px;
            margin: 15px 0;
            line-height: 1.2;
        }

        .hero h1 b {
            color: #a36be8;
        }

        .hero p {
            color: #766b83;
            line-height: 1.8;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            background: #9564d8;
            color: white;
            padding: 13px 28px;
            border-radius: 30px;
            text-decoration: none;
            transition: .3s;
        }

        .btn:hover {
            background: #7545b7;
            transform: translateY(-3px);
        }

        .hero-image {
            width: 320px;
            height: 320px;
            border-radius: 50%;
            background: linear-gradient(135deg, #e9d7ff, #f9cce8);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 110px;
            box-shadow: 0 15px 40px #b48bdc44;
        }

        section {
            padding: 80px 10%;
        }

        .section-title {
            text-align: center;
            font-size: 32px;
            margin-bottom: 15px;
            color: #7045a8;
        }

        .subtitle {
            text-align: center;
            color: #877b91;
            margin-bottom: 45px;
        }

        .about {
            background: white;
        }

        .about-content {
            max-width: 800px;
            margin: auto;
            text-align: center;
            line-height: 2;
            color: #756982;
        }

        .skills-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .skill-card {
            background: white;
            padding: 30px 20px;
            border-radius: 18px;
            text-align: center;
            box-shadow: 0 5px 20px #00000009;
            transition: .3s;
        }

        .skill-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 12px 25px #a36be833;
        }

        .skill-card .icon {
            font-size: 40px;
            margin-bottom: 15px;
        }

        .skill-card h3 {
            margin-bottom: 10px;
            color: #8957c5;
        }

        .skill-card p {
            color: #81758b;
            line-height: 1.7;
            font-size: 14px;
        }

        .contact {
            background: linear-gradient(135deg, #9362d9, #c28be9);
            color: white;
            text-align: center;
        }

        .contact h2 {
            font-size: 32px;
            margin-bottom: 15px;
        }

        .contact p {
            margin-bottom: 25px;
        }

        .contact .btn {
            background: white;
            color: #8957c5;
        }

        footer {
            background: #302442;
            color: white;
            text-align: center;
            padding: 22px;
            font-size: 14px;
        }

        @media(max-width: 768px) {
            header {
                flex-direction: column;
                gap: 15px;
            }

            nav a {
                margin: 0 8px;
                font-size: 13px;
            }

            .hero {
                flex-direction: column-reverse;
                text-align: center;
                padding: 60px 7%;
            }

            .hero h1 {
                font-size: 40px;
            }

            .hero-image {
                width: 230px;
                height: 230px;
                font-size: 80px;
            }

            .skills-container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>

<body>

    <header>
        <div class="logo">ZHAIRA.</div>

        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero" id="home">
        <div class="hero-text">
            <span>HELLO, WELCOME TO MY WEBSITE!</span>

            <h1>Hi, I'm <b>Zhaira</b></h1>

            <p>
                Seorang siswi kelas 11 RPL 3 yang memiliki
                ketertarikan dalam dunia teknologi, terutama
                desain website dan pengembangan halaman web.
                Saya senang menciptakan tampilan website
                yang kreatif, menarik, dan nyaman digunakan.
            </p>

            <a href="#about" class="btn">Explore My Profile</a>
        </div>

        <div class="hero-image">
            💜
        </div>
    </section>

    <section class="about" id="about">
        <h2 class="section-title">About Me</h2>
        <p class="subtitle">Get to know me better!</p>

        <div class="about-content">
            <p>
                Halo! Perkenalkan, nama saya <b>Zhaira</b>.
                Saya merupakan siswi kelas <b>11 RPL 3</b>
                (Rekayasa Perangkat Lunak).

                Saya mempunyai minat dan ketertarikan
                dalam bidang desain digital, khususnya
                membuat dan mendesain halaman website.

                Saya suka mencoba hal-hal baru, mengembangkan
                kreativitas, serta mempelajari berbagai
                teknologi untuk menciptakan karya digital
                yang menarik dan bermanfaat.
            </p>
        </div>
    </section>

    <section id="skills">
        <h2 class="section-title">My Skills</h2>
        <p class="subtitle">Things I love to do</p>

        <div class="skills-container">

            <div class="skill-card">
                <div class="icon">🎨</div>
                <h3>Web Design</h3>
                <p>
                    Suka mendesain tampilan halaman website
                    yang modern, menarik, dan aesthetic.
                </p>
            </div>

            <div class="skill-card">
                <div class="icon">💻</div>
                <h3>HTML & CSS</h3>
                <p>
                    Memiliki ketertarikan dalam membuat
                    struktur dan mempercantik tampilan website.
                </p>
            </div>

            <div class="skill-card">
                <div class="icon">✨</div>
                <h3>Creative Thinking</h3>
                <p>
                    Senang menuangkan ide kreatif dan
                    mencoba berbagai konsep desain baru.
                </p>
            </div>

        </div>
    </section>

    <section class="contact" id="contact">
        <h2>Let's Connect!</h2>

        <p>
            Terima kasih sudah mengunjungi profil saya.
            Mari belajar, berkarya, dan berkembang bersama!
        </p>

        <a href="mailto:emailkamu@gmail.com" class="btn">
            Contact Me
        </a>
    </section>

    <footer>
        <p>© 2026 Zhaira | 11 RPL 3. All Rights Reserved.</p>
    </footer>

</body>
</html>
