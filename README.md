# AI Compute Infrastructure

**RimWorld 1.6／1.7 模組｜不需 DLC｜支援 Multiplayer｜完整繁體中文**

在邊緣世界蓋一座真正的資料中心。

製作或收購 AI 運算卡、插進機櫃、拉區網、鋪液冷迴路 —— 讓算力替你做研究、訓練自己的模型，
最後把模型變成機器人勞動力與自主無人機。每張卡都吃電、都發熱，機房一過熱就降頻，再不管就燒卡。

*Build a real datacenter on the rim. Rack AI accelerators, wire a LAN, plumb liquid cooling —
then let compute run your research, train your own models, and power robot workers and
autonomous drones. Every card draws watts and dumps heat: run hot and it throttles, then burns.*

---

## 📖 完整攻略手冊 · Full guide

從第一張二手礦卡到 Tier IV 機房：開局 10 步、研究樹、建築成本、散熱三層、模型訓練與未對齊、
合約談判、機器人、無人機與反無人機 —— 附 **25 張建築圖鑑**與 **10 張物品圖鑑**，中英雙語、深／淺主題。

**➡️ [開啟攻略手冊](https://hidanny666.github.io/RimWorld-AICompute-Public/)**

可離線使用：下載 [`index.html`](index.html)，雙擊就能在任何瀏覽器開啟（所有圖片已內嵌，不需要其他檔案）。

*A complete illustrated guide in Chinese and English: the 10-step start, research tree, building
costs, cooling, model training, contracts, robots, drones and counter-drone. It works offline too —
download [`index.html`](index.html) and open it in any browser.*

---

## 內容 · Features

| | |
|---|---|
| **機房** | 運算機櫃、NVL16 機櫃、浸沒式運算槽。機櫃只是鐵殼，耗電來自插進去的卡 |
| **運算卡** | 27 款真實型號（NVIDIA、AMD Instinct、Intel Gaudi、Google TPU、HGX B300），真實 FP16 規格、功耗與記憶體；千瓦級的卡需要液冷 |
| **散熱** | 冷熱分管液冷、冷卻液分配單元、空調箱、乾式冷卻器、冷卻塔、餘熱回收 |
| **網路** | 16 色網路線、叢集與骨幹交換器。每個區網是一座獨立機房，有自己的訓練佇列 |
| **電力** | UPS、備援發電機、即時 PUE。達成 Uptime Tier I～IV，換取不掉檢查點、自動切換、降低故障率 |
| **監控** | NOC 監控牆、營運控制台，以及機房熱度／負載／故障風險總覽地圖層 |
| **研究** | 殖民者睡覺時，算力自動推進研究 |
| **模型** | 約 30 種可訓練模型。權重是實體儲存匣 —— 會被搶 |
| **推論** | 推論伺服器提供全殖民地加成，以及戰場預測、AI 議價、健康掃描、深層礦脈探勘、作物檢查等主動任務 |
| **合約** | 出租算力、談判桌、SLA 稽核與違約金 |
| **機器人** | 組裝台打造人形機器人（五種外觀），插上策略匣就會那項技能 —— 它不會在工作中學習。附充電站與六種改裝模組 |
| **無人機** | 七款遊蕩彈藥（FPV、Switchblade 300/600、Kargu-2、Lancet-3、Shahed-136、電戰干擾機），操作員控制器、蜂群發射器、終端俯衝 |
| **反無人機** | 反無人機砲塔與干擾塔 —— 研究完自主彈藥後，工業等級以上的敵人會派無人機操作員來；無人機看不穿屋頂，屋頂會擋下爆炸 |

---

## 安裝 · Install

**Steam 創意工坊**：[訂閱即可](https://steamcommunity.com/sharedfiles/filedetails/?id=3820710553)。

**手動安裝**：到 **[Releases](../../releases)** 下載最新的 `AICompute-vX.Y.zip`，
解壓縮後把 `AICompute` 資料夾放進 `<RimWorld 安裝路徑>\Mods\`，再到遊戲模組清單啟用。

*Subscribe on the Steam Workshop, or download the latest zip from [Releases](../../releases)
and drop the `AICompute` folder into your RimWorld `Mods\` directory.*

**載入順序**：排在 Harmony 與 Multiplayer（如果有裝）**之後**。

**多人連線／複製到另一台電腦**：請複製**整個** `AICompute` 資料夾（About、Assemblies、Biotech、Defs、
Languages、Patches、Sounds、Textures 與 LoadFolders.xml）。只複製一部分時，開遊戲會看到一長串
「Failed to find … AIC_…」，後面會有一條說明列出缺了哪些資料夾。

*For Multiplayer or another PC, copy the **whole** `AICompute` folder. A partial copy shows a long list
of "Failed to find … AIC_…" followed by one message naming the missing folders.*

---

## 回報問題 · Bug reports

**[開一個 Issue](../../issues/new/choose)** —— 回報前請先看看 [已知問題](../../issues)。

**最簡單的方式（v41 起）**：遊戲中本模組噴紅字時會跳出回報視窗，按「**回報到 GitHub**」——
完整報告（版本、模組清單、錯誤內容；路徑裡的電腦使用者名稱已移除）會複製到剪貼簿，
並開啟已經預先填好的回報表單，把報告貼到「Player.log」欄位再送出即可。沒按就不會送出任何東西。
沒有錯誤也能從「選項 → 模組設定 → AI Compute Infrastructure → 回報問題…」開啟；不想被提示可以在同一頁關掉。

*Since v41: when this mod logs an error, a window offers **Report on GitHub** — it copies a full report
(versions, mod list, error text; your user name is stripped from paths) and opens the bug form already
filled in. Paste the report into the "Player.log" field and submit. Nothing is sent unless you click it.
You can also open it from Mod settings → "Report a problem…", or turn the pop-up off there.*

也可以手動附 log：用 [HugsLib](https://steamcommunity.com/sharedfiles/filedetails/?id=818773962)
按 **Ctrl+F12** 上傳並貼連結；或直接附上 `Player.log`：

```
%USERPROFILE%\AppData\LocalLow\Ludeon Studios\RimWorld by Ludeon Studios\Player.log
```

*Please include your mod list and a log (HugsLib Ctrl+F12 link, or `Player.log`).*

---

## 授權 · License

這個 repo 只放發布檔與問題回報，**原始碼不公開**。發布內容可以自由下載遊玩；
如果要轉載、重新打包或製作衍生模組，請先開 Issue 詢問。

*Source is not public. Builds are free to play. Please ask via an issue before
redistributing or publishing derivative mods.*
