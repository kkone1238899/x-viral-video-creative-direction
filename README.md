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

### AI 短视频工业化生产 5 步法（@Ox_Shinji）

**核心提炼**
- 解决什么问题：AI 味主要不在主体而在环境层——跨镜头漂移的图形、静止镜头下移动的广告牌、走位穿帮；观众先读环境层，再决定是"电视质感"还是"AI 垃圾"。
- 核心用法（5 步）：1) 找格式不找创意：不看爆款绝对播放量，找"平时 2 万播放的号突然出 60 万"的离群值；扔掉话题，只提取注意力机制骨架（熟悉物体立即出现→一处细节不对劲→观众等它打开→每次揭示升级→最后一帧解释）；2) 给导演 agent 下 brief：把格式骨架+主体交出去拿回分镜级计划，像带小剧组一样分工（专管 reels / 跨镜头风格一致 / 本地化）；3) 让模型赛跑：同一 prompt 在 100+ 模型上跑，用眼看结果选胜者而不看测评；广播级镜头选能稳住人物面孔/服装/世界的模型；4) 搭建"框"而非主体：倒计时图形跨镜头连续不重置、品牌标识固定同一位置、剪辑遵循观众已知语法——主体是便宜的一半，语境是贵的一半；5) 发布即测量：每条按格式打标签，优先看完播率（日常 30% vs 某结构稳定 40%+），数据回流第 1 步形成闭环。
- 什么时候用 / 常见坑：做 AI 短视频账号/内容矩阵的内容策略与工业化生产设计时；开工前定一条绝不打破的视觉铁律（一个镜头规格、一种调色、一段逐字复制到每个镜头的角色描述）——一致性碾压聪明；不要把原创等同于从零开始，短视频注意力运行在已知机制上（变形/升级/倒计时/对比/反转）。

**适用场景**：AI 短视频账号、内容矩阵的内容策略与工业化生产流程设计。

**怎么用它搞钱**："AI 账号工业化生产"代做/代运营——按格式矩阵卖内容、把流程卖给公司、流量稳定后接产品植入，一条生产循环三种收费。

**来源**：[@Ox_Shinji](https://x.com/Ox_Shinji/status/2109577121010225410) · 2026-10-12

### 导演风格圣经速查：7 大导演视觉语言卡（@JokerLiu1119）

**核心提炼**
- 解决什么问题：AI 短片想要电影质感但不懂导演语言——7 张卡把名导风格翻译成机位/运镜/光线/色彩参数，直接拼装成 prompt。
- 风格卡速览：王家卫（18mm 超广角贴身手持、2.35:1、青绿阴影+洋红高光对冲、慢门抽帧拖影、粗颗粒胶片）；侯孝贤（50-85mm 中长焦固定机位、大片空景、自然窗光、低饱和绿灰调、生活流留白）；姜文（25-35mm 略畸变快速推拉、不稳定倾斜构图、高反差暖金黄）；贾樟柯（手持 DV 粗粝纪实、低饱和灰绿黄脏旧发闷）；诺兰（IMAX 65mm 大画幅、冷灰钢蓝去饱和、机械般精准稳定器推进）；韦斯·安德森（绝对左右对称、粉彩配色、机械横移+90 度转场+俯拍平铺）；昆汀（超低机位仰拍、暖黄正红高饱和、突然推镜+快速摇镜）。
- 配套资源：nolanx-ai/nolanx.ai（导演视觉语言库，把风格翻译成机位/运镜/光线参数）、Mikefluff/skills（内置 12 种导演风格的 video director style library，一条命令调用）、ZeroLu/awesome-seedance（导演风 Seedance 提示词模板）、jnMetaCode/ai-shortfilm-prompts（21 套电影类型模板，Sora/Kling/Veo/Seedance 通用）。
- 什么时候用 / 常见坑：做 AI 短片/品牌短片定风格圣经（style bible）时速查拼装；别照抄整卡，要按项目拆机位/光线/色彩分别调用。

**适用场景**：需要电影质感/导演风格统一的 AI 短片、品牌短片的风格定调。

**怎么用它搞钱**：电影感 AI 短片代做——按"导演风格套餐"卖（如诺兰风/韦斯·安德森风产品片）；或做成风格 prompt 包在私域/知识星球出售。

**来源**：[@JokerLiu1119](https://x.com/JokerLiu1119/status/2109615276627202076) · 2026-10-12

### Three.js 白模 previs 工作流：代码管"怎么动"，AI 管"长什么样"（@swordBluesy）

**核心提炼**
- 解决什么问题：纯文本提示词下，船往哪开、飞机从哪飞、镜头怎么动基本靠运气，改一点就得重新"抽卡"——白模预演给 AI 精确的动作参考。
- 核心用法（4 步）：1) 用 Three.js 写白模：先用代码排练船/飞机/镜头的运动轨迹（比 Blender 轻，还能让 AI 帮你写代码）；2) 把"白模视频"+外观参考图一起交给 Seedance 2.5 生成真实质感画面；3) 白模解决"动"的问题、参考图解决"像"的问题，中间要人判断反复调试，不是魔法；4) Seedance 2.5 支持参考绿幕/白模素材，还出了 Maya、Blender 插件。
- 什么时候用 / 常见坑：需要精确控制运镜/走位的 AI 叙事短片、产品演示、复杂运动镜头；坑：前几轮可能像玩具、会出现 AI 理解错关系的情况，多加参考图调试，别指望一遍成。
- 对新工种的看法：技术门槛降低，但"知道想要什么画面"的门槛没降——AI 让每个人都能拍出画面，但只有知道镜头往哪推的人才能拍出电影。

**适用场景**：AI 叙事短片、产品演示片、复杂运动镜头的预演（previs）工作流。

**怎么用它搞钱**：复杂运镜 AI 短片代做——"导演级运镜"向品牌方收溢价；把预演工作流做成教程内容吸粉引流。

**来源**：[@swordBluesy](https://x.com/swordBluesy/status/2109587037728952370) · 2026-10-12

### AI 音乐广告 brief 六要素 + 叙事闭环结构（@Justin_lords）

**核心提炼**
- 解决什么问题：AI 品牌广告没故事——从顾客已经深恶痛绝的场景出发写 brief，歌词即文案，产品负责解决开场的那个瞬间。
- 核心用法（5 步）：1) 找起点：合影时遮脸、晚餐中途补妆、"又买一个产品赌这次有用"这类顾客真实痛点场景——有了它就有东西可写；2) 给 Claude 写 brief 六要素：产品+它实际做什么、顾客是谁、反复遇到的痛点、何时最困扰、自信与人际关系如何受影响、希望那个瞬间变成什么样；3) 叙事结构：最糟糕的时刻开场呈现问题→把顾客心声变成他们会自己说出口的歌词→用动作/表情/他人反应展示后果→通过清晰的使用瞬间引入产品→回到开场场景展示改变；4) 核心结论：给故事一个去向，也给产品一个存在的理由；5) 生产管线：Claude + Kie 工作流——歌曲→角色参考→按歌词匹配场景→成片，全程同一角色、同一产品、同一故事线。
- 什么时候用 / 常见坑：做 AI 生成式品牌广告（尤其歌曲/音乐类广告）时；开场和结尾必须是同一个瞬间——闭环不封死，观众不记得产品。

**适用场景**：AI 生成式品牌广告（尤其音乐/歌曲类广告）的 brief 拆解与叙事结构设计。

**怎么用它搞钱**：音乐广告创意代做——给美妆/消费品品牌做歌曲类 AI 广告，按条收费。

**来源**：[@Justin_lords](https://x.com/Justin_lords/status/2109563569511743800) · 2026-10-12

### Blender+Seedance 产品 TVC 白模预演：扫地机器人案例（@Jiangjiefu）

**核心提炼**
- 解决什么问题：AI 产品视频画面扭曲、产品结构变形、产品大小不一致——用 Blender 建模锁定结构，白模排练镜头后再交给 Seedance。
- 核心用法（6 步）：1) 分工先行：Codex 写建模和动画脚本、Blender 负责产品/房间/运动、AI 画图定外观、Seedance 生成最终视频；2) 用参考图让 Codex 写 Blender Python 脚本，搭建产品与完整客餐厅（保留透明顶盖和前脸双镜头），保存可编辑 .blend 工程，在 Blender 里逐项反馈修改；3) 先做 30 秒白模把镜头走顺（0-6 秒产品已入画镜头慢慢下降→6-20 秒贴地跟拍展示前脸和双侧刷→20-30 秒连续抬升后退展开整个空间）；4) 特效也放进白模排练（3.5-5 秒启动扫描→5-9 秒扫过环境逐步雷达化，之后只有机器人保持实体，其余房间都是蓝色半透明扫描表面）；5) 准备参考图并分任务：2 张 AI 场景图固定同一房间不同视角（黑木地板/米色地毯/暖光）、1 张 AI 雷达图固定扫描阶段的蓝色透明环境；6) Seedance 2.5 白模/视频参考入口选 30 秒，核对素材标签明确每个素材管什么，上传分辨率按入口要求（像素总数受限时白模 1080p 等比转 720p，时长和运动保持不变）。
- 什么时候用 / 常见坑：AI 产品广告/TVC 中产品一致性要求高的宣传片；有 CAD/三维模型优先用，只有图片时务必核对比例和关键结构。

**适用场景**：产品广告/TVC、电商产品宣传片中产品一致性要求高的制作。

**怎么用它搞钱**：产品 TVC 代做——以"产品零变形"作为卖点向电商/3C 品牌收费；把预演流程标准化成服务 SOP 复用。

**来源**：[@Jiangjiefu](https://x.com/Jiangjiefu/status/2109627264988221900) · 2026-10-12
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

- 2026-10-12：晚档 X 5 条（@Ox_Shinji 工业化 5 步法、@JokerLiu1119 导演风格圣经 7 卡、@swordBluesy Three.js 白模 previs、@Justin_lords 音乐广告 brief 六要素+闭环、@Jiangjiefu Blender+Seedance 产品 TVC 白模）；共 9 条
- 2026-10-12：条目改小节格式（核心提炼/适用场景/怎么用它搞钱/来源）；新增 Ethanxwang/tvc-director、smixs/creative-director-skill、kratosxxxxxx/Agency-Workflow-skills；共 4 条
- 2026-10-11：首版，1 个项目，持续收录中
