---
description: Troubleshooting common issues with AWP.GG
layout: default
date: 2025-02-08 03:07:12
author: linhisreal
---

# 🔧 Troubleshooting

## ❗ Common Issues

{% tabs %}
{% tab title="Proxy & Launch Issues" %}

### Error: "Failed to Launch Proxy"

{% hint style="warning" %}
This issue is commonly related to Windows Defender blocking necessary files.
{% endhint %}

#### Solution Steps

1. **Add Required Exclusions:**

   ```plaintext
   %localappdata%\Roblox\
   ```

2. **Configure Windows Defender:**
   * Open Windows Start menu
   * Search for "Windows Security"
   * Click "Virus & threat protection"
   * Select "Manage settings"
   * Scroll to "Exclusions"
   * Click "Add or remove exclusions"
   * Choose "Add an exclusion" > "Folder"
   * Add the path above

### Error: "Client Not Up To Date"

{% hint style="info" %}
This occurs when Windows security prevents proper updates.
{% endhint %}

#### Required Exclusions

```plaintext
%localappdata%\Roblox\
AppData\Local\ui
```

#### Resolution Steps

1. Type `/guide` in ⁠commands channel
2. Follow the guide instructions
3. Add both directories as exclusions
4. Restart AWP.GG application
{% endtab %}

{% tab title="Installation Issues" %}

#### Installation Errors

##### Error: "Installation failed due to missing prerequisites"

{% hint style="warning" %}
**Follow these steps:**

1. Check [Prerequisites](../getting-started/prerequisites.md) are installed
2. Verify system compatibility
3. Run installer as administrator
{% endhint %}

##### Error: "Access Denied During Installation"

{% hint style="info" %}
**Quick Fix:**

1. Right-click installer
2. Select "Run as administrator"
3. Try installation again
{% endhint %}
{% endtab %}

{% tab title="License Issues" %}

#### License Activation Problems

##### Error: "Invalid license key"

{% hint style="danger" %}
**Verification Steps:**

1. Double-check license key format
2. Verify key hasn't expired
3. Ensure key isn't already in use
{% endhint %}

##### Error: "License Server Unavailable"

{% hint style="info" %}
**Resolution Steps:**

1. Check internet connection
2. Disable VPN if active
3. Wait 5 minutes and retry
{% endhint %}
{% endtab %}

{% tab title="Software Issues" %}

#### Software Crashes

##### Issue: "AWP.GG crashes on startup"

{% hint style="warning" %}
**Follow these steps:**

1. Check [Security Setup](../getting-started/security-setup.md)
2. Update to latest version
3. Install pending Windows updates
{% endhint %}

##### Issue: "Performance Problems"

{% hint style="info" %}
**Optimization Steps:**

1. Close unnecessary applications
2. Update graphics drivers
3. Check system resources
{% endhint %}
{% endtab %}
{% endtabs %}

## 🎮 Game-Specific Issues

{% tabs %}
{% tab title="ROBLOX Issues" %}

### ROBLOX Integration Problems

1. **Game Not Detected**
   * Close ROBLOX completely
   * Restart AWP.GG as administrator
   * Launch ROBLOX through AWP.GG

2. **Script Execution Errors**
   * Verify antivirus is disabled
   * Check Windows Defender settings
   * Ensure proper permissions
{% endtab %}

{% tab title="Connection Issues" %}

#### Connection Problems

1. **Server Connection Lost**
   * Check internet connection
   * Disable VPN/Proxy
   * Verify firewall settings

2. **High Latency**
   * Close background applications
   * Check internet speed
   * Try different server region
{% endtab %}
{% endtabs %}

## Advanced Troubleshooting

{% tabs %}
{% tab title="File Locations" %}

### Important Directories

```plaintext
Main Application: %localappdata%\ui
ROBLOX Files: %localappdata%\Roblox\
Temporary Files: %temp%
```

{% endtab %}

{% tab title="Commands" %}

### Useful Discord Commands

* `/guide` - View complete setup guide
* `/download` - Get latest version
* `/claim` - Activate license
{% endtab %}
{% endtabs %}

## 📞 Support Channels

{% tabs %}
{% tab title="Discord Support" %}

### Discord Communities

| Server | Purpose | Link |
|---------|---------|------|
| Support Server | Direct assistance | [Join Support](https://discord.gg/buyawp) |
| Official Server | Updates & news | [Join Official](https://discord.gg/awpgg) |

{% endtab %}

{% tab title="Additional Help" %}

#### Other Resources

* [📚 Documentation](../getting-started/installation.md)
* [❓ FAQ](faq.md)
* [🔧 Setup Guide](../getting-started/prerequisites.md)
{% endtab %}
{% endtabs %}

## 🔄 Quick Fixes

### Common Solutions Checklist

{% hint style="info" %}
Try these steps before contacting support:

1. ✅ Restart AWP.GG and ROBLOX
2. ✅ Check for software updates
3. ✅ Verify security settings
4. ✅ Run as administrator
5. ✅ Clear cache files
{% endhint %}

### System Requirements Verification

```mermaid
graph TD
    A[Check System] -->|Verify| B[Requirements]
    B --> C{Meet Specs?}
    C -->|Yes| D[Proceed]
    C -->|No| E[Upgrade System]
    E --> B
```

## 📈 Performance Optimization

### Recommended Settings

{% hint style="info" %}
Optimize your experience:

* Keep AWP.GG and ROBLOX updated
* Close unnecessary background apps
* Regular system maintenance
* Monitor resource usage
{% endhint %}

{% hint style="warning" %}
Remember to save your settings before making any changes!
{% endhint %}
