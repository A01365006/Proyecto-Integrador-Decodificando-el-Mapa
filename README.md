# Proyecto-Integrador-Decodificando-el-Mapa
## Integrantes
- Arturo González Corona - A01796900
- Jean Oliver Hernández Antillón - A01796723
- Oscar Gerardo Álvarez Mejía - A01365006
## Problemática
Los documentos coloniales de la Nueva España del siglo XVI mencionan cientos de lugares con formas ortográficas variables, inestables y a menudo irreconocibles para herramientas computacionales modernas, lo que impide vincularlos automáticamente con coordenadas geográficas o con registros históricos verificados.
## Objetivo
- Diseñar e implementar un procedimiento automatizado para identificar y extraer menciones de lugares geográficos del corpus de transcripciones (DECM Machine Ready Corpus) y vincularlas con entradas del gazetteer (DECM General Historical Gazetteer), mediante técnicas de similitud léxica y desambiguación contextual.
- Integrar el gazetteer histórico digital DECM como autoridad de referencia para la identificación y georreferenciación de topónimos del corpus colonial novohispano, documentando su estructura y alcance para el equipo.
- Desarrollar una estrategia para detectar y agrupar variantes ortográficas, formas abreviadas y denominaciones híbridas (castellanas, indígenas o mixtas) de un mismo topónimo, especialmente en contextos donde el idioma o la referencia administrativa son ambiguos.
- Generar un dataset geoespacial reutilizable que relacione cada mención textual de un lugar con su variante en el gazetteer, la fuente documental, la fecha del documento y la referencia geográfica correspondiente, acompañado de una visualización cartográfica preliminar que ilustre el alcance espacial del corpus.

Al final del proyecto se tendrá un Pipeline reproducible que sea capaz de lo siguiente:
- Identificar menciones de lugares en textos históricos
- Recuperar posibles correspondencias en el gazetteer
- Seleccionar o proponer la entidad histórico más probable
- Asignar información geográfica
- Evaluar el resultado contra las anotaciones existentes
