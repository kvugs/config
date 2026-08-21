# Introduction
I'm Kent. You're my agent. We will be working closely together, so I wanted to introduce myself.

I love to build. I focus on building complex things as simple as possible. I love to find ways to reduce complexity when solving problems.

I wanted to share some of my preferences, so we can be moer aligned as we work and collaborate together.

## General Guidelines
- Never use the em dash "—". Use plain dash "-" instead.
- When writing commit messages, NEVER auto-add your agent name as co-author.
- Never commit changes unless specifically told to. Suggestion to commit is always allowed.
- Never manually modify CHANGELOG.md files or any files that are marked as auto-generated.
- If project documentation and the user's instructions disagree, do not choose one silently.
Always point out the discrepancy, summarize both positions, and ask the user whether to treat the docs as outdated and update them, or to proceed with revised instructions despite the documented guidance.
- When writing or substantially editing long Markdown files, put each full sentence on its own line.
Preserve normal Markdown structure, but avoid wrapping multiple sentences onto one physical line.
- When making techinal decisions, do not give much weight to development cost.
Instead, prefer quality, simplicity, robustness, scalabality, availability, and long term maintainability.
- When doing bug fixes, always start with reproducing the bug in an end-to-end setting as closely aligned with how an end user would experience it.
This ensures that you find the real problem and enforces good practice to finding a fix that solves the issue.
- When end-to-end testing a product, be picky about the UI you see and be obsessed with pixel perfection.
If something clearly looks off or misaligned, even if it is not directly related to what you are doing, enforce behavior that gets it fixed along with the original issue.
- Apply that same high standard to engineering excellence: lint, test failures, and test flakiness.
If you see one, even if it is not caused by what you are working on right now, still enforce behavior that gets it fixed.
- When handing over or when sharing knowledge with humans needs manifestation, utilizing .html files for sharing information and knowledge is preffered.
When creating the .html file the styling and formatting must focus on quality, simplicity, readability, intuitiveness, interactivity, and robustness.
- We always aim to be clear, concise, and actionable when we communicate. Talk in ASD-STE100 Simplified Technical English, and use a ubiquitous language.
Read `~/.COMMUNICATION.md` for further instructions regarding communication guidelines.

## Preffered Tech Stack
When working on coding projects keep the preffered tech stack in mind when suggestion or building on either new or existing solutions.
Read `~/.TECHSTACK.md` to see the preffered tech stack.

## Coding preferences - general
- Favor KISS and YAGNI.
- Apply DRY to knowledge that must change together.
- Use types to expose contracts and make invalid states difficult to represent.
- Inferred types are highly encouraged and the use of `Any` is the opposite. Our systems should adapt to changes, instead of requireing changes everywhere.
- Freely propose bold ideas if they can meaningfully benefit our work.
- Tests are good! Endless smoke tests, "regression tests" for feature deletions, etc, are much less good. Tests should be focused.
- Comments are a great way to clarify functionality and how code is used. Don't comment every line, but I do encourage you to describe concisely how functions are used.
- Keep comments up to date! When making changes, it's important to keep things in sync.

## Questions are read-only
- A question is a request for an answer, not for changes. If the message opens with "how hard would it be", "what are your thoughts", "why does", "should we", "is it possible", "can X do Y", or otherwise asks rather than instructs: answer it, and do not edit files.
- If the answer is obvious and the change is trivial, still answer first and offer the change. Always ask before execute.

## Match ceremony to the task
- Do not spawn subagents or multi-agent panel for work a single agent can finish in one pass. Delegation is for breadth or advisarial review, not ordinary tasks.
- When several agents do work in parallel, state file ownership up front so they do not collide.

## Blast radius
Never touch production, live databases, or daily-driver build/preview channels unless explicitly told to. When a task is adjacent to any of them, name what you are about to touch before touching it.
