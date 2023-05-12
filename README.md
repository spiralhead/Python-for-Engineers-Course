# Python-for-Engineers-Course
Курс для использования python в инженерных расчетах.
## Установка Python и дополнительных пакетов
Рекомендую установку  miniconda https://docs.conda.io/en/latest/miniconda.html.
Далее находим приложение в меню Пуск "Anaconda Prompt(miniconda3)", и открываем его.
У нас загружается среда "base", для того, чтобы установить все необходимые библиотеки используйте следующую последовательность команд:
```
conda create -n eng_test python=3.10 -y
conda activate eng_base
conda install -y pandas numpy sympy matplotlib jupyter
```
## Запуск курса:
Скопируйте себе папки материалы курса, в родительской папке откройте anaconda prompt (Можно открыть через меню пуск и перейти в папку с курсом с помощью команд pushd или сd).
Пропишите следующую последовательность команд:
```
conda activate eng_base
jupyter notebook
```
В браузере по умолчанию откроется графический интерфейс, который даст вам возможность запустить файлы ipynb, начинать лучше с Part_1_Basics/introduction_to_ipython.ipynb
