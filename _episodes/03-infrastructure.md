---
title: "Lesson Infrastructure"
teaching: 60
exercises: 0
start: true
questions:
- "What are the tools required to develop lessons in The Carpentries?"
- "What is the structure of a Carpentries lesson repository?"
objectives:
- "Navigate the directory structure of a lesson repository."
- "Adjust the global configuration of a lesson."
- "Write formatted text with Markdown."
keypoints:
- "The Carpentries lessons use a shared [lesson template](https://github.com/carpentries/styles/) to provide aesthetic and structural consistency across all lessons."
- "Lesson pages are written with Markdown and/or RMarkdown, built with Jekyll, and served via GitHub Pages."
- "The global configuration of a lesson site is set in the `_config.yml` file."
- "Supporting files are stored both in `_extras/` and the root of directory of the repository."
---

> ## Reading List
>
> - [CDH Chapter 8: Technological Introductions][cdh-8].
> - [Section A.2 of CDH Appendix A: The Carpentries Incubator][cdh-a1-a2].
{: .checklist }

> ## Discussion Prompts
>
> - What questions do you have after setting up/trying to set up your lesson repository?
> - What was confusing about the process?
> - What are some of the potential benefits of your lesson being listed
>   on [the Community Developed Lessons page][community-lessons] at this
>   early stage of development?
> - What are some of the potential downsides of this?
> - What topics did you choose to add to your lesson repository?
>   Did you use a strategy to decide what these topics should be?
{: .objectives }

> ## Homework Tasks
>
> - Read the [Working with Learning Objectives section of The Carpentries Instructor Training Curriculum][training-LOs].
> - Read the [Learning Objectives section of Teaching Tech Together][ttt-LOs].
> - Read the [Concept Maps][ttt-maps] and [Seven Plus or Minus Two][ttt-load] sections of Teaching Tech Together.
> - In your Lesson Design Notes, write 2-5 learning objectives for your lesson.
> - Create at least one episode file in your lesson repository and add 2-4 learning objectives in the `objectives` field for that episode.
{: .challenge}

{% include links.md %}
