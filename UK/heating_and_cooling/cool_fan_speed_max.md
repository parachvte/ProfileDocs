Максимальна швидкість обдуву
====

### **Опис**

Швидкість з якою вентилятори в головці будуть обертатись, коли виконується друк за мінімально зазначений час (Мін. час шару).

![Which fan speed is used where](../images/cool_fan_speed.svg)

Luban обчислює час друку кожного шару для того, щоб визначити швидкість його обдуву. Якщо час друку більший ніж зазначено у «Мін. час шару», але менший за Поріг звичайної/максимальної швидкості обдуву, тоді швидкість обдуву для такого шару обчислюватиметься наступним чином:

Швидкість обдуву шару = Максимальна швидкість обдуву - (Максимальна швидкість обдуву - Поріг звичайної/максимальної швидкості обдуву)/(Поріг звичайної/максимальної швидкості обдуву - Мінімальний час друку шару) × (Час друку шару - Мінімальний час друку шару)

### **Використання**

Шари, чий час друку менший, можуть охолоджуватись швидше та твердіти перед тим як наступний шар ляже зверху, тож використання параметра максимальної швидкості обдуву дозволяє запобігати просідань.
