# 🚀 FiveBoosts — Professional FiveM Load Simulation Platform

![Version](https://img.shields.io/badge/version-1.0.2-blue) ![Platform](https://img.shields.io/badge/platform-FiveM-orange) ![Status](https://img.shields.io/badge/status-stable-green) ![License](https://img.shields.io/badge/license-MIT-purple)

Stop guessing if your upcoming major server update lags out at 64 or 128 slots. **FiveBoosts** is an independent software infrastructure platform built for FiveM operators and developers to simulate full-scale server traffic natively before real communities connect.

🔗 **Official Website & Console:** [fiveboosts.net](https://fiveboosts.net/)  
🔐 **Secure Dashboard:** [fiveboosts.net/dashboard](https://fiveboosts.net/dashboard)

---

## 💡 Why FiveBoosts?

Unlike traditional, risky server list boosters or basic menu injections that get your infrastructure blacklisted by Cfx/Rockstar, FiveBoosts utilizes official scripting natives and clean network pooling.

* **Three Simulation Modes:** Dynamically toggle units to **Walk**, **Drive**, or **Fly** live from your dashboard to stress-test entity streaming, physics subsystems, and vehicle sync.
* **Real-Time Control Center:** Scale active unit counts up or down seamlessly with less than 10 seconds command latency—no server restarts required.
* **Verified 0.00ms Idle Overhead:** Built on spatial logic that puts thread processes to sleep at zero load, causing absolute zero performance penalty when inactive.
* **Native Compatibility:** Simulation units display properly in txAdmin, server browser player lists, and custom scoreboards out of the box.

---

## 💻 Quick Installation (Under 2 Minutes)

Implementing the open-source server bridge into your development cycle is simple:

1. Create your developer account and generate your secure RSA-signed token at [fiveboosts.net/dashboard](https://fiveboosts.net/dashboard).
2. Download this repository folder and place it into your server's `resources` directory (name the folder `fiveboosts`).
3. Add the authentication token string directly to your `server.cfg` file:
   ```cfg
   set sv_fiveboosts_token "YOUR_RSA_DASHBOARD_TOKEN_HERE"
   ensure fiveboosts
