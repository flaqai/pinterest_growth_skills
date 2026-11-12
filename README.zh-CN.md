# Pinterest 运营技能

[English](README.md) · **简体中文**

用 Codex 调研 Pinterest 趋势、策划 Pin（Pinterest 帖子）并维护画板。先了解目标市场的读者在搜索和收藏什么，再把需求做成有实际用途的 Pin，让读者收藏作品，并到链接的产品页尝试自己的版本。

本仓库提供简体中文编写的 [Pinterest 长期画板维护](pinterest-board-maintenance/SKILL.md) 技能。每个项目可指定目标市场和发布语言。

## 从调研到发布

| 阶段 | 交付内容 |
| --- | --- |
| 调研 | 从 **Top monthly trends**（月榜）、**Growing trends**（上升榜）、**Trends in the spotlight**（收藏焦点）、**Moments**（活动节点）和 Pinterest 社区案例中找选题依据。 |
| 提案 | 提供可供确认的具体 Pin、所属画板、制作顺序和选题取舍理由。新画板附名称、简介、封面方向和画风。 |
| 制作与验收 | 交付可用图片、标题、描述、替代文字、主题标签建议和产品链接。手部、五官等细节优先用获准修改和发布的实拍照做局部调整。 |
| 发布与维护 | 获得授权后发布，核对公开 Pin、画板归属和链接落点。按相同发布时长比较收藏与出站点击，决定后续选题。 |

## 在 Codex 中使用

```sh
git clone https://github.com/flaqai/pinterest_growth_skills.git
```

将 `pinterest-board-maintenance` 文件夹复制到 Codex 能发现技能的目录，例如 `~/.codex/skills/`。保留文件夹内的 `SKILL.md`、`agents/` 和 `references/`，再在 Codex 中发起下面这样的请求。

```text
$pinterest-board-maintenance

品牌或账号：Example Studio
目标产品页：https://example.com/product
目标市场：美国
Pin 语言：英语
任务：调研选题，为我的 Pinterest 画板提出 Pin 方案。
```

也可以只做一个阶段，例如查趋势、给画板方案、制作 Pin 图文，或核验已经发布的 Pin。[锁屏壁纸示例](pinterest-board-maintenance/references/phone-wallpaper-example.md)展示了如何让读者有具体理由收藏一张图，并尝试自己的版本。

## 许可证

[MIT](LICENSE)
