# TV QR Code - Privacy Policy

Веб-сайт с политикой конфиденциальности для приложения TV QR Code.

## Описание

Этот проект содержит статический веб-сайт, отображающий политику конфиденциальности для Android TV приложения TV QR Code.

## Структура проекта

- `index.html` - главная страница с политикой конфиденциальности
- `styles.css` - стили оформления
- `script.js` - JavaScript для динамического контента

## Технологии

- HTML5
- CSS3
- JavaScript (Vanilla)
- Nginx (для production)

## Развертывание на Railway

### Быстрый старт

1. Перейдите на [Railway](https://railway.com) и войдите в аккаунт
2. Нажмите "New Project" → "Deploy from GitHub repo"
3. Выберите репозиторий `Abenedis/TVRQ`
4. Railway автоматически обнаружит `Dockerfile` и развернет проект
5. После деплоя Railway предоставит публичный URL для вашего сайта

### Альтернативный способ (через Railway CLI)

```bash
# Установите Railway CLI
npm i -g @railway/cli

# Войдите в Railway
railway login

# Инициализируйте проект
railway init

# Разверните проект
railway up
```

### Конфигурация

Проект использует:
- `Dockerfile` - для сборки Docker образа с Nginx
- `nginx.conf` - конфигурация Nginx для статических файлов
- `railway.json` - настройки деплоя на Railway

