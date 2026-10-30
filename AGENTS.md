# Proyecto HTML - Universidad de Los Lagos

Este es el archivo principal del proyecto. Contiene toda la información y reglas del proyecto. **Siempre debe mantenerse actualizado y debe ser leído antes de realizar cualquier cambio.**

## Estructura del Proyecto

El proyecto sigue esta estructura de directorios:

```text
/
├── .doc/
│   └── prompts.md          # Historial de prompts y reglas iniciales
├── input/
│   └── input.css           # Archivo CSS de entrada para Tailwind
├── src/
│   ├── index.html          # Archivo HTML principal
│   └── assets/
│       ├── css/
│       │   └── style.css   # CSS generado por Tailwind (watch)
│       ├── image/
│       │   └── logo.png    # Logo de la Universidad
│       └── js/             # Scripts JavaScript (vacío por ahora)
├── package.json            # Configuración de Node.js y scripts
└── AGENTS.md               # Este archivo principal
```

## Reglas del Proyecto

1. **Uso de Tailwind CSS 4.x:** El proyecto utiliza Tailwind CSS 4.* configurado vía `@tailwindcss/cli`.
2. **Watch:** Se debe mantener corriendo un proceso de watch para compilar el CSS. Ejecutar con: `npm run watch`.
3. **Colores Globales:** Se utilizan los colores corporativos de la Universidad de Los Lagos:
   - Azul principal: `--color-ulagos-blue`
   - Amarillo/Secundario: `--color-ulagos-yellow`
4. **Header:** El archivo `src/index.html` debe tener un header con el fondo azul de la universidad, el logo a la izquierda, y un menú de navegación de 4 opciones básicas a la derecha.

## Notas

- El logo de la Universidad fue obtenido de su sitio oficial (ulagos.cl).
- Las configuraciones de variables de color de Tailwind están definidas en `input/input.css`.
