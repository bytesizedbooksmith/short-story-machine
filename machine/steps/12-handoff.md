# Step 12 — ✋ Final Check And Handoff

**Goal:** one last independent check, then hand the author a clean draft and a short note. After this, the story is theirs.

**Creates:** `reviews/final-challenge.md`, `FINALS/<story-name>-v1.md` and `FINALS/handoff-note.md`. (`<story-name>` is the story's folder name, for example `the-haunted-bakery-v1.md`. No spaces or special characters, so it works in every tool.)

## Do This

1. Run the **Challenger** with the **Final** lens. Give it `writing/full-draft.md`, the plan, the style sheet, the three audit reports with their decisions, and the round change files and recheck reports.
2. Fix supported findings (two rounds at most) the same way as Step 11: archive first, change the scene files, rebuild `full-draft.md`.
3. Copy the final text into `FINALS/<story-name>-v1.md`: the title, the byline (pen name), then the scenes with a blank line and `* * *` between them. No notes, labels or comments inside the story. Separate drafters can punctuate differently, so make the mechanics match across scenes: one style of quotation marks and apostrophes, one style of dash. Change punctuation only, not wording.
4. Write `FINALS/handoff-note.md` from [../templates/handoff-note.md](../templates/handoff-note.md): the draft's filename, word count, what was checked (and whether by separate agents or self-review), what you fixed, anything left open, and two or three things you'd look at first when editing. Before saving, reread **Still Open** against the final text and drop anything already resolved.
5. Set the status in `PROGRESS.md` to `handed off`.
6. Tell the author, briefly:
   - Where the story and the note are.
   - Any open questions, with your recommendation.
   - That the draft is theirs now: they can edit it themselves, or ask you for help editing in this chat.
   - That they can type `start` any time to begin a new story.

**Done when:** the files are in `FINALS/` and the author has been told.

## If The Author Asks For Edits After Handoff

Help them. Make each requested change, save a new version (`-v2`, `-v3`) in `FINALS/`, and move the older one to `archive/`. If a change affects other scenes (a name, a fact, an event), tell them where else it shows up.

Then update the handoff note, replacing old details rather than adding new sections on top: the **Draft** filename, **Words**, **These checks cover**, and the **Still Open** list (remove anything the edit answered). Note the edit in `PROGRESS.md`.

**Tell the author which checks the new version hasn't had.** After a change that touches more than a few lines, offer one recheck: **Continuity** on the facts, including anything that depended on cut material, and **Style** on repetition only. Say it uses more of their plan. If they say yes, save the reports as `reviews/recheck-continuity-v<n>.md` and `reviews/recheck-repetition-v<n>.md`, then give them the findings. Fix only what they choose.
