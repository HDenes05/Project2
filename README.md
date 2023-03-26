# Project2
0. Lépés: Github<br>
<br>
    Visual Studio terminal vagy Windows Powershell indítása: (Stargomb > jobb click > Windows Powershell)<br>
    ssh-keygen -t rsa -b 4096 -C "email cim"<br>
    enter 3-szor<br>
    cat ~/.ssh/id_rsa.pub<br>
    A kilistázott publikus kulcsot kimásolni<br>
    https://github.com/settings/keys    /   New SSH key   /   Ctrl-V    /    Save<br>
    git config --global user.name "saját név"<br>
    git config --global user.email "email cim"<br>
<br>
1. Lépés: Python letoltése<br>
<br>
    https://www.python.org/downloads/<br>
<br>
2. Lépés: Pip telepítése<br>
<br>
    https://phoenixnap.com/kb/install-pip-windows<br>
<br>
3. Lépés: Függőlégek telepítése telepítése<br>
<br>
    Visual Studio / Windows Powershell indítása<br>
    Írd be a következőket:<br>
    pip install pygame<br>
    pip install pygbag<br>
    pip show pygbag - Másold ki az útvonalat (Pl.:Location: c:\users\hocza\appdata\local\packages\pythonsoftwarefoundation.python.3.10_qbz5n2kfra8p0\localcache\local-packages\python310\site-packages)<br>
    Windows path környereti változóba beletenni a kimásolt útvonalat: https://linuxhint.com/add-directory-to-path-environment-variables-windows/<br>
<br>
4. Lépés: Szerver indítása<br>
<br>
    Visual Studio / Powershell terminálba beírni a következőt: <br>
    pygbag.exe --port 8000 yarc<br>
