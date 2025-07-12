# VIS-Airlines-Sim
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VIS Airlines - Symulacja Zakupu Biletów</title>
    <link rel="icon" href="assets/images/logo.png" type="image/png">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="assets/images/logo.png" alt="Logo VIS Airlines" class="header-logo">
        <h1>Witaj w VIS Airlines!</h1>
    </header>

    <main>
        <section id="flight-selection">
            <h2>Znajdź swój lot</h2>
            <form id="flight-form">
                <p>Wybierz miasto wylotu, przylotu i daty podróży.</p>
                <button type="submit">Wyszukaj loty</button>
            </form>
        </section>

        <section id="payment-simulation" style="display:none;">
            <h2>Symulacja płatności</h2>
            <p>To jest tylko test. Żadna prawdziwa płatność nie zostanie dokonana.</p>
            <button>Zasymuluj płatność</button>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 VIS Airlines. Wszystkie prawa zastrzeżone.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
