Annex C - Proposed Requirements for Human and Organizational Readiness
==========================================================================

C.1 Status and Application
--------------------------

This annex consolidates proposed requirements for discussion and review within
the ITU-T Focus Group on Trust and Identity for Humans and Agentic AI
(FG-TIDA). The requirements are a proposed baseline for a delegation-specific
readiness assessment. They are not approved ITU-T requirements and have not
been validated as a certification or conformity-assessment scheme.

The term **shall** expresses a proposed mandatory requirement within this
working specification. Applicability depends on the delegation context.
Where a requirement is not applicable, the assessor should record the reason
and supporting evidence.

C.2 General Requirements
------------------------

**HORA-REQ-001 - Defined delegation context**

Before delegated authority is activated, the delegating party shall define
and record the delegation objective, intended activities, operating
environment, affected parties, relevant systems and information, and
conditions under which the agent may act.

**HORA-REQ-002 - Explicit authority boundary**

The delegating party shall define the authority granted to the agent,
including permitted actions, prohibited actions, applicable limits,
validity conditions, approval conditions, and escalation conditions.

**HORA-REQ-003 - Proportionality of delegated authority**

The authority granted to an agent shall be limited to what is necessary
for the defined objective. The delegation decision shall consider agent
capability, autonomy, potential consequence, reversibility, operating
context, and available controls as distinct factors.

**HORA-REQ-004 - Separate assessment domains**

A readiness assessment shall evaluate agent capability, human readiness,
and organizational readiness as distinct assessment domains. A strength
in one domain shall not automatically compensate for a material
deficiency in another domain.

C.3 Human Capability and Oversight Requirements
------------------------------------------------

**HORA-REQ-005 - Competence of responsible humans**

The organization shall identify the human roles responsible for
authorizing, supervising, operating, reviewing, and intervening in the
delegation. It shall establish that those roles have appropriate
knowledge, skills, information, authority, and capacity for their
assigned responsibilities.

**HORA-REQ-006 - Understanding of agent limitations**

Before assuming an oversight role, responsible humans shall receive
information appropriate to their role about the agent's intended
purpose, relevant capabilities, known limitations, material failure
modes, and applicable delegation boundaries.

**HORA-REQ-007 - Effective oversight**

The organization shall establish oversight arrangements that provide
responsible humans with sufficient visibility, information, time,
capability, and authority to perform their assigned oversight functions.
Nominal human presence or approval without a practical ability to
evaluate or influence the agent's activity shall not, by itself, be
treated as meaningful oversight.

**HORA-REQ-008 - Intervention and escalation**

The organization shall define and provide operational mechanisms for
authorized humans or control functions to pause, constrain, redirect,
suspend, or terminate delegated activity, and to escalate actions or
conditions outside the approved boundary.

**HORA-REQ-009 - Intervention timing**

The oversight assessment shall consider whether the time available to
identify and intervene in agent activity is sufficient in relation to
the potential consequences and reversibility of the activity. Where
effective human intervention cannot occur in time, the delegation shall
include appropriate preventive or automated safeguards, or the
delegated authority shall be reduced or withheld.

C.4 Organizational Governance and Accountability Requirements
--------------------------------------------------------------

**HORA-REQ-010 - Delegation authorization and review**

The organization shall establish a documented process identifying who
may authorize, modify, renew, review, reduce, suspend, and terminate
delegated authority. The process shall include approval criteria
proportionate to the delegation context.

**HORA-REQ-011 - Assignment of accountability**

The organization shall identify the delegating party, operational
owner, agent operator, supervising human or function, escalation
authority, and incident-review responsibility, as applicable. The
assignment shall not imply that delegation to an agent removes
accountability from the responsible human or organization.

**HORA-REQ-012 - Workforce and operational capacity**

The organization shall assess whether staffing, role-specific training,
technical expertise, governance expertise, risk-management capability,
operational support, and incident-response capacity are sufficient for
the proposed delegation and its expected workload.

**HORA-REQ-013 - Incident and exception handling**

The organization shall establish procedures for detecting, reporting,
escalating, investigating, and learning from material incidents,
unexpected agent actions, control failures, and near misses associated
with delegated activity.

C.5 Authorization, Traceability, and Assurance Requirements
------------------------------------------------------------

**HORA-REQ-014 - Enforceable delegation boundaries**

The organization shall implement or arrange controls that constrain
agent activity to the authorized scope, including relevant permissions,
transaction limits, information-access restrictions, approval
requirements, and validity conditions.

**HORA-REQ-015 - Revocation and suspension**

Delegated authority shall be capable of being reduced, suspended, or
revoked by an appropriately authorized human or organizational
function. The organization shall define the conditions and operational
processes for doing so.

**HORA-REQ-016 - Traceability records**

The organization shall determine and maintain records sufficient to
reconstruct, to a degree proportionate to the delegation context, the
agent identity, delegating party, applicable authority, relevant
instructions or objectives, material actions, external interactions,
human interventions, escalations, exceptions, and outcomes.

**HORA-REQ-017 - Assurance evidence**

A readiness determination shall be supported by identifiable and
sufficiently current evidence. Evidence may include authorization
records, competence and training records, governance policies,
intervention tests, monitoring results, incident records, audit
records, and documented assessments.

C.6 Continuous Readiness Requirements
-------------------------------------

**HORA-REQ-018 - Reassessment**

The organization shall reassess readiness when material changes occur
to agent capability, delegated authority, connected tools or systems,
operating conditions, organizational responsibilities, workforce
capacity, applicable requirements, or the potential consequences of
agent activity. It shall also define periodic reassessment conditions
appropriate to the delegation context.

**HORA-REQ-019 - Readiness gaps and remediation**

The assessment shall identify material readiness gaps, their potential
effect on the delegation, the actions required to address them, the
responsible owner, and the conditions for verifying remediation.
Where a material gap cannot be adequately addressed, delegated
authority shall be reduced, deferred, suspended, or not activated.

**HORA-REQ-020 - Delegation decision record**

The organization shall record the readiness determination and its
basis. The record shall identify the delegation context, authority
boundary, proposed delegation level, assessment findings, material
gaps, controls, accountable roles, supporting evidence, decision,
conditions, and reassessment triggers.

C.7 Assessment and Interpretation
----------------------------------

The requirements shall be assessed in relation to a specific delegation
context. They shall not be combined into a single numerical score unless
a future validated method establishes the basis, reliability, and
limitations of such aggregation.

Delegation level and potential consequence shall be assessed separately.
A higher autonomy level does not necessarily imply a higher consequence,
and a narrowly constrained action may still have significant effects.
Reversibility, intervention time, affected parties, and the operating
context should inform the assessment.

The assessment outcome should state whether the delegation may proceed,
may proceed subject to conditions, should be reduced, should be deferred,
should be suspended, or should be terminated.

C.8 Requirement Traceability
----------------------------

The following mapping links the proposed requirements to the eight
readiness dimensions in Chapter 4.

+----------------+--------------------------------------------------+
| Requirement    | Primary readiness dimension                      |
+================+==================================================+
| HORA-REQ-001   | Delegation Governance                            |
+----------------+--------------------------------------------------+
| HORA-REQ-002   | Authorization and Boundary Management            |
+----------------+--------------------------------------------------+
| HORA-REQ-003   | Authorization and Boundary Management            |
+----------------+--------------------------------------------------+
| HORA-REQ-004   | Cross-cutting assessment principle               |
+----------------+--------------------------------------------------+
| HORA-REQ-005   | Human Capability and Understanding               |
+----------------+--------------------------------------------------+
| HORA-REQ-006   | Human Capability and Understanding               |
+----------------+--------------------------------------------------+
| HORA-REQ-007   | Meaningful Human Oversight                       |
+----------------+--------------------------------------------------+
| HORA-REQ-008   | Meaningful Human Oversight                       |
+----------------+--------------------------------------------------+
| HORA-REQ-009   | Meaningful Human Oversight                       |
+----------------+--------------------------------------------------+
| HORA-REQ-010   | Delegation Governance                            |
+----------------+--------------------------------------------------+
| HORA-REQ-011   | Accountability and Responsibility               |
+----------------+--------------------------------------------------+
| HORA-REQ-012   | Workforce and Organizational Capability          |
+----------------+--------------------------------------------------+
| HORA-REQ-013   | Continuous Monitoring and Adaptation             |
+----------------+--------------------------------------------------+
| HORA-REQ-014   | Authorization and Boundary Management            |
+----------------+--------------------------------------------------+
| HORA-REQ-015   | Authorization and Boundary Management            |
+----------------+--------------------------------------------------+
| HORA-REQ-016   | Traceability and Assurance Evidence              |
+----------------+--------------------------------------------------+
| HORA-REQ-017   | Traceability and Assurance Evidence              |
+----------------+--------------------------------------------------+
| HORA-REQ-018   | Continuous Monitoring and Adaptation             |
+----------------+--------------------------------------------------+
| HORA-REQ-019   | Cross-cutting assessment and remediation         |
+----------------+--------------------------------------------------+
| HORA-REQ-020   | Cross-cutting assessment and accountability      |
+----------------+--------------------------------------------------+

This mapping is indicative. A requirement may support more than one
readiness dimension depending on the delegation context.

C.9 Validation Questions for FG-TIDA
------------------------------------

The following questions are proposed for review by FG-TIDA participants:

* Are the proposed requirements within the Focus Group's trust and
  identity scope, and how should they interface with identity,
  authentication, authorization, provenance, and trust-management work?
* Which requirements should be expressed as technical capabilities,
  organizational controls, human-capability expectations, or guidance?
* What minimum evidence is needed to demonstrate effective human
  oversight and intervention?
* How should multi-agent delegation chains and changes in delegated
  authority be represented in interoperable records?
* Which requirements can be tested consistently across sectors, and
  which require context-specific interpretation?
* What terminology and requirement structure should be harmonized with
  other FG-TIDA contributions and relevant standards?

The requirements are proposed for discussion and should be refined
through stakeholder review, use-case analysis, and practical
validation before any claim of standardization or conformity is made.
