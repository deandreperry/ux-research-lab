# Onboarding Copy A/B Test

- **Status:** Pre-registration draft; experiment not run

## Hypothesis

Onboarding copy that normalizes mistakes and explains error recovery will improve lesson completion because beginner learners will feel safer continuing after a failed step.

## Control

Standard onboarding copy that explains platform features and lesson structure.

## Variant

Onboarding copy adds reassurance: mistakes are expected, feedback will explain what happened, and learners can use hints before revealing answers.

## Primary Metric

First lesson completion rate: eligible newly enrolled learners completing the defined lesson within the attribution window divided by eligible learners who start it.

## Secondary Metrics

- Hint usage
- Error recovery rate
- Drop-off after first failed validation
- Self-reported confidence after lesson
- Return rate for a second lesson

## Sample Size Considerations

Use baseline completion, a minimum practically important lift, significance level, power, expected traffic, and attrition to calculate the required sample before launch. Experience-level effects are exploratory unless the study is powered and preregistered for interaction analysis. Confidence is supporting self-report, not the sole success measure.

## Directional Hypothesis

The variant is expected to improve completion for beginner learners and reduce abandonment after errors.

## Decision Rule

Ship only when the preregistered analysis shows a practically meaningful improvement in completion or independent recovery and guardrails for time, hint dependence, accessibility, return behavior, and intermediate-user friction remain within agreed limits. Report uncertainty, absolute change, exclusions, and null or negative results.

## Follow-Up Action

Explore adaptive onboarding that changes based on learner confidence, prior experience, or first-task behavior.

## Assignment And Instrumentation

- Randomize eligible new learners at the account level and persist assignment.
- Define lesson start, failure, hint, recovery, completion, return, and exposure events before launch.
- Log whether recovery was independent, hint-assisted, or required support.
- Check sample-ratio mismatch, missing events, repeated exposure, and instrumentation parity.
- Use a fixed attribution window and document timezone and late-arriving events.

## Guardrails And Ethics

Guardrails include task errors, time to completion, hint dependence, accessibility failures, frustration or support signals, and seven-day return. Reassurance must not minimize real consequences, conceal destructive commands, or encourage users to ignore warnings. Run only in a safe learning environment.
