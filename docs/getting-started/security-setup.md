---
date: 2025-02-10 16:06:19
author: linhisreal
description: Configure your system's security settings for AWP.GG
icon: shield-halved
---

# Security Setup

## ⚠️ Security Notice

{% hint style="danger" %}
Your antivirus software must be temporarily disabled for AWP.GG to function properly. This is required for the installation process only.
{% endhint %}

## 🔒 Windows Defender

{% tabs %}
{% tab title="Automatic Method" %}

### Using Defender Control

```mermaid
flowchart LR
    A[Download Tool] --> B[Run as Admin]
    B --> C[Disable Defender]
    C --> D[Verify Status]
```

[⬇️ Download Defender Control v1.5](https://github.com/qtkite/defender-control/releases/tag/v1.5)
{% endtab %}

{% tab title="Manual Method" %}

#### Manual Configuration Steps

{% embed url="https://www.youtube.com/watch?v=UKu6qtc534A" %}
Step-by-step video guide
{% endembed %}
{% endtab %}
{% endtabs %}

## 🚫 Security Settings

### Windows Security Configuration

1. **Firewall Settings**

{% hint style="info" %}

* Open Windows Security
* Navigate to "Firewall & Network Protection"
* Disable all protection features
{% endhint %}

1. **Browser Protection**

{% hint style="info" %}

* Access "App & Browser Control"
* Open "Reputation-based protection settings"
* Disable all features
{% endhint %}

## 🗑️ Antivirus Removal

{% hint style="warning" %}
Follow these steps carefully to remove third-party antivirus:
{% endhint %}

1. Open Control Panel
2. Go to "Programs"
3. Click "Uninstall a program"
4. Remove antivirus software
5. Restart your PC

{% hint style="success" %}
After completing security setup, proceed to [Installation Guide](installation.md)
{% endhint %}
