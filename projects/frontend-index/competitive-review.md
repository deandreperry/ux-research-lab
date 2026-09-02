# Frontend Index Competitive Review

- **Status:** Completed desk review of public documentation; reviewed September 2, 2026
- **Purpose:** Identify content-model and navigation assumptions to test with practitioners
- **Important limitation:** This review describes published documentation. It does not establish how users behave, which system performs best, or what Frontend Index should build.

## Review Questions

1. How are components and task-level patterns separated?
2. What information helps a reader judge when to use or avoid a pattern?
3. Where do accessibility and implementation details appear?
4. How is guidance connected to reusable code or structured data?

## Sources Reviewed

| Source | Desk-Review Observation | Assumption To Test |
| --- | --- | --- |
| [GOV.UK Design System](https://design-system.service.gov.uk/) | Separates styles, reusable components, and task-oriented patterns. Individual component guidance can include “when to use” and “when not to use” sections. | Users may benefit from a visible distinction between interface parts and user-task patterns. |
| [GOV.UK accordion guidance](https://design-system.service.gov.uk/components/accordion/) | Explains appropriate and inappropriate contexts and explicitly recommends testing content without the component first. | “When not to use” and an alternative may support a more defensible choice than implementation instructions alone. |
| [U.S. Web Design System](https://designsystem.digital.gov/) | Presents components with UX, accessibility, and implementation guidance and offers separate inclusive-experience patterns. | Bringing multiple evidence types into one entry may reduce context switching, but density and discoverability require testing. |
| [Adobe Spectrum](https://spectrum.adobe.com/) | Connects design guidance to multiple open-source implementations. | Readers may need a shared conceptual summary before framework-specific implementation detail. |
| [Spectrum Design Data component format](https://opensource.adobe.com/spectrum-design-data/spec/component-format/) | Its structured component model can include purpose, anatomy, states, lifecycle, tokens, documentation, and accessibility information. | A structured schema may improve consistency and search, but required fields could create maintenance burden. |

## Cross-Source Patterns

### Guidance And Implementation Are Related But Distinct

The reviewed systems connect design intent to implementation without presenting code as the entire decision. Frontend Index should test a shared decision summary followed by progressive technical depth.

### Components And User Tasks Need Different Entry Points

Government systems visibly distinguish reusable components from patterns that help users complete tasks. Frontend Index should test whether its audience understands that distinction or prefers task, component, and accessibility facets within one search model.

### Accessibility Is Part Of The Content Model

The sources place accessibility within component or pattern guidance rather than only in a separate compliance destination. Frontend Index should test placement, comprehension, and whether accessibility evidence changes a choice.

### Governance Affects Trust

Published implementations, version or lifecycle detail, and explicit usage rules may signal that guidance is maintained. Interviews should determine which signals actually influence trust and which add noise.

## Gaps This Review Cannot Answer

- Which entry point practitioners use during real work
- Whether users read guidance before copying code
- Which details cause someone to reject a pattern
- How organizational standards constrain choice
- Whether a comparison feature would improve decisions
- Which accessibility language is understandable and actionable

## Prototype Implications

The desk review supports testing—not adopting—the following content fields: purpose, use and avoid guidance, alternatives, anatomy, states, accessibility behavior, implementation constraints, examples, lifecycle, and source evidence. See the [prototype specification](prototype-spec.md).
