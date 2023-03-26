# Project2
## 1. Lépés: Github<br>
<br>
    Visual Studio terminal vagy Windows Powershell indítása: (Stargomb > jobb click > Windows Powershell)<br>
    ssh-keygen -t rsa -b 4096 -C "email cím"<br>
    enter 3-szor<br>
    cat ~/.ssh/id_rsa.pub<br>
    A kilistázott publikus kulcsot kimásolni<br>
    https://github.com/settings/keys > New SSH key > Ctrl-V > Save<br>
    git config --global user.name "saját név"<br>
    git config --global user.email "email cím"<br>

## 2. Projekt klónozása a GitHubból
<br>
    Visual Studio Code indítása
    Főmenüben Start menüpont alatt > Clone Git Repository...
    Illeszd be a következőt: git@github.com:HDenes05/Project2.git
    Clone from GitHub > célkönyvtár (célmappa) megadása

## 3. Módosítás beküldése a Git repository-ba
<br>
    Visual Studio Code-ban a bal oldali menüben > Source control (Ctrl + Shift + G)
    Commit melletti lenyíló menü > Commit & Push
    Beírni egysorban a módosítás tartalmát röviden
    Ctrl + S
    Tab (Commit üzenet) bezárása

## 4. Lépés: Python letoltése<br>
<br>
    https://www.python.org/downloads/<br>

## 5. Lépés: Pip telepítése<br>
<br>
    https://phoenixnap.com/kb/install-pip-windows<br>

## 6. Lépés: Függőlégek telepítése telepítése<br>
<br>
    Visual Studio / Windows Powershell indítása<br>
    Írd be a következőket:<br>
    pip install pygame<br>
    pip install pygbag<br>
    pip show pygbag - Másold ki az útvonalat (Pl.:Location: c:\users\hocza\appdata\local\packages\pythonsoftwarefoundation.python.3.10_qbz5n2kfra8p0\localcache\local-packages\python310\site-packages)<br>
    Windows path környereti változóba beletenni a kimásolt útvonalat: https://linuxhint.com/add-directory-to-path-environment-variables-windows/<br>

## 7. Lépés: Szerver indítása<br>
<br>
    Visual Studio / Powershell terminálba beírni a következőt: <br>
    pygbag.exe --port 8000 yarc<br>
