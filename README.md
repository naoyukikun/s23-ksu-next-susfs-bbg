SM8550 (S23) Custom Kernel - KSU Next & SUSFS
An experimental custom kernel build for the Samsung Galaxy S23 series (SM8550). This project focuses on integrating the latest stealth root solutions and security enhancements, specifically targeting advanced detection bypass.

🚀 Features
KernelSU Next: The next-generation implementation of KernelSU for advanced root management.

WildKSU: Enhanced KernelSU variant with additional patches for stability and compatibility.

SuKiSu: Specialized integration for seamless root access.

SUSFS (Kernel Space File Hiding): Full integration of SUSFS to hide files, folders, and symbolic links from user-space detection (SafetyNet/Play Integrity bypass).

Baseband Guard (BBG): Custom protection layer for the baseband/modem to enhance security and prevent unauthorized access or modifications.

SM8550 Optimized: Specifically tuned for the Snapdragon 8 Gen 2 (Kalama) architecture.

🛠 Included Patches
The repository contains specific patches used during the build process:

rezoss_next3_susfs2.patch: Integrates KernelSU Next with SUSFS.

rezoss_sukisu_susfs.patch: SuKiSu compatibility layer for SUSFS.

rezoss_susfs1512.patch: Core SUSFS v1.5.12 functionality.

📦 Downloads
You can find the flashable kernel images and AnyKernel3 zip files in the Releases section. These are automatically built using GitHub Actions.

🏗 Build Information
This kernel is built using GitHub Actions. To replicate the build:

Fork this repository.

Enable Actions in your fork settings.

Run the workflow manually or trigger it via a push.

⚠️ Disclaimer
[!WARNING] Flashing a custom kernel can result in a bootloop or permanent damage to your device. This project is experimental. Always ensure you have a backup of your data and the original init_boot or boot image before proceeding. The developers are not responsible for bricked devices.

🤝 Credits
KernelSU & KernelSU Next

SUSFS (Simonpunk)

Rezoss-Reza (Original source/patches)

AnyKernel3 (osm0sis)


*This readme is made by an AI
