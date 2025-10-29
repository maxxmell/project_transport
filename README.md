# Анализ Московского метрополитена и МЦД  
**Пассажиропоток • Тарифы • Инфраструктура • МЦД**

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-green)](https://pandas.pydata.org/)
[![Folium](https://img.shields.io/badge/Folium-Interactive%20Maps-orange)](https://python-visualization.github.io/folium/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)](https://creativecommons.org/licenses/by/4.0/)

---

## Описание проекта

**Аналитический проект** на основе открытых данных [data.mos.ru](https://data.mos.ru)  
8 вкладок в Jupyter Notebook: от пассажиропотока до интеграции МЦД с метро.

> **Цель:** выявить ключевые тренды, эффективность линий, тарифы, географию  
> **Результат:** готовое портфолио аналитика данных

---

## Структура проекта
```bash
project_transport/
├── notebooks/
│   └── metro_analysis.ipynb
├── data/
│   ├── data-624.csv
│   ├── data-62523.csv
│   ├── data-62743.csv
│   ├── data-62888.csv
│   └── sub/
│       ├── data-658.csv
│       ├── data-62207.csv
│       ├── data-62741.csv
│       └── data-62745.csv
├── export/
│   └── report_clean.html
├── requirements.txt
└── README.md
```
---

## Основные разделы анализа

| Раздел | Описание |
|--------|-----------|
| **Пассажиропоток** | ТОП станций, динамика по годам |
| **География** | Интерактивные карты станций |
| **Интеграция МЦД** | Пересадки между системами |
| **Тарифы** | Сравнение сценариев использования |
| **Эффективность** | Загрузка линий метро |
| **Операционная эффективность** | Точность расписания |

## Отчеты

| Отчет | Формат | Назначение |
|-------|--------|------------|
| **Полный отчет HTML** | `.html` | Готовый отчет для просмотра |
| **Исходный анализ** | `.ipynb` | Полный код анализа |

---

## Источники данных

| ID | Название | Ссылка |
|----|----------|--------|
| data-624 | Станции метро | [data.mos.ru/opendata/624](https://data.mos.ru/opendata/624) |
| data-62743 | Пассажиропоток по станциям | [data.mos.ru/opendata/62743](https://data.mos.ru/opendata/62743) |
| data-62523 | Годовой пассажиропоток | [data.mos.ru/opendata/62523](https://data.mos.ru/opendata/62523) |
| data-658 | Тарифы | [data.mos.ru/opendata/658](https://data.mos.ru/opendata/658) |
| data-62207 | Входы/выходы МЦД | [data.mos.ru/opendata/62207](https://data.mos.ru/opendata/62207) |
| data-62888 | Станции МЦД | [data.mos.ru/opendata/62888](https://data.mos.ru/opendata/62888) |
| data-62741 | Характеристики линий метрополитена | [data.mos.ru/opendata/62741](https://data.mos.ru/opendata/62741) |
| data-62745 | Точность выполнения расписания | [data.mos.ru/opendata/62745](https://data.mos.ru/opendata/62745) |

**Лицензия:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ru)

---

## Как запустить

```bash
# 1. Клонировать
git clone https://github.com/maxxmell/project_transport.git
cd project_transport

# 2. Установить зависимости
pip install -r requirements.txt

# 3. Запустить
jupyter notebook notebooks/metro_analysis.ipynb
