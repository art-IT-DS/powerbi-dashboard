# Дашборд Olist в Power BI

## Описание
Интерактивный дашборд для анализа продаж бразильского маркетплейса Olist (данные за 2016–2018 гг.).

## Что внутри
- **Модель данных:** Схема "звезда" (таблица фактов `order_items`, измерения `customers`, `orders`, `products`).
- **DAX-меры:** Total Revenue (выручка), Orders Count (заказы), Avg Order Value (средний чек).
- **Визуализации:** 
  - Динамика выручки по месяцам.
  - Карточки с ключевыми метриками (Total Revenue, Orders Count, Avg Order Value).
  - Топ категорий товаров по выручке.
  - Топ штатов по выручке.
  - Интерактивный фильтр по годам (Slicer).

## Инсайты
1. Пик продаж пришелся на ноябрь 2017 года (сезон распродаж).
2. Основная доля выручки сосредоточена в штате Сан-Паулу (SP).
3. Самые прибыльные категории: товары для красоты и здоровья (`beleza_saude`), а также часы и подарки (`relogios_presentes`).

## Файлы
- `olist_dashboard.pbix` — исходный файл Power BI.
- `dashboard_overview.png` — скриншот дашборда.

## Данные
Датасет: [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) (Kaggle).
