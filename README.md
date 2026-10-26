# ClorofilIA

El laboratorio de fisiología vegetal del campo. Aplicación web de un solo fichero que acompaña la asignatura de **Fisiología Vegetal** (Carrera de Agropecuaria, Universidad Politécnica Estatal del Carchi) y sirve a cualquier estudiante de agronomía, biología o ciencias ambientales.

**Usar la app:** https://fborrasumh.github.io/clorofilia/

**Idiomas:** español (por defecto), inglés y portugués; selector en la barra superior (o `?lang=en` / `?lang=pt` en la URL).

## Qué hace

- **Problemas individualizados.** Cada estudiante escribe un código o alias y recibe sus propios problemas, siempre los mismos para ese código (el profesor puede reproducirlos). La solución la calcula el código y, si la respuesta es errónea, recalcula los errores típicos (temperatura en °C en lugar de kelvin, signo, R sin convertir, logaritmo decimal, Q₁₀ lineal, cociente invertido, fotosíntesis bruta en vez de neta…) para decir cuál se cometió.
- **Agua:** potencial osmótico (van ’t Hoff), célula en una disolución (dirección del agua, Ψp de equilibrio, plasmólisis), potencial hídrico del aire; simulador de una célula en sacarosa.
- **Estomas y transpiración:** simulador (temperatura, humedad relativa, luz, potencial del suelo) con conductancia estomática y transpiración, retos de predicción y problemas de déficit de presión de vapor.
- **Respiración y poscosecha:** curva del Q₁₀, cálculo del Q₁₀, cociente respiratorio y almacenamiento en frío.
- **Hormonas y nutrición:** 14 casos agronómicos de fitohormonas, diagnóstico de deficiencias minerales con una clave (zona de la planta y tipo de síntoma) y lectura de un análisis foliar.
- **Fotosíntesis:** curvas de respuesta a la luz C3 y C4 con temperatura y CO₂, fotorrespiración y un reto con datos (respiración en oscuridad, punto de compensación y saturación).
- **Proyecto integrador (ABP):** portafolio del trasplante y establecimiento de frutales con diseño comparativo de estimulación radicular: registro de altura, turgencia y brotes; medias y desviaciones por fecha, tasa de crecimiento relativo, t de Welch y g de Hedges; reporte en Word con declaración de uso de IA y CSV.
- **Lectura crítica de artículos:** pega o sube (PDF, Word) un artículo; la IA propone pregunta, diseño, variables, limitaciones y preguntas para el debate con una cita literal, y el código comprueba que cada cita aparece en el texto. Ficha de lectura en Word.
- **Práctica de parcial:** intentos del parcial 1 o 2 con problemas y preguntas, distintos por código e intento, corregidos por el código y con explicación de cada fallo; historial en CSV.

## Cómo se usa la IA

Todo funciona sin clave. La IA es opcional y se usa solo en la lectura de artículos y para proponer preguntas y un borrador de discusión del proyecto, con la propia clave de OpenAI, Google Gemini o Anthropic Claude (guardada solo en el navegador). La IA propone; el código comprueba citas y cifras.

## Privacidad

Respuestas, progreso y datos del proyecto se guardan solo en el navegador (IndexedDB). Hacia el proveedor de IA sale únicamente lo que la persona pide analizar: el texto del artículo o el **resumen numérico** del proyecto (nunca las filas de datos), con correos, números de identificación y teléfonos enmascarados y tras un aviso previo con muestra de lo que sale.

## Límites

- Los simuladores son modelos didácticos simplificados con parámetros ilustrativos: sirven para razonar tendencias, no para predecir un cultivo concreto.
- Los rangos de análisis foliar son generales y orientativos; en un informe real se usan los del cultivo, la variedad y el órgano.
- La comparación del proyecto usa la t de Welch entre plantas; si el diseño tiene bloques o parcelas, la unidad experimental es la parcela y hace falta otro análisis (por ejemplo, ANOVA de bloques).
- La práctica de parcial es orientativa: no sustituye al examen ni a las prácticas de campo.
- Los datos del ejemplo del proyecto y el resumen de artículo de ejemplo son ficticios.
- Probado con IA simulada; las respuestas reales de la IA pueden equivocarse: por eso se verifican las citas y las cifras.

## Autoría

Fernando Borrás Rocher (Universidad Miguel Hernández de Elche) y Guillermo Alexander Jácome Sarchi (Universidad Politécnica Estatal del Carchi).

Sigue el sílabo de Fisiología Vegetal (0811BFV4UB-AJ2025, nivel 4, Carrera de Agropecuaria, UPEC) del profesor Guillermo Alexander Jácome Sarchi: sus unidades, sus dos parciales, su aprendizaje basado en proyectos con frutales y su lectura crítica de artículos.

ORCID: Fernando Borrás Rocher [0000-0002-5519-4573](https://orcid.org/0000-0002-5519-4573) · Guillermo Alexander Jácome Sarchi [0009-0009-5311-2544](https://orcid.org/0009-0009-5311-2544)

## Cómo citar

Borrás Rocher, F. y Jácome Sarchi, G. A. (2026). *ClorofilIA* (v1.0.0) [Software]. (DOI en trámite)

## Licencia

MIT. Véase [LICENSE](LICENSE).
