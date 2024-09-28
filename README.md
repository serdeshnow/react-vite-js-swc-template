# react-vite-js-swc-template

> Данный шаблон проекта предназначен для быстрого создания react-приложений на языке JavaScript, созданный на базе vite-swc. 

> Дата создания шаблона: 28.09.2024

## Quick start:

### 1. `>> cd app`
### 2. `>> npm i`
### 3. `>> npm run dev`

## Change list: 

## `/app`:

### `/.editorconfig`:
- создан и сконфигурирован

### `/.prettierrc.json`:
- создан и сконфигурирован

### `/package.json`:
- `"sass": "^1.79.4"` - [css-препроцессор](https://www.npmjs.com/package/sass)
- `"prettier": "^3.3.3"`
- `"vite-plugin-svgr": "^4.2.0"` - [импорт файлов `.svg` как react-компонент](https://www.npmjs.com/package/vite-plugin-svgr)
> Пример использования пакета `"vite-plugin-svgr"` есть в `./App.jsx `
- `"browserslist": {...}`

### `./index.html`:
- Добавлена базовая мета-информация
- Настроен импорт `main.jsx` файла

### `/src`:
- Стандартные стили были перенесены в отдельную папку `/styles`, туда входят:
  - `App.scss`
  - `class-names.scss` - отдельный файл для создания универсальных классовых имен 
  - `index.scss` - файл со стилями `:root` и тегов (?)
  - `variables.scss` - отдельный файл для создания css-переменных 
  - `normalize.css` - нормализатор стилей 
  
Последние 4 стиля импортированы в `/main.jsx`.
