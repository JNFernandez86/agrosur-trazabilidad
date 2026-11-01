# AgroSur S.A. – Módulo de Trazabilidad e Inventario

Trabajo Práctico Integrador – Organización Empresarial
Tecnicatura Universitaria en Programación a Distancia – Universidad Tecnológica Nacional (UTN)

## Descripción del sistema
Módulo de software de trazabilidad y gestión de inventario para AgroSur S.A.,
empresa agroindustrial de alimentos orgánicos. Permite registrar el ingreso de
insumos, vincular cada lote de producción con los insumos consumidos y generar
los reportes de trazabilidad que exigen SENASA y la certificadora orgánica.

## Integrantes
| Nombre y apellido | Usuario de GitHub |
|---|---|
|Jorge Nahuel Fernandez | [@JNFernandez86](https://github.com/JNFernandez86) |

## Contenido de la documentación
- [Caso de estudio](docs/01-caso-estudio/)
- [Sistema abierto y FODA](docs/02-sistema-abierto-y-foda/)
- [Organigrama](docs/03-organigrama/)
- [Diccionario de datos](docs/04-diccionario-de-datos/)
- [Modelado BPMN](docs/05-bpmn/)
- [Planificación (Gantt)](docs/06-planificacion-gantt/)

## Declaración de uso de IA

Para este trabajo utilicé dos asistentes de IA generativa. **Microsoft Copilot** se
usó para mejorar la redacción de los textos y para dar formato a los documentos.
**Claude (Anthropic)** se usó como apoyo para estructurar los entregables, proponer
borradores y resolver dudas técnicas. La estructura general, las decisiones de diseño
y la versión final de cada entregable son de mi autoría.


### Usos y justificación de los prompts

| Uso | Cómo se formuló y por qué | Corrección humana sobre el resultado |
|---|---|---|
| Elección del caso de estudio | Pedí tres casos de estudio a cada asistente, con justificación, para comparar alternativas en lugar de aceptar la primera. | Elegí AgroSur S.A. por mi cuenta, buscando un sector menos asociado a lo tecnológico. |
| Organigrama | Partí de un esquema propio y pedí propuestas de mejora, para que la IA ampliara y no definiera la estructura. | Rehice las áreas de Sistemas con la estructura real que conozco del sector (Sistemas del Negocio y ERP, Infraestructura y Soporte, Ciberseguridad, Base de datos), por considerar demasiado general la propuesta de la IA. |
| Diagrama BPMN | Pedí un esquema del proceso con pools, lanes y compuertas de decisión para las excepciones. | Lo rehice en Bizagi eligiendo yo los elementos (compuerta exclusiva, tarea de servicio, fin simple) según la notación de la unidad. |
| FODA y Gantt | Pedí ideas y ordenamiento de la información. | Armé el FODA en la plantilla de la cátedra y adapté el Gantt al formato de hitos con fechas. |
| Historias de usuario (HU-01 a HU-03) | Las originales no estaban disponibles, así que pedí un borrador coherente con el BPMN y el diccionario de datos. | Las revisé, las cargué como issues y las gestioné en el tablero y en pull requests propios. |
| Uso de Git y GitHub | Consulté los pasos del flujo de ramas, commits y pull requests. | Ejecuté los comandos yo mismo y resolví un error de rama (un commit hecho sobre `main`) antes de continuar. |
| Redacción y formato del informe | Pedí a Copilot que mejorara la claridad de los textos y diera formato uniforme al documento. | Revisé cada texto para que conservara el sentido original y los datos del caso, y corregí lo que no coincidía con mi trabajo. |

### Limitaciones
La IA puede generar errores o valores inventados. Los estándares numéricos de los
indicadores de control son propuestas razonables y no datos de una empresa real.