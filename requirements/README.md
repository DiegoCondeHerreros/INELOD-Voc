# Requisitos ontológicos

Esta carpeta contiene toda la información sobre los **requisitos ontológicos y material suplementario** usado durante el desarrollo de la ontología.

# Propósito


El objetivo de esta carpeta es almacenar y organizar la **información de base o fundacional** que guía el diseño y la implementación de la ontología.

Estos requisitos definen **qué debe representar la ontología**, **para qué se está desarrollando** y **cómo debe apoyar los casos de uso previstos**.


# Contenido

Incluya cualquier documento o recurso que describa o justifique los requisitos de la ontología, tales como:

- **Preguntas de competencia** — Preguntas que la ontología debe ser capaz de responder.
- **Casos de uso y escenarios** — Descripciones de contextos del mundo real en los que se aplicará la ontología.
- **Requisitos del dominio** — Listas de conceptos clave, relaciones o restricciones recopiladas de expertos.
- **Requisitos de las partes interesadas** — Necesidades funcionales y no funcionales de usuarios u organizaciones.


# Formatos aceptados

Incluya recursos en los siguientes formatos:
- `.md` — Documentos Markdown   
- `.docx` / `.pdf` — Documentos de formalización de requisitos  
- `.csv` / `.xlsx` — Listas de requisitos o matrices de trazabilidad  
- `.txt` — Notas o borradores preliminares de los requisitos  

# Buenas prácticas

- Mantenga los requisitos **trazables** — vincule cada uno a los elementos de la ontología (clases, propiedades, etc. Ver plantilla).
- Mantenga un historial de versiones a medida que los requisitos evolucionan.
- Asegure la coherencia entre los requisitos, los diagramas de conceptualización y la implementación.
- Revise y valide los requisitos con expertos del dominio antes de que comience el desarrollo de la ontología. La [metodología LOT] (https://doi.org/10.1016/j.engappai.2022.104755) propone algunas guías:
  - Un conjunto de requisitos es correcto si cada requisito se refiere a alguna característica de la ontología que se va a desarrollar.
  - Un conjunto de requisitos es completo si los usuarios y expertos del dominio revisan los requisitos y confirman que no conocen requisitos adicionales.
  - Un conjunto de requisitos es internamente consistente si no existen conflictos entre ellos.
  - Un conjunto de requisitos es verificable si existe un proceso finito y de costo razonable que permita comprobar si la ontología final satisface cada requisito.
  - Un conjunto de requisitos es comprensible si cada requisito es entendible para los usuarios y expertos del dominio.
  - Un conjunto de requisitos no es ambiguo si cada requisito tiene una única interpretación posible; es decir, si no admite dudas o malentendidos.
  - Un conjunto de requisitos es conciso si cada requisito es relevante y no existen requisitos duplicados o irrelevantes.


# Notas
- Esta carpeta está destinada únicamente a la **documentación de los requisitos** — no para diagramas de la ontología ni archivos de implementación.  
- Se sugiere la organización en subcarpetas, e.g.:
  - `/preguntas-de-competencia/`  
  - `/casos-de-uso/`  
  - `/trazabilidad/`
