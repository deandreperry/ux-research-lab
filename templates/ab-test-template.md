# A/B Test Pre-Registration Template

## Experiment Metadata

- **Experiment:** `[Name]`
- **Status:** `Pre-registration; not started`
- **Decision owner:** `[Role]`
- **Analysis owner:** `[Role]`
- **Planned dates:** `[Dates]`
- **Assignment unit:** `[User, account, organization, or session]`

## Decision And Rationale

`[State the decision, existing evidence, and why an experiment is necessary.]`

## Hypothesis

`[If change, then behavior, because mechanism.]`

## Eligibility And Exclusions

- **Included:** `[Rules]`
- **Excluded:** `[Employees, bots, existing users, test traffic, or other preregistered rules]`
- **Exposure definition:** `[When assignment counts as exposure]`
- **Contamination risks:** `[Cross-device, shared account, repeat exposure]`

## Variants

| Version | Description | Accessibility And Performance Parity |
| --- | --- | --- |
| Control | `[Current experience]` | `[Checks]` |
| Variant | `[One intentional change]` | `[Checks]` |

## Metrics

| Type | Metric | Numerator | Denominator | Window | Direction Or Limit |
| --- | --- | --- | --- | --- | --- |
| Primary | `[Metric]` | `[Definition]` | `[Definition]` | `[Window]` | `[Target]` |
| Guardrail | `[Metric]` | `[Definition]` | `[Definition]` | `[Window]` | `[Limit]` |

## Sample And Statistical Plan

- **Baseline:** `[Value and period]`
- **Minimum practically important effect:** `[Absolute and relative]`
- **Significance level:** `[Alpha]`
- **Power:** `[Target]`
- **Required sample per variant:** `[Calculated value]`
- **Multiple comparisons:** `[Adjustment or limitation]`
- **Planned model or test:** `[Method]`
- **Missing data:** `[Treatment]`
- **Stopping rule:** `[Fixed horizon or approved sequential method]`

Do not stop when a desirable result appears. If traffic cannot support the plan, choose a different method.

## Randomization And Instrumentation

Document assignment persistence, identity handling, event names, properties, attribution, timezones, late events, quality checks, and sample-ratio mismatch response.

## Segmentation

List only preregistered, decision-relevant segments. Label all other subgroup analysis exploratory and avoid shipping from a small favorable subgroup.

## Ethical And Operational Review

Confirm truthful content, informed expectations, privacy, accessibility parity, performance parity, risk to vulnerable users, rollback ownership, and customer-support readiness.

## Decision Rule

`[State practical and statistical criteria, guardrail limits, and actions for positive, negative, and inconclusive results.]`

## Reporting

Report absolute and relative effects, uncertainty, sample, exclusions, quality checks, null or negative results, implementation incidents, limitations, decision, and follow-up.
