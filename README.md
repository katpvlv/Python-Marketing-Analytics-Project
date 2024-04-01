# Проект «‎Маркетинговая аналитика: дашборд конверсий»‎
В ходе проекта были рассчитаны конверсии на сайте, выявлены платформы, которые приносят больше визитов и регистраций, проанализировано, как отрабатывают рекламные кампании. В итоге была подготовлена презентация с результатами исследования и даны рекомендации.


Проект выполнен в Jupiter Notebook с помощью GUI-интерфейса Anaconda. 

Проект написан на Python с использованием следующих библиотек:
   * Pandas
   * Numpy
   * Matplotlib
   * Matplotlib.pyplot
   * Seaborn
   * Requests
   * Os
   * Dotenv


Версии программ, использованных в проекте, находятся в файле [pyproject.toml](https://github.com/katpvlv/Python-Marketing-Analytics-Project/blob/main/pyproject.toml)


## Как воспроизвести проект:
1. Установить [Anaconda](https://www.anaconda.com/download)
2. Через интерфейс Anaconda установить в выбранную среду необходимые библиотеки из списка выше, выбрать ту же версию, что указана в файле [pyproject.toml](https://github.com/katpvlv/Python-Marketing-Analytics-Project/blob/main/pyproject.toml)
3. Через интерфейс Anaconda установить Jupier Notebook
4. Скачать проект
5. Открыть файл [charts_project.ipynb](https://github.com/katpvlv/Python-Marketing-Analytics-Project/blob/main/charts_project.ipynb) через Jupier Notebook в Anaconda
6. Запустить проект. Он сам создаст нужные папки и файлы.


Просто посмотреть код можно в файле [charts_project.ipynb](https://github.com/katpvlv/Python-Marketing-Analytics-Project/blob/main/charts_project.ipynb)


## Задачи:
1. Запросить данные по API и преобразовать их в датафреймы. Добавить переменные окружения
2. Сгруппировать данные визитов и данные регистраций по датам и платформам. Для каждого пользователя оставить только последний визит. Исключить визиты, в которых источник 'bot'
3. Объединить датайфреймы, рассчитать конверсии в итоговом датафрейме. Датафрейм [conversion.json](https://github.com/katpvlv/Python-Marketing-Analytics-Project/blob/main/conversion.json)
4. Объединить датафрейм конверсий с данными о рекламных кампаниях. Датафрейм [ads.json](https://github.com/katpvlv/Python-Marketing-Analytics-Project/blob/main/ads.json)
5. Полученные данные визуализировать с помощью графиков. [Charts](https://github.com/katpvlv/Python-Marketing-Analytics-Project/tree/main/charts)
6. Подготовить презентацию, сделать выводы и ответить на вопросы, поставленные аналитику. Презентация [presentation.pdf](https://github.com/katpvlv/Python-Marketing-Analytics-Project/blob/main/presentation.pdf)
