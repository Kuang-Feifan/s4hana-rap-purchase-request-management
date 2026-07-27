# System Architecture


## Overview

This project follows the modern SAP development architecture based on:

- ABAP Cloud
- CDS
- RAP
- OData V4
- Fiori Elements


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

