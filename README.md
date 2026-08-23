# Gscatter-Blender-5.2-Fix
Unofficial community fix and update for Gscatter, making the free scattering add-on compatible with Blender 5.2 and Python 3.13.

# Gscatter (Blender 5.2 / Python 3.13 Fix)

An unofficial community compatibility update for **Gscatter** (originally developed by [Graswald](https://gscatter.com/)), patched to work smoothly on **Blender 5.2** and **Python 3.13**.

## 🛠️ What Was Fixed
* **Python 3.13 Wheels:** Replaced older compiled dependencies (such as Pillow for `cp313`) so the extension loads properly on newer Blender runtimes.
* **Geometry Node Layouts:** Fixed a crashing `IndexError` on the `Random Value` node inside the distribution mask logic due to internal socket index shifts in Blender 5.2.

## 📥 Installation
1. Download the latest release `.zip` from this repository.
2. Open Blender 5.2.
3. Go to **Edit > Preferences > Get Extensions** (or the top-right dropdown arrow) -> **Install from Disk...**
4. Select the downloaded `.zip` file.

## 📜 License & Credits
* **Original Add-on:** Created by **Graswald GmbH** and licensed under the **GNU General Public License v3.0 or later (GPL-3.0-or-later)**.
* **Disclaimer:** This is an independent, community-maintained fix package intended solely to restore functionality on newer Blender releases. All rights and core assets belong to their respective creators.
