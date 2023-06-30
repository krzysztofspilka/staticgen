---
title: Jspreadsheet
direct: https://github.com/jspreadsheet/pro
homepage: https://jspreadsheet.com/
examples:  https://jspreadsheet.com/docs/examples/
license: Commercial License
technology: Javascript, Jquery, Web Component
leading technology: Javascript
author: Paul Hodel
authorurl: https://www.linkedin.com/in/paulhodel
description: Jspreadsheet is a lightweight Vanilla JavaScript plugin that help developers to create exceptional web-based interactive data grid with spreadsheet controls.
---

#### Advantages

* Make rich web applications
* Improve your clients software experience
* Better CRUDS and beautiful UI
* Compatibility with excel, just copy and paste
* Powerful customizations

#### Download:

[Github](http://github.com/jspreadsheet/pro)
[Jspreadsheet Page](https://jspreadsheet.com/)

#### Usage:
```html
<html>
<script src="https://jspreadsheet.com/v10/jspreadsheet.js"></script>
<script src="https://jsuites.net/v5/jsuites.js"></script>
<link rel="stylesheet" href="https://jsuites.net/v5/jsuites.css" type="text/css" />
<link rel="stylesheet" href="https://jspreadsheet.com/v10/jspreadsheet.css" type="text/css" />

<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Material+Icons" />

<div id="spreadsheet"></div>

<script>
var data = [
  ['Google', 1998, 807.80],
  ['Apple', 1976, 116.52],
  ['Yahoo', 1994, 38.66],
];

jspreadsheet(document.getElementById('spreadsheet'), {
    data: data
    worksheets: [{
        minDimensions: [8,8],
    }],
});
</script>
</html>
```

#### Examples:

* [Creating a table from an external CSV file](https://jspreadsheet.com/products/csv-importer)
* [Calendar column type](https://jspreadsheet.com/docs/date)
* [Sorting by column](https://jspreadsheet.com/docs/sorting)
* [Currency and masking numbers](https://jspreadsheet.com/docs/format)
* [Working with dropdowns](https://jspreadsheet.com/docs/dropdown-and-autocomplete)
* [Including formulas on your spreadsheet](https://jspreadsheet.com/docs/formulas)