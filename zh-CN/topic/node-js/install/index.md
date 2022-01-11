---
title: 安装 NodeJS
layout: base
localization: zh-CN
---

{% include banner/dependencies/resource.html
    dependency0=site.data.topic.package-manager
%}

# {{ page.title }}

安装 NodeJS 的最佳方式是使用一个包管理器来先安装 `Node Version Manager (NVM)`。点击上面的链接来获取更多关于如何准备一个包管理器的信息。

## 安装 NVM

### 在 Windows 上安装 NVM

{% include copyable/copyable-highlight.html
    shell="PowerShell"
    language="powershell"
    file="install-nvm.ps"
%}

### 在 MacOS 上安装 NVM

{% include copyable/copyable-highlight.html
    shell="Shell"
    language="shell"
    file="install-nvm.sh"
%}

### 确认 NVM 已安装

{% include copyable/copyable-highlight.html
    shell="any-terminal"
    language="shell"
    file="nvm-list.sh"
%}

## 安装 NodeJS 16 版本

{% include copyable/copyable-highlight.html
    shell="any-terminal"
    language="shell"
    file="nvm-use.sh"
%}
