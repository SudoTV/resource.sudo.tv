---
title: 安装 Chocolatey
layout: default
localization: zh-CN
---

{% include banner/not-ready.html %}

{% include banner/chapter-reference.html 
  references=site.data.topic.chocolatey.articles.install.references
%}

# 安装 Chocolatey

1. First, ensure that you are using an [administrative powershell](https://www.howtogeek.com/194041/how-to-open-the-command-prompt-as-administrator-in-windows-8.1/)
2. Install with `powershell.exe`.

With administrative powershell, run the following command.

{% include copyable/copyable-highlight.html
  language="powershell"
  file="install.ps"
%}

{:start="3"}
3. Paste the copied text into your shell and press Enter.
4. Wait a few seconds for the command to complete.
5. If you don't see any errors, you are ready to use Chocolatey! Type `choco` or `choco -?` now, or see Getting Started for usage instructions.