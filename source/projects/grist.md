---
title: Grist
repo: gristlabs/grist-core
homepage: https://www.getgrist.com
license:  Apache-2.0
author: Grist Labs
authorurl: https://github.com/gristlabs
description: Grist is the evolution of spreadsheets.
---

Grist is a modern relational spreadsheet. It combines the flexibility of a spreadsheet with the robustness of a database.
way, it has the following features:

#### Features

Grist is a hybrid database/spreadsheet, meaning that:

  - Columns work like they do in databases: they are named, and they hold one kind of data.
  - Columns can be filled by formula, spreadsheet-style, with automatic updates when referenced cells change.

This difference can confuse people coming directly from Excel or Google Sheets. Give it a chance! There's also a [Grist for Spreadsheet Users](https://www.getgrist.com/blog/grist-for-spreadsheet-users/) article to help get you oriented. If you're coming from Airtable, you'll find the model familiar (and there's also our [Grist vs Airtable](https://www.getgrist.com/blog/grist-v-airtable/) article for a direct comparison).

Here are some specific feature highlights of Grist:

  * Python formulas.
    - Full [Python syntax is supported](https://support.getgrist.com/formulas/#python), including the standard library.
    - Many [Excel functions](https://support.getgrist.com/functions/) also available.
    - An [AI Assistant](https://www.getgrist.com/ai-formula-assistant/) specifically tuned for formula generation (using OpenAI gpt-3.5-turbo or [Llama](https://ai.meta.com/llama/) via <a href="https://github.com/abetlen/llama-cpp-python">llama-cpp-python</a>).
  * A portable, self-contained format.
    - Based on SQLite, the most widely deployed database engine.
    - Any tool that can read SQLite can read numeric and text data from a Grist file.
    - Enables [backups](https://support.getgrist.com/exports/#backing-up-an-entire-document) that you can confidently restore in full.
    - Great for moving between different hosts.
  * Can be displayed on a static website with [`grist-static`](https://github.com/gristlabs/grist-static) – no special server needed.
  * A self-contained desktop app for viewing and editing locally: [`grist-desktop`](https://github.com/gristlabs/grist-desktop).
  * Convenient editing and formatting features.
    - Choices and [choice lists](https://support.getgrist.com/col-types/#choice-list-columns), for adding colorful tags to records.
    - [References](https://support.getgrist.com/col-refs/#creating-a-new-reference-list-column) and reference lists, for cross-referencing records in other tables.
    - [Attachments](https://support.getgrist.com/col-types/#attachment-columns), to include media or document files in records.
    - Dates and times, toggles, and special numerics such as currency all have specialized editors and formatting options.
    - [Conditional Formatting](https://support.getgrist.com/conditional-formatting/), letting you control the style of cells with formulas to draw attention to important information.
  * Drag-and-drop dashboards.
    - [Charts](https://support.getgrist.com/widget-chart/), [card views](https://support.getgrist.com/widget-card/) and a [calendar widget](https://support.getgrist.com/widget-calendar/) for visualization.
    - [Summary tables](https://support.getgrist.com/summary-tables/) for summing and counting across groups.
    - [Widget linking](https://support.getgrist.com/linking-widgets/) streamlines filtering and editing data.
    Grist has a unique approach to visualization, where you can lay out and link distinct widgets to show together,
    without cramming mixed material into a table.
    - [Filter bar](https://support.getgrist.com/search-sort-filter/#filter-buttons) for quick slicing and dicing.
  * [Incremental imports](https://support.getgrist.com/imports/#updating-existing-records).
    - Import a CSV of the last three months activity from your bank...
    - ...and import new activity a month later without fuss or duplication.
  * Integrations.
    - A [REST API](https://support.getgrist.com/api/), [Zapier actions/triggers](https://support.getgrist.com/integrators/#integrations-via-zapier), and support from similar [integrators](https://support.getgrist.com/integrators/).
    - Import/export to Google drive, Excel format, CSV.
    - Link data with [custom widgets](https://support.getgrist.com/widget-custom/#_top), hosted externally.
    - Configurable outgoing webhooks.
  * [Many templates](https://templates.getgrist.com/) to get you started, from investment research to organizing treasure hunts.
  * Access control options.
    - (You'll need SSO logins set up to make use of these options; [`grist-omnibus`](https://github.com/gristlabs/grist-omnibus) has a prepackaged solution if configuring this feels daunting)
    - Share [individual documents](https://support.getgrist.com/sharing/), workspaces, or [team sites](https://support.getgrist.com/team-sharing/).
    - Control access to [individual rows, columns, and tables](https://support.getgrist.com/access-rules/).
    - Control access based on cell values and user attributes.
  * Self-maintainable.
    - Useful for intranet operation and specific compliance requirements.
  * Sandboxing options for untrusted documents.
    - On Linux or with Docker, you can enable [gVisor](https://github.com/google/gvisor) sandboxing at the individual document level.
    - On macOS, you can use native sandboxing.
    - On any OS, including Windows, you can use a wasm-based sandbox.
  * Translated to many languages.
  * `F1` key brings up some quick help. This used to go without saying, but in general Grist has good keyboard support.
  * We post progress on [𝕏 or Twitter or whatever](https://twitter.com/getgrist) and publish [monthly newsletters](https://support.getgrist.com/newsletters/).

#### Preview:

https://user-images.githubusercontent.com/118367/151245587-892e50a6-41f5-4b74-9786-fe3566f6b1fb.mp4