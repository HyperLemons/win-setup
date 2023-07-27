My recommended programs (organized in folders) and setup for Windows 10 (and possibly 11 in the future)

## Step 1: Windows setup
Since i'm still a current user of Windows 10 this is primarily focused on only Windows 10 setup, programs, and possibly tweaks.
If at any time in the future I switch to Windows 11, I will either update sections of this guide to include parts for Windows 11 or create a new guide dedicated to Windows 11.

If you want to go all in, especially for gaming, optimize for latency. A great guide that is constantly being updated (at the time of writing this) is **[amitxv's PC-Tuning guide](https://github.com/amitxv/PC-Tuning)**.
If the guide has too many comprimises (the Physical Setup section is more recommendations than mandatory) than you can do a clean Windows 10 install with [Microsoft's Windows 10 USB installer](https://www.microsoft.com/en-gb/software-download/windows10) or with [Ventoy](https://github.com/ventoy/Ventoy) using a Windows ISO from [UUP dump](https://uupdump.net) (Windows 10 1709+)

    **(this is a blatant rip from https://github.com/amitxv/PC-Tuning/blob/main/docs/building.md,
    i'm still figuring out Github formatting and will link/give proper credit to that section of his guide if I fix this and
    decide not to make own version of this ISO download tutorial)**
    
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
        

## Step 2: Programs

- Key:
    - ⭐ - Highly recommended
    - ✅ - Open Source
    - ❌ - Closed Source/Proprietary


- Sections:
    - List all folders after getting back home
    - Recommended Djsckrd Clients
    - [Misc programs from fresh install at Went program (to be sorted out after getting back home)](#misc-programs-from-fresh-install-at-went-program)


## Misc programs from fresh install at Went program

### [7zip](https://www.7-zip.org/)
__⭐ - Highly recommended, ✅ - Open Source__

Include brief description here along with possible use cases if applicable

### [PathCopyCopy](https://github.com/clechasseur/pathcopycopy)
__⭐ - Highly recommended, ✅ - Open Source__

Include brief description here along with possible use cases if applicable

### [ContextMenuManager](https://github.com/BluePointLilac/ContextMenuManager/blob/master/README-en.md)
__⭐ - Highly recommended, ✅ - Open Source__

Include brief description here along with possible use cases if applicable

### [SwiftSearch](https://sourceforge.net/projects/swiftsearch/)
__✅ - Open Source__

Include brief description here along with possible use cases if applicable

### [paint.net](https://www.getpaint.net/download.html)
__❌ - Closed Source/Proprietary__

Include brief description here along with possible use cases if applicable
   - Alternatively, [Pinta](https://www.pinta-project.com/) exists and is ✅ open source but it's features are limited due to being built upon Paint.net's 3.0 source code.


### [GetStoreApp](https://github.com/Gaoyifei1011/GetStoreApp/blob/master/Description/README_EN-US.md)
__✅ - Open Source__

Include brief description here along with possible use cases if applicable
   - Alternatively (or if you aren't able to install your own provided uwp/appx files with GetStoreApp), [Alt App Installer](https://github.com/m-jishnu/alt-app-installer) exists and is ✅ open source.
