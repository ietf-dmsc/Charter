## **DMSC(Dynamic Multi-agent Secured Collaboration) WG Charter**

### **1. Introduction**

With the rapid emergence of diverse AI agents and various use cases, especially that are described in 3GPP(SA1 R20 Study on 6G Use Cases and Service Requirements(TR 22.870)) , a critical challenge arose is to enable dynamic collaboration among these agents to perform complex tasks on behalf of end-users. At the same time, there is a growing need to ensure that such collaboration is scalable, manageable, operational and secure.<br>
Service providers and cloud operators face the task of designing and optimizing a comprehensive communication architecture that enables secure and efficient collaboration between heterogeneous AI agents, ensuring the following:<br>

* AI Agent Gateway based, distributed agent identification, capability advertisement, and reachability.<br>
* Capability based peer agent selection and request forwarding via the AI Agent Gateway.<br>
* Synchronization or exchange of agent capability information among distributed AI Agent Gateways within the same domain, including support for existing agent metadata representation approaches (e.g., agent cards).<br>
* Inter-domain AI Agents information exchange and trust establishment, including interoperable capability representation and policy exchange across gateways and domains to support secure agent collaboration and forwarding <br>
* Operational visibility, observability, and policy control for AI agent communications and collaboration flows.<br>

To address these challenges, the Dynamic, Multi-Agent, Secured Collaboration (DMSC) working group will explore solutions for defining interoperable protocols and mechanisms that enables AI agents to collaborate effectively in complex human-driven tasks. This work will focus on interoperable mechanisms for agent capability exposure, forwarding, coordination, and secure communication, while allowing flexibility for different agent metadata representation models and deployment architectures (e.g., agent-card-based approaches) <br>

### **2. Scope**

The DMSC working group will focus on the following areas:<br>

 1) Use cases and Requirements: <br>
    Identifying critical use cases for multi-agent collaboration, including AI agents used in complex tasks that span multiple AI-agent Gateways.<br>

 2) AI Agent collaboration protocol suite and necessary specific protocols: <br>
    Protocol blocks required for AI Agent Gateway based agent-to-agent collaboration.<br>

 3) Operational visibility:<br>
    Addressing the management of agents in AI Agent Gateway-based infrastructure, including administrative protocols for monitoring, troubleshooting the process of collaboration task etc.<br>

After the stabilization of the above standards, the DMSC working group can extend to consider the following aspects:<br>
    Cross‑domain interoperability:<br>
    Defining mechanisms to support seamless collaboration among AI agents operating across different networks, administrative domains, and platforms, including semantic interoperability and related validation requirements for cross-domain collaboration.<br>
 
### **3. Out of Scope**

To clearly define the boundaries of this group, this working group will not:
* Specify AI agent decision‑making, learning algorithms, or cognitive reasoning.
* Define application‑level user interfaces or interaction models for AI agents.

### **4. Deliverables**

The working group will deliver the following outcomes:

1) Use Case and Requirements Document:<br> 
   A document detailing representative use cases, and the requirements for the AI Agent Gateway based dynamic multi-agent collaboration.<br>

2) Protocol Suite Document:<br> 
   The document describing the infrastructure and protocol suites for enabling collaboration among AI agents via the AI Agent Gateway, focusing on dynamic registration, gateway capability directory functions, AI Agent gateway synchronization, semantic and other interoperability aspects, and security.<br>

3) Protocol Specifications:<br> 
   Specifications for key protocols to enable dynamic AI agent gateway based registration, discovery, semantic profile carriage, gateway capability directory synchronization etc.<br>

4) Operational visibility:<br> 
   The documents on best practices for managing, maintaining and monitor AI agents performance in collaborative environments.<br>

5) Security Considerations:<br> 
   A document outlining security challenges and solutions, particularly in heterogeneous, multi-agent environments.<br>

### **5. Proposed Milestones**

* Milestone 1: Identify use cases, requirements, and essential features for AI agent gateway based multi-agent collaboration (6 months).
* Milestone 2: Develop and propose the protocol suite for dynamic, AI agent gateway based multi-agent collaboration (12 months).
* Milestone 3: Draft protocol specifications for AI agent gateway based registration, peer selection, and information synchronization (18 months).
* Milestone 4: Address OAM challenges and security requirements, propose a set of best practices (24 months).

### **6. IETF Area and Relation to Other Work**

The DMSC working group will primarily operate within the Applications Area, with close collaboration with other IETF working groups in Routing and Securities area on information synchronize among the AI Agent gateway and related security concerns.<br>

### **7. Security Considerations**

Security is a critical aspect of AI agent gateway based multi-agent collaboration. The working group will place significant emphasis on AI agent gateway to ensure trustworthiness, and authorization among agents, as well as the confidentiality and integrity of the data they process. Specifically, this includes:
* Secure agent registration and identity verification
* Protection against common security threats, such as spoofing and man-in-the-middle attacks

### **8. Related Works**
The DMSC working group will leverage existing IETF protocols and standards where applicable, including:
* OAuth 2.0 for secure authorization
* DTLS or TLS for secure communications
* Routing Protocol extensions for agent information advertisement
* IETF YANG models for AI agent gateway management

The working group will aim to fill this gap with a unified approach tailored to the needs of heterogeneous AI agents’ collaboration systems.
