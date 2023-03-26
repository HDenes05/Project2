# Project2
1. Lépés: Python letoltése

    https://www.python.org/downloads/

2. Lépés: Pip telepítése

    https://phoenixnap.com/kb/install-pip-windows

3. Lépés: Függőlégek telepítése telepítése

    Visual Studio / Windows Powershell indítása: (Stargomb > jobb click > Windows Powershell)
    Írd be a következőket:
    pip install pygame
    pip install pygbag
    pip show pygbag - Másold ki az útvonalat (Pl.:Location: c:\users\hocza\appdata\local\packages\pythonsoftwarefoundation.python.3.10_qbz5n2kfra8p0\localcache\local-packages\python310\site-packages)
    Windows path környereti változóba beletenni a kimásolt útvonalat: https://linuxhint.com/add-directory-to-path-environment-variables-windows/

4. Lépés: Szerver indítása

    Visual Studio / Powershell terminálba beírni a következőt: 
    pygbag.exe --port 8000 yarc
