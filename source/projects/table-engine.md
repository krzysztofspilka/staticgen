---
title: Table Engine
repo: bennyboer/table-engine
homepage: https://github.com/bennyboer/table-engine
examples: https://bennyboer.github.io/table-engine/
license: MIT
author: Benjamin Eder
authorurl: https://github.com/bennyboer
description: Library to visualize huge tables in web environments
---

## Introduction

The Table Engine is a library to visualize huge tables in web environments with high-performance rendering.
Traditional DOM-based libraries are too slow for huge amounts of data and conceptually lack good support for things like fixed rows and columns.
Most libraries seem to be either spreadsheets or data tables, while with this library you're able to implement every form of table.

## Demo

![demo-image](https://github.com/bennyboer/table-engine/blob/main/docs/img/demo-screenshot.png)

Check out the demo application at https://bennyboer.github.io/table-engine/ that shows more of a spreadsheet use-case.
Keep in mind that you're not bound to a spreadsheet use-case.
You can easily implement a data table as well.

## Features

### General features

* Zooming in/out
* Excel-like borders
* High-performance HTML5 canvas rendering
* Selection copy handle

### Cell Features

* Predefined cell renderers/editors
  * Text (with line wrapping)
  * Image
  * Checkbox
  * Combobox/dropdown selection
  * Rating (stars)
  * ...
* Custom cell renderers/editors
  * Either based on HTML5 canvas...
  * ... or traditional DOM-renderers
* Editing cell content
* Cell selection
  * Select only a single cell
  * Select multiple cells at once
  * Select multiple cell ranges by pressing Ctrl while clicking and dragging
* Merging/splitting cell ranges to a single cell
* Copying cell contents using Ctrl+C
* Excel-like Keyboard Navigation
  * Shift to extend the selection
  * Ctrl to jump to the end or start of the row/column
  * Tab and Shift-Tab to change the primary selected cell in a selected cell range

### Row/column Features

* Fixing/freezing rows/columns
* Resizing rows/columns
* Insert rows/columns
* Remove rows/columns
* Hide/show rows/columns
* Reordering, sorting and filtering needs to be implemented by the users of this library

## Install

```bash
npm install table-library
```

## Usage

Check out the repository under https://github.com/bennyboer/table-engine and especially have a look at the Angular example at https://github.com/bennyboer/table-engine/tree/main/example.

## License

[MIT](http://opensource.org/licenses/MIT)
