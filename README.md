# Front-End_recupera-o2T_2B_Ana-Clara
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja Exemplo</title>
    <link rel="stylesheet" href="front-end_2B_2T_08_seunome.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <h1>Bem-vindo à Loja Exemplo</h1>
    </header>
    <main>
        <section>
            <h2>Sobre Nós</h2>
            <p>Somos uma loja de exemplo que oferece uma variedade de produtos incríveis!</p>
            <img src="exemplo-imagem.jpg" alt="Imagem de exemplo">
        </section>
        <section>
            <h2>Localização</h2>
            <iframe 
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d126911.03757385315!2d-46.67586835824857!3d-23.5481662467983!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce5a46a4cddded%3A0x8c39c3b5d7c91b18!2sSão%20Paulo%2C%20SP!5e0!3m2!1spt-BR!2sbr!4v1632349347164!5m2!1spt-BR!2sbr" 
                width="600" 
                height="450" 
                style="border:0;" 
                allowfullscreen="" 
                loading="lazy">
            </iframe>
        </section>
        <section>
            <h2>Vídeo</h2>
            <iframe 
                width="560" 
                height="315" 
                src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
                title="YouTube video player" 
                frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen>
            </iframe>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Loja Exemplo. Todos os direitos reservados.</p>
    </footer>
</body>
</html>



/* Configuração da fonte externa */
body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    background: linear-gradient(135deg, #FF7F50, #87CEEB); /* Gradiente de fundo */
}

/* Estilos do header */
header {
    background: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

/* Estilos do main */
main {
    padding: 2rem;
}

/* Estilos das seções */
section {
    margin-bottom: 2rem;
}

/* Estilos da imagem */
img {
    max-width: 100%;
    height: auto;
    opacity: 0.8; /* Transparência da imagem */
}

/* Estilos do footer */
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
    position: fixed;
    bottom: 0;
    width: 100%;
}

/* Pseudo-elemento */
h1::after {
    content: " - Loja Exemplo";
    color: #FF6347;
    font-weight: 700;
}




