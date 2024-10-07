<!DOCTYPE html>
<html lang="is">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rúmfatamerkið mitt</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #5D5FEF;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: #333;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            background-image: url('rumfot.jpg'); /* Settu hérna mynd af rúmfötunum þínum */
            background-size: cover;
            background-position: center;
            height: 400px;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .hero h1 {
            font-size: 48px;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 20px;
        }
        .section {
            padding: 40px;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Rúmfatamerkið mitt</h1>
    </header>

    <nav>
        <a href="#products">Vörur</a>
        <a href="#about">Um okkur</a>
        <a href="#contact">Hafa samband</a>
    </nav>

    <div class="hero">
        <h1>Þægileg og stílhrein rúmföt</h1>
    </div>

    <section id="products" class="section">
        <h2>Vörur</h2>
        <p>Við bjóðum upp á hágæða sængurföt, lök og koddaver í mörgum litum og stærðum.</p>
    </section>

    <section id="about" class="section">
        <h2>Um Okkur</h2>
        <p>Rúmfatamerkið okkar leggur áherslu á gæði, stíl og þægindi með sjálfbærum efnum og handverki.</p>
    </section>

    <section id="contact" class="section">
        <h2>Hafa Samband</h2>
        <p>Sendu okkur línu á netfangið: <a href="mailto:info@rumfata.is">info@rumfata.is</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Rúmfatamerkið mitt</p>
    </footer>
</body>
</html>
