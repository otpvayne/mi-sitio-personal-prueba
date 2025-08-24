# Mi Sitio Personal (estático)

## 🎯 Objetivo
Sitio personal estático (Home, Sobre mí, Contacto) para presentar mi perfil profesional y facilitar el contacto.

## 🗺️ Alcance (MVP)
- Home (hero + habilidades + CTA)
- Sobre mí (bio, experiencia, foto)
- Contacto (formulario básico)

## 🧩 Componentes previstos
- Header (logo + nav)
- Hero (titular + subtítulo + CTA)
- Card (habilidades/servicios)
- ContactForm (inputs + botón)
- Footer

## 🧱 Estructura
mi-sitio-personal/
├─ index.html
├─ sobre-mi.html
├─ contacto.html
├─ css/
│ ├─ style.css
│ └─ components.css
├─ components/
│ ├─ header.html
│ ├─ hero.html
│ ├─ card.html
│ ├─ contact-form.html
│ └─ footer.html
└─ assets/
├─ img/
└─ icons/


## 🧪 Criterios de aceptación (MVP)
- Navegación funcional entre las 3 páginas.
- Diseño responsive ≥ 320px de ancho.
- Accesibilidad básica (alt en imágenes, `lang="es"`, etiquetas semánticas).
- Lighthouse Accesibilidad ≥ 90 (a completar cuando se maquete).

## 🗂️ Planificación ágil (resumen)
- **Historias de usuario**
  - *Como reclutador, quiero ver un resumen claro en Home para decidir si reviso el CV completo.*
  - *Como cliente, quiero un formulario sencillo para solicitar contacto rápido.*
- **Tareas** (backlog)
  - Crear header y navegación
  - Maquetar hero Home
  - Crear componente card y listarlo en Home
  - Página Sobre mí
  - Página Contacto (form)
  - Estilos responsive y accesibilidad
- **Definición de Hecho**
  - HTML validado, semántico
  - CSS sin warnings
  - Navegación probada
  - README actualizado
