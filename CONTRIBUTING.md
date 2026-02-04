# Contributing Guide / Руководство по внесению вклада

[English](#english) | [Русский](#russian)

---

<a name="english"></a>
## English

Thank you for your interest in contributing to the Gameloft JAR Archive!

### How to Contribute

#### 1. Adding Game Files

If you have JAR files to contribute:

1. Fork this repository
2. Create a new branch (`git checkout -b add-game-version`)
3. Follow the directory structure:
   ```
   /games/[game-name]/v[version]/[resolution]/[control-type]/
   ```
4. Add the JAR file with a descriptive name
5. Update the version table in README.md
6. Commit your changes
7. Push to your fork
8. Open a Pull Request

#### 2. File Naming Convention

Use this format for JAR files:
```
GameName_v[version]_[resolution]_[control]_[lang]_[mod].jar
```

Example:
```
WonderZoo_v1.0.0_240x320_touch_ru_original.jar
WonderZoo_v1.0.0_240x320_keypad_ru_mod.jar
```

#### 3. Required Information

When adding a game version, please provide:

- Game name and version
- Screen resolution
- Control type (touchscreen/keypad)
- Language
- Modified or original
- Source (if known)
- Any additional notes

#### 4. Reporting Issues

If you find broken links or incorrect information:

1. Open an issue
2. Describe the problem
3. Provide suggestions if possible

### Guidelines

- Verify the JAR file works before contributing
- Include accurate version information
- Respect copyright and intellectual property
- Only contribute files you legally own or have permission to share

---

<a name="russian"></a>
## Русский

Спасибо за ваш интерес к вкладу в Архив Gameloft JAR!

### Как внести вклад

#### 1. Добавление файлов игр

Если у вас есть JAR файлы для добавления:

1. Сделайте fork этого репозитория
2. Создайте новую ветку (`git checkout -b add-game-version`)
3. Следуйте структуре директорий:
   ```
   /games/[название-игры]/v[версия]/[разрешение]/[тип-управления]/
   ```
4. Добавьте JAR файл с описательным названием
5. Обновите таблицу версий в README.md
6. Зафиксируйте изменения
7. Отправьте в ваш fork
8. Откройте Pull Request

#### 2. Соглашение об именовании файлов

Используйте этот формат для JAR файлов:
```
НазваниеИгры_v[версия]_[разрешение]_[управление]_[язык]_[мод].jar
```

Пример:
```
WonderZoo_v1.0.0_240x320_touch_ru_original.jar
WonderZoo_v1.0.0_240x320_keypad_ru_mod.jar
```

#### 3. Необходимая информация

При добавлении версии игры, пожалуйста, предоставьте:

- Название игры и версию
- Разрешение экрана
- Тип управления (сенсор/клавиатура)
- Язык
- Модифицированная или оригинальная
- Источник (если известен)
- Любые дополнительные заметки

#### 4. Сообщение о проблемах

Если вы нашли неработающие ссылки или неверную информацию:

1. Откройте issue
2. Опишите проблему
3. Предоставьте предложения, если возможно

### Правила

- Проверьте, что JAR файл работает перед добавлением
- Включайте точную информацию о версии
- Уважайте авторские права и интеллектуальную собственность
- Добавляйте только файлы, которыми вы легально владеете или имеете разрешение делиться

---

### Questions? / Вопросы?

Open an issue if you have any questions about contributing.
Откройте issue, если у вас есть вопросы о внесении вклада.
