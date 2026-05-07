# Pruebas de la ontología

Esta carpeta contiene todas las **pruebas diseñadas para verificar que la ontología cumple con los requisitos definidos**.
Estas pruebas garantizan que la ontología represente correctamente el conocimiento previsto, satisfaga las preguntas de competencia y esté alineada con las necesidades del dominio.

# Propósito

El objetivo de esta carpeta es almacenar los **artefactos generados para la validación y verificación** que confirmen que la ontología se comporta según lo esperado.

Las pruebas ayudan a garantizar la **calidad, coherencia y completitud** de la ontología con respecto a sus requisitos.

# Contenidos

Incluir cualqueir fichero o scripts utilizados para validar la ontología, como por ejemplo:

- **Pruebas de Themis** — Pruebas automatizadas descritas usando  [Themis](https://themis.linkeddata.es/).
- **Consultas SPARQL** — Consultas para comprobar que las preguntas de competencia pueden responderse utilizando la ontología. 
- **Informes de validacón de SHACL** — Para verificar que los datos se ajustan a las restricciones de la ontología.  
- **Automatización de pruebas/scripts** — Implementados en Python, Java u otros lenguajes para ejecutar validaciones de la ontología.
- **Datos para pruebas** — Ficheros RDF o Turtle files utilizados como input de la validación.  
- **Informes** — Documentos informando o resumiendo el resultado de las pruebas.

# Formatos aceptados

Se pueden utilizar formatos como:
- `.rq` — Ficheros de consultas SPARQL 
- `.py`, `.sh`, `.ipynb` — Scripts para testeo autómatico 
- `.ttl`, `.rdf`, `.jsonld` — Datos de ejemplo 
- `.md`, `.pdf` — Informes o documentación de los resultados de las pruebas 

# Buenas prácticas

Aquí tienes la traducción al español, manteniendo el tono técnico y claro:

- Alinee cada prueba con un **requisito específico o una pregunta de competencia.**
- Mantenga los archivos de prueba **versionados** de acuerdo a las actualizaciones de la ontología.
- Automatice las pruebas siempre que sea posible (por ejemplo, mediante GitHub Actions o flujos de trabajo de integración contínua).
- Documente los resultados esperados de cada prueba para asegurar su reproducibilidad.
- Almacene los datos de prueba por separado de los datos de producción o de ejemplo.


# Notas
- Esta carpeta es únicamente para la **validación de requisitos y las pruebas de la ontología** — no para archivos de implementación ni para las propias restricciones SHACL.
- Se sugiere la organización en subcarpetas, e.g.:
  - `/preguntas-de-competencia/`  
  - `/pruebas/`  
  - `/informes/`