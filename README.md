worldChef - Utilidades de Procesamiento de Texto en Español

Descripción:
worldChef integra varias herramientas para analizar texto en español: normalización, búsqueda con expresiones regulares (fechas, dinero, correos), resumen simple, extracción de entidades nombradas (NER), palabras clave y análisis de sentimiento.

Requisitos:
- Python 3.x
- Opcional: spaCy con modelo español, nltk, transformers para funcionalidades avanzadas.

Instalación necesaria:
pip install spacy nltk transformers
python -m spacy download es_core_news_sm

Uso:
Ejecutar el script worldChef.py desde línea de comandos.
Seleccionar opciones del menú para ejecutar análisis sobre texto ingresado manualmente o desde archivo.
Se generan logs automáticos en la carpeta "logs" con registro de entradas y resultados.

Funcionalidades principales:
- Normalización de texto con corrección y lematización.
- Detección de patrones: fechas, cantidades monetarias y correos electrónicos.
- Resumen simple basado en relevancia de oraciones.
- Extracción de entidades nombradas: personas, lugares, empresas, fechas y cantidades.
- Identificación de palabras clave y términos frecuentes.
- Análisis de sentimiento usando modelo BERT multilingüe.

Notas:
- Algunas funciones requieren instalaciones adicionales para funcionar.
- El proyecto incluye manejo básico de errores y registro de sesiones.
- Permite análisis interactivo mediante menú de consola.

Autor: Desarrollo para procesamiento textual en español.
Fecha: Noviembre 2025
