---
title: frappe-datatable
repo: frappe/datatable
homepage: https://frappe.io/datatable
examples: https://frappe.io/datatable
license: MIT
author: Frappe Technologies Pvt. Ltd.
authorurl: https://frappe.io
description: A simple, modern and interactive datatable library for the web
---

## Introduction

Frappe DataTable is a simple, modern and interactive datatable library for displaying tabular data. Originally built for [ERPNext](https://github.com/frappe/erpnext), it can be used to render large amount of rows without sacrificing performance and has the basic data grid features like inline editing and keyboard navigation. It does not require jQuery, unlike most data grids out there.

## Demo

![datatable-demo-2](https://user-images.githubusercontent.com/9355208/40740030-5412aa40-6465-11e8-8542-b0247ab1daac.gif)

## Features

### Cell Features

* Custom Formatters
* Inline Editing
* Mouse Selection
* Copy Cells
* Keyboard Navigation
* Custom Cell Editor

### Column Features

* Reorder Columns
* Sort by Column
* Remove / Hide Column
* Custom Actions
* Resize Column
* Flexible Layout

### Row Features

* Row Selection
* Tree Structured Rows
* Inline Filters
* Large Number of Rows
* Dynamic Row Height

## Install

```bash
yarn add frappe-datatable
# or
npm install frappe-datatable
```

> Note: [`sortablejs`](https://github.com/RubaXa/Sortable) is required to be installed as well.

## Usage

```js
const datatable = new DataTable('#datatable', {
  columns: [ 'First Name', 'Last Name', 'Position' ],
  data: [
    [ 'Don', 'Joe', 'Designer' ],
    [ 'Mary', 'Jane', 'Software Developer' ]
  ]
});
```

## Contribution

* `yarn start` - Start dev server
* Open `index.html` located in the root folder, and start development.
* Run `yarn lint` before committing changes
* This project uses [commitizen](https://github.com/commitizen/cz-cli) for conventional commit messages, use `yarn commit` command instead of `git commit`

## Read the blog

[Making a new datatable for the web](https://medium.com/frapp%C3%A9-thoughts/things-i-learned-building-a-library-for-the-web-6846a588bf53)

## License

[MIT](http://opensource.org/licenses/MIT)
