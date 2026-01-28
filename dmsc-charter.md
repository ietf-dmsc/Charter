## **DMSC(Dynamic Multi-agent Secured Collaboration) WG Charter**

### **1. Introduction**

With the rapid emergence of diverse AI agents—including host agents, device agents, network agents, and application agents—a critical challenge is to enable dynamic collaboration among these agents to perform complex tasks on behalf of end-users. At the same time, there is a growing need to ensure that such collaboration is secure, scalable, and manageable operationally.
Service providers and network operators face the task of designing and optimizing a comprehensive communication architecture that enables secure and efficient collaboration between heterogeneous AI agents, ensuring the following:

* Standardized agent registration and identification
* Discovery of suitable peer agents
* Intelligent request routing and coordination
* Secure inter-agent communication and trust establishment
* Sustained high performance and operational visibility

To address these challenges, the Dynamic, Multi-Agent, Secured Collaboration (DMSC) working group will explore solutions for defining interoperable protocols and mechanisms that enables AI agents to collaborate effectively in complex human-driven tasks. This work will focus on core aspects of collaboration—such as agent registration, discovery, request coordination, and secure inter‑agent communication

### **2. Scope**

The DMSC working group will focus on the following areas:

 1) Use cases and scenarios: 
    Identifying critical use cases for multi-agent collaboration, including AI agents used in complex tasks that span across multiple domains such as automation, decision-making, and resource management.

 2) Infrastructure architecture: 
    Proposing an infrastructure architecture for agent collaboration, including key functional components and interfaces.

 3) Collaboration mechanisms: 
    Defining collaboration mechanisms such as agent registration, peer discovery, request routing, and coordination protocols that support efficient and secure inter-agent collaboration.

 4) Cross‑domain interoperability: 
    Defining mechanisms to support seamless collaboration among AI agents operating across different networks, administrative domains, and platforms.

 5) Scalability and performance:
    Ensuring the solution scales to handle large numbers of agents and transactions, without compromising performance.

 6) Operations, Administration, and Maintenance (OAM): 
    Addressing the management of agents in DMSC-based systems, including scalable operational and administrative protocols for monitoring, troubleshooting, and upgrading agents.

 7) Security and trust: 
    Ensuring that the collaboration mechanisms uphold security and trustworthiness, particularly in open environments where agents of different types and from different providers may interact.


### **3. Out of Scope**

To clearly define the boundaries of this group, this working group will not:
* Specify AI agent decision‑making, learning algorithms, or cognitive reasoning.
* Define application‑level user interfaces or interaction models for AI agents.

### **4. Deliverables**

The working group will deliver the following outcomes:

1) Use Case and Requirements Document: 
   A document detailing representative use cases, scenarios, and the functional and non-functional requirements for dynamic multi-agent collaboration.

2) Architecture Documents: 
   The documents describing the infrastructure and protocol architecture for enabling collaboration among AI agents, focusing on communication, coordination, discovery, interoperability and security.

3) Protocol Specifications: 
   Specifications for key protocols to enable dynamic agent registration, discovery, request routing, and secure communication.

4) Security Considerations: 
   A document outlining security challenges and solutions, particularly in heterogeneous, multi-agent environments.

5) OAM Best Practices: 
   The documents on best practices for managing, maintaining and monitor AI agents performance in collaborative environments.

### **5. Proposed Milestones**

* Milestone 1: Identify use cases, requirements, and essential features for multi-agent collaboration (6 months).
* Milestone 2: Develop and propose an architecture for dynamic multi-agent collaboration (12 months).
* Milestone 3: Draft protocol specifications for registration, discovery, and request routing (18 months).
* Milestone 4: Address scalability, security, and OAM challenges, and propose a set of best practices (24 months).

### **6. IETF Area and Relation to Other Work**

The DMSC working group will primarily operate within the Applications Area, with close collaboration with other IETF working groups in Security and Routing area on interoperability, security, and agent-based systems.

### **7. Security Considerations**

Security is a critical aspect of multi-agent collaboration. The working group will place significant emphasis on ensuring secure communication, trustworthiness, and authorization among agents, as well as the confidentiality and integrity of the data they process. Specifically, this includes:
* Secure agent registration and identity verification
* Encryption for agent-to-agent communication
* Robust trust models for heterogeneous agents
* Protection against common security threats, such as spoofing and man-in-the-middle attacks

### **8. Related Works**
The DMSC working group will leverage existing IETF protocols and standards where applicable, including:
* OAuth 2.0 for secure authorization
* DTLS or TLS for secure communications
* Routing Protocol extensions for agent information advertisement
* IETF YANG models for network management

The working group will aim to fill this gap with a unified approach tailored to the needs of heterogeneous AI agents’ collaboration systems.
