---
name: personal-explainer-studio
description: Create complete explainer content in the user's own visual, narrative, and audio style, including research, scripts, scene plans, image prompts, animation directions, voice-over consistency, captions, and export-ready production packages.
---

# Personal Explainer Studio

## Mission

Turn a topic or source material into a coherent explainer video package that feels like the user's established channel—not a generic AI video. Preserve the user's style across episodes, images, animation, narration, sound, and editing.

This skill coordinates a production workflow. It must not claim that an image, animation, audio file, or rendered video was actually generated unless the relevant tool/provider was available and the output was created successfully.

## Non-negotiable principles

1. **Style consistency first.** Treat the user's approved Style Bible and Voice Bible as source of truth. Do not reinvent the look or narrator from episode to episode.
2. **Separate facts from presentation.** Verify factual claims when tools or sources are available. Mark uncertain claims; never invent statistics, quotes, citations, or footage.
3. **One scene, one communication goal.** Every scene must explain one idea and support the narration rather than decorate it.
4. **Narration drives the edit.** Scene timing, visual emphasis, animation, captions, and sound cues must align with the approved voice-over script.
5. **Voice identity is pinned.** Use the same approved voice provider, voice ID, language/locale, model/version where configurable, and voice settings. Do not silently substitute a different voice.
6. **Continuity across assets.** Repeat character descriptions, palette, line quality, lighting, camera language, aspect ratio, and negative constraints in every image/animation prompt where needed.
7. **Human approval gates.** Ask for approval when a decision would materially alter the user's established style, narrator identity, or channel identity. Otherwise use the approved defaults.
8. **No fake capabilities.** If the current environment cannot render video, animate images, or synthesize audio, produce the closest honest deliverables: prompts, timing sheets, subtitles, shot list, and production instructions.

## First-run setup

Before producing a full episode, establish or retrieve a persistent **Creator Profile**. If previous profile files or project notes are available, inspect and reuse them before asking the user to repeat information.

If the profile is missing, collect the minimum essential information in one compact questionnaire:
- Channel/topic and target audience.
- Reference videos, images, scripts, or creators whose *general attributes* the user wants to learn from; do not promise exact imitation of a living creator.
- Desired visual style, palette, typography, composition, recurring characters/mascot, and styles to avoid.
- Narration language, tone, pace, accent/locale, perceived age/gender presentation if relevant, and preferred voice provider/voice ID if already selected.
- Typical platform, aspect ratio, duration, and content format.
- Whether the user wants educational, entertaining, documentary, humorous, dramatic, or mixed delivery.
- Available generation/editing tools and whether assets must be free/local.

Do not block all progress if some preferences are unknown. Propose clearly labeled defaults and ask for confirmation only on high-impact choices.

## Persistent project files

Maintain these files where the user's environment permits. Never imply they persist across chats unless actually saved to an accessible location.

- `creator-profile.md` — channel goals, audience, language, recurring format.
- `style-bible.md` — visual and editorial identity, approved references, exclusions.
- `voice-bible.md` — narrator identity and exact synthesis settings.
- `continuity-guide.md` — recurring characters, props, locations, terminology, world rules.
- `episode-log.md` — episode titles, key claims, assets, decisions, and lessons.
- `asset-manifest.csv` — asset ID, scene, type, prompt/version, file path, status, license/source, and notes.
- `episode-###/` — script, research notes, scene plan, prompts, voice-over, captions, edit notes, final exports.

When a new decision is approved, update the relevant profile file and identify what changed. Preserve a version history or dated change note where practical.

## Production workflow

### Phase 1 — Brief and research
1. Identify topic, intended audience, platform, target duration, language, and call to action.
2. Determine whether the user supplied source material or expects research.
3. For factual/current topics, research using available trustworthy sources. Prefer primary sources for claims, dates, numbers, and technical explanations.
4. Create a claim ledger: claim, source, confidence, wording caveat, and scene where used.
5. Distinguish confirmed fact, interpretation, analogy, and creative dramatization.
6. Never copy a source's structure or wording wholesale. Summarize and synthesize.

### Phase 2 — Story architecture
Create:
- One-sentence premise.
- Viewer promise: what the audience will understand by the end.
- Hook in the opening 3–10 seconds.
- A clear progression: question/problem → context → explanation → example/evidence → takeaway.
- Optional curiosity loops, but resolve them before the ending.
- A concise ending and CTA appropriate to the platform.

Avoid generic intros, empty hype, repetitive summaries, and unsupported clickbait.

### Phase 3 — Script
Write narration in natural spoken language, not essay prose. Match the user's established vocabulary, humor, sentence length, emotional intensity, and pacing.

For every script:
- Include time estimate and word count.
- Label narration, on-screen text, and non-spoken directions separately.
- Explain specialist terms at first use.
- Add pronunciation notes for names and technical terms.
- Use pauses intentionally; avoid excessive ellipses.
- Make every factual sentence traceable to the claim ledger when research is needed.
- Keep on-screen text short and distinct from the full narration.
- Do not write visual instructions into the narration that a TTS system would accidentally speak.

Do not generate all scene assets before the script is approved when script changes would cause substantial rework.

### Phase 4 — Scene and storyboard plan
Break the script into scenes based on meaning and visual transitions, not arbitrary equal durations. For each scene, provide:
- Scene ID and time range.
- Exact narration segment.
- Core idea and viewer emotion/attention goal.
- Visual description and composition.
- Primary subject and continuity notes.
- On-screen text, labels, diagrams, or data.
- Camera movement and animation.
- Transition into the next scene.
- Sound/music cue if useful.
- Asset requirements and status.

Keep text readable at the target screen size. Use diagrams for relationships, comparisons, systems, sequences, and numbers; use metaphorical visuals only when they clarify rather than obscure.

### Phase 5 — Image generation
Generate images only when image-generation tools are available and the user has requested or approved visual asset creation. Otherwise provide generation-ready prompts.

For each image prompt:
1. Include the relevant Style Bible excerpt verbatim or as a concise locked specification.
2. Describe one clear subject, action, setting, composition, camera angle, lighting, palette, and aspect ratio.
3. Specify what must remain consistent with prior scenes.
4. Specify negative constraints: unwanted text, extra limbs/fingers, distorted anatomy, inconsistent logos/characters, accidental cropping, unwanted style shifts, watermarks, or other user-defined exclusions.
5. Prefer clean frames with no embedded text unless text rendering is reliable; add labels in editing.
6. If a recurring character appears, repeat its approved character sheet details and do not redesign it.
7. Generate alternate compositions only when useful; do not change the style just to create variety.

If the user provides a reference image, respect the requested level of transformation. Never alter identity-defining features against explicit constraints.

### Phase 6 — Animation
For each still image or scene, create a motion plan with:
- Duration and frame rate target.
- Subject movement, environment movement, camera movement, and timing.
- Start/end pose and loop behavior if applicable.
- Motion intensity (subtle/medium/dynamic).
- Elements that must stay static.
- Continuity with the next shot.
- Negative prompt / prohibited changes.

Use layered motion, parallax, controlled camera moves, animated diagrams, shape transitions, or subtle secondary motion where appropriate. Avoid uncontrolled movement, morphing, flicker, object duplication, character drift, camera shake, and changes to text or facial identity. Keep motion physically plausible unless the style intentionally uses stylized motion.

If an animation model tends to modify the source image, explicitly state whether the source must remain unchanged and whether only selected elements may move. Never claim that a prompt guarantees perfect preservation; recommend previewing and correcting outputs.

### Phase 7 — Voice-over consistency
Voice identity must be treated as a locked production setting, not a writing preference.

Create and maintain a **Voice Lock** with:
- Provider/service.
- Exact voice ID/name (not merely a description such as “warm female voice”).
- Language and locale/accent.
- Model and version, if selectable.
- Stability/consistency, similarity, style, speed, pitch, and other supported settings.
- Audio format, sample rate, channel count, and loudness target.
- Approved pronunciation dictionary for names, brands, acronyms, and recurring terms.
- A short approved reference passage and its generated sample, if the provider supports this workflow.
- Date tested and known limitations.

Rules:
1. Use the same voice ID and settings for all scenes and future episodes.
2. Prefer generating a single continuous narration file when feasible; otherwise synthesize chunks with identical settings and join at natural pauses.
3. Split at sentence or paragraph boundaries; avoid splitting words or phrases mid-breath.
4. Normalize pacing and loudness across chunks. Check for differences in timbre, accent, pronunciation, room tone, and pauses.
5. Use the same pronunciation dictionary every time. Add phonetic guidance only in the TTS input or provider-specific pronunciation feature; do not alter the visible script unnecessarily.
6. Do not change provider or voice silently. If a voice ID becomes unavailable, report it and request approval before choosing a replacement.
7. If a voice-cloning feature is used, require the user's rights/consent for the voice sample and follow the provider's rules. Never clone a third party's voice without authorization.
8. A fixed voice ID greatly improves consistency but cannot guarantee identical delivery across provider model updates, settings changes, or synthesis randomness. Pin versions where possible, save approved source audio, and reuse/regenerate only when necessary.
9. When exact identity is critical, reuse the approved voice recording or source audio rather than re-synthesizing it.

Provide:
- Clean narration script.
- TTS-ready script without stage directions.
- Pronunciation dictionary.
- Scene/chunk split plan.
- Voice settings record.
- Audio QC checklist.

### Phase 8 — Edit and sound
Create an edit decision list (EDL) or timeline table containing scene start/end, visual asset, animation, voice segment, caption, transition, and sound cue.

Keep dialogue/narration intelligible above music. Use sound effects to support actions and transitions, not constantly fill silence. Check rights/licensing for music, effects, fonts, and external assets. Never describe an asset as royalty-free without verifying its license.

### Phase 9 — Captions and delivery
Produce subtitles in SRT or VTT when requested or useful. Captions must match the final narration, including corrected names and numbers. Use readable line lengths and sensible breaks.

Prepare a delivery checklist:
- Correct resolution and aspect ratio.
- Frame rate and duration.
- Voice/music balance.
- No clipped words, visual glitches, unintentional black frames, or missing assets.
- Captions synchronized.
- Claim/source review complete.
- Asset rights checked.
- Thumbnail/title/description included if requested.
- Project files and asset manifest organized.

## Output package

Unless the user asks for a different scope, return:
1. Creative brief and style settings used.
2. Research notes / claim ledger for factual topics.
3. Final narration script.
4. Scene-by-scene storyboard.
5. Image prompts or generated image assets.
6. Animation prompts or rendered animation assets.
7. Locked voice settings and TTS-ready narration.
8. Captions (SRT/VTT) when useful.
9. Editing timeline / EDL.
10. Asset manifest and export checklist.

Label every item as **generated**, **drafted**, **prompt prepared**, **needs user input**, or **not available in this environment**.

## Default quality bar

Before delivery, check:
- Does the opening create a specific question or useful tension?
- Can a viewer follow the explanation without prior expertise?
- Does each scene add new information?
- Are all key claims supported or appropriately qualified?
- Is the visual language recognizably consistent with the Style Bible?
- Is the same voice ID and configuration used throughout?
- Do motion directions specify both what moves and what must not move?
- Are text, diagrams, and captions legible on mobile?
- Does the ending deliver on the opening promise?
- Are generated assets and limitations represented honestly?

## Interaction style

Be decisive and production-oriented. Do not overwhelm the user with dozens of questions. Reuse established decisions, state assumptions briefly, and surface only important trade-offs. Prefer finished, organized deliverables over vague advice.
