# Severity Matrix

**Artifact type:** Portfolio Simulation

## Severity Model

Severity is based on user impact, task blockage, frequency, and recovery effort.

| Severity | Definition | Product Response |
| --- | --- | --- |
| Critical | Prevents task completion for many users or creates a serious accessibility barrier. | Fix before release. |
| High | Causes major confusion, requires help, or significantly reduces confidence. | Prioritize in the next iteration. |
| Medium | Slows users down but allows independent recovery. | Schedule after high-severity issues. |
| Low | Minor clarity, polish, or preference issue. | Address when related work is already planned. |

## Issue Matrix

| Issue | Impact | Frequency | Recovery | Severity | Recommended Action |
| --- | --- | --- | --- | --- | --- |
| Prerequisites are easy to miss | Users start tasks without needed context | Common | Difficult without backtracking | High | Move prerequisites before lesson start and summarize skill needs. |
| Error feedback lacks next action | Users know task failed but not how to recover | Common | Moderate to difficult | High | Add likely cause, example correction, and concept link. |
| Filters do not support learner level | Users choose lessons that are too easy or too advanced | Occasional | Moderate | Medium | Add beginner, intermediate, advanced, and topic filters. |
| Progress during task is unclear | Users are unsure whether partial work is saved | Occasional | Easy to moderate | Medium | Add step status and save confirmation. |
| Accessibility impact appears late | Learners see rules before understanding why they matter | Occasional | Easy | Medium | Add brief impact notes near each accessibility concept. |
| Button label "Continue" is vague | Users do not know whether it saves, submits, or moves forward | Occasional | Easy | Low | Use task-specific labels such as "Check answer" or "Next step." |

## Prioritization Notes

The highest priority issues are those that reduce learner confidence and prevent independent recovery. For an education product, confusion is not just friction; it can change whether a user believes they are capable of continuing.
