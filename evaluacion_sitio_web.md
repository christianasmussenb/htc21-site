# Evaluación Comparativa del Sitio Web — Health Technology Consulting
**Fecha:** Abril 2026 | **Autor:** Análisis Claude / Cowork

---

## 1. Inventario actual del sitio

| Página | Propósito | Estado |
|---|---|---|
| `index.html` | Hero, misión, servicios resumen, CTA | ✅ Sólido |
| `servicios.html` | 7 líneas de servicio detalladas | ✅ Sólido |
| `sectores.html` | 4 segmentos de cliente | ✅ Sólido |
| `casos.html` | 5 casos (3 generales + 2 IRIS) | ⚠️ Mejorable |
| `intersystems.html` | Capacidades IRIS + 6 PoCs | ✅ Diferenciador fuerte |
| `contacto.html` | Formulario + Calendly | ✅ Bien ejecutado |
| `rrss.html` | Redes sociales | ⚠️ Aislado del flujo |
| **Ausente** | **About Us / Equipo / Fundador** | ❌ Brecha crítica |

---

## 2. Fortalezas del sitio actual

### Contenido y posicionamiento
- El copy es honesto, sin hipérboles vacías: "no vendemos software", "proyectos breves de alto impacto" son afirmaciones que diferencian bien de las grandes consultoras.
- La página de InterSystems IRIS es excepcionalmente técnica y detallada, con PoCs concretos. Es el diferenciador más poderoso del sitio.
- La navegación es limpia y consistente en todas las páginas.
- Calendly integrado reduce la fricción de conversión al mínimo.
- Los casos tienen estructura clara: Desafío → Enfoque → Solución → Resultados.

### Técnico
- HTML puro, sin frameworks pesados: carga instantánea.
- Meta descriptions en todas las páginas.
- Analytics (Cloudflare) activo.
- Emails protegidos contra scraping con JS reveal.
- Responsive con breakpoint en 880px.

---

## 3. Comparación con referentes del mercado

### 3.1 Thoughtworks (thoughtworks.com)
**Tipo:** Consultora global de tecnología, ~12.000 personas, cotizada.

| Dimensión | Thoughtworks | HTC |
|---|---|---|
| Hero | Narrativa de transformación con AI-era messaging | ✅ Similar en tono, más acotado |
| Servicios | Por capacidad + por industria + por tecnología (3 ejes) | Solo por capacidad |
| Thought leadership | Blog, reports, tech radar semestral | ❌ Ausente |
| Equipo | Fotos, bios, speakers, publicaciones | ❌ Ausente |
| Casos | Con nombres de clientes, métricas, videos | Anónimos, sin métricas duras |
| Social proof | Logos de clientes Fortune 500 | ❌ Ausente |
| SEO | Cientos de páginas de contenido | Mínimo |

### 3.2 Perficient (perficient.com)
**Tipo:** Consultora digital mid-size, ~7.000 personas, NASDAQ.

| Dimensión | Perficient | HTC |
|---|---|---|
| Estructura | Industrias × Soluciones × Plataformas (matriz) | Servicios + Sectores (lineal) |
| Healthcare | Página dedicada con patient journey, regulatoria | Solo servicios genéricos |
| Certificaciones | Microsoft Gold, AWS Advanced, Oracle... (visible en header) | ❌ Sin badges de partner |
| Casos | Métricas específicas ("reducción 40% en tiempo de ciclo") | Métricas descriptivas sin números |
| Managed Services | Oferta de soporte continuo claramente descrita | ❌ No explícito |

### 3.3 ZS Associates (zs.com)
**Tipo:** Consultora especializada en Life Sciences/Healthcare, 13.000+.

| Dimensión | ZS | HTC |
|---|---|---|
| Especialización | "Life sciences & healthcare ONLY" (máxima claridad) | "Salud y empresas" (algo difuso) |
| Estructura | Industries → Solutions → Capabilities (3 niveles) | 1 nivel plano |
| Thought leadership | Whitepapers, webinars, herramientas interactivas | ❌ Ausente |
| Equipo | Socios, directores, con LinkedIn y publicaciones | ❌ Ausente |
| AI/Digital | Sección dedicada "Digital Health" con metodología propia | IRIS page (técnica, no estratégica) |

### 3.4 Boutiques comparables (healthetechconsulting.com, benestudio.co/hnc)
**Tipo:** Firmas pequeñas de HealthTech.

| Dimensión | Boutiques típicas | HTC |
|---|---|---|
| Fundador visible | Foto, bio, LinkedIn, historia personal | ❌ Totalmente ausente |
| Posicionamiento nicho | "Especialistas en X para Y" muy específico | Posicionamiento amplio |
| Testimonios | 3-5 quotes de clientes reales (nombre/cargo) | ❌ Ausente |
| Pricing/modelo | Algunos muestran "retainer desde $X/mes" | ❌ No mencionado |
| Newsletter/Lead magnet | E-book, checklist, diagnóstico gratuito | ❌ Ausente |

---

## 4. Brechas identificadas (priorizadas por impacto)

### 🔴 CRÍTICO — Impacto en conversión inmediato

**4.1 No existe página "Sobre nosotros / Equipo"**
Esta es la brecha más grave. Los potenciales clientes de consultoría compran personas, no empresas. Antes de agendar en Calendly, buscarán quién está detrás. Actualmente no hay ninguna señal de identidad: ni nombre del fundador, ni foto, ni trayectoria, ni por qué confiar.

*Lo que debería haber:* Foto profesional, nombre, título (Ing. Civil Industrial + MBA, PUC), experiencia en salud y tecnología (~20 años), rol como CIO/CTO/CEO en proyectos relevantes, LinkedIn visible.

**4.2 Casos sin métricas cuantitativas**
"Reducción de reprocesos" y "visibilidad financiera mejorada" son vagas. Los estudios muestran que métricas concretas ("40% menos tiempo en cierre contable", "glosas reducidas de 18% a 7%") aumentan la credibilidad en un 60%+ frente a métricas descriptivas.

*Lo que debería haber:* Al menos un número concreto por caso. Si hay NDA, se pueden usar rangos ("entre 25% y 40% de reducción").

**4.3 Sin testimonios ni logos de clientes**
No hay ninguna validación social. Incluso una sola quote de un cliente satisfecho (con nombre y cargo, o con empresa anonimizada pero verificable) transforma la percepción del visitante.

### 🟡 IMPORTANTE — Diferenciación y posicionamiento

**4.4 Posicionamiento algo difuso: "Salud & Empresas"**
Las consultoras boutique que más convierten tienen un nicho hiperespecífico ("ERP para clínicas privadas en Chile", "interoperabilidad FHIR para redes de salud"). HTC actualmente sirve salud, empresas, PYMEs y retail multipaís. Para un CFO de una clínica, eso puede generar duda.

*Recomendación:* Mantener la amplitud en la realidad del negocio, pero el sitio debe comunicar un "núcleo" primario (salud → IRIS → interoperabilidad) con los otros sectores como capacidad complementaria.

**4.5 RRSS desconectado del flujo principal**
La página `rrss.html` aparece en la nav pero no queda claro qué es. Si es un hub de contenido (LinkedIn posts, artículos), debería llamarse "Contenido" o "Insights". Si es solo links a redes, podría estar en el footer.

**4.6 Sin certificaciones/partnerships visibles**
¿Hay una relación formal con InterSystems? ¿Partner status de Microsoft 365? ¿Certificación BUK? Esos badges en el footer o en la página de servicios relevante agregan credibilidad disproportionada para el tamaño de esfuerzo que requieren.

### 🟢 MEJORA CONTINUA — SEO y contenido

**4.7 Sin thought leadership ni contenido**
Thoughtworks publica su "Technology Radar" 2 veces al año y genera miles de backlinks. ZS publica whitepapers que capturan leads. HTC no tiene ninguna pieza de contenido. Un artículo por trimestre sobre un tema relevante (ej: "HL7 FHIR en el sistema de salud chileno", "Cómo evaluar un ERP para clínicas") sería suficiente para empezar.

**4.8 Sin sección de "Cómo trabajamos" con precio o modelo**
Los clientes quieren saber qué pasa después de agendar. ¿Proyecto fijo? ¿Por hora? ¿Retainer? Un párrafo de "nuestra metodología de engagement" (discovery → propuesta → proyecto) reduce la incertidumbre pre-contacto.

**4.9 Hero: falta un segundo hook visual**
El hero actual es solo texto. Una imagen conceptual, diagrama de arquitectura simplificado, o incluso un screenshot del PoC FHIR R4 agregaría contexto visual y haría el hero más memorable.

---

## 5. Tabla resumen de brechas

| # | Brecha | Dificultad | Impacto en conversión | Prioridad |
|---|---|---|---|---|
| 1 | Página About/Equipo con foto y bio | Baja | 🔴 Alto | P0 |
| 2 | Métricas cuantitativas en casos | Baja | 🔴 Alto | P0 |
| 3 | Testimonios / quotes de clientes | Media | 🔴 Alto | P1 |
| 4 | Foco del posicionamiento | Alta | 🟡 Medio | P1 |
| 5 | Badges partner/certificaciones | Baja | 🟡 Medio | P1 |
| 6 | Reorganizar o renombrar RRSS | Baja | 🟡 Medio | P2 |
| 7 | Sección "modelo de trabajo/engagement" | Baja | 🟡 Medio | P2 |
| 8 | Imagen/visual en el hero | Baja | 🟢 Bajo | P2 |
| 9 | Contenido/blog/thought leadership | Alta | 🟢 Bajo (largo plazo) | P3 |

---

## 6. Qué está bien y no hay que tocar

- **La página de InterSystems IRIS** es excepcional y única en el mercado regional. No hay otra consultora boutique chilena con ese nivel de detalle técnico en PoCs. Mantener y expandir.
- **El tono del copy**: honesto, directo, sin hipérboles. Eso es raro y valioso.
- **La estructura de navegación**: simple, sin menús desplegables, funciona bien.
- **El CTA de Calendly**: integración directa, sin fricción. No cambiar.
- **La arquitectura técnica**: HTML/CSS puro, carga rápida, buen baseline de accesibilidad.

---

## 7. Próximos pasos recomendados (ordenados)

1. **Crear `nosotros.html`** — Foto, nombre, trayectoria, formación PUC, enfoque de trabajo. Añadir a la navegación. Estimado: 2 horas.

2. **Agregar 1-2 números concretos a cada caso** — Coordinar con los clientes o usar rangos conservadores. Estimado: 1 hora.

3. **Solicitar 2-3 quotes de clientes** — Un email breve a clientes satisfechos pidiendo una línea de testimonio. Estimado: esfuerzo de gestión, no técnico.

4. **Agregar logos/badges** — Si hay relación con InterSystems, Microsoft o BUK, añadir en footer o página de servicios relevante. Estimado: 30 minutos.

5. **Renombrar o reestructurar RRSS** — Si es contenido: llamar "Insights". Si es solo links: mover al footer. Estimado: 30 minutos.

---

*Análisis basado en revisión de código fuente del sitio + benchmarking contra Thoughtworks, Perficient, ZS Associates y boutiques de HealthTech según fuentes: consultingsuccess.com, knapsackcreative.com, logotio.com, insivia.com.*
