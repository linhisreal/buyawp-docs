---
description: Complete installation guide for AWP.GG
layout: default
date: 2025-02-07 14:43:44
author: linhisreal
---

# 📦 Installation Guide

## 🔑 License Activation

{% tabs %}
{% tab title="New Users" %}
### Registration Process

{ % mermaid % }
sequenceDiagram
    participant User
    participant Bot
    participant System
    User->>Bot: /register command
    Bot->>User: Send DM with instructions
    User->>Bot: Complete registration
    System->>User: Account created
{% endmermaid %}
{% endtab %}

{% tab title="Existing Users" %}
### License Claims
* Use `/claim` to activate license
* New duration adds to existing time
* One license per user
{% endtab %}
{% endtabs %}

## 💾 Installation Process

### Download Steps

{% hint style="warning" %}
1. Execute `/download` command
2. Wait for DM with download link
3. Download within 5 minutes

⚠️ Links are single-use and time-limited!
{% endhint %}

### Installation Checklist

{% tabs %}
{% tab title="Pre-Install" %}
* ✅ ROBLOX fully closed
* ✅ Prerequisites installed
* ✅ Antivirus disabled
* ✅ Windows Defender off
{% endtab %}

{% tab title="Installation" %}
1. Run installer as admin
2. Follow setup wizard
3. Configure settings
4. Complete initial setup
{% endtab %}
{% endtabs %}

## 🚀 First Launch

### Setup Process

{ % mermaid % }}
graph TD
    A[Launch UI] -->B[Login]
    B -->C[Click Launch Icon]
    C -->|Error| D[Open Scripting]
    D -->E[Go to Settings]
    E -->F[Fix Channel]
    F -->C
    C -->|Success| G[Ready to Use]
{ % endmermaid % }

## 🗑️ Uninstallation

{% hint style="info" %}
To remove AWP.GG:
1. Open UI
2. Go to Scripting > Settings
3. Click "Remove AWP"
4. Reinstall ROBLOX
{% endhint %}

{% hint style="success" %}
Installation complete! Check our [FAQ](../additional-resources/faq.md) for common questions.
{% endhint %}
