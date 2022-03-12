# RTUweatherBot

**RTUweatherBot** - это Telegram-бот, предназначенный для подписки на 
информацию о погодных условиях в конкретном городе и получении необходимых уведомлений.

## Settings
Настройка производится через переменные окружения. 
Для запуска в docker-compose переменные окружения необходимо объявить в файле ``./.env``.

Доступные переменные окружения:

| Наименование      | Описание                            |
|-------------------|-------------------------------------|
| RTU_WEATHER_BOT_TOKEN | Токен для авторизации telegram-бота |

