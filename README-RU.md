# Cash Detective Bot

Cash Detective Bot - это Telegram-бот, созданный для управления вашими финансами. Он помогает отслеживать ваши расходы, категоризировать их и анализировать ваши финансовые привычки через различные графики.

## Основные функции

1. **Добавление трат**:
   - Пользователи могут легко добавлять свои траты с описанием, стоимостью и категорией.
   
2. **Управление категориями**:
   - Пользователи могут создавать и просматривать категории для лучшей организации своих расходов.
   
3. **Добавление средств**:
   - Пользователи могут обновлять свой баланс, добавляя средства на свой счет.
   
4. **Просмотр баланса**:
   - Пользователи могут проверять свой текущий баланс в любое время.
   
5. **Анализ финансов**:
   - Пользователи могут анализировать свои расходы через различные графики, включая историю расходов, распределение расходов по категориям и дням недели и т.д.

## Установка и запуск

1. Клонируйте репозиторий:

```bash
git clone https://github.com/DeevsTheBest/cash-detective-bot.git
cd cash-detective-bot
```

2. Установите зависимости:

```bash
pip install -r requirements.txt
```

4. Создайте .env с токеном и путем до базы
```
BOT_TOKEN = 'your-telegram-bot-token'
STORAGE_PATH = 'storage/'
```

3. Запустите бота:

```bash
python main.py
```

Теперь ваш бот должен быть в сети и готов к использованию в Telegram!

## Запуск тестов

Для запуска тестов выполните следующую команду в корневом каталоге проекта:

```bash
python tests.py
```

Это запустит все тесты в директории `tests`, и вы увидите результаты тестирования в консоли.

## Генерация Демонстрационных Данных

Для демонстрационных целей вы можете легко генерировать примеры данных с помощью скрипта `gen_sample_data.py`. Этот скрипт создает набор случайных покупок вместе с списком категорий и сохраняет их в файл, который можно использовать для тестирования бота.
