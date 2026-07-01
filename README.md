# Build an Agent with RAG in DPAF

Este laboratorio acompaña el proceso de creación de agentes con **Oracle AI Database Private Agent Factory (DPAF)**, usando una base de datos Oracle como fuente de conocimiento y modelos de IA generativa para responder preguntas en lenguaje natural.

La idea es avanzar paso a paso por los notebooks/documentos del laboratorio. Cada uno cubre una parte del flujo y debe seguirse en orden.

## Orden recomendado

1. [Instalación](<1. Instalación.md>)

   Prepara los recursos necesarios en OCI, despliega DPAF desde Marketplace y conecta la plataforma con la base de datos.

2. [Creación de un agente para análisis de datos](<2. Creación de un agente para análisis de datos.md>)

   Carga datos en la base, crea un Data Source en DPAF y publica un agente capaz de responder preguntas sobre esos datos.

3. [Creación de un flujo con Agent Builder](<3. Creación de un flujo con Agent Builder.md>)

   Construye un flujo visual con componentes como Chat Input, Prompt, Agent, SQL Query, File Upload y Chat Output.

## Datos incluidos

La carpeta [datos](<datos>) contiene archivos CSV y un PDF de ejemplo que pueden usarse durante los ejercicios de carga, análisis y RAG.

## Resultado esperado

Al finalizar los notebooks, tendrás DPAF desplegado, una base de datos conectada, agentes publicados y flujos capaces de combinar datos estructurados, documentos y preguntas en lenguaje natural.
