Спіральний зовнішній контур
====

### **Опис**

Під час створення спірального зовнішнього контуру модель не матиме жодного заповнення чи верхів. Вона отримає лише одну стінку та дно. Важливо, що якщо ввімкнути [Згладжування спіральних контурів](smooth_spiralized_contours.md), сопло поступово підійматиметься під час друку шару. Таким чином створюється спіраль по контуру моделі. Не буде значного підйому робочої головки від одного шару до іншого, оскільки сопло поступово рухається вгору до наступного шару.

Під час друку шар за шаром сопло зазвичай має рухатися від одного шару до наступного. Цей рух змушує сопло залишатися майже нерухомим у напрямку XY протягом частки секунди, що залишає шов на поверхні, який називається Z-швом. Спіралізоване моделювання може запобігти цьому.

### **Використання**

Режим спіралізації поширений у багатьох слайсерах. Іноді його також називають «режим вази», оскільки це хороший спосіб друкувати вази. Спіральний зовнішній контур має такі ефекти:

* Друк надзвичайно швидкий.
* Поверхня стає дуже гладкою. Більше немає [Z-шва](../troubleshooting/seam.md), де сопло переходить до друку наступного шару, якщо ввімкнено [Згладжування спіральних контурів](smooth_spiralized_contours.md).
* Модель буде не дуже міцною. Якщо модель занадто велика, вона має тенденцію розколюватися через [деформацію](../troubleshooting/warping.md).
* Важко зробити модель водонепроникною, якщо вона велика.

Спіралізація погано працюватиме з деталями з великою кількістю горизонтальних поверхонь. Вона взагалі не справляється з нависаннями і не друкує верхні поверхні, тому в цьому випаду немає на що спиратися під час друку. Це також погано працює, якщо шар складається з кількох частин.