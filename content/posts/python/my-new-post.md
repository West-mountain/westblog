---
title: "My New Post"
date: 2023-07-16
draft: false
---
{{ range where .Site.Pages "Section" "posts/python" }}
## [{{ .Title }}]({{ .Permalink }})

{{ .Summary }}

[阅读更多]({{ .Permalink }})

---
{{ end }}