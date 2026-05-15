# Aston React Learning

Учебный проект, выполненный в рамках подготовки к стажировке в Aston. Приложение на базе JSONPlaceholder API — работа с публичными данными (посты, пользователи, альбомы, фото, комментарии, задачи).

Задача — изучить и применить на практике современный стек React-разработки: Redux Toolkit, React Router, TypeScript, архитектурные подходы. 

🔗 **[Live Demo](https://gupre.github.io/Aston-React-learning/)** 
---
Страницы:
- Список постов с фильтрацией по длине
- Детальная страница поста с комментариями
- Посты конкретного пользователя
- Альбомы пользователя
- Фото внутри альбома
- Задачи (todos) пользователя

Что реализовано технически:
- FSD-архитектура (app / entities / features / pages / shared / widgets) — полноценная, не просто папки
- Redux Toolkit с разделёнными слайсами для постов и пользователей
- React Router с вложенными маршрутами
- Кастомная тема (светлая/тёмная) через Context API + ThemeProvider + хук useTheme
- HOC withLoading для состояния загрузки
- CSS-модули везде
- TypeScript типы вынесены отдельно для каждой сущности

---

## Стек

| Технология | Версия |
|---|---|
| React | 19 |
| TypeScript | 5.9 |
| Redux Toolkit | 2.11 |
| React Router | 7 |
| Vite | 7 |
| ESLint | 9 |

---

## Запуск

```bash
git clone https://github.com/gupre/Aston-React-learning.git
cd Aston-React-learning
npm install
npm run dev
```

Приложение откроется на `http://localhost:5173`

---

## Цель проекта

Практическое освоение:
- Построение Redux store с Redux Toolkit (slices, selectors, thunks)
- Клиентская маршрутизация с React Router v7
- Типизация компонентов, пропсов и Redux state с TypeScript
- Структурирование проекта по компонентам и слоям
- Настройка инструментов качества кода (ESLint, TypeScript strict mode)
