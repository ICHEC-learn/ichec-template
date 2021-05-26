---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
---

<p align="center"><img src="../fig/ICHEC_Logo.jpg" width="40%"/></p>

{% include gh_variables.html %}

For guidelines on how to develop curriculum content, please visit
[The Carpentries Curriculum Development Handbook][curriculum-handbook].

This setup has been adapted from the Carpentries [lesson example](https://carpentries.github.io/lesson-example/)
for use at ICHEC. You should be familiar with using both GitHub and Markdown tools. You can refer to the Carpentries 
supplied [Technological introductions][tech-intro] section of The Carpentries Curriculum Development Handbook.

> ## Prerequisites
>
> Use the `.prereq` style to specify prerequisites.
> 
> For setting up lessons in the Carpentries style with ICHEC, it is recommended that you have knowledge of 
> GitHub and Markdown. Feel free to refer to the Carpentries 
> [lesson template](https://carpentries.github.io/lesson-example/).
>
{: .prereq}

> ## For ICHEC users
>
> 0.  Refer to README.md for instructions on setting up a new lesson or editing an existing one.
> 1.  Create a new lesson by using GitHub Import, *not* by forking.
> 2.  Put lesson episodes in `_episodes` (or `_episodes_rmd` if you are writing in RMarkdown).
> 3.  Each episode should have a set of related concepts, and contain a set of challenges to practice these concepts
> 4.  There are many styles of challenges you can create for your episodes, as a rough guide however, start with
>     [Designing challenges][designing-challenges].
> 5.  Style blocks and code samples by putting `{: .stylename}` on a newline *after* the block or
      code.
> 6.  Put solutions inside challenges using nested blockquotes.
> 7.  This template repo is set to **Private**, and upon creating a new repo and github.io, this will by default
>     be generated, so make sure that the existing content is deleted and modified accordingly.
> 8.  Your main editing will take place in `_episodes`, `fig`, `_includes`, and `data`/`files` directories. 
> 9.  Ensure the page builds! This can be done by cheking the tests on your own forked repo, otherwise the page will not build.
{: .checklist}

[curriculum-handbook]: https://carpentries.github.io/curriculum-development/
[tech-intro]: https://carpentries.github.io/curriculum-development/technological-introductions.html
[designing-challenges]: https://carpentries.github.io/curriculum-development/designing-challenges.html#designing-challenges-1

{% include links.md %}

