---
date: 2023-09-04
type: section
---
This is a bit of text because why not that's why.

{{ range where .Site.Pages "Section" .Page.Section | first 5 }}
