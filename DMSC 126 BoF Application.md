# Name: Dynamic Multi-agent Secured Collaboration (DMSC)
## Description 
With the rapid emergence of diverse AI agents and various use cases, especially that are described in 3GPP(SA1 R20 Study on 6G Use Cases and Service Requirements(TR 22.870)) , a critical challenge arose is to enable dynamic collaboration among these agents to perform complex tasks on behalf of end-users. At the same time, there is a growing need to ensure that such collaboration is scalable, manageable, operational and secure.
Service providers and cloud operators face the task of designing and optimizing a comprehensive communication architecture that enables secure and efficient collaboration between heterogeneous AI agents, ensuring the following: <br>

- AI Agent Gateway based, distributed agent identification, capability advertisement, and reachability.<br>
- Capability based peer agent selection and request forwarding via the AI Agent Gateway.<br>
- Synchronization or exchange of agent capability information among distributed AI Agent Gateways within the same domain, including support for existing agent metadata representation approaches (e.g., agent cards). <br>
- Inter-domain AI Agents information exchange and trust establishment, including interoperable capability representation and policy exchange across gateways and domains to support secure agent collaboration and forwarding. <br>
- Operational visibility, observability, and policy control for AI agent communications and collaboration flows. <br>

To address these challenges, the Dynamic, Multi-Agent, Secured Collaboration (DMSC) working group will explore interoperable protocols and mechanisms for AI Agent Gateway-mediated collaboration, including agent capability exposure, request forwarding, coordination, synchronization, policy control, observability, and secure communication. <br>

DMSC is intended to complement related efforts such as ACP/agentproto, DAWN, A2A, Agent Cards, MCP, and similar ecosystems. It will not define a new general-purpose agent-to-agent application protocol, discovery protocol, MCP replacement, or competing agent capability card format; instead, it may use, profile, or provide gateway-mediated management around such mechanisms where applicable. <br>

## Required Details
- Status: "non-WG forming"
- Responsible AD: Charles Eckel, Andy Newton 
- BOF proponents: Aijun Wang <wangaj3@chinatelecom.cn>, Lionel Morand lionel.morand@huawei.com, Bing Liu <leo.liubing@huawei.com>, Linda Dunbar <linda.dunbar@futurewei.com>, Dinesh C. Verma <dverma@us.ibm.com>, Jun Liu <liujun@bupt.edu.cn>, Enge Song <enge.seg@alibaba-inc.com>, Lianhua Zhang <zhanglh2@asiainfo.com> <br>
- Number of people expected to attend: 100
- Length of session (1 or usually 2 hours): 2 hours
- Conflicts (whole Areas and/or WGs)
   - Chair Conflicts: TBD
   - Technology Overlap: TBD
   - Key Participant Conflict: ART AD

## Information for IAB/IESG
To allow evaluation of your proposal, please include the following items:

- Any protocols or practices that already exist in this space: <br>
  There are no standardized protocols that define how to build an operable, manageable infrastructure for AI agent collaboration via an AI agent gateway. <br>
  Various AI Agent Gateway implementations already exist, which creates a demand for standardization of communication between AI agents and their gateways, as well as synchronization across AI agent gateways. Existing emerging approaches, including Agent Card based ecosystems and open source A2A frameworks, primarily relying on centralized registration or directory mechanisms, but do not address gateway anchored agent communication, distributed gateway coordination, and operational management <br>

- Which (if any) modifications to existing protocols or practices are required: TBD
   
- Which (if any) entirely new protocols or practices are required: <br>
   The AI agent gateway based communication protocol suites,the communication between AI agents and their gateway, as well as information synchronization among AI agent gateways.

- Open source projects (if any) implementing this work: <br>
   OpenGateway: https://github.com/anAtheist987/OpenGateway <br>
   ANP: https://github.com/agent-network-protocol/AgentNetworkProtocol <br>
   AIP: https://github.com/AIP-PUB/Agent-Interconnection-Protocol-Project <br>

- Relationship with other ongoing AI agent effortrs in the IETF: <br>
  ACP: focuses mainly on the transport issues between AI agents. <br>
  DAWN: focuses mainly on the DNS based AI agents discovery now and will not involve the AI Agents Gateway. <br>

DMSC will focus on AI Agent Gateway-centric management, control-plane, and operational infrastructure for dynamic multi-agent collaboration. The working group will leverage existing industry agent description and interaction mechanisms, such as A2A Agent Cards and MCP, where applicable, rather than defining competing formats or protocols.

DMSC will not define a new general-purpose agent-to-agent application protocol or a competing agent capability card format. The work will instead focus on gateway-mediated functions, including agent registration or attachment to gateways, gateway-local agent state, policy-controlled metadata exposure, gateway-to-gateway synchronization, operational visibility, and security for gateway-mediated collaboration.


## Agenda
The DMSC BoF is intended as a non-WG-forming discussion to gather community input on whether AI Agent Gateway functions represent an Internet interoperability problem suitable for IETF standardization, to better understand deployment scenarios and requirements, and to determine the appropriate scope of potential future work.

<ol type="1">
<li> Problem Statement and Deployment Scenarios: 40 minutes </li> 
   Are AI Agent Gateways necessary? In which deployment scenarios? Do they provide value? <br> 
   Candidate Presentations: Experts from Alibaba, Unipay, and 3GPP and Huawei experts etc.  <br>  <br>
   
<li> AI agent gateway based architecture/protocol suites: 30 minutes </li> 
   Do they require a fundamentally new architecture for AI Agents?  <br>
   Candidate Presentations: Experts from China Telecom, CAS etc.  <br>  <br>
   
<li> Relationship to Existing Agent Ecosystems: 30 minutes </li> 
   How does the problem relate to MCP, A2A, and other emerging agent communication frameworks?  <br>
   Candidate Presentations: Experts from AsiaInfo, ATN, ANML and IBM etc.  <br>  <br>

<li> Community Interest and Next Steps: 20 minutes </li> 
   Is there sufficient interest and a well-defined problem space to justify future IETF work?  <br>
   Open Discussions(DMSC Charter)  <br>  <br>

## Links to the mailing list, draft charter if any (for WG-forming BoF), relevant Internet-Drafts, etc.
   - Mailing List: dmsc@ietf.org (subscribe the list at: https://mailman3.ietf.org/mailman3/lists/dmsc@ietf.org/
   - Draft charter:  https://github.com/ietf-dmsc/Charter/blob/main/dmsc-charter.md

   - Relevant Internet-Drafts:
      - Use Cases:
        <ol type="1">
        <li>AI Agent Use Cases and Requirements in 6G Network(https://datatracker.ietf.org/doc/draft-yu-dmsc-ai-agent-use-cases-in-6g/)</li>
        <li>Network AI Agent Use Cases and Requirements in 6G(https://datatracker.ietf.org/doc/html/draft-tong-network-agent-use-cases-in-6g-00)</li>
        <li>Problem Statement and Requirements for Dynamic Multi-agent Secured Collaboration (DMSC) (https://datatracker.ietf.org/doc/html/draft-song-dmsc-problem-statement)</li>
        </ol>
       
      - Solutions
        <ol type="1">
        <li> Multi-agent Collaboration Protocol Suite(https://datatracker.ietf.org/doc/draft-li-dmsc-macp/))</li>
        <li> Dynamic Multi-agents Secured Collaboration Infrastructure architecture(https://datatracker.ietf.org/doc/draft-li-dmsc-inf-architecture/)</li> 
        <li> Agent Collaboration Protocols Architecture for Internet of Agents https://datatracker.ietf.org/doc/draft-liu-dmsc-acps-arc/</li>
        <li> Internet of Agents Task Protocol (IoA Task Protocol) for Heterogeneous Agent Collaboration https://datatracker.ietf.org/doc/draft-yang-dmsc-ioa-task-protocol/ </li>
        <li> Requirements for Agent Gateway(https://datatracker.ietf.org/doc/draft-liu-dmsc-gw-requirements/) </li>
        <li> Agent Communication Gateway for Semantic Routing and Working Memory (https://datatracker.ietf.org/doc/draft-agent-gw/) </li>
        <li> Intent-based Agent Interconnection Protocol at Agent Gateway (https://www.ietf.org/ietf-ftp/internet-drafts/draft-sz-dmsc-iaip-00.txt) </li>
        <li> Agent Trust Negotiation: Capability, Delegation, and Provenance Binding for AI Agents (https://datatracker.ietf.org/doc/draft-somoza-dmsc-atn-agent-trust-negotiation/)</li>   
        <li> Security Analysis of Multi-agents Secured Communication and Limitations of Existing Protocols(https://datatracker.ietf.org/doc/draft-zhang-dmsc-mas-communication/) </li>
        <li> Ontology-based Semantic Interaction for Internet of Agents(https://datatracker.ietf.org/doc/draft-zhang-dmsc-ioa-semantic-interaction/) </li>
        <li> Cross-Domain Interoperability Framework for AI Agent Collaboration(https://datatracker.ietf.org/doc/draft-cui-dmsc-agent-cdi/) </li>
        <li> Using Natural Language for Universal Coordination in Multi Agent Systems(https://datatracker.ietf.org/doc/draft-verma-dmsc-nlip-notes/) </li>
        </ol>
