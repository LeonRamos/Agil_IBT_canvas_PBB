# PBB CANVAS 

El PBB Canvas es una herramienta colaborativa diseñada para ayudar a los equipos a escribir historias de usuario de manera efectiva. Este enfoque fue desarrollado por Fábio Aguiar y Paulo Caroli para facilitar la creación de un backlog de producto bien estructurado.

### Componentes principales del PBB Canvas

El canvas se compone de tres bloques principales:

- **Personas**
- **Funcionalidades**
- **Elementos del Backlog de Producto (PBIs)**

### Proceso de llenado del PBB Canvas

#### 1. Describir las Personas

**Objetivo**: Crear una representación realista de los usuarios del producto.

**Método**:
- Responder preguntas como: "¿Cuál es el perfil de esta persona? ¿Qué hace? ¿Qué espera?"
- Incluir información sobre el rol, necesidades y objetivos de la persona.

**Ejemplo**:

Persona: Orador
Perfil: Profesional que desea compartir conocimientos
Actividades: Preparar presentaciones, dar charlas
Expectativas: Llegar a una audiencia interesada, mejorar habilidades de presentación

#### 2. Entender las Funcionalidades

**Objetivo**: Identificar las interacciones clave entre las personas y el producto.

**Método**:
- Analizar las actividades de las personas.
- Identificar acciones o interacciones con el producto.
- Describir cada funcionalidad respondiendo: "¿Qué está tratando de hacer el usuario? ¿Qué problemas resuelve? ¿Qué beneficios aporta?"

**Ejemplo**:

Funcionalidad: Publicar una charla
Descripción: Permite a los oradores subir y compartir sus presentaciones
Desafíos: Asegurar la calidad del contenido, gestionar formatos diversos
Beneficios: Hacer el contenido disponible, aumentar visibilidad del orador

#### 3. Identificar los Elementos del Backlog de Producto (PBIs)

**Objetivo**: Desglosar las funcionalidades en elementos de trabajo más pequeños y precisos.

**Método**:
- Para cada funcionalidad, preguntar: "¿Cuál es el primer elemento de trabajo? ¿Y el segundo? ¿Y los siguientes?"
- Describir cada PBI como una acción realizada por un usuario en el producto.

**Ejemplo**:

PBI 1: Acceder a un espacio de trabajo privado
PBI 2: Subir una presentación
PBI 3: Editar detalles de la charla
PBI 4: Publicar la charla


#### 4. Conectar los bloques como una Historia de Usuario

**Objetivo**: Crear historias de usuario completas utilizando la información de los bloques anteriores.

**Método**: Utilizar el formato "Como [Persona], quiero [Acción] para [Beneficio]".

**Ejemplo de Historia de Usuario**:

Como Orador,
Quiero realizar la publicación del trabajo
Para hacer el contenido disponible


#### 5. Completar la Historia de Usuario

**Objetivo**: Añadir detalles adicionales para una implementación efectiva.

**Método**: Incluir criterios de aceptación, tareas, interfaz de usuario y habilitadores (si los hay).

**Ejemplo de Historia de Usuario Completa**:

Como Orador,
Quiero realizar la publicación del trabajo
Para hacer el contenido disponible

**Criterios de Aceptación**:
- El orador puede subir archivos en formatos PPT, PDF y video
- El sistema verifica que todos los campos obligatorios estén completos
- La charla aparece en la lista de charlas públicas después de la publicación

**Tareas**:
1. Implementar formulario de carga de archivos
2. Crear sistema de verificación de campos
3. Desarrollar función de publicación

**Interfaz de Usuario**:
- Diseñar página de carga de charlas con campos para título, descripción, etiquetas y archivo

### Beneficios del PBB Canvas

- **Colaboración**: Fomenta la participación de todo el equipo en la creación del backlog.
- **Enfoque en el usuario**: Mantiene el foco en las necesidades y objetivos de los usuarios.
- **Estructura clara**: Proporciona un proceso paso a paso para crear historias de usuario efectivas.
- **Visibilidad**: Ofrece una representación visual del backlog y sus componentes.
- **Flexibilidad**: Permite ajustes y refinamientos continuos del backlog.

El PBB Canvas es una herramienta valiosa para equipos ágiles que buscan mejorar la calidad de sus historias de usuario y, por ende, la eficacia de su desarrollo de producto.

# Origen y Contexto

El concepto de Historias de Usuario fue introducido por Kent Beck como parte de la Programación Extrema para fomentar un enfoque máságil y conversacional en la recopilación de requisitos. Mike Cohn posteriormente popularizó el concepto con su libro "User Stories Applied: For Agile Software Development" (2003).

Fábio Aguiar y Paulo Caroli desarrollaron la técnica de Product Backlog Building para ayudar a todos los miembros del equipo a escribir historias de usuario efectivas, no solo al Product Owner.

## Características de una Buena Historia de Usuario

###3W de la Historia de Usuario

Una historia de usuario debe responder a tres preguntas clave:

1. **Who?** (¿Quién?): ¿Para quién es?
2. **What?** (¿Qué?): ¿Cuál es la acción o actividad que la persona realiza?
3. **Why?** (¿Por qué?): ¿Por qué la persona lo usará (beneficio o razón)?

### INVEST

William C. Wake creó el acrónimo INVEST para describir las características de una buena historia de usuario:

- **I**ndependiente
- **N**egociable
- **V**aliosa
- **E**stimable
- **S**ized appropriately (Dimensionada adecuadamente)
- **T**esteable

### Modelo3Cs

- **Tarjeta** (Card): Descripción breve de la historia.
- **Conversación**: Detalles y aclaraciones a través del diálogo.
- **Confirmación**: Criterios de aceptación para verificar la implementación.

## Ejemplo Práctico: "La Colección de Charlas"

Para ilustrar el uso del PBB Canvas, utilizaremos un producto digital de ejemplo llamado "La Colección de Charlas", creado por una comunidad ágil regional para preparar un portafolio de charlas y organizar eventos.

### Ejemplo de Historia de Usuario

**PERSONA: PONENTE**

**FUNCIONALIDAD 1: Publicar una charla**

**HISTORIA 1.1:**
Como ponente,
Quiero acceder a un espacio de trabajo
Para gestionar mis charlas de forma privada

[Aquí se pueden añadir más detalles como criterios de aceptación, tareas e interfaz de usuario]

## Conclusión

El PBB Canvas proporciona una estructura clara y colaborativa para crear historias de usuario efectivas, mejorando la comunicación y el enfoque en el valor para el usuario en el desarrollo de productos.

---

Para más información, consulta la [traducción del artículo «Product Backlog Building Canvas» en la página de Martin Fowler](https://martinfowler.com/articles/product-backlog-building-canvas.html).

> **Cita**: "Una herramienta colaborativa para escribir historias de usuario. Muchos equipos de software describen las funcionalidades deseadas del producto como un backlog de producto: una lista de historias de usuario. Estas historias captan quién necesita la funcionalidad, qué se espera de ella y por qué se necesita. Con frecuencia, los equipos esperan que el propietario de producto (Product Owner) sea la única persona que alimenta el backlog, pero cualquier persona podría (y debería) escribir historias de usuario. El Canvas de Product Backlog Building (PBB) proporciona un proceso simple para desarrollar historias de usuario, comenzando con la descripción de las personas para el producto y las actividades que realizan." - [Martin Fowler](https://caroli.org/es/el-canvas-de-pbb/)

