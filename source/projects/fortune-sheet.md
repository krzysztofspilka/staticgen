---
title: FortuneSheet
repo: ruilisi/fortune-sheet
direct: https://github.com/ruilisi/fortune-sheet
homepage: https://ruilisi.github.io/fortune-sheet-demo
examples: https://ruilisi.github.io/fortune-sheet-demo
license: MIT
npm: \@fortune-sheet/react
technology: TypeScript
leading technology: javascript
author: Suzhou Ruilisi Technology Co., Ltd
authorurl: https://ruilisi.com/
description: FortuneSheet is a drop-in javascript spreadsheet library that provides rich features like Excel and Google Sheets.
---

## Introduction
🚀FortuneSheet is a drop-in javascript spreadsheet library that provides rich features like Excel and Google Sheets.
The goal of FortuneSheet is to make a feature-rich, easy-to-configure online spreadsheet that you can use out-of-the-box.
This project is originated from Luckysheet and has inherited many code from it. Lots of efforts have done to translate the whole project to typescript (still in progress), and solved problems in the design of the original project.

## Purpose

The goal of `FortuneSheet` is to make a feature-rich, easy-to-configure online spreadsheet that you can use out-of-the-box.
This project is originated from [Luckysheet](https://github.com/mengshukeji/Luckysheet) and has inherited many code from it. Lots of efforts have done to translate the whole project to typescript (still in progress), and solved problems in the design of the original project.

## Improvements to Luckysheet

- Written fully in typescript.
- You can now use `import` / `require` to use the library.
  ```js
  import { Workbook } from '@fortune-sheet/react'
  ```
- Multiple instance on the same page is supported.
- Dropped `jQuery` dependency, uses native `React` / `Vue` + `immer` to manage the dom and state.
- Changed to a forked [handsontable/formula-parser](https://github.com/handsontable/formula-parser) to handle formula calculations.
- Optimized the dom structure.
- Replaced icons from `iconfont` with SVGs, as `iconfont` icons are inconvenient to update for other maintainers.
- No visible elements is created outside container.
- Never stores data in the `window` object.

## Features

- Data structure is mostly compatible with Luckysheet (see [Migration Guide](#migrating-data-from-luckysheet)).
- **Formatting**: style, text alignment and rotation, text truncation, overflow, automatic line wrapping, multiple data types, cell segmentation style
- **Cells**: multiple selection, merge cells
- **Row & column**: insert, delete rows or columns
- **Operation**: copy, paste, cut, hot key
- **Formulas & Functions**: Built-in formulas
