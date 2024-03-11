---
comments: true
---

# Setting up IDE (Integrated Development Environment)
You can use any IDE or code editor<br>
For choosing there it is

## Choosing the IDE or Code Editor

I mostly prefer Visual Studio Codium for easy development and fast setup<br>
You can use PyCharm Community Edition as most proffessional developers use it but the con of this it works kinda slow on mid-low end computers/laptops and downloading the installor is mostly big<br>
You might say why not Visual Studio Code?

#### VSCode vs VSCodium
Visual Studio is Open-Source-Software but the binaries are not builded from Open-Source Code<br>
While Visual Studio Codium is a manual builded version with patches for telemetry being disabled but also there is no some of extensions from VSCode as it uses [Open VSX](https://open-vsx.org/)

## List of IDEs for Python specific
1. PyCharm Community Edition
2. Visual Studio Codium
3. Visual Studio Code

# Installation Questions
I don't want to spend time on installing it is simple like you install any programs

But i give you downloads to not struggle with choosing CPU architecture like i said on project's description ALL-AT-ONE-HOME<br>
PS: The Python downloading is bit doesn't match to it but it is easy

## For windows
### PyCharm Community Edition
It is universal:
[Download PyCharm Community Edition (Universal)](https://download.jetbrains.com/python/pycharm-community-2023.3.4.exe)<br>
For Arm64 Proccessors more likely ARM with ARM64 extension
[Download Pycharm Community Edition (ARM64)](https://download.jetbrains.com/python/pycharm-community-2023.3.4-aarch64.exe)

### Visual Studio Codium
[VSCodium Updates Disabled x64](https://github.com/VSCodium/vscodium/releases/download/1.87.1.24068/VSCodium-x64-updates-disabled-1.87.1.24068.msi)<br>
[VSCodium x64](https://github.com/VSCodium/vscodium/releases/download/1.87.1.24068/VSCodium-x64-1.87.1.24068.msi)<br>

### Visual Studio Code
[VSCode User Installer x64](https://code.visualstudio.com/docs/?dv=win64user)<br>
[VSCode User Installer ARM64](https://code.visualstudio.com/docs/?dv=win32arm64user)<br>
[VScode System Installer x64](https://code.visualstudio.com/docs/?dv=win64)<br>
[VSCode System Installer ARM64](https://code.visualstudio.com/docs/?dv=win32arm64)<br>
[VSCode Portable zip x64](https://code.visualstudio.com/docs/?dv=winzip)<br>
[VSCode Portable zip ARM64](https://code.visualstudio.com/docs/?dv=win32arm64zip)<br>
[VSCode CLI zip x64](https://code.visualstudio.com/docs/?dv=winzip)<br>
[VSCode CLI zip ARM64](https://code.visualstudio.com/docs/?dv=win32arm64zip)<br>
## For Linux

### VSCodium
For Arch-based distros:
```bash
sudo pacman -S vscodium
```
For Other distros please download it from [VSCodium WebSite](https://vscodium.com)<br>
After downloading appropriate file then install it with these commands
For Debian-based distros:
```bash
sudo apt install <file.deb>
```
For RHEL-based distros:
```bash
sudo yum install <file.rpm>
or
sudo dnf install <file.rpm>
```
For Fedora-based distros:
```bash
sudo dnf install <file.rpm>
```

### VSCode
For Arch-based distros:
```bash
sudo pacman -S code
```
For Debian-based distros:
```bash
sudo apt install code
```
For RHEL-based distros:
```bash
sudo yum install code
or
sudo dnf install code
```
For Fedora-based distros:
```bash
sudo dnf install code
```

### Pycharm CE
For Arch-based distro
```bash
sudo pacman -S pycharm-community-edition
```
For Other distros please download it from [Pycharm Community Edition](https://www.jetbrains.com/pycharm/download/?section=linux), or please read the manual to add the repo and install it<br>

# For VSCod(e/ium) users
Please install Python extension as it helps a lot

# You've been done setting up IDE!!
> I think it needs some corrections so contribrutors are, Welcome!