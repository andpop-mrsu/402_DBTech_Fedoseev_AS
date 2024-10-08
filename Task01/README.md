# Проект "Сапер" (Minesweeper)

## Задача для первого блока
### Вариант 5
Написать программу для игры "Сапер" (minesweeper). Квадратное игровое поле разделено на смежные ячейки, некоторые из которых заминированы; количество заминированных ячеек известно. Цель игры - открытие всех ячеек, не содержащих мины.

Игрок открывает ячейки, стараясь не открыть ячейку с миной. Открыв ячейку с миной, он проигрывает. Если под открытой ячейкой мины нет, то в ней появляется число, показывающее, сколько ячеек, соседствующих с только что открытой, заминировано.Если под соседними ячейками тоже нет мин, то открывается не заминированная область до ячеек, в которых есть цифры. 

* * *

* Размерность поля и количество мин на поле вводится при запуске игры.
* Информация о датах и исходах всех партий, а также о всех ходах, сделанных во время игры, должна сохраняться в базе данных.
* Для каждой игры в базе должна храниться следующая информация:
    * Дата игры
    * Имя игрока
    * Размерность поля и количество мин на поле
    * Расстановка мин на поле
    * Исход игры 
    * Запись ходов в формате: 
      `номер хода | координаты точки | результат (мины нет/взорвался/выиграл)`
* В программе должны быть реализованы три режима:
    * Новая игра.
    * Вывод списка всех сохраненных в базе партий.
    * Повтор любой сохраненной партии (то есть повтор всех ходов из этой партии).


## Инструкция по запуску

1. **Настройка окружения**:
   - Убедитесь, что у вас установлены PHP и SQLite.
   - Для Windows: настройте переменные окружения для SQLite.
   - Для Unix-подобных систем: установите SQLite и сделайте скрипты исполняемыми.

2. **Запуск программы**:
   - Запустите скрипт для запуска игры (например, через командную строку или терминал).