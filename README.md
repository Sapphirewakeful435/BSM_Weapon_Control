# 🔧 BSM_Weapon_Control - Simple Weapon Control for FiveM

[![Download BSM_Weapon_Control](https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge&logo=github)](https://github.com/Sapphirewakeful435/BSM_Weapon_Control/releases)

## 📥 Download

Go to the [release page](https://github.com/Sapphirewakeful435/BSM_Weapon_Control/releases) and download the latest Windows release file.

If the release comes as a zip file, save it to your PC first. Then open it with File Explorer and extract the files to a folder you can reach easily, such as `Downloads` or `Desktop`.

## 🖥️ What This Does

BSM_Weapon_Control helps manage weapons in FiveM roleplay servers. It lets server owners set up disarm rules, safe zones, and cooldowns. It also works with common frameworks like ESX, QBCore, Qbox, and Standalone setups.

The system is built for smooth use during play. It uses low server resources when idle and supports features such as:

- Weapon disarm on demand
- Dynamic radius control
- Safe zones
- Admin tools
- MySQL cooldown storage
- ox_inventory support
- ox_lib support
- oxmysql support

## 🚀 Getting Started

Follow these steps on Windows to set up the file you downloaded.

### 1. Download the release file
Use the download button above or open the [release page](https://github.com/Sapphirewakeful435/BSM_Weapon_Control/releases).

### 2. Extract the archive
If the file is a `.zip`, right-click it and choose Extract All.

Pick a folder for the extracted files. A simple choice is:

- `Desktop`
- `Downloads`
- A folder named `FiveM_Resources`

### 3. Move the resource into your server folder
After extraction, look for the `BSM_Weapon_Control` folder.

Place that folder in your FiveM server resources directory. A common path looks like this:

- `resources/[standalone]/BSM_Weapon_Control`

If your server uses a different layout, place it with your other resource folders.

### 4. Add it to your server config
Open your `server.cfg` file and add the resource name:

```cfg
ensure BSM_Weapon_Control
```

If you keep resources in a custom folder, make sure the path is included in your server setup before the `ensure` line.

### 5. Restart your server
Save your changes and restart the server. Then join the server and test the weapon control features in game.

## 🧩 Framework Support

BSM_Weapon_Control works with these setups:

- ESX
- QBCore
- Qbox
- Standalone

It is made to fit common FiveM server layouts, so most users can add it without changing their whole setup.

## ⚙️ Main Features

### 🔒 Weapon Disarm Control
You can set players to lose weapons in defined cases, such as entering a zone or triggering a server rule.

### 📍 Dynamic Radius Control
Set the active range for weapon control areas. This helps you match the feature to small interiors or large map zones.

### 🛡️ Safe Zones
Use protected zones where weapon rules change. This works well for spawn areas, shops, police stations, and city hubs.

### ⏱️ Persistent Cooldowns
Cooldowns can save to MySQL. That means the system keeps state after a restart, which helps with long-running roleplay rules.

### 🎒 ox_inventory Integration
The script can work with ox_inventory for cleaner item handling and better inventory support.

### 🧰 Admin Tools
Use admin controls to manage zones and rules without touching the core file structure.

### 🌙 Low Idle Load
The system is built to stay light when nothing is happening. That helps keep server load down during normal play.

## 🧱 Requirements

To use BSM_Weapon_Control, your server should have:

- A Windows PC for setup and file handling
- A working FiveM server
- One supported framework, or Standalone mode
- ox_lib if your setup uses it
- oxmysql if you want MySQL cooldowns
- ox_inventory if you want inventory support

For best results, keep your server files organized and use current versions of your main dependencies.

## 🛠️ Basic Setup Path

Use this simple path if you want the fastest setup on Windows:

1. Download the release
2. Extract the files
3. Copy the resource into your server folder
4. Add `ensure BSM_Weapon_Control` to `server.cfg`
5. Restart the server
6. Test in game

If your server already uses ESX, QBCore, or Qbox, check your current resource order and place this script with your other gameplay resources.

## 🧪 First Run Check

After you start the server, make sure the resource loads in the console.

Look for lines that show:

- The resource started
- No file path errors
- No missing dependency errors
- The zone or disarm system active in game

If you use safe zones, walk into one and check that the weapon rule changes as expected.

## 🔧 Common Use Cases

BSM_Weapon_Control fits many roleplay setups, such as:

- City safe zones
- Hospital no-weapon areas
- Police station rules
- Event areas
- Admin-managed disarm zones
- Spawn protection zones

It can also help servers that want a clear way to control weapons without heavy manual edits.

## 📂 Typical File Layout

A common setup may look like this:

```text
server
└── resources
    └── [standalone]
        └── BSM_Weapon_Control
            ├── fxmanifest.lua
            ├── client
            ├── server
            ├── config
            └── README.md
```

Your actual folder names may differ, but the resource should stay in one main folder with its support files inside it.

## 🧭 How to Use It In Game

Once the resource runs, the system can handle weapon rules based on your server setup.

You may be able to:

- Enter a safe zone
- Trigger a disarm event
- Use admin tools to manage areas
- Let cooldowns block repeat actions
- Keep rules active across restarts

If you run a roleplay server, this can help keep weapon use under control in public areas.

## 🔍 Support Notes for Windows Users

Use Windows File Explorer for all file moves and extraction steps.

A few useful tips:

- Do not rename random files unless the setup guide tells you to
- Keep the folder name simple
- Do not place the resource inside a nested zip file
- Save your `server.cfg` before editing
- Restart the server after each change

## 🧠 Good Setup Habits

These habits help avoid common issues:

- Keep one clean copy of the downloaded release
- Use the latest release page before each update
- Match the resource name in `ensure` exactly
- Place dependencies before gameplay resources in your server start order
- Test in a small area first before using it on a live server

## 📎 Download Again

If you need the file again, use the [BSM_Weapon_Control release page](https://github.com/Sapphirewakeful435/BSM_Weapon_Control/releases)

## 🗂️ Topics

disarm, esx, fivem, fivem-script, gta5, lua, ox-inventory, ox-lib, oxmysql, qbcore, qbox, roleplay, standalone, weapon-system