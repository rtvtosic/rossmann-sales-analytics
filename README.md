# Rossmann Sales Analytics

Аналитическая система для исследования и визуализации данных о продажах в розничной сети Rossmann.

## 📊 Описание проекта

Проект включает:
- **Исследовательский анализ данных (EDA)**: выявление паттернов продаж, влияние промоакций, сезонность
- **Интерактивный дашборд**: визуализация ключевых метрик для принятия управленческих решений
- **Датасет**: [Rossmann Store Sales](https://www.kaggle.com/c/rossmann-store-sales/) (1,115 магазинов, ~1 млн записей)

## Структура проекта
```
rossmann-sales-analytics/
│
├── README.md                          # Описание проекта
├── requirements.txt                   # Зависимости
├── .gitignore                         # Игнорируемые файлы
│
├── data/                              # Данные
│   ├── train.csv
│   ├── test.csv
│   └── store.csv
│
├── notebooks/
│   ├── eda_analysis.ipynb             # Весь EDA в одном ноутбуке
│   └── hypothesis_testing.ipynb       # Проверка гипотез (опционально)
│
├── dashboard/
│   └── app.py                         # Streamlit дашборд
│
└── course_work/
    ├── course_work.docx               # Курсовая работа
    └── presentation.pptx              # Презентация
```