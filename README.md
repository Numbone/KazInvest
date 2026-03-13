# KazInvest AI Chat

Fullstack AI-чат приложение с поддержкой голосового ввода.

## Технологии

- **Frontend**: React + Vite + Tailwind CSS
- **Backend**: Node.js + Express
- **AI**: OpenAI ChatGPT API
- **Голосовой ввод**: Web Speech API

## Структура проекта

```
kazInvest/
├── client/          # React frontend
│   └── src/
│       ├── components/   # UI компоненты
│       ├── hooks/        # React хуки (Speech Recognition)
│       └── App.jsx       # Главный компонент
├── server/          # Express backend
│   ├── index.js     # Сервер и API
│   └── .env         # Переменные окружения
└── package.json     # Корневые скрипты
```

## Запуск

### 1. Установка зависимостей

```bash
npm run install:all
```

### 2. Настройка API ключа

В файле `server/.env` укажите ваш OpenAI API ключ:

```
OPENAI_API_KEY=sk-your-actual-key
```

### 3. Запуск сервера (в одном терминале)

```bash
npm run dev:server
```

### 4. Запуск клиента (в другом терминале)

```bash
npm run dev:client
```

Приложение откроется на http://localhost:5173

## Функции

- Текстовый чат с ChatGPT
- История сообщений в рамках сессии
- Голосовой ввод через микрофон (Web Speech API)
- Индикатор загрузки при ожидании ответа
- Обработка ошибок API
# KazInvest
