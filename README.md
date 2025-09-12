# 🕰️ LuxTime - Página Web de Relojes de Lujo

## 📋 Descripción del Proyecto

**LuxTime** es una página web moderna y elegante dedicada a la exhibición y comercialización de relojes de lujo. El proyecto presenta una experiencia de usuario completa que incluye un catálogo extenso de productos, información corporativa detallada y un sistema de contacto integrado.

La página web está inspirada en la historia y evolución de marcas icónicas como Casio, G-Shock, Baby-G y otras líneas de relojes premium, ofreciendo una experiencia visual atractiva y funcional para los amantes de la relojería.

## ✨ Características Destacadas

- **🎨 Diseño Moderno**: Interfaz elegante con gradientes azules y efectos visuales sofisticados
- **📱 Responsive Design**: Adaptable a todos los dispositivos (desktop, tablet, móvil)
- **🛍️ Catálogo Completo**: Más de 20 productos con información detallada y precios
- **📖 Historia Corporativa**: Timeline interactivo con la evolución de la empresa desde 1946
- **🖼️ Galería Visual**: Mosaico de imágenes históricas y productos icónicos
- **📞 Sistema de Contacto**: Formulario funcional para comunicación con clientes
- **⭐ Sistema de Calificaciones**: Visualización de ratings con estrellas
- **🎯 Navegación Intuitiva**: Menú sticky con transiciones suaves

## 🎯 Objetivo

El objetivo principal de LuxTime es crear una plataforma web que:

1. **Presente productos de relojería** de manera atractiva y profesional
2. **Eduque a los usuarios** sobre la historia y evolución de la relojería digital
3. **Facilite la exploración** de productos con información detallada
4. **Proporcione una experiencia premium** que refleje la calidad de los productos
5. **Mantenga la coherencia visual** en todas las secciones del sitio

## 🛠️ Tecnologías Utilizadas

### Frontend
- **HTML5**: Estructura semántica y accesible
- **CSS3**: Estilos avanzados con variables CSS, flexbox y grid

### Características CSS
- **CSS Variables**: Sistema de colores y estilos centralizados
- **Flexbox & Grid**: Layouts modernos y responsivos
- **Animaciones**: Transiciones suaves y efectos hover
- **Gradientes**: Fondos con gradientes lineales y radiales
- **Sombras**: Sistema de sombras para profundidad visual

### Estructura de Archivos
- **Organización modular**: CSS separado por funcionalidad
- **Imágenes optimizadas**: Formatos AVIF, PNG y JPEG
- **Navegación relativa**: Enlaces optimizados para diferentes rutas

## 📁 Estructura del Sistema

```
Pagina de reloj/
├── 📄 index.html                 # Página principal
├── 📁 html/                      # Páginas secundarias
│   ├── catalogo.html            # Catálogo de productos
│   ├── empresa.html             # Historia corporativa
│   ├── contacto.html            # Formulario de contacto
│   └── 📁 detalles/             # Páginas de productos individuales
│       ├── 1.detalle.html       # Detalle producto 1
│       ├── 2.detalle.html       # Detalle producto 2
│       └── ... (hasta 20.detalle.html)
├── 📁 css/                      # Hojas de estilo
│   ├── variables.css            # Variables CSS globales
│   ├── common.css               # Estilos comunes (header, footer)
│   ├── syle.css                 # Estilos de la página principal
│   ├── catalogo.css             # Estilos del catálogo
│   ├── empresa.css              # Estilos de la página empresa
│   ├── contacto.css             # Estilos del formulario de contacto
│   └── 📁 detalle/              # Estilos de páginas de detalle
│       └── 1.destalle.css       # Estilos para páginas de detalle
└── 📁 images/                   # Recursos gráficos
    ├── 📁 catalogo/             # Imágenes de productos
    ├── 📁 detalles/             # Imágenes detalladas de productos
    ├── 📁 galeria/              # Imágenes históricas
    ├── 📁 inicio/               # Imágenes de la página principal
    └── *.png, *.avif, *.jpeg   # Imágenes generales
```

## 📝 Qué hace cada archivo?

### Páginas HTML

#### `index.html`
- **Página principal** con hero section y carrusel de imágenes
- **Sección de recomendaciones** con 6 productos destacados
- **Historia corporativa** completa con timeline interactivo
- **Footer** con información de contacto y desarrollador

#### `html/catalogo.html`
- **Catálogo completo** con 20 productos organizados en grid
- **Información de stock** (disponible/agotado)
- **Enlaces a páginas de detalle** individuales
- **Navegación** hacia otras secciones

#### `html/empresa.html`
- **Timeline interactivo** con hitos históricos desde 1946
- **Galería visual** con mosaico de imágenes históricas
- **Navegación por años** con botones de acceso rápido
- **Información corporativa** detallada

#### `html/contacto.html`
- **Formulario de contacto** con validación
- **Campos**: nombre, email, teléfono, mensaje
- **Diseño responsive** y accesible

#### `html/detalles/1-20.detalle.html`
- **Páginas individuales** para cada producto
- **Información detallada** del reloj específico
- **Galería de imágenes** del producto
- **Especificaciones técnicas** y características

### Archivos CSS

#### `css/variables.css`
- **Variables CSS globales** para colores, sombras y transiciones
- **Sistema de colores** basado en azules (#2563eb, #1e40af)
- **Configuración centralizada** para mantener consistencia

#### `css/common.css`
- **Estilos del header** con navegación sticky
- **Estilos del footer** con información corporativa
- **Componentes reutilizables** como botones y cards
- **Sistema de navegación** con efectos hover

#### `css/syle.css`
- **Estilos de la página principal** (index.html)
- **Hero section** con carrusel de imágenes
- **Sección de recomendaciones** con grid de productos
- **Historia corporativa** con timeline y estadísticas

#### `css/catalogo.css`
- **Grid de productos** responsive
- **Cards de productos** con información y precios
- **Estados de stock** (disponible/agotado)
- **Hero section** específico del catálogo

#### `css/empresa.css`
- **Timeline interactivo** con navegación por años
- **Galería en mosaico** con efectos overlay
- **Animaciones** para elementos de la línea de tiempo
- **Responsive design** para diferentes dispositivos

#### `css/contacto.css`
- **Formulario de contacto** con estilos modernos
- **Validación visual** de campos
- **Layout responsive** para móviles
- **Efectos de focus** y hover

#### `css/detalle/1.destalle.css`
- **Estilos para páginas de detalle** de productos
- **Galería de imágenes** del producto
- **Layout de información** técnica y comercial
- **Componentes específicos** para detalles de productos

### Recursos Gráficos

#### `images/catalogo/`
- **Imágenes de productos** en formato PNG
- **Nombres descriptivos** con códigos de modelo
- **Optimización** para web

#### `images/detalles/`
- **Imágenes detalladas** en formatos AVIF y PNG
- **Múltiples ángulos** de cada producto
- **Alta resolución** para zoom

#### `images/galeria/`
- **Imágenes históricas** de la empresa
- **Fotografías de productos** icónicos
- **Contenido visual** para la sección de historia

## Wireframe

![](https://i.ibb.co/nhkV8ZC/Lux-Time-Wireframe-pdf.png)






![](https://i.ibb.co/FGRWpwt/Wireframe-Cat-logo-de-Relojes-pdf.png)







![](https://i.ibb.co/PZ8WTbdQ/Lux-Time-Product-Page-Wireframe-pdf.png)






![](https://i.ibb.co/cKzt0hhH/Wireframe-Historia-de-la-Empresa-Lux-Time-pdf.png)









![](https://i.ibb.co/fVHrN5rT/Wireframe-Lux-Time-Contacto-pdf.png)









## Netifly



## ✍️ Autores

Desarrollado por: Valentina Mancilla

