	Это моя первая нейронная сеть. Она распознаёт цифровое представление цифры 5.
![Подаваемые цифры на вход](https://github.com/Luzinsan/my_first_neuroset/blob/ff1c69588ce182c493bc6fb78bd63ab3e568bf09/digits.png)

	Для этого используется однослойный персептрон с порогом bias=9.
	К тому же проверяется, как нейронная сеть признает искажённое представление цифры 5.
![Искажённые варианты пятёрки](https://github.com/Luzinsan/my_first_neuroset/blob/ff1c69588ce182c493bc6fb78bd63ab3e568bf09/5digits.png)
    
    Вот и сам результат.
    
    [1, 1, 1, 2, 0, -4, 1, 1, 1, -4, 0, 1, 1, 1, 1]
    
    0 это 5?  False
    1 это 5?  False
    2 это 5?  False
    3 это 5?  False
    4 это 5?  False
    5 это 5?  True
    6 это 5?  False
    7 это 5?  False
    8 это 5?  False
    9 это 5?  False
    
    
    Узнал 5 - 0?  True
    Узнал 5 - 1?  True
    Узнал 5 - 2?  True
    Узнал 5 - 3?  True
    Узнал 5 - 4?  True
    Узнал 5 - 5?  True
    
    Process finished with exit code 0