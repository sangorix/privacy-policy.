<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Demande de Suppression de Données Personnelles</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #f4f4f8;
            margin: 0;
            padding: 40px 20px;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: #fff;
            padding: 30px 40px;
            border-radius: 12px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333;
            margin-bottom: 20px;
        }
        p {
            color: #666;
            line-height: 1.6;
        }
        form {
            margin-top: 20px;
        }
        label {
            display: block;
            margin: 15px 0 5px;
            font-weight: bold;
            color: #444;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            font-size: 1rem;
            border-radius: 6px;
            border: 1px solid #ccc;
            box-sizing: border-box;
        }
        button {
            margin-top: 20px;
            width: 100%;
            padding: 12px;
            background-color: #d9534f;
            color: white;
            border: none;
            border-radius: 6px;
            font-size: 1rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #c9302c;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Demande de Suppression de Données</h1>
        <p>
            Conformément au Règlement Général sur la Protection des Données (RGPD), vous pouvez demander la suppression de vos données personnelles en remplissant le formulaire ci-dessous.
        </p>
        <form action="#" method="post">
            <label for="nom">Nom complet</label>
            <input type="text" id="nom" name="nom" required>

            <label for="email">Adresse e-mail</label>
            <input type="email" id="email" name="email" required>

            <label for="raison">Motif de la demande</label>
            <textarea id="raison" name="raison" rows="5" placeholder="Expliquez la raison de votre demande..." required></textarea>

            <button type="submit">Envoyer la demande</button>
        </form>
    </div>
</body>
</html>
