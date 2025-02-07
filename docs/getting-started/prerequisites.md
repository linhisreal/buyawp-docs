---
description: Essential system requirements and preparation steps for AWP.GG installation
layout: default
date: 2025-02-07 14:43:44
author: linhisreal
---

# 📋 Prerequisites

## 💻 System Requirements

{% tabs %}
{% tab title="Windows Requirements" %}

### Required Specifications

* Windows 10/11 64-bit
* Administrative Account
* Space Required: 15.7 MB (might changed in future)
* Active Internet Connection

### Checking System Type

1. Press `Windows + R`
2. Type `msinfo32` and press Enter
3. Look for "System Type"
   * Must show: "x64-Based PC"
{% endtab %}

{% tab title="Account Requirements" %}
{% mermaid %}

{% endtab %}
{% endtabs %}

## 📥 Required Software

### Visual C++ Redistributables

{% tabs %}
{% tab title="Download Links" %}

| Version | Link | Status |
|---------|------|--------|
| x64 | [Download VC_Redist x64](https://aka.ms/vs/17/release/vc_redist.x64.exe) | Required |
| x86 | [Download VC_Redist x86](https://aka.ms/vs/17/release/vc_redist.x86.exe) | Required |

{% endtab %}

{% tab title="Installation Steps" %}

1. Download both x64 and x86 versions
2. Run each installer as administrator
3. Follow the installation prompts
4. Restart your computer
{% endtab %}
{% endtabs %}

## 🎮 ROBLOX Setup

{% hint style="danger" %}
A clean ROBLOX installation is required for optimal performance!
{% endhint %}

### Clean Installation Steps

1. **Remove Existing Installation:**
   * Use Revo Uninstaller Pro
   * Remove ALL registry entries
   * Delete related folders

2. **Fresh Installation:**
   * Download latest ROBLOX
   * Run as administrator
   * Complete setup wizard

{% hint style="success" %}
After completing these steps, proceed to [Security Setup](security-setup.md)
{% endhint %}
