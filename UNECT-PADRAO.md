![Imgur](https://i.imgur.com/Z4EzwWF.png)

# Unect Jr. Ambiente Padronizado (Style Guides)

Olá Unectianos, nesse tópico iremos definir as nossa style guides, style guides são formas de padronização de códigos em projetos que contenham diferentes pessoas trabalhando no mesmo. Lembrando que boa parte desse tópico foi baseado nesse material https://www.youtube.com/watch?v=TI4v4Y8yRjw

---

## Ferramentas

Bom pessoal para que essa padronização seja feita iremos utilizar 3 ferramentas.

1. [ESLint](https://eslint.org/);
2. [Prettier](https://github.com/prettier/prettier);
3. [Editor Config](https://editorconfig.org/).


### Instalando ESLint

Dentro do projeto, instale o ESLint:

```
yarn add eslint -D
# ou
npm i eslint -D
```

Após feito isso nós iremos configurar o ESLint. Para iniciar a sua configuração, digite:

```
yarn run eslint --init
# ou
./node_modules/.bin/eslint --init
```
Após feito isso começará algumas perguntas. Para que seja mantido um padrão iremos responder dessa maneira:

- Primeira resposta
```
User popular style guide
```
- Segunda resposta
```
Airbnb
```
- Terceira resposta

Essa é uma resposta que irá depender do projeto, a pergunta é referente ao projeto ser em React ou não. Responda de acordo com o projeto.

- Quarta resposta
```
JSON
```

Após feito isso ele deve instalar alguns pacotes para a sua configuração.
Será criado um arquivo .eslintrc dentro da pasta raíz do seu projeto. Abra este arquivo e subistitua as configurações existentes pelas configurações a seguir: 
```
{
  "parser": "babel-eslint",
  "env": {
    "browser": true,
    "jest": true
  },
  "plugins": ["react", "jsx-a11y", "import"],
  "extends": "airbnb",
  "rules": {
    "react/jsx-filename-extension": [
      "error",
      {
        "extensions": [".js", ".jsx"]
      }
    ],
    "semi": [2, "never"],
    "global-require": "off",
    "import/prefer-default-export": "off",
    "no-unused-expressions": ["error", {
      "allowTaggedTemplates": true
    }]
  }
}
```
Essas configurações significam que o eslint seguirá o padrão airbnb, porém com algumas configurações adicionais.

## Configurando VSCode

Após feitas as configurações do ESLint, instale no seu VSCode os seguintes plugins: 

- ESLint
- Prettier
- EditorConfig for VSCode

Após instalar os 3 plugins, abra as configurações de usuário do seu VSCode e adicione as seguintes linhas de configuração:
```
"editor.formatOnPaste": true,
"editor.formatOnSave": true,
"prettier.eslintIntegration": true,
"prettier.tslintIntegration": true
```

Essas configurações são usadas para informar ao VSCode que as definições de configurações do nosso arquivo .eslintrc podem sobrescrever o arquivo.

Ainda dentro do VSCode, na pasta raíz do seu projeto crie um arquivo chamado ".editorconfig", e dentro dele coloque as seguintes informações e salve:
```
root = true

[*]
indent_style = space
indent_size = 2
end_of_line = lf
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true
```

## Lembrete

Não é necessário criar ou utilizar o arquivo .prettierrc pois qualquer configuração do Prettier está definida pelo ESLint.

## Concluindo

Ao final da configuração, o style guide estará configurado de forma que todos os membros do projeto estejam programando nos mesmos padrões, e caso alguma parte do código saia desse padrão o ESLint informará em forma de erro no código. Além disso configurações de identação e de algumas partes do código podem ser criadas automáticamente ao salvar o arquivo, por exemplo, ao não adicionar o ";" ao final de alguma linha e o ESLint julgar que for necessário, ao salvar o arquivo utilizando "Ctrl + S", o próprio ESLint irá adicionar o ";" para você.

---

Após isso o seu ambiente estará configurado e dentro dos padrões. Qualquer contribuição é super bem vinda!
Obrigado!
