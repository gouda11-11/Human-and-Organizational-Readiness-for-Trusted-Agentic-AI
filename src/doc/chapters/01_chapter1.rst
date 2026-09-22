1 Introduction and Scope
========================

1.1 Introduction
----------------

Agentic artificial intelligence (AI) systems are evolving from systems that primarily generate information or recommendations into systems capable of interpreting objectives, planning actions, using tools, interacting with external systems, and executing tasks on behalf of humans and organizations.

This evolution changes the nature of the relationship between humans and AI systems. In conventional AI-assisted workflows, the human generally remains the direct decision-maker and uses AI as an informational or analytical resource. In agentic workflows, humans may delegate defined objectives or actions to an AI agent, allowing the agent to make intermediate decisions and execute actions within an authorized boundary.

Delegation introduces a distinct trust requirement.

The reliability and safety of an agent alone do not determine whether a delegated activity is trustworthy. The human or organization granting authority must also be capable of defining appropriate boundaries, understanding the implications of delegation, establishing effective oversight, maintaining accountability, and responding when an agent behaves unexpectedly.

This specification therefore addresses the human and organizational conditions required for trusted delegation to agentic AI.

The central principle of this specification is:

**Trustworthy agentic AI requires not only trustworthy agents, but trustworthy delegation.**

1.2 Purpose
-----------

The purpose of this specification is to establish a structured framework for assessing human and organizational readiness for the delegation of authority to agentic AI systems.

The framework is intended to support:

* meaningful human oversight;
* appropriate definition and allocation of delegated authority;
* clear accountability for agent actions and outcomes;
* traceability of delegated decisions and actions;
* assessment of human capabilities and workforce readiness;
* organizational governance of agentic AI;
* continuous monitoring and assurance; and
* informed decisions about when and how authority may be delegated to an agentic AI system.

The framework is intended to complement, rather than replace, technical mechanisms for trust, identity, authentication, authorization, security, privacy, safety, and AI assurance.

1.3 Scope
---------

This specification addresses the readiness of humans and organizations to delegate defined authority to agentic AI systems.

The scope includes:

* individual human readiness to supervise and interact with agentic AI;
* team and workforce capabilities required to operate and supervise agentic AI;
* organizational governance and accountability structures;
* definition of delegation boundaries and conditions;
* meaningful human oversight;
* human understanding of agent capabilities and limitations;
* authorization and escalation processes;
* traceability and accountability for agent actions;
* continuous assurance and reassessment; and
* organizational readiness for changes resulting from increased AI autonomy.

The specification is technology-neutral. It does not prescribe a particular AI model, agent architecture, identity technology, security mechanism, vendor, deployment environment, or implementation approach.

The specification may be applied across different sectors and organizational contexts, subject to the specific risks, regulatory requirements, operational conditions, and consequences associated with the delegated activity.

1.4 Relationship to Agent Trust
-------------------------------

Agentic AI trust involves multiple interacting layers.

An agent may have appropriate technical capabilities and controls, including identity, authentication, authorization, security mechanisms, monitoring, and safeguards. These mechanisms are necessary but may not be sufficient to establish trustworthy delegation.

A trusted delegation relationship also requires the relevant human and organizational actors to understand:

* what authority is being delegated;
* why that authority is being delegated;
* what actions the agent is permitted to perform;
* what actions remain subject to human approval;
* what risks may arise from the delegation;
* how agent actions can be monitored and traced;
* who remains accountable for outcomes; and
* what conditions require intervention, escalation, suspension, or termination of delegated authority.

Accordingly, this specification treats human and organizational readiness as a complementary component of trusted agentic AI.

1.5 Intended Users
------------------

This specification may be relevant to:

* organizations deploying agentic AI systems;
* AI system developers and providers;
* organizations responsible for AI governance and assurance;
* risk, compliance, security, and audit functions;
* technology and digital transformation leaders;
* workforce and learning functions;
* policymakers and regulators;
* standards-development organizations;
* researchers studying human-AI interaction and AI governance; and
* individuals responsible for supervising or operating agentic AI systems.

1.6 Applicability
-----------------

The framework may be applied wherever an agentic AI system receives authority to perform actions, make intermediate decisions, or interact with external systems on behalf of a human or organization.

Examples may include:

* customer service agents authorized to resolve customer requests;
* enterprise agents authorized to initiate business processes;
* procurement agents authorized to identify or purchase goods and services;
* software agents authorized to modify or deploy code;
* financial agents authorized to initiate defined transactions;
* administrative agents authorized to perform organizational tasks; and
* public-sector agents operating within defined administrative processes.

The appropriate level of readiness required depends on the nature of the delegated authority, the potential consequences of agent actions, the reversibility of those actions, the sensitivity of the information involved, and the effectiveness of available human oversight and technical controls.

1.7 Core Principle
------------------

The framework is based on the following principle:

**The authority delegated to an agent should not exceed the human and organizational capacity to understand, supervise, govern, and remain accountable for that delegation.**

This principle recognizes that increasing agent autonomy can create corresponding requirements for human capability, organizational governance, oversight, and assurance.

Readiness should therefore be assessed in relation to the specific delegation rather than treated as a universal characteristic of an individual or organization.

1.8 Structure of This Specification
-----------------------------------

This specification develops the framework progressively.

Chapter 2 defines the problem addressed by the specification and establishes its objectives.

Chapter 3 provides terms and definitions used throughout the framework.

Chapter 4 presents the human and organizational readiness dimensions and the proposed approach for assessing readiness.

The annexes and appendices provide supporting material, including illustrative delegation levels, assessment considerations, and examples for further discussion.

The framework is intended as a working specification for discussion within the ITU-T Focus Group on Trust and Identity for Humans and Agentic AI (FG-TIDA). The concepts and requirements presented in this document are proposals for review, refinement, and potential future standardization.
