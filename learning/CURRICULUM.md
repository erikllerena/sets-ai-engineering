# Mapa de competencias — AI Engineering

**Programa v1.0.0 · SETS Framework v1.4.1 · Namespace `AIE00–AIE14`**

Desarrollar criterio para diseñar, integrar, evaluar, desplegar, observar y mantener sistemas basados en IA durante su ciclo de vida, considerando calidad, seguridad, rendimiento, costes y cambios en datos o modelos.

Este mapa define competencias prioritarias, no agota todos los temas que pueden estudiarse. Enseña preguntas relevantes fuera del índice y relaciónalas con competencias existentes cuando ayude; solo propón un módulo nuevo si el tema es recurrente o estratégicamente central. Fundamento, profundización y especialización son alcances adaptativos, no fases obligatorias.

## Competencias observables

| ID | Competencia | Capacidad observable | Pregunta conceptual central | Evidencia posible |
| --- | --- | --- | --- | --- |
| AIE00 | Diagnóstico y encuadre del caso de uso | Identificar usuario, decisión, baseline, coste de error, datos y restricciones antes de elegir IA. | ¿La IA es necesaria y cómo mediríamos el valor real? | Ficha de caso de uso con baseline y criterios de salida. |
| AIE01 | Ciclo de vida de sistemas de IA | Relacionar datos, experimentos, modelo, producto, evaluación, operación y retirada. | ¿Qué artefactos y responsabilidades cambian a lo largo del ciclo de vida? | Mapa del ciclo de vida con ownership y riesgos. |
| AIE02 | Patrones de integración de modelos | Comparar inferencia síncrona, batch, streaming, sidecar, servicio dedicado y sistemas híbridos. | ¿Dónde debe ejecutarse la inferencia y qué compromisos introduce? | Diseño de integración con latencia, fallos y contratos. |
| AIE03 | Pipelines y versionado de datos/modelos | Gestionar linaje, reproducibilidad, datasets, artefactos, prompts y dependencias. | ¿Cómo reconstruimos qué datos y versiones produjeron un resultado? | Esquema de linaje y plan de reproducción. |
| AIE04 | Evaluación continua y gates de calidad | Diseñar datasets de evaluación, pruebas de regresión, pruebas online y criterios de lanzamiento. | ¿Qué evidencia necesitamos antes y después de publicar un cambio? | Pipeline de evaluación con umbrales y política de bloqueo. |
| AIE05 | Serving e inferencia | Analizar carga, colas, batching, concurrencia, recursos, timeout y contratos de respuesta. | ¿Cómo entregamos predicciones bajo las restricciones del producto? | Diseño de serving y presupuesto de latencia. |
| AIE06 | MLOps, LLMOps y automatización | Comprender pipelines, registro de modelos, promoción, rollback y automatización apropiada. | ¿Cómo reducimos errores humanos sin ocultar decisiones críticas? | Flujo de promoción y reversión con controles. |
| AIE07 | Monitorización, drift y degradación | Distinguir métricas técnicas, calidad de predicción, cambios de datos y cambios de comportamiento. | ¿Cómo detectamos que el sistema dejó de ser válido? | Plan de señales, alertas y respuesta ante degradación. |
| AIE08 | Rendimiento, escalabilidad y costes | Medir latencia, throughput, utilización, coste por tarea y calidad por unidad de coste. | ¿Qué optimización mejora el sistema sin romper sus objetivos? | Experimento de rendimiento y análisis coste-calidad. |
| AIE09 | Confiabilidad y degradación controlada | Diseñar timeouts, retries, circuit breakers, caché, fallback, abstención y revisión humana. | ¿Qué ocurre cuando el modelo o el proveedor no responde o responde mal? | Matriz de fallos y comportamiento degradado. |
| AIE10 | Seguridad, privacidad y gobernanza operativa | Analizar datos sensibles, permisos, supply chain, trazabilidad, retención y responsabilidades. | ¿Qué riesgos se introducen al operar modelos y cómo se controlan? | Threat model y controles verificables. |
| AIE11 | Observabilidad y trazabilidad de IA | Relacionar trazas, versiones, inputs seguros, outputs, herramientas, evaluaciones y auditoría. | ¿Cómo investigamos una respuesta incorrecta sin exponer datos innecesarios? | Diseño de trazas con límites de privacidad. |
| AIE12 | Human-in-the-loop y supervisión | Definir cuándo solicitar revisión, cómo presentar incertidumbre y cómo evitar automatización ciega. | ¿Qué decisiones necesitan intervención humana y con qué señal? | Política de escalamiento y criterios de abstención. |
| AIE13 | Selección, compra y evolución de soluciones | Comparar modelo propio, API, modelo abierto, reglas y sistema híbrido según riesgos y coste total. | ¿Qué opción es sostenible y qué evidencia justificaría cambiarla? | ADR con coste total, lock-in, privacidad y reversibilidad. |
| AIE14 | Capstone de AI Engineering | Integrar evaluación, despliegue, observabilidad, confiabilidad, seguridad y evolución. | ¿Cómo sabemos que el sistema aporta valor y sigue siendo operable? | Dossier de producción con gates, señales, fallos y rollback. |

## Cómo se aprende

Selecciona las lentes conceptuales según la pregunta y las brechas observadas: origen/problema, mecanismo causal, supuestos y límites, alternativas/trade-offs y transferencia. No conviertas las lentes en cinco pasos obligatorios ni en una escala de dominio.

## Formas de evidencia

La evidencia puede ser una explicación propia, una predicción, un cálculo, un diagrama, una traza, una comparación, un experimento, un análisis de error o una implementación. Una respuesta del tutor, una lectura o una salida copiada no demuestra por sí sola el desempeño del estudiante.

## Criterio de comprensión profunda

Se busca que el estudiante pueda explicar el problema y el mecanismo, declarar supuestos, anticipar consecuencias o fallos, reconocer límites y razonar sobre alternativas. El dominio se decide con las reglas de `sets-framework/core/ASSESSMENT_ENGINE.md`, no por contar módulos completados.
