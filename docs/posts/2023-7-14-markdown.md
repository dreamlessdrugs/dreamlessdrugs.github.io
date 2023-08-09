---
layout: default
title: Jekyll & Markdown
parent: Posts
nav_order: 2
last_modified_date: 2023-07-15T1:00
---

# Jekyll & Markdown
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Jekyll
Jekyll中Jinja2的变量位于_config.yml文件中
{% raw %}
```
{% assign variable = value %}
在代码块中插入 Liquid 语句, 要使用{% raw %}，让Jekyll不处理
用于在模板中创建或修改变量
```
{% endraw %}

---

## Markdown
