```dataview
TABLE length(file.inlinks) as "Data Points", length(file.outlinks) as "Related Themes"
FROM "codes"
SORT length(file.inlinks) DESC
```