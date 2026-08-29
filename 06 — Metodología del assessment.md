# 06 — Metodología del assessment

> **Fase 06 del AI Enablement Readiness Framework**
> **Propósito:** convertir la evaluación de las cinco dimensiones de preparación en evidencia estructurada para orientar el diagnóstico y las decisiones posteriores.

---

## 1. Propósito de esta fase

Las cinco dimensiones anteriores permiten observar diferentes condiciones relacionadas con la preparación para AI Enablement:

1. **Calidad y preparación de datos**
2. **Skills y talento**
3. **Gobernanza**
4. **Tecnología e infraestructura**
5. **Estrategia y alineación con el negocio**

La función de esta fase es explicar **cómo se recopila, estructura, puntúa e interpreta la información obtenida mediante el assessment**.

El assessment no debe entenderse como un examen.

Su propósito es generar una **línea base estructurada** que permita identificar:

* fortalezas;
* posibles brechas;
* patrones;
* diferencias entre grupos;
* prioridades de investigación;
* condiciones que pueden favorecer o limitar AI Enablement.

### Pregunta orientadora

> **¿Cómo convertimos las respuestas del assessment en evidencia útil para comprender el nivel de preparación y decidir qué debe investigarse a continuación?**

---

# 2. El assessment dentro del framework

El assessment ocupa una posición central entre las dimensiones de readiness y las fases posteriores de diagnóstico y acción.

```text
01 Datos
02 Skills y talento
03 Gobernanza
04 Tecnología e infraestructura
05 Estrategia y alineación
          ↓
       Assessment
          ↓
   Resultados estructurados
          ↓
      Interpretación
          ↓
      Investigación
          ↓
        TNA
          ↓
Estrategia de aprendizaje
          ↓
      Plan de acción
```

Esta secuencia evita saltar directamente desde una puntuación hacia una solución.

---

# 3. Principio metodológico: medir para investigar

El resultado del assessment debe considerarse una **señal diagnóstica**, no una explicación causal.

Por ejemplo:

> Una puntuación baja en Skills y talento indica una posible brecha de capacidad.

Pero todavía no responde:

* qué capacidad específica falta;
* quién presenta la brecha;
* qué nivel de desempeño se espera;
* por qué existe la diferencia;
* si la capacitación es la intervención apropiada.

Por eso:

```text
Resultado
   ↓
Señal
   ↓
Investigación
   ↓
Causa
   ↓
Diagnóstico
   ↓
Intervención
```

### Principio clave

> **El assessment identifica dónde mirar; el diagnóstico determina qué significa el resultado.**

---

# 4. Estructura del assessment

El assessment organiza las preguntas en función de las cinco dimensiones del framework.

| Dimensión                              | Código | Propósito                                       |
| -------------------------------------- | ------ | ----------------------------------------------- |
| Calidad y preparación de datos         | DATA   | Evaluar condiciones relacionadas con los datos  |
| Skills y talento                       | SKILL  | Evaluar capacidades humanas relacionadas con IA |
| Gobernanza                             | GOV    | Evaluar reglas, responsabilidades y controles   |
| Tecnología e infraestructura           | TECH   | Evaluar condiciones tecnológicas                |
| Estrategia y alineación con el negocio | STRAT  | Evaluar conexión con prioridades y resultados   |

Esta estructura permite analizar tanto cada dimensión individualmente como el conjunto.

---

# 5. Unidad de análisis

El assessment debe capturar información suficiente para contextualizar los resultados.

Como mínimo, el registro de evaluación debe permitir asociar los resultados con:

| Campo                    | Propósito                                                |
| ------------------------ | -------------------------------------------------------- |
| Nombre                   | Identificar a la persona participante cuando corresponda |
| Identificador único      | Distinguir registros de manera consistente               |
| Ocupación                | Relacionar resultados con el trabajo                     |
| Nivel                    | Diferenciar responsabilidades y niveles organizacionales |
| Organización             | Contextualizar el resultado                              |
| Fecha                    | Identificar el momento de la evaluación                  |
| Timestamp                | Registrar fecha y hora del registro                      |
| Resultados por dimensión | Analizar las cinco dimensiones                           |
| Resultado global         | Obtener una visión agregada de readiness                 |

Estos datos permiten realizar análisis posteriores y comparar resultados cuando el diseño del programa lo requiera.

---

# 6. Diseño de las preguntas

Las preguntas deben estar redactadas en lenguaje claro y orientadas a condiciones observables.

Deben evitar:

* terminología innecesariamente técnica;
* preguntas ambiguas;
* preguntas dobles;
* supuestos sobre conocimientos previos;
* formulaciones que sugieran la respuesta correcta.

### Principio

> **Una pregunta debe medir una condición que pueda interpretarse de manera consistente.**

---

# 7. Opciones de respuesta

Las opciones de respuesta deben representar niveles diferenciables de preparación.

Un ejemplo de lógica de madurez puede ser:

| Nivel | Interpretación                                        |
| ----- | ----------------------------------------------------- |
| 1     | No existe o es muy limitado                           |
| 2     | Existe de manera inicial o inconsistente              |
| 3     | Existe parcialmente y se aplica en algunos contextos  |
| 4     | Está establecido y se aplica de manera consistente    |
| 5     | Está integrado, gestionado y sujeto a mejora continua |

La escala concreta utilizada por la aplicación debe mantenerse consistente en todo el assessment.

### Importante

La escala representa **nivel de preparación**, no una calificación académica de la persona.

---

# 8. Scoring

Cada respuesta puede asociarse con un valor numérico para permitir el cálculo de resultados.

Por ejemplo:

```text
Respuesta
   ↓
Valor
   ↓
Criterio
   ↓
Dimensión
   ↓
Resultado agregado
```

El scoring debe mantenerse transparente y consistente.

Cuando se utilizan pesos diferentes, estos deben estar definidos previamente y documentados.

---

# 9. Pesos

No necesariamente todos los criterios tienen la misma importancia para todos los casos de uso.

El framework puede utilizar pesos para reflejar prioridades determinadas durante el diseño del assessment.

La lógica general es:

```text
Respuesta
   ×
Peso
   ↓
Puntuación del criterio
   ↓
Agregación
   ↓
Puntuación de dimensión
```

### Principio

> **Los pesos son una decisión metodológica; no deben introducirse arbitrariamente durante la interpretación de los resultados.**

Cuando el assessment se adapte para un cliente, los pesos pueden revisarse si existe una razón clara y documentada.

---

# 10. Resultado por dimensión

El resultado por dimensión permite observar dónde se concentran las fortalezas y posibles brechas.

Por ejemplo:

| Dimensión        | Resultado |
| ---------------- | --------: |
| Datos            |       3.8 |
| Skills y talento |       2.6 |
| Gobernanza       |       3.4 |
| Tecnología       |       4.1 |
| Estrategia       |       2.9 |

La utilidad principal no está en el número aislado.

Está en identificar **patrones que requieren interpretación**.

En este ejemplo, Skills podría requerir una investigación más profunda, pero todavía no puede concluirse qué capacitación debe diseñarse.

---

# 11. Resultado global

Puede calcularse un resultado agregado para proporcionar una visión general de readiness.

Sin embargo, el resultado global no debe ocultar las diferencias entre dimensiones.

```text
Resultado global
       ↓
Visión general
       +
Resultados por dimensión
       ↓
Análisis detallado
```

Una organización podría obtener un resultado global intermedio mientras presenta una limitación crítica en una dimensión específica.

Por eso, el resultado global debe utilizarse como **indicador complementario**, no como sustituto del análisis por dimensión.

---

# 12. Segmentación de resultados

Los resultados pueden analizarse por variables relevantes para el diagnóstico.

Entre ellas:

* ocupación;
* nivel;
* área;
* grupo;
* organización;
* caso de uso;
* dimensión.

Esto permite identificar patrones que pueden desaparecer cuando todos los participantes se agrupan en un único resultado.

### Ejemplo

```text
Resultado global
      ↓
Segmentación por ocupación
      ↓
Segmentación por nivel
      ↓
Identificación de patrones
      ↓
Investigación
```

---

# 13. Ocupación y nivel como variables estratégicas

El assessment debe conservar la relación entre resultados y trabajo.

La ocupación ayuda a responder:

> **¿Qué capacidades están relacionadas con este tipo de trabajo?**

El nivel ayuda a responder:

> **¿Qué nivel de responsabilidad tiene la persona respecto de esas capacidades?**

Por ejemplo, las capacidades requeridas por una persona usuaria pueden ser diferentes de las requeridas por un director que debe priorizar inversiones, supervisar riesgos o liderar cambios.

Por eso, el mismo resultado no necesariamente tiene el mismo significado para todos los roles.

---

# 14. Identificación de brechas

Una brecha surge cuando existe una diferencia relevante entre una condición actual y una condición requerida.

El assessment puede proporcionar evidencia sobre el **estado actual**.

El estado requerido debe definirse posteriormente en función de:

* rol;
* tarea;
* contexto;
* caso de uso;
* resultado esperado;
* nivel de responsabilidad.

La lógica es:

```text
Estado actual
      ↓
Estado requerido
      ↓
Diferencia
      ↓
Brecha
```

Esta distinción es fundamental para el TNA.

---

# 15. Del score a la causa

Una puntuación baja no explica por qué existe una condición.

Por ejemplo, un resultado bajo en Tecnología podría deberse a:

* falta de herramientas;
* falta de acceso;
* integración insuficiente;
* restricciones de seguridad;
* falta de soporte;
* falta de conocimiento del usuario.

Cada causa requiere una respuesta diferente.

Por eso:

> **La puntuación identifica una condición; la investigación identifica la causa.**

---

# 16. Del assessment al diagnóstico

La metodología debe utilizar una secuencia de análisis:

```text
1. Recopilar respuestas
        ↓
2. Calcular resultados
        ↓
3. Analizar dimensiones
        ↓
4. Identificar patrones
        ↓
5. Identificar posibles brechas
        ↓
6. Investigar causas
        ↓
7. Determinar necesidades
```

El resultado del assessment es, por tanto, un **punto de partida para el diagnóstico**, no el diagnóstico completo.

---

# 17. Validación cualitativa

Los resultados cuantitativos deben complementarse con información cualitativa cuando sea necesario.

Esto puede realizarse mediante:

* entrevistas;
* workshops;
* observación;
* revisión de tareas;
* análisis de workflows;
* conversaciones con líderes;
* revisión de casos de uso.

### ¿Por qué?

Porque un número puede mostrar **dónde existe una señal**, pero no necesariamente explicar **qué está ocurriendo en el trabajo real**.

---

# 18. Triangulación

La interpretación puede fortalecerse mediante la triangulación de diferentes tipos de evidencia.

```text
Assessment
    +
Perspectiva del participante
    +
Perspectiva del liderazgo
    +
Evidencia del trabajo
    +
Datos disponibles
    ↓
Diagnóstico más sólido
```

La triangulación reduce el riesgo de diseñar una intervención basándose exclusivamente en percepciones individuales.

---

# 19. Relación con Training Needs Analysis

El assessment y el TNA cumplen funciones diferentes.

| Assessment                       | TNA                                    |
| -------------------------------- | -------------------------------------- |
| Identifica condiciones           | Determina necesidades de aprendizaje   |
| Genera una línea base            | Define brechas de desempeño/capacidad  |
| Produce señales                  | Investiga causas                       |
| Compara resultados               | Define capacidades requeridas          |
| Identifica áreas para investigar | Determina si la formación es apropiada |

Por lo tanto:

> **Assessment ≠ TNA**

El assessment alimenta el TNA.

→ [07 — Training Needs Analysis](07-training-needs-analysis.md)

---

# 20. Relación con la estrategia de aprendizaje

Una vez que el TNA determina qué capacidades necesitan desarrollarse y para quién, los resultados pueden alimentar la estrategia de aprendizaje.

```text
Assessment
    ↓
Diagnóstico
    ↓
TNA
    ↓
Capacidades prioritarias
    ↓
Estrategia de aprendizaje
```

Esto permite que el aprendizaje responda a necesidades identificadas en lugar de comenzar con un catálogo genérico de contenidos.

→ [08 — Estrategia de aprendizaje](08-learning-strategy.md)

---

# 21. Uso del assessment para el workshop

El assessment puede utilizarse como actividad inicial del workshop para:

* establecer una línea base;
* activar la reflexión;
* identificar áreas prioritarias;
* facilitar conversaciones;
* contextualizar los contenidos;
* orientar actividades posteriores.

El resultado no debe utilizarse para etiquetar personas como "buenas" o "malas" en IA.

Su función es facilitar una conversación estructurada sobre **preparación y necesidades**.

---

# 22. Uso de resultados para diseño de actividades

Los resultados pueden orientar el diseño de actividades del workshop.

Por ejemplo:

| Señal identificada                   | Posible enfoque de actividad                    |
| ------------------------------------ | ----------------------------------------------- |
| Baja identificación de oportunidades | Análisis de tareas y casos de uso               |
| Baja capacidad de evaluación         | Ejercicios de revisión y validación de outputs  |
| Baja integración en workflows        | Rediseño de procesos                            |
| Baja comprensión de gobernanza       | Análisis de escenarios y decisiones             |
| Baja alineación estratégica          | Priorización de casos de uso                    |
| Baja preparación de datos            | Análisis de fuentes y requisitos de información |

Estas actividades deben definirse después de interpretar los resultados y confirmar las necesidades.

---

# 23. Resultados longitudinales

Cuando el assessment se aplica antes y después de una intervención, puede proporcionar información para comparar cambios.

Por ejemplo:

```text
Pre-assessment
      ↓
Intervención
      ↓
Post-assessment
      ↓
Comparación
      ↓
Evidencia de cambio
```

El registro de fecha y timestamp permite conservar la dimensión temporal del resultado.

Sin embargo, un cambio en la puntuación no debe interpretarse automáticamente como evidencia de transferencia al trabajo.

La evaluación de aplicación y desempeño requiere evidencia adicional.

---

# 24. Exportación de resultados

La aplicación debe permitir generar resultados en formato **CSV** para facilitar:

* análisis posterior;
* almacenamiento;
* segmentación;
* comparación;
* integración con otras herramientas;
* seguimiento de resultados.

El registro debe conservar, como mínimo, los campos definidos para la identificación y análisis del assessment, incluyendo:

* nombre;
* organización;
* ocupación;
* nivel;
* identificador único;
* fecha;
* timestamp;
* resultados por dimensión;
* resultado global.

La estructura exacta debe mantenerse consistente para facilitar el análisis posterior.

---

# 25. Principios de calidad metodológica

El assessment debe procurar:

### Claridad

Las preguntas deben ser comprensibles y evitar ambigüedad.

### Consistencia

Las mismas reglas de scoring deben aplicarse de manera uniforme.

### Relevancia

Cada pregunta debe contribuir a evaluar una condición relacionada con AI Enablement.

### Trazabilidad

Debe ser posible relacionar una puntuación con la dimensión y criterio que la generaron.

### Contextualización

Los resultados deben interpretarse considerando ocupación, nivel, caso de uso y contexto.

### Accionabilidad

Los resultados deben ayudar a determinar qué investigar y qué decisiones tomar posteriormente.

---

# 26. Lo que el assessment NO debe hacer

El assessment no debe:

* diagnosticar automáticamente competencias individuales;
* determinar automáticamente quién necesita capacitación;
* sustituir entrevistas o análisis de trabajo;
* convertirse en una prueba de conocimientos sobre herramientas;
* asumir que una puntuación baja tiene una única causa;
* recomendar cursos sin investigar la necesidad;
* utilizar el resultado global como única medida de readiness.

### Principio

> **El assessment es una herramienta de diagnóstico inicial, no un mecanismo automático de prescripción.**

---

# 27. Resultado esperado de esta fase

Al finalizar esta fase, la organización debería disponer de:

* una estructura consistente de evaluación;
* resultados por dimensión;
* una línea base;
* posibles brechas;
* patrones que requieren investigación;
* información segmentada;
* evidencia para orientar el TNA.

La salida de esta fase puede representarse así:

```text
Respuestas
    ↓
Scoring
    ↓
Resultados
    ↓
Patrones
    ↓
Posibles brechas
    ↓
Preguntas diagnósticas
```

---

# 28. El puente hacia la acción

Las cinco dimensiones responden:

> **¿Qué tan preparada está la organización?**

La metodología responde:

> **¿Cómo obtenemos e interpretamos esa evidencia?**

La siguiente fase responde:

> **¿Qué capacidades necesitan desarrollarse y por qué?**

Ese siguiente paso es:

**07 — Training Needs Analysis.**

---

## Navegación

⬅️ [05 — Estrategia y alineación con el negocio](05-strategy-and-business-alignment.md)

➡️ [07 — Training Needs Analysis](07-training-needs-analysis.md)

🏠 [Volver al README](README.md)
