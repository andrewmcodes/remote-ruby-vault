---
cssClasses: row-lines, row-alt
---

```dataview
table rows.file.link AS Episodes, "" as ""
from #episode and !"_assets"
where guests
group by guests
sort number desc
```
