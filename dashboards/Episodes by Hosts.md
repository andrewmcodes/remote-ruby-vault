---
cssClasses: row-lines, row-alt
---

```dataview
table rows.file.link AS Episodes, "" as ""
from #episode and !"_assets"
group by panelists
sort number desc
```
