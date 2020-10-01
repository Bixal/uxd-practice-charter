---
title: Activities & Outputs
layout: section
slug: activities-and-outputs
subtitle: How do we do what we do? And what are the outputs of those activities?
color: maroon
# options: light-green, maroon, purple
---

### Agile mindset and levels of confidence

With an agile mindset, the way we conduct our practice is less about following a prescribed set of steps than **_working iteratively from a point of more abstraction to a point of more tangibility_**.  

{% include image-tangibility-over-time.html %}

As our understanding becomes less abstract and more tangible, **_our level of confidence increases_**.  

In the discovery and research iterations, this means talking to clients to better understand the goals of the project and talking to the people we’re designing for to better understand their needs.  

In the design and development iterations, this means prototyping our hypotheses and validating our assumptions.  

{% include image-confidence-over-time.html %}

As we learn more about the people we’re working with and designing for, our level of confidence about what to do increases. And as we prototype solutions and test them, our level of confidence about whether we’re on the right track increases further.

### The Playbook

The framework we use to communicate and validate this approach is the [Digital Services Playbook](https://playbook.cio.gov/) from the U.S. Digital Service. The first three plays constitute a **“definition of done”** for major components of a project.  

1. [Understand what people need](https://playbook.cio.gov/#play1)
2. [Address the whole experience, from start to finish](https://playbook.cio.gov/#play2)
3. [Make it simple and intuitive](https://playbook.cio.gov/#play3)  

Do we know who the primary users are? Have we articulated what needs the service will address? If yes, we can proceed with a higher level of confidence. If no, we should do another round of research activities to answer those questions.  

Are we using language that is familiar to the primary audience? Are we using language and design consistently throughout the service? If yes, we can proceed with a higher level of confidence. If no, we should do another round of design exploration and test again.

Sometimes these questions may already have answers. Not all projects start at the same point or run for the same length of time. And sometimes we're not the only team working on a project. By approaching a project with questions to answer instead of steps to check off, we can adapt to different situations.

### The Methods  

We have a collection of activities and tools we call the [Bixal Methods](https://bixal.github.io/methods/) that we’ve begun adapting from the original 18F version. Depending on what questions we have at a given point within a project, we choose an appropriate set of methods to conduct within an iteration of research or design.  

{% include image-research-plan.html %}

Instead of mapping the methods to specific “phases” of a project, they’re organized by the “goal” at a particular point in the project in terms of the questions you're trying to answer.

-  **Awareness**: what is this project all about?
-  **Observation**: what are people doing today?
-  **Interpretation**: what did we learn from talking to and observing people?
-  **Exploration**: what might we do based on what we learned?
-  **Validation**: are we comfortable moving forward?  

Each method includes a description of what the activity is, why to use it, and how to conduct it. **This approach gives us a consistent, scalable framework for collaborating on and defining our key activities and deliverables over time as our practice grows and evolves.**

### Mapping to an agile project framework

While the Playbook and Methods provide guidance on what to do on a project and when, they don't describe exactly how to organize and track that work within an agile project. Here's how we're currently thinking about it:

-  **Plays as epics** (e.g., Understand what people need): these describe the higher level goal of a major piece of a project, particularly in the earlier phases before we've decided what to build.
-  **Method "whys" as user stories** (e.g., Gain insights from users about how to organize content in an intuitive way): instead of a task that simply says "card sorting," this describes the need in terms of value to the customer.
-  **Method "hows" as sub-tasks** (e.g., Set up the study, Recruit users, Summarize results): these are the atomic steps of the activity that can be tracked to better plan and update progress throughout a sprint cycle.

This approach helps avoid practice jargon and makes it more clear to all stakeholders (project team, practice leads, clients) what we're actually doing and what to expect in terms of timing and output.

Here's an example of how this might be structured in a Jira project:

{% include image-organizing-work.html %}
