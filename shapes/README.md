# Restricciones SHACL 


Esta carpeta contiene las **restricciones descritas en SHACL (Shapes Constraint Language)** asociadas con la ontología.

Estas restricciones se utilizan para validar datos RDF y asegurar que los datos de instancia se ajusten a la estructura, restricciones y semántica de la ontología.


# Propósito

El objetivo de este directorio es almacenar las **reglas y restricciones de validación** definidas para la ontología.

Las restricciones SHACL ayudan a verificar que los datos que utilizan la ontología sigan el modelo previsto, comprobando la pertenencia a clases, los rangos de las propiedades, las cardinalidades y otras condiciones.


# Formatos aceptados

Incluir cualquier tipo de fichero que defina restricciones SHACL como:

- `.ttl` — Restricciones SHACL shapes en sintaxis Turtle   
- `.rdf` — Restricciones SHACL shapes en sintaxis Turtle RDF/XML   
- `.jsonld` — Restricciones SHACL shapes en sintaxis JSON-LD   

También se puede incluir documentación complementaria que explique la lógica de validación o las instrucciones de uso.

# Buenas prácticas

- Mantenga las restricciones SHACL **consistentes** con la versión más reciente de la ontología.
- Documente el propósito y el alcance de cada restricción (por ejemplo, a nivel de clase, de propiedad o de conjunto de datos).
- Utilice un diseño modular si su ontología incluye múltiples dominios o módulos (por ejemplo, `/restricciones/core/`, `/restricciones/extension/`).


# Notas

- Esta carpeta es únicamente para la definición de **validaciones y restricciones** — no para la implementación de la ontología ni para los datos de ejemplo.
- Considere mantener un registro de cambios para seguir las actualizaciones de las restricciones SHACL.


