# 🔐 MensajesOcultos

![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![Status](https://img.shields.io/badge/Status-Activo-green)

Aplicación o herramienta para **generar y descubrir mensajes ocultos** dentro de textos, utilizando técnicas simples de procesamiento de cadenas.
------------------------------------------------------------------------

# 📚 Tabla de Contenido

-   Descripción
-   Tecnologías utilizadas
-   Cómo funciona
-   Estructura del proyecto
-   Cómo ejecutar el proyecto
-   Ejemplo de código
-   Mejoras futuras
-   Autor

------------------------------------------------------------------------

# 📖 Descripción

**MensajesOcultos** es un proyecto que permite **extraer o generar mensajes ocultos a partir de un texto** mediante diferentes técnicas simples de análisis de cadenas.

Un ejemplo clásico consiste en formar un mensaje secreto utilizando **la primera letra de cada palabra de una frase**, lo que permite esconder información dentro de textos aparentemente normales.

El proyecto sirve como ejemplo educativo para practicar algoritmos simples y procesamiento de texto.

------------------------------------------------------------------------

# 🛠 Tecnologías utilizadas

Este proyecto utiliza tecnologías básicas de desarrollo web:

-   HTML5
-   CSS3
------------------------------------------------------------------------

# 📂 Estructura del proyecto

    MensajesOcultos/
    │
    ├── index.html
    ├── styles.css
    └── README.md
------------------------------------------------------------------------

# ▶️ Cómo ejecutar el proyecto

### 1️⃣ Clonar el repositorio

``` bash
git clone https://github.com/Joseluis30c/MensajesOcultos.git
```

### 2️⃣ Entrar a la carpeta del proyecto

``` bash
cd MensajesOcultos
```

### 3️⃣ Abrir el archivo HTML

Solo abre el archivo en tu navegador:

    index.html

------------------------------------------------------------------------

# 💡 Ejemplo de código

Ejemplo de animación CSS para simular el latido:

``` javascript
function obtenerMensajeOculto(texto) {
    return texto
        .split(" ")
        .map(palabra => palabra[0])
        .join("");
}

const texto = "compete online design event rating";

console.log(obtenerMensajeOculto(texto));
// Resultado: coder
```

------------------------------------------------------------------------

# 🚀 Mejoras futuras

Posibles mejoras para este proyecto:

-   Implementar algoritmos de criptografía básica
-   Mostrar diferentes tipos de mensajes ocultos
-   Crear una interfaz web interactiva
------------------------------------------------------------------------

# 👨‍💻 Autor

**Jose Luis Chavesta Rivas**

GitHub\
https://github.com/Joseluis30c

------------------------------------------------------------------------

# ⭐ Apoya el proyecto

Si este proyecto te resulta útil o interesante:

⭐ Dale una estrella al repositorio en GitHub.
