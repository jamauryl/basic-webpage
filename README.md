Descripción
La página web está diseñada para ser simple y funcional, con una estructura clara usando HTML y CSS. Aquí se detalla el propósito de cada sección y cómo se utilizan estos lenguajes para lograr el diseño:
Encabezado (<header>)
Propósito:
Presentar el título de la página y proporcionar una breve descripción que informe a los usuarios sobre el propósito del sitio.
Implementación:
•	En HTML, el <header> contiene un <h1> para el título y un <p> para la descripción.
•	En CSS, el encabezado se estiliza con un fondo azul (background: #007BFF), texto blanco (color: #fff), y centrado (text-align: center). Este diseño asegura que el encabezado destaque como la sección principal.
Introducción (<section id="introduccion">)
Propósito:
Ofrecer un texto introductorio que explique el objetivo general de la página.
Implementación:
•	En HTML, se utiliza un <section> con un <h2> para el subtítulo y un <p> para el texto descriptivo.
•	En CSS, los márgenes y el espaciado proporcionan una separación visual entre esta sección y las demás. Esto mejora la legibilidad del contenido.
Galería de Imágenes (<section id="galeria">)
Propósito:
Mostrar una serie de imágenes organizadas visualmente, ideal para exhibir contenido gráfico o ejemplos visuales.
Implementación:
•	En HTML, se usa un <div> con la clase gallery que contiene varias etiquetas <img> para las imágenes.
•	En CSS, se utiliza el modelo de caja flexible (display: flex) con un espaciado entre las imágenes (gap: 10px). Las imágenes tienen bordes redondeados (border-radius: 5px) y un efecto de marco (border: 2px solid #ddd) para darles un aspecto limpio y profesional.
Formulario de Contacto (<section id="contacto">)
Propósito:
Permitir que los usuarios proporcionen su información para contactar al creador del sitio.
Implementación:
•	En HTML, se utiliza un formulario (<form>) con etiquetas <label> y campos de entrada (<input>) para el nombre y correo electrónico, además de un botón (<button>) para enviar el formulario.
•	En CSS, el formulario se organiza en una columna vertical (flex-direction: column) con un diseño limpio. Los campos de entrada tienen bordes redondeados (border-radius: 5px) y el botón cambia de color al pasar el cursor (:hover), mejorando la experiencia del usuario.
Pie de página (<footer>)
Propósito:
Proporcionar información de derechos de autor y cerrar la página con un diseño coherente.
Implementación:
•	En HTML, se incluye un <footer> con un <p> que contiene el texto de derechos reservados.
•	En CSS, se utiliza un fondo oscuro (background: #222) y texto blanco (color: #fff) con centrado para crear una apariencia elegante y discreta.
