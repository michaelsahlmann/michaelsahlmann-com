# Michael Sahlmann — Sitio Web Oficial

> **"Libera tu potencial. Más con menos esfuerzo."**  
> Sitio web personal y profesional de **Michael Sahlmann** — Experto en Negocios, Productividad de Élite e Inteligencia Artificial Estratégica.  
> Dominio objetivo: [`https://michaelsahlmann.com/`](https://michaelsahlmann.com/)

---

## ⚡ Enfoque: Velocidad Absoluta & Estética de Élite

Construido específicamente para sustituir el entorno WordPress anterior por una arquitectura estática moderna de ultra-alto rendimiento (Astro 5 + Tailwind CSS v4) orientada a alcanzar **100/100 en Google Lighthouse & Core Web Vitals**:

- **Tiempo de carga instantáneo (TTFB < 10ms)**: Pre-renderizado 100% estático servido desde el Anycast Edge CDN global de Vercel.
- **Cero dependencias innecesarias de JavaScript en el cliente**: Rendimiento nativo sin penalización de hidratación de frameworks pesados.
- **Tríada Tipográfica Varkentis 100% Self-Hosted**:
  - `Young Serif` para títulos, marca y contundencia editorial.
  - `Labrada` para lectura inmersiva y cuerpo de texto.
  - `JetBrains Mono` para datos, métricas y badges técnicos.
  - Todas las fuentes cuentan con formato `.woff2` y `<link rel="preload">` para **0 Cumulative Layout Shift (CLS)**.
- **Activos Optimizados**: Fotografías de conferencias en formato `.webp` de última generación y logotipo vectorial SVG.

---

## 🏛️ Estructura & Secciones

1. **Header Flotante en Cápsula**: Barra de navegación flotante con `backdrop-blur`, acceso directo y menú móvil responsive.
2. **Hero Section**: Titular contundente, propuesta de valor, indicador de disponibilidad en Asunción, Paraguay, fotografía oficial en escenario y barra de KPIs (`+9 Años`, `+493 Alumnos`, `50% Eficiencia`, `Vida Legendaria`).
3. **Sobre Mí (Trayectoria & Filosofía)**: La historia de Michael, desde su sólida experiencia en el sector bancario financiero hasta su rol como pionero de IA empresarial en Paraguay.
4. **Los 5 Pilares de la Metodología**:
   - `01. Optimización de Negocios & Procesos (Framework Linchpin)`
   - `02. Gestión Avanzada de Productividad & Foco (Brian Tracy & Deep Work)`
   - `03. Implementación Estratégica de Inteligencia Artificial (N8N & LLMs)`
   - `04. Liderazgo & Mentalidad Empresarial Legendaria (El Ejecutor)`
   - `05. Transformación de Equipos de Alto Rendimiento`
5. **Evidencia Operativa**: Contraste analítico entre el modelo tradicional obsoleto (40 hrs de trabajo manual/semana) y el ecosistema optimizado con IA (20 hrs liberadas), desglosando métricas en PYMES paraguayas.
6. **Calculadora Interactiva de ROI**: Herramienta interactiva en tiempo real donde el empresario ajusta su tamaño de equipo, horas manuales y costo laboral para obtener horas recuperadas y ahorro proyectado en USD. Incluye botón directo con mensaje preconfigurado para WhatsApp.
7. **Servicios & Soluciones**: 4 modalidades (Consultoría en IA, Conferencias Magistrales, Entrenamiento In-Company y Mentoría 1 a 1).
8. **Testimonios & Social Proof**: Avales reales de directores y empresarios capacitados.
9. **Contacto & Formulario**: Formulario estratégico con validación instantánea y enlace directo prioritario a WhatsApp.
10. **Footer Institucional**: Cita de marca (*"Paraguay puede estar atrasado. Vos no."*), enlaces y copyright.

---

## 🚀 Despliegue en Vercel

El repositorio ya está creado y sincronizado en GitHub:  
👉 **[https://github.com/michaelsahlmann/michaelsahlmann-com](https://github.com/michaelsahlmann/michaelsahlmann-com)**

### Opción 1: Conexión Automática con 1 Clic (Recomendada)
1. Entra a tu cuenta en [vercel.com](https://vercel.com).
2. Haz clic en **"Add New..."** &rarr; **"Project"**.
3. Selecciona el repositorio **`michaelsahlmann-com`**.
4. Vercel detectará automáticamente que es un proyecto **Astro**.
5. Haz clic en **Deploy**. ¡Estará publicado en ~10 segundos!
6. En la pestaña **Settings &rarr; Domains**, agrega `michaelsahlmann.com` y `www.michaelsahlmann.com`.

### Opción 2: Despliegue directo por CLI
Desde esta misma terminal en `/mnt/sandisk/projectos/michael_page`:
```bash
# 1. Iniciar sesión en Vercel
npx vercel login

# 2. Desplegar a producción
npx vercel --prod
```

---

## 🛠️ Comandos de Desarrollo Local

```bash
# Iniciar servidor de desarrollo local
npm run dev

# Compilar para producción (genera /dist en menos de 0.5s)
npm run build

# Previsualizar la versión de producción
npm run preview
```
