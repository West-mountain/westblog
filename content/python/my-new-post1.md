---
title: "My New Post1"
date: 2023-07-16T20:25:44+08:00
draft: false
---

{{ range where .Site.Pages "Section" "python" }}
## [{{ .Title }}]({{ .Permalink }})

{{ .Summary }}

[阅读更多]({{ .Permalink }})

---
{{ end }}

