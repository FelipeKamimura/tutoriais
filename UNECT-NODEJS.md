![Imgur](https://i.imgur.com/Z4EzwWF.png)

# Unect Jr. NodeJS

Olá Unectianos, nesse tópico nós abordaremos a instalação do ambiente NodeJS em sua máquina.

---

## Windows

Com o Windows totalemente atualizado, baixe o arquivo .zip e siga os passos para concluir a instalação.
[Download](https://nodejs.org/en/download/)

## Linux

### Manjaro

No terminal execute os seguintes comandos:
```
sudo pacman -Syy

sudo pacman -Su

sudo pacman -S nodejs npm
```
Caso você tente executar algum módulo do Node.JS e tenha uma mensagem de erro parecida com a citada logo abaixo:
```
usr/bin/env: ‘node’: No such file or directory
```
Execute o comando seguinte para corrigir, esse problema pode ser ocasionado devido a ausência de algumas dependências mais atualizadas em torno do Node.JS:
```
sudo ln -s /usr/bin/nodejs /usr/bin/node
```
### elementaryOS

No terminal execute os seguintes comandos:
```
sudo apt uptade

sudo apt install nodejs npm
```
### Linux Mint
```
sudo apt uptade

sudo apt install nodejs npm
```
### Ubuntu

No terminal execute os seguintes comandos:
```
sudo apt uptade

sudo apt install nodejs npm
```
### Deepin

No terminal execute os seguintes comandos:
```
curl -sL https://deb.nodesource.com/setup_11.x | bash -

apt-get install -y nodejs
```

---

Por enquanto é isso galera. Qualquer contribuição é super bem vinda!
Obrigado!
