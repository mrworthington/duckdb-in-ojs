# duckdb-in-ojs

This is a fork of [Bob Rudis's Example of using DuckDB in Quarto OJS blocks](https://github.com/hrbrmstr/duckdb-in-ojs). It's reorganized as a quarto dashboard with some value boxes to show a relatively weird bug in quarto dashboards whenever a table is rendered with Observable's `Inputs.table()`. The core issue is that whenever row height is explicitly set in the quarto dashboard, it prohibits the table rendered with `Inputs.table()` from scrolling. If Row height isn't set, the table scrolls as expected.

* The file named `index.qmd` does not have row height set in the quarto dashboard.
* The file named "index_2.qmd" does explicitly set a row height.

To see Bob's original quarto doc of using DuckDB in Quarto OJS blocks, visit this repo: https://github.com/hrbrmstr/duckdb-in-ojs

To see the version of that repo built on Observable's platform, visit this link: https://observablehq.com/@hrbrmstr/duckdb-observable-companion-to-the-quarto-version
