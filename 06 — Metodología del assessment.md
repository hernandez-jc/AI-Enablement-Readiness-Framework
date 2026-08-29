# 06 — Metodología del assessment

> **Función dentro del framework:** Convertir las cinco dimensiones de preparación para AI Enablement en un diagnóstico estructurado, comparable y accionable.
> **Pregunta central:** ¿Cómo evaluamos de manera consistente la preparación de la organización y transformamos los resultados en información útil para la toma de decisiones y el Training Needs Analysis?

---

## 1. Propósito del assessment

El assessment constituye el punto de partida del framework de AI Enablement.

Su función no es simplemente determinar si una organización está "preparada" o "no preparada" para utilizar IA.

Su propósito es construir una **línea base estructurada** que permita identificar:

* fortalezas actuales;
* brechas de capacidad;
* condiciones habilitadoras;
* restricciones;
* prioridades;
* necesidades potenciales de desarrollo;
* áreas que requieren intervención organizacional, tecnológica o de procesos.

El resultado debe permitir pasar de una percepción general de preparación:

> "Necesitamos prepararnos para IA."

a una comprensión más precisa:

> **"Estas son nuestras capacidades actuales, estas son las brechas prioritarias, estas condiciones están limitando la adopción y estas capacidades deben desarrollarse para alcanzar nuestros objetivos."**

---

# 2. Las cinco dimensiones

El assessment se estructura en cinco dimensiones complementarias.

| Dimensión                                       | Pregunta central                                                                                 |
| ----------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| **01 — Calidad y preparación de datos**         | ¿Contamos con datos suficientemente disponibles, confiables, pertinentes y utilizables?          |
| **02 — Skills y talento**                       | ¿Contamos con las capacidades humanas necesarias para utilizar, evaluar y desarrollar IA?        |
| **03 — Gobernanza**                             | ¿Existen reglas, responsabilidades y controles para utilizar IA de manera responsable?           |
| **04 — Tecnología e infraestructura**           | ¿Contamos con la tecnología e infraestructura necesarias para implementar IA?                    |
| **05 — Estrategia y alineación con el negocio** | ¿Las iniciativas de IA están conectadas con prioridades y resultados relevantes para el negocio? |

Las cinco dimensiones deben analizarse conjuntamente.

Una fortaleza en una dimensión no elimina automáticamente una brecha en otra.

Por ejemplo:

```text
Buena tecnología
      +
Datos disponibles
      +
Baja capacidad de Skills
      =
Capacidad tecnológica sin capacidad suficiente de adopción
```

Por esta razón, el resultado debe interpretarse como un **sistema de capacidades**, no como cinco puntuaciones independientes.

---

# 3. Unidad de análisis

El assessment puede utilizarse a diferentes niveles.

| Nivel             | Propósito                                                    |
| ----------------- | ------------------------------------------------------------ |
| **Individual**    | Identificar percepción y capacidades de una persona          |
| **Rol**           | Identificar necesidades asociadas con una función específica |
| **Equipo**        | Identificar patrones y brechas compartidas                   |
| **Área / unidad** | Comparar capacidades entre funciones                         |
| **Organización**  | Construir una visión global de preparación                   |

Esta distinción es importante porque una organización puede presentar una puntuación general razonable y, al mismo tiempo, tener **brechas críticas concentradas en determinados roles o áreas**.

---

# 4. El assessment como línea base

El assessment debe establecer una línea base que pueda utilizarse posteriormente para comparar evolución.

La lógica recomendada es:

```text
Assessment inicial
        ↓
Línea base
        ↓
Intervención
        ↓
Aprendizaje / Enablement
        ↓
Aplicación
        ↓
Assessment posterior
        ↓
Comparación
        ↓
Evolución observada
```

Por esta razón, los datos de identificación del participante son importantes.

La aplicación debe permitir asociar cada respuesta con información como:

* nombre;
* organización;
* cargo;
* ocupación;
* nivel;
* identificador único;
* fecha;
* timestamp.

Esto permite realizar análisis posteriores sin depender únicamente de resultados agregados.

---

# 5. Información del participante

La aplicación de assessment debe recopilar, como mínimo, los campos necesarios para identificar y segmentar los resultados.

| Campo            | Propósito                                 |
| ---------------- | ----------------------------------------- |
| **Nombre**       | Identificación del participante           |
| **Organización** | Agrupación por empresa                    |
| **Cargo**        | Identificación del rol                    |
| **Ocupación**    | Clasificación del trabajo realizado       |
| **Nivel**        | Segmentación por nivel de responsabilidad |
| **ID único**     | Identificación consistente del registro   |
| **Fecha**        | Identificación del momento del assessment |
| **Timestamp**    | Registro preciso de fecha y hora          |

El nivel puede utilizar categorías como:

* Director;
* Ejecutivo;
* Gerente;
* Líder / Supervisor;
* Profesional;
* Especialista;
* Coordinador;
* Analista;
* Operativo;
* Otro.

Las categorías pueden adaptarse posteriormente a la estructura de cada cliente.

---

# 6. Estructura de las preguntas

Cada dimensión debe descomponerse en elementos observables.

La estructura general es:

```text
Dimensión
    ↓
Elemento
    ↓
Pregunta / indicador
    ↓
Respuesta
    ↓
Puntuación
```

Esto permite evitar preguntas excesivamente generales como:

> "¿Qué tan preparada está su organización para IA?"

En su lugar, el assessment debe formular preguntas que permitan evaluar componentes concretos de la preparación.

---

# 7. Escala de respuesta

Se recomienda utilizar una escala consistente de madurez de **1 a 5**.

| Score | Nivel         | Significado general                                        |
| ----: | ------------- | ---------------------------------------------------------- |
| **1** | Inicial       | Capacidad inexistente, mínima o altamente limitada         |
| **2** | En desarrollo | Existen capacidades parciales o iniciativas aisladas       |
| **3** | Funcional     | La capacidad existe y permite atender necesidades actuales |
| **4** | Gestionada    | La capacidad está estructurada, documentada y gestionada   |
| **5** | Optimizada    | La capacidad está integrada, medida y mejora continuamente |

La escala debe mantenerse consistente entre dimensiones para facilitar la comparación.

Sin embargo:

> **El significado específico de cada puntuación debe adaptarse al elemento evaluado.**

Un "3" en datos no significa exactamente lo mismo que un "3" en Skills o Gobernanza.

---

# 8. No confundir percepción con evidencia

Un assessment puede recoger percepciones de los participantes, pero una percepción no necesariamente constituye evidencia objetiva.

Por ejemplo:

> "Tenemos datos de buena calidad."

es una percepción.

Mientras que:

> "Existe un estándar documentado de calidad, indicadores y responsables definidos."

constituye evidencia organizacional más concreta.

Por eso, cuando sea posible, las preguntas deben orientar al participante hacia **condiciones observables**.

### Principio metodológico

> **Evaluar condiciones y comportamientos observables, no solamente opiniones generales.**

---

# 9. Scoring

El scoring convierte las respuestas en información comparable.

Para cada dimensión puede calcularse un resultado agregado:

```text
Score de dimensión
=
resultado de sus elementos evaluados
```

Posteriormente pueden calcularse:

* score por dimensión;
* score global;
* distribución de respuestas;
* fortalezas;
* brechas;
* diferencias entre grupos;
* diferencias entre niveles;
* diferencias entre ocupaciones.

El objetivo del scoring no es producir una falsa precisión.

Su propósito es **hacer visibles patrones y prioridades**.

---

# 10. Interpretación del resultado

El resultado debe evitar interpretaciones binarias.

No se recomienda:

> "La organización obtuvo 3.7, por lo tanto está preparada."

Es preferible:

> "La organización presenta un nivel funcional general, pero existen brechas específicas que pueden limitar determinados casos de uso."

El análisis debe considerar:

```text
Score global
     +
Scores por dimensión
     +
Elementos críticos
     +
Contexto del negocio
     +
Casos de uso prioritarios
     =
Diagnóstico
```

---

# 11. Score global versus perfil de madurez

El score global puede ser útil para obtener una visión general, pero **no debe sustituir el análisis por dimensión**.

Por ejemplo:

| Dimensión  | Score |
| ---------- | ----: |
| Datos      |   4.2 |
| Skills     |   2.3 |
| Gobernanza |   3.8 |
| Tecnología |   4.1 |
| Estrategia |   4.0 |

El promedio podría parecer razonablemente alto.

Sin embargo, el resultado revela una posible brecha importante en **Skills**.

La interpretación correcta sería:

> La organización presenta buenas condiciones tecnológicas y estratégicas, pero la capacidad humana puede limitar la adopción efectiva.

Por eso:

> **El perfil es más informativo que un único número.**

---

# 12. Identificación de brechas

El assessment debe permitir identificar la diferencia entre:

**capacidad actual**

y

**capacidad requerida**.

La lógica puede representarse así:

```text
Capacidad requerida
        -
Capacidad actual
        =
Brecha
```

Pero la existencia de una brecha no determina automáticamente la solución.

Una brecha puede requerir:

* capacitación;
* rediseño de procesos;
* tecnología;
* datos;
* gobernanza;
* cambios organizacionales;
* liderazgo;
* combinación de intervenciones.

Esta distinción será fundamental en la siguiente etapa del framework.

---

# 13. Priorización de brechas

No todas las brechas tienen la misma importancia.

La priorización debe considerar factores como:

| Factor                     | Pregunta                                         |
| -------------------------- | ------------------------------------------------ |
| **Magnitud**               | ¿Qué tan grande es la brecha?                    |
| **Impacto**                | ¿Qué consecuencias produce?                      |
| **Urgencia**               | ¿Qué tan pronto debe abordarse?                  |
| **Relevancia estratégica** | ¿Está relacionada con una prioridad del negocio? |
| **Alcance**                | ¿A cuántas personas o procesos afecta?           |
| **Dependencias**           | ¿Bloquea otras capacidades?                      |
| **Factibilidad**           | ¿Puede abordarse razonablemente?                 |

Una brecha pequeña pero crítica puede tener mayor prioridad que una brecha grande pero de bajo impacto.

---

# 14. Análisis cruzado de dimensiones

Una de las principales ventajas de un assessment integral es poder observar relaciones entre dimensiones.

Ejemplo:

```text
Estrategia alta
        +
Tecnología alta
        +
Datos altos
        +
Skills bajos
        ↓
Capacidad de ejecución limitada
```

Otro escenario:

```text
Skills altos
        +
Tecnología alta
        +
Gobernanza baja
        ↓
Capacidad técnica sin controles suficientes
```

Otro:

```text
Estrategia alta
        +
Gobernanza alta
        +
Datos bajos
        ↓
Casos de uso estratégicamente definidos
pero difíciles de ejecutar
```

El valor del assessment está precisamente en identificar estas combinaciones.

---

# 15. Assessment integral

El assessment debe evitar evaluar cada dimensión como si existiera de manera independiente.

La preparación organizacional puede representarse como:

```text
                 ESTRATEGIA
                     │
          ┌──────────┼──────────┐
          │          │          │
        DATOS      SKILLS   GOBERNANZA
          │          │          │
          └──────────┼──────────┘
                     │
                TECNOLOGÍA
                     │
                     ↓
              AI ENABLEMENT
                     │
                     ↓
             RESULTADOS
```

La interpretación debe considerar las interdependencias.

---

# 16. De resultados a diagnóstico

El assessment produce datos.

El diagnóstico produce significado.

Esta diferencia es fundamental.

### Assessment

> "Skills = 2.4"

### Diagnóstico

> "La organización presenta capacidades iniciales en Skills. La principal brecha está relacionada con la capacidad de identificar oportunidades de uso de IA y evaluar críticamente sus resultados."

El segundo resultado es mucho más útil para diseñar una intervención.

Por eso:

> **El assessment es un instrumento de diagnóstico, no el diagnóstico completo.**

---

# 17. De diagnóstico a Training Needs Analysis

Los resultados del assessment alimentan directamente el **Training Needs Analysis (TNA)**.

La secuencia es:

```text
Datos del assessment
        ↓
Patrones
        ↓
Brechas
        ↓
Causas
        ↓
Capacidades requeridas
        ↓
Necesidades de aprendizaje
```

El TNA debe determinar posteriormente:

> ¿Qué necesitan las personas saber, hacer o demostrar para desempeñarse eficazmente en el nuevo contexto?

---

# 18. Diagnóstico de causa antes de capacitación

Una regla fundamental del framework es:

> **No convertir automáticamente una puntuación baja en una capacitación.**

Ejemplo:

| Resultado                       | Posible causa            | Respuesta             |
| ------------------------------- | ------------------------ | --------------------- |
| Baja capacidad para utilizar IA | Falta de conocimientos   | Aprendizaje           |
| Baja disponibilidad de datos    | Problema estructural     | Datos                 |
| Falta de herramientas           | Restricción tecnológica  | Tecnología            |
| Uso inconsistente               | Falta de estándares      | Gobernanza / proceso  |
| Falta de adopción               | Barrera de cambio        | Cambio / liderazgo    |
| Falta de casos de uso           | Brecha de identificación | Learning + estrategia |

Esto protege la calidad del TNA.

---

# 19. Uso del assessment antes del workshop

El assessment puede aplicarse como actividad previa al workshop.

Esto permite al facilitador llegar con una primera visión de:

* nivel de preparación;
* prioridades;
* brechas;
* diferencias entre grupos;
* temas que requieren mayor atención.

El workshop puede entonces dedicar menos tiempo a explicar conceptos generales y más tiempo a trabajar sobre **necesidades reales identificadas**.

---

# 20. Uso del assessment durante el workshop

Los resultados también pueden utilizarse como insumo para actividades.

Por ejemplo:

### Score bajo en Estrategia

Actividad:

> Identificación y priorización de casos de uso.

### Score bajo en Skills

Actividad:

> Análisis de tareas + práctica con IA.

### Score bajo en Gobernanza

Actividad:

> Análisis de escenarios y toma de decisiones.

### Score bajo en Datos

Actividad:

> Evaluación de calidad y disponibilidad de información.

### Score bajo en Tecnología

Actividad:

> Mapeo de herramientas, sistemas e integraciones.

De esta manera:

> **el assessment informa el diseño de la experiencia de aprendizaje.**

---

# 21. Uso del assessment después del workshop

La aplicación puede utilizarse nuevamente después de una intervención.

El objetivo no es simplemente demostrar que las personas "aprendieron".

Debe analizarse si hubo cambios en:

* conocimiento;
* confianza;
* capacidad percibida;
* prácticas;
* adopción;
* condiciones organizacionales.

Cuando se utilizan instrumentos comparables, es posible observar evolución entre:

**pre-assessment → intervención → post-assessment**

---

# 22. Exportación de resultados

La aplicación debe generar los resultados en formato **CSV** para permitir análisis posterior.

El archivo debe conservar la información necesaria para relacionar cada respuesta o resultado con el participante y el momento de evaluación.

Como mínimo, debe contemplar:

| Campo        | Descripción                          |
| ------------ | ------------------------------------ |
| `unique_id`  | Identificador único del participante |
| `name`       | Nombre                               |
| `company`    | Organización                         |
| `job_title`  | Cargo                                |
| `occupation` | Ocupación                            |
| `level`      | Nivel organizacional                 |
| `date`       | Fecha                                |
| `timestamp`  | Fecha y hora exactas                 |
| `dimension`  | Dimensión evaluada                   |
| `item_id`    | Identificador del elemento           |
| `response`   | Respuesta seleccionada               |
| `score`      | Puntuación obtenida                  |

El diseño final del CSV puede ampliarse según las necesidades analíticas del cliente.

---

# 23. El timestamp como elemento analítico

El timestamp no debe considerarse simplemente información administrativa.

Permite:

* diferenciar aplicaciones múltiples;
* identificar pre y post assessment;
* ordenar registros;
* analizar períodos;
* asociar resultados con intervenciones;
* realizar seguimiento longitudinal.

Por esta razón, debe registrarse automáticamente siempre que sea técnicamente posible.

---

# 24. Segmentación de resultados

Los datos pueden analizarse por:

* organización;
* ocupación;
* cargo;
* nivel;
* área;
* dimensión;
* período;
* grupo de aprendizaje.

Esto permite detectar patrones que quedarían ocultos en un promedio general.

Por ejemplo:

> La organización puede presentar un nivel adecuado de Skills en roles directivos, pero una brecha importante entre profesionales y personal operativo.

La intervención puede entonces diferenciarse por audiencia.

---

# 25. Principio de adaptación al cliente

El framework funciona como **arquitectura inicial**, no como instrumento inmutable.

La estructura debe mantenerse consistente, pero pueden adaptarse:

* terminología;
* ejemplos;
* roles;
* ocupaciones;
* casos de uso;
* ponderaciones;
* preguntas;
* criterios de interpretación;
* prioridades.

Esto permite utilizar una misma arquitectura metodológica con diferentes organizaciones.

### Principio:

> **Estandarizar la metodología; adaptar el contenido al contexto.**

---

# 26. Qué debe producir el assessment

El assessment debe generar cuatro niveles de información:

| Nivel              | Resultado                          |
| ------------------ | ---------------------------------- |
| **1. Datos**       | Respuestas individuales            |
| **2. Medición**    | Scores y niveles                   |
| **3. Diagnóstico** | Fortalezas y brechas               |
| **4. Acción**      | Prioridades para TNA y aprendizaje |

Por lo tanto:

```text
RESPUESTAS
    ↓
RESULTADOS
    ↓
DIAGNÓSTICO
    ↓
TRAINING NEEDS ANALYSIS
    ↓
ESTRATEGIA DE APRENDIZAJE
    ↓
PLAN DE ACCIÓN
```

Este flujo constituye la lógica central del framework.

---

# 27. Criterios de calidad metodológica

El assessment debe buscar ser:

### Claro

Las preguntas deben ser comprensibles y evitar lenguaje innecesariamente técnico.

### Relevante

Cada pregunta debe contribuir al objetivo de evaluar preparación para AI Enablement.

### Observable

Las preguntas deben orientarse hacia condiciones, comportamientos o capacidades identificables.

### Comparable

La estructura debe permitir comparar resultados entre personas, grupos y momentos.

### Accionable

Los resultados deben poder utilizarse para tomar decisiones.

### Integral

Las cinco dimensiones deben analizarse conjuntamente.

### Adaptable

El contenido debe poder contextualizarse para diferentes organizaciones.

### Medible

Los resultados deben poder convertirse en datos analizables.

---

# 28. Limitaciones que deben reconocerse

El assessment no sustituye:

* auditorías;
* evaluaciones técnicas;
* auditorías de seguridad;
* análisis jurídico;
* análisis detallado de datos;
* diagnóstico organizacional completo;
* entrevistas profundas;
* observación del trabajo.

Su función es proporcionar una **línea base estructurada** que permita determinar dónde profundizar.

Por eso:

> **El assessment indica dónde investigar; no pretende responder por sí solo todas las preguntas.**

---

# 29. Principio clave: medir para decidir

El objetivo final del instrumento no es producir un dashboard atractivo ni una puntuación general.

El objetivo es permitir mejores decisiones.

Cada resultado debería llevar a una pregunta:

> **¿Qué significa esto para nuestra capacidad de implementar AI Enablement?**

Y posteriormente:

> **¿Qué debemos hacer al respecto?**

Esta orientación permite que el assessment sea el primer componente de una estrategia de aprendizaje y transformación, y no un ejercicio aislado.

---

# 30. Idea clave para el workshop

💡 **El assessment es el punto de partida, no el punto final.**

Su propósito es convertir percepciones y condiciones organizacionales en información estructurada que permita identificar:

**dónde estamos → qué necesitamos → qué brechas existen → qué capacidades debemos desarrollar → qué intervención necesitamos → cómo mediremos el progreso.**

La arquitectura completa queda así:

```text
01 — DATOS
02 — SKILLS
03 — GOBERNANZA
04 — TECNOLOGÍA
05 — ESTRATEGIA
        ↓
06 — METODOLOGÍA DEL ASSESSMENT
        ↓
07 — TRAINING NEEDS ANALYSIS
        ↓
08 — ESTRATEGIA DE APRENDIZAJE
        ↓
09 — PLAN DE ACCIÓN
        ↓
     MEJORA CONTINUA
```

El assessment, por lo tanto, funciona como el **puente metodológico entre el estado actual de la organización y las decisiones concretas de AI Enablement**.

---

## Navegación

⬅️ [05 — Estrategia y alineación con el negocio](05-strategy-and-alignment.md)

➡️ [07 — Training Needs Analysis](07-training-needs-analysis.md)

[Volver al inicio del framework](README.md)
