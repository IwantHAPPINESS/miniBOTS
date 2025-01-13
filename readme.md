# CRYCLANS Бот для MineBlaze.net

## Описание
Бот для автоматизации клановых процессов на сервере MineBlaze.net. Разработан специально для клана CRYCLANS.

## Основной функционал
1. **Автоматическое подключение к серверу:**
   - Автоматический вход на сервер
   - Автоматическая авторизация
   - Переход на сервер /s8
   - Телепортация на нужный варп
   - Автоматический перезаход каждые 30 минут
   - Система проверки состояния подключения

2. **Работа с клановым чатом:**
   - Отслеживание сообщений в клановом чате (/cc)
   - Обработка команд, начинающихся с "!"
   - Автоматические ответы на команды

3. **Система принятия заявок:**
   - Автоматическое отслеживание заявок на вступление в клан
   - Проверка игрока по черному списку
   - Автоматическое принятие/отклонение заявок
   - Автоматическая выдача ранга [Игрок]

4. **Система черного списка (ЧС):**
   - Хранение черного списка в JSON файле
   - Автоматическая проверка заявок по ЧС
   - Управление черным списком через команды

## Команды бота
- `!help` - показать список доступных команд
- `!status` - проверить статус бота
- `!online` - проверить активность бота
- `!requests` - проверить статус автопринятия заявок
- `!blacklist` - показать список игроков в ЧС
- `!addbl <ник>` - добавить игрока в ЧС
- `!removebl <ник>` - удалить игрока из ЧС

## Установка и настройка
1. Установите Node.js (версия 14+ рекомендуется). Это также установит npm (Node Package Manager).
   - [Node.js - Официальный сайт](https://nodejs.org/)
2. Установите необходимые зависимости:
   ```bash
   npm install
   ```
3. Отредактируйте конфигурацию в файле `bot.js`:
   - Укажите логин бота
   - Укажите пароль
   - Настройте нужный варп

4. Запуск бота:
   ```bash
   npm start
   ```

## Технические требования
- Node.js 14+
- Стабильное интернет-соединение
- Доступ к серверу MineBlaze.net

## Безопасность
- Бот использует защищенное соединение
- Пароли хранятся локально
- Автоматический перезаход предотвращает потерю соединения
- Черный список хранится локально в JSON файле

## Обработка ошибок
- Автоматическое переподключение при разрыве соединения
- Логирование ошибок
- Защита от крашей
- Периодическая проверка состояния подключения

## Файловая структура
(Добавьте описание файловой структуры, если необходимо)

## Поддержка
При возникновении проблем или вопросов обращайтесь:
- Discord: [ваш Discord]
- Telegram: [ваш Telegram]

## Обновления
**Текущая версия:** 1.1.0
- Базовый функционал подключения
- Система автопринятия заявок
- Клановый чат
- Автоматический перезаход
- Система черного списка
- Улучшенная обработка состояния подключения

**Планируемые обновления:**
(Добавьте информацию о планируемых обновлениях, если необходимо)

## Примечания
- Бот разработан специально для MineBlaze.net (по заказу клана Justice)
- Все функции соответствуют правилам сервера
- Регулярные обновления для поддержки актуальной версии сервера