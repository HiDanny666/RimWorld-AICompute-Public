# AI Compute Infrastructure

<!-- 📌 本檔是公開 repo（`RimWorld-AICompute-Public`）`README.md` 的唯一來源。
改完之後把整份內容複製到 `AICompute-Public/README.md`，兩邊內容要一致。
對外介紹文案看 `宣傳介紹文.md`；Steam 工作坊描述看 `Steam工作坊說明.md`；玩家手冊看 `教學手冊.md`。
     這段是 HTML 註解，GitHub 上看不到，整份複製過去也不會露出來。 -->

**RimWorld 1.6／1.7 模組｜不需 DLC｜支援 Multiplayer｜相容 Combat Extended｜完整繁體中文**

在邊緣世界蓋一座真正的資料中心。

製作或收購 AI 運算卡、插進機櫃、拉區網、鋪液冷迴路 —— 讓算力替你做研究、訓練自己的模型，
最後把模型變成機器人勞動力與自主無人機。每張卡都吃電、都發熱，機房一過熱就降頻，再不管就燒卡。

*Build a real datacenter on the rim. Rack AI accelerators, wire a LAN, plumb liquid cooling —
then let compute run your research, train your own models, and power robot workers and
autonomous drones. Every card draws watts and dumps heat: run hot and it throttles, then burns.*

---

## 📖 完整攻略手冊 · Full guide

從第一張二手礦卡到 Tier IV 機房：開局 10 步、研究樹、建築成本、散熱三層、模型訓練與未對齊、
合約談判、市場、機器人、無人機與反無人機、AGI 終局，以及故障、韌體、湧浪、通知設定等所有規則 —— 附 **46 張建築圖鑑**與 **29 張物品圖鑑**，中英雙語、深／淺主題。

**➡️ [開啟攻略手冊](https://hidanny666.github.io/RimWorld-AICompute-Public/)**

可離線使用：下載 [`index.html`](index.html)，雙擊就能在任何瀏覽器開啟（所有圖片已內嵌，不需要其他檔案）。

*A complete illustrated guide in Chinese and English: the 10-step start, research tree, building
costs, cooling, model training, contracts, the market, robots, drones and counter-drone, the AGI endgame and every
other rule (failures, firmware, surges, settings). It works offline too —
download [`index.html`](index.html) and open it in any browser.*

---

## v43.0 更新內容 · What's new in v43.0

| | |
|---|---|
| **新設備** | 背門熱交換器、列間液冷機組、冰水主機、大型冷卻塔、燃氣渦輪、變電站、SMR-300 反應爐；NVL72 機櫃（GB300 托盤）與 CXL 記憶體擴充櫃；紅隊演練台、AGI 對齊監控台、隔離沙盒櫃、冷存檔磁帶庫、生物辨識門；機器人維修站、補給四軸、手持無人機干擾器 |
| **玩法** | 市場（行情、現貨、長約、對手、AI 公司、挖角、黑市）、碳排等級與綠電專案、卡齡與晶片短缺、AI 助理終端與數位分身、終局（被偷走的模型、AGI 專案）；運算卡分五級、推論容量改成「位」、訓練任務分類視窗、合約履約保證金與欠款 |
| **無人機** | 射控重寫、彈艙配置、徵召右鍵操作發射器；平衡調整（見攻略手冊）；敵人在研究前就會零星帶無人機，研究後會用手持干擾器、電戰四軸與圍攻干擾塔反制 |
| **上手** | 機櫃面板第一行寫「在做什麼／為什麼沒在做」、營運控制台「下一步」、第一次說明信；研究集中在獨立的「AI 算力」分頁 |
| **外觀** | 全部設備、物品、機器人與無人機以高解析重新繪製，並有動畫與設備音效 |

*New hyperscale cooling and power, NVL72 and CXL memory, AI-safety facilities, a robot repair station and supply drones; a full market, carbon grades, card ageing, AI companions and the AGI endgame; rewritten swarm fire control with magazine loadouts and manned launchers; enemies that field drones earlier and jam yours; high-resolution art, animation and sound throughout. Full notes are on the [Releases](../../releases) page.*

---

## 內容 · Features

| | |
|---|---|
| **機房** | 運算機櫃、NVL16 機櫃、浸沒式運算槽，後期的 NVL72 機櫃（18 片 GB300 托盤、180,000 TFLOPS）與 CXL 記憶體擴充櫃。機櫃只是鐵殼，耗電來自插進去的卡 |
| **運算卡** | 28 款真實型號（NVIDIA、AMD Instinct、Intel Gaudi、Google TPU、HGX B300、GB300 托盤），真實 FP16 規格、功耗與記憶體；千瓦級的卡需要液冷 |
| **散熱** | 冷熱分管液冷、冷卻液分配單元、空調箱、乾式冷卻器、冷卻塔、餘熱回收；後期有背門熱交換器、列間液冷機組、不看天氣的冰水主機與大型冷卻塔 |
| **網路** | 16 色網路線、叢集與骨幹交換器。每個區網是一座獨立機房，有自己的訓練佇列 |
| **電力** | UPS、備援發電機、電池儲能站、小型模組化反應爐、後期的燃氣渦輪、變電站與 SMR-300 反應爐、即時 PUE。達成 Uptime Tier I～IV，換取不掉檢查點、自動切換、降低故障率；能接哪一級的合約還要看過去 30 天的實測可用性 |
| **終局** | 被敵人偷走的模型會被拿來對付你（無人機、射擊、近戰、規模加成，未對齊的還會讓他們自相殘殺），可以打下「被竊的權重」據點奪回；AGI 專案：Tier IV、20,000 GB HBM、4,000 機櫃日、四段奇點危機（電網、派系施壓、內部破壞），對齊成功得到原版 AI 人格核心、照原版造船離開，失敗則是失控 AGI 大襲擊；紅隊演練台、AGI 對齊監控台拉高對齊率，隔離沙盒櫃安全使用未對齊模型，冷存檔磁帶庫與生物辨識門防偷 |
| **市場** | 算力與模型的行情指數、現貨單（可鎖單）與 30 天長約、三家會搶單的競爭對手；兩家互相競爭的 AI 公司（主要客戶、採購船、會挖角你的研究員；新遊戲才有）；未對齊匣的海盜黑市 |
| **無人機戰** | 蜂群發射器的射控：把站在同一個爆炸範圍的敵人算成一群、替每群挑「一發打得死的最便宜機型」、照威脅（離殖民者多近、是否正在攻擊）排順序、敵人躲進屋頂底下 10 秒內不叫回；**彈艙配置**像機櫃插卡一樣排每款幾架；徵召殖民者右鍵「操作」發射器＝人類監督（誤標率 0）；自主辨識吃同區網辨識機櫃的算力，台數越多需求越高。光纖 FPV（干擾塔打不下來，只能由操作員放）、干擾塔的 GPS 欺騙模式、蜂群指揮中心（包圍／飽和／誘餌編隊） |
| **人與 AI** | AI 助理終端：殖民者聊天得到心情與學習加成，但會產生依賴；新特性 AI 信徒／AI 恐懼者／數位成癮、「被 AI 取代」焦慮；機器人工作時錄下自有資料；殖民者死後可以上傳意識，把記憶移植到機器人成為數位分身 |
| **硬體** | 每張卡記錄自己的運轉時間：新卡頭 5 天容易壞、跑滿 120／240 天開始老化（故障率 ×1.5／×2、市價打折），機櫃可一鍵退出老卡；「晶片短缺」事件讓商人沒有新卡、價格 ×1.5 |
| **碳排** | 碳排等級 A～E 看低碳發電佔比：好等級合約結算加價、能接綠電專案（×1.3）、鄰避反彈減輕、每 15 天派系好感；儲能站讓太陽能＋風力也能升 Tier III；可以捐「社區回饋」換 30 天鄰避緩和 |
| **消防** | 機房氣體滅火系統：極早期偵煙、一起火就放氣撲滅整個房間；過熱燒卡可能起火，Tier III 以上要求自動滅火 |
| **監控** | NOC 監控牆、營運控制台（含可排序比較所有權重匣的「模型庫」分頁），以及機房熱度／負載／故障風險總覽地圖層 |
| **音效** | 每台設備都有自己的運轉聲（風扇、泵浦、落水、靜電……待機小聲、滿載轉上去），加上出膛、放氣、燒卡、警報等事件音；模組設定可調音量 |
| **研究** | 殖民者睡覺時，算力自動推進研究 |
| **模型** | 約 40 種可訓練模型（殖民地增益模型＋機器人與無人機策略）。權重是實體儲存匣 —— 會被搶。資料分七個領域、四種來源（標註、授權、從襲擊者身上拿的原始資料、自己生成的合成資料）；新練的模型要評估（或服務夠久）才知道有沒有對齊；訓練從同機房區網的資料語料庫取用資料；可加長訓練、繼續預訓練刷新舊權重，或用基礎模型便宜地微調出機器人策略 |
| **推論** | 權重匣插進模型匣讀取機，機櫃切到推論模式就自動把模型提供給殖民者（一顆匣可以供整個區網） —— 同時服務幾「位」看算力、記憶體與頻寬三個上限，可量化、蒸餾或開深度推理；另有戰場預測、AI 議價、健康掃描、深層礦脈探勘、作物檢查等主動任務 |
| **上手** | 機櫃面板第一行直接寫「在做什麼／為什麼沒在做」；營運控制台列出這個區網的「下一步」；過熱、卡壞、合約、機器人等十類事件第一次發生時寄一封說明信（可在模組設定關掉） |
| **合約** | 出租算力、談判桌、SLA 稽核與違約金；報價輪流照每個區網的規模開（大機房接得到大單、小機房也有適合自己的單）；接單要押履約保證金，違約收不齊會欠款 |
| **模型經濟** | 模型授權收租（匣鎖在讀取機裡）、推論合約（MaaS：預留推論容量給客戶）、開放權重換全世界好感（可能收到社群微調版） |
| **機器人** | 組裝台打造人形機器人（五種外觀），插上策略匣就會那項技能 —— 它不會在工作中學習。附充電站與六種改裝模組；每 30 天要保養一次（零件 1），逾期會變慢。機器人維修站一站包辦充電、修傷、補回被打掉的肢體與保養（吃鋼材） |
| **無人機** | 八款遊蕩彈藥（FPV、光纖 FPV（只能由操作員放）、Switchblade 300/600、Kargu-2、Lancet-3（反裝甲射流）、Shahed-136、電戰干擾機），操作員控制器（部署時可以直接選型號）、蜂群發射器、終端俯衝；補給四軸從倉庫取藥品、食物等，空投到地圖上任何地方；手持無人機干擾器（腰帶，徵召時啟動 30 秒） |
| **反無人機** | 反無人機砲塔、干擾塔與手持干擾器。工業等級以上的敵人：研究「自主彈藥」前只會零星帶 1～2 架（用槍打得下來），之後一般襲擊 10% 的人當操作員、專屬無人機襲擊依戰術 15～50%；敵人也會帶手持干擾器、電戰四軸，圍攻時在營地架干擾塔。無人機看不穿屋頂，屋頂會擋下爆炸 |
| **Combat Extended** | 有裝 CE 時自動換成 CE 尺度的寫實數值：每款無人機對應真實彈頭（RPG-7、標槍、155mm 級……）並噴出 CE 破片，機器人與無人機用 CE 護甲，反無人機砲塔改打 35mm 高爆彈、要裝填彈藥。沒裝 CE 時完全不變 *(With CE active: real warheads with CE fragments, CE-scale armour, a 35mm counter-drone gun that needs ammo. Nothing changes without CE.)* |

---

## 安裝 · Install

**Steam 創意工坊**：[訂閱即可](https://steamcommunity.com/sharedfiles/filedetails/?id=3820710553)。

**手動安裝**：到 **[Releases](../../releases)** 下載最新的 `AICompute-vX.Y.zip`，
解壓縮後把 `AICompute` 資料夾放進 `<RimWorld 安裝路徑>\Mods\`，再到遊戲模組清單啟用。

*Subscribe on the Steam Workshop, or download the latest zip from [Releases](../../releases)
and drop the `AICompute` folder into your RimWorld `Mods\` directory.*

**載入順序**：排在 Harmony、Multiplayer 與 Combat Extended（如果有裝）**之後**。

**多人連線／複製到另一台電腦**：請複製**整個** `AICompute` 資料夾（About、Assemblies、Biotech、CombatExtended、Defs、
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
