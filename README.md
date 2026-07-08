<h1 align="center">Informe del Trabajo Final</h1>

<h3 align="center">Universidad Peruana de Ciencias Aplicadas</h3>

<br/>

<div align="center">
  <img src="./Informe/assets/LogoUPC.png" alt="UPC Logo" width="200">
</div>

<br/>

<h5 align="center">Ingeniería de Software</h5>

<h5 align="center">Desarrollo de Aplicaciones Open Source - 1ASI0729 – 2610</h5>

<h5 align="center">Docente: Juan Antonio Flores Moroco</h5>

<h5 align="center">Startup: IntegraVida</h5>

<h5 align="center">Producto: GlucoSmart</h5>

## Team members:

<div align="center">

| Nombre | Código |
| :--- | :---: |
| Arias Tasayco, Jean Pool Alexander | U202414054 |
| Raymundo Villarroel, Abigail Nadhim | U202318001 |
| Estupiñan Olortegui, Juan Sebastian | U202223405 |
| Tello Murga, Javier Oswaldo | U202218387 |

</div>

<h5 align="center">Ciclo 2026-10</h5>

---

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de Modificación |
| :---: | :---: | :--- | :--- |
| 0.1 | 10/04 | Jean Arias | Definición del Startup Profile y Lean UX Assumption y Hypothesis Statement (Capítulo I). |
| 0.2 | 13/04 | Jean Arias | Desarrollo de Artefactos de Negocio: Empathy Map, Persona y Journey Map (Capítulo II). |
| 0.3 | 16/04 | Jean Arias | Especificación de requerimientos: Impact Mapping (Capítulo III). |
| 0.4 | 19/04 | Jean Arias | Desarrollo e integración de la interfaz de usuario (UI) para la Landing Page de GlucoSmart (Capítulo IV). |
| 0.5 | 19/04 | Abigail Raymundo | Creación de wireframes y mockups de alta fidelidad en Figma. |
| 0.6 | 21/04 | Jean Arias | Implementación del Sprint 1, configuración de software y despliegue (Capítulo V). |
| 0.7 | 21/04 | Abigail Raymundo | Desarrollo e integración de la UI para la Landing Page de GlucoSmart. |
| 0.8 | 21/04 | Javier Tello | Lenguaje ubicuo, estimación del Product Backlog, diagramas de clases y ERD. |
| 0.9 | 23/04 | Jose Muñoz | User Stories, diseño UX/UI, wireframes, mockups, wireflows, user flows, prototipo, Event Storming y diagramas C4. |
| 1.0 | 10/05 | Jean Arias | Implementación de servicios frontend, integración de API REST, json-server y despliegue en Firebase Hosting y Render. |
| 1.1 | 12/05 | Abigail Raymundo | Bounded context Patient Profile Management: componente, edición de perfil, mejoras visuales responsive. |
| 1.2 | 13/05 | Juan Sebastian Estupiñan | Bounded context Glucose Monitoring: registro de glucosa, historial, filtros y gráficos. |
| 1.3 | 14/05 | Javier Tello | Bounded context Appointment Management y mejoras de navegación. |
| 1.4 | 14/05 | Jose Muñoz | Servicios REST, validaciones y lógica de integración para módulos clínicos. |
| 1.5 | 25/05 | Abigail Raymundo | Correcciones de feedback AV1/TB1: reordenamiento del Product Backlog, Technical Stories, explicaciones por bounded context en Class Diagrams y Database Design, corrección de Software Configuration Management, Sprint 1 y 2. |
| 1.6 | 18/06 | Jean Arias | Implementación del Sprint 3: backend Spring Boot con arquitectura DDD + CQRS, PostgreSQL, Docker y Swagger. |
| 1.7 | 18/06 | Abigail Raymundo | Implementación del bounded context Profiles (Spring Boot) e integración frontend Angular con `/api/v1/profiles`. |
| 1.8 | 18/06 | Javier Tello | Implementación del bounded context Medical (Spring Boot) e integración frontend Appointment Management. |
| 1.9 | 18/06 | Juan Sebastian Estupiñan | Implementación del bounded context Monitoring (Spring Boot): GlucoseRecord, Alert y GlucoseRange aggregates. |
| 2.0 | 18/06 | Jose Muñoz | Implementación del bounded context Medical: Diagnosis, ClinicalReport y Appointment aggregates. |
| 2.1 | 05/07 | Jean Arias | Implementación del Sprint 4: finalización de backend, integración externa, despliegue final y validaciones. |
| 2.2 | 06/07 | Abigail Raymundo | Correcciones de feedback AV2: mejora de Lean UX Canvas, Assumptions y Hypothesis; corrección de Big Picture Event Storming y Design-Level Event Storming. |
| 2.3 | 07/07 | Javier Tello | Correcciones de feedback AV2/TB1: Container y Component Diagrams por bounded context con CQRS; mejora de Class y Database Diagrams. |
| 2.4 | 08/07 | Equipo | Validación final, videos About-the-Product y About-the-Team, conclusiones finales y anexos. |

# Project Report Collaboration Insights

- Enlace del Repositorio del Informe:
  - [https://github.com/MTS-OpenSource/InformeProyecto.git](https://github.com/MTS-OpenSource/InformeProyecto)
- Repositorio de la Landing Page:
  - [https://github.com/MTS-OpenSource/IntegraVida.git](https://github.com/MTS-OpenSource/IntegraVida)
- Repositorio del Frontend Web App:
  - [https://github.com/MTS-OpenSource/Integravida-FrontendServices.git](https://github.com/MTS-OpenSource/Integravida-FrontendServices.git)
- Repositorio del Backend (Spring Boot):
  - [https://github.com/MTS-OpenSource/IntegraVida-BackendServices.git](https://github.com/MTS-OpenSource/IntegraVida-BackendServices.git)
- Repositorio del Fake API (json-server):
  - [https://github.com/MTS-OpenSource/JsondbData.git](https://github.com/MTS-OpenSource/JsondbData.git)

## Colaboración en el Informe

<!-- TODO: Reemplazar con la descripción real de cómo se organizaron para escribir el informe en TB2 -->
Para la entrega TB2, el equipo trabajó de forma colaborativa en el repositorio `InformeProyecto`, aplicando GitFlow con ramas feature por capítulo. Cada integrante se encargó de revisar y corregir los artefactos correspondientes a su bounded context, así como de incorporar las nuevas secciones requeridas (Sprint 4, Validation Interviews, About-the-Product, About-the-Team). Se realizaron reuniones de sincronización vía Discord para validar la consistencia del documento antes de la entrega final.

<!-- TODO: Insertar captura de los analytics de commits del repositorio del informe -->
![Commits Review](./Informe/assets/commitSpring3.png)

| Integrante               |          Commits           | Cambios principales                                                          |
| :----------------------- | :------------------------: | :--------------------------------------------------------------------------- |
| Jean Pool Arias          | <!-- TODO: número real --> | Estructura general, Sprint 3 y 4, Conclusiones, About-the-Team Video, Anexos |
| Abigail Raymundo         | <!-- TODO: número real --> | Correcciones Cap I, II, III; Style Guidelines, Deployment                    |
| Javier Tello             | <!-- TODO: número real --> | Correcciones Cap IV, Class Diagrams, Database Design                         |
| Juan Sebastian Estupiñan | <!-- TODO: número real --> | Validation Interviews, About-the-Product Video                               |
|                          | <!-- TODO: número real --> |                                                                              |

---

# Contenido

- [Registro de versiones del informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introduction](#capítulo-i-introduction)
  - [1.1 Startup Profile](#11-startup-profile)
  - [1.2 Solution Profile](#12-solution-profile)
  - [1.3 Segmento Objetivo](#13-segmento-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1 Competidores](#21-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
  - [2.3 Needfinding](#23-needfinding)
  - [2.4 Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5 Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1 User Stories](#31-user-stories)
  - [3.2 Impact Mapping](#32-impact-mapping)
  - [3.3 Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1 Style Guidelines](#41-style-guidelines)
  - [4.2 Information Architecture](#42-information-architecture)
  - [4.3 Landing Page UI Design](#43-landing-page-ui-design)
  - [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
  - [4.5 Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6 Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
  - [4.7 Software Object-Oriented Design](#47-software-object-oriented-design)
  - [4.8 Database Design](#48-database-design)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1 Software Configuration Management](#51-software-configuration-management)
  - [5.2 Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1 Sprint 1](#521-sprint-1)
    - [5.2.2 Sprint 2](#522-sprint-2)
    - [5.2.3 Sprint 3](#523-sprint-3)
    - [5.2.4 Sprint 4](#524-sprint-4)
  - [5.3 Validation Interviews](#53-validation-interviews)
  - [5.4 Video About-the-Product](#54-video-about-the-product)
  - [5.5 Video About-the-Team](#55-video-about-the-team)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:  
**ABET – EAC - Student Outcome 3**

**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.

En el siguiente cuadro se describen las acciones realizadas y conclusiones por parte del grupo, que permiten sustentar el logro del ABET – EAC - Student Outcome 3.

| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Comunica oralmente con efectividad a diferentes rangos de audiencia.** | **Jean Pool Alexander Arias Tasayco**<br/>**AV1:** Participó activamente en reuniones de validación con usuarios entrevistados para presentar la propuesta de valor de GlucoSmart y recopilar retroalimentación relacionada con funcionalidades médicas y experiencia de usuario.<br/><br/>**TB1:** Lideró las reuniones de coordinación técnica del Sprint 2 explicando la arquitectura frontend, bounded contexts y despliegue de servicios a los integrantes del equipo y usuarios entrevistados.<br/><br/>**AV2:** Participó activamente en el desarrollo del backend de GlucoSmart durante el Sprint 3, implementando aggregates y endpoints para la gestión de pacientes, tratamientos y medicamentos, asegurando la correcta integración de reglas de negocio vinculadas al seguimiento clínico.<br/><br/>**Abigail Nadhim Raymundo Villarroel**<br/>**AV1:** Presentó propuestas visuales mediante wireframes y mockups de alta fidelidad para comunicar la estructura visual de la Landing Page y validar la experiencia de usuario.<br/><br/>**TB1:** Explicó el funcionamiento del módulo Patient Profile Management mostrando la interacción entre interfaces, formularios y servicios REST durante las revisiones funcionales del Sprint 2.<br/><br/>**AV2:** Explicó ante el equipo la arquitectura del bounded context Profiles implementado en Spring Boot (capas domain, application, infrastructure e interfaces) y demostró la integración del frontend Angular con los endpoints reales `/api/v1/profiles`, sustentando las decisiones de diseño DDD adoptadas.<br/><br/>**Javier Oswaldo Tello Murga**<br/>**AV1:** Expuso los artefactos de análisis como lenguaje ubicuo, historias de usuario y diagramas técnicos para comunicar la estructura del dominio del problema.<br/><br/>**TB1:** Explicó el funcionamiento del módulo Appointment Management y su integración con la arquitectura modular del frontend.<br/><br/>**AV2:** Sustentó el bounded context Medical con sus aggregates (Appointment, Diagnosis, ClinicalReport) y la integración con PostgreSQL mediante Docker, demostrando la comunicación entre contextos a través de ACL Facades.<br/><br/>**Juan Sebastian Estupiñan**<br/>**TB1:** Explicó el módulo Glucose Monitoring, el registro de glucosa, historial, filtros y gráficos médicos implementados en el frontend.<br/><br/>**AV2:** Sustentó el bounded context Monitoring (GlucoseRecord, Alert, GlucoseRange) con su implementación en Spring Boot, explicando la lógica de auto-generación de alertas.<br/><br/>**Jose Antonio Muñoz**<br/>**AV2:** Sustentó el bounded context Medical en el backend y las vistas de seguimiento clínico en el frontend.<br/><br/><!-- TODO: Agregar acciones de TB2 para cada integrante --> | El equipo ha demostrado capacidad para comunicar efectivamente los resultados del proyecto a diferentes audiencias, utilizando los canales y formatos adecuados para cada contexto: presentaciones técnicas al equipo, entrevistas con usuarios, sustentaciones síncronas y documentación escrita del informe. |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia.** | **Jean Pool Alexander Arias Tasayco**<br/>**AV1:** Elaboró secciones del informe relacionadas con Startup Profile, Lean UX, Sprint Planning y despliegue del proyecto.<br/><br/>**TB1:** Documentó la arquitectura frontend, servicios REST, configuración de despliegue y evidencias técnicas del Sprint 2.<br/><br/>**AV2:** Elaboró secciones del informe relacionadas con la implementación del backend del Sprint 3, incluyendo el desarrollo de funcionalidades para la gestión de pacientes, tratamientos y medicamentos.<br/><br/>**Abigail Nadhim Raymundo Villarroel**<br/>**AV1:** Elaboró documentación visual mediante wireframes y mockups.<br/><br/>**TB1:** Documentó el bounded context Patient Profile Management, evidencias de frontend e integración de componentes.<br/><br/>**AV2:** Documentó la implementación completa del bounded context Profiles en el backend, incluyendo la especificación de sus 4 endpoints REST y su documentación en Swagger UI.<br/><br/>**Javier Oswaldo Tello Murga**<br/>**AV1:** Desarrolló documentación relacionada con historias de usuario, criterios de aceptación y diagramas técnicos.<br/><br/>**TB1:** Documentó funcionalidades de Appointment Management.<br/><br/>**AV2:** Documentó el bounded context Medical (Appointment, Diagnosis, ClinicalReport) y los diagramas de base de datos por bounded context.<br/><br/>**Juan Sebastian Estupiñan**<br/>**TB1:** Documentó funcionalidades del módulo Glucose Monitoring.<br/><br/>**AV2:** Documentó el bounded context Monitoring y las pruebas realizadas.<br/><br/><!-- TODO: Agregar acciones de TB2 para cada integrante --> | La elaboración del presente informe demuestra la capacidad del equipo para comunicar por escrito de manera estructurada y técnica, utilizando el formato Markdown con tablas, diagramas y referencias bibliográficas. Se evidencia una mejora continua en la calidad de la documentación a lo largo de las entregas. |

---

# Capítulo I: Introduction

## 1.1 Startup Profile

IntegraVida es una startup tecnológica del sector HealthTech nacida con la ambición de transformar radicalmente el paradigma del manejo de enfermedades crónicas, con un enfoque inicial en la diabetes. Nos definimos como una organización orientada a la innovación que desarrolla ecosistemas de software abiertos, rompiendo con las limitaciones de las soluciones propietarias y cerradas que fragmentan la información médica.

Nuestra propuesta de valor reside en la interoperabilidad y la democratización de los datos de salud. A través del uso de arquitecturas distribuidas y modernas, IntegraVida conecta a pacientes, especialistas y sistemas de farmacovigilancia en una red de colaboración en tiempo real.

**Misión:** Empoderar a pacientes que conviven con enfermedades crónicas a través de soluciones de software de código abierto de alto rendimiento, diseñadas para facilitar una gestión integral, autónoma y segura de su salud.

**Visión:** Consolidarnos para el año 2030 como la plataforma referente a nivel mundial en el ecosistema de salud abierta, convirtiéndonos en el núcleo digital estándar para la atención médica personalizada.

### 1.1.1 Descripción de la Startup

**IntegraVida** es una startup peruana del sector **HealthTech** orientada al desarrollo de soluciones digitales para el seguimiento y control de enfermedades crónicas, con un enfoque inicial en la diabetes. La empresa surge como respuesta a la fragmentación de información clínica, la baja interoperabilidad entre actores del sistema de salud y la falta de herramientas que acompañen de forma continua tanto al paciente como al profesional médico en la toma de decisiones.

Como primer producto, desarrolla **GlucoSmart**, una plataforma web que permite monitorear niveles de glucosa, registrar medicamentos, generar recordatorios, visualizar reportes y fortalecer la trazabilidad terapéutica.

### 1.1.2 Perfiles de integrantes del equipo

**Arias Tasayco, Jean Pool Alexander** — Ingeniería de Software  
Soy un estudiante apasionado por la tecnología. Me dedico a transformar ideas en soluciones digitales eficientes y escalables. Mi objetivo es utilizar mis conocimientos para resolver problemas reales y generar un impacto positivo.

**Raymundo Villarroel, Abigail Nadhim** — Ingeniería de Software  
Estudiante de 5° ciclo, apasionada por crear, diseñar y programar soluciones innovadoras. Mis habilidades incluyen creatividad, disciplina y trabajo en equipo.

**Tello Murga, Javier Oswaldo** — Ingeniería de Software  
Estudiante de 6° ciclo, responsable, perseverante y comprometido. Me interesa el desarrollo de software y la creación de soluciones digitales que resuelvan problemas reales.

**Estupiñan Olortegui, Juan Sebastian** — Ingeniería de Software  
<!-- TODO: Agregar descripción breve del perfil -->

## 1.2 Solution Profile

### 1.2.1 Antecedentes y problemática

**Who (¿A quiénes les afecta?)**  
El impacto de esta problemática es sistémico y se distribuye en tres niveles críticos:
- **Pacientes con diabetes:** Gestionan su condición con herramientas de datos fragmentados, sin visión holística de su salud.
- **Personal Médico:** Reciben datos asíncronos sin contexto, limitando ajustes terapéuticos precisos.
- **Sistemas de Salud:** Asumen el impacto financiero de complicaciones evitables.

**What (¿Cuál es el problema?)**  
Ineficiencia funcional y desarticulación de datos en el ecosistema mHealth actual. Las aplicaciones convencionales ignoran la farmacovigilancia y la trazabilidad terapéutica.

**Where (¿Dónde surge el problema?)**  
En la convergencia entre el sector salud y la ingeniería de software. Las interfaces no están ancladas a protocolos clínicos reales.

**When (¿Cuándo sucede el problema?)**  
Durante todo el ciclo de vida del tratamiento, agudizándose en el periodo ambulatorio cuando se pierde el control sobre la adherencia.

**Why (¿Por qué sucede el problema?)**  
Las herramientas actuales carecen de módulos de retroalimentación profesional y sistemas de apoyo a la decisión clínica.

**How (¿Cómo sucede el problema?)**  
A través de aplicaciones reactivas con alertas genéricas que el paciente ignora.

**How Much (¿Qué impacto tiene?)**  
A escala global, 830 millones de personas afectadas, más del 50% sin terapia adecuada. En Lima Metropolitana se identifica un mercado de alta densidad que requiere soluciones urgentes.

### 1.2.2 Lean UX Process

#### 1.2.2.1 Lean UX Problem Statements

**Problem Statement**

Actualmente, el manejo de enfermedades crónicas como la diabetes se caracteriza por la fragmentación de datos y el uso de silos de información. Las aplicaciones existentes (mHealth) se limitan al registro cuantitativo de glucosa, pero carecen de una conexión real con los protocolos clínicos y la trazabilidad terapéutica.

- **Problema:** La desarticulación de datos y la falta de alertas preventivas en el monitoreo ambulatorio de pacientes diabéticos.
- **Afectados:** Pacientes que sufren "fatiga de datos", médicos que trabajan bajo ensayo y error reactivo, y sistemas de salud que asumen altos costos por complicaciones evitables.
- **Impacto:** Los pacientes pierden el control sobre su adherencia farmacológica al salir del consultorio, impidiendo la reducción sostenida de niveles de hemoglobina glicosilada.
- **Solución:** Una infraestructura de software de código abierto que garantice la interoperabilidad y transforme los datos en activos clínicos accionables en tiempo real.

<!-- TODO: Verificar que el Problem Statement cubra domain, customer segments, pain points, gap, vision/strategy, e initial segment según la rúbrica -->

#### 1.2.2.2 Lean UX Assumptions

**Business Assumptions:**
1. Creemos que hospitales, clínicas y consultorios privados necesitan una plataforma unificada para el monitoreo integral de la diabetes, porque actualmente dependen de historiales fragmentados en papel y Excel que dificultan el seguimiento clínico.
2. Creemos que estas instituciones están dispuestas a adoptar un nuevo software si este demuestra optimizar el tiempo de consulta en al menos un 20% y reducir las complicaciones derivadas de una mala adherencia al tratamiento.
3. Creemos que el valor principal que ofrecemos es la centralización de datos clínicos (glucosa, historial de medicación, farmacovigilancia), permitiendo una toma de decisiones médicas más certera y rápida.
4. Creemos que los pacientes estarán dispuestos a compartir sus datos de salud con sus médicos a cambio de recibir un seguimiento personalizado y alertas preventivas que mejoren su calidad de vida.
5. Creemos que el modelo de negocio B2B2C (venta a instituciones, uso gratuito para pacientes referidos) generará ingresos recurrentes sostenibles en un plazo de 12 meses.

**User Assumptions:**
1. **¿Quién es el usuario?** Nuestros usuarios principales son pacientes con diabetes (tipo 1 y 2) de 18 a 65 años que requieren seguimiento constante, y doctores (endocrinólogos y médicos generales) encargados de su tratamiento.
2. **¿Dónde encaja el producto en su trabajo o vida?** Para los pacientes, encaja en su rutina diaria como herramienta para registrar niveles y recibir alertas. Para los médicos, encaja en su flujo de trabajo clínico durante y entre consultas.
3. **¿Qué problemas resuelve?** Resuelve la fragmentación de información y la falta de seguimiento de adherencia y reacciones adversas mediante un historial clínico consolidado e interactivo.
4. **¿Cuándo y cómo se usa?** El paciente lo usará diariamente para registrar medicación y glucosa. El médico lo usará durante consultas para revisar reportes y tendencias, y recibirá alertas inmediatas en caso de riesgo.

**User Outcome:** Los pacientes incrementarán su adherencia a la medicación en un 30% durante los primeros 3 meses de uso, reflejado en una reducción de sus niveles de HbA1c.

**Business Outcome:** IntegraVida alcanzará 200 pacientes monitoreados activamente y 10 médicos registrados en la plataforma durante los primeros 6 meses de operación.

**Feature Assumptions:**
1. Creemos que el registro de farmacovigilancia y reacciones adversas será una de las funcionalidades más valoradas por los doctores, ya que mejora la seguridad del paciente.
2. Creemos que el módulo de recordatorios y control de adherencia incrementará drásticamente la fidelidad de los pacientes a su tratamiento prescrito.
3. Creemos que la generación de gráficos de tendencias automáticos permitirá a los médicos optimizar el tiempo de diagnóstico y ajuste de dosis.
4. Creemos que el sistema de alertas críticas en tiempo real reducirá las hospitalizaciones por crisis de hipoglucemia severa.
5. Creemos que la funcionalidad de compartir reportes en tiempo real con el médico incrementará la retención de pacientes en la plataforma.

#### 1.2.2.3 Lean UX Hypothesis Statements

- **Hipótesis 1 (Adherencia del Paciente):** Creemos que lograremos un incremento en la adherencia a la medicación en un 30% dentro de los primeros 3 meses, si los pacientes con diabetes logran reducir sus episodios de olvido de medicación a través de un sistema automatizado de alarmas y confirmación de consumo de medicamentos.
- **Hipótesis 2 (Eficiencia Médica):** Creemos que lograremos reducir el tiempo de revisión de historial clínico en las consultas médicas en un 20%, si los endocrinólogos y médicos generales logran interpretar el estado del paciente en menos de 2 minutos mediante un dashboard interactivo con gráficas de evolución de glucosa y reportes de adherencia.
- **Hipótesis 3 (Farmacovigilancia):** Creemos que reduciremos las complicaciones de salud evitables por cambios de tratamiento inadecuados, si los médicos tratantes logran identificar rápidamente las reacciones adversas a la medicación mediante un módulo de alertas inmediatas y registros de efectos adversos vinculados a la historia clínica.
- **Hipótesis 4 (Retención de Pacientes):** Creemos que aumentaremos la retención de pacientes en el uso de la plataforma, si los pacientes con diabetes logran sentir un mayor acompañamiento médico a través de reportes en tiempo real compartidos con sus médicos.
- **Hipótesis 5 (Adopción Institucional):** Creemos que lograremos la adopción de GlucoSmart en al menos 5 clínicas privadas en el primer año, si los administradores de salud logran evidenciar una reducción en los costos operativos de seguimiento de pacientes crónicos mediante la centralización de datos clínicos.

#### 1.2.2.4 Lean UX Canvas

<!-- TODO: Reemplazar con el Lean UX Canvas actualizado que cubra todo el alcance del proyecto -->
![LeanUXCanvas](./Informe/assets/LeanUxCanvas.png)

<!-- TODO: Verificar que el Lean UX Canvas incluya todas las secciones: Business Problem, Business Outcome, Users, User Outcomes, Solutions, Hypotheses, What's the most important thing we need to learn first? -->

## 1.3 Segmento Objetivo

### 1.3.1 Segmento Primario 1: Pacientes con Diabetes Mellitus (Tipo 1 y 2)

- **Perfil Demográfico:** Hombres y mujeres de 18 a 65 años, residentes en zonas urbanas con acceso a dispositivos móviles y conexión a internet.
- **Perfil Psicográfico:** Personas que buscan mayor autonomía en el manejo de su enfermedad, pero experimentan frustración por el olvido de dosis o la falta de interpretación de sus datos clínicos.
- **Necesidades Críticas:** Recordatorios de medicación, visualización clara de glucosa y HbA1c, canal para reportar efectos adversos, consejos personalizados.

### 1.3.2 Segmento Primario 2: Médicos Especialistas y Personal de Salud

- **Perfil Profesional:** Endocrinólogos, médicos generales y personal de enfermería con alta carga de pacientes con diabetes.
- **Necesidades Críticas:** Historia clínica centralizada en tiempo real, herramientas de análisis de tendencias, alertas tempranas, registro estructurado de reacciones adversas.

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1 Competidores

Para comprender el posicionamiento de **GlucoSmart** en el mercado de la salud digital, se ha realizado un análisis competitivo identificando a los principales actores actuales que ofrecen soluciones para el manejo de la diabetes.

### 2.1.1 Análisis competitivo

| **Perfil** | **IntegraVida (GlucoSmart)** | **mySugr** | **SocialDiabetes** | **Glucose Buddy** |
| :--- | :--- | :--- | :--- | :--- |
| **Overview** | Plataforma integral B2B2C con enfoque en farmacovigilancia. | App móvil con gamificación para pacientes. | Plataforma certificada para interconexión de dispositivos. | Diario digital para seguimiento de glucosa. |
| **Ventaja Competitiva** | Centralización de historial clínico y alertas de reacciones adversas. | Interfaz intuitiva y gamificación. | Alta compatibilidad con hardware médico y certificación CE. | Simplicidad de uso y base de datos de alimentos. |
| **Mercado Objetivo** | Clínicas, hospitales, endocrinólogos y pacientes crónicos. | Pacientes con diabetes tipo 1 y 2. | Usuarios avanzados con dispositivos médicos. | Usuarios que buscan registro manual sencillo. |
| **Estrategias de Marketing** | Venta directa a instituciones y marketing de contenidos médicos. | Alianzas con farmacéuticas (Roche) y App Stores. | Certificaciones médicas y prescripción profesional. | Modelo Freemium con publicidad. |
| **Productos & Servicios** | Dashboard médico, App pacientes, Farmacovigilancia. | Diario de azúcar, calculadora de bolos, reportes. | Registro de carbohidratos, conector nube, telemedicina. | Diario de glucosa, presión arterial y peso. |
| **Precios & Costos** | SaaS por suscripción institucional. | Gratis / Suscripción Pro. | Suscripción mensual/anual. | Gratuito con anuncios / Premium. |
| **Canales de Distribución** | Web (Panel Médico) y Móvil (Paciente). | Móvil (iOS/Android). | Web y Móvil. | Móvil (iOS/Android). |

#### Análisis SWOT (FODA)

**1. IntegraVida**
- **Fortalezas:** Base de datos relacional robusta, enfoque único en farmacovigilancia, interoperabilidad médico-paciente.
- **Debilidades:** Marca nueva en el mercado, dependencia de adopción institucional.
- **Oportunidades:** Digitalización del sector salud, falta de herramientas que consoliden reacciones adversas.
- **Amenazas:** Regulaciones estrictas sobre datos de salud.

**2. mySugr**
- **Fortalezas:** Gran base de usuarios, respaldo de Roche, excelente UX.
- **Debilidades:** Poca profundidad en farmacovigilancia para el médico.
- **Oportunidades:** Expansión a mercados emergentes.
- **Amenazas:** Nuevas apps con IA que automaticen el registro.

**3. SocialDiabetes**
- **Fortalezas:** Certificaciones sanitarias europeas, conectividad con hardware médico.
- **Debilidades:** Costo elevado para clínicas pequeñas.
- **Oportunidades:** Alianzas con sistemas de salud pública.
- **Amenazas:** Competencia de fabricantes de glucómetros.

**4. Glucose Buddy**
- **Fortalezas:** Facilidad de uso, marca establecida.
- **Debilidades:** Funcionalidades limitadas para uso médico profesional.
- **Oportunidades:** Mejora de plataforma web para telemedicina.
- **Amenazas:** Migración de usuarios a apps más especializadas.

### 2.1.2 Estrategias y tácticas frente a competidores

1. **Diferenciación Técnica:** Implementar reportes automáticos de farmacovigilancia que los competidores no poseen.
2. **Alianzas Institucionales:** Ofrecer Dashboard de Gestión gratuito para el médico por pacientes referidos.
3. **Contenido y Confianza:** Publicar casos de estudio sobre reducción de errores de prescripción.
4. **Optimización de Canales:** Fortalecer la plataforma Web con visualizaciones de datos complejas orientadas al consultorio.

<!-- TODO: Mejorar Estrategias y Tácticas según feedback — incluir matriz detallada con acciones específicas frente a cada competidor -->

## 2.2 Entrevistas

### 2.2.1 Diseño de entrevistas

**Segmento 1: Pacientes con Diabetes**

1. ¿Cómo describes tu experiencia diaria gestionando tu diabetes con las herramientas actuales?
2. ¿Has sentido fatiga de datos al registrar manualmente tus niveles de glucosa?
3. ¿Qué tan difícil es mantener la adherencia a tus medicamentos fuera del consultorio?
4. ¿Las apps actuales te brindan alertas preventivas realmente útiles?
5. ¿Has ignorado notificaciones de salud por considerarlas irrelevantes?
6. ¿Te resultaría valioso cruzar tus registros de glucosa con los horarios de medicación?
7. ¿Qué opinas de que tu médico vea tus datos en tiempo real?
8. ¿Estarías dispuesto a usar una app que garantice la seguridad de tu información médica?
9. ¿Cómo mejoraría tu calidad de vida tener una visión completa de tu tratamiento en una sola app?
10. ¿Qué función de GlucoSmart resolvería mejor tus problemas diarios?
11. ¿Qué otras funciones te gustaría agregar?
12. ¿Usarías GlucoSmart como herramienta principal si estuviera disponible hoy?

**Segmento 2: Doctores**

1. ¿Qué tan complicado es realizar ajustes terapéuticos con datos manuales del paciente?
2. ¿Los silos de información dificultan obtener una visión precisa del paciente?
3. ¿Cómo afecta recibir datos asíncronos sin contexto clínico?
4. ¿Has sentido que tu tratamiento se basa en ensayo y error por falta de trazabilidad?
5. ¿Qué importancia le das a la brecha entre lo que recetas y lo que el paciente consume?
6. ¿Crees que una app facilitaría la integración de datos entre instituciones?
7. ¿Qué valor le darías a herramientas de analítica en tiempo real?
8. ¿Cómo podría una app mejorar la precisión en el seguimiento de enfermedades crónicas?
9. ¿Te interesaría una plataforma que conecte farmacovigilancia con variaciones glicémicas?
10. ¿Cómo evaluarías una solución diseñada según protocolos clínicos reales?
11. ¿Crees que los datos accionables en tiempo real reducirían complicaciones severas?
12. ¿Integrarías GlucoSmart en tu flujo de trabajo clínico?

### 2.2.2 Registro de entrevistas

<!-- TODO: Expandir con más entrevistas (3-5 por segmento) y mejorar los resúmenes -->
<!-- NOTA: Para cada entrevista incluir: nombre, apellidos, edad, distrito, screenshot del video, URL de Microsoft Stream, timing de inicio y duración -->

**Entrevista a Paciente 01**
- **Nombre:** Jorge
- **Apellidos:** Quispe
- **Edad:** 19 años
- **Distrito:** San Miguel

![Entrevista 1](./Informe/assets/CapturaEntrevista1.png)

[Enlace al video](https://youtu.be/siAso9B_aSc)

**Resumen:** La entrevista fue realizada a Jorge Quispe, de 19 años, diagnosticado con diabetes tipo 2 hace 7-8 años. Mide su glucosa diariamente por las mañanas. En el último mes tuvo dos episodios de hiperglucemia. Usa metformina y glibenclamida. Olvida ocasionalmente una dosis (1-2 veces al mes). Reporta mareos como efecto secundario leve. Hace actividad física 3 veces por semana. El estrés afecta sus niveles de glucosa. Le gustaría recibir recordatorios, ver gráficos de evolución, y tener un chat con profesionales. Está dispuesto a compartir datos con su médico.

**Entrevista a Paciente 02**
- **Nombre:** Virgilia
- **Apellidos:** Velasque Huarcalla
- **Edad:** 49 años
- **Distrito:** Callao

![Entrevista 2](./Informe/assets/CapturaEntrevista2.png)

[Enlace al video](https://youtu.be/RhP6C_cGmqs)

**Resumen:** Virgilia fue diagnosticada con diabetes tipo 2 hace 15 años. Mide su glucosa cada 2-3 meses. Ha tenido dos episodios de hipoglucemia. Usó metformina por 10 años con ardor gástrico, cambió de medicación hace 6 meses. Hace 6 años que cumple al pie de la letra el tratamiento. Hace ejercicio con pesas. Su dieta es alta en proteínas y verduras. El estrés le genera descompensaciones. Le interesan las alarmas, los gráficos de evolución y las citas virtuales personalizadas.

**Entrevista a Paciente 03**
- **Nombre:** Andy Jermy Ascalla Venancio
- **Edad:** 18 años
- **Distrito:** San Martin de Porres

![Entrevista 3](./Informe/assets/CapturaEntrevista3.png)

[Enlace al video](https://youtu.be/rn8sOZuT5MM)

**Resumen:** Andy fue diagnosticado con diabetes tipo 1 hace 5 años. Mide su glucosa diariamente. En el último mes tuvo dos episodios de hiperglucemia. Usa metformina y glibenclamida. Olvida dosis 1-2 veces al mes. Reporta mareos como efecto secundario. Hace actividad física 3 veces por semana. El estrés afecta su glucosa. Le gustaría recibir recordatorios y ver gráficos de evolución.

**Entrevista a Médico 01**
- **Nombre:** Walter
- **Apellidos:** Gomez Navarro
- **Edad:** 70 años
- **Distrito:** La Molina

![Entrevista 4](./Informe/assets/CapturaEntrevista4.png)

[Enlace al video](https://youtu.be/O9gIC_WXCfg)

**Resumen:** Médico con 40 años de experiencia. Atiende 5 pacientes diabéticos mensuales. Considera la HbA1c como estándar internacional. La historia clínica es la unidad central, complementada con Excel. Señala que la adherencia es un problema frecuente: olvidos aislados pueden desencadenar hiperglucemia y coma. Considera esencial recibir alertas inmediatas de hipoglucemia. Ver tendencias gráficas es muy útil para entender la evolución del paciente rápidamente.

<!-- TODO: Agregar 1-2 entrevistas más por segmento para alcanzar 3-5 por segmento -->

### 2.2.3 Análisis de entrevistas

<!-- TODO: Mejorar con sustento estadístico (porcentajes) por segmento objetivo -->
Tras el procesamiento de las entrevistas realizadas, se han identificado los siguientes patrones críticos:

1. **Deficiencia en Adherencia (75% de pacientes):** Los pacientes jóvenes reportan olvidos mensuales. El Dr. Gómez advierte que incrementan el riesgo de coma diabético.
2. **Monitoreo Basado en Tendencias (100% de médicos):** El Dr. Gómez señala que la HbA1c y las tendencias gráficas son indicadores de calidad.
3. **Farmacovigilancia (50% de pacientes reportan efectos secundarios):** Se identificaron efectos reales (ardor gástrico, mareos). El Dr. Gómez califica las alertas como "esenciales".
4. **Colaboración y Telemedicina (100% de pacientes dispuestos a compartir datos):** Los pacientes expresaron disposición a compartir datos para consultas virtuales.
5. **Educación y Factores Externos (100% de pacientes afectados por estrés):** El estrés afecta directamente los niveles de glucosa de todos los pacientes.

## 2.3 Needfinding

<!-- TODO: Agregar introducción explicando la relación entre los artefactos (User Personas, Task Matrix, Journey Map, Empathy Map) y las principales características del análisis de entrevistas y de la competencia -->
El proceso de Needfinding se realizó con base en el análisis de las entrevistas a pacientes y médicos, así como del estudio de la competencia. A continuación se presentan los artefactos resultantes: User Personas, User Task Matrix (versión AS-IS), User Journey Maps (versión AS-IS) y Empathy Maps.

### 2.3.1 User Personas

<!-- TODO: Verificar que los User Personas se hayan elaborado en UXPressia -->
**User Persona - Segmento 1: Paciente**
![User Persona Paciente](./Informe/assets/UserPersona1.png)

**User Persona - Segmento 2: Médico**
![User Persona Médico](./Informe/assets/UserPersona2.png)

### 2.3.2 User Task Matrix

<!-- NOTA: La matriz debe estar enfocada en AS-IS (situación actual, sin la solución) -->
<!-- TODO: Verificar que las tareas reflejen lo que los usuarios hacen actualmente, NO lo que harían con GlucoSmart -->

**Introducción:** La siguiente matriz presenta las tareas que los User Personas de cada segmento objetivo realizan actualmente (AS-IS) para gestionar la diabetes. Se incluyen la frecuencia e importancia de cada tarea.

| Tarea | Paciente con Diabetes (Frecuencia) | Paciente con Diabetes (Importancia) | Médico (Frecuencia) | Médico (Importancia) |
| :--- | :---: | :---: | :---: | :---: |
| Medir nivel de glucosa con glucómetro | Diaria | Alta | — | — |
| Registrar resultados en libreta/Excel | Diaria | Alta | — | — |
| Tomar medicación según prescripción | Diaria | Muy Alta | — | — |
| Recordar horarios de medicación sin ayuda | Diaria | Alta | — | — |
| Reportar síntomas a médico en consulta | Trimestral | Media | — | — |
| Revisar historial clínico en papel/Excel | — | — | Por consulta | Muy Alta |
| Interpretar tendencias de HbA1c | — | — | Trimestral | Muy Alta |
| Ajustar tratamiento según datos disponibles | — | — | Trimestral | Alta |
| Agendar citas de seguimiento | Trimestral | Alta | Diaria | Alta |
| Comunicar efectos secundarios al médico | Ocasional | Media | Ocasional | Alta |

**Análisis:** Las tareas con mayor frecuencia para el paciente son la medición y registro de glucosa (diaria) y la toma de medicación (diaria). Para el médico, las tareas más críticas son la revisión del historial clínico y la interpretación de tendencias de HbA1c. La principal diferencia radica en que el paciente realiza tareas operativas diarias mientras que el médico realiza tareas analíticas periódicas.

### 2.3.3 User Journey Mapping

<!-- NOTA: Versión AS-IS (situación actual, sin la solución) -->
<!-- TODO: Agregar introducción que resuma el end-to-end journey que se pretende ilustrar -->
**Introducción:** El siguiente User Journey Map representa la experiencia actual (AS-IS) de un paciente con diabetes en su proceso de gestión de la enfermedad, desde el diagnóstico hasta la consulta de seguimiento.

| Etapa | Acciones | Pensamientos | Emociones | Oportunidades |
| :--- | :--- | :--- | :--- | :--- |
| **Diagnóstico** | Recibe diagnóstico, le explican tratamiento | "¿Cómo voy a recordar todo?" | Abrumado / Temor | Tutorial guiado |
| **Compra de insumos** | Compra glucómetro, tiras reactivas | "Esto es caro y complicado" | Frustración | Guía de dispositivos |
| **Registro Diario** | Mide glucosa, anota en libreta | "Ojalá hubiera una forma más fácil" | Cansancio | Automatización de registro |
| **Olvido de Dosis** | Se salta una dosis por falta de recordatorio | "Se me pasó, lo tomaré después" | Culpa / Preocupación | Recordatorios automáticos |
| **Síntoma** | Siente mareo, espera a la consulta | "¿Será por la medicina?" | Incertidumbre | Reporte inmediato al médico |
| **Consulta** | Lleva libreta desordenada al médico | "Espero que el doctor entienda mis notas" | Ansiedad | Dashboard estructurado |
| **Ajuste** | Médico modifica dosis basado en datos incompletos | "No tengo todos los datos para decidir" | Insatisfacción | Analítica de datos |

### 2.3.4 Empathy Mapping

<!-- TODO: Ampliar la redacción para que sea más detallada (feedback: "redacción muy básica") -->
**Empathy Map - Segmento 1: Paciente con Diabetes**
![Empathy Map Paciente](./Informe/assets/EmpathyMap1.png)

**Descripción:** El Empathy Map del paciente refleja una persona que constantemente piensa en su condición ("¿estará bien mi nivel?"), escucha recomendaciones generales de su médico pero también mitos de familiares, ve publicaciones en redes sociales sobre diabetes que a veces son contradictorias, y siente frustración por la cantidad de cosas que debe recordar cada día. Sus principales **pains** incluyen el costo de los insumos, la dificultad para recordar dosis y la falta de comprensión de sus datos. Sus **gains** serían tener un registro claro, sentir acompañamiento médico y recibir alertas útiles.

**Empathy Map - Segmento 2: Médico Especialista**
![Empathy Map Médico](./Informe/assets/EmpathyMap2.png)

**Descripción:** El médico piensa en cómo optimizar el tiempo limitado de consulta, escucha las quejas de los pacientes sobre la dificultad del tratamiento, ve historiales desordenados en papel, y siente que su capacidad de intervención preventiva está limitada por la falta de datos continuos. Sus principales **pains** son la falta de trazabilidad de la adherencia y el tiempo perdido organizando datos. Sus **gains** serían contar con un dashboard centralizado y alertas automáticas de riesgo.

## 2.4 Big Picture Event Storming

<!-- NOTA: El gráfico DEBE ser un Event Storming real, no un diagrama de flujo de proceso -->
<!-- TODO: Reemplazar el gráfico actual por uno que use la notación estándar de Event Storming:
       - Naranja: Domain Events
       - Azul: Commands  
       - Verde: Read Models
       - Amarillo: Actors
       - Rosado: External Systems
       - Rojo: Hot Spots / Pain Points -->
![Big Picture Event Storming](./Informe/assets/EventStorming.jpg)

El análisis de _Big Picture Event Storming_ se ha realizado con el objetivo de comprender la complejidad del dominio de la gestión de la diabetes y la farmacovigilancia. Esta dinámica nos permitió visualizar cronológicamente cómo interactúan los pacientes, los médicos y el sistema a lo largo del proceso de tratamiento.

**Leyenda:**
- **Actores (Amarillo):** Quién ejecuta la acción (Paciente, Médico, Sistema)
- **Comandos (Azul):** La intención o acción ejecutada
- **Eventos de Dominio (Naranja):** El resultado inmutable en tiempo pasado
- **Sistemas Externos (Rosado):** Servicios de terceros
- **Modelos de Lectura (Verde):** Información visualizada para decisiones
- **Hot Spots (Rojo):** Puntos de dolor y cuellos de botella

<!-- TODO: Incluir una explicación más detallada del proceso colaborativo realizado por el equipo para el Event Storming -->

## 2.5 Ubiquitous Language

El lenguaje ubicuo del proyecto **GlucoSmart** define los términos clave utilizados de manera consistente a lo largo del análisis, diseño e implementación del sistema.

**General:**
1. **Platform** — Sistema digital de GlucoSmart para centralizar información clínica.
2. **Patient** — Persona con diabetes que usa la plataforma.
3. **Doctor** — Profesional de salud que revisa la información del paciente.
4. **Diabetes Management** — Proceso de control, seguimiento y tratamiento continuo de la diabetes.
5. **Clinical Information** — Datos del estado de salud del paciente (glucosa, síntomas, medicamentos).

**Perfil de Usuario – Paciente:**
1. **Glucose Level** — Valor de concentración de glucosa en sangre.
2. **Glucose Log** — Historial de mediciones de glucosa.
3. **Medication** — Fármaco indicado al paciente.
4. **Medication Intake** — Registro de consumo de un medicamento.
5. **Symptom** — Malestar o señal física reportada.
6. **Treatment Adherence** — Nivel de cumplimiento del tratamiento.
7. **Reminder** — Notificación del sistema para recordar medicación.
8. **Alert** — Aviso emitido al detectar una situación de riesgo.
9. **Appointment** — Encuentro programado con el médico.
10. **Adverse Effect** — Reacción no deseada por medicamento.

**Perfil de Usuario – Doctor:**
1. **Clinical Review** — Análisis del doctor sobre la información del paciente.
2. **Diagnosis** — Determinación médica de la condición de salud.
3. **Prescription** — Indicación médica de medicamentos, dosis y frecuencia.
4. **Clinical Follow-up** — Supervisión periódica del estado del paciente.
5. **Therapeutic Adjustment** — Modificación del tratamiento según evolución.
6. **Medical Observation** — Anotación del doctor sobre el estado del paciente.
7. **Clinical Report** — Resumen organizado de la información clínica.
8. **Traceability** — Capacidad de seguir la evolución del paciente en el tiempo.

---

# Capítulo III: Requirements Specification

## 3.1 User Stories

En esta sección se presentan las épicas y las historias de usuario del proyecto **GlucoSmart**, incluyendo Technical Stories para los features del RESTful API. Se han definido criterios de aceptación siguiendo el formato Gherkin (Given-When-Then) y reglas de negocio donde aplica.

### Epics

| Epic ID | Título | Descripción |
| :--- | :--- | :--- |
| EP-01 | Landing Page y Captación de Usuarios | Presentar la propuesta de valor de GlucoSmart para informar y captar potenciales usuarios. |
| EP-02 | Gestión de Cuenta y Acceso | Registro e inicio de sesión seguros para acceder a la plataforma. |
| EP-03 | Perfil y Datos Clínicos del Paciente | Gestión de perfil y antecedentes clínicos. |
| EP-04 | Monitoreo y Registro de Salud | Registro y consulta de datos de salud para control continuo. |
| EP-05 | Tratamiento, Medicación y Alertas | Gestión de tratamientos, medicación y alertas. |
| EP-06 | Seguimiento Clínico del Doctor | Revisión y registro de información clínica por el médico. |
| EP-07 | Gestión de Citas Médicas | Programación y gestión de citas médicas. |
| EP-08 | RESTful API y Servicios Backend | Technical Stories para la implementación del backend. |

### User Stories

| Story ID | Título | Descripción | Criterios de Aceptación | Epic ID |
| :--- | :--- | :--- | :--- | :--- |
| US-01 | Hero section del Landing Page | Como visitante, quiero visualizar la propuesta de valor principal de GlucoSmart para comprender rápidamente el propósito de la plataforma. | **Scenario 1:** Given the visitor accesses the landing page, When the main section is displayed, Then the visitor can clearly identify the purpose of GlucoSmart and its focus on diabetes management. | EP-01 |
| US-02 | Registro de paciente | Como paciente, quiero registrarme en la plataforma para acceder a las funcionalidades de monitoreo. | **Scenario 1:** Given the patient completes the registration form with valid data (name, email, password), When the patient selects "Sign Up", Then the system creates the account and returns a JWT token. **Scenario 2:** Given the patient enters an already registered email, When the patient submits the form, Then the system displays an error "Email already registered". | EP-02 |
| US-03 | Registro de doctor | Como doctor, quiero registrarme en la plataforma para acceder a la información clínica de mis pacientes. | **Scenario 1:** Given the doctor completes the registration form with valid professional data, When the doctor selects "Sign Up", Then the system creates the account with role DOCTOR. | EP-02 |
| US-04 | Log in | Como usuario, quiero iniciar sesión con mis credenciales para acceder de forma segura a mi cuenta. | **Scenario 1:** Given the user has a registered account, When the user enters valid email and password, Then the system grants access and redirects to the dashboard. **Scenario 2:** Given the user enters invalid credentials, When the user submits the form, Then the system displays "Invalid email or password". | EP-02 |
| US-05 | Recuperación de contraseña | Como usuario, quiero recuperar mi contraseña para volver a acceder a mi cuenta. | **Scenario 1:** Given the user selects password recovery, When the user enters a valid email, Then the system sends a recovery link to the email. | EP-02 |
| US-06 | Cerrar sesión | Como usuario, quiero cerrar sesión para proteger mi privacidad. | **Scenario 1:** Given the user is authenticated, When the user selects "Log Out", Then the system ends the session and redirects to login. | EP-02 |
| US-07 | Crear perfil de paciente | Como paciente, quiero completar mi perfil personal y clínico. | **Scenario 1:** Given the patient accesses the profile section, When the patient completes required information, Then the system stores the profile successfully. | EP-03 |
| US-08 | Editar perfil de paciente | Como paciente, quiero actualizar mis datos personales y clínicos. | **Scenario 1:** Given the patient has a registered profile, When the patient edits and saves changes, Then the system updates the information. | EP-03 |
| US-09 | Registrar antecedentes médicos | Como paciente, quiero registrar mis antecedentes médicos. | **Rule:** El paciente debe tener un perfil creado para registrar antecedentes. Each antecedent must include description and date. | EP-03 |
| US-10 | Visualizar historial de salud | Como paciente, quiero consultar mi historial de salud. | **Scenario 1:** Given the patient has health records, When the patient accesses the history section, Then the system displays records organized chronologically. | EP-03 |
| US-11 | Consultar perfil y datos clínicos | Como paciente, quiero visualizar mi información consolidada. | **Scenario 1:** Given the patient accesses the profile section, When the patient requests to view data, Then the system displays personal and clinical data in a consolidated view. | EP-03 |
| US-12 | Registrar nivel de glucosa | Como paciente, quiero registrar mis niveles de glucosa. | **Scenario 1:** Given the patient accesses the monitoring module, When the patient enters a valid glucose value (mg/dL), date and time, Then the system stores the measurement. **Scenario 2:** Given the entered value is outside the configured safe range, When the patient saves the reading, Then the system automatically generates an alert. | EP-04 |
| US-13 | Visualizar historial de glucosa | Como paciente, quiero consultar el historial de mis mediciones. | **Scenario 1:** Given the patient has glucose records, When the patient accesses the history, Then the system displays the list paginated and sorted by date descending. | EP-04 |
| US-14 | Registrar síntomas | Como paciente, quiero registrar síntomas que presento. | **Rule:** Symptoms must include type, severity (mild/moderate/severe), date and optional notes. | EP-04 |
| US-15 | Visualizar evolución de salud | Como paciente, quiero ver un resumen de mi evolución. | **Scenario 1:** Given the patient has health data, When the patient accesses the health progress panel, Then the system displays a summary with key metrics. | EP-04 |
| US-16 | Alerta por glucosa fuera de rango | Como paciente, quiero recibir alertas cuando mi glucosa esté fuera de rango. | **Scenario 1:** Given the patient registers a glucose value outside the configured range, When the system validates the value, Then the system creates an alert with type HIGH or LOW. | EP-04 |
| US-17 | Visualizar tratamiento actual | Como paciente, quiero consultar mi tratamiento actual. | **Scenario 1:** Given the patient has an active treatment, When the patient accesses the treatment section, Then the system displays medications, doses and schedules. | EP-05 |
| US-18 | Registrar tratamiento prescrito | Como doctor, quiero registrar el tratamiento del paciente. | **Scenario 1:** Given the doctor accesses the patient's clinical profile, When the doctor enters a valid treatment plan, Then the system stores the treatment. | EP-05 |
| US-19 | Registrar toma de medicación | Como paciente, quiero registrar cada toma de medicación. | **Scenario 1:** Given the patient accesses the medication section, When the patient confirms a dose, Then the system records the intake with timestamp. | EP-05 |
| US-20 | Recibir recordatorio de medicación | Como paciente, quiero recibir recordatorios de medicación. | **Scenario 1:** Given the patient has configured medication schedules, When the scheduled time is reached, Then the system sends a notification. | EP-05 |
| US-21 | Reportar efectos adversos | Como paciente, quiero reportar efectos adversos. | **Scenario 1:** Given the patient accesses the pharmacovigilance section, When the patient records an adverse effect (medication, symptom, severity), Then the system stores the report. | EP-05 |
| US-22 | Consultar adherencia al tratamiento | Como doctor, quiero consultar la adherencia del paciente. | **Scenario 1:** Given the doctor accesses the patient's history, When the doctor reviews medication records, Then the system displays the adherence percentage. | EP-05 |
| US-23 | Revisar información clínica del paciente | Como doctor, quiero revisar la información clínica del paciente. | **Scenario 1:** Given the doctor accesses the patient record, When the doctor reviews the clinical data, Then the system displays consolidated information. | EP-06 |
| US-24 | Registrar observaciones médicas | Como doctor, quiero registrar observaciones sobre el paciente. | **Scenario 1:** Given the doctor accesses the patient record, When the doctor enters a valid observation, Then the system stores it. | EP-06 |
| US-25 | Emitir diagnóstico | Como doctor, quiero registrar un diagnóstico. | **Scenario 1:** Given the doctor accesses the patient's clinical history, When the doctor enters a valid diagnosis with code, Then the system stores it. | EP-06 |
| US-26 | Generar reporte clínico | Como doctor, quiero generar un reporte clínico del paciente. | **Scenario 1:** Given the doctor accesses the patient record, When the doctor requests a clinical report, Then the system displays a structured summary. | EP-06 |
| US-27 | Solicitar cita médica | Como paciente, quiero solicitar una cita médica. | **Scenario 1:** Given the patient accesses the appointment module, When the patient selects doctor, date and time, Then the system schedules the appointment with SCHEDULED status. | EP-07 |
| US-28 | Visualizar agenda de citas | Como usuario, quiero visualizar mis citas programadas. | **Scenario 1:** Given the user has appointments, When the user accesses the agenda, Then the system displays appointments chronologically. | EP-07 |
| US-29 | Navegación por Landing Page | Como visitante, quiero navegar entre secciones del landing page. | **Scenario 1:** Given the visitor is on the landing page, When the visitor clicks a navigation link, Then the page scrolls smoothly to the corresponding section. | EP-01 |
| US-30 | Información de la Startup | Como visitante, quiero ver información sobre IntegraVida. | **Scenario 1:** Given the visitor accesses the "About Us" section, When the visitor reads the content, Then the system displays startup and product info. | EP-01 |
| US-31 | Misión y visión | Como visitante, quiero leer la misión y visión. | **Scenario 1:** Given the visitor accesses the "About Us" section, When the visitor reviews the cards, Then the system displays mission and vision. | EP-01 |
| US-32 | Cambiar idioma del Landing Page | Como visitante, quiero cambiar el idioma del landing page. | **Scenario 1:** Given the visitor is on the landing page, When the visitor selects a language, Then the interface content is updated to the selected language. | EP-01 |
| US-33 | Contactar al equipo | Como visitante, quiero enviar un mensaje al equipo de soporte. | **Scenario 1:** Given the visitor completes the contact form with valid data, When the visitor selects "Send", Then the system registers/sends the message. | EP-01 |
| US-34 | Reprogramar cita médica | Como usuario, quiero reprogramar una cita. | **Scenario 1:** Given the user has a scheduled appointment, When the user selects a new valid date/time, Then the system updates the appointment. | EP-07 |
| US-35 | Cancelar cita médica | Como usuario, quiero cancelar una cita. | **Scenario 1:** Given the user has a scheduled appointment, When the user selects "Cancel", Then the system changes status to CANCELLED. | EP-07 |
| US-36 | Recibir recordatorio de cita | Como usuario, quiero recibir recordatorios de citas. | **Scenario 1:** Given the user has an upcoming appointment, When the appointment date approaches, Then the system sends a reminder. | EP-07 |

### Technical Stories

| Story ID | Título | Descripción | Criterios de Aceptación | Epic ID |
| :--- | :--- | :--- | :--- | :--- |
| TS-01 | Configurar json-server | Como developer, necesito configurar un servidor fake con json-server que exponga los endpoints necesarios para el frontend. | **Scenario 1:** Given the json-server is running, When a GET request is sent to any endpoint, Then the server returns the corresponding data from db.json. | EP-08 |
| TS-02 | Endpoints CRUD /users | Como developer, necesito endpoints GET y POST /users para login y registro. | **Scenario 1:** Given a POST request to /users with valid body, When the server processes it, Then it returns 201 with the created user. **Scenario 2:** Given a GET request to /users with email query, When the server processes it, Then it returns the matching user. | EP-08 |
| TS-03 | Endpoints CRUD /patients | Como developer, necesito endpoints de gestión de perfil de paciente. | **Scenario 1:** Given a GET request to /patients/:id, When the patient exists, Then it returns 200 with patient data. **Scenario 2:** Given a PUT request to /patients/:id, When the body is valid, Then it returns 200 with updated data. | EP-08 |
| TS-04 | Endpoints CRUD /glucose_records | Como developer, necesito endpoints de gestión de registros de glucosa. | **Scenario 1:** Given a POST request to /glucose_records with valid data, When processed, Then it returns 201. **Scenario 2:** Given a GET request with patientId filter, When records exist, Then it returns the list sorted by date. | EP-08 |
| TS-05 | Endpoints CRUD /alerts | Como developer, necesito endpoints de gestión de alertas. | **Scenario 1:** Given a PATCH request to /alerts/:id with {read:true}, When processed, Then it returns 200 with updated status. | EP-08 |
| TS-06 | Endpoints /glucose_ranges | Como developer, necesito endpoints de configuración de rangos de glucosa. | **Scenario 1:** Given a GET request to /glucose_ranges?patientId=X, When range exists, Then it returns 200 with the configuration. | EP-08 |
| TS-07 | Endpoints CRUD /medications | Como developer, necesito endpoints de gestión de medicamentos. | **Scenario 1:** Given a POST request to /medications with valid body, When processed, Then it returns 201. | EP-08 |
| TS-08 | Endpoint POST /medication_intakes | Como developer, necesito endpoint de confirmación de tomas. | **Scenario 1:** Given a POST to /medication_intakes with valid body, When processed, Then it returns 201 with timestamp. | EP-08 |
| TS-09 | Configurar despliegue Firebase | Como developer, necesito desplegar el frontend en Firebase Hosting. | **Scenario 1:** Given the Angular project is built for production, When firebase deploy is executed, Then the app is accessible via the Firebase URL. | EP-08 |
| TS-10 | Configurar despliegue Render | Como developer, necesito desplegar json-server en Render. | **Scenario 1:** Given the repository has db.json and package.json, When Render builds and starts the service, Then the API is accessible via the Render URL. | EP-08 |
| TS-11 | Endpoints Spring Boot IAM | Como developer, necesito endpoints de autenticación JWT en Spring Boot. | **Scenario 1:** Given a POST to /api/v1/authentication/sign-up with valid data, When processed, Then returns 201 with JWT token. **Scenario 2:** Given a POST to /api/v1/authentication/sign-in with valid credentials, When processed, Then returns 200 with JWT token. | EP-08 |
| TS-12 | Endpoints Spring Boot Profiles | Como developer, necesito endpoints CRUD de perfiles en Spring Boot. | **Scenario 1:** Given a POST to /api/v1/profiles with valid Profile data, When processed, Then returns 201. **Scenario 2:** Given a GET to /api/v1/profiles/:id, When the profile exists, Then returns 200. | EP-08 |
| TS-13 | Endpoints Spring Boot Patients | Como developer, necesito endpoints de pacientes y tratamientos. | **Scenario 1:** Given a POST to /api/v1/patients with valid Patient data, When processed, Then returns 201. | EP-08 |
| TS-14 | Endpoints Spring Boot Monitoring | Como developer, necesito endpoints de glucosa y alertas en Spring Boot. | **Scenario 1:** Given a POST to /api/v1/glucose-records with valid data, When processed, Then returns 201 and auto-generates an alert if value is out of range. | EP-08 |
| TS-15 | Endpoints Spring Boot Medical | Como developer, necesito endpoints de diagnósticos, reportes y citas. | **Scenario 1:** Given a POST to /api/v1/appointments with valid data, When processed, Then returns 201 with SCHEDULED status. | EP-08 |
| TS-16 | Configurar Swagger/OpenAPI | Como developer, necesito documentar todos los endpoints con Swagger. | **Scenario 1:** Given the Spring Boot app is running, When accessing /swagger-ui/index.html, Then all endpoints are listed with request/response schemas. | EP-08 |
| TS-17 | Configurar Docker PostgreSQL | Como developer, necesito configurar PostgreSQL mediante Docker. | **Scenario 1:** Given docker-compose.yml is configured, When `docker compose up -d` is executed, Then PostgreSQL runs with persistent volume. | EP-08 |

## 3.2 Impact Mapping

<!-- TODO: Incluir Business Goals SMART (Specific, Measurable, Attainable, Relevant, Time-bound) -->
![Impact Mapping](./Informe/assets/ImpactMapping.jpg)

**Business Goals SMART:**
1. Alcanzar 500 pacientes registrados activos en la plataforma en los primeros 6 meses de operación.
2. Reducir en un 20% el tiempo promedio de revisión de historial clínico en consultas médicas que utilicen GlucoSmart.
3. Lograr una tasa de adherencia a la medicación del 70% en pacientes que usen el sistema de recordatorios por al menos 3 meses.

**Actors:**
- Paciente con Diabetes (Jorge - User Persona 1)
- Médico Especialista (Dr. Walter - User Persona 2)

**Impacts:**
- **Paciente:** Que registre su glucosa y confirme la ingesta de medicación diariamente; que reporte efectos adversos oportunamente.
- **Médico:** Que interprete la evolución de HbA1c en segundos; que intervenga preventivamente ante riesgos.

**Deliverables:**
- Sistema automatizado de recordatorios
- Módulo de farmacovigilancia
- Dashboard interactivo con tendencias
- Sistema de alertas críticas en tiempo real

<!-- TODO: Verificar que el Impact Mapping incluya la relación completa: Business Goals → Actors → Impacts → Deliverables → User Stories -->

## 3.3 Product Backlog

El Product Backlog ha sido priorizado en función del valor de negocio. El orden sigue la secuencia recomendada: Landing Page, CRUDs fundamentales, core de negocio, Technical Stories para RESTful API, gestión de usuarios.

**URL pública del Product Backlog:** <!-- TODO: Reemplazar con URL real del board -->
[Product Backlog en Linear](https://linear.app/aplicaciones-web/team/INT/all)

![Product Backlog](./Informe/assets/ProductBacklogLinear.png)

| # Orden | User Story ID | Título | Descripción | Story Points |
| :---: | :---: | :--- | :--- | :---: |
| 1 | US-01 | Hero section del Landing Page | Como visitante, quiero visualizar la propuesta de valor principal de GlucoSmart. | 2 |
| 2 | US-29 | Navegación por el Landing Page | Como visitante, quiero navegar fácilmente entre las secciones del landing page. | 3 |
| 3 | US-30 | Ver información de la Startup | Como visitante, quiero visualizar información sobre IntegraVida. | 2 |
| 4 | US-31 | Conocer la misión y visión | Como visitante, quiero leer la misión y visión de la startup. | 2 |
| 5 | US-32 | Cambiar idioma del Landing Page | Como visitante, quiero cambiar el idioma del landing page. | 3 |
| 6 | US-33 | Contactar al equipo | Como visitante, quiero enviar un mensaje al equipo de soporte. | 3 |
| 7 | US-02 | Registro de paciente | Como paciente, quiero registrarme en la plataforma. | 5 |
| 8 | US-03 | Registro de doctor | Como doctor, quiero registrarme en la plataforma. | 5 |
| 9 | US-04 | Log in | Como usuario, quiero iniciar sesión con mis credenciales. | 3 |
| 10 | US-06 | Cerrar sesión | Como usuario, quiero cerrar sesión de manera segura. | 1 |
| 11 | US-07 | Crear perfil de paciente | Como paciente, quiero completar mi perfil. | 5 |
| 12 | US-08 | Editar perfil de paciente | Como paciente, quiero actualizar mis datos. | 3 |
| 13 | US-11 | Consultar perfil y datos clínicos | Como paciente, quiero visualizar mi información consolidada. | 2 |
| 14 | US-12 | Registrar nivel de glucosa | Como paciente, quiero registrar mis niveles de glucosa. | 5 |
| 15 | US-13 | Visualizar historial de glucosa | Como paciente, quiero consultar mi historial de mediciones. | 3 |
| 16 | US-37 | Visualizar gráficos de glucosa | Como paciente, quiero visualizar gráficos de mis niveles de glucosa. | 5 |
| 17 | US-38 | Filtrar historial de glucosa | Como paciente, quiero filtrar mi historial por fechas. | 3 |
| 18 | US-39 | Editar registro de glucosa | Como paciente, quiero editar un registro de glucosa. | 3 |
| 19 | US-40 | Eliminar registro de glucosa | Como paciente, quiero eliminar un registro de glucosa. | 2 |
| 20 | US-16 | Alerta por glucosa fuera de rango | Como paciente, quiero recibir alertas cuando mi glucosa esté fuera de rango. | 5 |
| 21 | US-41 | Visualizar alertas generadas | Como paciente, quiero ver el historial de alertas. | 3 |
| 22 | US-42 | Configurar rango de glucosa | Como paciente, quiero configurar mis rangos personalizados. | 5 |
| 23 | US-43 | Confirmar lectura de alerta | Como paciente, quiero marcar alertas como leídas. | 2 |
| 24 | US-17 | Visualizar tratamiento actual | Como paciente, quiero consultar mi tratamiento. | 3 |
| 25 | US-19 | Registrar toma de medicación | Como paciente, quiero registrar cada toma. | 3 |
| 26 | US-55 | Visualizar resumen general | Como usuario, quiero ver un resumen de mi información. | 5 |
| 27 | TS-01 | Configurar json-server | Como developer, necesito configurar json-server. | 3 |
| 28 | TS-02 | Endpoints CRUD /users | Como developer, necesito endpoints de autenticación. | 2 |
| 29 | TS-03 | Endpoints CRUD /patients | Como developer, necesito endpoints de perfil de paciente. | 3 |
| 30 | TS-04 | Endpoints CRUD /glucose_records | Como developer, necesito endpoints de registros de glucosa. | 3 |
| 31 | TS-05 | Endpoints CRUD /alerts | Como developer, necesito endpoints de alertas. | 2 |
| 32 | TS-06 | Endpoints /glucose_ranges | Como developer, necesito endpoints de rangos de glucosa. | 2 |
| 33 | TS-07 | Endpoints CRUD /medications | Como developer, necesito endpoints de medicamentos. | 3 |
| 34 | TS-08 | Endpoint POST /medication_intakes | Como developer, necesito endpoint de tomas. | 2 |
| 35 | TS-09 | Configurar Firebase Hosting | Como developer, necesito desplegar frontend en Firebase. | 3 |
| 36 | TS-10 | Configurar Render para json-server | Como developer, necesito desplegar json-server. | 3 |
| 37 | US-05 | Recuperación de contraseña | Como usuario, quiero recuperar mi contraseña. | 3 |
| 38 | US-09 | Registrar antecedentes médicos | Como paciente, quiero registrar mis antecedentes. | 3 |
| 39 | US-14 | Registrar síntomas | Como paciente, quiero registrar síntomas. | 2 |
| 40 | US-15 | Visualizar evolución de salud | Como paciente, quiero ver resumen de evolución. | 5 |
| 41 | US-18 | Registrar tratamiento prescrito | Como doctor, quiero registrar tratamiento. | 5 |
| 42 | US-20 | Recibir recordatorio de medicación | Como paciente, quiero recibir recordatorios. | 5 |
| 43 | US-21 | Reportar efectos adversos | Como paciente, quiero reportar efectos adversos. | 3 |
| 44 | US-22 | Consultar adherencia | Como doctor, quiero consultar adherencia del paciente. | 5 |
| 45 | US-23 | Revisar info clínica del paciente | Como doctor, quiero revisar información clínica. | 5 |
| 46 | US-24 | Registrar observaciones médicas | Como doctor, quiero registrar observaciones. | 3 |
| 47 | US-25 | Emitir diagnóstico | Como doctor, quiero registrar diagnóstico. | 3 |
| 48 | US-26 | Generar reporte clínico | Como doctor, quiero generar reporte clínico. | 5 |
| 49 | US-27 | Solicitar cita médica | Como paciente, quiero solicitar cita. | 5 |
| 50 | US-28 | Visualizar agenda de citas | Como usuario, quiero ver mis citas. | 3 |
| 51 | US-34 | Reprogramar cita médica | Como usuario, quiero reprogramar cita. | 3 |
| 52 | US-35 | Cancelar cita médica | Como usuario, quiero cancelar cita. | 2 |
| 53 | US-36 | Recordatorio de cita | Como usuario, quiero recibir recordatorio de cita. | 3 |
| 54 | US-44 | Visualizar efectos adversos | Como paciente, quiero consultar efectos adversos. | 3 |
| 55 | US-45 | Evaluar efectos adversos | Como doctor, quiero analizar efectos reportados. | 5 |
| 56 | US-46 | Dashboard de pacientes | Como doctor, quiero listado de mis pacientes. | 5 |
| 57 | US-47 | Buscar paciente | Como doctor, quiero buscar pacientes. | 3 |
| 58 | US-48 | Evolución gráfica del paciente | Como doctor, quiero gráficos de evolución. | 5 |
| 59 | US-49 | Actualizar tratamiento | Como doctor, quiero modificar tratamiento. | 5 |
| 60 | US-50 | Compartir información clínica | Como paciente, quiero compartir info con mi doctor. | 3 |
| 61 | US-10 | Visualizar historial de salud | Como paciente, quiero consultar mi historial. | 3 |
| 62 | TS-11 | Endpoints Spring Boot IAM | Como developer, necesito endpoints JWT. | 5 |
| 63 | TS-12 | Endpoints Spring Boot Profiles | Como developer, necesito endpoints de perfiles. | 5 |
| 64 | TS-13 | Endpoints Spring Boot Patients | Como developer, necesito endpoints pacientes. | 5 |
| 65 | TS-14 | Endpoints Spring Boot Monitoring | Como developer, necesito endpoints monitoreo. | 8 |
| 66 | TS-15 | Endpoints Spring Boot Medical | Como developer, necesito endpoints médicos. | 8 |
| 67 | TS-16 | Configurar Swagger/OpenAPI | Como developer, necesito documentar API con Swagger. | 3 |
| 68 | TS-17 | Configurar Docker PostgreSQL | Como developer, necesito base de datos relacional. | 3 |
