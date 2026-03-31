## # linux-scripts

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

### Usage Note
These scripts are designed for **Lead Dev/System Admin** workflows. Most are tailored for a **Triple-GPU** architecture (**AMD Primary**, Intel Compute, NVIDIA Passthrough) and account for high-memory environments (**80GB RAM / 16GB ZRAM**).

### License
Personal use for **Kapcode** projects. "Software made simple."
