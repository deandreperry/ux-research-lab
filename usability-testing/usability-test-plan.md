# Usability Test Plan

- **Status:** Study-ready portfolio simulation; no sessions completed
- **Decision owner:** Learning-product lead
- **Planned sample:** 5–6 formative sessions
- **Session length:** 45 minutes

## Product

An interactive frontend learning platform that teaches UI implementation through guided lessons, code tasks, feedback, and visual previews.

## Test Objectives

- Evaluate whether learners can find the right lesson for their goal.
- Identify where instructions, code tasks, or feedback create confusion.
- Assess whether progress indicators help users understand what to do next.
- Understand how learners recover from errors.

## Participant Criteria

- Beginner to intermediate frontend learners
- Familiarity with HTML and CSS basics
- Limited to moderate JavaScript experience
- Mix of self-taught learners, bootcamp students, and designers learning implementation

Participants must have attempted a frontend learning activity in the previous six months. Recruit for variation in recent CLI use and assistive-technology needs. Exclude routine professional users if their expertise makes the beginner tasks unrealistic. Record recruitment source and sample gaps.

## Tasks

1. Find a lesson about accessible form validation.
2. Start the lesson and explain what you expect to learn.
3. Complete the first coding task.
4. Recover from an intentionally triggered error.
5. Use feedback to decide what to do next.
6. Find where to review completed lesson progress.

## Task Success Criteria

- Participant reaches the correct lesson without moderator help.
- Participant understands the lesson objective.
- Participant completes the first task or can explain what blocked them.
- Participant uses error feedback to attempt recovery.
- Participant understands completion state and next recommended action.

For every task, record independent completion, completion with a hint, completion with moderator intervention, abandonment, time as contextual evidence, path, errors, and participant explanation. Do not collapse these states into one success percentage.

## Method Rationale

Moderated formative testing is appropriate because the team needs to observe comprehension and recovery before implementation. The method will not estimate market demand, long-term learning, or production conversion. A delayed comparable task is required before making retention claims.

## Consent, Accessibility, And Safety

- Explain purpose, duration, incentive, recording, data use, and retention before consent.
- Obtain separate permission for recording and public de-identified excerpts.
- Ask about accommodations and test the prototype with keyboard, screen reader, zoom, and reduced motion.
- Run code tasks in an isolated sandbox with no access to participant files or accounts.
- Participants may skip tasks, take breaks, or stop and still receive the stated incentive.

## Session Operations

- Pilot the protocol with one eligible participant.
- Use a standardized build and record its version.
- Assign a moderator and note-taker when possible.
- Log technical failures separately from usability issues.
- Record all hints and interventions.

## Analysis Plan

Map observations to research questions and task IDs. Separate behavior, participant explanation, and researcher interpretation. Compare patterns by recent experience without implying prevalence. Preserve counterexamples. Require evidence IDs, relevant denominators, confidence, limitation, and decision owner for each reported finding.

## Error Tracking

| Error Type | Description |
| --- | --- |
| Navigation error | User chooses the wrong lesson, filter, or path. |
| Comprehension error | User misinterprets instructions or task purpose. |
| Input error | User enters incorrect code or interacts with the wrong field. |
| Recovery error | User cannot interpret feedback or repair the issue. |
| Confidence drop | User expresses uncertainty, frustration, or fear of continuing. |

## Severity Levels

- Critical: Blocks task completion and no recovery path is clear.
- High: Causes significant delay or requires moderator intervention.
- Medium: Creates confusion but user can recover independently.
- Low: Minor friction, wording issue, or visual clarity concern.

## Findings

Findings will be documented using the [illustrative findings format](findings-report.md) and prioritized with the [severity matrix](severity-matrix.md). Hypothetical examples will be removed when real reporting begins.

## Recommendations

Recommendations will focus on navigation clarity, instruction sequencing, error feedback, progress visibility, and accessibility of learning interactions.

Each recommendation must identify an owner, evidence IDs, user impact, priority rationale, stakeholder disposition, and follow-up measure.
