# Boosters. Raiffeisen Data Cup

Этот репозиторий – мое решение [конкурса](https://boosters.pro/champ_11) на площадке Boosters.Pro от Raiffeisen банка.

В директории **dump_scripts** можно найти скрипты, которые я использовал для обкачивания сайтов Raiffeisen банка и его партнеров
с целью заполучить истинные координаты atm-терминалов.

В **jupyter-ноутбуках** с префиксом:
- '**01**' можно найти код, отвечающий за предобработку данных;
- '**02**' – формирование итогового датасета;
- '**03**' – финальная модель.

Большое внимание было уделено предобработки названия городов и адресов. Для этого был написан простенький спелчекер, а также использовалась информация об индексах городов, см. *01-06_preprocess_cities_final.ipynb*.

В директории **attempts** находятся некоторые мои неудачные, к сожалению, попытки.
