# Prompt Framework Advisory Reference

This reference contains the detailed output formats and templates for the `prompt-framework-advisory` skill.

## Framework 1: Reverse Questioning

Use this when the user asks for a large plan, thesis section, business analysis, strategy, report, or complex deliverable but the information is incomplete.

### Output Format

```markdown
## 一、目前需求判讀

- **使用者想完成的事：**
- **目前已知背景：**
- **初步判斷：**

---

## 二、資訊真空地帶

| 類別 | 缺失或模糊處 | 可能造成的問題 |
|---|---|---|
| 目標 |  |  |
| 對象 |  |  |
| 資料 |  |  |
| 格式 |  |  |
| 成功標準 |  |  |

---

## 三、潛在假設與影響

| 潛在假設 | 若假設錯誤，可能造成的影響 |
|---|---|
|  |  |

---

## 四、請先回答這 3-5 個關鍵問題

1. 
2. 
3. 
4. 
5. 
```

### User Template

```markdown
### 背景資料與現有需求：
[請貼上目前現有的不完整資料、想法或狀況]

### 最終任務目標：
[請說明希望 AI 最終產出什麼]
```

## Framework 2: Anti-Sycophancy Five-Advisor Council

Use this for decision evaluation, business model pressure testing, strategic planning, proposal review, product/course positioning, and risk analysis.

### Advisor Roles

**顧問 1：反駁者（The Contrarian）**

- 這個想法最可能死在哪裡？
- 哪些假設太樂觀？
- 市場上有沒有類似失敗案例？
- 哪些成本、競爭、法規或執行問題被低估？

**顧問 2：本質追問者（The First-Principles Questioner）**

- 這件事的底層需求是什麼？
- 使用者真的需要這個嗎？
- 這是痛點、癢點，還是自嗨點？
- 若拿掉品牌、技術與話術，本質價值還剩什麼？

**顧問 3：擴張者（The Expander）**

- 是否有更好的切入市場？
- 是否能換商業模式？
- 是否能跨界整合？
- 是否有更高槓桿的產品、服務或通路？

**顧問 4：外行人（The Outsider）**

- 一般人聽得懂嗎？
- 為什麼我要買？
- 我不買會怎樣？
- 是否被說得太複雜？
- 價格、流程、承諾是否合理？

**顧問 5：無情的執行者（The Ruthless Executor）**

- 明天第一步做什麼？
- 誰負責？
- 要花多少錢？
- 要多久驗證？
- 成功與失敗的判斷標準是什麼？
- 哪些內容現在就該砍掉？

### Output Format

```markdown
## 五人 AI 智囊團壓力測試

### 一、顧問 1：反駁者（The Contrarian）

**尖銳判斷：**

**可能失敗點：**

**被低估的風險：**

---

### 二、顧問 2：本質追問者（The First-Principles Questioner）

**底層追問：**

**真需求 / 偽需求判斷：**

**核心假設檢查：**

---

### 三、顧問 3：擴張者（The Expander）

**被漏掉的機會：**

**可替代路徑：**

**跨界組合建議：**

---

### 四、顧問 4：外行人（The Outsider）

**一般用戶會問：**

**聽不懂或不買單的地方：**

**常識檢查：**

---

### 五、顧問 5：無情的執行者（The Ruthless Executor）

**落地檢查：**

**應該立刻砍掉的空談：**

**明天第一步：**

---

## 智囊團主席總結

| 評估項目 | 結論 |
|---|---|
| 值不值得做 |  |
| 核心修正 |  |
| 最大風險 |  |
| 缺乏的驗證證據 |  |
| Next Action |  |

### 最終判斷

[請給出客觀、直接、可執行的結論。]
```

### User Template

```markdown
### 我的提案 / 決策內容如下：
[請詳細寫下你的想法、商業模式或正在糾結的決策]
```

## Combined Use Rule

When the user's request is both ambiguous and strategically important:

1. Use Framework 1 first to clarify background, goals, constraints, and success criteria.
2. After the user answers, use Framework 2 to run the five-advisor pressure test.

Do not pressure-test a strategy with insufficient facts unless explicitly asked to provide a provisional critique.
