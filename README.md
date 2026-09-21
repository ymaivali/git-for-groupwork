# Git for group work

A tutorial for students organising group projects around git and GitHub, from
R and RStudio, with Claude Code doing the git commands.

**Read it here: <https://ymaivali.github.io/git-for-groupwork/>**

Built as a Quarto website. To read it locally:

```bash
quarto preview
```

To republish after editing:

```bash
quarto publish gh-pages
```

## Design principle

**Teach the pictures, delegate the syntax.** Students are not asked to
memorise git commands — an AI types those faster and writes better commit
messages. They are asked to hold four ideas, because when a merge conflict
appears, the AI can fix the mechanics but only the group knows which version
is correct.

The bar: a student must be able to draw the four-places diagram from memory
and explain what a merge conflict is. Everything else is delegable.

## Contents

| Page | For |
|------|-----|
| `00-setup.qmd` | One-time setup — homework, before the session |
| `01-concepts.qmd` | The four ideas, plus a no-computer check |
| `02-solo.qmd` | RStudio Project → git repo → GitHub |
| `03-collaborate.qmd` | Clone, branch, pull request, and a conflict on a shared branch |
| `03b-pr-conflict.qmd` | The conflict that appears on the pull request instead |
| `04-troubleshooting.qmd` | Five real errors, and a prompt cheat-sheet |
| `05-rules.qmd` | Group rules of the road |
| `99-instructor.qmd` | Timing, exercise scripts, assessment — **not for students** |

## Worked example

The project students build, with its full history, merged pull request and a
real resolved merge conflict:
[github.com/ymaivali/penguin-clinic](https://github.com/ymaivali/penguin-clinic).

All its data are simulated.

## Provenance

Every command and every output shown in the handout was executed on macOS with
git 2.39.3, gh 2.90.0, R 4.6.0 and Quarto 1.4.554. The Windows and Linux
install instructions in Part 0 are **untested** — verify them on a student
machine before first use.

## Licence

No licence chosen yet. Add one before reusing this outside the course.
