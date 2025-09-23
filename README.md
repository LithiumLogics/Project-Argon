# 🛣️ ArgonOS Roadmap

ArgonOS is a lightweight, customized Linux distribution built on **Ubuntu Lite** and optimized for the **Raspberry Pi 3B**.  
This roadmap outlines the development milestones and goals for the project.  

---

## 📌 Phase 1: Base Setup
- [ ] Flash Ubuntu Server Lite (ARM64) for Raspberry Pi 3B  
- [ ] Boot and configure hostname → `argon-os`  
- [ ] Update base system (`apt update && apt upgrade`)  
- [ ] Enable SSH for remote access  

---

## 📌 Phase 2: Core Environment
- [ ] Install development tools (GCC, Python, Git, etc.)  
- [ ] Configure networking via **NetworkManager**  
- [ ] Ensure stable SSH + WiFi/Ethernet support  

---

## 📌 Phase 3: Desktop Environment
- [ ] Install **XFCE4** as the primary desktop environment  
- [ ] Configure X.Org for Pi GPU  
- [ ] Enable auto-boot into graphical target  

---

## 📌 Phase 4: Branding & Identity
- [ ] Design and integrate **ArgonOS splash screen** (Plymouth)  
- [ ] Set default **wallpaper + XFCE theme**  
- [ ] Configure ArgonOS default hostname, login banner, and GRUB branding  

---

## 📌 Phase 5: Core Applications
- [ ] Lightweight web browser (Midori / Falkon)  
- [ ] File manager (Thunar)  
- [ ] Text editor (Mousepad)  
- [ ] Python 3 + essential libraries  

---

## 📌 Phase 6: Optimization
- [ ] Optimize boot speed (systemd analyze + service trimming)  
- [ ] Enable Raspberry Pi 3B hardware acceleration & drivers  
- [ ] Remove unused packages to shrink image size  

---

## 📌 Phase 7: Distribution & Release
- [ ] Export ArgonOS as a `.img` file  
- [ ] Compress image (`.img.xz`) for release  
- [ ] Publish on GitHub with release notes + checksum  
- [ ] Write user installation guide (flash with `Raspberry Pi Imager` / `dd`)  

---

✅ **Final Goal**: Deliver a clean, fast, and lightweight OS for Raspberry Pi 3B with ArgonOS branding.

**Then Work On The PCB**
