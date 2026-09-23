# Reusable AI Workflow Risk Checklist

## Before starting
- [ ] Confirm the AI tool/environment is approved for this data. Check with your organization if unsure.
- [ ] Scan inputs for restricted content: client-identifying information, financial data, real personal data, unreleased pricing/roadmap, credentials, or other confidential material.

## Choose the simplest safe building block
- [ ] Is the step organizing, formatting, or summarizing known information? Use straightforward summarization.
- [ ] Does it require inferring intent, weighing tradeoffs, or working through incomplete information? Use reasoning deliberately.
- [ ] Does it require a fact that could be outdated or wrong? Verify it with an approved source/search capability.
- [ ] Does it require broad synthesis across many external sources? Use deeper research only when the task truly needs it.
- [ ] Default to the lightest capability that does the job.

## Before sharing or acting on output
- [ ] Does every claim or criterion trace back to an actual input rather than an inference presented as fact?
- [ ] Are assumptions and open questions explicitly flagged?
- [ ] Are dependencies on other people or teams confirmed with them directly?
- [ ] Is confidential, restricted, or personal information present that should not be shared with this audience?
- [ ] Would you be comfortable if the output were reviewed by your manager or the people it concerns, as-is?
- [ ] Is there a policy question that should be confirmed with your organization?

## Human decision points: do not delegate
- [ ] Final confirmation of cross-team or vendor dependencies
- [ ] Final sprint, timing, or delivery commitments
- [ ] Decisions involving confidential, regulated, or personal data
- [ ] Final go/no-go on what enters the meeting or gets sent onward
