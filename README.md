# Accessible Learning

An AI plugin for designing and reviewing adult-facing learning materials through the lenses of accessibility, Universal Design for Learning (UDL), inclusive design, and adult-learning quality. It works in Codex and Claude Code.

**Status:** early pilot. Feedback is welcome.

## What it supports

- PowerPoint and Google Slides decks
- Documents, PDFs, and facilitator guides
- E-learning modules, workshops, and course outlines
- Design guidance from the start, or prioritized review feedback on existing material

Reviews list strengths first, then findings ranked **Critical**, **Important**, or **Enhancement**, each with the evidence, the impact on learners, and a specific revision.

The plugin gives practical guidance. It does not issue legal or technical accessibility certification.

## Install

**Codex**

```sh
codex plugin marketplace add JJfww/accessible-learning
codex plugin add accessible-learning@accessible-learning
```

**Claude Code**

```sh
claude plugin marketplace add JJfww/accessible-learning
claude plugin install accessible-learning@accessible-learning
```

Or, inside a Claude Code session: `/plugin install accessible-learning --marketplace JJfww/accessible-learning`

## Try it

> Use Accessible Learning to review this slide deck for accessibility, UDL, and adult-learning design. Prioritize the five most important improvements.

> Use Accessible Learning to help me design an accessible 45-minute staff training on de-escalation.

## Pilot feedback

[Share feedback](https://github.com/JJfww/accessible-learning/issues/new?template=pilot-feedback.yml): what you reviewed, what feedback was useful or missing, and any recommendation that felt impractical in your setting. Do not include confidential learner or organizational information.

## Foundations

- WCAG 2.2 for practical digital-accessibility guidance
- CAST UDL Guidelines 3.0
- Adult-learning, inclusive-design, and cognitive-load principles

## Author and license

Created by Jennifer Burnes, PhD. Licensed under [CC BY-NC 4.0](LICENSE): you may share and adapt it for non-commercial purposes with credit.
