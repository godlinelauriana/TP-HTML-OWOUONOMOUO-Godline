´<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon site de rattrapage</title>

    <style>
        body {
            background-color: #f2f2f2;
            font-family: Arial, sans-serif;
            color: #333;
            margin: 0;
            padding: 20px;
        }

        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
            border-radius: 10px;
        }

        nav {
            margin: 20px 0;
            padding: 15px;
            background-color: white;
            border-radius: 10px;
            text-align: center;
        }

        nav a {
            margin: 10px;
            color: #2980b9;
            text-decoration: none;
        }

        nav a:hover {
            color: red;
        }

        section {
            background-color: white;
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            border-radius: 10px;
            border: 2px solid #ddd;
        }

        img {
            width: 300px;
            border-radius: 10px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table, th, td {
            border: 1px solid black;
        }

        th, td {
            padding: 10px;
            text-align: center;
        }

        input, button {
            padding: 10px;
            margin: 5px;
            border-radius: 5px;
            border: 1px solid gray;
        }

        button:hover {
            background-color: #2980b9;
            color: white;
        }
    </style>
</head>

<body>

<header>
    <h1>Bienvenue sur mon site</h1>
</header>

<nav>
    <a href="#">Accueil</a>
    <a href="#">Présentation</a>
    <a href="#">Services</a>
    <a href="#">Contact</a>
</nav>

<section>
    <h2>Présentation</h2>
    <p>
        Je suis étudiant(e) en développement frontend.
        Cette page présente un exercice réalisé avec HTML et CSS.
    </p>

    <img src="https://via.placeholder.com/300" alt="Image de présentation">
</section>

<section>
    <h2>Mes compétences</h2>
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Création de pages web</li>
        <li>Design responsive</li>
    </ul>
</section>

<section>
    <h2>Tableau</h2>

    <table>
        <tr>
            <th>Nom</th>
            <th>Matière</th>
            <th>Note</th>
        </tr>
        <tr>
            <td>Étudiant</td>
            <td>HTML</td>
            <td>15</td>
        </tr>
        <tr>
            <td>Étudiant</td>
            <td>CSS</td>
            <td>16</td>
        </tr>
        <tr>
            <td>Étudiant</td>
            <td>Frontend</td>
            <td>14</td>
        </tr>
    </table>
</section>

<section>
    <h2>Contact</h2>

    <form>
        <input type="text" placeholder="Nom"><br>
        <input type="email" placeholder="E-mail"><br>
        <input type="tel" placeholder="Téléphone"><br>
        <button type="submit">Envoyer</button>
    </form>
</section>

</body>
</html>´´´´
