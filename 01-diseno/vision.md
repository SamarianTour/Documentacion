# Documento de Visión del Proyecto

> **Proyecto:** Plataforma Digital para la Gestión Integrada y Sostenible del Turismo en Santa Marta
> **Curso:** Arquitectura de Software — Ingeniería de Sistemas — UniMagdalena
> **Fase OpenUP:** Inicio · Iteración 1
> **Semestre:** 2026-02

---

## 1. Propósito del documento

Este documento define la visión del producto: qué problema resuelve, para quién, qué capacidades debe ofrecer y bajo qué restricciones se desarrollará. Sirve como referencia común para el equipo durante todo el ciclo del proyecto y como base para el refinamiento del backlog y las decisiones arquitectónicas posteriores.

---

## 2. Posicionamiento

### 2.1 Problema

Actualmente la información turística de Santa Marta está dispersa entre hoteles, restaurantes, operadores, redes sociales, portales web y sistemas de reserva independientes, cada uno con su propia estructura de datos y niveles de actualización. Esto genera un ecosistema fragmentado que dificulta que los turistas planifiquen su experiencia, que los pequeños prestadores compitan en igualdad de condiciones, y que las entidades responsables del destino puedan tomar decisiones basadas en información oportuna.

A esto se suman fenómenos como la concentración excesiva de visitantes en atractivos puntuales (Tayrona, Playa Blanca, Centro Histórico) durante temporadas altas, y la ausencia de mecanismos que permitan al turista descubrir alternativas acordes a sus preferencias y a la capacidad de carga real del destino.

### 2.2 Declaración de posicionamiento del producto

> **Para** turistas, prestadores de servicios turísticos y entidades responsables de la gestión del destino,
>
> **que necesitan** un punto único, actualizado e integrado para consultar, ofertar, reservar y analizar la actividad turística de Santa Marta,
>
> **la Plataforma Digital para la Gestión Integrada y Sostenible del Turismo en Santa Marta**
>
> **es** una solución web y móvil
>
> **que** integra múltiples fuentes de información, gestiona disponibilidad y reservas, recomienda experiencias mediante inteligencia artificial y genera indicadores para la planificación del destino,
>
> **a diferencia de** las plataformas turísticas actuales, que operan de forma aislada y favorecen mayoritariamente a grandes operadores,
>
> **nuestra solución** promueve la visibilidad de pequeños y medianos prestadores, apoya la sostenibilidad del destino y responde a escenarios de alta concurrencia sin degradar la experiencia.

---

## 3. Stakeholders y usuarios (resumen)

**Usuarios directos del sistema:**

- Turistas (nacionales e internacionales)
- Prestadores de servicios (grandes y pequeños/medianos)
- Administrador de plataforma
- Gestores del destino
- Sistemas externos (RNT, pasarela de pagos, servicio de IA)

**Stakeholders no-usuarios:**

- Alcaldía de Santa Marta
- MinCIT
- Registro Nacional De Turismo (RNT)
- Parques Nacionales Naturales
- Superintendencia de Industria y Comercio (SIC)
- Comunidades indígenas de la Sierra Nevada
- Comunidad local samaria
- Cuerpo docente evaluador

*(La tabla detallada de stakeholders forma parte del entregable [`stakeholders.md`](stakeholders.md).)*

---

## 4. Vista general del producto

### 4.1 Perspectiva

La plataforma se concibe como un **ecosistema digital integrador**, no como una app aislada. Su núcleo es una arquitectura de software capaz de comunicarse con múltiples fuentes de información turística heterogéneas, exponer servicios estandarizados a clientes web y móviles, e integrar de forma desacoplada un componente de inteligencia artificial como servicio complementario.

### 4.2 Capacidades clave

- Integrar información proveniente de diferentes prestadores y fuentes turísticas.
- Gestionar el catálogo de atractivos, actividades, eventos y servicios.
- Consultar disponibilidad en tiempo cercano al real.
- Gestionar reservas de actividades turísticas.
- Incorporar y visibilizar pequeños y medianos prestadores.
- Generar recomendaciones personalizadas basadas en IA.
- Producir indicadores y reportes para la planificación del destino.
- Soportar escenarios de alta demanda (temporadas y eventos).
- Aplicar controles de seguridad, autenticación, trazabilidad y cumplimiento normativo.
- Evolucionar mediante la incorporación futura de nuevos servicios sin afectar el núcleo.

---

## 5. Restricciones

Se adoptan íntegramente las restricciones definidas en el enunciado del proyecto:

- **Técnicas:** acceso web/móvil, disponibilidad ≥ 99%, integración multi-fuente, alta concurrencia.
- **Económicas:** presupuesto máximo USD 20.000 para infraestructura, software libre y cloud de bajo costo.
- **Temporales:** 6 meses, equipo de 5 personas.
- **Sociales:** accesibilidad, bilingüe español/inglés, inclusión de pequeños operadores.
- **Ambientales:** turismo sostenible, capacidad de carga.
- **Normativas:** Ley 1581 de 2012 (protección de datos personales).
- **Éticas:** explicabilidad de recomendaciones IA, no favoritismo, privacidad.

---

## 6. Atributos de calidad prioritarios

De la lista de atributos exigidos por la arquitectura, el equipo prioriza los siguientes por su criticidad frente al contexto del problema:

| Atributo | Justificación |
|---|---|
| **Escalabilidad** | Soportar picos de temporada alta sin degradación. |
| **Disponibilidad** | Objetivo mínimo del 99%. |
| **Interoperabilidad** | Integración con múltiples fuentes heterogéneas. |
| **Seguridad** | Cumplimiento de Ley 1581 y protección de datos comerciales. |
| **Mantenibilidad y evolutibilidad** | Incorporación de nuevos servicios sin tocar el núcleo. |
| **Rendimiento** | Tiempos de respuesta aceptables en consulta y reserva. |

Cada uno será formulado como escenario medible (QAS) durante la fase de Elaboración.

---

## 7. Supuestos y dependencias

- Se asume disponibilidad de al menos una fuente de datos abierta o convenio con prestadores locales para el piloto.
- Se asume acceso a una pasarela de pagos con modalidad de prueba (sandbox).
- La funcionalidad de IA se limitará a **una sola opción** de las cuatro planteadas por el docente (recomendación, clasificación de opiniones, predicción de ocupación o chatbot); la selección se justificará en Elaboración.
- El alcance del prototipo cubrirá **mínimo el 60% de los casos de uso priorizados**, con al menos un flujo crítico funcional de extremo a extremo.
