![Imgur](https://i.imgur.com/Z4EzwWF.png)
#Unect Jr. VSCode

Olá Unectianos, nesse tópico nós abordaremos algumas configurações e puglins para o VSCode.

---

VSCode é um editor de texto extremamente útil. Nós da empresa o utilizamos por ser o editor de texto mais útilizado do mundo e por este fato possui MUITOS plugins disponíveis, e esses plugins se utilizados corretamente tornam o desenvolvimento muito mais ágil.

---

## Instalação

O VSCode está disponível para grande parte dos sistemas operacionais.
[Download](https://code.visualstudio.com/download)

## Plugins

### [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

Plugin que possibilita o fechamento de tagas HTML e XML automaticamente. 

### [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)

Beautify é um plugin que faz a automação da identação de um código que foi colado e não esta identado.

### [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)

Bracket Pair Colorizer é um plugin que nos auxilia a saber quais os pares entre ([{.

### [colorize](https://marketplace.visualstudio.com/items?itemName=kamikillerto.vscode-colorize)

colorize é um plugin que nos auxilia nas colorações CSS.

### [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)

Plugin que nos auxilia a encontrar até uma definição CSS a partir de um HTML

### [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)

 Plugin que permite o highlight de arquivos .env 

 ### [Dracula Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)

Dracula é um tema para o VSCode.

### [EditorConfig for VSCode](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

Plugin que possibilita a sobrescrita de um arquivo .editorconfig.

### [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

Integração do ESLint para o VSCode.

### [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

GitLens é um plugin que nos mostra o autor de um código.

### [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)

Um plugin que facilita a criação de elementos HTML.

### [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

Plugin que cria um local server para paginas estáticas e/ou dinâmicas.

### [Markdown Preview Enchanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)

Plugin para pré-visualização de arquivos Markdown para o VSCode.

### [Material Icon theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

Tema de ícones para vários tipos de arquivos do VSCode.

### [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

Prettier é um formatador de códigos.

## Configurações

Aqui estão algumas configurações interessantes para o VSCode. Para utiliza-las, abra o VSCode, entre nas configurações e no canto direito superior clique no ícone "{}", após isso na coluna da direita, cole esse código: 
```
{
    "editor.wordWrap": "on",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "Dracula",
    "window.zoomLevel": 0,
    "editor.fontLigatures": true,
    "editor.fontSize": 16,
    "workbench.activityBar.visible": true,
    "material-icon-theme.showUpdateMessage": false,
    "editor.lineHeight": 26,
    "workbench.statusBar.visible": true,
    "git.enableSmartCommit": true,
    "editor.tabSize": 2,
    "workbench.startupEditor": "newUntitledFile",
    "editor.formatOnPaste": true,
    "editor.fontFamily": "'monospace', monospace, 'Droid Sans Fallback'",
    "terminal.integrated.fontFamily": "'monospace'",
    "colorize.ignore_search_variables_info": true,
}
```
Recomendo fortemente que busquem entender o que cada uma dessas linhas muda em seu VSCode.

---

Por enquanto é isso galera. Qualquer contribuição é super bem vinda!
Obrigado!