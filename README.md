# Project2
0. Lépés: Github

    Visual Studio terminal vagy Windows Powershell indítása: (Stargomb > jobb click > Windows Powershell)
    ssh-keygen -t rsa -b 4096 -C "email cim"
    enter 3-szor
    cat ~/.ssh/id_rsa.pub
    A kilistázott publikus kulcsot kimásolni
    https://github.com/settings/keys    /   New SSH key   /   Ctrl-V    /    Save
    git config --global user.name "saját név"      
    git config --global user.email "email cim"

1. Lépés: Python letoltése

    https://www.python.org/downloads/

2. Lépés: Pip telepítése

    https://phoenixnap.com/kb/install-pip-windows

3. Lépés: Függőlégek telepítése telepítése

    Visual Studio / Windows Powershell indítása
    Írd be a következőket:
    pip install pygame
    pip install pygbag
    pip show pygbag - Másold ki az útvonalat (Pl.:Location: c:\users\hocza\appdata\local\packages\pythonsoftwarefoundation.python.3.10_qbz5n2kfra8p0\localcache\local-packages\python310\site-packages)
    Windows path környereti változóba beletenni a kimásolt útvonalat: https://linuxhint.com/add-directory-to-path-environment-variables-windows/

4. Lépés: Szerver indítása

    Visual Studio / Powershell terminálba beírni a következőt: 
    pygbag.exe --port 8000 yarc
