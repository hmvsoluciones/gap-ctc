# CTC Telecom — GAP Analysis Estratégico
### Presentación ejecutiva para Dirección General · HMV Soluciones

Presentación en **reveal.js** (18 diapositivas, formato 16:9, 1440×810) construida a partir del análisis de procesos, la transcripción de la reunión de levantamiento y las notas de campo de noviembre de 2026.

---

## Cómo abrirla

**Opción 1 — doble clic**
Abrir `index.html` en Chrome, Edge o Firefox.

**Opción 2 — servidor local (recomendado si el navegador bloquea fuentes)**
```bash
cd presentacion-gap-analysis
python -m http.server 8765
```
Abrir `http://127.0.0.1:8765/`.

## Navegación

| Tecla | Acción |
|---|---|
| `→` / `Espacio` | Siguiente diapositiva |
| `←` | Anterior |
| `F` | Pantalla completa |
| `O` | Vista general |
| `S` | Notas del expositor (si el plugin de notas está activo) |
| `Esc` | Salir de la vista general |

También se puede navegar con los controles de la esquina inferior derecha y con la barra de progreso.

---

## Estructura (18 diapositivas)

1. **Portada** — GAP Analysis / Análisis de Brechas, solo con los logos CTC × HMV.
2. **Lo que aporta HMV** — mapa visual de capacidades: tecnología e innovación, arquitectura e ingeniería, metodologías ágiles, gestión y aseguramiento, gobernanza, negocio y procesos.
3. **Resumen ejecutivo** — la tesis: la operación creció, el sistema operativo no. KPIs: 38 procesos, 0 aprobados, 30 h extras, 3 almacenes.
4. **Diagnóstico** — “No es falta de demanda. Es falta de estructura”; 32 estados, 5 países, 3 almacenes.
5. **Cadena de valor** — 6 etapas de CTC mapeadas a eTOM, con los procesos documentados que embonan en cada una.
6. **Procesos en eTOM** — listado completo: 33 procesos agrupados en 8 dominios principales (mercado/venta, producto, cumplimiento, aseguramiento, facturación, cliente, empresa y proveedores) + 5 mapas de referencia = 38 documentos.
7. **GAP Analysis** — 8 macroprocesos con madurez, riesgo, prioridad y evidencia actualizada (CRM no funcional, almacén en implementación, procesos objetivo sin implementar, seguridad sin roles).
8. **Evidencia** — 6 dolores que más cuestan y su impacto (1–10).
9. **Madurez** — 38 procesos documentados y 0 aprobados/implementados; “Lo que ya existe”: ingresos altos, inversión en mejora continua, 2 iniciativas activas y red propia.
10. **Brechas transversales** — personas (resistencia a controles, horas extras fuera de presupuesto), procesos, tecnología (herramientas que no se usan) y datos.
11. **Causa raíz** — la pila que sostiene el problema y la proporción 10/90.
12. **Decisión tecnológica** — “la herramienta no arregla el proceso”; ERP y OSS explicados en palabras llanas.
13. **Secuencia** — fases 0 a 3: identificación y rediseño, especificación, diseño del flujo, herramientas; compuertas de salida y pausa de QA.
14. **Solución híbrida** — Jira para acción inmediata, agentes de IA en procesos críticos, software a medida en procesos normalizados e integraciones con APIs; 30 días / 90 días / 12 meses.
15. **Decisiones** — las cinco decisiones que se piden al CEO, incluido el piloto híbrido.
16. **Mensaje para el CEO** — la cita que resume el diagnóstico.
17. **Próximos pasos** — 30 días, CTA e hitos 30/60/90/120.
18. **Cierre** — “El siguiente paso no es comprar más software; es construir el sistema operativo de CTC”, con CTA para arrancar la fase 0 y bloque de contacto.

> La página de soluciones también está disponible como archivo independiente: **`soluciones.html`**.

---

## Branding

- **Base:** marfil cálido `#F8F6EF`.
- **Tinta:** carbón `#1B1D17`.
- **Acento:** lima HMV `#C9E265` para fondos y detalles; olivo `#6F8A2F` para texto sobre claro (contraste accesible).
- **Riesgo:** terracota `#B9553F`, ámbar `#B9852A`, salvia `#6C8C68`.
- **Tipografía:** Fraunces (títulos, elegante y legible), Source Sans 3 (texto), JetBrains Mono (etiquetas y cifras).
- **Logos:** solo CTC Telecom y HMV Soluciones, en versión monocromática de tinta para el tema claro.
- **Estilo:** editorial, luminoso y minimalista; tarjetas blancas con sombra muy sutil, retícula tenue y acentos lima.

Los logos se tomaron de `hmvsoluciones.com` y `ctctelecom.mx`; la presentación no usa otras imágenes.

---

## Archivos

```
presentacion-gap-analysis/
├── index.html                  # La presentación completa (18 diapositivas)
├── soluciones.html             # Página independiente de soluciones
├── css/
│   └── hmv.css                 # Sistema visual claro HMV
├── assets/
│   ├── logo.png                # Logo HMV (tinta)
│   ├── ctc-logo-ink.png        # Logo CTC Telecom (tinta)
│   ├── hmv-capacidades.png     # Mapa de capacidades HMV
│   ├── favicon.svg
│   └── preview-cover.png       # Miniatura de portada
├── vendor/reveal/              # reveal.js 4.x local (sin CDN)
│   ├── reveal.js
│   ├── reveal.css
│   ├── reset.css
│   └── notes.js
└── README.md
```

No requiere instalación ni conexión a internet, salvo Google Fonts (si no hay red, el navegador usa Georgia/Segoe UI como respaldo).

---

## Nota sobre las cifras

Los datos provienen del expediente `CTC-ERP_Modelo_Operativo_Carrier_B2B` (42 documentos, 38 procesos, 322 requerimientos) y de las notas de campo del 18-nov-2026. Los costos y plazos son **órdenes de magnitud para planeación**, no cotizaciones. La valoración de madurez e impacto es de HMV y debe validarse con los dueños de proceso antes de convertirse en compromiso.

Para exportar a PDF: abrir `index.html?print-pdf` en Chrome y usar “Imprimir → Guardar como PDF” (tamaño horizontal, márgenes ninguno, fondo gráfico activado).







