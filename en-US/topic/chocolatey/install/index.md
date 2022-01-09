---
title: Install Chocolatey
layout: base
localization: en-US
---

{% include banner/chapter-reference.html 
  references=site.data.topic.chocolatey.articles.install.references
%}

# Install Chocolatey

1. First, ensure that you are using an [administrative powershell](https://www.howtogeek.com/194041/how-to-open-the-command-prompt-as-administrator-in-windows-8.1/)
2. Install with `powershell.exe`.

{% include copyable/copyable-highlight.html
  admin=true
  shell="PowerShell"
  language="powershell"
  file="install.ps"
%}

{:start="3"}
3. Paste the copied text into your shell and press Enter.
4. Wait a few seconds for the command to complete.
5. If you don't see any errors, you are ready to use Chocolatey! Type `choco` or `choco -?` now, or see [Getting Started](https://docs.chocolatey.org/en-us/getting-started) for usage instructions.