Annex B - Delegation Levels and Assurance Considerations
=========================================================

B.1 Purpose
-----------

This annex provides additional detail on the proposed delegation levels used by the Human and Organizational Readiness Framework for Trusted Agentic AI (HORA-TAI).

The delegation levels provide a common vocabulary for describing the relative degree of authority and autonomy delegated to an agentic AI system.

The levels are descriptive rather than normative. They are not intended to establish a universal risk classification, regulatory category, or certification scheme.

B.2 Delegation as a Multidimensional Relationship
-------------------------------------------------

The degree of delegation should not be determined solely by whether an agent is described as autonomous.

Delegation may vary across multiple dimensions, including:

* scope of authority;
* duration of authority;
* number and complexity of actions;
* degree of independent decision-making;
* access to information and systems;
* ability to interact with external parties;
* potential consequences;
* reversibility of actions;
* required speed of execution;
* availability of human intervention; and
* effectiveness of technical and organizational controls.

Two agents operating at a similar level of technical autonomy may therefore require different readiness conditions because the consequences and operating environments differ.

B.3 Level 0 - Advisory
----------------------

At Level 0, the AI system provides information, analysis, recommendations, proposed decisions, or proposed actions.

The human remains the direct decision-maker and action-taker.

Typical characteristics include:

* no independent consequential action;
* human review before action;
* human control over the final decision;
* limited or no delegated authority;
* direct human interpretation of agent output.

Examples include:

* generating a business recommendation;
* summarizing customer information;
* identifying potential procurement options;
* drafting a response;
* suggesting software changes; or
* analyzing a set of alternatives.

Primary readiness considerations include:

* basic AI literacy;
* understanding of limitations;
* ability to evaluate outputs;
* awareness of potential errors; and
* appropriate human judgment.

B.4 Level 1 - Constrained Execution
-----------------------------------

At Level 1, the agent may execute narrowly defined actions within explicit and predetermined constraints.

The human or organization establishes the permitted actions and relevant boundaries.

Typical characteristics include:

* narrow action scope;
* explicit authorization;
* predefined conditions;
* limited consequences;
* defined intervention mechanisms; and
* relatively high human visibility.

Examples include:

* submitting predefined administrative forms;
* updating approved records;
* initiating routine workflow steps;
* executing predefined software tasks; or
* sending communications that meet predefined conditions.

Primary assurance considerations include:

* authorization;
* boundary enforcement;
* action logging;
* basic intervention;
* human understanding of the delegation; and
* defined accountability.

B.5 Level 2 - Conditional Autonomy
----------------------------------

At Level 2, the agent may make intermediate decisions and execute multiple actions without requiring human approval for every individual step, provided that predefined conditions are satisfied.

The agent operates within a defined decision and action space.

Typical characteristics include:

* multiple-step execution;
* conditional decision-making;
* predefined escalation conditions;
* exception-based human oversight;
* broader access to operational systems; and
* increased dependence on monitoring.

Examples include:

* resolving routine customer-service cases;
* coordinating predefined workflows;
* managing routine scheduling;
* processing standard administrative cases; or
* selecting among approved operational options.

Primary assurance considerations include:

* robust delegation boundaries;
* exception detection;
* escalation;
* monitoring;
* workforce capability;
* traceability;
* incident response; and
* periodic reassessment.

B.6 Level 3 - Extended Autonomy
-------------------------------

At Level 3, the agent may pursue a defined objective through multiple steps and make broader intermediate decisions with limited direct human intervention.

The agent may adapt its actions within a defined operational domain.

Typical characteristics include:

* extended multi-step activity;
* broader decision space;
* limited direct human intervention;
* increased interaction with external systems;
* greater dependence on continuous monitoring; and
* greater potential for emergent or unexpected action sequences.

Examples may include:

* managing complex business workflows;
* coordinating multiple software tools;
* optimizing operational processes;
* managing defined procurement workflows; or
* executing extended technical operations.

Primary assurance considerations include:

* advanced governance;
* strong authorization controls;
* continuous monitoring;
* effective intervention;
* detailed traceability;
* incident response;
* workforce readiness;
* periodic assurance; and
* clear accountability.

B.7 Level 4 - High-Consequence Autonomy
----------------------------------------

At Level 4, the agent may exercise substantial autonomy in activities where errors, unexpected behavior, or unauthorized actions could produce significant consequences.

Level 4 is not defined solely by technical autonomy.

A delegation may be considered high-consequence because of the potential impact of its actions even when the technical workflow appears relatively constrained.

Examples may include activities involving:

* material financial consequences;
* critical organizational operations;
* sensitive information;
* significant effects on individuals;
* critical infrastructure;
* high-impact services; or
* other contexts where unintended actions could produce substantial harm or disruption.

Primary assurance considerations include:

* strong authorization;
* clearly defined delegation boundaries;
* demonstrable human oversight;
* rapid intervention capability;
* robust traceability;
* continuous assurance;
* tested escalation mechanisms;
* strong organizational governance;
* appropriate workforce capability;
* defined accountability; and
* documented conditions for suspension or termination.

The existence of Level 4 does not imply that a particular high-consequence activity should be delegated.

B.8 Delegation Level and Consequence
------------------------------------

Delegation level and consequence should be assessed separately.

A relatively autonomous agent operating within a low-consequence environment may require different controls from a less autonomous agent operating in a high-consequence environment.

Assessment should therefore consider at least two dimensions:

**Autonomy**

The degree to which the agent can determine and execute actions without direct human approval.

**Consequence**

The potential magnitude and significance of effects resulting from an incorrect, unauthorized, or unintended action.

The combination of these dimensions should inform the required readiness and assurance conditions.

B.9 Reversibility
-----------------

Reversibility is an important consideration in determining appropriate delegation.

Actions that can be quickly and completely reversed may require different oversight arrangements from actions that create permanent or difficult-to-reverse effects.

Assessment should consider:

* whether an action can be reversed;
* how quickly it can be reversed;
* who can reverse it;
* whether reversal itself may create consequences;
* whether affected parties can be restored to their previous state; and
* whether residual effects remain after reversal.

Lower reversibility generally increases the importance of appropriate authorization, oversight, and assurance.

B.10 Speed and Intervention
---------------------------

The speed at which an agent can act should be considered when designing human oversight.

An oversight mechanism is not meaningful if the human cannot reasonably intervene before a consequential action occurs.

Assessment should therefore consider:

* agent execution speed;
* time available for human review;
* time required to identify an abnormal action;
* time required to intervene;
* time required to suspend the agent;
* availability of automated safeguards; and
* consequences of delayed intervention.

Where agent activity can occur faster than effective human intervention, additional controls may be required.

B.11 Delegation Expansion
-------------------------

Delegated authority should not automatically expand merely because an agent performs successfully at a lower level.

Expansion of authority should be supported by evidence that:

* the agent continues to perform reliably;
* relevant humans remain capable of supervising the agent;
* organizational governance remains effective;
* monitoring remains adequate;
* intervention mechanisms remain effective;
* new risks have been evaluated; and
* the organization has sufficient assurance evidence.

An increase in delegation level should therefore be treated as a new or materially changed delegation decision.

B.12 Delegation Reduction
-------------------------

Delegated authority should be capable of being reduced when readiness conditions deteriorate.

Reduction may be appropriate when:

* agent performance degrades;
* new failure modes emerge;
* human oversight becomes ineffective;
* workforce capacity decreases;
* organizational responsibilities change;
* monitoring becomes unavailable;
* incidents occur;
* operating conditions change; or
* new risks are identified.

Delegation reduction should be treated as a normal governance capability rather than only an emergency response.

B.13 Suspension and Termination
-------------------------------

Organizations should establish conditions under which delegated authority may be suspended or terminated.

Suspension may be appropriate when:

* an active incident is under investigation;
* a material control fails;
* oversight is temporarily unavailable;
* the agent behaves unexpectedly;
* relevant assurance evidence becomes invalid; or
* required organizational capabilities are temporarily unavailable.

Termination may be appropriate when:

* the delegation is no longer necessary;
* the organization determines that the readiness conditions cannot be maintained;
* the operating environment changes materially;
* the agent is replaced;
* the delegation objective changes; or
* continued delegation is determined to be inappropriate.

B.14 Assurance Considerations by Delegation Level
--------------------------------------------------

The following table provides an illustrative mapping between delegation level and assurance considerations.

+---------+----------------------+-----------------------+-------------------------+
| Level   | Human Oversight      | Primary Controls      | Assurance Focus         |
+=========+======================+=======================+=========================+
| 0       | Direct decision      | Human review          | Output evaluation      |
+---------+----------------------+-----------------------+-------------------------+
| 1       | Defined intervention | Authorization and     | Boundary compliance    |
|         |                      | action constraints    | and traceability       |
+---------+----------------------+-----------------------+-------------------------+
| 2       | Exception-based      | Escalation, monitoring| Operational performance|
|         | oversight            | and boundaries        | and incident response  |
+---------+----------------------+-----------------------+-------------------------+
| 3       | Limited direct       | Continuous monitoring,| Delegation integrity,  |
|         | intervention         | intervention and      | governance and         |
|         |                      | strong governance     | continuous assurance   |
+---------+----------------------+-----------------------+-------------------------+
| 4       | Strong, demonstrable | Strong authorization, | Comprehensive          |
|         | oversight and rapid  | intervention,         | assurance, accountability|
|         | intervention         | traceability and      | and readiness          |
|         |                      | continuous assurance  |                         |
+---------+----------------------+-----------------------+-------------------------+

The table is illustrative and should be refined through further research and practical evaluation.

B.15 Relationship to HORA-TAI Readiness
---------------------------------------

Delegation level should not be used independently of the readiness dimensions defined in Chapter 4.

For each proposed delegation, the organization should evaluate whether the relevant readiness dimensions are sufficient for the proposed level of authority.

A higher delegation level generally requires stronger evidence across multiple readiness dimensions, but the relationship should remain context-dependent.

The framework should avoid treating delegation level as a simple numerical score.

The purpose of the levels is to support structured reasoning about delegated authority, not to replace context-specific assessment.

B.16 Future Validation
----------------------

The delegation levels proposed in this annex should be evaluated through:

* practical deployment studies;
* cross-sector case studies;
* expert review;
* human oversight experiments;
* organizational readiness assessments;
* incident analysis;
* workforce capability research; and
* comparison with existing AI assurance and governance frameworks.

Future versions may revise the number, terminology, characteristics, or assessment implications of the delegation levels based on evidence and stakeholder input.
