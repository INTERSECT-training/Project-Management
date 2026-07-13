---
title: "GenAI in Project Management"
teaching: 5
exercises: 0
---

::::::::::::::::::::::::::::::::::::::: objectives

- Identify practical ways generative AI can support project management tasks.
- Recognize the risks and limitations of using genAI in a project workflow.
- Understand special considerations for using genAI in research software.

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- Where can generative AI genuinely help with project management?
- What are the risks of relying on it?
- What should research software engineers keep in mind?

::::::::::::::::::::::::::::::::::::::::::::::::::

## A New Tool in the Toolbox

Generative AI — large language models (LLMs) like ChatGPT, Claude, and others — has
quickly become part of many developers' daily workflow. These tools are good at
working with *text*, and a surprising amount of project management **is** text:
user stories, backlogs, meeting notes, status updates, documentation.

Used well, genAI can take the friction out of the routine writing-and-organizing
parts of project management, freeing you to spend time on the parts that need human
judgement. Used carelessly, it can introduce confident-sounding mistakes and erode
the very communication that good project management depends on.

## Where It Helps

| Task | How genAI can help |
|------|--------------------|
| **Drafting user stories** | Turn a rough feature idea into well-formed "As a..., I want to..., so that..." stories |
| **Breaking down epics** | Suggest how to decompose a large feature into sprint-sized tasks |
| **Backlog generation** | Brainstorm candidate features or edge cases you might have missed |
| **Estimation support** | Surface considerations that affect complexity (a starting point, not the answer) |
| **Summarizing** | Condense standup notes, long issue threads, or a sprint's activity |
| **Retrospectives** | Cluster feedback into themes and suggest action items |
| **Documentation** | Draft READMEs, docstrings, changelogs, and "how to contribute" guides |
| **Communication** | Rephrase a technical update for a non-technical stakeholder |

The common thread: genAI is best as a **fast first draft** and a **brainstorming
partner**, as long as you then review, correct, and own.

## Where to Be Careful

::::::::::::::::::::::::::::::::::::::::::  callout

## Keep a human in the loop

- **Hallucination.** LLMs can produce plausible, fluent, and *wrong* output —
  invented requirements, mis-estimated tasks, fabricated references. Always verify.
- **False confidence.** The polished tone makes errors easy to miss. Treat output as
  a draft from an eager junior colleague, not an authority.
- **Eroding communication.** Agile values *individuals and interactions*. If an
  AI-summarized standup replaces the team actually talking, you've optimized away the
  point of the meeting.
- **Data, privacy, and IP.** Anything you paste into a third-party tool may leave your
  control. Don't share confidential, sensitive, or proprietary information without
  knowing the tool's data policy.
- **Accountability stays human.** The AI doesn't own the deadline, the bug, or the
  stakeholder relationship — you do.

::::::::::::::::::::::::::::::::::::::::::::::::::::::

## For Research Software Specifically

::::::::::::::::::::::::::::::::::::::::::  callout

## Research considerations

- **Reproducibility and provenance.** If genAI shaped your plan, design, or docs, keep
  a record of how. Reproducibility is a core value of research software.
- **Disclosure.** Many journals, funders, and institutions now have policies on
  disclosing AI use. Check them before you rely on AI-generated content in outputs.
- **Sensitive and unpublished data.** Unpublished results, participant data, and
  embargoed work generally should **not** go into external AI tools.
- **Grant and reporting language.** GenAI can help draft progress reports and broader-
  impacts text — but you remain responsible for accuracy and for meeting the funder's
  expectations.

::::::::::::::::::::::::::::::::::::::::::::::::::::::

## The Bottom Line

GenAI is a genuinely useful project-management assistant for the routine, text-heavy
work — drafting, summarizing, brainstorming, reorganizing. It is **not** a substitute
for the human judgement, communication, and accountability that make a project
succeed. The teams that benefit most are the ones who already understand good project
management, and use AI to do it faster — not to avoid doing it at all.

:::::::::::::::::::::::::::::::::::::::: keypoints

- GenAI excels at the text-heavy parts of project management: drafting stories, summarizing, and brainstorming.
- Always verify AI output — hallucination and false confidence are real risks, and accountability stays with you.
- For research software, mind reproducibility, disclosure policies, and never share sensitive or unpublished data with external tools.
- GenAI augments good project management; it doesn't replace human judgement.

::::::::::::::::::::::::::::::::::::::::::::::::::
