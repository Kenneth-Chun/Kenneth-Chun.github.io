---
layout: essay
type: essay
title: "Value of Coding Standards and Linting"
# All dates must be YYYY-MM-DD format!
date: 2026-09-24
published: true
labels:
  - Coding Standards
  - Lint
---

<img width="300px" class="rounded float-start pe-4" src="../img/project/lint.png">

Coding standards are often dismissed as simple formatting rules about indentation and brace placement. In reality, they are a foundational part of software engineering and a key way to ensure code quality. This essay explores the role of coding standards and looks at what happens when automated linting tools become part of a daily workflow.

At their core, coding standards enforce consistent patterns and help prevent fragile code. For example, in TypeScript, banning the any type and enforcing strict null checks force developers to explicitly define their data structures. This removes guesswork and pushes teams toward safer, more deliberate design choices.

I saw the practical impact of these standards during my first week using ESLint in Visual Studio Code, specifically through the E24 and E25 exercises. At first, the experience was frustrating. The editor constantly flagged issues like missing trailing commas, mixed quotation marks, unused variables, and broken comment formatting. These warnings disrupted my focus and forced me into constant context-switching between fixing formatting and actually writing code.

However, once those initial errors were cleared, my workflow shifted. Letting the linter handle formatting allowed me to spend my time focusing on code logic. Fixing linting errors stopped feeling like a chore and became a normal part of the development process.

This consistency is especially important when working on a team that uses version control like Git. When everyone follows the same style guide, such as the ZE JavaScript/TypeScript Style Guide, it is much easier to read and understand code written by others. This makes bringing new developers up to speed faster and keeps code reviews focused on the actual logic and design. 

Coding standards cannot be learned just by reading about them ; they require practice. Working through the Workouts of the Day (WODs) in E26 and E27 gave me the practice needed to apply these rules until following them became second nature.

Ultimately, using strict coding standards and a linter does more than just clean up code; it improves developer efficiency. Introducing a tool like ESLint causes some initial annoyance, but it pays off by streamlining the whole process. Once the linter handles formatting and enforces good patterns, developers are free to focus on solving real problems. The end result is software that is easier to read and maintain.

AI used to support writing.
Used to correct grammar.
Used to improve sentence structure.