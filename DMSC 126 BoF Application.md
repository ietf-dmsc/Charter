# Name: Dynamic Multi-agent Secured Collaboration (DMSC)
## Description 
With the rapid emergence of diverse AI agents and various use cases, especially that are described in 3GPP(SA1 R20 Study on 6G Use Cases and Service Requirements(TR 22.870)) , a critical challenge arose is to enable dynamic collaboration among these agents to perform complex tasks on behalf of end-users. At the same time, there is a growing need to ensure that such collaboration is scalable, manageable, operational and secure.
Service providers and cloud operators face the task of designing and optimizing a comprehensive communication architecture that enables secure and efficient collaboration between heterogeneous AI agents, ensuring the following:

AI Agent Gateway based, distributed agent registration and identification.
Discovery of suitable peer agents via the AI Agent Gateway.
Agents registration and capabilities information synchronize among the distributed AI Agent Gateways within the same domain.
Inter-domain AI Agents related information exchange and trust establishment, including semantic interoperability for agent capabilities, intents, tasks, and context across gateways and domains
Operational visibility for the AI Agents communication.

To address these challenges, the Dynamic, Multi-Agent, Secured Collaboration (DMSC) working group will explore solutions for defining interoperable protocols and mechanisms that enables AI agents to collaborate effectively in complex human-driven tasks. This work will focus on core aspects of collaboration—such as distributed agent registration, AI agent gateway based discovery, request coordination, and secure inter‑agent communication

## Required Details
- Status: "WG forming"
- Responsible AD: Charles Eckel, Andy Newton 
- BOF proponents: Aijun Wang <wangaj3@chinatelecom.cn>, Bing Liu <leo.liubing@huawei.com>, Dinesh C. Verma <dverma@us.ibm.com>, Jun Liu <liujun@bupt.edu.cn>, Enge Song <enge.seg@alibaba-inc.com> 
- Number of people expected to attend: 100
- Length of session (1 or usually 2 hours): 2 hours
- Conflicts (whole Areas and/or WGs)
   - Chair Conflicts: TBD
   - Technology Overlap: TBD
   - Key Participant Conflict: ART/SEC AD

## Information for IAB/IESG
To allow evaluation of your proposal, please include the following items:

- Any protocols or practices that already exist in this space: <br>
  There are no protocols that define how to build an operable, manageable infrastructure to enable AI agent collaboration via an AI agent gateway. <br>
  Various AI Agent Gateway implementations already exist, which creates a demand for standardization of communication between AI agents and their gateways, as well as synchronization across AI agent gateways. <br>

- Which (if any) modifications to existing protocols or practices are required: TBD
   
- Which (if any) entirely new protocols or practices are required: <br>
   The AI agent gateway based communication protocol suites,the communication between AI agents and their gateway, as well as synchronization across AI agent gateways.

- Open source projects (if any) implementing this work: <br>
   OpenGateway: https://github.com/anAtheist987/OpenGateway <br>
   ANP: https://github.com/agent-network-protocol/AgentNetworkProtocol <br>
   AIP <br>


## Agenda
   - Use cases, scenarios and requirements(20 minutes)
      <ol type="1">
      <li> AI Agent Use Cases and Requirements in 6G Network(https://datatracker.ietf.org/doc/draft-yu-dmsc-ai-agent-use-cases-in-6g/ </li>  
      <li> Problem Statement and Requirements for Dynamic Multi-agent Secured Collaboration (DMSC) (https://datatracker.ietf.org/doc/html/draft-song-dmsc-problem-statement) </li> <br>
      </ol>

   - AI agent gateway based communication architecture/protocol suites(20 minutes)
      <ol type="1">
      Multi-agent Collaboration Protocol Suite(https://datatracker.ietf.org/doc/draft-li-dmsc-macp/) <br>
      </ol>
      
   - Ontology-based Semantic Interaction for Internet of Agents(15 minutes)
      <ol type="1">
      Ontology-based Semantic Interaction for Internet of Agents(https://datatracker.ietf.org/doc/draft-zhang-dmsc-ioa-semantic-interaction/ <br>
      </ol>
      
   - Using Natural Language for Universal Coordination in Multi Agent Systems(15 minutes)
      <ol type="1">
      Using Natural Language for Universal Coordination in Multi Agent Systems(https://datatracker.ietf.org/doc/draft-verma-dmsc-nlip-notes/) <br>
      </ol>

   - DMSC Charter (20 minutes)
      <ol type="1">
      DMSC Charter https://github.com/ietf-dmsc/Charter/blob/main/dmsc-charter.md <br>
      </ol>
      
   - Open Discussion(30 minutes)


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
        <li> Security Analysis of Multi-agents Secured Communication and Limitations of Existing Protocols(https://datatracker.ietf.org/doc/draft-zhang-dmsc-mas-communication/) </li>
        <li> Ontology-based Semantic Interaction for Internet of Agents(https://datatracker.ietf.org/doc/draft-zhang-dmsc-ioa-semantic-interaction/) </li>
        <li> AI Agent Discovery and Invocation Protocol(https://datatracker.ietf.org/doc/draft-cui-ai-agent-discovery-invocation/) </li>
        <li> Cross-Domain Interoperability Framework for AI Agent Collaboration(https://datatracker.ietf.org/doc/draft-cui-dmsc-agent-cdi/) </li>
        <li> Using Natural Language for Universal Coordination in Multi Agent Systems(https://datatracker.ietf.org/doc/draft-verma-dmsc-nlip-notes/) </li>
        <li> HJS: A Judgment Event Protocol(https://datatracker.ietf.org/doc/draft-wang-hjs-judgment-event/)</li> 
        </ol>
