---
canonical: {{ .Canonical }}
locale: {{ .seo.og.locale }}
type: {{ .seo.og.type }}
title: {{ .seo.og.title }}
url: {{ .seo.og.url }}
description: {{ .seo.og.description }}
site_name: {{ .seo.og.site_name }}
card: {{ .seo.twitter.card }}
site: {{ .seo.twitter.site }}
service: "Mortgages"
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
author_name: "TotallyMoney"
author_title: ""
categories: [ "Mortgages" ]
tags: [ "Mortgages" ]
draft: true
---
