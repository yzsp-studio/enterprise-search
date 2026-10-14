<div align="center">

# 🎬 enterprise-search

## 企业资料里的答案，先读规则再检索，句句带来源
## Full-sentence questions, internal answers, every fact tied to a source

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

决定一个问题该不该调用企业知识问答工具，并在调用前要求先完整读完本技能，否则不做任何路由判断。它覆盖进入判断、调用边界、query 构造、多轮继承、无结果兜底与结果使用要求：query 必须是完整、可独立理解的自然语言问题，禁止关键词、标签或名词枚举。先用一句话区分你是想「从企业内部资料里找答案并综合」，还是已经「锁定某个具体对象要读取、编辑或操作它」——后者走对应的对象能力，不用检索工具。适用于会议、群聊、文档、日程、项目与人员相关信息的搜索、追溯、复盘和汇总，提炼结论、待办、风险、反馈或进展；内部信息与公开信息混合时也要先区分来源。默认每个用户问题只调一次检索，多个内部子问题合并调用。

### ✨ 能做什么

- 先分流「从内部资料找答案并综合」与「锁定明确对象要读取/编辑/操作」，后者不调用检索工具而走对应对象能力
- query 必须是完整、可独立理解的自然语言问题，禁止关键词、标签或名词枚举，多个内部子问题合并为一次调用
- 覆盖会议、群聊、文档、日程、项目与人员信息的搜索、追溯、复盘和汇总，提炼结论、待办、风险、反馈与进展
- 每条来源的事实、数据、结论或转述都必须就地添加来源引用，保留来源链接与材料入口链接，Markdown 材料链接原样迁移
- 内部信息与公开信息混合时先完成内部资料查询再处理对象操作，并明确区分内部资料与公开来源
- 检索无结果或结果不足时不断言事实不存在；用户未排除公开来源时可补充公开信息，并标清两类来源的边界

### 📦 包含的技能

- `enterprise-search` —— 见 [`enterprise-search/SKILL.md`](enterprise-search/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/enterprise-search.git
cp -r enterprise-search/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

Decides whether a question warrants calling the enterprise knowledge Q&A tool, and requires the skill to be read in full before any routing or tool call happens. It covers entry judgement, call boundaries, query construction, multi-turn inheritance, no-result fallbacks and how results may be used: a query must be a complete, independently understandable natural-language question, never a list of keywords, tags or nouns. One line separates the two cases — do you want an answer synthesised from internal material, or have you already identified a specific object to read, edit or operate? The latter goes to the matching object capability instead of search. It applies to searching, tracing, reviewing and summarising meetings, group chats, documents, calendars, projects and people, and to distilling conclusions, to-dos, risks, feedback or progress. When internal and public information mix, sources must be distinguished, and each question defaults to a single search call with internal sub-questions merged.

### ✨ What it does

- First separates "synthesise an answer from internal material" from "an identified object I need to read, edit or operate" — the latter skips search and uses the matching object capability
- Queries must be complete, standalone natural-language questions with no keyword, tag or noun lists, and multiple internal sub-questions merge into one call
- Covers search, tracing, review and summary across meetings, group chats, documents, calendars, projects and people, distilling conclusions, to-dos, risks, feedback and progress
- Every fact, figure, conclusion or paraphrase from a source gets an in-place citation, keeping source and material-entry links intact and migrating Markdown links verbatim
- When internal and public information mix, internal lookup completes before any object operation, and the two source types stay explicitly separated
- Empty or thin results never justify claiming a fact does not exist; public sources may fill the gap when the user has not excluded them, with the boundary clearly marked

### 📦 Skills included

- `enterprise-search` — [`enterprise-search/SKILL.md`](enterprise-search/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/enterprise-search.git
cp -r enterprise-search/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
