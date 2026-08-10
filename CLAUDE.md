# dgti-course

**`kansasray/gym-course`(自有框架 fork)的 clone,放一門課:`courses/dgti/`「空地協同」。** 課程內容全在 `courses/dgti/`;`courses/gym/` 是上游對照範例不要動。

課程:防災技能樹的**整合層**,3 章 8 單元 20 支影片、3 小時 34 分的精實小課。雙軌定調:搜救主軸+任務導向訓練實務(OPORD 簡報格式做民用語域轉譯)。前置課程:ATAK(圖上指管)、Meshtastic(通訊)、無人機課(飛行)—— 本課教「人與人的協同協定」,那三門教工具。

## 指令
```bash
COURSE=courses/dgti make build audit verify
COURSE=courses/dgti COOKIES_BROWSER= uv run python src/build/fetch_meta.py
```

## 這門課的特殊紀律(改動前必讀)

1. **CAP 任務編號課程是骨幹**:O-5001(空地協同示範)、P-5110(影像判讀)、O-5003(證據攝影)幾乎是全網僅存的專門教學,數百次觀看是常態,why 都寫了「別無分號」的理由。CAP 是美國體系,導讀註明台灣無直接對應組織、方法可移植。
2. **選片紅線**:戰場實錄不收(無人機步兵協同的內容 9 成是實錄非教學,已盤點證實)、偽裝成課程的招生 teaser 不收、黑熊學院不收(政論訪談格式)。
3. **與 drone-course 的邊界**:那門 CH9 的六支搜救影片(ig7ssGRJFq8 等)本課禁用,視角區分:那門教飛、本課教組織。
4. **軍事來源的語域轉譯**:CH1 的 OPORD/MDMP 內容每支都帶轉譯提醒(敵情→災情、攻擊目標→搜索目標)。
5. **Steering Mariners 頻道大多 oEmbed 401 不可嵌入**(只有少數例外),策展時逐支預查過。
6. 張喬志(台中消防周邊)是中文骨幹人選,但他的內容多屬空拍操作;本課只收了花蓮合歡山空拍支援搜救紀實那支(他頻道唯一直接呈現空地配合現場的)。

## 框架陷阱
同 atak/pilot/firstaid/hamradio/drone 清單;tight/weak 禁用。

## 狀態(2026-08-10 完成)
- **verify 20/20、audit 0 錯誤、89 tests**;零跨章重複;CAP 最高佔比 15%
- **已上線 https://dgti-course.pages.dev**(Pages 專案 dgti-course)
- **GitHub**:kansasray/dgti-course(public,Discussions 已開,giscus 已填待裝 App)
