# BIOS

## Boot Option Priorities
**Naming Syntax**

{Operating System}_{OS Priority}_{Drive Description}_{File Type}


win11_00_hd00_bmgfwefi 
- main windows boot
EFI/Microsoft/Boot/bootmgfw.efi


win11_01_hd00_sosbmgfwefi 
- dell recovery tools
EFI/Dell/SOS/bootmgfw.efi


win11_02_hd00_bmgfwefi 
- generic windows fall back
EFI/Boot/bootx64.efi


kali_00_hd01_grub64x
- [x] boots, [x] backed-up 
- backup location - alienwear 64gb sd
