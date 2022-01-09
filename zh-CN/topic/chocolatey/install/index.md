---
title: 安装 Chocolatey
layout: default
localization: zh-CN
---

{% include banner/chapter-reference.html 
  references=site.data.topic.chocolatey.articles.install.references
%}

# 安装 Chocolatey

1. 首先，确保使用管理员权限的 PowerShell。
2. 使用 `powershell.exe` 安装此脚本。

{% include copyable/copyable-highlight.html
  admin=true
  shell="PowerShell"
  language="powershell"
  file="install.ps"
%}

{:start="3"}
3. 将命令粘贴在控制台中并按下回车。
4. 等待命令运行完毕。
5. 如果没有任何错误提示，安装就完成了！输入 `choco` 或者 `choco -?` 或者访问 [开始使用](https://docs.chocolatey.org/en-us/getting-started) 了解运行方式。