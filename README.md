# 🐐 AnyKernel3 Template for Messi Kernel (Xiaomi Redmi Note 5 Pro - `whyred`)

Template installer **AnyKernel3** resmi untuk pengemasan otomatis flashable zip **Messi Kernel** pada device **Xiaomi Redmi Note 5 Pro / AI (`whyred`)**.

---

## 📁 Struktur Installer
* `Image.gz-dtb`: Kernel image terkompresi dengan concatenated device tree blob (SDM636 / SDM660).
* `anykernel.sh`: Script instalasi ramdisk dinamis & patch boot partition otomatis.
* `banner`: Banner ASCII Art yang digenerate oleh compiler `build.sh` / GitHub Actions.
* `.metadata`: File metadata konfigurasi kernel dan flag aktif (otomatis digenerate saat build).
* `tools/`: Binary installer multi-arch (`ak3-core.sh`, `busybox`, `magiskboot`, `magiskpolicy`).

---

## ⚙️ Kompatibilitas & Fitur
* 📱 **Target Device**: `whyred` (Xiaomi Redmi Note 5 Pro / AI)
* 🚀 **Architecture**: ARM64 (`aarch64`)
* 🐧 **Linux Kernel**: 4.4.x EAS (Energy Aware Scheduling)
* 🤖 **Android OS**: Android 9 (Pie), 10 (Q), 11 (R), 12 (S), 13 (T), 14 (U) (AOSP / LineageOS / PixelExperience / Custom ROMs)
* 🛡️ **Root Solutions**:
  - **Vanilla (Non-Root)**: Kompatibel dengan Magisk & APatch
  - **KernelSU (Backslashxx)**: In-tree KernelSU dengan manual hooks 4.4
* 🔒 **Stealth Protection**: In-kernel SELinux stealth, path_umount isolation, VFS custom ROM & mount gap masking, Zero-Latency syscall timing.

---

## 📲 Cara Flash
1. Masuk ke **Custom Recovery** (OrangeFox / TWRP).
2. Pilih file `4.4.302-Messi-x1.0-whyred-*.zip`.
3. Swipe to Flash.
4. Reboot System!

---
*Maintained with ❤️ by [KuyangID](https://github.com/KuyangID)*
