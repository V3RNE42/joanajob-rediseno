# JoanaJob.com — Complete Site Audit

**Audit Date:** 2026-05-08  
**Site URL:** https://www.joanajob.com  
**Platform:** Next.js (hosted on gestionaweb.cat infrastructure)  
**E-commerce:** Self-coded cart system + Stripe for product purchases  
**CMS:** Custom GestiónWeb platform  

---

## Table of Contents

1. [Meta Info & SEO](#1-meta-info--seo)
2. [Color Scheme & Styling](#2-color-scheme--styling)
3. [Fonts & Typography](#3-fonts--typography)
4. [Favicon](#4-favicon)
5. [Language Switcher](#5-language-switcher)
6. [Header / Navigation Structure](#6-header--navigation-structure)
7. [Footer Structure](#7-footer-structure)
8. [Homepage (/es/)](#8-homepage-es)
9. [Esencia Page (/es/esencia/)](#9-esencia-page-esesencia)
10. [Servicios Page (/es/servicios/)](#10-servicios-page-esservicios)
11. [Contacto Page (/es/contacto/)](#11-contacto-page-escontacto)
12. [Recursos Page (/es/recursos/)](#12-recursos-page-esrecursos)
13. [Product: Fundamentos Laborales (/es/productos/fundamentos-laborales/)](#13-product-fundamentos-laborales)
14. [Product: Proyección del Crecimiento (/es/productos/proyeccion-del-crecimiento/)](#14-product-proyeccion-del-crecimiento)
15. [Product: Consolidación de la Trayectoria (/es/productos/consolidacion-de-la-trayectoria/)](#15-product-consolidacion-de-la-trayectoria)
16. [Legal: Aviso Legal (/es/aviso-legal/)](#16-legal-aviso-legal)
17. [Legal: Política de Privacidad (/es/politica-de-privacidad/)](#17-legal-politica-de-privacidad)
18. [Legal: Condiciones Generales (/es/condiciones-generales-y-de-contratacion/)](#18-legal-condiciones-generales)
19. [Legal: Política de Cookies (/es/politica-de-cookies/)](#19-legal-politica-de-cookies)
20. [Accesibilidad (/es/accesibilidad/)](#20-accesibilidad)
21. [Mapa Web (/es/mapa-web/)](#21-mapa-web)
22. [English Version (/en/)](#22-english-version-en)
23. [Catalan Version (/ca/)](#23-catalan-version-ca)
24. [E-commerce / Cart System](#24-e-commerce--cart-system)
25. [Cookie Consent System (Cookienator)](#25-cookie-consent-system-cookienator)
26. [Accessibility Audit](#26-accessibility-audit)
27. [All Images Inventory](#27-all-images-inventory)
28. [All Links Inventory](#28-all-links-inventory)
29. [Summary of Findings](#29-summary-of-findings)

---

## 1. Meta Info & SEO

### Spanish (Homepage)
- **Title:** `Joana Job — Psicóloga Laboral y Consultoría de Carrera`
- **Description:** `Transforma tu carrera con Joana Job, psicóloga laboral. Consultoría personalizada, optimiza CV y LinkedIn, prepárate para entrevistas y negocia tu salario.`
- **Keywords:** `consultoría laboral online, optimización CV, perfil LinkedIn, preparación entrevistas, negociación salarial, psicóloga laboral, transición profesional`
- **Canonical:** `https://www.joanajob.com/es/`
- **OG Title:** `Joana Job — Psicóloga Laboral y Consultoría de Carrera`
- **OG Description:** same as meta description
- **OG Image:** `https://images.gestionaweb.cat/7517/imgf-1200-630/captura-de-pantalla-2025-10-20-a-las-12-40-28-4.png`
- **OG Type:** `website`
- **OG Site Name:** `Joana Job`
- **Hreflang:** `x-default`, `es`, `ca`, `en`
- **Schema.org:** `@type: Organization` — with name, url, logo, sameAs (Instagram + LinkedIn)

### Esencia (/es/esencia/)
- **Title:** `Transformación profesional - JoanaJob`
- **Description:** `Consultoría en psicología laboral para inserción y ascenso: análisis de mercado, CV, LinkedIn, entrevistas y negociación. Seguimiento y resultados.`
- **Canonical:** `https://www.joanajob.com/es/esencia/`

### Servicios (/es/servicios/)
- **Title:** `Servicios de consultoría laboral – JoanaJob`
- **Description:** `Descubre nuestros programas de orientación laboral y consultoría profesional para potenciar tu perfil, ascenso y oportunidades de empleo.`

### Contacto (/es/contacto/)
- **Title:** `Contacto – JoanaJob | Psicóloga Laboral Online`

### Recursos (/es/recursos/)
- **Title:** `Biblioteca de Recursos – JoanaJob | Psicología Laboral`

### Product Pages
- **Fundamentos Laborales:** `Pack Base – Fundamentos Laborales | JoanaJob`
- **Proyección del Crecimiento:** `Pack Completo – Proyección del Crecimiento | JoanaJob`
- **Consolidación de la Trayectoria:** `Pack Premium – Consolidación de la Trayectoria | JoanaJob`
  - Has schema.org `@type: Product` with category, audience, name, description

### English Homepage (/en/)
- **Title:** `Joana Job — Occupational Psychologist & Career Consulting`
- **Description:** `Transform your career with Joana Job. Personalized consulting: CV & LinkedIn optimization, interview practice and salary negotiation.`

### Catalan Homepage (/ca/)
- **Title:** `Joana Job — Psicòloga Laboral i Consultoria de Carrera`
- **Description:** `Transforma la teva carrera amb Joana Job, psicòloga laboral. Consultoria personalitzada: CV i LinkedIn, preparació d'entrevistes i negociació salarial.`

---

## 2. Color Scheme & Styling

### Primary Colors (extracted from CSS)
| Color | Hex | Usage |
|-------|-----|-------|
| Dark Green | `#013322` | Footer background |
| Medium Green | `#175750` | Separator color in footer |
| Light Blue | `#bdd2ff` | Header background (nav area) |
| Lighter Blue | `#d1dfff` | Submenu background |
| Lightest Blue | `#e6eeff` | Sub-submenu background |
| Pale Blue | `#aabde6` | Navigation bar background |
| Blue link | `#0078a8` | Link color |
| Body text | `#2e2e2e` | Main text color |
| Footer text | `#ffffff` | White text on footer |
| White | `#ffffff` | Background, buttons |
| Light gray | `#f9f9f9`, `#f5f5f5`, `#eee` | Section backgrounds |
| Red accent | `#FB3C2D` | Potential error/accent |
| Green accent | `#028a02`, `#25d366` | Success, WhatsApp |
| Orange/CTA | `#a50b00` | CTA elements |
| Dark overlay | `rgba(0,0,0,0.3)` | Cookie dialog shadow |

### CSS Variables
- `--cookienator-primary-color: #000000`
- `--cookienator-primary-color-dimmed: #dddddd`
- `--f-button-color: #374151`
- `--f-button-bg: #f8f8f8`

### Background Colors Used
- Nav header: `#bdd2ff` (light blue)
- Submenus: `#d1dfff` → `#e6eeff`
- Main content area: White/transparent
- Footer section: `#013322` (dark green)
- Product cards: Various shades of white/gray

---

## 3. Fonts & Typography

### Font Families
- **Primary (body):** `Poppins, sans-serif`
- **Secondary (headings/accents):** `Lora, sans-serif`
- **Icons:** `Font Awesome 7 Pro`, `Font Awesome 7 Brands`, `Font Awesome 7 Duotone`
- **Custom icon font:** `FontCustom`
- **Fallback:** `Roboto, Arial, sans-serif`

### Font Loading
- Preconnect to `fonts.googleapis.com` and `fonts.gstatic.com`
- Google Fonts loaded: Poppins (300-700, italic included) + Lora (300-700, italic included)
- `display=swap` used

### Body Text
- Font size: `15px` (computed), `1em` (CSS)
- Line height: `1.4`
- Color: `#2e2e2e` (rgb(46, 46, 46))

---

## 4. Favicon
- **URL:** `https://docs.gestionaweb.cat/7517/logo2.ico`

---

## 5. Language Switcher

### Desktop
- A simple text-based language indicator showing the current language code (ES / CA / EN)
- Dropdown with links to:
  - `https://www.joanajob.com/es/` (Español)
  - `https://www.joanajob.com/ca/` (Català)
  - `https://www.joanajob.com/en/` (English)

### Mobile
- Same structure — a globe icon + current language label, expandable to show all three options
- Uses `hreflang` attributes on each `<a>` tag

### Hreflang Tags in `<head>`
```html
<link rel="alternate" hreflang="x-default" href="https://www.joanajob.com/es/">
<link rel="alternate" hreflang="es" href="https://www.joanajob.com/es/">
<link rel="alternate" hreflang="ca" href="https://www.joanajob.com/ca/">
<link rel="alternate" hreflang="en" href="https://www.joanajob.com/en/">
```

---

## 6. Header / Navigation Structure

### Desktop Navigation
- **Left side:** Language selector (ES/CA/EN)
- **Center:** Logo linking to `/es/`
- **Main nav items:** ESENCIA | SERVICIOS | CONTACTO | RECURSOS
- **Right icons:** Shopping bag (cart) → `/es/proceso-de-compra/step1/`, User account → `/es/account/login/`
- **Cart counter:** Shows "0 Mi cesta" badge
- **Background:** `#bdd2ff` (light blue)
- **Dropdown menus:** Submenus use `#d1dfff` → `#e6eeff` backgrounds

### Mobile Navigation (Off-canvas)
- Hamburger toggle (`data-offcanvas-toggle="menu-mobil"`)
- Slides in from right
- Contains: Language selector, Main navigation links (Inicio, Esencia, Servicios, Contacto, Recursos)
- Legal links at bottom

### Navigation Links
| Text | URL |
|------|-----|
| Inicio | `/es/` |
| Esencia | `/es/esencia/` |
| Servicios | `/es/servicios/` |
| Contacto | `/es/contacto/` |
| Recursos | `/es/recursos/` |
| Mi cesta | `/es/proceso-de-compra/step1/` |
| Mi cuenta | `/es/account/login/` |

---

## 7. Footer Structure

The footer appears on ALL pages with identical structure:

### Footer Sections

**Section 1: Logo + Email**
- Joana Job logo (linked to homepage)
- Email: `joana@martinez.cat`

**Section 2: Social Links**
- Instagram (`https://www.instagram.com/joanajob.es?igsh=MXVqNGU0MDFpcGxkaw==`) — target=_blank, rel=nofollow
- LinkedIn (`https://www.linkedin.com/in/joana-mart%C3%ADnez-pardell/`) — target=_blank, rel=nofollow

**Section 3: CO₂ Donation Message**
> "En JoanaJob donamos el 0,5 % de todos los beneficios para ayudar a eliminar el CO₂ de la atmósfera."

**Section 4: Kit Digital Badges (NextGenerationEU)**
- EU flag logo (alt: "Financiado por la Unión Europea NextGenerationEU")
- Spanish Government logo (alt: "Gobierno de España")
- Plan de Recuperación logo (alt: "Plan de Recuperación, Transformación y Resiliencia")

**Section 5: Attribution**
- "Hooba web" → `https://www.hooba.com/es/` (target=_blank)

**Section 6: Legal Links (separator + list)**
- Aviso legal
- Política de privacidad
- Condiciones generales y de contratación
- Política de cookies
- Configuración de cookies (JavaScript trigger)
- Mapa web
- Accesibilidad

**Footer background:** `#013322` (dark green)  
**Footer text color:** `#ffffff`  
**Footer link color:** `#ffffff`  
**Footer font size:** `14px`, weight: `400`

---

## 8. Homepage (/es/)

### Layout Structure
1. **Hero Section**
   - Background image: "Imagen Especialistas en Psicología Laboral" (`https://images.gestionaweb.cat/7517/img-480-270/1000044878-fd9ec1f8f9c117f7452300f0a82fa3ee-11-4-2024-6-38-38-pm-2-2.jpg`)
   - H1: "Especialistas en Psicología Laboral"
   - CTA button: "Llamada Informativa" → Google Calendar appointment link
   - Image gallery carousel (1 slide)

2. **Services Section ("SERVICIOS")**
   - **PACK BASE (Fundamentos Laborales)**
     - Image: "Imagen PACK BASE" (`https://images.gestionaweb.cat/7517/img-480-0/pexels-andri-file-288172640-36906867-1.jpg`)
     - Description: "Desarrollo del perfil profesional para convertir el potencial en oportunidades laborales sostenibles"
     - CTA: "FUNDAMENTOS LABORALES" → `/es/productos/fundamentos-laborales/`
   - **PACK COMPLETO (Proyección del Crecimiento)**
     - Image: "Imagen PACK COMPLETO" (`https://images.gestionaweb.cat/7517/img-480-0/diseno-sin-titulo-13.png`)
     - Description: "Acelerando el desarrollo profesional mediante la gestión activa de inserción y ascenso laboral"
     - CTA: "PROYECCIÓN DEL CRECIMIENTO" → `/es/productos/proyeccion-del-crecimiento/`
   - **PACK PREMIUM (Consolidación de la Trayectoria)**
     - Image: "Imagen PACK PREMIUM" (`https://images.gestionaweb.cat/7517/img-480-0/diseno-sin-titulo-14.png`)
     - Description: "Trabajando visibilidad, posicionamiento y negociación, para un crecimiento laboral sostenido a largo plazo"
     - CTA: "CONSOLIDACIÓN DE LA TRAYECTORIA" → `/es/productos/consolidacion-de-la-trayectoria/`
   - Link: "¿TIENES DUDAS? EMPIEZA POR UNA LLAMADA DE ORIENTACIÓN QUE SE DESCONTARÁ SI ELIJES UNO DE LOS PACKS" → `/es/servicios/`

3. **Clients/Testimonials Section**
   - Heading: "Los resultados son nuestra seña de identidad"
   - H2: "NUESTROS CLIENTES SON PARTE DE EMPRESAS DE PRESTIGIO INTERNACIONAL"
   - **15-slide logo carousel** of company logos (Previous/Next buttons)
   - Logo images hosted on gestionaweb.cat (e.g., `1-2.png`, `2-logos.png`, etc.)
   - CTA: "CONOCE A NUESTROS CLIENTES" → `/es/esencia/#section-466018`

4. **Differentiators Section**
   - Image: "LAPICERO" (`https://images.gestionaweb.cat/7517/pwimg-480/ad2431ac-1465-4daa-a134-ec42a1157195.jpg`)
   - H3: "Lo que nos diferencia"
   - Paragraphs emphasizing **Applied Occupational Psychology** and **data-driven career strategy**
   - Key phrases: "Psicología Laboral Aplicada", "datos del mercado laboral actual", "una elección informada", "oportunidades laborales concretas", "acompañamiento constante"
   - CTA: "¿QUIERES CONOCERNOS DIRECTAMENTE?" → Google Calendar

5. **Statistics Section**
   - H3: "+130 profesionales de 27 países han trabajado su inserción laboral, cambio de sector o ascenso profesional con nosotros."
   - Stats: 34 sectors, 30+ professional areas, 67% in leadership positions
   - "El 90% está actualmente empleado, el 8% en formación y el 2% jubilado"
   - Two images: "MAPA" and "GRAFICO" (map + chart graphics)

6. **Business Segments Section ("TAMBIÉN TRABAJAMOS CON")**
   - **Emprendedores (Entrepreneurs)** — accordion/collapse section "Leer más"
     - Title: "Consultoría y Herramientas de Marketing, Funneling, Ventas y Negocio"
     - 6 sessions, 6 personalized documents, WhatsApp & Email support
   - **Empresas (Companies)** — accordion "Leer más"
     - Title: "Estrategias de Captación Desarrollo y Retención de Talento"
     - HR consulting, workshops for middle management
   - **Organizaciones y Universidades** — accordion "Leer más"
     - Title: "Conferencias, Programas y Talleres de Psicología Laboral"
     - Talks, masterclasses, modular formats

7. **Footer** (as described in section 7)

### Key CTA Links on Homepage
- Llamada Informativa → Google Calendar appointment
- FUNDAMENTOS LABORALES → product page
- PROYECCIÓN DEL CRECIMIENTO → product page
- CONSOLIDACIÓN DE LA TRAYECTORIA → product page
- CONOCE A NUESTROS CLIENTES → `/es/esencia/#section-466018`
- ¿QUIERES CONOCERNOS DIRECTAMENTE? → Google Calendar
- ¿TIENES DUDAS? → `/es/servicios/`
- SÍGUENOS → `/es/contacto/`

---

## 9. Esencia Page (/es/esencia/)

### Layout Structure
1. **H1: "Nuestra esencia"**
2. **Anchor links:** METODOLOGIA | CLIENTES | EQUIPO (internal page anchors)
3. **"LA EXPERIENCIA" section**
   - H2: "LA EXPERIENCIA"
   - Subtitle: "Cercana, Exigente y Profundamente Personalizada."
   - Description: Weekly follow-up, concrete tasks, limited spots
   - CTA: "RESERVAR" → Google Calendar

4. **"NUESTRA METODOLOGÍA" section**
   - 4-step methodology:
     - **Partimos del Análisis:** 1 form + 3 work documents
     - **Fomentamos el Aprendizaje:** 6 deliverables (Market Analysis, Employment Strategy, Professional Profile, CV, Interview, Negotiation)
     - **Nos Encargamos de Todo:** Specialists write all 6 pieces
     - **Pensamos en el Presente y Futuro:** Sustainable transformation

5. **"EL TRABAJO COMO EJE DE VIDA" section**
   - Philosophical content about work as life axis
   - Key concept: "transformación profesional" affects all personal areas

6. **"CUANDO APARECE EL BLOQUEO" section**
   - Content about career stagnation and how to overcome it
   - Theme: "Transformar la trayectoria profesional es recuperar control"

7. **Testimonials Carousel**
   - H1: "+130 CLIENTES"
   - H1: "DE 27 PAÍSES, 20 PROFESIONES Y 30 SECTORES DISTINTOS"
   - 10 testimonial slides with 5-star ratings
   - Previous/Next slide buttons + dot indicators
   - Sample testimonial: "Trabajar con Joana fue un antes y un después..."
   - Client labels: "Cliente Nivel Directivo", "Cliente Sector IT", etc.

8. **Pricing links to products** (Fundamentos 480€, Proyección 600€, Consolidación 1200€)

9. **Standard footer**

### Images on Esencia page
- Logo images (header + footer)
- `captura-de-pantalla-2025-10-24-125121-2.png` (decorative)
- `travel-brand-guidelines-presentation-5.png` (decorative)
- `travel-brand-guidelines-presentation-7.png` (decorative)
- `travel-brand-guidelines-presentation-6.png` (decorative)
- `logo-gray-en.png` (decorative)
- `r.png` (decorative)
- Kit Digital badges (footer)

---

## 10. Servicios Page (/es/servicios/)

### Layout Structure
1. **H1: "Servicios"**
2. **Anchor links:** FUNDAMENTOS | PROYECCIÓN | CONSOLIDACIÓN

3. **Orientación Profesional (LLAMADA INDIVIDUAL)**
   - 30-minute call
   - Description: "Llamada de 30 minutos para analizar la situación actual, hacer una revisión correctiva del perfil, y resolver dudas profesionales."
   - CTA: "RESERVA" → Stripe payment link (80€)

4. **Fundamentos Laborales (PACK BASE)**
   - H2: "Fundamentos Laborales"
   - Description: "Programa de transformación con supervisión personalizada."
   - Includes: Análisis del Mercado, Estrategia de Empleo, Perfil Laboral, Curriculum, Entrevista y Negociación
   - CTA: "RESERVA" → Stripe payment link

5. **Proyección del Crecimiento (PACK COMPLETO)**
   - H2: "Proyección del Crecimiento"
   - Description: "Programa de crecimiento y transformación con acompañamiento integral."
   - CTA: "RESERVA" → Stripe payment link

6. **Consolidación de la Trayectoria (PACK PREMIUM)**
   - H2: "Consolidación de la Trayectoria"
   - CTA: "TRABAJA DE LA MANO DE UN ESPECIALISTA" → Stripe payment link

7. **CTA:** "LLAMADA INFORMATIVA PARA VER CON CUÁL ENCAJAS" → Google Calendar

8. **CO₂ Donation message**
9. **Standard footer**

---

## 11. Contacto Page (/es/contacto/)

### Layout Structure
1. **H1: "Contacta"**
2. **Anchor links:** SESIÓN DE ORIENTACIÓN | LLAMADA INFORMATIVA

3. **Community section**
   - H1: "Únete a nuestra comunidad"
   - Instagram embed link
   - LinkedIn embed link

4. **Call booking**
   - H2: "No queremos que tus dudas queden sin responder"
   - CTA: "RESERVA TU LLAMADA" → Google Calendar

5. **Contact Form**
   - H2: "Resuelve tus dudas por email"
   - Fields:
     - Nombre y apellidos* (text input)
     - Número de teléfono (text input)
     - Correo electrónico* (text input)
     - Mensaje* (textarea)
     - Checkbox: "He leído y acepto la política de privacidad. *" + link to privacy policy
   - Privacy info box:
     - Responsable: Joana Martínez Pardell
     - Finalidad: Ofrecer, prestar y facturar nuestros servicios y productos
     - Legitimación: Consentimiento del interesado
     - Destinatarios: No se cederán a terceros
     - Derechos: Acceder, rectificar y suprimir datos
   - Submit button: "Enviar"
   - Links: Política de privacidad, Condiciones del servicio

6. **CTA:** "DESCUBRE TODAS TUS OPCIONES" → services page

7. **Standard footer**

---

## 12. Recursos Page (/es/recursos/)

### Layout Structure
1. **H1: "Biblioteca de recursos"**

2. **Introduction**
   - "Estamos creando todos los recursos que necesitas para la inserción y ascenso laboral"
   - CTA: "CONTACTA Y ACCEDE POR ADELANTADO"

3. **Resource Categories**
   - **Posicionamento:** Formaciones, Cursos, Test Psicometricos, Networking, Plan de Carrera
   - **LinkedIn y Aplicación Web:** Posicionamiento, Filtros, Publicaciones, Título, Imagen, Experiencia, Educación, Aptitudes, LinkedIn Sales
   - **Reto Laboral:** Tiempo, Ascensos, Viajes, Riesgo, Crecimiento
   - **Básicos:** Curriculum, Carta de Motivación, Portfolio
   - **Análisis del Mercado Laboral:** Oferta, Profesionales, Empresa
   - **Branding:** Marketing, Diferenciación, Comunicación
   - **Entrevista y Negociación:** Posicionamiento, Aplicación, Publicaciones

4. **Resource Listings (filterable)**
   - Filter: "Tipo de Suscripción" dropdown (Todos / Compra individual de documento)
   - Filter: "Palabras clave" text search
   - **3 available documents (30€ each):**
     - **Curriculum** — "Documento de Trabajo con el esqueleto de Currículum e indicaciones de información a rellenar en cada uno de los apartados. 30 €"
     - **Dossier de Entrevista** — "Estrategia para la preparatoria, introducción, preguntas generales, preguntas trampa y negociación de las entrevistas. 30 €"
     - **Dossier de LinkedIn** — "Teoría y actividades para que el perfil cumpla con las preferencias del personal de recursos humanos. Orientado tanto para inserción como para ascenso laboral. 30 €"

5. **CTA:** "¿QUÉ SABES DE NOSOTROS?" → /es/esencia/

6. **Standard footer**

---

## 13. Product: Fundamentos Laborales (/es/productos/fundamentos-laborales/)

### Meta
- **Title:** `Pack Base – Fundamentos Laborales | JoanaJob`
- **Price:** `480 €` (full) or `80€/mes` (financing)

### Content
- H1: "Fundamentos Laborales"
- H2 subtitle: "Una supervisión de los seis ámbitos para el crecimiento profesional en el mercado laboral actual."
- **Description:** Introduction, doubt resolution, professional registration for diagnosis

### Features
- **5 Registration Documents:**
  - REGISTRO DE DATOS Y PREFERENCIAS
  - REGISTRO DEL PERFIL O CURRÍCULUM
  - REGISTRO DE POSICIONES LABORALES OBJETIVO
  - REGISTRO DEL HISTORIAL PROFESIONAL
  - CUESTIONARIO DEL HISTORIAL PROFESIONAL

- **6 Delivered Reports:**
  - ANÁLISIS DEL MERCADO LABORAL
  - ESTRATEGIA DE EMPLEO
  - PERFIL LABORAL - PERFIL DE LINKEDIN
  - CURRÍCULUM
  - ESTRATEGIAS DE ENTREVISTA
  - ESTRATEGIAS DE NEGOCIACIÓN

### CTAs
- **"RESERVA COMPLETA"** → `https://book.stripe.com/00w9AT13L7jM3PtaVTeEo02`
- **"FINANCIACIÓN 80€ /MES"** → `https://buy.stripe.com/6oU9ATeUB33w1Hl0hfeEo03`

### Sidebar (cross-sell)
- LLAMADA INDIVIDUAL: Orientación Profesional (80€) → Stripe
- PACK COMPLETO: Proyección del Crecimiento (600€) → product page
- PACK PREMIUM: Consolidación de la Trayectoria (1.200€) → product page

---

## 14. Product: Proyección del Crecimiento (/es/productos/proyeccion-del-crecimiento/)

### Meta
- **Title:** `Pack Completo – Proyección del Crecimiento | JoanaJob`
- **Price:** `600 €` (full) or `100€/mes` (financing)

### Content
- H1: "Proyección del Crecimiento"
- H2 subtitle: "Transforma los seis ámbitos para el crecimiento profesional con la tranquilidad de la supervisión personalizada incluyendo entregas y resolución de dudas por llamada."
- **Includes 2 thirty-minute calls:**
  - LLAMADA DE TRABAJO: Quality assurance on collected info
  - LLAMADA DE PRACTICA: Simulated interview & negotiation

### Features
Same 5 registration docs + 6 delivered reports as Fundamentos

### CTAs
- **"RESERVA COMPLETA"** → `https://book.stripe.com/8x200j5k1bA25XBfc9eEo04`
- **"FINANCIACIÓN 100€ /MES"** → `https://buy.stripe.com/4gM28raEl7jM99N5BzeEo05`

### Sidebar (cross-sell)
- LLAMADA INDIVIDUAL (80€) → Stripe
- PACK BASE: Fundamentos (480€) → product page
- PACK PREMIUM: Consolidación (1.200€) → product page

---

## 15. Product: Consolidación de la Trayectoria (/es/productos/consolidacion-de-la-trayectoria/)

### Meta
- **Title:** `Pack Premium – Consolidación de la Trayectoria | JoanaJob`
- **Price:** `1200 €` (full) or `200€/mes` (financing)
- **Schema.org:** `@type: Product` — Category: "Consultoría Laboral y Desarrollo Profesional"

### Content
- H1: "Consolidación de la Trayectoria"
- H2 subtitle: "Nuestro pack más completo, enfocado a profesionales en posiciones Directivas y Ejecutivas."
- **SESIONES DE TRABAJO:** Up to 4 supervised sessions
- **SESIONES DE ENTRENAMIENTO:** 6 consulting sessions

### CTAs
- **"RESERVA COMPLETA"** → `https://book.stripe.com/14AeVd4fX5bEdq3fc9eEo00`
- **"FINANCIACIÓN 200€ /MES"** → `https://buy.stripe.com/3cIdR9eUB1Zs4Txd41eEo01`

### Sidebar (cross-sell)
- LLAMADA INDIVIDUAL (80€) → Stripe
- PACK BASE: Fundamentos (480€) → product page
- PACK COMPLETO: Proyección (600€) → product page

---

## 16. Legal: Aviso Legal (/es/aviso-legal/)

### Content
- **H1: "Aviso legal"**
- **Owner:** Joana Martínez Pardell (JoanaJob)
- **NIF:** 48256690E
- **Address:** C Joan Culleré 1, 6B, 25005 Lleida
- **Contact:** joana@martinez.cat
- **Phone:** 614179980
- **Purpose:** Consulting and training in occupational psychology
- **Intellectual Property:** All content owned by Joana Martínez Pardell; personal, non-exclusive, non-transferable license granted upon payment
- **Liability:** Site content updates with no guarantee of accuracy; modifications reserved

---

## 17. Legal: Política de Privacidad (/es/politica-de-privacidad/)

### Content
- **H1: "Política de privacidad"**
- **Data Controller:** Joana Martínez Pardell (joana@martinez.cat)
- **Processing Purposes:**
  1. Provide and bill services
  2. Manage client relationship
  3. Send commercial communications (with consent)
  4. Manage inquiries via contact form
- **Legal Basis:** Consent + Contract execution
- **Data Categories:** Identification, contact, professional, billing
- **Data Processors/Platforms:** Google, Stripe, Canva, email systems, hosting provider
- **Retention:** 5 years for billing, until consent withdrawal for marketing
- **Rights:** Access, rectification, deletion, objection, limitation, portability
- **International Transfers:** Google, Stripe, Canva provide appropriate safeguards
- **Security:** Access controls, backups, encryption, strong passwords
- **Testimonials:** Anonymous publication, express consent required

---

## 18. Legal: Condiciones Generales (/es/condiciones-generales-y-de-contratacion/)

### Content
- **H1: "Condiciones generales y de contratación"**
- **Owner:** Joana Martínez Pardell (NIF: 48256690E, C Joan Culleré 1, 6B, 25005 Lleida)
- **Scope:** Remote contracting of consulting and training services
- **Acceptance:** Express by checkbox at checkout
- **Contract Language:** Spanish
- **Document Retention:** 1 year
- **Pricing:** In euros, may include VAT
- **Payment Methods:**
  - Full payment at time of purchase
  - Reservation (immediate charge) + 5 monthly installments (6 total charges)
- **Service Start:** After payment confirmation + receipt of required documentation
- **Delivery:** Within 2 weeks of complete documentation
- **Withdrawal:** No right of withdrawal once service has begun (Art. 103 TRLGDCU)
- **No Refunds:** General policy, with exceptions for non-compliance
- **Session Duration:** 45-60 minutes depending on modality
- **No-shows:** Treated as session consumed unless 24h notice given
- **Confidentiality:** All materials confidential
- **Jurisdiction:** Spanish law, courts of Lleida

---

## 19. Legal: Política de Cookies (/es/politica-de-cookies/)

### Content
- **H1: "Política de cookies"**
- **Cookie definition** and classification explanation
- **Own cookies:** `cart_id` (30 days), `PHPSESSID` (session), `cookienator-consent-v*` (1 year)
- **Third-party cookies (Google Analytics):** `_ga`, `_gac_*`, `_gali`, `_gat`, `_gat_*`, `_ga_*`, `_gid`, `__utma`, `__utmb`, `__utmc`, `__utmt`, `__utmv`, `__utmx`, `__utmz`
- **Consent:** Obtained via initial cookie notice banner
- **Withdrawal:** Via browser settings or "Configuración de cookies" link

---

## 20. Accesibilidad (/es/accesibilidad/)

### Content
- **H1: "Accesibilidad"**
- **Declaration:** Site is accessible per UNE-EN 301549:2022 (based on WCAG 2.1)
- **Compliance Level:** AA WCAG 2.1
- **Last Review:** 26/10/2025
- **Contact for issues:** joana@martinez.cat

---

## 21. Mapa Web (/es/mapa-web/)

### Content
- **H1: "Mapa web"**
- **Navigation list with 12 links:**
  1. Inicio → `/es/`
  2. Esencia → `/es/esencia/`
  3. Servicios → `/es/servicios/`
  4. Contacto → `/es/contacto/`
  5. Recursos → `/es/recursos/`
  6. Aviso legal → `/es/aviso-legal/`
  7. Política de privacidad → `/es/politica-de-privacidad/`
  8. Condiciones generales y de contratación → `/es/condiciones-generales-y-de-contratacion/`
  9. Política de cookies → `/es/politica-de-cookies/`
  10. Configuración de cookies → JavaScript event
  11. Mapa web → `/es/mapa-web/`
  12. Accesibilidad → `/es/accesibilidad/`

---

## 22. English Version (/en/)

Same structure as Spanish homepage with translated content:
- **H1:** "Workplace Psychologist"
- **CTA:** "Book a Call"
- **Products:** "STANDARD PACK" (Career Foundations), "COMPLEATE PACK" [sic] (Growth Projection), "PREMIUM PACK" (Career Consolidation)
- **Tagline:** "Our costumers are part of" [typo: should be "customers"]
- **H2:** "OWR CLIENTS ARE PART OF INTERNATIONALLY RENOWN BUSINESSES" [typo: "OWR" should be "OUR"]
- **Social proof:** "Over 130 professionals from 27 countries"
- **Business sections:** Entrepreneurs, Companies, Organizations and Universities
- **Footer:** Same structure, "My cart", "Resources", "Contact", "Essence", "Services"
- **Note:** Translation has multiple typos and inconsistencies

---

## 23. Catalan Version (/ca/)

Same structure as Spanish homepage with Catalan translation:
- **H1:** "Especialistes Psicòloga Laboral"
- **CTA:** "Reserva Trucada Informativa"
- **Products:** "PACK BASE" (Fonaments Laborals), "PACK COMPLET" (Projecció del Creixement), "PACK PREMIUM" (Consolidació de la Trajectòria)
- **Tagline:** "Els nostres clients formen part de"
- **Social proof:** "+130 professionals de 27 països"
- **Footer:** "El meu cistell", "Recursos", "Contacte", "Essència", "Serveis"

---

## 24. E-commerce / Cart System

### How Products Are Sold
The site has **two separate purchasing flows:**

#### Flow 1: Consulting Packs (via Stripe)
- Product pages (Fundamentos Laborales, Proyección del Crecimiento, Consolidación de la Trayectoria) link **directly to Stripe Checkout**
- "RESERVA COMPLETA" → `book.stripe.com/...` (Stripe booking/payment page)
- "FINANCIACIÓN X€/MES" → `buy.stripe.com/...` (Stripe payment link with installment plan)
- These are external links — they bypass the internal cart system entirely
- The "0 Mi cesta" counter does NOT track these products

#### Flow 2: Digital Documents (via Internal Cart)
- The Recursos page offers digital documents for 30€ each
- These appear to use the internal cart/checkout system
- The internal cart URL: `/es/proceso-de-compra/step1/`
- The cart dropdown: `//www.joanajob.com/es/account/login/?back=/es/...` (requires login)

#### Checkout Page (/es/proceso-de-compra/step1/)
- Shows: Product listing, quantity, total
- Empty state: "Tu cesta está vacía."
- **Account options:**
  - Register (with login link)
  - Guest checkout
- **Form fields:**
  - Correo electrónico* (email)
  - Contraseña* (password) + confirm
  - Nombre y apellidos o Empresa* (billing name/company)
  - NIF/CIF* (tax ID)
  - Teléfono* (phone)
  - Dirección* (address, max 50 chars)
  - Código postal* (postal code)
  - Población* (city, max 50 chars)
  - País* (country dropdown — comprehensive list of countries)

#### Cart/Account Links
- Shopping bag icon → `/es/proceso-de-compra/step1/`
- User icon → `/es/account/login/`
- "Mi cesta" in nav → `/es/proceso-de-compra/step1/`
- "Mi cesta" in mobile → `/es/account/login/?back=/es/`

#### Stripe Payment Links Summary
| Product | Full Payment | Financing |
|---------|-------------|-----------|
| Fundamentos Laborales (480€) | `book.stripe.com/00w9AT13L7jM3PtaVTeEo02` | `buy.stripe.com/6oU9ATeUB33w1Hl0hfeEo03` |
| Proyección del Crecimiento (600€) | `book.stripe.com/8x200j5k1bA25XBfc9eEo04` | `buy.stripe.com/4gM28raEl7jM99N5BzeEo05` |
| Consolidación de la Trayectoria (1.200€) | `book.stripe.com/14AeVd4fX5bEdq3fc9eEo00` | `buy.stripe.com/3cIdR9eUB1Zs4Txd41eEo01` |
| Orientación Profesional (80€) | `buy.stripe.com/14A8wPcMt47A85J6FDeEo06` | — |

---

## 25. Cookie Consent System (Cookienator)

The site uses a custom cookie consent system called **Cookienator** (self-hosted JavaScript).

### Configuration
```javascript
window.CookienatorSettings = {
    thirdParties: true,
    placeholder: true,
    cookiesPolicyUrl: '/es/politica-de-cookies',
    whiteList: [/^data:image\/svg\+xml/, /^blob:/, /^data:/, /gestionaweb\.cat/, /recaptcha/, /recaptcha\.net/, /vz-49f9ecdf-f80\.b-cdn\.net/, /analytics\.google\.com/],
    forceRefreshOnAccept: false,
    providers : ["google-analytics.com"]
};
```

### Cookie Banner
- Shows at bottom of page
- Buttons: "Aceptar cookies" (Accept), "Rechazar cookies" (Reject), "Más opciones" (More options)
- Link to "política de cookies"

### Cookie Categories
- **Measurement (analytics):** Google Analytics cookies
- **Advertising:** No advertising cookies configured

### Storage
- Consent stored in cookie `cookienator-consent-v3` (365 days expiry)
- Blocks scripts/iframes/images until consent is given
- Uses DOM mutation observer to catch dynamically loaded elements
- Placeholder system for blocked iframes/images

---

## 26. Accessibility Audit

### What's Present
- `sr-only` (screen-reader only) class used for icon labels
- Skip link? Not visible in the snapshot
- Alt text on most images (some generic like "Imagen PACK BASE", "MAPA", "GRAFICO")
- Semantic heading structure (h1, h2, h3 used)
- `lang` attribute on `<html>` tag
- `aria-label` not consistently found in snapshot

### Issues Found
1. **Logo images with alt="Joana Job"** repeated in header and footer — should use site title for one, decorative empty alt for the other
2. **Decorative images** like "LAPICERO", "MAPA", "GRAFICO", "travel-brand-guidelines-presentation-5.png" have no meaningful alt text — should have `alt=""` for truly decorative images
3. **Client logo carousel** has no alt text on logo images (empty alt) — this is acceptable for decorative logos
4. **No visible skip-to-content link** — important for keyboard users
5. **Carousel buttons** use icon-only text "" and "" — no visible text labels for screen readers
6. **Color contrast:** Light blue nav background (#bdd2ff) with #2e2e2e text — may have contrast issues
7. **Form labels** on contact page appear to use `LabelText` but need proper `for` attributes
8. **Cookie banner** uses generic Arial font rather than site font

### Self-Declaration
- Claims **AA WCAG 2.1** compliance
- Standard: **UNE-EN 301549:2022**
- Last reviewed: **26/10/2025**
- Contact for issues: joana@martinez.cat

---

## 27. All Images Inventory

| Image URL | Alt Text | Pages Used |
|-----------|----------|------------|
| `https://images.gestionaweb.cat/7517/pqimg-240-240/baixa-3-2.jpg` | "Joana Job" | ALL pages (header logo) |
| `https://images.gestionaweb.cat/7517/pqimg-640-640/captura-de-pantalla-2025-10-20-a-las-9-25-19.png` | "Joana Job" | ALL pages (footer logo) |
| `https://images.gestionaweb.cat/7517/img-480-270/1000044878-fd9ec1f8f9c117f7452300f0a82fa3ee-11-4-2024-6-38-38-pm-2-2.jpg` | "Imagen Especialistas en Psicología Laboral" | Homepage hero |
| `https://images.gestionaweb.cat/7517/img-480-0/pexels-andri-file-288172640-36906867-1.jpg` | "Imagen PACK BASE" | Homepage |
| `https://images.gestionaweb.cat/7517/img-480-0/diseno-sin-titulo-13.png` | "Imagen PACK COMPLETO" | Homepage |
| `https://images.gestionaweb.cat/7517/img-480-0/diseno-sin-titulo-14.png` | "Imagen PACK PREMIUM" | Homepage |
| `https://images.gestionaweb.cat/7517/pwimg-480/ad2431ac-1465-4daa-a134-ec42a1157195.jpg` | "LAPICERO" | Homepage |
| `https://images.gestionaweb.cat/7517/pwimg-480/mapa2.png` | "MAPA" | Homepage |
| `https://images.gestionaweb.cat/7517/pwimg-480/grafico2.png` | "GRAFICO" | Homepage |
| `https://images.gestionaweb.cat/7517/pwimg-480/1-2.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/pwimg-480/2-logos.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/pwimg-480/3-logos.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/pwimg-480/4-logos.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/pwimg-480/5-logos.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/pwimg-480/6-logos.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/pwimg-480/7-logos.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/pwimg-480/8-logos.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/pwimg-480/9-logos.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/pwimg-480/10-logos.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/pwimg-480/11-logos.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/pwimg-480/12-logos.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/pwimg-480/13-logos.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/pwimg-480/14-logos.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/pwimg-480/15-logos.png` | (empty) | Homepage (client logo) |
| `https://images.gestionaweb.cat/7517/img-480-270/captura-de-pantalla-2025-10-24-125121-2.png` | (empty) | Esencia page |
| `https://images.gestionaweb.cat/7517/img-480-480/travel-brand-guidelines-presentation-5.png` | (empty) | Esencia page |
| `https://images.gestionaweb.cat/7517/img-480-480/travel-brand-guidelines-presentation-7.png` | (empty) | Esencia page |
| `https://images.gestionaweb.cat/7517/img-480-480/travel-brand-guidelines-presentation-6.png` | (empty) | Esencia page |
| `https://images.gestionaweb.cat/7517/pwimg-480/logo-gray-en.png` | (empty) | Esencia page |
| `https://images.gestionaweb.cat/7517/pwimg-480/r.png` | (empty) | Esencia page |
| `https://images.gestionaweb.cat/7517/imgf-1200-630/captura-de-pantalla-2025-10-20-a-las-12-40-28-4.png` | OG image (no alt) | All pages (social sharing) |
| `https://docs.gestionaweb.cat/0000/kit-digital/kd-ue-nextgeneration-white-negative.svg` | "Financiado por la Unión Europea NextGenerationEU" | Footer (all pages) |
| `https://docs.gestionaweb.cat/0000/kit-digital/kd-govern-white-negative.svg` | "Gobierno de España" | Footer (all pages) |
| `https://docs.gestionaweb.cat/0000/kit-digital/kd-logo-plan-white-negative.svg` | "Plan de Recuperación, Transformación y Resiliencia" | Footer (all pages) |
| `https://docs.gestionaweb.cat/7517/logo2.ico` | Favicon (no alt) | ALL pages |

---

## 28. All Links Inventory

### External Links

| Text | URL | Target | Rel |
|------|-----|--------|-----|
| Llamada Informativa | `https://calendar.google.com/calendar/u/0/appointments/AcZssZ0eFx3oKzJ0E7Ke6MsrUKRqMrmT5W_bdr6Ub6c=` | _blank | — |
| Instagram Joana Job | `https://www.instagram.com/joanajob.es?igsh=MXVqNGU0MDFpcGxkaw==` | _blank | nofollow |
| Linkedin Joana Job | `https://www.linkedin.com/in/joana-mart%C3%ADnez-pardell/` | _blank | nofollow |
| Instagram | same Instagram URL | _blank | nofollow |
| Linkedin | same LinkedIn URL | _blank | nofollow |
| Hooba web | `https://www.hooba.com/es/` | _blank | — |
| AEPD | `https://www.aepd.es` | — | — |
| RESERVA COMPLETA (Fundamentos) | `https://book.stripe.com/00w9AT13L7jM3PtaVTeEo02` | — | — |
| FINANCIACIÓN 80€/MES | `https://buy.stripe.com/6oU9ATeUB33w1Hl0hfeEo03` | — | — |
| RESERVA COMPLETA (Proyección) | `https://book.stripe.com/8x200j5k1bA25XBfc9eEo04` | — | — |
| FINANCIACIÓN 100€/MES | `https://buy.stripe.com/4gM28raEl7jM99N5BzeEo05` | — | — |
| RESERVA COMPLETA (Consolidación) | `https://book.stripe.com/14AeVd4fX5bEdq3fc9eEo00` | — | — |
| FINANCIACIÓN 200€/MES | `https://buy.stripe.com/3cIdR9eUB1Zs4Txd41eEo01` | — | — |
| RESERVAR POR 80€ | `https://buy.stripe.com/14A8wPcMt47A85J6FDeEo06` | — | — |
| Email | `mailto:joana@martinez.cat` | — | — |

### Internal Navigation Links

| Text | URL |
|------|-----|
| Inicio | `/es/` |
| Esencia | `/es/esencia/` |
| Servicios | `/es/servicios/` |
| Contacto | `/es/contacto/` |
| Recursos | `/es/recursos/` |
| Mi cesta | `/es/proceso-de-compra/step1/` |
| Mi cuenta | `/es/account/login/` |
| FUNDAMENTOS LABORALES | `/es/productos/fundamentos-laborales/` |
| PROYECCIÓN DEL CRECIMIENTO | `/es/productos/proyeccion-del-crecimiento/` |
| CONSOLIDACIÓN DE LA TRAYECTORIA | `/es/productos/consolidacion-de-la-trayectoria/` |
| CONOCE A NUESTROS CLIENTES | `/es/esencia/#section-466018` |
| Aviso legal | `/es/aviso-legal/` |
| Política de privacidad | `/es/politica-de-privacidad/` |
| Condiciones generales y de contratación | `/es/condiciones-generales-y-de-contratacion/` |
| Política de cookies | `/es/politica-de-cookies/` |
| Configuración de cookies | `javascript:document.dispatchEvent(new Event('cookienator:show-configurator'))` |
| Mapa web | `/es/mapa-web/` |
| Accesibilidad | `/es/accesibilidad/` |
| Español | `/es/` |
| Català | `/ca/` |
| English | `/en/` |

---

## 29. Summary of Findings

### Strengths
- **Clean, modern design** with Poppins + Lora fonts
- **Good SEO foundation** with proper meta tags, OG tags, hreflang, canonical URLs, and schema.org
- **Multilingual** (ES/CA/EN) with proper hreflang implementation
- **Legal compliance:** Privacy policy, cookie policy, terms & conditions, accessibility statement, aviso legal all present
- **Direct Stripe integration** for service purchases — clean checkout flow
- **Cookie consent** with granular controls (accept/reject/configure)
- **Accessibility declaration** at AA WCAG 2.1 level
- **Footer is consistent** across all pages
- **CO₂ donation messaging** shows social responsibility

### Issues & Areas for Improvement

#### Content Issues
1. **English typos:** "OWR CLIENTS" should be "OUR CLIENTS", "costumers" should be "customers", "COMPLEATE" should be "COMPLETE", "WE ALLSO" should be "WE ALSO", "Etrepreneurs" should be "Entrepreneurs"
2. **Spanish typos:** "PREFERENCIAAS" should be "PREFERENCIAS" (on product pages)
3. **No blog/articles** — the resources page is under construction with only 3 documents available
4. **Product page content** is duplicated across all three products (same 6 areas listed)

#### UX Issues
5. **Two separate purchase flows** — consulting packs go directly to Stripe (bypassing cart), while documents use the internal cart. This creates confusion.
6. **No add-to-cart functionality for main products** — "RESERVA COMPLETA" goes directly to Stripe, which means the cart counter always shows "0"
7. **Cart flow requires login** — `/es/account/login/` is a prerequisite to accessing the cart
8. **No search functionality** evident on the site
9. **No 404 page** detected in the audit
10. **Mobile menu** uses off-canvas pattern which is good, but language switching in mobile could be more intuitive
11. **Cookie banner** can be visually intrusive

#### Accessibility Issues
12. **No visible skip-to-content link** found
13. **Carousel previous/next buttons** use unicode icons without visible text labels
14. **Decorative images** have descriptive alt text when they should have `alt=""` (e.g., "LAPICERO", "MAPA", "GRAFICO")
15. **Logo images** repeated in header and footer with same alt text
16. **Light blue nav background** with dark text — color contrast not verified but potentially borderline

#### Technical Issues
17. **CSS minified** — hard to customize without full source
18. **Custom icon font** (FontCustom) used — may not render on all systems
19. **Schema.org only on Consolidación product page** — missing on other product pages
20. **No HTTPS redirect enforcement** evident
21. **No performance optimization** evident (large images loaded directly)

#### E-commerce Issues
22. **No product images on product pages** — images only shown on homepage
23. **No reviews/ratings on product pages** — testimonials are on the Esencia page
24. **Cart doesn't show main products** — confusing user experience
25. **No stock/availability indicators** for the services

### Page Count
- Total pages audited: **16**
- 3 language versions of homepage (ES, CA, EN)
- 3 product pages
- 1 services listing page
- 1 about (esencia) page
- 1 contact page (with form)
- 1 resources page (with cart documents)
- 5 legal pages (aviso legal, privacidad, condiciones, cookies, accesibilidad)
- 1 sitemap page

### Technology Stack
- **Frontend:** Next.js (custom, using GestiónWeb platform)
- **Hosting:** gestionaweb.cat infrastructure
- **E-commerce:** Self-built PHP-based cart system
- **Payments:** Stripe (via `book.stripe.com` and `buy.stripe.com`)
- **Fonts:** Google Fonts (Poppins + Lora)
- **Icons:** Font Awesome 7 Pro + custom icon font
- **Image CDN:** images.gestionaweb.cat
- **Cookie Consent:** Custom "Cookienator" script
- **Image Lightbox:** Fancybox-style viewer (CSS custom properties `--f-*`)
- **Analytics:** Google Analytics (categorized in cookie consent)
- **Schema:** JSON-LD structured data

---

*End of Audit*
