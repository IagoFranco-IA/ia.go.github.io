<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IA.go | Controlled Chaos</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: #0f1117;
            color: #f5f5f5;
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.6;
        }

        .hero {
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 40px;
            background:
                radial-gradient(circle at top, rgba(111,66,193,.25), transparent 50%),
                radial-gradient(circle at bottom, rgba(0,251,255,.15), transparent 50%),
                #0f1117;
        }

        .container {
            max-width: 900px;
        }

        h1 {
            font-size: 5rem;
            letter-spacing: 4px;
            margin-bottom: 10px;
        }

        h2 {
            font-size: 1.8rem;
            color: #00FBFF;
            margin-bottom: 25px;
        }

        p {
            color: #c9c9c9;
            margin-bottom: 20px;
            font-size: 1.1rem;
        }

        .buttons {
            margin-top: 30px;
        }

        .btn {
            display: inline-block;
            padding: 14px 28px;
            margin: 10px;
            border-radius: 999px;
            text-decoration: none;
            font-weight: bold;
            transition: .3s ease;
        }

        .spotify {
            background: #1DB954;
            color: white;
        }

        .spotify:hover {
            transform: translateY(-3px);
        }

        .linkedin {
            background: #0A66C2;
            color: white;
        }

        .linkedin:hover {
            transform: translateY(-3px);
        }

        .album {
            padding: 80px 20px;
            text-align: center;
            background: #151922;
        }

        .album h3 {
            font-size: 2rem;
            margin-bottom: 20px;
        }

        .tracklist {
            max-width: 500px;
            margin: auto;
            text-align: left;
            color: #d7d7d7;
        }

        .tracklist li {
            margin: 10px 0;
        }

        footer {
            text-align: center;
            padding: 30px;
            color: #888;
            font-size: 0.9rem;
        }
    </style>
</head>

<body>

<section class="hero">
    <div class="container">

        <h1>IA.go</h1>

        <h2>Controlled Chaos</h2>

        <p>
            Projeto musical criado por Iago Franco.
        </p>

        <p>
            Uma exploração artística do equilíbrio entre caos e controle,
            transformando governança de dados, tecnologia e cultura digital
            em música.
        </p>

        <div class="buttons">

            <a class="btn spotify"
               href="https://open.spotify.com/artist/3NOZUPV1z4snI99p63XgSd?si=cv17u50KSQuqGHHSlSNOOg"
               target="_blank">
               Ouvir no Spotify
            </a>

            <a class="btn linkedin"
               href="https://www.linkedin.com/in/iago-franco?utm_source=share_via&utm_content=profile&utm_medium=member_android"
               target="_blank">
               LinkedIn
            </a>

        </div>

    </div>
</section>

<section class="album">

    <h3>Tracklist</h3>

    <ul class="tracklist">
        <li>Controlled Chaos</li>
        <li>Export to Excel</li>
        <li>Who Owns This Data?</li>
        <li>Broken Pipeline</li>
        <li>Data Product (or is it?)</li>
        <li>Lineage Missing</li>
        <li>Just One More Access</li>
        <li>Shadow Data</li>
        <li>Trust Issues</li>
        <li>Source of Truth</li>
    </ul>

</section>

<footer>
    © 2026 IA.go • Created by ℗ Iago Franco 
</footer>

</body>
</html>
