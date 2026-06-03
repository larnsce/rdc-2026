---
title: "Git for Scientists: a 120-minute hands-on workshop, taught from the learner's seat and pitched to educators"
subtitle: "RDC 2026 workshop submission - Swiss Research Data Support Network"
title-block-banner: true
date: today
author:
  - name: Lars Schöbitz
    orcid: 0000-0003-1271-7044
    email: lars.schoebitz@ethz.ch
    affiliations:
      - name: ETH Zürich
        address: Clausiusstrasse 37
        city: Zürich
        postal-code: 8092
        url: https://ghe.ethz.ch/
    attributes:
      corresponding: true
format:
  html:
    toc: true
    toc-depth: 2
    number-sections: false
    embed-resources: true
    theme: cosmo
  docx:
    toc: false
    number-sections: false
---

## Submission metadata

- **Conference:** Research Data Conference (RDC) 2026, Swiss Research Data Support Network (SRDSN)
- **Format:** Workshop (120 min)
- **Presenter:** Lars Schöbitz (sole presenter)

## Abstract

Git and GitHub remain the connective tissue of reproducible, collaborative research, yet many researchers learn them through fragmented tutorials that stop short of the collaboration patterns that matter in practice: branching, pull requests, code review, and merging. *Git for Scientists* is a 120-minute hands-on workshop offering an applied, project-based introduction for learners who have worked with software before but have not had a solid, applied introduction to Git and GitHub.

The workshop is delivered as if every participant were a learner, but the real audience is educators: data stewards, research software engineers, data science instructors, and others who teach (or want to teach) similar material. Attendees first experience a condensed version of the full course from the learner's seat, then switch to an educator lens for a substantial closing block to evaluate whether they could teach the workshop in their own context. The session is both a learning experience and a peer review of the design. A positive evaluation would motivate a follow-up "teach-the-teachers" workshop on reusing this Open Educational Resource (OER).

*Git for Scientists* is our group's first resource published as a complete OER, with a three-organisation GitHub layout (canonical, development, per-iteration delivery) and a FAIR audit applied to every teaching repository. Pre-workshop instructions cover a local Git and RStudio install, which deliberately differs from the Posit Cloud environment we use for complete novices and is itself a design decision worth scrutinising.

## Learning objectives

By the end of the workshop, participants will be able to:

1. Apply core Git and GitHub collaboration patterns (branching, pull requests, code review, merging) to a small project.
2. Evaluate the workshop's instructional design (sequencing, scaffolding, exercises) from an educator's perspective.
3. Assess whether they could reuse and adapt the workshop materials to teach Git and GitHub in their own setting.

## Agenda (120 min)

- 0:00–0:10 — Welcome and dual framing (learner seat / educator lens).
- 0:10–1:25 — Condensed *Git for Scientists* course: create and clone, branching, pull requests and review, merging, publishing.
- 1:25–1:30 — Break.
- 1:30–2:00 — Educator-lens walk-through of the OER infrastructure and structured feedback round.

## Prerequisites

Participants are expected to be comfortable with R and RStudio, specifically:

- Installing and loading R packages
- Reading and running short R scripts
- Editing and running R Markdown or Quarto documents
- Navigating the RStudio IDE and identifying its four panes (Script, Environment, Files, Console)

A GitHub account and a working local install of Git, R, and RStudio (set up via the pre-workshop instructions) are required. Participants without these will still benefit from the educator-lens portion but will not be able to follow the hands-on exercises.

Prior experience with Git and GitHub is an advantage but not required. Participants new to Git and GitHub can use the workshop to build a foundation they can later draw on when teaching the material themselves.

## Target audience

Educators and educator-adjacent practitioners in data stewardship, research software engineering, data science, and related fields who teach (or plan to teach) applied Git and GitHub. Secondary audience: data stewards and research support staff who run training programmes and are evaluating OER for adoption.

## Keywords

Git and GitHub, Open Educational Resources, instructional design, collaboration, project-based learning

## Optional links

- Workshop website (current iteration): <https://gitforsci-cis.github.io/website/>
- Workshop source repository: <https://github.com/gitforsci-cis/website>