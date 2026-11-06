# W02 · Git practice

Practice repository for TA session 2 of *AI Fluency and Agentic Methods for Engineers*
(00560413, Technion, Winter 2026–27).

It has three branches. They start from the same first commit, then each goes its own way:

- `main`: the finished version. Its own file is `main.md`.
- `develop`: where new work happens first. Its own file is `develop.md`.
- `feature`: a third line of work, started from `develop`. It changes the last line of `develop.md` in a different
  way from `develop`, so merging both into `main` gives a merge conflict on purpose.

In VS Code's Source Control Graph you see them as separate lines.

## What you do with it

1. **Fork** it. On the fork page, untick **Copy the `main` branch only**, so your copy gets all three branches.
2. **Clone** your fork in VS Code.
3. **Switch** to `develop`, add `about-me.md`, commit, and push.
4. **Merge** `develop` into `main` in VS Code, and push `main`.
5. **Merge** `feature` into `main` too: both branches changed the same line, so you resolve a conflict, then push.

This is a practice repository. Your project (M1) lives in its own repository.
