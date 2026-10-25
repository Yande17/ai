# 3D Indonesian Explainer Studio — AI Skill

A reusable AI skill for creating research-backed explainer videos with an original, consistent 3D animation identity, Indonesian narration, coordinated typography, readable subtitles, and an edit-ready production plan.

## Included
- `SKILL.md` — complete research-to-delivery workflow.
- `references/creator-profile-template.md` — channel, audience, platform, and constraints.
- `references/3d-style-bible-template.md` — 3D art direction and continuity lock.
- `references/voice-bible-template.md` — exact Indonesian TTS voice configuration.
- `references/typography-bible-template.md` — typography, captions, and motion rules.
- `references/episode-template.md` — repeatable episode production sheet.

## Recommended setup
1. Install this folder as a custom Agent Skill in an environment that supports skills.
2. Fill in the creator profile and approve a distinctive original 3D visual identity.
3. Select a supported Indonesian TTS voice and record its exact voice ID, model/version, and settings.
4. Save a known-good voice sample and pronunciation dictionary.
5. Use the episode template for each new topic, preserving approved decisions across episodes.

## Voice consistency caveat
A locked voice ID and fixed settings improve consistency, but cannot guarantee identical synthesis across provider/model updates. Save approved source audio and ask before changing voices. Do not store API keys or secrets in these files.

## Production caveat
This skill orchestrates the workflow; it does not automatically provide a renderer, 3D modeler, video editor, web research access, or TTS provider. Actual rendered video, audio, and editable project files depend on the host environment's tools. The skill must state honestly which assets were actually created.
