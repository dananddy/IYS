# IYS KPI
## Репозитерій з предмета ІУС                                                                     #### Andriychuk Bohdan, IS-83




Лабораторна №1

1. Модуль Introduction to Azure Virtual Machines
Андрійчук Богдан
ІС – 83

I МодульIntroduction to Azure Virtual Machines
![image](https://user-images.githubusercontent.com/56149077/137602694-92fd369e-bce5-4f18-884a-c7fd6314b27d.png)


1. Виконаємо налаштування віртуальної машини з нашими параметрами


2. Розгортання пройшло без проблем









 II МодульCreate a Linux virtual machine in Azure
1. Створення ключ пари SSH на віртулаьній машині Linux за допомогою CloudShell.
Пароль фраза для даної пари є andriychuk




2. Перегляд публічного ключа в файлі bohdan.pub


Скопіюємо ключ:
AAAAB3NzaC1yc2EAAAADAQABAAACAQDIblql5tVfvbOQKRkB9BBV+e+ILa/mD9TDglCkDE0hME4a5FV5p2js548m36v/AG95uKG7k61rc2/0zGQ09UGuDrGa2uEG29xgSW1BcTbsOXTT1lOfw28dHpYm7K6jRSksR3HS5Xihs7+6Ufl+j0wAAgUJa7PXzVOwk32DTu3kdpNhxBDwa3VrzOYmOvU71dTcF8QfcbyFHbkrkw+lPxEAMuWioQ4toUUJG1z1MoqMGYZ1f/EXictIkMGnPw5bAg1HbnFvcgtshXDTgzqJP0Vsazq/s2xCgJNeS90oorwKAgcTr5eiyeJRLIzs6Uw2YCj9iZj2fWqtZhiVGtOBPz3JBV9NARmIO6Lo3cF3OkybeevKkJOGD4GqqeJ1mKqiDyTbgeWCnSIy/4ni7C+VHOFk8adp4NeY2QA8QRhqrCoPCnqle7BDXzomLV/6F8lYu7sG0SwhaEyGK5ct1usktRr2h/zL854+1HbVOpB617MSiB9T89IThPhHZy3jjOiYwfqG8GDOYSl3IzgI2nvbqYLR6TZFGhHz0n3jGeErymvLSrtrHfNhRxbJABToWBIR6o4s79al9wh53yrVu95Hx98Xb+IKQzdd/eLvoX/BvQP5uAXig9K+N8wZSRaPoZHitUnJ5/cUYPmAdsuxW5IGiq51vH406QWBQWP4+vB4uB6wnQ== azureuser@cc-94e7e80-5d4ffbdf88-7mw6g

4. Створення нової ВМ на базі Linux



5. Створивши ВМ, ми підєдналися до неї використовуючи Cloud Shell




6. Зробимо декілька елементарних запитів



7. ініціалізуємо диски з даними
	Спочатку виведем всі повідомлення ядра для SCSI
	Далі ініціалізуємо диск sdc за допомогою fdisk
	зайдемо в розділ 1 та створимо папку bohdan та встановимо диск



8. Оновимо локальний індекс пакетів та встановимо Apache. Відразу перевірим його стан


9. Налаштуємо мережу та оновимо групу безпеки в мережевому інтерфейсі

