# react-test
Сборка для удобной верстки

# Установка
Склонировать этот репозиторий и запустить `npm install` для установки зависимостей

## Структура

```
|--build/                  # →  Папка сборки
|
|--node_modules/           # →  Npm зависимости
|--src/                    # →  Исходники
|  |--blocks/              # →  Блоки проекта: шапка, футер, лого и т.д.
|  |--favicon/             # →  Фавиконки
|  |--fonts/               # →  Шрифты
|  |--images/              # →  Изображения
|  |  |--content           # →  Основные
|  |  |--sprites           # →  Спрайты
|  |  |  |--png            # →  Спрайты png
|  |  |  |--svg            # →  Спрайты svg
|  |  |--temp              # →  Временные
|  |--scripts/             # →  JS
|  |--static/              # →  Статичные файлы (копируются в корень проекта)
|  |--styles/              # →  Стили
|  |  |--base/             # →  Основные стили (переменные, функции, миксины)
|--.babelrc
|--.editorconfig
|--.eslintrc
|--.gitignore
|--.stylelintignore
|--.stylelintrc
|--gulpConfig.js/          # →  Основные пути проекта
|--gulpfile.js/            # →  Сборщик
|--package.json
```

# Font Шрифты
Or get from google-webfonts-helper: [https://google-webfonts-helper.herokuapp.com/fonts](https://google-webfonts-helper.herokuapp.com/fonts)

### Font weight helper

*   **100** - Extra Light or Ultra Light
*   **200** - Light or Thin
*   **300** - Book or Demi
*   **400** - Regular or Normal
*   **500** - Medium
*   **600** - Semibold or Demibold
*   **700** - Bold
*   **800** - Black or Extra Bold or Heavy
*   **900** - Extra Black or Fat or Ultra Blac or Heavy
