<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invito alla Santa Cresima di <i>Tommaso</i></title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: linear-gradient(45deg, #8b0000 30%, #b8860b 70%);
            background-attachment: fixed;
            height: 100vh;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
            max-width: 500px;
            text-align: center;
            border: 3px solid #b8860b;
        }
        h1 {
            color: #b22222;
        }
        p {
            font-size: 18px;
            color: #333;
        }
        .button {
            display: inline-block;
            background: #b8860b;
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 8px;
            margin: 10px;
            font-weight: bold;
            transition: all 0.3s ease;
            box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.2);
        }
        .button:hover {
            background: #d4af37;
            transform: scale(1.05);
        }
        .confirmation {
            font-size: 14px;
            font-weight: bold;
            color: #333;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Sei invitato alla Santa Cresima di <i>Tommaso</i>!</h1>
        <p>Ti aspettiamo per festeggiare insieme questo giorno speciale.</p>
        <p><strong>Data:</strong> 15/06/25</p>
        <p><strong>Ora:</strong> dalle 11:00</p>
        <p><strong>Luogo della cerimonia:</strong> Chiesa "Il Risorto" Teramo</p>
        <a class="button" href="https://maps.app.goo.gl/pZjTTFtdohU9m1iA9" target="_blank">Posizione Chiesa</a>
        <p><strong>Ristorante:</strong> "Casa Delfico" Toricella Sicura</p>
        <a class="button" href="https://maps.app.goo.gl/pq6x6hW8h8JRrRd39" target="_blank">Posizione Ristorante</a>
        <p class="confirmation">Ti aspettiamo, gradita conferma!</p>
    </div>
</body>
</html>
