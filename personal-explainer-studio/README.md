# Personal Explainer Studio — AI Skill

A reusable skill for producing explainer videos in a consistent personal style, from topic and research through scripts, image prompts, animation direction, fixed voice-over settings, captions, and an editing timeline.

## Contents
- `SKILL.md` — main workflow and rules.
- `references/creator-profile-template.md` — channel and creator profile.
- `references/style-bible-template.md` — locked visual style.
- `references/voice-bible-template.md` — persistent voice settings.
- `references/episode-template.md` — repeatable episode production sheet.

## Setup
1. Install/import the skill in an AI environment that supports custom Agent Skills.
2. Fill out the Creator Profile, Style Bible, and Voice Bible using your own reference materials.
3. Select one voice provider and save the exact voice ID and synthesis settings. A descriptive prompt alone does not lock a voice.
4. Store approved images, voice samples, prompt versions, and final audio in a persistent project folder.
5. For every new episode, invoke the skill and provide a topic, source material, or rough idea.

## Important voice note
The skill enforces a stable voice configuration and workflow; it cannot itself guarantee a fixed voice without a TTS provider and a persistent exact voice ID. Provider updates and synthesis randomness can change results. Preserve approved audio as the canonical version and ask before switching voices.

## Platform note
This is a standalone Agent Skill package, not a plugin or a renderer. Actual image generation, animation rendering, text-to-speech, and final video export depend on the tools/services available in the host environment.
