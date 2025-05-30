# 🚖 TaxiReact

**TaxiReact** — это одностраничное приложение (SPA) для службы такси, разработанное с использованием **React + Vite**.  
Проект представляет собой **рефакторинг** [предыдущей PHP-версии с MySQL и Telegram API](https://github.com/OlehBilenkyi/Taxi), с акцентом на современный фронтенд, модульную структуру и лучшие практики React-разработки.

> 🛠️ **Старый проект**: [Taxi (PHP)](https://github.com/OlehBilenkyi/Taxi)

---

## 👥 Соавторы

- 👨‍💻 Основной разработчик: [Oleh Bilenkyi](https://github.com/OlehBilenkyi)
- 🤝 Идея и поддержка: Друг (можно указать GitHub, если есть)

---

## 🚀 Технологии и стек

| Инструмент | Назначение |
|-----------|------------|
| ![React](https://img.shields.io/badge/-React-20232a?style=flat&logo=react) | Фреймворк для построения UI |
| ![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat&logo=vite&logoColor=white) | Быстрый инструмент сборки |
| ![SASS](https://img.shields.io/badge/-SASS-cc6699?style=flat&logo=sass&logoColor=white) | Стилизация и модульные CSS |
| ![ESLint](https://img.shields.io/badge/-ESLint-4B32C3?style=flat&logo=eslint&logoColor=white) | Анализатор кода |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-f7df1e?style=flat&logo=javascript&logoColor=black) | Язык логики |
| ![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white) | Контроль версий |

---

## 📁 Структура проекта

<details>
<summary>Открыть структуру</summary>

TaxiReact/
├── public/
├── src/
│ ├── App.jsx
│ ├── main.jsx
│ ├── App.css / index.css
│ ├── styles/ # Глобальные переменные
│ │ └── variables.css
│ ├── Pages/ # Страницы маршрутов
│ │ ├── HomePage/
│ │ ├── NewsReviews/
│ │ ├── Vehicle/
│ │ └── Videos/
│ ├── components/
│ │ ├── HomePage/
│ │ │ ├── Hero/
│ │ │ ├── Advantages/
│ │ │ │ ├── AdvantagesBox/
│ │ │ │ └── AdvantagesH2/
│ │ ├── Layout/
│ │ │ ├── Header/
│ │ │ └── Footer/
│ │ ├── NewsReviewsSection/
│ │ ├── VehicleFleet/
│ │ └── VideosOnYouTube/
├── vite.config.js
├── package.json
└── README.md

yaml
Копировать
Редактировать

</details>

---

## 🧩 Страницы и компоненты

- **HomePage** — главная страница:
  - `Hero` — баннер с призывом
  - `Advantages` — преимущества службы
  - `NewsReviews` — отзывы и публикации
  - `VehicleFleet` — автопарк
  - `VideosOnYouTube` — видеоконтент

---

## 📦 Установка и запуск

```bash
# 1. Клонировать репозиторий
git clone https://github.com/OlehBilenkyi/TaxiReact.git
cd TaxiReact

# 2. Установить зависимости
npm install

# 3. Запустить в режиме разработки
npm run dev

# 4. Собрать проект для продакшена
npm run build
🔗 Старый проект (архив)
Если интересно, с чего всё начиналось — посмотри первую версию проекта на PHP:

📂 Taxi (Legacy PHP) — https://github.com/OlehBilenkyi/Taxi

📬 Контакты
Если у тебя есть вопросы или предложения — пиши:

GitHub: @OlehBilenkyi

Email: I3eLuy@gmail.com

📄 Лицензия
Этот проект распространяется под лицензией MIT. Подробнее смотри в LICENSE.

