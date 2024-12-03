# Webpack TypeScript React Configuration

Этот проект представляет собой настроенную конфигурацию Webpack для разработки React приложений с использованием TypeScript.

## 🚀 Возможности

- TypeScript поддержка
- React 18
- Sass/SCSS поддержка
- Development и Production сборки
- Source Maps для разработки
- Hot Module Replacement (HMR)
- Оптимизация сборки

## 📁 Структура проекта

```
webpack/
├── build/            # Скомпилированные файлы
├── config/           # Конфигурационные файлы webpack
│   └── build/       # Модули конфигурации
├── public/          # Статические файлы
├── src/             # Исходный код
└── webpack.config.ts # Основной конфиг webpack
```

## 🛠 Технологии

- Webpack 5
- TypeScript
- React 18
- Sass
- HTML Webpack Plugin
- Mini CSS Extract Plugin

## 📥 Установка

```bash
# Клонировать репозиторий
git clone [url-репозитория]

# Перейти в директорию проекта
cd webpack

# Установить зависимости
npm install
```

## 🚦 Доступные скрипты

```bash
# Запуск сервера разработки
npm start

# Сборка для разработки
npm run build:dev

# Сборка для продакшена
npm run build:prod
```

## ⚙️ Конфигурация

Проект использует модульную конфигурацию Webpack, разделенную на несколько файлов:

- `webpack.config.ts` - основной конфигурационный файл
- `config/build/buildWebpack.ts` - сборка конфигурации
- `config/build/buildLoaders.ts` - настройка лоадеров
- `config/build/buildPlugins.ts` - настройка плагинов
- `config/build/buildResolvers.ts` - настройка резолверов
- `config/build/buildDevServer.ts` - настройка сервера разработки

## 🔧 Настройка окружения

По умолчанию сервер разработки запускается на порту 3000. Вы можете изменить порт, передав его через переменные окружения:

```bash
npm start -- --env port=4000
```

## 📝 Особенности

1. **TypeScript**
   - Полная поддержка TypeScript
   - Типизированная конфигурация webpack

2. **Режимы сборки**
   - Development режим с source maps
   - Production режим с оптимизацией

3. **Стили**
   - Поддержка CSS
   - Поддержка Sass/SCSS
   - Извлечение CSS в отдельные файлы для production

4. **Оптимизация**
   - Минификация кода в production
   - Хэширование файлов для кэширования
   - Очистка папки сборки

## 📜 Лицензия

ISC
