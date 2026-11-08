# Step 7 — Writing Plan

**Goal:** turn the approved plan into instructions the Drafter can follow, and make sure those instructions don't contradict each other.

**Creates:** `writing/idea.md`, `writing/brief.md` (from [../templates/writing-brief.md](../templates/writing-brief.md)), one packet per scene in `writing/packets/` (from [../templates/scene-packet.md](../templates/scene-packet.md)) and `reviews/conflict-check.md`.

## Do This

1. Copy the plan's **Idea** section, word for word, into `writing/idea.md`. The opening challenger (Step 8) and the Reader (Step 10) get this file instead of the plan, so they read the story the way a reader would.
2. Write the **brief**: voice, point of view, tense, tone, the reader promise, content limits and the style rules that apply, all drawn from the style sheet and the plan. No new creative decisions.
3. Write one **packet per scene**. Each packet holds only what the Drafter needs for that scene:
   - The scene card.
   - Every named person who appears **or is mentioned**, and what matters about them here.
   - The **Fixed Facts** this scene could use or contradict. Leave out later reveals and twists.
   - **The reader should understand now:** the setting, genre and present problem the reader needs by the end of the scene. Protecting a later surprise is never a reason to blur these.
   - **Hide until <event>:** only if needed, the exact fact being protected and where it's revealed, not a broad topic.
   - What the point-of-view character knows at the start of the scene, learns during it, believes but may be wrong about, and doesn't know yet. Use the rule in [../guides/scenes.md](../guides/scenes.md).
   - A short summary of what has happened so far (blank for Scene 1).
   - **Never** the ending or later twists, unless this scene has to set them up. Then say what to set up, not what it pays off.
   - Only the story rules this scene actually uses, marked **background: show through action, don't explain**.
   - For Scene 1, the chosen **Opening hook** first, and the line "Follow `machine/guides/hooks.md`." (Write the path exactly like that; packets live inside the story folder, so a relative link would break.)
4. **Instruction Conflict Check.** Read the brief, every packet, the style sheet and [../roles/drafter.md](../roles/drafter.md) side by side. Look for:
   - Two rules that can't both be followed ("keep it light" and "graphic violence").
   - Facts that differ between files (a name, an age, a timeline).
   - A packet that leaks something the character can't know yet.
   - A style rule the scene card would break.
5. Fix each conflict in the brief or packet. If the only fix changes the approved plan, ask the author one clear question with your recommendation.
6. Note the result in `reviews/conflict-check.md`: what you found and what you changed, or "No conflicts found." This check is always you reviewing your own packets, so mark it **Run as: self-review** in the report and list it that way in the handoff note.

**Done when:** the brief and packets exist and the conflict check is clean. Update `PROGRESS.md`, then go to Step 8.
