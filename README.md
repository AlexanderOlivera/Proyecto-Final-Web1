# 🍽️ Corazón de Agave - Restaurante Digital

![HTML](https://img.shields.io/badge/HTML-79.5%25-orange)
![CSS](https://img.shields.io/badge/CSS-20.5%25-blue)
![License](https://img.shields.io/badge/license-Open-brightgreen)

## 📋 Descripción

**Corazón de Agave** es un proyecto de sitio web para un restaurante elegante y minimalista, desarrollado como trabajo final del curso de **Programación Web**. El proyecto presenta una interfaz moderna y responsiva que permite a los clientes explorar el menú, ver promociones y galería de platillos.

### Información del Proyecto
- **Autores**: Alexander e Ivan
- **Materia**: Programación Web
- **Año**: 2026
- **Tipo**: Proyecto final de curso
- **Repositorio**: [AlexanderOlivera/Proyecto-Final-Web1](https://github.com/AlexanderOlivera/Proyecto-Final-Web1)

---

## 🎯 Características Principales

- ✅ **Diseño minimalista y elegante** - Interfaz limpia con colores sofisticados
- ✅ **Menú Digital** - Visualización de platillos con precios y tamaños
- ✅ **Navegación intuitiva** - Acceso fácil a diferentes secciones
- ✅ **Galería de imágenes** - Showcasing de platillos y ambiente
- ✅ **Sección de promociones** - Ofertas especiales
- ✅ **Diseño responsive** - Compatible con dispositivos móviles
- ✅ **Paleta de colores profesional** - Verde agave y dorado

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
└── README.md                          # Este archivo
```

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Uso | Porcentaje |
|-----------|-----|-----------|
| **HTML5** | Estructura y contenido | 79.5% |
| **CSS3** | Estilos y diseño | 20.5% |

### Características Técnicas:
- **Semántica HTML5** - Uso correcto de etiquetas semánticas
- **CSS Grid y Flexbox** - Layouts modernos y responsivos
- **Variables CSS** - Sistema de colores personalizado
- **Media Queries** - Diseño adaptable a diferentes pantallas
- **Meta tags** - Optimización SEO y compatibilidad

---

## 🎨 Paleta de Colores

El diseño utiliza una paleta de colores sofisticada y elegante:

| Color | Código | Uso |
|-------|--------|-----|
| Fondo | `#fbfbfb` | Fondo general de la página |
| Texto | `#333333` | Color de texto principal |
| Acento (Verde Agave) | `#2c5e3b` | Títulos y elementos destacados |
| Dorado | `#c5a059` | Acentos y efectos hover |
| Blanco | `#ffffff` | Encabezado y tarjetas |

---

## 📄 Descripción de Páginas

### 🏠 **Inicio (index.html)**
- Página principal del sitio
- Mensaje de bienvenida y presentación del restaurante
- Descripción de la experiencia culinaria
- Navegación principal a todas las secciones

### 🍴 **Menú (menu.html)**
- Visualización de platos principales
- Cards de platillos con:
  - Imagen del plato
  - Nombre y descripción
  - Opciones de tamaño
  - Precios por tamaño
- Layout en grid responsivo

### 🖼️ **Galería (galeria.html)**
- Galería visual del ambiente y platillos
- Showcasing de la experiencia gastronómica
- Diseño visual atractivo

### 🎉 **Promociones (promociones.html)**
- Ofertas especiales y descuentos
- Promociones del restaurante
- Sección dinámica para campañas

---

## 🔧 Características del CSS

### Sistema de Diseño
- **Reset CSS** - Restablecimiento de márgenes y paddings
- **Variables CSS** - Sistema de colores consistente
- **Grid Layout** - Header con 3 columnas
- **Flexbox** - Navegación y tarjetas
- **Transitions** - Efectos suaves en interacciones

### Componentes Principales

#### Header
```css
- Grid de 3 columnas (Título | Logo | Navegación)
- Logo escalado 1.8x
- Efecto hover en navegación
- Sombra sutil (0 2px 5px)
```

#### Tarjetas de Platillos
```css
- Cards con border y border-radius
- Hover: elevación (translateY -5px)
- Imagen con height fijo (200px)
- Información de tamaños y precios
```

#### Footer
```css
- Fondo con color acento (verde agave)
- Texto blanco
- Centrado
- Créditos a autores y materia
```

---

## 📱 Responsividad

El sitio está diseñado para ser responsivo utilizando:
- **Media Queries** - Adaptación a diferentes tamaños
- **CSS Grid** - `auto-fit` y `minmax()` para layouts fluidos
- **Viewport Meta Tag** - Escala correcta en dispositivos móviles
- **Font Sizes Relativos** - Uso de `rem` y porcentajes

---

## 🚀 Cómo Usar

### Ver en tu navegador
1. Clona el repositorio:
   ```bash
   git clone https://github.com/AlexanderOlivera/Proyecto-Final-Web1.git
   ```

2. Abre `index.html` en tu navegador preferido

3. Navega por las diferentes secciones usando el menú principal

### Editar el proyecto
1. Abre los archivos en tu editor de código favorito
2. Modifica HTML en `index.html` y archivos en `inedex de navegacion/`
3. Actualiza estilos en `css/estilos.css`
4. Guarda y recarga la página

---

## 🐛 Notas sobre el Proyecto

### Puntos a considerar:
- El nombre de la carpeta `inedex de navegacion` contiene un error de ortografía (debería ser `index`)
- Los menús tienen rutas relativas que funcionan correctamente con la estructura actual
- Las imágenes externas se obtienen de URLs de búsqueda (considerar descargar localmente en producción)

### Mejoras futuras sugeridas:
- [ ] Renombrar la carpeta `inedex de navegacion` a `navegacion` o `pages`
- [ ] Guardar imágenes localmente en lugar de URLs externas
- [ ] Agregar formulario de contacto
- [ ] Implementar JavaScript para interactividad adicional
- [ ] Agregar animaciones CSS avanzadas
- [ ] Implementar carrito de compras
- [ ] Agregar base de datos de menú
- [ ] Crear página de reservaciones

---

## 📝 Metaetiquetas SEO

El proyecto incluye metaetiquetas importantes para optimización:
- **Description**: Descripción del restaurante
- **Keywords**: Términos relevantes para búsqueda
- **Author**: Crédito a los autores
- **Viewport**: Adaptabilidad a dispositivos móviles

---

## 📧 Contacto y Créditos

- **Desarrolladores**: Alexander e Ivan
- **Proyecto**: Programación Web - Proyecto Final
- **Año**: 2026
- **Repositorio**: [GitHub](https://github.com/AlexanderOlivera/Proyecto-Final-Web1)

---

## 📄 Licencia

Este proyecto es de código abierto y está disponible públicamente en GitHub.

---

**Última actualización**: Junio 2026

