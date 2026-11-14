# Control de Rescate y Adopción

Prototipo académico estructural en HTML5, sin CSS ni JavaScript.

## Estructura

```text
control-rescate-adopcion/
├── index.html
├── reportar.html
├── rescates.html
├── README.md
├── .gitignore
└── assets/
    └── img/
```

## Cómo visualizarlo

Abre `index.html` en un navegador. Desde la navegación principal puedes acceder a las otras dos páginas.

## Contenido

- `index.html`: bienvenida y resumen del refugio.
- `reportar.html`: formulario HTML para registrar un animal rescatado.
- `rescates.html`: tabla semántica con registros de ejemplo.

Los datos del listado son demostrativos. El formulario tiene `action="#"` porque esta entrega es únicamente una maqueta estructural: todavía no almacena información ni se conecta a una base de datos.

## Validación

Valida cada archivo en https://validator.w3.org/ seleccionando “Validate by File Upload” o “Validate by Direct Input”.

## Gitflow solicitado

```bash
git checkout develop
git pull origin develop
git checkout -b feature/maquetacion-html

git add .
git commit -m "feat: crear estructura HTML5 del sistema de rescate"
git push -u origin feature/maquetacion-html

# Luego de revisar la rama feature, integrar en develop:
git checkout develop
git pull origin develop
git merge --no-ff feature/maquetacion-html
git push origin develop
```

Si el repositorio aún no tiene la rama `develop`, créala desde la rama principal antes de iniciar el flujo.
