# Implementación de pruebas unitarias y funcionales en un proyecto

El equipo de desarrollo necesita mejorar la calidad del código a través de la implementación de pruebas unitarias y funcionales automatizadas. El objetivo es asegurar que las funcionalidades del sistema se comporten como se espera y que los cambios en el código no introduzcan errores.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | pruebas unitarias y funcionales |
| **Nivel** | junior-l2 |
| **Tipo** | practical |
| **Tiempo estimado** | 3-4 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: JDK 17+, Maven 3.9+, IDE con soporte Java.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Ejecuta `mvn compile` en la raíz. Si no hay errores, estás listo.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Definición de pruebas unitarias

**Objetivo:** Identificar las funcionalidades del sistema que requieren pruebas unitarias y definir las pruebas correspondientes.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Analiza el sistema para identificar las funcionalidades críticas que deben ser probadas.
- Define las pruebas unitarias para cada funcionalidad identificada.

**Entregable:** Documento con las pruebas unitarias definidas.

<details>
<summary>Pistas de conocimiento</summary>

- Las pruebas unitarias deben aislar la funcionalidad que se está probando.
- Considera los diferentes escenarios y casos de prueba para cada funcionalidad.

</details>

### Fase 2: Implementación de pruebas unitarias

**Objetivo:** Implementar las pruebas unitarias definidas en la fase anterior.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Implementa las pruebas unitarias utilizando un enfoque de desarrollo dirigido por pruebas (TDD).
- Ejecuta las pruebas unitarias para verificar que las funcionalidades del sistema se comportan como se espera.

**Entregable:** Código con las pruebas unitarias implementadas.

<details>
<summary>Pistas de conocimiento</summary>

- Utiliza un enfoque de desarrollo dirigido por pruebas para implementar las pruebas unitarias.
- Verifica que las pruebas unitarias se ejecuten correctamente y que los resultados sean los esperados.

</details>

### Fase 3: Definición de pruebas funcionales

**Objetivo:** Identificar las funcionalidades del sistema que requieren pruebas funcionales y definir las pruebas correspondientes.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Analiza el sistema para identificar las funcionalidades que deben ser probadas a nivel de usuario.
- Define las pruebas funcionales para cada funcionalidad identificada.

**Entregable:** Documento con las pruebas funcionales definidas.

<details>
<summary>Pistas de conocimiento</summary>

- Las pruebas funcionales deben simular el comportamiento del usuario en el sistema.
- Considera los diferentes escenarios y casos de prueba para cada funcionalidad.

</details>

### Fase 4: Implementación de pruebas funcionales

**Objetivo:** Implementar las pruebas funcionales definidas en la fase anterior.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Implementa las pruebas funcionales utilizando un enfoque de desarrollo dirigido por pruebas (TDD).
- Ejecuta las pruebas funcionales para verificar que las funcionalidades del sistema se comportan como se espera desde la perspectiva del usuario.

**Entregable:** Código con las pruebas funcionales implementadas.

<details>
<summary>Pistas de conocimiento</summary>

- Utiliza un enfoque de desarrollo dirigido por pruebas para implementar las pruebas funcionales.
- Verifica que las pruebas funcionales se ejecuten correctamente y que los resultados sean los esperados desde la perspectiva del usuario.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué son las pruebas unitarias y funcionales?
- **paraQueSirve**: ¿Para qué sirven las pruebas unitarias y funcionales en un proyecto de desarrollo?
- **comoSeUsa**: ¿Cómo se implementan las pruebas unitarias y funcionales utilizando un enfoque de desarrollo dirigido por pruebas?
- **erroresComunes**: ¿Cuáles son los errores comunes al implementar pruebas unitarias y funcionales?

## Criterios de Evaluacion

- Definición de pruebas unitarias y funcionales.
- Implementación de pruebas unitarias y funcionales.
- Ejecución de pruebas unitarias y funcionales para verificar el comportamiento del sistema.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
