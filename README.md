# Регулярные выражения 

## Шаг 1: Удаление пустых строк в документе.
1. В приложении Sublime Text выбрала синтаксис: регулярные варыжения.
2. Затем набором клавиш открыла панель Find->Replace
![](https://github.com/barchukstacy/hw9/blob/master/Step%201%20Before.png)
3. В поле Find What написала ^\n,поле Replace With оставила пустым и нажала Replace All.
Вот что вышло:
![](https://github.com/barchukstacy/hw9/blob/master/Step%201%20After.png)

## Шаг 2: Поиск всех князей и города, имя и название которых оканчивается на "слав".
1. Использовала регулярное выражение: [А-Я][а-яѵѣ]+(слав)[а-яѵѣ]+
Так же учла, что могут быть буквы, которые могут не входить в диапазон А-Я\а-я.
2. Всего найдено было 564 вхождений.
![](https://github.com/barchukstacy/hw9/blob/master/Step%202%20Results.png)

## Шаг 3: Поиск всех упоминаний Новгорода.
1.Использовала регулярное выражение: (Нов)[а-яѣѵ]+(город)[а-яѣѵ]+
Так же учла, что написание может быть разным и могут быть буквы, которые могут не входить в диапазон А-Я\а-я.
2. Всего найдено было 56 вхождений.
![](https://github.com/barchukstacy/hw9/blob/master/Step%203%20Results.png)
