# "Наниты и все с ними связанное"

Для чего нужны наниты? Для того, чтоб стать сильным, ловким, быстрым или каким вам там еще захочется/повезёт. "Повезёт", так как в этом деле довольно многое зависит от удачи.

### 1. Подготовка

Заранее требуется сделать зарядник, с помощью которого мы будем заряжать нанитов и планшет (о нём позже).

![Зарядное устройство](./images/charger.png) ![Крафт зарядного устройства](./images/charger_craft.jpg)

После этого нам понадобятся сами наниты:

![Нанороботы](./images/creating_nanites.jpg)

Сделав нанороботов можем смело их есть!

А после трапезы самое время ознакомиться с тем, что нам поможет узнать, что же за дрянь только что попала в наш организм.

Заряд нанитов указан рядом с хотбаром.

Делаем себе планшет. Создаётся он в сборщике:

![Сборщик](./images/assembler.png) ![Крафт сборщика](./images/assembler_craft.jpg)

Для сборки планшета нам потребуется заранее скрафтить корпус планшета и остальные его части:

![Планшет](./images/creating_tablet.jpg)

Из обязательного (кроме корпуса) тут:

1. Клавиатура

2. Плата беспроводной сети

3. Интернет карта (ну а как иначе проги скачать то)

4. ОЗУ

5. Жёсткий диск

6. Процессор со встроенной видеокартой

7. EEPROM (Lua)

Дисковод ставится по желанию, он позволяет устанавливать ОС прямо из под планшета, без использования дополнительного компа.

### 2. Установка

И так, вот наш свежеиспеченный планшет готов, вставляем дискету по shift+пкм \(при наличии дисковода\) и устанавливаем OpenOS, а вмете с ней и пару программ.

![Установка](./images/installation.jpg)

Команды для ввода:
```
install
pastebin get 0YL9pTk8 nano
pastebin get 5DwVXSpc nscan
pastebin get i3KdR3Aa nconf 
```

### 3. ПО и как с ним работать

#### 3.1 Nscan. Сканирование нанитов

Запускаем nscan, чтобы наконец-то узнать чтоже такое у нас теперь внутри.

![Nscan](./images/nscan.jpg)

По завершении программа выдаёт что интересного нашлось, в моём случае из полезного, это поглощение, магнит, подводное дыхание со скоростью копания и скорость бега

!!! warning
    **ОСТОРОЖНО!**

    Могут попасться эффекты как положительные так и негативные, а такие как harm и wither могут спокойно убить, так что советую выложить всё, помимо планешета, и заныкаться, чтоб при смерти он далеко не улетел.

Вот мы узнали, что у нас есть. Допустим, хотим мы себе включить поглощение с магнитом.

#### 3.2 Nano. Управление нанитами

Для управления нанитами запускаем программу nano. Про нее распишу поподробнее, ибо функционала немало.

![Nano](./images/nano.jpg)

1. Узнать оставшийся заряд

2. Узнать активные эффекты

3. Проверить определённый канал на предмет работы

4. Задать канал и включить его

5. Узнать максимальное количество каналов

6. Узнать количество безопасных каналов

7. Узнать максимальное количество одновременно включенных каналов (если больше 2-х включить сразу будет больно бить, больше 3-х мгновенная смерть.

8. Сохранить ту конфигурацию, что есть сейчас. Для сохранения нужно, чтобы в инвентаре лежали наниты, на которые эта конфигурация и запишется. Таким образом, можно, например, копировать и продавать наниты с удачной конфигурацией.

9. Узнать показатель здоровья

10. Узнать показатель голода

11. Узнать возраст своего персонажа

12. Узнать имя

13. Узнать количество опыта

14. Выход из программы

Самое часто используемое - это 4, то есть управление, включение и выключение определенных каналов.

И так, хотим мы значит поглощение и магнит, заходим в программу и выбираем 4 пункт, затем номер канала (в моем случае 2) и выбираем "включить", тобишь 1. Нажимаем и проверяем.

![Включение и проверка](./images/turn_on_and_test_1.jpg)

И вот у нас уже есть поглощение.

Проделываем то же самое с магнитом, но подставляем уже его номер канала.

![](./images/turn_on_and_test_2.jpg)

С виду ничего не произошло, но предметы на расстоянии примерно 2-х блоков стали притягиваться к персонажу.

Продолжать не будем, иначе получения урона не избежать.

Ну и в основном всё. Если эффекты не понравились, делаем новых нанитов, едим и смотрим, что выпало на этот раз.

#### 3.4 Nconf. Аналог Nano

Программа nconf это аналог программы nano

![Nconf](./images/nconf.jpg)

Можно сказать тоже самое, что и nano, но урезанное. Основной функционал тот же.

Также хочу обратить ваше внимание на то, что чем больше каналов у вас одновременно включено, тем быстрее будет расход энергии нанитами! Тем чаще вам придется бегать к зарядному устройству для подзарядки. А если ваши наниты полностью разрядятся, и при этом будут включены какие-либо каналы, то вам будет наноситься ощутимый урон.

На этом все, спасибо за внимание =\)
