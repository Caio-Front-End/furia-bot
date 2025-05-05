# 🦁 Bot Telegram FURIA CS2

Este é um bot para Telegram feito em Node.js com a biblioteca `node-telegram-bot-api`, criado para informar fãs sobre tudo relacionado ao time de **Counter-Strike 2 da FURIA**.

## 🚀 Funcionalidades

- `/start` – Mensagem de boas-vindas com menu de comandos.
- `/proximoJogo` – Exibe informações sobre o próximo jogo da FURIA.
- `/elenco` – Mostra o elenco atual da equipe.
- `/ranking` – Informa a posição da FURIA no ranking.
- `/loja` – Link para a loja oficial da FURIA.
- `/noticias` – Traz as últimas notícias sobre o time.
- `/ajuda` – Explica todos os comandos disponíveis.

## 📦 Tecnologias usadas

- [Node.js](https://nodejs.org/)
- [node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api)
- [dotenv](https://www.npmjs.com/package/dotenv)

## ⚙️ Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/furia-bot.git
   cd furia-bot
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Crie um arquivo `.env` na raiz com o seguinte conteúdo:
   ```
   TELEGRAM_TOKEN=seu_token_do_bot
   ```

4. Inicie o bot:
   ```bash
   node index.js
   ```

## 📌 Observações

Este projeto é um exemplo simples e pode ser expandido para buscar dados em tempo real de APIs esportivas, integração com banco de dados e muito mais.
