# 🏢 Uzum Market | Складской Дашборд Сменных Начальников (WMS Analytics)
### 📊 Система Мониторинга KPI, Производительности (OPS) и Контроля Качества на Главном Складе

<div align="center">

![Складской Дашборд](image/dashboard_preview.png)

### 🌐 **[👉 ОТКРЫТЬ LIVE DEMO В БРАУЗЕРЕ 👈](https://theanvarow.github.io/Werehose-Dashbord/)**

<br/>

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Онлайн_Портал-FF6D00?style=for-the-badge&logo=googlechrome&logoColor=white)](https://theanvarow.github.io/Werehose-Dashbord/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Репозиторий-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/theanvarow/Werehose-Dashbord)
[![Google Sheets](https://img.shields.io/badge/Google%20Sheets-Live%20Sync-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)](https://sheets.google.com)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Charts-Chart.js%20v4-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![Status](https://img.shields.io/badge/Статус-Активный_Продакшн-00C853?style=for-the-badge)](https://github.com/theanvarow/Werehose-Dashbord)

</div>

---

## 🎯 Цель Проекта (Project Objective)

**Складской Дашборд Uzum Market (Главный Склад — Отдел Товародвижения / Входящий Поток)** — это комплексная аналитическая веб-панель реального времени, разработанная для начальников смен, операционных менеджеров и руководства логистического хаба.

### 📌 Ключевые Задачи и Преимущества:
1. **Оперативный мониторинг 24/7:** Автоматическое отслеживание ключевых показателей производительности (OPS) и выполнения планов по всем 4 сменным бригадам (*Бригада 1, 2, 3, 4*).
2. **Контроль и минимизация ошибок:** Мгновенное выявление ошибок пересчета (*Пересчет*), некорректного категорийного размещения (*Неправильные категории*) и нулевых актов (*Акт закрыт с нулевым*).
3. **Мотивация и рейтинг смен (Leaderboard):** Расчет общего рейтинга (Score), определение лучших зон (Best Zone) и оценка эффективности каждого сменного руководителя.
4. **Сквозная синхронизация с Google Таблицами (Live Sync):** Работает без сложной серверной инфраструктуры — все данные, графики и метрики обновляются напрямую из облачных Google Таблиц в реальном времени.

---

## 🌐 Ссылка на Рабочий Сайт (Live Demo Link)

> 🚀 **Рабочая версия системы доступна онлайн:**
> **[https://theanvarow.github.io/Werehose-Dashbord/](https://theanvarow.github.io/Werehose-Dashbord/)**

---

## ✨ Основной Функционал (Key Features)

### 👥 1. Карточки и Рейтинг Начальников Смен
- **Профили Руководителей:** Детальная информация по каждому начальнику смены (*Каримов Ильхом, Низомиддин, Довуд, Рамиль*).
- **Сводные Метрики:** Количество сотрудников в смене, фактический объем операций (OPS), динамика выполнения плана, процент использования системных ботов.
- **Индивидуальный статус:** Текущий фокус месяца, задачи и итоговый балл (Score).

### 📈 2. Интерактивная Аналитика и Графики (Chart.js)
- **Общая Динамика Смен:** Сравнительный анализ производительности и объемов обработки грузов по всем 4 сменам.
- **Статистика Использования Бота:** Процентная динамика взаимодействия персонала со складскими ботами по дням.
- **Категорийное Размещение:** Доля безошибочного и ошибочного распределения товаров по зонам хранения.
- **Анализ Ошибок по Месяцам:** Сопоставление инцидентов пересчета и размещения товаров.

### 📅 3. Месячный График и Календарь Смен
- Наглядный календарь рабочих смен, ротации бригад (дневные/ночные смены, выходные дни).
- Справочник состава бригад и зон ответственности.

### ⚡ 4. Real-Time Синхронизация с Google Таблицами
- Интеграция через Google Sheets API / CSV.
- Любое изменение, внесенное оператором в таблицу, мгновенно отображается на дашборде без перезапуска системы.

### 🎨 5. Премиальный Dark UI & Glassmorphism Дизайн
- Тёмная неоновая палитра, оптимизированная для круглосуточной работы на терминалах и больших экранах.
- Полная адаптивность: мониторы, ноутбуки, планшеты и смартфоны.

---

## 🖼️ Скриншоты Интерфейса (Screenshots)

<div align="center">

### 🖥️ Главная Панель Мониторинга (Dashboard Overview)
![Главная Панель](image/dashboard_preview.png)

### 📊 Полноразмерный Обзор Системы (Full Dashboard View)
![Полный Дашборд](image/dashboard_full.png)

</div>

---

## 🏗️ Технологический Стек (Tech Stack)

| Слой | Технологии | Описание |
| :--- | :--- | :--- |
| **Frontend** | `HTML5`, `CSS3 (Vanilla)`, `JavaScript (ES6+)` | Быстрый, легкий интерфейс без лишних фреймворков |
| **Визуализация** | `Chart.js v4` | Интерактивные графики, круговые диаграммы и тренды |
| **Хранилище Данных** | `Google Sheets API / Cloud CSV` | Простое, надежное облачное управление данными |
| **Хостинг** | `GitHub Pages` | Быстрый и отказоустойчивый глобальный деплой |

---

## 📑 Структура Данных Google Таблицы (Data Schema)

Данные в таблице разделяются на 2 типа строк:
1. `shift` — индивидуальные KPI показатели для 4 начальников смен.
2. `table` — общая аналитика и расширенная таблица смен.

### 📋 Описание Столбцов:

| Название Столбца | Тип | Описание |
| :--- | :--- | :--- |
| `entry_type` | `String` | Тип строки: `shift` или `table` |
| `month` | `String` | Отчетный месяц (`yanvar`, `fevral`, `mart`, `aprel`...) |
| `shift_key` | `String` | Ключ смены: `shift1`, `shift2`, `shift3`, `shift4` |
| `name` / `leader_name` | `String` | Ф.И.О. начальника смены |
| `employees` | `Number` | Количество сотрудников в смене |
| `ops` / `fact_ops` | `Number` | Общее количество операций (OPS) |
| `errors` / `fact_errors` | `Number` | Количество зафиксированных ошибок |
| `recountManager` | `String` | Ф.И.О. менеджера пересчета |
| `recountOps` | `Number` | OPS по пересчету |
| `placementManager1/2` | `String` | Ф.И.О. менеджеров размещения |
| `placementOps1/2` | `Number` | OPS по размещению |
| `actClosedZero` | `Number` | Количество актов, закрытых с нулевым результатом |
| `recountErrors` | `Number` | Количество ошибок пересчета |
| `placementErrors` | `Number` | Количество ошибок размещения |
| `botUsageStats` | `Percentage` | Процент использования бота сотрудниками (%) |
| `wrongCategoryPlacement` | `Percentage` | Доля неправильно размещенных категорий (%) |

---

## 🚀 Быстрый Старт и Локальный Запуск (Quick Start)

### 1. Клонирование репозитория:
```bash
git clone https://github.com/theanvarow/Werehose-Dashbord.git
cd Werehose-Dashbord
```

### 2. Запуск в браузере:
Просто откройте файл `index.html` в любом современном браузере или запустите локальный сервер:

```bash
# Через Python:
python3 -m http.server 8080

# Или через Node.js (npx serve):
npx serve .
```

Перейдите по адресу: **`http://localhost:8080`**

---

## 📁 Структура Репозитория (File Structure)

```plaintext
Werehose-Dashbord/
├── index.html                  # Главная страница дашборда и весь функционал UI
├── google_sheets_template.csv  # Шаблон структуры Google Таблицы
├── GOOGLE_SHEETS_USTUNLAR.txt  # Документация по колонкам и правилам заполнения
├── image/                      # Изображения, аватары смен, логотип и скриншоты
│   ├── big-logo.webp           # Официальный логотип Uzum Market
│   ├── dashboard_preview.png   # Превью главного экрана дашборда
│   ├── dashboard_full.png      # Полный скриншот системы
│   ├── Ilhom.jpg               # Начальник смены 1
│   ├── Nizim.jpg               # Начальник смены 2
│   ├── dovud.png               # Начальник смены 3
│   └── ramil.jpg               # Начальник смены 4
└── README.md                   # Документация проекта на русском языке
```

---

## 👨‍💻 Автор и Контакты (Author)

- **Автор:** Сирожиддин Анваров ([@theanvarow](https://github.com/theanvarow))
- **Проект:** Uzum Market Logistics & Warehouse Operations Management
- **Репозиторий:** [https://github.com/theanvarow/Werehose-Dashbord](https://github.com/theanvarow/Werehose-Dashbord)
- **Live Сайт:** [https://theanvarow.github.io/Werehose-Dashbord/](https://theanvarow.github.io/Werehose-Dashbord/)

---

<div align="center">
⭐ Если вам понравился этот проект, поддержите его, поставив <b>Star</b> на GitHub! ⭐
</div>
