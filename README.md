# Favourite Skills

A curated collection of favourite skills vendored into one repository.

Each skill lives in a top-level directory with its own `SKILL.md`, so it can be installed from this repo with:

```bash
npx skills add https://github.com/hebilicious/skills --skill <skill-name>
```

## Updating Vendored Skills

Upstream-sourced skills are tracked in `vendir.yml` and pinned in `vendir.lock.yml`.

To refresh them from their upstream repositories:

```bash
scripts/update-vendored-skills
```

Then review the diff and commit the updated skill directories plus `vendir.lock.yml`.
`codex-review` is maintained locally and is not managed by vendir.

## Available Skills

| Skill | Source |
| --- | --- |
| `git-commit` | [github/awesome-copilot](https://skills.sh/github/awesome-copilot/git-commit) |
| `moon` | [hyperb1iss/moonrepo-skill](https://skills.sh/hyperb1iss/moonrepo-skill/moon) |
| `proto` | [hyperb1iss/moonrepo-skill](https://skills.sh/hyperb1iss/moonrepo-skill/proto) |
| `grill-me` | [mattpocock/skills](https://skills.sh/mattpocock/skills/grill-me) |
| `grill-with-docs` | [mattpocock/skills](https://github.com/mattpocock/skills/blob/main/skills/engineering/grill-with-docs/SKILL.md) |
| `tdd` | [mattpocock/skills](https://skills.sh/mattpocock/skills/tdd) |
| `ataski` | [hebilicious/ataski](https://skills.sh/hebilicious/ataski/ataski) |
| `cucumber-best-practices` | [thebushidocollective/han](https://skills.sh/thebushidocollective/han/cucumber-best-practices) |
| `architecture-diagram` | [cocoon-ai/architecture-diagram-generator](https://skills.sh/cocoon-ai/architecture-diagram-generator/architecture-diagram) |
| `codex-review` | Local skill |

## Install Commands

### `git-commit`

```bash
npx skills add https://github.com/hebilicious/skills --skill git-commit
```

### `moon`

```bash
npx skills add https://github.com/hebilicious/skills --skill moon
```

### `proto`

```bash
npx skills add https://github.com/hebilicious/skills --skill proto
```

### `grill-me`

```bash
npx skills add https://github.com/hebilicious/skills --skill grill-me
```

### `grill-with-docs`

```bash
npx skills add https://github.com/hebilicious/skills --skill grill-with-docs
```

### `tdd`

```bash
npx skills add https://github.com/hebilicious/skills --skill tdd
```

### `ataski`

```bash
npx skills add https://github.com/hebilicious/skills --skill ataski
```

### `cucumber-best-practices`

```bash
npx skills add https://github.com/hebilicious/skills --skill cucumber-best-practices
```

### `architecture-diagram`

```bash
npx skills add https://github.com/hebilicious/skills --skill architecture-diagram
```

### `codex-review`

```bash
npx skills add https://github.com/hebilicious/skills --skill codex-review
```
