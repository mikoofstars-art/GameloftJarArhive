# Repository Overview / Обзор репозитория

[English](#english) | [Русский](#russian)

---

<a name="english"></a>
## English

### Project Summary

The **Gameloft JAR Archive** is a comprehensive preservation project dedicated to collecting, organizing, and archiving Java mobile games (J2ME) from Gameloft. The project focuses on maintaining multiple versions, screen resolutions, and modifications of classic mobile games for future generations.

### Key Features

- **Multi-version Support**: Track all versions from initial release to latest
- **Resolution Coverage**: Support for all screen resolutions (128x128 to 352x416)
- **Control Type Variants**: Separate archives for touchscreen and keypad devices
- **Modification Tracking**: Both original and modified versions
- **Bilingual Documentation**: Full documentation in English and Russian
- **Structured Organization**: Systematic folder structure for easy navigation

### Current Status

- **Active Games**: 1 (Wonder Zoo)
- **Total Versions**: 28 files across 17 version releases
- **Version Range**: 1.0.4 - 1.4.6
- **Screen Resolutions**: 7 different resolutions
- **Documentation**: Complete
- **Languages**: English, Russian, Portuguese (primarily Russian)

### Repository Structure

```
Gameloft-JAR-Archive/
├── Documentation
│   ├── README.md           - Main repository readme
│   ├── CONTRIBUTING.md     - Contribution guidelines
│   ├── FAQ.md              - Frequently asked questions
│   ├── STRUCTURE.md        - Repository structure details
│   ├── WISHLIST.md         - Games we're looking for
│   ├── LICENSE             - License information
│   └── OVERVIEW.md         - This file
│
├── GitHub Templates
│   └── .github/
│       ├── ISSUE_TEMPLATE/
│       │   └── add-game-version.md
│       └── GAME_TEMPLATE.md
│
└── Games Archive
    └── games/
        ├── README.md
        └── wonder-zoo/
            ├── README.md
            └── v1.0.0/
                ├── VERSION_INFO.md
                └── [resolutions]/
                    ├── touchscreen/
                    └── keypad/
```

### Documentation Files

| File | Purpose |
|------|---------|
| `README.md` | Main project introduction and overview |
| `CONTRIBUTING.md` | Guidelines for contributing to the archive |
| `FAQ.md` | Common questions and answers |
| `STRUCTURE.md` | Detailed repository structure explanation |
| `WISHLIST.md` | List of games we'd like to archive |
| `LICENSE` | Licensing and legal information |
| `OVERVIEW.md` | This comprehensive overview document |

### How to Use This Archive

#### For Players

1. Browse the `/games` directory
2. Find your desired game and version
3. Select the appropriate screen resolution
4. Choose touchscreen or keypad version
5. Download the JAR file
6. Install on your Java-compatible device or emulator

#### For Contributors

1. Read `CONTRIBUTING.md`
2. Check `WISHLIST.md` for needed games
3. Use `.github/GAME_TEMPLATE.md` for new games
4. Follow the naming conventions
5. Submit via pull request

#### For Preservationists

- All versions are tracked with detailed metadata
- Original and modified versions are clearly labeled
- Version history is documented
- Multiple resolutions ensure compatibility preservation

### Next Steps

1. **Complete Wonder Zoo collection** - All versions and resolutions
2. **Start Asphalt series** - High-demand racing games
3. **Add Real Football series** - Popular sports titles
4. **Expand to other genres** - Adventure, puzzle, casual games

### Technical Specifications

- **Platform**: Java ME (J2ME)
- **File Format**: JAR (Java Archive)
- **Supported Resolutions**: 128x128 to 352x416
- **Languages**: Primarily Russian, some English
- **Control Types**: Touchscreen and Keypad

### Community

- **Contributions**: Always welcome
- **Issues**: Use GitHub issues for discussions
- **Updates**: Regular additions as games become available
- **Preservation Goal**: Complete Gameloft J2ME library

---

<a name="russian"></a>
## Русский

### Краткое описание проекта

**Архив Gameloft JAR** - это комплексный проект по сохранению, посвященный сбору, организации и архивированию Java мобильных игр (J2ME) от Gameloft. Проект фокусируется на поддержании множественных версий, разрешений экрана и модификаций классических мобильных игр для будущих поколений.

### Ключевые особенности

- **Поддержка множества версий**: Отслеживание всех версий от первого релиза до последнего
- **Покрытие разрешений**: Поддержка всех разрешений экрана (от 128x128 до 352x416)
- **Варианты управления**: Отдельные архивы для сенсорных и кнопочных устройств
- **Отслеживание модификаций**: Как оригинальные, так и модифицированные версии
- **Двуязычная документация**: Полная документация на английском и русском
- **Структурированная организация**: Систематическая структура папок для легкой навигации

### Текущий статус

- **Активные игры**: 1 (Wonder Zoo)
- **Всего версий**: 28 файлов в 17 релизах
- **Диапазон версий**: 1.0.4 - 1.4.6
- **Разрешения экрана**: 7 различных разрешений
- **Документация**: Завершена
- **Языки**: Английский, Русский, Португальский (в основном русский)

### Структура репозитория

```
Gameloft-JAR-Archive/
├── Документация
│   ├── README.md           - Основной readme репозитория
│   ├── CONTRIBUTING.md     - Руководство по внесению вклада
│   ├── FAQ.md              - Часто задаваемые вопросы
│   ├── STRUCTURE.md        - Детали структуры репозитория
│   ├── WISHLIST.md         - Игры, которые мы ищем
│   ├── LICENSE             - Информация о лицензии
│   └── OVERVIEW.md         - Этот файл
│
├── Шаблоны GitHub
│   └── .github/
│       ├── ISSUE_TEMPLATE/
│       │   └── add-game-version.md
│       └── GAME_TEMPLATE.md
│
└── Архив игр
    └── games/
        ├── README.md
        └── wonder-zoo/
            ├── README.md
            └── v1.0.0/
                ├── VERSION_INFO.md
                └── [разрешения]/
                    ├── touchscreen/
                    └── keypad/
```

### Файлы документации

| Файл | Назначение |
|------|------------|
| `README.md` | Основное введение и обзор проекта |
| `CONTRIBUTING.md` | Руководство по внесению вклада в архив |
| `FAQ.md` | Часто задаваемые вопросы и ответы |
| `STRUCTURE.md` | Подробное объяснение структуры репозитория |
| `WISHLIST.md` | Список игр, которые мы хотели бы архивировать |
| `LICENSE` | Лицензирование и юридическая информация |
| `OVERVIEW.md` | Этот комплексный обзорный документ |

### Как использовать этот архив

#### Для игроков

1. Просмотрите директорию `/games`
2. Найдите желаемую игру и версию
3. Выберите подходящее разрешение экрана
4. Выберите сенсорную или кнопочную версию
5. Скачайте JAR файл
6. Установите на совместимое Java устройство или эмулятор

#### Для контрибьюторов

1. Прочитайте `CONTRIBUTING.md`
2. Проверьте `WISHLIST.md` для нужных игр
3. Используйте `.github/GAME_TEMPLATE.md` для новых игр
4. Следуйте соглашениям об именовании
5. Отправьте через pull request

#### Для архивариусов

- Все версии отслеживаются с подробными метаданными
- Оригинальные и модифицированные версии четко помечены
- История версий документирована
- Множественные разрешения обеспечивают сохранение совместимости

### Следующие шаги

1. **Завершить коллекцию Wonder Zoo** - Все версии и разрешения
2. **Начать серию Asphalt** - Востребованные гоночные игры
3. **Добавить серию Real Football** - Популярные спортивные игры
4. **Расширить на другие жанры** - Приключения, головоломки, казуальные игры

### Технические характеристики

- **Платформа**: Java ME (J2ME)
- **Формат файла**: JAR (Java Archive)
- **Поддерживаемые разрешения**: От 128x128 до 352x416
- **Языки**: В основном русский, немного английский
- **Типы управления**: Сенсорный экран и клавиатура

### Сообщество

- **Вклады**: Всегда приветствуются
- **Проблемы**: Используйте GitHub issues для обсуждений
- **Обновления**: Регулярные дополнения по мере появления игр
- **Цель сохранения**: Полная библиотека J2ME Gameloft

---

### Quick Links / Быстрые ссылки

- [Main README / Главный README](./README.md)
- [Start Contributing / Начать вносить вклад](./CONTRIBUTING.md)
- [Ask Questions / Задать вопросы](./FAQ.md)
- [Game Wishlist / Список желаемых игр](./WISHLIST.md)

---

**Status**: 🟢 Active | Активен
**Last Updated**: 2026-02-05
**Maintainer**: Community-driven / Поддерживается сообществом
