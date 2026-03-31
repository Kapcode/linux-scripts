# linux-scripts

Useful scripts for Linux I have written to solve some issue or another.

---

## Scripts

### **Moonlight Installer (MX Linux)**

Optimized for MX Linux Live USB environments. Executes a strict update and installation order to prevent full system upgrades while ensuring proper runtime dependencies.

* **File:** `moonlight-installer-mx`
* **Execution Order:** `apt update` → `apt install flatpak` → `flatpak remote-add flathub` → `flatpak install moonlight`

#### **Installation One-Liner**

```bash
curl -sL bit.ly/install-moonlight-mx | bash
```
License

Internal use for Kapcode projects.

Kapcode | Software made simple.
