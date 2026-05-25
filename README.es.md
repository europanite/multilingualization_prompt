---
layout: page
title: "🇪🇸 Español"
permalink: /es/
lang: es
---

# [multilingualization_prompt](https://github.com/europanite/multilingualization_prompt "multilingualization_prompt")

<p align="right">
  <a href="https://europanite.github.io/multilingualization_prompt/">🇺🇸 English</a> |
  <a href="https://europanite.github.io/multilingualization_prompt/hi/">🇮🇳 हिंदी</a> |
  <a href="https://europanite.github.io/multilingualization_prompt/ja/">🇯🇵 日本語</a> |
  <a href="https://europanite.github.io/multilingualization_prompt/zh-CN/">🇨🇳 简体中文</a> |
  <a href="https://europanite.github.io/multilingualization_prompt/es/">🇪🇸 Español</a> |
  <a href="https://europanite.github.io/multilingualization_prompt/pt-BR/">🇧🇷 Português (Brasil)</a> |
  <a href="https://europanite.github.io/multilingualization_prompt/ko/">🇰🇷 한국어</a> |
  <a href="https://europanite.github.io/multilingualization_prompt/de/">🇩🇪 Deutsch</a> |
  <a href="https://europanite.github.io/multilingualization_prompt/fr/">🇫🇷 Français</a>
</p>

Prompt para la multilingüización

---

## 🚀 Primeros pasos

### Un prompt para multilingüizar README

```bash
You are a professional technical translator and GitHub documentation expert.

Task:
Given an input README.md written in English, generate translated versions in multiple languages and provide them as downloadable files.

Target languages and file names:
- README.hi.md (Hindi)
- README.ja.md (Japanese)
- README.zh-CN.md (Simplified Chinese)
- README.es.md (Spanish)
- README.pt-BR.md (Portuguese - Brazil)
- README.ko.md (Korean)
- README.de.md (German)
- README.fr.md (French)

Requirements:
1. Preserve the original Markdown structure exactly (headings, code blocks, links, badges, etc.).
2. Do NOT translate:
   - code blocks
   - commands
   - file paths
   - URLs
3. Translate naturally for developers (not literal translation).
4. Keep technical terms accurate and consistent.
5. Each translated file must:
   - start with the same language switcher block (keep it in English + native language names)
   - include a notice that it is a translated version and English is the source of truth

Output format:
- Generate each file separately
- For each file:
  1. Show the file name
  2. Show the full content
  3. Provide a downloadable file (as a file attachment or downloadable artifact)

Important:
Do not summarize. Do not omit any section. Fully translate the entire README.
```


### Un fragmento para README.md
```bash
<p align="right">
  <a href="./README.md">🇺🇸 English</a> |
  <a href="./README.hi.md">🇮🇳 हिंदी</a> |
  <a href="./README.ja.md">🇯🇵 日本語</a> |
  <a href="./README.zh-CN.md">🇨🇳 简体中文</a> |
  <a href="./README.es.md">🇪🇸 Español</a> |
  <a href="./README.pt-BR.md">🇧🇷 Português (Brasil)</a> |
  <a href="./README.ko.md">🇰🇷 한국어</a> |
  <a href="./README.de.md">🇩🇪 Deutsch</a> |
  <a href="./README.fr.md">🇫🇷 Français</a>
</p>
```

---

# Licencia
- Apache License 2.0
