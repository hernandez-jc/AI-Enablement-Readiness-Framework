# 01 — Calidad y preparación de datos

> **Dimensión del framework:** Datos  
> **Pregunta central:** ¿La organización dispone de datos suficientemente disponibles, confiables, pertinentes y utilizables para el caso de uso de IA?

---

## 1. ¿Por qué importa?

Los sistemas de IA dependen de los datos con los que trabajan.

Sin embargo, "tener datos" no significa necesariamente estar preparado para utilizarlos en un caso de uso de IA.

Una organización puede almacenar grandes cantidades de información y, al mismo tiempo, enfrentar problemas de:

- calidad;
- disponibilidad;
- consistencia;
- actualización;
- integración;
- documentación;
- acceso;
- permisos;
- trazabilidad;
- propiedad de los datos.

Por eso, la preparación de datos debe analizarse **en relación con el caso de uso específico**.

La pregunta no es simplemente:

> "¿Tenemos suficientes datos?"

Sino:

> "¿Tenemos los datos correctos, con la calidad, disponibilidad, permisos y trazabilidad necesarias para producir un resultado confiable para este caso de uso?"

---

## 2. El principio de "datos suficientes para el propósito"

No todos los casos de uso de IA requieren el mismo nivel de preparación de datos.

Por ejemplo:

| Caso de uso | Necesidades principales de datos |
|---|---|
| Generación de contenido interno | Documentos confiables, actualizados y accesibles |
| Asistente para políticas internas | Base documental completa, vigente y bien estructurada |
| Análisis predictivo | Datos históricos suficientes y consistentes |
| Atención al cliente | Información actualizada del cliente, productos y transacciones |
| Automatización de procesos | Datos estructurados, integrados y disponibles en tiempo adecuado |
| Sistema que apoya decisiones de alto impacto | Datos de alta calidad, trazables, gobernados y sujetos a controles adicionales |

Por lo tanto, una puntuación de preparación de datos no debe interpretarse de manera aislada.

Debe preguntarse:

**¿Es suficiente esta capacidad para el riesgo y las exigencias del caso de uso?**

---

# 3. Qué evalúa esta dimensión

La aplicación de assessment analiza la preparación de datos mediante diez criterios.

| ID | Elemento evaluado | Qué busca determinar |
|---|---|---|
| DATA-01 | Disponibilidad de datos | Si los datos necesarios existen y pueden obtenerse |
| DATA-02 | Calidad de datos | Si los datos son suficientemente precisos, completos y consistentes |
| DATA-03 | Relevancia | Si los datos realmente representan el problema que se quiere resolver |
| DATA-04 | Actualidad | Si los datos están suficientemente actualizados para el caso de uso |
| DATA-05 | Accesibilidad | Si las personas y sistemas autorizados pueden acceder a ellos |
| DATA-06 | Integración | Si las fuentes pueden conectarse y utilizarse conjuntamente |
| DATA-07 | Documentación | Si existe información suficiente para comprender los datos |
| DATA-08 | Trazabilidad | Si puede identificarse el origen y recorrido de los datos |
| DATA-09 | Propiedad y responsabilidad | Si existen responsables claros sobre los datos |
| DATA-10 | Permisos y uso | Si los datos pueden utilizarse legítimamente para el caso de uso |

Estos criterios permiten observar la preparación desde varias perspectivas.

Una organización puede, por ejemplo, tener datos abundantes pero una puntuación baja en trazabilidad o permisos.

---

# 4. DATA-01 — Disponibilidad de datos

### Qué significa

Evalúa si los datos necesarios para el caso de uso existen y pueden obtenerse de manera consistente.

La disponibilidad incluye más que la existencia física de información.

También considera:

- dónde están los datos;
- quién puede acceder a ellos;
- con qué frecuencia están disponibles;
- en qué formato;
- bajo qué condiciones;
- si su acceso depende de procesos manuales.

### ¿Por qué importa?

Un caso de uso puede parecer viable conceptualmente y, sin embargo, resultar difícil de implementar porque los datos requeridos no están disponibles cuando se necesitan.

### Conexión con el assessment

Una puntuación baja en este criterio puede indicar una limitación estructural, no necesariamente una necesidad de capacitación.

La investigación posterior debe determinar si la brecha se debe a:

- ausencia de datos;
- acceso restringido;
- procesos manuales;
- falta de integración;
- falta de conocimiento sobre dónde encontrar los datos.

### Implicación para AI Enablement

Si el problema es que los usuarios **no saben localizar o utilizar las fuentes disponibles**, puede existir una necesidad de aprendizaje.

Si los datos simplemente **no existen**, la solución probablemente requiere una intervención tecnológica, operativa o de gestión de información.

---

# 5. DATA-02 — Calidad de datos

### Qué significa

Evalúa si los datos presentan condiciones suficientes de:

- exactitud;
- completitud;
- consistencia;
- validez;
- unicidad;
- confiabilidad.

### ¿Por qué importa?

La IA puede producir resultados convincentes a partir de información incorrecta.

La sofisticación del modelo no corrige automáticamente datos deficientes.

### Conexión con el assessment

Una puntuación baja debe llevar a investigar:

> ¿Qué dimensiones de calidad están afectando el caso de uso?

No basta con afirmar que "los datos tienen problemas".

Es necesario identificar cuáles.

### Implicación para aprendizaje

Puede existir una necesidad de capacitación cuando las personas responsables:

- no conocen los estándares de calidad;
- no saben interpretar indicadores;
- no aplican correctamente reglas de validación;
- desconocen sus responsabilidades sobre la calidad.

Pero si la causa es estructural, la respuesta puede requerir cambios en:

- procesos;
- sistemas;
- controles;
- arquitectura de datos;
- responsabilidades.

---

# 6. DATA-03 — Relevancia

### Qué significa

Evalúa si los datos disponibles son pertinentes para el problema que la IA debe resolver.

No toda información disponible es información útil.

### ¿Por qué importa?

Un sistema puede tener acceso a grandes volúmenes de información y aun así carecer de los datos que explican adecuadamente el fenómeno, proceso o decisión que se quiere apoyar.

### Conexión con el assessment

Una puntuación baja debe provocar una revisión del vínculo entre:

```text
Problema
   ↓
Decisión / tarea
   ↓
Información necesaria
   ↓
Datos disponibles
   ↓
Resultado esperado
```

### Implicación para AI Enablement

Si el problema es que los usuarios **no saben localizar o utilizar las fuentes disponibles**, puede existir una necesidad de aprendizaje.

Si los datos simplemente **no existen**, la solución probablemente requiere una intervención tecnológica, operativa o de gestión de información.

---

# 5. DATA-02 — Calidad de datos

### Qué significa

Evalúa si los datos presentan condiciones suficientes de:

- exactitud;
- completitud;
- consistencia;
- validez;
- unicidad;
- confiabilidad.

### ¿Por qué importa?

La IA puede producir resultados convincentes a partir de información incorrecta.

La sofisticación del modelo no corrige automáticamente datos deficientes.

### Conexión con el assessment

Una puntuación baja debe llevar a investigar:

> ¿Qué dimensiones de calidad están afectando el caso de uso?

No basta con afirmar que "los datos tienen problemas".

Es necesario identificar cuáles.

### Implicación para aprendizaje

Puede existir una necesidad de capacitación cuando las personas responsables:

- no conocen los estándares de calidad;
- no saben interpretar indicadores;
- no aplican correctamente reglas de validación;
- desconocen sus responsabilidades sobre la calidad.

Pero si la causa es estructural, la respuesta puede requerir cambios en:

- procesos;
- sistemas;
- controles;
- arquitectura de datos;
- responsabilidades.

---

# 6. DATA-03 — Relevancia

### Qué significa

Evalúa si los datos disponibles son pertinentes para el problema que la IA debe resolver.

No toda información disponible es información útil.

### ¿Por qué importa?

Un sistema puede tener acceso a grandes volúmenes de información y aun así carecer de los datos que explican adecuadamente el fenómeno, proceso o decisión que se quiere apoyar.

### Conexión con el assessment

Una puntuación baja debe provocar una revisión del vínculo entre:

```text
Problema
   ↓
Decisión / tarea
   ↓
Información necesaria
   ↓
Datos disponibles
   ↓
Resultado esperado
```

Implicación para AI Enablement

Esta dimensión puede revelar una necesidad de aprendizaje relacionada con:

identificación de datos relevantes; formulación del problema; comprensión del proceso; interpretación de indicadores.

También puede revelar que el caso de uso necesita ser redefinido.

## DATA-04 — Actualidad

Qué significa

Evalúa si los datos están suficientemente actualizados para el propósito del sistema.

La frecuencia necesaria depende del caso de uso.

Caso de uso	Posible necesidad de actualización
Análisis histórico	Baja
Reportes mensuales	Periódica
Planeación operativa	Frecuente
Atención al cliente	Alta
Detección de eventos	Casi inmediata

No existe una frecuencia de actualización universalmente correcta.

La pregunta es:

¿La información sigue siendo válida cuando la IA la necesita?

## DATA-05 — Accesibilidad

Qué significa

Evalúa si los usuarios y sistemas autorizados pueden acceder a los datos necesarios.

La accesibilidad debe analizarse junto con:

seguridad; privacidad; permisos; roles; controles de acceso.

*Más accesible* no significa necesariamente *mejor*.

La meta es:

acceso adecuado para las personas y sistemas autorizados.

Conexión con aprendizaje

Una brecha puede deberse a que las personas:

desconocen los canales correctos; no saben solicitar acceso; no comprenden las reglas; no conocen las fuentes disponibles.

En ese caso, una intervención de aprendizaje puede complementar una solución tecnológica.

## DATA-06 — Integración

Qué significa

Evalúa la capacidad de combinar las fuentes necesarias para el caso de uso.

Puede involucrar:

sistemas empresariales; bases de datos; documentos; APIs; archivos; aplicaciones; repositorios. ¿Por qué importa?

Los datos necesarios para un caso de uso suelen estar distribuidos entre diferentes sistemas.

La falta de integración puede impedir que una solución funcione de forma consistente.

Implicación

Una puntuación baja suele señalar una necesidad tecnológica o arquitectónica.

No debe convertirse automáticamente en una recomendación de capacitación.

## DATA-07 — Documentación

Qué significa

Evalúa si existe información suficiente para comprender:

qué representa un dato; de dónde proviene; quién lo mantiene; qué significa cada campo; cuáles son sus limitaciones; cómo debe utilizarse. ¿Por qué importa?

La documentación permite que las personas y los sistemas utilicen los datos de manera consistente.

También facilita:

incorporación de nuevos usuarios; resolución de problemas; auditoría; mantenimiento; desarrollo de soluciones de IA. Conexión con aprendizaje

Aquí puede existir una necesidad directa de desarrollo de capacidades:

alfabetización de datos; interpretación de datasets; lectura de metadatos; comprensión de definiciones; uso correcto de fuentes. 

## DATA-08 — Trazabilidad Concepto clave: Data Lineage

La trazabilidad permite conocer el recorrido de un dato:

Fuente original
      ↓
Transformación
      ↓
Almacenamiento
      ↓
Integración
      ↓
Uso por la IA
      ↓
Resultado
¿Por qué importa?

Cuando un resultado generado por IA es cuestionado, la organización necesita poder investigar:

¿De dónde provino la información utilizada?

La trazabilidad es especialmente importante cuando:

las decisiones tienen impacto significativo; existen obligaciones regulatorias; los datos se transforman varias veces; intervienen múltiples sistemas. Conexión con el assessment

Una puntuación baja debe elevar el nivel de análisis antes de considerar determinados casos de uso como candidatos para producción.

## DATA-09 — Propiedad y responsabilidad

Concepto clave: Data Ownership

Debe existir claridad sobre quién es responsable de:

definir; mantener; validar; proteger; actualizar; corregir

los datos utilizados.

¿Por qué importa?

Cuando nadie tiene responsabilidad clara, los problemas de datos pueden permanecer sin resolver.

Conexión con AI Enablement

Esta dimensión también tiene una dimensión organizacional.

Las personas necesitan comprender:

qué responsabilidades tienen; qué decisiones pueden tomar; cuándo deben escalar un problema; quién debe aprobar cambios.

Por eso, una brecha puede requerir tanto:

definición organizacional + capacitación.

## DATA-10 — Permisos y uso

Concepto clave: Data Governance

Evalúa si los datos pueden utilizarse legítimamente para el caso de uso propuesto.

Debe considerarse:

autorización; privacidad; confidencialidad; propiedad intelectual; restricciones contractuales; políticas internas; requisitos regulatorios. Punto crítico

La disponibilidad técnica de un dato no implica automáticamente autorización para utilizarlo con IA.

Esta distinción debe formar parte de la cultura de AI Enablement.
