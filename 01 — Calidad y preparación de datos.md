# 01 — Calidad y preparación de datos

> **Dimensión 01 del AI Enablement Readiness Framework**
> **Pregunta central:** ¿La organización dispone de datos suficientemente disponibles, confiables, pertinentes y utilizables para el caso de uso de IA?

---

## 1. Propósito de esta dimensión

La preparación de datos es una condición fundamental para utilizar IA de manera efectiva.

Sin embargo, **tener datos no significa necesariamente estar preparado para utilizarlos**.

Una organización puede disponer de grandes volúmenes de información y, al mismo tiempo, enfrentar problemas relacionados con:

* disponibilidad;
* calidad;
* relevancia;
* actualidad;
* accesibilidad;
* integración;
* documentación;
* trazabilidad;
* propiedad;
* permisos y uso.

Por esta razón, esta dimensión no evalúa solamente si existen datos.

Evalúa si los datos disponibles son **adecuados para el caso de uso específico**.

### Pregunta orientadora

> **¿Tenemos los datos correctos, con la calidad, disponibilidad, acceso y condiciones de uso necesarias para producir un resultado confiable para este caso de uso?**

---

# 2. Datos suficientes para el propósito

No todos los casos de uso de IA requieren el mismo tipo o nivel de preparación de datos.

| Caso de uso                         | Necesidades principales de datos                                 |
| ----------------------------------- | ---------------------------------------------------------------- |
| Generación de contenido interno     | Documentos confiables, actualizados y accesibles                 |
| Asistente para políticas internas   | Información completa, vigente y correctamente documentada        |
| Análisis predictivo                 | Datos históricos suficientes, consistentes y pertinentes         |
| Atención al cliente                 | Información actualizada y disponible en el momento necesario     |
| Automatización de procesos          | Datos estructurados, integrados y disponibles de manera oportuna |
| Apoyo a decisiones de mayor impacto | Datos confiables, trazables y sujetos a controles apropiados     |

Por lo tanto, la preparación de datos debe evaluarse **en función del propósito y contexto del caso de uso**.

Una puntuación determinada no debe interpretarse de manera aislada.

La pregunta es:

> **¿El nivel actual de preparación de datos es suficiente para las exigencias de este caso de uso?**

---

# 3. Qué evalúa esta dimensión

El assessment utiliza criterios que permiten observar diferentes aspectos de la preparación de datos.

| ID      | Criterio                    | Qué busca determinar                                                                     |
| ------- | --------------------------- | ---------------------------------------------------------------------------------------- |
| DATA-01 | Disponibilidad              | Si los datos necesarios existen y pueden obtenerse                                       |
| DATA-02 | Calidad                     | Si los datos son suficientemente precisos, completos y consistentes                      |
| DATA-03 | Relevancia                  | Si los datos representan adecuadamente el problema o tarea                               |
| DATA-04 | Actualidad                  | Si los datos están suficientemente actualizados                                          |
| DATA-05 | Accesibilidad               | Si las personas y sistemas autorizados pueden acceder a ellos                            |
| DATA-06 | Integración                 | Si las fuentes pueden conectarse y utilizarse conjuntamente                              |
| DATA-07 | Documentación               | Si existe información suficiente para comprender los datos                               |
| DATA-08 | Trazabilidad                | Si puede identificarse el origen y recorrido de los datos                                |
| DATA-09 | Propiedad y responsabilidad | Si existen responsables claros sobre los datos                                           |
| DATA-10 | Permisos y uso              | Si los datos pueden utilizarse para el caso de uso bajo las condiciones correspondientes |

Estos criterios permiten evitar una interpretación simplista basada únicamente en el volumen de datos disponible.

---

# 4. DATA-01 — Disponibilidad

### Qué significa

Evalúa si los datos necesarios para el caso de uso existen y pueden obtenerse cuando son necesarios.

La disponibilidad puede depender de:

* ubicación de los datos;
* formato;
* frecuencia de actualización;
* acceso;
* procesos manuales;
* sistemas utilizados;
* responsables.

### ¿Por qué importa?

Un caso de uso puede parecer viable conceptualmente y, sin embargo, resultar difícil de implementar porque los datos requeridos no están disponibles de manera consistente.

### Relación con el assessment

Una puntuación baja identifica una condición que requiere investigación.

No determina por sí sola que exista una necesidad de capacitación.

La causa puede estar relacionada con:

* ausencia de datos;
* acceso restringido;
* procesos manuales;
* falta de integración;
* falta de conocimiento sobre dónde localizar información.

### Posible implicación para AI Enablement

Si las personas no saben **dónde localizar o cómo utilizar datos que ya están disponibles**, puede existir una necesidad de desarrollo de capacidades.

Si los datos simplemente **no existen o no pueden utilizarse**, la respuesta probablemente requerirá otro tipo de intervención.

---

# 5. DATA-02 — Calidad

### Qué significa

Evalúa si los datos presentan condiciones suficientes de:

* exactitud;
* completitud;
* consistencia;
* validez;
* unicidad;
* confiabilidad.

### ¿Por qué importa?

Un sistema de IA puede generar resultados aparentemente convincentes a partir de información incorrecta o incompleta.

La sofisticación de la herramienta no corrige automáticamente una deficiencia en los datos.

### Relación con el assessment

Una puntuación baja debe conducir a una investigación más específica.

La pregunta no debe ser solamente:

> "¿La calidad de los datos es baja?"

Debe ser:

> **"¿Qué dimensión de calidad está afectando el caso de uso y por qué?"**

### Posible implicación para aprendizaje

Puede existir una necesidad de aprendizaje cuando las personas responsables:

* desconocen estándares de calidad;
* no saben interpretar indicadores;
* no aplican correctamente reglas de validación;
* desconocen sus responsabilidades.

Pero si la causa es estructural, puede ser necesario intervenir en:

* procesos;
* sistemas;
* controles;
* arquitectura;
* responsabilidades.

---

# 6. DATA-03 — Relevancia

### Qué significa

Evalúa si los datos disponibles son pertinentes para el problema, tarea, proceso o decisión que la IA debe apoyar.

No toda información disponible es información útil para un caso de uso determinado.

### ¿Por qué importa?

Una organización puede disponer de grandes cantidades de información y, aun así, no contar con los datos necesarios para representar adecuadamente el problema que desea resolver.

### Relación con el assessment

La relevancia debe analizarse siguiendo una cadena lógica:

```text
Problema
    ↓
Tarea o decisión
    ↓
Información necesaria
    ↓
Datos disponibles
    ↓
Resultado esperado
```

Si existe una desconexión entre estos elementos, la disponibilidad de grandes cantidades de datos no garantiza que el caso de uso sea viable.

---

# 7. DATA-04 — Actualidad

### Qué significa

Evalúa si los datos están suficientemente actualizados para el propósito del caso de uso.

La frecuencia de actualización requerida dependerá del contexto.

Por ejemplo, un caso de uso puede requerir:

* información histórica;
* actualización diaria;
* actualización en tiempo casi real;
* información vigente al momento de la decisión.

### Relación con el assessment

Una puntuación baja debe interpretarse en función de la necesidad real del caso de uso.

**Datos antiguos no son necesariamente datos deficientes.**

Su utilidad depende del propósito para el cual se utilizan.

---

# 8. DATA-05 — Accesibilidad

### Qué significa

Evalúa si las personas y sistemas autorizados pueden acceder a los datos que necesitan.

La accesibilidad puede verse afectada por:

* permisos;
* sistemas aislados;
* procesos manuales;
* formatos;
* restricciones organizacionales;
* falta de conocimiento sobre dónde encontrar la información.

### Relación con AI Enablement

La accesibilidad conecta la preparación de datos con la capacidad de las personas y con la infraestructura tecnológica.

Por ello, una limitación identificada aquí puede requerir una intervención de:

* datos;
* tecnología;
* procesos;
* gobernanza;
* aprendizaje.

---

# 9. DATA-06 — Integración

### Qué significa

Evalúa si diferentes fuentes de datos pueden conectarse y utilizarse conjuntamente cuando el caso de uso lo requiere.

Puede involucrar:

* sistemas;
* bases de datos;
* aplicaciones;
* formatos;
* interfaces;
* procesos de intercambio.

### ¿Por qué importa?

Un caso de uso puede depender de información distribuida entre diferentes sistemas.

La existencia de cada fuente por separado no garantiza que puedan utilizarse conjuntamente.

---

# 10. DATA-07 — Documentación

### Qué significa

Evalúa si existe información suficiente para comprender:

* qué representan los datos;
* de dónde provienen;
* cómo están estructurados;
* qué significan sus campos;
* cómo deben utilizarse;
* quién es responsable de ellos.

### ¿Por qué importa?

La falta de documentación dificulta que las personas y los sistemas interpreten correctamente la información.

También dificulta la trazabilidad y el uso consistente.

---

# 11. DATA-08 — Trazabilidad

### Qué significa

Evalúa si puede identificarse el origen, recorrido y transformación de los datos.

La trazabilidad permite comprender:

```text
Fuente
   ↓
Captura
   ↓
Transformación
   ↓
Almacenamiento
   ↓
Uso
   ↓
Resultado
```

### ¿Por qué importa?

La trazabilidad facilita la investigación de errores, la supervisión y la comprensión de cómo la información llegó a formar parte de un resultado.

---

# 12. DATA-09 — Propiedad y responsabilidad

### Qué significa

Evalúa si existen responsabilidades claras respecto de los datos.

Debe ser posible identificar, según corresponda:

* quién administra los datos;
* quién es responsable de su calidad;
* quién autoriza determinados usos;
* quién debe resolver problemas;
* quién mantiene la documentación.

### Relación con AI Enablement

La ausencia de responsabilidades claras puede convertirse en una barrera para la utilización sostenible de IA.

Una solución tecnológica no elimina la necesidad de responsabilidades organizacionales.

---

# 13. DATA-10 — Permisos y uso

### Qué significa

Evalúa si los datos pueden utilizarse para el caso de uso bajo las condiciones correspondientes.

Esto incluye considerar las restricciones y condiciones organizacionales aplicables al acceso y utilización de la información.

### ¿Por qué importa?

Que una persona pueda técnicamente acceder a determinados datos no significa necesariamente que pueda utilizarlos para cualquier propósito.

Este criterio conecta la preparación de datos con la dimensión de **Gobernanza**.

---

# 14. Interpretación de los resultados

Los resultados de esta dimensión deben utilizarse como **evidencia para orientar la investigación**, no como una conclusión automática.

La lógica es:

```text
Resultado del assessment
        ↓
Identificación de posible brecha
        ↓
Investigación
        ↓
Identificación de causa
        ↓
Determinación de intervención
```

Una puntuación baja puede indicar una necesidad relacionada con:

* datos;
* procesos;
* tecnología;
* gobernanza;
* responsabilidades;
* capacidades humanas.

Por lo tanto:

> **DATA score bajo ≠ automáticamente capacitación.**

---

# 15. Relación con las demás dimensiones

La preparación de datos no funciona de manera independiente.

Puede existir una relación directa con:

| Dimensión                                  | Relación                                                                                    |
| ------------------------------------------ | ------------------------------------------------------------------------------------------- |
| **Skills y talento**                       | Las personas necesitan capacidades para localizar, interpretar, utilizar y evaluar datos    |
| **Gobernanza**                             | Los datos requieren reglas, responsabilidades, controles y condiciones de uso               |
| **Tecnología e infraestructura**           | Los sistemas determinan cómo se almacenan, integran, protegen y hacen disponibles los datos |
| **Estrategia y alineación con el negocio** | Los datos deben responder a necesidades y casos de uso relevantes para la organización      |

Esto refuerza el principio general del framework:

> **La preparación para IA es un sistema de condiciones interdependientes.**

---

# 16. Relación con el assessment app

La aplicación de assessment utiliza preguntas estructuradas para generar información sobre esta dimensión.

Los resultados pueden contribuir a identificar:

* fortalezas;
* posibles brechas;
* áreas que requieren investigación;
* prioridades relativas;
* señales que deben considerarse junto con las demás dimensiones.

La aplicación **no sustituye la validación posterior con la organización**.

Su función es proporcionar una primera capa de evidencia que facilite la conversación y el análisis.

---

# 17. Del resultado a la necesidad de aprendizaje

Cuando el assessment identifica una posible brecha relacionada con datos, debe realizarse una investigación adicional.

Por ejemplo:

```text
DATA score bajo
      ↓
¿Los datos existen?
      ↓
Sí ─────────────── No
 ↓                   ↓
¿Son accesibles?     Intervención
 ↓                   de datos/
Sí / No              estrategia
 ↓
¿Las personas
saben utilizarlos?
 ↓
Sí / No
 ↓
Posible necesidad
de capacidades
```

Esta lógica evita convertir automáticamente todos los problemas de datos en cursos.

---

# 18. Preguntas para profundizar durante el workshop

Los resultados pueden utilizarse como punto de partida para preguntas como:

1. ¿Qué datos requiere realmente el caso de uso?
2. ¿Dónde se encuentran?
3. ¿Quién puede acceder a ellos?
4. ¿Qué tan confiables son?
5. ¿Qué tan actualizados deben estar?
6. ¿Existen diferentes fuentes que deben integrarse?
7. ¿La información está suficientemente documentada?
8. ¿Puede rastrearse su origen?
9. ¿Quién es responsable de su calidad y uso?
10. ¿Existen restricciones sobre cómo pueden utilizarse?

Estas preguntas ayudan a transformar una puntuación en una conversación diagnóstica.

---

# 19. Conexión con el TNA

La información de esta dimensión puede contribuir al **Training Needs Analysis**, pero solamente después de investigar la causa de la brecha.

La cadena es:

```text
Assessment
    ↓
Posible brecha en datos
    ↓
Investigación de la causa
    ↓
¿La causa está relacionada con una capacidad?
    ↓
Sí → TNA
No → Otra intervención
```

Por ejemplo, si las personas no saben interpretar o utilizar correctamente una fuente de datos disponible, puede existir una necesidad de aprendizaje.

Si el problema es que la fuente no existe o no está integrada, la solución no es necesariamente formativa.

→ [Continuar con 02 — Skills y talento](02-skills-and-talent.md)

---

## Navegación

⬅️ [Volver al README](README.md)

➡️ [02 — Skills y talento](02-skills-and-talent.md)
