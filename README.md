# AI Compute Infrastructure

**RimWorld 1.6 模組｜Mod for RimWorld 1.6**

在邊緣世界蓋一座真的資料中心：製作 AI 加速卡、插進運算機櫃，讓算力自己把研究做完，
或者訓練你自己的模型 —— 不需要任何殖民者，但要面對電力與散熱的真實約束。

*Build a real datacenter on the rim. Craft accelerator cards, rack them, and let raw
compute grind through your research queue while your colonists sleep — no researcher
required, but the machines answer to physics instead.*

**無 DLC 需求。相容 RimWorld Multiplayer。**
*No DLC required. Compatible with RimWorld Multiplayer.*

---

## 下載 · Download

到 **[Releases](../../releases)** 頁面下載最新的 `AICompute.zip`，解壓縮之後把
`AICompute` 資料夾整個放進：

```
<RimWorld 安裝路徑>\Mods\
```

然後在遊戲的模組清單裡啟用「AI Compute Infrastructure」。

*Download the latest `AICompute.zip` from [Releases](../../releases), extract it, and
drop the `AICompute` folder into your RimWorld `Mods\` directory.*

### 載入順序 · Load order

如果你有裝 RimWorld Multiplayer 或 Harmony，把本模組排在它們**之後**。

---

## 內容 · What's in it

| | |
|---|---|
| **算力** | 27 款真實 GPU 型號（V100 到 B300、MI 系列、Gaudi、TPU），規格取自官方稠密 FP16 數字 |
| **熱** | 冷熱雙管實體管網、液冷／浸沒式、乾式冷卻器、蒸發冷卻塔、真實 PUE |
| **電** | 不斷電系統、備援發電機、功率封頂、啟動湧浪、Tier I～IV 分級 |
| **模型** | 18 種可訓練模型、權重是實體儲存匣、過時衰退、蒸餾／量化 |
| **對齊** | 超大型模型有失控風險。未對齊的更強 —— 那正是問題所在 |
| **合約** | 算力合約、談判桌、SLA 稽核、違約金 |
| **機器人** | 把訓練好的策略裝進會走路的機器裡。它不會在工作中學習 |
| **無人機** | 偵察／攻擊／干擾／遊蕩彈藥，由穿戴式控制器或蜂群發射器指揮 |
| **蜂群發射器** | 48 管、自主目標辨識 —— 而它會標錯人 |

完整的機制說明、平衡數值與設計理由在 **[Releases](../../releases)** 的每一版說明裡。

---

## 回報問題 · Reporting issues

**[開一個 Issue](../../issues/new/choose)**

回報前請先看一眼 [已知問題](../../issues)，可能已經有人回報過了。

**紅字錯誤請務必附上 `Player.log`** —— 沒有它幾乎不可能定位問題。檔案在：

```
%USERPROFILE%\AppData\LocalLow\Ludeon Studios\RimWorld by Ludeon Studios\Player.log
```

（Mac：`~/Library/Logs/Ludeon Studios/RimWorld by Ludeon Studios/Player.log`）

推薦用 [HugsLib](https://steamcommunity.com/sharedfiles/filedetails/?id=818773962) 的
**Ctrl+F12** 一鍵上傳 log，貼連結給我就好。

*Please attach your `Player.log` for any error report — HugsLib's Ctrl+F12 uploads it
and gives you a link.*

---

## 授權 · License

本模組的**原始碼未公開**。發布的內容可以自由下載遊玩。

轉載、重新打包上傳到其他平台、或以本模組為基礎發布衍生模組，請先開 Issue 詢問。

*Source code is not public. Released builds are free to download and play.
Please open an issue before redistributing or publishing derivative mods.*

---

## 這個倉庫沒有原始碼

這裡只放**發布內容**與**問題回報**。原始碼在另一個私有倉庫。

如果你在找某個機制到底怎麼運作的、或想討論設計，開 Issue 問就好 —— 我很樂意講。
