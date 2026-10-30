---
name: motiongit
description: Extract and package reusable MotionGit .motion templates from a user's finished video code project, preserving the original animation and sound. Also inspect or update an existing MotionGit template using its verified official instructions.
metadata:
  version: "1.0.0"
  canonical_bundle: "https://motiongit.com/skill/motiongit-skill.zip"
---

# MotionGit Skill entry

This is the public entry to the current MotionGit Skill. Fetch the current official bundle for each new authoring task; do not use an old installed copy or a private website repository. The bundle contains the full authoring guide and tools. This repository deliberately does not maintain a second copy of those tools.

1. Use the user's selected finished project and scope. Preserve the source project and existing outputs. Do not confuse MotionGit `.motion` packages with Apple Motion documents.
2. Fetch `https://motiongit.com/skill/motiongit-skill.zip` over HTTPS. Do not follow a redirect to another host. List the ZIP before extracting; reject absolute paths, traversal, symlinks and duplicate entries. Extract only the `motiongit/` contents into a fresh task tool directory, preserving any existing installation or edits.
3. Read `motiongit/SKILL.md` and `motiongit/references/authoring.md`. Before executing `scripts/motion.mjs`, read `BUILD.json`, require a helper version matching `1.0.0-rc.<positive integer>`, and fetch `https://motiongit.com/assets/motion-runtimes/<helperVersion>.json` without cross-host redirects. Require the official metadata, BUILD and actual script to agree on version, SHA256 and byte count. The HTTPS official metadata establishes trust; files from this repository or the ZIP alone do not. Use BUILD and verified metadata for version identity, not a version quoted in descriptive prose.
4. Follow the current bundled authoring instructions for extraction, source and license review, real editable inputs, complete animation and sound coverage, packaging and validation. Use Node.js 22 or later for the verified tool. Do not replace the selected project's style, omit effects, flatten an editable template to video, or mistake static validation for a successful new-content production test.
5. Save the author `.motion` without personal API credentials, retain the source project, and report the actual validation and preview scope. Uploading or publishing is a separate action: do it only when the user also asks, following the current website upload instructions and the user's own upload authorization.

If a user instead supplies an already downloaded personal `.motion`, start with its outer `00-START-HERE.md` and `assistant/guide.json` and the verified personal-package path in the current Skill. Never extract its private core or copy its Key into chat. A request to update an existing package follows `https://motiongit.com/update.md`; preserve the old package and project.

If this assistant cannot access the actual project files or run local tools, explain that limitation and direct the user to a capable local assistant or the manual route at `https://motiongit.com/skill/manual`. Do not claim a package was created without a real output file.
