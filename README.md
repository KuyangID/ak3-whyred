# AnyKernel3 Template for Xiaomi Redmi Note 7 / 7S (lavender)

Template installer AnyKernel3 untuk pengemasan otomatis kernel Kage (Xiaomi Redmi Note 7/7S - `lavender`).

## 📁 Struktur Installer
* `Image.gz-dtb`: Kernel image terkompresi dengan concatenated device tree blob.
* `anykernel.sh`: Script instalasi ramdisk & patch boot partition.
* `banner`: Banner dinamis yang digenerate oleh `build.sh`.
* `.metadata`: File metadata konfigurasi kernel dan flag aktif (otomatis digenerate saat build).
* `tools/`: Binary pendukung (`ak3-core.sh`, `busybox`, `magiskboot`, `magiskpolicy`).

## ⚙️ Kompatibilitas
* **Device**: `lavender` (Redmi Note 7 / 7S)
* **Android OS**: Android 10, 11, 12, 13, 14 (AOSP / Custom ROM)
* **Root Solutions**: Non-Root/APatch, KernelSU (Backslashxx), Re-KernelSU, KernelSU Next.
