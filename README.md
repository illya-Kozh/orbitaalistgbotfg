TG Mini App — demo scaffold
===========================

Что внутри:
- server.js — Express backend (demo, in-memory store)
- public/index.html — frontend (Telegram Web App compatible UI)

Как запустить:
1. Убедись, что установлен Node.js (>=16).
2. В терминале в папке проекта выполните:
   npm install
   npm start
3. Открой в браузере http://localhost:3000
4. Для интеграции с Telegram: в BotFather укажи Web App URL (http://your-server.com/)

Примечание: это демо-реализация. Для продакшена нужно добавить базу данных, авторизацию,
хранение сессий и защиту от читов.
