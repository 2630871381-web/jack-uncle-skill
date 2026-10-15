# 结构溯源与维护规则

## 结构原型

本技能的研究组织方式参考了 MIT 许可仓库：

- `YixiaJack/feng-ge-skill`：<https://github.com/YixiaJack/feng-ge-skill>
- 本次审查固定提交：`9416674e9a2682bbcda6f3c6fade3f3f69ff6328`
- 许可证：<https://github.com/YixiaJack/feng-ge-skill/blob/main/LICENSE>

复用的是通用研究架构：写作/观点、对话、表达 DNA、外部评价、决策、时间线、术语，再聚合为身份卡、心智模型、决策启发式、价值观、内在张力和诚实边界。没有复制原仓库中与“峰哥亡命天涯”有关的人物观点、故事、敏感理论或长段文本。

安全与输出协议也参考了另一个 MIT 许可的同类实现：

- `rottenpen/fengge-wangmingtianya-perspective`：<https://github.com/rottenpen/fengge-wangmingtianya-perspective>

本技能新增了原型中欠缺或不充分的：逐项证据分层、非冒充声明、金融安全边界、回归测试和资料快照日期。

## REA 审查记录

- 使用 REA 6.5.0 的目标路由原则评估目标。
- 原型仓库是完整、可读的 Markdown 源码，不含二进制、打包产物、脚本或运行时，因此应走普通 Git/文本静态审查，而不是反编译或运行时注入。
- REA 的 `import-reference-source` 在当前 Windows 主机上因缺少安全 no-follow 文件打开能力而拒绝导入；没有绕过这一保护，也没有为完成任务启动 Hopper/Ghidra/Frida。
- 结构结论来自固定提交的文件清单、标题层级与正文对照；“响应流程”是结构推断，不冒充仓库作者写下的显式算法。

## JackandLinda 资料来源

身份与内容证据清单位于 [01-profile-and-evidence.md](01-profile-and-evidence.md)。来源按以下优先级维护：

1. 本人公开主页、完整投稿和直播回放；
2. 账号简介的跨平台互证；
3. 独立公开索引；
4. 粉丝切片、标题和评论，只用于主题/形式观察；
5. 推断，必须显式标注。

2026-10-15 扩充了 [03-expression-dna.md](03-expression-dna.md) 的直播问答证据，并新增 [07-six-year-pact.md](07-six-year-pact.md) 核查时间、三条记录、百万目标与会员更新节奏。新增细节大多依赖粉丝转发和平台自动文稿；它们支持高层结构归纳，不支持逐字引述或确定所有参加规则。

## 更新流程

1. 记录核验日期和原始 URL。
2. 对新增结论标为 `已核实 / 公开转述 / 分析推断 / 未知`。
3. 身份、经历、财富和争议至少需要一手来源或两个独立可靠来源。
4. 修改核心模型前，检查它是否在多个完整样本中反复出现。
5. 新增口头表达时避免逐字模仿；只保留高层结构。
6. 每次更新后运行技能校验和 [05-evaluation-cases.md](05-evaluation-cases.md)。

资料快照：2026-10-15。
