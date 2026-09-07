
<p align="center">
  <img src="./assets/images/shared/logo_upc.png" alt="Logo UPC" width="200"/>
</p>

<h1 align="center">Universidad Peruana de Ciencias Aplicadas</h1>
<h2 align="center">Carrera de Ingeniería de Software</h2>

<h3 align="center">1ACC0238</h3>

<h3 align="center">Aplicaciones para Dispositivos Móviles</h3>
<h3 align="center">NRC</h3>
<h3 align="center">4939</h3>

<h1 align="center">Informe de Trabajo Final</h1>

<h3 align="center">Docente</h3>
<h2 align="center">David Gerardo Quevedo Velasco</h2>

<h3 align="center">Equipo</h3>
<h2 align="center">Trakto</h2>

<h3 align="center">Proyecto</h3>
<h2 align="center">Trakto Route</h2>

<h2 align="center">Integrantes</h2>

<table align="center">
  <tr>
    <th>Código</th>
    <th>Apellidos y Nombres</th>
  </tr>
  <tr>
    <td>UXXXXXXXXXX</td>
    <td>Miembro 1</td>
  </tr>
  <tr>
    <td>UXXXXXXXXXX</td>
    <td>Miembro 2</td>
  </tr>
  <tr>
    <td>U202019498</td>
    <td>Fernandez Garfias, Alexander Piero</td>
  </tr>
  <tr>
    <td>UXXXXXXXXXX</td>
    <td>Miembro 4</td>
  </tr>
  <tr>
    <td>UXXXXXXXXXX</td>
    <td>Miembro 5</td>
  </tr>
</table>

<h3 align="center">Periodo 202620</h3>



<div style="page-break-after: always;"></div>

<h2 align="center">Registro de Versiones del Informe</h2>

| Versión | Fecha | Autor | Descripción de modificación |
|---|---|---|---|
| AV1 | [Fecha] | [Nombre del equipo] | Creación del informe. Inclusión de la presentación de la startup y del producto, Lean UX, análisis de competidores, entrevistas, Needfinding y Requirements Specification hasta Product Backlog. |

<div style="page-break-after: always;"></div>

<h2 align="center">Project Report Collaboration Insights</h2>

![Project Report Collaboration Insights AV1](./assets/images/shared/report_av1.png)

**AV1.** Para el primer avance, el equipo trabajó en la definición de la startup y de **Trakto**, el desarrollo del proceso Lean UX, el análisis competitivo, las entrevistas, los artefactos de Needfinding y la especificación inicial de requisitos. Las actividades fueron distribuidas entre los integrantes y consolidadas mediante herramientas colaborativas y control de versiones.

<div style="page-break-after: always;"></div>

## Contenido

- [Student Outcome](#student-outcome)
- [Capítulo I: Presentación](#capítulo-i-presentación)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2. Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)
    - [2.1. Competidores](#21-competidores)
        - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
        - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2. Entrevistas](#22-entrevistas)
        - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
        - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
        - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
    - [2.3. Needfinding](#23-needfinding)
        - [2.3.1. User Personas](#231-user-personas)
        - [2.3.2. User Task Matrix](#232-user-task-matrix)
        - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
        - [2.3.4. Empathy Mapping](#234-empathy-mapping)
        - [2.3.5. Big Picture EventStorming](#235-big-picture-eventstorming)
        - [2.3.6. Ubiquitous Language](#236-ubiquitous-language)
    - [2.4. Requirements Specification](#24-requirements-specification)
        - [2.4.1. User Stories](#241-user-stories)
        - [2.4.2. Impact Mapping](#242-impact-mapping)
        - [2.4.3. Product Backlog](#243-product-backlog)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
    - [Links](#links)

<div style="page-break-after: always;"></div>

# Student Outcome

[Completar con el Student Outcome indicado por el docente. Debe incluir las acciones específicas realizadas por cada integrante y las conclusiones grupales correspondientes al avance.]

<div style="page-break-after: always;"></div>

# Capítulo I: Presentación

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**Trakto** es una startup tecnológica orientada a mejorar la gestión de las operaciones de transporte de carga mediante soluciones móviles. La propuesta surge ante la necesidad de muchas empresas de mantener organizada y disponible la información relacionada con sus vehículos, conductores, rutas, viajes e incidencias.

La startup desarrolla **Trakto**, una aplicación móvil desarrollada con **Kotlin** que busca centralizar la consulta del estado de los viajes, las rutas registradas, las paradas, descansos, retrasos, problemas e incidencias reportadas durante una operación.

Asimismo, Trakto permite consultar el historial de conductores, vehículos y viajes. De esta manera, las empresas pueden analizar operaciones anteriores, evaluar el desempeño de sus recursos y tomar decisiones basadas en la información registrada.


### 1.1.2. Perfiles de integrantes del equipo

| Foto | Información |
|---|---|
| <img src="assets/images/shared/miembro1.png" width="400"/> | **Nombre:** Miembro 1<br><br>**Código:** UXXXXXXXXXX<br><br>**Carrera:** Ingeniería de Software<br><br>**Acerca de mí:** [Conocimientos técnicos, habilidades y aporte al equipo.] |
| <img src="assets/images/shared/miembro2.png" width="400"/> | **Nombre:** Miembro 2<br><br>**Código:** UXXXXXXXXXX<br><br>**Carrera:** Ingeniería de Software<br><br>**Acerca de mí:** [Conocimientos técnicos, habilidades y aporte al equipo.] |
| <img src="assets/images/shared/miembro3.png" width="400"/> | **Nombre:** Alexander Piero Fernandez Garfias<br><br>**Código:** U202019498<br><br>**Carrera:** Ingeniería de Software<br><br>**Acerca de mí:** Soy estudiante de Ingeniería de Software. Me interesa el desarrollo de aplicaciones móviles y la construcción de soluciones de software aplicando buenas prácticas de programación y diseño. |
| <img src="assets/images/shared/miembro4.png" width="400"/> | **Nombre:** Miembro 4<br><br>**Código:** UXXXXXXXXXX<br><br>**Carrera:** Ingeniería de Software<br><br>**Acerca de mí:** [Conocimientos técnicos, habilidades y aporte al equipo.] |
| <img src="assets/images/shared/miembro5.png" width="400"/> | **Nombre:** Miembro 5<br><br>**Código:** UXXXXXXXXXX<br><br>**Carrera:** Ingeniería de Software<br><br>**Acerca de mí:** [Conocimientos técnicos, habilidades y aporte al equipo.] |
<div style="page-break-after: always;"></div>

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

**Who (¿Quién?) - ¿A quiénes afecta el problema?**\
Empresas de transporte de carga y operadores logísticos que necesitan
supervisar sus vehículos, conductores y recorridos durante el traslado
de mercancías.

**What (¿Qué?) - ¿Cuál es el problema exactamente?**\
La falta de una aplicación móvil centralizada que permita realizar el
seguimiento de los vehículos mediante GPS, conocer el estado de los
recorridos, mantener comunicación con los conductores y registrar las
incidencias ocurridas durante cada viaje. Esto dificulta que las
empresas tengan una visión completa y actualizada de sus operaciones de
transporte.

**Where (¿Dónde?) - ¿En qué contexto ocurre?**\
En las operaciones de transporte terrestre de carga, principalmente
durante el desplazamiento de camiones entre los puntos de origen y
destino de las mercancías, con un enfoque inicial en empresas que operan
dentro del mercado peruano.

**When (¿Cuándo?) - ¿En qué momento se manifiesta el problema?**\
Durante el desarrollo de los viajes y recorridos de transporte,
especialmente cuando ocurren paradas no previstas, descansos, retrasos,
congestión vehicular, problemas en la ruta, accidentes u otras
incidencias que requieren una respuesta oportuna por parte de la
empresa.

**Why (¿Por qué?) - ¿Por qué ocurre el problema?**\
El problema surge debido a la falta de integración entre el seguimiento
de vehículos mediante GPS, la comunicación con los conductores y el
registro de las operaciones. Cuando esta información se encuentra
dispersa o no está disponible de manera oportuna, las empresas tienen
mayores dificultades para supervisar sus unidades y responder ante
situaciones inesperadas.

**How (¿Cómo?) - ¿Cómo impacta en el usuario?**\
La falta de visibilidad y comunicación dificulta conocer el estado real
de los vehículos y conductores, identificar retrasos, paradas o
incidencias y tomar decisiones oportunas. Además, limita la posibilidad
de consultar posteriormente lo ocurrido durante cada recorrido y evaluar
el desarrollo de las operaciones realizadas.

**How Much (¿Cuánto?) - ¿Qué tan grande es el problema?**\
El transporte de carga requiere un seguimiento constante de vehículos,
conductores y recorridos para garantizar el cumplimiento de las
operaciones. La ausencia de herramientas que centralicen esta
información puede generar menor capacidad de supervisión y respuesta
ante incidencias. En este contexto, existe una oportunidad para
soluciones como **Trakto**, que integren seguimiento mediante GPS,
comunicación, gestión de viajes y registro histórico de las operaciones
en una misma aplicación móvil.

<div style="page-break-after: always;"></div>

