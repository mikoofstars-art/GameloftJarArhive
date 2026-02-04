# Repository Structure / Структура репозитория

## English

### Directory Tree

```
Gameloft-JAR-Archive/
│
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── add-game-version.md    # Template for adding new games
│
├── games/                          # Main games directory
│   ├── README.md                   # Games archive overview
│   │
│   └── wonder-zoo/                 # Wonder Zoo game directory
│       ├── README.md               # Wonder Zoo information
│       │
│       ├── v1.0.0/                 # Version 1.0.0
│       │   ├── VERSION_INFO.md     # Version details
│       │   │
│       │   └── 240x320/            # Screen resolution
│       │       ├── touchscreen/    # Touchscreen versions
│       │       │   ├── README.md
│       │       │   └── *.jar       # JAR files here
│       │       │
│       │       └── keypad/         # Keypad versions
│       │           ├── README.md
│       │           └── *.jar       # JAR files here
│       │
│       ├── v1.1.0/                 # Version 1.1.0 (future)
│       │   └── ...
│       │
│       └── v1.2.0/                 # Version 1.2.0 (future)
│           └── ...
│
├── .gitignore                      # Git ignore rules
├── CONTRIBUTING.md                 # Contribution guidelines
├── LICENSE                         # License information
├── README.md                       # Main repository readme
└── STRUCTURE.md                    # This file
```

### File Naming Convention

JAR files should follow this pattern:
```
GameName_v[Version]_[Resolution]_[Control]_[Language]_[Type].jar
```

**Examples:**
- `WonderZoo_v1.0.0_240x320_touch_ru_original.jar`
- `WonderZoo_v1.0.0_240x320_keypad_ru_mod.jar`
- `WonderZoo_v1.5.0_176x220_keypad_en_original.jar`

### Adding New Games

To add a new game, create this structure:
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

## Русский

### Дерево директорий

```
Gameloft-JAR-Archive/
│
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── add-game-version.md    # Шаблон для добавления новых игр
│
├── games/                          # Основная директория игр
│   ├── README.md                   # Обзор архива игр
│   │
│   └── wonder-zoo/                 # Директория игры Wonder Zoo
│       ├── README.md               # Информация о Wonder Zoo
│       │
│       ├── v1.0.0/                 # Версия 1.0.0
│       │   ├── VERSION_INFO.md     # Детали версии
│       │   │
│       │   └── 240x320/            # Разрешение экрана
│       │       ├── touchscreen/    # Сенсорные версии
│       │       │   ├── README.md
│       │       │   └── *.jar       # JAR файлы здесь
│       │       │
│       │       └── keypad/         # Версии с клавиатурой
│       │           ├── README.md
│       │           └── *.jar       # JAR файлы здесь
│       │
│       ├── v1.1.0/                 # Версия 1.1.0 (будущее)
│       │   └── ...
│       │
│       └── v1.2.0/                 # Версия 1.2.0 (будущее)
│           └── ...
│
├── .gitignore                      # Правила игнорирования Git
├── CONTRIBUTING.md                 # Руководство по внесению вклада
├── LICENSE                         # Информация о лицензии
├── README.md                       # Основной readme репозитория
└── STRUCTURE.md                    # Этот файл
```

### Соглашение об именовании файлов

JAR файлы должны следовать этому паттерну:
```
ИмяИгры_v[Версия]_[Разрешение]_[Управление]_[Язык]_[Тип].jar
```

**Примеры:**
- `WonderZoo_v1.0.0_240x320_touch_ru_original.jar`
- `WonderZoo_v1.0.0_240x320_keypad_ru_mod.jar`
- `WonderZoo_v1.5.0_176x220_keypad_en_original.jar`

### Добавление новых игр

Для добавления новой игры создайте эту структуру:
```
games/
└── [название-игры]/
    ├── README.md
    └── v[версия]/
        ├── VERSION_INFO.md
        └── [разрешение]/
            ├── touchscreen/
            │   └── README.md
            └── keypad/
                └── README.md
```

---

### Legend / Легенда

- `*.jar` - Java archive files / JAR файлы Java
- `*.md` - Markdown documentation / Markdown документация
- `v[x.x.x]` - Version number / Номер версии
- `[resolution]` - Screen resolution (e.g., 240x320) / Разрешение экрана
- `touchscreen` - Touch input devices / Устройства с сенсорным вводом
- `keypad` - Button input devices / Устройства с кнопочным вводом
