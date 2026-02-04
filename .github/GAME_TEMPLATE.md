# Game Template / Шаблон игры

This template can be used when adding a new game to the archive.
Этот шаблон можно использовать при добавлении новой игры в архив.

---

## Directory Structure / Структура директорий

```
games/
└── [game-name]/
    ├── README.md
    └── v[version]/
        ├── VERSION_INFO.md
        └── [resolution]/
            ├── touchscreen/
            │   └── README.md
            └── keypad/
                └── README.md
```

---

## README.md Template (for game root)

```markdown
# [Game Name] - Version Archive

## English

### Game Information

**[Game Name]** is a [game genre] by Gameloft. [Brief game description]

### Available Versions

This directory contains all available versions of [Game Name] for Java feature phones.

#### Version History

- **1.0.0** - [Release notes]
- More versions coming soon...

### Screen Resolutions

Common resolutions for this game:
- [List resolutions]

### Control Types

- **Touchscreen** - For devices with touch input
- **Keypad** - For traditional button-based phones

---

## Русский

### Информация об игре

**[Название игры]** - это [жанр игры] от Gameloft. [Краткое описание игры]

### Доступные версии

Эта директория содержит все доступные версии [Название игры] для Java телефонов.

#### История версий

- **1.0.0** - [Примечания к выпуску]
- Больше версий скоро...

### Разрешения экрана

Распространенные разрешения для этой игры:
- [Список разрешений]

### Типы управления

- **Сенсорный экран** - Для устройств с сенсорным вводом
- **Клавиатура** - Для традиционных кнопочных телефонов

---

### ⚠️ Notice / Уведомление

Games in this archive are primarily in Russian and may include modified versions.
Игры в этом архиве в основном на русском языке и могут включать модифицированные версии.
```

---

## VERSION_INFO.md Template

```markdown
# [Game Name] v[X.X.X]

## English

### Version Details

- **Version**: [X.X.X]
- **Release Date**: [Date or TBA]
- **Language**: [Language]
- **Developer**: Gameloft

### Available Builds

#### [Resolution]
- **Touchscreen**: Place JAR file in `[resolution]/touchscreen/` directory
- **Keypad**: Place JAR file in `[resolution]/keypad/` directory

### Game Features

- [Feature 1]
- [Feature 2]
- [Feature 3]

### Installation

1. Download the appropriate JAR file for your device
2. Transfer to your phone via Bluetooth, USB, or memory card
3. Install and run the JAR file

---

## Русский

### Детали версии

- **Версия**: [X.X.X]
- **Дата выхода**: [Дата или Будет объявлено]
- **Язык**: [Язык]
- **Разработчик**: Gameloft

### Доступные сборки

#### [Разрешение]
- **Сенсорный экран**: Поместите JAR файл в директорию `[resolution]/touchscreen/`
- **Клавиатура**: Поместите JAR файл в директорию `[resolution]/keypad/`

### Особенности игры

- [Особенность 1]
- [Особенность 2]
- [Особенность 3]

### Установка

1. Скачайте подходящий JAR файл для вашего устройства
2. Перенесите на телефон через Bluetooth, USB или карту памяти
3. Установите и запустите JAR файл

---

### ⚠️ Notice / Уведомление

Files will be added as they become available.
Файлы будут добавлены по мере их появления.
```

---

## Resolution Folder README.md Template

```markdown
# [Game Name] v[X.X.X] - [Resolution] [Control Type]

## Файлы / Files

Place JAR files here with the naming format:
```
[GameName]_v[X.X.X]_[resolution]_[control]_[lang]_[type].jar
```

Размещайте JAR файлы здесь с форматом именования:
```
[ИмяИгры]_v[X.X.X]_[разрешение]_[управление]_[язык]_[тип].jar
```

---

### File List / Список файлов

- Coming soon / Скоро будет добавлено

### Compatibility / Совместимость

This version is compatible with [control type] devices with [resolution] resolution.
Эта версия совместима с [тип управления] устройствами с разрешением [разрешение].
```

---

## Quick Command for Creating Structure

```bash
# Replace [game-name] and [version] with actual values
GAME="game-name"
VERSION="1.0.0"
RES="240x320"

mkdir -p "games/${GAME}/v${VERSION}/${RES}/{touchscreen,keypad}"

# Create README files
touch "games/${GAME}/README.md"
touch "games/${GAME}/v${VERSION}/VERSION_INFO.md"
touch "games/${GAME}/v${VERSION}/${RES}/touchscreen/README.md"
touch "games/${GAME}/v${VERSION}/${RES}/keypad/README.md"
```
