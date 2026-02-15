# 🎬 Present — Next-Generation HTML Presentations

An [OpenClaw](https://github.com/openclaw/openclaw) skill that creates stunning, interactive presentations from a single prompt. No PowerPoint. No dependencies. Just one self-contained HTML file you open in any browser.

**[See a live example →](https://mikedyan.github.io/fff-openclaw/)**

## What Makes This Different

Most presentation tools give you slides. This gives you **experiences**.

- 🖥️ **Terminal boot sequences** that simulate a system starting up
- 🃏 **Flip cards** you click to reveal hidden content
- 💬 **Chat replays** that type out conversations in real-time
- 📊 **Animated dashboards** with numbers counting up on entry
- 🎯 **Clickable diagrams** where each node reveals detail panels
- ✨ **Particle systems** reactive to mouse movement
- ⌨️ **Live code terminals** with typing animations

All in a single HTML file. Zero external dependencies (except optional Google Fonts).

## Install

Clone into your OpenClaw skills directory:

```bash
git clone https://github.com/mikedyan/openclaw-skill-present.git \
  ~/.openclaw/skills/present
```

## Usage

Just ask your OpenClaw agent to make a presentation:

> "Create a presentation about our Q1 results"

> "Make a pitch deck for my startup idea"

> "Build an interactive slide deck explaining how neural networks work"

The skill handles the rest — it'll ask about your audience, vibe, and content, then generate a complete HTML file.

### Vibes

Pick a starting point or describe your own:

| Vibe | Feel |
|------|------|
| 🌑 **Dark Tech** | Apple keynote meets hacker terminal |
| 🏔️ **Minimal Zen** | Whitespace, elegant type, serene motion |
| 🎨 **Bold Creative** | Vivid colors, playful animations |
| 🏢 **Corporate Sharp** | Clean, professional, data-forward |
| 🌅 **Warm Narrative** | Earthy tones, storytelling flow |
| ✨ **Custom** | Describe it and the agent builds it |

## How It Works

1. **Discover** — The agent clarifies your content, audience, and aesthetic
2. **Architect** — Plans each slide as a *moment*, not a page
3. **Build** — Generates a single self-contained HTML file (all CSS + JS inline)
4. **Iterate** — Refine with feedback until it's right

### Technical Details

- Keyboard navigation (arrow keys + space)
- Navigation dots + slide counter
- Smooth CSS transitions between slides
- Responsive for 16:9 screens
- Canvas background effects (particles, starfield, etc.)
- No build step, no bundler, no framework — just HTML

## Design Philosophy

- **Typography is the hero** — Great presentations are 80% type
- **Restraint over excess** — Every animation earns its place
- **Interactive moments are peaks** — Placed strategically, not everywhere
- **Contrast creates impact** — Quiet slides make dramatic ones hit harder

The goal isn't "a nice slide deck." It's an experience that makes people ask for the source file.

## Example Output

The [OpenClaw presentation](https://mikedyan.github.io/fff-openclaw/) was built entirely with this skill. It features:

- Animated starfield background
- Terminal-style boot sequence opening
- Interactive flip cards for feature demos
- Chat replay mockups
- Smooth slide transitions with navigation dots

## License

MIT
