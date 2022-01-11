---
title: Install NodeJS
layout: base
localization: en-US
---

{% include banner/dependencies/resource.html
    dependency0=site.data.topic.package-manager
%}

# {{ page.title }}

The best way to install NodeJS is to install `Node Version Manager (NVM)` with a package manager. Click on link on top of this page to get more information about how to get a package manager prepared.

## Install NVM

### Install NVM on windows

{% include copyable/copyable-highlight.html
    shell="PowerShell"
    language="powershell"
    file="install-nvm.ps"
%}

### Install NVM on MacOS

{% include copyable/copyable-highlight.html
    shell="Shell"
    language="shell"
    file="install-nvm.sh"
%}

### Verify NVM is Installed

{% include copyable/copyable-highlight.html
    shell="any-terminal"
    language="shell"
    file="nvm-list.sh"
%}

## Install NodeJS Version 16

{% include copyable/copyable-highlight.html
    shell="any-terminal"
    language="shell"
    file="nvm-use.sh"
%}
