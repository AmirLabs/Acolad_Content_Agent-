# Project Agent Instructions

These instructions apply to work in this repository.

## Git

- Git belongs to the user. Never run a Git command that changes repository state, including add, commit, branch, checkout, merge, rebase, push, pull, stash, tag, reset, or config edits. Never ask permission to run one; the user decides and runs it. Read-only inspection such as `git status`, `git log`, and `git diff` is allowed when needed.
- Do all work on `develop`. Before the first edit of a session, check the current branch. Never write files while on `main` or `release`; stop and ask the user to switch to `develop`.

## Commit Messages

- The user writes and runs every commit. Draft commit messages and advise how to group changes; never run Git commands.
- Do not add attribution trailers such as `Co-Authored-By` or `Generated with`, or any other line crediting a tool or model.
- A commit message must have two to nine lines, excluding the blank line after its subject. Use an imperative subject under about 60 characters, matching prefixes already used in repository history. The body explains why the change was made and what it affects; do not restate what the diff shows.
- Default to one file per commit. Combine two files only when one is unusable without the other; never combine more than two. Propose the split in landing order and leave the decision to the user.
- Present every drafted message with the path of the file it belongs to.

## User-Facing Writing

- Start every line written for the user with a Persian word, especially the first line of each paragraph. Do not begin a response or paragraph with an English word, because it can disrupt right-to-left formatting. This applies to chat messages, Markdown, commit-message drafts, reports, list items, table cells, and other user-facing text, but not source code.
- Do not end a sentence with a Latin word. Put commands, paths, code, and identifiers in fenced code blocks rather than inline at the beginning of a line.

## Required project tools

- **Superpowers:** Use the relevant `superpowers` skill workflow for project work. At the start of each task, inspect the available skills and invoke the applicable process skill before acting. For new features or behavior changes, use brainstorming first; for bugs, use systematic debugging; for implementation, follow the applicable planning, TDD, and verification skills. Do not force an irrelevant workflow onto a simple read-only request.


These are project-level usage requirements, not plugin installation settings. Use the connected Superpowers and Context7 tools available in the Codex session.
