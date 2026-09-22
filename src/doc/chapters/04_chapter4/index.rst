4 Human and Organizational Readiness Framework
===============================================

4.1 Overview
------------

This chapter defines the proposed Human and Organizational Readiness Framework for Trusted Agentic AI (HORA-TAI).

The framework provides a structured approach for assessing whether the human and organizational conditions surrounding a defined delegation of authority are sufficient to support trustworthy operation of an agentic AI system.

The framework is based on the principle that the appropriate level of delegated authority depends not only on agent capability, but also on the ability of humans and organizations to understand, supervise, govern, intervene in, and remain accountable for agent activity.

The framework therefore evaluates readiness across multiple dimensions.

Readiness is not treated as a permanent characteristic of an individual or organization. It is assessed in relation to a specific delegation context.

4.2 Framework Model
-------------------

The HORA-TAI framework consists of the following core components:

* delegation context;
* delegated authority;
* readiness dimensions;
* delegation level;
* human oversight;
* organizational governance;
* accountability and traceability;
* assurance evidence; and
* continuous reassessment.

These components are interdependent.

A delegation decision should consider the relationship between:

**Agent capability + Delegated authority + Human readiness + Organizational readiness + Oversight capability + Assurance**

A high-capability agent does not by itself establish that a delegation is appropriate.

Similarly, a highly capable organization may not be ready to delegate a particular activity if the agent lacks sufficient capability, safeguards, or controllability.

4.3 Readiness Dimensions
------------------------

The framework proposes eight primary readiness dimensions:

1. Human Capability and Understanding
2. Meaningful Human Oversight
3. Delegation Governance
4. Accountability and Responsibility
5. Authorization and Boundary Management
6. Workforce and Organizational Capability
7. Traceability and Assurance
8. Continuous Monitoring and Adaptation

Each dimension should be assessed in relation to the specific delegation context.

4.3.1 Human Capability and Understanding
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This dimension addresses whether the relevant human actors possess sufficient knowledge and capability to understand and appropriately interact with the agentic AI system.

Assessment may consider:

* understanding of the agent's purpose and capabilities;
* understanding of relevant limitations and failure modes;
* ability to interpret agent outputs and actions;
* awareness of material risks;
* ability to recognize unexpected or anomalous behavior;
* knowledge of intervention procedures;
* ability to exercise appropriate judgment; and
* familiarity with applicable policies and responsibilities.

Human capability should be proportionate to the authority delegated and the consequences of agent activity.

4.3.2 Meaningful Human Oversight
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This dimension addresses whether human oversight is substantive and effective rather than merely procedural.

Assessment may consider:

* whether relevant agent activity is visible to the responsible human;
* whether the human receives sufficient information to exercise judgment;
* whether intervention is technically possible;
* whether intervention can occur within an appropriate timeframe;
* whether the responsible human has authority to intervene;
* whether workload permits effective supervision;
* whether escalation mechanisms are available; and
* whether oversight remains effective as agent autonomy increases.

The presence of a human in a workflow should not, by itself, be considered evidence of meaningful human oversight.

4.3.3 Delegation Governance
~~~~~~~~~~~~~~~~~~~~~~~~~~

This dimension addresses whether the organization has appropriate processes for deciding when, why, and under what conditions authority may be delegated to an agentic AI system.

Assessment may consider:

* defined delegation policies;
* approval processes;
* risk assessment procedures;
* role and responsibility definitions;
* delegation criteria;
* escalation requirements;
* suspension and termination procedures;
* change-management processes; and
* governance oversight.

Delegation governance should establish who is authorized to grant, modify, review, and terminate delegated authority.

4.3.4 Accountability and Responsibility
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This dimension addresses whether responsibility for delegated activities and outcomes remains identifiable.

Assessment may consider:

* identification of the delegating party;
* identification of the supervising human or function;
* identification of operational responsibilities;
* assignment of decision rights;
* incident ownership;
* escalation responsibility;
* review responsibility; and
* applicable legal, regulatory, and organizational obligations.

The use of an AI agent should not create an accountability gap.

4.3.5 Authorization and Boundary Management
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This dimension addresses whether the authority granted to an agent is explicit, appropriately limited, and technically and organizationally controllable.

Assessment may consider:

* defined permissions;
* permitted and prohibited actions;
* transaction or operational limits;
* access boundaries;
* temporal limitations;
* geographic or organizational boundaries where applicable;
* approval requirements;
* escalation thresholds;
* emergency controls; and
* authority revocation mechanisms.

Delegated authority should be no broader than necessary to achieve the defined objective.

4.3.6 Workforce and Organizational Capability
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This dimension addresses whether the organization has the workforce capabilities and organizational resources required to operate and supervise agentic AI.

Assessment may consider:

* AI literacy;
* role-specific training;
* technical expertise;
* governance expertise;
* risk-management capabilities;
* operational support;
* incident-response capabilities;
* staffing levels;
* workload allocation; and
* organizational change-management capability.

Workforce readiness should be considered across the full lifecycle of agentic AI deployment rather than only during initial implementation.

4.3.7 Traceability and Assurance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This dimension addresses whether relevant agent activity can be sufficiently reconstructed and evaluated.

Assessment may consider:

* records of delegated authority;
* agent instructions and objectives;
* authorization information;
* significant agent decisions;
* material actions;
* external interactions;
* human interventions;
* exceptions and escalations;
* outcomes; and
* assurance evidence.

The level of traceability should be proportionate to the nature and consequences of the delegated activity.

4.3.8 Continuous Monitoring and Adaptation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This dimension addresses whether readiness and delegation remain appropriate as conditions change.

Assessment may consider:

* changes in agent capabilities;
* changes in operating environments;
* changes in organizational structures;
* changes in workforce capabilities;
* changes in applicable requirements;
* changes in risk;
* performance trends;
* incidents and near misses;
* emerging failure modes; and
* changes in delegated authority.

Continuous assurance should provide mechanisms for reducing, modifying, suspending, or terminating delegation when readiness conditions are no longer satisfied.

4.4 Delegation and Readiness Relationship
-----------------------------------------

The relationship between delegated authority and readiness is central to the framework.

As the scope, autonomy, complexity, or consequence of delegated authority increases, the required level of human and organizational readiness may also increase.

The framework therefore does not define readiness independently of delegation.

Instead:

**Required readiness = f(delegated authority, autonomy, consequence, reversibility, operating context, and available controls)**

This relationship should be interpreted qualitatively during the initial development of the framework and may subsequently be supported by empirical assessment methods.

4.5 Proposed Delegation Levels
------------------------------

For the purposes of this specification, five descriptive delegation levels are proposed.

These levels are intended to provide a common vocabulary for discussing the relative degree of authority delegated to an agentic AI system.

They are not intended to constitute a universal risk classification.

4.5.1 Level 0 - Advisory
~~~~~~~~~~~~~~~~~~~~~~~~

At Level 0, the agent provides information, analysis, recommendations, or proposed actions.

The human remains responsible for deciding whether and how to act.

The agent does not independently execute consequential actions.

Examples may include:

* generating recommendations;
* summarizing information;
* identifying potential options;
* drafting content; and
* proposing actions for human review.

4.5.2 Level 1 - Constrained Execution
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

At Level 1, the agent may execute narrowly defined actions within explicit constraints.

Human authorization establishes the permitted activity, and the agent operates within predetermined boundaries.

Examples may include:

* submitting routine administrative requests;
* executing predefined software or workflow tasks;
* updating approved records; and
* initiating low-consequence operational activities.

4.5.3 Level 2 - Conditional Autonomy
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

At Level 2, the agent may make intermediate decisions and execute multiple actions without obtaining human approval for every individual step, provided that predefined conditions are satisfied.

Human oversight remains available and defined escalation conditions apply.

Examples may include:

* resolving routine customer-service cases;
* coordinating predefined business workflows;
* executing multi-step administrative processes; and
* selecting among predefined operational options.

4.5.4 Level 3 - Extended Autonomy
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

At Level 3, the agent may pursue a defined objective through multiple steps and make broader intermediate decisions with limited direct human intervention.

The organization should establish stronger governance, monitoring, intervention, and assurance mechanisms.

Examples may include:

* managing complex operational workflows;
* coordinating multiple software tools or services;
* optimizing defined business processes; and
* executing extended sequences of actions within a defined operational domain.

4.5.5 Level 4 - High-Consequence Autonomy
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

At Level 4, the agent may exercise substantial autonomy in activities where errors or unintended actions could produce significant consequences.

Level 4 requires particularly strong consideration of:

* human oversight;
* intervention capability;
* authorization;
* accountability;
* traceability;
* assurance;
* reversibility;
* escalation; and
* organizational readiness.

This level does not imply that high-consequence activities should automatically be delegated. Rather, it identifies contexts in which the readiness requirements for delegation are expected to be particularly demanding.

4.6 Readiness Assessment
------------------------

A readiness assessment should evaluate the relationship between the proposed delegation and the readiness dimensions defined in this chapter.

The assessment should consider at least:

* the objective of the delegation;
* the authority granted;
* the proposed delegation level;
* the agent's relevant capabilities and limitations;
* the consequences of incorrect or unintended actions;
* the reversibility of actions;
* the information and systems accessible to the agent;
* the available human oversight;
* intervention and escalation mechanisms;
* organizational governance;
* workforce capabilities;
* accountability arrangements;
* traceability mechanisms; and
* continuous assurance capabilities.

The assessment should identify both capabilities that are present and readiness gaps that may require remediation.

4.7 Readiness Determination
---------------------------

A readiness determination should result in one of the following types of outcomes:

* delegation may proceed under the defined conditions;
* delegation may proceed subject to specified controls or remediation;
* delegation authority should be reduced;
* additional human oversight should be established;
* additional organizational capabilities should be developed;
* delegation should be deferred pending remediation; or
* delegation should not proceed under the assessed conditions.

These outcomes are intended to support operational decision-making and are not intended to establish a universal certification scheme.

4.8 Readiness Evidence
---------------------

Readiness determinations should be supported by evidence appropriate to the delegation context.

Evidence may include:

* training records;
* competency assessments;
* governance policies;
* authorization records;
* risk assessments;
* oversight procedures;
* intervention tests;
* audit records;
* incident records;
* monitoring data;
* system documentation;
* assurance reports; and
* records of previous delegation decisions.

Evidence should be sufficiently reliable and current to support the relevant readiness determination.

4.9 Readiness Gaps and Remediation
----------------------------------

Where a readiness assessment identifies a gap, the organization should determine whether the gap can be addressed before delegation proceeds or whether delegated authority should be reduced.

Potential remediation measures include:

* additional human training;
* improved AI literacy;
* strengthened supervision;
* narrower delegation boundaries;
* additional approval requirements;
* stronger monitoring;
* improved traceability;
* enhanced incident response;
* additional technical safeguards;
* revised organizational responsibilities; and
* reassessment before increasing delegated authority.

4.10 Relationship Between Delegation and Oversight
---------------------------------------------------

Human oversight should be designed in relation to the actual authority and autonomy granted to the agent.

Oversight mechanisms may include:

* pre-action approval;
* approval of defined classes of actions;
* real-time monitoring;
* exception-based escalation;
* periodic review;
* post-action review;
* automated safeguards;
* authority suspension; and
* emergency intervention.

The appropriate combination depends on the delegation context.

Oversight should not be designed solely around the technical capabilities of the agent. It should also consider the ability of the responsible humans and organization to understand and exercise control over the agent.

4.11 Continuous Readiness
-------------------------

Readiness should not be treated as a one-time determination.

A previously acceptable delegation may become inappropriate when:

* agent capabilities change;
* the agent is connected to new tools or systems;
* the scope of authority expands;
* organizational responsibilities change;
* workforce capabilities change;
* operating conditions change;
* incidents reveal previously unidentified risks;
* applicable requirements change; or
* the consequences of agent actions change.

Organizations should therefore establish mechanisms for periodic and event-driven reassessment.

4.12 Framework Output
--------------------

The output of applying the HORA-TAI framework should provide a structured representation of:

* the delegation context;
* the delegated authority;
* the delegation level;
* the assessed readiness dimensions;
* identified readiness gaps;
* required controls;
* human oversight arrangements;
* accountability arrangements;
* assurance evidence;
* reassessment conditions; and
* the resulting delegation decision.

This output may subsequently be represented through a structured assurance record as described in the supporting annexes.

4.13 Future Development
-----------------------

The framework presented in this chapter is intended as an initial proposal for discussion.

Further development may include:

* empirical validation of readiness dimensions;
* development of quantitative or semi-quantitative assessment methods;
* testing across sectors and organizational contexts;
* development of maturity models;
* development of machine-readable assurance records;
* integration with identity and authorization infrastructures;
* development of interoperability mechanisms;
* analysis of workforce readiness indicators; and
* development of evidence-based thresholds for different delegation contexts.

Such development should be informed by research, practical deployments, stakeholder consultation, and experience from standards and assurance activities.
