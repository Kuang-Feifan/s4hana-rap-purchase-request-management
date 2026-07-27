# S/4HANA RAP Purchase Request Management


## Overview

This project demonstrates a modern SAP application developed using:

- ABAP Cloud
- CDS View Entity
- RAP (RESTful Application Programming Model)
- OData V4
- Fiori Elements


The goal is to build a clean-core compliant business application following SAP's modern development approach.


---

# Business Scenario


A company needs a digital purchase request process.


Users can:

- Create purchase requests
- Maintain request items
- Submit requests
- Approve or reject requests
- Track request status


---

# Architecture
Fiori Elements

    |

OData V4 Service

    |

RAP Business Object

    |

CDS View Entity

    |

Database Tables


---

# Data Model


## Purchase Request Header

Main information:

- Request ID
- Requester
- Company Code
- Request Date
- Status


## Purchase Request Item

Detail information:

- Item Number
- Material
- Quantity
- Price


Relationship:
Purchase Request Header

      |

 Composition

      |

Purchase Request Item


---

# Development Roadmap


## Phase 1 - Data Model

Status:

🚧 Planned


- [ ] Database table design
- [ ] CDS Interface View
- [ ] CDS Projection View


## Phase 2 - RAP Business Object

Status:

⏳ Planned


- [ ] Behavior Definition
- [ ] Behavior Implementation
- [ ] Validation
- [ ] Action


## Phase 3 - Application

Status:

⏳ Planned


- [ ] Service Definition
- [ ] Service Binding
- [ ] Fiori Elements UI


## Phase 4 - AI Extension

Status:

⏳ Future


Possible scenarios:

- AI purchase request summary
- Approval recommendation
- Procurement risk analysis


---

# Technology Stack


| Technology | Purpose |
|---|---|
| ABAP Cloud | Backend development |
| CDS | Data modeling |
| RAP | Business object framework |
| OData V4 | Service exposure |
| Fiori Elements | User interface |
| SAP BTP | Cloud extension |
| AI | Intelligent scenarios |


---

# Project Status

🚧 Learning Project

