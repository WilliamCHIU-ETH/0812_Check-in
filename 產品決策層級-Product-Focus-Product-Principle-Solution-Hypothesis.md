---
title: 產品決策層級：Product Focus、Product Principle 與 Solution Hypothesis
status: Provisional Note
scope: 可跨產品重用的概念草稿
---

# 產品決策層級：Product Focus、Product Principle 與 Solution Hypothesis

這份筆記用來避免把「產品要解決什麼」、「如何做取捨」與「某個方案能否奏效」混成同一個問題。

## 四個決策層級

| 層級 | 核心問題 | 產物 | 是否需要驗證 |
|---|---|---|---|
| Product Focus | 產品主要要把哪一件事做好？ | 核心責任與邊界 | 需要市場與使用者證據持續校正 |
| Product Principle | 遇到取捨時，要優先守住什麼？ | 穩定的產品準則 | 是 owner decision，但需觀察長期代價 |
| Product Rule | Principle 如何變成可審查的規則？ | Flow、內容與功能規則 | 需透過案例與產品結果修正 |
| Solution Hypothesis | 在特定情境採用這個方案，預期改變什麼？ | 可驗證的因果假設 | 必須驗證 |

## Lite 範例

- **Product Focus 候選**：協助新手完成一個初步投資判斷。
- **Product Principle**：簡單。
- **Product Rule 候選**：一個畫面只協助使用者完成一項判斷；進階資訊在需要時再展開。
- **Solution Hypothesis**：若只呈現完成當下判斷所需的資訊，新手能更快回答方向與主要依據，而且不降低理解正確性。

「簡單」不能同時替以上四層回答所有問題。否則它會被拿來證明服務對象、需求、介面方案與產品效果，最後失去作為取捨準則的作用。

## PMF 能證明什麼

已達 Product-Market Fit 的產品，可以提供高品質的實務案例，但 PMF 驗證的是整體產品組合，不是其中每一個介面決策。

| 證據類型 | 可以支持 | 不能直接支持 |
|---|---|---|
| PMF product | 整體產品與某個市場形成了匹配 | 單一 Flow 或 UI pattern 造成 PMF |
| Confirmed observation | 產品目前實際採用某個做法 | 原團隊為什麼這樣決定 |
| Stated rationale | 團隊公開宣稱的設計理由 | 該理由已被嚴格因果驗證 |
| Repeated pattern | 多個產品反覆採用相似做法 | 這個做法一定適用於不同 context |
| Inferred rationale | 對背後假設形成可討論推論 | 原團隊真的做過相同假設或實驗 |
| Transfer hypothesis | 定義移植到自己產品後的預期 | 移植後必然成立 |

因此，比較精確的說法是：

> 成熟產品中的 Flow 與 UI pattern，比從空白畫布憑空想像具有更強的實務先驗，值得優先成為候選 hypothesis；但仍需在自己的產品情境重新驗證。

## 從成熟產品到自己的 hypothesis

研究時可以依序回答：

1. **Observation**：它實際做了什麼？
2. **Friction**：這可能降低哪種認知、心理或操作成本？
3. **Trade-off**：它隱藏、延後、刪除或犧牲了什麼？
4. **Context**：這項決策成立需要哪些條件？
5. **Transfer**：哪些部分能轉譯到自己的產品？
6. **Hypothesis**：預期改變哪個使用者結果？
7. **Validation**：要用什麼證據確認或推翻？

## 常見誤區

- 把 Product Principle 寫成產品需求已成立的證據。
- 把「成功產品這樣做」寫成「這個做法造成產品成功」。
- 只複製最後畫面，沒有理解任務、商業模式與技術條件。
- 只找支持既定 Principle 的成功案例，沒有找反例或失敗代價。
- 把自己反推的 rationale 寫成原團隊已驗證的事實。
- 用操作步驟變少取代使用者是否理解、是否能完成正確判斷。

## 使用原則

這份筆記目前是 provisional note。未來若建立「一個產品可能有哪些東西」的獨立 repo，可將它移入該知識體系，並補上 Product Intent、Target User、Job、Value Proposition、Business Model、Metric 與驗證層級之間的關係。
