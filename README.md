# Pastelería Delicias - Web Estática

Este proyecto es una página web estática simple para una pastelería, ideal para ser desplegada en GitHub Pages. Incluye secciones de inicio, tortas y contacto.

## Estructura del Proyecto

```
pasteleria-pages/
├── public/
│   ├── assets/       # Imágenes de las tortas y otros recursos
│   ├── index.html    # Página principal de la pastelería
│   ├── script.js     # Archivo JavaScript (vacío por ahora)
│   └── styles.css    # Estilos CSS de la página
└── README.md
```

## Visualización Local

Para ver la página localmente, simplemente abre el archivo `public/index.html` en tu navegador web.

## Despliegue en GitHub Pages

Este proyecto está configurado para ser desplegado automáticamente en GitHub Pages usando GitHub Actions. Sigue estos pasos:

1.  **Crea un Repositorio en GitHub**: Sube este proyecto a un nuevo repositorio de GitHub.
2.  **Configura GitHub Pages**: 
    *   Ve a la sección `Settings` de tu repositorio.
    *   En la barra lateral izquierda, haz clic en `Pages`.
    *   En la sección `Build and deployment`, selecciona `GitHub Actions` como fuente.
3.  **El workflow de GitHub Actions se encargará del resto.** Cada vez que hagas un `push` a la rama `main`, el workflow se ejecutará y desplegará tu sitio web en GitHub Pages. La URL de tu sitio será algo como `https://<tu-usuario>.github.io/<nombre-del-repositorio>/`.

## Contribuciones

Siéntete libre de clonar, modificar y mejorar este proyecto. ¡Es un ejemplo simple para empezar!
