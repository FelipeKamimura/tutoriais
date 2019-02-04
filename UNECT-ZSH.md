![Imgur](https://i.imgur.com/Z4EzwWF.png)
#Unect Jr. Zsh + Oh My Zsh

Olá Unectianos, nesse tópico abordaremos a instalação do Zsh e do Oh My Zsh

---
O terminal Zsh é um terminal muito útil que existe para a maioria dos sistemas operacionais. Nós optamos por usá-lo como complemento do bash e ao invés do bash puro/cmd existem muitos plugins para o Zsh que facilitam o desenvolvimento por meio de atalhos dentro do terminal, além de possuir diversos temas para o terminal, como o exemplo abaixo: 
![Imgur](https://i.imgur.com/ORhHgSn.png)

Oh My Zsh é um framework do Zsh que facilita a inclusão de plugins e temas para o Zsh

## Instalação ZSH

### Linux

Utilizando o gerenciador de pacotes da sua distribuição instale o zsh. Por exemplo:
```
sudo apt-get install zsh
```
Verifique a versão na qual foi instalada utilizando o comando:
```
zsh --version
```
Torne o zsh o seu terminal principal utilizando o comando:
```
chsh -s $(which zsh)
```
Faça o logout e logue novamente.

(Pode ser que a instalação mude de uma distribuição para outra além do tipo de gerenciador de pacotes, se for o seu caso, leia a documentação [link](https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH))

Assim que abrir o terminal com o zsh pela primeira vez ele dará opções de inicialização. Recomendo a teclar "0" e pressionar "enter" para continuar.

### Windows

Para instalar o Zsh no Windows, primeiro necessita-se a instalação do Bash no Windows, temos um tópico específico para a [instalação do Bash no Windows](UNECT-BASH-WINDOWS.md)

## Instalação Oh My Zsh

A instalação do Oh My Zsh pode ser feita de duas formas, via ```curl``` ou ```wget```. Portante já tenha algum dos dois instalado.

**via wget**

```
sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
```

**via curl**

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

Pronto, ao final disso o Oh My Zsh estará instalado.

## Plugins

Alguns plugins são altamente recomendados para o Zsh, são eles:

- zsh-syntax-highlighting
- zsh-autosuggestions

Para saber mais sobre a instalação desses plugins e outros, além de temas e fontes, acesse: [Clique](https://medium.com/@ivanaugustobd/seu-terminal-pode-ser-muito-muito-mais-produtivo-3159c8ef77b2).

---
Por enquanto é isso galera. Qualquer contribuição é super bem vinda!
Obrigado!