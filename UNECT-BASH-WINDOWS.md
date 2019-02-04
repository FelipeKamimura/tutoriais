![Imgur](https://i.imgur.com/Yrfi0E6.png)
# Unect Jr. Bash no Windows

Olá Unectianos, esse é o tópico para os guerreiros, os ~~bravos~~ que ainda se mantém firmes e fortes no Windows. Será uma breve explicação de instalação do Bash no Windows.

---

## Atualização

Verifique se o seu Windows está atualizado em sua última versão(Windows 10). 

Caso não seja possível, utilize o git bash que vem junto com o git for Windws. [Download](https://git-scm.com/downloads)

## Instalação

Presumimos que você possua a versão mais recente do Windows.

Siga este tutorial oficial de instalação: [Link](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

Utilize a versão Ubuntu de sistema operacional.

Para iniciar a nova instalação siga estes passos: [Link](https://docs.microsoft.com/en-us/windows/wsl/initialize-distro)

## Criação de senha

Para você poder ter acesso ao comando ```sudo``` você precisará criar uma senha para o mesmo, utilize os comandos:
```
sudo su

psswd
```

Após executar será solicitada para que digite uma senha para o usuário root.

## Atualizando o ambiente Linux

Eventualmente iremos utilizar de pacotes do package manager do linux e é recomendado que o package manager esteja em sua última versão, bem como os pacotes já existentes. Utilize os comandos: 
```
sudo apt-get update

sudo apt-get upgrade
```

## Instalando o GIT

Agora iremos instalar a principal ferramenta de versionamento de arquivos. Utilize os comandos: 
```
sudo apt-get install git
```

## Instalando o ZSH 

Zsh é um terminal assim como o Bash, porém possui diversas funcionalidades como por exemplo a instalação de plugins e temas, existe um tópico nesse tutorial para a instalação do zsh.

[ZSH + OH MY ZSH](UNECT-ZSH.md)

---
Por enquanto é isso galera. Qualquer contribuição é super bem vinda!
Obrigado!