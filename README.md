# B460-TUF-I5-10600-macOS-Catalina-Opencore

## Specification

- ASUS TUF GAMING B460-PLUS
- Intel® Core™ i5-10600 Processor 
- Patriot Memory Viper 4 Series 3000MHz (PC4 24000) 8GB
- Patriot 512GB SATA III SSD
- Gamdias TALOS E1 Mini Tower dual Fan Case
- GPU Nvidia 1050 (Disabled)

## Does Xcode Work?

- Catalina only supports Xcode upto 12.4. Xcode 12.4 works.

## Steps

- follow the steps provided on [Dortiana guide](https://dortania.github.io/OpenCore-Install-Guide/) to format the USB drive.
- copy the  EFI folder to USB
- create a folder `com.apple.recovery.boot`. or download macos catalina directly from here. [catalina google drive com.apple.recovery.boot link](https://drive.google.com/file/d/1UIV0l6vrry6tz50HoDG4pMXFoNa8UmlF/view?usp=sharing) 

## Before installing

- There are no kexts for wifi support. If you want then, search for the supported chipset [dortiana wireless chipset guide](https://dortania.github.io/Wireless-Buyers-Guide/unsupported.html#supported-chipsets), then head to [wireless kext](https://dortania.github.io/OpenCore-Install-Guide/ktext.html#wifi-and-bluetooth) then download and place the kext inside `EFI/OC/Kexts/`.


## After installing

- You can use [chris wifi adapter support drivers](https://github.com/chris1111/Wireless-USB-Adapter) for various kind fo wifi adapter. follow the steps there.

