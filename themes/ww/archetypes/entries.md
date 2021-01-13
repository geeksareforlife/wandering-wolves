---
{{- $dateString := now.Format "2006-01-02-" -}}
{{- $newTitle := replace .Name $dateString "" }}
title: {{ replace $newTitle "-" " " |  title }}
author: "Seral"
aptisdate: 233842
date: {{ .Date }}
slug: "{{ lower $newTitle }}"
sessions:
  - "2020-08-06"
draft: true
---

