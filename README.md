# TourMZA: Asistente Inteligente para Planificar Visitas a Bodegas en Mendoza

## Resumen
Este proyecto propone el desarrollo de una Proof of Concept (POC) de un asistente inteligente para la planificación de visitas a bodegas en Mendoza, utilizando modelos de inteligencia artificial basados en texto-texto y texto-imagen. La solución busca resolver la dificultad que enfrentan turistas y visitantes al organizar recorridos personalizados debido a la dispersión de información, horarios poco claros y la saturación de opciones disponibles.

A través del uso de ingeniería de prompts, se generan itinerarios optimizados según preferencias del usuario y visualizaciones ilustrativas del recorrido, demostrando cómo la IA puede mejorar la experiencia turística sin necesidad de programación avanzada ni infraestructura compleja.

---

## Introducción

### Nombre del proyecto
TourMZA: Asistente Inteligente para Planificar Visitas a Bodegas en Mendoza.

### Presentación del problema a abordar
Mendoza es una de las capitales mundiales del vino y recibe miles de turistas cada año interesados en recorrer sus bodegas. Sin embargo, la planificación de estos recorridos presenta una problemática recurrente: la información se encuentra dispersa en múltiples plataformas, los horarios no siempre son claros, muchas bodegas requieren reserva previa y existen diferencias importantes entre tipos de experiencias, precios y ubicaciones.

Como consecuencia, los visitantes deben invertir mucho tiempo comparando opciones, contactando bodegas individualmente y organizando traslados, lo que genera frustración y decisiones improvisadas. Esta situación afecta especialmente a quienes no conocen la región o disponen de poco tiempo para planificar.

El problema principal es que turistas y visitantes locales tienen dificultades para planificar recorridos eficientes y personalizados por bodegas de Mendoza debido a la dispersión de información, la falta de guías claras y la saturación de opciones.

### Relevancia del problema
- Impacta directamente en la experiencia turística.
- Afecta el flujo de visitantes hacia bodegas menos conocidas.
- Genera pérdida de tiempo y frustración.
- Es una problemática real y frecuente en foros, redes sociales y blogs de viajes.

---

## Desarrollo de la propuesta de solución

La propuesta consiste en desarrollar un asistente inteligente basado en ingeniería de prompts que ayude al usuario a generar un itinerario personalizado de visitas a bodegas en Mendoza. El proyecto se presenta como una Proof of Concept (POC), cuyo objetivo es demostrar la viabilidad del uso de inteligencia artificial para resolver esta problemática sin requerir programación avanzada.

La solución combina dos tipos de modelos de IA:
- Modelo texto-texto, para clasificar bodegas, generar itinerarios y optimizar recorridos según preferencias.
- Modelo texto-imagen, para generar visualizaciones ilustrativas del recorrido y de las bodegas.

---

## Prompts Texto–Texto

### Prompt 1 – Clasificación de bodegas
Actúa como guía turístico de Mendoza. Clasifica una lista de bodegas en Luján de Cuyo según tipo de experiencia, rango de precios y horarios disponibles. Devuelve la información en una tabla clara.

### Prompt 2 – Generación de itinerario
Crea un itinerario de bodegas en Luján de Cuyo para un turista con 6 horas disponibles. Incluye horarios estimados, recomendaciones de transporte, experiencia sugerida y nivel de dificultad.

### Prompt 3 – Optimización por preferencias
Propón tres itinerarios alternativos para un viajero que prioriza experiencias gourmet y vistas panorámicas, justificando cada opción.

---

## Prompts Texto–Imagen

### Prompt – Imagen del recorrido
Mapa ilustrado en estilo flat de un recorrido enoturístico por Luján de Cuyo, Mendoza. Viñedos extensos, caminos señalizados entre bodegas, pequeños íconos de copas de vino, montañas de la Cordillera de los Andes al fondo. Estilo minimalista, colores suaves y naturales, iluminación equilibrada, diseño limpio y amigable para interfaz de usuario, vista aérea ligeramente inclinada, alta calidad.

---

## Objetivos

### Objetivo general
Desarrollar una prueba de concepto de un asistente inteligente que facilite la planificación de recorridos por bodegas en Mendoza mediante el uso de inteligencia artificial.

### Objetivos específicos
- Generar itinerarios personalizados según tiempo, presupuesto y preferencias.
- Centralizar información dispersa sobre bodegas.
- Optimizar el uso de prompts (fast prompting).
- Crear visualizaciones ilustrativas del recorrido y las bodegas.
- Reducir la frustración del usuario durante la planificación.

---

## Metodología
El proyecto se desarrolla mediante una metodología exploratoria y práctica:
1. Identificación de la problemática.
2. Investigación y selección de bodegas de Luján de Cuyo.
3. Diseño de prompts texto-texto para clasificación y generación de itinerarios.
4. Diseño de prompts texto-imagen para visualización del recorrido.
5. Pruebas de resultados generados por IA.
6. Evaluación de la efectividad de la solución propuesta.

---

## Herramientas y tecnologías
- ChatGPT: generación de texto e itinerarios.
- NightCafe: generación de imágenes a partir de prompts visuales.
- Jupyter Notebook: documentación del proceso y presentación de la POC.
- GitHub: repositorio del proyecto y entrega final.

---

## Implementación
La implementación se realiza a través de una Jupyter Notebook que combina texto explicativo, prompts utilizados, resultados obtenidos y visualizaciones generadas. En el caso de la generación de imágenes, al utilizar una herramienta gratuita externa (NightCafe), los prompts y las imágenes finales se documentan directamente sin uso de API.

---

## Resultados
La implementación permitió generar itinerarios claros y personalizados en función de las preferencias del usuario, reduciendo significativamente la complejidad de la planificación manual. Las imágenes generadas complementan la experiencia, facilitando la comprensión visual del recorrido propuesto.

---

## Conclusiones
El proyecto TourMZA demuestra que, mediante el uso de ingeniería de prompts y modelos de inteligencia artificial accesibles, es posible resolver una problemática real vinculada al turismo en Mendoza. La prueba de concepto valida la viabilidad técnica y temporal del proyecto, logrando cumplir los objetivos planteados.

---

## Referencias
- https://solsalute.com/blog/mendoza-argentina-wine-capital/
- https://www.setours.com/7-insider-tips-to-explore-mendoza-wine-region/
