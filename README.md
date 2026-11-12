# Portafolio (solo HTML y CSS)

```
portafolio/
├── index.html                # Inicio: una tarjeta por materia
├── public/
│   ├── html-css.html         # Una página por materia, con sus trayectorias
│   ├── algoritmia.html
│   ├── ia-generativa.html
│   ├── analitica-datos.html
│   └── favicon.svg
├── resources/
│   ├── docs/                 # PDFs, informes
│   └── img/                  # Imágenes y capturas
├── scripts/                  # Vacía por ahora (sin scripts propios; solo el JS de Bootstrap por CDN)
└── styles/
    └── main.css
```

## Agregar un repositorio
Abre la página de la materia, ubica la trayectoria y copia un bloque `<li class="list-group-item fila ...">`
dentro de su `<ul>`. Cambia título, descripción, etiquetas, fecha y el `href` del botón.
Si aún no hay repo, deja el `<span class="btn btn-repo btn-sm disabled">Próximamente</span>`.

## Agregar una trayectoria
Copia un bloque `<section class="trayectoria mb-5">...</section>` completo y cambia el título.

## Publicar en GitHub Pages
1. Sube la carpeta a un repositorio (el `index.html` debe quedar en la raíz).
2. En el repo: Settings → Pages → Source: "Deploy from a branch" → rama `main`, carpeta `/ (root)`.
3. Tu portafolio quedará en `https://tu-usuario.github.io/nombre-del-repo/`.
