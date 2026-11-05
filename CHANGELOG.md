# Changelog

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
