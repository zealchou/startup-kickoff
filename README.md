# Idea Gauntlet — The Startup Idea Death March
# 創業點子死亡行軍

**An idea walks in. Evidence walks out. Most of the idea will not survive —
and that is the product.**
**一個點子走進來，只有證據能走出去。這個點子的大部分都活不下來——而這正是這個
產品的價值所在。**

Every assumption killed here for free would have cost the founder months and
real money to kill in the market. This is a Claude skill that runs a startup
idea through a 12-gate, 4-ring validation gauntlet and hands back a survival
number you can actually defend.

在這裡免費殺死的每一條假設，換到市場上都是創辦人要用好幾個月和真金白銀去換來
的教訓。這是一個 Claude skill：把一個創業點子丟進 12 道關卡、4 個環的驗證死亡
行軍，最後吐出一個你敢拿出來為自己辯護的存活數字。

```
╔══════════════════════════════════════════════════════╗
║  IDEA GAUNTLET · CERTIFICATE OF AUTOPSY   2026-07-07  ║
╠══════════════════════════════════════════════════════╣
║  Undertone — AI journaling for early burnout          ║
║  ☠️ BURIED ON ARRIVAL — SURVIVAL INDEX 29%*            ║
║                                                       ║
║  Problem & Customer      {█████░░░░░░░}  43%          ║
║  Market & Timing         {█████████░░░}  75%          ║
║  Business Engine         {██████████░░}  83%          ║
║  Buildability & Exec.    {████████░░░░}  67%          ║
║                                                       ║
║  🪦 Free and "good enough" is undefeated; nobody      ║
║      traded a habit for a feature.                    ║
║  🪦 15/15 interviewees described the bad week; zero   ║
║      described downloading anything.                  ║
║  🪦 "People want to have journaled, not to journal."  ║
║                                                       ║
║  7/17 assumptions survived · 3 killed · 7 wounded     ║
║  *directional indicator, not a probability            ║
╚══════════════════════════════════════════════════════╝
```
*(fictional example — full run in [`examples/example-run-en.md`](examples/example-run-en.md) /
虛構示範，完整過程見 [`examples/example-run-en.md`](examples/example-run-en.md))*

---

## What it does
## 這是什麼

You pitch an idea, in one line or one page. The skill decomposes it into a
15–25 assumption ledger, runs each assumption through the gate it hangs on
with a strongest-case-against-it argument first, tiers the evidence, and
computes a **Survival Index** — a weighted, transparent number with a Kill
cap that overrides the arithmetic the moment a foundational assumption dies.
Out comes a shareable **Autopsy Card** (or a **Survival Certificate**, for
the rare idea that clears every gate) and a **Resurrection List** — the
exact evidence that would bring every killed or wounded assumption back to
life.

你丟進一個點子，一句話或一頁都行。這個 skill 會把它拆解成 15–25 條假設組成的
帳本，逐一放進它掛靠的關卡，每一關都先打一輪「最強反方論證」再打分，把證據分
級，算出一個**存活指數**——一個有權重、可回溯、而且只要根基性假設一死就會啟動
「封頂」蓋過算術結果的誠實數字。最後產出一張可分享的**死亡診斷卡**（少數闖過
全部關卡的點子則拿到**存活證書**），以及一份**復活清單**——每一條被殺死或重傷
的假設，具體要拿到什麼證據才能翻案。

**Core argument (from Anthropic's [*Founder's Playbook*](https://claude.com/blog/the-founders-playbook), 2026):**
in the AI-native era, building is nearly free — so the deadliest failure mode
is no longer "we couldn't build it" but "we built it before validating it."
42% of startups already died from no-market-need when building was
expensive; agentic coding makes that trap cheaper to fall into and more
expensive to climb out of. This skill is the counterweight: **the same AI
that can build your idea in a weekend is used here to try to kill it in an
hour, on paper, before it costs you anything.**

**核心論點（源自 Anthropic 的 [《創辦人手冊》](https://claude.com/blog/the-founders-playbook)，2026）：**
在 AI 原生時代，把東西建出來幾乎是免費的——所以最致命的失敗模式，已經不是
「我們建不出來」，而是「我們在驗證之前就先建出來了」。就算在建造成本還很高的
年代，42% 的新創死因都已經是「市場根本不需要」；當寫程式這件事被 agentic
coding 變得更便宜，跌進這個陷阱的成本更低，但爬出來的代價卻更高。這個 skill
就是那個反作用力：**同一套能在一個週末把你的點子建出來的 AI，在這裡被用來在
一小時內、在紙上把它殺死——趁它還沒花掉你任何一分錢之前。**

---

## The Gauntlet at a glance
## 關卡一覽

| Ring (weight) | Gate | Kills on |
|---|---|---|
| **R1 Problem & Customer (35%)** | G1 Problem Reality & Testability | unfalsifiable hypothesis; can't name who / how often / how bad |
| | G2 Target Customer & Reachability | target = "everyone" |
| | G3 Existing Alternatives & Switching | current solution is free and good enough; no switching trigger |
| **R2 Market & Timing (25%)** | G4 Market Size (bottom-up) | SOM can't sustain minimum viable revenue |
| | G5 Why Now | no enabling shift answerable |
| | G6 Competitive Landscape | claims "no competitors" |
| **R3 Business Engine (20%)** | G7 Unit Economics & Pricing | LTV:CAC < 1 even in the optimistic case |
| | G8 Channel & Growth | growth plan = "build it and they will come" |
| | G9 Capital & Runway | no realistic path to the capital validation requires |
| **R4 Buildability & Execution (20%)** | G10 Solution Feasibility | core interaction depends on unavailable tech/data/licenses |
| | G11 Launch Responsibility | real user data with no security review plan; regulated industry with no compliance path |
| | G12 Founder–Market Fit | no unfair advantage and no plan to acquire one |

Every gate runs the same protocol, in order: **strongest refutation first →
tiered evidence review → 0–5 score against fixed anchors → assumption
verdicts (✅ survived / 🩸 wounded / ☠️ killed) → one falsifiable, quotable
gate verdict.** A Ring-1 Kill caps the Survival Index at 29%; a Kill in any
other ring caps it at 54% — a dead foundation cannot be averaged back to
life by strong scores elsewhere.

| 環（權重） | 關卡 | 觸發 Kill 的條件 |
|---|---|---|
| **R1 問題與客群（35%）** | G1 問題真實性與可驗證性 | 假設無法可證偽表述；答不出誰／多常／多嚴重 |
| | G2 目標客群與觸及性 | 目標客群＝「所有人」 |
| | G3 現有替代方案與轉換 | 現有解法免費又夠用；沒有轉換觸發 |
| **R2 市場與時機（25%）** | G4 市場規模（由下而上） | SOM 撐不住最低可生存營收 |
| | G5 為什麼是現在 | 答不出任何推動因素 |
| | G6 競爭格局 | 宣稱「沒有競爭者」 |
| **R3 商業引擎（20%）** | G7 單位經濟與定價 | 即使最樂觀情境 LTV:CAC 仍 < 1 |
| | G8 通路與成長 | 成長計畫＝「做出來，人自然會來」 |
| | G9 資金與跑道 | 撐到驗證所需資金沒有現實路徑 |
| **R4 可建性與執行（20%）** | G10 解決方案可行性 | 核心互動依賴拿不到的技術／資料／授權 |
| | G11 上線責任 | 碰真實用戶資料卻無資安審查計畫；受監管產業卻無合規路徑 |
| | G12 創辦人與市場契合度 | 沒有不公平優勢也沒有取得優勢的計畫 |

每一關都走同一套流程，依序：**先打最強反方論證 → 證據分級檢視 → 對照固定錨點
打 0–5 分 → 假設判定（✅存活／🩸重傷／☠️陣亡）→ 一句可證偽、可被引用的本關判
決。** Ring 1 觸發 Kill，存活指數封頂 29%；其他任何一環觸發 Kill，封頂 54%——
根基性的死亡不會因為其他地方分數高就被平均救回來。

---

## Why trust the number
## 這個數字憑什麼可信

- **Three evidence tiers, always tagged.** A — empirical (real
  conversations, observed behavior, actual data). B — inferred (reasonable
  derivation from public data, named sources). C — asserted (founder belief,
  untested). **C-tier-only evidence caps any gate score at 2/5** — no matter
  how confident the founder sounds.
- **Refutations are graded too.** A refutation built on speculation can
  lower confidence but can never trigger a Kill. Only an A/B-tier refutation
  kills — no theater in either direction.
- **No fabricated numbers.** Market sizes, benchmarks, competitor claims —
  cited with source and method, or marked `[UNVERIFIED]`. A wrong-but-
  confident number is worse than an honest gap.
- **Kill caps override arithmetic.** In the burnout-journaling example
  above, the raw weighted math actually comes out to **64%** — but a Ring-1
  Kill fired at G3, so the reported index is **29%**, not 64%. The cap wins,
  every time.
- **Full transparency ledger.** Every point of the Survival Index traces
  back to a named assumption with a verdict and an evidence tier — nothing
  is a black box, and nothing in the appendix is optional to check.
- **The tier is the headline, the % is a disclaimer.** "Survival Index" is
  always labeled a directional indicator, not a probability, and reported
  with zero decimal places — false precision is its own kind of lie.

- **三級證據，逐條標註。** A——實證（真實對話、觀察到的行為、實際資料）。
  B——推論（有名可查來源的公開資料合理推導）。C——斷言（創辦人自己相信，未經
  驗證）。**只有 C 級證據支撐的關卡，分數硬性封頂 2/5**——不管創辦人講得多有
  把握。
- **反方論證本身也要分級。** 建立在猜測上的反方論證可以拉低信心，但永遠不能
  觸發 Kill。只有 A／B 級的反方論證才能殺死假設——兩個方向都不准演戲。
- **不編造數字。** 市場規模、基準值、競爭者聲稱——一律附上來源與方法，或標
  `[UNVERIFIED]（未驗證）`。一個講得很有信心但錯的數字，比誠實承認「這裡有
  缺口」更糟。
- **Kill 封頂會蓋過算術結果。** 上面那個燒光型的燒盡型案例（AI 日記偵測職業
  倦怠），加權算術實際上算出來是 **64%**——但 G3 這關觸發了 Ring 1 Kill，所以
  最後回報的指數是 **29%**，不是 64%。封頂永遠贏。
- **完整可回溯的假設帳本。** 存活指數上的每一分，都能回溯到一條具名假設、
  一個判定、一個證據級——沒有黑箱，附錄裡的每一條都可以被查核，不是選擇性
  公開。
- **判決等級是標題，百分比是警語。**「存活指數」永遠會標明是方向性指標而非
  機率，而且不顯示小數點——假精確本身就是一種說謊。

---

## Install & use
## 安裝與使用

**Claude Code:** copy this whole folder to `~/.claude/skills/idea-gauntlet/`
(keep the folder name matching `idea-gauntlet` so Claude Code discovers it
by its `SKILL.md` frontmatter `name:`). It then activates automatically
whenever you pitch an idea and ask for it to be validated, stress-tested,
audited, or "kicked off."

**Claude Code：** 把整個資料夾複製到 `~/.claude/skills/idea-gauntlet/`（資料夾
名稱維持 `idea-gauntlet`，Claude Code 才會照 `SKILL.md` frontmatter 的 `name:`
辨識到它）。之後你只要丟一個點子並要求驗證、壓力測試、審計或「kick off」，它
就會自動啟動。

**Claude.ai:** upload this folder as a Skill in your workspace (Settings →
Capabilities → Skills → upload), or, if your plan doesn't yet support Skill
uploads, attach `SKILL.md` and the `references/` folder as project
knowledge — the skill reads its own reference files by relative path, so
keep the folder structure intact either way.

**Claude.ai：** 在你的工作區把這個資料夾當作 Skill 上傳（設定 → Capabilities →
Skills → 上傳），若你的方案還不支援 Skill 上傳，退而求其次把 `SKILL.md` 與
`references/` 資料夾整包加進專案知識——這個 skill 是用相對路徑讀自己的參考
檔案，不管哪種方式都要保持資料夾結構完整。

**Four modes / 四種模式:**

| Mode | One line |
|---|---|
| `full` (default) | Everything: intake → 12 gates → overlays → verdict → deliverables → kickoff package if you survive. |
| `quick` | All 12 gates at one-paragraph depth, 10–12 assumptions, Autopsy Card, no appendix — a first date with an idea. |
| `gate G7` | One gate, maximum depth — for when you already know where the doubt is. |
| `rerun` | You return with new evidence; the ledger updates, assumptions can be revived, the index recomputes and shows the delta. |

| 模式 | 一句話說明 |
|---|---|
| `full`（預設） | 全套流程：進場問診 → 12 關 → 診斷疊層 → 判決 → 交付物 → 若存活則附開工套件。 |
| `quick` | 12 關都用一段話深度打完，10–12 條假設，附死亡診斷卡，不附附錄——跟一個點子的第一次約會。 |
| `gate G7` | 只打一關，打到最深——當你已經知道疑點在哪一關的時候用。 |
| `rerun` | 帶新證據回來；帳本更新，假設可被翻案，重新計算指數並顯示變化量。 |

---

## What's in the box
## 內容物

```
idea-gauntlet/
├── SKILL.md                          — the full workflow definition
├── README.md                         — this file
├── references/
│   ├── 01-ai-native-playbook.md      — AI-native building/validation playbook
│   ├── 02-startup-canon.md           — startup methodology backup
│   ├── 03-gauntlet-rubrics.md        — full 12-gate scoring specification
│   ├── 04-diagnostic-overlays.md     — D1/D2/D3 overlay specs
│   ├── 05-founder-os.md              — founder leverage & operating rhythm
│   └── 06-deliverable-templates.md   — verdict / card / list templates
└── examples/
    ├── example-run-en.md             — full run, ☠️ buried on arrival
    └── example-run-zh.md             — full run, 🛠 repair and re-run
```

---

## Philosophy
## 設計哲學

Every kill comes with a resurrection condition. The gauntlet's job is to
kill assumptions cheaply, not to kill founders' will — the goal is that you
walk away from every run, whatever the tier, knowing exactly what evidence
to go collect next. Be severe, never cruel. If you push back on a verdict,
it only moves with new evidence — charm is not evidence, persistence is not
data, but real evidence arriving is always honored.

每一次殺死假設，都附帶一個復活條件。這場死亡行軍的工作是便宜地殺死假設，不是
殺死創辦人的意志——目標是不管拿到哪個判決等級，你走出來的時候都清楚知道下一步
該去收集什麼證據。嚴厲，但不殘忍。如果你想反駁一個判決，它只會因為新證據而改
變——魅力不是證據，堅持不是資料，但真正的新證據一到，一定被認真對待。

---

## License
## 授權

MIT.

**Disclaimer:** this is a diagnostic and validation-discipline exercise, not
investment advice.

**免責聲明：** 這是一套診斷與驗證紀律練習工具，不構成投資建議。
