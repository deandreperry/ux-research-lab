# Signup CTA A/B Test

- **Status:** Pre-registration draft; experiment not run

## Hypothesis

A task-oriented CTA will increase signups for a frontend learning platform because users will understand the immediate value of starting.

## Control

Button label: "Sign Up"

## Variant

Button label: "Start Learning Frontend"

## Primary Metric

Signup start rate: unique eligible visitors who begin signup divided by unique eligible visitors exposed to a variant.

## Secondary Metrics

- Account completion rate
- Lesson start rate after signup
- CTA click-through rate
- Bounce rate from the signup page
- Return visits within seven days

## Sample Size Considerations

Before launch, document baseline signup-start rate, minimum practically important lift, significance level, statistical power, expected traffic, and calculated sample per variant. Run through complete business cycles and do not stop when a desirable result first appears. If traffic cannot support the required sample, use qualitative message testing rather than an underpowered experiment.

## Directional Hypothesis

The variant is expected to increase CTA clicks because it makes the outcome more concrete.

## Decision Rule

Adopt the variant only when the preregistered analysis indicates a practically meaningful improvement in signup starts and account completion, lesson starts, accessibility errors, and bounce guardrails remain within agreed limits. Report uncertainty and absolute as well as relative change. An increase in clicks with lower completion indicates that the label may overpromise value.

## Follow-Up Action

Test CTA copy by user intent, such as "Practice Accessible Forms" for learners entering from accessibility content.

## Assignment And Instrumentation

- Randomize eligible unique visitors at the user level and persist assignment across visits.
- Exclude employees, bots, duplicate identities, and users already enrolled according to preregistered rules.
- Log exposure only when the CTA is rendered and viewable.
- Define event names, properties, identity resolution, attribution window, and missing-event handling before launch.
- Run sample-ratio mismatch, cross-device contamination, and event-quality checks.

## Guardrails And Segmentation

Guardrails include account completion, lesson start, accessibility failures, page performance, support contacts, and misleading-copy complaints. Experience-level or acquisition-channel analysis is exploratory unless powered and preregistered; do not ship based on a small favorable subgroup.

## Ethical Review

The variant must describe the next action accurately. Do not hide account requirements, imply immediate access that is unavailable, or introduce accessibility differences between conditions.
