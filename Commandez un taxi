
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chauffeur Privé IDF | Taxi, Van & Grande Remise</title>
    <style>
        :root {
            --gold: #d4af37;
            --dark: #1a1a1a;
            --light: #f9f9f9;
        }

        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            margin: 0;
            background: var(--light);
            color: #333;
        }

        header {
            background: var(--dark);
            color: white;
            padding: 40px 20px;
            text-align: center;
            border-bottom: 4px solid var(--gold);
        }

        h1 {
            font-size: 1.8rem;
            margin: 0;
            letter-spacing: 1px;
        }

        /* Bouton d'appel direct avec ton numéro */
        .btn-call {
            display: inline-block;
            background: var(--gold);
            color: white;
            padding: 18px 30px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            font-size: 1.2rem;
            margin-top: 20px;
            box-shadow: 0 4px 15px rgba(212, 175, 55, 0.3);
        }

        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            padding: 30px;
        }

        .card {
            background: white;
            padding: 20px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            border-top: 3px solid var(--gold);
        }

        .card h3 {
            margin-top: 0;
            color: var(--dark);
        }

        .booking-form {
            max-width: 500px;
            margin: 20px auto;
            padding: 25px;
            background: white;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
            border: 1px solid #eee;
        }

        .booking-form h2 {
            text-align: center;
            color: var(--dark);
            margin-bottom: 20px;
        }

        .form-group {
            margin-bottom: 15px;
        }

        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
            font-size: 0.9rem;
        }

        input, select, textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 8px;
            box-sizing: border-box;
            font-size: 1rem;
        }

        .btn-submit {
            width: 100%;
            background: var(--dark);
            color: var(--gold);
            padding: 15px;
            border: 2px solid var(--gold);
            border-radius: 8px;
            font-weight: bold;
            cursor: pointer;
            font-size: 1.1rem;
            transition: 0.3s;
        }

        .btn-submit:hover {
            background: var(--gold);
            color: white;
        }

        footer {
            text-align: center;
            padding: 30px;
            font-size: 0.9rem;
            color: #777;
            background: #eee;
            margin-top: 20px;
        }

        .phone-footer {
            color: var(--dark);
            font-weight: bold;
            font-size: 1.1rem;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <h1>CHAUFFEUR PRIVÉ & TAXI IDF</h1>
    <p>Région Parisienne : Berline, Van 7+ & Grande Remise</p>
    <a href="tel:0759771691" class="btn-call">📞 APPELER LE CHAUFFEUR</a>
</header>

<section class="services">
    <div class="card">
        <h3>Grande Remise</h3>
        <p>Service de prestige, discrétion et chauffeurs expérimentés pour vos besoins VIP.</p>
    </div>
    <div class="card">
        <h3>Service VAN (7+)</h3>
        <p>Capacité jusqu'à 7 passagers et plus. Idéal pour les groupes, familles et bagages volumineux.</p>
    </div>
    <div class="card">
        <h3>Mise à Disposition</h3>
        <p>Réservez votre chauffeur à l'heure ou à la journée pour vos événements ou rendez-vous.</p>
    </div>
</section>

<section class="booking-form">
    <h2>Demande de Réservation</h2>
    <form action="https://formspree.io/f/xjgjegga" method="POST">
        <div class="form-group">
            <label>Nom & Prénom</label>
            <input type="text" name="nom" placeholder="Votre nom complet" required>
        </div>
        <div class="form-group">
            <label>Votre Numéro de Téléphone</label>
            <input type="tel" name="telephone" placeholder="06 00 00 00 00" required>
        </div>
        <div class="form-group">
            <label>Type de véhicule souhaité</label>
            <select name="type_vehicule">
                <option value="Berline">Berline Standard</option>
                <option value="Grande Remise">Grande Remise (Luxe)</option>
                <option value="VAN">VAN (Jusqu'à 7 passagers)</option>
                <option value="VAN+">VAN (Plus de 7 passagers)</option>
                <option value="Mise à disposition">Mise à disposition (Heure/Journée)</option>
            </select>
        </div>
        <div class="form-group">
            <label>Date et Heure du trajet</label>
            <input type="datetime-local" name="date_heure_trajet" required>
        </div>
        <div class="form-group">
            <label>Détails du trajet</label>
            <textarea name="details_trajety" placeholder="Lieu de départ, destination, gares/aéroports..." rows="3"></textarea>
        </div>
        <button type="submit" class="btn-submit">ENVOYER MA DEMANDE</button>
    </form>
</section>

<footer>
    © 2026 Votre Service de Transport de Prestige - Île-de-France<br>
    Contact direct : <a href="tel:0759771691" class="phone-footer">07 59 77 16 91</a><br>
    Disponible 24h/24 - 7j/7
</footer>

</body>
</html>
