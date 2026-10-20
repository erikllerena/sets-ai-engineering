# SETS — AI Engineering

**Programa:** v1.0.2 · **Framework:** SETS v1.4.1 · **Namespace:** `AIE00–AIE14`

Desarrollar criterio para diseñar, integrar, evaluar, desplegar, observar y mantener sistemas basados en IA durante su ciclo de vida, considerando calidad, seguridad, rendimiento, costes y cambios en datos o modelos.

## Pregunta central

> ¿Cómo convertimos una capacidad de IA en un sistema confiable, evaluable, operable y mantenible?

## Qué cubre

Selección de casos de uso; sistemas híbridos y patrones de integración; pipelines de datos/modelos; experimentación reproducible; evaluación offline/online; serving de inferencia; MLOps y LLMOps; versionado; monitorización y drift; latencia, throughput y costes; confiabilidad, fallback y revisión humana; seguridad, privacidad, gobernanza y operación.

## Qué no intenta cubrir

Se centra en el ciclo de vida y los problemas de ingeniería específicos de modelos y sistemas de IA. No reemplaza Software Architecture, Backend Architecture ni Frontend Architecture: estos conservan el diseño general de la aplicación, APIs, persistencia y experiencia de usuario. Los fundamentos de algoritmos y modelos pertenecen a AI Foundations, Machine Learning, Deep Learning y Generative AI.

## Principios de aprendizaje

- Conceptos y mecanismos antes que recetas o herramientas.
- Currículo abierto: los módulos priorizan competencias; no limitan los temas que pueden estudiarse.
- Casos ilustrativos, no exclusivos. El caso conductor es opcional.
- Profundidad adaptable: fundamento, profundización y especialización son alcances, no etapas obligatorias.
- Neutralidad tecnológica: ningún lenguaje, biblioteca, proveedor o stack es requisito universal.
- Práctica opcional por defecto; explicar y razonar también producen evidencia.
- Evidencia honesta: no se infiere dominio por lectura pasiva, familiaridad o una sola respuesta.
- Autonomía: este programa conserva su propio currículo y estado; no importa progreso de otros SETS.

## Estructura

- `PROJECT_CONFIG.yaml`: configuración del programa.
- `PROJECT_RULES.md`: reglas específicas y límites disciplinares.
- `CHATGPT_PROJECT_INSTRUCTIONS.md`: instrucciones para el Proyecto de ChatGPT.
- `learning/CURRICULUM.md`: mapa de competencias abierto.
- `learning/CASEBOOK.md`: casos ilustrativos.
- `learning/LEARNING_PATHS.md`: rutas no obligatorias.
- `practice/EXPERIMENTS.md`: ideas de experimentación optativas.
- `practice/TRANSFER_CHALLENGES.md`: ejercicios para transferir principios.
- `state/`: estado y evidencias del aprendizaje; incluye `state/CONCEPT_MAP.md`, recomendado como fuente de relaciones conceptuales desde el inicio (opcional y sin progreso acreditado).
- `docs/ACCEPTANCE_CHECKS.md`: pruebas manuales de comportamiento esperado.

## Cómo empezar

1. Lee `SETUP_CHATGPT.md`.
2. Crea un Proyecto independiente en ChatGPT para esta especialidad.
3. Copia el contenido de `CHATGPT_PROJECT_INSTRUCTIONS.md` en sus instrucciones y carga los archivos pertinentes.
4. Inicia con `/start` o comienza directamente con `/learn <tema>`.
5. Al cerrar una sesión, utiliza `/close` y revisa los artefactos de continuidad antes de actualizar tu copia local o GitHub.

> GitHub y los archivos de un Proyecto de ChatGPT no se sincronizan automáticamente por defecto. Mantén cualquier actualización manual y verifica el contenido antes de reemplazar archivos.

## Versionado

Versión actual del programa: `v1.0.2` (base inicial `v1.0.0`). Se alinea con SETS Framework `v1.4.1`, sin modificarlo.
