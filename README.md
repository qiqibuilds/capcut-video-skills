# CapCut video effect skills

Reusable skills that help Codex recreate specific video effects in CapCut. The repository contains instructions and shape references, not tutorial videos, personal footage, screenshots, or account data.

## Install in Codex

Install both skills with one command:

```bash
gh skill install qiqibuilds/capcut-video-skills --all --agent codex --scope user
```

This uses the [GitHub CLI skill installer](https://cli.github.com/manual/gh_skill_install). Install GitHub CLI first if `gh` is not already available. Start a new Codex conversation after installing so it discovers the skills.

To install only one effect, replace `--all` with its name:

```bash
gh skill install qiqibuilds/capcut-video-skills constellation-text-overlay --agent codex --scope user
```

The skills tell Codex how to edit; they do not provide a CapCut connection. Enable and connect the CapCut plugin in Codex before asking it to create a cloud draft. An existing desktop-only project may need to be opened in the desktop editor.

## Available effects

| Skill | What it creates | What to provide |
| --- | --- | --- |
| `story-tapping-intro` | A person reaches through an Instagram-style screen and taps a story | Opening screen, reach footage, reveal video |
| `constellation-text-overlay` | Words appear on stars connected by a hand-drawn line | Background video and exact text; Codex then asks for color and shape |

The constellation's shape guides the layout. The line connects exactly one star per word; other same-size stars stay unconnected.

## Try it

> Use `$story-tapping-intro` with my opening screen, reach footage, and reveal video. Build the effect in CapCut and let me preview it.

> Use `$constellation-text-overlay` on this clip. Ask me for the words, color, and shape, then build the effect in CapCut and let me preview it.
