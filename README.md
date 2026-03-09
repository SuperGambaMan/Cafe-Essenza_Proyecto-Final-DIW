# ☕ Café Essenza

> Proyecto Final - Diseño de Interfaces Web (DIW)

Sitio web responsive para una cafetería moderna que ofrece una experiencia completa de navegación, visualización de productos, pedidos online y sistema de reservas.

## 📋 Descripción

**Café Essenza** es un proyecto web desarrollado con Bootstrap 5 y SCSS personalizado que simula el sitio web de una cafetería premium. El diseño combina elegancia y funcionalidad con una paleta de colores cálidos que reflejan la esencia del café.

## ✨ Características

- 🎨 **Diseño responsive** adaptado a todos los dispositivos
- 🍰 **Carta digital** con productos categorizados (bebidas calientes, frías y repostería)
- 🛒 **Sistema de pedido online** con carrito de compras
- 📅 **Reservas de mesa** con formulario interactivo
- 👤 **Sistema de registro** de usuarios
- 🎯 **Navegación intuitiva** con menú responsive
- 💳 **Métodos de pago** integrados (Bizum, PayPal, tarjeta)

## 🗂️ Estructura del Proyecto

```
Café-Essenza/
├── pages/                    # Páginas HTML
│   ├── home.html            # Página principal
│   ├── carta.html           # Menú de productos
│   ├── pedido-online.html   # Carrito y pedidos
│   ├── reservas.html        # Sistema de reservas
│   └── sobre-nosotros.html  # Información del negocio
├── scss/                     # Archivos SCSS de Bootstrap personalizados
│   ├── _variables.scss      # Variables personalizadas
│   ├── bootstrap.scss       # Bootstrap principal
│   ├── forms/              # Estilos de formularios
│   ├── helpers/            # Utilidades
│   ├── mixins/             # Mixins de Bootstrap
│   └── utilities/          # Utilidades API
├── dist/                     # CSS compilado
│   └── css/
│       └── bootstrap.css
├── img/                      # Recursos gráficos
│   ├── Logo.png
│   ├── productos/           # Imágenes de productos
│   └── iconos/              # Iconos del sitio
└── mapas-bootstrap.md       # Documentación de customización
```

## 🎨 Personalización de Bootstrap

Este proyecto utiliza una personalización completa de Bootstrap mediante variables y mapas SCSS, sin necesidad de CSS personalizado adicional.

### Paleta de Colores

El proyecto define una paleta de colores personalizada inspirada en los tonos del café:

```scss
$brown: #a67c52;           // Marrón principal
$beige: #f5ede3;           // Beige suave
$accent: #3e2723;          // Marrón oscuro (acento)
$essenza-green: #7DAF9C;   // Verde característico
```

### Colores del Tema

```scss
$primary: $accent          // Marrón oscuro (#3e2723)
$secondary: $brown         // Marrón claro (#a67c52)
$success: $essenza-green   // Verde Essenza (#7DAF9C)
$light: $beige             // Beige (#f5ede3)
$dark: $gray-900           // Gris oscuro de Bootstrap
```

### Tipografía

- **Fuente principal**: Roboto (sans-serif)
- **Fuente de títulos**: Playfair Display (serif)
- **Color de texto**: `$accent` (#3e2723)

### Componentes Personalizados

#### Botones
- Color de texto global: `$light` (beige claro)
- Border radius: `50rem` (pill/redondeado completo)
- Todos los botones son rounded-pill por defecto

#### Configuración Global
- `$body-color`: `$accent` - Color de texto principal
- `$body-bg`: `$white` - Fondo principal
- `$enable-rounded`: `true` - Bordes redondeados activos

### Mapas Modificados

Los colores personalizados están integrados en:
- **`$colors`**: Incluye todos los colores personalizados junto a los de Bootstrap
- **`$theme-colors`**: Integra los valores redefinidos de primary, secondary, success, light y dark

> **Nota importante**: Toda la personalización se realiza exclusivamente mediante variables y mapas de Bootstrap en `scss/_variables.scss`. No se utilizan clases ni mixins personalizados, facilitando el mantenimiento y escalabilidad del proyecto.

## 🚀 Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **Bootstrap 5** - Framework CSS
- **SCSS** - Preprocesador CSS
- **Font Awesome 6** - Iconos
- **JavaScript** - Interactividad (componentes Bootstrap)

## 📦 Instalación y Uso

### Prerrequisitos

- Navegador web moderno
- (Opcional) Compilador SCSS si deseas modificar los estilos

### Ejecución Local

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/Cafe-Essenza_Proyecto-Final-DIW.git
```

2. Navega al directorio del proyecto:
```bash
cd Cafe-Essenza_Proyecto-Final-DIW
```

3. Abre cualquier página HTML en tu navegador:
```bash
# Abre directamente el archivo
start pages/home.html
```

### Compilar SCSS (Opcional)

Si deseas modificar los estilos, necesitarás compilar los archivos SCSS:

```bash
# Instalar dart-sass (si no lo tienes)
npm install -g sass

# Compilar SCSS
sass scss/bootstrap.scss dist/css/bootstrap.css
```

## 📱 Páginas del Sitio

### 🏠 Home
Página de bienvenida con presentación del café y acceso rápido a todas las secciones.

### 📖 Carta
Visualización completa de productos organizados en categorías:
- Bebidas Calientes
- Bebidas Frías
- Repostería

### 🛍️ Pedido Online
Sistema de carrito de compras con:
- Añadir/eliminar productos
- Cálculo de subtotal
- Selección de método de pago
- Formulario de datos de entrega

### 📅 Reservas
Formulario para reservar mesa con:
- Selección de fecha y hora
- Número de comensales
- Información de contacto

### ℹ️ Sobre Nosotros
Información sobre la historia, misión y valores de Café Essenza.

## 🎯 Características de Diseño

- ✅ **Mobile First**: Diseño optimizado para móviles
- ✅ **Responsive**: Adaptación perfecta a tablets y escritorio
- ✅ **Accesibilidad**: Estructura semántica y navegación por teclado
- ✅ **Consistencia**: Uso coherente de variables y componentes
- ✅ **Performance**: CSS optimizado sin código innecesario

## 📝 Documentación Adicional

Para más detalles sobre la personalización de Bootstrap, consulta:
- [_resumen-mapas-bootstrap.md](_resumen-mapas-bootstrap.md) - Documentación completa de modificaciones

## 👨‍💻 Autor

Desarrollado como Proyecto Final para la asignatura de Diseño de Interfaces Web (DIW).

## 📄 Licencia

Este proyecto es un trabajo académico desarrollado con fines educativos.

---

⭐ **¿Te gusta el proyecto? ¡Deja una estrella en el repositorio!**

☕ **Café Essenza - Donde cada taza cuenta una historia**

