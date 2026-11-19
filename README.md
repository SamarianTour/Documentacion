<div align="center">

# 📐 Documentación de Arquitectura — SamarianTour

**Repositorio central de documentos, diagramas y entregables del proyecto SamarianTour**
_Arquitectura de Software · Ingeniería de Sistemas · Universidad del Magdalena_

![Estado](https://img.shields.io/badge/estado-en%20curso-2ea44f?style=for-the-badge)
![Semestre](https://img.shields.io/badge/semestre-VIII-blue?style=for-the-badge)
![Proyecto](https://img.shields.io/badge/proyecto-SamarianTour-orange?style=for-the-badge)

</div>

---

## 📌 Propósito

Este repositorio concentra **toda la documentación técnica y académica** del proyecto
**SamarianTour**: diseño, diagramas, presentaciones y los entregables de cada corte.

La regla es simple: **si es un documento del proyecto, va aquí**. Las fotos de reuniones,
chats y apuntes van en el repositorio de [Evidencias](../EVIDENCIAS).

> 🌱 La estructura arranca sencilla a propósito. Se irán agregando carpetas
> (requisitos, arquitectura, diagramas, referencias…) a medida que el proyecto lo pida.

---

## 🗂️ Organización de carpetas

| Carpeta | Qué se guarda aquí |
| :--- | :--- |
| 🎨 `01-diseno/` | Mockups, prototipos navegables y guía de estilo de la interfaz. |
| 📦 `02-entregables/` | Los paquetes finales que se suben a la plataforma, organizados por corte. |
| 🖥️ `03-presentaciones/` | Diapositivas de sustentaciones y exposiciones. |

### Estructura completa

```
DOCUMENTACION/
├── 01-diseno/
│   ├── mockups/            # Bocetos y pantallas propuestas
│   ├── prototipos/         # Prototipos navegables (Figma, enlaces, exportados)
│   └── guia-de-estilo/     # Colores, tipografías, componentes de UI
├── 02-entregables/
│   ├── corte-1/
│   ├── corte-2/
│   └── corte-3/
└── 03-presentaciones/
```

---

## 🧭 Cómo aportar documentos

1. **Ubica la carpeta correcta** según la tabla de arriba.
2. **Nombra el archivo** siguiendo la convención de la sección siguiente.
3. **Exporta a PDF** todo documento que se vaya a entregar; deja también el archivo editable.
4. **Registra el documento** en la tabla de la sección _Índice de documentos_ de este README.
5. Nunca sobreescribas un entregable ya enviado: si cambia, crea una versión nueva (`-v2`).
6. Si algo no encaja en ninguna carpeta, **avísale al equipo antes de crear una nueva**, para
   que la estructura no se desordene.

---

## 🏷️ Convención de nombres

| Tipo | Formato | Ejemplo |
| :--- | :--- | :--- |
| Documento general | `tema-descripcion.pdf` | `guia-de-estilo.pdf` |
| Documento versionado | `tema-descripcion-vN.pdf` | `mockups-inicio-v2.pdf` |
| Entregable de corte | `corteN-nombre-entregable.pdf` | `corte1-documento-vision.pdf` |
| Presentación | `corteN-presentacion-tema.pdf` | `corte1-presentacion-vision.pdf` |

> Todo en **minúsculas**, **sin tildes** y con **guiones** en lugar de espacios.

---

## 📚 Índice de documentos

| Corte | Documento | PDF | Editable |
| :---: | :--- | :---: | :---: |
| 1 | Entregable 1 · Documento de requerimientos (v3) | [PDF](02-entregables/corte-1/corte1-entregable-1-requerimientos-v3.pdf) | [DOCX](02-entregables/corte-1/corte1-entregable-1-requerimientos-v3.docx) |
| 1 | Especificación de requisitos (SRS) ISO/IEC/IEEE 29148 · v1.1 | [PDF](02-entregables/corte-1/corte1-srs-iso29148-v1-1.pdf) | [DOCX](02-entregables/corte-1/corte1-srs-iso29148-v1-1.docx) |
| 1 | Plan, cronograma y presupuesto (v2) | — | [XLSX](02-entregables/corte-1/corte1-plan-cronograma-presupuesto-v2.xlsx) |
| 2 | Entregable 2 · Documento de diseño | [PDF](02-entregables/corte-2/corte2-entregable-2-diseno.pdf) | [DOCX](02-entregables/corte-2/corte2-entregable-2-diseno.docx) |
| 3 | **Entrega final (Capstone Design) · documento único** | [PDF](02-entregables/corte-3/corte3-documento-final-capstone.pdf) | [DOCX](02-entregables/corte-3/corte3-documento-final-capstone.docx) |
| 3 | Especificación de requisitos (SRS) · v1.2, ajustada a lo construido | [PDF](02-entregables/corte-3/corte3-srs-iso29148-v1-2.pdf) | [DOCX](02-entregables/corte-3/corte3-srs-iso29148-v1-2.docx) |
| 3 | Entregable 1 · Documento de requerimientos (v4) | [PDF](02-entregables/corte-3/corte3-entregable-1-requerimientos-v4.pdf) | [DOCX](02-entregables/corte-3/corte3-entregable-1-requerimientos-v4.docx) |
| 3 | Plan, cronograma y presupuesto (v3) | — | [XLSX](02-entregables/corte-3/corte3-plan-cronograma-presupuesto-v3.xlsx) |
| 3 | Diagrama de paquetes detallado · v2, actualizado a lo construido (con el módulo bandeja) | [PDF](02-entregables/corte-3/corte3-diagrama-paquetes-detallado-v2.pdf) | [DOCX](02-entregables/corte-3/corte3-diagrama-paquetes-detallado-v2.docx) |
| 3 | Entregable 2 · Documento de diseño · v2, diagramas actualizados a lo construido | [PDF](02-entregables/corte-3/corte3-entregable-2-diseno-v2.pdf) | [DOCX](02-entregables/corte-3/corte3-entregable-2-diseno-v2.docx) |
| 3 | Evaluación de la arquitectura (ATAM y reevaluación) | [PDF](02-entregables/corte-3/corte3-evaluacion-arquitectura-atam.pdf) | [DOCX](02-entregables/corte-3/corte3-evaluacion-arquitectura-atam.docx) |

El código, los scripts de base de datos y los registros de decisiones están en el repositorio
[samarianTour-platform](https://github.com/SamarianTour/samarianTour-platform).

---

<div align="center">

_Repositorio de documentación · Proyecto **SamarianTour** · 2026_

</div>
