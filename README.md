# Forest Fires in Bulgaria: Data Analysis 🌲🔥

An analytical and data-driven repository dedicated to examining historical trends, causes, geographic distribution, and environmental impacts of forest fires in Bulgaria. This project aims to process raw wildfire statistics to extract meaningful insights, support risk assessment, and provide visualizations that highlight the socio-economic and ecological toll of wildfires.

## 📌 Project Overview
Forest fires pose a critical threat to Bulgaria's rich biodiversity, causing vast economic losses, severe soil erosion, and substantial carbon dioxide ($CO_2$) emissions. This project parses official and open-source data (such as historical registries from the Executive Forest Agency - EFA, academic publications, or satellite data) to visualize and analyze the wildfire crisis.

Key areas of focus include:
* **Temporal Trends:** Seasonality patterns (identifying dangerous shifts into autumn/winter) and long-term cyclic peaks.
* **Geographic Hotspots:** Regional risk mapping, with specific deep dives into high-risk areas like Southwest Bulgaria (Sofia, Blagoevgrad, Kyustendil) and Southern regions (Stara Zagora, Rhodopes, Strandzha).
* **Anthropogenic vs. Natural Causes:** Investigating the impact of human negligence (agricultural burning, arson) vs. lightning strikes.
* **Impact Quantification:** Calculating affected forest types (broadleaved vs. coniferous) and tracking environmental degradation metrics.

## 🚀 Features
* **Data Cleaning & Preprocessing:** Scripts to clean messy historical fire logs.
* **Exploratory Data Analysis (EDA):** Jupyter Notebooks detailing correlations between fire frequency, weather indices (temperature, humidity, vapor pressure deficit), and seasonal trends.
* **Data Visualization:** Clear, interpretable charts detailing burned areas (in hectares) by region and vegetation type.
* **Risk Assessment Models:** Implementation of regional risk assessment metrics.

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`, `plotly`
* **Geospatial Analysis (Optional):** `geopandas` or `folium` (if mapping tools are included)
* **Environment:** Jupyter Notebooks

## 📂 Project Structure
```text
├── data/                  # Raw and processed datasets (CSV, Excel, etc.)
├── notebooks/             # Jupyter Notebooks containing the core analysis & EDA
├── src/                   # Reusable Python helper scripts and source code
├── plots/                 # Exported charts, maps, and visualizations
├── requirements.txt       # List of Python dependencies
└── README.md              # Project documentation

---------------------------------------------------------------------------------------------------------------------------------------------

# Българска версия (Bulgarian Version)

```markdown
# Горски пожари в България: Анализ на данни 🌲🔥

Това хранилище съдържа аналитичен проект, посветен на изследването на историческите тенденции, причините, географското разпределение и екологичните последици от горските пожари в България. Проектът цели да обработи сурови статистически данни за горските пожари, за да извлече ценна информация, да подпомогне оценката на риска и да предостави визуализации, които подчертават социално-икономическите и екологичните щети.

## 📌 Общ преглед на проекта
Горските пожари представляват сериозна заплаха за богатото биоразнообразие на България, като причиняват огромни икономически загуби, тежка ерозия на почвата и значителни емисии на въглероден диоксид ($CO_2$). Този проект анализира официални данни и данни с отворен код (като исторически регистри на Изпълнителната агенция по горите – ИАГ, академични публикации или сателитни данни), за да визуализира и анализира кризата с пожарите.

Основни фокусни точки:
* **Времеви тенденции:** Сезонни модели (идентифициране на опасни промени с поява на пожари през есента/зимата) и дългосрочни циклични пикове.
* **Географски горещи точки:** Регионално картиране на риска с подробен анализ на високорискови райони като Югозападна България (София, Благоевград, Кюстендил) и Южна България (Стара Загора, Родопите, Странджа, Сакар).
* **Антропогенни срещу естествени причини:** Изследване на влиянието на човешката небрежност (палене на стърнища, пасища, умишлени палежи) спрямо естествени причини (мълнии).
* **Количествена оценка на щетите:** Изчисляване на засегнатите видове гори (широколистни спрямо иглолистни) и проследяване на показателите за влошаване на околната среда.

## 🚀 Функционалности
* **Почистване и предварителна обработка на данни:** Скриптове за обработка на сурови исторически дневници на пожари.
* **Употребителен анализ на данни (EDA):** Jupyter Notebooks, показващи корелациите между честотата на пожарите, метеорологичните показатели (температура, влажност, дефицит на налягането на водната пара) и сезонните тенденции.
* **Визуализация на данни:** Ясни графики, описващи изгорелите площи (в хектари) по региони и видове растителност.
* **Модели за оценка на риска:** Внедряване на метрики за оценка на регионалния риск.

## 🛠️ Използвани технологии и библиотеки
* **Език за програмиране:** Python 3.x
* **Обработка на данни:** `pandas`, `numpy`
* **Визуализация на данни:** `matplotlib`, `seaborn`, `plotly`
* **Геопространствен анализ (по избор):** `geopandas` или `folium` (ако са включени инструменти за картографиране)
* **Работна среда:** Jupyter Notebooks

## 📂 Структура на проекта
```text
├── data/                  # Сурови и обработени масиви от данни (CSV, Excel и др.)
├── notebooks/             # Jupyter Notebooks с основния анализ и EDA
├── src/                   # Помощни Python скриптове и изходен код за многократна употреба
├── plots/                 # Експортирани графики, карти и визуализации
├── requirements.txt       # Списък с Python зависимости
└── README.md              # Документация на проекта
