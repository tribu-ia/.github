# Lineamientos de Documentación - Investigación de Agentes IA

La siguiente guía establece un estándar para documentar el proceso de investigación, pruebas y hallazgos relacionados con diferentes agentes de IA dentro del repositorio `documentacion-investigacion-agentes-ia`. La idea es contar con una estructura base que pueda adaptarse a cada tipo de herramienta (framework, plataforma low/no-code, producto digital), permitiendo a futuros usuarios comprender rápidamente el potencial, las limitaciones y el modo de operación de cada agente.

## Estructura General de la Documentación

Todas las investigaciones deben incluir las secciones base, independientemente del tipo de agente. Posteriormente, se pueden agregar secciones específicas según la naturaleza de la herramienta.

### Secciones Base (Para Todos los Agentes)

1. **Introducción**  
   - Breve descripción del agente: ¿Qué es y para qué sirve?  
   - Enlace(s) a la documentación oficial o sitio del producto.  
   - Contexto del por qué se eligió este agente.

2. **Objetivos de la Investigación/Prueba**  
   - ¿Qué se esperaba aprender o validar con el agente?  
   - Alcance y metas específicas.

3. **Características Principales**  
   - Funcionalidades clave.  
   - Tipos de problemas que resuelve.  
   - Integraciones con otras herramientas o APIs.

4. **Requerimientos Previos**  
   - Lenguajes, librerías, cuentas o suscripciones.  
   - Conocimientos técnicos recomendados.

5. **Instalación / Configuración Inicial**  
   - Pasos a seguir (instrucciones claras, comando por comando).  
   - Variables de entorno, claves API, acceso a cuentas, etc.

6. **Ejemplos Prácticos / Casos de Uso**  
   - Caso simple reproducible con instrucciones claras.  
   - Fragmentos de código (si aplica), capturas de pantalla o diagramas.

7. **Ventajas y Limitaciones**  
   - Puntos fuertes (facilidad, rendimiento, escalabilidad, etc.).  
   - Puntos débiles (complejidad, limitaciones técnicas, costos, etc.).

8. **Lecciones Aprendidas y Mejores Prácticas**  
   - Sugerencias para usar la herramienta de manera más eficaz.  
   - Retos encontrados y cómo superarlos.

9. **Siguientes Pasos / Desarrollo Futuro**  
   - Ideas de extensión, nuevos casos de uso o posibles mejoras.

10. **Referencias y Recursos**  
    - Documentación oficial.  
    - Links a tutoriales externos, foros, comunidades.

---

## Lineamientos Específicos por Tipo de Agente

### 1. Frameworks (e.g. LangChain, Haystack, Rasa)

- **Instalación Detallada y Dependencias**: Indicar versiones, librerías y entornos recomendados.  
- **Arquitectura Interna**: Explicar componentes clave (cadenas, memorias, herramientas).  
- **Ejemplos de Código Reproducibles**: Un snippet mínimo para correr un agente básico.  
- **Integraciones con LLMs y Otros Servicios**: Explicar cómo conectarse a OpenAI, Llama2, etc.

### 2. Plataformas Low-Code / No-Code (e.g. Zapier con IA, Bubble)

- **Onboarding en la Plataforma**: Cómo crear una cuenta, activar el plugin/funcionalidad de IA.  
- **Flujos Visuales**: Incluir diagramas o capturas de pantalla de los flujos creados sin código.  
- **Limitaciones del Entorno Visual**: Indicar qué se puede hacer sin código y qué no.  
- **Ejemplo Práctico Paso a Paso**: Un flujo completo construido visualmente.

### 3. Productos Digitales con Agentes Internos (SaaS con agentes preconfigurados)

- **Onboarding y Modelos de Suscripción**: Indicar planes (Free, Pro, etc.) y cómo acceder a la funcionalidad de agentes.  
- **Configuración de la IA Interna**: ¿Se pueden ajustar prompts o parámetros del modelo?  
- **Pruebas de Funcionalidades Clave**: Ejemplos concretos (ej.: chatbot interno, análisis automatizado).  
- **Evaluación de la Usabilidad y UX**: Facilidad de uso para personas no técnicas.  
- **Modelo de Precios y Costos Asociados**.

---

## Estándares de Calidad y Formato

- **Claridad y Concisión**: Explicar con sencillez, evitar jerga innecesaria.  
- **Markdown y Estructura**: Utilizar subtítulos, listas, resaltados en **negrita** para mejorar la legibilidad.  
- **Ejemplos Reales**: Incluir ejemplos reales, reproducibles, no solo teóricos.  
- **Links Funcionales**: Revisar que todos los enlaces funcionen.  
- **Actualizaciones Periódicas**: Mantener la documentación actualizada si la herramienta o el proceso cambia.

---

## Resultado Esperado

Siguiendo estos lineamientos, la documentación resultante permitirá:

- Comprender rápidamente qué hace el agente y su potencial.  
- Reproducir las pruebas sin comenzar desde cero.  
- Identificar oportunidades, limitaciones y cómo encajar el agente en nuevos proyectos.  
- Crear una base de conocimiento colectiva y creciente sobre el ecosistema de agentes IA.

<!-- Links -->
[Ejemplo de Agent Directory]: https://docs.google.com/spreadsheets/d/1vW9ngNpA5UQQTlkCPvdfAoXY3p_Omfj_jZ_d6H1jKik/edit?gid=0
