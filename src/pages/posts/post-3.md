---
layout: "../../layouts/MarkdownBaseLayout.astro"
title: "我的部落格文章第三篇"
author: "前端菜雞"
pubDate: "2024-09-08"
description: "這是我的第三篇astro 部落格文章"
image: 
    url: "../../../public/picture.jpg"
    alt : "demo picture"
tags: ["react", "Web Development", ]
---

### React 介紹文章

# React 介紹

## 什麼是 React？

React 是一個由 Facebook 開發和維護的開源 JavaScript 庫，用於構建用戶界面。它的設計目的是提供一個高效、靈活且聲明式的方式來構建 UI 組件。React 最初由 Jordan Walke 於 2013 年開發，並迅速成為現代前端開發的重要工具。

## React 的核心特性

1. **組件化**：
   React 的核心概念是組件。你可以將 UI 拆分成可重用的組件，每個組件都封裝了自己的邏輯和樣式。這使得代碼更加模塊化和可維護。

2. **虛擬 DOM**：
   React 使用虛擬 DOM 技術來提升性能。虛擬 DOM 是一個輕量級的 JavaScript 表示，用於描述實際 DOM 的狀態。React 會計算虛擬 DOM 和實際 DOM 之間的差異，並僅更新需要變化的部分，從而提高應用程序的性能。

3. **聲明式 UI**：
   在 React 中，你可以聲明 UI 應該如何顯示，而不是如何更新它。這使得 UI 的設計更加直觀和易於理解。

4. **單向數據流**：
   React 提供了單向數據流的機制，即數據只能從父組件流向子組件。這使得數據流動變得可預測和容易管理。

## React 的安裝與設置

### 1. 使用 CDN 安裝

你可以通過在 HTML 文件中引入 React 的 CDN 來快速開始使用 React：

```html
<script src="https://unpkg.com/react/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom/umd/react-dom.development.js"></script>
```


