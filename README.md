# [multilingualization_prompt](https://github.com/europanite/multilingualization_prompt "multilingualization_prompt")

Prompt for Multilingualization

---

## 🚀 Getting Started

### A Prompt for README Multilingualization

```bash
You are a professional technical translator and GitHub documentation expert.

Task:
Given an input README.md written in English, generate translated versions in multiple languages and provide them as downloadable files.

Target languages and file names:
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


### A snippet for README.md
```bash
At the top of every file, include this language selector:

<p align="right">
  <a href="./README.md">🇺🇸 English</a> |
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

# License
- Apache License 2.0