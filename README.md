# Prompt Engineering para Superar la Saturación Creativa en UX/UI

## Introducción
Este proyecto explora cómo el Prompt Engineering y las técnicas de Fast Prompting pueden funcionar como herramientas de apoyo creativo para diseñadores UX/UI que enfrentan saturación estética, repetición de patrones y bloqueo conceptual durante las primeras etapas del diseño.

## Problema
En el contexto actual del diseño UX/UI, los profesionales se enfrentan a una paradoja creativa: la abundancia de referencias, tendencias y soluciones estandarizadas, lejos de facilitar el proceso creativo, suele generar saturación, repetición y bloqueo.
Muchas interfaces comienzan a parecerse entre sí, lo que provoca frustración, pérdida de motivación y dificultad para definir una dirección visual original.

Este bloqueo no es técnico, sino conceptual, estético y emocional, y se manifiesta en dudas recurrentes sobre estilos, niveles de carga visual, coherencia y originalidad sin comprometer la usabilidad. Esto evidencia la necesidad de herramientas que estimulen el pensamiento divergente y amplíen el campo de exploración creativa.

## Propuesta de solución
Se propone una POC (Proof of Concept) basada en técnicas de Fast Prompting que combina:
* prompts texto → texto para expansión conceptual
* prompts texto → imagen para exploración visual abstracta

Este sistema no reemplaza al diseñador, sino que actúa como un catalizador creativo, ayudando a desbloquear ideas y explorar nuevas direcciones estéticas antes de tomar decisiones formales de diseño.

Ambos tipos de prompts funcionan de manera complementaria: el primero amplía la visión conceptual mediante lenguaje estructurado, mientras que el segundo traduce esas ideas en abstracciones visuales que estimulan la inspiración.

## Objetivos
1. Aplicar técnicas de Zero-shot, One-shot y Few-shot Prompting
2. Evaluar cómo estas técnicas mejoran la calidad de las respuestas
3. Analizar si la optimización de prompts mejora la propuesta planteada en la Preentrega 1
4. Demostrar una implementación clara mediante una Jupyter Notebook

## Metodología
El proyecto se desarrolla mediante experimentación progresiva de prompts:

1. Zero-shot (sin ejemplos)
2. One-shot (con un ejemplo)
3. Few-shot (con múltiples ejemplos)

Cada técnica se prueba en:
* generación conceptual (texto → texto)
* exploración visual (texto → imagen)

## Herramientas y tecnologías
Se emplearán herramientas accesibles, gratuitas o de bajo costo para la implementación de la prueba de concepto:

**Técnicas y enfoques**
* Prompt Engineering
* Fast Prompting (Zero-shot, One-shot y Few-shot)

**Entorno de implementación**
* Jupyter Notebook
* Python (nivel básico, sin uso obligatorio de API paga)

**Herramientas de IA**
* ChatGPT (modelo texto → texto)
* Gemini / Claude / Grok como alternativas para pruebas
* NanoBanana, Leonardo AI y DALL·E (modelo texto → imagen)
* Midjourney como opción adicional, no obligatoria

Estas plataformas permiten crear, testear y ajustar los prompts sin costos elevados. Además, todas las herramientas seleccionadas cuentan con planes gratuitos o de muy bajo costo (por debajo de los USD $10), lo que garantiza la viabilidad económica del proyecto dentro del marco de la cursada.

## Viabilidad
El proyecto es técnicamente viable, de bajo costo y realizable dentro del tiempo del curso.
Se prioriza la optimización del prompt por sobre la cantidad de consultas, evitando llamadas innecesarias a APIs y manteniendo un alcance controlado.

## Limitaciones
Si bien la IA es una herramienta eficaz para estimular la exploración creativa, puede reproducir patrones dominantes o generar resultados no directamente aplicables a una interfaz real. Por ello, se plantea como un apoyo estratégico y no como un sustituto del criterio profesional del diseñador.

## Cierre
Este proyecto demuestra cómo la inteligencia artificial, aplicada desde el Prompt Engineering, puede convertirse en un socio creativo para superar la saturación estética en UX/UI. Al potenciar la exploración conceptual y visual, la IA contribuye a recuperar claridad creativa y a abrir nuevas posibilidades de diseño con intención y coherencia.

_La implementación y la prueba de concepto se pueden encontrar en el Jupyter Notebook incluido en este repositorio._
