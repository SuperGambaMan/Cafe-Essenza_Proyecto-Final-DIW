# Resumen de modificaciones de mapas y variables Bootstrap

Este documento recoge todas las modificaciones realizadas sobre los mapas y variables de Bootstrap en el proyecto Essenza, centralizadas en `scss/_variables.scss`.

---

## 1. Colores personalizados

- **Variables añadidas:**
  - `$brown: #a67c52` (color-marrón)
  - `$beige: #f5ede3` (color-beige)
  - `$accent: #3e2723` (color-acento)
  - `$essenza-green: #7DAF9C` (verde-acento)

- **Integración en mapas:**
  - Añadidos a `$colors` y `$theme-colors` para uso en utilidades y componentes.

---

## 2. Paleta principal redefinida

- `$primary: $accent`
- `$secondary: $brown`
- `$success: $essenza-green`
- `$light: $beige`
- `$dark: $gray-900`

---

## 3. Mapas modificados

- **$colors:**
  Incluye los colores personalizados junto a los de Bootstrap.
- **$theme-colors:**
  Incluye los nuevos valores de `$primary`, `$secondary`, `$success`, `$light`, `$dark`.

---

## 4. Tipografía

- `$font-family-sans-serif: 'Roboto', ...`
- `$font-family-serif: 'Playfair Display', serif`
- `$font-family-base: $font-family-sans-serif`
- `$headings-font-family: $font-family-serif`

---

## 5. Botones

- `$btn-color: $light` (color de texto global para botones)
- `$btn-border-radius: 50rem` (todos los botones son rounded-pill por defecto)

---

## 6. Otros ajustes relevantes

- `$body-color: $accent` (color de texto principal)
- `$body-bg: $white` (fondo principal)
- `$enable-rounded: true` (bordes redondeados activos)

---

## 7. Utilidades y variables no modificadas

- Breakpoints, espaciados y sistema de grid se mantienen como en Bootstrap por defecto.

---

**Nota:** Toda la personalización se realiza exclusivamente mediante variables y mapas de Bootstrap, sin clases ni mixins personalizados. El mantenimiento y futuras modificaciones deben hacerse editando estas variables en `scss/_variables.scss`.
