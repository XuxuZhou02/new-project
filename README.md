# Content Systems Portfolio

为申请 **Lyft · UX Content Design Intern (Summer 2027, Toronto)** 准备的作品集网站。
单文件静态站点（`index.html`），可直接用 GitHub Pages 发布。

## 三个案例分别对应 JD 要求

| 案例 | 对应 JD 要求 | 展示的能力 |
| --- | --- | --- |
| **One concept, every surface** | Information architecture、publishing workflows、"connected content objects" | 内容审计、四层内容模型（Concept → Facts → Variants → Placements）、分面分类法、string key 命名规范、发布流程重设计、治理、可交互的"改一次政策、所有渠道同步更新"演示 |
| **When the ride doesn't go to plan** | UX writing（UI、notifications、errors）、brand voice、accessibility | 错误文案三问框架、语气随风险变化、6 组 before/after 改写（自动字数统计）、无障碍与法语扩展 |
| **Ready for trip one** | Learning experience design、learning center、knowledge base | 学习目标、"上岗前 vs 发生时"内容分拣、学习路径、微课分镜、带反馈的知识检测（可交互）、与案例 1 内容模型的连接 |

三个案例共用同一个网约车场景，体现 JD 里强调的 "systems mind"。

## 提交前必须修改的地方

在 `index.html` 中搜索 `[` 和 `TODO`：

- `[Your Name]`、`[program]`、`[university]`、`[Month 2028]`、`[Degree, program]`、语言
- `[your.email@example.com]` 和 LinkedIn 链接（搜索 `linkedin.com`）
- 每个案例的 Timeline（`[3 weeks, Fall 2026]` 等）
- About 部分用你自己的经历重写
- Tools 列表只保留你真正用过的工具
- 改完后可以删除 `class="ph"`（那是让占位符高亮的样式）

## 让作品集更有说服力（强烈建议）

这些案例目前是"自发概念项目"，已在页面上如实标注。面试时会被追问细节，建议：

1. **真实做一次审计**：挑一个你常用的 App（例如网约车或外卖）和它的帮助中心，截图记录同一概念在不同地方的说法，替换案例 1 的审计表。
2. **做 5 人理解度测试**：把案例 2 的 before/after 给 5 个朋友看，问"读完你会做什么？"，把结果写进页面里 `TODO` 的位置。
3. **访谈 2–3 位司机**：验证案例 3 的假设，把一句真实引用放进页面。
4. 用自己的话过一遍每段文字，确保你能在面试里解释每个决定背后的原因。

## 发布到 GitHub Pages

1. 把这个分支合并到 `main`
2. 仓库 Settings → Pages → Source 选 `Deploy from a branch`，Branch 选 `main` / `(root)`
3. 几分钟后访问 `https://<你的用户名>.github.io/new-project/`

## 本地预览

直接用浏览器打开 `index.html` 即可，不需要构建。
