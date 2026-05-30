# Usability Test Plan

**Artifact type:** Portfolio Simulation

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

## Tasks

1. Find a lesson about accessible form validation.
2. Start the lesson and explain what you expect to learn.
3. Complete the first coding task.
4. Recover from an intentionally triggered error.
5. Use feedback to decide what to do next.
6. Find where to review completed lesson progress.

## Success Criteria

- Participant reaches the correct lesson without moderator help.
- Participant understands the lesson objective.
- Participant completes the first task or can explain what blocked them.
- Participant uses error feedback to attempt recovery.
- Participant understands completion state and next recommended action.

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

Findings will be documented in `findings-report.md` and prioritized with `severity-matrix.md`.

## Recommendations

Recommendations will focus on navigation clarity, instruction sequencing, error feedback, progress visibility, and accessibility of learning interactions.
