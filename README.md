# 创意总监

> 品牌短片没创意方向？这个库收集 X 上实战验证过的创意总监级 prompt，每条都写清楚能帮你解决什么、怎么用它搞钱。
>
> A curated collection of creative direction prompts & skills for viral short videos, gathered from practitioners sharing on X.
> 
> Each entry answers two questions: what problem it solves (and who it's for), and how to make money with it.
> 
> Star counts verified via GitHub API on 2026-10-12. Continuously updated.

## 条目

### 零门槛电影级 AI 媒体生成（Hao0321/ai-media-generator）

**核心提炼**
- 解决什么问题："cinematic, 8k"这种万能 prompt 在每个平台效果都差——不同模型吃不同 token，这个 skill 给 14+ 平台（Seedance/Veo/Kling/Midjourney/Flux…）配了导演级提示词写法，还能按需求自动选平台、驱动浏览器提交。
- 核心用法（4 步）：1) 说一句话需求（"做个古代将军骑马冲锋的电影感短片"）；2) Agent 按各平台的签名知识选对平台、写对提示词（导演/摄影指导/胶片/镜头词汇，不用废话词）；3) 通过浏览器 MCP 把提示词提交到对应平台；4) 把成品取回。
- 什么时候用 / 常见坑：要品牌短片/电影感镜头、但不知道每个平台提示词怎么写时；坑：导演人名在 Midjourney/Sora/Veo 有效，在 Flux/Nano Banana Pro/Seedance 反而降质——skill 已内置这条规则，别自己乱加名字。

**适用场景**：品牌短片、广告片、产品宣传片的创意从业者；想给客户出电影感成片的个人创作者。

**怎么用它搞钱**：品牌短片创意代做——按"一句话出片"接品牌/商家的 AI 广告单。

**来源**：[Hao0321/ai-media-generator](https://github.com/Hao0321/ai-media-generator) · ⭐260 · 更新于 2026-08-09

### AI TVC 广告创意导演（Ethanxwang/tvc-director）

**核心提炼**
- 解决什么问题：AI 做广告永远是"产品+黑底+旋转"的套路——这个 skill 按真实 TVC 制片流程（brief→提案→视觉定调→分镜→拍摄→审片→交付）组织整条创意链，输出可直接粘到 Nano Banana Pro/Seedance 的提示词。
- 核心用法（4 步）：1) 给一张参考图 + 一句话需求（"银色轿跑的 15 秒 TVC"）；2) AI 输出产品多视图提示词 → Nano Banana Pro 出产品锚定图；3) 输出 9 宫格分镜提示词 → Nano Banana Pro 出分镜；4) 输出 Seedance Multi-Phase 视频提示词 → 双图输入生成 15 秒成片。
- 什么时候用 / 常见坑：接品牌/商家 TVC 广告单、要做产品电影化拆解时；坑：每个阶段都要人工确认调整再往下走，别一键黑盒到底；Nano Banana Pro 用 edit 模式传入参考图才能保持产品一致性。

**适用场景**：广告创意人、TVC 外包团队、想做品牌广告片的 AI 视频创作者。

**怎么用它搞钱**：TVC 广告片代做，按条/按项目收费；给电商品牌做产品电影化广告。

**来源**：[Ethanxwang/tvc-director](https://github.com/Ethanxwang/tvc-director) · ⭐326 · 更新于 2026-04-18

### 方法论驱动的 AI 创意总监（smixs/creative-director-skill）

**核心提炼**
- 解决什么问题：AI 创意全是"给我 10 个点子"式灌水——这个 skill 强制走 4A 级 agency 流程：先挖消费者洞察，再用 20+ 方法论（SIT/TRIZ/横向思维等）生成点子，最后用戛纳/D&AD 标准打分迭代。
- 核心用法（5 步）：1) 喂 brief（文本/录音转写/PDF 都行）；2) 洞察挖掘（7 种技法）；3) 按方法论生成 8–12 个创意；4) 571 个传奇广告案例库做原创度校验（同类手法用过 3 次就封顶降分）+ 打分迭代；5) 输出提案级文档（一页纸/top3/战役平台）。
- 什么时候用 / 常见坑：品牌 campaign、大创意提案、要交提案文档时；坑：原创度是实证封顶的——别指望它给你"史无前例"的创意，撞车会被扣分；流程较重，小活别用。

**适用场景**：广告公司的创意总监/策略人、品牌方市场部、接品牌全案的独立顾问。

**怎么用它搞钱**：品牌创意提案代做、广告 campaign 创意咨询，按项目收费。

**来源**：[smixs/creative-director-skill](https://github.com/smixs/creative-director-skill) · ⭐251 · 更新于 2026-08-08

### 广告公司岗位 Skill 包（kratosxxxxxx/Agency-Workflow-skills）

**核心提炼**
- 解决什么问题：一个人干不了广告公司的活——6 个岗位 skill（客户执行/策略总监/创意总监/文案/设计/BOSS）按真实协作链 AE→策略→创意→文案/设计→复核推进，每步要你确认才往下走。
- 核心用法（4 步）：1) 复制 6 个 skill 文件夹到 `~/.codex/skills`；2) 客户执行把客户需求转成内部 brief；3) 策略总监出定位和创意简报；4) 创意总监定方向后文案/设计执行，BOSS 统管全流程。
- 什么时候用 / 常见坑：品牌全案、launch campaign、社媒战役这种多角色项目；坑：缺材料时它会停下来问你，别跳过确认环节；每个岗位边界是硬的，别让文案去干策略的活。

**适用场景**：独立广告人、小型创意工作室、要给客户出全案提案的个人。

**怎么用它搞钱**：品牌全案/整合营销提案代做，按项目收费；把流程标准化后做成 SOP 卖给同行。

**来源**：[kratosxxxxxx/Agency-Workflow-skills](https://github.com/kratosxxxxxx/Agency-Workflow-skills) · ⭐99 · 更新于 2026-05-24

## 收录标准

- 来源：X 博主实战分享（原帖 / 评论区 / 引用链）及 GitHub 高星项目
- 收录线：star > 20 且一年内有更新；不达标的条目移除
- 每条格式：核心提炼（解决什么问题 / 核心用法 3–5 步 / 什么时候用和常见坑）+ 适用场景 + 怎么用它搞钱 + 来源
- Star 数为 2026-10-12 经 GitHub API 核验；持续收录中
- 去重：同一项目只收录一次，不堆 raw 链接

## 相关分类

- 总索引：[x-viral-video-skills](https://github.com/kkone1238899/x-viral-video-skills) —— 13 个分类导航
- [x-viral-video-scripts](https://github.com/kkone1238899/x-viral-video-scripts) —— 编剧 / 脚本
- [x-viral-video-hooks](https://github.com/kkone1238899/x-viral-video-hooks) —— 标题 / 5 秒钩子
- [x-viral-video-directing](https://github.com/kkone1238899/x-viral-video-directing) —— 导演
- [x-viral-video-replication](https://github.com/kkone1238899/x-viral-video-replication) —— 复制爆款
- [x-viral-video-breakdown](https://github.com/kkone1238899/x-viral-video-breakdown) —— 拉片
- [x-viral-video-pipeline](https://github.com/kkone1238899/x-viral-video-pipeline) —— 流水线 / 生产管线
- [x-viral-video-de-ai](https://github.com/kkone1238899/x-viral-video-de-ai) —— 去 AI 味
- [x-viral-video-characters](https://github.com/kkone1238899/x-viral-video-characters) —— 人物构建
- [x-viral-video-editing](https://github.com/kkone1238899/x-viral-video-editing) —— 视听剪辑技巧
- [x-viral-video-prompt-opt](https://github.com/kkone1238899/x-viral-video-prompt-opt) —— 提示词优化
- [x-viral-video-copywriting](https://github.com/kkone1238899/x-viral-video-copywriting) —— 文案
- [x-viral-video-showcase](https://github.com/kkone1238899/x-viral-video-showcase) —— X 病毒视频合集

## 投稿

发现好的创意总监 prompt / skill，欢迎提 Issue 或 PR（格式见 CONTRIBUTING.md）。

## 更新日志

- 2026-10-12：条目改小节格式（核心提炼/适用场景/怎么用它搞钱/来源）；新增 Ethanxwang/tvc-director、smixs/creative-director-skill、kratosxxxxxx/Agency-Workflow-skills；共 4 条
- 2026-10-11：首版，1 个项目，持续收录中
