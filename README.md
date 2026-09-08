
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

**Who (¿Quién?) - ¿A quiénes afecta el problema?**  
Empresas de transporte de carga y operadores logísticos que necesitan supervisar sus vehículos, conductores y rutas durante el traslado de mercancías.

**What (¿Qué?) - ¿Cuál es el problema exactamente?**  
La falta de una plataforma centralizada que permita monitorear en tiempo real la ubicación de los vehículos, conocer el estado de los recorridos, mantener comunicación con los conductores y registrar las incidencias ocurridas durante cada viaje. Esto dificulta que las empresas tengan una visión completa y actualizada de sus operaciones de transporte.

**Where (¿Dónde?) - ¿En qué contexto ocurre?**  
En las operaciones de transporte terrestre de carga, principalmente durante el desplazamiento de camiones entre los puntos de origen y destino de las mercancías, con un enfoque inicial en empresas que operan dentro del mercado peruano.

**When (¿Cuándo?) - ¿En qué momento se manifiesta el problema?**  
Durante el desarrollo de los viajes y recorridos de transporte, especialmente cuando ocurren paradas no previstas, retrasos, congestión vehicular, problemas en la ruta, accidentes u otras incidencias que requieren una respuesta oportuna por parte de la empresa.

**Why (¿Por qué?) - ¿Por qué ocurre el problema?**  
El problema surge debido a la falta de integración entre el seguimiento de vehículos, la comunicación con los conductores y el registro de las operaciones. Cuando esta información se encuentra dispersa o no está disponible en tiempo real, las empresas tienen mayores dificultades para supervisar sus unidades y responder ante situaciones inesperadas.

**How (¿Cómo?) - ¿Cómo impacta en el usuario?**  
La falta de visibilidad y comunicación dificulta conocer el estado real de los vehículos y conductores, identificar retrasos o incidencias y tomar decisiones oportunas. Además, limita la posibilidad de consultar posteriormente lo ocurrido durante cada recorrido y evaluar el desempeño de los recursos involucrados.

**How Much (¿Cuánto?) - ¿Qué tan grande es el problema?**  
El transporte de carga requiere un seguimiento constante de vehículos, conductores y recorridos para garantizar el cumplimiento de las operaciones. La ausencia de herramientas que centralicen esta información puede generar menor capacidad de supervisión y respuesta ante incidencias. En este contexto, existe una oportunidad para soluciones como **TrackTruck**, que integren geolocalización, comunicación y registro histórico de las operaciones en una misma plataforma.

<div style="page-break-after: always;"></div>


### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Problem statement:**

Actualmente, muchas empresas dedicadas al transporte de carga enfrentan dificultades para gestionar de manera centralizada la información relacionada con sus vehículos, conductores, rutas, viajes e incidencias. En muchos casos, esta información se encuentra distribuida entre llamadas, mensajes, registros manuales o diferentes herramientas, lo que dificulta conocer con rapidez el estado de una operación y mantener una adecuada trazabilidad de lo ocurrido durante cada recorrido.

Esta problemática afecta especialmente a empresas de transporte y operadores logísticos que necesitan consultar el estado de sus viajes, revisar las rutas realizadas, identificar paradas, descansos, retrasos, problemas o posibles accidentes, así como acceder posteriormente al historial de sus conductores y vehículos. La falta de centralización puede generar menor control operativo y mayores dificultades para evaluar el desempeño de los recursos utilizados en cada operación.

Trakto busca atender esta necesidad mediante una aplicación móvil desarrollada con Kotlin que centralice la gestión y consulta de viajes, rutas, vehículos, conductores, estados, incidencias e historial operativo. La solución estará orientada inicialmente a empresas de transporte de carga y operadores logísticos del mercado peruano, priorizando la facilidad de uso, el acceso rápido a la información y la trazabilidad de las operaciones para apoyar una mejor toma de decisiones.

<div style="page-break-after: always;"></div>



#### 1.2.2.2. Lean UX Assumptions

Lean UX Assumptions es una técnica que permite identificar las principales suposiciones relacionadas con el negocio, los usuarios y sus necesidades antes de desarrollar completamente una solución. Estas suposiciones permiten orientar las decisiones del equipo y posteriormente validarlas mediante investigación y retroalimentación de los usuarios, reduciendo el riesgo de desarrollar funcionalidades que no respondan a necesidades reales.

#### Business Outcomes

**Creemos que nuestros clientes necesitan:**
Nuestros clientes necesitan una aplicación móvil que les permita gestionar de manera centralizada la información relacionada con sus viajes, vehículos, conductores, rutas e incidencias, así como consultar el estado de las operaciones y revisar posteriormente el historial de los recorridos realizados.

**Estas necesidades se pueden resolver con:**
Estas necesidades se pueden resolver mediante Trakto, una aplicación móvil que centralice la gestión de viajes, rutas, vehículos y conductores, permita consultar el estado de las operaciones, registrar incidencias y mantener un historial de los eventos ocurridos durante cada recorrido.

**Nuestros clientes iniciales son (o serán):**
Nuestros clientes iniciales serán empresas de transporte de carga y operadores logísticos que administren vehículos, conductores y operaciones de transporte y que necesiten mejorar la organización, supervisión y trazabilidad de sus actividades.

**El valor #1 que un cliente quiere de nuestro servicio es:**
El principal valor que nuestros clientes buscan es tener mayor control y trazabilidad sobre sus operaciones de transporte mediante el acceso rápido y centralizado a la información de viajes, vehículos, conductores, rutas e incidencias.

**El cliente también puede obtener estos beneficios adicionales:**
Además de centralizar la información operativa, los clientes podrán consultar el historial de los viajes, revisar paradas, descansos, retrasos, problemas o accidentes registrados y evaluar el desempeño histórico de sus vehículos y conductores.

**Vamos a adquirir la mayoría de nuestros clientes a través de:**
Buscaremos adquirir clientes principalmente mediante estrategias de marketing digital dirigidas a empresas de transporte y logística, presencia en redes profesionales, contacto directo con organizaciones del sector y alianzas estratégicas relacionadas con el transporte de carga.

**Haremos dinero a través de:**
Generaremos ingresos mediante planes de suscripción dirigidos a empresas, considerando las funcionalidades disponibles y las necesidades de gestión de sus operaciones de transporte.

**Nuestra competencia principal en el mercado será:**
Nuestra competencia estará conformada por plataformas de gestión de flotas, aplicaciones de administración logística y otras soluciones digitales orientadas al control, organización y seguimiento de operaciones de transporte.

**Los venceremos debido a:**
Buscaremos diferenciarnos mediante una aplicación móvil enfocada en centralizar de manera sencilla la gestión de viajes, vehículos, conductores, rutas, incidencias e historial operativo, priorizando una experiencia clara, accesible y orientada a las tareas frecuentes de los responsables de transporte.

**Nuestro mayor riesgo de producto es:**
Nuestro principal riesgo es que las empresas no perciban suficiente valor diferencial frente a otras soluciones de gestión de flotas o frente a las herramientas que actualmente utilizan para organizar sus operaciones.

**Resolveremos esto a través de:**
Buscaremos reducir este riesgo mediante la validación continua con representantes de los segmentos objetivo, el análisis de sus necesidades reales y la priorización de funcionalidades que aporten valor directo a la gestión y trazabilidad de las operaciones.

<div style="page-break-after: always;"></div>



#### User Outcomes

**¿Quién será nuestro usuario?**
Nuestros usuarios serán principalmente supervisores de transporte, responsables de operaciones, gestores de flotas y coordinadores logísticos encargados de administrar viajes, vehículos, conductores y rutas.

**¿Dónde encaja nuestro producto en su vida?**
Trakto formará parte de la gestión cotidiana de las operaciones de transporte, permitiendo a los usuarios consultar desde una aplicación móvil la información relacionada con viajes, conductores, vehículos, rutas, estados e incidencias.

**¿Qué problemas tiene nuestro usuario y cómo se pueden resolver?**
Los usuarios pueden tener dificultades para encontrar rápidamente información sobre una operación, consultar antecedentes de conductores y vehículos, identificar retrasos o incidencias y revisar lo ocurrido durante viajes anteriores. Trakto busca resolver estas necesidades centralizando esta información dentro de una única aplicación móvil.

**¿Cómo y cuándo es usado nuestro producto?**
Trakto será utilizado antes, durante y después de las operaciones de transporte. Antes de un viaje, los usuarios podrán revisar la información del vehículo, conductor y ruta asignados. Durante la operación podrán consultar su estado y los eventos registrados. Después del viaje podrán revisar el historial y analizar lo ocurrido durante el recorrido.

**¿Qué problemas puede tener nuestro producto?**
Algunos problemas potenciales incluyen dependencia de una conexión a Internet para sincronizar información, datos desactualizados si no se registran correctamente los eventos, dificultades de adopción por parte de algunos usuarios y errores en el ingreso manual de información.

**¿Qué características son importantes?**
Las características principales de Trakto incluyen gestión y consulta de viajes, vehículos, conductores y rutas; consulta del estado de las operaciones; registro de paradas, descansos, retrasos, problemas e incidencias; historial de viajes; e historial de vehículos y conductores.

<div style="page-break-after: always;"></div>



#### 1.2.2.3. Lean UX Hypothesis Statements

**Hypothesis Statement 1:**  
Creemos que centralizar la información de viajes, vehículos, conductores y rutas en una aplicación móvil permitirá a los responsables de operaciones gestionar de manera más eficiente sus actividades de transporte.
Sabremos que esto es cierto cuando los usuarios puedan consultar la información necesaria de una operación sin depender de múltiples registros, mensajes o herramientas externas.


**Hypothesis Statement 2:**  
Creemos que permitir la consulta del estado de los viajes y el registro de paradas, descansos, retrasos, problemas e incidencias facilitará la comprensión de lo ocurrido durante una operación de transporte.
Sabremos que esto es cierto cuando los usuarios puedan identificar los principales eventos registrados durante un viaje y utilizar esta información para tomar decisiones sobre la operación.


**Hypothesis Statement 3:**  
Creemos que disponer de un historial centralizado de viajes permitirá a las empresas contar con una mayor trazabilidad de sus operaciones de transporte.
Sabremos que esto es cierto cuando los usuarios puedan consultar operaciones anteriores y encontrar fácilmente información sobre las rutas, vehículos, conductores y eventos registrados durante cada viaje.


**Hypothesis Statement 4:**  
Creemos que mantener un historial de conductores y vehículos permitirá a los responsables de operaciones evaluar mejor el desempeño de los recursos utilizados durante el transporte.
Sabremos que esto es cierto cuando los usuarios puedan revisar los viajes e incidencias asociados a cada conductor o vehículo y utilizar esta información como apoyo para sus decisiones.


**Hypothesis Statement 5:**  
Creemos que centralizar la gestión, consulta y registro de las operaciones en Trakto facilitará el trabajo de supervisores y coordinadores logísticos.
Sabremos que esto es cierto cuando los usuarios puedan realizar las principales tareas relacionadas con la consulta de viajes, rutas, vehículos, conductores, incidencias e historial desde una sola aplicación móvil y con menor dependencia de herramientas externas.


<div style="page-break-after: always;"></div>



#### 1.2.2.4. Lean UX Canvas

El **Lean UX Canvas** de Trakto fue elaborado en **Miro**, considerando la problemática, los supuestos, las hipótesis y los segmentos objetivo definidos durante el proceso Lean UX.

![Lean UX Canvas](./assets/images/chapter1/lean_ux_canvas.png)

<div style="page-break-after: always;"></div>

#### 1.2.3. Segmentos objetivo

### Segmento 1: Empresas de transporte de carga

Este segmento está conformado por empresas dedicadas al transporte terrestre de mercancías que administran vehículos, conductores, rutas y viajes. Estas organizaciones necesitan mantener organizada la información de sus operaciones, consultar el estado de los viajes e identificar paradas, descansos, retrasos, problemas, accidentes u otras incidencias que puedan presentarse durante los recorridos.

**Trakto** busca atender estas necesidades mediante una aplicación móvil que centralice la gestión y consulta de viajes, vehículos, conductores, rutas e incidencias. Asimismo, permite mantener un historial de las operaciones realizadas, facilitando la revisión de viajes anteriores y la evaluación del desempeño de los vehículos y conductores.

**Segmento Objetivo: Empresas de transporte de carga**

| Característica | Descripción |
|---|---|
| Tipo de cliente | Empresa (B2B) |
| Sector | Transporte terrestre de carga |
| Ubicación | Perú |
| Usuarios principales | Gestores de flota, supervisores y responsables de operaciones |
| Recursos gestionados | Camiones, conductores, rutas y viajes |
| Necesidad principal | Gestionar y mantener la trazabilidad de las operaciones de transporte |
| Funcionalidades de mayor valor | Gestión de viajes, consulta de rutas y estados, registro de incidencias e historial de vehículos, conductores y operaciones |

### Segmento 2: Operadores y empresas de logística

Este segmento comprende operadores y empresas de logística encargados de coordinar actividades relacionadas con el traslado de mercancías. Debido a que pueden gestionar múltiples vehículos, conductores, rutas y operaciones, necesitan acceder de manera rápida y organizada a la información relacionada con cada viaje y mantener un registro de los eventos ocurridos durante su desarrollo.

Para este segmento, **Trakto** permite centralizar la información de las operaciones y consultar el estado de los viajes, las rutas asignadas y los eventos registrados, como paradas, descansos, retrasos, problemas o incidencias. Además, el historial de viajes, vehículos y conductores permite revisar operaciones anteriores y disponer de información que apoye la toma de decisiones.

**Segmento Objetivo: Operadores y empresas de logística**

| Característica | Descripción |
|---|---|
| Tipo de cliente | Empresa (B2B) |
| Sector | Logística y gestión del transporte |
| Ubicación | Perú |
| Usuarios principales | Operadores logísticos, coordinadores y responsables de operaciones |
| Recursos gestionados | Vehículos, conductores, rutas y operaciones de transporte |
| Necesidad principal | Centralizar la información y mantener la trazabilidad de las operaciones de transporte |
| Funcionalidades de mayor valor | Consulta de viajes y rutas, estados de operaciones, registro de eventos e incidencias e historial operativo |

<div style="page-break-after: always;"></div>


# Capítulo II: Requirements Elicitation & Analysis

# 2.1. Competidores

Para comprender el entorno competitivo de **Trakto**, se analizaron soluciones relacionadas con la gestión de flotas, administración de operaciones logísticas y gestión del transporte de carga. Este análisis permite identificar las principales funcionalidades ofrecidas actualmente en el mercado, así como sus fortalezas y diferencias frente a nuestra propuesta.

Para el análisis competitivo se han considerado competidores directos e indirectos que ofrecen funcionalidades relacionadas con la gestión de vehículos, conductores, rutas, viajes, incidencias e historial de operaciones.

### Fleet Complete

**Tipo de competidor: Directo**

Fleet Complete es una plataforma orientada a la gestión de flotas que permite a las empresas administrar vehículos y conductores, además de disponer de información relacionada con sus operaciones. Sus soluciones incluyen herramientas orientadas al control de flotas, conductores, mantenimiento y análisis del desempeño operativo.

Representa un competidor para Trakto debido a sus capacidades para gestionar vehículos y conductores dentro de las operaciones empresariales. Sin embargo, Trakto busca concentrar su propuesta en una aplicación móvil orientada a centralizar de manera sencilla la información de viajes, rutas, vehículos, conductores, estados, incidencias e historial operativo.

### Samsara

**Tipo de competidor: Directo**

Samsara ofrece soluciones orientadas a la gestión de flotas y operaciones físicas. Su plataforma permite administrar información relacionada con vehículos, conductores, seguridad, mantenimiento y desempeño de las operaciones, proporcionando a las organizaciones herramientas para mejorar el control de sus recursos.

Se considera un competidor directo debido a que comparte funcionalidades relacionadas con la administración de vehículos, conductores y operaciones de transporte. Trakto busca diferenciarse mediante una propuesta móvil enfocada específicamente en facilitar la gestión de viajes, rutas, incidencias e historial de operaciones para empresas de transporte de carga y operadores logísticos.

### Tookan

**Tipo de competidor: Indirecto**

Tookan es una plataforma orientada principalmente a la gestión de entregas y operaciones de campo. Permite administrar conductores o agentes, asignar tareas, organizar rutas y gestionar diferentes actividades relacionadas con las operaciones de distribución.

Se considera un competidor indirecto debido a que comparte funcionalidades relacionadas con la gestión de conductores, rutas y operaciones, aunque su enfoque está principalmente orientado a entregas y servicios de última milla. En contraste, Trakto se enfoca en la gestión y trazabilidad de operaciones de transporte de carga, incluyendo viajes, vehículos, conductores, rutas, eventos e historial operativo.

<div style="page-break-after: always;"></div>


### 2.1.1. Análisis competitivo

| | **Trakto** | **Fleet Complete** | **Samsara** | **Tookan** |
|---|---|---|---|---|
| **Perfil** | | | | |
| Overview | Aplicación móvil orientada a la gestión de operaciones de transporte de carga que permite centralizar información sobre viajes, vehículos, conductores y rutas, consultar el estado de las operaciones, registrar incidencias y revisar el historial de viajes y recursos utilizados. | Plataforma orientada a la gestión de flotas que ofrece herramientas para administrar vehículos, conductores, mantenimiento y diferentes aspectos relacionados con el desempeño de las operaciones. | Plataforma tecnológica orientada a la gestión de flotas y operaciones físicas que ofrece herramientas relacionadas con vehículos, conductores, seguridad, mantenimiento y análisis operativo. | Plataforma orientada a la gestión de entregas y operaciones de campo que permite administrar conductores, asignar tareas, organizar rutas y gestionar operaciones de distribución. |
| Ventaja competitiva | Centralización de viajes, vehículos, conductores, rutas, incidencias e historial operativo mediante una aplicación móvil enfocada en empresas de transporte de carga y operadores logísticos. | Amplia variedad de herramientas para administrar flotas, vehículos y conductores dentro de las operaciones empresariales. | Ecosistema amplio de herramientas para la gestión de flotas, seguridad, conductores, mantenimiento y análisis de operaciones. | Facilidad para administrar entregas, asignar tareas y coordinar conductores mediante una plataforma orientada a operaciones de distribución. |
| **Perfil de Marketing** | | | | |
| Mercado objetivo | Empresas de transporte de carga y operadores logísticos que necesitan gestionar viajes, vehículos, conductores, rutas e incidencias. | Empresas que administran flotas de vehículos y requieren herramientas para gestionar sus unidades y conductores. | Empresas que administran flotas y operaciones físicas y requieren herramientas para mejorar la gestión, seguridad y eficiencia de sus recursos. | Empresas de delivery, logística, comercio electrónico y organizaciones que gestionan entregas u operaciones de campo. |
| Estrategias de marketing | Marketing digital B2B, contacto directo con empresas de transporte y logística, presencia en redes profesionales y alianzas estratégicas con organizaciones relacionadas con el sector. | Posicionamiento basado en eficiencia operativa, gestión de flotas y optimización de vehículos y conductores. | Posicionamiento empresarial basado en seguridad, eficiencia, digitalización y administración integral de operaciones físicas. | Posicionamiento basado en facilidad de uso, automatización de operaciones, optimización de entregas y flexibilidad para diferentes tipos de empresas. |
| **Perfil de Producto** | | | | |
| Productos & Servicios | Gestión y consulta de viajes, vehículos, conductores y rutas; consulta del estado de las operaciones; registro de paradas, descansos, retrasos e incidencias; historial de viajes; e historial de vehículos y conductores. | Gestión de flotas, vehículos y conductores, mantenimiento y herramientas relacionadas con el análisis del desempeño operativo. | Gestión de flotas, conductores, seguridad, mantenimiento, análisis operativo y herramientas para administrar diferentes aspectos de las operaciones físicas. | Planificación de rutas, asignación de tareas, gestión de conductores, administración de entregas y reportes relacionados con las operaciones. |
| Precios & Costos | Modelo de suscripción empresarial. Precios por definir según el alcance y las funcionalidades ofrecidas. | Precios variables según la solución, cantidad de vehículos y servicios contratados. | Precios empresariales variables según los productos, servicios y características contratadas por la organización. | Planes de suscripción según las funcionalidades y necesidades de las operaciones gestionadas. |
| Canales de distribución | Aplicación móvil desarrollada con Kotlin para dispositivos Android. | Web y móvil. | Web y móvil. | Web y móvil. |
| **Análisis SWOT** | | | | |
| Fortalezas | Aplicación móvil enfocada en transporte de carga; centralización de viajes, vehículos, conductores, rutas e incidencias; historial de operaciones; propuesta enfocada en facilitar las tareas frecuentes de supervisores y coordinadores logísticos. | Amplia variedad de herramientas para la gestión de flotas, vehículos y conductores y experiencia en soluciones empresariales. | Plataforma consolidada con un amplio conjunto de herramientas para la administración de flotas y operaciones físicas. | Facilidad de uso, flexibilidad para diferentes operaciones y herramientas especializadas en planificación, asignación y gestión de entregas. |
| Debilidades | Producto nuevo sin una base de clientes consolidada; menor cantidad de funcionalidades avanzadas frente a plataformas internacionales; dependencia del correcto registro y actualización de la información operativa. | La cantidad de funcionalidades disponibles puede incrementar la complejidad de adopción para empresas que requieren una solución más sencilla. | Su amplio conjunto de soluciones puede resultar más complejo de adoptar para pequeñas empresas que únicamente necesitan funcionalidades específicas de gestión de transporte. | Su enfoque principal en entregas y operaciones de última milla puede limitar su adaptación a determinadas operaciones de transporte de carga. |
| Oportunidades | Digitalización de las empresas de transporte de carga; necesidad de centralizar información operativa; crecimiento del uso de dispositivos móviles en procesos empresariales; posibilidad de atender empresas peruanas que buscan una solución sencilla para organizar viajes, vehículos, conductores e incidencias. | Crecimiento de la digitalización de flotas y mayor demanda de herramientas para la gestión de vehículos y conductores. | Mayor digitalización de las operaciones empresariales y crecimiento de la demanda de herramientas para administrar flotas y recursos físicos. | Crecimiento del comercio electrónico, delivery y operaciones de última milla que requieren herramientas digitales de coordinación y gestión. |
| Amenazas | Competencia de plataformas internacionales consolidadas; aparición de nuevas aplicaciones de gestión de transporte; resistencia de algunas empresas a cambiar sus procesos actuales; posibilidad de que competidores incorporen funcionalidades similares. | Competencia de soluciones de gestión de flotas más económicas y aparición de nuevas tecnologías para la administración vehicular. | Competencia de otras plataformas empresariales de gestión de flotas y evolución constante de las tecnologías utilizadas en el sector. | Competencia de plataformas más especializadas y completas para gestión de flotas y transporte de carga. |

<div style="page-break-after: always;"></div>



# 2.1.2. Estrategias y tácticas frente a competidores

En esta sección se presentan las principales estrategias y tácticas que **Trakto** aplicará para competir dentro del mercado de soluciones de gestión de flotas y operaciones de transporte de carga. Estas acciones buscan fortalecer la propuesta de valor de la aplicación, diferenciarla de otras alternativas y responder a las necesidades de empresas de transporte y operadores logísticos.

## Estrategias

**Diferenciación del producto:**  
Trakto buscará diferenciarse mediante una aplicación móvil que centralice, en un solo entorno, funcionalidades orientadas a la gestión de viajes, vehículos, conductores, rutas, estados, incidencias e historial de operaciones. La propuesta estará enfocada en facilitar el acceso a la información operativa sin depender de múltiples herramientas o registros separados.

**Enfoque en la trazabilidad de las operaciones:**  
Se priorizará el registro y almacenamiento de información relacionada con viajes, conductores, vehículos, rutas, paradas, descansos, retrasos e incidencias. Esto permitirá que las empresas puedan consultar posteriormente lo ocurrido durante cada operación y mantener un historial organizado de sus actividades de transporte.

**Experiencia de usuario accesible:**  
Trakto buscará ofrecer una interfaz móvil clara, intuitiva y fácil de utilizar, de manera que supervisores, gestores de flota y coordinadores logísticos puedan consultar rápidamente la información relevante de sus operaciones sin requerir conocimientos técnicos avanzados.

**Adaptación a las necesidades de las empresas:**  
La aplicación evolucionará considerando las necesidades identificadas en empresas de transporte de carga y operadores logísticos, priorizando aquellas funcionalidades que aporten mayor valor a la organización, gestión y trazabilidad de sus operaciones.

**Enfoque en la movilidad:**  
Trakto priorizará el acceso a la información desde dispositivos móviles, permitiendo que los responsables de las operaciones puedan consultar viajes, conductores, vehículos, rutas e incidencias desde una aplicación Android desarrollada específicamente para este propósito.

## Tácticas

**Implementación de retroalimentación de usuarios:**  
Se recopilarán y analizarán comentarios de supervisores, gestores de flota, coordinadores y operadores logísticos para identificar problemas de uso, nuevas necesidades y oportunidades de mejora. Esta información permitirá priorizar funcionalidades que generen mayor valor para los usuarios de Trakto.

**Monitoreo de la competencia:**  
Se realizará un seguimiento periódico de plataformas como Fleet Complete, Samsara y Tookan para identificar nuevas funcionalidades, cambios en sus propuestas de valor y tendencias relacionadas con la gestión de flotas y operaciones de transporte.

**Marketing digital B2B:**  
Se desarrollarán acciones de marketing digital dirigidas específicamente a empresas de transporte de carga y operadores logísticos, utilizando contenido relacionado con gestión de viajes, trazabilidad de operaciones, organización de flotas, incidencias e historial operativo para dar a conocer la propuesta de valor de Trakto.

**Contacto y demostraciones con empresas:**  
Se buscará establecer contacto directo con empresas del sector transporte y logística para presentar el funcionamiento de Trakto mediante demostraciones de la aplicación. Esto permitirá mostrar de manera práctica cómo la solución puede facilitar la consulta y organización de viajes, vehículos, conductores, rutas e incidencias.

**Validación mediante pruebas con usuarios:**  
Se realizarán pruebas con representantes de los segmentos objetivo para evaluar la facilidad de uso de la aplicación, la comprensión de sus funcionalidades y la utilidad de la información presentada. Los resultados obtenidos servirán para identificar oportunidades de mejora antes de incorporar nuevas funcionalidades.

**Mejora continua de la aplicación:**  
Se realizarán iteraciones constantes sobre Trakto a partir de los resultados obtenidos durante las pruebas con usuarios, entrevistas y análisis del mercado, con el objetivo de mantener una solución competitiva y alineada con las necesidades del sector de transporte y logística.

<div style="page-break-after: always;"></div>


# 2.2. Entrevistas

## 2.2.1. Diseño de entrevistas

Las entrevistas tienen como objetivo conocer las necesidades, dificultades y procesos actuales de los segmentos objetivo de **Trakto** en relación con la gestión de viajes, vehículos, conductores, rutas e incidencias dentro de las operaciones de transporte. Asimismo, buscan identificar las herramientas que utilizan actualmente, la manera en que registran y consultan la información de sus operaciones y las dificultades que enfrentan para mantener la trazabilidad de los viajes.

La información obtenida permitirá validar las principales suposiciones planteadas durante el proceso Lean UX y determinar qué funcionalidades de Trakto generan mayor valor para los usuarios.

### Segmento objetivo 1: Empresas de transporte de carga

1. ¿Cuánto tiempo lleva su empresa realizando operaciones de transporte de carga?
2. ¿Cuántos vehículos y conductores aproximadamente gestionan actualmente?
3. ¿Cómo organizan y consultan actualmente la información de los viajes que realiza su empresa?
4. ¿Qué herramientas o tecnologías utilizan para gestionar la información de sus vehículos, conductores, rutas y viajes?
5. ¿Cuáles son los principales problemas que enfrentan al gestionar sus operaciones de transporte?
6. ¿Cómo registran actualmente paradas, descansos, retrasos, problemas, accidentes u otras incidencias que ocurren durante un viaje?
7. ¿Cómo consultan el estado de un viaje cuando necesitan conocer cómo se está desarrollando una operación?
8. ¿Qué procedimiento siguen cuando ocurre una incidencia o problema durante una operación de transporte?
9. ¿Mantienen algún registro o historial de los viajes, rutas e incidencias ocurridas? ¿Cómo gestionan actualmente esta información?
10. ¿Qué información consideran más importante consultar sobre un viaje para gestionar adecuadamente una operación?
11. ¿Qué dificultades encuentran al administrar información relacionada con vehículos, conductores, rutas y viajes?
12. ¿Qué tan útil sería para su empresa contar con una aplicación móvil que centralice la información de viajes, vehículos, conductores, rutas e incidencias?
13. ¿Qué funcionalidades consideraría indispensables en una aplicación móvil para la gestión de operaciones de transporte de carga?
14. ¿Qué factores tomaría en cuenta su empresa antes de adoptar una aplicación como Trakto?

### Segmento objetivo 2: Operadores y empresas de logística

1. ¿Qué tipo de operaciones logísticas y de transporte gestiona actualmente su empresa?
2. ¿Con qué frecuencia necesitan consultar o gestionar información sobre vehículos, conductores, rutas o viajes?
3. ¿Cómo organizan actualmente la información relacionada con sus operaciones de transporte?
4. ¿Qué herramientas o sistemas utilizan para gestionar la información de viajes, vehículos, conductores y rutas?
5. ¿Cuáles son las principales dificultades que encuentran al gestionar múltiples operaciones de transporte?
6. ¿Cómo registran actualmente paradas, descansos, retrasos, problemas, accidentes u otras incidencias que puedan afectar un viaje?
7. ¿Cómo consultan el estado de una operación cuando necesitan conocer lo ocurrido durante un viaje?
8. ¿Qué información necesitan conocer para determinar si una operación de transporte se está desarrollando correctamente?
9. ¿Cómo registran y consultan actualmente la información de rutas, viajes e incidencias de operaciones anteriores?
10. ¿Qué dificultades tienen para mantener la trazabilidad de una operación desde su inicio hasta su finalización?
11. ¿Qué tan importante es para sus operaciones disponer de información organizada sobre viajes, vehículos, conductores, rutas e incidencias?
12. ¿Qué tan útil sería contar con una aplicación móvil que permita centralizar y consultar esta información?
13. ¿Qué funcionalidades esperaría encontrar en una aplicación como Trakto?
14. ¿Qué aspectos relacionados con facilidad de uso, acceso a la información y organización de las operaciones consideraría importantes para utilizar este tipo de aplicación?

<div style="page-break-after: always;"></div>

### 2.2.2. Registro de entrevistas

En esta sección se presenta el registro de las entrevistas realizadas a los usuarios pertenecientes a los segmentos objetivo de **Trakto**. Para cada entrevista se registrarán los datos del entrevistado, la evidencia visual, el enlace al video, el timing correspondiente y un resumen de las principales respuestas obtenidas.

---

## Segmento objetivo 1: Empresas de transporte de carga

### Entrevista 1

**Responsable de la entrevista:** Miembro X

| Campo | Detalle |
|---|---|
| Nombres y apellidos | Por completar |
| Edad | Por completar |
| Distrito | Por completar |
| Segmento objetivo | Empresas de transporte de carga |
| Cargo / función | Por completar |
| Empresa | Por completar |
| Fecha de entrevista | Por completar |
| Duración | Por completar |
| Timing en el video | Por completar |
| URL del video | [Ver video](URL_POR_COMPLETAR) |

<p align="center">
  <img src="assets/images/chapter2/entrevista-segmento1-1.png" width="700">
</p>

**Resumen:**  
Por completar. Describir las principales respuestas proporcionadas por el entrevistado, considerando cómo gestiona actualmente sus viajes, vehículos, conductores y rutas, qué herramientas utiliza, cuáles son sus principales dificultades, cómo registra las incidencias y qué funcionalidades considera importantes para una aplicación móvil como Trakto.

---

### Entrevista 2

**Responsable de la entrevista:** Miembro X

| Campo | Detalle |
|---|---|
| Nombres y apellidos | Por completar |
| Edad | Por completar |
| Distrito | Por completar |
| Segmento objetivo | Empresas de transporte de carga |
| Cargo / función | Por completar |
| Empresa | Por completar |
| Fecha de entrevista | Por completar |
| Duración | Por completar |
| Timing en el video | Por completar |
| URL del video | [Ver video](URL_POR_COMPLETAR) |

<p align="center">
  <img src="assets/images/chapter2/entrevista-segmento1-2.png" width="700">
</p>

**Resumen:**  
Por completar. Describir las necesidades y dificultades identificadas en relación con la gestión de viajes, vehículos, conductores, rutas, estados e incidencias, así como las herramientas utilizadas actualmente por el entrevistado.

---

### Entrevista 3

**Responsable de la entrevista:** Miembro X

| Campo | Detalle |
|---|---|
| Nombres y apellidos | Por completar |
| Edad | Por completar |
| Distrito | Por completar |
| Segmento objetivo | Empresas de transporte de carga |
| Cargo / función | Por completar |
| Empresa | Por completar |
| Fecha de entrevista | Por completar |
| Duración | Por completar |
| Timing en el video | Por completar |
| URL del video | [Ver video](URL_POR_COMPLETAR) |

<p align="center">
  <img src="assets/images/chapter2/entrevista-segmento1-3.png" width="700">
</p>

**Resumen:**  
Por completar. Identificar los principales problemas del entrevistado relacionados con la organización de la información operativa, consulta del estado de los viajes, registro de incidencias e historial de las operaciones.

---

## Segmento objetivo 2: Operadores y empresas de logística

### Entrevista 4

**Responsable de la entrevista:** Miembro X

| Campo | Detalle |
|---|---|
| Nombres y apellidos | Por completar |
| Edad | Por completar |
| Distrito | Por completar |
| Segmento objetivo | Operadores y empresas de logística |
| Cargo / función | Por completar |
| Empresa | Por completar |
| Fecha de entrevista | Por completar |
| Duración | Por completar |
| Timing en el video | Por completar |
| URL del video | [Ver video](URL_POR_COMPLETAR) |

<p align="center">
  <img src="assets/images/chapter2/entrevista-segmento2-1.png" width="700">
</p>

**Resumen:**  
Por completar. Describir las principales respuestas proporcionadas por el entrevistado, considerando cómo gestiona actualmente sus operaciones de transporte, qué información necesita consultar, cómo registra retrasos o incidencias y qué funcionalidades esperaría encontrar en Trakto.

---

### Entrevista 5

**Responsable de la entrevista:** Miembro X

| Campo | Detalle |
|---|---|
| Nombres y apellidos | Por completar |
| Edad | Por completar |
| Distrito | Por completar |
| Segmento objetivo | Operadores y empresas de logística |
| Cargo / función | Por completar |
| Empresa | Por completar |
| Fecha de entrevista | Por completar |
| Duración | Por completar |
| Timing en el video | Por completar |
| URL del video | [Ver video](URL_POR_COMPLETAR) |

<p align="center">
  <img src="assets/images/chapter2/entrevista-segmento2-2.png" width="700">
</p>

**Resumen:**  
Por completar. Describir las dificultades identificadas al gestionar diferentes viajes, vehículos, conductores y rutas, así como la forma en que el entrevistado mantiene actualmente la trazabilidad de sus operaciones.

---

### Entrevista 6

**Responsable de la entrevista:** Miembro X

| Campo | Detalle |
|---|---|
| Nombres y apellidos | Por completar |
| Edad | Por completar |
| Distrito | Por completar |
| Segmento objetivo | Operadores y empresas de logística |
| Cargo / función | Por completar |
| Empresa | Por completar |
| Fecha de entrevista | Por completar |
| Duración | Por completar |
| Timing en el video | Por completar |
| URL del video | [Ver video](URL_POR_COMPLETAR) |

<p align="center">
  <img src="assets/images/chapter2/entrevista-segmento2-3.png" width="700">
</p>

**Resumen:**  
Por completar. Identificar las principales necesidades del entrevistado respecto a la centralización de información, gestión de viajes, consulta de rutas, registro de incidencias e historial de operaciones.

<div style="page-break-after: always;"></div>

### 2.2.3. Análisis de entrevistas

Se realizaron **seis entrevistas**, distribuidas en **tres participantes por cada segmento objetivo**. A partir de sus respuestas se analizarán las principales necesidades, dificultades y expectativas relacionadas con la gestión de operaciones de transporte.

### Segmento objetivo 1: Empresas de transporte de carga

A partir de las tres entrevistas realizadas, se analizarán las principales dificultades relacionadas con la gestión de viajes, vehículos, conductores, rutas e incidencias.

| **Aspecto analizado** | **Cantidad** | **Porcentaje** |
|---|---:|---:|
| Utilizan varias herramientas para gestionar sus operaciones | Por completar | Por completar |
| Presentan dificultades para consultar el estado de los viajes | Por completar | Por completar |
| Consideran importante registrar incidencias | Por completar | Por completar |
| Necesitan consultar operaciones anteriores | Por completar | Por completar |
| Consideran útil centralizar la información | Por completar | Por completar |
| Muestran interés en utilizar una aplicación móvil | Por completar | Por completar |

**Conclusión del segmento:**  
Por completar después de analizar las tres entrevistas.

### Segmento objetivo 2: Operadores y empresas de logística

A partir de las tres entrevistas realizadas, se analizarán las dificultades relacionadas con la organización de múltiples operaciones, consulta de información, incidencias e historial de viajes.

| **Aspecto analizado** | **Cantidad** | **Porcentaje** |
|---|---:|---:|
| Gestionan múltiples operaciones de transporte | Por completar | Por completar |
| Presentan dificultades para centralizar la información | Por completar | Por completar |
| Consideran importante registrar incidencias | Por completar | Por completar |
| Necesitan consultar operaciones anteriores | Por completar | Por completar |
| Consideran importante mantener la trazabilidad | Por completar | Por completar |
| Muestran interés en utilizar una aplicación móvil | Por completar | Por completar |

**Conclusión del segmento:**  
Por completar después de analizar las tres entrevistas.

> **Referencia para los porcentajes:** 1 de 3 = 33.3%, 2 de 3 = 66.7%, 3 de 3 = 100%.

<div style="page-break-after: always;"></div>

## 2.3. Needfinding

### 2.3.1. User Personas

Las siguientes fichas de **User Persona** fueron elaboradas en **UXPressia** a partir del análisis de los segmentos objetivo de Trakto, considerando las necesidades, comportamientos, objetivos y dificultades identificadas durante el proceso de entrevistas. Cada ficha representa un arquetipo de usuario que permite comprender mejor el contexto en el que se desarrollan las operaciones de transporte y las necesidades que Trakto busca atender.

Para el primer segmento, correspondiente a **empresas de transporte de carga**, se identificó un perfil relacionado con la gestión y supervisión de las operaciones de transporte, cuyo principal objetivo es mantener organizada la información de los viajes, vehículos, conductores y rutas. Este usuario necesita consultar el estado de los viajes, registrar incidencias y acceder al historial de las operaciones para mantener una adecuada trazabilidad de las actividades realizadas.

Para el segundo segmento, correspondiente a **operadores y empresas de logística**, se identificó un perfil orientado a la coordinación y gestión de múltiples operaciones de transporte. Este usuario valora especialmente el acceso rápido a información organizada, la posibilidad de consultar los eventos registrados durante los viajes y la centralización de información sobre vehículos, conductores, rutas e incidencias para facilitar la gestión y toma de decisiones.

**1. Primer segmento: Empresas de transporte de carga**

![User Persona - Empresas de transporte de carga](assets/images/chapter2/user-persona1.png)

**2. Segundo segmento: Operadores y empresas de logística**

![User Persona - Operadores y empresas de logística](assets/images/chapter2/user-persona2.png)

<div style="page-break-after: always;"></div>

## 2.3.2. User Task Matrix

El **User Task Matrix** permite identificar y comparar las principales tareas que realizan los User Personas de los segmentos objetivo de Trakto para alcanzar sus objetivos dentro de las operaciones de transporte.

Para este análisis se consideran dos User Personas. **Carlos Mendoza** representa al segmento de empresas de transporte de carga y desempeña funciones relacionadas con la gestión y supervisión de vehículos, conductores y viajes. Por otro lado, **Andrea Salazar** representa al segmento de operadores y empresas de logística y se encarga principalmente de coordinar y gestionar diferentes operaciones de transporte.

Las tareas presentadas corresponden a actividades propias de cada usuario dentro de su contexto de trabajo, independientemente de la existencia de Trakto.

| **User Task** | **Carlos Mendoza** | | **Andrea Salazar** | |
|---|---|---|---|---|
| | **Frecuencia** | **Importancia** | **Frecuencia** | **Importancia** |
| Revisar los viajes programados y en curso | Siempre | Alta | Siempre | Alta |
| Verificar la información de los vehículos asignados | Siempre | Alta | A veces | Media |
| Verificar la información de los conductores asignados | Siempre | Alta | A veces | Media |
| Revisar las rutas asignadas a los viajes | Siempre | Alta | Siempre | Alta |
| Consultar el estado de las operaciones de transporte | Siempre | Alta | Siempre | Alta |
| Identificar paradas, descansos, retrasos o problemas durante un viaje | Siempre | Alta | Siempre | Alta |
| Registrar y revisar incidencias ocurridas durante las operaciones | A veces | Alta | A veces | Alta |
| Coordinar diferentes operaciones de transporte simultáneamente | A veces | Media | Siempre | Alta |
| Registrar información relacionada con los viajes realizados | Siempre | Media | Siempre | Media |
| Consultar información de viajes y operaciones anteriores | A veces | Media | A veces | Media |
| Revisar antecedentes relacionados con vehículos y conductores | A veces | Media | A veces | Media |
| Evaluar el cumplimiento de una operación al finalizar el viaje | Siempre | Alta | Siempre | Alta |

### Análisis de la User Task Matrix

La matriz evidencia que ambos User Personas comparten como tareas de **alta importancia** la revisión de los viajes, la consulta del estado de las operaciones, la verificación de las rutas asignadas, la identificación de retrasos o incidencias y la evaluación del cumplimiento de las operaciones. Esto demuestra que ambos segmentos necesitan disponer de información organizada que les permita conocer lo ocurrido durante los viajes y mantener la trazabilidad de sus actividades.

En el caso de **Carlos Mendoza**, debido a su rol como supervisor de flota, destacan con mayor frecuencia las tareas relacionadas con la revisión de vehículos y conductores, la consulta del estado de los viajes y la verificación de los recursos asignados a cada operación.

Por otro lado, **Andrea Salazar**, como coordinadora de operaciones logísticas, realiza con mayor frecuencia tareas relacionadas con la coordinación simultánea de diferentes operaciones, la revisión de rutas y la consulta del estado general de los viajes bajo su responsabilidad.

La principal coincidencia entre ambos perfiles se encuentra en la necesidad de **consultar el estado de las operaciones, identificar incidencias y mantener información organizada sobre los viajes realizados**. La principal diferencia radica en que el primer User Persona presenta un enfoque más orientado al **control de vehículos, conductores y viajes**, mientras que el segundo tiene un enfoque relacionado con la **coordinación y gestión general de múltiples operaciones logísticas**.

<div style="page-break-after: always;"></div>


### 2.3.3. User Journey Mapping

En esta sección se presentan los **User Journey Maps elaborados en UXPressia** correspondientes a cada uno de los User Personas identificados para los segmentos objetivo de Trakto. Estos diagramas permiten representar de manera secuencial las actividades que realizan actualmente los usuarios durante una operación de transporte, desde la preparación del viaje hasta su finalización.

Para este análisis se elaboraron las versiones **As-Is** de los User Journey Maps, por lo que se representa la situación actual de los usuarios **sin considerar la existencia de Trakto como solución**. El objetivo es identificar las acciones realizadas durante el proceso, así como los pensamientos, emociones, dificultades y oportunidades que aparecen en cada etapa.

Cada User Journey Map se encuentra vinculado con el User Persona correspondiente. **Carlos Mendoza** representa al segmento de empresas de transporte de carga, mientras que **Andrea Salazar** representa al segmento de operadores y empresas de logística.

#### 1. As-Is User Journey Map – Carlos Mendoza

El primer User Journey Map corresponde a **Carlos Mendoza**, supervisor de flota y representante del segmento de **empresas de transporte de carga**.

El journey representa el proceso actual que realiza Carlos para preparar y supervisar una operación de transporte. El recorrido comienza con la preparación del viaje y la verificación de los recursos necesarios, continúa con el inicio y seguimiento de la operación, contempla la gestión de posibles incidencias y finaliza con la revisión y registro de la información correspondiente al viaje realizado.

Durante este proceso, Carlos necesita consultar información sobre vehículos, conductores y rutas, verificar el estado de las operaciones, identificar retrasos o problemas y mantener registros que posteriormente le permitan revisar lo ocurrido durante cada viaje.

Las principales etapas consideradas en su As-Is User Journey Map son:

1. **Preparación del viaje:** revisa la información del viaje, la ruta, el vehículo y el conductor asignado.
2. **Inicio del viaje:** verifica que la operación haya comenzado de acuerdo con lo planificado y registra la información correspondiente al inicio.
3. **Seguimiento de la operación:** consulta el estado del viaje y obtiene información sobre su desarrollo mediante los medios disponibles actualmente.
4. **Gestión de incidencias:** identifica retrasos, paradas, problemas o accidentes y coordina las acciones necesarias para responder ante la situación.
5. **Finalización del viaje:** verifica la culminación de la operación, registra la información correspondiente y revisa lo ocurrido durante el recorrido.

A lo largo de estas etapas se identifican dificultades relacionadas con la **información distribuida entre diferentes medios, la necesidad de consultar constantemente el estado de las operaciones y la dificultad para mantener un historial organizado de viajes, vehículos, conductores e incidencias**.

![As-Is User Journey Map - Carlos Mendoza](assets/images/chapter2/user-journey-map-carlos.png)

<div style="page-break-after: always;"></div>



#### 2. As-Is User Journey Map – Andrea Salazar

El segundo User Journey Map corresponde a **Andrea Salazar**, coordinadora de operaciones y representante del segmento de **operadores y empresas de logística**.

El journey representa el proceso actual que realiza Andrea para coordinar diferentes operaciones de transporte. El recorrido comienza con la planificación y revisión de la información necesaria para cada operación, continúa con el inicio y seguimiento de los viajes, contempla la coordinación frente a retrasos o incidencias y finaliza con la revisión de los resultados y registros de las operaciones realizadas.

Durante este proceso, Andrea necesita organizar información relacionada con diferentes viajes, revisar las rutas y recursos asignados, consultar el estado de las operaciones y coordinar acciones cuando se presentan situaciones que puedan afectar su desarrollo.

Las principales etapas consideradas en su As-Is User Journey Map son:

1. **Preparación de las operaciones:** revisa los viajes programados, las rutas y los recursos asignados a cada operación.
2. **Inicio de las operaciones:** verifica el inicio de los viajes programados y organiza la información necesaria para su coordinación.
3. **Seguimiento de las operaciones:** consulta el estado de diferentes viajes y revisa la información disponible para conocer cómo se están desarrollando.
4. **Gestión de incidencias:** identifica retrasos, problemas o incidencias y coordina las acciones necesarias con las personas involucradas.
5. **Cierre y revisión:** verifica la finalización de las operaciones, revisa la información registrada y consulta los resultados de los viajes realizados.

A lo largo de estas etapas se identifican dificultades relacionadas con la **gestión simultánea de diferentes operaciones, la información distribuida entre distintos medios, la dificultad para consultar rápidamente el estado de los viajes y la falta de registros centralizados para revisar operaciones anteriores**.

![As-Is User Journey Map - Andrea Salazar](assets/images/chapter2/user-journey-map-andrea.png)

Los User Journey Maps permiten identificar similitudes y diferencias entre ambos perfiles. Mientras **Carlos Mendoza** presenta un mayor enfoque en la supervisión de vehículos, conductores y viajes individuales, **Andrea Salazar** necesita coordinar simultáneamente diferentes operaciones y mantener organizada la información necesaria para su gestión.

En ambos casos, el journey evidencia oportunidades relacionadas con la **centralización de la información, organización de los registros, trazabilidad de los viajes y acceso eficiente al historial de las operaciones**. Estas oportunidades servirán posteriormente como insumo para definir y priorizar las funcionalidades de la solución.

<div style="page-break-after: always;"></div>



### 2.3.4. Empathy Mapping

En esta sección se presentan los **Empathy Maps elaborados en UXPressia** para cada uno de los User Personas identificados en los segmentos objetivo de Trakto. Estos mapas permiten comprender con mayor profundidad las necesidades, comportamientos, pensamientos, preocupaciones y expectativas de los usuarios dentro de su contexto actual de trabajo.

Para su elaboración, se tomó como referencia la información obtenida durante las entrevistas y el análisis realizado previamente. Cada Empathy Map se encuentra vinculado con su respectivo User Persona y organiza los principales hallazgos relacionados con lo que el usuario necesita hacer, dice, ve, hace, escucha, piensa y siente. Asimismo, se identifican sus principales **Pains** y **Gains**, permitiendo comprender las dificultades que enfrenta actualmente y los resultados que espera alcanzar.

Al igual que los User Journey Maps As-Is, los Empathy Maps representan la **situación actual de los usuarios sin considerar a Trakto como solución**, permitiendo identificar posteriormente oportunidades de mejora a partir de problemas y necesidades reales.

#### 1. Empathy Map del primer segmento: Empresas de transporte de carga

El primer Empathy Map corresponde a **Carlos Mendoza**, supervisor de flota y representante del segmento de **empresas de transporte de carga**. Este perfil necesita gestionar información relacionada con los viajes, vehículos, conductores y rutas de la empresa, además de consultar el estado de las operaciones y atender las incidencias que puedan presentarse durante su desarrollo.

En su trabajo cotidiano, Carlos necesita revisar los viajes programados, verificar los vehículos y conductores asignados, consultar las rutas, conocer el estado de las operaciones y revisar los eventos ocurridos durante los recorridos. Para realizar estas actividades puede depender de diferentes registros, mensajes, llamadas u otras herramientas utilizadas por la empresa.

Entre sus principales preocupaciones se encuentran la dificultad para encontrar rápidamente información sobre una operación, la existencia de datos distribuidos entre diferentes medios, los posibles errores en los registros y la dificultad para consultar posteriormente lo ocurrido durante viajes anteriores.

Sus principales **Pains** están relacionados con la información dispersa, el tiempo necesario para consultar diferentes fuentes, la dificultad para mantener registros organizados y la necesidad de obtener información suficiente cuando ocurre un retraso, problema o incidencia.

Como principales **Gains**, Carlos busca disponer de información organizada y accesible, mantener una mayor trazabilidad de los viajes, facilitar la revisión de incidencias y contar con registros que le permitan evaluar posteriormente las operaciones, los vehículos y los conductores.

![Empathy Map - Carlos Mendoza](assets/images/chapter2/empathy-map1.png)

#### 2. Empathy Map del segundo segmento: Operadores y empresas de logística

El segundo Empathy Map corresponde a **Andrea Salazar**, coordinadora de operaciones y representante del segmento de **operadores y empresas de logística**. Este perfil necesita coordinar diferentes operaciones de transporte, organizar la información de los viajes, revisar las rutas asignadas y conocer el estado de las actividades bajo su responsabilidad.

En su trabajo cotidiano, Andrea debe gestionar información correspondiente a diferentes operaciones, coordinar recursos, revisar el desarrollo de los viajes e identificar retrasos, problemas o incidencias que puedan afectar el cumplimiento de las actividades planificadas.

Entre sus principales preocupaciones se encuentran la dificultad para gestionar simultáneamente diferentes operaciones, la información distribuida entre distintos medios, el tiempo requerido para encontrar datos específicos y la necesidad de mantener registros que permitan revisar posteriormente lo ocurrido durante cada viaje.

Sus principales **Pains** están relacionados con la dificultad para centralizar la información, la necesidad de consultar diferentes fuentes, la gestión simultánea de múltiples operaciones y la falta de registros organizados que faciliten la trazabilidad de los viajes.

Como principales **Gains**, Andrea busca disponer de información organizada sobre las operaciones, facilitar la consulta de viajes y rutas, mantener registros de incidencias y contar con información histórica que facilite la coordinación y la toma de decisiones.

![Empathy Map - Andrea Salazar](assets/images/chapter2/empathy-map2.png)

Los Empathy Maps permiten identificar que ambos perfiles comparten necesidades relacionadas con la **organización de la información, trazabilidad de las operaciones, consulta de incidencias y acceso a registros históricos**. Sin embargo, Carlos presenta un mayor enfoque en la gestión de vehículos, conductores y viajes individuales, mientras que Andrea requiere principalmente coordinar y organizar información correspondiente a múltiples operaciones de transporte.

Estos hallazgos complementan los resultados obtenidos mediante los User Personas, User Task Matrix y User Journey Maps, y permiten identificar oportunidades que posteriormente podrán ser consideradas durante la definición de las funcionalidades de Trakto.

<div style="page-break-after: always;"></div>



### 2.3.5. Big Picture EventStorming

En esta sección se presenta el resultado del **Big Picture EventStorming elaborado en Miro** con el objetivo de explorar y comprender el dominio de negocio de **Trakto** a alto nivel. Durante la sesión, el equipo identificó y organizó cronológicamente los principales **Domain Events**, actores y procesos relacionados con la gestión de las operaciones de transporte.

A partir del análisis colaborativo se identificaron seis **Bounded Contexts** principales: **IAM, Profile, Trip Management, Fleet Management, Incident Management y Operational History**. Cada contexto agrupa eventos y conceptos relacionados con una responsabilidad específica del dominio, permitiendo establecer una primera separación siguiendo los principios de **Domain-Driven Design**.

El contexto **IAM (Identity and Access Management)** gestiona los eventos relacionados con la autenticación, autorización y acceso de los usuarios. **Profile** administra la información asociada al perfil de cada usuario. **Trip Management** concentra el ciclo de vida de los viajes, incluyendo rutas, estados, paradas y descansos. **Fleet Management** administra los vehículos y conductores involucrados en las operaciones. **Incident Management** gestiona los retrasos, problemas, accidentes e incidencias ocurridas durante los viajes. Finalmente, **Operational History** mantiene el historial de viajes, vehículos y conductores, permitiendo conservar la trazabilidad de las operaciones realizadas.

Durante la sesión también se identificaron **Hot Spots** relacionados con los cambios de estado de los viajes, la disponibilidad de vehículos y conductores, los tipos de incidencias y las condiciones bajo las cuales una operación puede continuar o finalizar. Estos puntos representan aspectos del dominio que requieren un análisis posterior con mayor nivel de detalle.

A continuación, se presenta una captura del **Big Picture EventStorming de Trakto elaborado en Miro** durante la sesión.

![Big Picture EventStorming - Trakto](assets/images/chapter2/big-picture-eventstorming.png)

<div style="page-break-after: always;"></div>



### 2.3.6. Ubiquitous Language

El siguiente glosario reúne los principales términos y conceptos utilizados dentro del dominio de negocio de **Trakto**, relacionados con la gestión de operaciones de transporte de carga. Su objetivo es establecer un lenguaje común, claro y sin ambigüedades entre los miembros del equipo y stakeholders del proyecto.

Los términos se presentan en inglés junto con su equivalente en español y corresponden exclusivamente a conceptos del dominio del negocio identificados durante el proceso de análisis y Big Picture EventStorming.

| **Term** | **Definition** |
|---|---|
| **Trip (Viaje)** | Operación de transporte realizada desde un punto de origen hasta un destino determinado, utilizando un vehículo, un conductor y una ruta asignada. |
| **Trip Status (Estado del viaje)** | Condición en la que se encuentra un viaje durante su ciclo de vida, como programado, preparado, en curso, finalizado o cancelado. |
| **Route (Ruta)** | Recorrido definido que debe seguirse durante una operación de transporte entre el origen y el destino. |
| **Driver (Conductor)** | Persona responsable de conducir el vehículo asignado durante una operación de transporte. |
| **Vehicle (Vehículo)** | Unidad de transporte utilizada para realizar un viaje y trasladar la carga entre el origen y el destino. |
| **Vehicle Availability (Disponibilidad del vehículo)** | Condición que determina si un vehículo se encuentra disponible para ser asignado a una operación de transporte. |
| **Driver Availability (Disponibilidad del conductor)** | Condición que determina si un conductor se encuentra disponible para participar en una operación de transporte. |
| **Stop (Parada)** | Interrupción temporal del desplazamiento del vehículo durante el desarrollo de un viaje. |
| **Rest (Descanso)** | Pausa realizada por el conductor durante una operación de transporte antes de continuar el viaje. |
| **Delay (Retraso)** | Situación en la que una operación presenta una demora respecto al tiempo previsto para su desarrollo. |
| **Problem (Problema)** | Situación inesperada que puede afectar el desarrollo normal de una operación de transporte. |
| **Incident (Incidencia)** | Evento ocurrido durante un viaje que afecta o puede afectar el desarrollo normal de la operación y requiere ser registrado o atendido. |
| **Incident Type (Tipo de incidencia)** | Clasificación utilizada para identificar la naturaleza de una incidencia ocurrida durante un viaje. |
| **Incident Status (Estado de incidencia)** | Condición actual de una incidencia, utilizada para determinar si se encuentra pendiente, en atención o atendida. |
| **Accident (Accidente)** | Suceso no planificado ocurrido durante una operación de transporte que puede afectar al conductor, vehículo, carga o continuidad del viaje. |
| **Trip History (Historial de viajes)** | Registro de los viajes realizados que permite consultar posteriormente la información y los eventos asociados a cada operación. |
| **Driver History (Historial del conductor)** | Registro de los viajes e incidencias asociados a un conductor a lo largo de sus operaciones. |
| **Vehicle History (Historial del vehículo)** | Registro de los viajes e incidencias asociados a un vehículo durante las operaciones en las que ha participado. |
| **Operation Performance (Desempeño de la operación)** | Resultado de la revisión de una operación de transporte considerando su desarrollo, cumplimiento y eventos registrados. |

<div style="page-break-after: always;"></div>


## 2.4. Requirements Specification

En esta sección se especifican los principales requisitos de **Trakto** a partir de la información obtenida durante el proceso de investigación, análisis de usuarios y Needfinding. Los requisitos identificados permiten definir las funcionalidades necesarias para atender las necesidades de los segmentos objetivo y establecer una base para la planificación y desarrollo del producto digital.

La especificación de requisitos comprende las secciones de **To-Be Scenario Mapping, User Stories, Impact Map y Product Backlog**, permitiendo relacionar las necesidades de los usuarios con las funcionalidades, prioridades y objetivos del producto.

### 2.4.1. User Stories

En esta sección se presentan las **User Stories** identificadas para Trakto. Estas historias describen las funcionalidades requeridas desde la perspectiva de los usuarios y se encuentran agrupadas mediante **Epics** relacionadas con las principales responsabilidades del dominio.

Cada User Story incluye su identificador, usuario, prioridad, Epic, título, descripción y varios criterios de aceptación verificables. Los criterios de aceptación se encuentran redactados en tiempo presente, en tercera persona y utilizando la estructura **Given-When-Then**, evitando referencias a elementos específicos de interfaz.

Adicionalmente, se incluyen **Technical Stories** para funcionalidades que no representan una interacción directa con el usuario final y **Spike Stories** destinadas a reducir incertidumbre mediante actividades de investigación, análisis o pruebas de viabilidad técnica.

#### Epics

| Epic ID | Epic | Descripción |
|---|---|---|
| EP01 | Identity and Access Management | Gestiona el registro, autenticación y acceso de los usuarios a Trakto. |
| EP02 | Profile Management | Gestiona la información asociada al perfil de los usuarios. |
| EP03 | Trip Management | Gestiona el ciclo de vida de los viajes, rutas, estados, paradas y descansos. |
| EP04 | Fleet Management | Gestiona los vehículos, conductores y su disponibilidad para las operaciones. |
| EP05 | Incident Management | Gestiona retrasos, problemas, accidentes e incidencias relacionadas con los viajes. |
| EP06 | Operational History | Gestiona el historial de viajes, vehículos, conductores, incidencias y desempeño de las operaciones. |

---

#### US01 – Registrar cuenta

| Campo | Detalle |
|---|---|
| **Story ID** | US01 |
| **User** | Usuario |
| **Priority** | High |
| **Epic** | EP01 – Identity and Access Management |
| **Title** | Registrar cuenta |
| **Description** | Como usuario, deseo registrar una cuenta para acceder a las funcionalidades de Trakto. |
| **Acceptance Criteria** | **Scenario 1: Registro válido**<br>**Given** que el usuario proporciona los datos requeridos y un correo no registrado<br>**When** solicita registrar su cuenta<br>**Then** el sistema registra la cuenta correctamente.<br><br>**Scenario 2: Correo ya registrado**<br>**Given** que existe una cuenta asociada al correo proporcionado<br>**When** el usuario solicita registrar una nueva cuenta<br>**Then** el sistema rechaza el registro e informa que el correo ya se encuentra registrado.<br><br>**Scenario 3: Datos inválidos**<br>**Given** que los datos proporcionados no cumplen las reglas establecidas<br>**When** el usuario solicita registrar su cuenta<br>**Then** el sistema rechaza el registro. |

---

#### US02 – Iniciar sesión

| Campo | Detalle |
|---|---|
| **Story ID** | US02 |
| **User** | Usuario |
| **Priority** | High |
| **Epic** | EP01 – Identity and Access Management |
| **Title** | Iniciar sesión |
| **Description** | Como usuario registrado, deseo autenticarme con mis credenciales para acceder de manera segura a Trakto. |
| **Acceptance Criteria** | **Scenario 1: Credenciales válidas**<br>**Given** que el usuario posee una cuenta registrada<br>**When** proporciona credenciales válidas<br>**Then** el sistema autentica al usuario y permite el acceso.<br><br>**Scenario 2: Credenciales inválidas**<br>**Given** que las credenciales proporcionadas son incorrectas<br>**When** el usuario intenta autenticarse<br>**Then** el sistema rechaza la autenticación.<br><br>**Scenario 3: Credenciales incompletas**<br>**Given** que el usuario no proporciona todos los datos requeridos<br>**When** intenta autenticarse<br>**Then** el sistema rechaza la solicitud. |

---

#### US03 – Consultar perfil

| Campo | Detalle |
|---|---|
| **Story ID** | US03 |
| **User** | Usuario |
| **Priority** | Medium |
| **Epic** | EP02 – Profile Management |
| **Title** | Consultar perfil |
| **Description** | Como usuario, deseo consultar la información de mi perfil para conocer los datos asociados a mi cuenta. |
| **Acceptance Criteria** | **Scenario 1: Perfil existente**<br>**Given** que el usuario posee un perfil registrado<br>**When** solicita consultar su información<br>**Then** el sistema proporciona los datos asociados al perfil.<br><br>**Scenario 2: Perfil inexistente**<br>**Given** que no existe un perfil asociado al usuario<br>**When** solicita consultar su información<br>**Then** el sistema informa que el perfil no se encuentra disponible. |

---

#### US04 – Actualizar perfil

| Campo | Detalle |
|---|---|
| **Story ID** | US04 |
| **User** | Usuario |
| **Priority** | Medium |
| **Epic** | EP02 – Profile Management |
| **Title** | Actualizar perfil |
| **Description** | Como usuario, deseo actualizar la información de mi perfil para mantener mis datos vigentes. |
| **Acceptance Criteria** | **Scenario 1: Actualización válida**<br>**Given** que el usuario posee un perfil registrado<br>**When** proporciona información válida para actualizarlo<br>**Then** el sistema actualiza los datos del perfil.<br><br>**Scenario 2: Información inválida**<br>**Given** que la información proporcionada no cumple las reglas establecidas<br>**When** el usuario solicita actualizar su perfil<br>**Then** el sistema rechaza la actualización y conserva la información anterior. |

---

#### US05 – Consultar viajes

| Campo | Detalle |
|---|---|
| **Story ID** | US05 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP03 – Trip Management |
| **Title** | Consultar viajes |
| **Description** | Como supervisor de flota, deseo consultar los viajes registrados para conocer las operaciones de transporte bajo mi responsabilidad. |
| **Acceptance Criteria** | **Scenario 1: Existen viajes**<br>**Given** que existen viajes registrados<br>**When** el supervisor solicita consultar los viajes<br>**Then** el sistema proporciona las operaciones disponibles.<br><br>**Scenario 2: No existen viajes**<br>**Given** que no existen viajes registrados<br>**When** el supervisor realiza la consulta<br>**Then** el sistema informa que no existen viajes disponibles. |

---

#### US06 – Consultar detalle de viaje

| Campo | Detalle |
|---|---|
| **Story ID** | US06 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP03 – Trip Management |
| **Title** | Consultar detalle de viaje |
| **Description** | Como supervisor de flota, deseo consultar el detalle de un viaje para conocer su ruta, conductor, vehículo, estado y demás información asociada. |
| **Acceptance Criteria** | **Scenario 1: Viaje existente**<br>**Given** que el viaje solicitado existe<br>**When** el supervisor consulta sus detalles<br>**Then** el sistema proporciona la información asociada al viaje.<br><br>**Scenario 2: Viaje inexistente**<br>**Given** que el viaje solicitado no existe<br>**When** el supervisor intenta consultar sus detalles<br>**Then** el sistema informa que el viaje no se encuentra disponible. |

---

#### US07 – Consultar estado del viaje

| Campo | Detalle |
|---|---|
| **Story ID** | US07 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP03 – Trip Management |
| **Title** | Consultar estado del viaje |
| **Description** | Como supervisor de flota, deseo consultar el estado de un viaje para conocer la situación actual de la operación. |
| **Acceptance Criteria** | **Scenario 1: Estado disponible**<br>**Given** que el viaje existe y posee un estado registrado<br>**When** el supervisor consulta su estado<br>**Then** el sistema proporciona el estado actual del viaje.<br><br>**Scenario 2: Viaje inexistente**<br>**Given** que el viaje solicitado no existe<br>**When** el supervisor consulta su estado<br>**Then** el sistema informa que el viaje no se encuentra disponible. |

---

#### US08 – Consultar ruta asignada

| Campo | Detalle |
|---|---|
| **Story ID** | US08 |
| **User** | Coordinador de operaciones |
| **Priority** | High |
| **Epic** | EP03 – Trip Management |
| **Title** | Consultar ruta asignada |
| **Description** | Como coordinador de operaciones, deseo consultar la ruta asignada a un viaje para conocer el recorrido establecido para la operación. |
| **Acceptance Criteria** | **Scenario 1: Ruta asignada**<br>**Given** que el viaje posee una ruta asignada<br>**When** el coordinador consulta la ruta<br>**Then** el sistema proporciona la información correspondiente.<br><br>**Scenario 2: Ruta no asignada**<br>**Given** que el viaje no posee una ruta asignada<br>**When** el coordinador realiza la consulta<br>**Then** el sistema informa que no existe una ruta asociada. |

---

#### US09 – Consultar conductor

| Campo | Detalle |
|---|---|
| **Story ID** | US09 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP04 – Fleet Management |
| **Title** | Consultar información del conductor |
| **Description** | Como supervisor de flota, deseo consultar la información del conductor asignado para conocer los datos del responsable de una operación. |
| **Acceptance Criteria** | **Scenario 1: Conductor asignado**<br>**Given** que el viaje posee un conductor asignado<br>**When** el supervisor solicita consultar su información<br>**Then** el sistema proporciona los datos disponibles del conductor.<br><br>**Scenario 2: Conductor no asignado**<br>**Given** que el viaje no posee un conductor asignado<br>**When** el supervisor realiza la consulta<br>**Then** el sistema informa que no existe un conductor asignado. |

---

#### US10 – Consultar vehículo

| Campo | Detalle |
|---|---|
| **Story ID** | US10 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP04 – Fleet Management |
| **Title** | Consultar información del vehículo |
| **Description** | Como supervisor de flota, deseo consultar la información del vehículo asignado para conocer la unidad utilizada en una operación. |
| **Acceptance Criteria** | **Scenario 1: Vehículo asignado**<br>**Given** que el viaje posee un vehículo asignado<br>**When** el supervisor solicita consultar su información<br>**Then** el sistema proporciona los datos disponibles del vehículo.<br><br>**Scenario 2: Vehículo no asignado**<br>**Given** que el viaje no posee un vehículo asignado<br>**When** el supervisor realiza la consulta<br>**Then** el sistema informa que no existe un vehículo asignado. |

---

#### US11 – Registrar incidencia

| Campo | Detalle |
|---|---|
| **Story ID** | US11 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP05 – Incident Management |
| **Title** | Registrar incidencia |
| **Description** | Como supervisor de flota, deseo registrar una incidencia asociada a un viaje para mantener constancia de los problemas ocurridos durante la operación. |
| **Acceptance Criteria** | **Scenario 1: Registro válido**<br>**Given** que existe un viaje y se proporciona información válida sobre una incidencia<br>**When** el supervisor solicita registrarla<br>**Then** el sistema registra la incidencia asociada al viaje.<br><br>**Scenario 2: Viaje inexistente**<br>**Given** que el viaje indicado no existe<br>**When** el supervisor intenta registrar una incidencia<br>**Then** el sistema rechaza el registro.<br><br>**Scenario 3: Información incompleta**<br>**Given** que no se proporciona la información requerida<br>**When** el supervisor solicita registrar la incidencia<br>**Then** el sistema rechaza la operación. |

---

#### US12 – Consultar eventos e incidencias del viaje

| Campo | Detalle |
|---|---|
| **Story ID** | US12 |
| **User** | Coordinador de operaciones |
| **Priority** | High |
| **Epic** | EP05 – Incident Management |
| **Title** | Consultar eventos e incidencias del viaje |
| **Description** | Como coordinador de operaciones, deseo consultar los eventos e incidencias de un viaje para conocer las situaciones ocurridas durante la operación. |
| **Acceptance Criteria** | **Scenario 1: Existen eventos**<br>**Given** que el viaje posee eventos o incidencias registrados<br>**When** el coordinador solicita consultarlos<br>**Then** el sistema proporciona los registros asociados.<br><br>**Scenario 2: No existen eventos**<br>**Given** que el viaje no posee eventos registrados<br>**When** el coordinador realiza la consulta<br>**Then** el sistema informa que no existen eventos disponibles. |

---

#### US13 – Consultar historial de viajes

| Campo | Detalle |
|---|---|
| **Story ID** | US13 |
| **User** | Coordinador de operaciones |
| **Priority** | High |
| **Epic** | EP06 – Operational History |
| **Title** | Consultar historial de viajes |
| **Description** | Como coordinador de operaciones, deseo consultar el historial de viajes para revisar operaciones realizadas anteriormente. |
| **Acceptance Criteria** | **Scenario 1: Historial disponible**<br>**Given** que existen viajes finalizados registrados<br>**When** el coordinador consulta el historial<br>**Then** el sistema proporciona las operaciones históricas disponibles.<br><br>**Scenario 2: Historial vacío**<br>**Given** que no existen operaciones históricas<br>**When** el coordinador realiza la consulta<br>**Then** el sistema informa que no existen registros disponibles. |

---

#### US14 – Consultar historial del conductor

| Campo | Detalle |
|---|---|
| **Story ID** | US14 |
| **User** | Supervisor de flota |
| **Priority** | Medium |
| **Epic** | EP06 – Operational History |
| **Title** | Consultar historial del conductor |
| **Description** | Como supervisor de flota, deseo consultar el historial de un conductor para revisar los viajes e incidencias asociados a sus operaciones anteriores. |
| **Acceptance Criteria** | **Scenario 1: Historial disponible**<br>**Given** que el conductor posee operaciones registradas<br>**When** el supervisor consulta su historial<br>**Then** el sistema proporciona los viajes e incidencias asociados.<br><br>**Scenario 2: Sin historial**<br>**Given** que el conductor no posee operaciones históricas<br>**When** el supervisor realiza la consulta<br>**Then** el sistema informa que no existen registros disponibles. |

---

#### US15 – Consultar historial del vehículo

| Campo | Detalle |
|---|---|
| **Story ID** | US15 |
| **User** | Supervisor de flota |
| **Priority** | Medium |
| **Epic** | EP06 – Operational History |
| **Title** | Consultar historial del vehículo |
| **Description** | Como supervisor de flota, deseo consultar el historial de un vehículo para revisar los viajes e incidencias asociados a la unidad. |
| **Acceptance Criteria** | **Scenario 1: Historial disponible**<br>**Given** que el vehículo posee operaciones registradas<br>**When** el supervisor consulta su historial<br>**Then** el sistema proporciona los viajes e incidencias asociados.<br><br>**Scenario 2: Sin historial**<br>**Given** que el vehículo no posee operaciones históricas<br>**When** el supervisor realiza la consulta<br>**Then** el sistema informa que no existen registros disponibles. |

---

#### US16 – Filtrar historial de viajes

| Campo | Detalle |
|---|---|
| **Story ID** | US16 |
| **User** | Coordinador de operaciones |
| **Priority** | Medium |
| **Epic** | EP06 – Operational History |
| **Title** | Filtrar historial de viajes |
| **Description** | Como coordinador de operaciones, deseo filtrar el historial de viajes para localizar operaciones anteriores según criterios específicos. |
| **Acceptance Criteria** | **Scenario 1: Existen coincidencias**<br>**Given** que existen viajes que cumplen los criterios indicados<br>**When** el coordinador aplica los criterios de filtrado<br>**Then** el sistema proporciona las operaciones coincidentes.<br><br>**Scenario 2: No existen coincidencias**<br>**Given** que ningún viaje cumple los criterios indicados<br>**When** el coordinador realiza el filtrado<br>**Then** el sistema informa que no existen resultados coincidentes. |

---

#### US17 – Programar viaje

| Campo | Detalle |
|---|---|
| **Story ID** | US17 |
| **User** | Coordinador de operaciones |
| **Priority** | High |
| **Epic** | EP03 – Trip Management |
| **Title** | Programar viaje |
| **Description** | Como coordinador de operaciones, deseo programar un viaje para registrar una nueva operación de transporte. |
| **Acceptance Criteria** | **Scenario 1: Programación válida**<br>**Given** que se proporciona la información requerida<br>**When** el coordinador solicita programar el viaje<br>**Then** el sistema registra la operación con estado programado.<br><br>**Scenario 2: Información incompleta**<br>**Given** que faltan datos requeridos<br>**When** el coordinador solicita programar el viaje<br>**Then** el sistema rechaza la operación.<br><br>**Scenario 3: Información inválida**<br>**Given** que los datos no cumplen las reglas establecidas<br>**When** el coordinador solicita programar el viaje<br>**Then** el sistema rechaza el registro. |

---

#### US18 – Asignar ruta a un viaje

| Campo | Detalle |
|---|---|
| **Story ID** | US18 |
| **User** | Coordinador de operaciones |
| **Priority** | High |
| **Epic** | EP03 – Trip Management |
| **Title** | Asignar ruta a un viaje |
| **Description** | Como coordinador de operaciones, deseo asignar una ruta a un viaje para establecer el recorrido que debe realizarse. |
| **Acceptance Criteria** | **Scenario 1: Asignación válida**<br>**Given** que existe un viaje y una ruta disponible<br>**When** el coordinador asigna la ruta<br>**Then** el sistema registra la ruta asociada al viaje.<br><br>**Scenario 2: Viaje inexistente**<br>**Given** que el viaje indicado no existe<br>**When** el coordinador intenta asignar una ruta<br>**Then** el sistema rechaza la operación.<br><br>**Scenario 3: Ruta inexistente**<br>**Given** que la ruta indicada no existe<br>**When** se intenta realizar la asignación<br>**Then** el sistema rechaza la operación. |

---

#### US19 – Actualizar estado del viaje

| Campo | Detalle |
|---|---|
| **Story ID** | US19 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP03 – Trip Management |
| **Title** | Actualizar estado del viaje |
| **Description** | Como supervisor de flota, deseo actualizar el estado de un viaje para reflejar la situación actual de la operación. |
| **Acceptance Criteria** | **Scenario 1: Cambio válido**<br>**Given** que el viaje existe y el cambio de estado está permitido<br>**When** el supervisor actualiza el estado<br>**Then** el sistema registra el nuevo estado.<br><br>**Scenario 2: Cambio no permitido**<br>**Given** que la transición solicitada no cumple las reglas establecidas<br>**When** el supervisor intenta actualizar el estado<br>**Then** el sistema rechaza el cambio.<br><br>**Scenario 3: Viaje inexistente**<br>**Given** que el viaje no existe<br>**When** el supervisor solicita actualizar su estado<br>**Then** el sistema rechaza la operación. |

---

#### US20 – Registrar parada

| Campo | Detalle |
|---|---|
| **Story ID** | US20 |
| **User** | Supervisor de flota |
| **Priority** | Medium |
| **Epic** | EP03 – Trip Management |
| **Title** | Registrar parada |
| **Description** | Como supervisor de flota, deseo registrar una parada ocurrida durante un viaje para mantener la trazabilidad de la operación. |
| **Acceptance Criteria** | **Scenario 1: Registro válido**<br>**Given** que el viaje se encuentra en curso<br>**When** el supervisor registra una parada válida<br>**Then** el sistema asocia la parada al viaje.<br><br>**Scenario 2: Viaje no iniciado**<br>**Given** que el viaje no se encuentra en curso<br>**When** se intenta registrar una parada<br>**Then** el sistema rechaza el registro.<br><br>**Scenario 3: Datos incompletos**<br>**Given** que faltan datos requeridos<br>**When** el supervisor solicita registrar la parada<br>**Then** el sistema rechaza la operación. |

---

#### US21 – Registrar descanso

| Campo | Detalle |
|---|---|
| **Story ID** | US21 |
| **User** | Supervisor de flota |
| **Priority** | Medium |
| **Epic** | EP03 – Trip Management |
| **Title** | Registrar descanso |
| **Description** | Como supervisor de flota, deseo registrar un descanso realizado durante un viaje para mantener constancia de las pausas de la operación. |
| **Acceptance Criteria** | **Scenario 1: Registro válido**<br>**Given** que el viaje se encuentra en curso<br>**When** el supervisor registra un descanso válido<br>**Then** el sistema asocia el descanso al viaje.<br><br>**Scenario 2: Viaje no iniciado**<br>**Given** que el viaje no se encuentra en curso<br>**When** se intenta registrar un descanso<br>**Then** el sistema rechaza el registro.<br><br>**Scenario 3: Datos incompletos**<br>**Given** que faltan datos requeridos<br>**When** se solicita registrar el descanso<br>**Then** el sistema rechaza la operación. |

---

#### US22 – Finalizar viaje

| Campo | Detalle |
|---|---|
| **Story ID** | US22 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP03 – Trip Management |
| **Title** | Finalizar viaje |
| **Description** | Como supervisor de flota, deseo finalizar un viaje para registrar que la operación de transporte ha concluido. |
| **Acceptance Criteria** | **Scenario 1: Finalización válida**<br>**Given** que el viaje se encuentra en curso y cumple las condiciones de finalización<br>**When** el supervisor solicita finalizarlo<br>**Then** el sistema registra el viaje como finalizado.<br><br>**Scenario 2: Estado incompatible**<br>**Given** que el viaje se encuentra en un estado que no permite su finalización<br>**When** el supervisor intenta finalizarlo<br>**Then** el sistema rechaza la operación.<br><br>**Scenario 3: Viaje inexistente**<br>**Given** que el viaje no existe<br>**When** se intenta finalizarlo<br>**Then** el sistema rechaza la operación. |

---

#### US23 – Registrar vehículo

| Campo | Detalle |
|---|---|
| **Story ID** | US23 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP04 – Fleet Management |
| **Title** | Registrar vehículo |
| **Description** | Como supervisor de flota, deseo registrar un vehículo para incorporarlo a las operaciones de transporte. |
| **Acceptance Criteria** | **Scenario 1: Registro válido**<br>**Given** que se proporcionan los datos requeridos de un vehículo no registrado<br>**When** el supervisor solicita registrarlo<br>**Then** el sistema registra el vehículo.<br><br>**Scenario 2: Vehículo duplicado**<br>**Given** que el vehículo ya se encuentra registrado<br>**When** el supervisor intenta registrarlo nuevamente<br>**Then** el sistema rechaza el registro.<br><br>**Scenario 3: Datos inválidos**<br>**Given** que los datos no cumplen las reglas establecidas<br>**When** se solicita registrar el vehículo<br>**Then** el sistema rechaza la operación. |

---

#### US24 – Actualizar información del vehículo

| Campo | Detalle |
|---|---|
| **Story ID** | US24 |
| **User** | Supervisor de flota |
| **Priority** | Medium |
| **Epic** | EP04 – Fleet Management |
| **Title** | Actualizar información del vehículo |
| **Description** | Como supervisor de flota, deseo actualizar la información de un vehículo para mantener sus datos vigentes. |
| **Acceptance Criteria** | **Scenario 1: Actualización válida**<br>**Given** que el vehículo se encuentra registrado<br>**When** el supervisor proporciona información válida<br>**Then** el sistema actualiza los datos del vehículo.<br><br>**Scenario 2: Vehículo inexistente**<br>**Given** que el vehículo no existe<br>**When** el supervisor intenta actualizarlo<br>**Then** el sistema rechaza la operación.<br><br>**Scenario 3: Datos inválidos**<br>**Given** que los datos proporcionados no son válidos<br>**When** se solicita la actualización<br>**Then** el sistema conserva la información anterior. |

---

#### US25 – Registrar conductor

| Campo | Detalle |
|---|---|
| **Story ID** | US25 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP04 – Fleet Management |
| **Title** | Registrar conductor |
| **Description** | Como supervisor de flota, deseo registrar un conductor para incorporarlo a las operaciones de transporte. |
| **Acceptance Criteria** | **Scenario 1: Registro válido**<br>**Given** que se proporcionan los datos requeridos de un conductor no registrado<br>**When** el supervisor solicita registrarlo<br>**Then** el sistema registra al conductor.<br><br>**Scenario 2: Conductor duplicado**<br>**Given** que el conductor ya se encuentra registrado<br>**When** se intenta registrarlo nuevamente<br>**Then** el sistema rechaza el registro.<br><br>**Scenario 3: Datos inválidos**<br>**Given** que los datos no cumplen las reglas establecidas<br>**When** se solicita registrar al conductor<br>**Then** el sistema rechaza la operación. |

---

#### US26 – Actualizar información del conductor

| Campo | Detalle |
|---|---|
| **Story ID** | US26 |
| **User** | Supervisor de flota |
| **Priority** | Medium |
| **Epic** | EP04 – Fleet Management |
| **Title** | Actualizar información del conductor |
| **Description** | Como supervisor de flota, deseo actualizar la información de un conductor para mantener sus datos vigentes. |
| **Acceptance Criteria** | **Scenario 1: Actualización válida**<br>**Given** que el conductor se encuentra registrado<br>**When** el supervisor proporciona información válida<br>**Then** el sistema actualiza los datos del conductor.<br><br>**Scenario 2: Conductor inexistente**<br>**Given** que el conductor no existe<br>**When** se intenta actualizar su información<br>**Then** el sistema rechaza la operación.<br><br>**Scenario 3: Datos inválidos**<br>**Given** que los datos proporcionados no son válidos<br>**When** se solicita la actualización<br>**Then** el sistema conserva la información anterior. |

---

#### US27 – Asignar vehículo a un viaje

| Campo | Detalle |
|---|---|
| **Story ID** | US27 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP04 – Fleet Management |
| **Title** | Asignar vehículo a un viaje |
| **Description** | Como supervisor de flota, deseo asignar un vehículo a un viaje para definir la unidad que realizará la operación. |
| **Acceptance Criteria** | **Scenario 1: Vehículo disponible**<br>**Given** que existe un viaje y el vehículo se encuentra disponible<br>**When** el supervisor realiza la asignación<br>**Then** el sistema registra el vehículo asociado al viaje.<br><br>**Scenario 2: Vehículo no disponible**<br>**Given** que el vehículo no se encuentra disponible<br>**When** se intenta asignarlo<br>**Then** el sistema rechaza la asignación.<br><br>**Scenario 3: Viaje inexistente**<br>**Given** que el viaje no existe<br>**When** se intenta realizar la asignación<br>**Then** el sistema rechaza la operación. |

---

#### US28 – Asignar conductor a un viaje

| Campo | Detalle |
|---|---|
| **Story ID** | US28 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP04 – Fleet Management |
| **Title** | Asignar conductor a un viaje |
| **Description** | Como supervisor de flota, deseo asignar un conductor a un viaje para definir al responsable de realizar la operación. |
| **Acceptance Criteria** | **Scenario 1: Conductor disponible**<br>**Given** que existe un viaje y el conductor se encuentra disponible<br>**When** el supervisor realiza la asignación<br>**Then** el sistema registra al conductor asociado al viaje.<br><br>**Scenario 2: Conductor no disponible**<br>**Given** que el conductor no se encuentra disponible<br>**When** se intenta asignarlo<br>**Then** el sistema rechaza la asignación.<br><br>**Scenario 3: Viaje inexistente**<br>**Given** que el viaje no existe<br>**When** se intenta realizar la asignación<br>**Then** el sistema rechaza la operación. |

---

#### US29 – Consultar disponibilidad de vehículos

| Campo | Detalle |
|---|---|
| **Story ID** | US29 |
| **User** | Supervisor de flota |
| **Priority** | Medium |
| **Epic** | EP04 – Fleet Management |
| **Title** | Consultar disponibilidad de vehículos |
| **Description** | Como supervisor de flota, deseo consultar la disponibilidad de los vehículos para identificar qué unidades pueden ser asignadas a una operación. |
| **Acceptance Criteria** | **Scenario 1: Vehículos disponibles**<br>**Given** que existen vehículos disponibles<br>**When** el supervisor consulta su disponibilidad<br>**Then** el sistema proporciona las unidades disponibles.<br><br>**Scenario 2: Sin vehículos disponibles**<br>**Given** que ninguna unidad se encuentra disponible<br>**When** el supervisor realiza la consulta<br>**Then** el sistema informa que no existen vehículos disponibles. |

---

#### US30 – Consultar disponibilidad de conductores

| Campo | Detalle |
|---|---|
| **Story ID** | US30 |
| **User** | Supervisor de flota |
| **Priority** | Medium |
| **Epic** | EP04 – Fleet Management |
| **Title** | Consultar disponibilidad de conductores |
| **Description** | Como supervisor de flota, deseo consultar la disponibilidad de los conductores para identificar quién puede ser asignado a una operación. |
| **Acceptance Criteria** | **Scenario 1: Conductores disponibles**<br>**Given** que existen conductores disponibles<br>**When** el supervisor consulta su disponibilidad<br>**Then** el sistema proporciona los conductores disponibles.<br><br>**Scenario 2: Sin conductores disponibles**<br>**Given** que ningún conductor se encuentra disponible<br>**When** el supervisor realiza la consulta<br>**Then** el sistema informa que no existen conductores disponibles. |

---

#### US31 – Registrar retraso

| Campo | Detalle |
|---|---|
| **Story ID** | US31 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP05 – Incident Management |
| **Title** | Registrar retraso |
| **Description** | Como supervisor de flota, deseo registrar un retraso ocurrido durante un viaje para mantener constancia de las demoras de la operación. |
| **Acceptance Criteria** | **Scenario 1: Registro válido**<br>**Given** que existe un viaje en curso<br>**When** el supervisor registra un retraso con la información requerida<br>**Then** el sistema asocia el retraso al viaje.<br><br>**Scenario 2: Viaje inexistente**<br>**Given** que el viaje indicado no existe<br>**When** se intenta registrar el retraso<br>**Then** el sistema rechaza la operación.<br><br>**Scenario 3: Información incompleta**<br>**Given** que faltan datos requeridos<br>**When** se solicita registrar el retraso<br>**Then** el sistema rechaza el registro. |

---

#### US32 – Registrar problema

| Campo | Detalle |
|---|---|
| **Story ID** | US32 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP05 – Incident Management |
| **Title** | Registrar problema |
| **Description** | Como supervisor de flota, deseo registrar un problema ocurrido durante un viaje para documentar situaciones que puedan afectar la operación. |
| **Acceptance Criteria** | **Scenario 1: Registro válido**<br>**Given** que existe un viaje en curso<br>**When** el supervisor registra un problema con información válida<br>**Then** el sistema asocia el problema al viaje.<br><br>**Scenario 2: Viaje inexistente**<br>**Given** que el viaje indicado no existe<br>**When** se intenta registrar el problema<br>**Then** el sistema rechaza la operación.<br><br>**Scenario 3: Información insuficiente**<br>**Given** que faltan datos requeridos<br>**When** se solicita registrar el problema<br>**Then** el sistema rechaza el registro. |

---

#### US33 – Registrar accidente

| Campo | Detalle |
|---|---|
| **Story ID** | US33 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP05 – Incident Management |
| **Title** | Registrar accidente |
| **Description** | Como supervisor de flota, deseo registrar un accidente asociado a un viaje para mantener constancia de los eventos que afectan la operación, el vehículo o el conductor. |
| **Acceptance Criteria** | **Scenario 1: Registro válido**<br>**Given** que existe un viaje en curso y se proporciona la información requerida<br>**When** el supervisor registra el accidente<br>**Then** el sistema asocia el accidente al viaje.<br><br>**Scenario 2: Viaje inexistente**<br>**Given** que el viaje indicado no existe<br>**When** se intenta registrar el accidente<br>**Then** el sistema rechaza la operación.<br><br>**Scenario 3: Información incompleta**<br>**Given** que faltan datos requeridos del accidente<br>**When** se solicita registrarlo<br>**Then** el sistema rechaza el registro. |

---

#### US34 – Actualizar estado de incidencia

| Campo | Detalle |
|---|---|
| **Story ID** | US34 |
| **User** | Supervisor de flota |
| **Priority** | High |
| **Epic** | EP05 – Incident Management |
| **Title** | Actualizar estado de incidencia |
| **Description** | Como supervisor de flota, deseo actualizar el estado de una incidencia para reflejar su situación durante el proceso de atención. |
| **Acceptance Criteria** | **Scenario 1: Cambio válido**<br>**Given** que existe una incidencia registrada y la transición está permitida<br>**When** el supervisor actualiza su estado<br>**Then** el sistema registra el nuevo estado.<br><br>**Scenario 2: Cambio no permitido**<br>**Given** que la transición solicitada no cumple las reglas establecidas<br>**When** se intenta actualizar la incidencia<br>**Then** el sistema rechaza la modificación.<br><br>**Scenario 3: Incidencia inexistente**<br>**Given** que la incidencia no existe<br>**When** se intenta actualizar su estado<br>**Then** el sistema rechaza la operación. |

---

#### US35 – Consultar detalle de incidencia

| Campo | Detalle |
|---|---|
| **Story ID** | US35 |
| **User** | Coordinador de operaciones |
| **Priority** | Medium |
| **Epic** | EP05 – Incident Management |
| **Title** | Consultar detalle de incidencia |
| **Description** | Como coordinador de operaciones, deseo consultar el detalle de una incidencia para conocer la situación registrada durante un viaje. |
| **Acceptance Criteria** | **Scenario 1: Incidencia existente**<br>**Given** que la incidencia se encuentra registrada<br>**When** el coordinador solicita consultar sus detalles<br>**Then** el sistema proporciona la información asociada.<br><br>**Scenario 2: Incidencia inexistente**<br>**Given** que la incidencia no existe<br>**When** el coordinador intenta consultarla<br>**Then** el sistema informa que la incidencia no se encuentra disponible. |

---

#### US36 – Consultar historial de incidencias

| Campo | Detalle |
|---|---|
| **Story ID** | US36 |
| **User** | Coordinador de operaciones |
| **Priority** | Medium |
| **Epic** | EP06 – Operational History |
| **Title** | Consultar historial de incidencias |
| **Description** | Como coordinador de operaciones, deseo consultar las incidencias registradas en operaciones anteriores para analizar los problemas ocurridos durante los viajes. |
| **Acceptance Criteria** | **Scenario 1: Historial disponible**<br>**Given** que existen incidencias registradas en operaciones anteriores<br>**When** el coordinador consulta el historial<br>**Then** el sistema proporciona las incidencias disponibles.<br><br>**Scenario 2: Historial vacío**<br>**Given** que no existen incidencias históricas<br>**When** el coordinador realiza la consulta<br>**Then** el sistema informa que no existen registros disponibles. |

---

#### US37 – Revisar desempeño de una operación

| Campo | Detalle |
|---|---|
| **Story ID** | US37 |
| **User** | Coordinador de operaciones |
| **Priority** | Medium |
| **Epic** | EP06 – Operational History |
| **Title** | Revisar desempeño de una operación |
| **Description** | Como coordinador de operaciones, deseo revisar el desempeño de un viaje finalizado para evaluar el desarrollo de la operación. |
| **Acceptance Criteria** | **Scenario 1: Operación finalizada**<br>**Given** que existe un viaje finalizado con información registrada<br>**When** el coordinador solicita revisar su desempeño<br>**Then** el sistema proporciona la información relacionada con el desarrollo de la operación.<br><br>**Scenario 2: Viaje no finalizado**<br>**Given** que el viaje todavía no ha finalizado<br>**When** el coordinador solicita evaluar su desempeño final<br>**Then** el sistema informa que la operación aún no puede evaluarse como finalizada. |

---

#### US38 – Consultar viajes por conductor

| Campo | Detalle |
|---|---|
| **Story ID** | US38 |
| **User** | Supervisor de flota |
| **Priority** | Medium |
| **Epic** | EP06 – Operational History |
| **Title** | Consultar viajes por conductor |
| **Description** | Como supervisor de flota, deseo consultar los viajes realizados por un conductor para revisar las operaciones en las que ha participado. |
| **Acceptance Criteria** | **Scenario 1: Existen viajes asociados**<br>**Given** que el conductor posee viajes registrados<br>**When** el supervisor consulta sus operaciones<br>**Then** el sistema proporciona los viajes asociados al conductor.<br><br>**Scenario 2: Sin viajes asociados**<br>**Given** que el conductor no posee viajes registrados<br>**When** el supervisor realiza la consulta<br>**Then** el sistema informa que no existen operaciones asociadas. |

---

#### US39 – Consultar viajes por vehículo

| Campo | Detalle |
|---|---|
| **Story ID** | US39 |
| **User** | Supervisor de flota |
| **Priority** | Medium |
| **Epic** | EP06 – Operational History |
| **Title** | Consultar viajes por vehículo |
| **Description** | Como supervisor de flota, deseo consultar los viajes realizados por un vehículo para revisar las operaciones en las que ha sido utilizado. |
| **Acceptance Criteria** | **Scenario 1: Existen viajes asociados**<br>**Given** que el vehículo posee viajes registrados<br>**When** el supervisor consulta sus operaciones<br>**Then** el sistema proporciona los viajes asociados al vehículo.<br><br>**Scenario 2: Sin viajes asociados**<br>**Given** que el vehículo no posee viajes registrados<br>**When** el supervisor realiza la consulta<br>**Then** el sistema informa que no existen operaciones asociadas. |

---

### Technical Stories

Las siguientes historias representan requisitos técnicos necesarios para soportar las funcionalidades de Trakto que no implican una interacción directa con los usuarios finales. De acuerdo con la rúbrica, estas historias utilizan **Developer** como rol y sus criterios de aceptación consideran escenarios de solicitud y respuesta.

#### TS01 – Proporcionar servicios para la gestión de viajes

| Campo | Detalle |
|---|---|
| **Story ID** | TS01 |
| **User** | Developer |
| **Priority** | High |
| **Epic** | EP03 – Trip Management |
| **Title** | Proporcionar servicios para la gestión de viajes |
| **Description** | Como Developer, deseo disponer de servicios para gestionar la información de los viajes para que los datos de las operaciones puedan ser consultados y procesados de manera consistente. |
| **Acceptance Criteria** | **Scenario 1: Consulta válida**<br>**Given** que existen viajes registrados<br>**When** se realiza una solicitud válida de consulta<br>**Then** el servicio proporciona una respuesta exitosa con la información correspondiente.<br><br>**Scenario 2: Recurso inexistente**<br>**Given** que se solicita un viaje inexistente<br>**When** el servicio procesa la solicitud<br>**Then** proporciona una respuesta indicando que el recurso no fue encontrado.<br><br>**Scenario 3: Solicitud inválida**<br>**Given** que la solicitud contiene datos inválidos<br>**When** el servicio procesa la solicitud<br>**Then** proporciona una respuesta indicando que la solicitud no es válida. |

---

#### TS02 – Proporcionar servicios para la gestión de flota

| Campo | Detalle |
|---|---|
| **Story ID** | TS02 |
| **User** | Developer |
| **Priority** | High |
| **Epic** | EP04 – Fleet Management |
| **Title** | Proporcionar servicios para la gestión de flota |
| **Description** | Como Developer, deseo disponer de servicios para gestionar vehículos y conductores para que la información de la flota pueda ser consultada y actualizada de manera consistente. |
| **Acceptance Criteria** | **Scenario 1: Consulta válida**<br>**Given** que existen recursos de flota registrados<br>**When** se realiza una solicitud válida<br>**Then** el servicio proporciona la información correspondiente.<br><br>**Scenario 2: Recurso inexistente**<br>**Given** que se solicita un vehículo o conductor inexistente<br>**When** el servicio procesa la solicitud<br>**Then** proporciona una respuesta indicando que el recurso no fue encontrado.<br><br>**Scenario 3: Datos inválidos**<br>**Given** que la solicitud contiene información inválida<br>**When** el servicio intenta procesarla<br>**Then** proporciona una respuesta indicando que la solicitud no es válida. |

---

#### TS03 – Proporcionar servicios para la gestión de incidencias

| Campo | Detalle |
|---|---|
| **Story ID** | TS03 |
| **User** | Developer |
| **Priority** | High |
| **Epic** | EP05 – Incident Management |
| **Title** | Proporcionar servicios para la gestión de incidencias |
| **Description** | Como Developer, deseo disponer de servicios para registrar y consultar incidencias para que los eventos ocurridos durante los viajes puedan ser gestionados de manera consistente. |
| **Acceptance Criteria** | **Scenario 1: Registro válido**<br>**Given** que se proporciona una solicitud válida asociada a un viaje existente<br>**When** el servicio procesa el registro<br>**Then** registra la incidencia y proporciona una respuesta exitosa.<br><br>**Scenario 2: Viaje inexistente**<br>**Given** que la solicitud referencia un viaje inexistente<br>**When** el servicio procesa el registro<br>**Then** proporciona una respuesta indicando que el viaje no fue encontrado.<br><br>**Scenario 3: Consulta válida**<br>**Given** que existen incidencias asociadas a un viaje<br>**When** se solicita consultarlas<br>**Then** el servicio proporciona los registros correspondientes. |

---

#### TS04 – Proporcionar servicios para el historial operativo

| Campo | Detalle |
|---|---|
| **Story ID** | TS04 |
| **User** | Developer |
| **Priority** | Medium |
| **Epic** | EP06 – Operational History |
| **Title** | Proporcionar servicios para el historial operativo |
| **Description** | Como Developer, deseo disponer de servicios para consultar el historial operativo para que la información histórica de viajes, vehículos y conductores pueda ser recuperada de manera consistente. |
| **Acceptance Criteria** | **Scenario 1: Historial disponible**<br>**Given** que existen registros históricos<br>**When** se realiza una solicitud válida<br>**Then** el servicio proporciona la información histórica correspondiente.<br><br>**Scenario 2: Sin registros**<br>**Given** que no existen registros para los criterios solicitados<br>**When** el servicio procesa la consulta<br>**Then** proporciona una respuesta sin resultados.<br><br>**Scenario 3: Solicitud inválida**<br>**Given** que los parámetros solicitados no son válidos<br>**When** el servicio procesa la solicitud<br>**Then** proporciona una respuesta indicando que la consulta no es válida. |

---

### Spike Stories

Las Spike Stories permiten investigar aspectos técnicos antes de implementar una funcionalidad, reduciendo incertidumbre y facilitando la toma de decisiones del equipo.

#### SP01 – Investigar persistencia local para Trakto

**Spike Story:**  
Como equipo de desarrollo, deseamos investigar alternativas de persistencia local para Android con Kotlin para determinar la opción más adecuada para almacenar y consultar información de Trakto.

**Acceptance Criteria:**

- **Given** que Trakto requiere almacenamiento local  
  **When** el equipo investiga las alternativas disponibles  
  **Then** documenta sus principales ventajas y limitaciones.

- **Given** que se ha seleccionado una alternativa  
  **When** el desarrollador realiza una prueba de concepto  
  **Then** la solución permite almacenar, consultar y actualizar información básica.

- **Given** que la prueba ha sido evaluada  
  **When** finaliza la investigación  
  **Then** el equipo documenta la alternativa recomendada y su justificación.

**Definition of Done:**

- Alternativas investigadas y comparadas.
- Prueba de concepto realizada.
- Resultados y recomendación documentados.

---

#### SP02 – Investigar estrategia de autenticación segura

**Spike Story:**  
Como equipo de desarrollo, deseamos investigar alternativas de autenticación para determinar una estrategia segura y adecuada para Trakto.

**Acceptance Criteria:**

- **Given** que Trakto requiere autenticación de usuarios  
  **When** el equipo investiga las alternativas disponibles  
  **Then** documenta sus ventajas, limitaciones y consideraciones de seguridad.

- **Given** que se identifica una alternativa adecuada  
  **When** el desarrollador realiza una prueba de concepto  
  **Then** se valida un flujo básico de autenticación.

- **Given** que las alternativas han sido evaluadas  
  **When** finaliza la investigación  
  **Then** el equipo documenta la opción recomendada y su justificación.

**Definition of Done:**

- Alternativas de autenticación evaluadas.
- Prueba de concepto realizada.
- Riesgos y recomendación técnica documentados.

<div style="page-break-after: always;"></div>



### 2.4.2. Impact Mapping

El **Impact Mapping de Trakto fue elaborado en Miro** y permite relacionar los objetivos de negocio con los usuarios, los cambios de comportamiento esperados y las funcionalidades necesarias para alcanzarlos. Para su elaboración se consideran los User Personas previamente definidos: **Carlos Mendoza**, supervisor de flota, y **Andrea Salazar**, coordinadora de operaciones.

Se establecieron los siguientes Business Goals siguiendo los criterios SMART:

- **BG01:** Alcanzar al menos **100 usuarios registrados** en Trakto durante los primeros **6 meses** posteriores al lanzamiento.
- **BG02:** Lograr que al menos el **70% de los usuarios activos** utilice las funcionalidades de gestión y consulta de viajes durante los primeros **6 meses**.
- **BG03:** Lograr que al menos el **60% de las operaciones gestionadas en Trakto** mantenga un registro de sus principales eventos e incidencias durante los primeros **8 meses**.

#### Business Goal 1

**Goal:** Alcanzar al menos 100 usuarios registrados en Trakto durante los primeros 6 meses posteriores al lanzamiento.

| **Actor / Persona** | **Impact** | **Deliverables** | **User Stories** |
|---|---|---|---|
| Carlos Mendoza – Supervisor de flota | Adopta Trakto como herramienta para gestionar sus operaciones de transporte. | Registro y autenticación de usuarios. | **US01:** Como usuario, deseo registrar una cuenta para acceder a las funcionalidades de Trakto.<br>**US02:** Como usuario registrado, deseo autenticarme con mis credenciales para acceder de manera segura a Trakto. |
| Andrea Salazar – Coordinadora de operaciones | Utiliza Trakto para centralizar la consulta de información relacionada con sus operaciones. | Gestión de cuenta y perfil de usuario. | **US03:** Como usuario, deseo consultar la información de mi perfil para conocer los datos asociados a mi cuenta.<br>**US04:** Como usuario, deseo actualizar la información de mi perfil para mantener mis datos vigentes. |

#### Business Goal 2

**Goal:** Lograr que al menos el 70% de los usuarios activos utilice las funcionalidades de gestión y consulta de viajes durante los primeros 6 meses.

| **Actor / Persona** | **Impact** | **Deliverables** | **User Stories** |
|---|---|---|---|
| Carlos Mendoza – Supervisor de flota | Consulta frecuentemente los viajes y verifica los recursos asignados a cada operación. | Gestión y consulta de viajes, vehículos y conductores. | **US05:** Como supervisor de flota, deseo consultar los viajes registrados para conocer las operaciones bajo mi responsabilidad.<br>**US06:** Como supervisor de flota, deseo consultar el detalle de un viaje para conocer su información asociada.<br>**US09:** Como supervisor de flota, deseo consultar la información del conductor asignado para conocer al responsable de una operación.<br>**US10:** Como supervisor de flota, deseo consultar la información del vehículo asignado para conocer la unidad utilizada. |
| Andrea Salazar – Coordinadora de operaciones | Organiza y consulta los viajes y rutas necesarios para coordinar las operaciones de transporte. | Programación de viajes y gestión de rutas. | **US17:** Como coordinador de operaciones, deseo programar un viaje para registrar una nueva operación de transporte.<br>**US18:** Como coordinador de operaciones, deseo asignar una ruta a un viaje para establecer el recorrido que debe realizarse.<br>**US08:** Como coordinador de operaciones, deseo consultar la ruta asignada a un viaje para conocer el recorrido establecido. |

#### Business Goal 3

**Goal:** Lograr que al menos el 60% de las operaciones gestionadas en Trakto mantenga un registro de sus principales eventos e incidencias durante los primeros 8 meses.

| **Actor / Persona** | **Impact** | **Deliverables** | **User Stories** |
|---|---|---|---|
| Carlos Mendoza – Supervisor de flota | Registra los eventos e incidencias relevantes ocurridos durante los viajes. | Registro de paradas, descansos, retrasos, problemas e incidencias. | **US20:** Como supervisor de flota, deseo registrar una parada ocurrida durante un viaje para mantener la trazabilidad de la operación.<br>**US21:** Como supervisor de flota, deseo registrar un descanso realizado durante un viaje para mantener constancia de las pausas.<br>**US11:** Como supervisor de flota, deseo registrar una incidencia asociada a un viaje para mantener constancia de los problemas ocurridos.<br>**US31:** Como supervisor de flota, deseo registrar un retraso ocurrido durante un viaje para mantener constancia de las demoras. |
| Andrea Salazar – Coordinadora de operaciones | Revisa los eventos históricos de las operaciones para mejorar su seguimiento y evaluación. | Consulta de incidencias e historial operativo. | **US12:** Como coordinador de operaciones, deseo consultar los eventos e incidencias de un viaje para conocer las situaciones ocurridas durante la operación.<br>**US13:** Como coordinador de operaciones, deseo consultar el historial de viajes para revisar operaciones realizadas anteriormente.<br>**US36:** Como coordinador de operaciones, deseo consultar las incidencias registradas en operaciones anteriores para analizar los problemas ocurridos. |

A continuación, se presenta una captura del **Impact Mapping de Trakto elaborado en Miro** a partir de los Business Goals, User Personas, Impacts, Deliverables y User Stories identificados.

![Impact Mapping - Trakto](assets/images/chapter2/impact-mapping.png)

<div style="page-break-after: always;"></div>


### 2.4.3. Product Backlog

El **Product Backlog** de Trakto reúne las User Stories identificadas y las organiza según su valor para el negocio. Cada historia cuenta con una estimación mediante **Story Points**, utilizando los valores **1, 2, 3, 5 y 8**, y se distribuye entre los Sprints planificados para el desarrollo del producto.

El orden del Product Backlog prioriza inicialmente las funcionalidades relacionadas con la gestión de viajes, flota e incidencias, debido a que representan las principales capacidades del dominio de Trakto.

| **Orden** | **User Story Id** | **Título** | **Story Points** | **Sprint** |
|---:|---|---|---:|---:|
| 1 | US17 | Programar viaje | 5 | 1 |
| 2 | US05 | Consultar viajes | 3 | 1 |
| 3 | US06 | Consultar detalle de viaje | 3 | 1 |
| 4 | US18 | Asignar ruta a un viaje | 3 | 1 |
| 5 | US23 | Registrar vehículo | 3 | 1 |
| 6 | US25 | Registrar conductor | 3 | 1 |
| 7 | US27 | Asignar vehículo a un viaje | 5 | 1 |
| 8 | US28 | Asignar conductor a un viaje | 5 | 1 |
| 9 | US07 | Consultar estado del viaje | 2 | 1 |
| 10 | US19 | Actualizar estado del viaje | 3 | 1 |
| 11 | US01 | Registrar cuenta | 3 | 1 |
| 12 | US02 | Iniciar sesión | 3 | 1 |
| 13 | US08 | Consultar ruta asignada | 2 | 2 |
| 14 | US09 | Consultar información del conductor | 2 | 2 |
| 15 | US10 | Consultar información del vehículo | 2 | 2 |
| 16 | US29 | Consultar disponibilidad de vehículos | 3 | 2 |
| 17 | US30 | Consultar disponibilidad de conductores | 3 | 2 |
| 18 | US11 | Registrar incidencia | 5 | 2 |
| 19 | US31 | Registrar retraso | 3 | 2 |
| 20 | US32 | Registrar problema | 3 | 2 |
| 21 | US33 | Registrar accidente | 3 | 2 |
| 22 | US34 | Actualizar estado de incidencia | 3 | 2 |
| 23 | US35 | Consultar detalle de incidencia | 2 | 2 |
| 24 | US12 | Consultar eventos e incidencias del viaje | 3 | 2 |
| 25 | US20 | Registrar parada | 3 | 2 |
| 26 | US21 | Registrar descanso | 3 | 2 |
| 27 | US22 | Finalizar viaje | 3 | 2 |
| 28 | US13 | Consultar historial de viajes | 5 | 3 |
| 29 | US16 | Filtrar historial de viajes | 3 | 3 |
| 30 | US14 | Consultar historial del conductor | 3 | 3 |
| 31 | US15 | Consultar historial del vehículo | 3 | 3 |
| 32 | US36 | Consultar historial de incidencias | 3 | 3 |
| 33 | US37 | Revisar desempeño de una operación | 5 | 3 |
| 34 | US38 | Consultar viajes por conductor | 3 | 3 |
| 35 | US39 | Consultar viajes por vehículo | 3 | 3 |
| 36 | US24 | Actualizar información del vehículo | 2 | 3 |
| 37 | US26 | Actualizar información del conductor | 2 | 3 |
| 38 | US03 | Consultar perfil | 2 | 3 |
| 39 | US04 | Actualizar perfil | 2 | 3 |

A continuación, se presenta una captura del **Product Backlog de Trakto elaborado en Trello**.

![Product Backlog - Trakto](assets/images/chapter2/product-backlog.png)

**Enlace público del Product Backlog en Trello:**  
[Agregar URL pública de Trello]

<div style="page-break-after: always;"></div>


## 2.5. Strategic-Level Domain-Driven Design

En esta sección se aplica **Domain-Driven Design (DDD)** a nivel estratégico para identificar los límites naturales del dominio de Trakto y definir sus Bounded Contexts. Para ello se utilizan **EventStorming** y **Bounded Context Canvas**.

### 2.5.1. EventStorming

Se realizó una sesión de **EventStorming en Miro** para modelar el dominio general de Trakto e identificar los principales eventos relacionados con las operaciones de transporte.

Durante la sesión se organizaron cronológicamente eventos relacionados con viajes, vehículos, conductores, rutas, incidencias, usuarios e historial operativo.

![EventStorming - Trakto](assets/images/chapter2/eventstorming-trakto.png)

#### 2.5.1.1. Candidate Context Discovery

A partir del EventStorm, se realizó el **Candidate Context Discovery en Miro** para identificar posibles Bounded Contexts. Se utilizó principalmente la técnica **look-for-pivotal-events**, agrupando eventos relacionados e identificando cambios importantes dentro del proceso de negocio.

Durante el análisis se identificaron progresivamente los siguientes Candidate Bounded Contexts:

- **IAM**
- **Profile**
- **Trip Management**
- **Fleet Management**
- **Incident Management**
- **Operational History**

A continuación, se muestran capturas de los cambios progresivos realizados durante el Candidate Context Discovery.

![Candidate Context Discovery - Proceso 1](assets/images/chapter2/candidate-context-discovery-1.png)

![Candidate Context Discovery - Proceso 2](assets/images/chapter2/candidate-context-discovery-2.png)

![Candidate Context Discovery - Final](assets/images/chapter2/candidate-context-discovery-final.png)

<div style="page-break-after: always;"></div>

#### 2.5.1.2. Domain Message Flows Modeling

En esta sección se modela la colaboración entre los Bounded Contexts de Trakto mediante la técnica **Domain Storytelling**, con el objetivo de visualizar cómo interactúan entre sí para resolver los principales casos de negocio.

Para ello se elaboraron diagramas en **Miro**, representando la participación de los contextos **IAM, Profile, Trip Management, Fleet Management, Incident Management y Operational History** en diferentes escenarios del dominio.

A continuación, se presentan los diagramas de Domain Storytelling elaborados.

![Domain Storytelling - Flujo 1](assets/images/chapter2/domain-storytelling-1.png)

![Domain Storytelling - Flujo 2](assets/images/chapter2/domain-storytelling-2.png)

<div style="page-break-after: always;"></div>

#### 2.5.1.3. Bounded Context Canvases

En esta sección se detallan los Candidate Bounded Contexts identificados previamente mediante la elaboración de **Bounded Context Canvases**.

Los contextos se trabajan por orden de importancia y cada canvas sigue el proceso indicado en la rúbrica:

- **Context Overview Definition**
- **Business Rules Distillation & Ubiquitous Language Capture**
- **Capability Analysis**
- **Capability Layering**, cuando corresponda
- **Dependencies Capture**
- **Design Critique**

Para Trakto se elaboran los siguientes Bounded Context Canvases:

1. **Trip Management**
2. **Fleet Management**
3. **Incident Management**
4. **Operational History**
5. **IAM**
6. **Profile**

A continuación, se presentan las capturas de los Bounded Context Canvases elaborados en **Miro**.

![Bounded Context Canvas - Trip Management](assets/images/chapter2/bounded-context-canvas-trip-management.png)

![Bounded Context Canvas - Fleet Management](assets/images/chapter2/bounded-context-canvas-fleet-management.png)

![Bounded Context Canvas - Incident Management](assets/images/chapter2/bounded-context-canvas-incident-management.png)

![Bounded Context Canvas - Operational History](assets/images/chapter2/bounded-context-canvas-operational-history.png)

![Bounded Context Canvas - IAM](assets/images/chapter2/bounded-context-canvas-iam.png)

![Bounded Context Canvas - Profile](assets/images/chapter2/bounded-context-canvas-profile.png)

<div style="page-break-after: always;"></div>

### 2.5.2. Context Mapping

En esta sección se analizan las relaciones estructurales entre los Bounded Contexts identificados para **Trakto**, evaluando sus dependencias y responsabilidades para obtener una adecuada separación del dominio.

Durante el proceso se revisaron diferentes alternativas de organización de los contextos y sus capabilities, considerando patrones de relación de **Domain-Driven Design** como **Customer/Supplier, Conformist, Anticorruption Layer y Shared Kernel**.

Como resultado del análisis se definió el Context Map final de Trakto, conformado por los contextos **IAM, Profile, Trip Management, Fleet Management, Incident Management y Operational History**.

A continuación, se presentan las alternativas analizadas y el Context Map final elaborado en **Miro**.

![Context Mapping - Alternativa 1](assets/images/chapter2/context-mapping-1.png)

![Context Mapping - Alternativa 2](assets/images/chapter2/context-mapping-2.png)

![Context Mapping - Final](assets/images/chapter2/context-mapping-final.png)

<div style="page-break-after: always;"></div>

### 2.5.3. Software Architecture

En esta sección se presenta la arquitectura de software de **Trakto** aplicando el **C4 Model** y utilizando **Lucidchart** para la elaboración de los diagramas. Se representa la solución desde diferentes niveles, mostrando su contexto, los elementos principales de la arquitectura, las tecnologías utilizadas y su despliegue.

#### 2.5.3.1. Software Architecture Context Level Diagrams

El **Context Diagram** representa a **Trakto** como el sistema central y muestra los usuarios y sistemas externos con los que interactúa.

Para Trakto se consideran como usuarios principales al **Supervisor de flota** y al **Coordinador de operaciones**, quienes interactúan con el sistema para gestionar y consultar las operaciones de transporte.

A continuación, se presenta el Context Diagram elaborado en **Lucidchart**.

![Software Architecture Context Diagram - Trakto](assets/images/chapter2/software-architecture-context.png)

El diagrama permite visualizar los límites de Trakto y las principales interacciones entre el sistema, sus usuarios y los sistemas externos identificados.

<div style="page-break-after: always;"></div>

#### 2.5.3.2. Software Architecture Container Level Diagrams

El **Container Diagram** representa los elementos de alto nivel que conforman la arquitectura de Trakto, sus principales responsabilidades, las tecnologías utilizadas y la comunicación entre ellos.

La solución contempla una **aplicación móvil Android desarrollada con Kotlin**, encargada de proporcionar las funcionalidades de Trakto a los usuarios. Los demás containers y tecnologías se incorporarán en el diagrama de acuerdo con la arquitectura definida para la solución.

A continuación, se presenta el Container Diagram elaborado en **Lucidchart**.

![Software Architecture Container Diagram - Trakto](assets/images/chapter2/software-architecture-container.png)

<div style="page-break-after: always;"></div>

#### 2.5.3.3. Software Architecture Deployment Diagrams

El **Deployment Diagram** representa la distribución física de Trakto, mostrando los dispositivos, servidores, redes y demás entornos donde se despliegan los componentes de software, así como las relaciones entre los diferentes nodos.

A continuación, se presenta el Deployment Diagram elaborado en **Lucidchart**.

![Software Architecture Deployment Diagram - Trakto](assets/images/chapter2/software-architecture-deployment.png)

El diagrama permite visualizar cómo los elementos de la solución se distribuyen sobre la infraestructura utilizada para ejecutar Trakto.

<div style="page-break-after: always;"></div>

## 2.6. Tactical-Level Domain-Driven Design

En esta sección se presenta la propuesta de diseño táctico de **Trakto** aplicando Domain-Driven Design. Para cada Bounded Context se identifican las clases correspondientes a las capas **Domain, Interface, Application e Infrastructure**, considerando sus responsabilidades dentro de la solución.

Los Bounded Contexts definidos son:

1. **Trip Management**
2. **Fleet Management**
3. **Incident Management**
4. **Operational History**
5. **IAM**
6. **Profile**

<div style="page-break-after: always;"></div>

### 2.6.1. Bounded Context: Trip Management

El Bounded Context **Trip Management** gestiona el ciclo de vida de los viajes, incluyendo su programación, ruta, estado, paradas, descansos, inicio y finalización.

#### 2.6.1.1. Domain Layer

Esta capa representa el core y las reglas de negocio de **Trip Management**.

| **Clase** | **Tipo** | **Propósito** | **Atributos / Métodos principales** |
|---|---|---|---|
| `Trip` | Aggregate Root | Representar y controlar un viaje. | `id`, `route`, `status`, `stops`, `rests`; `assignRoute()`, `start()`, `updateStatus()`, `registerStop()`, `registerRest()`, `complete()` |
| `Route` | Entity | Representar la ruta asignada. | `id`, `origin`, `destination`; `updateRoute()` |
| `Stop` | Entity | Representar una parada. | `id`, `reason`, `startedAt`, `endedAt`; `finish()` |
| `Rest` | Entity | Representar un descanso. | `id`, `startedAt`, `endedAt`; `finish()` |
| `TripId` | Value Object | Identificar un viaje. | `value` |
| `TripStatus` | Enumeration | Representar el estado del viaje. | `SCHEDULED`, `PREPARED`, `IN_PROGRESS`, `COMPLETED`, `CANCELLED` |
| `TripRepository` | Repository Interface | Definir las operaciones de persistencia de viajes. | `save()`, `findById()`, `findAll()` |

Relaciones principales:

```text
Trip "1" ─── "1" Route
Trip "1" ─── "0..*" Stop
Trip "1" ─── "0..*" Rest
Trip ─────── TripStatus
Trip ─────── TripId
TripRepository ───> Trip
```

#### 2.6.1.2. Interface Layer

Esta capa contiene las clases de presentación utilizadas para interactuar con las funcionalidades de Trip Management.

| **Clase** | **Tipo** | **Propósito** | **Atributos / Métodos principales** |
|---|---|---|---|
| `TripViewModel` | ViewModel | Gestionar las acciones relacionadas con viajes. | `uiState`; `loadTrips()`, `loadTrip()`, `scheduleTrip()`, `startTrip()`, `updateStatus()`, `registerStop()`, `registerRest()`, `completeTrip()` |
| `TripUiState` | UI State | Representar el estado de la información presentada. | `trips`, `selectedTrip`, `isLoading`, `error` |

#### 2.6.1.3. Application Layer

Esta capa coordina los flujos y capabilities de Trip Management mediante Commands, Queries y Handlers.

| **Clase** | **Tipo** | **Propósito** |
|---|---|---|
| `ScheduleTripCommand` | Command | Contener los datos para programar un viaje. |
| `ScheduleTripCommandHandler` | Command Handler | Procesar la programación del viaje. |
| `AssignRouteCommand` | Command | Solicitar la asignación de una ruta. |
| `AssignRouteCommandHandler` | Command Handler | Procesar la asignación de una ruta. |
| `StartTripCommand` | Command | Solicitar el inicio de un viaje. |
| `StartTripCommandHandler` | Command Handler | Procesar el inicio del viaje. |
| `UpdateTripStatusCommand` | Command | Solicitar un cambio de estado. |
| `UpdateTripStatusCommandHandler` | Command Handler | Procesar el cambio de estado. |
| `RegisterStopCommand` | Command | Solicitar el registro de una parada. |
| `RegisterStopCommandHandler` | Command Handler | Procesar el registro de una parada. |
| `RegisterRestCommand` | Command | Solicitar el registro de un descanso. |
| `RegisterRestCommandHandler` | Command Handler | Procesar el registro de un descanso. |
| `CompleteTripCommand` | Command | Solicitar la finalización del viaje. |
| `CompleteTripCommandHandler` | Command Handler | Procesar la finalización del viaje. |
| `GetTripsQuery` | Query | Solicitar los viajes registrados. |
| `GetTripsQueryHandler` | Query Handler | Obtener los viajes registrados. |
| `GetTripByIdQuery` | Query | Solicitar un viaje específico. |
| `GetTripByIdQueryHandler` | Query Handler | Obtener el detalle de un viaje. |

#### 2.6.1.4. Infrastructure Layer

Esta capa implementa la persistencia de Trip Management mediante **Room y SQLite**.

| **Clase** | **Tipo** | **Propósito** |
|---|---|---|
| `TripRoomEntity` | Room Entity | Representar un viaje persistido. |
| `RouteRoomEntity` | Room Entity | Representar una ruta persistida. |
| `StopRoomEntity` | Room Entity | Representar una parada persistida. |
| `RestRoomEntity` | Room Entity | Representar un descanso persistido. |
| `TripDao` | DAO | Realizar operaciones de persistencia y consulta. |
| `TripRepositoryImpl` | Repository Implementation | Implementar `TripRepository` mediante Room. |

<div style="page-break-after: always;"></div>

#### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams

El **Component Diagram del C4 Model** representa los componentes principales de Trip Management, sus responsabilidades, tecnologías e interacciones.

```text
Trip Presentation
        ↓
Trip Application
        ↓
Trip Domain
        ↓
Trip Infrastructure
        ↓
Room / SQLite
```

Tecnologías utilizadas: **Kotlin, Jetpack Compose, ViewModel, Room y SQLite**.

![Trip Management - Component Diagram](assets/images/chapter2/trip-management-component-diagram.png)

<div style="page-break-after: always;"></div>

#### 2.6.1.6. Bounded Context Software Architecture Code Level Diagrams

En esta sección se presentan los diagramas de mayor detalle de implementación de **Trip Management**.

##### 2.6.1.6.1. Bounded Context Domain Layer Class Diagrams

El UML Class Diagram representa las clases, interfaces, enumeraciones, atributos, métodos, scopes, relaciones y multiplicidades del Domain Layer.

```text
Trip
--------------------------------
- id: TripId
- route: Route
- status: TripStatus
- stops: List<Stop>
- rests: List<Rest>
--------------------------------
+ assignRoute(route: Route): Unit
+ start(): Unit
+ updateStatus(status: TripStatus): Unit
+ registerStop(stop: Stop): Unit
+ registerRest(rest: Rest): Unit
+ complete(): Unit

Route
--------------------------------
- id: Long
- origin: String
- destination: String
--------------------------------
+ updateRoute(origin: String, destination: String): Unit

Stop
--------------------------------
- id: Long
- reason: String
- startedAt: LocalDateTime
- endedAt: LocalDateTime?
--------------------------------
+ finish(endTime: LocalDateTime): Unit

Rest
--------------------------------
- id: Long
- startedAt: LocalDateTime
- endedAt: LocalDateTime?
--------------------------------
+ finish(endTime: LocalDateTime): Unit

TripId
--------------------------------
- value: Long

<<enumeration>>
TripStatus
--------------------------------
SCHEDULED
PREPARED
IN_PROGRESS
COMPLETED
CANCELLED

<<interface>>
TripRepository
--------------------------------
+ save(trip: Trip): Unit
+ findById(id: TripId): Trip?
+ findAll(): List<Trip>
```

Relaciones:

```text
Trip "1" ─── "1" Route
Trip "1" ─── "0..*" Stop
Trip "1" ─── "0..*" Rest
Trip ─────── TripStatus
Trip ─────── TripId
TripRepository ───> Trip
```

![Trip Management - Domain Layer Class Diagram](assets/images/chapter2/trip-management-domain-class-diagram.png)

<div style="page-break-after: always;"></div>

##### 2.6.1.6.2. Bounded Context Database Design Diagram

El Database Diagram representa las tablas, columnas, constraints y relaciones utilizadas para la persistencia de **Trip Management** mediante Room y SQLite.

| **Tabla** | **Columnas** | **Constraints** |
|---|---|---|
| `trips` | `id`, `route_id`, `status` | `id PK`, `route_id FK`, `status NOT NULL` |
| `routes` | `id`, `origin`, `destination` | `id PK`, `origin NOT NULL`, `destination NOT NULL` |
| `stops` | `id`, `trip_id`, `reason`, `started_at`, `ended_at` | `id PK`, `trip_id FK`, `reason NOT NULL`, `started_at NOT NULL` |
| `rests` | `id`, `trip_id`, `started_at`, `ended_at` | `id PK`, `trip_id FK`, `started_at NOT NULL` |

Relaciones:

```text
routes.id  "1" ─── "0..*" trips.route_id
trips.id   "1" ─── "0..*" stops.trip_id
trips.id   "1" ─── "0..*" rests.trip_id
```

![Trip Management - Database Diagram](assets/images/chapter2/trip-management-database-diagram.png)

<div style="page-break-after: always;"></div>



### 2.6.2. Bounded Context: Fleet Management

El Bounded Context **Fleet Management** gestiona los vehículos y conductores utilizados en las operaciones de transporte, incluyendo su registro, actualización, disponibilidad y asignación.

#### 2.6.2.1. Domain Layer

Esta capa representa el core y las reglas de negocio de **Fleet Management**.

| **Clase** | **Tipo** | **Propósito** | **Atributos / Métodos principales** |
|---|---|---|---|
| `Vehicle` | Aggregate Root | Representar y controlar un vehículo. | `id`, `plate`, `brand`, `model`, `availability`; `update()`, `changeAvailability()` |
| `Driver` | Aggregate Root | Representar y controlar un conductor. | `id`, `name`, `licenseNumber`, `availability`; `update()`, `changeAvailability()` |
| `VehicleId` | Value Object | Identificar un vehículo. | `value` |
| `DriverId` | Value Object | Identificar un conductor. | `value` |
| `VehicleAvailability` | Enumeration | Representar la disponibilidad del vehículo. | `AVAILABLE`, `ASSIGNED`, `UNAVAILABLE` |
| `DriverAvailability` | Enumeration | Representar la disponibilidad del conductor. | `AVAILABLE`, `ASSIGNED`, `UNAVAILABLE` |
| `VehicleRepository` | Repository Interface | Definir las operaciones de persistencia de vehículos. | `save()`, `findById()`, `findAll()`, `findAvailable()` |
| `DriverRepository` | Repository Interface | Definir las operaciones de persistencia de conductores. | `save()`, `findById()`, `findAll()`, `findAvailable()` |

Relaciones principales:

```text
Vehicle ───── VehicleId
Vehicle ───── VehicleAvailability
Driver ────── DriverId
Driver ────── DriverAvailability
VehicleRepository ───> Vehicle
DriverRepository ─────> Driver
```

#### 2.6.2.2. Interface Layer

Esta capa contiene las clases de presentación utilizadas para interactuar con las funcionalidades de Fleet Management.

| **Clase** | **Tipo** | **Propósito** | **Atributos / Métodos principales** |
|---|---|---|---|
| `FleetViewModel` | ViewModel | Gestionar la información general de vehículos y conductores. | `uiState`; `loadVehicles()`, `loadDrivers()` |
| `VehicleViewModel` | ViewModel | Gestionar las acciones relacionadas con vehículos. | `registerVehicle()`, `updateVehicle()`, `loadAvailableVehicles()` |
| `DriverViewModel` | ViewModel | Gestionar las acciones relacionadas con conductores. | `registerDriver()`, `updateDriver()`, `loadAvailableDrivers()` |
| `FleetUiState` | UI State | Representar los datos mostrados en la interfaz. | `vehicles`, `drivers`, `isLoading`, `error` |

#### 2.6.2.3. Application Layer

Esta capa coordina los flujos y capabilities relacionados con la gestión de vehículos y conductores.

| **Clase** | **Tipo** | **Propósito** |
|---|---|---|
| `RegisterVehicleCommand` | Command | Contener los datos para registrar un vehículo. |
| `RegisterVehicleCommandHandler` | Command Handler | Procesar el registro de un vehículo. |
| `UpdateVehicleCommand` | Command | Solicitar la actualización de un vehículo. |
| `UpdateVehicleCommandHandler` | Command Handler | Procesar la actualización de un vehículo. |
| `RegisterDriverCommand` | Command | Contener los datos para registrar un conductor. |
| `RegisterDriverCommandHandler` | Command Handler | Procesar el registro de un conductor. |
| `UpdateDriverCommand` | Command | Solicitar la actualización de un conductor. |
| `UpdateDriverCommandHandler` | Command Handler | Procesar la actualización de un conductor. |
| `AssignVehicleCommand` | Command | Solicitar la asignación de un vehículo. |
| `AssignVehicleCommandHandler` | Command Handler | Procesar la asignación de un vehículo. |
| `AssignDriverCommand` | Command | Solicitar la asignación de un conductor. |
| `AssignDriverCommandHandler` | Command Handler | Procesar la asignación de un conductor. |
| `GetVehiclesQuery` | Query | Solicitar los vehículos registrados. |
| `GetVehiclesQueryHandler` | Query Handler | Obtener los vehículos registrados. |
| `GetDriversQuery` | Query | Solicitar los conductores registrados. |
| `GetDriversQueryHandler` | Query Handler | Obtener los conductores registrados. |
| `GetAvailableVehiclesQueryHandler` | Query Handler | Obtener los vehículos disponibles. |
| `GetAvailableDriversQueryHandler` | Query Handler | Obtener los conductores disponibles. |

#### 2.6.2.4. Infrastructure Layer

Esta capa implementa la persistencia de Fleet Management mediante **Room y SQLite**.

| **Clase** | **Tipo** | **Propósito** |
|---|---|---|
| `VehicleRoomEntity` | Room Entity | Representar un vehículo persistido. |
| `DriverRoomEntity` | Room Entity | Representar un conductor persistido. |
| `VehicleDao` | DAO | Realizar operaciones de persistencia de vehículos. |
| `DriverDao` | DAO | Realizar operaciones de persistencia de conductores. |
| `VehicleRepositoryImpl` | Repository Implementation | Implementar `VehicleRepository` mediante Room. |
| `DriverRepositoryImpl` | Repository Implementation | Implementar `DriverRepository` mediante Room. |

<div style="page-break-after: always;"></div>

#### 2.6.2.5. Bounded Context Software Architecture Component Level Diagrams

El **Component Diagram del C4 Model** representa los componentes principales de Fleet Management, sus responsabilidades, tecnologías e interacciones.

```text
Fleet Presentation
        ↓
Fleet Application
        ↓
Fleet Domain
        ↓
Fleet Infrastructure
        ↓
Room / SQLite
```

Tecnologías utilizadas: **Kotlin, Jetpack Compose, ViewModel, Room y SQLite**.

![Fleet Management - Component Diagram](assets/images/chapter2/fleet-management-component-diagram.png)

<div style="page-break-after: always;"></div>

#### 2.6.2.6. Bounded Context Software Architecture Code Level Diagrams

En esta sección se presentan los diagramas de mayor detalle de implementación de **Fleet Management**.

##### 2.6.2.6.1. Bounded Context Domain Layer Class Diagrams

El UML Class Diagram representa las clases, interfaces, enumeraciones, atributos, métodos, scopes y relaciones del Domain Layer.

```text
Vehicle
--------------------------------
- id: VehicleId
- plate: String
- brand: String
- model: String
- availability: VehicleAvailability
--------------------------------
+ update(brand: String, model: String): Unit
+ changeAvailability(
    availability: VehicleAvailability
  ): Unit


Driver
--------------------------------
- id: DriverId
- name: String
- licenseNumber: String
- availability: DriverAvailability
--------------------------------
+ update(name: String, licenseNumber: String): Unit
+ changeAvailability(
    availability: DriverAvailability
  ): Unit


VehicleId
--------------------------------
- value: Long


DriverId
--------------------------------
- value: Long


<<enumeration>>
VehicleAvailability
--------------------------------
AVAILABLE
ASSIGNED
UNAVAILABLE


<<enumeration>>
DriverAvailability
--------------------------------
AVAILABLE
ASSIGNED
UNAVAILABLE


<<interface>>
VehicleRepository
--------------------------------
+ save(vehicle: Vehicle): Unit
+ findById(id: VehicleId): Vehicle?
+ findAll(): List<Vehicle>
+ findAvailable(): List<Vehicle>


<<interface>>
DriverRepository
--------------------------------
+ save(driver: Driver): Unit
+ findById(id: DriverId): Driver?
+ findAll(): List<Driver>
+ findAvailable(): List<Driver>
```

Relaciones:

```text
Vehicle ───── VehicleId
Vehicle ───── VehicleAvailability
Driver ────── DriverId
Driver ────── DriverAvailability

VehicleRepository ───> Vehicle
DriverRepository ─────> Driver
```

![Fleet Management - Domain Layer Class Diagram](assets/images/chapter2/fleet-management-domain-class-diagram.png)

<div style="page-break-after: always;"></div>

##### 2.6.2.6.2. Bounded Context Database Design Diagram

El Database Diagram representa las tablas, columnas, constraints y relaciones utilizadas para la persistencia de **Fleet Management** mediante Room y SQLite.

| **Tabla** | **Columnas** | **Constraints** |
|---|---|---|
| `vehicles` | `id`, `plate`, `brand`, `model`, `availability` | `id PK`, `plate UNIQUE NOT NULL`, `availability NOT NULL` |
| `drivers` | `id`, `name`, `license_number`, `availability` | `id PK`, `license_number UNIQUE NOT NULL`, `availability NOT NULL` |

```text
vehicles
--------------------------------
PK  id
    plate UNIQUE NOT NULL
    brand NOT NULL
    model NOT NULL
    availability NOT NULL


drivers
--------------------------------
PK  id
    name NOT NULL
    license_number UNIQUE NOT NULL
    availability NOT NULL
```

Las tablas `vehicles` y `drivers` son independientes dentro de Fleet Management. La asociación con los viajes se realiza desde **Trip Management** mediante los identificadores correspondientes.

![Fleet Management - Database Diagram](assets/images/chapter2/fleet-management-database-diagram.png)

<div style="page-break-after: always;"></div>




### 2.6.3. Bounded Context: Incident Management

El Bounded Context **Incident Management** gestiona las incidencias ocurridas durante los viajes, incluyendo retrasos, problemas, accidentes y su estado de atención.

#### 2.6.3.1. Domain Layer

Esta capa representa el core y las reglas de negocio de **Incident Management**.

| **Clase** | **Tipo** | **Propósito** | **Atributos / Métodos principales** |
|---|---|---|---|
| `Incident` | Aggregate Root | Representar y gestionar una incidencia. | `id`, `tripId`, `type`, `status`, `description`, `occurredAt`; `updateStatus()`, `resolve()` |
| `IncidentId` | Value Object | Identificar una incidencia. | `value` |
| `IncidentType` | Enumeration | Clasificar el tipo de incidencia. | `DELAY`, `PROBLEM`, `ACCIDENT`, `OTHER` |
| `IncidentStatus` | Enumeration | Representar el estado de la incidencia. | `PENDING`, `IN_PROGRESS`, `RESOLVED` |
| `IncidentRepository` | Repository Interface | Definir las operaciones de persistencia de incidencias. | `save()`, `findById()`, `findByTripId()`, `findAll()` |

Relaciones principales:

```text
Incident ───── IncidentId
Incident ───── IncidentType
Incident ───── IncidentStatus
IncidentRepository ───> Incident
```

#### 2.6.3.2. Interface Layer

Esta capa contiene las clases de presentación utilizadas para interactuar con las funcionalidades de Incident Management.

| **Clase** | **Tipo** | **Propósito** | **Atributos / Métodos principales** |
|---|---|---|---|
| `IncidentViewModel` | ViewModel | Gestionar acciones relacionadas con incidencias. | `uiState`; `loadIncidents()`, `loadIncident()`, `registerIncident()`, `updateStatus()` |
| `IncidentUiState` | UI State | Representar la información mostrada en la interfaz. | `incidents`, `selectedIncident`, `isLoading`, `error` |

#### 2.6.3.3. Application Layer

Esta capa coordina los flujos y capabilities relacionados con el registro y gestión de incidencias.

| **Clase** | **Tipo** | **Propósito** |
|---|---|---|
| `RegisterIncidentCommand` | Command | Contener los datos para registrar una incidencia. |
| `RegisterIncidentCommandHandler` | Command Handler | Procesar el registro de una incidencia. |
| `RegisterDelayCommand` | Command | Solicitar el registro de un retraso. |
| `RegisterDelayCommandHandler` | Command Handler | Procesar el registro de un retraso. |
| `RegisterProblemCommand` | Command | Solicitar el registro de un problema. |
| `RegisterProblemCommandHandler` | Command Handler | Procesar el registro de un problema. |
| `RegisterAccidentCommand` | Command | Solicitar el registro de un accidente. |
| `RegisterAccidentCommandHandler` | Command Handler | Procesar el registro de un accidente. |
| `UpdateIncidentStatusCommand` | Command | Solicitar la actualización del estado. |
| `UpdateIncidentStatusCommandHandler` | Command Handler | Procesar el cambio de estado de una incidencia. |
| `GetIncidentsQuery` | Query | Solicitar las incidencias registradas. |
| `GetIncidentsQueryHandler` | Query Handler | Obtener las incidencias registradas. |
| `GetIncidentByIdQuery` | Query | Solicitar una incidencia específica. |
| `GetIncidentByIdQueryHandler` | Query Handler | Obtener el detalle de una incidencia. |

#### 2.6.3.4. Infrastructure Layer

Esta capa implementa la persistencia de Incident Management mediante **Room y SQLite**.

| **Clase** | **Tipo** | **Propósito** |
|---|---|---|
| `IncidentRoomEntity` | Room Entity | Representar una incidencia persistida. |
| `IncidentDao` | DAO | Realizar operaciones de persistencia y consulta de incidencias. |
| `IncidentRepositoryImpl` | Repository Implementation | Implementar `IncidentRepository` mediante Room. |

<div style="page-break-after: always;"></div>

#### 2.6.3.5. Bounded Context Software Architecture Component Level Diagrams

El **Component Diagram del C4 Model** representa los componentes principales de Incident Management, sus responsabilidades, tecnologías e interacciones.

```text
Incident Presentation
        ↓
Incident Application
        ↓
Incident Domain
        ↓
Incident Infrastructure
        ↓
Room / SQLite
```

Tecnologías utilizadas: **Kotlin, Jetpack Compose, ViewModel, Room y SQLite**.

![Incident Management - Component Diagram](assets/images/chapter2/incident-management-component-diagram.png)

<div style="page-break-after: always;"></div>

#### 2.6.3.6. Bounded Context Software Architecture Code Level Diagrams

En esta sección se presentan los diagramas de mayor detalle de implementación de **Incident Management**.

##### 2.6.3.6.1. Bounded Context Domain Layer Class Diagrams

El UML Class Diagram representa las clases, interfaces, enumeraciones, atributos, métodos, scopes, relaciones y multiplicidades del Domain Layer.

```text
Incident
--------------------------------
- id: IncidentId
- tripId: Long
- type: IncidentType
- status: IncidentStatus
- description: String
- occurredAt: LocalDateTime
--------------------------------
+ updateStatus(status: IncidentStatus): Unit
+ resolve(): Unit


IncidentId
--------------------------------
- value: Long


<<enumeration>>
IncidentType
--------------------------------
DELAY
PROBLEM
ACCIDENT
OTHER


<<enumeration>>
IncidentStatus
--------------------------------
PENDING
IN_PROGRESS
RESOLVED


<<interface>>
IncidentRepository
--------------------------------
+ save(incident: Incident): Unit
+ findById(id: IncidentId): Incident?
+ findByTripId(tripId: Long): List<Incident>
+ findAll(): List<Incident>
```

Relaciones:

```text
Incident ───── IncidentId
Incident ───── IncidentType
Incident ───── IncidentStatus
IncidentRepository ───> Incident
```

![Incident Management - Domain Layer Class Diagram](assets/images/chapter2/incident-management-domain-class-diagram.png)

<div style="page-break-after: always;"></div>

##### 2.6.3.6.2. Bounded Context Database Design Diagram

El Database Diagram representa las tablas, columnas, constraints y relaciones utilizadas para la persistencia de **Incident Management** mediante Room y SQLite.

| **Tabla** | **Columnas** | **Constraints** |
|---|---|---|
| `incidents` | `id`, `trip_id`, `type`, `status`, `description`, `occurred_at` | `id PK`, `trip_id NOT NULL`, `type NOT NULL`, `status NOT NULL`, `description NOT NULL`, `occurred_at NOT NULL` |

```text
incidents
--------------------------------
PK  id
    trip_id NOT NULL
    type NOT NULL
    status NOT NULL
    description NOT NULL
    occurred_at NOT NULL
```

`trip_id` permite asociar la incidencia con el viaje correspondiente del Bounded Context **Trip Management**.

![Incident Management - Database Diagram](assets/images/chapter2/incident-management-database-diagram.png)

<div style="page-break-after: always;"></div>





### 2.6.4. Bounded Context: Operational History

El Bounded Context **Operational History** gestiona la consulta del historial de viajes, vehículos, conductores e incidencias, así como la revisión del desempeño de las operaciones realizadas.

#### 2.6.4.1. Domain Layer

Esta capa representa el core y las reglas de negocio de **Operational History**.

| **Clase** | **Tipo** | **Propósito** | **Atributos / Métodos principales** |
|---|---|---|---|
| `OperationHistory` | Aggregate Root | Representar el historial general de una operación. | `id`, `tripId`, `completedAt`, `performance`; `reviewPerformance()` |
| `TripHistory` | Entity | Representar información histórica de un viaje. | `tripId`, `status`, `startedAt`, `completedAt` |
| `VehicleHistory` | Entity | Representar el historial operativo de un vehículo. | `vehicleId`, `tripId`, `recordedAt` |
| `DriverHistory` | Entity | Representar el historial operativo de un conductor. | `driverId`, `tripId`, `recordedAt` |
| `OperationPerformance` | Value Object | Representar información de desempeño de una operación. | `completedTrips`, `incidentCount`, `delayCount` |
| `HistoryRepository` | Repository Interface | Definir las operaciones de consulta del historial. | `findTripHistory()`, `findVehicleHistory()`, `findDriverHistory()`, `findIncidentHistory()` |

Relaciones principales:

```text
OperationHistory ───── TripHistory
OperationHistory ───── VehicleHistory
OperationHistory ───── DriverHistory
OperationHistory ───── OperationPerformance
HistoryRepository ───> OperationHistory
```

#### 2.6.4.2. Interface Layer

Esta capa contiene las clases de presentación utilizadas para consultar el historial operativo.

| **Clase** | **Tipo** | **Propósito** | **Atributos / Métodos principales** |
|---|---|---|---|
| `HistoryViewModel` | ViewModel | Gestionar las consultas del historial operativo. | `uiState`; `loadTripHistory()`, `loadVehicleHistory()`, `loadDriverHistory()`, `loadIncidentHistory()`, `reviewPerformance()` |
| `HistoryUiState` | UI State | Representar los datos históricos mostrados en la interfaz. | `tripHistory`, `vehicleHistory`, `driverHistory`, `incidentHistory`, `performance`, `isLoading`, `error` |

#### 2.6.4.3. Application Layer

Esta capa coordina los flujos y capabilities relacionados con la consulta del historial y desempeño operativo.

| **Clase** | **Tipo** | **Propósito** |
|---|---|---|
| `GetTripHistoryQuery` | Query | Solicitar el historial de viajes. |
| `GetTripHistoryQueryHandler` | Query Handler | Obtener el historial de viajes. |
| `GetVehicleHistoryQuery` | Query | Solicitar el historial de un vehículo. |
| `GetVehicleHistoryQueryHandler` | Query Handler | Obtener el historial de un vehículo. |
| `GetDriverHistoryQuery` | Query | Solicitar el historial de un conductor. |
| `GetDriverHistoryQueryHandler` | Query Handler | Obtener el historial de un conductor. |
| `GetIncidentHistoryQuery` | Query | Solicitar el historial de incidencias. |
| `GetIncidentHistoryQueryHandler` | Query Handler | Obtener el historial de incidencias. |
| `ReviewOperationPerformanceQuery` | Query | Solicitar la revisión del desempeño operativo. |
| `ReviewOperationPerformanceQueryHandler` | Query Handler | Obtener la información de desempeño de una operación. |
| `RecordCompletedTripEventHandler` | Event Handler | Registrar información histórica cuando un viaje finaliza. |

#### 2.6.4.4. Infrastructure Layer

Esta capa implementa el acceso a la información histórica mediante **Room y SQLite**.

| **Clase** | **Tipo** | **Propósito** |
|---|---|---|
| `OperationHistoryRoomEntity` | Room Entity | Representar una operación histórica persistida. |
| `TripHistoryRoomEntity` | Room Entity | Representar el historial de viajes persistido. |
| `VehicleHistoryRoomEntity` | Room Entity | Representar el historial de vehículos persistido. |
| `DriverHistoryRoomEntity` | Room Entity | Representar el historial de conductores persistido. |
| `HistoryDao` | DAO | Realizar consultas y operaciones sobre el historial. |
| `HistoryRepositoryImpl` | Repository Implementation | Implementar `HistoryRepository` mediante Room. |

<div style="page-break-after: always;"></div>

#### 2.6.4.5. Bounded Context Software Architecture Component Level Diagrams

El **Component Diagram del C4 Model** representa los componentes principales de Operational History, sus responsabilidades, tecnologías e interacciones.

```text
History Presentation
        ↓
History Application
        ↓
History Domain
        ↓
History Infrastructure
        ↓
Room / SQLite
```

Tecnologías utilizadas: **Kotlin, Jetpack Compose, ViewModel, Room y SQLite**.

![Operational History - Component Diagram](assets/images/chapter2/operational-history-component-diagram.png)

<div style="page-break-after: always;"></div>

#### 2.6.4.6. Bounded Context Software Architecture Code Level Diagrams

En esta sección se presentan los diagramas de mayor detalle de implementación de **Operational History**.

##### 2.6.4.6.1. Bounded Context Domain Layer Class Diagrams

El UML Class Diagram representa las clases, interfaces, atributos, métodos, scopes, relaciones y multiplicidades del Domain Layer.

```text
OperationHistory
--------------------------------
- id: Long
- tripId: Long
- completedAt: LocalDateTime
- performance: OperationPerformance
--------------------------------
+ reviewPerformance(): OperationPerformance


TripHistory
--------------------------------
- tripId: Long
- status: String
- startedAt: LocalDateTime
- completedAt: LocalDateTime


VehicleHistory
--------------------------------
- vehicleId: Long
- tripId: Long
- recordedAt: LocalDateTime


DriverHistory
--------------------------------
- driverId: Long
- tripId: Long
- recordedAt: LocalDateTime


OperationPerformance
--------------------------------
- completedTrips: Int
- incidentCount: Int
- delayCount: Int


<<interface>>
HistoryRepository
--------------------------------
+ findTripHistory(tripId: Long): TripHistory?
+ findVehicleHistory(vehicleId: Long): List<VehicleHistory>
+ findDriverHistory(driverId: Long): List<DriverHistory>
+ findIncidentHistory(tripId: Long): List<Long>
```

Relaciones:

```text
OperationHistory "1" ─── "1" TripHistory
OperationHistory "1" ─── "0..*" VehicleHistory
OperationHistory "1" ─── "0..*" DriverHistory
OperationHistory "1" ─── "1" OperationPerformance
HistoryRepository ───> OperationHistory
```

![Operational History - Domain Layer Class Diagram](assets/images/chapter2/operational-history-domain-class-diagram.png)

<div style="page-break-after: always;"></div>

##### 2.6.4.6.2. Bounded Context Database Design Diagram

El Database Diagram representa las tablas, columnas, constraints y relaciones utilizadas para la persistencia de **Operational History** mediante Room y SQLite.

| **Tabla** | **Columnas** | **Constraints** |
|---|---|---|
| `operation_history` | `id`, `trip_id`, `completed_at`, `completed_trips`, `incident_count`, `delay_count` | `id PK`, `trip_id NOT NULL` |
| `trip_history` | `id`, `trip_id`, `status`, `started_at`, `completed_at` | `id PK`, `trip_id NOT NULL` |
| `vehicle_history` | `id`, `vehicle_id`, `trip_id`, `recorded_at` | `id PK`, `vehicle_id NOT NULL`, `trip_id NOT NULL` |
| `driver_history` | `id`, `driver_id`, `trip_id`, `recorded_at` | `id PK`, `driver_id NOT NULL`, `trip_id NOT NULL` |

Relaciones:

```text
operation_history.trip_id ─── trip_history.trip_id
trip_history.trip_id ─── vehicle_history.trip_id
trip_history.trip_id ─── driver_history.trip_id
```

![Operational History - Database Diagram](assets/images/chapter2/operational-history-database-diagram.png)

<div style="page-break-after: always;"></div>





### 2.6.5. Bounded Context: IAM

El Bounded Context **IAM (Identity and Access Management)** gestiona la identidad, autenticación y acceso de los usuarios de Trakto.

#### 2.6.5.1. Domain Layer

Esta capa representa las reglas de negocio relacionadas con usuarios, credenciales y roles.

| **Clase** | **Tipo** | **Propósito** | **Atributos / Métodos principales** |
|---|---|---|---|
| `User` | Aggregate Root | Representar la identidad de un usuario. | `id`, `email`, `passwordHash`, `role`; `changePassword()`, `changeRole()` |
| `UserId` | Value Object | Identificar un usuario. | `value` |
| `Email` | Value Object | Representar y validar el correo del usuario. | `value`; `isValid()` |
| `UserRole` | Enumeration | Representar el rol del usuario. | `FLEET_SUPERVISOR`, `OPERATIONS_COORDINATOR` |
| `UserRepository` | Repository Interface | Definir operaciones de persistencia de usuarios. | `save()`, `findById()`, `findByEmail()`, `existsByEmail()` |
| `AuthenticationService` | Domain Service Interface | Definir la validación de credenciales. | `authenticate()` |

Relaciones principales:

```text
User ───── UserId
User ───── Email
User ───── UserRole
UserRepository ───> User
AuthenticationService ───> User
```

#### 2.6.5.2. Interface Layer

Esta capa contiene las clases de presentación utilizadas para autenticación y gestión de sesión.

| **Clase** | **Tipo** | **Propósito** | **Atributos / Métodos principales** |
|---|---|---|---|
| `AuthViewModel` | ViewModel | Gestionar registro, inicio y cierre de sesión. | `uiState`; `register()`, `login()`, `logout()`, `loadCurrentUser()` |
| `AuthUiState` | UI State | Representar el estado de autenticación. | `currentUser`, `isAuthenticated`, `isLoading`, `error` |

#### 2.6.5.3. Application Layer

Esta capa coordina los flujos relacionados con registro, autenticación y sesión.

| **Clase** | **Tipo** | **Propósito** |
|---|---|---|
| `RegisterUserCommand` | Command | Contener los datos para registrar un usuario. |
| `RegisterUserCommandHandler` | Command Handler | Procesar el registro del usuario. |
| `LoginCommand` | Command | Contener las credenciales de acceso. |
| `LoginCommandHandler` | Command Handler | Procesar la autenticación del usuario. |
| `LogoutCommand` | Command | Solicitar el cierre de sesión. |
| `LogoutCommandHandler` | Command Handler | Procesar el cierre de sesión. |
| `GetCurrentUserQuery` | Query | Solicitar el usuario autenticado. |
| `GetCurrentUserQueryHandler` | Query Handler | Obtener el usuario autenticado. |

#### 2.6.5.4. Infrastructure Layer

Esta capa implementa la persistencia, autenticación y gestión de sesión mediante **Room y SQLite**.

| **Clase** | **Tipo** | **Propósito** |
|---|---|---|
| `UserRoomEntity` | Room Entity | Representar un usuario persistido. |
| `UserDao` | DAO | Realizar operaciones de persistencia de usuarios. |
| `UserRepositoryImpl` | Repository Implementation | Implementar `UserRepository` mediante Room. |
| `AuthenticationServiceImpl` | Service Implementation | Implementar la validación de credenciales. |
| `PasswordHasher` | Infrastructure Service | Generar y verificar hashes de contraseñas. |
| `SessionManager` | Infrastructure Service | Gestionar la sesión del usuario. |

<div style="page-break-after: always;"></div>

#### 2.6.5.5. Bounded Context Software Architecture Component Level Diagrams

El **Component Diagram del C4 Model** representa los componentes principales de IAM, sus responsabilidades, tecnologías e interacciones.

```text
IAM Presentation
        ↓
IAM Application
        ↓
IAM Domain
        ↓
IAM Infrastructure
        ↓
Room / SQLite
```

Tecnologías utilizadas: **Kotlin, Jetpack Compose, ViewModel, Room y SQLite**.

![IAM - Component Diagram](assets/images/chapter2/iam-component-diagram.png)

<div style="page-break-after: always;"></div>

#### 2.6.5.6. Bounded Context Software Architecture Code Level Diagrams

En esta sección se presentan los diagramas de mayor detalle de implementación del Bounded Context **IAM**.

##### 2.6.5.6.1. Bounded Context Domain Layer Class Diagrams

El UML Class Diagram representa las clases, interfaces, enumeraciones, atributos, métodos, scopes y relaciones del Domain Layer.

```text
User
--------------------------------
- id: UserId
- email: Email
- passwordHash: String
- role: UserRole
--------------------------------
+ changePassword(passwordHash: String): Unit
+ changeRole(role: UserRole): Unit


UserId
--------------------------------
- value: Long


Email
--------------------------------
- value: String
--------------------------------
+ isValid(): Boolean


<<enumeration>>
UserRole
--------------------------------
FLEET_SUPERVISOR
OPERATIONS_COORDINATOR


<<interface>>
UserRepository
--------------------------------
+ save(user: User): Unit
+ findById(id: UserId): User?
+ findByEmail(email: Email): User?
+ existsByEmail(email: Email): Boolean


<<interface>>
AuthenticationService
--------------------------------
+ authenticate(
    email: Email,
    password: String
  ): Boolean
```

Relaciones:

```text
User ───── UserId
User ───── Email
User ───── UserRole
UserRepository ───> User
AuthenticationService ───> User
```

![IAM - Domain Layer Class Diagram](assets/images/chapter2/iam-domain-class-diagram.png)

<div style="page-break-after: always;"></div>

##### 2.6.5.6.2. Bounded Context Database Design Diagram

El Database Diagram representa las tablas, columnas y constraints utilizadas para la persistencia de **IAM** mediante Room y SQLite.

| **Tabla** | **Columnas** | **Constraints** |
|---|---|---|
| `users` | `id`, `email`, `password_hash`, `role`, `created_at` | `id PK`, `email UNIQUE NOT NULL`, `password_hash NOT NULL`, `role NOT NULL` |

```text
users
--------------------------------
PK  id
    email UNIQUE NOT NULL
    password_hash NOT NULL
    role NOT NULL
    created_at NOT NULL
```

![IAM - Database Diagram](assets/images/chapter2/iam-database-diagram.png)

<div style="page-break-after: always;"></div>




### 2.6.6. Bounded Context: Profile

El Bounded Context **Profile** gestiona la información personal asociada a los usuarios de Trakto.

#### 2.6.6.1. Domain Layer

Esta capa representa las reglas de negocio relacionadas con la información del perfil del usuario.

| **Clase** | **Tipo** | **Propósito** | **Atributos / Métodos principales** |
|---|---|---|---|
| `Profile` | Aggregate Root | Representar y gestionar el perfil de un usuario. | `id`, `userId`, `firstName`, `lastName`, `phone`; `updatePersonalInformation()` |
| `ProfileId` | Value Object | Identificar un perfil. | `value` |
| `ProfileRepository` | Repository Interface | Definir las operaciones de persistencia de perfiles. | `save()`, `findById()`, `findByUserId()` |

Relaciones principales:

```text
Profile ───── ProfileId
ProfileRepository ───> Profile
```

#### 2.6.6.2. Interface Layer

Esta capa contiene las clases de presentación utilizadas para consultar y actualizar el perfil.

| **Clase** | **Tipo** | **Propósito** | **Atributos / Métodos principales** |
|---|---|---|---|
| `ProfileViewModel` | ViewModel | Gestionar las acciones relacionadas con el perfil. | `uiState`; `loadProfile()`, `createProfile()`, `updateProfile()` |
| `ProfileUiState` | UI State | Representar la información mostrada en la interfaz. | `profile`, `isLoading`, `error` |

#### 2.6.6.3. Application Layer

Esta capa coordina los flujos relacionados con la creación, consulta y actualización del perfil.

| **Clase** | **Tipo** | **Propósito** |
|---|---|---|
| `CreateProfileCommand` | Command | Contener los datos para crear un perfil. |
| `CreateProfileCommandHandler` | Command Handler | Procesar la creación del perfil. |
| `UpdateProfileCommand` | Command | Solicitar la actualización del perfil. |
| `UpdateProfileCommandHandler` | Command Handler | Procesar la actualización del perfil. |
| `GetProfileQuery` | Query | Solicitar el perfil de un usuario. |
| `GetProfileQueryHandler` | Query Handler | Obtener la información del perfil. |
| `UserRegisteredEventHandler` | Event Handler | Crear el perfil inicial cuando se registra un usuario. |

#### 2.6.6.4. Infrastructure Layer

Esta capa implementa la persistencia de Profile mediante **Room y SQLite**.

| **Clase** | **Tipo** | **Propósito** |
|---|---|---|
| `ProfileRoomEntity` | Room Entity | Representar un perfil persistido. |
| `ProfileDao` | DAO | Realizar operaciones de persistencia y consulta. |
| `ProfileRepositoryImpl` | Repository Implementation | Implementar `ProfileRepository` mediante Room. |

<div style="page-break-after: always;"></div>

#### 2.6.6.5. Bounded Context Software Architecture Component Level Diagrams

El **Component Diagram del C4 Model** representa los componentes principales de Profile, sus responsabilidades, tecnologías e interacciones.

```text
Profile Presentation
        ↓
Profile Application
        ↓
Profile Domain
        ↓
Profile Infrastructure
        ↓
Room / SQLite
```

Tecnologías utilizadas: **Kotlin, Jetpack Compose, ViewModel, Room y SQLite**.

![Profile - Component Diagram](assets/images/chapter2/profile-component-diagram.png)

<div style="page-break-after: always;"></div>

#### 2.6.6.6. Bounded Context Software Architecture Code Level Diagrams

En esta sección se presentan los diagramas de mayor detalle de implementación del Bounded Context **Profile**.

##### 2.6.6.6.1. Bounded Context Domain Layer Class Diagrams

El UML Class Diagram representa las clases, interfaces, atributos, métodos, scopes y relaciones del Domain Layer.

```text
Profile
--------------------------------
- id: ProfileId
- userId: Long
- firstName: String
- lastName: String
- phone: String
--------------------------------
+ updatePersonalInformation(
    firstName: String,
    lastName: String,
    phone: String
  ): Unit


ProfileId
--------------------------------
- value: Long


<<interface>>
ProfileRepository
--------------------------------
+ save(profile: Profile): Unit
+ findById(id: ProfileId): Profile?
+ findByUserId(userId: Long): Profile?
```

Relaciones:

```text
Profile ───── ProfileId
ProfileRepository ───> Profile
```

![Profile - Domain Layer Class Diagram](assets/images/chapter2/profile-domain-class-diagram.png)

<div style="page-break-after: always;"></div>

##### 2.6.6.6.2. Bounded Context Database Design Diagram

El Database Diagram representa las tablas, columnas y constraints utilizadas para la persistencia de **Profile** mediante Room y SQLite.

| **Tabla** | **Columnas** | **Constraints** |
|---|---|---|
| `profiles` | `id`, `user_id`, `first_name`, `last_name`, `phone` | `id PK`, `user_id UNIQUE NOT NULL`, `first_name NOT NULL`, `last_name NOT NULL` |

```text
profiles
--------------------------------
PK  id
    user_id UNIQUE NOT NULL
    first_name NOT NULL
    last_name NOT NULL
    phone
```

`user_id` permite asociar el perfil con el usuario correspondiente del Bounded Context **IAM**.

![Profile - Database Diagram](assets/images/chapter2/profile-database-diagram.png)

<div style="page-break-after: always;"></div>


