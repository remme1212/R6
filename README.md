<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rainbow Six Siege Community</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Hem</a></li>
                <li><a href="#guides">Guider</a></li>
                <li><a href="#community">Community</a></li>
                <li><a href="#news">Nyheter</a></li>
                <li><a href="#about">Om oss</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <div class="hero">
            <h1>Välkommen till Rainbow Six Siege Community</h1>
            <p>Följ med oss på våra äventyr och bli en bättre spelare!</p>
        </div>
    </section>

    <section id="guides">
        <h2>Guider & Tips</h2>
        <p>Här hittar du tips på operatörer, kartor och taktiker för att dominera på fältet!</p>
    </section>

    <section id="community">
        <h2>Community</h2>
        <p>Gå med i vår Discord och diskutera strategier och spela med andra!</p>
    </section>

    <section id="news">
        <h2>Nyheter</h2>
        <p>Håll dig uppdaterad om de senaste patcharna och tävlingarna.</p>
    </section>

    <section id="about">
        <h2>Om Oss</h2>
        <p>Vi är ett passionerat community för Rainbow Six Siege och andra gamingfans!</p>
    </section>

    <footer>
        <p>&copy; 2025 Rainbow Six Siege Community</p>
    </footer>
</body>
</html>
/* Grundläggande styling */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #111;
    color: #fff;
}

header {
    background-color: #222;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

.hero {
    background-image: url('your-image-url.jpg'); /* Byt ut till en bildlänk från Rainbow Six Siege */
    background-size: cover;
    background-position: center;
    color: #fff;
    text-align: center;
    padding: 100px 0;
}

h1 {
    font-size: 3em;
}

h2 {
    margin: 20px 0;
    text-align: center;
    font-size: 2em;
}

section {
    padding: 40px 10%;
    text-align: center;
}

footer {
    background-color: #222;
    padding: 20px 0;
    text-align: center;
    color: #888;
}

/* Anpassad layout */
#home {
    background-color: #333;
    color: #fff;
}

#guides, #community, #news, #about {
    background-color: #444;
    color: #fff;
}