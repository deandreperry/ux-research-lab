# Accessibility Platform Research Plan

- **Status:** Research proposal; participant findings and outcomes pending

- **Decision owner:** Product lead with accessibility, design, engineering, and QA partners

## Background

The accessibility platform is a proposed tool for helping teams learn, audit, and apply accessibility practices across frontend work. It combines learning modules, checklists, audit workflows, and plain-language remediation guidance.

## Problem Statement

Teams often treat accessibility as a late-stage compliance task instead of an ongoing product quality practice. Existing tools may flag issues but fail to help teams understand impact, priority, and remediation.

## Research Goals

- Understand how teams currently learn and apply accessibility guidance.
- Identify gaps between automated test results and human-centered accessibility decisions.
- Explore how users with disabilities evaluate trust, clarity, and usability.
- Define requirements for actionable audit workflows.

## Research Questions

- Which accessibility tasks are confusing for designers and developers?
- How do teams decide which accessibility issues to fix first?
- What information helps users understand impact beyond compliance language?
- How should the platform support keyboard, screen reader, and cognitive accessibility needs?

## Target Users

- Frontend developers
- UX designers
- QA testers
- Accessibility learners
- Users of assistive technologies

## Methodology

| Method | Proposed Sample | Rationale |
| --- | --- | --- |
| Standards and workflow review | WCAG guidance, internal process, and comparable tools | Establish known requirements and tool limitations without treating desk research as user evidence |
| Recent-experience team interviews | 6–8 design, engineering, QA, product, and accessibility practitioners | Understand ownership, prioritization, and remediation decisions |
| Compensated sessions with disabled participants | Recruit across relevant access experiences; document sample coverage and gaps | Evaluate whether impact language and the prototype reflect lived experience |
| Accessible task-based prototype testing | Product-team and disabled participants | Test audit, validation, prioritization, and handoff behavior |

## Product Validation Criteria

- Users can distinguish severity, impact, and remediation effort.
- Accessibility guidance is understandable without specialist language.
- Keyboard and screen reader users can complete core audit tasks.
- Product teams can translate findings into trackable implementation work.

Research success also requires traceable evidence, accessible participation, explicit recommendation owners, and documented stakeholder decisions.

## Recruitment And Inclusion

Recruit based on relevant tasks and access experiences rather than using “people with disabilities” as one homogeneous segment. Document which disability, assistive-technology, communication, and product-role perspectives are present and absent. Do not require diagnosis disclosure. Compensate pilots and completed or participant-ended sessions fully.

## Ethics, Accommodations, And Data Handling

- Ask participants how they prefer disability-related language to be used.
- Offer accessible materials in advance, flexible pacing, breaks, captions, keyboard access, and participant-selected assistive technology.
- Obtain separate consent for recording and public excerpts.
- Do not ask participants to disclose unnecessary medical information or act as unpaid accessibility educators.
- Store recruiting information separately and publish only consented, de-identified evidence.
- Have disabled advisors and accessibility specialists review the protocol and prototype before recruitment.

## Analysis Plan

Analyze product-team workflow evidence separately from disabled participants’ experience evidence before examining intersections. Code observation, impact, ownership, prioritization, and remediation themes. Preserve disagreements and avoid translating frequency in a small sample into prevalence. Each recommendation must show its evidence source, affected experience, confidence, owner, and validation need.

## Communication Plan

Provide an accessible pre-read, plain-language executive summary, and decision workshop. Record whether recommendations are adopted, tested, deferred, or declined. Share a participant-facing summary in an accessible format when requested.

## Timeline

| Week | Activity |
| --- | --- |
| 1 | Define audit workflow assumptions and accessibility principles |
| 2 | Conduct team interviews and review comparable tools |
| 3 | Evaluate prototype flows with accessibility-focused tasks |
| 4 | Deliver findings, severity model, and roadmap recommendations |

## Risks And Assumptions

- Accessibility needs vary widely and should not be generalized from one user group.
- Automated checks cannot represent the complete accessibility experience.
- Simulated findings are not a substitute for testing with disabled users.
- Recommendations should be reviewed by accessibility specialists before production use.

## Expected Outputs

- Accessibility workflow findings
- Audit prioritization model
- Content clarity recommendations
- Inclusive testing checklist
- Product roadmap considerations
