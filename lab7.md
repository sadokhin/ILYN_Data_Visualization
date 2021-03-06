# Лабораторная работа №7 "Python"

[Обратно к выбору лабораторной :back:](https://github.com/sadokhin/A1_Data_Visualization/blob/962705b6445b2bc117fa2d7bd38c10e4f1718aba/README.md)

> Датасет: [filmtv_movies](https://drive.google.com/file/d/1iB5_UY4TPC2d8TNparIvbfJzrGpdSj-G/view?usp=sharing)

__Записи уроков__

> [Лекция 1 "Практика Python в Google Colab"](https://youtu.be/IAP6vEc-ang)
>
> [Лекция 2 "Библиотеки matplotlib + seaborn"](https://youtu.be/hI0I51yOLF8)
> 
> [Лекция 3 "Библиотека plotly"](https://youtu.be/EEtpfh4QqLI)
> 
> [Разбор лабораторной №7](https://youtu.be/ozYDh5dFpeA)

__Тетрадки Google Colab__

> [week7_lecture1.ipynb](https://colab.research.google.com/drive/1cSWAr_dU6617GgxqXFI-R0WEi1YprJYt?usp=sharing)
> 
> [week7_lecture2.ipynb](https://colab.research.google.com/drive/1gon_cDA99pj6AhlVbji-hAAI_ydzjgyt?usp=sharing)
> 
> [week7_lecture3.ipynb](https://colab.research.google.com/drive/1jx9MqbV0zXm2XzvigRSeult-KLsmv0tD?usp=sharing)
> 
> [Ответы на воросы к лаб7](https://colab.research.google.com/drive/1KOTe7S13evywtzYlCAbYMG_qGe8Js-ls?usp=sharing)

В данной лабораторной работе вам необходимо построить визуализации с помощью Python в Google Colab и ответить на вопросы в гугл-форме.

## Описание полей датасета

Данные о фильмах с сайта filmtv.it - самого популярного в Италии:

| Название столбца | Значение |
| -----------------|:--------:|
| filmtv_id | Идентификатор фильма |
| title |	Название |
| year |	Год премьеры |
| genre |	Жанр |
| duration | Продолжительность (мин) |
| country | Страна |
| directors |	Режиссеры |
| actors |	Актеры |
| avg_vote | Средний рейтинг |
| critics_vote | Рейтинг критиков |
| public_vote |	Рейтинг пользователей |
| total_votes |	Кол-во голосов |
| description |	Описание фильма |
| notes | Заметки к фильму |
| humor | Оценка юмора |
| rhythm |	Ритм, такт |
| efforts |	Старания |
| tension |	Напряжение |
| erotism | Эротизм |

## Задания

Вам необходимо открыть Google Colab, создать новый документ. Построить визуализации. Ответить на вопросы в гугл-форме, где нужно будет прикрепить ссылку на документ Google Colab. 

__1. Визуализации__

> Каждая визуализация в отдельной ячейке.
> Перед ячейкой с кодом диаграммы, должна быть ячейка с названием диаграммы жирным шрифтом.

- __Количество фильмов по жанрам__ : функция `barplot()` у библиотеки seaborn.
- __Распределение среднего рейтинга по жанрам__ : функция `boxplot()` у библиотеки seaborn.
- __Распределение фильмов по продолжительности в разрезе жанра__ : функция `histplot()` у библиотеки seaborn.
- __Средний ретинг и количество голосов у ТОП-20 фильмов__ : `Scatter()` у библиотеки plotly.

__2. Ответы на вопросы__
> [Ссылка на гугл форму](https://forms.gle/wK5fVu4AKCYmyWpR6)

Заполните гугл форму. Тут уж думаю, у вас не будет выбора, кроме как находить ответы с помощью Python 😑. Последние два вопроса - для обратной связи. Буду рад, если заполните, но они не обязательны.

__Желаю удачи в решении задач!__
