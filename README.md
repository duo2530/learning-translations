# learning-translations

可公开 AI 学习资料的分类索引。从这里按主题找到原标题和原链接，再决定要不要读。

## 状态怎么读

「收藏」只表示这条资料已经收进索引。它不表示已经学完，也不表示已经理解。学习进度未知的条目，状态只写「收藏」。用户明确标成待学、尚未开始的，状态写「待学」。本索引不填写理解程度。

目前 41 个信息源全部是「收藏」。95 条具体资源里，94 条是「收藏」，1 条是「待学」（下面这条视频）。

## 先看这条（待学）

[17 agents, one SDLC: How Levi Strauss reimagined development on GitHub](https://www.youtube.com/watch?v=-GpxKKgoWWg)

YouTube，GitHub 官方频道。状态：待学。整理记录：链接已抽查可访问。收录日期：2026-11-13。

完整条目只在 [SDLC 与多 Agent 研发](resources/sdlc-and-multi-agent.md#levi-strauss-sdlc)。上面的链接是同一条的入口，不另计资源。

## 信息源

[信息源](sources.md) 收录长期关注的账号和站点，共 41 条。

| 平台 | 数量 |
| --- | ---: |
| B站 | 7 |
| GitHub | 4 |
| YouTube | 2 |
| 公众号 | 9 |
| 掘金 | 2 |
| X | 13 |
| 网站 | 2 |
| 知乎 | 2 |

其中 13 条没有直达链接，只保留名称和平台：Github Trending、Github Stars、9 个公众号，以及 X 上的 OpenAI开发者、ClaudeCode开发者。

## 具体资源

95 条资源按主题放在 `resources/`。分类沿用原表的类型和标签。短介绍只保留原收藏里已有的一两句说明，不另写学习心得。

同一条资料若跨多个主题，会在对应文件里各列一次，链接相同。下面的数字是各文件中的出现次数；按 URL 去重后仍是 95 条。有 12 条出现在两个主题里，所以出现次数合计是 107。

标题相同的条目不一定是同一条，以链接区分。例如多条都叫「软件工厂」或「代码审查」。

- [AGENTS.md / CLAUDE.md](resources/agents-md.md)（5）
- [Skills](resources/skills.md)（17）
- [Spec-Driven Development](resources/spec-driven-development.md)（14）
- [Harness 与软件工厂](resources/harness-and-software-factory.md)（26）
- [Code Review](resources/code-review.md)（5）
- [SDLC 与多 Agent 研发](resources/sdlc-and-multi-agent.md)（5）
- [Codex](resources/codex.md)（5）
- [项目与仓库](resources/projects-and-repos.md)（8）
- [课程、书籍与教程](resources/courses-books-and-tutorials.md)（3）
- [其他文章与技巧](resources/articles-and-tips.md)（19）

## 链接状态

链接状态沿用整理时的记录。未查过或被拦截的链接保持未验证，不写成可访问。

- **链接已抽查可访问**：整理时记录到成功响应。信息源 8 条，具体资源 37 条。以后仍可能失效。
- **链接未验证**：未做远程校验。常见于微信公众号、X、知乎。这个标记不等于链接已失效。具体资源 58 条。信息源里另有 13 条有链接但未做远程校验（X 11、知乎 2）。
- **链接未验证（访问被拦截）**：整理时访问被拦截，没有完成校验。目前是 [信息源](sources.md) 里的 7 条 B站。这个标记不等于链接已失效。
- **无直达链接**：原收藏没有 URL，只保留名称和平台。

整理记录里没有标成 404 的条目。以后若抽查到打不开，再单独标明，并保留人工确认。

## 怎么继续维护

Markdown 是这份索引的唯一名单，不另存一份 JSON，避免两处同时改。

新增一条时：

1. 保留原标题和原链接。没有链接就写名称和平台。
2. 写上原有类型或标签。短介绍只用已有的一句说明。
3. 状态默认写「收藏」。只有明确待学时写「待学」。
4. 放进上面的主题文件。确实跨主题时，可以在多个文件列出同一链接。
5. 改完后核对主题文件里的出现次数、按 URL 去重后的资源数，以及 [信息源](sources.md) 的平台数量。

可以公开的标题和链接才能放进来。私人笔记、未公开文档、内部地址和凭据不写入这个仓库。
