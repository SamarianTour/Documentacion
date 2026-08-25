# Estructura del repositorio: plataforma-turismo-santamarta

```
plataforma-turismo-santamarta/
│
├── README.md                          ← Portada del repo (qué es, equipo, cómo navegar)
├── LICENSE
├── .gitignore
│
├── docs/                              ← Toda la documentación del proyecto
│   │
│   ├── 00-gestion-proyecto/           ← Fase INICIO: gestión y planificación
│   │   ├── vision.md
│   │   ├── justificacion-metodologia.md
│   │   ├── plan-proyecto.md           (referencia al Excel)
│   │   ├── stakeholders.md
│   │   ├── contexto-problema.md
│   │   ├── glosario.md
│   │   ├── riesgos-iniciales.md
│   │   └── plan-openup.xlsx           ← El Excel del plan
│   │
│   ├── 01-requerimientos/             ← Fase ELABORACIÓN: requisitos
│   │   ├── backlog-inicial.md
│   │   ├── historias-usuario/         ← Una por HU cuando se detallen
│   │   │   ├── HU01-explorar-atractivos.md
│   │   │   └── ...
│   │   ├── casos-uso/
│   │   │   ├── nivel-0-diagrama.md    (PlantUML embebido)
│   │   │   ├── nivel-1-diagramas.md
│   │   │   └── especificaciones/      ← CU detallados
│   │   ├── ers-ieee-29148.md          ← Especificación formal
│   │   ├── atributos-calidad.md       ← Escenarios QAS medibles
│   │   └── analisis-restricciones.md
│   │
│   ├── 02-arquitectura/               ← Fase ELABORACIÓN: diseño
│   │   ├── comparacion-alternativas.md
│   │   ├── diseno-final.md
│   │   ├── modelo-datos/
│   │   │   ├── conceptual.md
│   │   │   ├── logico.md
│   │   │   └── justificacion-persistencia.md
│   │   ├── diagramas/
│   │   │   ├── paquetes.puml
│   │   │   ├── despliegue.puml
│   │   │   ├── componentes.puml
│   │   │   └── secuencia/
│   │   ├── wireframes/                ← Mockups (imágenes o Figma links)
│   │   └── adrs/                      ← Architecture Decision Records
│   │       ├── ADR-001-metodologia-openup.md
│   │       ├── ADR-002-estilo-arquitectonico.md
│   │       ├── ADR-003-base-datos.md
│   │       └── ADR-004-conectividad.md
│   │
│   ├── 03-construccion/               ← Fase CONSTRUCCIÓN: reportes iterativos
│   │   ├── iteracion-01/
│   │   │   ├── planificacion.md
│   │   │   ├── retrospectiva.md
│   │   │   └── evidencias/
│   │   ├── iteracion-02/
│   │   ├── iteracion-03/
│   │   ├── iteracion-04/
│   │   └── evaluacion-arquitectonica.md
│   │
│   ├── 04-transicion/                 ← Fase TRANSICIÓN: cierre
│   │   ├── documento-final.md
│   │   ├── validacion-restricciones.md
│   │   ├── impacto-comparativo.md
│   │   ├── manual-usuario.md
│   │   ├── manual-operacion.md
│   │   └── sustentacion.md
│   │
│   └── assets/                        ← Recursos compartidos
│       ├── images/
│       ├── diagrams/
│       └── templates/
│
├── src/                               ← Código fuente del prototipo
│   ├── frontend/
│   ├── backend/
│   ├── ia-service/                    ← Módulo de IA desacoplado
│   └── shared/
│
├── infrastructure/                    ← Infra as code, despliegue
│   ├── docker/
│   ├── ci-cd/
│   └── deployment/
│
├── tests/                             ← Pruebas
│   ├── unit/
│   ├── integration/
│   └── quality-scenarios/             ← Pruebas de escenarios de calidad
│
└── scripts/                           ← Utilitarios
```
