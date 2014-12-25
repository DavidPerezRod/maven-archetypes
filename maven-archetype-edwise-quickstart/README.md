maven-archetype-edwise-quickstart
================

Archetype maven basado en el quickstart de apache, pero con los siguientes cambios:

- Formateado de ficheros pom y java
- En el pom, versión junit actualizada
- En el pom, property java.version a 1.8
- Renombradas clases java a Application
- Clase test de junit4
- Otras modificaciones de código

Datos archetype:

groupId: com.edwise.archetype

artifactId: maven-archetype-edwise-quickstart

version: 0.3.1

<br/>
Pasos para usarlo:

- Para instalar el archetype en tu repositorio local, ejecutar esto en el raiz del proyecto:

    ```
    mvn install
    ```
 
- Para crear un proyecto usando el archetype: 

    ```
    mvn archetype:generate -DarchetypeGroupId=com.edwise.archetype -DarchetypeArtifactId=maven-archetype-edwise-quickstart
    ```
 También puede usarse desde un IDE, por ejemplo, en Intellij: 'Create New Proyect', seleccionamos 'Maven', chequeamos  'Create from archetype', pulsamos en 'Add archetype...' y rellenamos con los datos del archetype.
