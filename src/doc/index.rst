.. raw:: latex

    \pagestyle{plain}
    \thispagestyle{plain}
    %% Suppress all TOC entries for the overview chapter (sections, subsections,
    %% Copyright addcontentsline) — restored just before \sphinxtableofcontents
    %% so chapters from Introduction onward appear in the TOC normally.
    \let\osiaorigaddcontentsline\addcontentsline
    \renewcommand{\addcontentsline}[3]{}

.. _chapter-overview:

Human and Organizational Readiness for Trusted Agentic AI
==========================================================

**HORA-TAI**

*A framework for assessing human and organizational readiness to delegate authority to agentic AI*

Abstract
--------

Agentic AI systems are increasingly capable of reasoning, planning, using tools, interacting with external systems, and executing actions with varying degrees of autonomy. As these capabilities expand, trust in agentic AI depends not only on the technical properties of the agent, but also on the readiness of the humans and organizations that delegate authority to it.

This specification proposes a human and organizational readiness framework for trusted agentic AI. It addresses the conditions required for meaningful human oversight, appropriate delegation of authority, accountability, traceability, workforce readiness, organizational governance, and continuous assurance.

The proposed framework complements technical trust, identity, authorization, and security mechanisms by addressing the human and organizational context in which agentic AI operates. It introduces readiness dimensions and a structured approach for assessing whether a person, team, or organization is prepared to delegate defined levels of authority to an agentic AI system.

The core principle is that trustworthy agentic AI requires not only trustworthy agents, but trustworthy delegation.

This document is a working specification for discussion within the ITU-T Focus Group on Trust and Identity for Humans and Agentic AI (FG-TIDA). It does not constitute an ITU-T Recommendation or an approved ITU-T standard.

History
-------

.. list-table::
   :header-rows: 1
   :widths: 10 26 32 14 18

   * - Version
     - Document
     - Approval
     - Focus Group
     - Working Group
   * - 0.6
     - Human and Organizational Readiness for Trusted Agentic AI
     - 2026-11-26; working draft, not approved. Changes: restore FG-TIDA PDF front-matter and TOC controls; align History table and hidden numbered toctree with the official template.
     - TIDA
     - Not yet assigned
   * - 0.5
     - Human and Organizational Readiness for Trusted Agentic AI
     - 2026-11-26; working draft, not approved. Changes: add HORA-REQ-001 to HORA-REQ-020; clarify applicability and evidence; replace template demonstration content with HORA-TAI chapters and assessment annexes; apply BCP 14 conventions; correct Annex A table.
     - TIDA
     - Not yet assigned
   * - 0.4
     - Human and Organizational Readiness for Trusted Agentic AI
     - 2026-11-26; working draft, not approved. Changes: align front matter and document structure with the FG-TIDA specification template; synchronize source, repository, and PDF version metadata.
     - TIDA
     - Not yet assigned
   * - 0.3
     - Human and Organizational Readiness for Trusted Agentic AI
     - 2026-11-15; working draft, not approved. Changes: refine assessment architecture; distinguish agent capability, human readiness, and organizational readiness; separate delegation autonomy from potential consequence; clarify traceability and assurance evidence.
     - TIDA
     - Not yet assigned
   * - 0.2
     - Human and Organizational Readiness for Trusted Agentic AI
     - 2026-09-22; working draft, not approved. Changes: earlier working version.
     - TIDA
     - Not yet assigned
Authors
-------

.. list-table::
   :header-rows: 1
   :widths: 22 43 35

   * - Name
     - Affiliation
     - Contact
   * - Dr. Islam Gouda
     - Humanized AI Economy Initiative
     - islamgouda@hotmail.com

Keywords
--------

Agentic AI, human oversight, organizational readiness, delegated authority, accountability, traceability, AI assurance, human agency, workforce readiness, trusted AI, continuous assurance.

.. raw:: latex

    \newpage
    \osiacenternextsection

Foreword
--------

Agentic AI introduces a shift from AI systems that primarily provide information or recommendations toward systems that can interpret objectives, plan actions, use tools, interact with external systems, and execute tasks on behalf of people and organizations.

This shift creates a complementary trust challenge. An agent may possess appropriate technical safeguards while the human or organization delegating authority to that agent may lack the capabilities, processes, governance, or workforce readiness required to supervise and remain accountable for its actions.

The Focus Group on Trust and Identity for Humans and Agentic AI (FG-TIDA) addresses trust management and interoperable digital identity infrastructure for humans and agentic AI, supporting the development of secure and trustworthy digital ecosystems in which humans and agentic AI can safely interact and collaborate.

This specification complements that work by focusing on the human and organizational conditions surrounding delegated authority. It proposes that the assessment of trusted agentic AI should consider not only whether an agent can be trusted to perform a task, but also whether the relevant human and organizational actors are prepared to delegate that task under defined conditions.

The proposed framework considers meaningful human oversight, delegation boundaries, accountability, traceability, workforce capabilities, organizational governance, and continuous assurance. It is intended to provide a common vocabulary and a structured basis for further discussion, experimentation, and potential standardization.

The framework is designed to be technology-neutral. It does not prescribe a particular AI model, architecture, identity mechanism, or deployment environment. Instead, it focuses on the relationship between agent capability, delegated authority, human oversight, and organizational readiness.

This document is submitted as a working specification for discussion within FG-TIDA. The concepts, terminology, levels, and requirements presented here are proposals for further review and refinement by the Focus Group and its participants.

.. raw:: latex

    \osiacenternextsection

Note
----

This document is a working specification for discussion and is not an ITU-T Recommendation or approved ITU-T standard. The terminology, framework dimensions, delegation levels, requirements, and assessment methodology are proposals that may be revised through the FG-TIDA development process.

The Working Group assignment for this contribution has not yet been made by FG-TIDA. This document remains an independent working proposal for discussion and refinement; its inclusion in the DataTracker does not imply endorsement or approval by ITU-T or FG-TIDA.

The key words **MUST**, **MUST NOT**, **REQUIRED**, **SHALL**, **SHALL NOT**, **SHOULD**, **SHOULD NOT**, **RECOMMENDED**, **NOT RECOMMENDED**, **MAY**, and **OPTIONAL** in this document are to be interpreted as described in BCP 14, comprising RFC 2119 and RFC 8174, when and only when they appear in uppercase. These terms express proposed requirement levels within this working specification and are submitted for review and refinement by FG-TIDA; they do not, by themselves, establish obligations under an approved ITU-T Recommendation or regulation.

Intellectual Property Rights
-----------------------------

This document is submitted as a working contribution for discussion within FG-TIDA. Any intellectual property disclosures, licensing conditions, and use obligations applicable to this contribution are governed by the relevant ITU-T and FG-TIDA procedures. This statement does not assert the absence of third-party intellectual property claims or imply approval or endorsement by ITU-T.

Content
-------

.. raw:: latex

    %% Copyright notice intentionally omitted for this independent working proposal.
    %% Restore the template's TOC handling and begin numbered main matter.
    \let\addcontentsline\osiaorigaddcontentsline
    \sphinxtableofcontents
    \osiamainmatter

.. toctree::
   :maxdepth: 3
   :numbered:
   :hidden:

   chapters/01_chapter1
   chapters/02_chapter2
   chapters/03_chapter3
   chapters/04_chapter4/index
   chapters/05_annex/index
   chapters/06_appendix/index
   chapters/07_references
