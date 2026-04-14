# Prompts

## Prompt #0
Bajo la técnica de prompt engineering, si quiero realizar la primera fase de un proyecto donde se pide diseñar y documentar un sistema de software siguiendo las fases de investigación y análisis, casos de uso, modelado de datos, y diseño de alto nivel, contaba con lanzar varios prompts con distintos perfiles de experto en product management, software analyst y software architect. Es buena idea que primero dé el contexto de la empresa y luego pida punto por punto indicando el rol adecuado para cada subfase de la documentación?

## Prompt #1
Actúa como un Product Manager experto. Quiero realizar la primera fase de un proyecto donde se pide diseñar y documentar un sistema de software siguiendo las fases de investigación y análisis, casos de uso, modelado de datos, y diseño de alto nivel.

Contexto de Negocio:
- Idea de proyecto: Desarrollar el ATS (Applicant-Tracking System) del futuro. 
- Objetivos: Aumentar la eficiencia para los departamentos de HR, mejorar la colaboración en tiempo real entre reclutadores y managers, automatizaciones, asistencia de IA en diversas tareas..

Lo que necesito ahora:
- Resume el contexto y pregúntame si tienes dudas.
- Investiga cuáles pueden ser las claves del éxito.

### Iteración Prompt #1
Respondiendo a tus dudas:
1. Target de empresa: Ambos perfiles. Es decir, grandes corporaciones y startups. Podríamos hacer una fase previa de selección de target en base al numero de empleados.
2. Foco de la IA: Ambas cosas. Es decir, tener un copiloto que ayude al usuario en cualquier fase del ATS así como automatizaciones como la que sugieres.
3. Ecosistemas: Integración con herramientas externas para poder agilizar la incorporación de datos en el sistema
Una vez quede esto claro me dices y te indico el siguiente paso

## Prompt #2
Actúa como un Product Manager senior. Genera un PRD completo incluyendo:
- Descripción breve del software LTI
- valor añadido
- Ventajas competitivas
- Explicación de las funciones principales
- Añade un diagrama Lean Canvas para entender el modelo de negocio

## Prompt #3
Eres un analista de software experto. Describe los 3 casos de uso principales, con el diagrama asociado a cada uno

## Prompt #4
Eres un arquitecto de software experto. Define las entidades de modelo de datos esenciales en nuestro sistema. Dame algunos campos esenciales de cada una y cómo se relacionan.
Representa el modelo de datos mediante un diagrama que incluya entidades, atributos (nombre y tipo) y relaciones

## Prompt #5
Eres un arquitecto de software experto. Genera un diseño del sistema a alto nivel, tanto explicado como diagrama adjunto

## Prompt #6
Eres un arquitecto de software experto. Genera un diagrama de arquitectura C4 del Application Service

### Iteración Prompt #6
En el diagrama de componentes, al querer visualizarlo con mermaid.ai me da error en:
subgraph Application_Service [Microservicio: Application Service]

## Prompt #7
Quiero que generes un unico markdown para documentacion de todos los artefactos que hemos generado

### Iteración Prompt #7
Has hecho un resumen de todo, y me gustaria mantener toda la informacion en este unico markdown que te pedia. Si queda demasiado grande para procesarlo de una vez podemos partirlo en varios