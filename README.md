# Xypex in Taiwan by Synercon

**Xypex（賽柏斯）滲透結晶型混凝土防水技術 — 台灣獨家總代理 進協和國際有限公司（Synercon International LTD.）**

線上網站：https://maxlu1980.github.io/Xypex-in-Taiwan-by-Synercon/

本網站以單一網頁呈現 Xypex 在台灣的完整技術與應用：沉浸式 3D 工地、兩本產品指南、技術資料、同類產品逐項數值對照、生命週期成本與可下載的 Word／PDF 文件。介面提供 English 與繁體中文（台灣）。

---

## 主要內容

**沉浸式 3D 工地（首頁）**
- 11 個應用領域：污水收集與處理、淨水廠、蓄水結構物、一般建築基礎、隧道、橋梁、電力與公用設施、水壩與灌溉、海事結構物、預鑄結構物、工業結構物
- 9 個子工地：人孔與下水道、地下停車場、深開挖連續壁、連續壁施工中、浴室牆面壁癌與白華、NATM 噴凝土、明挖覆蓋、沉埋管、農業設施
- 施工班組依實際工序作業：表面處理、攪拌、刷塗、噴塗、養護、Patch'n Plug 止漏、Dry-Pac 填塞、Admix 投料
- 即時時間與天氣、依觀看地點計算的太陽、月亮（NASA 月面影像）、星空與行星
- 畫質分級（自動 … 極致）：多重取樣、時間性抗鋸齒、環境遮蔽、螢幕空間反射、延遲光源與陰影、體積光
- 操控：滑鼠、鍵盤、觸控（旋轉、平移、縮放、飛往）

**產品指南**
- 表面塗佈・修補與配件：Xypex Concentrate、Modified、Concentrate Dry-Pac、Patch'n Plug、Megamix I／II、Gamma Cure、Xycrylic Admix、Quickset、FCM 80
- 摻料：Xypex Admix C-Series（C-500／C-1000／C-2000 及 NF 版）、Bio-San C500
- 應用情境、施工程序、3D 模型（含 X-ray）、實作模擬器；人員、材料桶與首頁工地為同一套模型
- 「工地現場」視窗可直接進入各領域的子工地

**比較與文件**
- 同類產品逐項數值對照（附每筆數值的來源與讀取日期，只做同基準比較）
- 生命週期成本
- 文件中心：產生 Word／PDF（使用 `fonts/` 內的字型）

## 檢核與版本

- [全面需求檢核報告](docs/REVIEW.md)：自 2026-11-09 起的全部需求、對應改善與驗證結果
- [版本紀錄](CHANGELOG.md)
- 目前版本：**v47**（2026-11-20）

## 檔案結構

```
index.html                 網站本體（單一檔案；three.js r147 由 jsDelivr 載入，網頁字型由 Google Fonts 載入）
fonts/                     Word／PDF 文件產生用字型（Roboto、Noto Sans TC）及授權
docs/REVIEW.md             全面需求檢核報告
CHANGELOG.md               版本紀錄
THIRD-PARTY-NOTICES.md     第三方資料與字型授權聲明
.nojekyll                  GitHub Pages 直接提供靜態檔案
```

## 本機瀏覽

```bash
python3 -m http.server 8000
# 開啟 http://localhost:8000/
```

建議使用桌上型 Chrome 或 Edge 最新版（WebGL 2）；手機可瀏覽，3D 畫質會依裝置效能自動調整。

## 商標與版權

Xypex、Xypex Concentrate、Modified、Patch'n Plug、Megamix、Admix C-Series、Bio-San 等為 Xypex Chemical Corporation 之商標。產品標籤圖樣取自 Xypex 官方網站。本網站由 Xypex 台灣獨家總代理 進協和國際有限公司（Synercon International LTD.）製作。第三方資料與字型的授權見 [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md)。

---

## English summary

*Xypex in Taiwan by Synercon* presents Xypex crystalline concrete waterproofing in Taiwan as one web page: an immersive 3D construction site covering all eleven Xypex areas of application and nine sub-sites, two product guides (surface-applied coatings, repairs & accessories; admixtures) with application scenarios, procedures, 3D models and a hands-on simulator, a like-for-like comparison with competing products (every value with its source and access date), life-cycle cost and Word/PDF documents. English and Traditional Chinese (Taiwan). Built by Synercon International LTD., Xypex Authorized Exclusive Distributor of Taiwan.
