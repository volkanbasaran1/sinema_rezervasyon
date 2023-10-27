![ekran](https://github.com/volkanbasaran1/sinema_rezervasyon/assets/76842256/52b3978a-a47c-4d56-ae13-cf39c15fdbf9)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Sinema Rezervasyon Sitesi</title>
</head>
<body>
    <header>
        <h1>Sinema Rezervasyon Sitesi</h1>
        <p>Film keyfinizi bizimle yaşayın. En son filmleri izlemek için yerinizi şimdi ayırtın!</p>
    </header>
    <nav>
        <ul>
            <li><a href="#movies">Filmler</a></li>
            <li><a href="#showtimes">Seanslar</a></li>
            <li><a href="#contact">İletişim</a></li>
        </ul>
    </nav>
    <div class="container" id="movies">
        <h2>Filmler</h2>
        <ul>
            <li>
                <h3>Film Adı 1</h3>
                <p>Açıklama: Bu film harika bir film ve sizi eğlendirecek.</p>
                <p>Oyuncular: Oyuncu 1, Oyuncu 2</p>
                <button onclick="reserveTicket(1)">Bilet Al</button>
            </li>
            <li>
                <h3>Film Adı 2</h3>
                <p>Açıklama: Bu film de harika bir film ve sizi eğlendirecek.</p>
                <p>Oyuncular: Oyuncu 3, Oyuncu 4</p>
                <button onclick="reserveTicket(2)">Bilet Al</button>
            </li>
            <!-- Daha fazla film öğesi eklenebilir -->
        </ul>
    </div>
    <div class="container" id="showtimes">
        <h2>Seanslar</h2>
        <ul>
            <li>
                <h3>Film Adı 1 - Seans 1</h3>
                <p>Tarih: 27 Ekim 2023</p>
                <p>Saat: 14:00</p>
                <button onclick="reserveTicket(1, 1)">Bilet Al</button>
            </li>
            <li>
                <h3>Film Adı 2 - Seans 1</h3>
                <p>Tarih: 27 Ekim 2023</p>
                <p>Saat: 16:30</p>
                <button onclick="reserveTicket(2, 1)">Bilet Al</button>
            </li>
            <!-- Daha fazla seans öğesi eklenebilir -->
        </ul>
    </div>
    <div class="container" id="contact">
        <h2>İletişim</h2>
        <p>Bizimle iletişime geçmek için lütfen aşağıdaki bilgileri kullanın:</p>
        <p>Telefon: 555-555-5555</p>
        <p>E-posta: info@sinemarezervasyon.com</p>
    </div>
</body>
</html>
