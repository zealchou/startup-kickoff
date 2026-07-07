# Contributing
# 貢獻指南

Improvements welcome — especially better gate rubrics, sharper kill
conditions, real-world example runs, and translations.

歡迎改進——特別是更好的關卡評分標準、更銳利的 Kill 條件、真實世界的示範
run，以及翻譯。

**Ground rules / 基本規則:**

1. **Keep it falsifiable.** Every rubric change must preserve the evidence-tier
   system (A/B/C) and the fixed evaluation order (base → cap → bonus → clamp).
   任何評分規則的修改都必須保留證據分級制度與固定算術順序。
2. **Severe, never cruel.** Tone changes that make the gauntlet crueler (or
   softer) than the operating principles allow will be declined.
   讓死亡行軍變得更殘忍（或更鄉愿）的語氣修改不會被接受。
3. **Run the regression tests.** Any change to gate definitions, kill
   conditions, cap/bonus rules, the aggregation formula, or Reforge rules
   requires re-running Q1–Q8 in `tests/quality-baseline.md` and reporting
   results in the PR.
   改到關卡定義／Kill 條件／封頂與加分規則／彙總公式／Reforge 規則，必須
   重跑 Q1–Q8 回歸測試並在 PR 裡回報結果。
4. **Bilingual README stays paired.** If you edit an English section of the
   README, update its Traditional Chinese pair (or flag it for translation).
   README 是段落成對雙語——改了英文段落就要同步更新對應繁中段落。

Open an issue first for anything structural (new gates, new phases, scoring
changes). Small fixes can go straight to a PR.

結構性修改（新關卡、新階段、計分變更）請先開 issue 討論；小修正可以直接
發 PR。
