
# Telegram Bot: Консультації

## Що вміє бот

- Приймає короткі запитання, запити на консультацію та на вартість
- Надсилає їх адміну з кнопкою "Відповісти"
- Дозволяє адміну відповісти прямо з Telegram
- Має антиспам-фільтр (видаляє посилання)
- Працює на Render через Node.js

## Запуск на Render

1. Завантаж код у GitHub
2. У Render створити Web Service:
   - Build command: `npm install`
   - Start command: `npm start`
   - Environment: `Node`
   - Environment Variables:
     - `BOT_TOKEN=...` (вставити ваш токен)

3. Натиснути Deploy
