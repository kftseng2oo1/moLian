# 🖋️ 墨聯 AI 對聯產生器

輸入關鍵字，由 Gemini 創作合乎平仄的對聯（上聯、下聯、橫批），排版成紅底書法圖片。

**線上使用**：https://kftseng2oo1.github.io/moLian/

## 主要功能
- 字數：五字、六字、七字或不限
- 規則：上下聯字數相同，上聯末字仄聲、下聯末字平聲，橫批四字，附簡短解析
- 「🔍 查詢可用模型」自動挑選可用的 Gemini 模型
- 結果畫成對聯圖：💾 存 PNG／SVG、📤 分享
- ⭐ 收藏歷史紀錄，可重新載入或刪除

## 使用方式
1. 填入 Gemini API Key（`AIza` 開頭）並按「記住」
2. 輸入關鍵字、選字數
3. 按「生成對聯」

## 技術與依賴
- 單檔 HTML PWA（`index.html` 內含全部 HTML/CSS/JS），`manifest.json` + `sw.js` 提供安裝到主畫面與離線快取。
- Google Gemini API（直連 `generativelanguage.googleapis.com`）
- 本機資料：`gemini_api_key`、`couplet_history`
