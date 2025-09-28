# 🌸 Carolina Spa - Sitio Web Profesional

![Carolina Spa](build/img/logo.svg)

## 📋 Descripción del Proyecto

**Carolina Spa** es un sitio web moderno y elegante diseñado para un spa y salón de belleza. La aplicación presenta una interfaz limpia y profesional que permite a los clientes conocer los servicios, productos y horarios del establecimiento, además de facilitar la reserva de citas.

### ✨ Características Principales

- **Diseño Responsivo**: Optimizado para dispositivos móviles, tablets y escritorio
- **Slider Interactivo**: Presentación visual atractiva con efecto cubo
- **Galería de Productos**: Catálogo visual de productos y servicios
- **Horarios de Atención**: Tabla informativa de horarios semanales
- **Sistema de Citas**: Sección dedicada para reservas
- **Integración Social**: Enlaces a redes sociales principales
- **Optimización de Imágenes**: Formatos modernos (AVIF, WebP) para mejor rendimiento

## 🚀 Funcionalidades

### 🏠 Página Principal
- **Header**: Logo del spa y enlaces a redes sociales
- **Navegación**: Menú principal con secciones (Inicio, Nosotros, Servicios, Productos, Contacto)
- **Slider**: Carrusel de imágenes con efecto cubo 3D
- **Bienvenida**: Mensaje de acogida personalizado

### 📱 Secciones Principales
- **Cards de Servicios**: Tres tarjetas principales con enlaces a más información
- **Horarios**: Tabla completa de horarios de atención semanal
- **Productos**: Grid responsivo con catálogo de productos
- **Citas**: Sección para reserva de citas con llamada a la acción
- **Footer**: Información de contacto, horarios y redes sociales

### 🎨 Características de Diseño
- **Metodología BEM**: Nomenclatura consistente para CSS
- **CSS Grid y Flexbox**: Layouts modernos y responsivos
- **Tipografía Elegante**: Fuentes Google Fonts (Italianno, Lato)
- **Paleta de Colores**: Diseño sofisticado y relajante
- **Efectos Visuales**: Transiciones suaves y efectos hover

## 🛠️ Tecnologías Utilizadas

### Frontend
- **HTML5**: Estructura semántica y accesible
- **CSS3**: Estilos modernos con Grid y Flexbox
- **SASS/SCSS**: Preprocesador CSS con arquitectura modular
- **JavaScript (ES6+)**: Interactividad y funcionalidades dinámicas
- **Swiper.js**: Biblioteca para sliders y carruseles

### Herramientas de Desarrollo
- **Gulp**: Automatización de tareas de desarrollo
- **PostCSS**: Procesamiento de CSS con autoprefixer
- **Source Maps**: Depuración de código fuente
- **CSSnano**: Minificación y optimización de CSS

### Optimización de Imágenes
- **Gulp Imagemin**: Compresión de imágenes
- **WebP**: Formato de imagen moderno y eficiente
- **AVIF**: Formato de imagen de próxima generación
- **Lazy Loading**: Carga diferida de imágenes

### Fuentes y Recursos
- **Google Fonts**: Tipografías web optimizadas
- **SVG**: Iconos vectoriales escalables
- **CDN**: Recursos externos optimizados

## 📊 Rendimiento y Optimización

### 🚀 Optimizaciones Implementadas
- **Imágenes Optimizadas**: Formatos AVIF y WebP con fallback a JPG
- **CSS Minificado**: Reducción del tamaño de archivos CSS
- **Lazy Loading**: Carga diferida de imágenes para mejorar velocidad
- **Source Maps**: Facilitan la depuración en desarrollo
- **Autoprefixer**: Compatibilidad automática con navegadores

### 📈 Métricas de Rendimiento
- **Tiempo de Carga**: Optimizado para carga rápida
- **SEO Friendly**: Estructura semántica y meta tags apropiados
- **Accesibilidad**: Navegación accesible y texto alternativo
- **Responsive Design**: Adaptable a todos los dispositivos

## 🏗️ Arquitectura del Proyecto

```
CarolinaSpa/
├── build/                 # Archivos compilados y optimizados
│   ├── css/              # CSS compilado y minificado
│   └── img/              # Imágenes optimizadas (JPG, WebP, AVIF)
├── src/                  # Código fuente
│   ├── scss/             # Archivos SASS/SCSS
│   │   ├── base/         # Variables, mixins, normalización
│   │   ├── ui/           # Componentes de interfaz
│   │   └── app.scss      # Archivo principal
│   └── img/              # Imágenes originales
├── js/                   # JavaScript
├── index.html            # Página principal
├── gulpfile.js           # Configuración de Gulp
└── package.json          # Dependencias del proyecto
```

## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js (versión 14 o superior)
- npm (Node Package Manager)

### Pasos de Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/carolina-spa.git
   cd carolina-spa
   ```

2. **Instalar dependencias**
   ```bash
   npm install
   ```

3. **Ejecutar en modo desarrollo**
   ```bash
   npm run dev
   ```

4. **Compilar para producción**
   ```bash
   gulp
   ```

### Comandos Disponibles
- `npm run dev`: Inicia el servidor de desarrollo con watch
- `gulp css`: Compila solo los archivos CSS
- `gulp imagenes`: Optimiza las imágenes
- `gulp versionWebp`: Convierte imágenes a formato WebP
- `gulp versionAvif`: Convierte imágenes a formato AVIF

## 🎯 Características Técnicas

### Metodología BEM
El proyecto utiliza la metodología BEM (Block Element Modifier) para una nomenclatura CSS consistente y mantenible:

```scss
.block__element--modifier {
  // Estilos del componente
}
```

### Estructura SASS Modular
- **Variables**: Colores, tipografías y medidas
- **Mixins**: Funciones reutilizables
- **Componentes**: Estilos modulares por sección
- **Base**: Normalización y estilos globales

### Responsive Design
- **Mobile First**: Diseño optimizado para móviles
- **Breakpoints**: Adaptación a diferentes tamaños de pantalla
- **Grid System**: Layout flexible y responsivo

## 👨‍💻 Autor del Proyecto

**JEB$DEV de Javier Berchtold**

- **Desarrollador Frontend**: Especializado en tecnologías web modernas
- **Metodología**: BEM, SASS, Gulp, CSS Grid
- **Enfoque**: Desarrollo de sitios web profesionales y optimizados

## 📄 Licencia

Este proyecto está bajo la Licencia ISC. Ver el archivo `package.json` para más detalles.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para cambios importantes:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📞 Contacto

Para más información sobre el proyecto o servicios de desarrollo web:

- **Proyecto**: Carolina Spa & Salon
- **Desarrollador**: JEB$DEV de Javier Berchtold
- **Tecnologías**: HTML5, CSS3, SASS, JavaScript, Gulp

---

⭐ **¡Dale una estrella al proyecto si te gusta!** ⭐
