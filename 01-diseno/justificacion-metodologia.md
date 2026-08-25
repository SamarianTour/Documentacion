# Justificación de la Metodología: OpenUP

> **Proyecto:** Plataforma Digital para la Gestión Integrada y Sostenible del Turismo en Santa Marta
> **Fase OpenUP:** Inicio · Iteración 1
> **Semestre:** 2026-02

---

## Contexto

Para este proyecto tenemos una ventana real de **97 días** (del 24 de agosto al 28 de noviembre de 2026) y un equipo de **5 personas**, así que decidimos trabajar con **OpenUP**, que es básicamente una versión ágil y aliviana de RUP. Lo organizamos en las **4 fases clásicas del proceso unificado** (Inicio, Elaboración, Construcción y Transición), repartidas en **8 iteraciones de 12 días** que nos cubren todo el semestre sin dejar días sueltos al final.

---

## ¿Por qué NO RUP completo?

Porque trae demasiados artefactos y roles especializados que, siendo honestos, no alcanzamos a cubrir en menos de 14 semanas y con la carga de otras materias encima. El horizonte temporal es muy comprimido para el peso metodológico de RUP.

## ¿Por qué NO Scrum puro?

Porque Scrum, por diseño, **no exige la documentación formal** que el proyecto sí pide:

- Especificación bajo IEEE/IEC/IEEE 29148:2018
- Architecture Decision Records (ADRs)
- Modelos de diseño arquitectónico formales
- Trazabilidad ABET/SO2
- Decisiones arquitectónicas justificadas desde etapas tempranas

Con Scrum "de manual" nos quedaríamos cortos en el papeleo que la rúbrica sí evalúa.

---

## ¿Por qué iteraciones de 12 días y no los típicos sprints de 2 semanas?

Por dos razones:

1. **Encaja exacto en el semestre.** Con 14 días nos quedaría una iteración final incompleta justo en Transición, que es cuando se despliega y se sustenta — ahí no podemos improvisar.
2. **Dedicación parcial del equipo.** Como el equipo tiene dedicación parcial (compartida con las demás asignaturas del semestre), ciclos un poquito más cortos nos dan más puntos de control. Si una iteración sale floja, no perdemos una tajada gigante del proyecto.

**Contrapartida asumida:** exige más disciplina de cierre y más ceremonias (revisión, retro, actualización del backlog cada 12 días en vez de cada 14), pero eso lo asumimos como parte del compromiso.

---

## Qué le tomamos a cada enfoque

### De RUP/OpenUP conservamos:

- **Enfoque *architecture-centric* y *dirigido por riesgo*** — clave acá porque no tenemos tiempo para descubrir errores de diseño tarde. Por eso destinamos **4 de las 8 iteraciones a Construcción**, que es donde se concentra el mayor riesgo técnico:
  - Flujo crítico de disponibilidad/reserva
  - Adaptador de interoperabilidad con el RNT
  - Módulo de IA desacoplado

### De Scrum nos quedamos con:

- **Cadencia iterativa con entregas funcionales verificables cada 12 días**, para mitigar la compresión de tiempo mediante retroalimentación continua en lugar de jugarnos todo a una entrega final.

---

## Distribución de fases

| Fase | Iteraciones | Días | % del proyecto |
|---|:---:|:---:|:---:|
| Inicio | 1 | 12 | 12.5% |
| Elaboración | 2 | 24 | 25% |
| Construcción | 4 | 48 | 50% |
| Transición | 1 | 12 | 12.5% |
| **Total** | **8** | **96** | **100%** |

La concentración del 50% del esfuerzo en Construcción es coherente con el patrón clásico de OpenUP/RUP y responde al peso real de riesgo técnico del proyecto.
