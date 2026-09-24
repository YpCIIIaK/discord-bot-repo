# discord-bot-repo

Краткое описание проекта: Discord-бот на Node.js.

## Установка
```bash
git clone https://github.com/YpCIIIaK/discord-bot-repo.git
cd discord-bot-repo
npm install
```

## Запуск
```bash
cp .env.example .env   # заполнить DISCORD_TOKEN
npm start
```

## Структура
```
src/        — исходный код бота
.env        — секреты (не коммитить)
README.md   — этот файл
```

## Безопасность
- Токен бота хранить только в `.env`, добавить его в `.gitignore`.
- Не логировать содержимое токена и приватные сообщения.
- Ограничивать права бота (минимально необходимые интенты).