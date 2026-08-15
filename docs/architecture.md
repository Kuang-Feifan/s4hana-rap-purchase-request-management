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
+----------------------+
| Fiori Elements App |
+----------------------+
|
|
OData V4
|
|
+----------------------+
| RAP Business Object |
+----------------------+
|
|
+----------------------+
| CDS View Entity |
+----------------------+
|
|
+----------------------+
| Database Tables |
+----------------------+


## Development Principles


### Clean Core

The application follows SAP Clean Core principles:

- No modification of SAP standard objects
- Use released APIs
- Cloud-ready development


### RAP Approach

The application is developed using:

- Data modeling with CDS
- Behavior definition
- Service exposure
- Fiori Elements UI

