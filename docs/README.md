# AGUARIO - Sitio Web Institucional

![AGUARIO Logo](logo.png)

Sitio web oficial de la **Asociación de Municipios Eco-Subregión del Guájaro, Canal del Dique y Municipios Ribereños del Río Magdalena**.

## 🌊 Descripción

Sitio web institucional moderno y responsive diseñado con enfoque **mobile-first** que presenta los servicios, proyectos y objetivos estratégicos de AGUARIO. El diseño refleja la identidad visual de la organización con colores que evocan naturaleza, agua y desarrollo sostenible.

## ✨ Características

- 🎨 **Diseño Mobile-First**: Optimizado para smartphones, tablets y desktop
- � **Video de Fondo**: Video institucional en la sección hero
- �🎯 **Identidad de Marca**: Colores oficiales y logo de AGUARIO
- 📱 **Menú Hamburguesa**: Navegación intuitiva en dispositivos móviles
- 💬 **Botón WhatsApp Flotante**: Contacto directo (+57 311 603 1497)
- ⚡ **Animaciones Suaves**: Efectos de scroll y hover para mejor UX
- ♿ **Accesible**: Cumple con estándares de accesibilidad web
- 🔍 **SEO Optimizado**: Meta tags y estructura semántica

## 🎨 Paleta de Colores

| Color           | Código Hex | Uso                              |
| --------------- | ---------- | -------------------------------- |
| Azul Turquesa   | `#1B9AAA`  | Color primario, botones, enlaces |
| Azul Oscuro     | `#2E5C7F`  | Títulos, elementos de agua       |
| Verde Oscuro    | `#006838`  | Color secundario, naturaleza     |
| Verde Oliva     | `#8B9456`  | Acentos, tierra                  |
| Amarillo Dorado | `#F5B942`  | Destacados, sol                  |

## 📁 Estructura del Proyecto

```
Aguario/
├── index.html          # Página principal
├── styles.css          # Estilos CSS con diseño responsive
├── script.js           # JavaScript para interactividad
├── logo.png            # Logo oficial de AGUARIO
├── video_aguario.mp4   # Video de fondo para hero section
├── IMAGE_GUIDE.md      # Guía para optimización de imágenes
└── README.md           # Este archivo
```

## 🚀 Instalación y Uso

### Opción 1: Abrir Directamente

1. Descarga o clona el repositorio
2. Abre `index.html` en tu navegador web
3. ¡Listo! El sitio funciona sin necesidad de servidor

### Opción 2: Servidor Local (Recomendado)

```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (npx)
npx serve

# Con PHP
php -S localhost:8000
```

Luego abre `http://localhost:8000` en tu navegador.

## 📱 Secciones del Sitio

1. **Header**: Logo, navegación y botón de contacto
2. **Hero**: Mensaje principal y llamado a la acción
3. **Quiénes Somos**: Propósito, misión, visión y valores
4. **Servicios**: 6 áreas de servicio con iconos
5. **Objetivos Estratégicos**: 6 objetivos numerados
6. **Proyectos**: Casos de éxito y experiencia
7. **Impacto**: Áreas de impacto (ambiental, social, económico, tecnológico)
8. **Footer**: Información de contacto y redes sociales

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Diseño responsive con Flexbox y Grid
- **JavaScript (Vanilla)**: Interactividad sin frameworks
- **Google Fonts**: Tipografía Montserrat
- **Font Awesome 6**: Iconos vectoriales

## 📞 Información de Contacto

- **Dirección**: Calle 95 No. 47 - 143, Barranquilla, Atlántico
- **Teléfono**: +57 311 603 1497
- **Email**: asoaguario@gmail.com
- **NIT**: 901812571-7

## 🎯 Responsive Breakpoints

- **Mobile**: < 768px (diseño de 1 columna)
- **Tablet**: 768px - 1023px (diseño de 2-3 columnas)
- **Desktop**: ≥ 1024px (diseño de 3-4 columnas)

## 🔧 Personalización

### Cambiar Colores

Edita las variables CSS en `styles.css` (líneas 5-14):

```css
:root {
  --color-primary: #1b9aaa;
  --color-secondary: #006838;
  /* ... más colores */
}
```

### Actualizar Contenido

Todo el contenido está en `index.html`. Busca las secciones por sus IDs:

- `#inicio` - Hero
- `#nosotros` - Quiénes Somos
- `#servicios` - Servicios
- `#proyectos` - Proyectos
- `#contacto` - Footer

### Agregar Imágenes

Consulta `IMAGE_GUIDE.md` para recomendaciones sobre optimización y fuentes de imágenes.

## 🌐 Navegadores Compatibles

- ✅ Chrome/Edge (últimas versiones)
- ✅ Firefox (últimas versiones)
- ✅ Safari (últimas versiones)
- ✅ Navegadores móviles (iOS Safari, Chrome Mobile)

## 📝 Licencia

© 2024 AGUARIO. Todos los derechos reservados.

## 👨‍💻 Desarrollo

Sitio desarrollado con tecnologías web modernas siguiendo las mejores prácticas de:

- Diseño responsive mobile-first
- Accesibilidad web (WCAG)
- SEO on-page
- Performance web

---

**AGUARIO** - _Integración para un territorio vivo_ 🌿💧
