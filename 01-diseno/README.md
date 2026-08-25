# Plataforma Digital para la Gestión Integrada y Sostenible del Turismo en Santa Marta

> Proyecto **Capstone Design** — Curso de Arquitectura de Software
> Programa de Ingeniería de Sistemas — Universidad del Magdalena
> Semestre **2026-02**

---

## 📌 Descripción

Diseño e implementación de una plataforma digital que integra información turística de Santa Marta (atractivos, hoteles, restaurantes, operadores, actividades) en un único ecosistema web y móvil. La plataforma permite consultar disponibilidad, gestionar reservas, generar recomendaciones personalizadas mediante IA y producir indicadores para la planificación del destino, promoviendo la visibilidad de pequeños y medianos prestadores y un turismo sostenible.

El proyecto se enfoca en el **diseño arquitectónico**: definición de atributos de calidad, análisis de restricciones, comparación de alternativas, decisiones arquitectónicas justificadas (ADRs) y validación mediante un prototipo funcional.

---

## 🧭 Metodología

Se adopta **OpenUP** (subconjunto ágil de RUP) con 4 fases y 8 iteraciones de 12 días, distribuidas en los 97 días del semestre (24 de agosto al 28 de noviembre de 2026).

| Fase | Iteraciones | Foco |
|---|---|---|
| Inicio | 1 | Visión, alcance, stakeholders, plan |
| Elaboración | 2 | Requisitos, arquitectura baseline, prototipo arquitectónico |
| Construcción | 4 | Implementación incremental |
| Transición | 1 | Despliegue, validación, cierre |

Ver justificación completa en [`docs/00-gestion-proyecto/justificacion-metodologia.md`](docs/00-gestion-proyecto/justificacion-metodologia.md).

---

## 👥 Equipo

| Rol | Responsable |
|---|---|
| Líder Técnico / Arquitecto | *[por asignar]* |
| Desarrollador Full-stack | *[por asignar]* |
| Desarrollador Backend | *[por asignar]* |
| Analista de Requisitos | *[por asignar]* |
| Ingeniero QA | *[por asignar]* |

---

## 📂 Estructura del repositorio

```
├── docs/                    Documentación del proyecto (organizada por fase OpenUP)
│   ├── 00-gestion-proyecto/ Fase Inicio: visión, plan, stakeholders
│   ├── 01-requerimientos/   Fase Elaboración: ERS, HU, casos de uso, QAS
│   ├── 02-arquitectura/     Fase Elaboración: diseño, ADRs, diagramas
│   ├── 03-construccion/     Fase Construcción: iteraciones y evaluaciones
│   ├── 04-transicion/       Fase Transición: cierre y validación final
│   └── assets/              Imágenes, diagramas, plantillas
├── src/                     Código fuente del prototipo
├── infrastructure/          Docker, CI/CD, despliegue
├── tests/                   Pruebas unitarias, integración y de escenarios de calidad
└── scripts/                 Utilitarios
```

---

## 🚀 Cómo navegar la documentación

1. **Para entender el proyecto:** empezar por [`docs/00-gestion-proyecto/vision.md`](docs/00-gestion-proyecto/vision.md)
2. **Para entender el problema y contexto:** [`docs/00-gestion-proyecto/contexto-problema.md`](docs/00-gestion-proyecto/contexto-problema.md)
3. **Para ver qué se construirá:** [`docs/01-requerimientos/backlog-inicial.md`](docs/01-requerimientos/backlog-inicial.md)
4. **Para entender las decisiones de diseño:** [`docs/02-arquitectura/adrs/`](docs/02-arquitectura/adrs/)

---

## 📅 Cronograma

Ver el plan detallado en [`docs/00-gestion-proyecto/plan-openup.xlsx`](docs/00-gestion-proyecto/plan-openup.xlsx).

**Ventana de ejecución:** 24 de agosto — 28 de noviembre de 2026 (97 días · 8 iteraciones)
