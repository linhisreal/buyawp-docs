---
date: 2025-02-10 16:06:19
author: linhisreal
description: AWP.GG version history and updates
icon: bookmark
---

# Change Logs

{% hint style="info" %}
For latest updates and announcements:

* Join our [Support Server](https://discord.gg/buyawp)
* Follow [Official Discord](https://discord.gg/awpgg)

{% endhint %}

## 🔄 Update Instructions

{% hint style="warning" %}
When updating AWP.GG:

1. Close the UI completely
2. Reopen UI and wait for update
3. Press rocket button to apply changes
4. If issues persist:
   * Reinstall Roblox
   * Check Discord announcements
   * Contact support
{% endhint %}

## February 2025

### February 8, 2025

* Updated for version-f9977b146957492c

### February 6, 2025

* Updated for version-b7a853f1584049b4

### February 3, 2025

* Fixed getgenv error that sometimes occurs during Teleports

### January 31, 2025

* Update for version-dd2acaf7460f42ee
* Users must reopen UI and ensure updates before attaching
* For update issues: Reinstall Roblox and retry rocket button

### January 30, 2025

{% tabs %}
{% tab title="Updates" %}

* Updated for version-233850ad55fa4798
* Fixed for revert
* Required UI restart for changes

{% endtab %}

{% tab title="Troubleshooting" %}
**If Attachment Fails:**

* Reinstall Roblox before retrying
* For "Client likely has not been updated" error:
  * Press "Fix Channel" in AWP UI settings

{% endtab %}
{% endtabs %}

### January 24, 2025

{% hint style="info" %}
**Version 0.657.0.6570603 Release Notes**

Important announcements regarding Hyperion updates:

* Hyperion updates don't affect our emulator unless directly targeted
* Update times remain competitive
* 1-day delay after major updates for security verification
* Alternative bypasses prepared for potential direct attacks
* Maximum downtime estimate: 1 week in worst-case scenarios

{% endhint %}

### January 22, 2025

* Fixed anti-afk functionality
* Resolved crashes during Roblox startup

### January 18-19, 2025

* Fixed crash on teleport in games with actors
* Upcoming update for account farmers announced

### January 17, 2025

{% tabs %}
{% tab title="Major Updates" %}
**Updated for version-080ad6451df24461**

* Added saveinstance, saveplace functions
* Implemented antiafk setting in UI options
* Added disable internal UI setting
* Enhanced internal UI with:
  * ID correlation to multi-instance selector
  * Time in game display
{% endtab %}
{% endtabs %}

### January 9, 2025

* Updated for version-37cf60402a5648b4
* Server issues mitigated

## December 2024

### December 22, 2024

* Fixed gcobjects marking in hookfunction and setconstant

### December 16, 2024

* Added bit library
* Fixed gethui crash when leaving main menu

### December 15, 2024

{% tabs %}
{% tab title="Features" %}

* Improved gethui functionality
  * Creates isolated container outside coregui
  * Enhanced security against attacks
* Enhanced getconnections
* Fixed cloned lclosures debug name retention
* Added isvalidlevel alias

{% endtab %}
{% endtabs %}

### December 12, 2024

{% tabs %}
{% tab title="Fixes & Improvements" %}

* Fixed getactors for games that destroy actor instance but still use thread
* Fixed hookmetamethod typechecking for non cclosure metamethods
* Improvements to getconnections coming in next update

{% endtab %}
{% endtabs %}

### December 11, 2024

* Updated for version-b71c150c7c1f40de
* Reimplemented previous updates with performance fixes
* Resolved script-related bugs

### December 10, 2024

{% tabs %}
{% tab title="Major Update" %}
**Significant Improvements:**

* Enhanced filesystem library - resolved most errors
* WebSocket library improvements:
  * Added TLS support
  * Added IsClosed boolean
  * Added binary data support
* Crypt library hash function now returns hex string digest
* Added function aliases:
  * queueteleport
  * get_signal_cons
  * get_hidden_gui
* Added isnewcclosure
* Fixed purchase prompt message box behavior

**New Actor Library:**

* getactors
* run_on_actor
* isparallel
* create_comm_channel
* get_comm_channel
* on_actor_added

{% endtab %}

{% tab title="Performance" %}

* Performance issues identified and being addressed
* Update temporarily reverted due to unexpected Roblox update
* Working on compatibility fixes

{% endtab %}
{% endtabs %}

### December 7, 2024

**Application & Bot Updates:**

* Fixed registration errors
* Added functional /subscription command with time display

### December 6, 2024

* Filesystem library improvements

### December 5, 2024

* Updated for version-a2fb906f52d742c1
* Fixed cookiebuilder issues

### December 3, 2024

{% tabs %}
{% tab title="Features & Fixes" %}

* Added server script support for getsenv
* Enhanced identifyexecutor with version info
* Fixed request vulnerability
* Improved request response completeness
* Fixed get and setfflag functionality
* Resolved multi-instance crash issues

{% endtab %}

{% tab title="Notes" %}
**Important Information:**

* makefolder errors with trailing / are expected behavior
* Curl errors on localhost related to Discord RPC are not AWP issues

{% endtab %}
{% endtabs %}

### December 1, 2024

* Added support for Client RunContext scripts
* Fixed security prompt triggers
* Fixed CoreGui element loading on rejoin
* Improved pcall async error handling

## November 2024

### November 30, 2024

{% tabs %}
{% tab title="Major Update" %}
**AWP Improvements:**

* Fixed output redirection for errors
* Enhanced cache library stability
* Fixed require function bugs
* Resolved getconnections crash
* Fixed backend HWID errors
* Improved luarmour support
* Added new functions:
  * SystemAddress support in gethiddenproperty
  * messagebox
  * dofile
{% endtab %}
{% endtabs %}

### November 28, 2024

{% tabs %}
{% tab title="Features" %}
**New Version Deployed:**

* Added optional distance argument to fireclickdetector
* Added UI topmost feature
* Added isnetworkowner
* Implemented auto-execute functionality

{% endtab %}

{% tab title="Fixes" %}
**Bug Fixes:**

* Fixed UI settings deselection issue
* Resolved authentication token location
* Fixed setclipboard error handling
* Fixed script HWID stability
* Improved executor launch reliability

{% endtab %}
{% endtabs %}

### November 27, 2024

{% tabs %}
{% tab title="Stability Update" %}
**Major Improvements:**

* Fixed async function crash with disabled console redirection
* Fixed firetouchinterest crash
* Fixed require invalid arguments crash
* Enhanced debug library with:
  * restorefunction
  * isfunctionhooked
  * gethookcache

{% endtab %}
{% endtabs %}

### November 26, 2024

{% tabs %}
{% tab title="Updates" %}

* Added toggleable output redirection in UI
* Fixed setrawmetatable crashes
* Fixed getconnection issues
* Improved exception handling
* Added PromptPurchases security prompt
* Enhanced function blacklist

{% endtab %}

{% tab title="Notes" %}
**Important:**

* Toggle output redirection BEFORE launching games
* Mid-game updates temporarily unavailable
* ScriptContext errors and logservice visible without redirection

{% endtab %}
{% endtabs %}

### November 25, 2024

{% tabs %}
{% tab title="Initial Release" %}
**First Version:**

* Added _G and shared to getrenv()
* Fixed HWID-related script issues
* Fixed filesystem library writefile
* Fixed Roblox window resize crash
* Enhanced sandbox thread support
* Updated function blacklist

{% endtab %}
{% endtabs %}
