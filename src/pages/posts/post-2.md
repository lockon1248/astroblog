---
layout: "../../layouts/MarkdownBaseLayout.astro"
title: "我的部落格文章第二篇"
author: "前端菜雞"
pubDate: "2024-09-08"
description: "這是我的第二篇astro 部落格文章"
image: 
    url: "../../../public/picture.jpg"
    alt : "demo picture"
tags: ["vue", "Web Development", ]
---

# Vue.js 介紹

## 什麼是 Vue.js？

Vue.js（簡稱 Vue）是一個漸進式的 JavaScript 框架，用於構建用戶界面。它由尤雨溪（Evan You）於 2014 年開發，旨在提供一個簡單、靈活且高效的前端開發體驗。Vue 的設計理念是「漸進式」的，即你可以逐步引入其功能，而不需要完全重構現有的代碼。

## Vue 的核心特性

1. **響應式數據綁定**：
   Vue 提供了簡單的數據綁定機制，讓你的數據和視圖保持同步。當數據變化時，視圖會自動更新，反之亦然。這使得用戶界面的開發變得更加簡單和高效。

2. **組件化**：
   Vue 讓開發者可以將應用程序分解成小的、可重用的組件。每個組件都封裝了自己的模板、邏輯和樣式，使得代碼更加結構化和可維護。

3. **虛擬 DOM**：
   Vue 使用虛擬 DOM 技術來提高性能。虛擬 DOM 是一個輕量級的 JavaScript 表示，用於描述實際 DOM 的狀態。當數據發生變化時，Vue 會計算出虛擬 DOM 和實際 DOM 之間的差異，並僅更新那些真正需要變化的部分。

4. **指令**：
   Vue 提供了一些內置指令（如 `v-if`、`v-for`、`v-bind`、`v-model` 等），這些指令可以在模板中用於控制渲染和數據綁定。

## Vue 的安裝與設置

### 1. 使用 CDN 安裝

你可以通過在 HTML 文件中引入 Vue 的 CDN 來快速開始使用 Vue：

```html
<script src="https://cdn.jsdelivr.net/npm/vue@2"></script>


