# **Ubuntu-Setup**

![Shell](https://img.shields.io/static/v1?label=Shell%20Script&logo=Ubuntu&message=Linux&color=orange)
![GitHub](https://img.shields.io/github/license/fstecnologiainfo/Ubuntu-Setup)
![GitHub top language](https://img.shields.io/github/languages/top/fstecnologiainfo/Ubuntu-Setup?logo=Linux&logoColor=white)
![GitHub repo size](https://img.shields.io/github/repo-size/fstecnologiainfo/Ubuntu-Setup)

 Script para realizar instalações e customização do Ubuntu Server e Desktop com versões superior a 21.10, incluído distros instaladas no Microsoft WSL2.

>**IMPORTANTE**\
>Esses scripts são programados para executar apenas 1 vez, caso haja algum erro verifique os arquivos de log em **/var/log/** \
>Caso queira realizar modificação nos programas que serão instalados, modifique a sessão de **VARIAVEIS GLOBAIS**

***

## **COMO USAR?**

1 - Faça o download do arquivo compactado na página do GitHub ou clone o repositório usando o comando

Git
```
git clone https://github.com/fstecnologiainfo/Ubuntu-Setup.git
```

PowerShell
```
Invoke-WebRequest -Uri https://codeload.github.com/fstecnologiainfo/Ubuntu-Setup/zip/refs/heads/main -OutFile C:\Ubuntu-Setup.zip
```

2 - Acesse a pasta **/Ubuntu-Setup** e altere as permissões do arquivos *setup-(tipo-distro).sh* em arquivos executáveis.

3 - Execute a instalação com os privilégios *root*, sendo **/Ubuntu-Setup/setup-workstation.sh** para realizar as instalações e customização no Ubuntu Desktop e **/Ubuntu-Setup/setup-wsl2.sh** para realizar as instalações e customização no Microsoft WSL2 Ubuntu.

***

## **WORKSTATION**

***Instalação***

Softwares SNAP: *Whatsdesk - MIcrosoft Teams - PDF Mix Tool*

Softwares .DEB: *htop - VLC - FileZilla - Flatpak - Git - Preload - Curl - qBittorrent - Nano - Nomacs*

Softwares .DEB (Administrador de Redes): *Synaptic Open VPN - Gnome Boxes - Remmina - Net-tools - DNS Utils - Neofetch - SpeedTest (cli) - NMap - Open SSL*

***Customização***

- Ajuste de data e hora para dual boot e VM's
- Codecs para execução de arquivos de media

***

## **MICROSOFT WSL2**

***Instalação***

Softwares .DEB (Administrador de Redes): *NMap - SpeedTest (cli) - Neofetch - Net-tools - cMatrix - Figlet - Open SSL - DNS  Utils*

***Extra***

ACME: Para gerar certificados com Let's Encrypt

OpenSSL: Para gerar certificados auto-assinados e certificados .pfx

***

## **CRÉDITOS**

**Autor**: Fernando da S. Conceição

**Contato**: [GMail](fstecnologia.info@gmail.com)
