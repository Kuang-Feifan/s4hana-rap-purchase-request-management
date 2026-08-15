# System Architecture - SAP S/4HANA AI Portfolio


## Overview

## Overview

This project follows a modern SAP S/4HANA development architecture based on SAP Clean Core principles.

The core application architecture is built using:

* ABAP Cloud
* Core Data Services (CDS)
* RESTful Application Programming Model (RAP)
* OData V4
* Fiori Elements

The architecture is designed to provide a clean, cloud-ready, and extensible foundation for integrating AI capabilities into SAP business processes.



## Architecture Diagram
+-----------------------------+
|      Fiori Elements         |
|        UI Layer             |
+-----------------------------+
              |
              | OData V4
              v
+-----------------------------+
|   RAP Business Object       |
|     Application Layer       |
+-----------------------------+
              |
              v
+-----------------------------+
|       CDS View Entity       |
|       Data Model Layer      |
+-----------------------------+
              |
              v
+-----------------------------+
|        S/4HANA Data         |
|      Persistence Layer      |
+-----------------------------+


        AI Integration Layer
+-----------------------------+
|     AI-enabled Services     |
|   AI / LLM Integration      |
+-----------------------------+


## Development Principles


### Clean Core

### Clean Core

The application follows SAP Clean Core principles to ensure that business logic remains upgrade-safe, maintainable, and extensible.

Key principles include:

* Avoid modifications to SAP standard objects
* Use released SAP APIs and extension points
* Keep custom development isolated from the SAP standard
* Prefer cloud-ready and upgrade-stable development approaches



### RAP Approach

The application is developed using:

- Data modeling with CDS
- Behavior definition
- Service exposure
- Fiori Elements UI

