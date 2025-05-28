<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Solaris Engine</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background-color: #1f9900;
            color: rgb(0, 0, 0);
        }

        .taskbar {
            background-color: #3cff00;
            padding: 15px 30px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 2px 5px rgba(0,0,0,0.5);
        }

        .taskbar h1 {
            margin: 0;
            font-size: 22px;
            color: #000000;
        }

        .content {
            text-align: center;
            padding: 80px 20px;
        }

        .content h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .content p {
            font-size: 18px;
            max-width: 700px;
            margin: auto;
            line-height: 1.6;
        }

        .download-btn {
            margin-top: 60px; /* Augmenté pour plus d'espace */
            padding: 15px 30px;
            font-size: 18px;
            background-color: #00ffc8;
            color: #111;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            text-decoration: none;
            transition: background-color 0.3s;
            display: inline-block;
        }

        .download-btn:hover {
            background-color: #00c3a1;
        }
    </style>
</head>
<body>

    <div class="taskbar">
        <h1>Solaris Engine</h1>
    </div>

    <div class="content">
        <h2>Solaris Engine</h2>
        <p>
            Solaris Engine est un moteur de jeu créé à base de Python, PyGame et OpenGL,
            integration d'Ursina prévu dans un temps indéfini.
        </p>
        <a class="download-btn" href="https://drive.google.com/drive/folders/1l1RVAH1ceCjob-StlTGbM9L0zySgBTTo?usp=drive_link" target="_blank">
            Télécharger Solaris Engine
        </a>
    </div>

</body>
</html>
