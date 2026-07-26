<!doctype html>
<html lang="fr">
<head>
    <meta charset="utf-8"/>
    <meta content="IE=edge,chrome=1" http-equiv="X-UA-Compatible"/>
    <meta content="width=device-width, initial-scale=1" name="viewport"/>
    <title>eSanté - Prescription Valide</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"/>
    <style>
        body {
          margin: 0;
          padding: 0;
          background-color: #e6f1f8;
          font-family: 'Roboto', sans-serif;
          display: flex;
          justify-content: center;
          align-items: center;
          height: 100vh;
          color: #333;
          flex-direction: column;
        }
        .container {
          background-color: white;
          box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
          border-radius: 15px;
          padding: 20px;
          width: 90%;
          max-width: 650px;
          margin: 20px;
          text-align: center;
        }
        .message {
          font-size: 20px;
          font-weight: 700;
          color: #2e7d32; /* Vert pour "Valide" au lieu du rouge #c62828 */
        }
        .retour {
          font-size: 11px;
          color: #000000;
          text-decoration: none;
          margin-top: 10px;
          display: inline-block;
        }
        .logo {
          display: block;
          margin-left: auto;
          margin-right: auto;
          width: 25%;
          margin-bottom: 20px;
        }
        @media (max-width: 600px) {
          .logo {
            width: 40%;
          }
        }
    </style>
</head>
<body>
<div class="container">
    <a href="https://www.esante.lu/portal/fr/" target="_blank">
        <img alt="eSanté.png" class="logo" src="/images/eSante.png"/>
    </a>
    <p class="message">Cette prescription est valide.</p>
    <a class="retour" href="https://www.esante.lu/portal/fr/">Cliquez ici pour retourner sur la page d'accueil</a>
</div>
</body>
</html>
