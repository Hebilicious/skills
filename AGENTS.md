# Repository Instructions

This repository is a curated collection of favorite skills.

Repository layout requirement:

- Each skill must live in its own top-level directory at the repository root.
- Each skill directory must contain its own `SKILL.md`.
- Keep bundled references, examples, scripts, and support files inside that same skill directory.
- Preserve this layout so `npx skills add https://github.com/hebilicious/skills --skill <name>` works.

When the user provides a new skill to add:

1. Copy the skill into this repository as a top-level directory named after the skill.
2. Preserve the skill contents needed for it to work, including bundled references, examples, scripts, or other support files.
3. If the upstream layout does not match this repository layout, normalize it locally so the skill lives in its own top-level folder.
4. Update `README.md` to include the new skill.
5. In `README.md`, add both:
   - the upstream source link
   - the install command using `https://github.com/hebilicious/skills --skill <name>`

When updating existing skills:

1. Prefer copying from the upstream source again instead of rewriting the skill by hand.
2. Keep local fixes minimal and only use them when required to make the vendored layout work in this repository.
3. Preserve existing README entries unless the upstream source or install command has changed.
