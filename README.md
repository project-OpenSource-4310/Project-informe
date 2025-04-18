# Informe del Trabajo Final

<div>
  <p align="center"><img src="assets/readme/upc-logo.png" alt="UPC Icon" width=150px /></p>
  <p align="center"><b>Informe de Trabajo Final</b></p>
  <p align="center">Facultad de Ingeniería</p>
  <p align="center">Universidad Peruana de Ciencias Aplicadas</p>
  <p align="center">Desarrollo de Aplicaciones Open Source</p>
  <p align="center">4310</p>
  <p align="center">Ivan Robles Fernández</p>
  <p align="center">Startup: A.N. Team</p>
  <p align="center">Producto: AutoNexo</p>
</div>

---

## Team Members
<div align="center">
  
| **Nombre**                        | **Código** |
|-----------------------------------|------------|
| Peralta Chipa, Ronald Joel        | U202224619 |
| Céspedes Pillco, Jarod Jack       | U202318588 |
| Cardenas Minaya, Ricardo Fernando | U202310004 |
| Cruz Ibarra, Victor Andres        | U202311053 |
| Vivanco Salazar, Rafael Andres    | U202311064 |

</div>

<div>
  <p align="center"><b>Ciclo 2025 - 01</b></p>
</div>

---

# Contenido
1. __[Capítulo I: Introducción](#1-capítulo-i-introducción)__   
   1.1. [Startup Profile](#11-startup-profile)   
   &nbsp;&nbsp;&nbsp;&nbsp;1.1.1. [Descripción de la Startup](#111-descripción-de-la-startup)   
   &nbsp;&nbsp;&nbsp;&nbsp;1.1.2. [Perfiles de Integrantes del Equipo](#112-perfiles-de-integrantes-del-equipo)   
   1.2. [Solution Profile](#12-solution-profile)   
   &nbsp;&nbsp;&nbsp;&nbsp;1.2.1. [Antecedentes y Problemática](#121-antecedentes-y-problemática)   
   &nbsp;&nbsp;&nbsp;&nbsp;1.2.2. [Lean UX Process](#122-lean-ux-process)   
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.1. [Lean UX Problem Statement](#1221-lean-ux-problem-statement)   
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.2. [Lean UX Assumptions](#1222-lean-ux-assumptions)   
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.3. [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)   
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.4. [Lean UX Canvas](#1224-lean-ux-canvas)   
   1.3. [Segmentos Objetivo](#13-segmentos-objetivo)   
2. __[Capítulo II: Requirements Elicitation & Analysis](#2-capítulo-ii-requirements-elicitation--analysis)__   
   2.1. [Competidores](#21-competidores)   
   &nbsp;&nbsp;&nbsp;&nbsp;2.1.1. [Análisis Competitivo](#211-análisis-competitivo)   
   &nbsp;&nbsp;&nbsp;&nbsp;2.1.2. [Estrategias y Tácticas frente a Competidores](#212-estrategias-y-tácticas-frente-a-competidores)   
   2.2. [Estrevistas](#22-entrevistas)   
   &nbsp;&nbsp;&nbsp;&nbsp;2.2.1. [Diseño de Entrevistas](#221-diseño-de-entrevistas)   
   &nbsp;&nbsp;&nbsp;&nbsp;2.2.2. [Registro de Entrevistas](#222-registro-de-entrevistas)   
   &nbsp;&nbsp;&nbsp;&nbsp;2.2.3. [Análisis de Entrevistas](#223-análisis-de-entrevistas)   
   2.3. [Needfinding](#23-needfinding)   
   &nbsp;&nbsp;&nbsp;&nbsp;2.3.1. [User Personas](#231-user-personas)   
   &nbsp;&nbsp;&nbsp;&nbsp;2.3.2. [User Task Matrix](#232-user-task-matrix)   
   &nbsp;&nbsp;&nbsp;&nbsp;2.3.3. [User Journey Mapping](#233-user-journey-mapping)   
   &nbsp;&nbsp;&nbsp;&nbsp;2.3.4. [Empathy Mapping](#234-empathy-mapping)   
   &nbsp;&nbsp;&nbsp;&nbsp;2.3.5. [As-Is Scenario Mapping](#235-as-is-scenario-mapping)   
   2.4. [Ubiquitous Language](#24-ubiquitous-language)   
3. __[Capítulo III: Requirements Specification](#3-capítulo-iii-requirements-specification)__   
   3.1. [To-Be Scenario Mapping](#31-to-be-scenario-mapping)   
   3.2. [User Stories](#32-user-stories)   
   3.3. [Impact Mapping](#33-impact-mapping)   
   3.4. [Product Backlog](#34-product-backlog)   
4. __[Capítulo IV: Product Design](#4-capítulo-iv-product-design)__   
   4.1. [Style Guidelines](#41-style-guidelines)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.1.1. [General Style Guidelines](#411-general-style-guidelines)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.1.2. [Web Style Guidelines](#412-web-style-guidelines)   
   4.2. [Information Architecture](#42-information-architecture)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.2.1. [Organization Systems](#421-organization-systems)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.2.2. [Labeling Systems](#422-labeling-systems)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.2.3. [SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.2.4. [Searching Systems](#424-searching-systems)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.2.5. [Navigation Systems](#425-navigation-systems)   
   4.3. [Landing Page UI Design](#43-landing-page-ui-design)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.3.1. [Landing Page Wireframe](#431-landing-page-wireframes)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.3.2. [Landing Page Mock-Up](#432-landing-page-mock-ups)   
   4.4. [Web Applications UX/UI Design](#44-web-applications-ux-ui-design)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.4.1. [Web Applications Wireframes](#441-web-applications-wireframes)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.4.2. [Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.4.3. [Web Applications Mock-Ups](#443-web-applications-mock-ups)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.4.4. [Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)   
   4.5. [Web Applications Prototyping](#45-web-applications-prototyping)   
   4.6. [Domain-Driven Software Architecture](#46-domain-driven-software-architectury)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.6.1. [Software Architecture Context Diagrams](#461-software-architecture-context-diagrams)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.6.2. [Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.6.3. [Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)   
   4.7. [Software Object-Oriented Architecture](#47-software-object-oriented-architecture)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.7.1. [Class Diagrams](#471-class-diagrams)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.7.2. [Class Dictionary](#472-class-dictionary)   
   4.8. [Database Design](#48-database-design)   
   &nbsp;&nbsp;&nbsp;&nbsp;4.8.1. [Database Diagram](#481-database-diagram)   
5. __[Capítulo V: Product Implementation, Validation & Deployment](#5-capítulo-v-product-implementation-validation--deployment)__   
   5.1. [Software Configuration Management](#51-software-configuration-management)   
   &nbsp;&nbsp;&nbsp;&nbsp;5.1.1. [Software Development Environment Configuration](#511-software-development-environment-configuration)   
   &nbsp;&nbsp;&nbsp;&nbsp;5.1.2. [Source Code Management](#512-source-code-management)   
   &nbsp;&nbsp;&nbsp;&nbsp;5.1.3. [Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)   
   &nbsp;&nbsp;&nbsp;&nbsp;5.1.4. [Software Deployment Configuration](#514-software-deployment-configuration)   
   5.2. [Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)   
   
   
