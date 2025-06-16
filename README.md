<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TERE – Transfeminist Education on Relationships and Emotions</title>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="TERE_css_style/Tere_css">
    <style.css>
body, h1, h2, p, ul {
    margin: 0;
    padding: 0;
}
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #fefefe;
    color: #222;
}

/* Navbar */
.navbar {
    background-color: #333;
    padding: 1em;
}
.navbar ul {
    display: flex;
    list-style: none;
    justify-content: center;
    gap: 1.5em;
}
.navbar a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}
.navbar a:hover {
    text-decoration: underline;
}

/* Hero */
.hero {
    position: relative;
    text-align: center;
}
.hero img {
    width: 100%;
    height: auto;
    max-height: 500px;
    object-fit: cover;
}
.hero-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    background: rgba(0, 0, 0, 0.5);
    padding: 2em;
    border-radius: 10px;
}
.hero-text h1 {
    font-size: 3em;
    margin-bottom: 0.3em;
}
.hero-text p {
    font-size: 1.5em;
}

/* Main content */
.intro {
    padding: 2em;
    max-width: 800px;
    margin: auto;
}
.intro h2 {
    margin-top: 1.5em;
    color: #b137a2;
}
.intro ul {
    list-style-type: none;
    margin-top: 1em;
}
.intro li {
    margin: 0.5em 0;
}

/* Footer */
footer {
    text-align: center;
    padding: 1em;
    background-color: #eee;
    margin-top: 2em;
}
</style>
    <!-- Metadati Dublin Core -->
    <meta name="DC.title" content="TERE – Transfeminist Education on Relationships and Emotions">
    <meta name="DC.creator" content="Tuo Nome">
    <meta name="DC.language" content="it">
    <meta name="DC.subject" content="Educazione sessuale, transfemminismo, emozioni, relazioni, diritti di genere">
    <meta name="DC.description" content="Un archivio digitale di risorse, progetti e iniziative sull’educazione sessuo-affettiva in chiave transfemminista in Europa.">

    <!-- Link al CSS -->
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar">
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="associazioni.html">Associazioni e Progetti</a></li>
            <li><a href="materiali.html">Materiali e Risorse</a></li>
            <li><a href="eventi.html">Eventi e Iniziative</a></li>
            <li><a href="mappa.html">Mappa</a></li>
            <li><a href="contribuisci.html">Contribuisci</a></li>
        </ul>
    </nav>

    <!-- Hero Image -->
    <header class="hero">
        <img src="img/hero.jpg" alt="Immagine di apertura di TERE">
        <div class="hero-text">
            <h1>TERE</h1>
            <p>Transfeminist Education on Relationships and Emotions</p>
        </div>
    </header>

    <!-- Sezioni introduttive -->
    <main class="intro">
        <section>
            <h2>Benvenut* su TERE</h2>
            <p>Questo sito raccoglie risorse, progetti e iniziative per un'educazione sessuo-affettiva transfemminista, inclusiva e intersezionale. È rivolto a chi educa, a chi lotta, a chi apprende.</p>
        </section>

        <section>
            <h2>Esplora</h2>
            <p>Scopri collettivi, reti europee, materiali didattici e strumenti per trasformare l'educazione alla sessualità e alle relazioni.</p>
            <ul>
                <li><a href="associazioni.html">Associazioni e progetti</a></li>
                <li><a href="materiali.html">Materiali e risorse</a></li>
                <li><a href="eventi.html">Eventi e iniziative</a></li>
                <li><a href="mappa.html">Mappa collaborativa</a></li>
                <li><a href="contribuisci.html">Segnala un contenuto</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <p>© 2025 TERE – Progetto universitario. Tutti i diritti riservati. Powered by transfeminist values.</p>
    </footer>

</body>
</html>
