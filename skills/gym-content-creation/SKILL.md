# Gym Content Creation

## Two modes, one skill

- Route by the requested deliverable and do not mix the two production contracts in one video unless the user asks for a hybrid.

- Use Mode A Filmed for content a real person performs on camera in a gym or at home.

- Use Mode B Faceless for AI generated explainers with the locked 2.5D sketch duo from `references/gym-character.md` — the bulky grey Coach who teaches and the lean Student whose trained muscle glows red — with voiceover and no filming needed. Use a stickman style only when the user explicitly asks for one.

- Ask one short question when the mode is ambiguous and honor choices the user already supplied.

## Setup gate

- Require a topic or goal, a mode, a platform, and a target length before planning.

- Default to vertical 9:16, 30 to 45 seconds, and English voiceover or dialogue when the user gives a topic and nothing else, and state those defaults in Phase A.

- Ask in one concise message when the platform or length would change the script structure, for example a long YouTube tutorial instead of a Short.

- Read `references/hooks-and-pillars.md` before choosing a format and `references/platform-specs.md` before locking length and framing.

- Read `references/form-and-safety.md` before writing any exercise instruction, routine, or nutrition claim.

## Phase A proposal

- Produce Phase A first and stop for explicit approval before Phase B.

- Include the hook for the first 2 seconds, the exact spoken script with a word count matched to the target length, and a shot by shot outline with timing.

- Include the audience, the one clear takeaway, the equipment needed, the location, and the on-screen text as a post-production note.

- Include two title options, a thumbnail or cover idea, and a caption draft from `references/captions-and-publishing.md`.

- Recompose Phase A and ask for approval again when the user changes the mode, platform, length, exercise, or audience.

- Treat approval of an older draft as approval of nothing in a changed draft.

## Phase B for Mode A Filmed

- Turn the approved Phase A into a filming checklist the user can follow set by set.

- Give each shot its camera angle, framing, distance, movement cue, exact line or silent demo note, and the number of clean reps to film.

- Mark one hero shot for the cover frame and note where to leave pauses for captions.

- End with an editing order, caption placement notes, and the publishing kit from `references/captions-and-publishing.md`.

## Phase B for Mode B Faceless

- Turn the approved Phase A into standalone per-clip video prompts, one per clip, each repeatable without reading the others.

- Read `references/gym-character.md` before planning any Mode B video and use its locked 2.5D sketch Coach and Student characters, its reference images in `assets/`, and its frozen voice blocks by default. Repeat the full style anchor, both character anchors, and the frozen voice blocks verbatim in every prompt, keep the hand-drawn grey sketch style with only the Student's orange shorts and red muscle glow in colour, never photorealistic and never flat stick figure, and follow the `directing_stickman_videos` skill only when a stickman style is explicitly selected.

- Keep generated clips free of visible words and put all text in a post-production overlay note.

- Follow the `iterative_video_continuity` skill when Muse generates chained clips itself, locking character, setting, camera, voice, and spoken lines before the first generation and checking frames before delivery.

- State plainly that audio and voice cannot be verified from frames and ask the user to listen-check generated clips.

## Content rules

- Build every script on one promise, one takeaway, and one call to action.

- Open with a mistake, a myth, a result, or a direct question, and never open with a greeting or a channel introduction.

- Show the correct form before adding weight, speed, or variations, and give one beginner regression and one harder progression when the format allows.

- Use plain cue words a beginner can act on, such as brace, hinge, or ribs down, and explain each cue in one short line the first time it appears.

- Do not invent statistics, studies, personal results, or product claims.

- Do not diagnose pain or injury, promise fat loss in a body part, or give calorie or supplement prescriptions for a named person.

- Add a short see a qualified professional note only when a topic touches pain, injury, medical conditions, or eating.

## Revision and final check

- Recheck form cues, exercise order, and rest guidance against `references/form-and-safety.md` before delivering Phase A or Phase B.

- Check the script word count against the target length and cut repetition before cutting the takeaway.

- Check that every shot in Phase B traces back to an approved line in Phase A and that no new exercise or claim appears unapproved.

- Offer a 30 day calendar built from `templates/content-calendar-30-days.md` once, after a first video is approved, and never block delivery on it.

## Available connectors

- Use `muse.skill_search` to find related skills, including `directing_stickman_videos` for stickman styles and `iterative_video_continuity` for chained AI clips.

- Use `muse.connector_search` to find connectors for publishing or scheduling when the user asks to post the finished content.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with the `custom_connector_setup` skill, or build a custom connector.
