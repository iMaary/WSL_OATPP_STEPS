## WSL Installation Tutorial

Painel de Controle > Programas > Ativar ou Desativar Recursos
=> Selecionar CheckBox: Subsistema do Windows para Linux

Tente instalar o WSL pelo comando:
```bash
wsl --install
```

Caso não funcione, siga os próximos passo abaixo:

```bash
$ dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
```

```bash
$ dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```

```bash
$ https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi
```

```bash
$ wsl --set-default-version 2
```

Pesquisar na microsoft store: Ubuntu && Instalar a primeira que aparecer no Preview.
- CLique em "abrir"
- Ele vai pedir para você adicinar um User (usuário) e uma Password (senha) 

```
$ touch ~/.hushlogin

$ sudo apt update && sudo apt upgrade
```

Pesquisar na microsoft store: Windows Terminal && Instalar


## CRUD REST_API Tutorial no Unbuntu

#### LINUX
```
$ sudo apt-get install build-essential
$ cmake --version
=> cmake version 3.23.1
\\ if returns cmake not found, so run the command:
$ sudo apt-get install cmake
\\ Now Check-up again
$ cmake --version
=> cmake version 3.23.1
```

Baixar Pré-Requisitos Básico: https://oatpp.io/docs/installation/unix-linux/#ubuntu

Clonar Repositório da URL: https://github.com/oatpp/example-crud
- Seguir os passos descritos no README.md
