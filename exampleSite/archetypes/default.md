---
title: "{{ replace (replaceRE "^(.{0,11})" "" .Name) "-" " " | title }}"
date: {{ .Date }}
draft: true
---

