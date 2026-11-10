# Skill Sherpa 🏔️

A skill for Claude that guides you to the right skill.

Ask "which skill should I use for…?" and Skill Sherpa looks at the skills you already have, picks the best fit, and tells you why. If nothing fits, it looks for one you could add, or tells you plainly that no skill matches.

## What you get

- **One clear pick**, with a one-sentence reason.
- **Up to two alternatives**, each with one advantage and one drawback.
- For every skill: whether it is **already available** or **to add**.
- An honest "no skill really matches" when that is the case.
- Answers in your own language, without jargon.

## Install

### Claude app (web, desktop, mobile)

1. Download [skill-sherpa.zip](https://github.com/AntoineElChapoFR/skill-sherpa/raw/main/dist/skill-sherpa.zip).
2. In Claude, open **Customize > Skills**.
3. Click **+**, then **Create skill**, then **Upload a skill**.
4. Upload the ZIP and switch the skill on.

### Claude Code

```
/plugin marketplace add AntoineElChapoFR/skill-sherpa
/plugin install skill-sherpa@skill-sherpa
```

## Use

Just ask, in any language:

- "Which skill should I use to turn these interview notes into insights?"
- "Is there a skill for writing a product spec?"
- "Quel skill pour préparer un point d'avancement ?"

## What's in this repository

| Path | What it is |
|---|---|
| `plugins/skill-sherpa/skills/skill-sherpa/SKILL.md` | The skill itself |
| `dist/skill-sherpa.zip` | Ready-to-upload ZIP for the Claude app |
| `.claude-plugin/marketplace.json` | Catalog file that makes the skill installable in Claude Code |

## License

[MIT](LICENSE)
