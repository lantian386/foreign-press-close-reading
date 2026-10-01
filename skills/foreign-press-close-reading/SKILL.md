---
name: foreign-press-close-reading
description: 外刊精读天团 —— 把英文外刊拆成"看得懂、学得会、记得住、考得到"的中文精读包。当用户要精读英文外刊或英文长文、做中英对照翻译、逐句拆解生词与长难句、分析段落论点与文章结构、画文章脉络思维导图、辨析熟词生义、提炼考点词汇与写作句型、命制仿真自测题，或要求 A4 打印版 / PDF 讲义 / 纸质卷子时使用。适用考研英语（一/二）、雅思、托福、四六级等备考场景，也适合泛读爱好者。Triggers 外刊精读、帮我读一篇外刊、经济学人精读、纽约时报文章、逐句拆解、长难句分析、生词整理、熟词生义、一词多义、思维导图、文章结构、考点词汇、写作句型、仿真出题、自测题、打印卷、A4、PDF讲义。
version: 1.0.0
---

# 外刊精读天团

把一篇英文外刊，拆成一份**可消化、可背诵、可提分**的中文精读包。

本技能用**五个专业视角**处理一篇文章：选刊定级 → 中英对照译导 → 逐句精读 → 考点提炼 → 汇编交付。你可以一次跑完整链路，也可以只做其中一环。

---

## 什么时候用

**完整链路**（默认，用户说"帮我读一篇外刊 / 做完整精读"）：
> 选刊 → 译导 → 精读 → 考点 → 交付精读包

**单点触发**（用户只提其中一项，就只做那一项，不要过度展开）：

| 用户想做的事 | 做什么 | 对应本文小节 |
|---|---|---|
| 推荐篇目、判断难度、适不适合某考试 | 选刊定级 | 附录「选刊定级」 |
| 翻译、导读、"先让我看懂大意" | 中英对照译导 | 附录「中英对照译导」 |
| 逐句讲、生词、长难句语法 | 逐句精读 | 附录「逐句精读」 |
| 画思维导图、梳理文章结构 | 文章脉络导图 | 附录「逐句精读」 |
| 熟词生义、一词多义、易误读词 | 熟词生义专项 | 附录「逐句精读」 |
| 高频词、写作句型、考点 | 考点提炼 | 附录「考点提炼与仿真出题」 |
| 出几道题、自测 | 仿真出题 | 附录「考点提炼与仿真出题」 |
| A4 打印、PDF、纸质卷子、带批注栏 | 打印卷交付 | 附录「交付物版式规范」 |

---

## 工作流（五阶段）

### 阶段 1 · 选刊定级
- **输入**：考试类型（考研/雅思/托福/四六级）、目标分数或水平、话题偏好。
- **产出**：来源 + 难度定级 + 字数 + 预计用时 + 阅读重点提示。
- **注意**：用户已粘贴原文时，**跳过选文**，只做难度定级 + 阅读策略，别浪费轮次。
- 详见 附录「选刊定级」。

### 阶段 2 · 中英对照译导
- **输入**：原文。
- **产出**：**逐段成对**的「英文原文 + 中文译文」（`[EN]` / `[ZH]` 标记）+ 一句话主旨 + 作者立场 + 背景补充 + 建议精读句。
- **硬要求**：英文原文照抄，不得改写或省略；每段英文后面**紧跟**对应中文，不允许把译文集中到文末。
- 详见 附录「中英对照译导」。

### 阶段 3 · 逐句精读
- **输入**：原文（必须基于原文，不能只基于译导产出）。
- **产出**：
  1. 生词：释义 / 音标 / 词性 / 搭配 / 真题联想
  2. 长难句：主干 / 从句 / 非谓语 / 插入语 / 倒装
  3. 段落功能：立论 / 举例 / 转折 / 让步 / 收束
  4. **文章脉络思维导图**：「主题 → 论点 → 论据/反驳 → 结论」三层结构
  5. **熟词生义表**：常见义 / 文中义 / 辨析 / 误读陷阱
- 详见 附录「逐句精读」。

### 阶段 4 · 考点提炼与仿真出题
- **输入**：阶段 2、3 的产出。
- **产出**：高频词分级表 + 固定搭配 + 写作可复用句型（框架 + 例句）+ 考试考点标注；按需命制 4 道左右仿真题。
- **出题铁律**：**答案不在题后**。题目区只给题干和选项，正确答案与解析统一放文末，便于先自测再对答案。
- 详见 附录「考点提炼与仿真出题」。

### 阶段 5 · 汇编交付
- **默认交付物**：**单文件 HTML 精读包** —— 内联 CSS、无外部依赖、可离线打开与打印。
- **按需交付物**：**A4 打印卷** —— 左栏中英对照正文 + 右栏批注栏，用户要求打印 / PDF / A4 / 纸质时产出。
- 两种交付物的完整版式规范见文末附录。

---

## 交付物

### A. HTML 精读包（默认）

七个模块，每模块一个专属色块的卡片，帮用户一眼定位：

| # | 模块 | 色 | 色值 |
|---|---|---|---|
| 1 | 选刊卡 · 为什么选这篇 | 靛紫 | `#6366F1` |
| 2 | 导读卡 · 中英对照 | 青 | `#06B6D4` |
| 3 | 精读卡 · 逐句拆解 | 琥珀 | `#F59E0B` |
| 4 | 逻辑思维导图 | 绿 | `#10B981` |
| 5 | 熟词生义 · 专项突破 | 玫红 | `#F43F5E` |
| 6 | 考点卡 · 提分清单 | 蓝 | `#3B82F6` |
| 7 | 复习建议 & 自测 | 紫 | `#8B5CF6` |

### B. A4 打印卷（用户要求打印时）

- 左栏：正文，每段「英文原文 → 紧跟中文译文」，长难句紧跟一张浅黄底分析卡。
- 右栏：批注栏，三类色条小卡 —— 生词（琥珀）/ 熟词生义（玫红）/ 谚语习语（绿）。
- 文末：文章脉络思维导图 → 仿真出题 → 答案与解析（另起页）。
- 段落组整块排版，**禁止跨页拆散**。

---

## 怎么生成交付物

本技能提供两条路径，**产出完全一致的成品**。优先用「路径一」——它不依赖任何运行环境，在任何 chat 客户端（含 Chatbox）都能用；有 Node 环境、想把文章先整理成结构化数据再批量生成时，再用「路径二」。

### 路径一：按模板直接产出 HTML（推荐，零依赖、跨平台）

本文末附录里给了**两份可直接套用的完整 HTML 骨架**（HTML 精读包 + A4 打印卷），CSS 已内联、带 `{{占位}}` 标记。直接把骨架复制到回复里，按注释把文章内容填进去，整段发回给用户即可；用户存成 `.html` 双击打开。

> 适用场景：Chatbox 等 chat 客户端（模型通常不能直接跑命令）、只想快速出一份、或字段不全只做部分模块。

### 路径二：用脚本批量生成（Node 用户）

（本单文件版未附带脚本，路径一已完全够用；若要脚本，请用完整多文件版里的 `scripts/build_sheet.mjs`——纯 Node 零依赖），读一份 JSON 就能吐出成品 HTML，适合把文章内容先整理成结构化数据再一键生成：

```bash
node scripts/build_sheet.mjs data.json out.html              # HTML 精读包
node scripts/build_sheet.mjs data.json out-print.html --print # A4 打印卷
```

JSON 结构见 附录「交付物版式规范」 与脚本头部注释。内容缺失的字段会被自动跳过，不会渲染空模块。

### 交付提示

无论哪条路径，交付时都告诉用户：**保存为 `.html` 用浏览器打开即可**；需要纸质版就 `Ctrl/Cmd + P` → 另存为 PDF（打印卷已内置 A4 分页规则）。

---

## 质量红线

1. **不编造原文**。只处理用户提供或明确指出的英文文本。不凭记忆复述《经济学人》等付费外刊全文，不虚构链接。
2. **英文原文照抄**。中英对照里的英文必须是原文，不改写、不省略、不重排。
3. **不裸输出纯文本长文**。用户要精读包时给 HTML，不要丢一大段无排版的 Markdown。
4. **答案与题目分离**。仿真题答案一律放文末，不要紧跟题干。
5. **熟词生义只收"认识但用错义"的词**，不收生僻词；每条必须给常见义 + 文中义 + 辨析。
6. **思维导图只给可视化版本**，不要让 mermaid 源码和渲染结果同时出现、造成重复。
7. **翻译是理解辅助**，不是权威译本；不确定的事实标"待核实"，不杜撰。
8. **难度判断要保守可解释**，宁可低估不高估用户水平。

---

---

# 附录 · 各阶段详细规范（原 references/ 内容已内联）
> 正文中提到的「附录」小节即以下内容，全部已内联，无需任何外部文件。

---

## 阶段 1 · 选刊定级

按考生的考试类型与水平，挑出难度匹配、话题高频的篇目，并给出阅读策略。

### 能力清单

1. **考试匹配**：熟悉考研（英语一/二）、雅思、托福、四六级的选材偏好、难度梯度与高频话题。
2. **难度定级**：依据字数、平均句长、词汇密度、长难句比例评估对应等级。
3. **来源甄选**：覆盖 The Economist、The New York Times、The Guardian、The Atlantic、Scientific American、BBC、Nature 等权威外刊。
4. **阅读策略**：给出先读哪段、抓什么、跳过什么的重点提示。

### 各考试选材偏好（速查）

| 考试 | 常见话题 | 文本特征 | 参考难度 |
|---|---|---|---|
| 考研英语一 | 社科、经济、科技、教育、传媒 | 长难句密集、抽象论证、态度含蓄 | C1 |
| 考研英语二 | 商业、管理、职场、消费 | 结构清晰、数据较多 | B2–C1 |
| 雅思 Academic | 科普、环境、社会、教育 | 说明文为主、术语较多 | B2–C1 |
| 托福 | 生物、地质、天文、历史、艺术 | 学术性强、因果链复杂 | C1 |
| 四六级 | 校园、生活、科技、文化 | 篇幅较短、句式较简单 | B1–B2 |

### 工作流程

1. 确认考试类型、目标水平 / 分数、话题偏好（科技 / 社会 / 经济 / 环境等）。
2. 推荐 1–3 篇候选，说明来源、难度、字数、预计用时、主题词，并注明**为什么适合该考试**。
3. 用户选定后，输出「选刊卡」并给出阅读顺序与重点。
4. **若用户已粘贴原文**：跳过选文，直接定级 + 给阅读策略。

### 数据获取

- 优先使用用户粘贴的原文或链接文本。
- 若用户只给主题，推荐具体篇目并**请用户粘贴对应段落** —— 不在线抓取付费外刊全文，不虚构链接。

### 输出模板（选刊卡）

```
【选刊卡】
来源：<刊物名 / 栏目>
难度：<等级 + 对应考试>
字数：<约 xxx 词>　预计用时：<xx 分钟>
主题词：<3-5 个>
为什么适合：<一句话说明与目标考试的匹配点>
阅读重点：<先读结论段 / 抓数据 / 注意态度词 等>
```

### 注意事项

- 难度判断要**保守、可解释**，避免高估用户水平。
- 同一考试不连续重复同一话题，保证覆盖面。
- 不编造不存在的文章链接。

---

## 阶段 2 · 中英对照译导

把外刊原文翻译成地道中文，并先帮用户看懂大意、理清主旨与背景。

### 能力清单

1. **中英对照翻译**：逐段给出「英文原文 + 中文译文」成对呈现，保留英文原句便于回看与背诵。以「信达雅」为尺度，重语意流畅而非字对字硬翻，保留原文语气与修辞。
2. **主旨概括**：用一段话提炼中英文主旨，点明作者立场。
3. **背景补充**：补充相关文化背景、历史事件、争议点或专有名词。
4. **难句预提示**：圈出后续精读的高难句，但**不在此展开语法**。

### 工作流程

1. 接收原文。
2. 通读，标记结构（导语 / 论点 / 论据 / 结论）。
3. 逐段做中英对照翻译：**每段先英文原文、后中文译文**。难词在译文后括注中文释义（音标留给精读阶段）。
4. 写一段式中英文主旨 + 背景补充。
5. 圈出 2–3 个建议精读的高难句。

### 输出模板（导读卡）

```
【导读卡】
◇ 中英对照译文
  [EN] <英文原文段落 1>
  [ZH] <对应中文译文 1>
  [EN] <英文原文段落 2>
  [ZH] <对应中文译文 2>
  （逐段成对，长段可拆分为多组，段数不限）
◇ 中英主旨：<一句话>
◇ 作者立场：<中立 / 支持 / 批判 …>
◇ 背景补充：<2-3 条>
◇ 建议精读句：<引用原句>
```

### 硬性要求

- **必须逐段成对**给出英文原文与中文译文，缺一不可。
- **英文原文照抄**，不得改写、省略或重排。
- 以 `[EN]` / `[ZH]` 标记成对，便于后续逐段嵌入 HTML 的青色对照色块。
- 专有名词首次出现时括注原文。

### 翻译尺度（几个判断原则）

| 情况 | 处理 |
|---|---|
| 长句含多重从句 | 按中文习惯拆成 2–3 个短句，不要硬凑一句话 |
| 被动语态 | 视语境转主动，中文更自然 |
| 抽象名词堆叠 | 补出隐含的施动者，必要时加"（即…）"轻解释 |
| 作者的反讽 / 保留语气 | 保留，可加引号或"所谓…"提示 |
| 文化专有项 | 首现给原文 + 一句背景，不硬译 |
| 术语 | 用通行译名，首现标英文原词 |

### 注意事项

- 翻译先于精读，目的是「看懂」，此处不逐词讲语法。
- 保持客观，不替作者下价值判断。
- 背景知识来自通用常识；不确定的事实标注「待核实」，不杜撰。

---

## 阶段 3 · 逐句精读

基于原文做逐句拆解：生词、长难句语法、段落论点结构，产出可背诵的精读笔记，并附**文章脉络思维导图**与**熟词生义专项表**。

### 能力清单

1. **逐句生词**：释义、音标、词性、常见搭配、真题联想。
2. **长难句拆解**：划分主干 / 修饰，标注从句、非谓语、插入语、倒装。
3. **论点结构**：还原段落的「观点—论据—结论」逻辑链与全文脉络。
4. **文章脉络思维导图**：可视化全文骨架，一眼看清结构。
5. **熟词生义**：揪出「以为认识、其实用错义」的词，标注文中义 vs 常见义并给辨析。
6. **可背诵化**：输出结构化、便于记忆与复述的笔记。

### 工作流程

1. 接收原文（可参考导读卡，但**必须基于原文逐句做**）。
2. 逐段拆解：先给生词，再拆长难句；遇到熟词生义即时标注。
3. 每段结尾用 1 句话概括该段功能（立论 / 举例 / 转折 / 让步 / 收束）。
4. 全文结尾还原「论点结构」总览，并输出思维导图的嵌套结构。
5. 整理「熟词生义」专项表。

---

### 长难句拆解法

用「**主干 + 修饰**」二分法，清晰优先。

1. **找主干**：先剥掉所有修饰，定位主语、谓语、宾语（或表语）。
2. **挂修饰**：把剩下的成分归位 —— 定语从句修饰哪个名词、状语修饰哪个动词、非谓语做什么成分。
3. **标连接**：并列词、从属连词、关系词，说明逻辑关系（因果 / 让步 / 转折 / 条件）。
4. **说人话**：最后用一句中文把这句话的意思顺下来。

常见难点速查：

| 结构 | 识别信号 | 拆解要点 |
|---|---|---|
| 定语从句 | which / that / who / whose / where | 找准先行词，注意从句可能很长 |
| 状语从句 | although / while / since / if | 先拎出来放一边，主干就清楚了 |
| 非谓语 | -ing / -ed / to do 开头或跟在名词后 | 判断作定语还是状语 |
| 插入语 | 两个逗号 / 破折号夹住 | 先跳过，读通主干再回填 |
| 倒装 | 否定词提前 / only 开头 | 还原正常语序 |
| 省略 | 并列结构中重复成分省掉 | 补全后再理解 |

---

### 文章脉络思维导图

三层结构，**只给可视化版本**（不要同时输出 mermaid 源码，避免重复）。

```
主题
├── 核心论点一
│   ├── 论据 / 案例
│   └── 限定 / 反驳
├── 核心论点二
│   └── 论据 / 案例
└── 结论与启示
```

规则：
- 覆盖全文主干，分支**不超过三层**。
- 节点用**短语**，不要用长句。
- 根节点是文章主题（不是标题的照抄，要提炼）。

---

### 熟词生义专项

只收「**认识但易用错义**」的词，不收生僻词。每条必须给三件套：

| 字段 | 说明 |
|---|---|
| 常见义 | 用户第一反应的义项 |
| 文中义 | 该词在本篇语境下的实际含义，给出同义替换 |
| 辨析 | 为什么容易误读，句中什么信号提示了正确义项 |

**误读陷阱类型**（标注时选一个）：
- 词性误判（名词当动词读）
- 义项误选（多义词选错义）
- 搭配混淆（固定搭配里词义变了）
- 同义替换误判（阅读题常见失分点）

**常见高频熟词生义示例**（供参考，实际以文章为准）：

| 词 | 常见义 | 文中常义 |
|---|---|---|
| address | 地址；致辞 | 处理、应对（v.） |
| appreciate | 感激 | 意识到、理解 |
| argue | 争论 | 主张、论证 |
| capital | 首都；资本 | 主要的、极好的（adj.） |
| discipline | 纪律 | 学科（n.） |
| figure | 数字 | 认为、断定（v.） |
| issue | 问题 | 发布、发行（v.） |
| just | 仅仅 | 公正的（adj.） |
| last | 最后的 | 持续（v.） |
| mean | 意思是 | 平均的；吝啬的 |
| observe | 观察 | 评论、指出 |
| practice | 练习 | 惯例、做法 |
| reserve | 预订 | 保留意见（n.） |
| sanction | 制裁 | 批准、许可（v.） |
| sound | 声音 | 合理的、可靠的（adj.） |
| subject | 科目 | 使遭受（v.） |
| tell | 告诉 | 分辨、区分 |

---

### 输出模板

```
【精读卡 · 第 N 段】
原句：<英文>
★ 生词：word /wɜːd/ n. 词；搭配：~ sth. up
★ 长难句：主干 = …；修饰 = 定语从句(…) / 非谓语(…)
★ 熟词生义：address 常见义「地址；致辞」→ 文中义「处理 / 应对」(v.)，易误读
★ 段落功能：<立论 / 举例 / 转折 / 收束>

【全文论点结构】
引子 → 观点A(论据) → 反驳B → 结论

【思维导图】
root((文章主题))
  核心论点一
    论据 / 案例
    限定 / 反驳
  核心论点二
    论据 / 案例
  结论与启示

【熟词生义 · 专项突破】
1. address /əˈdres/ v.
   常见义：地址；向…致辞
   文中义：处理、应对（= deal with / tackle）
   辨析：文中作及物动词接 problem / issue，极易误读为「地址」或「发表演讲」
2. <更多词按此格式逐条列出，按误读风险排序>
```

### 注意事项

- **必须基于原文**，不臆测未出现的语义。
- 每句只拆**必要结构**，避免过度语法堆砌。
- 生词标注在**首次出现处**，重复词不重复列。
- 释义以权威词典义项为准；多义词结合语境择义。
- 思维导图只给可视化版本，不要附带 mermaid 源码。

---

## 阶段 4 · 考点提炼与仿真出题

从译文与精读产出中，提炼高频 / 核心词汇、固定搭配、写作可复用句型，关联考试考点，并命制仿真自测题。

### 能力清单

1. **词汇分级**：区分高频核心词、写作加分词、仅需识记的词。
2. **搭配提炼**：提取地道固定搭配与介词用法。
3. **句型复用**：归纳可用于写作（尤其雅思 / 考研）的句式框架。
4. **考点映射**：关联阅读同义替换、写作语料、翻译要点等考试维度。
5. **熟词生义联动**：承接熟词生义表，标注考试陷阱（同义替换误判、写作误用、阅读曲解）。
6. **仿真出题**：按目标考试题型命制 4 题左右自测题，附答案与解析。

### 工作流程

1. 接收导读卡 + 精读卡。
2. 抽取词汇表（按考试分级），给音标 / 释义 / 搭配；熟词生义单列进高频易错清单。
3. 归纳 3–5 个写作可复用句型，给「框架 + 原文例句 + 仿写示例」。
4. 标注每个词 / 句对应的考试考点。
5. 按需命制仿真自测题，单独产出「答案与解析」。

---

### 词汇分级标准

| 级别 | 判定 | 处理 |
|---|---|---|
| **核心高频** | 真题复现率高、多义项 | 必须掌握：音标 + 义项 + 搭配 |
| **写作加分** | 书面语、替换基础词更出彩 | 给搭配与例句，鼓励用进作文 |
| **识记即可** | 专业术语、低频词 | 只给释义，不要求拼写 |
| **易错熟词** | 熟悉但易用错义 | 单列，给辨析与陷阱类型 |

### 写作句型提炼要求

每个句型给**三件套**：

```
框架：Not only does A …, but B also …
原文例句：<从本文摘一句>
仿写示例：<换一个话题写一句，示范怎么套>
```

优先提炼这些高分结构：
- 倒装（Not only… but also / Only when…）
- 强调句（It is … that …）
- 让步（While it is true that …, …）
- 虚拟（Were it not for …, …）
- 分词状语（Faced with …, …）
- 名词化（The proliferation of … has …）

### 仿真出题规范

**题型配比**（按目标考试选 4 题左右）：

| 题型 | 常见问法 |
|---|---|
| 词义猜测 | The word "X" is closest in meaning to… |
| 细节理解 | According to Paragraph N, … |
| 推理判断 | It can be inferred from the passage that… |
| 作者态度 | The author's attitude towards X is… |
| 主旨大意 | The passage mainly discusses… |

**硬性规则**：

1. **题干用英文**，选项 A–D 用英文；四个选项**长度与难度相当**。
2. 干扰项必须「**像但对**」—— 用文中真实出现但答非所问的词、或半对的表述；不要凑明显错误项。
3. **答案与解析分开**：题目区只给题号和选项，**正确答案统一放文末「答案与解析」区**，便于先自测再对答案。
4. **解析用中文**，必须写明：正确项依据（回指原文具体位置）+ 每个干扰项错在哪里。
5. 每题标注对应考点（如：考点：词义猜测 · 同义替换）。

---

### 输出模板（考点卡）

```
【考点卡】
◆ 高频 / 核心词（分级）
  core /kɔːr/ adj. 核心的 — 搭配：core issue｜考点：写作高频
◆ 固定搭配
  shed light on sth. 阐明…｜考点：阅读同义替换 illuminate
◆ 写作可复用句型
  [Not only does A …, but B also …]
  原文例句：…
  仿写示例：…
◆ 易错熟词（联动熟词生义）
  address 常见义「地址」→ 文中义「处理」｜陷阱：词性误判
◆ 自测：用今天词汇写 1 句 / 找出文中同义替换
```

### 注意事项

- 不堆砌生僻词，重「**高频 + 可复用**」。
- 句型必须给出可套用的框架，而非孤立好句。
- 考点标注具体到考试（考研 / 雅思 / 托福 / 四六级）。
- 输出为**结构化条目**（词 / 搭配 / 句型 / 考点各成一段），便于嵌入 HTML 的蓝色词条卡与左边框引用块。

---

## 阶段 5 · 交付物版式规范

最终交付物有两种：**HTML 精读包**（默认）与 **A4 打印卷**（用户要求打印时）。两者同源不同版式 —— HTML 重屏幕阅读，打印卷重纸面排版。

**两条产出路径（二选一，成品一致）：**
- **路径一 · 按骨架手写**（推荐，零依赖）：直接复制本文末尾的「§A HTML 精读包骨架」「§B A4 打印卷骨架」，把 `{{占位}}` 换成内容即可。适合 chat 客户端（模型不能直接跑命令）与字段不全的局部精读。
- **路径二 · 用脚本生成**（Node 用户）：把文章整理成 JSON，跑 `scripts/build_sheet.mjs`。样式统一、分页规则正确，缺失字段自动跳过。

下面先给视觉规范与 JSON 结构，末尾给可直接套用的完整 HTML 骨架。

---

## 一、HTML 精读包

### 视觉规范（丰富色块）

- **单一容器**：`max-width:900px` 居中；页面背景柔和渐变（靛紫 → 浅紫）。
- **封面 Hero**：渐变条（靛紫 → 紫 → 玫红），白字，含文章标题 + 来源/难度/适用考试/字数 四枚半透明胶囊徽章。
- **模块卡片**：每节一张白底圆角卡（圆角 18px、柔和投影），卡头为**该模块专属色**的实色横条 + 序号圆角标 + 标题。

| # | 模块 | 色 | 色值 |
|---|---|---|---|
| 1 | 选刊卡 · 为什么选这篇 | 靛紫 | `#6366F1` |
| 2 | 导读卡 · 中英对照 | 青 | `#06B6D4` |
| 3 | 精读卡 · 逐句拆解 | 琥珀 | `#F59E0B` |
| 4 | 逻辑思维导图 | 绿 | `#10B981` |
| 5 | 熟词生义 · 专项突破 | 玫红 | `#F43F5E` |
| 6 | 考点卡 · 提分清单 | 蓝 | `#3B82F6` |
| 7 | 复习建议 & 自测 | 紫 | `#8B5CF6` |

**色块微元件**：
- 中英对照段（`.bi`）：左边框青色，上排英文（Georgia 衬线体、带编号徽章），下排中文（虚线分隔）。
- 生词用琥珀色胶囊 chip；熟词生义用玫红描边三栏卡（常见义/文中义/辨析）；考点词用蓝色词条卡；写作句型用蓝色左边框引用块；思维导图用绿系嵌套节点（根节点渐变实色 / L1 浅绿底 / L2 虚线浅绿）。

### JSON 数据结构（`build_sheet.mjs` 输入）

```json
{
  "title": "英文原标题",
  "titleZh": "中文译题",
  "meta": {
    "source": "The Economist",
    "level": "C1 · 考研英语一",
    "exams": "考研 / 雅思",
    "words": "约 420 词"
  },
  "curation": {
    "why": "为什么适合该考试的说明",
    "points": ["阅读重点 1", "阅读重点 2"]
  },
  "paragraphs": [
    {
      "en": "English paragraph text …",
      "zh": "对应中文译文 …",
      "grammar": "主干 = …；修饰 = 定语从句(…)（可选，有则渲染长难句卡）",
      "annotations": [
        { "type": "word",  "text": "trial /ˈtraɪəl/ n. 试验" },
        { "type": "poly",  "text": "address 常见义「地址」→ 文中义「处理」" },
        { "type": "idiom", "text": "level the playing field 拉平起跑线" }
      ]
    }
  ],
  "guide": {
    "summary": "一句话主旨",
    "stance": "作者立场",
    "background": ["背景 1", "背景 2"],
    "focus": ["建议精读句"]
  },
  "mindmap": {
    "root": "文章主题",
    "branches": [
      { "node": "核心论点一", "children": ["论据 / 案例", "限定 / 反驳"] }
    ]
  },
  "polysemy": [
    { "word": "address", "common": "地址；致辞", "inText": "处理、应对", "note": "作及物动词接 problem，易误读" }
  ],
  "vocab": [
    { "word": "core", "phonetic": "/kɔːr/", "pos": "adj.", "meaning": "核心的", "collocation": "core issue", "exam": "写作高频" }
  ],
  "collocations": [
    { "phrase": "shed light on", "meaning": "阐明", "exam": "同义替换 illuminate" }
  ],
  "patterns": [
    { "frame": "Not only does A …, but B also …", "example": "原文例句", "imitation": "仿写示例" }
  ],
  "quiz": [
    { "q": "The word \"trial\" is closest in meaning to…", "options": ["A 选项", "B 选项", "C 选项", "D 选项"], "point": "词义猜测 · 同义替换" }
  ],
  "answers": [
    { "no": 1, "ans": "B", "why": "依据见第 2 段 …", "distractors": "A 项错在 …；C 项错在 …" }
  ],
  "review": ["复习建议 1", "复习建议 2"]
}
```

**字段可缺失**。`build_sheet.mjs` 会跳过没有内容的模块，不会渲染空卡片。

### 生成

```bash
node scripts/build_sheet.mjs data.json reading-package.html
```

---

## 二、A4 打印卷

面向纸质打印的第二交付物。与 HTML 内容同源，版式重排为「左正文 + 右批注」的讲义式卷面。

> **为什么是 HTML 而不是直接生成 PDF**：Chatbox 的沙箱是 Node.js / Bash 环境，不带 Python 科学栈，无法运行 PDF 排版引擎。改用**打印优化的 HTML**（内置 A4 `@page` 规则）—— 用户在浏览器 `Ctrl/Cmd + P` → 「另存为 PDF」即可得到 A4 PDF，效果等同，且跨平台可用、所见即所得。

### 页面与分栏（A4 = 210 × 297 mm）

- **页边距**：12mm。
- **双栏**：左栏正文（约 62% 宽）+ 右栏批注（约 34% 宽），中间留 4% 栏间距。
- **页眉**：`外刊精读天团 · 打印版 · 中英对照精读卷`（细线 + 小字灰）。
- **关键约束**：一个段落组（英文 + 译文 + 长难句卡 + 右侧批注）**整块排版、禁止跨页拆散**（`page-break-inside: avoid`）。

### 字体与字号

| 用途 | 字体 | 字号 |
|---|---|---|
| 英文正文 | 衬线体（Georgia / Times New Roman 回退） | 9.4pt / 行高 1.55 |
| 中文译文 | 黑体（PingFang SC / Noto Sans CJK / 微软雅黑） | 8.8pt / 行高 1.6 |
| 右栏批注 | 同正文 | 7.8pt |
| 英文标题 | 衬线体加粗 | 18pt，居中 |
| 中文译题 | 黑体 | 12pt，居中 |

### 内容结构（自上而下）

1. **标题区（通栏居中）**：英文原标题 → 中文译题 → 细分隔线 → 元信息（来源 / 难度 / 词数 / 适用考试）→ 左右栏目标记（`正文 · 中英对照` / `批注栏`）。
2. **正文区（左栏，逐段）**：
   - `¶ N` 段号 → **英文原文**（衬线体，深色）→ **紧跟中文译文**（黑体，灰色，缩进）。
   - 段落中若有长难句，紧跟一张**长难句卡**：浅黄底 `#FFF7E8` + 左侧竖色条，标题「长难句」，写主干 / 从句 / 插入语分析。
3. **批注区（右栏，按段对应）**：三类小卡，左侧竖色条 + 灰底 `#F8FAFC`：
   - **生词**（琥珀 `#B45309`）：`word /音标/ 词性 释义`
   - **熟词生义**（玫红 `#BE185D`）：`word 常见义 → 文中义`（必须给辨析与误读陷阱）
   - **谚语 / 习语 / 搭配**（绿 `#15803D`）：原文 + 释义 + 用法提示
4. **文章脉络 · 思维导图（通栏，另起页）**：靛紫主题色，缩进树形 —— 根节点加量，一级 `●`、二级 `○`，层级缩进。
5. **仿真出题 · 自测（通栏）**：蓝色主题，4 题左右，题干英文、四选项 A–D，**答案不在题后**。
6. **答案与解析（通栏，另起页）**：绿色主题，`1. B` + 解析（中文，讲清干扰项为什么错）。

### 生成

```bash
node scripts/build_sheet.mjs data.json print-sheet.html --print
```

生成后**必须自检**（沙箱内无法目视，用几何检查代替）：

1. 确认 HTML 结构完整（标签闭合、无未替换的占位符）。
2. 确认中文字符正常（无乱码、无 `□`）。
3. 确认所有段落组都带 `page-break-inside: avoid`。
4. 若环境有 Chromium / Puppeteer，可选做一次 PDF 快照核对；没有就依赖打印预览。

---

## 三、交付话术

生成后告诉用户：

> 已生成精读包 HTML，**保存为 `.html` 用浏览器打开**即可阅读。
> 需要纸质版：打开后按 `Ctrl/Cmd + P`，目标选「另存为 PDF」，纸张 A4，边距选「无」或「默认」，即可得到打印卷。

---

## 附录 · 可直接套用的完整 HTML 骨架

下面两份骨架 CSS 已内联、自带配色与分页规则。**复制整段到回复里，把 `{{占位}}` 换成你的内容，删掉用不到的模块，整段发回给用户**。用户存成 `.html` 双击即看。骨架与 `scripts/build_sheet.mjs` 的产出完全一致。

### §A HTML 精读包骨架

```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>外刊精读包 · {{英文标题}}</title>
<style>
:root{--bg1:#eef1f8;--bg2:#f7f3fb;--ink:#1f2430;--muted:#6b7280;
 --curator:#6366f1;--guide:#06b6d4;--read:#f59e0b;--map:#10b981;
 --poly:#f43f5e;--exam:#3b82f6;--review:#8b5cf6;--radius:18px;--shadow:0 8px 30px rgba(20,30,60,.10)}
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:-apple-system,"PingFang SC","Microsoft YaHei",Segoe UI,Roboto,sans-serif;background:linear-gradient(160deg,var(--bg1),var(--bg2));color:var(--ink);line-height:1.7;padding:28px 16px 60px}
.wrap{max-width:900px;margin:0 auto}
.hero{background:linear-gradient(135deg,#6366f1,#8b5cf6 55%,#f43f5e);border-radius:24px;padding:30px 32px;color:#fff;box-shadow:var(--shadow)}
.hero h1{font-size:26px;margin:10px 0 0;letter-spacing:.5px}
.hero .zh-title{font-size:16px;opacity:.92;margin-top:6px}
.hero .meta{display:flex;flex-wrap:wrap;gap:8px;margin-top:14px}
.badge{background:rgba(255,255,255,.18);padding:5px 12px;border-radius:999px;font-size:13px}
.card{background:#fff;border-radius:var(--radius);box-shadow:var(--shadow);margin-top:22px;overflow:hidden}
.card>.head{display:flex;align-items:center;gap:12px;padding:16px 22px;color:#fff;font-weight:700;font-size:18px}
.card>.head .num{width:30px;height:30px;border-radius:10px;background:rgba(255,255,255,.25);display:flex;align-items:center;justify-content:center;font-size:15px}
.card .body{padding:20px 24px}
.c-curator .head{background:var(--curator)}.c-guide .head{background:var(--guide)}.c-read .head{background:var(--read)}
.c-map .head{background:var(--map)}.c-poly .head{background:var(--poly)}.c-exam .head{background:var(--exam)}.c-review .head{background:var(--review)}
.bullets{margin:10px 0 0 20px}.bullets li{margin:6px 0}
.bi{border-left:4px solid var(--guide);background:#f0fdfa;border-radius:0 14px 14px 0;padding:12px 16px;margin:14px 0}
.bi .en{color:#0f766e;font-size:15px;line-height:1.65;font-family:Georgia,"Times New Roman",serif}
.bi .zh{color:#134e4a;font-size:15px;line-height:1.8;margin-top:8px;padding-top:8px;border-top:1px dashed #99f6e4}
.idx{display:inline-block;background:var(--guide);color:#fff;font-size:12px;font-weight:700;border-radius:8px;padding:1px 8px;margin-right:8px;vertical-align:2px}
.guide-meta{margin-top:18px;padding-top:14px;border-top:1px solid #e5e7eb}.guide-meta p{margin:6px 0}
.para{border-left:4px solid var(--read);background:#fffaf0;border-radius:0 14px 14px 0;padding:14px 18px;margin:14px 0}
.para .en{font-style:italic;color:#374151;margin-bottom:8px;font-family:Georgia,"Times New Roman",serif}
.chips{margin:8px 0}.chip{display:inline-block;background:#fff3e0;color:#b45309;border:1px solid #fcd9a6;border-radius:999px;padding:2px 10px;margin:3px 4px 3px 0;font-size:13px}
.grammar{margin-top:8px;background:#fff7e8;border-left:3px solid #f59e0b;border-radius:0 10px 10px 0;padding:8px 12px;font-size:14px;color:#7c4a03}.grammar b{color:#b45309;margin-right:8px}
.fn{display:inline-block;margin-top:8px;font-size:13px;color:#92400e;background:#fef3c7;border-radius:6px;padding:2px 10px}
.mindmap{padding:6px 0}.mm-root{display:inline-block;background:linear-gradient(135deg,var(--map),#34d399);color:#fff;font-weight:700;padding:10px 22px;border-radius:14px;box-shadow:var(--shadow)}
.mm-lvl1{margin:14px 0 0 26px;border-left:3px solid var(--map);padding-left:16px}
.mm-lvl1>.node{display:inline-block;background:#ecfdf5;color:#047857;font-weight:600;padding:8px 16px;border-radius:12px;border:1px solid #a7f3d0;margin:8px 0}
.mm-lvl2{margin:6px 0 6px 28px;border-left:3px dashed #6ee7b7;padding-left:14px}
.mm-lvl2>.node{display:inline-block;background:#f0fdf9;color:#065f46;padding:6px 14px;border-radius:10px;border:1px solid #bbf7e1;font-size:14px}
.poly{border:1px solid #fecdd3;background:#fff1f2;border-radius:14px;padding:14px 18px;margin:12px 0}
.poly .w{font-weight:700;color:#be123c;font-size:16px}.poly .row{display:flex;gap:10px;margin-top:6px;flex-wrap:wrap}
.poly .tag{flex:1;min-width:160px;background:#fff;border-radius:10px;padding:8px 12px;font-size:14px}.poly .tag b{color:#9f1239;display:block;margin-bottom:2px}
h4{margin:16px 0 8px;color:#1e3a8a;font-size:15px}h4:first-child{margin-top:0}
.kw{display:flex;gap:12px;align-items:flex-start;background:#f5f9ff;border:1px solid #dbeafe;border-radius:12px;padding:12px 16px;margin:10px 0}
.kw .k{font-weight:700;color:#1d4ed8;min-width:140px}.kw s{text-decoration:none;font-weight:400;color:#60a5fa}
.exam-tag{background:#dbeafe;color:#1e40af;border-radius:6px;padding:1px 8px;font-size:12px}
.pattern{background:#eef4ff;border-left:4px solid var(--exam);border-radius:0 12px 12px 0;padding:12px 16px;margin:10px 0}
.pattern .ex{font-size:14px;color:#334155;margin-top:4px}
.review li{margin:8px 0 8px 4px;list-style:none;padding-left:26px;position:relative}.review li:before{content:"★";position:absolute;left:0;color:var(--review)}
footer{text-align:center;color:var(--muted);font-size:13px;margin-top:30px}
</style>
</head>
<body>
<div class="wrap">
  <div class="hero">
    <div class="badge">外刊精读天团</div>
    <h1>{{英文标题}}</h1>
    <div class="zh-title">{{中文译题}}</div>
    <div class="meta">
      <span class="badge">来源：{{source}}</span>
      <span class="badge">难度：{{level}}</span>
      <span class="badge">适用：{{exams}}</span>
      <span class="badge">字数：{{words}}</span>
    </div>
  </div>

  <!-- ① 选刊卡（无则整段删） -->
  <section class="card c-curator">
    <div class="head"><span class="num">1</span> 选刊卡 · 为什么选这篇</div>
    <div class="body">
      <p>{{为什么适合该考试}}</p>
      <ul class="bullets"><li>{{阅读重点 1}}</li><li>{{阅读重点 2}}</li></ul>
    </div>
  </section>

  <!-- ② 导读卡：每段复制一个 .bi 块 -->
  <section class="card c-guide">
    <div class="head"><span class="num">2</span> 导读卡 · 中英对照</div>
    <div class="body">
      <div class="bi"><div class="en"><span class="idx">1</span>{{英文段 1}}</div><div class="zh">{{中文段 1}}</div></div>
      <div class="bi"><div class="en"><span class="idx">2</span>{{英文段 2}}</div><div class="zh">{{中文段 2}}</div></div>
      <div class="guide-meta">
        <p><b>一句话主旨：</b>{{summary}}</p>
        <p><b>作者立场：</b>{{stance}}</p>
      </div>
    </div>
  </section>

  <!-- ③ 精读卡：每段复制一个 .para -->
  <section class="card c-read">
    <div class="head"><span class="num">3</span> 精读卡 · 逐句拆解</div>
    <div class="body">
      <div class="para">
        <div class="en"><span class="idx">1</span>{{英文段 1}}</div>
        <div class="chips"><span class="chip">{{生词1}}</span><span class="chip">{{生词2}}</span></div>
        <div class="grammar"><b>长难句</b>{{主干/从句/非谓语分析}}</div>
        <span class="fn">段落功能：{{立论/举例/转折/收束}}</span>
      </div>
    </div>
  </section>

  <!-- ④ 思维导图 -->
  <section class="card c-map">
    <div class="head"><span class="num">4</span> 逻辑思维导图</div>
    <div class="body mindmap">
      <span class="mm-root">{{主题}}</span>
      <div class="mm-lvl1"><span class="node">{{核心论点 1}}</span>
        <div class="mm-lvl2"><span class="node">{{论据/案例}}</span></div>
        <div class="mm-lvl2"><span class="node">{{限定/反驳}}</span></div>
      </div>
      <div class="mm-lvl1"><span class="node">{{核心论点 2}}</span>
        <div class="mm-lvl2"><span class="node">{{论据/案例}}</span></div>
      </div>
    </div>
  </section>

  <!-- ⑤ 熟词生义 -->
  <section class="card c-poly">
    <div class="head"><span class="num">5</span> 熟词生义 · 专项突破</div>
    <div class="body">
      <div class="poly"><div class="w">{{word}}</div>
        <div class="row">
          <div class="tag"><b>常见义</b>{{common}}</div>
          <div class="tag"><b>文中义</b>{{inText}}</div>
          <div class="tag"><b>辨析</b>{{note}}</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ⑥ 考点卡 -->
  <section class="card c-exam">
    <div class="head"><span class="num">6</span> 考点卡 · 提分清单</div>
    <div class="body">
      <h4>高频 / 核心词</h4>
      <div class="kw"><span class="k">{{word}} <s>{{phonetic}}</s> {{pos}}</span><span>{{meaning}}　搭配：{{collocation}}</span></div>
      <h4>写作可复用句型</h4>
      <div class="pattern"><b>{{frame}}</b><div class="ex">原文例句：{{example}}</div><div class="ex">仿写示例：{{imitation}}</div></div>
    </div>
  </section>

  <!-- ⑦ 复习建议 -->
  <section class="card c-review">
    <div class="head"><span class="num">7</span> 复习建议 & 自测</div>
    <div class="body"><ul class="review"><li>{{建议 1}}</li><li>{{建议 2}}</li></ul></div>
  </section>

  <footer>由「外刊精读天团」生成 · 可离线打开 / 打印</footer>
</div>
</body>
</html>
```

### §B A4 打印卷骨架

```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<title>外刊精读打印卷 · {{英文标题}}</title>
<style>
@page { size: A4; margin: 12mm; }
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:-apple-system,"PingFang SC","Microsoft YaHei","Noto Sans CJK SC",sans-serif;color:#1f2430;background:#fff;line-height:1.65;font-size:9.4pt;-webkit-print-color-adjust:exact;print-color-adjust:exact}
.sheet{max-width:186mm;margin:0 auto;padding:6mm 0}
.title-block{text-align:center;border-bottom:1.4pt solid #c7d2fe;padding-bottom:8px;margin-bottom:4px}
.title-en{font-family:Georgia,"Times New Roman",serif;font-size:18pt;font-weight:700;color:#312e81;line-height:1.3}
.title-zh{font-size:12pt;color:#4338ca;margin-top:4px}
.title-meta{font-size:8.4pt;color:#6b7280;margin-top:6px}
.col-label{display:flex;justify-content:space-between;font-size:7.6pt;color:#94a3b8;margin:6px 0 8px;padding-bottom:3px;border-bottom:.6pt dashed #e2e8f0}
.group{display:grid;grid-template-columns:62% 34%;gap:4%;page-break-inside:avoid;break-inside:avoid;margin-bottom:11px;padding-bottom:9px;border-bottom:.6pt solid #f1f5f9}
.pno{font-size:7.4pt;font-weight:700;color:#b45309;margin-bottom:3px}
.en{font-family:Georgia,"Times New Roman",serif;font-size:9.4pt;line-height:1.55;color:#1f2937}
.zh{font-size:8.8pt;line-height:1.6;color:#4b5563;margin-top:4px;padding-left:8px;border-left:2pt solid #e5e7eb}
.grammar{margin-top:6px;background:#FFF7E8;border-left:2.6pt solid #f59e0b;border-radius:0 6px 6px 0;padding:6px 9px;font-size:8pt;color:#7c4a03}.grammar b{color:#b45309;margin-right:6px}
.right{display:flex;flex-direction:column;gap:6px}
.note{background:#F8FAFC;border-left:2.6pt solid #cbd5e1;border-radius:0 6px 6px 0;padding:5px 8px;font-size:7.8pt;line-height:1.5;color:#334155}.note .n-tag{display:block;font-size:7pt;font-weight:700;margin-bottom:1px}
.n-word{border-left-color:#f59e0b}.n-word .n-tag{color:#B45309}
.n-poly{border-left-color:#f43f5e}.n-poly .n-tag{color:#BE185D}
.n-idiom{border-left-color:#22c55e}.n-idiom .n-tag{color:#15803D}
.note-empty{font-size:7.4pt;color:#cbd5e1}
.page-break{page-break-before:always;break-before:page}
.sec{font-size:12pt;font-weight:700;text-align:center;padding:6px 0;border-radius:8px;margin:0 0 12px;color:#fff}
.sec-map{background:#6366f1}.sec-quiz{background:#3b82f6}.sec-ans{background:#10b981}
.mm-root{display:inline-block;background:#6366f1;color:#fff;font-weight:700;font-size:10.4pt;padding:6px 16px;border-radius:8px;margin-bottom:10px}
.mm1{font-size:9.4pt;font-weight:600;color:#4338ca;margin:8px 0 0 20px}.mm2{font-size:8.6pt;color:#475569;margin:4px 0 0 40px}
.q{margin-bottom:12px;page-break-inside:avoid;break-inside:avoid}.qt{font-family:Georgia,"Times New Roman",serif;font-size:9.4pt;color:#1f2937;margin-bottom:5px}
.opt{font-family:Georgia,"Times New Roman",serif;font-size:8.8pt;color:#374151;margin-left:14px;line-height:1.7}.qp{font-size:7.6pt;color:#2563eb;margin-top:4px}
.ans{margin-bottom:12px;page-break-inside:avoid;break-inside:avoid}.ans-h{margin-bottom:4px}
.ans-no{display:inline-block;background:#10b981;color:#fff;font-weight:700;font-size:8.4pt;border-radius:50%;width:16px;height:16px;line-height:16px;text-align:center;margin-right:6px}
.ans-key{font-weight:700;color:#047857;font-size:10pt}.ans-b{font-size:8.6pt;color:#374151;margin:3px 0 0 22px}.ans-b b{color:#047857;margin-right:6px}
.foot{text-align:center;font-size:7.4pt;color:#94a3b8;margin-top:14px;padding-top:6px;border-top:.6pt solid #e2e8f0}
</style>
</head>
<body>
<div class="sheet">
  <div class="title-block">
    <div class="title-en">{{英文标题}}</div>
    <div class="title-zh">{{中文译题}}</div>
    <div class="title-meta">来源：{{source}}　·　难度：{{level}}　·　词数：{{words}}　·　适用：{{exams}}</div>
  </div>
  <div class="col-label"><span>左栏 · 正文（中英对照）</span><span>右栏 · 批注（生词 / 熟词生义 / 谚语）</span></div>

  <!-- 每段复制一个 .group：左正文 + 右批注 -->
  <div class="group">
    <div class="left">
      <div class="pno">¶ 1</div>
      <div class="en">{{英文段 1}}</div>
      <div class="zh">{{中文段 1}}</div>
      <div class="grammar"><b>长难句</b>{{语法分析}}</div>
    </div>
    <div class="right">
      <div class="note n-word"><span class="n-tag">生词</span>{{word /音标/ 词性 释义}}</div>
      <div class="note n-poly"><span class="n-tag">熟词生义</span>{{word 常见义 → 文中义}}</div>
      <div class="note n-idiom"><span class="n-tag">谚语 / 习语</span>{{原文 + 释义}}</div>
    </div>
  </div>

  <!-- 思维导图（另起页） -->
  <section class="page-break">
    <h2 class="sec sec-map">文章脉络 · 思维导图</h2>
    <div class="mm-root">{{主题}}</div>
    <div class="mm1">● {{核心论点 1}}</div>
    <div class="mm2">○ {{论据}}</div>
    <div class="mm1">● {{核心论点 2}}</div>
    <div class="mm2">○ {{论据}}</div>
  </section>

  <!-- 仿真出题（答案不在题后） -->
  <section>
    <h2 class="sec sec-quiz">仿真出题 · 自测</h2>
    <div class="q"><div class="qt">1. {{题干（英文）}}</div>
      <div class="opt">A. {{选项}}</div><div class="opt">B. {{选项}}</div>
      <div class="opt">C. {{选项}}</div><div class="opt">D. {{选项}}</div>
      <div class="qp">考点：{{考点}}</div></div>
  </section>

  <!-- 答案与解析（另起页） -->
  <section class="page-break">
    <h2 class="sec sec-ans">答案与解析</h2>
    <div class="ans"><div class="ans-h"><span class="ans-no">1</span><span class="ans-key">{{B}}</span></div>
      <div class="ans-b"><b>依据</b>{{解析}}</div>
      <div class="ans-b"><b>干扰项</b>{{A/C/D 为什么错}}</div></div>
  </section>

  <div class="foot">外刊精读天团 · 打印版 · 中英对照精读卷　|　浏览器 Ctrl/Cmd + P → 另存为 PDF（A4）</div>
</div>
</body>
</html>
```
