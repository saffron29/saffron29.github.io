---
traduccion: /en/sitemap/
layout: single
title: "Mapa del sitio"
permalink: /sitemap/
author_profile: true
---

Todas las páginas de este sitio. También existe una [versión XML](/sitemap.xml) para buscadores.

## Páginas

- [Inicio](/)
- [Proyectos](/portfolio/)
- [Videos](/videos/)
- [Tesis y CV](/cv/)
- [Contacto](/#contacto)

## Proyectos

{% for p in site.data.portafolio.principales %}- [{{ p.titulo }}]({{ p.enlace }})
{% endfor %}
## Documentos

- [CV en PDF](/files/cv-frank-pinares.pdf)
- [Tesis de licenciatura en PDF](/files/tesis-pinares-gutierrez-2025.pdf)
