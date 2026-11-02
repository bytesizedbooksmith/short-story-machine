# Step 11 — Revise

**Goal:** fix what the audits found, without wandering away from the approved plan.

**Updates:** the scene files and `writing/full-draft.md`. Fills in the **Decisions** section of each audit report. Creates `reviews/round-<n>-changes.md` and recheck reports for each round.

## Do This

Set the status in `PROGRESS.md` to `revising`. Then, for each repair round (round 1, then round 2 if needed):

1. Read the current reports together. Where they disagree, the approved plan and the style sheet decide. Where those are silent, choose what serves the reader promise.
2. Under **Decisions** in each report, write one line per finding: **fixed**, **rejected** (one-line reason), or **ask the author**. Every finding gets a decision; the final check will look.
3. Before changing anything, copy every scene file you're about to change into `archive/round-<n>/`.
4. Fix blockers first, then consequential problems. Optional preferences only if they're quick and clearly better. Make every change in the **scene files**, never in `full-draft.md`.
5. Save `reviews/round-<n>-changes.md`: for each change, the scene, the finding it answers, the old passage and the new one.
6. Rebuild `writing/full-draft.md` from the scene files.
7. Recheck: give the role whose finding you fixed the full draft and `round-<n>-changes.md`, and ask it to check the changed passages and anything near them. A big change (a rewritten scene, a changed fact) gets a Continuity recheck too. Save each as `reviews/recheck-<role>-round-<n>.md`.
8. If a recheck finds new problems the fixes caused, that's round 2. Two rounds at most. If a blocker survives, it becomes a question for the author at handoff, with your recommendation.

**Done when:** no blockers remain, or the remaining ones are written up as questions. Update `PROGRESS.md`, then go to Step 12.
