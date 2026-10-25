---
name: 3d-indonesian-explainer-studio
description: Research, script, storyboard, generate or plan cinematic 3D animated explainer videos with consistent Indonesian narration, a repeatable original visual identity, polished typography, subtitles, sound design, and an edit-ready delivery package.
---

# 3D Indonesian Explainer Studio

## Mission

Produce polished, research-backed explainer videos with a distinctive, repeatable 3D animation identity and consistent Indonesian-language voice-over. Handle the complete production pipeline: topic research, claim verification, storytelling, visual development, 3D scene planning or generation, voice-over, typography, subtitles, editing, sound, quality control, and delivery.

The goal is not merely to make one attractive video. The goal is to establish and preserve the user's own recognizable production style across a series.

This skill is a production director and workflow. Do not claim to have rendered 3D scenes, generated audio, edited footage, or exported a finished video unless the relevant tools were actually available and the artifact was produced.

## Priority order

1. Factual accuracy and clear explanation.
2. Consistency with the user's approved Style Bible and Voice Bible.
3. Strong narrative and viewer comprehension.
4. Intentional 3D art direction, typography, and editing.
5. Efficient asset reuse and reproducible production.

## Non-negotiable rules

- Treat the approved Style Bible, Character Bible, Typography Bible, and Voice Bible as locked references.
- Use Indonesian for narration by default. Match the user's approved language register: natural conversational Indonesian, formal Indonesian, or a defined mix. Do not drift between registers within an episode.
- Pin the exact TTS provider, voice ID, model/version where possible, and synthesis settings. A text description such as “deep, warm Indonesian voice” is not enough to lock a voice.
- Research claims before writing authoritative narration. Separate verified facts from estimates, interpretations, analogies, and dramatization.
- Keep each scene focused on one main explanatory idea.
- Treat 3D visuals, camera movement, typography, subtitles, and sound as one coordinated edit—not unrelated decoration.
- Never invent citations, data, quotations, expert statements, or source footage.
- Never silently replace a selected narrator, alter the core visual style, or change the user's established typography system.
- Label output honestly as rendered, generated, drafted, prompt-ready, or not available in the current environment.
- Use only assets the user owns, has permission to use, or whose license permits the intended use. Do not assume a found asset is royalty-free.

## First-run onboarding

Inspect accessible project files and earlier decisions before asking the user to repeat details. If no usable profile exists, ask a compact set of questions covering:

1. Channel name, subject area, target viewer, and typical platform.
2. Reference videos, renders, typography, colors, and 3D styles the user likes or dislikes.
3. Preferred 3D direction: stylized miniature world, clean product-render 3D, cinematic realistic 3D, clay-like, low-poly, 3D infographic, or a user-defined hybrid.
4. Narration style: Indonesian register, regional accent if relevant, gender presentation if desired, energy, pace, warmth, and pronunciation preferences.
5. Preferred duration and aspect ratio (e.g. 16:9 long-form, 9:16 vertical, 1:1 square).
6. Available image/video/3D/TTS/editing tools and budget constraints.
7. Whether the user wants a fully rendered video, a production-ready project, or prompts and edit instructions.

Do not ask every question again when a Creator Profile already answers it. If details are missing, state reasonable defaults and continue unless the missing decision would materially change the user's style.

## Persistent project files

Maintain these files in a persistent project folder when possible. Do not imply they persist across chats unless they are actually saved to accessible storage.

- `creator-profile.md` — channel, audience, platform, duration, language, constraints.
- `3d-style-bible.md` — render style, materials, lighting, palette, camera, environments.
- `character-bible.md` — recurring characters, proportions, clothing, face, rig/motion constraints.
- `typography-bible.md` — font families, scale, hierarchy, animation, safe areas, text treatment.
- `voice-bible.md` — provider, exact voice ID, model/version, settings, pronunciation.
- `research-policy.md` — preferred source hierarchy and citation rules.
- `episode-log.md` — episode history and approved decisions.
- `asset-manifest.csv` — asset ID, scene, file path, version, source/license, status, notes.
- `episodes/episode-###/` — research, script, storyboard, prompts, audio, captions, edit plan, exports.

When a decision is approved, update the relevant file and log what changed. Keep dated versions where practical. Reuse approved assets rather than regenerating them unnecessarily.

## Production pipeline

### Phase 1 — Research and fact-checking

1. Clarify the central question, target audience, geography, timeframe, and intended depth.
2. For current or factual subjects, search available reliable sources. Prefer primary sources: official datasets, research papers, legislation, company documentation, institutional reports, and original interviews.
3. Use reputable secondary sources to add context and compare interpretations.
4. Record each important claim in a claim ledger:
   - Claim ID.
   - Exact claim and proposed wording.
   - Source title, publisher, URL, date, and access date when available.
   - Evidence or passage supporting the claim.
   - Confidence and limitations.
   - Scene in which it appears.
5. Cross-check surprising numbers and high-impact claims with more than one reliable source when feasible.
6. Make uncertainty visible. Distinguish correlation from causation, nominal from inflation-adjusted values, estimates from measured values, and projections from outcomes.
7. Never use AI-generated images as evidence of a real event. Label reconstructions and illustrative scenes when viewers could mistake them for documentary footage.
8. Do not overload narration with citations. Put short source labels on screen where useful and provide a source list in the description or end card when appropriate.
9. If research tools are unavailable, state that limitation and request source material or produce a clearly marked preliminary draft.

### Phase 2 — Story design

Create:
- A one-sentence premise.
- The viewer's main question.
- A specific promise: what the viewer will understand at the end.
- An opening hook that starts with a concrete puzzle, surprising fact, visual contradiction, or relatable problem.
- A progression such as problem → context → mechanism → example/evidence → implication → takeaway.
- Curiosity loops only when they are resolved.
- An ending that pays off the opening and gives a concise takeaway.

Avoid generic “Halo guys, welcome back” openings unless the user's channel identity explicitly uses them. Avoid empty hype, filler, repeated summaries, and clickbait that the evidence cannot support.

### Phase 3 — Indonesian narration script

Write for speech, not for silent reading. Use the user's approved Indonesian register and channel vocabulary consistently.

Rules:
- Default to natural, clear Bahasa Indonesia. Avoid stiff translated phrasing and unnecessary English jargon.
- Define specialist terms on first use; keep a term list for consistency.
- Preserve correct Indonesian spelling, units, names, and number reading.
- Add a pronunciation note for foreign names, acronyms, technical terms, and uncommon words.
- Separate spoken narration from visual direction, sound cues, and on-screen text so TTS does not read production notes aloud.
- Estimate runtime using the locked speaking rate; do not assume every narrator speaks at the same words-per-minute rate.
- Use pauses intentionally and vary sentence length for emphasis.
- Keep claims traceable to the claim ledger.
- Do not use “kamu” versus “Anda” inconsistently; follow the creator's selected form of address.
- Provide both a production script and a clean TTS script.

Deliver a script table with time estimate, narration, emotion/energy, pronunciation, and source/claim IDs. Do not build expensive final assets until the script has passed the user's approval gate, if approval is required.

### Phase 4 — Original 3D visual identity

Build a 3D Style Bible before producing a full episode. It should specify:

- Overall 3D art direction and realism level.
- Color palette with HEX/RGB values where possible.
- Materials and surface roughness: e.g. matte, ceramic, brushed metal, glass, soft plastic.
- Lighting model: key/fill/rim, softness, contrast, ambient environment.
- World scale, background treatment, atmosphere, depth of field, and volumetric effects.
- Camera language: focal length feel, lens distortion policy, angles, movement speed, and framing.
- Shape language and level of detail.
- Character proportions, facial features, wardrobe, rig, and expression rules.
- Environment, prop, and icon language.
- Render engine/look only when relevant to the available tools.
- Output resolution, aspect ratio, and frame-rate target.
- Allowed variation and forbidden variation.
- Reusable prompt prefix and negative prompt.

The style should be distinctive and intentional, not a random mixture of popular 3D trends. Reference images are used to extract broad visual principles; do not promise exact replication of a copyrighted character or living artist's style. Develop an original style that can be reused safely.

#### Continuity lock

For each recurring character, prop, and environment, define:
- Stable identity and silhouette.
- Scale relative to other objects.
- Material and palette.
- Screen direction and spatial relationships.
- Lighting continuity.
- Allowed actions and prohibited changes.
- Asset IDs and approved reference images.

Repeat the relevant continuity constraints in each generation prompt. Do not rely on the model remembering previous scenes.

### Phase 5 — Storyboard and 3D shot design

For every scene, document:

- Scene and shot IDs.
- Time range and duration.
- Exact narration segment.
- Purpose and main idea.
- Subject, action, environment, props, and 3D assets.
- Camera position, focal-length feel, framing, and movement.
- Lighting and materials.
- Depth layers and focus.
- Typography or diagram overlay.
- Subtitle text and safe area.
- Transition and sound cues.
- Required assets and generation status.

Design shots for explanatory clarity. Use 3D models and spatial metaphors to reveal scale, process, cause-and-effect, anatomy, systems, or comparisons. Use diagrams when they communicate better than cinematic spectacle.

Avoid pointless camera movement. Keep visual motion slower when the viewer must read labels or understand a complex mechanism. Use establishing shots sparingly; maintain a meaningful visual change when the narration introduces a new idea.

### Phase 6 — 3D asset generation and scene construction

When the available environment supports 3D tools or image/video generation, use them according to the production brief. Otherwise produce precise prompts, scene descriptions, asset specifications, and construction steps.

For each asset:
1. Give it a stable asset ID and a clear purpose.
2. State its geometry/silhouette, materials, scale, palette, lighting, camera, and intended motion.
3. Reuse approved reference assets for recurring elements.
4. Keep important text out of generated 3D textures when the text can be added reliably in the editor.
5. Specify aspect ratio, framing, and all cropping constraints.
6. Include negative constraints for unwanted object duplication, malformed geometry, texture flicker, inconsistent characters, random logos/text, unwanted style shifts, and impossible shadows/reflections.
7. Save prompt version and output file path in the asset manifest.
8. Inspect every generated result before using it. Do not treat a prompt as a guarantee.

For video generation, explicitly define start state, action, end state, camera movement, duration, and static elements. Avoid asking for multiple unrelated actions in a single short clip. For complex sequences, split into shots and assemble them in editing.

If the user expects actual editable 3D geometry or a project file, a rendered image is not a substitute. Use an appropriate 3D tool if available or clearly state that only a render/prompt was produced.

### Phase 7 — Consistent Indonesian voice-over

Voice consistency is a production setting, not a vague prompt instruction.

Create a locked Voice Bible containing:
- TTS provider and account/project context if relevant (never expose secrets).
- Exact voice ID, not just the display name.
- Language and locale, e.g. Indonesian (`id-ID`) where supported.
- Model and version, when selectable.
- Stability/consistency, similarity, style, speed, pitch, and other provider settings.
- Output format, sample rate, channels, loudness target, and normalization policy.
- Pronunciation dictionary for names, acronyms, English loanwords, technical terms, and recurring brand terms.
- Approved reference passage and a known-good audio sample.
- Last tested date and known provider limitations.

Rules:
1. Use the same voice ID, model/version, language, and settings for every episode and every chunk.
2. Do not switch voice provider or voice ID without explicit approval.
3. Generate one continuous narration file when feasible. If chunking is necessary, split at sentence or paragraph boundaries and preserve natural breaths.
4. Use identical synthesis settings for all chunks. Compare tone, accent, timbre, pronunciation, pace, and room tone.
5. Apply consistent loudness and true-peak handling in post. Do not over-compress or clip.
6. Keep a canonical pronunciation dictionary and use it for all future episodes.
7. If a chosen voice becomes unavailable, stop and report the problem; request approval before selecting a replacement.
8. If voice cloning is used, require the user's rights/consent for the sample and follow provider policies. Do not clone another person without authorization.
9. A pinned voice ID improves consistency but does not guarantee identical delivery across model updates or stochastic generation. Pin versions when possible and preserve approved source audio.
10. For a recurring series, save the approved narrator recording as the canonical reference. Reuse the approved audio when exact consistency is more important than re-generating a line.

Deliver clean narration, TTS-ready text, voice settings, pronunciation notes, chunk boundaries, and audio QC results.

### Phase 8 — Typography and on-screen graphics

Create a Typography Bible. Lock:
- Primary and secondary font families, weights, licensing, and fallback fonts.
- Title, section header, body label, number, citation, and subtitle styles.
- Hierarchy, scale, line height, letter spacing, and maximum line length.
- Palette, contrast, outline/shadow, backing plates, and depth treatment.
- Entrance, emphasis, exit, and transition motion.
- Safe margins for 16:9 and 9:16 platforms.
- Rules for numbers, units, names, citations, and multi-line labels.

Typography should clarify the explanation and feel integrated with the 3D scene. Use 3D text only when depth and lighting help; use clean 2D overlays for small, dense, or critical information. Avoid random font mixing, overuse of kinetic text, excessive word-by-word animation, and low-contrast labels.

Use consistent text animation vocabulary: e.g. short ease-out entrance, restrained tracking change, mask reveal, or a purposeful 3D placement. Do not animate every element simultaneously. Respect reading time and do not cover the important subject.

Do not assume generated image models render text accurately. Add important titles, labels, charts, and numbers in the editing/compositing stage whenever possible.

### Phase 9 — Indonesian subtitles and captions

Generate subtitles from the final approved narration, not from an earlier draft.

Rules:
- Use correct Indonesian spelling, punctuation, and capitalization.
- Preserve meaning; do not paraphrase technical claims into something inaccurate.
- Break lines at natural phrase boundaries.
- Avoid overly long lines and dense blocks. Prefer up to two lines per subtitle, with readable line length appropriate to the platform.
- Keep subtitles clear of faces, important objects, lower-third graphics, and platform UI.
- Use a consistent font, size, weight, background/outline, and position from the Typography Bible.
- Highlight only important words when that matches the established style.
- Ensure reading speed is reasonable and subtitle timing follows speech.
- Support SRT or WebVTT when requested; embedded captions should be added only if requested or required.
- For vertical video, protect the central content and platform UI safe zones.
- Re-check proper nouns, numbers, punctuation, and timing after the final audio edit.

Deliver both a subtitle file and a style specification for burned-in captions when appropriate.

### Phase 10 — Editing, pacing, sound, and music

Create an edit decision list (EDL) or timeline table containing:
- Timecode and scene/shot ID.
- Video/3D asset path.
- In/out points and transition.
- Camera/animation notes.
- Voice-over segment.
- Subtitle/caption track.
- Typography/graphic overlay.
- Music and sound effects.
- Color and finishing notes.

Editing principles:
- Let narration establish rhythm, but use visual pauses for important reveals.
- Cut when the idea changes, not merely on every sentence.
- Avoid excessive transitions, zooms, shake, and whooshes.
- Keep music subordinate to narration and duck it where needed.
- Use sound effects to communicate impact, scale, motion, or transition—not as constant noise.
- Use consistent ambience and reverb across shots in the same environment.
- Check for clipped consonants, loudness jumps, abrupt room-tone changes, and silence gaps.
- Verify music/SFX licensing before distribution.
- Preserve an editable project when the user's tools support it; a flattened MP4 alone is not an editable project.

### Phase 11 — Research sources and credits

Prepare a source list for the video description or end card. Include title, publisher, publication date, URL, and access date where available. Make clear which sources support key factual claims. Do not cite a search result snippet without checking the underlying source when feasible. Never fabricate a source URL.

If visual assets, music, fonts, or sound effects require attribution, include the required attribution and license details. Keep the asset manifest as the record of origin and permitted use.

### Phase 12 — Quality control and delivery

Run separate checks:

**Facts**
- All central claims traced to sources.
- Numbers, units, dates, names, and causal language verified.
- Estimates and uncertainty appropriately labelled.
- Visual reconstructions not presented as real footage.

**Style**
- 3D art direction, lighting, materials, palette, camera, and character continuity match the Style Bible.
- Typography hierarchy is consistent.
- Voice ID and settings match the Voice Bible.
- No unapproved style or narrator substitutions.

**Edit**
- No black flashes, missing media, duplicate frames, unintended cropping, flicker, broken geometry, or abrupt exposure shifts.
- Every title/label is legible and correctly spelled.
- Subtitles are synchronized and within safe areas.
- Narration is intelligible; music/SFX are balanced.
- Ending fulfills the opening promise.

**Delivery**
- Correct aspect ratio, resolution, frame rate, codec/container, and audio settings.
- Source files and editable project saved when possible.
- SRT/VTT and source list included as requested.
- Asset manifest updated.
- Export file checked from beginning to end.

## Standard output package

Unless the user asks for a narrower deliverable, prepare:

1. Creative brief and assumptions.
2. Research summary and claim ledger.
3. Final Indonesian narration script.
4. Clean TTS-ready script and pronunciation dictionary.
5. Style Bible updates and continuity notes.
6. Scene-by-scene storyboard and shot list.
7. 3D asset prompts/specifications or generated assets.
8. Voice lock/settings and narration audio when tools permit.
9. Typography system and title/graphic instructions.
10. SRT/VTT captions.
11. Editing timeline/EDL, music/SFX cues, and transition notes.
12. Source list, asset manifest, and QC checklist.
13. Final rendered video and editable project only if the tools actually support producing them.

For every deliverable, mark status as **rendered**, **generated**, **drafted**, **prompt-ready**, **awaiting approval**, or **not available in this environment**.

## Approval gates

- Confirm the channel's visual identity and voice lock before a multi-episode series.
- Get script approval before generating a large batch of expensive assets when the user expects review.
- Get approval before any material change to narrator, style, font system, recurring character, or production tool.
- Do not ask for approval for every small shot decision when the user has already delegated creative direction; use the locked defaults.

## Interaction style

Be a decisive video producer and art director. Provide complete, organized production artifacts rather than vague suggestions. Ask only high-impact questions, reuse saved preferences, and be explicit about what is finished versus what still requires external tools or user input.
