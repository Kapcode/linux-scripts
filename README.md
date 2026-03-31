That’s a clean, branded short link. It fits the **Kapcode** identity perfectly.

Since you've got the repo and the link ready, here is the final **README.md** structure for your `linux-scripts` repository. I’ve kept it technical and concise, matching your lead dev workflow.

---

# linux-scripts
Useful scripts for Linux I have written to solve some issue or another.

---

## Scripts

### **Moonlight Installer (MX Linux)**
Designed specifically for **MX Linux Live USB** sessions to get streaming capability active in seconds without performing a full system `dist-upgrade`.

* **File:** `moonlight-installer-mx`
* **Execution Order:** `apt update` → `install flatpak` → `add flathub` → `install moonlight`
* **Hardware Target:** Optimized for **AMD RX 6500 XT** hardware decoding (VA-API).

#### **One-Liner (Shortened)**
```bash
curl -sL bit.ly/kapcode-linux-scripts | bash
```

---

## System Context
Scripts in this repository are developed and tested against:
* **OS:** Pop!_OS / MX Linux (Debian Base)
* **Desktop:** KDE Plasma via X11
* **Hardware:** Triple-GPU (AMD Primary, Intel Compute, NVIDIA Passthrough)
* **Memory:** 80GB RAM / 16GB ZRAM

## License
**Software made simple.** Internal use for Kapcode projects.

---

### Pro-Tip for the Live USB:
If you find yourself needing to run this frequently, you can actually add that `curl` command as a **KRunner** shortcut or a **Guake** startup script on your persistent storage to make it even faster. 

Ready to push this to the repo?## # linux-scripts

Useful scripts for Linux I have written to solve some issue or another.

---

### Scripts

#### **Moonlight Installer (MX Linux)**
Optimized for **MX Linux Live USB** environments. Follows a strict execution order to ensure Flatpak and Moonlight are installed correctly without a full system upgrade.

* **File:** `moonlight-installer-mx`
* **Target OS:** MX Linux (Debian/Ubuntu base)
* **One-Liner (Standard):**
    ```bash
    curl -sL https://raw.githubusercontent.com/kapcode/linux-scripts/main/moonlight-installer-mx | bash
    ```
* **One-Liner (Shortened):**
    ```bash
    curl -sL bit.ly/your-short-link | bash
    ```

---

### License
Personal use for **Kapcode** projects. "Software made simple."
