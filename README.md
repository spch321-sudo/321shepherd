# 321牧養服事 v1.0.202610071338

## v1.3（2026-10-20）新增「美圖工作室」（與創世記至彼得後書同一套）
- **哪裡進去**：原有的「做成美圖」入口，現在開的就是完整的美圖工作室。「我的作品」在美圖工作室裡的「我的作品」按鈕。
- **做什麼**：9 種版型、5 種尺寸、6 種外框；相片可用內建圖庫、免費圖庫或自己的相簿；**AI 生成美圖**（寫好提示詞，可在 App 內直接生成，或複製到 Gemini／ChatGPT／豆包／Pollinations）；**AI 生成配樂**（Suno／MusicFX／Stable Audio 提示詞）；卡片字體（明體／黑體／楷體／圓體）與文字顏色；詩歌配樂、錄音、卡片影片、自拍影片。
- **自拍相機打不開**時會說清楚原因並給兩條退路；離開去第三方工具再回來，自動接回原位。
- 這一版是獨立模組（自己的作品與設定存在本機，不動本 App 原有資料）。沒有 AI 影片（已決定不做）。
- 上傳：index.html（有的有 sc.html／en.html）、sw.js、README.md 一起覆蓋。

321學神院・服事技能課程 PWA（繁體／简体／English）。

## 發佈到 GitHub Pages
1. 在 spch321-sudo 帳號建立（或打開）儲存庫 `321shepherd`。
2. 把本資料夾裡**所有檔案**（共 21 個，含隱藏檔 .nojekyll）直接放在儲存庫根目錄，不要外包資料夾。
3. Settings → Pages → Branch 選 main／root，儲存。
4. 網址：https://spch321-sudo.github.io/321shepherd/

## 更新
新版本整包覆蓋即可；sw.js 版本號改變，使用者打開 App 會自動更新。

## 檔案
index.html 主程式｜media.js 美圖影音｜c-zh／c-zs／c-en.json 課程與工具｜lang-zs／lang-en.json 介面字串｜sw.js 離線與自動更新｜manifest.json、icon-*、apple-touch-icon、favicon 圖示｜hero.jpg、hero-s.jpg 首頁主視覺｜music.json 配樂清單｜version.json 版本

經文：新標點和合本（神版）；English: World English Bible（engwebp）。
願一切榮耀歸給耶穌。
