---
canonical: {{ .Canonical }}
seo:
  - og:
    - og_locale: {{ .seo.og.og_locale }}
      og_type: {{ .seo.og.og_type }}
      og_title: {{ .seo.og.og_title }}
      og_url: {{ .seo.og.og_url }}
      og_description: {{ .seo.og.og_description }}
      og_site_name: {{ .seo.og.og_site_name }}
service: "Credit Cards"
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
author_name: "TotallyMoney"
author_title: ""
categories: [ "Credit Cards" ]
tags: [ "Credit Cards" ]
draft: true
---
