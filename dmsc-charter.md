## **DMSC(Dynamic Multi-agent Secured Collaboration) WG Charter**

### **1. Introduction**

With the rapid emergence of diverse AI agents and various use cases, especially that are described in 3GPP(SA1 R20 Study on 6G Use Cases and Service Requirements(TR 22.870)) , a critical challenge arose is to enable dynamic collaboration among these agents to perform complex tasks on behalf of end-users. At the same time, there is a growing need to ensure that such collaboration is scalable, manageable, operational and secure.
Service providers and cloud operators face the task of designing and optimizing a comprehensive communication architecture that enables secure and efficient collaboration between heterogeneous AI agents, ensuring the following:

* AI Agent Gateway based, distributed agent registration and identification.
* Discovery of suitable peer agents via the AI Agent Gateway.
* Agents registration and capabilities information synchronize among the distributed AI Agent Gateways within the same domain.
* Inter-domain AI Agents related information exchange and trust establishment, including semantic interoperability for agent capabilities, intents, tasks, and context across gateways and domains
* Sustained high performance and operational visibility for the AI Agents communication.

To address these challenges, the Dynamic, Multi-Agent, Secured Collaboration (DMSC) working group will explore solutions for defining interoperable protocols and mechanisms that enables AI agents to collaborate effectively in complex human-driven tasks. This work will focus on core aspects of collaboration—such as distributed agent registration, discovery, request coordination, and secure inter‑agent communication

### **2. Scope**

The DMSC working group will focus on the following areas:

 1) Use cases and scenarios: <br>
    Identifying critical use cases for multi-agent collaboration, including AI agents used in complex tasks that span multi AI-agent Gateway within one domain and across multiple domains.

 2) Infrastructure architecture:<br> 
    Proposing an infrastructure architecture for AI-agent gateway based agents collaboration, including key functional components and interfaces.

 3) Framework of protocol suite: <br>
    Framework for the protocol composite required for AI Agent Gateway based agent-to-agent collaboration.
    
 4) Cross‑domain interoperability:<br>
    Defining mechanisms to support seamless collaboration among AI agents operating across different networks, administrative domains, and platforms,, including semantic interoperability and related validation requirements for cross-domain collaboration.

 6) Scalability and performance:<br>
    Ensuring the solution scales to handle large numbers of agents and transactions, without compromising performance.

 7) Sustained high performance and operational visibility:<br> 
    Addressing the management of agents in AI Agent Gateway-based infrastructure, including scalable operational and administrative protocols for monitoring, troubleshooting the process of collaboration task.

 8) Security and trust:<br> 
    Analysize the security requirement among AI Agent communication to ensuring that the collaboration mechanisms uphold security and trustworthiness, particularly in open environments where agents of different types and from different providers may interact.


### **3. Out of Scope**

To clearly define the boundaries of this group, this working group will not:
* Specify AI agent decision‑making, learning algorithms, or cognitive reasoning.
* Define application‑level user interfaces or interaction models for AI agents.

### **4. Deliverables**

The working group will deliver the following outcomes:

1) Use Case and Requirements Document:<br> 
   A document detailing representative use cases, scenarios, and the functional and non-functional requirements for the AI Agent Gateway based dynamic multi-agent collaboration.

2) Architecture Documents:<br> 
   The documents describing the infrastructure and protocol suites for enabling collaboration among AI agents via the AI Agent Gateway, focusing on dynamic registration, gateway capability directory functions, AI Agent gateway synchronization, semantic and other interoperability aspects, and security.

3) Protocol Specifications:<br> 
   Specifications for key protocols to enable dynamic AI agent gateway based registration, discovery, semantic profile carriage, gateway capability directory synchronization, request routing, and secure communication.

4) Security Considerations:<br> 
   A document outlining security challenges and solutions, particularly in heterogeneous, multi-agent environments.

5) Operational visibility:<br> 
   The documents on best practices for managing, maintaining and monitor AI agents performance in collaborative environments.

### **5. Proposed Milestones**

* Milestone 1: Identify use cases, requirements, and essential features for AI agent gateway based multi-agent collaboration (6 months).
* Milestone 2: Develop and propose the architecture for dynamic, AI agent gateway based multi-agent collaboration (12 months).
* Milestone 3: Draft protocol specifications for AI agent gateway based registration, discovery, and information synchronize (18 months).
* Milestone 4: Address scalability, OAM challenges and security requirements, propose a set of best practices (24 months).

### **6. IETF Area and Relation to Other Work**

The DMSC working group will primarily operate within the Applications Area, with close collaboration with other IETF working groups in Routing and Securities area on information synchronize among the AI Agent gateway and related security concerns.

### **7. Security Considerations**

Security is a critical aspect of AI agent gateway based multi-agent collaboration. The working group will place significant emphasis to ensure secure communication, trustworthiness, and authorization among agents, as well as the confidentiality and integrity of the data they process. Specifically, this includes:
* Secure agent registration and identity verification
* Encryption for agent-to-agent communication
* Robust trust models for heterogeneous agents
* Protection against common security threats, such as spoofing and man-in-the-middle attacks

### **8. Related Works**
The DMSC working group will leverage existing IETF protocols and standards where applicable, including:
* OAuth 2.0 for secure authorization
* DTLS or TLS for secure communications
* Routing Protocol extensions for agent information advertisement
* IETF YANG models for AI agent gateway management

The working group will aim to fill this gap with a unified approach tailored to the needs of heterogeneous AI agents’ collaboration systems.
