# Landing Page Futurando

Bem-vindo ao projeto Next.js! Este documento tem como objetivo fornecer um guia para os usuários interessados em colaborar com o desenvolvimento do projeto. Aqui você encontrará os passos necessários para configurar o ambiente de desenvolvimento, informações sobre extensões úteis e algumas diretrizes para contribuir.

## Configuração do Ambiente de Desenvolvimento

Para colaborar com o desenvolvimento do projeto Next.js, siga as etapas abaixo para configurar o ambiente de desenvolvimento em seu sistema:

### Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas em seu sistema:

- Node.js (versão 12 ou superior)
- npm (gerenciador de pacotes do Node.js)

### Passos

1. **Clone o repositório**: Comece clonando o repositório do projeto Next.js em sua máquina local usando o seguinte comando:

   ```
   git clone https://github.com/nextjs/next.js.git
   ```

2. **Instale as dependências**: Navegue até o diretório raiz do projeto clonado e execute o comando abaixo para instalar as dependências necessárias:

   ```
   npm install
   ```

3. **Inicie o servidor de desenvolvimento**: Após a conclusão da instalação das dependências, execute o seguinte comando para iniciar o servidor de desenvolvimento:

   ```
   npm run dev
   ```

4. **Acesse o aplicativo**: Abra o navegador e acesse `http://localhost:3000` para visualizar o aplicativo Next.js em execução no seu ambiente de desenvolvimento.

## Extensões Úteis

Aqui estão algumas extensões úteis para o desenvolvimento do Next.js que podem ser instaladas em seu editor de código:

- [ESLint](https://eslint.org/): Ajuda a identificar e corrigir erros de sintaxe e estilo de código.
- [Prettier](https://prettier.io/): Formata automaticamente o código para um estilo consistente.
- [EditorConfig](https://editorconfig.org/): Mantém a consistência nas configurações do editor entre diferentes membros da equipe.
- [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome): Permite a depuração de aplicativos Next.js no navegador Chrome.

Certifique-se de instalar e configurar essas extensões em seu editor de código preferido para ajudar no desenvolvimento e garantir a qualidade do código.

## Configurações adiconais

```
    {
        "emmet.syntaxProfiles": {
            "javascript": "jsx"
        },
        "workbench.iconTheme": "symbols",
        "workbench.productIconTheme": "fluent-icons",
        "editor.inlineSuggest.enabled": true,
        "workbench.colorTheme": "Omni",
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
            "source.addMissingImports": true
        },
        "[prisma]": {
            "editor.formatOnSave": true
        },
        "emmet.includeLanguages": {
            "javascript": "javascriptreact"
        },
        "explorer.confirmDelete": false,
        "tabnine.experimentalAutoImports": true,
        "editor.fontSize": 18,
        "window.zoomLevel": -1,
        "symbols.hidesExplorerArrows": false,
        "git.enableSmartCommit": true,
        "git.confirmSync": false,
    }
```
