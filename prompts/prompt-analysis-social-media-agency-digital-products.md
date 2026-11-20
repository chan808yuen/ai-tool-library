# Prompt 分析：AI 社交媒體代理 vs 數碼產品

日期：2026年11月20日

## 原 Prompt 1 — Start an AI Social Media Agency

> Act as a professional social media strategist. Create a 30-day Facebook and Instagram content calendar for a [business type]. Include engaging headlines, captions, calls to action, visual concepts, and target audiences. Identify which tasks can be automated using AI tools.

## 原 Prompt 2 — Create Digital Products

> Act as a digital product entrepreneur. Suggest 10 digital products I can create and sell using AI for [target audience]. Include the problem each product solves, suggested pricing, sales platforms, production steps, and a seven-day launch plan for the most promising idea.

## 分析

### 共通點

- 角色設定明確：第一段是社交媒體策略師，第二段是數碼產品創業者
- 要求具體輸出，不是空泛問答
- 都有方括號變數要填，未填就只會得到通用答案

### Prompt 1 — AI 社交媒體代理

- 優點：交付物明確，30 日曆、Facebook 及 Instagram、標題、文案、CTA、視覺概念、目標受眾、AI 自動化部分，元素齊全
- 缺點：未定發佈頻率，每日一篇還是每週三篇；未定目標，是增粉、引流還是成交；未定語調、品牌風格及預算
- 風險：[business type] 太闊，輸出容易流於通用內容曆

### Prompt 2 — 數碼產品

- 優點：由發想到執行一條龍，10 個產品、問題、定價、平台、製作步驟，最後還要選出最有潛力的一個做七日上線計劃，有篩選機制
- 缺點：[target audience] 未定，產品方向全靠 AI 猜；未定你的技能、時間及預算；定價沒有市場對照；10 個想法容易每項只講表面，欠缺驗證步驟
- 風險：未要求先驗證需求，直接跳到上線計劃

### 比較

- Prompt 2 較強，因為有優先排序及執行計劃，不只是清單
- Prompt 1 較實務，適合已有業務要做內容時用；Prompt 2 適合由零開始找產品方向時用

### 改良方向

- 填實方括號，再加三項：目標受眾的具體特徵、你的限制（時間、技能、預算）、成功標準
- Prompt 1 要加發佈頻率及每篇目的；Prompt 2 要加需求驗證一步，才做七日計劃
