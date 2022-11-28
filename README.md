# django-single-page
This is a very simple implementation of single-page functionality with django and javascript's fetch API.

----------- 

https://www.pythonstacks.com/blog/post/create-single-page-application/

https://pypi.org/project/django-spa/

https://github.com/tiangolo/fastapi


-----------------------
https://docs.conda.io/projects/conda/en/latest/_downloads/843d9e0198f2a193a3484886fa28163c/conda-cheatsheet.pdf
http://pastie.org/p/3viYFB7ldLPRLsZNQtBVIR

## Основной сайт anaconda
https://www.anaconda.com/


## Как добавить канал conda-forge
Кнопка Add
Добавить conda-forge
и нажать update channels


## Основной сайт miniconda
https://docs.conda.io/en/latest/miniconda.html


## Работа в терминале
## Подключаем канал conda-forge:
conda config --add channels conda-forge

## Создание нового виртуального окружения
conda create --name data_one python=3.10

## Активация виртуального окружения data_one
$ conda activate data_one

## Установка новых пакетов в окружение data_one
(data_one) $ conda install numpy pandas matplotlib jupyter --yes

## Запуск ноутбука
(data_one) $ python -m notebook

## Деактивация виртуального окружения data_one
(data_one) $ conda deactivate

## Форматирование
https://github.com/dnanhkhoa/nb_black
conda install nb_black  # ставим в текущее окружение
conda install -n data_one nb_black  # ставим в окружение data_one

## Подключаем в Jupyter Notebook:

%load_ext nb_black

## Подключаем в Jupyter Lab:

%load_ext lab_black

## Как добавить слайды
(data_one) $ conda install rise
