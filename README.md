# BeyondROM Main Hub

![Current Issues](https://img.shields.io/github/issues-raw/LeeXDA21/BeyondROM_Hub?color=red&label=Current%20Issues%3A)
![Closed Issues](https://img.shields.io/github/issues-closed-raw/LeeXDA21/BeyondROM_Hub?color=green&label=Closed%20Issues%3A)
![](https://img.shields.io/github/downloads/LeeXDA21/BeyondROM_Hub/total?color=Green&label=Kit%20Downloads)
![](https://img.shields.io/github/v/release/LeeXDA21/BeyondROM_Hub?color=greeen&include_prereleases&label=Current%20Kit%20Version%3A)
[![Channel](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram&label=S10%20Chat)](https://t.me/beyondrom_s10)
[![Channel](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram&label=S20%20Chat)](https://t.me/BeyondROM_S20)
[![Channel](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram&label=S21%20Chat)](https://t.me/+00MtTfRzreRlYzQ0)
[![Channel](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram&label=Beyond%20News)](https://t.me/+P7IDXNOdDHNmNGZk)
[![](https://img.shields.io/discord/923564469571973120?label=Join%20Our%20Discord)](https://discord.gg/jawYw8525E)
[![Download](https://img.shields.io/github/v/release/LeeXDA21/BeyondROM_Hub?color=green&logoColor=orange&label=Download%20Latest%20Kit&logo=DocuSign)](https://github.com/LeeXDA21/BeyondROM_Hub/releases/latest)

![alt text](https://i.imgur.com/cSSKUQo_d.webp?maxwidth=640&shape=thumb&fidelity=medium)

**Credits to Anan1211 for the Logging Kit.**

### How to Report a bug or a request a feature:

* Go to Issues tab
* Select the right template for your issue request `([BUG] for bug, [FEATURE] for Features)`
* Please explain your bug/feature correctly
* Give as much details as possible.
* Low effort in descriptions will most likely have your request closed.
* Gather logs (for bug reports), reports without a log will be closed.

### XDA Links for BeyondROM:

* [S10](https://forum.xda-developers.com/t/rom-beyondrom-v8-8-21-10-2021-11-0-fui5-oct-patch-g970-g973-g975-f-fd.4017921/)

* [S20](https://forum.xda-developers.com/t/rom-beyondrom-v3-1-24-03-2021-duc7-mar-patch-a11-g980f-g981b-g985f-g986b-g988b.4203109/)

* [S21](https://forum.xda-developers.com/t/rom-beyondrom-v1-1-01-04-2021-auc8-exynos-sm-g99xx.4254933/post-84830965)

### How to gather logs with **LoggingKit**
* Download the latest release via [LoggingKit_v5](https://github.com/LeeXDA21/BeyondROM_Hub/releases/download/v5.0/LoggingKit_v5.zip) and follow the legend.

### [With booted System] - **Intended for Crashes, FCs and other SYSTEM Logs**

1) 1. For Windows users: Install **Universal ADB drivers** or **Brand specific ADB drivers** if you don't have them
    2. For Linux and macOS users: To make the files executable, type in Terminal `chmod +x` and drag the files
2) On your phone **enable USB debugging** under `Developer options`
3) Launch your required log type (to find out which logs you should gather, check [Legend](#Legend))
4) Grant `ADB Keys`
5) Close your log type
6) Launch the needed log, again
7) After recording log, attach the created file to your GitHub issue post.

### **Legend**

| Log type | Description |
| :------: | :------: |
| log-ball | Full buffer logcat. Don't use unless requested|
| log-all | Verbose logcat, messy but records everything|
| log-e | Log for Error filter, only shows crashes|
| log-ril | Log for Modem/SIM and other RIL issues|
| log-kmsg | Log for Kernel msg when the kernel panics|
| log-dmsg | Log for Kernel on an active system|
| log-ActiveDmesg 	| Looping Log for Kernel on active system|
| log-dump 	| Get the prev_dump.log (Don't use unless requested by Dev)|

* Being stuck at **`"Waiting For Device"`** means you either **did not auth the adb key** or your **device does not even have debugging enabled**
* **Extra**: You can skip step 3/4 by running **`ADB_Keys.bat`** if you previously allowed your computer ADB
