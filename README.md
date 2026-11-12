# Pinterest Growth Skills

**English** · [简体中文](README.zh-CN.md)

Research Pinterest trends, plan Pins, and maintain boards with Codex. Start with what readers in your target market search for and save. Create Pins that give them something useful to keep and a clear next step on the linked product page.

The repository includes [Pinterest Board Maintenance](pinterest-board-maintenance/SKILL.md), a Codex skill written in Simplified Chinese. Set the target market and language for each project.

## From research to published Pins

| Step | What you get |
| --- | --- |
| Research | Topic evidence from **Top monthly trends**, **Growing trends**, saves in **Trends in the spotlight**, seasonal **Moments**, and Pinterest community examples. |
| Plan | A proposal for review with concrete Pin ideas, board assignments, production order, and reasons to pursue or defer each topic. New boards include a name, description, cover direction, and visual style. |
| Create and review | Ready-to-use images, titles, descriptions, alt text, suggested topic tags, and product links. For details such as hands or faces, the skill favors localized edits to photos cleared for editing and publication. |
| Publish and maintain | With your approval, publish and check the public Pin, board placement, and link destination. Compare saves and outbound clicks over the same number of days after publication to decide what to make next. |

## Quick start with Codex

```sh
git clone https://github.com/flaqai/pinterest_growth_skills.git
```

Copy the `pinterest-board-maintenance` folder into a directory Codex can discover, such as `~/.codex/skills/`. Keep `SKILL.md`, `agents/`, and `references/` together. Then start a Codex conversation with a request like this:

```text
$pinterest-board-maintenance

Brand: Example Studio
Product page: https://example.com/product
Market: United States
Pin language: English
Task: Research topics and propose Pins for my Pinterest boards.
```

You can request a single stage, such as trend research, a board proposal, Pin images and copy, or a review of published Pins. The [lock-screen wallpaper example](pinterest-board-maintenance/references/phone-wallpaper-example.md) shows how to give readers a concrete reason to save a design and try their own version.

## License

[MIT](LICENSE)
