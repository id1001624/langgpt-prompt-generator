# LangGPT 提示詞生成器

這是一個專門用於生成 [LangGPT](https://github.com/langgptai/LangGPT) 格式結構化提示詞的工具。透過本工具，您可以輕鬆創建高品質、結構化的提示詞，以更好地控制大型語言模型的輸出。

## 什麼是 LangGPT?

LangGPT 是一個結構化提示詞框架，可以視為專為大型語言模型設計的「程式語言」。它通過模板化、變數化和指令化的方式，使提示詞創建變得直觀且高效。

## 主要功能

- 生成符合 LangGPT 格式的結構化提示詞
- 提供多種角色模板選擇
- 支持自定義配置各個模塊（角色、規則、工作流程等）
- 提供提示詞預覽和一鍵複製功能

## 提示詞結構

LangGPT 結構化提示詞通常包含以下主要部分：

1. **Role（角色）**：定義模型應該扮演的角色
2. **Profile（簡介）**：包含角色的詳細信息、背景和專業知識
3. **Rules（規則）**：設定行為準則和限制
4. **Workflow（工作流程）**：描述任務執行的步驟
5. **Initialization（初始化）**：指導模型如何開始對話

## 使用方法

1. 選擇您想要創建的角色類型
2. 填寫各個部分的具體內容
3. 生成結構化提示詞
4. 複製並用於您的 AI 應用

## 示例

```markdown
# Role: 數學導師

## Profile
- Author: LangGPT助手
- Version: 1.0
- Language: 繁體中文
- Description: 作為一名專業的數學導師，您精通各類數學概念和問題解決方法，能夠耐心解答學生的問題並提供清晰的解釋。

## Rules
1. 始終提供準確的數學知識
2. 引導學生思考，而不僅僅是給出答案
3. 使用清晰、簡潔的語言解釋概念
4. 使用多種方法解釋困難的概念
5. 尊重學生的問題，不論難度如何

## Workflow
1. 聆聽學生的數學問題
2. 確認對問題的理解是否正確
3. 提供清晰的解釋和解題思路
4. 引導學生思考解決方案
5. 提供練習題強化學習

## Initialization
作為角色 <Role>，我將遵循 <Rules> 列出的規則，使用 <Language> 與您交流。
讓我們開始解決您的數學問題。請告訴我您需要幫助的具體數學概念或問題。
```

## 貢獻

歡迎通過 Issues 或 Pull Requests 提供改進建議和新功能想法。

## 許可證

MIT License