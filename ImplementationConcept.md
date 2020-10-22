# Common Legal Platform – A Concept for Implementation
[![LTA](https://img.shields.io/badge/CLP-Ecosystem-blue)](https://github.com/Liquid-Legal-Institute/Common-Legal-Platform)
[![LTA](https://img.shields.io/badge/CLP-Framework-green)](https://github.com/Liquid-Legal-Institute/Common-Legal-Platform)

Publisher: **Liquid Legal Institute e.V.**  

### Table Of Contents
- [Preface](#preface)
- [Four Layers of a CLP](#four-layers-of-a-clp)
- [A White-box View on the Foure Layers of a CLP](#a-white-box-view-on-the-foure-layers-of-a-clp)
- [Compatibility and Interoperability of Components within the same Layer ](#compatibility-and-interoperability-of-components-within-the-same-layer)
- [Compatibility and Interoperability of Components between different Layers ](#compatibility-and-interoperability-of-components-between-different-layers)
- [The Liquid Legal Institute e.V.](#the-liquid-legal-institute-ev)
- [Imprint](#imprint)

## Preface

See Preface of [CLP Principles](https://github.com/Liquid-Legal-Institute/Common-Legal-Platform/blob/main/Principles.md#preface)

## Four Layers of a CLP
![alt text](https://github.com/Liquid-Legal-Institute/Common-Legal-Platform/blob/main/images/4layers.png "Four Layers")

In accordance with the CLP Principles four different layers will be subject for implementation: 

1. Business or utilization layer
2. Application layer 
3. Data layer 
4. Technology layer 

Thereby, the layered structured follows the design principle of a modular and structured concept, that allows for compatibility and extensibility. The concept structured of layers can be found in commonly accepted approaches for modeling enterprise architectures or complex systems (see Archimate), such as the internet communication protocol (see ISO/OSI). 

Business and utilization layer offers services to customers (e.g., lawyers, law firms, in-house legal departments, public administration offices or governmental authorities), which are realized in an organization by business processes performed by business actors. 

Application layer supports the business layer with application services which are realized by (software) applications. 

Data layer harmonizes different data structures efficiently and securely, by ensuring interoperability and compatibility between different schemas and databases that are used by applications. 

Technology layer offers infrastructure services (e.g., processing, storage, and communication services) needed to run applications, realized by computer and communication hardware and system software. 

## A White-box View on the Foure Layers of a CLP  

The components and systems within the different layers the contribute to the Common Legal Platform by offering its functionalities and services in a modular way. Thereby, a white-box view on the different layers provides valuable insights for implementation.  

![alt text](https://github.com/Liquid-Legal-Institute/Common-Legal-Platform/blob/main/images/4layers_whitebox.png "Four Layers White Box View")

The white-box view unveils different components within the different layers. These cover processes and workflows, applications and (software) systems, databases and data assets, and infrastructure components. Some of those components have been identified and are listed below. 

### Business and utilization layer 

* (Innovative) Business models 
* Legal Core Processes 
* Legal Support Processes 
* Functional Management Processes 
* Office Processes 
* ... 

### Application layer 
* Collaboration and Communication System 
* Matter and Case Management System 
* Document Management System 
* Knowledge Management System 
* Client and Customer Management System 
* Calendaring and Time Tracking System 
* Court Case Management System 
* Legal Project Management System 
* Workflow Management System 
* ... 

### Data layer 
* Legal Documents 
* Knowledge (including Clauses) 
* Contracts and Policies 
* Cases and Matters 
* Customer and Clients 
* Processes and Workflows 
* Projects and Financial Matter 
* ... 

### Technology layer 
* On-prem infrastructure and services 
* Cloud infrastructure and services 

## Compatibility and Interoperability of Components within the same Layer 

Following the CLP Principles, the components within the same layer should support the consumption and provision of services and functionality: 

1. Offer non-proprietary interfaces 
2. Data exchange using standard interfaces (e.g. HTTP or REST API) 
3. Data exchange using standardized and well-documented format or schema 
4. Secure and encrypted data exchange  
5. Not every component must necessarily communicate, i.e. exchange data, with every other component, but the communication should be – in principle – be possible  
6. If required, authentication and access control using standardized mechanisms (e.g. LDAP, Single Sign-on, etc.) 

## Compatibility and Interoperability of Components between different Layers 

Following the CLP Principles, the components between different layers should follow the following principles: 

1. Encapsulate inner-working of a component  
2. Offer functionality via open and non-proprietary interfaces 
3. Data exchange using standardized and well-documented format or schema 
4. Avoid dependencies to systems outside of the CLP 
5. Minimize downward dependencies (i.e. components should have minimal dependencies to a component from a lower layer) e.g. a component from the application layer should have only the minimum of dependencies on a component from the data layer 
6. No upward dependencies (i.e. components should have no dependencies to a component from a higher layer) e.g. a component from data layer should not depend on a component from application layer 
7. Secure and encrypted data exchange  

If required, authentication and access control using standardized mechanisms (e.g. LDAP, Single Sign-on, etc.) 

## The Liquid Legal Institute e.V.
The Liquid Legal Institute e.V. is a non-profit organization incorporated as a registered association (eingetragener Verein) under the laws of Germany. Its purpose, as defined in the articles of association, is to research and promote new ways of thinking and new technologies and other innovations in the legal ecosystem, i.e. so-called Legal Transformation. It is made up of members who belong to different stakeholder groups, including corporates, law firms, legal tech start-ups and individuals. 

> For more information about us and about what drives us visit www.liquid-legal-institute.org

## Imprint
Liquid Legal Institute e.V.  
Munich (Germany)

Office address:  
Almenrausch 25, 85521 Ottobrunn, Germany  
E-Mail: info@liquid-legal-institute.org

Management board in the terms of § 26 BGB: Kai Jacob (Chairperson), Dierk Schindler, Bernhard Waltl  
Executive director: Dierk Schindler  
Register of associations: Amtsgericht München  
Registration number: VR 207699  

