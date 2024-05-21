<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El lenguaje de la Web</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>El lenguaje de la Web</h1>
        <h2>HTML: La estructura subyacente de la web</h2>
    </header>
    <main>
        <section>
            <p>En el corazón de cada página web se encuentra el <em>Hyper Text Markup Language</em>
            (Lenguaje de marcado de hipertexto), más conocido como HTML, el lenguaje que ha sido la
            columna vertebral de la web desde sus inicios. Este lenguaje de marcado es responsable de
            estructurar y presentar el contenido en Internet, permitiendo a los navegadores interpretar y
            mostrar las páginas web tal como los diseñadores y desarrolladores las han concebido.</p>

            <p>SEO (Search Engine Optimization) se refiere a prácticas que mejoran la visibilidad de un sitio
            web en los motores de búsqueda. La semántica HTML contribuye al SEO al permitir que los motores de búsqueda comprendan mejor la estructura y el contenido de una página. Esto ayuda a posicionar el sitio web de manera más efectiva en los resultados de búsqueda, aumentando
            su visibilidad.</p>

            <p>Mientras que el HTML es la estructura del contenido, el CSS (Cascading Style Sheets) es decir,
            las hojas de estilo en cascada, lo embellecen. CSS es el lenguaje que se utiliza para definir la
            presentación visual de una página web. A través de CSS, los diseñadores pueden controlar la
            disposición de los elementos HTML, ajustar colores, tamaños y crear un diseño adaptable que
            responda a diferentes tamaños de pantalla y/o dispositivos. La combinación de HTML y CSS es
            poderosa, permitiendo a los creadores de contenido y desarrolladores web controlar
            precisamente cómo se ve y se siente un sitio web.</p>

            <footer>
                <p>Fuente bibliográfica: Reyes Ramirez G.G. (2024). Cultura Digital II. México:
                Editorial Stanford Publising.</p>
            </footer>
        </section>
        <section class="images">
            <img src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="Programación 1">
            <img src="https://images.pexels.com/photos/1181675/pexels-photo-1181675.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="Programación 2">
            <img src="https://images.pexels.com/photos/270404/pexels-photo-270404.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="Programación 3">
        </section>
    </main>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5rem;
}

header h2 {
    margin: 0;
    font-size: 1.5rem;
    font-weight: lighter;
    color: #ddd;
}

main {
    padding: 2rem;
}

section p {
    margin: 1rem 0;
}

footer {
    margin-top: 2rem;
    font-style: italic;
    color: #777;
}

.images {
    display: flex;
    justify-content: space-around;
    margin-top: 2rem;
}

.images img {
    width: 30%;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

@media (max-width: 768px) {
    .images {
        flex-direction: column;
        align-items: center;
    }

    .images img {
        width: 80%;
        margin-bottom: 1rem;
    }
}
