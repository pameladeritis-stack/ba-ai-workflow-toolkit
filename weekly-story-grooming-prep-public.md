---
name: weekly-story-grooming-prep
description: "Prepares user stories for a recurring grooming and technical review meeting by drafting an As a / I want / So that statement, drafting acceptance criteria, and flagging gaps against a completeness checklist using ticket content and visual comps."
---

# Weekly Story Grooming Prep

## Purpose

This skill turns raw work-item tickets and visual comps into meeting-ready user stories. The meeting should be able to focus on implementation approach, technical risks/dependencies, and next steps rather than spending its time discovering basic gaps.

Story sizing and sprint placement remain with the development team and are outside this skill.

Treat every output as a draft for human review. The value of the skill is first-pass synthesis and gap detection, not replacing BA judgment about what is true, risky, or ready to commit to.

## Before starting: data sensitivity pre-check

Before processing any ticket or comp, scan it for content that should not be shared with the AI tool or environment being used, including client-identifying information, financial data, real customer/employee personal data, vendor contract terms, credentials, or unreleased pricing, roadmap, or strategic initiatives.

If questionable content is present, stop rather than guessing whether it is safe to process.

## Workflow

Process one story at a time so assumptions and gaps do not blur across stories.

### Step 1: Intake

Confirm that both the ticket content and the visual comp are available. The comp may be an image, description, or approved link. If either is missing, flag it rather than drafting from incomplete information.

### Step 2: Write the User Story Statement

Write a concise "As a / I want / So that" statement.

- Write from the point of view of the relevant end user.
- Keep each clause concise.
- Base the statement on the actual problem and intended solution, not a generic restatement of the ticket title.

### Step 3: Draft Acceptance Criteria

Read the ticket and comp together.

- Base each criterion only on what is stated or reasonably inferable from the approved inputs.
- Cover the primary flow, at least one relevant edge case, and any error/empty state visible in the comp.
- If the comp and ticket conflict, call out the mismatch rather than silently choosing one.
- Order criteria in a way that makes review easy for your team. If visual layout matters, mirror the comp's visual sequence.

Suggested format:

### Scenario 1: [Scenario title]
Verify that [specific, testable behavior].
Verify that [another specific, testable behavior].

### Scenario 2: [Scenario title]
Verify that [specific, testable behavior].

Always include an **Assumptions & Open Questions** section. Anything inferred, unclear, or requiring team confirmation belongs there.

### Step 4: Gap Check

Check the story for:
- Clear problem statement
- Visual comp or design reference
- Acceptance criteria
- Dependencies
- Unresolved questions or mismatches

If another team appears to be a dependency, flag it for confirmation. Do not claim that a cross-team dependency is resolved based on the ticket alone.

### Step 5: Consolidate

Combine the user story statement, acceptance criteria, flagged gaps, and assumptions/open questions into one per-story summary. Confirm that nothing was dropped or materially altered during consolidation.

### Step 6: Feed Forward

After the meeting, carry unresolved gaps and questions into the next preparation cycle. Mark something resolved only when a human confirms that it was resolved.

## Output Format

## [Story Title / Work Item ID]

### User Story
As a [user], I want [goal], so that [benefit].

### Acceptance Criteria

### Scenario 1: [Scenario title]
Verify that [behavior].
Verify that [behavior].

### Flagged Gaps
- ...

### Assumptions & Open Questions
- ...

## Verify Before Using the Output

- Do the acceptance criteria match the approved source material rather than a plausible guess?
- Is anything too vague to test?
- Are cross-team dependencies confirmed with the owning team?
- Is anything present that should not be shared with the meeting audience?
- Has a human made the final call on readiness, commitments, and next steps?
