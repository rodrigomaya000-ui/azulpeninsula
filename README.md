# Azul Península — Sitio Web

Sitio web oficial del fraccionamiento residencial Azul Península.

## Estructura

```
azul-peninsula/
├── index.html        ← Página de inicio
├── about.html        ← Nosotros / Administración
├── listings.html     ← Catálogo de departamentos
├── contact.html      ← Formulario y datos de contacto
├── css/
│   └── styles.css    ← Estilos globales
├── js/
│   └── main.js       ← Navbar, idioma ES/EN, animaciones
└── img/              ← (crear carpeta para imágenes)
    ├── hero/
    ├── directiva/
    └── departamentos/
```

## Cómo usar

1. Clona el repositorio
2. Abre `index.html` en tu navegador — no necesitas servidor
3. Publica en GitHub Pages activando el repositorio en Settings → Pages

## Pendientes antes de publicar

### Datos reales
- [ ] Reemplazar "Nombre Apellido" con los miembros reales de la mesa directiva
- [ ] Reemplazar "Nombre Apellido" con los miembros del consejo de vigilancia
- [ ] Actualizar teléfono y correo en footer y contact.html
- [ ] Actualizar dirección real en contact.html

### Imágenes
- [ ] Agregar foto del fraccionamiento (hero de index.html)
- [ ] Agregar fotos de los miembros de la administración
- [ ] Agregar fotos de cada departamento en listings.html

### Formulario
- [ ] Crear cuenta en [Formspree.io](https://formspree.io) (gratis)
- [ ] Reemplazar `YOUR_FORM_ID` en contact.html con tu ID real

### WhatsApp
- [ ] Reemplazar `52XXXXXXXXXX` en contact.html con el número real

### Mapa
- [ ] Ir a Google Maps → Compartir → Insertar mapa → copiar el iframe
- [ ] Reemplazar el `<div class="map-placeholder">` en contact.html

### Departamentos
- [ ] Duplicar las tarjetas en listings.html para agregar los 16+ departamentos
- [ ] Actualizar precios, m², pisos y amenidades de cada uno

## Funcionalidades incluidas

- ✅ Navbar con scroll effect
- ✅ Switch de idioma ES / EN (persiste entre páginas via localStorage)
- ✅ Menú hamburguesa para móvil
- ✅ Animaciones de entrada con IntersectionObserver
- ✅ Filtro de departamentos por disponibilidad (JS puro)
- ✅ Formulario de contacto async con Formspree
- ✅ CTA de WhatsApp con mensaje predefinido
- ✅ Diseño responsivo (desktop → tablet → móvil)

## Tecnologías

- HTML5 semántico
- CSS3 (variables, grid, flexbox, animaciones)
- JavaScript vanilla (sin frameworks)
- Google Fonts (Cormorant Garamond + DM Sans)
- Formspree (formulario sin backend)

## Fase 2 (después del bootcamp)

- Panel de administración con Node.js + Express
- Base de datos (PostgreSQL) para gestionar departamentos dinámicamente
- Sistema de citas con notificaciones automáticas
- Login para administradores
