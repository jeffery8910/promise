深入淺出 Promise 與 React Suspense - 互動式教學網站
[Live Demo](https://jeffery8910.github.io/promise/)
這是一個專為解釋 throw new Promise(() => {}) 概念而設計的互動式單頁面教學網站。透過實際操作與視覺化呈現，讓開發者能深刻理解這個看似奇特卻十分有用的 JavaScript/React 技巧。

🚀 這個專案解決了什麼問題？
在現代前端框架（特別是 React）中，非同步處理是核心概念。React Suspense 機制讓我們能優雅地處理資料載入狀態，但其背後的原理——特別是 throw Promise——對許多人來說可能有些抽象。
本專案聚焦於一個極端的例子：throw new Promise(() => {})。這行程式碼會建立一個永遠處於等待中 (Pending) 的 Promise，當它與 Suspense 結合時，可以創造出一個「永不結束的載入狀態」。
這個互動式網站透過三個循序漸進的步驟，讓您：
 * 看到 Promise 狀態的變化。
 * 體驗 一個永遠無法被決議 (resolve/reject) 的 Promise。
 * 理解 它如何影響 React Suspense 的行為。
✨ 核心教學概念
在這個網站中，您將會學到並親手體驗：
 * 基本 Promise: 回顧一個標準 Promise 如何從 pending 走向 fulfilled (成功) 或 rejected (失敗)。
 * 永遠等待的 Promise: 深入解析 new Promise(() => {}) 語法，以及為什麼它會產生一個永不改變狀態的 Promise。
 * React Suspense 模擬: 在一個模擬的環境中，觀察當元件拋出 (throw) 一個「會完成的 Promise」和一個「永遠等待的 Promise」時，Suspense 的 fallback UI 會如何反應。
 * 應用場景: 了解這項技術的實際用途，例如在 Storybook 中展示元件的載入狀態，或在特定情境下刻意凍結 UI 更新。
🛠️ 使用的技術
 * HTML: 網頁結構。
 * Tailwind CSS: 快速打造現代化、響應式的 UI 介面。
 * JavaScript (ES6+): 實現所有互動邏輯與 Promise 的行為模擬。
🖥️ 如何在本地端運行
本專案沒有複雜的建置流程，您可以直接：
 * Clone 或下載此專案。
 * 用您的瀏覽器開啟 index.html 檔案即可。
git clone https://github.com/jeffery8910/promise.git
cd promise
# 直接在瀏覽器中開啟 index.html

歡迎提供回饋或提出問題！
