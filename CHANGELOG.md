# Changelog

## Optional Voice & Texture supplement — 2026-11-05

- 依据跨模型审阅建议，新增 U 的隐式边界承载和 R 的有内容接力检查，**不新增核心原语**。
- 新增按需 [Voice & Texture](references/VOICE_TEXTURE.md) 和独立 [natural-chinese-voice Skill](skills/natural-chinese-voice/SKILL.md)。
- 在 SKILL/METHOD/REVISION 增加媒介适配、语义回查、表达回归与停止规则，禁止为“自然”编造故障、经历或硬造分歧。
- 加入三类原创合成对照稿、十二个未执行 Voice 测试场景和三份跨模型固定任务；**暂无真实 Gemini 生成稿**。
- Gemini 优势、Voice Pass 改善与读者效果均属待验证问题，不作为已证明的事实。

## vNext design proposal — 2026-11-05

**Not a stable release; no parser, automated evaluator, or real-reader study is claimed.**

- 建议将 Writing IR 从七个同级原语，收缩为 **D/C/U/R 四核心对象**。
- 将 E 调整为 `C.kind=event`，B 改为按需派生的 Move，RS 移出作品 IR，成为 Reader Evidence。
- 将“审稿数量”转成“问题证据与优先级”，默认 0–3 个关键问题，允许明确不改。
- 建立 issue → anchored patch → preservation guards → regression → status → stop 的独立修订协议。
- 强化作者约束、范围/情态、来源、表达归属、高承载语句与对话关系。
- 纳入对照实验和消融实验设计；不宣称已有实验结果。
- 公开目录使用合成案例与通用说明；旧版历史保持独立。

Related: [Migration](references/MIGRATION.md) · [Evaluation plan](tests/EVALUATION.md).
