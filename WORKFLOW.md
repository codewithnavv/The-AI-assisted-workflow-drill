# Workflow

This repository is used to practice AI-assisted development across separate
Git branches. Keep each exercise isolated so its changes can be reviewed and
compared independently.

## Starting an exercise

1. Start from the agreed base branch, usually `main`.
2. Create and switch to a branch named for the exercise before editing.
3. Check `git status` and preserve any existing uncommitted work. Do not discard
   or move another exercise's changes without permission.
4. Read the relevant project files and instructions before making changes.

## Implementing a change

1. Clarify requirements that materially affect the design or behavior.
2. Make the smallest complete change that meets the request and follows the
   existing project conventions.
3. Update directly related documentation and tests when appropriate.
4. Run the relevant tests, checks, or build. Report checks that could not be
   run instead of implying they passed.

## Reviewing and sharing

1. Review `git diff` and `git diff --check`; confirm only intended files are
   changed.
2. Stage only the files for the current exercise.
3. Commit with a message that describes the change.
4. Push the exercise branch and set its upstream when needed.
5. Compare exercise branches with `git diff <base>...<branch>` and
   `git diff --stat <base>...<branch>`.

Do not force-push, rewrite shared history, or include secrets in commits.
