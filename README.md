# EMEDE - One Page Landing

Una landing page moderna y minimalista para la consultora de reclutamiento EMEDE, diseñada con HTML5, CSS3 y JavaScript vanilla.

## 🎨 Características del Diseño

- **Diseño Minimalista**: Estilo clean con mucho espacio en blanco
- **Colores Oficiales EMEDE**: Paleta basada en los colores de marca oficiales
- **Responsive**: Optimizado para todos los dispositivos
- **Animaciones Suaves**: Transiciones y efectos visuales elegantes
- **Tipografía Oficial**: Lato para texto y Montserrat para títulos según manual de marca

## 📱 Secciones Incluidas

1. **Header/Navegación**: Menú fijo con navegación suave
2. **Hero Section**: Llamada a la acción principal con animación
3. **Quiénes Somos**: Información de la empresa con estadísticas
4. **Servicios**: Grid de servicios con iconos y descripciones
5. **Etapas del Proceso**: Timeline del proceso de reclutamiento
6. **Clientes**: Carousel de marcas de clientes
7. **Contacto**: Formulario de contacto con validación
8. **Footer**: Información adicional y enlaces

## 🚀 Funcionalidades JavaScript

- **Navegación Móvil**: Menú hamburguesa responsive
- **Carousel de Clientes**: Carrusel automático con controles manuales
- **Formulario de Contacto**: Validación en tiempo real y estados de carga
- **Animaciones al Scroll**: Efectos de aparición al hacer scroll
- **Scroll Suave**: Navegación fluida entre secciones
- **Botón Volver Arriba**: Acceso rápido al inicio
- **Notificaciones**: Sistema de notificaciones para feedback

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: 
  - Grid y Flexbox para layouts
  - Variables CSS para consistencia
  - Animaciones y transiciones
  - Media queries para responsive design
- **JavaScript ES6+**:
  - Intersection Observer API
  - Touch events para móviles
  - Form validation
  - Carousel functionality

## 📁 Estructura de Archivos

```
landing-emede/
├── index.html              # Página principal
├── css/
│   └── styles.css          # Estilos CSS
├── js/
│   └── script.js           # Funcionalidad JavaScript
├── assets/
│   ├── images/             # Imágenes del proyecto
│   └── docs/               # Documentación de marca
├── .git/                   # Control de versiones
├── .gitattributes          # Configuración Git
└── README.md               # Documentación del proyecto
```

## 🎯 Paleta de Colores Oficiales EMEDE

- **Púrpura Principal**: `#7745DB` (Color más distintivo - creatividad, sabiduría y ambición)
- **Azul Profundo**: `#080DB5` (Confianza, seguridad y profesionalismo)
- **Púrpura Profundo**: `#6445A6` (Tono de transición y contraste)
- **Variaciones Pastel**: Versiones suavizadas para fondos y elementos decorativos
- **Texto Primario**: `#1A1A1A` (Negro suave)
- **Texto Secundario**: `#4A4A4A` (Gris medio)

## 📱 Responsive Breakpoints

- **Mobile**: ≤ 480px
- **Tablet**: ≤ 768px
- **Desktop**: ≤ 1024px
- **Large Desktop**: > 1024px

## 🔧 Personalización

### Cambiar Colores
Modifica las variables CSS en `:root` dentro de `styles.css`:

```css
:root {
    --primary-color: #7745DB; /* Púrpura Principal */
    --secondary-color: #080DB5; /* Azul Profundo */
    --accent-color: #6445A6; /* Púrpura Profundo */
    /* ... más variables */
}
```

### Agregar Contenido
1. **Servicios**: Edita la sección `.services-grid` en `index.html` (8 servicios específicos de EMEDE)
2. **Clientes**: Modifica el carousel en la sección `.clients`
3. **Información de Contacto**: Actualiza la sección `.contact-info`
4. **Equipo**: Información de Mariela Ceñal y Daniela Carrano

### Configurar Formulario PHP
El formulario está listo para integrar con PHP. Los campos incluyen:
- `name` (requerido)
- `email` (requerido)
- `phone` (opcional)
- `company` (opcional)
- `position` (opcional - posición que buscan cubrir)
- `message` (requerido - detalles de la búsqueda)

## 🚀 Próximos Pasos

1. **Integración PHP**: Agregar backend para procesar el formulario
2. **Base de Datos**: Conectar con MySQL/PostgreSQL para almacenar consultas
3. **Email**: Configurar envío automático de emails
4. **Analytics**: Integrar Google Analytics o similar
5. **SEO**: Optimizar meta tags y estructura semántica

## 📞 Información de Contacto

- **Teléfono**: +54 11 1234-5678
- **Email**: info@emede.com.ar
- **Dirección**: Av. Corrientes 1234, CABA

## 📄 Licencia

Este proyecto está desarrollado específicamente para EMEDE. Todos los derechos reservados.

---

**Desarrollado con ❤️ para EMEDE Consultora de Reclutamiento**
