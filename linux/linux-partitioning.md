## Quick Partitioning Guide - Ubuntu/Linux Mint

- Manual Partition Settings
- Select the drive

- For the EFI mode, recommendations (Let's say 150gb free space)
  - **efi(UEFI bootloader)** (Select efi system partition) = 100 MB
  - **swap (temporary storage)** = same size as RAM (Let's say 8GB)
  - **/ (Linux system)** (Select ext4 journaling system) = 50-60 GB or more (Softwares will be installed here)
  - **/home (personal user data)** (Select ext4 journaling system) = 82-92 GB or more/less
