# Elaboración de protocolos y buenas prácticas para códigos y datos abiertos

Diseño de protocolos, códigos y datos abiertos (<https://atc26.com/programa-dia2-conferencia1.html>).

**Duración:** 25 min + 5 min de preguntas/comentarios
Puede libremente decidir si quiere que las personas hagan preguntas en el proceso o al final.
**Día/Hora:** viernes 23/01 - 09:00 a 10:00

## ¿Qué se espera?

Esta conferencia aborda estrategias para el diseño de protocolos de investigación, organización de códigos y gestión de datos abiertos, proporcionando marcos conceptuales y herramientas prácticas para investigadores que buscan implementar estándares de transparencia y accesibilidad. Se discutirán principios FAIR (Findable, Accessible, Interoperable, Reusable) y mejores prácticas para la documentación y publicación de recursos de investigación. La idea es que pueda abordar estos aspectos desde su ámbito de trabajo/ investigación.

---

## Ideas para la conferencia

### 1. Apertura – El problema real (4–5 min)

### Diagnóstico honesto
- La apertura suele hacerse al final del proyecto, si acaso
- Protocolos implícitos o incompletos
- Código desorganizado, frágil o imposible de reutilizar
- Datos abiertos sin contexto ni documentación

#### Consecuencia
- Transparencia superficial
- Baja reutilización
- Dificultad para evaluar, replicar o extender resultados

**Mensaje clave:**  
FAIR falla más por mal diseño inicial que por falta de buena voluntad.

### 2. Protocolos abiertos = decisiones explícitas (6–7 min)

#### Qué es un protocolo
- No es solo un preregistro
- Es un contrato metodológico y cognitivo
- Define qué cuenta como dato, análisis y evidencia

#### Buen diseño de protocolos abiertos
- Separar decisiones teóricas de decisiones técnicas
- Documentar criterios de inclusión, exclusión y análisis
- Versionado del protocolo (los protocolos también evolucionan)
- Trazabilidad de cambios y justificaciones

#### Relación con FAIR
- Findable: el protocolo existe y se puede localizar
- Reusable: se entiende por qué se tomaron las decisiones

### 3. Código abierto ≠ subir scripts rotos (6–7 min)

#### Idea central
- El código es parte del método, no solo una herramienta técnica
- Código público sin estructura no garantiza transparencia

#### Buenas prácticas mínimas
- Un script = una tarea o función clara
- Separación entre:
  - datos crudos
  - datos procesados
  - análisis
- README que explique:
  - estructura del proyecto
  - dependencias
  - flujo de ejecución
- Automatización mínima para asegurar reproducibilidad

#### Punto clave
Un análisis que no se puede volver a correr no es reproducible, aunque el código sea público.

### 4. Datos abiertos: abrir sin dañar (5–6 min)

#### Problemas reales
- Privacidad y confidencialidad
- Consentimiento informado
- Poblaciones vulnerables
- Variables sensibles que no parecen sensibles

#### Buenas prácticas
- Metadatos y documentación antes que volumen de datos
- Diccionarios de variables claros
- Anonimización o datos sintéticos cuando sea necesario
- Acceso escalonado cuando abrir todo no es ético

#### Relación con FAIR
- Interoperable: formatos abiertos y estándares
- Reusable: contexto, licencias y limitaciones explícitas

### 5. Cierre – Una regla simple (2–3 min)

#### Propuesta
- Diseñar apertura pensando en el yo futuro
- Si el proyecto no se entiende sin explicación adicional, no está listo para ser abierto

#### Mensaje final
La ciencia abierta no es un paso administrativo final,  
es infraestructura intelectual diseñada desde el inicio.

### Espacio para preguntas (5 min)
