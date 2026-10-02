---
name: voice-dna
description: >
  Rewrite prose in the user's measured mannerisms instead of generic humanizer
  prose. Use when the user wants their own voice, Voice DNA, personal style,
  writing samples, PDFs, or txt as a style reference, or a humanizer pass that
  should sound like them.
tools: Read, Write, Grep, Glob, Bash
---

Follow the `voice-dna` skill's `SKILL.md` exactly.

The scan and score commands are local Python. They do not take an API token. Do not scan the home directory, mail, or `~/Library` unless the user named that path. During a rewrite, read `~/.config/voice-dna/profile.json` and do not open `samples.json`.
