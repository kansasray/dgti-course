# DGTI（無人機×地面小組協同）YouTube 內容覆蓋度盤點

日期：2026-08-09
方法：`yt-dlp --flat-playlist "ytsearch12~15:<query>"` 打 YouTube 搜尋（結構化結果，非爬網頁），共執行 44 組搜尋（12 組 SAR 空地協同 + 14 組任務規劃/戰術 + 12 組中文 + 6 組收斂/補缺）。原始結果約 600+ 筆（含重複），逐筆人工判讀後去重。定調依 Kansas 的雙軌設計：主軸＝防災搜救空地協同，附錄章＝任務導向戰術實務。原始搜尋結果檔存於 scratchpad，未附於本報告。

---

## 1. 搜救空地協同供給

**中等偏薄，但核心概念「協同」本身找得到專門教學，只是產量小、多在小頻道。**

| 細項 | 厚度 | 代表頻道/影片 |
|---|---|---|
| 搜索模式（grid/spiral/creeping line） | **中等，10-14 支** | Steering Mariners 一整個系列（Sector Search、Parallel Sweep Search、Track Line Search、Expanding Square Search，海事 SAR 語境非無人機專屬但模式通用）；Epic F.P.V《DJI Pilot 2 waypoint Search & Rescue search patterns mission tutorial》；SPH Engineering／UgCS 的 SAR 搜尋模式 webinar；少數個人頻道直接示範 creeping line（Craig N、Cristy Kirschke，觀看數個位數到百位數，畫質陽春但動作正確） |
| 熱像搜索（夜間/山區） | **豐富，15+ 支** | DJI Enterprise（Zenmuse H30T 官方案例）、Savage Tactical Recon（Mavic 3T Thermal 完整 workflow，含 CalTopo 搭配）、多支新聞台真實案例（USA TODAY、NBC News、Inside Edition）可作情境素材但非操作教學、2A Tac Air Ops（一系列真實 SAR 出勤紀錄，Part 107 民間飛手視角） |
| 目標辨識與定位回報 | **薄，4-6 支** | Civil Air Patrol Arizona Wing 的官方任務清單影片《Task P-5110: Identify Visual Clues and Wreckage Patterns from FPV and Orthomosaic Imagery》《Task P-5111: Identify what to look for during damage assessment》《Task O-5003: Discuss Consideration Variables to Image Composition》——這是全盤點裡最貼題的內容，但單支觀看數僅百位數，屬小眾官方訓練教材 |
| **無人機隊與地面隊的通訊協調（核心主題本身）** | **最薄，3-5 支，但確實存在** | **Civil Air Patrol Arizona Wing《Task O-5001: Demonstrate Air & Ground Team Coordination》**是目前找到唯一直接以「空地協同」為題的專門教學片；同系列 Michigan Wing《O 5001 Demonstrate Aircraft & Ground Team Coordination》為同任務的另一次錄製版本；Hawaii Wing CAP 有配套的《Visual Search Patterns and Procedures》《Crew Resource Management》《Navigation and Position Determination》可搭配使用。**這是全份報告最重要的單一發現**：CAP（美國民用航空巡邏隊，官方 SAR 輔助組織）有一套任務編號化的教材體系，直接命中課程核心，但產量極小、全部來自各州分會小頻道，觀看數多在百位數 |
| SAR 團隊指揮體系（ICS 在 SAR 的應用） | **中等，6-8 支** | MovieMedic《ICS 200 Lesson 2》、JIBC《Ground Search Team Leader Training Video》（41 分鐘正式課程）、RemoteRescueTraining《ICS in Small Team Rescues》、The Hiker's Advice《How Does ICS Organize Wilderness SAR?》。**注意**：這批內容教的是「SAR 組織怎麼用 ICS」，與 ATAK 課程模組三缺口清單裡的「ICS 整合」（教 ICS 概念本身如何套進 ATAK 軟體）是不同顆粒度，不重複，但兩門課都會出現「ICS 是什麼」的基礎鋪陳，策展時要注意不要抄同一批影片 |
| real-world SAR 案例（消防/民間搜救隊紀錄） | **豐富，15+ 支，但多為新聞非教學** | DJI 官方案例（M200/M300/H30T 系列敘事式 demo）、各地消防局新聞片（FDNY、Wake Forest、West Midlands Fire）、《On Location Show》SAR Training Camp 紀錄片。**這類內容適合當「為什麼/案例佐證」而非「怎麼操作」**，配額要與操作教學分開算，比照 ATAK 報告的既有原則 |

**小結**：SAR 空地協同的「協同」本身——也就是課程最想教的那個核心——全網幾乎只靠 Civil Air Patrol 一個組織的任務教材撐著，量極小。但它確實存在、確實是官方系統化教材（美國 CAP 的 O-5001/P-5110/P-5111/O-5003 任務編號體系，類似 ATAKwizard 的 A/B 系列邏輯），可以當骨幹用。周邊題目（搜索模式、熱像、ICS）供給量中等到豐富，可以把厚度撐起來。

---

## 2. 任務導向戰術供給

**教學向與紀錄向比例嚴重失衡，紀錄向壓倒性多。**

| 細項 | 厚度 | 備註 |
|---|---|---|
| 小部隊任務規劃/簡報格式（OPORD/SMEAC） | **豐富，20+ 支，全英文、全美軍語境** | University of Iowa Army ROTC 有完整系列（OPORD Paragraph 1-5、Warning Order、戰術科目各一支）、MIT Army ROTC、Army Flashcards、166th Regiment、OCS Prep（Marine OCS 5 paragraph order 系列）、Life is a Special Operation《What is the Military Operation Order - OPORD?》。**這是本盤點單一供給最豐富的子題**，但全部是美軍軍官學校訓練語境，需要跟 ATAK 課處理蓋瑞修特內容一樣的「文字銜接/改寫框架」才能套進民用戰術訓練課的語氣 |
| 無人機支援地面小組的戰術運用 | **供給存在但幾乎是紀錄向，教學向極薄** | 見下方專門分析 |
| milsim/airsoft 團隊訓練頻道的系統性教學 | **薄，零星，不成系列** | DesertFoxAirsoft《Milsim West: Objective Stavropol - Squad Leader (Tactics Explained)》是單場活動戰術復盤，非系統教學；Jolly Roger Airsoft《Bounding - Simple Infantry Tactics Basics》是真正的基礎戰術教學但不含無人機；找不到任何一個 airsoft/milsim 頻道有「無人機融入戰術」的系統化教學系列。多數搜尋結果是遊戲內空拍花絮（Airsoft Drone Gameplay 系列，純娛樂剪輯不是教學） |

**教學向 vs 紀錄向的比例判定（回應題目要求）**：

實測「drone infantry integration training」「Ukraine drone infantry coordination」「FPV drone infantry attack」三組搜尋，**命中結果 40+ 支中，教學向（有明確教學步驟或課程結構）不到 5 支，其餘全是戰場實錄剪輯頻道（Military Force、FUNKER530、Frontline 24、Beyond Military）、新聞紀錄片（WSJ、NBC News、Daily Mail、WELT Documentary）、或官方 B-roll 宣傳片（U.S. Army、Defence Australia）**。少數看似教學的命中，逐一檢視後多為**收費課程的宣傳短片**而非可直接排課的完整教學：
- 《Inside Look - U.S. Marine Corps Small Attack Drone Operators Course》（Media Magik Entertainment）——是課程介紹片，非課程本身
- 《T3i Inc TDOC FPV - Tactical Drone Operator Course》——同樣是招生宣傳性質
- 《C.R.I. Training TACTICAL DRONE ACADEMY》、《FSC Africa: Tactical Drone Operator Course: Become Mission-Ready》——同類，60-100 秒的招生短片

**結論：無人機-步兵協同這個主題，YouTube 上幾乎沒有「教你怎麼做」的內容，只有「看別人做」（戰場實錄）跟「跟我們付費學」（招生短片）兩種。這是整份盤點最大的落差**——供給看起來量很大（搜尋隨便都是幾十萬到幾百萬觀看），但可用性趨近於零，因為都不是教學片。附錄章如果要教這一段，必須走 ATAK 課處理 VZ 缺口的同一套解法：拿戰術基礎教學片（非無人機專屬，如 Jolly Roger Airsoft 的 Bounding 教學）+ 無人機戰術新聞紀錄片當佐證素材，靠繁中導讀把兩者串成「無人機如何改變這個戰術動作」的敘事，而不是期待找到一支「無人機步兵協同教學片」。

---

## 3. 中文供給

**比 ATAK 課的中文供給處境好一點，但仍然無法撐起整章，且分布不均——SAR 側有零星真實內容，戰術規劃側幾乎掛零。**

- **台灣消防/民間搜救的無人機應用**：有一個持續產出的個人創作者頻道 **張喬志**，內容包括《無人機救災 無人機RIT 無人機室內搜索》《穿越機倒塌建物搜索》《拋繩槍 vs 穿越機 無人機科技救災運用》《內政部消防署遙控無人機應用訓練 竹山訓練中心》《UAV search and rescue 無人機消防搜救運用 山域搜救》等 8-10 支，看得出是台中消防體系相關的實務操作示範（RIT=Rapid Intervention Team），觀看數低（300-2600），畫質與剪輯陽春，但**技術內容是真的**，性質類似 ATAK 報告裡的蓋瑞修特——可當中文補充連結。另有 **Carbon-Based Technology 碳基科技**（台灣無人機製造商）的任務規劃軟體展示片（UAVER BESRA mission plan、Mission_Planner Wizard），偏產品介紹非教學。
- **大量 TVBS/公視/民視/中視/華視等新聞台的無人機搜救報導**（能高山山難、消防搜溺、熱成像找到失蹤者等），**這些是新聞不是教學**，比照 ATAK 報告的既有判準不算進教學配額，但可作為「為什麼」情境素材。
- **戰術訓練圈（類生存遊戲教學頻道）的量級**：**幾乎為零**。搜尋「戰術訓練 無人機」「台灣 戰術 訓練 課程」主要命中三類：(1) 軍聞社等官方軍事宣傳片（正規軍隊訓練花絮，非教學）、(2) 台灣軍警戰術研究發展協會（TTRDA）相關的 IDPA 防衛手槍訓練影片——**主題是手槍戰術，與無人機無關**，(3) 黑熊學院的政論/訪談節目。**沒有找到任何一個台灣生存遊戲/airsoft 頻道教「無人機融入戰術」**。
- **黑熊學院（Kuma Academy）**：頻道本身有大量無人機相關影片，但幾乎全是「有BEAR來」政論訪談格式（討論烏克蘭蜘蛛網行動、無人機產業鏈、國防政策），**性質是時事評論不是操作教學**，而且該頻道 2024 年因「募款買中國製空拍機」爆爭議、涉入統獨政治對立敘事（可查中天新聞等多支負面報導），**意識形態濃度高，不建議作為中性教育內容來源**，即使個別影片技術含量尚可也建議謹慎篩選或直接排除。
- **「任務簡報」關鍵字幾乎全軍覆沒**：中文搜尋「任務簡報 教學」**零個真正的軍事/戰術簡報教學命中**，結果被 PPT/Gemini/ChatGPT 簡報製作教學（辦公室簡報軟體）完全淹沒——這是本盤點最嚴重的一個關鍵字碰撞（見下節）。OPORD/SMEAC 這類軍事簡報格式在中文語境幾乎沒有對應的 YouTube 教學。

**結論**：中文核心教學片同樣無法撐起任何一章。SAR 側有張喬志一個小頻道（8-10 支）可用，戰術規劃側是真空。這門課如果要有中文血統，必須靠英文源片 + 大量繁中導讀，跟 ATAK 課的處境幾乎一樣，且比 ATAK 更嚴重的是連「軍事教召語境」的替代品（如蓋瑞修特）在戰術規劃這個子題上都找不到對應角色。

---

## 4. 與既有課的邊界——這門課成不成立？

**成立，但邊界要抓精準,且供給比想像中薄,需要「工具組合+導讀串接」策略,不能只靠現成教學片排課。**

逐一比對三門既有/同批課程：

- **ATAK 課**教「情資標繪與指管」——也就是拿到座標、事件後怎麼在地圖軟體上畫出來、分享出去、串成 SA（態勢感知）。它完全不碰「怎麼決定要用什麼搜索模式飛」「空中組跟地面組怎麼互相回報」這些**流程/協定層**的問題,ATAK 課教的是**工具操作**,DGTI 要教的是**人與人之間的協同動作**,兩者在概念上清楚分層,不重疊。
- **Meshtastic 課**教離網通訊硬體（Heltec/T-Beam、頻段設定、mesh 網路組建）——這是**通訊管道本身**,DGTI 教的是「拿到通訊管道之後,空地兩組人要用什麼流程溝通什麼內容」（回報座標格式、簡報流程、指揮鏈）,一個是水管,一個是水管裡流的內容和規矩,不重疊。
- **drone-course**（同批建置,教基礎飛行與考證）——教的是「怎麼讓無人機飛起來、怎麼考照」,DGTI 預設學員已經會飛,教的是「飛起來之後,怎麼在一個團隊任務裡跟地面配合」,是下一層的應用,不重疊。

**實測後的判斷**：三門課的既有內容確實不會被 DGTI 重複收錄——**這點驗證了課程在概念上站得住腳**。但「協同教學的實際存量」比 Kansas 原先設想的可能更薄：

1. 真正命中「協同本身」的教學片,全網幾乎只有 Civil Air Patrol 一個組織的任務教材(O-5001/P-5110/P-5111/O-5003,約 5-8 支,小頻道、低觀看數)。這不是「找不到」,是「找到了但量極小」。
2. 周邊題目(搜索模式、熱像、ICS 指揮體系)供給中等到豐富,可以把 SAR 主軸章節撐得有分量。
3. 附錄章(任務導向戰術)的「無人機-步兵協同」這個最吸睛的主題,**供給雖然量很大但幾乎全是戰場實錄/紀錄片,不是教學**,能直接排課的教學片極少。OPORD/SMEAC 這個附錄章骨幹倒是供給豐富,但需要美軍語境→民用戰術訓練語境的轉譯,跟 ATAK 處理蓋瑞修特的手法一樣。

**結論**：這門課成立的理由不是「協同教學片很多」,而是「協同這個概念在市面上沒人系統教,ATAK/Meshtastic/drone-course 三門課都不教這塊,DGTI 填的是一個真空」。但正因為是真空,curator 不能期待「搜尋然後排課」這麼簡單,**至少 SAR 主軸的「空地通訊協調」一節、附錄章的「無人機戰術運用」一節,都需要採用 ATAK 課處理 VZ 缺口的同一套解法——用周邊教學片(CAP 任務教材、搜索模式教學、OPORD 系列、基礎戰術教學)拼接,靠繁中導讀串成完整流程,並在 `assessment` 誠實標注「無專門教學可用,以下由多支影片組合說明」**。這不是課程站不住腳的訊號,是跟 ATAK 課 VZ 缺口一樣性質的「工具組合」章節,只是這次遇到的比例更高(可能兩節而非一節)。

---

## 5. 陷阱

1. **關鍵字碰撞,三種模式**：
   - **中文「任務簡報」→ 100% 撞辦公室簡報軟體教學**（Gemini/ChatGPT/Canva 做 PPT）,零軍事簡報命中。中文搜尋務必用「軍事簡報」「作戰命令」「五段式命令」等更窄的詞,且預期低命中率。
   - **「squad」在英文搜尋裡會撞電玩《Squad》(一款軍事模擬 FPS 遊戲)的社群教學**（如 A Honcho《Squad Commander Guide》、Karmakut《How to Run a Realistic Military Unit》——這些教的是遊戲內指揮技巧,不是真實戰術）,需要用頻道白名單過濾。
   - **「drone team」本身沒有明顯撞電競戰隊**（實測未見任何電競/遊戲戰隊命中,多是 DARPA 競賽隊伍、警用無人機隊、DJI 相關內容）,這個特定詞的碰撞風險比預期低,但「drone squad」會混入《Squad》遊戲內容,策展時仍要留意。
2. **戰爭實錄的獵奇內容,觀看數壓倒性領先**：「Ukraine drone infantry」「FPV drone attack」類搜尋,命中影片觀看數常態是幾十萬到幾百萬（例：WSJ《On the Front Lines With Ukraine's Killer Drone Pilot》161 萬、Daily Mail《The Terrifying Reality of Drone Warfare in Ukraine》494 萬）,遠高於任何教學片的觀看數（CAP 教材百位數、SAR 操作教學千到萬位數）。**如果只看觀看數排序選片,附錄章會被戰場獵奇內容淹沒**,必須先做「教學向/紀錄向」二分類再篩,不能用觀看數當品質代理指標。
3. **軍事頻道的意識形態濃度**：中文戰術/國防類頻道普遍帶有強烈政治立場——黑熊學院捲入「中國製空拍機」爭議與統獨敘事戰;寶傑點兵、我想問的是、新聞大破解等政論節目格式對無人機戰爭議題的討論夾雜大量政治評論,不是中性技術內容。**策展這門課的中文素材時,優先選擇技術操作導向（如張喬志的消防實務片）,避開政論/訪談格式的頻道**,即使後者的無人機技術資訊量看起來更豐富。
4. **招生宣傳片偽裝成教學片**：多支「Tactical Drone Operator Course」「Small Attack Drone Operators Course」標題的影片,點開後是 60-100 秒的**收費課程招生短片**,不含實際教學內容,策展時要看片長與內容,不能只看標題命中。
5. **官方 B-roll/公關片偽裝成教學片**：美軍/國軍官方頻道（The U.S. Army、軍聞社等）大量發布「XX 部隊無人機訓練」標題的短片,實為公關宣傳片段,無教學步驟,不可誤判為教學資源。
6. **中文「戰術訓練」關鍵字命中的多為正規軍訓練公關片或手槍防衛訓練（TTRDA/IDPA）**,與無人機戰術無直接關係,需人工逐支排除。

---

## 6. 長度分布

以本次盤點中判讀為「真實相關」（含 SAR 教學/CAP 任務教材/OPORD 系列/中文實務片,排除純新聞與招生宣傳片）的樣本為基礎（n=101）：

- **最短 11 秒,最長 5961 秒（約 99 分鐘,CAP Washington Wing 的完整 sUAS 飛手說明會）**
- **平均約 846 秒（≈14 分鐘）,中位數約 523 秒（≈8.7 分鐘）**
- 累積分布：**28% 落在 3 分鐘以內**（多為新聞片段與 CAP 任務教材的短版）、**52% 落在 10 分鐘以內**、**75% 落在 20 分鐘以內**、**83% 落在 30 分鐘以內**
- 長尾集中在兩類：**OPORD/戰術系列的完整課堂錄影**（University of Iowa Army ROTC 多支 25-50 分鐘）與**CAP 官方說明會/座談**（Washington Wing sUAS 說明會近 100 分鐘、DroneSense 的公共安全無人機座談 40-50 分鐘）

**建議 audit 長度門檻**：與 ATAK 課一致,主力區間 **3-20 分鐘**;放寬到 **30 分鐘**給完整 OPORD/CAP 任務教材;**超過 30 分鐘一律排除**或僅供導讀引用片段,不排入正課。

---

## 7. 配額建議

假設架構：3 章（任務規劃與指揮 / 空中搜索與情報 / 地面協同與實戰）,對應「主軸 SAR + 附錄戰術」的雙軌設計——**空中搜索與情報**與**地面協同與實戰**屬 SAR 主軸,**任務規劃與指揮**屬附錄戰術。

### CH 空中搜索與情報（SAR 主軸,供給中等偏豐,配額可以撐得起來）
| 子題 | 建議配額 | 依據 |
|---|---|---|
| 搜索模式（grid/spiral/creeping line/expanding square） | **4-5 支** | Steering Mariners 系列 + Epic FPV waypoint 教學 + 個人示範片,足夠但需混搭海事/無人機兩種語境並用導讀橋接 |
| 熱像/夜間搜索 | **4-5 支** | 供給最豐富的子題,DJI 官方案例 + Savage Tactical Recon workflow + 2A Tac Air Ops 實戰紀錄可選 |
| 目標辨識與影像判讀 | **2-3 支** | 幾乎全靠 CAP P-5110/P-5111 兩支任務教材撐,配額不能設更高,誠實反映 |

**本章預估：3 個單元,10-13 支影片**,是全課供給最好的一章。

### CH 地面協同與實戰（SAR 主軸,本課最薄的一章,需要工具組合策略）
| 子題 | 建議配額 | 依據 |
|---|---|---|
| **空地通訊協調（核心主題本身）** | **1 個單元,2-3 支** | 全網只有 CAP O-5001（含兩個分會版本）可用,配額設低,`assessment` 需誠實標注「全網空缺,以下為僅有的官方任務教材」 |
| SAR 指揮體系（ICS 應用） | **1 個單元,3-4 支** | JIBC + MovieMedic + RemoteRescueTraining,供給中等 |
| 真實案例佐證（消防/民間搜救隊紀錄,非操作教學） | **1 個單元,4-6 支** | DJI 官方案例 + 消防局新聞片,型別標為「案例」非「操作」,比照 ATAK 既有原則不與操作教學混算配額 |

**本章預估：3 個單元,9-13 支影片**,但核心子題（空地通訊協調）是**全網空缺等級**（比照 ATAK 課的 VZ 缺口),必須用「CAP 任務教材 + 導讀串接」處理,不能單靠現成教學片撐滿。

### CH 任務規劃與指揮（附錄戰術,兩極分化：規劃格式供給豐富,無人機戰術教學供給空缺）
| 子題 | 建議配額 | 依據 |
|---|---|---|
| OPORD/SMEAC 簡報格式 | **4-6 支** | 供給最豐富的單一子題,University of Iowa Army ROTC + Army Flashcards + OCS Prep 系列任選,需美軍語境→民用戰術訓練語境的繁中導讀轉譯（比照 ATAK 蓋瑞修特處理手法） |
| 無人機支援地面戰術運用 | **建議 0-1 支正課 + 2-3 支「佐證/案例」外掛** | **這是全課第二個近乎空缺的子題**——教學向內容幾乎不存在（招生短片與戰場紀錄片不算）,建議不單獨開操作型單元,改用「基礎戰術教學（非無人機專屬,如 Jolly Roger Airsoft 的 Bounding）+ 無人機戰術新聞紀錄片當佐證」的組合式一個 `guide` 型單元,`assessment` 明講「無專門教學可用」 |

**本章預估：2 個單元,6-10 支影片**,是三章中最需要「導讀強力介入」的一章。

### 全課總結
- **全課預估：8 個單元,約 25-36 支影片**,落在題目假設的「3 部 8-9 章」規模區間的下緣,建議先抓 8 個單元起跳,若後續補搜（如擴大到英文以外的德/日語系 SAR 訓練頻道,或加入 NASAR/ESAR 等 SAR 認證機構的官方教材頻道)有新發現再往 9 個單元擴。
- **兩個全網近乎空缺、需要「工具組合+導讀串接」的子題**（比照 ATAK 課 VZ 缺口的處理邏輯）：**(1) 空地通訊協調本身**（只有 CAP 一個組織的任務教材可用）、**(2) 無人機支援地面戰術運用**（教學向內容幾乎為零,只有戰場紀錄片和招生短片）。這兩處建議在課程立場頁或章節說明誠實標注「此為填空章節,教學片全網稀缺」,不要假裝有豐富教學資源。
- **中文素材**：張喬志（8-10 支,SAR/消防實務）可當補充連結,語氣與定位（防災/消防實務）比 ATAK 課的蓋瑞修特（軍事教召）更貼近本課「防災搜救」主軸,是相對正面的發現;但戰術規劃附錄章完全沒有對應中文素材可用。
