---
title: "The Waterfall Model"
teaching: 0
exercises: 0
questions:
- "Key question (FIXME)"
objectives:
- "First learning objective. (FIXME)"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---

## Software Development Process

Below are (most) of the different phases of the software development process. 
These phases can be mixed, or (sometimes) reordered.
This can happen for a variety of reasons.
The line between requirements and design are often blurry.
Implementation, testing and user docs often proceed concurrently.
Sometimes, tests are written first in what is called Test Driven Development (TDD).
Another thing to note is that the definition of roles vary.
For example, the “customer” or “user” may also be the author of the software, or may be quite removed.

1. Determine software requirements
2. Software design 
3. Implementation
4. Software testing
5. Software documentation
6. Release/deploy the software to the customer 
7. Ongoing maintenance

## The Waterfall Model

The idea of having defined phases is to try to complete each phase before the next phase begins.
This is generally referred to as the waterfall model, ala "Progress flows downwards through the phases, like a waterfall."
Each phase produces specific deliverables, which feed into the next phase with the assumption that the artifacts from the previous phases are actually correct.

Ideally, each phase will also identify any issues or flaws in the previous phase.
When this happens, you are supposed to iterate between phases to fix any issues that arise.

## The Waterfall Model in Real Life
It is very common in real life scenarios that there is a miscommunication of software requirements.
These miscommunications may not even be identified until the software is demonstrated for clients or formal acceptance testing is completed.
In traditional waterfall models, the client is often only involved in requirements phase, and in acceptance-testing or later phases.

If mistakes occur using the Waterfall model, very significant amounts of work may need to be reviewed, revised, or even discarded.
>It’s 50x to 200x less expensive to get a requirement right in the first place than to fix a requirement after implementation
>
> -Boehm and Papaccio, 1988

The Waterfall model works well when:
- Software requirements are very clear, well understood, and unchanging
- Technical implementation details are also very well understood (Generally considered more suited to manufacturing, but this is also changing with rapid prototyping!)

Inversely, waterfall model works terribly when these things aren’t present, and can lead to greatly exceeding time and financial budgets.
Waterfall-based models don’t handle lack of knowledge, or change, very effectively.
Poorly understood or changing software requirements, technology, or architecture choices can negatively impact the performance of the Waterfall-model.
Though, it should be noted that a lack of software-engineering discipline kills virtually all approaches.

Agile methodologies were suggested as a better alternative to Waterfall-based methods, and are discussed in the next section.

{% include links.md %}

