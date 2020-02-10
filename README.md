# robo-crawler

Pesquisa de preços de quartos por um intervalo de período específico


## Pré requisitos

- [Node.js](https://nodejs.org) versão 10.14.1 ou maior (não foi possível criar nada na versão 8.1.3 como solicitado)

    ```bash
    # ver versão do node
    node --version
    ```

## Rodar o bot

- Instalar módulos

    ```bash
    npm install
    ```

- Startar o bot

    ```bash
    npm start
    ```

## Testando o bot com Bot Framework Emulator

[Bot Framework Emulator](https://github.com/microsoft/botframework-emulator) é um aplicação desktop que ajuda os desenvolvedores a testar e debugar seus códigos localmente.

- Instalar o Bot Framework Emulator versão 4.3.0 ou maior [here](https://github.com/Microsoft/BotFramework-Emulator/releases)

### Conectando ao Bot Framework Emulator

- Startar a aplicação no terminal com npm start
- Entrar no Bot Framework Emulator
- File -> Open Bot
- Entrar com a url do bot `http://localhost:3978/api/messages`