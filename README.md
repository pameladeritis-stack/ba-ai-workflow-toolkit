# ba-ai-workflow-toolkit
# BA AI Workflow Toolkit

A reusable AI-assisted workflow for Business Analysts to prepare user stories for grooming, with built-in guardrails for human review.

## Why I Built This

I built this toolkit while looking for practical ways to incorporate AI into my day-to-day work as a Business Analyst.

The goal wasn't to ask AI to *write my requirements for me.*

The goal was to improve the workflow around preparing them.

Weekly story grooming works best when the team can spend its time discussing implementation approach, technical risks, dependencies, and next steps rather than discovering basic gaps in the story during the meeting.

So I created an AI skill to help with the preparation work.

## What the Skill Does

The **Weekly Story Grooming Prep** skill works with the source material a BA already uses, such as ticket content and visual comps, and helps:

* Draft a concise user story from the end user's perspective
* Cross-reference tickets and visual comps when drafting acceptance criteria
* Identify gaps or inconsistencies between source materials
* Surface dependencies that need confirmation
* Separate assumptions and open questions from established requirements
* Produce a consistent, meeting-ready draft for human review

The output is intentionally a **draft**, not a finished requirement.

The BA remains responsible for validating what is true, resolving ambiguity with stakeholders and technical teams, and deciding what is ready to move forward.

## The Workflow

The skill follows six basic steps:

**1. Intake**
Confirm that the necessary ticket information and visual/design reference are available.

**2. Write the User Story**
Translate the underlying problem into a concise user-centered statement.

**3. Draft Acceptance Criteria**
Read the ticket and visual comp together to create specific, testable criteria while identifying mismatches between the two.

**4. Gap Check**
Look for missing requirements, dependencies, unclear behavior, and unresolved questions.

**5. Consolidate**
Bring the story, acceptance criteria, gaps, assumptions, and questions into one consistent review package.

**6. Feed Forward**
After grooming, carry unresolved questions and gaps into the next preparation cycle rather than assuming they were resolved simply because they were discussed.

## The Risk Checklist

I also created a **Reusable AI Workflow Risk Checklist** to accompany the skill.

It addresses questions such as:

* Is this information appropriate to process in the AI environment being used?
* Does the output trace back to actual source material?
* Is AI presenting an inference as though it were a fact?
* Are assumptions and open questions clearly identified?
* Have cross-team dependencies actually been confirmed?
* Which decisions should remain exclusively with humans?

The checklist isn't specific to user story grooming. It can be adapted to other AI-assisted business workflows.

## Download the Toolkit

📘 [Download the complete BA AI Workflow Toolkit (PDF)](BA_AI_Workflow_Toolkit.pdf)

🤖 [Weekly Story Grooming Prep Skill](weekly-story-grooming-prep-public.md)

🛡️ [Reusable AI Workflow Risk Checklist](reusable-ai-workflow-risk-checklist.md)


## Using It With Your Team

This skill was built around one real-world BA workflow. **Don't assume my workflow should be your workflow.**

Before using it:

1. Adapt the terminology, inputs, outputs, and user perspective to your team's process.
2. Define what "meeting ready" means for your organization.
3. Identify the failure modes you specifically want AI to watch for.
4. Decide which decisions AI may assist with and which must remain human.
5. Confirm that your organization permits the AI tool and the data you intend to provide to it.

Then test it on a small number of stories and refine the instructions based on what you learn.

## A Principle Behind the Toolkit

For each step in an AI-assisted workflow, I find it useful to ask:

> **What is AI allowed to infer? What must it flag instead? What source should the output trace back to? And where does a human make the final call?**

That's ultimately what this project is about.

Not replacing the Business Analyst.

Designing a better workflow around one.

**Build the workflow. Keep the judgment.**

## About

Created by **Pamela DeRitis**, Senior Business Analyst and communication strategist.

I'm interested in the intersection of business analysis, AI-enabled workflows, human judgment, and the way people communicate complex ideas.

If you adapt the toolkit for your own BA workflow, I'd love to hear what you change and what you learn.

## Use & Adapt

This toolkit is free to download, use, and adapt to your own workflow.

If you improve it or take it in an interesting new direction, I'd love to hear what you did.

Please make sure your use complies with your organization's policies regarding AI, confidential information, personal data, and approved tools.
