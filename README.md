Setup for Windows 10 (and possibly 11 in the future) and my recommended programs (organized in folders)

# Step 1: Installing Windows
Since i'm still a current user of Windows 10 this is primarily focused on only Windows 10 setup, programs, and (possibly) miscellaneous tweaks for the OS and programs. If at any time in the future I switch to Windows 11, I will either update sections of this guide to include parts for Windows 11 or create a new guide dedicated to Windows 11.

If you want to go all in, especially for gaming, optimize for latency. A great guide that is constantly being updated (at the time of writing this) is **[amitxv's PC-Tuning guide](https://github.com/amitxv/PC-Tuning)**.

If the guide has too many comprimises for you (the Physical Setup section is more recommendations than mandatory, but support for various Windows features like UWP may be removed. Some of these features removed can be found [here](https://www.startpage.com/sp/search?query=does+fedora+support+ntfs&cat=web&pl=opensearch&language=english)) than you can do a clean Windows 10 install with [Microsoft's Windows 10 USB installer](https://www.microsoft.com/en-gb/software-download/windows10) or with [Ventoy](https://github.com/ventoy/Ventoy) using a Windows ISO from [UUP dump](https://uupdump.net) (Windows 10 1709+)

    **(this is a blatant rip from https://github.com/amitxv/PC-Tuning/blob/main/docs/building.md,
    i'm still figuring out Github formatting and will link/give proper credit to that section of his guide if I fix this and
    decide not to make my own version of this ISO download tutorial)**
    
        <details>
        <summary>Instructions</summary>

        - Search for the Windows version you desire and download the latest feature update instance

            <img src="/media/uupdump-search-image.png" width="750">

        - Choose the desired language and click next

            <img src="/media/uupdump-choose-language.png" width="750">

        - Uncheck all editions except the professional edition and click next

            <img src="/media/uupdump-choose-edition.png" width="750">

        - Copy the configuration below, ensure that ``Include updates`` is ticked and click ``Create download package``

            <img src="/media/uupdump-download-options.png" width="750">

        - Extract the downloaded package and run ``uup_download_windows.cmd``. The final ISO file will be created in the same directory as the script

        </details>
        

# Step 2: Programs

## Key:
   - ⭐ - Highly recommended
   - ✅ - Open Source
   - ❌ - Closed Source/Proprietary


## Sections:
   - [Storage Management](#storage-management)
   - [Downloading](#downloading)
   - [iPhone](#iphone)
   - [Android (this section will come in the near future...)](#android)
   - [Sound/Audio](#sound-and-audio)
   - [Browsers (Includes browser extensions and flags/tweaks)](#browsers)
   - [Games (Game Launchers, Upscalers, Tools)](#games)
   - [Images](#images)
   - [Video](#video)
   - [Productivity (Office alternatives and Office Service disablers)](#productivity-and-office)
   - [System Modifications](#system-modifications)
   - [System Themeing](#system-themeing)
   - [VPN & DNS](#vpn-and-dns)
   - [Monitoring (Hardware, FPS, Latency)](#monitoring)
   - [SD Card (Formatting and test for fakes](#sd-card-formatting-and-testing)
   - [Mouse/Mice](#mouse-aka-mice)
   - [Monitor/Display](#monitor-and-display)
   - [Recommended Discord Clients](#recommended-discord-clients)
   - [Replacements for proprietary laptop/hardware software/bloatware](#replacements-for-proprietary-laptop-and-hardware-software-aka-bloatware)
   - [Misc programs from fresh install at Went program (to be sorted out into folders after getting back home)](#misc-programs-from-fresh-install-at-went-program)

# Storage Management

## [7zip](https://www.7-zip.org/)
__⭐ - Highly recommended, ✅ - Open Source__

Include brief description here along with possible use cases if applicable

   - My 7zip context menu settings
     
     ![7zip_settings](https://github.com/HyperLemons/win10-setup/assets/36387099/693fe1b3-6cb9-4635-9378-874e852cb575)

## [Bulk Crap Uninstaller](https://www.bcuninstaller.com/)
__⭐ - Highly recommended, ✅ - Open Source__

Include brief description here along with possible use cases if applicable

## [WizTree](https://diskanalyzer.com/download)
__⭐ - Highly recommended, ❌ - Closed Source/Proprietary__

Include brief description here along with possible use cases if applicable (mention how it's much faster than WinDirStat by using MFT for NTFS, https://diskanalyzer.com/wiztree-vs-windirstat)

## [SwiftSearch](https://sourceforge.net/projects/swiftsearch/)
__✅ - Open Source__

Include brief description here along with possible use cases if applicable (mention how fast it is by using MFT for NTFS)
   - Alternatively, **[WizFile](https://antibody-software.com/wizfile/)** exists and is practically feature parity, but is **❌ closed source**.


# Downloading



# iPhone



# Android



# Sound and Audio



# Browsers



# Games



# Images



# Video



# Productivity and Office



# System Modifications



# System Themeing



# VPN and DNS



# Monitoring



# Sd Card formatting and testing



# Mouse aka Mice



# Monitor and Display



# Recommended Discord clients

## [ArmCord](https://github.com/ArmCord/ArmCord)
__✅ - Open Source__

Include brief description here along with possible use cases if applicable


## [Dorion](https://github.com/SpikeHD/Dorion/)
__✅ - Open Source__

Include brief description here along with possible use cases if applicable


# Replacements for proprietary laptop and hardware software AKA bloatware

## Asus Laptops:


### [G-Helper](https://github.com/seerge/g-helper)
__✅ - Open Source__

Include brief description here along with possible use cases if applicable



# Misc programs from fresh install at Went program
__(these programs will all be organized into their proper folder after getting home)__

## [PathCopyCopy](https://github.com/clechasseur/pathcopycopy)
__⭐ - Highly recommended, ✅ - Open Source__

Include brief description here along with possible use cases if applicable

## [ContextMenuManager](https://github.com/BluePointLilac/ContextMenuManager/blob/master/README-en.md)
__⭐ - Highly recommended, ✅ - Open Source__

Include brief description here along with possible use cases if applicable

## [paint.net](https://www.getpaint.net/download.html)
__❌ - Closed Source/Proprietary__

Include brief description here along with possible use cases if applicable
   - Alternatively, **[Pinta](https://www.pinta-project.com/)** exists and is **✅ open source** but it's features are limited due to being built upon Paint.net's 3.0 source code.

## [GetStoreApp](https://github.com/Gaoyifei1011/GetStoreApp/blob/master/Description/README_EN-US.md)
__✅ - Open Source__

Include brief description here along with possible use cases if applicable
   - Alternatively (or if you unable to install your own provided uwp/appx files with GetStoreApp), **[Alt App Installer](https://github.com/m-jishnu/alt-app-installer)** exists and is **✅ open source**.
   - Can't install .appx and .msixbundle files? Use ["Appx Installer" Installer](https://github.com/yqs112358/AppxInstaller-Installer).

## [SecureUxTheme](https://github.com/namazso/SecureUxTheme)
__✅ - Open Source__

Include brief description here along with possible use cases if applicable
