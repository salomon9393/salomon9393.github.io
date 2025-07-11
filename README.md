# salomon9393.github.io
Mi web de fichajes de fútbol 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Fichajes Top 5 Ligas</title>
    <link rel="stylesheet" href="styles.css" />
</head>
<body>
    <header>
        <h1>Fichajes Top 5 Ligas Europeas</h1>
        <nav>
            <button data-league="all" class="active">Todos</button>
            <button data-league="liga">LaLiga</button>
            <button data-league="premier">Premier</button>
            <button data-league="seriea">Serie A</button>
            <button data-league="bundesliga">Bundesliga</button>
            <button data-league="ligue1">Ligue 1</button>
        </nav>
    </header>
    <main>
        <section id="news-ticker">
            <h2>Noticias rápidas</h2>
            <ul id="news-list">
                <!-- Noticias rápidas se añadirán aquí -->
            </ul>
        </section>

        <section id="transfers">
            <!-- Fichajes se mostrarán aquí -->
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>