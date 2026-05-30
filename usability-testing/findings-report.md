# Usability Findings Report

**Artifact type:** Portfolio Simulation

## Product Tested

Interactive frontend learning platform focused on accessible form validation.

## Test Objectives

- Evaluate lesson discovery.
- Assess clarity of task instructions.
- Understand error recovery behavior.
- Identify improvements to progress visibility and confidence.

## Participant Criteria

This simulation assumes beginner to intermediate frontend learners. It does not claim that live sessions were conducted.

## Summary Of Findings

| Finding | Severity | Evidence Pattern | Recommendation |
| --- | --- | --- | --- |
| Lesson titles were understandable, but filters were too broad. | Medium | Users could search by topic but struggled to narrow by skill level. | Add skill level, topic, and accessibility filters with clear labels. |
| Prerequisites were easy to miss. | High | Learners started tasks before understanding required HTML knowledge. | Place prerequisites before the start button and summarize them in plain language. |
| Error messages identified failure but did not always explain recovery. | High | Users knew something was wrong but were unsure what to change. | Pair each error with likely cause, example fix, and link to concept review. |
| Progress state was visible after completion but weak during tasks. | Medium | Learners wanted reassurance that partial steps were moving forward. | Add step-level progress and "saved" or "checked" feedback. |
| Accessibility concepts needed more user impact context. | Medium | Learners understood rules better when connected to form users. | Add short impact notes explaining who is affected and why it matters. |

## Recommendations

- Make prerequisites impossible to miss before task start.
- Add recovery-focused error feedback, not just validation failure states.
- Include expected output examples for each step.
- Use progressive hints so learners can recover without giving away the answer immediately.
- Add accessibility impact notes near implementation steps.

## Success Criteria Review

| Criterion | Simulated Result |
| --- | --- |
| Find relevant lesson | Mostly successful with search; filtering needs refinement. |
| Understand lesson objective | Successful when objective is visible above the fold. |
| Complete first coding task | Mixed; errors increased when prerequisites were skipped. |
| Recover from error | Needs improvement; feedback should be more actionable. |
| Understand next step | Mostly successful after completion, weaker during active tasks. |

## Next Research Step

Run a follow-up usability test with revised prerequisites, improved error feedback, and clearer step-level progress indicators.
