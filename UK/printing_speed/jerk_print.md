Ривки друку
====

### **Опис**

Ривок визначає швидкість, з якою сопло може проходити повороти.

**Ривок у 3D-друці не те саме, що ривок у фізиці.** Термін «ривок» (jerk) був введений у Marlin. Він був представлений там як обхідний шлях для розвʼязання проблеми щодо ідеального слідування шляху друку лінії. Оскільки соплу заборонено відхилятися від траєкторії (теоретично), соплу потрібно сповільнюватися до 0 мм/с на кожному повороті. Це зіпсує ваш друк, оскільки уповільнення до 0 мм/с спричинить появу плям в кожному кутку. Щоб скоротити кут, робити криві не дозволяється, також не можна виходити за межі моделі. Натомість Marlin дозволяє миттєво змінювати вектор швидкості в кожному повороті. Величина цієї зміни вектора швидкості називається «ривком».

### **Вплив**

Завдяки високим значенням ривків сопло не сповільнюється при наближенні до повороту, що призводить до більш постійної швидкості, але також до більших вібрацій.

Збільшення ривка матиме дві позитивні наслідки для друку:

* Час друку скоротиться, тому що сопло менше гальмує в кутах.
* Оскільки сопло не сповільнюється до швидкості равлика, ви отримаєте менше плям у кутах. Сопло рухається з більш постійною швидкістю, тому воно не затримується в кутку, поки матеріал продовжує витікати з його отвору.

Збільшення ривка також має два негативних наслідки:

* Принтер, як правило, вібрує більше у кожному куті моделі, оскільки робоча головка має вказівку миттєво змінювати напрямки з певним прискоренням. Ці вібрації, як правило, створюють хвилі на вашій деталі, що призводить до появи хвилястості та зниження точності розмірів.
* При екстремальних значеннях ваші двигуни, ймовірно, втратять кроки в кутах, що може спричинити зсув шару.
