# A/B Test Results Analysis Template

## Experiment Metadata

- **Experiment:** `[Name]`
- **Status:** `[Preliminary / final]`
- **Pre-registration:** `[Link]`
- **Decision owner:** `[Role]`
- **Test window:** `[Start and end, including timezone]`
- **Assignment unit:** `[Unit]`
- **Exposure definition:** `[Definition]`

## Decision And Hypothesis

`[Restate the decision, expected behavior, and proposed mechanism without changing the original hypothesis after seeing results.]`

## Sample And Data Quality

| Check | Result | Interpretation Or Action |
| --- | --- | --- |
| Eligible sample by variant | `[Counts]` | `[Note]` |
| Sample-ratio mismatch | `[Result]` | `[Note]` |
| Missing or duplicate events | `[Result]` | `[Note]` |
| Cross-variant contamination | `[Result]` | `[Note]` |
| Accessibility or performance parity | `[Result]` | `[Note]` |

Document exclusions exactly as preregistered. Explain deviations before reporting outcome metrics.

## Results

| Metric | Control | Variant | Absolute Difference | Relative Difference | Interval Or Uncertainty | Decision Threshold |
| --- | --- | --- | --- | --- | --- | --- |
| Primary | `[Value]` | `[Value]` | `[Value]` | `[Value]` | `[Interval]` | `[Met/not met]` |
| Guardrail | `[Value]` | `[Value]` | `[Value]` | `[Value]` | `[Interval]` | `[Within/exceeded]` |

## Segment Analysis

Separate preregistered segment tests from exploratory cuts. Report sample sizes and interaction evidence; do not infer a segment effect because one subgroup is significant and another is not.

## Qualitative And Operational Context

Summarize relevant usability evidence, accessibility issues, support contacts, implementation incidents, or feedback that helps explain—not override—the experiment. Link to sources and distinguish evidence collected before and during the test.

## Interpretation

- **What the result supports:** `[Statement]`
- **What it does not establish:** `[Boundary]`
- **Alternative explanations:** `[Possibilities]`
- **Practical significance:** `[Why the effect matters or does not]`
- **Limitations:** `[Validity, seasonality, instrumentation, novelty, sample]`

## Decision

- **Disposition:** `[Ship / iterate / stop / retest / no change]`
- **Rationale:** `[Primary, guardrails, uncertainty, and constraints]`
- **Owner:** `[Role]`
- **Rollout or rollback plan:** `[Plan]`
- **Monitoring window:** `[Duration and metrics]`

## Follow-Up

Record the next research, design, analytics, engineering, accessibility, and communication actions. Publish null and negative results so the organization does not repeat the test without new evidence.
