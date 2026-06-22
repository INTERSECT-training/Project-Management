---
title: "Introduction"
teaching: 5
exercises: 5
---

::::::::::::::::::::::::::::::::::::::: objectives

- Understand the definition of Project Management.
- Understand the phases of the software development process.

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- What is project management?
- When should project management be used?
- What are the general phases of software development?

::::::::::::::::::::::::::::::::::::::::::::::::::

## Project Management Introduction

What is project management?

The [Project Management Institute](https://www.pmi.org/about/learn-about-pmi/what-is-project-management) defines project management as:

> The use of specific knowledge, skills, tools and techniques to deliver something of value to people.
> The development of software for an improved business process, the construction of a building, the relief effort after a natural disaster, the expansion of sales into a new geographic market—these are all examples of projects.

## Who needs Project Management?

If a group of people are working together, some amount of project management
methodology will help.
How large, long, and complex the project is will determine how much project management
discipline will be helpful.
Generally, the more time and/or people involved, the more project management helps.
If you are writing scripts for your own research to test out some ideas, and the
project will extend some time, you (and "future you") will probably benefit from project management.
If you are experimenting with something for just one week, you probably don't
need project management.

_But are you sure it's really just "one week"?_

::::::::::::::::::::::::::::::::::::::::::  callout

## Project management for research software

Research software has its own flavor of these questions. The "customer" might be your
PI, your grant's aims, a collaborating lab, or simply **"future you"** trying to
reproduce a result. "Release" might mean tagging a version for a paper, and
"maintenance" might mean keeping code runnable long after the student who wrote it
has graduated. Even a one-person project benefits from a little structure once it
needs to outlive a single deadline.

::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge 

## When do you need it?

Brainstorm with the people near you for a few minutes.
What are some examples of situations in which project management might be useful for you in your daily life?
What are some situations in which it might not be necessary?

::::::::::::::::::::::::::::::::::::::::::::::::

## Software Development Process

Below are (most) of the different phases of the software development process.

| # | Phase | What happens | Typical output |
|---|-------|--------------|----------------|
| 1 | Requirements | Figure out what the software needs to do | A list of needs / user stories |
| 2 | Design | Decide how it will be built | Architecture, interfaces, plans |
| 3 | Implementation | Write the code | Working code |
| 4 | Testing | Confirm it does what it should | Tests, bug reports |
| 5 | Documentation | Explain how to use and maintain it | User and developer docs |
| 6 | Release / Deploy | Get it to the people who use it | A usable version |
| 7 | Maintenance | Keep it working and fix issues over time | Patches, updates |

These phases can be mixed or (sometimes) reordered.
This can happen for a variety of reasons.
The line between requirements and design are often blurry.
Implementation, testing, and user docs often proceed concurrently.
Sometimes, tests are written first in what is called Test Driven Development (TDD).
Another thing to note is that the definition of roles vary.
For example, the "customer" or "user" may also be the author of the software, or may be quite removed.

There are many different methodologies to help organize the software development process.
In the rest of this lesson we will work through them in order:

1. **The Waterfall model** — phases done sequentially
2. **The Agile methodology** — iterative and responsive to change
3. **Agile frameworks** — Scrum, Kanban, and MoSCoW in practice
4. **Choosing a methodology** — how to decide which fits your project
5. **GenAI in project management** — where LLMs help, and where they don't


:::::::::::::::::::::::::::::::::::::::: keypoints

- Project management focuses on creating something of value in a systematic way.
- The larger or longer a project or task, the more that project management will help.
- Software development generally starts at requirements and ends at maintenance.

::::::::::::::::::::::::::::::::::::::::::::::::::
