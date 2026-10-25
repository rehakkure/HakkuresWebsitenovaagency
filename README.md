# ✳ NOVA AGENCY

> Dark-first digital agency landing page for ambitious brands, powered by a single lightweight HTML file.

[![Live-ready](https://img.shields.io/badge/status-live--ready-00a844?style=flat-square)](#-быстрый-старт) [![HTML](https://img.shields.io/badge/HTML5-static-00ff66?style=flat-square&logo=html5&logoColor=050706)](#-технологии) [![No build](https://img.shields.io/badge/build-none-050706?style=flat-square)](#-быстрый-старт)

NOVA AGENCY — эффектный одностраничный сайт digital-студии. Проект сочетает неоновую визуальную систему, интерактивный canvas-фон, плавные появления блоков, адаптивную навигацию и форму контакта без backend-зависимостей.

## ✨ Возможности

- **Hero-блок** с выразительной типографикой, CTA и animated ticker.
- **Секция услуг**: Web Development, AI & Chatbots, Automation и UI/UX Design.
- **Витрина кейсов** с атмосферными изображениями и hover-состояниями.
- **Секция команды** с демонстрационными ролями и статусами.
- **Контактная форма**, которая собирает данные и открывает письмо через `mailto:`.
- **Dark / light theme** с сохранением выбора в `localStorage`.
- **Адаптивная мобильная навигация** и responsive-layout для разных экранов.
- **Canvas-звёзды** с лёгким дрейфом и реакцией на курсор.
- **Scroll reveal-анимации** через `IntersectionObserver`.
- **Accessibility-friendly детали**: `aria-label`, фокусируемые элементы, `prefers-reduced-motion`.

## 🛠 Технологии

- HTML5 — семантическая структура страницы;
- CSS3 — custom properties, Grid, Flexbox, media queries, animations;
- Vanilla JavaScript — без фреймворков и сборщиков;
- Google Fonts — Inter и Space Grotesk;
- Unsplash — фоновые изображения для демонстрационных кейсов.

## 🚀 Быстрый старт

Проект не требует Node.js, зависимостей или сборки.

### Вариант 1 — открыть локально

```bash
git clone https://github.com/rehakkure/HakkuresWebsitenovaagency.git
cd HakkuresWebsitenovaagency
```

Откройте `index.html` в браузере.

### Вариант 2 — локальный статический сервер

```bash
python -m http.server 8000
```

Затем перейдите на [http://localhost:8000](http://localhost:8000).

## 📁 Структура

```text
.
├── index.html   # вся разметка, стили и клиентская логика
├── README.md    # документация проекта
└── .gitignore   # системные и служебные файлы, исключённые из Git
```

## ⚙️ Перед публикацией

В `index.html` находятся демонстрационные контакты, которые стоит заменить на реальные:

1. `hello@nova.agency` в обработчике формы — на рабочий email;
2. `https://t.me/` — на Telegram-аккаунт или канал студии;
3. `https://github.com/` — на настоящий GitHub-профиль;
4. изображения Unsplash — на собственные оптимизированные ассеты, если нужен полностью автономный офлайн-режим.

> Форма не отправляет данные на сервер: она формирует письмо и передаёт его в почтовое приложение пользователя.

## 🎨 Визуальная система

| Элемент | Решение |
| --- | --- |
| Основной фон | Глубокий почти чёрный `#050706` |
| Акцент | Неоновый green `#00ff66` |
| Вторичный акцент | Cyan `#00f3ff` |
| Display-шрифт | Space Grotesk |
| Текстовый шрифт | Inter |
| Стиль | Tech / editorial / premium dark |

## 🌐 Деплой

Поскольку это статический сайт, его можно разместить практически на любом static hosting:

- **GitHub Pages** — включите Pages для ветки `main`;
- **Netlify** — импортируйте репозиторий без build command;
- **Vercel** — выберите framework preset `Other` и оставьте build command пустой;
- **Cloudflare Pages** — подключите репозиторий без шага сборки.

## 📌 Дальнейшее развитие

- подключить backend или serverless-функцию для обработки формы;
- добавить реальные кейсы, отзывы и аналитику;
- вынести CSS и JavaScript в отдельные файлы при расширении проекта;
- добавить Open Graph-изображение и favicon;
- заменить внешние изображения и шрифты на локальные для полного контроля над производительностью.

## 📄 Лицензия

Проект предназначен для демонстрационных и коммерческих целей NOVA AGENCY. При повторном использовании замените брендинг, контакты и материалы на собственные.

---

Made with precision for **NOVA AGENCY** · 2026
