# LOczek
<!DOCTYPE html>
<html lang="pl">
  /* style.css */
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
}

header {
  background-color: #333;
  color: white;
  padding: 10px 0;
}

header nav ul {
  list-style-type: none;
  text-align: center;
}

header nav ul li {
  display: inline;
  margin: 0 15px;
}

header nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  background-color: #ff9900;
  color: white;
  text-align: center;
  padding: 50px 20px;
}

h2 {
  color: #333;
}

#pielęgnacja ul {
  padding-left: 20px;
}

.product {
  display: inline-block;
  width: 30%;
  margin: 20px 1%;
  text-align: center;
}

.product img {
  width: 100%;
  max-width: 200px;
}

footer {
  background-color: #333;
  color: white;
  padding: 20px;
  text-align: center;
}

footer a {
  color: white;
  text-decoration: none;
}

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Strona o pielęgnacji kręconych włosów - Loczek. Dowiedz się, jak dbać o swoje kręcone włosy, poznaj polecane produkty i odkryj, jak wydobyć skręt.">
  <meta name="keywords" content="pielęgnacja kręconych włosów, loczek, produkty do włosów, naturalne włosy, dbanie o włosy, skręt, pielęgnacja kręconych włosów">
  <meta name="author" content="Loczek">
  <title>Loczek - Pielęgnacja Kręconych Włosów</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Nagłówek -->
  <header>
    <nav>
      <ul>
        <li><a href="#home">Strona Główna</a></li>
        <li><a href="#pielęgnacja">Pielęgnacja</a></li>
        <li><a href="#produkty">Produkty</a></li>
        <li><a href="#motywacja">Zachęta</a></li>
        <li><a href="#contact">Kontakt</a></li>
      </ul>
    </nav>
  </header>

  <!-- Sekcja Hero -->
  <section id="home" class="hero">
    <h1>Witaj na Loczku!</h1>
    <p>Odkryj, jak dbać o swoje kręcone włosy i ciesz się ich naturalnym pięknem. Poznaj nasze porady, produkty i techniki, które pomogą Ci uzyskać idealny skręt.</p>
  </section>

  <!-- Sekcja pielęgnacji -->
  <section id="pielęgnacja">
    <h2>Pielęgnacja Kręconych Włosów</h2>
    <p>Kręcone włosy wymagają szczególnej troski, by były zdrowe, lśniące i pełne objętości. Oto kilka podstawowych zasad, których warto przestrzegać:</p>
    <ul>
      <li><strong>Odpowiednie nawilżenie:</strong> Kręcone włosy łatwo się przesuszają, dlatego ważne jest regularne nawilżanie.</li>
      <li><strong>Unikanie gorącego powietrza:</strong> Wysoka temperatura może zniszczyć strukturę włosa. Korzystaj z chłodnego powietrza przy suszeniu.</li>
      <li><strong>Delikatne mycie:</strong> Używaj łagodnych szamponów, które nie przesuszają włosów. Unikaj szamponów z SLS (Sodium Lauryl Sulfate).</li>
      <li><strong>Akceptacja naturalnej tekstury:</strong> Kręcone włosy to wyjątkowy typ, który zasługuje na to, byś się nimi cieszyła.</li>
    </ul>
  </section>

  <!-- Sekcja polecanych produktów -->
  <section id="produkty">
    <h2>Polecane Produkty</h2>
    <div class="product">
      <img src="product1.jpg" alt="Szampon do kręconych włosów">
      <h3>Szampon Nawilżający</h3>
      <p>Wysokiej jakości szampon, który dogłębnie nawilża kręcone włosy i nie pozbawia ich naturalnych olejków.</p>
    </div>
    <div class="product">
      <img src="product2.jpg" alt="Maska do włosów kręconych">
      <h3>Maska Nawilżająca</h3>
      <p>Intensywna maska do włosów kręconych, która odbudowuje skręt i dodaje objętości.</p>
    </div>
    <div class="product">
      <img src="product3.jpg" alt="Żel do stylizacji loków">
      <h3>Żel Stylizujący</h3>
      <p>Żel, który utrwala skręt, nie obciążając włosów i nadaje im naturalny wygląd.</p>
    </div>
  </section>

  <!-- Sekcja motywacyjna -->
  <section id="motywacja">
    <h2>Wydobądź swój Skręt!</h2>
    <p>Twoje kręcone włosy to prawdziwy skarb! Pamiętaj, że najważniejsze to akceptować ich naturalną strukturę. Oto kilka prostych trików, by wydobyć piękny skręt:</p>
    <ul>
      <li><strong>Używaj metody "Plopping":</strong> Zawijanie włosów w bawełnianą koszulkę po umyciu, aby zachować kształt loków.</li>
      <li><strong>Testuj różne produkty:</strong> Każdy typ kręconych włosów potrzebuje czegoś innego, więc eksperymentuj z różnymi kosmetykami.</li>
      <li><strong>Zachowaj cierpliwość:</strong> Kręcone włosy potrzebują czasu, by się ułożyć. Nie zniechęcaj się!</li>
    </ul>
  </section>

  <!-- Stopka -->
  <footer id="contact">
    <p>&copy; 2025 Loczek. Wszystkie prawa zastrzeżone.</p>
    <p>Kontakt: <a href="mailto:kontakt@loczek.pl">kontakt@loczek.pl</a></p>
    <div>
      <a href="https://www.instagram.com/loczek" target="_blank">Instagram</a> | <a href="https://www.facebook.com/loczek" target="_blank">Facebook</a>
    </div>
  </footer>


