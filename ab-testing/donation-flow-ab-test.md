# Donation Flow A/B Test

- **Status:** Pre-registration draft; experiment not run and impact claims not validated

## Hypothesis

Adding a concise impact statement near the donation amount selection will increase donation completion because users will better understand how their contribution may help.

## Control

Current donation flow with donation amounts, payment fields, and a generic "Donate" button.

## Variant

Donation flow includes short impact examples next to common donation amounts, such as what a small, medium, or larger contribution could support.

## Primary Metric

Donation completion rate: unique eligible donors who complete a donation divided by unique eligible donors exposed to and starting the tested flow. Also report completion among all exposed visitors so the denominator does not hide upstream effects.

## Secondary Metrics

- Donation form start rate
- Drop-off at amount selection
- Average donation amount
- Time to complete donation
- Clicks on financial transparency or impact links

## Sample Size Considerations

Document baseline conversion, minimum practically important lift, significance level, power, expected traffic, seasonality, attribution window, and calculated sample per variant before launch. Do not extend indefinitely or stop when a desirable result appears. If traffic is insufficient, use comprehension testing and phased observation rather than an underpowered experiment.

## Directional Hypothesis

The variant is expected to improve completion among first-time donors by reducing uncertainty about impact.

## Decision Rule

Ship only when the preregistered analysis shows a practically meaningful completion improvement and guardrails for comprehension, accessibility, payment error, refund, support contact, recurring-donation understanding, and average donation remain within agreed limits. Report absolute change, uncertainty, exclusions, and null or negative findings.

## Follow-Up Action

Test whether impact examples work better as amount-specific microcopy, a short story link, or a post-donation reassurance message.

## Assignment And Instrumentation

- Randomize eligible visitors at the user level and persist assignment through the payment journey.
- Define exposure, start, amount selection, payment error, completion, refund, and support events.
- Exclude staff, test transactions, bots, and duplicate activity through preregistered rules.
- Check sample-ratio mismatch, event parity, payment-provider differences, and device imbalance.
- Avoid running across materially different fundraising events unless period effects are modeled in advance.

## Ethical And Content Safeguards

Every impact example must be verified by the organization, qualified when costs vary, and reviewed for respectful representation of communities served. Do not use guilt, false scarcity, confusing recurring-donation defaults, or a more accessible experience in only one condition. Privacy, payment security, and accessibility failures override conversion gains.
