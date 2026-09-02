# Accessibility Audit Hypothesis Journey

- **Status:** Assumption map; disabled-participant and team-workflow validation required

The “Thoughts” entries are illustrative prompts, not participant quotations. Product-team and disabled-participant evidence must remain distinguishable.

## Scenario

A product team member uses an accessibility platform to audit a form workflow before release.

## User Goal

Identify accessibility issues, understand their user impact, prioritize fixes, and communicate next steps to the team.

## Stages

| Stage | Actions | Thoughts | Pain Points | Opportunities | UX Recommendations |
| --- | --- | --- | --- | --- | --- |
| Prepare | Opens audit checklist and selects form workflow. | "What should I test first?" | Audit scope may feel broad. | Guide users by product area and risk. | Provide workflow-specific audit templates. |
| Detect | Runs automated checks and reviews manual steps. | "Which findings matter most?" | Tool output can feel noisy. | Separate issue detection from severity. | Group findings by impact, not only rule. |
| Validate | Tests keyboard flow and reviews labels, errors, and focus. | "Can users actually complete this?" | Manual testing steps may be unfamiliar. | Teach while auditing. | Add short instructions and expected behavior examples. |
| Prioritize | Compares severity, frequency, and fix effort. | "What should we fix before release?" | Priority can be confused with engineering effort. | Make tradeoffs visible. | Use a matrix with user impact and effort separated. |
| Communicate | Creates tickets and shares recommendations. | "How do I explain this clearly?" | Findings may lack user impact language. | Improve cross-functional handoff. | Generate issue summaries with evidence, impact, and next action. |

## UX Recommendations

- Combine automated checks with guided manual validation.
- Explain impact in plain language before technical remediation.
- Provide role-based views for design, development, QA, and product.
- Make audit outputs easy to convert into implementation tasks.

## Validation Plan

Observe product-team audit work and compensated disabled participants using an accessible prototype. Attach evidence IDs and source type to every validated stage. Document alternate paths, access barriers, skipped automation, specialist escalation, and failed remediation rather than forcing one ideal workflow.
