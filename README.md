# Seko - Página Web

Página web para el emprendimiento Seko, especializado en productos deshidratados (frutas y verduras).

## Estructura del Proyecto

```
web_seko/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript para interactividad
├── assets/             # Carpeta para imágenes y recursos
│   └── logo.png        # Logo de Seko (coloca tu logo aquí)
└── README.md           # Este archivo
```

## Características

- ✅ Diseño moderno y responsive
- ✅ Navegación suave entre secciones
- ✅ Menú móvil adaptable
- ✅ Formulario de contacto
- ✅ Secciones: Inicio, Productos, Nosotros, Contacto
- ✅ Animaciones al hacer scroll
- ✅ Optimizado para móviles y tablets
- ✅ Colores personalizados según el logo de Seko

## Cómo usar

1. **Agregar tu logo:**
   - Coloca tu archivo de logo en la carpeta `assets/`
   - Nómbralo `logo.png`
   - El logo se mostrará automáticamente en el header y footer

2. **Personalizar contenido:**
   - Edita `index.html` para cambiar textos, información de contacto, etc.
   - Modifica `styles.css` para ajustar colores y estilos
   - Los colores principales están definidos en las variables CSS al inicio del archivo

3. **Abrir la página:**
   - Simplemente abre `index.html` en tu navegador
   - O usa un servidor local para desarrollo

## Personalización de Colores

Los colores principales están definidos en `styles.css`:

```css
--logo-bg: #8B4513;      /* Fondo rojizo-marrón del logo */
--logo-text: #FFF8DC;    /* Texto crema del logo */
--primary-color: #8B4513; /* Color principal */
--bg-warm: #F5E6D3;      /* Fondo cálido */
```

Puedes cambiar estos valores para ajustar la paleta de colores de tu marca.

## Información de Contacto

Recuerda actualizar la información de contacto en la sección correspondiente:
- Email
- Teléfono
- Ubicación
- Redes sociales

## Notas

- El formulario de contacto actualmente muestra una alerta. Para producción, necesitarás configurar un backend o servicio de email.
- Las imágenes de productos son placeholders. Puedes reemplazarlas con fotos reales de tus productos.
