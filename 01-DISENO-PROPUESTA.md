# JoanaJob — Propuesta de Rediseño

## Estilo: Profesional + Minimalista

Una mezcla de **elegancia corporativa** con la **claridad del minimalismo**. Transmite confianza, cercanía y solvencia profesional.

---

## Paleta de Colores

| Color | Hex | Uso |
|-------|-----|-----|
| Deep Green | `#0F2E24` | Footer, headings, acentos |
| Medium Green | `#1A5A4A` | Botones secundarios, hover states |
| Accent Green | `#2D8C72` | CTAs principales, enlaces |
| Off-White | `#F8F6F3` | Fondos de sección, suave calidez |
| Pure White | `#FFFFFF` | Fondos principales, cards |
| Dark Text | `#1A1A1A` | Texto body |
| Gray Text | `#6B6B6B` | Texto secundario, metadatos |
| Light Border | `#E8E6E1` | Bordes sutiles, separadores |

**Por qué esta paleta:** Mantiene el verde oscuro de la marca original (`#013322` → `#0F2E24`) pero lo sofistica. El verde medio aporta un punto de calidez sin perder profesionalidad. El off-white da ese toque acogedor que diferencia a JoanaJob de webs corporativas frías.

---

## Tipografía

- **Títulos:** `DM Serif Display` — serif elegante, transmite confianza y personalidad
- **Cuerpo:** `Inter` — sans-serif ultra-legible, muy moderna
- **Escala:**
  - H1: 3.5rem (56px)
  - H2: 2.25rem (36px)
  - H3: 1.5rem (24px)
  - Body: 1rem (16px)
  - Small: 0.875rem (14px)

---

## Layout & Espaciado

- **Max width:** 1200px con padding 24px
- **Secciones:** Separadas por 100-140px de espacio vertical
- **Cards:** Esquinas suaves (12px radio), sombras ligeras
- **Grids:** 3-columnas para servicios, 2-columnas para contenido mix

---

## Estructura de Navegación

```
[Logo] — ESENCIA · SERVICIOS · CONTACTO · RECURSOS — [🛒 0]
```

- Nav fija al hacer scroll (sticky, con fondo blanco semitransparente)
- Active page subrayado sutil
- Hamburguesa en mobile con overlay

---

## Componentes Clave

### Hero
- Imagen de fondo con overlay oscuro suave
- H1 grande con serif
- CTA botón verde redondeado
- Sin carrusel (foto única potente)

### Servicios (3 Packs)
- Grid de 3 cards
- Cada card: icono/ilustración → título → descripción corta → CTA
- Hover con elevación sutil

### Logos Clientes
- Grid de logos en grises con hover opacidad
- Sin carrusel automático (más accesible)

### Diferenciadores
- Layout 2-columnas: imagen | texto
- Alternar lado imagen para variedad

### Estadísticas
- Números grandes y bold
- Iconos acompañando cada cifra

### Empresas/Emprendedores
- Acordeones limpios con animación suave
- Iconos + títulos

### Footer
- Fondo verde oscuro
- 3 columnas: Logo+email | Social+legal | Kit Digital
- Links blancos con hover subrayado

---

## Rutas a Mantener (idénticas)

| Ruta | Página |
|------|--------|
| `/es/` | Home |
| `/es/esencia/` | Sobre nosotros |
| `/es/servicios/` | Servicios |
| `/es/contacto/` | Contacto |
| `/es/recursos/` | Biblioteca recursos |
| `/es/productos/fundamentos-laborales/` | Pack Base |
| `/es/productos/proyeccion-del-crecimiento/` | Pack Completo |
| `/es/productos/consolidacion-de-la-trayectoria/` | Pack Premium |
| `/es/aviso-legal/` | Aviso Legal |
| `/es/politica-de-privacidad/` | Privacidad |
| `/es/condiciones-generales-y-de-contratacion/` | Condiciones |
| `/es/politica-de-cookies/` | Cookies |
| `/es/accesibilidad/` | Accesibilidad |
| `/es/mapa-web/` | Mapa Web |
| `/es/proceso-de-compra/step1/` | Checkout |
| `/es/account/login/` | Login |
| `/ca/` | Catalan |
| `/en/` | English |

---

## Enlaces Externos a Mantener

| Texto | URL |
|------|-----|
| Llamada Informativa | Google Calendar app |
| Instagram | `instagram.com/joanajob.es` |
| LinkedIn | `linkedin.com/in/joana-martínez-pardell/` |
| Hooba web | `hooba.com/es/` |
| Stripe Fundamentos (completo) | `book.stripe.com/...fundamentos...` |
| Stripe Fundamentos (financiación) | `buy.stripe.com/...fundamentos...` |
| Stripe Proyección (completo) | `book.stripe.com/...proyeccion...` |
| Stripe Proyección (financiación) | `buy.stripe.com/...proyeccion...` |
| Stripe Consolidación (completo) | `book.stripe.com/...consolidacion...` |
| Stripe Consolidación (financiación) | `buy.stripe.com/...consolidacion...` |
| Stripe Orientación 80€ | `buy.stripe.com/...orientacion...` |
| Email | `mailto:joana@martinez.cat` |

---

## Imágenes (usar las mismas URLs)

Todas las imágenes actuales se mantienen con sus URLs de gestionaweb.cat.
Lista completa en el audit: `/joanajob-audit.md` (#27)

---

## Accesibilidad (WCAG 2.1 AA)

- Skip-to-content link (añadir)
- Alt texts descriptivos en todas las imágenes
- Imágenes decorativas → `alt=""`
- Contraste de color suficiente (verificado)
- Navegación por teclado completa
- Focus visible en todos los elementos interactivos
- Formularios con labels explícitos
- Carruseles con controles accesibles
- Texto semántico (h1→h6 jerarquía correcta)
- ARIA labels donde sea necesario
