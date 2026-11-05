---
layout: single
title: "Sitemap"
permalink: /en/sitemap/
author_profile: true
locale: en-US
lang: en
traduccion: /sitemap/
sitemap: false
---

All the pages on this site. There is also an [XML version](/sitemap.xml) for search engines.

## Pages

- [Home](/en/)
- [Projects](/en/projects/)
- [Videos](/en/videos/)
- [Thesis & CV](/en/cv/)
- [Contact](/en/#contact)
- [Versión en español](/)

## Projects

{% for p in site.data.portafolio_en.principales %}- [{{ p.titulo }}]({{ p.enlace }})
{% endfor %}
## Documents (in Spanish)

- [CV (PDF)](/files/cv-frank-pinares.pdf)
- [Licentiature thesis (PDF)](/files/tesis-pinares-gutierrez-2025.pdf)
