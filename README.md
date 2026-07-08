# Taste Skills — InspiredHub

> A living humanities archive that teaches AI what humans find worth returning to.

InspiredHub is a platform where people encounter great works — paintings, texts, music — and respond to them. They linger. They save. They write something down. Over time, a picture forms: not of what they like, but of who they are aesthetically. The Taste Skills distill that signal into a format any OpenClaw agent can absorb.

**[→ Try the Live Demo — no account needed](https://inspiredhub.ai/demo)**

---

## Before / After

![taste-modern applied to an AI product landing page — visual transformation](https://files.manuscdn.com/user_upload_by_module/session_file/310519663095235434/rZsELFHxYsgVTrfO.png)

*The same AI-generated landing page — without a Taste Skill (top) and with `taste-modern` applied (bottom). The skill doesn't just change the aesthetic: it changes the entire visual logic of the output.*

---

## Install

```bash
# Install a single skill
openclaw skills install @johnnyzijianwu/taste-van-gogh

# Or install the full collection
openclaw skills install @johnnyzijianwu/taste-baroque
openclaw skills install @johnnyzijianwu/taste-impressionism
openclaw skills install @johnnyzijianwu/taste-romanticism
openclaw skills install @johnnyzijianwu/taste-modern
openclaw skills install @johnnyzijianwu/taste-monet
openclaw skills install @johnnyzijianwu/taste-kandinsky
openclaw skills install @johnnyzijianwu/taste-hokusai
openclaw skills install @johnnyzijianwu/taste-goethe
openclaw skills install @johnnyzijianwu/taste-shakespeare
openclaw skills install @johnnyzijianwu/taste-dante-alighieri
```

---

## The Collection

Each Skill is a distillation of one master's aesthetic worldview — their compositional logic, their relationship to light and shadow, their emotional register. Not a biography. Not a style guide. A lens.

| Skill | Master | Domain | ClawHub |
|-------|--------|---------|---------|
| `taste-baroque` | Caravaggio, Rembrandt, Vermeer | Painting | [→ ClawHub](https://clawhub.ai/johnnyzijianwu/skills/taste-baroque) |
| `taste-impressionism` | Monet, Renoir, Pissarro | Painting | [→ ClawHub](https://clawhub.ai/johnnyzijianwu/skills/taste-impressionism) |
| `taste-romanticism` | Delacroix, Turner, Friedrich | Painting | [→ ClawHub](https://clawhub.ai/johnnyzijianwu/skills/taste-romanticism) |
| `taste-modern` | Picasso, Matisse, Duchamp | Painting | [→ ClawHub](https://clawhub.ai/johnnyzijianwu/skills/taste-modern) |
| `taste-van-gogh` | Vincent van Gogh | Painting | [→ ClawHub](https://clawhub.ai/johnnyzijianwu/skills/taste-van-gogh) |
| `taste-monet` | Claude Monet | Painting | [→ ClawHub](https://clawhub.ai/johnnyzijianwu/skills/taste-monet) |
| `taste-kandinsky` | Wassily Kandinsky | Painting | [→ ClawHub](https://clawhub.ai/johnnyzijianwu/skills/taste-kandinsky) |
| `taste-hokusai` | Katsushika Hokusai | Woodblock Print | [→ ClawHub](https://clawhub.ai/johnnyzijianwu/skills/taste-hokusai) |
| `taste-goethe` | Johann Wolfgang von Goethe | Literature | [→ ClawHub](https://clawhub.ai/johnnyzijianwu/skills/taste-goethe) |
| `taste-shakespeare` | William Shakespeare | Literature | [→ ClawHub](https://clawhub.ai/johnnyzijianwu/skills/taste-shakespeare) |
| `taste-dante-alighieri` | Dante Alighieri | Literature | [→ ClawHub](https://clawhub.ai/johnnyzijianwu/skills/taste-dante-alighieri) |

> The authoritative source for each SKILL.md is ClawHub. This repository is the index.

---

## What's inside a Taste Skill

Each SKILL.md contains:

- The master's core aesthetic principles (not facts — positions)
- How they approached composition, light, language, or structure
- What they valued, what they rejected, what they returned to
- Prompts that activate the aesthetic lens in agent output

Skills are grounded in primary works, not secondary commentary. The Van Gogh skill draws from 843 paintings and letters. The Dante skill draws from the Commedia itself.

The difference shows up in writing too:

![Before and After: AI writing quality with vs without InspiredHub Taste Skills](https://files.manuscdn.com/user_upload_by_module/session_file/310519663095235434/KCrBGpvCIKjHKXGa.png)

*Without a Taste Skill, agents default to generic, statistically average output. With one, they write from a specific aesthetic position — grounded in how a master actually saw the world.*

---

## The Data Behind It

These skills are the public-facing layer of a larger project. InspiredHub has been collecting authentic human aesthetic behavior since March 2025:

- **411 works** across painting, literature, and music
- **1,408 annotated behavioral events** (dwell time, return visits, written responses, creative output)
- **30.2 minutes** average session length — 8× the industry average for cultural platforms
- Data architecture grounded in neuroaesthetics literature: Brieber et al. (dwell time), Grinde & Husselman 2022 (return visits), Vessel & Bignardi (depth over time), Nadal (natural language response)

The Taste Model — a model trained to judge whether something is genuinely good, not just technically correct or statistically popular — is in development.

---

## Using this in a real project?

We'd love to see what you're building.
Drop us a note: [contact@inspiredhub.ai](mailto:contact@inspiredhub.ai)

---

*MIT-0 License · Made by [InspiredHub](https://inspiredhub.ai) · Shanghai & Paris*
