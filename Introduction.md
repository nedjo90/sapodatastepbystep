
**OData (Open Data Protocol)**

- **Interface:** Open standard for data exchange with SAP (Systems, Applications, and Products in Data Processing) via HTTP(s) (Hypertext Transfer Protocol Secure)
- **Supported formats:** XML (Extensible Markup Language), JSON (JavaScript Object Notation)

**Key Points:**

- **Web Protocol:** Unlocks and shares data; breaks application silos
- **Serialization:** Supports JSON, Atom/XML
- **Cross-Platform:** Enables web and mobile apps; high data integration and interoperability

**SAP Netweaver Gateway**

- **Position:** Sits on SAP Application Layer
- **Role:** Gateway for external communication via HTTP

![[SAPNWGW.jpg]]


**Roles:**

- **Clients:** Consume services (query) = "Consumers"
- **Servers:** Expose services (endpoints) = "Producers"

**Advantages:**

1. **Protocols:** XML/JSON - well-known, plain text
2. **Self-Describing Messages:** No need for ABAP (Advanced Business Application Programming)/SAP knowledge

**Interaction:**

- **Server:** Hosts data and exposes endpoints (services)
- **Clients:** Call services to query/manipulate data

**OData = ODBC (Open Database Connectivity) of the web**

- Middleware for data communication
- Independent of DBMS (Database Management System)/OS (Operating System)

![[SAPNWGW-3.jpg]]

**HTTP vs. TCP/IP:**

- **HTTP (Hypertext Transfer Protocol):** Defines _what_ data is transferred (e.g., web pages)
- **TCP/IP (Transmission Control Protocol/Internet Protocol):** Defines _how_ data is transferred (reliable delivery, addressing, routing)

**Stateless:**

- Each HTTP request is independent; no server memory of previous requests

**RESTful (Representational State Transfer):**

- **REST (Representational State Transfer):** Architectural style for designing networked applications.
- **Principle:** Resource-based communication; resources are identified by URIs (Uniform Resource Identifiers).

**Core Concepts:**

- **Stateless:** Each request contains all necessary information; no client context stored by the server.
- **Client-Server:** Clear separation; clients request resources, servers provide them.
- **Cacheable:** Responses indicate if they can be cached to improve performance.
- **Uniform Interface:** Consistent, standardized interaction with resources.

**Resource Representation:**

- **Resources:** Identifiable entities like data, objects, or services (e.g., users, products, articles).
- **URI (Uniform Resource Identifier):** Unique address for each resource (e.g., `/users/123` for a user with ID 123).
- **Representation:** Resources are represented in formats like JSON, XML, or HTML.
- **Accessed via:** URIs serve as the unique address for interacting with resources.

**HTTP Methods in REST:**

- **GET:** Retrieve a resource (e.g., fetch user data).
- **POST:** Create a new resource (e.g., add a new product).
- **PUT:** Update or replace an existing resource (e.g., edit a blog post).
- **DELETE:** Remove a resource (e.g., delete a record).

**RESTful Design:**

- **Resource-Based:** Focus on resources, not actions; operations are centered on resource manipulation.
- **Operations:** Uses standard HTTP methods; no custom methods needed.
- **Client-Server Interaction:** Clients interact with resource representations, not server logic.

