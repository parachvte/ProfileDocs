Поріг звичайної/максимальної швидкості обдуву
====

### **Опис**

Поріг звичайної/максимальної швидкості обдуву дозволяє налаштувати швидкість обдуву моделі в залежності від часу друку шару.

* Якщо час друку шару дорівнює чи більше ніж встановлене значення, тоді цей шар буде друкуватись зі Звичайною швидкістю обдуву.
* Якщо час друку шару менший ніж встановлене значення, тоді швидкість обдуву обчислюватиметься за наступною формулою:  
    Швидкість обдуву шару = Максимальна швидкість обдуву - (Максимальна швидкість обдуву - Звичайна швидкість обдуву)/(Поріг звичайної/максимальної швидкості обдуву - Мінімальна швидкість обдуву) × (Час друку шару - Мінімальний час друку шару)
* Якщо шар друкується за Мінімальний час друку, тоді цей шар буде друкуватись з Максимальною швидкістю обдуву.

![Which fan speed is used where](../images/cool_fan_speed.svg)

### **Використання**

Якщо час друку шару короткий, шар може охолоджуватись не відповідно. Ось чому нам потрібно підвищити швидкість обдуву для того, що бути впевненим в тому, що він вчасно затвердіє.
