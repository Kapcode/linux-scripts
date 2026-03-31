# linux-scripts

Useful scripts for Linux I have written to solve some issue or another.

---

## Scripts

### **Moonlight Installer (MX Linux)**

Optimized for MX Linux Live USB environments. Executes a strict update and installation order to prevent full system upgrades while ensuring proper runtime dependencies.

* **File:** `moonlight-installer-mx.sh`
* **Execution Order:** `apt update` → `apt install flatpak` → `flatpak remote-add flathub` → `flatpak install moonlight`

#### **Installation One-Liner**

```bash
curl -sL https://bit.ly/install-moonlight-mx | bash
```

---

### **SGIN Keyboard Dropout Fix (MX Linux)**

Resolves keyboard disconnects during extended runtimes on SGIN laptops running MX-25.1 Live USB. Disables aggressive power management (TLP, USB/I2C autosuspend), mitigates squashfs bus contention, and generates a fallback Xfce desktop recovery script to reload I2C/HID modules without rebooting.

* **File:** `sgin-kbd-fix.sh`
* **Execution Flow:** Masks `tlp` → Sets `udev` power rules → Optimizes `sysctl` dirty writeback → Generates `Reset_Keyboard.sh` on the live desktop.

#### **Execution One-Liner**

```bash
curl -sL https://bit.ly/fix-keyboard-mx | sudo bash
```

---

## License

Internal use for Kapcode projects.

Kapcode | Software made simple.
