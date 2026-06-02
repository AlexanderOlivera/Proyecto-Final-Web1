# 🍽️ Corazón de Agave - Restaurante Digital

![HTML](https://img.shields.io/badge/HTML-79.5%25-orange)
![CSS](https://img.shields.io/badge/CSS-20.5%25-blue)
![License](https://img.shields.io/badge/license-Open-brightgreen)
![Repository Status](https://img.shields.io/badge/status-Active-success)
![Last Update](https://img.shields.io/badge/updated-Junio%202026-blue)

## 📋 Descripción

**Corazón de Agave** es un proyecto de sitio web para un restaurante elegante y minimalista, desarrollado como trabajo final del curso de **Programación Web**. El proyecto presenta una interfaz moderna, responsive y user-friendly con navegación intuitiva y un diseño sofisticado basado en colores naturales de agave y dorado.

### Información del Proyecto
- **Autores**: Alexander e Ivan
- **Materia**: Programación Web
- **Año**: 2026
- **Tipo**: Proyecto final de curso
- **Estado**: ✅ Completado y activo
- **Repositorio**: [AlexanderOlivera/Proyecto-Final-Web1](https://github.com/AlexanderOlivera/Proyecto-Final-Web1)
- **GitHub Pages**: Disponible en repositorio

---

## 🎯 Características Principales

- ✅ **Diseño minimalista y elegante** - Interfaz limpia con colores sofisticados
- ✅ **Menú Digital** - Visualización de platillos con precios y tamaños
- ✅ **Navegación intuitiva** - Acceso fácil a diferentes secciones
- ✅ **Galería de imágenes** - Showcasing de platillos y ambiente
- ✅ **Sección de promociones** - Ofertas especiales
- ✅ **Diseño responsive** - Compatible con dispositivos móviles y tablets
- ✅ **Paleta de colores profesional** - Verde agave y dorado
- ✅ **Optimización SEO** - Meta tags y estructura semántica
- ✅ **Accesibilidad** - Navegación clara y legibilidad

---

## 📁 Estructura del Proyecto

```
Proyecto-Final-Web1/
├── index.html                          # Página principal (Inicio)
├── css/
│   └── estilos.css                    # Estilos globales del sitio
├── img/
│   └── logo-sin-fondo.png             # Logo del restaurante
├── inedex de navegacion/              # Sección de páginas internas
│   ├── menu.html                      # Página del menú
│   ├── galeria.html                   # Galería de imágenes
│   └── promociones.html               # Promociones especiales
├── .vscode/                           # Configuración de VSCode
├── README.md                          # Documentación del proyecto
└── .gitignore                         # Archivos a ignorar en git
```

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Uso | Porcentaje | Estado |
|-----------|-----|-----------|--------|
| **HTML5** | Estructura y contenido | 79.5% | ✅ Activo |
| **CSS3** | Estilos y diseño | 20.5% | ✅ Activo |

### Características Técnicas:
- **Semántica HTML5** - Uso correcto de etiquetas semánticas (`<header>`, `<nav>`, `<main>`, `<footer>`)
- **CSS Grid y Flexbox** - Layouts modernos y responsivos
- **Variables CSS** - Sistema de colores personalizado y reutilizable
- **Media Queries** - Diseño adaptable a diferentes tamaños de pantalla (móvil, tablet, desktop)
- **Meta tags** - Optimización SEO y compatibilidad
- **Transiciones CSS** - Efectos suaves en interacciones
- **Box Shadows** - Profundidad visual en componentes

---

## 🎨 Paleta de Colores

El diseño utiliza una paleta de colores sofisticada y elegante inspirada en la naturaleza:

| Color | Código | Uso | Aplicación |
|-------|--------|-----|-----------|
| Fondo | `#fbfbfb` | Fondo general de la página | Mantiene claridad |
| Texto | `#333333` | Color de texto principal | Excelente legibilidad |
| Acento Verde Agave | `#2c5e3b` | Títulos y elementos destacados | Identidad visual |
| Dorado | `#c5a059` | Acentos y efectos hover | Elegancia |
| Blanco | `#ffffff` | Encabezado y tarjetas | Contraste |

---

## 📄 Descripción de Páginas

### 🏠 **Inicio (index.html)**
- Página principal y punto de entrada del sitio
- Mensaje de bienvenida y presentación de la marca
- Descripción de la experiencia culinaria del restaurante
- Navegación principal a todas las secciones
- Hero section con llamada a la acción
- **Componentes**: Header, Hero, Footer

### 🍴 **Menú (menu.html)**
- Visualización dinámica de platos principales
- Cards de platillos con diseño grid responsive
- Información completa de cada platillo:
  - Imagen del plato
  - Nombre y descripción
  - Opciones de tamaño
  - Precios por tamaño
- Layout en grid que se adapta a dispositivos
- Efectos hover para mejorar UX

### 🖼️ **Galería (galeria.html)**
- Galería visual del ambiente del restaurante
- Showcasing de la experiencia gastronómica
- Imágenes de platillos destacados
- Diseño visual atractivo y profesional
- Layout responsivo en grid

### 🎉 **Promociones (promociones.html)**
- Ofertas especiales y descuentos vigentes
- Promociones del restaurante
- Sección dinámica para campañas estacionales
- Llamadas a la acción destacadas

---

## 🔧 Características del CSS

### Sistema de Diseño
- **Reset CSS** - Normalización de márgenes y paddings
- **Variables CSS** - Sistema de colores consistente y mantenible
- **Grid Layout** - Header con 3 columnas para navegación equilibrada
- **Flexbox** - Navegación y tarjetas con distribución flexible
- **Transitions** - Efectos suaves en todas las interacciones
- **Mobile First** - Enfoque responsive desde dispositivos pequeños

### Componentes Principales

#### Header
```css
- Grid de 3 columnas (Título | Logo | Navegación)
- Logo escalado 1.8x con bordes redondeados
- Efecto hover en elementos de navegación
- Sombra sutil (0 2px 5px) para profundidad
- Altura fija: 80px
- Fondo blanco con transiciones suaves
```

#### Tarjetas de Platillos
```css
- Cards con border radius y border 2px
- Efecto hover: elevación (translateY -5px)
- Box shadow dinámica en hover
- Imagen con height fijo (200px)
- Información estructurada de tamaños y precios
- Padding y espaciado consistente
```

#### Footer
```css
- Fondo con color acento (verde agave #2c5e3b)
- Texto blanco para alto contraste
- Centrado y padding generoso
- Créditos a autores y materia
- Año de creación visible
```

---

## 📱 Responsividad

El sitio está diseñado para ser completamente responsivo utilizando:

### Técnicas Implementadas
- **Media Queries** - Breakpoints en 768px (tablet) y 1024px (desktop)
- **CSS Grid** - `auto-fit` y `minmax()` para layouts fluidos
- **Viewport Meta Tag** - Escala correcta en dispositivos móviles
- **Font Sizes Relativos** - Uso de `rem` y porcentajes para escalabilidad
- **Flexible Images** - Imágenes que se adaptan al contenedor

### Breakpoints
- **Móvil**: 320px - 767px
- **Tablet**: 768px - 1023px
- **Desktop**: 1024px+

---

## 🚀 Cómo Usar

### Ver en tu navegador
1. Clona el repositorio:
   ```bash
   git clone https://github.com/AlexanderOlivera/Proyecto-Final-Web1.git
   ```

2. Abre `index.html` en tu navegador preferido (Chrome, Firefox, Safari, Edge)

3. Navega por las diferentes secciones usando el menú principal

4. Prueba la responsividad redimensionando la ventana o usando dispositivos móviles

### Editar el proyecto
1. Abre los archivos en tu editor de código favorito (VSCode, Sublime Text, etc.)
2. Modifica HTML en `index.html` y archivos en `inedex de navegacion/`
3. Actualiza estilos en `css/estilos.css`
4. Guarda y recarga la página (F5 o Ctrl+R)

### Cargar en GitHub Pages
1. Ve a Settings > Pages
2. Selecciona la rama `main` como source
3. El sitio estará disponible en: `https://AlexanderOlivera.github.io/Proyecto-Final-Web1/`

---

## 🐛 Notas sobre el Proyecto

### Puntos a considerar:
- ⚠️ El nombre de la carpeta `inedex de navegacion` contiene un error de ortografía (debería ser `index` o `navegacion`)
- ℹ️ Los menús tienen rutas relativas que funcionan correctamente con la estructura actual
- ℹ️ Las imágenes externas se obtienen de URLs de búsqueda (considerar descargar localmente en producción)
- ✅ El proyecto es completamente funcional sin dependencias externas

### Mejoras futuras sugeridas:
- [ ] Renombrar la carpeta `inedex de navegacion` a `pages` o `navegacion`
- [ ] Guardar imágenes localmente en lugar de URLs externas
- [ ] Agregar formulario de contacto interactivo
- [ ] Implementar JavaScript para interactividad adicional
- [ ] Agregar animaciones CSS avanzadas
- [ ] Implementar carrito de compras
- [ ] Crear base de datos de menú dinámico
- [ ] Agregar página de reservaciones
- [ ] Implementar búsqueda de platillos
- [ ] Agregar testimonios de clientes
- [ ] Integrar sistema de pedidos

---

## 📝 Metaetiquetas SEO

El proyecto incluye metaetiquetas importantes para optimización:
- **Description**: Descripción del restaurante y propuesta de valor
- **Keywords**: Términos relevantes para búsqueda (restaurante, comida, agave, etc.)
- **Author**: Crédito a Alexander e Ivan
- **Viewport**: `width=device-width, initial-scale=1` para adaptabilidad
- **Charset**: UTF-8 para caracteres especiales

---

## 📊 Estadísticas del Proyecto

- **Creación**: Junio 2, 2026
- **Lenguaje principal**: HTML (79.5%)
- **Estilos**: CSS (20.5%)
- **Archivos HTML**: 4 (index + 3 páginas internas)
- **Archivo CSS**: 1 (estilos globales)
- **Imágenes**: 1+ (logo + contenido)

---

## 📧 Contacto y Créditos

- **Desarrolladores**: Alexander e Ivan
- **Proyecto**: Programación Web - Proyecto Final
- **Institución**: [Tu institución educativa]
- **Año**: 2026
- **Repositorio**: [GitHub](https://github.com/AlexanderOlivera/Proyecto-Final-Web1)

---

## 📄 Licencia

Este proyecto es de código abierto y está disponible públicamente en GitHub bajo licencia Open.

---

## 📝 Historial de Actualizaciones

### v1.0 - Junio 2, 2026
- ✅ Creación inicial del proyecto
- ✅ Estructura HTML5 completa
- ✅ Sistema de estilos CSS con Grid y Flexbox
- ✅ 4 páginas principales (Inicio, Menú, Galería, Promociones)
- ✅ Diseño responsive
- ✅ Paleta de colores profesional
- ✅ Documentación completa en README.md

---

**Última actualización**: Junio 2, 2026 - 02:05:57 UTC

*Proyecto completado y disponible públicamente* ✨
