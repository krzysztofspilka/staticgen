---
title: Lemonade Data Grid
repo: lemonadejs/datagrid
direct: https://github.com/lemonadejs/data-grid
homepage: https://lemonadejs.net/components/data-grid
examples:  https://lemonadejs.net/components/data-grid
license: MIT
technology: Javascript, Jquery, Web Component
leading technology: Javascript
author: Paul Hodel
authorurl: https://www.linkedin.com/in/paulhodel
description: The LemonadeJS Data Grid is a lightweight (2KBytes compressed) and highly customizable JavaScript component that provides a free (MIT) solution for rendering data in rows and columns. It offers features like search, filter, pagination, and in-cell editing, making it ideal for building complex interfaces.
---

#### Advantages

* Make rich web applications
* Light-weight and Fast
* Improve your clients software experience
* Powerful customizations
* Improve display of data

#### Download:

[Github](https://github.com/lemonadejs/data-grid)
[Download](https://github.com/lemonadejs/data-grid/archive/master.zip)

#### Usage:
```html
<html>
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/lemonadejs/dist/lemonade.min.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@lemonadejs/datagrid/dist/index.min.js"></script>

<div id="data-grid"></div>

<script>
let data = [
  { id: 1, person: 'Maria', age: 28 },
  { id: 2, person: 'Carlos', age: 33 }
]

let columns = [
  { name: 'person', title: 'Name' },
  { name: 'age', title: 'Age' }
]


Datagrid(document.getElementById('data-grid'), {
  data: data,
  columns: columns
})
</script>
</html>
```

#### Examples:

* [Creating a basic table](https://lemonadejs.net/components/data-grid#example-1)
* [Working with large data sets](https://lemonadejs.net/components/data-grid#example-2)
* [Rendering customized components inside the Data Grid](https://lemonadejs.net/components/data-grid#example-3)
