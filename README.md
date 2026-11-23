# Studio Five Spaces: Branding Skills

Agent skills that apply the **Studio Five Spaces Branding Guidelines 2027 (V9)**. Use them to make or review on-brand websites, decks, social posts, thumbnails, video, print and copy.

**create. collab. cowork.**

## Skills

| Skill | What it does |
|---|---|
| [`studio-five-spaces-brand`](skills/studio-five-spaces-brand/SKILL.md) | Core brand rules (six colours, Sora/Inter, logo and tagline, voice, spacing), defaults for each format, a redesign workflow and the review checklist (READY / REVISE / CLARIFY). |

```
skills/studio-five-spaces-brand/
├── SKILL.md                      # rules used on almost every task
├── references/brand-book-2027.md # full 95-page brand book as Markdown
└── assets/tokens.css             # colour, type and spacing tokens
```

## Install

**Claude Code:** copy the skill folder into your skills directory:

```bash
git clone https://github.com/doniwirawan/studio-five-spaces-branding-skills
cp -r studio-five-spaces-branding-skills/skills/studio-five-spaces-brand ~/.claude/skills/
```

**Claude.ai:** zip `skills/studio-five-spaces-brand/` and upload it under *Settings → Capabilities → Skills*.

The skill loads automatically for any task that mentions Studio Five Spaces, SPACES, studiofivespaces.com or the tagline. You can also ask for it directly ("make this on-brand", "brand review this").

## Not included

The logo SVG/PDF/EPS masters aren't in this repo. Use the supplied files; never redraw the wordmark in a font.
