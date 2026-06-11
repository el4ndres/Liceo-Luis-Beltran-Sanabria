# Liceo 'Luís Beltrán Sanabria' - Sitio Web Institucional

## Descripción
Sitio web estático desarrollado en HTML y CSS para el Liceo 'Luís Beltrán Sanabria', ubicado en Cumanacoa, Municipio Montes, Estado Sucre, Venezuela.

## Estructura del Proyecto

```
liceo_moderno_nuevo/
│
├── index.html                      # Página principal
├── institucion.html                # Página institucional (Nosotros)
├── README.md                       # Este archivo
│
├── CSS/                            # Estilos para la página principal
│   ├── 00-reset.css               # Reset de estilos del navegador
│   ├── 01-header.css              # Estilos del encabezado y navegación
│   ├── 02-hero.css                # Estilos de la sección hero/banner
│   ├── 03-buttons.css             # Estilos de botones
│   ├── 04-sections.css            # Estilos de secciones generales
│   ├── 05-noticias.css            # Estilos de la sección de noticias
│   ├── 06-contacto.css            # Estilos de la sección de contacto
│   ├── 07-nosotros.css            # Estilos de la sección nosotros
│   ├── 08-footer.css              # Estilos del pie de página
│   ├── 09-responsive.css          # Estilos responsivos
│   └── styles.css                 # Archivo principal que importa todos los CSS
│
├── CSS-institucion/               # Estilos para la página institucional
│   ├── 00-reset.css              # Reset de estilos
│   ├── 01-header.css             # Estilos del encabezado
│   ├── 02-section-institucional.css  # Estilos de contenido institucional
│   ├── 03-footer.css             # Estilos del pie de página
│   ├── 04-responsive.css         # Estilos responsivos
│   └── styles.css                # Archivo principal que importa todos los CSS
│
└── images/                        # Carpeta de imágenes
    ├── logo.jpeg                  # Logo del liceo
    ├── aulas.jpeg                 # Imagen de aulas
    ├── laboratorios-new.jpeg      # Imagen de laboratorios
    ├── cancha.jpeg                # Imagen de canchas deportivas
    ├── sala-informatica.jpeg      # Imagen de sala de informática
    ├── olimpiadas.jpg             # Imagen de olimpiadas
    ├── entrada.jpeg               # Imagen de entrada del liceo
    ├── inicio.jpeg                # Imagen de inicio
    ├── estudiantes.jpeg           # Imagen de estudiantes
    ├── Imagen1.png                # Estructura organizativa
    └── Imagen3.png                # Ubicación geográfica
```

## Características del Sitio

### Página Principal (index.html)
- **Hero Section**: Banner de bienvenida con llamado a la acción
- **Instalaciones**: Muestra las 4 instalaciones principales del liceo
- **Noticias**: 2 noticias destacadas (Olimpiadas y Nueva Identidad)
- **Contacto**: Formulario de contacto e información de ubicación
- **Footer**: Enlaces rápidos, información de contacto y redes sociales

### Página Institucional (institucion.html)
- **Reseña Histórica**: Historia completa desde 1959 hasta 2025
- **Misión y Visión**: Objetivos y aspiraciones institucionales
- **Ubicación Geográfica**: Mapa y descripción de la ubicación
- **Estructura Organizativa**: Organigrama y listado de personal

### Menú de Navegación con Submenú
- Al pasar el cursor sobre "Nosotros" se despliega un submenú con:
  - Reseña Histórica
  - Misión
  - Visión
  - Ubicación
  - Estructura Organizativa

## Tecnologías Utilizadas

- **HTML5**: Estructura del sitio
- **CSS3**: Estilos y diseño
- **Google Fonts**: Tipografía Montserrat
- **SVG**: Iconos vectoriales

## Características Técnicas

✅ **100% HTML y CSS**: Sin JavaScript
✅ **Diseño Responsivo**: Se adapta a móviles, tablets y escritorio
✅ **Código Comentado**: Todos los archivos están completamente comentados en español
✅ **Estructura Modular**: CSS organizado en archivos separados por funcionalidad
✅ **Navegación Suave**: Smooth scroll nativo de CSS
✅ **Menú Desplegable**: Submenú CSS puro sin JavaScript
✅ **Accesibilidad**: Etiquetas semánticas y alt en imágenes

## Colores Institucionales

- **Azul Principal**: #1e3c72
- **Azul Secundario**: #2a5298
- **Dorado (Acento)**: #ffd700
- **Gris Claro (Fondos)**: #f8f9fa
- **Texto**: #333

## Cómo Usar

1. **Abrir el sitio**:
   - Haz doble clic en `index.html` para abrir la página principal
   - Navega a través del menú para explorar todas las secciones

2. **Personalizar**:
   - Las imágenes se encuentran en la carpeta `images/`
   - Los estilos se pueden modificar en los archivos CSS correspondientes
   - Los textos se pueden editar directamente en los archivos HTML

3. **Subir a un servidor**:
   - Sube todos los archivos y carpetas a tu hosting
   - Asegúrate de mantener la estructura de carpetas intacta
   - El archivo principal debe ser `index.html`

## Navegación del Sitio

- **Inicio**: Página principal con instalaciones y noticias
- **Noticias**: Sección con las últimas noticias del liceo
- **Nosotros**: Menú desplegable con:
  - Reseña Histórica
  - Misión
  - Visión
  - Ubicación
  - Estructura Organizativa
- **Contacto**: Formulario e información de contacto

## Responsive Design

El sitio está optimizado para:
- 📱 **Móviles**: < 480px
- 📱 **Tablets**: 481px - 768px
- 💻 **Escritorio**: > 769px

## Navegadores Compatibles

- ✅ Google Chrome (Recomendado)
- ✅ Mozilla Firefox
- ✅ Microsoft Edge
- ✅ Safari
- ✅ Opera

## Mantenimiento

### Actualizar Noticias
1. Abre `index.html`
2. Busca la sección `<section id="noticias">`
3. Edita el contenido de las tarjetas de noticias

### Actualizar Información Institucional
1. Abre `institucion.html`
2. Busca la sección correspondiente (resena, mision, vision, etc.)
3. Edita el contenido del párrafo

### Cambiar Imágenes
1. Reemplaza la imagen en la carpeta `images/`
2. Usa el mismo nombre de archivo o actualiza la referencia en el HTML

## Información de Contacto del Liceo

- **Dirección**: Calle "Las Flores", Cumanacoa, Municipio Montes, Estado Sucre, Venezuela
- **Teléfono**: 02938381865
- **Email**: luisbeltransanabria1@gmail.com
- **Facebook**: https://www.facebook.com/profile.php?id=100070040366858
- **Horario**: Lunes a Viernes, 7:00 AM - 3:00 PM

## Notas Importantes

- Todo el código está comentado en español para facilitar el mantenimiento
- No se requiere JavaScript para el funcionamiento del sitio
- El diseño es completamente estático (sin bases de datos)
- El formulario de contacto necesita configuración backend para funcionar

## Créditos

Desarrollado para el Liceo 'Luís Beltrán Sanabria'
© 2025 Todos los derechos reservados

---

**Versión**: 1.0
**Fecha**: Enero 2025
**Tecnología**: HTML5 + CSS3 (Sin JavaScript)
