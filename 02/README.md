# Task from a mentor's seminar at HSE
[link to data](https://docs.google.com/spreadsheets/d/1VpS-RWsszdv6lRnI03ogl7zcm-UU7rKp/edit?usp=drive_link&ouid=109353123672021623729&rtpof=true&sd=true)

- `main.py` - после запуска формируются файлы: `forecast_value.json` - с точечным прогнозом, `forecast_class.json` - с классификацией
- `time_series_task02.ipynb` - иллюстрация и логика решения

Необходимо построить прогноз на период с 03.01.2022 по 31.03.2022. Целевые даты указаны на 2-м листе таблицы с данными (48 значений)

Оценка качества:
- Точечный прогноз - MAE
- Бинарная классификация -  F1
- Данные в списках располагаются в порядке возрастания даты. Для задачи классификации 'л' - 1, 'ш' - 0