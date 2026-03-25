# CyberShelf 2026 Public Solution

## Ссылки

- **Kaggle Notebook:** [Public Solution Data Fusion](https://www.kaggle.com/code/dambek/public-solution-data-fusion)
- **Web App:** [CyberShelf Analytics Site](https://data-fusion-web-app.vercel.app/)

## Кратко про решение

Это публичное решение для задачи **Data Fusion Contest 2026 / CyberShelf**, оформленное как полный pipeline

Внутри проекта есть:

- **compact dataset builder**
  Сырые parquet-файлы сначала сжимаются в удобный рабочий датасет через screening дополнительных признаков

- **target-wise ensemble**
  Для каждого из 41 target обучается отдельный пайплайн с ансамблем моделей:
  - XGBoost на base features
  - CatBoost на base features
  - XGBoost на aux features
  - OOF blending
  - rank blending

- **EDA и аналитический слой**
  После обучения строятся:
  - PCA
  - кластеры
  - target profiles
  - feature importance
  - drift / missing analysis
  - экспорт таблиц и графиков

- **сайт с визуализацией**
  Отдельный web app показывает структуру датасета и результаты аналитики в удобном интерактивном виде

## Зачем это сделано

Мне хотелось сделать **top public solution** не только сильным по метрике, но и понятным по структуре.

То есть это решение закрывает весь путь:

**raw data -> compact dataset -> model ensemble -> analytics -> web presentation**

Такой формат полезен сразу в нескольких смыслах:

- удобно воспроизводить решение
- удобно улучшать модель
- удобно анализировать данные
- удобно показывать проект как законченный ML pipeline

## Документация

Полное техническое описание архитектуры, этапов обучения, EDA и экспорта находится в файле:

[solution.md](./solution.md)
